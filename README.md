# iOS (ios)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

iOS is Apple's mobile operating system and the developer platform behind iPhone apps. While the bulk of the iOS SDK is delivered as Swift / Objective-C client frameworks (UIKit, SwiftUI, MapKit, HealthKit, HomeKit, SiriKit, StoreKit, AppIntents, PassKit, WidgetKit, ActivityKit), Apple also exposes a substantial set of server-side HTTPS APIs that iOS developers, publishers, and back-end systems consume directly. This repository indexes that server-side surface — App Store Connect API, App Store Server API, App Store Server Notifications, Apple Push Notification service (APNs), DeviceCheck / App Attest, Sign in with Apple, Apple Music API, the Wallet / PassKit Web Service contract, and related developer infrastructure — and points to the matching OpenAPI artifacts where Apple publishes them.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ios/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ios/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- iOS
- Apple
- Mobile
- App Store
- Push Notifications
- In-App Purchases
- Subscriptions
- Authentication
- Wallet
- Developer Platform

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-23

## APIs

### App Store Connect API

"This standards-based REST API lets you automate tasks across developer tools, such as App Store Connect, Xcode, and Certificates, Identifiers & Profiles, to give you greater flexibility and efficiency in your workflows." The App Store Connect API is the primary REST surface Apple provides to iOS publishers — covering app metadata, builds, TestFlight, in-app purchases and subscriptions, pricing and availability, Game Center, Xcode Cloud, provisioning, analytics, and sales / financial / power-and- performance reports. Authentication uses JSON Web Tokens (JWT) signed with an API key created in App Store Connect. Apple publishes an official OpenAPI 3.0 specification as a downloadable ZIP from the App Store Connect API landing page.

- **Human URL:** [https://developer.apple.com/app-store-connect/api/](https://developer.apple.com/app-store-connect/api/)
- **Base URL:** `https://api.appstoreconnect.apple.com`

#### Tags

- App Store Connect
- App Store
- TestFlight
- In-App Purchases
- Subscriptions
- Game Center
- Xcode Cloud
- Provisioning
- Reporting

#### Properties

- [Documentation](https://developer.apple.com/documentation/appstoreconnectapi)
- [API Reference](https://developer.apple.com/documentation/appstoreconnectapi)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/ios/main/openapi/app-store-connect-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Getting Started](https://developer.apple.com/documentation/appstoreconnectapi/creating-api-keys-for-app-store-connect-api)
- [Authentication](https://developer.apple.com/documentation/appstoreconnectapi/generating-tokens-for-api-requests)
- [Release Notes](https://developer.apple.com/documentation/appstoreconnectapi/app-store-connect-api-release-notes)
- [SDK](https://github.com/apple/app-store-server-library-swift)
- [SDK](https://github.com/apple/app-store-server-library-java)
- [SDK](https://github.com/apple/app-store-server-library-python)
- [SDK](https://github.com/apple/app-store-server-library-node)
- [Postman Collection](collections/app-store-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/app-store-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### App Store Server API

The App Store Server API is the server-to-server REST API for managing App Store transactions — looking up transaction history, fetching all subscription statuses for a customer, requesting test notifications, and issuing refunds. It pairs with StoreKit on the device and with App Store Server Notifications v2 for asynchronous state changes. Authentication is JWT (ES256) signed with a key created in App Store Connect; payloads and responses are JWS-signed JSON.

- **Human URL:** [https://developer.apple.com/documentation/appstoreserverapi](https://developer.apple.com/documentation/appstoreserverapi)
- **Base URL:** `https://api.storekit.itunes.apple.com`

#### Tags

- In-App Purchases
- Subscriptions
- Receipts
- Refunds
- StoreKit

#### Properties

- [Documentation](https://developer.apple.com/documentation/appstoreserverapi)
- [API Reference](https://developer.apple.com/documentation/appstoreserverapi)
- [Sandbox](https://api.storekit-sandbox.itunes.apple.com)
- [SDK](https://github.com/apple/app-store-server-library-swift)
- [SDK](https://github.com/apple/app-store-server-library-java)
- [SDK](https://github.com/apple/app-store-server-library-python)
- [SDK](https://github.com/apple/app-store-server-library-node)
- [Postman Collection](collections/app-store-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/app-store-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### App Store Server Notifications

App Store Server Notifications v2 is Apple's webhook surface for in-app purchase and subscription lifecycle events — SUBSCRIBED, DID_RENEW, EXPIRED, REFUND, GRACE_PERIOD_EXPIRED, REVOKE, CONSUMPTION_REQUEST and related notification types. Providers register a production URL and a sandbox URL in App Store Connect; payloads are signed JWS (JSON Web Signatures) wrapping the transaction and renewal-info objects.

- **Human URL:** [https://developer.apple.com/documentation/appstoreservernotifications](https://developer.apple.com/documentation/appstoreservernotifications)

#### Tags

- Webhooks
- Subscriptions
- In-App Purchases
- Events
- JWS

#### Properties

- [Documentation](https://developer.apple.com/documentation/appstoreservernotifications)
- [API Reference](https://developer.apple.com/documentation/appstoreservernotifications)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/ios/main/asyncapi/app-store-server-notifications-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/app-store-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/app-store-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apple Push Notification Service (APNs)

The Apple Push Notification service (APNs) is the HTTP/2 + JSON push delivery surface for sending remote notifications, background updates, VoIP pushes, and Live Activity updates to iOS, iPadOS, watchOS, tvOS and macOS devices. Providers authenticate either with a token-based JWT (ES256) or with a per-app TLS client certificate, and POST a notification payload to /3/device/{deviceToken}. APNs is the transport behind every push notification on iOS.

- **Human URL:** [https://developer.apple.com/documentation/usernotifications/sending-notification-requests-to-apns](https://developer.apple.com/documentation/usernotifications/sending-notification-requests-to-apns)
- **Base URL:** `https://api.push.apple.com`

#### Tags

- Push Notifications
- HTTP/2
- Live Activities
- VoIP
- Background Updates

#### Properties

- [Documentation](https://developer.apple.com/documentation/usernotifications/sending-notification-requests-to-apns)
- [API Reference](https://developer.apple.com/documentation/usernotifications/setting-up-a-remote-notification-server)
- [Sandbox](https://api.sandbox.push.apple.com)
- [Authentication](https://developer.apple.com/documentation/usernotifications/establishing-a-token-based-connection-to-apns)
- [Postman Collection](collections/app-store-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/app-store-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DeviceCheck and App Attest

DeviceCheck allows servers to set and query two bits of per-device state and to verify that a request is coming from a genuine Apple device. App Attest, exposed through the same service, lets a server cryptographically verify that requests are coming from an authentic, uncompromised instance of an app. The API is JWT-authenticated (ES256) and is used as an anti- fraud / anti-abuse signal alongside iOS apps.

- **Human URL:** [https://developer.apple.com/documentation/devicecheck](https://developer.apple.com/documentation/devicecheck)
- **Base URL:** `https://api.devicecheck.apple.com`

#### Tags

- Device Attestation
- Anti-Fraud
- App Attest
- Security

#### Properties

- [Documentation](https://developer.apple.com/documentation/devicecheck)
- [API Reference](https://developer.apple.com/documentation/devicecheck/accessing-and-modifying-per-device-data)
- [Sandbox](https://api.development.devicecheck.apple.com)
- [Postman Collection](collections/app-store-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/app-store-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sign in with Apple REST API

Sign in with Apple is Apple's OpenID Connect-style identity provider for iOS, web, and other Apple-platform apps. The REST surface, hosted at appleid.apple.com, exposes /auth/token (authorization-code and refresh- token exchange), /auth/revoke (token revocation), /auth/keys (JWKS public keys for ID-token validation), and a server-to-server notification channel for account-deletion and email-relay events. Required for any iOS app offering third-party social login.

- **Human URL:** [https://developer.apple.com/sign-in-with-apple/](https://developer.apple.com/sign-in-with-apple/)
- **Base URL:** `https://appleid.apple.com`

#### Tags

- Authentication
- OpenID Connect
- OAuth 2.0
- Identity
- Single Sign-On

#### Properties

- [Documentation](https://developer.apple.com/documentation/sign_in_with_apple)
- [API Reference](https://developer.apple.com/documentation/sign_in_with_apple/sign_in_with_apple_rest_api)
- [Authentication](https://developer.apple.com/documentation/sign_in_with_apple/generate_and_validate_tokens)
- [Postman Collection](collections/app-store-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/app-store-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apple Music API

The Apple Music API is Apple's REST surface for Apple Music catalog, library, ratings, playlists, recommendations, and search. Calls are authenticated with a developer token (JWT) and, when accessing a subscriber's personal data, an additional Music User Token obtained through MusicKit on the device. It powers Apple Music integrations in iOS apps and on the web.

- **Human URL:** [https://developer.apple.com/documentation/applemusicapi](https://developer.apple.com/documentation/applemusicapi)
- **Base URL:** `https://api.music.apple.com`

#### Tags

- Apple Music
- Music
- Catalog
- Streaming
- MusicKit

#### Properties

- [Documentation](https://developer.apple.com/documentation/applemusicapi)
- [API Reference](https://developer.apple.com/documentation/applemusicapi)
- [Authentication](https://developer.apple.com/documentation/applemusicapi/generating-developer-tokens)
- [Postman Collection](collections/app-store-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/app-store-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Wallet / PassKit Web Service

The PassKit Web Service is a server-side HTTP contract that Wallet pass providers must implement so that Apple Wallet can register devices, enumerate pass serial numbers, fetch the latest pass version, unregister devices, and accept log messages. While Apple does not host this API itself, it specifies the exact endpoints (/v1/devices/.../registrations/..., /v1/passes/{passTypeIdentifier}/{serialNumber}, /v1/log) every provider must expose. APNs is the companion channel for pass-update notifications.

- **Human URL:** [https://developer.apple.com/documentation/walletpasses](https://developer.apple.com/documentation/walletpasses)

#### Tags

- Wallet
- PassKit
- Passes
- Loyalty
- Boarding Passes

#### Properties

- [Documentation](https://developer.apple.com/documentation/walletpasses)
- [API Reference](https://developer.apple.com/documentation/walletpasses/adding-a-web-service-to-update-passes)
- [Postman Collection](collections/app-store-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/app-store-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://developer.apple.com/)
- [Developer Portal](https://developer.apple.com/ios/)
- [Documentation](https://developer.apple.com/documentation/)
- [API Reference](https://developer.apple.com/documentation/appstoreconnectapi)
- [Sign Up](https://developer.apple.com/programs/enroll/)
- [Pricing](https://developer.apple.com/programs/whats-included/)
- [Plans](https://developer.apple.com/programs/)
- [Status Page](https://developer.apple.com/system-status/)
- [Blog](https://developer.apple.com/news/)
- [R S S](https://developer.apple.com/news/rss/news.rss)
- [Release Notes](https://developer.apple.com/news/releases/)
- [Forum](https://developer.apple.com/forums/)
- [Support](https://developer.apple.com/support/)
- [GitHub Organization](https://github.com/apple)
- [Events](https://developer.apple.com/wwdc/)
- [YouTube](https://www.youtube.com/appledevelopers)
- [Terms of Service](https://developer.apple.com/support/terms/)
- [Privacy](https://developer.apple.com/support/privacy/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/ios/main/openapi/app-store-connect-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/ios/main/asyncapi/app-store-server-notifications-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/ios/main/rules/app-store-connect-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)
- [Capabilities](https://github.com/api-evangelist/ios/tree/main/capabilities)
- [JSON Schema](https://github.com/api-evangelist/ios/tree/main/json-schema) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/ios/main/json-ld/ios-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/ios/main/vocabulary/ios-vocabulary.yml)
- [Plans](https://raw.githubusercontent.com/api-evangelist/ios/main/plans/ios-plans-pricing.yml)
- [Rate Limits](https://raw.githubusercontent.com/api-evangelist/ios/main/rate-limits/ios-rate-limits.yml)
- [Fin Ops](https://raw.githubusercontent.com/api-evangelist/ios/main/finops/ios-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
