# Introduction

This topic provides information about Content Console application publishing process.

# What is involved in the application publishing process?

The Digital Domain *Client Services* department manages the application publishing process and works with each client to gather specific requirements, publish these assets to each application, and add the application instance to the Content Console. Activities include:

## Step 1: Gather Application Requirements

* Determine if a custom application is needed and define requirements.
* Determine supported app platforms (e.g., iOS, Android, GearVR, Oculus Rift).
* Determine assets required for each app including:

| Asset         | Description                |
|:-----------------|:-------------------------------------|
| App Branding Logos  | Custom branding logos for app pages (.PNG).  |
| CMS Branding Logos  | Custom branding logos for Content Console Organization page (.PNG)   |
| Landing/Splash Page  | App landing page images. (.JPG)               |
| Event Icons      | Unique icons for specific app events or sections.                 |
| App Icons  | App icon that will display on each mobile device after application is installed (.PNG file type)  |
| Video Player Icons  | Icon that will display on app video player to uniquely identify your brand. (.PNG file type)  |
| Brand Assets       | Set of full sized brand assets for design development.     |
| Background Images   | Keyframe images to be used for live events or VoD metadata. This requirement will vary per each custom app.                |

Notes:

* Size requirements are not specified as they will vary for each custom app and will be defined on each clients'  onboarding specification document.
* If you will be publishing applications for all four platforms, you will be providing one set of onboarding assets for each platform.

## Step 2: Add Application to Content Console

Each client will provide their Client Services representative with the App Store URL for each specific platform app.

* Client Services will then add an instance of each app to the Digital Domain Content Console.
* Each completed app can then be associated with a specific property and added to the *Distribution Apps* section for videos in each Collection.

To add an app to the Content Console:

1. Select **Organization > Apps**. The *Applications* page displays and presents a list of applications currently added to the organization.
2. Select **+Application**. The *Create New Application* popup displays.
3. Enter the information in the table listed below.
4. Select **Register** to save the application.

| Name         | Description                |
|:-----------------|:-------------------------------------|
| Organization       | The name of the organization the app is defined in.                |
| App Name       | The internal app name.                |
| Bundle ID       | The ID of the asset bundle that includes branding art and stylesheet information for the app (e.g. com.<appname>.<companyname>).                |
| Description       | The app description (i.e., <companyname iOS App).             |
| Type       | The app platform (i.e., iOS, Android, GearVR, or Oculus Rift).                |
| Current Version       | The app version (e.g., 1.1.1).                |
| Store URL       | The store URL that your app will be downloaded from (e.g. https://play.google.com/apps, https://itunes.apple.com/us/app).                |
| Analytics ID       | The ID of the analytic bundle that includes captured statistical data about your app.    

To add an icon to your application profile:

1. Go to **Organization > Apps > AppName > Profile**.
2. Select the profile icon and upload a icon via the dialog box.

## Step 3: Add Application Assets

* Clients will deliver assets to their Client Services representative based on their onboarding specification.
* Client services will add each asset to the Content Console (using an automated script or **Create New Application Asset** function).
* The assets will be packaged into an *asset bundle* that will then be added to each application platform build.

| Name         | Description    |
|:-----------------|:-------------------------------------|
| Name       | Asset name. Use an easy to understand naming convention.  |
| Description       | Enter an asset description (e.g., asset purpose, app location, platform, etc.). |
| Value       | Embed the Scalable Vector Graphics (SVG) code representation of the asset *OR*...  |
| Upload       | Select the Cloud icon to select and upload an asset. |

## Step 4: Build, Test, and Refine Apps

* Client services and our engineering staff will test each app and work with clients to refine application.
* When a final application version is available, the client will establish accounts with each application store, and submit the application to each platform-specific store.
* Note that lead time for approval from app stores is approximately 10-14 days.
* Review each app stores' sign off timelines to ensure your app will be available for download based on your delivery requirements.  

## Step 5: Update Application Tokens

The **Apps > Token** section defines the self-encryption scheme used for the app. All information is auto-generated as part of the app creation process. Token secret can be updated if a app security has been compromised.

*Note: Token secrets are updated by your Client Services only.*

| Name         | Description    |
|:-----------------|:-------------------------------------|
| Organization       | Organization where app is stored and managed. This field is non-editable. |
| Application Id  | A string that is auto-generated when your app is added to the Content Console and uniquely identifies the app. This field is non-editable. |
| Application Name  | Application name. This field is non-editable.  |
| Token Id       | Token that is used to verify the identity of user signed-in to an app. This field is non-editable. |
| Token Secret       | Token shared secret. This field is editable and a new token secret can be added if app security has been compromised.  |

To update the token secret:

1. Generate a new token secret for the app using a random key generator, or prescribed method.
2. Select **Apps > Token**. The *Applications* page displays and presents a list of applications currently added to the organization.
3. Select an application from the *Applications Summary*.
3. Select *Token* tab.
4. Enter new Token Secret and select **Update**.
5. Select **Create** to save the asset.
