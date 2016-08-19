# Introduction

This topic includes topics on view, update, and maintenance activities that can be performed on video media profiles.

### How do I view a video profile?<a id="view-video-profile"></a>

1. Go to *Organization Name > Property > Collection*.
2. Select a video. The *Video Details* page displays.

### What activities can I perform on the video profile page?<a id="video-activities"></a>

The following table lists information that is displayed on the Video Details page. Each action:

* Indicates whether the activity is view/read-only on the page.
* Indicates if an available action exists that can be executed directly on the page.
* Indicates if an activity that is view only has an associated action (e.g., edit, update, etc.).

| Name             | Activity    | Associated Actions |
|:-----------------|:-------------------------------------|:-------------------------------------
| Property Name      | View / Read-Only   |  [Update Property](..\venom\manageproperty.md#update-property-video)     |
| Key Art   | Update   | [Upload / Refresh Key Art](managevideo.md#refresh-key-art-video)         |
| Collection Name   | View / Read-Only   | [Update Collection](..\venom\managecollection.md#update-collection)         |
| Visibility  | View / Read-Only     | [Update Visibility Settings](managevideo.md#update-visibility-video)         |
| Category  | View / Read-Only     |  [Update Category](managevideo.md#reassign-category-video)    |
| Views  | View / Read-Only     |  [Monitoring](..\venom\mediausageanalytics.md)        |
| Duration  | View / Read-Only     | None         |
| Play Video  | Action   |  [Play Video](managevideo.md#play-video)        |
| Copy Embed Code  | Action   |  [Copy Embed Code](managevideo.md#embed-code-video)           |
| Download | Enable/Disable   | [Enable / Disable Downloads](managevideo.md#enable-disable-downloads-video)         |
| View Formats  | Update | [Add New Format](..\venom\addvideoformats.md)          |

### How do I re-upload a video to a media profile?<a id="reupload-video"></a>

Currently, re-uploading a new video or external URL to replace an existing media entry is not supported. In this scenario, you will need to perform a new upload and create a new media profile.

### How do I obtain embed code for a video or external URL?<a id="embed-code-video"></a>

The *Video Details* pages include a **Copy Embed Code** option that allows you to embed videos (MP4 / External URLs) on external websites and social media sites. Example embed code looks similar to the following:

![Embed Code Example](images\embed_code_example.jpg "Embed Code Example")

**To copy embed code:**

1. Go to *Organization Name > Property > Collection*.
2. Select a video. The *Video Details* page displays.
3. Select **Copy Embed Code**. The Embed Code pop-up displays.
4. Select and copy the iframe code.
5. Integrate the code into your website or social media network.

### How do I download a video?<a id="download-video"></a>

The *Video Details* pages include a **Download** option that allows you to download videos that were initially uploaded using the Hosted Video or External URL option. This option is useful if you do not have Administrator privileges but need to download the video to upload to another Property or Collection, or convert to a different resolution.

**To download a video:**

1. Go to *Organization Name > Property > Collection*.
2. Select a video. The *Video Details* page displays.
3. Select **Download**. The video downloads using the method supported by your browswer.

### How do I test my hosted video?<a id="test-hosted-video"></a>

You can test the hosted VoD video to verify that it's running properly using the **Check Video** option. The following list briefly summarizes what happens during the hosted video check:

* Verify that the VoD MP4 file exists.
* Verify that the VoD content type is valid (e.g., application/octet-stream).
* Verify that the URL content-length matches video size.
* Verify that Access-Control-Allow-Origin header is valid.
* If the VoD is not accessible or raises errors, you will immediately receive a source error message.
* If the hosted video is successfully verified you will receive a confirmation message.

**To test hosted video:**

1. Go to *Organization Name > Property > Collection*.
2. Select a video. The *Video Details* page displays.
3. Select the *Edit* tab.
4. Select **Check Video**.
5. If the video is successful, you will receive a confirmation message.
6. If the video is not successful, you will receive a source error message. Determine steps necessary to resolve the errors and try again.  

### How do I play a video?<a id="play-video"></a>

1. Go to *Organization Name > Property > Collection*.
2. Select a video. The *Video Details* page displays.
3. Select **Play**.
4. Play speed is based on your wifi connection and local bandwidth. If a "not available" message displays, the video has either been taken down or the Content Delivery Network or Media Server URL is no longer valid.

### How do I upload or refresh key art?<a id="refresh-key-art-video"></a>

1. Go to *Organization Name > Property > Collection*.
2. Select a video. The *Video Details* page displays.
3. Select the *Edit* tab.
4. Select **Upload Key Art**.
5. Select a file to upload based on the image requirements, then **Close**.
6. Select **Save** to commit your changes and upload the new key art image.

### How do I change the property or collection of a media profile?<a id="change-property-collection-video"></a>

1. Go to *Organization Name > Property > Collection*.
2. Select a video. The *Video Details* page displays.
3. Select the *Edit* tab.
4. From the **Property** drop-down, select a new property to assign to the current video.
5. From the **Collection** drop-down, select a new property to assign to the current video.
6. After completing your selections, **Save**. The video will be regrouped into the new property and/or collection.

### How do I update the visibility settings of a media profile?<a id="update-visibility-video"></a>

A variety of scenarios may require you to change your visibility settings. For example:

* Your media profile configuration is complete and you are now ready to go live and publish it (i.e., set to Public).
* There is a technical issue with your media profile and you want to temporarily take it offline (i.e., set it to Private or Internal).
* The established run time of your media profile has completed and you want to permanently take it offline (i.e., set it to Private or Internal)

**To update visibility settings:**

1. Go to *Organization Name > Property > Collection*.
2. Select a video. The *Video Details* page displays.
3. Select the *Edit* tab.
4. In *Visibility*, select Private, Internal, or Public.
5. After completing your selections, **Save**. The visibility of your video will be updated. Videos that are set to Internal or Private will be removed from any collections exposed in your applications. Embedded URLs will present the video content as no longer available.

### How do I reassign a video to a different category?<a id="reassign-category-video"></a>

If you need to reclassify your video, you can reassign it to a new category on the *Edit* page.

**To update a video category:**

1. Go to *Organization Name > Property > Collection*.
2. Select a video. The *Video Details* page displays.
3. Select the *Edit* tab.
4. In *Category*, reassign your video to one of the following options: Entertainment, Sports, Music, Action, Family, Games, Funny, Political, TV, Movies, News, Drama, Education, Art, and Travel.
5. After completing your selections, **Save**. Your video will resort under the newly assigned category on the website and mobile device application platforms.

### How do I enable or disable downloads for a video?<a id="enable-disable-downloads-video"></a>

The ability to download a video versus playing it over the wire can greatly enhance the user experience, especially when there are scenarios where Internet bandwidth is not sufficient to get a continuous stream.

*Note: Certain factors may affect your ability to offer downloadable videos to users including ownership, video size, legal, etc. It's important that you verify the distribution requirements for each video prior to enabling the download capability.*

**To enable/disable video download option:**

1. Go to *Organization Name > Property > Collection*.
2. Select a video. The *Video Details* page displays.
3. Select the *Edit* tab.
4. In *Allow Downloads*, select Yes or No.
5. After completing your selection, **Save**.
6. A download icon will be visible in mobile device applications or websites where a video is embedded to allow downloading, and the Content Console *Video Details* will indicate **Download Allowed** or **Download Not Allowed**.

### How do I enable or disable video sharing?<a id="enable-disable-video-sharing"></a>

Based on your video distribution requirements, you can enable or disable the ability of a user to share a video on a social media site. The ability to offer videos to share is based on your specific video distribution requirements.

**To enable/disable video sharing option:**

1. Go to *Organization Name > Property > Collection*.
2. Select a video. The *Video Details* page displays.
3. Select the *Edit* tab.
4. In *Allow Downloads*, select Yes or No.
5. After completing your selection, **Save**.
6. A list of sharable social networks will be visible in mobile device applications or websites where a video is embedded to allow downloading, and the Content Console *Video Details* page will indicate **Sharing Allowed** or **Sharing Not Allowed**.

### How do I add an language to a video media profile?<a id="add-language-video"></a>

The following topics illustrate how to add a language to a video media profile:

* [Add Language - Video](addlanguage.md#add-language-video)

### How do I delete a language in a video media profile?<a id="delete-language-video"></a>

The following topic illustrate how to delete a language in a video media profile:

* [Delete Language](addlanguage.md#delete-language-video)

### How do I update metadata for a video profile?<a id="update-metadata-video"></a>

1. Go to *Organization Name > Property > Collection*.
2. Select a video. The *Video Details* page displays.
3. Select the *Edit* tab.
4. Update Title, Headline, Description, and Tags.
5. Perform an update and **Save**. The *Video Details* page displays and presents your updated content.

### How do I add a new format to a video profile?<a id="add-new-format-video"></a>

See [Add Video Format](addvideoformats.md) for details on uploading a VoD file, or adding an External Video URL.

### How do I change the projection of a media profile?<a id="change-projection-video"></a>

1. Go to *Organization Name > Property > Collection*.
2. Select a video. The *Video Details* page displays.
3. Select the *Edit* tab.
4. Perform an update and **Save**. The *Video Details* page displays and presents your updated content.

### How do I change the blindspot setting of a media profile?<a id="change-blindspot-video"></a>

Adding blindspot artwork to your video in post production is generally performed before you create a media profile. To update the blindspot position of a video:

1. Go to *Organization Name > Property > Collection*.
2. Select a video. The *Video Details* page displays.
3. Select the *Edit* tab.
4. In *Blindspot* select None, Top, or Bottom.
5. To commit your entries, **Save**.

| If Projection =             | Setting   |
|:-----------------|:-------------------------------------|
| Flat      | Blind Spot = None            |
| Spherical and video includes a Blind Spot   | Blind Spot = Top or Bottom |
| Spherical and video does not include a Blind Spot   | Blind Spot = None     |

### How do I save a media profile?<a id="save-media-profile-video"></a>

Updates to video media profiles are performed on the *Edit* page. After you perform an update you use **Save** to commit your changes.

**To save a media profile:**

1. Go to *Organization Name > Property > Collection*.
2. Select a video. The *Video Details* page displays.
3. Select the *Edit* tab.
4. Perform an update and **Save**. The *Video Details* page displays and presents your updated content.
