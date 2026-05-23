# iOS (ios)

API and integration profile for **iOS** — Apple's mobile operating system and developer platform — maintained as part of the [API Evangelist Network](https://apievangelist.com).

This repository indexes the **server-side HTTPS surface** Apple exposes to iOS developers. The bulk of the iOS SDK is delivered as Swift / Objective-C client frameworks (UIKit, SwiftUI, MapKit, HealthKit, HomeKit, SiriKit, StoreKit, AppIntents, PassKit, WidgetKit, ActivityKit) and is out of scope here — those are not HTTP APIs you call from a back-office system. What *is* in scope is everything an iOS publisher or back-end engineer actually hits over the wire: App Store Connect, App Store Server, the App Store Server Notifications webhook, APNs, DeviceCheck / App Attest, Sign in with Apple, the Apple Music API, and the Wallet / PassKit web-service contract.

> "This standards-based REST API lets you automate tasks across developer tools, such as App Store Connect, Xcode, and Certificates, Identifiers & Profiles, to give you greater flexibility and efficiency in your workflows."
>
> — developer.apple.com/app-store-connect/api

## APIs Documented

| API | Base URL | Auth | Style |
|---|---|---|---|
| **App Store Connect API** (v4.3.1) | `https://api.appstoreconnect.apple.com` | JWT (ES256) | REST / JSON:API — **923 paths, 1,208 operations, 1,337 schemas, 192 tags** in Apple's published OpenAPI 3.0 |
| **App Store Server API** | `https://api.storekit.itunes.apple.com` (sandbox: `…-sandbox…`) | JWT (ES256) | REST + JWS-signed payloads |
| **App Store Server Notifications V2** | (webhook — provider hosts) | JWS-signed payload from Apple | Webhook (19 notification types, 16 subtypes) |
| **Apple Push Notification Service (APNs)** | `https://api.push.apple.com` (sandbox: `https://api.sandbox.push.apple.com`) | JWT (ES256) or TLS client cert | HTTP/2 + JSON, POST `/3/device/{deviceToken}` |
| **DeviceCheck and App Attest** | `https://api.devicecheck.apple.com` (dev: `https://api.development.devicecheck.apple.com`) | JWT (ES256) | REST |
| **Sign in with Apple** | `https://appleid.apple.com` | client_secret JWT (ES256) | OAuth 2.0 / OIDC |
| **Apple Music API** | `https://api.music.apple.com` | Developer Token (JWT) + User Token | REST |
| **Wallet / PassKit Web Service** | (provider-hosted, Apple-specified contract) | Pass certificate + push token | REST contract |

## Repository Layout

```
ios/
├── apis.yml                            # Master index (apis.json/yml 0.19)
├── README.md
├── openapi/
│   └── app-store-connect-openapi.json  # Apple's official OpenAPI 3.0 (mirrored from Apple, summaries derived from operationId)
├── asyncapi/
│   └── app-store-server-notifications-asyncapi.yml
├── rules/
│   └── app-store-connect-rules.yml     # Spectral ruleset enforcing Apple's JSON:API conventions
├── capabilities/
│   ├── ios-publisher-workflow.yaml     # Composed Naftiko workflow (ship → revenue → retention → reviews → reporting)
│   └── shared/
│       ├── app-store-connect.yaml
│       ├── app-store-server.yaml
│       ├── apns.yaml
│       └── sign-in-with-apple.yaml
├── json-schema/
│   ├── app-store-connect-app-schema.json
│   ├── app-store-connect-build-schema.json
│   ├── app-store-server-transaction-schema.json
│   ├── apns-notification-payload-schema.json
│   └── sign-in-with-apple-id-token-schema.json
├── json-structure/
│   └── ios-server-apis-structure.json
├── json-ld/
│   └── ios-context.jsonld
├── examples/
│   ├── app-store-connect-list-apps-example.json
│   ├── apns-send-notification-example.json
│   ├── app-store-server-notification-subscribed-example.json
│   └── sign-in-with-apple-token-example.json
├── vocabulary/
│   └── ios-vocabulary.yml
├── plans/
│   └── ios-plans-pricing.yml
├── rate-limits/
│   └── ios-rate-limits.yml
└── finops/
    └── ios-finops.yml
```

## Source OpenAPI

Apple publishes the App Store Connect API OpenAPI 3.0 spec as a ZIP download from the [App Store Connect API landing page](https://developer.apple.com/app-store-connect/api/). The file in `openapi/app-store-connect-openapi.json` is the **4.3.1** release (May 12, 2026) mirrored verbatim, with the following minimal transforms applied:

- `info.description` populated (Apple ships an empty description).
- Per-operation `summary` fields derived from `operationId` (Apple ships only `operationId` + `tags`).
- Synthetic top-level `tags` array generated from operation tag references.

The remaining 6.8 MB of paths, parameters, and component schemas are unchanged.

## Scale of Apple's Developer Surface

- Apple's GitHub org ([github.com/apple](https://github.com/apple)) hosts **414 public repos**, including official `app-store-server-library-{swift,java,python,node}`, `swift-nio`, `foundationdb`, `pkl`, `coremltools`, `ml-stable-diffusion`, and `container`.
- The App Store Connect API alone exposes **191 distinct top-level resource families** — the largest concentrations being `apps` (84 ops), `gameCenterDetails` (35), `appStoreVersions` (26), `builds` (25), `subscriptions` (24), `inAppPurchases` (21), and `betaGroups` (14).

## Pricing Summary

| Plan | Cost | Notes |
|---|---|---|
| Apple Developer Program | **USD 99 / year** | Required for all server APIs documented here. Includes 25 Xcode Cloud compute hours/mo, 1 PB CloudKit, 500K WeatherKit calls/mo. |
| Apple Developer Enterprise Program | USD 299 / year | Internal-only distribution; no App Store. |
| App Store Small Business Program | Free enrollment | Reduces App Store commission from 30% to 15% for sellers under $1M/yr. |
| App Store Commission | 30% / 15% | Standard 30%; 15% after first 12 paid subscription months or under Small Business Program. |

See `plans/ios-plans-pricing.yml` and `finops/ios-finops.yml` for the full breakdown.

## Notable Absences

- **No public OpenAPI spec** for the App Store Server API, APNs, DeviceCheck, Sign in with Apple, the Apple Music API, or the Wallet / PassKit Web Service. Only the App Store Connect API ships with one.
- **No published per-second QPS** for most of Apple's server APIs — guidance is "back off on 429."
- **No usage-based billing** on the iOS server APIs themselves; all monetization is via the Apple Developer Program fee + App Store commission.

## License & Attribution

The OpenAPI spec mirrored under `openapi/` is © Apple Inc., distributed by Apple under the terms on [developer.apple.com/terms](https://developer.apple.com/terms/). Everything else in this repository is licensed CC BY 4.0 by API Evangelist.

---

Maintained by [Kin Lane](https://apievangelist.com) · part of the [API Evangelist Network](https://github.com/api-evangelist).
