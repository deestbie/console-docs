# Publishing a Hosted Video

The following tutorial illustrates how to publish a video that is hosted on the Content Console.

# PART 1 - COMPLETE PREREQUISITES

* Review [Media Publishing Requirements](mediapublishrequirements.md)
* Create [Property](manageproperty.md#create-property)
* Create [Collection](managecollection.md#create-collection)

# PART 2 - CREATE HOSTED VIDEO PROFILE

This section shows you how to publish a hosted video. You will:

* Select video source file to upload
* Define video metadata (i.e., title, headline, description, tags)
* Select video category
* Select the property and collection the hosted video will be contained in
* Configure video settings (i.e., visibility, downloadable, social sharing, video projection, and blind spot)
* Upload a video
* Test hosted video
* Upload key art
* Add video format
* Review final video configuration and publish video

## Step 1: Select Media Upload Method

1. You can launch the easy-to-use **Media Upload**  publishing tool using the following paths:

    * Select the Cloud Icon ![Cloud Icon](images\cloud_option.jpg "Upload Video") accessible via the Content Console header.

    * Navigate to **Property > Collection** and select **+Upload Video**.<p></p>

2. On the *Media Upload* page, select the **Hosted Video** option.

    ![Hosted Video Upload](images\hosted_video_tab.jpg "Hosted Video Option")

## Step 2: Select Video Source

The upload video process allows you to upload a VoD video. Supported video and audio requirements include:

| Type         | Description            |
|:-----------------|:-------------------------------------|
| Video Type      | On Demand (VoD)             |
| Video Format    | MP4 HD (1040p), MP4 (2K), and MP4 (4K) |
| Audio Compression and Encoding Scheme        | Advanced Audio Coding (AAC)                             |

* See [Video Publishing Requirements](mediapublishrequirements.md) for prerequisite steps and video and audio requirements.

**To select video source:**

1. Use **Drag and Drop** or **Browse** (click once) to select your video file. The name of the selected video file will display under the cloud icon.

## Step 3: Define Video Metadata

Metadata is used to uniquely identify the characteristics of each video.

* Videos can be tagged with metadata including Title, Headline, Description, and (Search) Tags.
* The default language for metadata is *English*.
* A Consumer will see the metadata on websites where a video is posted.  
* A Publisher can search for metadata in the Content Console.
* You can add additional language versions on the **Edit Video** page after the video upload process is complete.
* See [Video Metadata](terms.md#video-metadata) more information on metadata types.
<!--* The Add Language function allows you to add a new metadata instance to a video profile.-->
<!--* Content for additional languages can be defined in a Excel template and uploaded to the Content Console.-->

**To define video metadata:**

1. Go to **Details**.
2. Enter the Title, Headline, and Description for your video.
3. Enter one or more search Tags (comma separated). After entering each tag, select Return to commit it. The tag will display in blue. You can delete a tag by selecting "x". If attempt to add a tag name that already exists you will not be able to commit it.

## Step 4: Select Video Category

Select a category that best suits your video. Available options include Entertainment, Sports, Music, Action, Family, Games, Funny, Political, TV, Movies, News, Drama, Education, Art, and Travel.

1. Go to **Video Category Type**.
2. Select a category from the drop-down.

## Step 5: Select Property and Collection

Assign a property to your video and group it in a collection. Note that both steps are required.

1. Go to **Settings**.
2. In **Assign to a property**, select a property from the drop-down to assign to the current video.
2. After you select the property, the **Assign to a collection"** drop-down displays and presents a list of collections associated with the current property. Select a collection to assign to the video.

## Step 6: Configure Video Security

Throughout the publishing cycle, your videos will require different levels of security for access, downloading, and sharing to social networks.

*As a best practice, set your video to Private for the initial upload. You will need to add key art and set the video start time in post upload activities.*

Video access levels include:

| Visibility Setting     | Description   |
|:----------------|:--------------------------------------|
| Private    | Video can be accessed by the console user who uploaded it.   |
| Internal    | Video can be accessed by the console administrator and designated console users.    |
| Public      | Video is visible to external consumers and can be accessed by console administrator and designated console users.    |

**To configure video security:**

1. Go to **Visibility**.
2. Select an option box to set the access level.

## Step 7: Enable / Disable Video Downloading

You can set whether you want to enable or disable the ability for an external consumer to download a video.

* Option uses download method supported by website or device.
* Consumer must comply with video download terms of service of website or device.

**To enable / disable video downloading:**

1. Go to **Downloadable**.
2. Select an option box to enable/disable video download (Yes/No).

## Step 8: Enable / Disable Social Sharing

You can enable / disable social sharing of videos. Available social sharing networks is limited to those supported by the website or device a video is published on.

**To enable / disable social sharing:**

1. Go to **Sharing**.
2. Select an option box to enable/disable social sharing (Yes/No).

## Step 9: Set Video Projection

Indicate what type of video you will be uploading.

| Projection Type         | Description |
|:----------------|:--------------------------------------|
| Flat     | This mode supports Monoscopic 360° videos. This video type is typically filmed with a single camera and stitched together to form a single equirectangular video.   |
| Spherical      | This video type is usually filmed using two or more cameras and supports the use of HMD devices.     Characteristics include: <p></p><ul><li>Uses stereoscopic technique to render images so there is a slight offset between your left and right eye.</li> <li>This view creates and impression of depth a full 360 experience.</li></ul>

**To set video projection:**

1. Go to **VR Attributes**.
2. Go to **Projection**, select an option box to set video projection (i.e., Spherical or Flat).

## Step 10: Set Video Blind Spot

If your 360 video includes a blind spot and you adjusted it in post-production by adding a custom photo, logo, or icon to fill the blank space, you can designate the blind spot location (None, Top or Bottom). See [Blind Spot](terms.md#blind-spot) for more information.

**To configure blind spot:**

1. Go to **Blindspot**, select from the drop-down based on the following scenarios:

| If Projection =             | Setting   |
|:-----------------|:-------------------------------------|
| Flat      | Blind Spot = None            |
| Spherical and video includes a Blind Spot   | Blind Spot = Top or Bottom |
| Spherical and video does not include a Blind Spot   | Blind Spot = None     |

<!--## PART 4: Manage Video Profile

After your video is uploaded, the final step in the configuration process is to review and update your video details, upload video key art and set the video start time.-->

## Step 11: Upload Video

1. After completing your entries, select **Upload** begin the video upload. A progress indicator displays.
2. After the video upload is complete the **Edit** page displays.

The following table shows page options and permission state:

| Option / Setting         | Description            | Permission  |
|:-----------------|:-------------------------------------|------------|
| Update Key Art | Image that will display on video player. Select upload new image. | Update |
| Check Video | Performs master video file check. | Update |
| Video Origin    | Location where the video is hosted on the Digital Domain server. | Read-only |
| Video Title    | Title that summarizes video subject.          | Edit  |
| Headline    | Video headline caption.           | Edit |
| Description    | Video description.   | Edit |
| Visibility Settings  | Private, Internal, Public         | Update |
| Allow Downloads    | Video download setting Yes/No       | Update |
| Allow Sharing    | Video sharing setting Yes/No            | Update |
| Projection    | Video projection setting Flat/Spherical        | Update |
| Tags & Search Words    | List of search tags.        | Update |
| Views    | Number of video views.            | Read-only |
| Resolution    | Video resolution    | Read-only |
| Uploaded    | Video upload time.        | Read-only |
| File Size    | Video file size.        | Read-only |
| Duration    | Video play time.            | Read-only |
| Users    | Displays number of users in each role that has access to your video (Admins, Content Managers, Viewers)   | Read-only |
| Distribution Apps | Displays a list of apps the current video is associated with | Read-only |

## Step 12: Test Hosted Video

You can test the hosted VoD video to verify that it's running properly using the **Check Video** option. The following list briefly summarizes what happens during the hosted video check:

* Verify that the VoD MP4 file exists.

* Verify that the VoD content type is valid (e.g., application/octet-stream).

* Verify that the URL content-length matches video size.

* Verify that Access-Control-Allow-Origin header is valid.

* If the VoD is not accessible or raises errors, you will immediately receive a source error message.

* If the hosted video is successfully verified you will receive a confirmation message.

**To test hosted video:**

1. On the *Edit* page, select **Check Video**.
2. If the video is successful, you will receive a confirmation message.
3. If the video is not successful, you will receive a source error message. Determine steps necessary to resolve the errors and try again.  

## Step 13: Add Key Art

*Key Art* is an still image file that is used to showcase your video. It typically uses a memorable image or icon that represents the essence of the story or topic presented in a video. Key art is also referred to as a *thumbnail*. When your video was initially uploaded a thumbnail was assigned as the default start page.

* You can upload a key art to replace auto-generated version.
* Key Art displays on your video profile, property, and collection pages.

Supported key art size specifications include:

| Key Art Setting       | Description            |
|:-----------------|:-------------------------------------|
| Image Size    | 16:9, 1600 x 825     |
| Format    | 4K           |
| Live Area    | Square, 825 x 825           |

**To upload key art:**

1. Select **Upload Keyart**, select a file to upload based on the image requirements, then **Close**. The file will be uploaded when the video profile is saved.

## Step 14: Add Video Format

To add additional video formats to the current video profile, go to [Add Video Formats](addvideoformats.md) and follow the tutorial.

## Step 15: Publish Video

After completing your entries, review Hosted Video settings to verify they are correct.

1. If you would like your video to go live on all sites/applications where it is posted, set **Visibility** to **Public**.
2. If you are happy with the video configuration, and are ready to publish the video, select **Save**.
