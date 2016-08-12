# Introduction

This topic includes information on post-upload Content Console management tasks.

### How do I re-upload a video to a media profile?

Currently, re-uploading a new video, external URL, or live feed to replace an existing media entry is not supported. In this scenario, you will need to perform a new upload and create a new media profile.

### How do I obtain embed code for a video, external URL, or live event that I can post on an external website?

The *Video Details* and *Stream Details* pages include a **Copy Embed Code** option that allows you to embed videos (MP4 / External URLs) and live events on websites and social media sites. Example embed code looks similar to the following:

![Embed Code Example](images\embed_code_example.jpg "Embed Code Example")

**To copy embed code:**

1. Go to *Organization Name > Property > Collection*.
2. Select a video or live event. The *Video Details* page displays.
3. Select **Copy Embed Code**. The Embed Code pop-up displays.
4. Select and copy the iframe code.
5. Integrate the code into your website or social media network.

### How do I download a video?

The *Video Details* pages include a **Download** option that allows you to download videos that were initially uploaded using the Hosted Video or External URL option. This option is useful if you do not have Administrator privileges but need to download the video to upload to another Property or Collection, or convert to a different resolution.

**To download a video:**

1. Go to *Organization Name > Property > Collection*.
2. Select a video or live event. The *Video Details* page displays.
3. Select **Download**. The video downloads using the method supported by your browswer.

### How do I test my hosted video?

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
2. If the video is successful, you will receive a confirmation message.
3. If the video is not successful, you will receive a source error message. Determine steps necessary to resolve the errors and try again.  

### How do I test my live stream?

You can test the stream for your live event to determine if its running properly using the **Check Stream** option. The function executes a live stream check service and verifies the live stream against the Internet Engineering Task Force (IETF) document [HTTPS Live Streaming
draft-pantos-http-live-streaming-19](https://tools.ietf.org/html/draft-pantos-http-live-streaming-19).

The following list briefly summarizes what happens during the live stream check:

* Verify that the live stream playlist exists.
* Verify that the live stream playlist is valid according to the specification. Each playlist includes "tags." Some tags are required, other tags are required only when tags with specific values are present.
* The **Check Stream** service drills down through the HTTP Live Streaming rules to verify if the live stream playlist is valid.
* If the live stream is stopped, you will immediately receive a source error message. This indicates that the URL is not accessible. Because the stream content cannot be accessible the stream check ends.
* If the live stream is started, but the protocols do not match the HTTP Live Streaming specification, you will also receive a source error message.
* If the live stream is started and is successfully verified against the HTTP Live Streaming specification, you will receive a confirmation message that the stream check was successful.  

**To test live event stream:**

1. Go to *Organization Name > Property > Collection*.
2. Select a video. The *Video Details* page displays.
3. Select the *Edit* tab.
4. Select **Check Stream**.
2. If the stream check is successful, you will receive a confirmation message.
3. If the stream check is not successful, you will receive a source error message. Verify that your live stream is available and adheres to the HTTP Live Streaming requirements try again.

### How do I upload or refresh key art?

1. Go to *Organization Name > Property > Collection*.
2. Select a video or live stream. The *Video Details* or *Stream Details* page displays.
3. Select the *Edit* tab.
1. Select **Upload Key Art**.
2. Select a file to upload based on the image requirements, then **Close**. The file will be uploaded when the video profile is saved.

### How do I change the property or collection of a media profile?

1. Go to *Organization Name > Property > Collection*.
2. Select a video or live stream. The *Video Details* or *Stream Details* page displays.
3. Select the *Edit* tab.
4. From the **Property** drop-down, select a new property to assign to the current video.
5. From the **Collection** drop-down, select a new property to assign to the current video.
6. After completing your selections, **Save**. The video or live stream will be resorted into the new property and/or collection.

### How do I update the visibility settings of a media profile?

A variety of scenarios may require you to change your visibility settings. For example:

* Your media profile configuration is complete and you are now ready to go live and publish it (i.e., set to Public).
* There is a technical issue with your media profile and you want to temporarily take it offline (i.e., set it to Private or Internal).
* The established run time of your media profile has completed and you want to permanently take it offline (i.e., set it to Private or Internal)

**To update visibility settings:**

1. Go to *Organization Name > Property > Collection*.
2. Select a video or live stream. The *Video Details* or *Stream Details* page displays.
3. Select the *Edit* tab.
4. In *Visibility*, select Private, Internal, or Public.
6. After completing your selections, **Save**. The visibility of your video or live stream be updated. Videos that are set to Internal or Private will be removed from any collections exposed in your applications. Embedded URL will present the video content as no longer available.

### How do I enable or disable downloads for a video?

The ability to download a video versus playing it over the wire can greatly enhance the user experience, especially when there are scenarios where Internet bandwidth is not sufficient to get a continuous stream.

*Note: Certain factors may affect your ability to offer downloadable videos to users including ownership, video size, legal, etc. It's important that you verify the distribution requirements for each video prior to enabling the download capability.*

**To enable/disable video download option:**

1. Go to *Organization Name > Property > Collection*.
2. Select a video or live stream. The *Video Details* or *Stream Details* page displays.
3. Select the *Edit* tab.
4. In *Allow Downloads*, select Yes or No.
5. After completing your selection, **Save**.
7. A download icon will be visible in mobile device applications or websites where a video is embedded to allow downloading, and the Content Console *Video Details* will indicate **Download Allowed** or **Download Not Allowed**.

### How do I enable or disable video sharing?

Based on your video distribution requirements, you can enable or disable the ability of a user to share a video on a social media site. The ability to offer videos to share is based on your specific video distribution requirements.

**To enable/disable video sharing option:**

1. Go to *Organization Name > Property > Collection*.
2. Select a video or live stream. The *Video Details* or *Stream Details* page displays.
3. Select the *Edit* tab.
4. In *Allow Downloads*, select Yes or No.
6. After completing your selection, **Save**.
7. A list of sharable social networks will be visible in mobile device applications or websites where a video is embedded to allow downloading, and the Content Console *Video Details* page will indicate **Sharing Allowed** or **Sharing Not Allowed**.

### How do I add an language to a media profile?

The following topics illustrate how to add a language to video and live event media profiles:

* [Add Language - Video](addlanguage.md#add-language-video)
* [Add Language - Live Event](addlanguage.md#add-language-stream)

### How do I delete a language in a media profile?

The following topic illustrate how to delete a language in a video or live event media profile:

* [Delete Language](addlanguage.md#delete-language)

### How do I update metadata for a video profile?

1. Go to *Organization Name > Property > Collection*.
2. Select a video. The *Video Details* page displays.
3. Select the *Edit* tab.
4. Update Title, Headline, Description, and Tags.
4. Perform an update and **Save**. The *Video Details* page displays and presents your updated content.

### How do I update metadata for a live event profile?

1. Go to *Organization Name > Property > Collection*.
2. Select a live event. The *Stream Details* page displays.
3. Select the *Edit* tab.
4. Update Stream Title, Pre Stream Message, Post Stream Message, Description, and Tags.
4. Perform an update and **Save**. The *Stream Details* page displays and presents your updated content.

### How do I add a new format to a video profile?

See [Add Video Format](addvideoformats.md) for details on uploading a VoD file, or adding an External Video URL.

### How do I change the projection of a media profile?

1. Go to *Organization Name > Property > Collection*.
2. Select a video or live stream. The *Video Details* or *Stream Details* page displays.
3. Select the *Edit* tab.
4. Perform an update and **Save**. The *Video Details* or *Stream Details* page displays and presents your updated content.

### How do I change the blindspot setting of a media profile?

Adding blindspot artwork to your video in post production is generally performed before you create a media profile. With live stream video the blind spot position could change if your camera position changes. To update the blindspot position of a video of live stream:

1. Go to *Organization Name > Property > Collection*.
2. Select a video or live stream. The *Video Details* or *Stream Details* page displays.
3. Select the *Edit* tab.
4. In *Blindspot* select None, Top, or Bottom.
4. To commit your entries, **Save**.

| If Projection =             | Setting   |
|:-----------------|:-------------------------------------|
| Flat      | Blind Spot = None            |
| Spherical and video includes a Blind Spot   | Blind Spot = Top or Bottom |
| Spherical and video does not include a Blind Spot   | Blind Spot = None     |

### How do I save a media profile?

Updates to video or live event media profiles are performed on the *Edit* page. After you perform an update you use **Save** to commit your changes.

**To save a media profile:**

1. Go to *Organization Name > Property > Collection*.
2. Select a video or live stream. The *Video Details* or *Stream Details* page displays.
3. Select the *Edit* tab.
4. Perform an update and **Save**. The *Video Details* or *Stream Details* page displays and presents your updated content.
