
# Introduction

A Live event is composed of one or more live streams that are hosted on an external streaming Media Server, a Content Delivery Network (CDN), or streamed directly from a 360 camera.

#  About Live Events

* Cameras that support live 360 video stitching and streaming can utilize the live event option.

* You can add a live streams from a single 360 video camera or using an array of synchronized cameras (i.e., multiple 360 video cameras).

* Using your 360 video camera, you can create a customized RTSP request URL stream link for external media players, or let your camera generate a default URL.

* You can add live stream URLs from your Media Server or Content Delivery Network, or you can live stream directly from your 360 camera (depending on internet connectivity).

* You can add a URL to the Content Console for each additional 360 video camera and specify a camera label that uniquely identifies characteristics of the stream (e.g., angle, associated mobile devices, video format, etc.). See [Add Camera](addcamerastreams.md).

# PART 1 - COMPLETE PREREQUISITES

* Review [Media Publishing Requirements](mediapublishrequirements.md)
* Define a [Property](createproperty.md)
* Define a [Collection](createcollection.md)

## PART 2: CREATE LIVE EVENT

The following tutorial illustrates how to publish a live event that is hosted on an external streaming Media Server, Content Delivery Network (CDN), or directly from your 360 camera. You will:

* Specify stream origin
* Set the property and collection the live stream will be contained in.
* Define live event metadata (i.e., title, description, pre stream / post stream text, and tags).
* Configure live event visibility
* Set live event start time and duration.
* Specify additional stream URLs (Return, Share, and Meta)
* Set live stream projection
* Set stream blind spot
* Save live event
* Test live stream
* Add key art
* Edit live event
* Publish live event.

## Step 1: Select Media Upload Method

1. You can launch the easy-to-use **Media Upload** publishing tool using the following paths:

    * Select the Cloud Icon ![Cloud Icon](images\cloud_option.jpg "Upload Video") conveniently accessible via the Content Console header.

    * Navigate to **Property > Collection** and select **+Upload Video**.<p></p>

2. On the *Media Upload* page, select the **Live Event** option.

    ![Live Event Upload](images\live_event_tab.jpg "Live Event Option")

## Step 2: Specify Stream Origin URL

The first step in the live event setup process is to specify a Stream Origin URL. This URL type represents the publishing point URL where the live stream is originally hosted.

*Note: You can also specify additional optional Stream URLs (Stream Return, Stream Share, and Stream Meta). In Step X.*

Your live stream must meet the following requirements:

* Supported video formats include **MP4 HD (1040p)**, **MP4 (2K)**, and **MP4 (4K)**.
* Supported audio compression and encoding scheme is **Advanced Audio Coding (AAC)**
* See [Media Publishing Requirements](mediapublishrequirements.md) for prerequisite steps and video and audio requirements.
* If you will be using multiple live stream cameras, the URL published during the initial upload process represents your first stream in the sequence. You will then specify subsequent streams via the *Camera* page after the initial upload process is complete.
* You can set visibility for the entire "Live Event" instance *only*. You cannot set visibility for specific live stream camera entries within live event the instance (i.e., on the *Cameras* page).

**To specify the stream origin URL:**

1. Go to **Stream Origin URL**.
2. Specify the main stream for the live event.

## Step 3: Define Video Metadata

Metadata is used to uniquely identify the characteristics of each live event. Data entered here will be visibility for all stream entries (i.e., Stream Origin plus multiple camera entries).

* Videos can be tagged with metadata including Title, Description, Pre Stream Text, and Post Stream Text.
* The default language for metadata is *English*.
* A Consumer will see the metadata on websites where a video is posted.  
* A Publisher can search for metadata in the Content Console.
* You can add additional language versions on the **Edit Video** page after the video upload process is complete.
* See [Video Metadata](terms.md#video-metadata) more information on metadata types.

**To define video metadata:**

1. Go to **Details**.
2. Enter the (Stream) Title, Description, Pre Stream, and Post Stream text for your video.

## Step 4: Select Property and Collection

Assign a property to your live event and group it in a collection. Both steps are required.

1. Go to **Settings**.
2. In **Assign to a property**, select a property from the drop-down to assign to the current live event.
3. After you select the property, the **Assign to a collection"** drop-down displays and presents a list of collections associated with the current property. Select a collection to assign to the live event.

## Step 5: Configure Video Security

Throughout the publishing cycle, your  will require different levels of security for access, downloading, and sharing to social networks. Live event stream access levels include:

* **Private** - Live events can be accessed by the console user who uploaded it.
* **Internal** - Live events can be accessed by the console administrator and designated console users.
* **Public** - Live events are is visible to external consumers and can be accessed by console administrator and designated console users.

*As a best practice, set your live event to private for the initial upload. You will need to add key art in the post setup activities.*

**To configure live event security:**

1. Go to **Settings > Visibility**.
2. Select an option box to set the access level.

## Step 6: Set Start Time and Duration

The date and time you set your live event to broadcast is based on many factors. For example:

* You arrangements with web providers to post your live event at a designated time.
* You have considerations relating to the geographical area / time zone where your live event will be initially broadcast.
* You may be sequencing the premiere of a live event based on an event or product launch, etc.
* If your live event security is set to Private or Internal, set it to "Public" prior to the scheduled start time of the live event.

**To set video start time and duration:**

1. Go to **Settings > Start Time**.
3. Select the down arrow to load the calendar popup, then set the date and time the live event will broadcast.
3. In **Duration (In Minutes)** specify a number that indicates estimated maximum live event play time in minutes (e.g., 60 for 60 minutes).

## Step 7: Specify Additional Stream URLs (Optional)

You can optionally specify the following additional stream types for your live event:

| Stream URL Type          | Description               |
|:-------------------|:-------------------------------------|
| Stream Return URL    | The redirection URL the viewer will return to after the live-stream concludes. |
| Stream Share URL    | The URL that will upload when a video is shared on an external site.  |
| Stream Meta URL    | Typically includes a file uploaded with modified instructions on how to render
particular videos in the player.   |

**To specify stream URLs:**

1. Go **Settings**.
2. Specify each URL type as needed.

## Step 8: Set Live Stream Projection

Indicate what type of live stream you will be uploading.

| Projection Type         | Description |
|:----------------|:--------------------------------------|
| Flat     | This mode supports Monoscopic 360° videos. This stream type is typically filmed with a single camera and stitched together to form a single equirectangular video.   |
| Spherical      | This stream type is usually filmed using two or more cameras and supports the use of HMD devices.     Characteristics include: <p></p><ul><li>Uses stereoscopic technique to render images so there is a slight offset between your left and right eye.</li> <li>This view creates and impression of depth a full 360 experience.</li></ul>

**To set live stream projection:**

1. Go to **VR Attributes > Projection**.
2. Select an option box to set live stream projection (i.e., Spherical or Flat).

## Step 9: Set Video Blind Spot

If your 360 live stream includes a blind spot and you adjusted by adding a custom photo, logo, or icon to fill the blank space, you can designate the blind spot location (None, Top or Bottom). See [Blind Spot](terms.md#blind-spot) for more information.

**To configure blind spot:**

1. Go to **VR Attributes >  Blindspot**.
2. Select from the drop-down based on the following scenarios:

| If Projection =             | Setting   |
|:-----------------|:-------------------------------------|
| Flat      | Blind Spot = None            |
| Spherical and video includes a Blind Spot   | Blind Spot = Top or Bottom |
| Spherical and video does not include a Blind Spot   | Blind Spot = None     |

## Step 10: Create Live Event

1. After completing your entries, select **Create** create the live event.
2. After the live event instance is created **Edit** page displays.

## Step 11: Edit Live Event

The *Edit* page for a live event allows you to review Live Event settings to verify they are correct:

* Review the current settings assigned to the live event for accuracy.
* Verify that descriptions represent the message and style you want to present.
* Update the live event thumbnail as needed.
* Perform a stream check to validate that the live stream initiates properly.

The following table shows page options and permission state:

| Option / Setting         | Description            | Permission  |
|:-----------------|:-------------------------------------|------------|
| Update Key Art | Image that will display on video player. Select upload new image. | Update |
| Check Video | Performs master video file check. | Update |
| Start Time | Displays the date and time the live event will broadcast | Read-only |
| Projection | Displays the current live event projection setting (Flat/Spherical) | Read-only |
| Access | Displays the current visibility setting for the live event (Private/Internal/Public) | Read-only |
| Stream Title    | Title that summarizes live event subject.          | Update  |   
| Description    | Live event description.   | Update |
| Pre Stream Message | Introductory content for your live event. | Update |
| Post Stream Message | Text that will display after a live event has finished playing. | Update |
| Origin URL  | Publishing point URL where live event is originally hosted | Update |
| Return URL | The redirection URL the viewer will return to after the live-stream concludes.  | Update |
| Share URL | The URL that will upload when a live event is shared on an external site.  | Update |
| Meta URL | Typically includes a file uploaded with modified instructions on how to render
particular videos in the player.  | Update  |
| Visibility Settings  | Private, Internal, Public         | Update |
| Status | Indicates if the live event is active or stopped | Read-only|
| Stream Start Time | The live event stream broadcast time. | Update |
| Stream Duration | Live event play time. | Update |
| Users    | Displays number of users in each role that has access to the live event (Admins, Content Managers, Viewers)   | Read-only |
| Distribution Apps | Displays a list of apps the live event is associated with | Read-only |

**To edit the live event:**

1. Review the table above and update items as needed.  

## Step 12: Test Live Stream

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

1. On the *Edit* page*, select **Check Stream**.
2. If the stream check is successful, you will receive a confirmation message.
3. If the stream check is not successful, you will receive a source error message. Verify that your live stream is available and adheres to the HTTP Live Streaming requirements try again.

## Step 13: Add Key Art

*Key Art* is an still image file that is used to showcase your live event. It typically uses a memorable image or icon that represents the essence of the story or topic presented in a live event. Key art is also referred to as a *thumbnail*. When your live event was initially uploaded a thumbnail was assigned as the default start page.

* You can upload a key art to replace auto-generated version.
* Key Art displays on your live event profile, property, and collection pages.

Supported key art size specifications include:

| Key Art Setting       | Description            |
|:-----------------|:-------------------------------------|
| Image Size    | 16:9, 1600 x 825     |
| Format    | 4K           |
| Live Area    | Square, 825 x 825           |

**To upload key art:**

1. Select the current image and upload a new image based on the image requirements.

## Step 14: Publish Live Event

1. On the *Edit* page, if you are ready to publish the live event, select **Save**.
2. Make sure your live event is set to "Public" in  **Visibility** before the defined start time.
3. To add additional cameras to the current live event profile, go to [Add Camera](addcamerastreams.md).
