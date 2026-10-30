# iOS

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

**Areas:** iOS · Apple · Mobile · App Store · Push Notifications · In-App Purchases · Subscription · Authentication · Developer Platform

## iOS on APIs.io

Everything profiled for iOS is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/ios/](https://apis.io/providers/ios/)** — or go straight to one of the APIs or properties below.

### APIs (199)

- [App Store Server API](https://apis.io/apis/ios/app-store-server-api/) — The App Store Server API is the server-to-server REST API for managing App Store transactions — looking up transaction history, fetching all subscription…
- [App Store Server Notifications](https://apis.io/apis/ios/app-store-server-notifications/) — App Store Server Notifications v2 is Apple's webhook surface for in-app purchase and subscription lifecycle events — SUBSCRIBED, DID_RENEW, EXPIRED, REFUND,…
- [Apple Push Notification Service (APNs)](https://apis.io/apis/ios/apns/) — The Apple Push Notification service (APNs) is the HTTP/2 + JSON push delivery surface for sending remote notifications, background updates, VoIP pushes, and…
- [DeviceCheck and App Attest](https://apis.io/apis/ios/devicecheck/) — DeviceCheck allows servers to set and query two bits of per-device state and to verify that a request is coming from a genuine Apple device. App Attest,…
- [Sign in with Apple REST API](https://apis.io/apis/ios/sign-in-with-apple/) — Sign in with Apple is Apple's OpenID Connect-style identity provider for iOS, web, and other Apple-platform apps. The REST surface, hosted at…
- [Apple Music API](https://apis.io/apis/ios/apple-music-api/) — The Apple Music API is Apple's REST surface for Apple Music catalog, library, ratings, playlists, recommendations, and search. Calls are authenticated with…
- [Wallet / PassKit Web Service](https://apis.io/apis/ios/wallet-passkit-web-service/) — The PassKit Web Service is a server-side HTTP contract that Wallet pass providers must implement so that Apple Wallet can register devices, enumerate pass…
- [iOS AccessibilityDeclarations API](https://apis.io/apis/ios/ios-accessibilitydeclarations-api/) — The AccessibilityDeclarations API from iOS — 2 operation(s) for accessibilitydeclarations.
- [iOS Actors API](https://apis.io/apis/ios/ios-actors-api/) — The Actors API from iOS — 2 operation(s) for actors.
- [iOS AgeRatingDeclarations API](https://apis.io/apis/ios/ios-ageratingdeclarations-api/) — The AgeRatingDeclarations API from iOS — 1 operation(s) for ageratingdeclarations.
- [iOS AlternativeDistributionDomains API](https://apis.io/apis/ios/ios-alternativedistributiondomains-api/) — The AlternativeDistributionDomains API from iOS — 2 operation(s) for alternativedistributiondomains.
- [iOS AlternativeDistributionKeys API](https://apis.io/apis/ios/ios-alternativedistributionkeys-api/) — The AlternativeDistributionKeys API from iOS — 2 operation(s) for alternativedistributionkeys.
- [iOS AlternativeDistributionPackageDeltas API](https://apis.io/apis/ios/ios-alternativedistributionpackagedeltas-api/) — The AlternativeDistributionPackageDeltas API from iOS — 1 operation(s) for alternativedistributionpackagedeltas.
- [iOS AlternativeDistributionPackages API](https://apis.io/apis/ios/ios-alternativedistributionpackages-api/) — The AlternativeDistributionPackages API from iOS — 4 operation(s) for alternativedistributionpackages.
- [iOS AlternativeDistributionPackageVariants API](https://apis.io/apis/ios/ios-alternativedistributionpackagevariants-api/) — The AlternativeDistributionPackageVariants API from iOS — 1 operation(s) for alternativedistributionpackagevariants.
- [iOS AlternativeDistributionPackageVersions API](https://apis.io/apis/ios/ios-alternativedistributionpackageversions-api/) — The AlternativeDistributionPackageVersions API from iOS — 5 operation(s) for alternativedistributionpackageversions.
- [iOS AnalyticsReportInstances API](https://apis.io/apis/ios/ios-analyticsreportinstances-api/) — The AnalyticsReportInstances API from iOS — 3 operation(s) for analyticsreportinstances.
- [iOS AnalyticsReportRequests API](https://apis.io/apis/ios/ios-analyticsreportrequests-api/) — The AnalyticsReportRequests API from iOS — 4 operation(s) for analyticsreportrequests.
- [iOS AnalyticsReportSegments API](https://apis.io/apis/ios/ios-analyticsreportsegments-api/) — The AnalyticsReportSegments API from iOS — 1 operation(s) for analyticsreportsegments.
- [iOS AndroidToIosAppMappingDetails API](https://apis.io/apis/ios/ios-androidtoiosappmappingdetails-api/) — The AndroidToIosAppMappingDetails API from iOS — 2 operation(s) for androidtoiosappmappingdetails.
- [iOS AppAvailabilities API](https://apis.io/apis/ios/ios-appavailabilities-api/) — The AppAvailabilities API from iOS — 4 operation(s) for appavailabilities.
- [iOS AppClipAdvancedExperienceImages API](https://apis.io/apis/ios/ios-appclipadvancedexperienceimages-api/) — The AppClipAdvancedExperienceImages API from iOS — 2 operation(s) for appclipadvancedexperienceimages.
- [iOS AppClipAdvancedExperiences API](https://apis.io/apis/ios/ios-appclipadvancedexperiences-api/) — The AppClipAdvancedExperiences API from iOS — 2 operation(s) for appclipadvancedexperiences.
- [iOS AppClipAppStoreReviewDetails API](https://apis.io/apis/ios/ios-appclipappstorereviewdetails-api/) — The AppClipAppStoreReviewDetails API from iOS — 2 operation(s) for appclipappstorereviewdetails.
- [iOS AppClipDefaultExperienceLocalizations API](https://apis.io/apis/ios/ios-appclipdefaultexperiencelocalizations-api/) — The AppClipDefaultExperienceLocalizations API from iOS — 4 operation(s) for appclipdefaultexperiencelocalizations.
- [iOS AppClipDefaultExperiences API](https://apis.io/apis/ios/ios-appclipdefaultexperiences-api/) — The AppClipDefaultExperiences API from iOS — 8 operation(s) for appclipdefaultexperiences.
- [iOS AppClipHeaderImages API](https://apis.io/apis/ios/ios-appclipheaderimages-api/) — The AppClipHeaderImages API from iOS — 2 operation(s) for appclipheaderimages.
- [iOS AppClips API](https://apis.io/apis/ios/ios-appclips-api/) — The AppClips API from iOS — 5 operation(s) for appclips.
- [iOS AppCustomProductPageLocalizations API](https://apis.io/apis/ios/ios-appcustomproductpagelocalizations-api/) — The AppCustomProductPageLocalizations API from iOS — 8 operation(s) for appcustomproductpagelocalizations.
- [iOS AppCustomProductPages API](https://apis.io/apis/ios/ios-appcustomproductpages-api/) — The AppCustomProductPages API from iOS — 4 operation(s) for appcustomproductpages.
- [iOS AppCustomProductPageVersions API](https://apis.io/apis/ios/ios-appcustomproductpageversions-api/) — The AppCustomProductPageVersions API from iOS — 4 operation(s) for appcustomproductpageversions.
- [iOS AppEncryptionDeclarationDocuments API](https://apis.io/apis/ios/ios-appencryptiondeclarationdocuments-api/) — The AppEncryptionDeclarationDocuments API from iOS — 2 operation(s) for appencryptiondeclarationdocuments.
- [iOS AppEncryptionDeclarations API](https://apis.io/apis/ios/ios-appencryptiondeclarations-api/) — The AppEncryptionDeclarations API from iOS — 7 operation(s) for appencryptiondeclarations.
- [iOS AppEventLocalizations API](https://apis.io/apis/ios/ios-appeventlocalizations-api/) — The AppEventLocalizations API from iOS — 6 operation(s) for appeventlocalizations.
- [iOS AppEventScreenshots API](https://apis.io/apis/ios/ios-appeventscreenshots-api/) — The AppEventScreenshots API from iOS — 2 operation(s) for appeventscreenshots.
- [iOS AppEventVideoClips API](https://apis.io/apis/ios/ios-appeventvideoclips-api/) — The AppEventVideoClips API from iOS — 2 operation(s) for appeventvideoclips.
- [iOS AppInfoLocalizations API](https://apis.io/apis/ios/ios-appinfolocalizations-api/) — The AppInfoLocalizations API from iOS — 2 operation(s) for appinfolocalizations.
- [iOS AppInfos API](https://apis.io/apis/ios/ios-appinfos-api/) — The AppInfos API from iOS — 19 operation(s) for appinfos.
- [iOS AppPreviewSets API](https://apis.io/apis/ios/ios-apppreviewsets-api/) — The AppPreviewSets API from iOS — 4 operation(s) for apppreviewsets.
- [iOS AppPricePoints API](https://apis.io/apis/ios/ios-apppricepoints-api/) — The AppPricePoints API from iOS — 3 operation(s) for apppricepoints.
- [iOS AppPriceSchedules API](https://apis.io/apis/ios/ios-apppriceschedules-api/) — The AppPriceSchedules API from iOS — 8 operation(s) for apppriceschedules.
- [iOS Apps API](https://apis.io/apis/ios/ios-apps-api/) — The Apps API from iOS — 84 operation(s) for apps.
- [iOS AppScreenshots API](https://apis.io/apis/ios/ios-appscreenshots-api/) — The AppScreenshots API from iOS — 2 operation(s) for appscreenshots.
- [iOS AppScreenshotSets API](https://apis.io/apis/ios/ios-appscreenshotsets-api/) — The AppScreenshotSets API from iOS — 4 operation(s) for appscreenshotsets.
- [iOS AppStoreReviewAttachments API](https://apis.io/apis/ios/ios-appstorereviewattachments-api/) — The AppStoreReviewAttachments API from iOS — 2 operation(s) for appstorereviewattachments.
- [iOS AppStoreReviewDetails API](https://apis.io/apis/ios/ios-appstorereviewdetails-api/) — The AppStoreReviewDetails API from iOS — 4 operation(s) for appstorereviewdetails.
- [iOS AppStoreVersionExperiments API](https://apis.io/apis/ios/ios-appstoreversionexperiments-api/) — The AppStoreVersionExperiments API from iOS — 8 operation(s) for appstoreversionexperiments.
- [iOS AppStoreVersionExperimentTreatmentLocalizations API](https://apis.io/apis/ios/ios-appstoreversionexperimenttreatmentlocalizations-api/) — The AppStoreVersionExperimentTreatmentLocalizations API from iOS — 6 operation(s) for appstoreversionexperimenttreatmentlocalizations.
- [iOS AppStoreVersionExperimentTreatments API](https://apis.io/apis/ios/ios-appstoreversionexperimenttreatments-api/) — The AppStoreVersionExperimentTreatments API from iOS — 4 operation(s) for appstoreversionexperimenttreatments.
- [iOS AppStoreVersionLocalizations API](https://apis.io/apis/ios/ios-appstoreversionlocalizations-api/) — The AppStoreVersionLocalizations API from iOS — 8 operation(s) for appstoreversionlocalizations.
- [iOS AppStoreVersionPhasedReleases API](https://apis.io/apis/ios/ios-appstoreversionphasedreleases-api/) — The AppStoreVersionPhasedReleases API from iOS — 2 operation(s) for appstoreversionphasedreleases.
- [iOS AppStoreVersionPromotions API](https://apis.io/apis/ios/ios-appstoreversionpromotions-api/) — The AppStoreVersionPromotions API from iOS — 1 operation(s) for appstoreversionpromotions.
- [iOS AppStoreVersionReleaseRequests API](https://apis.io/apis/ios/ios-appstoreversionreleaserequests-api/) — The AppStoreVersionReleaseRequests API from iOS — 1 operation(s) for appstoreversionreleaserequests.
- [iOS AppStoreVersions API](https://apis.io/apis/ios/ios-appstoreversions-api/) — The AppStoreVersions API from iOS — 26 operation(s) for appstoreversions.
- [iOS AppStoreVersionSubmissions API](https://apis.io/apis/ios/ios-appstoreversionsubmissions-api/) — The AppStoreVersionSubmissions API from iOS — 1 operation(s) for appstoreversionsubmissions.
- [iOS AppTags API](https://apis.io/apis/ios/ios-apptags-api/) — The AppTags API from iOS — 3 operation(s) for apptags.
- [iOS BackgroundAssets API](https://apis.io/apis/ios/ios-backgroundassets-api/) — The BackgroundAssets API from iOS — 4 operation(s) for backgroundassets.
- [iOS BackgroundAssetUploadFiles API](https://apis.io/apis/ios/ios-backgroundassetuploadfiles-api/) — The BackgroundAssetUploadFiles API from iOS — 2 operation(s) for backgroundassetuploadfiles.
- [iOS BackgroundAssetVersionAppStoreReleases API](https://apis.io/apis/ios/ios-backgroundassetversionappstorereleases-api/) — The BackgroundAssetVersionAppStoreReleases API from iOS — 1 operation(s) for backgroundassetversionappstorereleases.
- [iOS BackgroundAssetVersionExternalBetaReleases API](https://apis.io/apis/ios/ios-backgroundassetversionexternalbetareleases-api/) — The BackgroundAssetVersionExternalBetaReleases API from iOS — 1 operation(s) for backgroundassetversionexternalbetareleases.
- [iOS BackgroundAssetVersionInternalBetaReleases API](https://apis.io/apis/ios/ios-backgroundassetversioninternalbetareleases-api/) — The BackgroundAssetVersionInternalBetaReleases API from iOS — 1 operation(s) for backgroundassetversioninternalbetareleases.
- [iOS BackgroundAssetVersions API](https://apis.io/apis/ios/ios-backgroundassetversions-api/) — The BackgroundAssetVersions API from iOS — 4 operation(s) for backgroundassetversions.
- [iOS BetaAppClipInvocationLocalizations API](https://apis.io/apis/ios/ios-betaappclipinvocationlocalizations-api/) — The BetaAppClipInvocationLocalizations API from iOS — 2 operation(s) for betaappclipinvocationlocalizations.
- [iOS BetaAppClipInvocations API](https://apis.io/apis/ios/ios-betaappclipinvocations-api/) — The BetaAppClipInvocations API from iOS — 2 operation(s) for betaappclipinvocations.
- [iOS BetaAppLocalizations API](https://apis.io/apis/ios/ios-betaapplocalizations-api/) — The BetaAppLocalizations API from iOS — 4 operation(s) for betaapplocalizations.
- [iOS BetaAppReviewDetails API](https://apis.io/apis/ios/ios-betaappreviewdetails-api/) — The BetaAppReviewDetails API from iOS — 4 operation(s) for betaappreviewdetails.
- [iOS BetaAppReviewSubmissions API](https://apis.io/apis/ios/ios-betaappreviewsubmissions-api/) — The BetaAppReviewSubmissions API from iOS — 4 operation(s) for betaappreviewsubmissions.
- [iOS BetaBuildLocalizations API](https://apis.io/apis/ios/ios-betabuildlocalizations-api/) — The BetaBuildLocalizations API from iOS — 4 operation(s) for betabuildlocalizations.
- [iOS BetaCrashLogs API](https://apis.io/apis/ios/ios-betacrashlogs-api/) — The BetaCrashLogs API from iOS — 1 operation(s) for betacrashlogs.
- [iOS BetaFeedbackCrashSubmissions API](https://apis.io/apis/ios/ios-betafeedbackcrashsubmissions-api/) — The BetaFeedbackCrashSubmissions API from iOS — 3 operation(s) for betafeedbackcrashsubmissions.
- [iOS BetaFeedbackScreenshotSubmissions API](https://apis.io/apis/ios/ios-betafeedbackscreenshotsubmissions-api/) — The BetaFeedbackScreenshotSubmissions API from iOS — 1 operation(s) for betafeedbackscreenshotsubmissions.
- [iOS BetaGroups API](https://apis.io/apis/ios/ios-betagroups-api/) — The BetaGroups API from iOS — 14 operation(s) for betagroups.
- [iOS BetaLicenseAgreements API](https://apis.io/apis/ios/ios-betalicenseagreements-api/) — The BetaLicenseAgreements API from iOS — 4 operation(s) for betalicenseagreements.
- [iOS BetaRecruitmentCriteria API](https://apis.io/apis/ios/ios-betarecruitmentcriteria-api/) — The BetaRecruitmentCriteria API from iOS — 2 operation(s) for betarecruitmentcriteria.
- [iOS BetaRecruitmentCriterionOptions API](https://apis.io/apis/ios/ios-betarecruitmentcriterionoptions-api/) — The BetaRecruitmentCriterionOptions API from iOS — 1 operation(s) for betarecruitmentcriterionoptions.
- [iOS BetaTesterInvitations API](https://apis.io/apis/ios/ios-betatesterinvitations-api/) — The BetaTesterInvitations API from iOS — 1 operation(s) for betatesterinvitations.
- [iOS BuildBetaDetails API](https://apis.io/apis/ios/ios-buildbetadetails-api/) — The BuildBetaDetails API from iOS — 4 operation(s) for buildbetadetails.
- [iOS BuildBetaNotifications API](https://apis.io/apis/ios/ios-buildbetanotifications-api/) — The BuildBetaNotifications API from iOS — 1 operation(s) for buildbetanotifications.
- [iOS BuildBundles API](https://apis.io/apis/ios/ios-buildbundles-api/) — The BuildBundles API from iOS — 8 operation(s) for buildbundles.
- [iOS Builds API](https://apis.io/apis/ios/ios-builds-api/) — The Builds API from iOS — 25 operation(s) for builds.
- [iOS BuildUploadFiles API](https://apis.io/apis/ios/ios-builduploadfiles-api/) — The BuildUploadFiles API from iOS — 2 operation(s) for builduploadfiles.
- [iOS BuildUploads API](https://apis.io/apis/ios/ios-builduploads-api/) — The BuildUploads API from iOS — 4 operation(s) for builduploads.
- [iOS BundleIdCapabilities API](https://apis.io/apis/ios/ios-bundleidcapabilities-api/) — The BundleIdCapabilities API from iOS — 2 operation(s) for bundleidcapabilities.
- [iOS BundleIds API](https://apis.io/apis/ios/ios-bundleids-api/) — The BundleIds API from iOS — 8 operation(s) for bundleids.
- [iOS Certificates API](https://apis.io/apis/ios/ios-certificates-api/) — The Certificates API from iOS — 4 operation(s) for certificates.
- [iOS CiArtifacts API](https://apis.io/apis/ios/ios-ciartifacts-api/) — The CiArtifacts API from iOS — 1 operation(s) for ciartifacts.
- [iOS CiBuildActions API](https://apis.io/apis/ios/ios-cibuildactions-api/) — The CiBuildActions API from iOS — 9 operation(s) for cibuildactions.
- [iOS CiBuildRuns API](https://apis.io/apis/ios/ios-cibuildruns-api/) — The CiBuildRuns API from iOS — 6 operation(s) for cibuildruns.
- [iOS CiIssues API](https://apis.io/apis/ios/ios-ciissues-api/) — The CiIssues API from iOS — 1 operation(s) for ciissues.
- [iOS CiMacOsVersions API](https://apis.io/apis/ios/ios-cimacosversions-api/) — The CiMacOsVersions API from iOS — 4 operation(s) for cimacosversions.
- [iOS CiProducts API](https://apis.io/apis/ios/ios-ciproducts-api/) — The CiProducts API from iOS — 12 operation(s) for ciproducts.
- [iOS CiTestResults API](https://apis.io/apis/ios/ios-citestresults-api/) — The CiTestResults API from iOS — 1 operation(s) for citestresults.
- [iOS CiWorkflows API](https://apis.io/apis/ios/ios-ciworkflows-api/) — The CiWorkflows API from iOS — 6 operation(s) for ciworkflows.
- [iOS CiXcodeVersions API](https://apis.io/apis/ios/ios-cixcodeversions-api/) — The CiXcodeVersions API from iOS — 4 operation(s) for cixcodeversions.
- [iOS CustomerReviewResponses API](https://apis.io/apis/ios/ios-customerreviewresponses-api/) — The CustomerReviewResponses API from iOS — 2 operation(s) for customerreviewresponses.
- [iOS CustomerReviews API](https://apis.io/apis/ios/ios-customerreviews-api/) — The CustomerReviews API from iOS — 3 operation(s) for customerreviews.
- [iOS Devices API](https://apis.io/apis/ios/ios-devices-api/) — The Devices API from iOS — 2 operation(s) for devices.
- [iOS DiagnosticSignatures API](https://apis.io/apis/ios/ios-diagnosticsignatures-api/) — The DiagnosticSignatures API from iOS — 1 operation(s) for diagnosticsignatures.
- [iOS EndAppAvailabilityPreOrders API](https://apis.io/apis/ios/ios-endappavailabilitypreorders-api/) — The EndAppAvailabilityPreOrders API from iOS — 1 operation(s) for endappavailabilitypreorders.
- [iOS EndUserLicenseAgreements API](https://apis.io/apis/ios/ios-enduserlicenseagreements-api/) — The EndUserLicenseAgreements API from iOS — 4 operation(s) for enduserlicenseagreements.
- [iOS FinanceReports API](https://apis.io/apis/ios/ios-financereports-api/) — The FinanceReports API from iOS — 1 operation(s) for financereports.
- [iOS GameCenterAchievementImages API](https://apis.io/apis/ios/ios-gamecenterachievementimages-api/) — The GameCenterAchievementImages API from iOS — 4 operation(s) for gamecenterachievementimages.
- [iOS GameCenterAchievementLocalizations API](https://apis.io/apis/ios/ios-gamecenterachievementlocalizations-api/) — The GameCenterAchievementLocalizations API from iOS — 10 operation(s) for gamecenterachievementlocalizations.
- [iOS GameCenterAchievementReleases API](https://apis.io/apis/ios/ios-gamecenterachievementreleases-api/) — The GameCenterAchievementReleases API from iOS — 2 operation(s) for gamecenterachievementreleases.
- [iOS GameCenterAchievements API](https://apis.io/apis/ios/ios-gamecenterachievements-api/) — The GameCenterAchievements API from iOS — 14 operation(s) for gamecenterachievements.
- [iOS GameCenterAchievementVersions API](https://apis.io/apis/ios/ios-gamecenterachievementversions-api/) — The GameCenterAchievementVersions API from iOS — 4 operation(s) for gamecenterachievementversions.
- [iOS GameCenterActivities API](https://apis.io/apis/ios/ios-gamecenteractivities-api/) — The GameCenterActivities API from iOS — 8 operation(s) for gamecenteractivities.
- [iOS GameCenterActivityImages API](https://apis.io/apis/ios/ios-gamecenteractivityimages-api/) — The GameCenterActivityImages API from iOS — 2 operation(s) for gamecenteractivityimages.
- [iOS GameCenterActivityLocalizations API](https://apis.io/apis/ios/ios-gamecenteractivitylocalizations-api/) — The GameCenterActivityLocalizations API from iOS — 4 operation(s) for gamecenteractivitylocalizations.
- [iOS GameCenterActivityVersionReleases API](https://apis.io/apis/ios/ios-gamecenteractivityversionreleases-api/) — The GameCenterActivityVersionReleases API from iOS — 2 operation(s) for gamecenteractivityversionreleases.
- [iOS GameCenterActivityVersions API](https://apis.io/apis/ios/ios-gamecenteractivityversions-api/) — The GameCenterActivityVersions API from iOS — 6 operation(s) for gamecenteractivityversions.
- [iOS GameCenterAppVersions API](https://apis.io/apis/ios/ios-gamecenterappversions-api/) — The GameCenterAppVersions API from iOS — 6 operation(s) for gamecenterappversions.
- [iOS GameCenterChallengeImages API](https://apis.io/apis/ios/ios-gamecenterchallengeimages-api/) — The GameCenterChallengeImages API from iOS — 2 operation(s) for gamecenterchallengeimages.
- [iOS GameCenterChallengeLocalizations API](https://apis.io/apis/ios/ios-gamecenterchallengelocalizations-api/) — The GameCenterChallengeLocalizations API from iOS — 4 operation(s) for gamecenterchallengelocalizations.
- [iOS GameCenterChallenges API](https://apis.io/apis/ios/ios-gamecenterchallenges-api/) — The GameCenterChallenges API from iOS — 6 operation(s) for gamecenterchallenges.
- [iOS GameCenterChallengeVersionReleases API](https://apis.io/apis/ios/ios-gamecenterchallengeversionreleases-api/) — The GameCenterChallengeVersionReleases API from iOS — 2 operation(s) for gamecenterchallengeversionreleases.
- [iOS GameCenterChallengeVersions API](https://apis.io/apis/ios/ios-gamecenterchallengeversions-api/) — The GameCenterChallengeVersions API from iOS — 6 operation(s) for gamecenterchallengeversions.
- [iOS GameCenterDetails API](https://apis.io/apis/ios/ios-gamecenterdetails-api/) — The GameCenterDetails API from iOS — 35 operation(s) for gamecenterdetails.
- [iOS GameCenterEnabledVersions API](https://apis.io/apis/ios/ios-gamecenterenabledversions-api/) — The GameCenterEnabledVersions API from iOS — 2 operation(s) for gamecenterenabledversions.
- [iOS GameCenterGroups API](https://apis.io/apis/ios/ios-gamecentergroups-api/) — The GameCenterGroups API from iOS — 20 operation(s) for gamecentergroups.
- [iOS GameCenterLeaderboardEntrySubmissions API](https://apis.io/apis/ios/ios-gamecenterleaderboardentrysubmissions-api/) — The GameCenterLeaderboardEntrySubmissions API from iOS — 1 operation(s) for gamecenterleaderboardentrysubmissions.
- [iOS GameCenterLeaderboardImages API](https://apis.io/apis/ios/ios-gamecenterleaderboardimages-api/) — The GameCenterLeaderboardImages API from iOS — 4 operation(s) for gamecenterleaderboardimages.
- [iOS GameCenterLeaderboardLocalizations API](https://apis.io/apis/ios/ios-gamecenterleaderboardlocalizations-api/) — The GameCenterLeaderboardLocalizations API from iOS — 8 operation(s) for gamecenterleaderboardlocalizations.
- [iOS GameCenterLeaderboardReleases API](https://apis.io/apis/ios/ios-gamecenterleaderboardreleases-api/) — The GameCenterLeaderboardReleases API from iOS — 2 operation(s) for gamecenterleaderboardreleases.
- [iOS GameCenterLeaderboards API](https://apis.io/apis/ios/ios-gamecenterleaderboards-api/) — The GameCenterLeaderboards API from iOS — 16 operation(s) for gamecenterleaderboards.
- [iOS GameCenterLeaderboardSetImages API](https://apis.io/apis/ios/ios-gamecenterleaderboardsetimages-api/) — The GameCenterLeaderboardSetImages API from iOS — 4 operation(s) for gamecenterleaderboardsetimages.
- [iOS GameCenterLeaderboardSetLocalizations API](https://apis.io/apis/ios/ios-gamecenterleaderboardsetlocalizations-api/) — The GameCenterLeaderboardSetLocalizations API from iOS — 8 operation(s) for gamecenterleaderboardsetlocalizations.
- [iOS GameCenterLeaderboardSetMemberLocalizations API](https://apis.io/apis/ios/ios-gamecenterleaderboardsetmemberlocalizations-api/) — The GameCenterLeaderboardSetMemberLocalizations API from iOS — 6 operation(s) for gamecenterleaderboardsetmemberlocalizations.
- [iOS GameCenterLeaderboardSetReleases API](https://apis.io/apis/ios/ios-gamecenterleaderboardsetreleases-api/) — The GameCenterLeaderboardSetReleases API from iOS — 2 operation(s) for gamecenterleaderboardsetreleases.
- [iOS GameCenterLeaderboardSets API](https://apis.io/apis/ios/ios-gamecenterleaderboardsets-api/) — The GameCenterLeaderboardSets API from iOS — 16 operation(s) for gamecenterleaderboardsets.
- [iOS GameCenterLeaderboardSetVersions API](https://apis.io/apis/ios/ios-gamecenterleaderboardsetversions-api/) — The GameCenterLeaderboardSetVersions API from iOS — 4 operation(s) for gamecenterleaderboardsetversions.
- [iOS GameCenterLeaderboardVersions API](https://apis.io/apis/ios/ios-gamecenterleaderboardversions-api/) — The GameCenterLeaderboardVersions API from iOS — 4 operation(s) for gamecenterleaderboardversions.
- [iOS GameCenterMatchmakingQueues API](https://apis.io/apis/ios/ios-gamecentermatchmakingqueues-api/) — The GameCenterMatchmakingQueues API from iOS — 7 operation(s) for gamecentermatchmakingqueues.
- [iOS GameCenterMatchmakingRules API](https://apis.io/apis/ios/ios-gamecentermatchmakingrules-api/) — The GameCenterMatchmakingRules API from iOS — 5 operation(s) for gamecentermatchmakingrules.
- [iOS GameCenterMatchmakingRuleSets API](https://apis.io/apis/ios/ios-gamecentermatchmakingrulesets-api/) — The GameCenterMatchmakingRuleSets API from iOS — 8 operation(s) for gamecentermatchmakingrulesets.
- [iOS GameCenterMatchmakingRuleSetTests API](https://apis.io/apis/ios/ios-gamecentermatchmakingrulesettests-api/) — The GameCenterMatchmakingRuleSetTests API from iOS — 1 operation(s) for gamecentermatchmakingrulesettests.
- [iOS GameCenterMatchmakingTeams API](https://apis.io/apis/ios/ios-gamecentermatchmakingteams-api/) — The GameCenterMatchmakingTeams API from iOS — 2 operation(s) for gamecentermatchmakingteams.
- [iOS GameCenterPlayerAchievementSubmissions API](https://apis.io/apis/ios/ios-gamecenterplayerachievementsubmissions-api/) — The GameCenterPlayerAchievementSubmissions API from iOS — 1 operation(s) for gamecenterplayerachievementsubmissions.
- [iOS InAppPurchaseAppStoreReviewScreenshots API](https://apis.io/apis/ios/ios-inapppurchaseappstorereviewscreenshots-api/) — The InAppPurchaseAppStoreReviewScreenshots API from iOS — 2 operation(s) for inapppurchaseappstorereviewscreenshots.
- [iOS InAppPurchaseAvailabilities API](https://apis.io/apis/ios/ios-inapppurchaseavailabilities-api/) — The InAppPurchaseAvailabilities API from iOS — 4 operation(s) for inapppurchaseavailabilities.
- [iOS InAppPurchaseContents API](https://apis.io/apis/ios/ios-inapppurchasecontents-api/) — The InAppPurchaseContents API from iOS — 1 operation(s) for inapppurchasecontents.
- [iOS InAppPurchaseImages API](https://apis.io/apis/ios/ios-inapppurchaseimages-api/) — The InAppPurchaseImages API from iOS — 2 operation(s) for inapppurchaseimages.
- [iOS InAppPurchaseLocalizations API](https://apis.io/apis/ios/ios-inapppurchaselocalizations-api/) — The InAppPurchaseLocalizations API from iOS — 2 operation(s) for inapppurchaselocalizations.
- [iOS InAppPurchaseOfferCodeCustomCodes API](https://apis.io/apis/ios/ios-inapppurchaseoffercodecustomcodes-api/) — The InAppPurchaseOfferCodeCustomCodes API from iOS — 2 operation(s) for inapppurchaseoffercodecustomcodes.
- [iOS InAppPurchaseOfferCodeOneTimeUseCodes API](https://apis.io/apis/ios/ios-inapppurchaseoffercodeonetimeusecodes-api/) — The InAppPurchaseOfferCodeOneTimeUseCodes API from iOS — 3 operation(s) for inapppurchaseoffercodeonetimeusecodes.
- [iOS InAppPurchaseOfferCodes API](https://apis.io/apis/ios/ios-inapppurchaseoffercodes-api/) — The InAppPurchaseOfferCodes API from iOS — 8 operation(s) for inapppurchaseoffercodes.
- [iOS InAppPurchasePricePoints API](https://apis.io/apis/ios/ios-inapppurchasepricepoints-api/) — The InAppPurchasePricePoints API from iOS — 2 operation(s) for inapppurchasepricepoints.
- [iOS InAppPurchasePriceSchedules API](https://apis.io/apis/ios/ios-inapppurchasepriceschedules-api/) — The InAppPurchasePriceSchedules API from iOS — 8 operation(s) for inapppurchasepriceschedules.
- [iOS InAppPurchases API](https://apis.io/apis/ios/ios-inapppurchases-api/) — The InAppPurchases API from iOS — 21 operation(s) for inapppurchases.
- [iOS InAppPurchaseSubmissions API](https://apis.io/apis/ios/ios-inapppurchasesubmissions-api/) — The InAppPurchaseSubmissions API from iOS — 1 operation(s) for inapppurchasesubmissions.
- [iOS MarketplaceSearchDetails API](https://apis.io/apis/ios/ios-marketplacesearchdetails-api/) — The MarketplaceSearchDetails API from iOS — 2 operation(s) for marketplacesearchdetails.
- [iOS MarketplaceWebhooks API](https://apis.io/apis/ios/ios-marketplacewebhooks-api/) — The MarketplaceWebhooks API from iOS — 2 operation(s) for marketplacewebhooks.
- [iOS Metrics API](https://apis.io/apis/ios/ios-metrics-api/) — The Metrics API from iOS — 15 operation(s) for metrics.
- [iOS Nominations API](https://apis.io/apis/ios/ios-nominations-api/) — The Nominations API from iOS — 2 operation(s) for nominations.
- [iOS PassTypeIds API](https://apis.io/apis/ios/ios-passtypeids-api/) — The PassTypeIds API from iOS — 4 operation(s) for passtypeids.
- [iOS PreReleaseVersions API](https://apis.io/apis/ios/ios-prereleaseversions-api/) — The PreReleaseVersions API from iOS — 6 operation(s) for prereleaseversions.
- [iOS Profiles API](https://apis.io/apis/ios/ios-profiles-api/) — The Profiles API from iOS — 8 operation(s) for profiles.
- [iOS PromotedPurchases API](https://apis.io/apis/ios/ios-promotedpurchases-api/) — The PromotedPurchases API from iOS — 2 operation(s) for promotedpurchases.
- [iOS ReviewSubmissionItems API](https://apis.io/apis/ios/ios-reviewsubmissionitems-api/) — The ReviewSubmissionItems API from iOS — 2 operation(s) for reviewsubmissionitems.
- [iOS ReviewSubmissions API](https://apis.io/apis/ios/ios-reviewsubmissions-api/) — The ReviewSubmissions API from iOS — 4 operation(s) for reviewsubmissions.
- [iOS RoutingAppCoverages API](https://apis.io/apis/ios/ios-routingappcoverages-api/) — The RoutingAppCoverages API from iOS — 2 operation(s) for routingappcoverages.
- [iOS SalesReports API](https://apis.io/apis/ios/ios-salesreports-api/) — The SalesReports API from iOS — 1 operation(s) for salesreports.
- [iOS SandboxTesters API](https://apis.io/apis/ios/ios-sandboxtesters-api/) — The SandboxTesters API from iOS — 2 operation(s) for sandboxtesters.
- [iOS SandboxTestersClearPurchaseHistoryRequest API](https://apis.io/apis/ios/ios-sandboxtestersclearpurchasehistoryrequest-api/) — The SandboxTestersClearPurchaseHistoryRequest API from iOS — 1 operation(s) for sandboxtestersclearpurchasehistoryrequest.
- [iOS ScmGitReferences API](https://apis.io/apis/ios/ios-scmgitreferences-api/) — The ScmGitReferences API from iOS — 1 operation(s) for scmgitreferences.
- [iOS ScmProviders API](https://apis.io/apis/ios/ios-scmproviders-api/) — The ScmProviders API from iOS — 4 operation(s) for scmproviders.
- [iOS ScmPullRequests API](https://apis.io/apis/ios/ios-scmpullrequests-api/) — The ScmPullRequests API from iOS — 1 operation(s) for scmpullrequests.
- [iOS ScmRepositories API](https://apis.io/apis/ios/ios-scmrepositories-api/) — The ScmRepositories API from iOS — 6 operation(s) for scmrepositories.
- [iOS SubscriptionAppStoreReviewScreenshots API](https://apis.io/apis/ios/ios-subscriptionappstorereviewscreenshots-api/) — The SubscriptionAppStoreReviewScreenshots API from iOS — 2 operation(s) for subscriptionappstorereviewscreenshots.
- [iOS SubscriptionAvailabilities API](https://apis.io/apis/ios/ios-subscriptionavailabilities-api/) — The SubscriptionAvailabilities API from iOS — 4 operation(s) for subscriptionavailabilities.
- [iOS SubscriptionGracePeriods API](https://apis.io/apis/ios/ios-subscriptiongraceperiods-api/) — The SubscriptionGracePeriods API from iOS — 1 operation(s) for subscriptiongraceperiods.
- [iOS SubscriptionGroupLocalizations API](https://apis.io/apis/ios/ios-subscriptiongrouplocalizations-api/) — The SubscriptionGroupLocalizations API from iOS — 2 operation(s) for subscriptiongrouplocalizations.
- [iOS SubscriptionGroupSubmissions API](https://apis.io/apis/ios/ios-subscriptiongroupsubmissions-api/) — The SubscriptionGroupSubmissions API from iOS — 1 operation(s) for subscriptiongroupsubmissions.
- [iOS SubscriptionImages API](https://apis.io/apis/ios/ios-subscriptionimages-api/) — The SubscriptionImages API from iOS — 2 operation(s) for subscriptionimages.
- [iOS SubscriptionIntroductoryOffers API](https://apis.io/apis/ios/ios-subscriptionintroductoryoffers-api/) — The SubscriptionIntroductoryOffers API from iOS — 2 operation(s) for subscriptionintroductoryoffers.
- [iOS SubscriptionLocalizations API](https://apis.io/apis/ios/ios-subscriptionlocalizations-api/) — The SubscriptionLocalizations API from iOS — 2 operation(s) for subscriptionlocalizations.
- [iOS SubscriptionOfferCodeCustomCodes API](https://apis.io/apis/ios/ios-subscriptionoffercodecustomcodes-api/) — The SubscriptionOfferCodeCustomCodes API from iOS — 2 operation(s) for subscriptionoffercodecustomcodes.
- [iOS SubscriptionOfferCodeOneTimeUseCodes API](https://apis.io/apis/ios/ios-subscriptionoffercodeonetimeusecodes-api/) — The SubscriptionOfferCodeOneTimeUseCodes API from iOS — 3 operation(s) for subscriptionoffercodeonetimeusecodes.
- [iOS SubscriptionOfferCodes API](https://apis.io/apis/ios/ios-subscriptionoffercodes-api/) — The SubscriptionOfferCodes API from iOS — 8 operation(s) for subscriptionoffercodes.
- [iOS SubscriptionPricePoints API](https://apis.io/apis/ios/ios-subscriptionpricepoints-api/) — The SubscriptionPricePoints API from iOS — 3 operation(s) for subscriptionpricepoints.
- [iOS SubscriptionPrices API](https://apis.io/apis/ios/ios-subscriptionprices-api/) — The SubscriptionPrices API from iOS — 2 operation(s) for subscriptionprices.
- [iOS SubscriptionPromotionalOffers API](https://apis.io/apis/ios/ios-subscriptionpromotionaloffers-api/) — The SubscriptionPromotionalOffers API from iOS — 4 operation(s) for subscriptionpromotionaloffers.
- [iOS Subscriptions API](https://apis.io/apis/ios/ios-subscriptions-api/) — The Subscriptions API from iOS — 24 operation(s) for subscriptions.
- [iOS SubscriptionSubmissions API](https://apis.io/apis/ios/ios-subscriptionsubmissions-api/) — The SubscriptionSubmissions API from iOS — 1 operation(s) for subscriptionsubmissions.
- [iOS Territories API](https://apis.io/apis/ios/ios-territories-api/) — The Territories API from iOS — 1 operation(s) for territories.
- [iOS TerritoryAvailabilities API](https://apis.io/apis/ios/ios-territoryavailabilities-api/) — The TerritoryAvailabilities API from iOS — 1 operation(s) for territoryavailabilities.
- [iOS UserInvitations API](https://apis.io/apis/ios/ios-userinvitations-api/) — The UserInvitations API from iOS — 4 operation(s) for userinvitations.
- [iOS Users API](https://apis.io/apis/ios/ios-users-api/) — The Users API from iOS — 4 operation(s) for users.
- [iOS WebhookPings API](https://apis.io/apis/ios/ios-webhookpings-api/) — The WebhookPings API from iOS — 1 operation(s) for webhookpings.
- [iOS Webhooks API](https://apis.io/apis/ios/ios-webhooks-api/) — The Webhooks API from iOS — 4 operation(s) for webhooks.
- [iOS WinBackOffers API](https://apis.io/apis/ios/ios-winbackoffers-api/) — The WinBackOffers API from iOS — 4 operation(s) for winbackoffers.
- [iOS Analytics Reports API](https://apis.io/apis/ios/ios-analytics-reports-api/) — The Analytics Reports API from iOS — 3 operation(s) for analytics reports.
- [iOS App Categories API](https://apis.io/apis/ios/ios-app-categories-api/) — The App Categories API from iOS — 6 operation(s) for app categories.
- [iOS App Events API](https://apis.io/apis/ios/ios-app-events-api/) — The App Events API from iOS — 4 operation(s) for app events.
- [iOS App Previews API](https://apis.io/apis/ios/ios-app-previews-api/) — The App Previews API from iOS — 2 operation(s) for app previews.
- [iOS Beta Testers API](https://apis.io/apis/ios/ios-beta-testers-api/) — The Beta Testers API from iOS — 9 operation(s) for beta testers.
- [iOS Merchant IDs API](https://apis.io/apis/ios/ios-merchant-ids-api/) — The Merchant IDs API from iOS — 4 operation(s) for merchant ids.
- [iOS Subscription groups API](https://apis.io/apis/ios/ios-subscription-groups-api/) — The Subscription groups API from iOS — 6 operation(s) for subscription groups.
- [iOS Webhook Deliveries API](https://apis.io/apis/ios/ios-webhook-deliveries-api/) — The Webhook Deliveries API from iOS — 1 operation(s) for webhook deliveries.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (12)

Multi-step workflows that chain operations into a business task.

- [iOS Create an App Store Version](https://apis.io/arazzos/ios/ios-create-app-store-version-workflow/)
- [iOS Create a TestFlight Beta Group and Assign a Build](https://apis.io/arazzos/ios/ios-create-beta-group-assign-build-workflow/)
- [iOS Create and Submit an In-App Purchase](https://apis.io/arazzos/ios/ios-create-in-app-purchase-workflow/)
- [iOS Create a Signing Certificate](https://apis.io/arazzos/ios/ios-create-signing-certificate-workflow/)
- [iOS Create an Auto-Renewable Subscription](https://apis.io/arazzos/ios/ios-create-subscription-workflow/)
- [iOS Enable a Capability on a Bundle ID](https://apis.io/arazzos/ios/ios-enable-bundle-id-capability-workflow/)
- [iOS Invite a TestFlight Beta Tester](https://apis.io/arazzos/ios/ios-invite-beta-tester-workflow/)
- [iOS Notify TestFlight Testers of a New Build](https://apis.io/arazzos/ios/ios-notify-testers-new-build-workflow/)
- [iOS Register a Provisioning Profile](https://apis.io/arazzos/ios/ios-register-provisioning-profile-workflow/)
- [iOS Respond to a Customer Review](https://apis.io/arazzos/ios/ios-respond-to-customer-review-workflow/)
- [iOS Submit a Build for TestFlight Beta Review](https://apis.io/arazzos/ios/ios-submit-build-for-beta-review-workflow/)
- [iOS Submit an App Store Version for Review](https://apis.io/arazzos/ios/ios-submit-version-for-review-workflow/)

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [App Store Server Notifications V2](https://apis.io/asyncapis/ios/app-store-server-notifications-asyncapi/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [app-store-server-notifications/v2](https://apis.io/channels/ios/app-store-server-notifications-v2/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Ios Agentic Access](https://apis.io/agentic-access/ios/ios-agentic-access/)

#### JSON Schema (5)

The data models the API reads and writes.

- [APNs Notification Payload](https://apis.io/schemas/ios/apns-notification-payload/)
- [App](https://apis.io/schemas/ios/app-store-connect-app/)
- [Build](https://apis.io/schemas/ios/app-store-connect-build/)
- [JWSTransactionDecodedPayload](https://apis.io/schemas/ios/app-store-server-transaction/)
- [Sign in with Apple ID Token Claims](https://apis.io/schemas/ios/sign-in-with-apple-id-token/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Ios Server Apis Structure](https://apis.io/json-structure/ios/ios-server-apis-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Ios Context](https://apis.io/jsonld/ios/ios-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [iOS Vocabulary](https://apis.io/vocabularies/ios/ios-vocabulary/)

#### Examples (4)

Example requests and responses.

- [Apns Send Notification Example](https://apis.io/examples/ios/apns-send-notification-example/)
- [App Store Connect List Apps Example](https://apis.io/examples/ios/app-store-connect-list-apps-example/)
- [App Store Server Notification Subscribed Example](https://apis.io/examples/ios/app-store-server-notification-subscribed-example/)
- [Sign In With Apple Token Example](https://apis.io/examples/ios/sign-in-with-apple-token-example/)

#### Collections (372)

Postman and Open Collection request collections.

- [App Store Connect API](https://apis.io/collections/ios/open-app-store-connect/)
- [App Store Connect AccessibilityDeclarations API](https://apis.io/collections/ios/open-ios-accessibilitydeclarations-api/)
- [App Store Connect AccessibilityDeclarations Actors API](https://apis.io/collections/ios/open-ios-actors-api/)
- [App Store Connect AccessibilityDeclarations AgeRatingDeclarations API](https://apis.io/collections/ios/open-ios-ageratingdeclarations-api/)
- [App Store Connect AccessibilityDeclarations AlternativeDistributionDomains API](https://apis.io/collections/ios/open-ios-alternativedistributiondomains-api/)
- [App Store Connect AccessibilityDeclarations AlternativeDistributionKeys API](https://apis.io/collections/ios/open-ios-alternativedistributionkeys-api/)
- [App Store Connect AccessibilityDeclarations AlternativeDistributionPackageDeltas API](https://apis.io/collections/ios/open-ios-alternativedistributionpackagedeltas-api/)
- [App Store Connect AccessibilityDeclarations AlternativeDistributionPackages API](https://apis.io/collections/ios/open-ios-alternativedistributionpackages-api/)
- [App Store Connect AccessibilityDeclarations AlternativeDistributionPackageVariants API](https://apis.io/collections/ios/open-ios-alternativedistributionpackagevariants-api/)
- [App Store Connect AccessibilityDeclarations AlternativeDistributionPackageVersions API](https://apis.io/collections/ios/open-ios-alternativedistributionpackageversions-api/)
- [App Store Connect AccessibilityDeclarations AnalyticsReportInstances API](https://apis.io/collections/ios/open-ios-analyticsreportinstances-api/)
- [App Store Connect AccessibilityDeclarations AnalyticsReportRequests API](https://apis.io/collections/ios/open-ios-analyticsreportrequests-api/)
- [App Store Connect AccessibilityDeclarations AnalyticsReports API](https://apis.io/collections/ios/open-ios-analyticsreports-api/)
- [App Store Connect AccessibilityDeclarations AnalyticsReportSegments API](https://apis.io/collections/ios/open-ios-analyticsreportsegments-api/)
- [App Store Connect AccessibilityDeclarations AndroidToIosAppMappingDetails API](https://apis.io/collections/ios/open-ios-androidtoiosappmappingdetails-api/)
- [App Store Connect AccessibilityDeclarations AppAvailabilities API](https://apis.io/collections/ios/open-ios-appavailabilities-api/)
- [App Store Connect AccessibilityDeclarations AppCategories API](https://apis.io/collections/ios/open-ios-appcategories-api/)
- [App Store Connect AccessibilityDeclarations AppClipAdvancedExperienceImages API](https://apis.io/collections/ios/open-ios-appclipadvancedexperienceimages-api/)
- [App Store Connect AccessibilityDeclarations AppClipAdvancedExperiences API](https://apis.io/collections/ios/open-ios-appclipadvancedexperiences-api/)
- [App Store Connect AccessibilityDeclarations AppClipDefaultExperienceLocalizations API](https://apis.io/collections/ios/open-ios-appclipdefaultexperiencelocalizations-api/)
- [App Store Connect AccessibilityDeclarations AppClipDefaultExperiences API](https://apis.io/collections/ios/open-ios-appclipdefaultexperiences-api/)
- [App Store Connect AccessibilityDeclarations AppClipHeaderImages API](https://apis.io/collections/ios/open-ios-appclipheaderimages-api/)
- [App Store Connect AccessibilityDeclarations AppClips API](https://apis.io/collections/ios/open-ios-appclips-api/)
- [App Store Connect AccessibilityDeclarations AppCustomProductPageLocalizations API](https://apis.io/collections/ios/open-ios-appcustomproductpagelocalizations-api/)
- [App Store Connect AccessibilityDeclarations AppCustomProductPages API](https://apis.io/collections/ios/open-ios-appcustomproductpages-api/)
- …and 347 more published on APIs.io

#### Overlays (192)

OpenAPI overlays, including conversational phrasing for each operation.

- [Ios Accessibilitydeclarations Api Phrasing Overlay](https://apis.io/overlays/ios/ios-accessibilitydeclarations-api-phrasing-overlay/)
- [Ios Actors Api Phrasing Overlay](https://apis.io/overlays/ios/ios-actors-api-phrasing-overlay/)
- [Ios Ageratingdeclarations Api Phrasing Overlay](https://apis.io/overlays/ios/ios-ageratingdeclarations-api-phrasing-overlay/)
- [Ios Alternativedistributiondomains Api Phrasing Overlay](https://apis.io/overlays/ios/ios-alternativedistributiondomains-api-phrasing-overlay/)
- [Ios Alternativedistributionkeys Api Phrasing Overlay](https://apis.io/overlays/ios/ios-alternativedistributionkeys-api-phrasing-overlay/)
- [Ios Alternativedistributionpackagedeltas Api Phrasing Overlay](https://apis.io/overlays/ios/ios-alternativedistributionpackagedeltas-api-phrasing-overlay/)
- [Ios Alternativedistributionpackages Api Phrasing Overlay](https://apis.io/overlays/ios/ios-alternativedistributionpackages-api-phrasing-overlay/)
- [Ios Alternativedistributionpackagevariants Api Phrasing Overlay](https://apis.io/overlays/ios/ios-alternativedistributionpackagevariants-api-phrasing-overlay/)
- [Ios Alternativedistributionpackageversions Api Phrasing Overlay](https://apis.io/overlays/ios/ios-alternativedistributionpackageversions-api-phrasing-overlay/)
- [Ios Analytics Reports Api Phrasing Overlay](https://apis.io/overlays/ios/ios-analytics-reports-api-phrasing-overlay/)
- [Ios Analyticsreportinstances Api Phrasing Overlay](https://apis.io/overlays/ios/ios-analyticsreportinstances-api-phrasing-overlay/)
- [Ios Analyticsreportrequests Api Phrasing Overlay](https://apis.io/overlays/ios/ios-analyticsreportrequests-api-phrasing-overlay/)
- [Ios Analyticsreportsegments Api Phrasing Overlay](https://apis.io/overlays/ios/ios-analyticsreportsegments-api-phrasing-overlay/)
- [Ios Androidtoiosappmappingdetails Api Phrasing Overlay](https://apis.io/overlays/ios/ios-androidtoiosappmappingdetails-api-phrasing-overlay/)
- [Ios App Categories Api Phrasing Overlay](https://apis.io/overlays/ios/ios-app-categories-api-phrasing-overlay/)
- [Ios App Events Api Phrasing Overlay](https://apis.io/overlays/ios/ios-app-events-api-phrasing-overlay/)
- [Ios App Previews Api Phrasing Overlay](https://apis.io/overlays/ios/ios-app-previews-api-phrasing-overlay/)
- [Ios Appavailabilities Api Phrasing Overlay](https://apis.io/overlays/ios/ios-appavailabilities-api-phrasing-overlay/)
- [Ios Appclipadvancedexperienceimages Api Phrasing Overlay](https://apis.io/overlays/ios/ios-appclipadvancedexperienceimages-api-phrasing-overlay/)
- [Ios Appclipadvancedexperiences Api Phrasing Overlay](https://apis.io/overlays/ios/ios-appclipadvancedexperiences-api-phrasing-overlay/)
- [Ios Appclipappstorereviewdetails Api Phrasing Overlay](https://apis.io/overlays/ios/ios-appclipappstorereviewdetails-api-phrasing-overlay/)
- [Ios Appclipdefaultexperiencelocalizations Api Phrasing Overlay](https://apis.io/overlays/ios/ios-appclipdefaultexperiencelocalizations-api-phrasing-overlay/)
- [Ios Appclipdefaultexperiences Api Phrasing Overlay](https://apis.io/overlays/ios/ios-appclipdefaultexperiences-api-phrasing-overlay/)
- [Ios Appclipheaderimages Api Phrasing Overlay](https://apis.io/overlays/ios/ios-appclipheaderimages-api-phrasing-overlay/)
- [Ios Appclips Api Phrasing Overlay](https://apis.io/overlays/ios/ios-appclips-api-phrasing-overlay/)
- …and 167 more published on APIs.io

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [iOS — app store connect rules](https://apis.io/rules/ios/app-store-connect-rules/)
- [iOS — asyncapi rules](https://apis.io/rules/ios/ios-asyncapi-spectral-rules/)
- [iOS — jsonschema rules](https://apis.io/rules/ios/ios-jsonschema-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Ios Authentication](https://apis.io/security/ios/ios-authentication/)
- [Ios Domain Security](https://apis.io/security/ios/ios-domain-security/)
- [Ios Vulnerability Disclosure](https://apis.io/security/ios/ios-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Ios Plans Pricing](https://apis.io/plans/ios/ios-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Ios Rate Limits](https://apis.io/rate-limits/ios/ios-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Ios Finops](https://apis.io/finops/ios/ios-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.apple.com/)
- [Documentation](https://developer.apple.com/documentation/)
- [API reference](https://developer.apple.com/documentation/appstoreconnectapi)
- [Pricing](https://developer.apple.com/programs/whats-included/)
- [Support](https://developer.apple.com/support/)
- [Blog](https://developer.apple.com/news/)
- [Terms of service](https://developer.apple.com/support/terms/)
- [GitHub](https://github.com/apple)
- [Status](https://developer.apple.com/system-status/)

## API Evangelist rating

**Kin Score 59.1** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 60.4 |
| Contract governance | 27.3 |
| Operational transparency | 55.3 |
| Developer ergonomics | 78.6 |
| Access clarity | 52.6 |

**Agent readiness 31.0** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | — |

**Regulatory alignment 30.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/ios/](https://apis.io/providers/ios/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for iOS: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/ios/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
