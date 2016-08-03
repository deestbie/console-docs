# Introduction

This topic provides information about Content Console application publishing process.

## Step 1: Review Application Requirements

Coming soon...

## Step 2: Add Application to Content Console

The **Create New Application** function allows you to add an application instance to the Digital Domain Content Console.

Your *Client Services* representative will add your application instance to the Digital Domain Content Console, and perform update and maintenance activities.

| Activity        | Description |
|:----------------|:--------------------------------------|
| Usage     | This application instance is used to store digital assets and metadata that will display in your live application.  |
| Bundle ID     | <ul><li>The application is associated with the Bundle ID.</li><li>This ID is created when an app is initially defined and is included in the published app on each platform-specific App Store.</li><li>It is the unique identifier for the application asset bundle that includes branding art and stylesheet information for the app.</li><li>When you add asset to your application using **Add / Edit Asset** the live application is automatically updated.</li></ul>|
| Distribution Apps    | <ul><li>Each application is associated with a Property and added to the *Distribution Apps* section for videos in each Collection.</li><</ul>|

**To add an app to the Content Console:**

1. Select **Organization > Apps**. The *Applications* page displays and presents a list of applications currently added to the organization.
2. Select **+Application**. The *Create New Application* popup displays.
3. Enter the information in the table listed below.
4. Select **Register** to save the application.

| Name         | Description                |
|:-----------------|:-------------------------------------|
| Organization       | The name of the organization the app is defined in.                |
| App Name       | The internal app name.                |
| Bundle ID       | Field used to specify the application Bundle ID (iOS) or Package Name (Android). The same Bundle ID must be used for when app updates are issued.   |
| Description       | The app description (i.e., <companyname> app platform, etc.).             |
| Type       | The app platform (i.e., iOS, Android, GearVR, or Oculus Rift).                |
| Current Version       | The app version (e.g., 1.1.1).                |
| Store URL       | The store URL that your app will be downloaded from (e.g. https://play.google.com/apps/<appname>, https://itunes.apple.com/us/<appname>), https://www.oculus.com/experiences/gear-vr/<appname>, and https://www.oculus.com/experiences/rift/<appname>).                 |
| Analytics ID       | The ID of the analytic bundle that includes captured statistical data about your app.    |

**To add an icon to your application profile:**

1. Go to **Organization > Apps > AppName > Profile**.
2. Select the profile icon and upload a icon via the dialog box.

## <a id="add-app-assets"></a>Step 3: Add Application Assets

* Clients will deliver assets to their Client Services representative based on their onboarding specification.
* Client services will add each asset to the Content Console (using an automated script or **Create New Application Asset** function).
* The assets will be packaged into an *asset bundle* that will then be added to each application platform build.
* Image assets must be uploaded using the exact names specified on the onboarding document provided to you by Client Services.
| Name         | Description    |
|:-----------------|:-------------------------------------|
| Name       | Asset name. Use an easy to understand naming convention.  |
| Description       | Enter an asset description (e.g., asset purpose, app location, platform, etc.). |
| Value       | Embed the Scalable Vector Graphics (SVG) code representation of the asset. |
| Upload       | Select the Cloud icon to select and upload an asset. |

## Step 4: Build, Test, and Refine Apps

* Client services and our engineering staff will test each app and work with clients to refine application.
* When a final application version is available, the client will establish accounts with each application store, and submit the application to each platform-specific store.
* Note that lead time for approval from app stores is approximately 10-14 days.
* Review each app stores' sign off timelines to ensure your app will be available for download based on your delivery requirements.  

## Step 5: Update Application Instance

The **App Profile** page allows you to update your application instance. The following table illustrates areas of the app that are available for update.

| Name         | Description    |
|:-----------------|:-------------------------------------|
| Application Name  | Update the app name.  |
| Published  | Update your apps published state (Yes/No). |
| Type  | Change your application's platform (iOS, Android, GearVR, Oculus) |
| Version  | Update your app version.  |
| Organization       | Organization where app is stored and managed. This field is non-editable. |
| Application Id  | A string that is auto-generated when your app is added to the Content Console and uniquely identifies the app. This field is non-editable. |
| Description  | Update your app description. |
| Scheme  | Represents the URI scheme used to open a mobile device application. Digital Domain native apps are assigne3d the default URI Scheme (im360://). Custom apps can assign unique URI Scheme.  |
| Bundle ID  | Update your the app ID that stores app settings and references the application. For iOS specify the Bundle ID, for Android apps specify the Package Name. |
| Analytics ID  | Update the Analytics ID that includes captured statistical data about your app. |
| Store URL  | Update the Store URL where your app could be downloaded. |
| Token Id       | Token that is used to verify the identity of user signed-in to an app. This field is non-editable. |
| Token Secret       | The token shared secret is updated if app security is compromised. This can only be updated by Client Services.  |

To update the application instance:

1. Select **Apps > App Name > Profile**. The *App Profile* page displays.
2. Update your app based on your requirements, then select **Update**.
