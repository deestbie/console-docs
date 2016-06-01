# Technical Specifications

## Video  

The following **MPEG-4 Part 14 (MP4)** video types with Advanced Audio Coding (AAC) are supported:

### Format HD

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

### Format 2K
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

### Format 4K
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

## Audio  

| Category        | Format                                |
|:----------------|:--------------------------------------|
| Encoding        | MPEG-4 AAC                            |
| Channels        | Stereo                                |
| Sample Rate     | 48000 HZ                              |
| Bitrate         | 127 Kbps (kilobits per second)        |
