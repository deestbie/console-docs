# Terminology

#### <a id="digital-assets"></a>Digital Assets

Digital assets are image files, media (video files, live stream URLs, external videos), description text (metadata) used to describe properties, collections, media profiles for Videos, Live Events, External Video, and profiles for mobile device applications in the Content Console.

#### <a id="property"></a>Property
Represents the top-level branding element of your videos (e.g., TV Network).

* Organization Administrators are responsible for creating and managing properties.
* A list of available properties display on the Content Console Home page.
* Within each property you define one or more mobile device applications.
* Within each property you define one or more video collections.
* You then add videos to collections defined in a property.
* You select a property and collection during the video upload process (i.e., Hosted, Live Event, URL).
* A video can be reassigned to a different property and collection after it is uploaded.
* A new property is auto-assigned a Display Priority number that reflects the display sequence on the Properties Summary. This setting can be updated as a post creation task using the Edit Property function. Numbers are assigned in sequential order based on when a property is initially defined.

#### <a id="collection"></a>Collection
A sub-category of a Property (e.g., TV Series Name). Within each Collection you also define a Season that represents a subcategory of the collection (i.e. episode #, etc.).  

#### <a id="collection"></a>Collection Type
A subcategory of a Collection and is used for grouping video content.

* It can include one or more segments (i.e., video upload), a set of related productions, or a single event.
* Developing a good naming convention strategy for a Season is important to ensure a consistent presentation when adding additional seasons.
* For example, using Episode, Event, or Part consistently followed for a numbering sequence.

#### <a id="video-metadata"></a>Video Metadata

Metadata allows you to describe the content of a video. The following list includes the metadata categories supported by the Content Console and composition guidelines.

**Title (Required)**

* Effective titles summarize the video subject.
* They typically contain 5 words are less.
* Use descriptive keywords that grab a viewers attention.
* Should make sense out of context when they appear in search research.
* There is no character limitation for video titles.
* The first 50 characters (including spaces) display in a search list.

**Headline**

* Effective headlines use a unique a set of reasons why a user should view your video.
* Some techniques for creating catchy headlines include using numbers, trigger words, adjectives, keywords, and promises (e.g., details on what you will experience when watching the video, etc.).
* Note that a Headline is optional and will only display on the *Video Details* page if content is defined. 

**Description**

* Effective descriptions are concise (e.g., a small paragraph or lead-in sentence with bullet points).
* Should include exciting descriptions about video topic that will attract viewers attention.
* Should include hashtags (#) so they can be easily promoted on social media site.
* Should include credits associated with video creator, participants, actors, promoters, etc.

**Pre Screen Text** (for LIVE EVENT ONLY)

* Represents introductory content for your video.

**Post Screen Text** (for LIVE EVENT ONLY)

* Represents text that will display after a video has finished playing (e.g., Thanks for watching, Visit our website, etc.).

**Tags**

* Search tags help to promote your video on social media sites and search engines.
* Should contain keywords on who you are (individual, business, event, etc.)
* To gain an edge on coverage, perform research on competitors, sites most relevant to your video subject, and tag names.
* Search tags must be comma separated.
* Tags are committed by selecting Return. The tag will display in blue.
* You can delete a tag by selecting "x".
* If attempt to add a tag name that already exists you will not be able to commit it.

#### <a id="blind-spot"></a>Blind Spot

Because a 360 video is created using multiple cameras, it’s possible your video output could include some clipping of content referred to as a *Nadir Blind Spot*.

* The blind spot represents the position where the camera rig is supported and the tripod point is either left out of the video or the images are pinched together to eliminate the hole.

* The blind spot is usually corrected in post-production and filled in to imply a fully captured 360 image.

* The blind spot is typically filled by superimposing footage in that area or by inserting a “black” image at the nadir of the 360 video. The blind spot can then be used to populate with advertising space, navigations, or other uses.  

If your video includes a blind spot and you adjusted it in post-production by adding a custom photo, logo, or icon to fill the blank space, you can designate the blind spot location (None, Top or Bottom) on the video profile page.

#### <a id="video-collection"></a>Video Projection

Represents the video projection mapping mode. The Content Console supports [Flat](terms.md#flat-video-projection) and [Spherical](terms.md#spherical-video-projection) modes.  

#### <a id="flat-video-projection"></a>Flat Video Projection

This mode supports Monoscopic 360° videos. This video type is typically filmed with a single camera and stitched together to form a single equirectangular video.

#### <a id="spherical-video-projection"></a>Spherical Video Projection

This video type is usually filmed using two or more cameras and supports the use of HMD devices. Characteristics include:

* Uses stereoscopic technique to render images so there is a slight offset between your left and right eye.
* This view creates and impression of depth a full 360 experience.

#### <a id="key-art"></a>Key Art

A still image file that is used to showcase your video.

* It typically uses a memorable image or icon that represents the essence of the story or topic presented in a video.
* You upload key art during the video publishing phase.
* Key Art displays on your video profile, property, and collection pages.
* Also referred to as a *Thumbnail*.

#### <a id="video-on-demand"></a>Video on Demand (VoD)

VoD stands for *Video on Demand*. This video format is saved in a MP4 file (required by the Content Console) and can be accessed any time by the user. VoD files can be directly uploaded to the Content Console, or can by specifying an external URL that represents where the video is stored (e.g., media server, content delivery network, etc.).

* This video format stores data (in a compressed form) that is required to depict a video signal. VoD files supported by the Content Console must be generated from 360 degree cameras.
* VoD files cannot be read in their initial "Raw" format and must be converted to the supported codec for video and audio file formats for mobile devices.
* When convert your VoD files to the required format, you will configure measurements for various categories of the video signal based on the file size you are converting the VoD file to.

See [Media Publishing Requirements](mediapublishrequirements.md) for more information on VoD conversion requirements for videos you would like to upload to the Content Console.

#### <a id="live-event"></a>Live Event

A Live event is composed of one or more live streams that are hosted on an external streaming Media Server, a Content Delivery Network (CDN), or streamed directly from a 360 camera.

* Cameras that support live 360 video stitching and streaming can utilize the live event option.

* You can add a live streams from a single 360 video camera or using an array of synchronized cameras (i.e., multiple 360 video cameras).

* Using your 360 video camera, you can create a customized RTSP request URL stream link for external media players, or let your camera generate a default URL.

* You can add live stream URLs from your Media Server or Content Delivery Network, or you can live stream directly from your 360 camera (depending on internet connectivity).

* You can add a URL to the Content Console for each additional 360 video camera and specify a camera label that uniquely identifies characteristics of the stream (e.g., angle, associated mobile devices, video format, etc.). See [Add Camera](addcamerastreams.md).

#### <a id="video-formats"></a>Video Formats

The distribution strategy for your video content is based on many factors. For example your video marketing plan may include requirements for:

* Achieving brand awareness
* The number of user engagements through social sharing you want to achieve
* The level of metrics (e.g., views, coverage in geographical region, etc.) you want to achieve

These goals will in turn require you to define where you want to post your video digital assets (e.g., on websites, mobile device applications, etc.). Each website or mobile device platform will have requirements for the *video format* and size they accept to guarantee optimum performance.

The *Video > Edit* page includes a *Video Formats* section that allows you to upload multiple formats of the same video for a single video profile. You can then label each video, designate the website or mobile device application (and platform) the video is associated with, and post the format-specific URL to these websites and applications.

See [Media Publishing Requirements](mediapublishrequirements.md) for a list of supported video formats. See go to [Add Video Formats](addvideoformats.md) for instruction on how to add a new video format.

#### <a id="http-live-streaming"></a>HLS (HTTP Live Streaming)

HTTP Live Streaming (HLS) is an HTTP-based streaming communications protocol. Videos encoded to HLS are created for different bandwidths and different resolutions. This provides a flexible means of delivering video on demand to content to a broad range of devices.

The Digital Domain HTML5 Player supports HTTP streaming, but HTTPS is preferred. HTTPS represents the newest standard because it is more secure. HTTPS is also required if you would like to include or request scripts, videos, images, iframes, etc.

The player supports the following HTTP Live Stream specification. The Live Media Playlist using HTTPS link outlines the preferred requirements.

* [HTTP Live Streaming](https://tools.ietf.org/html/draft-pantos-http-live-streaming-19)
* [Live Media Playlist Using HTTPS](https://tools.ietf.org/html/draft-pantos-http-live-streaming-19#section-8.2)

#### <a id="rtsp"></a>RTSP

Real Time Streaming Protocol (RTSP). A network control protocol used to control streaming media servers. The protocol is used for establishing and controlling media sessions between end points.

<!--#### H.264 Stream URL-->
#### <a id="bundle-id"></a>Bundle ID

Field used to specify the application Bundle ID (iOS) or Package Name (Android). This ID is a unique identifier for the application asset bundle that includes branding art and stylesheet information for the app (e.g. com.<appname>.<companyname>). The Bundle ID is automatically created when an app is initially defined. The same Bundle ID must be used for when app updates are issued.  

#### <a id="app-id"></a>Application ID (App ID)

The Application ID is automatically created by the Digital Domain Content Console at the time you define an application instance using **+ Application**. This id is used by the mobile device application to fetch the app's metadata (i.e., app assets uploaded to the Content Console).

For example, your mobile device app is live (i.e., published) and there is a requirement to update one of the application images. You upload the new asset to the app instance in the Content Console, the App ID gets passed to the mobile device API, and an API call is initiated that fetches the newly uploaded asset and updates the live application.   

#### <a id="application-uri-scheme"></a>Application URI Scheme

Represents the URI scheme used to open a mobile device application. To ensure a positive user experience, it's important to research your potential URI schemes to ensure that they are unique. You always want users of your app to be redirected to *your* application when they are deep linking, and not conflict with similar applications using a similar URI scheme. Digital Domain native apps will always have the same URI Scheme (im360://). Custom apps can assign unique URI Schemes.

#### <a id="store-url"></a>Store URL

Each application instance added to the Content Console requires that you specify a URL that represents the digital distribution platform (i.e., App Store) that will be used for your mobile app. The URL must launch the exact location of the platform-specific App Store where your app is published and can be downloaded. You receive your final App *Store URL* after your app completes the App Store review process. Some examples of App Store URLs for Digital Domain supported app platforms include:

* Google Play -  https://play.google.com/apps/<appname>
* iOS -  https://itunes.apple.com/us/<appname>)
* Gear VR - https://www.oculus.com/experiences/gear-vr/<appname>
* Oculus Rift - https://www.oculus.com/experiences/rift/<appname>
