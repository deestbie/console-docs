# Media Publishing Requirements

## What activities are involved in managing media assets on the Digital Domain Content Console?

* Content to be presented on Digital Domain websites or mobile device applications must be added to our Content Console.
* If you are not using a Media Server or Content Delivery Network, video content and live streams can be directly uploaded to our Content Console.
* Video content must be converted to the required format for Video on Demand (VOD) and Live Streaming video types prior to upload.
* Live stream URLs can be added from your Media Server or Content Delivery Network, or you can live stream directly from your 360 camera (depending on internet connectivity).
* Key Art (i.e., thumbnail) files for video uploads must be uploaded directly to the Content Console and cannot be referenced using a URL.

## What prerequisite steps must be completed prior to publishing content?

Before you publish media and application digital assets to the Content Console you must complete the following steps:

### Step 1. Create Media Assets

Prepare the following media assets and have them available prior to creating a media (video, external URL, or live event) or application profile in the Content Console. Because you will be required to upload a video, external URL, or post a live stream URL for a live event before you can save your video profile, having these assets available will help to expedite the video publishing process.

| Options          | Description                |
|:-------------------|:-------------------------------------|
| 360 Video Files       | Shoot 360 videos, perform post production, and generate output files. Determine if videos will be uploaded directly to the Digital Domain CMS, or whether they will be hosted on a Content Delivery Network or Media Server). In this scenario, you will need to have the external URL's of each video available.           |
| Live Event     | Determine number of live streams you will have per event (i.e., main stream, multiple camera angles, etc.), and where they will be hosted (i.e., Content Delivery Network, Media Server, or Direct from 360 video camera).           |
| Video Metadata         | Define video Title, Headline, Description, and Search Tags for each video language version. |
| Key Art          | Define thumbnails for each video that will stored in the Content Management System (i.e. Content Console).|

Note: Based on your distribution strategy, you may need to publish multiple video formats for the same video profile. These media assets should also be prepared as part of this prerequisite step.

### Step 2. Determine Digital Asset Storage and Management Approach

The digital asset management process involves storage of assets and managing them for presentation on websites or mobile device applications. Organizations with large projects typically use a combination of Content Delivery Network (CDN) services for storing digital assets and Content Management Systems (CMS) associated with each unique product.  

Based on your requirements select an external service to for managing your assets or use our hosted video solution:

*Streaming Media Service / Content Delivery Network (CDN)*

* Select a content delivery solution (high-end media server or Content Delivery Network) that can securely store your digital assets.
* Solution must support serving of content to end-users with high availability and high performance.
* Solution must provide easy-to-use codec conversion utilities that allow you to convert digital assets to the required format of any supported device.
* Solution must include a live streaming service.

*Digital Domain Hosted Video Solution*

* Upload videos and live stream directly to our server.
* In case of an outage, Content Console digital assets and the associated network infrastructure is stored on multiple offsite disparate locations to ensure continuity of service.

Contact our Client Services Specialists to develop a solution that best suits your needs and requirements.

### Step 3. Convert Video Digital Assets for Mobile Devices

***<a id="videos"></a>Videos***

Videos must be converted to the Video and Audio formats prior to being uploaded to the Content Console.

The supported codec for video and audio file formats for mobile devices is **H.264** also referred to as **MPEG-4 Part 10, Advanced Video Coding (MPEG-4 AVC), Version 10 (Constrained Baseline Profile)**.

*Supported Video File and Types*

The following video file types are supported for mobile devices:

*	Supported video formats include **MP4 HD (1040p)**, **MP4 (2K)**, and **MP4 (4K)**.
* Content Console supports **On Demand (VoD)** and **Live Stream,** video types.

***<a id="live-streams"></a>Live Streams***

The Digital Domain HTML5 Player supports HTTP streaming, but HTTPS is preferred. HTTPS is being the new standard because it is more secure and HTTPS is required if you want to include or request scripts, videos, images, iframes, etc.

Our HTML5 player supports the following HTTP Live Stream specification. The Live Media Playlist using HTTPS link outlines the preferred requirements.

* [HTTP Live Streaming](https://tools.ietf.org/html/draft-pantos-http-live-streaming-19)
* [Live Media Playlist Using HTTPS](https://tools.ietf.org/html/draft-pantos-http-live-streaming-19#section-8.2)

## Supported Video Formats

### --> Format HD

| Category         | Measurement                          |
|:-----------------|:-------------------------------------|
| Resolution       | 1920 x 1080                          |
| Encoding         | H.264 (Constrained Baseline Profile) |
| Framerate        | 30 FPS                               |
| Bitrate          | 3000 Kbps                           |
| Throughput       | 3M                                   |
| Distortion	   | Equirectangular   	 		  |
| Nadir Blind Spot | Top, Bottom, None 	 	          |
| Encode Options   | movflags faststart    		  |

### --> Format 2K
| Category         | Measurement                          |
|:-----------------|:-------------------------------------|
| Resolution       | 2048 x 1024			  |
| Encoding         | H.264 (Constrained Baseline Profile) |
| Framerate        | 30 FPS                               |
| Bitrate          | 4000 Kbps                            |
| Throughput       | 4M                                   |
| Distortion	   | Equirectangular   	 		  |
| Nadir Blind Spot | Top, Bottom, None 	 	          |
| Encode Options   | movflags faststart    		  |

### --> Format 4K
| Category         | Measurement                          |
|:-----------------|:-------------------------------------|
| Resolution       | 4096 x 2048			  |
| Encoding         | H.264 (Constrained Baseline Profile) |
| Framerate        | 60 FPS                               |
| Bitrate          | 8000 Kbps                          |
| Throughput       | 8M                                   |
| Distortion	   | Equirectangular   	 		  |
| Nadir Blind Spot | Top, Bottom, None 	 	          |
| Encode Options   | movflags faststart    		  |

## Supported Audio Format

| Category        | Format                                |
|:----------------|:--------------------------------------|
| Encoding        | MPEG-4 AAC                            |
| Channels        | Stereo                                |
| Sample Rate     | 48000 HZ                              |
| Bitrate         | 127 Kbps (kilobits per second)        |


## Video URL Checklist

* Verify the video URL is not behind a firewall.
* If your video is posted from another site, verify that you are in compliance with the sites posting rules and regulations.
* Verify the source video URL and not a copy.
* Accurately track any changes to posted URLs and promptly update the Content Console to avoid broken link.

## Key Art / Thumbnail Requirements

| Key Art Setting       | Description            |
|:-----------------|:-------------------------------------|
| Image Size    | 16:9, 1600 x 825     |
| Format    | 4K           |
| Live Area    | Square, 825 x 825           |
| Special Effects | Key Art will center on the x/y axis. A parallax effect can be applied to your Key Art image.  |
