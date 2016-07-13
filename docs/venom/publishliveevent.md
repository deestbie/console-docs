
# Introduction

The following tutorial illustrates how to publish a live stream that is hosted on an external streaming Media Server or Content Delivery Network (CDN). You will:

#  About Live Streams

* Cameras that support live 360 video stitching and streaming can utilize the live stream option.

* You can live stream from a single 360 video camera or using an array of synchronized cameras (i.e., multiple 360 video cameras).

* Using your 360 video camera, you can create a customized RTSP request URL stream link for external media players, or let your camera generate a default URL.

* You can add live stream URLs from your Media Server or Content Delivery Network, or you can live stream directly from your 360 camera (depending on internet connectivity).

* You can add a URL to the Content Console for each 360 video camera and specify a camera label that uniquely identifies the stream, angle, and unique characteristics.

# PART 1 - COMPLETE PREREQUISITES

* Review [Video Publishing Requirements](videopublishrequirements.md)
* Define a [Video Property](createproperty.md)
* Define a [Video Collection](createcollection.md)

## PART 2: CREATE VIDEO PROFILE (for LIVE STREAM)

The following tutorial illustrates how to publish a live stream that is hosted on an external streaming Media Server or Content Delivery Network (CDN). You will:

* Define video metadata (i.e., title, description, pre stream / post stream text, and tags).
* Set the property and collection the live stream will be contained in.
* Configure video settings (i.e., project, blind spot, and visibility).
* Specify Stream URLs (Origin [Required], Return, Share, and Meta).
* Set live stream start time and duration.
* Review / update final configuration.
* Publish video.

## Step 1: Select Video Upload Method

1. In **Home > Properties > Property Name > Collection**.
2. In the collection select Upload Video (**+Upload Video**).
3. On the Uploader screen, select **URL FOR LIVE STREAM**.

![Upload Video](images\addvideo_livestream_cms.jpg "URL FOR LIEVE STREAM")

## Step 2: Define Video Metadata

Metadata is used to uniquely identify the characteristics of each video.

* Videos can be tagged with metadata including Title, Headline, Description, Pre Stream Text, and Post Stream Text.
* The default language for metadata is *English*.
* A Consumer will see the metadata on websites where a video is posted.  
* A Publisher can search for metadata in the Content Console.
* You can add additional language versions on the **Edit Video** page after the video upload process is complete.
* See [Video Metadata](terms.md#video-metadata) more information on metadata types.
<!--* The Add Language function allows you to add a new metadata instance to a video profile.-->
<!--* Content for additional languages can be defined in a Excel template and uploaded to the Content Console.-->

**To define video metadata:**

1. Go to **Details**.
2. Enter the (Stream) Title, Description, Pre Stream, and Post Stream text for your video.

## Step 3: Select Property and Collection

Assign a property to your video and group it in a collection. Note that both steps are required.

1. In **Assign to a property**, select a property from the drop-down to assign to the current video.
2. After you select the property, the **Assign to a collection"** drop-down displays and presents a list of collections associated with the current property. Select a collection to assign to the video.

## Step 4: Set Stream Projection

Indicate what type of video you will be uploading.

| Projection Type         | Description |
|:----------------|:--------------------------------------|
| Flat     | This mode supports Monoscopic 360° videos. This video type is typically filmed with a single camera and stitched together to form a single equirectangular video.   |
| Spherical      | This video type is usually filmed using two or more cameras and supports the use of HMD devices.     Characteristics include: <p></p><ul><li>Uses stereoscopic technique to render images so there is a slight offset between your left and right eye.</li> <li>This view creates and impression of depth a full 360 experience.</li></ul>

**To set video projection:**

1. Go to **Stream Projection?**
2. Select an option box to set video projection (i.e., Spherical or Flat).

## Step 5: Specify Stream Settings

The upload video process involves specifying a series of stream URLs for your live stream.

* Supported video formats include **MP4 HD (1040p)**, **MP4 (2K)**, and **MP4 (4K)**.
* Supported audio compression and encoding scheme is **Advanced Audio Coding (AAC)**
* See [Video Publishing Requirements](videopublishrequirements.md) for prerequisite steps and video and audio requirements.
* If you will be using multiple live stream cameras, the URL published during the initial upload process represents your first stream in the sequence. You will then specify subsequent streams via the *Camera* page after the initial upload process is complete.

**To specify stream URLs:**

1. Go **Stream Settings**.
2. Specify the following stream URL types:

| Stream URL Type          | Description               |
|:-------------------|:-------------------------------------|
| Stream Origin URL    | Input the publishing point URL where the live stream is originally hosted. |
| Stream Return URL    | Input the redirection URL to that the viewer will return to after the live-stream concludes. |
| Stream Share URL    | Input the meta URL that will upload when a video is shared on an external site.  |
| Stream Meta URL    | Input the meta URL that will upload when a video is shared on an external site.  |

## Step 6: Set Video Blind Spot

If your live stream camera generates a blind spot you can designate the blind spot location (None, Top or Bottom), and optionally fill the blank space by adding a custom photo, logo, or icon to fill the blank space in the App Assets section. See [Blind Spot](terms.md#blind-spot) for more information.

**To configure blind spot:**

1. Go to **Blindspot**.
2. Select from the drop-down based on the following scenarios:

| If Projection =             |
|:-----------------|:-------------------------------------|
| Flat, Blind Spot = None            |
| Spherical and video includes a Blind Spot, Blind Spot = Top or Bottom |
| Spherical and video does not include a Blind Spot, Blind Spot = None                             |

## Step 7: Configure Video Security

Throughout the publishing cycle, your videos will require different levels of security for access, downloading, and sharing to social networks. Video access levels include:

* **Private** - Video can be accessed by the console user who uploaded it.
* **Internal** - Video can be accessed by the console administrator and designated console users.
* **Public** - Video is visible to external consumers and can be accessed by console administrator and designated console users.

*As a best practice, set your video to private for the initial upload. You will need to add key art and set the broadcast time in post upload activities.*

**To configure video security:**

1. Go to **Settings > Visibility**.
2. Select an option box to set the access level.

## Step 8: Set Start Time and Duration

The time you set your video to broadcast is based on many factors. For example:

* You arrangements with web providers to post your video at a designated time.
* You have considerations relating to the geographical area / time zone where your video will be initially broadcast.
* You may be sequencing the premiere of a video based on an event or product launch, etc.
* If your video security is set to Private or Internal, set it to "Public" prior to the defined start time.

**To set video start time and duration:**

1. Go to **Settings > Start Time**.
3. Select the down arrow to load the calendar popup, then set the date and time the video will broadcast.
3. In **Duration (In Minutes)** specify a number that indicates estimated maximum live stream play time in minutes (e.g., 60 for 60 minutes).
3. If you are ready to publish the video, select **Review** to continue, or **Save for Later** to commit your changes and resume publishing this video at a later time. Your video will display in the Production Area on the **Home**. page.
4. Make sure your video is set to "Public" in  **Visibility** before the defined start time.

## Step 9: Review Stream Details

The Stream Details section allows you to review the current settings assigned to the video. You can also test / play the video in the Content Console, or use the embed a video link to test the video.

| Option / Setting         | Description            |
|:-----------------|:-------------------------------------|
| Views    | Displays the number of video views            |
| Uploaded    | Displays the date and time video was uploaded            |
| Visibility Settings    | Displays the current visibility setting for the video (Private, Internal, Public)            |
| Allow Downloads    | Displays video download setting Yes/No            |
| Allow Sharing    | Displays video sharing setting Yes/No            |
| File Size    | Displays video file size            |
| Duration    | Display video play time            |
| Embed Link    | Displays video player and embed link.             |
| Users    | Displays number of users in each role that has access to your video (Admins, Content Managers, Viewers)   |     

**To view stream details:**

1. Go to **Home > Properties > Collection > Video**.
2. Select **Stream Details**.
3. Review the video information. You can test the video by playing it, or using the embed video link.
4. To update video settings, go to the **Edit** section.

## Step 10: Review Video

The Review Video Profile page displays a final presentation of your video configuration.

1. Review the content for accuracy.
2. Verify that it represents the message and style you want to present.
3. Verify that the Embed URL presented launches to the correct page and works properly.
4. Verify that all referenced websites are correct.
5. Verify that the auto-generated thumbnail or custom key art displays properly.
5. Select the edit icon to make any adjustments.

## Step 11: Publish Video

1. If you are happy with the video configuration, select **Publish**.
2. Your video will go live on all the sites posted based on your designated start time.
3. If you need to add additional live stream cameras or perform additional updates to the live stream profile, select **Save**.
