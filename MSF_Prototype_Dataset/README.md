# Metaverse Standards Forum Support Data
This is a subset of the data capture, selected to support prototype development in the Metaverse Standards Forum (MSF) Real/Virtual Integration Working Group. 
The data covers four successful rendezvous between the Ordnance Survey instrumented road vehicle (the "Street Drone" or the "car") and two people ("rider-3" and "rider 4") wearing chest-mounted 
GoPro 11 cameras.
The two people took the role of potential riders.

The four rendezvous were captured on 26 April, 2023. Participants were from the Ordnance Survey UK, Away Team Software, and OpenSitePlan. The car, the riders, a person with a Nokia 5 smartphone, and a Mavic Pro 2 drone flying above the surface 
made video, imagery, position, 
orientation, and image sensor sensor observations throughout the four rendezvous. 



## The MSF data

The data capture covered bith the static environment (the :stage:) as well as the moving entities (the "actors"). 

The actors included the OS Street Drone (1), flying drone (1), instrumented people (2) and non-participant bicyclists, walkers, runners, cars, and trucks. The drones and instrumented people have audio and 10-30 Hz video streams with per-frame IMU and other metadata.

The data is organized by whether it represents elements of the stage, or elements attached to the actors. 
Actor-sensed data is organised by actor ("platform"), "sensor", and data item (such as individual images) or data stream (such as video or navigation data).

## The Stage
We captured two independent reference RGB point clouds (the "reference point clouds") covering the full environment of the capture. One was derived from a late morning aerial survey on 25th April and the other at mid-afternoon of the same day. The nominal positional precision of these point clouds is 2 cm. The point clouds are registered via ground control points to a local LTP-ENU tangent plane coordinate system with an estimated accuracy of 50 cm. Each point cloud has about 140 million samples.

### Orthoimages

**+Image and description here+**

### Pointclouds

**+Image and description here+**

### 3D Models

**+Image and description here+**

### Survey Control points

**+Image and description here+**

## Actors

#### Static Cameras

**+Image and description here+**

### Litter

**+Image and description here+**

Away Team Software and Highways England provided a variety of road litter including rubbish, temporary road signs, road sign frames, sandbags, and traffic cones.

![StreetDrone vehicle with road litter](../SD_Signs2.jpg)

### Handheld Nokia-5

**+Image and description here+**

#### Camera-Images

Rider-4 held the Nokia 5 in addition to wearing the chect-mounted camera. No navigation sensor data was captured with the hadheld camera. The complete set of images in PNG or Jpeg format is available as a Zip archive:

| Platform.Sensor.Item | Type | Size | Length |
| :---- | :---- | :---- | :---- |
| [Handheld-Nokia-5.Camera-Images.20230426T134102.000_MSF_JPG.zip](https://content.hillyfieldsbubble.org/Data/Bubble/Actors/Handheld-Nokia-5/Handheld-Nokia-5.Camera-Images.20230426T134102.000_MSF_JPG.zip)  | JPG | 9.57 MB | 28 images |
| [Handheld-Nokia-5.Camera-Images.20230426T134102.000_MSF_PNG.zip](https://content.hillyfieldsbubble.org/Data/Bubble/Actors/Handheld-Nokia-5/Handheld-Nokia-5.Camera-Images.20230426T134102.000_MSF_PNG.zip)  | PNG | 44.05 MB | 28 images |

The image files also may be examined or downloaded as [individual files](./handheld_image_list.md).

#### Camera Video

#### Navigation-Sensors

The video frame rate is 29.97 fps.


### Mavic 2 Pro - Quadcopter

**+Image and description here+**

![Quadcopter MSF Subset map.](./quadcopter_map.png)

#### Camera Images

The images are a subset of the frames in the video capture, one frame every two seconds. The frames are identified by UTC time and are on the same time base as the video. 
Two formats - JPEG and PNG - are available. A Zip archive of all of the JPEG format images as well as a Zip archive of all of the PNG format images are available.

The frames are identified by UTC time and are on the same time base as the video. 
Two formats - JPEG and PNG - are available. A Zip archive of all of the JPEG format images, a Zip archive of all of the PNG format images. and the individual images files are available.

The complete set of images is available in Zip archives, one of PNG format images and one of Jpeg format images:

| Platform.Sensor.Item | Type | Size | Length |
| :---- | :---- | :---- | :---- |
| [Quadcopter.Camera-Images.20230426T134400.500_MSF_JPG.zip](https://content.hillyfieldsbubble.org/Data/Bubble/Actors/Quadcopter/Camera-Images/Quadcopter.Camera-Images.2023-04-26t134400.500_MSF_JPG.zip)  | JPG | 170.2 MB | 203 images |
| [Quadcopter.Camera-Images.20230426T134400.500_MSF_PNG.zip](https://content.hillyfieldsbubble.org/Data/Bubble/Actors/Quadcopter/Camera-Images/Quadcopter.Camera-Images.2023-04-26t134400.500_MSF_PNG.zip)  | JPG | 724.9 MB | 203 images |


The image files also may be examined or downloaded as [individual PNG or Jpeg files](./quadcopter_image_list.md).

#### Camera-Video


#### Navigation-Sensors


### Ordnance Survey Street Drone Front Mount


**+Image and description here+**

#### Camera Images

The images are a  subset of the capture, one frame every two seconds. The frames are identified by UTC time and are on the same time base as the video. 
Two formats - JPEG and PNG - are available. A Zip archive of all of the JPEG format images as well as a Zip archive of all of the PNG format images are available.

The frames are identified by UTC time and are on the same time base as the video. 
Two formats - JPEG and PNG - are available. A Zip archive of all of the JPEG format images, a Zip archive of all of the PNG format images. and the individual images files are available.

*The Zip archives:*

The image files also may be examined or downloaded as [individual PNG or Jpeg files](./streetdrone_front_image_list.md).

#### Camera video

The video frame rate is 4.86 fps.
#### Camera Targets

Objects in the classes "person", "car", "truck", "bicycle", and "motorcycle" were detected with a YOLO V8 CNN trained on the COCO-17 dataset. The class,onfidence, and centre-points are reported. 

### Ordnance Survey Street Drone Rear Mount

#### Camera Images

The images are a  subset of the capture, one frame every two seconds. The frames are identified by UTC time and are on the same time base as the video. 
Two formats - JPEG and PNG - are available. A Zip archive of all of the JPEG format images as well as a Zip archive of all of the PNG format images are available.



#### Camera Images

The images are a  subset of the capture, one frame every two seconds. The frames are identified by UTC time and are on the same time base as the video. 
Two formats - JPEG and PNG - are available. A Zip archive of all of the JPEG format images as well as a Zip archive of all of the PNG format images are available.

The frames are identified by UTC time and are on the same time base as the video. 
Two formats - JPEG and PNG - are available. A Zip archive of all of the JPEG format images, a Zip archive of all of the PNG format images. and the individual images files are available.

*The Zip archives:*

The image files also may be examined or downloaded as [individual PNG or Jpeg files](./streetdrone_rear_image_list.md).

#### Camera video

The video frame rate is 4.86 fps.
#### Camera Targets

Objects in the classes "person", "car", "truck", "bicycle", and "motorcycle" were detected with a YOLO V8 CNN trained on the COCO-17 dataset. The class,onfidence, and centre-points are reported. 

#### LiDAR 

#### Pointclouds

### Person - "Rider 3" Chest Mount

The frames are identified by UTC time and are on the same time base as the video. 
Two formats - JPEG and PNG - are available. A Zip archive of all of the JPEG format images, a Zip archive of all of the PNG format images. and the individual images files are available.

*The Zip archives:*

| Platform.Sensor.Item | Type | Size | Length |
| :---- | :---- | :---- | :---- |
| [Rider-3-Chest-Mount.Camera-Images.20230426_MSF_JPG.zip](https://content.hillyfieldsbubble.org/Data/Bubble/Actors/Rider-3-Chest-Mount/Camera-Images/Rider-3-Chest-Mount.Camera-Images.20230426_MSF_JPG.zip)  | JPG | 0.52 GB | 180 images |
| [Rider-3-Chest-Mount.Camera-Images.20230426_MSF_PNG.zip](https://content.hillyfieldsbubble.org/Data/Bubble/Actors/Rider-3-Chest-Mount/Camera-Images/Rider-3-Chest-Mount.Camera-Images.20230426_MSF_PNG.zip)  | PNG | 2.33 GB | 180 images |

*The individual image files:*


#### Camera images
The images are a  subset of the capture, one frame every two seconds. The frames are identified by UTC time and are on the same time base as the video. 
Two formats - JPEG and PNG - are available. A Zip archive of all of the JPEG format images as well as a Zip archive of all of the PNG format images are available.

The image files also may be examined or downloaded as [individual PNG or Jpeg files](./rider-3_image_list.md).

#### Camera Video

#### Camera Targets

Objects in the classes "person", "car", "truck", "bicycle", and "motorcycle" were detected with a YOLO V8 CNN trained on the COCO-17 dataset. The class, confidence, and pixel centre-points are reported. 

#### Camera Sensors

### Person - "Rider 4" Chest Mount

#### Camera images
The images are a  subset of the capture, one frame every two seconds. The frames are identified by UTC time and are on the same time base as the video. 
Two formats - JPEG and PNG - are available. A Zip archive of all of the JPEG format images, a Zip archive of all of the PNG format images. and the individual images files are available.

*The Zip archives:*


The image files also may be examined or downloaded as [individual PNG or Jpeg files](./rider-4_image_list.md).

#### Camera Video

The video frame rate is 29.97 fps.

#### Camera Targets

Objects in the classes "person", "car", "truck", "bicycle", and "motorcycle" were detected with a YOLO V8 CNN trained on the COCO-17 dataset. The class, confidence, and pixel centre-points of each detection are reported. 

#### Camera Sensors


