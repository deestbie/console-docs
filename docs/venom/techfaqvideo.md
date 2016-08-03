# Technical FAQ (Video)

### How long does it take to configure a single video profile?

If you have all the digital assets available and complete the prerequisite steps defined in [Media Publishing Requirements](mediapublishrequirements.md), the overall process will take approximately 5-10 minutes plus downloading and post processing time. Add additional time for:

* Localizations
* Testing
* Adding additional live stream cameras

## Can I download multiple videos at one time?

The current upload process is one step in the overall video profile creation process. Batch uploading of videos is currently not supported.  

### What is the maximum size video I can upload?

For optimum performance and upload time, the maximum recommended video play time should be no longer *20 to 30 minutes*. You can estimate the video play time (HH:MM:SS) by entering the file size into a Video Bitrate Calculator.  
### How do I estimate how long it will take for a video to download?

You can estimate how long it will take to download a video file using a Video Download File Size Estimator.

* The download time depends on the Internet bandwidth (which should be reliable), and the actual video file size.
* Perform a speed test to calculate your current internet bandwidth, then enter this figure plus the video size into the calculator.
* You can perform an Internet search to find a Video Download File Size Estimator.  

Meridian Outpost has an easy to use calculator:

* [Sample Download Estimator](http://www.meridianoutpost.com/resources/etools/calculators/calculator-file-download-time.php "Download Estimator")

##### Where are my digital assets stored?

In case of an outage, Content Console digital assets and the associated network infrastructure are stored on multiple offsite disparate locations to ensure continuity of service.

### What is the best approach for uploading large videos?

The Content Console upload process is fault tolerant. This means that large files can be uploaded and the process will seamlessly continue if a network connection is lost.

Officially, there is no size/play time limit for video uploads, but the recommended maximum size is 20-30 minutes.

Note: Use a Video Bitrate Calculator to estimate video play time, and a Video Download File Size Estimator to estimate video download time.

### What type of video player is used to play videos or live streams I post using the Content Console?

Supported iOS, Android, and GearVR apps use our HTML5 Video Player. The HTML5 player provides

* Full support for mobile devices    
* Does not require plugins
* Supports popular browsers including Safari, Opera, Chrome, Internet Explorer, and Firefox.
* Integrates easily when videos are embedded on websites or shared from app.

<!--###### How do I embed network camera video on a website?-->

### How do I embed a VoD, External URL, or Live Event on a website?

The video profile *Details* page includes an HTML5 player and **Embed Link** that you can use to post VoDs, External URLs, or Live Events to an external site.

### Can I publish live stream URLs from a Media Server or Content Distribution Network into the Content Console?

Yes, refer to the [URL Live Stream](publishliveevent.md) for information on how to publish a live stream.

Also see [Media Publishing Options](mediapublishingoptions.md) for information about publishing tools.

<!--### How do I set up a live stream media server?

### How do I find out what RTSP string my 360 video camera uses?

### How do I ensure my live stream can be accessed externally?-->

* Your live stream URL will most likely reside on a secure Media Server or Content Delivery Network.
* Set default port of router to allow media server to be accessed externally. The default port is usually 5119.
* Set firewall to allow users to access the media server.

### How do I fill a 360 live stream blind spot using an app asset?

The App Asset functionality does not support filling a blind spot with a graphic image. That process must be performed in post production before uploading your assets. You can, however, indicate the location of the blind spot (None, Top, or Bottom).
