
# Publishing an External Video

The following tutorial illustrates how to publish a URL to an externally published MP4 video file.

# PART 1 - COMPLETE PREREQUISITES

* Review [Video Publishing Requirements](videopublishrequirements.md)
* Define a [Video Property](createproperty.md).
* Define a [Video Collection](createcollection.md)

# PART 2 - CREATE VIDEO PROFILE (FOR EXTERNALLY HOSTED VIDEO)

This section shows you how to publish a hosted video. You will:

* Set the property and collection the hosted video is contained in
* Configure video settings (i.e., visibility, downloading, sharing, projection, and blind spot)
* Define video metadata (i.e., title, description, tags)
* Upload a video
* Review / update final configuration
* Publish video

## Step 1: Select Video Upload Method

1. In **Home > Properties > Property Name > Collection**, select Upload Video (**+Upload Video**).
3. On the *Add A Video* menu, select **URL for Externally Hosted Video**.

![Add a Video](images\addvideo_external_url.jpg "URL for Externally Hosted Video")

## Step 2: Select Property and Collection

Assign a property to your video and group it in a collection. Note that both steps are required.

1. In **Assign to a property**, select a property from the drop-down to assign to the current video.
2. After you select the property, the **Assign to a collection"** drop-down displays and presents a list of collections associated with the current property. Select a collection to assign to the video.

## Step 3: Configure Video Security

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
2. Select a option box to set the access level.

## Step 4: Enable / Disable Video Downloading

You can set whether you want to enable or disable the ability for an external consumer to download a video.

* Option uses download method supported by website or device.
* Consumer must comply with video download terms of service of website or device.

**To enable / disable video downloading:**

1. Go to **Downloadable**.
2. Select an option box to enable/disable video download (Yes/No).

## Step 5: Enable / Disable Social Sharing

You can enable / disable social sharing of videos. Available social sharing networks is limited to those supported by the website or device a video is published on.

**To enable / disable social sharing:**

1. Go to **Sharing**.
2. Select an option box to enable/disable social sharing (Yes/No).

## Step 6: Define Video Metadata

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
3. Enter one or more search Tags (comma separated).

## Step 7: Select Video Category

Select a category that best suits your video. Available options include Entertainment, Sports, Music, Action, Family, Games, Funny, Political, TV, Movies, News, Drama, Education, Art, and Travel.

1. Go to **Video Category Type**.
2. Select a category from the drop-down.

## Step 8: Set Video Projection

Indicate what type of video you will be uploading.

**Flat** - This mode supports Monoscopic 360° videos. This video type is typically filmed with a single camera and stitched together to form a single equirectangular video.

**Spherical** - This video type is usually filmed using two or more cameras and supports the use of HMD devices.     Characteristics include:

  * Uses stereoscopic technique to render images so there is a slight offset between your left and right eye.
  * This view creates and impression of depth a full 360 experience.

**To set video projection:**

1. Go to **Projection**.
2. Select an option box to set video projection (i.e., Spherical or Flat).

## Step 9: Set Video Blind Spot

If your video includes a blind spot and you adjusted it in post-production by adding a custom photo, logo, or icon to fill the blank space, you can designate the blind spot location (None, Top or Bottom). See [Blind Spot](terms.md#blind-spot) for more information.

**To configure blind spot and projection:**

1. Go to **Blindspot**.
2. Select from the drop-down based on the following scenarios:

| If Projection =             |
|:-----------------|:-------------------------------------|
| Flat, Blind Spot = None            |
| Spherical and video includes a Blind Spot, Blind Spot = Top or Bottom |
| Spherical and video does not include a Blind Spot, Blind Spot = None                             |

## Step 10: Specify Video URL

MP4 files associated with the specified URL must meet the following video and audio requirements:

| Type         | Description            |
|:-----------------|:-------------------------------------|
| Video Type      | On Demand (VoD)             |
| Video Format    | MP4 HD (1040p), MP4 (2K), and **MP4 (4K)* |
| Audio Compression and Encoding Scheme        | Advanced Audio Coding (AAC)                             |

See [Video Publishing Requirements](videopublishrequirements.md) for prerequisite steps and video and audio requirements.

**To specify a video url:**

1. Go to **External Video URL**.
2. Enter the video URL into the text box.
3. After the upload is complete, you will see a **Review** confirmation prompt.
<!--4. Confirm that your **Basic Video Information** and **Video Settings** are correct, then select **Publish**.-->

<!--## PART 4: Manage Video Profile

After your video is uploaded, the final step in the configuration process is to review and update your video details, upload video key art and set the video start time.-->

## Step 11: Review / Update Final Details

The **Video > Edit** page displays a final presentation of your video configuration. Here you can:

* Review the current settings assigned to the video for accuracy.
* Verify that descriptions represent the message and style you want to present.
* Update the video thumbnail as needed.
* Perform a video check to validate that the master video file is properly uploaded and initiates the stream.

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
| Tag & Search Words    | List of search tags.        | Update |
| Views    | Number of video views.            | Read-only |
| Downloads    | Number of video downloads.    | Read-only |
| Uploaded    | Video upload time.        | Read-only |
| File Size    | Video file size.        | Read-only |
| Duration    | Video play time.            | Read-only |
| Users    | Displays number of users in each role that has access to your video (Admins, Content Managers, Viewers)   | Read-only |
| Distribution Apps | Displays a list of apps the current video is associated with | Read-only |


**To update video details:**

1. Review the table above and Edit / Update items as needed.

**To update video key art:**

*Key Art* is an still image file that is used to showcase your video. It typically uses a memorable image or icon that represents the essence of the story or topic presented in a video. Key art is also referred to as a *thumbnail*. When your video was initially uploaded a thumbnail was assigned as the default start page.

* The initial video upload process auto-generates a thumbnail.
* You can upload a key art to replace auto-generated version.
* Key Art displays on your video profile, property, and collection pages.

Supported key art size specifications include:

| Key Art Setting       | Description            |
|:-----------------|:-------------------------------------|
| Image Size    | 16:9, 1600 x 825     |
| Format    | 4K           |
| Live Area    | Square, 825 x 825           |

**To upload key art:**

1. Select the current image and upload a new image based on the image requirements.

## Step 12: Publish Video

1. If you would like your video to go live on all sites/applications where it is posted, set visibility to **Public**.
2. If you are happy with the video configuration, click **Save**.
