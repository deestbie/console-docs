# Technical FAQ (Application)

### What is an App Profile?

Mobile device apps are developed using mobile device development tools specific to each supported platform. During the design process all of the assets required for a specific app are defined (i.e., images, screen content, etc.), along with image size requirements and format. All of the app assets are considered metadata and will be stored in the Digital Domain Content Console.

After the application development is complete and the assets have been defined, an application instance is added to the Digital Domain Content Console. Here you catalog the various parts of your app.

* The app is automatically associated with the current Organization.
* App Name, Description, Type, Version, and Store URL are informational identifiers that are internal to the Content Console
* Bundle ID (iOS) or Package Name (Android) is a unique identifier for the application asset bundle that includes branding art and stylesheet information.
* Analytics ID includes captured statistical data about your app.

When a new asset is added to the app, the asset bundle is updated (which is associated with the Bundle ID). The App ID then gets passed to the mobile device API, and an API call is initiated that fetches the newly uploaded asset and updates the live application. Statistical data is updated in a similar manner and report can be viewed at different hierarchies in the Content Console.

### How do I add an application instance to the Content Console?

See [Publish Application](publishapp.md) for detailed instructions on how to add an application instance to the Content Console.

### How long does it take to configure an app profile in the Content Console?

If you have all of your application assets available, the configuration process for each application should take approximately ten minutes.

### How do I associate an app with a video collection stored on the Content Console?

Your Organization Administrator is responsible for associating video collections with application instances. Depending on the nature of the app, the management and visibility of content within a video collection that is available app could be a 24/7 process (for live events), or on a periodic basis if the app presents VoD content only.   

### If update a video profile, are changes automatically posted my distribution apps?

If the collection the video you are updating is a designated distribution app, the video content will be automatically updated.

### Do I have to resubmit my app to its platform-specific store every time I perform an update?

The requirement of resubmitting an app to its platform-specific store is based on the type of update you are performing.

* If you are updating app assets, the updates will occur immediately.
* If the update is a more significant feature or bug update it may be necessary to resubmit the app to its store. In this scenario, the update would post to the app installation in the mobile device app store and the user would need to initiate the update process.

### How do I localize an app?

App localization occurs at the native code level, and at the app instance level (in the Content Console).

* At the app development level (i.e., native code), Client Services will provide each client with a localization package that includes metadata that will display in the app (i.e., labels, menu item names, hover text, description text, etc). This metadata will be translated by the client into the designated language. This translated code will then be added to the native app code for the localized app version.
* At the Content Console level, if your distribution scenario requires a mobile device app in English, Spanish, and French (for example) you will have three application instances added to the Content Console.
* Each will have localized assets, a unique bundle ID, application ID, and analytics ID.

### As a client, do I submit my mobile device application to a store, or does Client Services perform that task?

This depends on your onboarding agreement, application type, and specific requirements. To common scenarios include:

* *For native apps* (i.e., ones that Digital Domain exclusively develops for a client), Client Services handles generating the bundle id or package name, submitting it to the platform-specific store, and adding it to the application instance in the Content Console.

* *For custom apps* (depending on the arrangement with Client Services), the client may provide Digital Domain with a Bundle ID or Package Name that Client Services adds to an application instance in the Content Console, and the client may submit the application to the platform-specific store.

### Are application assets added to the Content Console after the mobile device application is published to a platform-specific store?

Application assets are independent from submission to a platform-specific app stores. An app store doesn't see the assets in the Digital Domain Content Console, only the resulting usage of the assets in the application. Generally the application instance and associated assets are added to the Content Console prior to submission to a platform-specific app store as they are needed for the development and design cycles.

### In what scenario would I need to update my Token Secret?

The Token ID / Token Secret is built into the mobile device app so it can talk to the Content Console (i.e., retrieve updated metadata/assets, fetch analytics ID so it can generate analytics reports, etc). If you feel your Content Console login has been compromised, as the client you will need a new Token Secret to successfully authenticate and log into the Content Console. In this scenario, send a request to your Client Services representative for assistance.
