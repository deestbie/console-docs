# Introduction

This topic includes topics on view, update, and maintenance activities that can be performed on live event media profiles.

### How do I view a live event profile?<a id="view-live-event-profile"></a>

1. Go to *Organization Name > Property > Collection*.
2. Select a live event (Type: HLS). The *Stream Details* page displays.
3. The

### What activities can I perform on the live event profile page?<a id="live-event-activities"></a>

The following table lists information that is displayed on the Stream Details page. Each action:

* Indicates whether the activity is view/read-only on the page.
* Indicates if an available action exists that can be executed directly on the page.
* Indicates if an activity that is view only has an associated action (e.g., edit, update, etc.).

| Name             | Activity    | Associated Actions |
|:-----------------|:-------------------------------------|:-------------------------------------|
| Property Name      | View / Read-Only   | [Update Property](..\venom\manageproperty.md#update-property)           |
| Key Art   | Update   |  [Upload / Refresh Key Art](manageliveevent.md#refresh-key-art-live-event)         |
| Collection Name   | View / Read-Only   |  [Update Collection](..\venom\managecollection.md#update-collection)        |
| Visibility  | View / Read-Only     |  [Update Visibility Settings](manageliveevent.md#update-visibility-live-event)         |
| Pre Stream  | View / Read-Only     |  [Update Live Event Metadata](manageliveevent.md#update-metadata-live-event)         |
| Post Stream  | View / Read-Only     |  [Update Live Event Metadata](manageliveevent.md#update-metadata-live-event)           |
| Time Until Start  | View / Read-Only     | [Update Stream Start Time / Duration ](manageliveevent.md#update-stream-start-duration) |
| Views  | View / Read-Only     |  [Monitoring](..\venom\mediausageanalytics.md)         |
| Play Video  | Action   |   [Play Live Stream](manageliveevent.md#play-live-stream)  |
| Copy Embed Code  | Action   |  [Copy Embed Code](manageliveevent.md#embed-code-live-event)        |
| Start Time   | Update   |  [Update Steam Start Time](manageliveevent.md#update-stream-start-duration) |
| End Time  | Update   | Update Steam Start Time](manageliveevent.md#update-stream-start-duration)       |
| Stream Status  | Read-Only   | [Update Live Event Status ](manageliveevent.md#update-live-event-status)          |
| Origin URL  | Update   | [Update Main Camera ](manageliveevent.md#update-main-camera)       |
| Meta URL  | Update   | [Update Stream URLs ](manageliveevent.md#update-stream-urls)    |
| Return URL  | Update   |  [Update Stream URLs ](manageliveevent.md#update-stream-urls)        |
| Share URL  | Update   |  [Update Stream URLs ](manageliveevent.md#update-stream-urls)        |
| View Cameras  | View   | [View Camera Instances](..\venom\addcamerastreams.md#view-camera-instances)   |

### How do update the *main* camera on a live event media profile?<a id="update-main-camera"></a>

For live events, you add a *main* camera when you create the initial media profile. Here's some background on how the process works:

* The *main* camera always retains a display order of zero (0).
* To update the *main* camera, you must change the Origin URL on the live event *Edit* page.
* You can add additional cameras that represent different views or angles using the **+ Camera** option on the live event *Edit* page.
* Additional cameras can be updated on the *Stream Details > Cameras* section by selecting the camera display name.
* You can change the sequence order of additional cameras.
* Each additional camera displays as a selectable button on the HTML5 player where your live event is posted (i.e., on a mobile device app, or embedded on a website or social media network).
* The *main* camera will always display as the first camera (far left) on the HTML5 player.

**To update a main live event camera:**

1. Go to *Organization Name > Property > Collection*.
2. Select a live stream (i.e., HLS). The *Stream Details* page displays.
3. Select the *Edit* tab.
4. Change the *Status* to **Stopped**.
5. In the *Cameras* section, update the "Origin URL" and **Save**.
6. Go back to the *Edit* tab and select **Check Stream** to verify that the updated URL works properly.
7. If the live stream runs successfully, change the *Status* to **Ready**.
8. If your *main* camera is embedded on a website or social media network, go to *Stream Details*, **Copy Embed Code** for this camera and repost to the appropriate locations.
9. If your *main* camera is on a mobile device app only, the URL is automatically updated after you **Save** the live event media profile.

### How do I obtain embed code for live event?<a id="embed-code-live-event"></a>

The *Stream Details* pages include a **Copy Embed Code** option that allows you to live event cameras on external websites and social media sites. Example embed code looks similar to the following:

![Embed Code Example](images\embed_code_example_live_event.jpg "Embed Code Example - Live Event")

**To copy embed code:**

1. Go to *Organization Name > Property > Collection*.
2. Select a live event (HLS). The *Stream Details* page displays.
3. Select **Copy Embed Code**. The Embed Code pop-up displays.
4. Select and copy the iframe code.
5. Integrate the code into your website or social media network.

### How do I test my live stream?<a id="test-live-stream"></a>

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

### How do I play a live stream?<a id="play-live-stream"></a>

1. Go to *Organization Name > Property > Collection*.
2. Select a video or live stream. The *Stream Details* page displays.
3. Select **Play**.
4. Play speed is based on your wifi connection and local bandwidth. If the live stream is not available a message "The requested program is unavailable" message displays. This means that the live stream event is over (based on the designated start / stop time).

### How do I upload or refresh key art?<a id="refresh-key-art-live-event"></a>

1. Go to *Organization Name > Property > Collection*.
2. Select a video or live stream. The *Stream Details* page displays.
3. Select the *Edit* tab.
4. Select **Upload Key Art**.
5. Select a file to upload based on the image requirements, then **Close**.
6. Select **Save** to upload the key art and save it to your live event media profile.

### How do I change the property or collection of a live event media profile?<a id="change-property-collection-live-event"></a>

1. Go to *Organization Name > Property > Collection*.
2. Select a video or live stream. The *Stream Details* page displays.
3. Select the *Edit* tab.
4. From the **Property** drop-down, select a new property to assign to the current live event.
5. From the **Collection** drop-down, select a new property to assign to the current live event.
6. After completing your selections, **Save**. The live event will be added and regrouped into the new property and/or collection.

### How do I update the visibility settings of a live event media profile?<a id="update-visibility-live-event"></a>

A variety of scenarios may require you to change your visibility settings. For example:

* Your live event media profile configuration is complete and you are now ready to go live and publish it (i.e., set to Public).
* There is a technical issue with your live event media profile and you want to temporarily take it offline (i.e., set it to Private or Internal).
* The established run time of your live event media profile has completed and you want to permanently take it offline (i.e., set it to Private or Internal)

**To update visibility settings:**

1. Go to *Organization Name > Property > Collection*.
2. Select a video or live stream. The *Stream Details* page displays.
3. Select the *Edit* tab.
4. In *Visibility*, select Private, Internal, or Public.
6. After completing your selections, **Save**. The visibility of your live event be updated. Live events that are set to Internal or Private will be removed from any collections exposed in your applications. Embedded URL will present the live event as no longer available.

### How do I enable or disable video sharing?<a id="enable-disable-video-sharing"></a>

Based on your video distribution requirements, you can enable or disable the ability of a user to share a video on a social media site. The ability to offer videos to share is based on your specific video distribution requirements.

**To enable/disable video sharing option:**

1. Go to *Organization Name > Property > Collection*.
2. Select a video or live stream. The *Video Details* or *Stream Details* page displays.
3. Select the *Edit* tab.
4. In *Allow Downloads*, select Yes or No.
6. After completing your selection, **Save**.
7. A list of sharable social networks will be visible in mobile device applications or websites where a video is embedded to allow downloading, and the Content Console *Video Details* page will indicate **Sharing Allowed** or **Sharing Not Allowed**.

### How do I add a language to a live event media profile?<a id="add-language-live-event"></a>

The following topics illustrate how to add a language to a live event media profile:

* [Add Language - Live Event](addlanguage.md#add-language-stream)

### How do I delete a language in a live event media profile?<a id="delete-language-live-event"></a>
The following topic illustrate how to delete a language in a live event media profile:

* [Delete Language](addlanguage.md#delete-language)

### How do I update metadata for a live event profile?<a id="update-metadata-live-event"></a>

1. Go to *Organization Name > Property > Collection*.
2. Select a live event. The *Stream Details* page displays.
3. Select the *Edit* tab.
4. Update Stream Title, Pre Stream Message, Post Stream Message, Description, and Tags.
4. Perform an update and **Save**. The *Stream Details* page displays and presents your updated content.

### How do I update the status of a live event?<a id="update-live-event-status"></a>

Each live event media profile includes a *Status* section that is used to manage the workflow cycle of your live event. The status applies to *All* cameras that are defined in the media profile as a group (i.e., main and additional cameras). The following status states are supported:

*Note: All Status settings must be set manually in the current Console Console release.*

| Live Event Status          | Description   |
|:-----------------|:-------------------------------------|
| Stopped      | When you initially create a live event media profile, the default status is *Stopped*.      |
| Ready    | All setup, configuration, and testing work is complete on the live event and it is ready to go live. If you set the live event to **Ready**, you would typically set visibility to **Public**. |
| Streaming   | Your live event has reached its designated start time and is streaming live.     |
| Error   | Your live event is presenting an  "Unavailable" error. This occurs when the live event has ended (based on the defined *Duration*), the live event URL in the Content Delivery Network, Media Server, or 360 Camera no longer exists or there is a service interruption.    |

**To change a live event status:**

1. Go to *Organization Name > Property > Collection*.
2. Select a live event. The *Stream Details* page displays.
3. Select the *Edit* tab.
4. In **Status** section, select the status (Stopped, Ready, Streaming, or Error) for the live event based on the definitions above, then **Save**.  the down arrow to load the calendar popup, then set the date and time the live event will broadcast.
5. You can then view the status of one or more live events on the *Collections Summary*.

## How do I update Stream Return, Stream Share, and Stream Meta URLs in a live event?<a id="update-stream-urls"></a>

After you create a live event profile, you can add or update the following optional stream types for your live event:

| Stream URL Type          | Description               |
|:-------------------|:-------------------------------------|
| Stream Return URL    | The redirection URL the viewer will return to after the live-stream concludes. |
| Stream Share URL    | The URL that will upload when a video is shared on an external site.  |
| Stream Meta URL    | Typically includes a file uploaded with modified instructions on how to render particular videos in the player.   |

**To update stream URLs:**

1. Go to *Organization Name > Property > Collection*.
2. Select a live event. The *Stream Details* page displays.
3. Select the *Edit* tab.
2. Specify each URL type as needed.


### How do I change the stream start time and duration for a live event?<a id="update-stream-start-duration"></a>

1. Go to *Organization Name > Property > Collection*.
2. Select a live event. The *Stream Details* page displays.
3. Select the *Edit* tab.
4. In **Stream Start Time** select the down arrow to load the calendar popup, then set the date and time the live event will broadcast.
5. In **Duration (In Minutes)** specify a number that indicates estimated maximum live event play time in minutes (e.g., 60 for 60 minutes).
6. Perform an update and **Save**. The *Stream Details* page displays and presents your updated content.

### How do I change the blindspot setting of a live event media profile?<a id="change-blindspot-live-event"></a>

Adding blindspot artwork to your live event in generally performed before you create a live event media profile. You may initially configure the position of the artwork for a specific camera position, and the blind spot position could change if for some reason your camera position changes. To update the blindspot position of a live event camera:

**To update blindspot for main live event camera:**

1. Go to *Organization Name > Property > Collection*.
2. Select a video or live stream. The *Stream Details* page displays.
3. Select the *Edit* tab.
4. In *Blindspot* select None, Top, or Bottom.
4. To commit your entries, **Save**.

**To update blindspot for additional live event camera:**

1. Go to *Organization Name > Property > Collection*.
2. Select a video or live stream. The *Stream Details* page displays.
3. In the *Cameras* section, select the (hyperlinked) name of a live event camera.
4. On the *Update Stream Camera* pop-up, select Top, Bottom, or None from the *Blindspot* dropdown.
4. To commit your entries, **Update**.

| If Projection =             | Setting   |
|:-----------------|:-------------------------------------|
| Flat      | Blind Spot = None            |
| Spherical and video includes a Blind Spot   | Blind Spot = Top or Bottom |
| Spherical and video does not include a Blind Spot   | Blind Spot = None     |

### How do I save a live event media profile?<a id="save-live-event-media-profile"></a>

Updates to a live event media profile are performed on the *Edit* page. After you perform an update you use **Save** to commit your changes.

**To save a live event media profile:**

1. Go to *Organization Name > Property > Collection*.
2. Select a video or live stream. The *Stream Details* page displays.
3. Select the *Edit* tab.
4. Perform an update and **Save**. The *Stream Details* page displays and presents your updated content.
