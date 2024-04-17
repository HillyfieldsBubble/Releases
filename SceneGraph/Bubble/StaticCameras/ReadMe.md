**Static Cameras**

Geotagged video recorded by smartphones mounted on static tripods at the roadside to simulate traffic cameras.

![Roadside smartphone on tripod](TripodCone.jpg)

Videos were captured using Away Team's TrkdCam app that natively records [WebVMT format](https://www.w3.org/TR/webvmt/). Raw files were then augmented with additional geotag data to track Ordnance Survey's StreetDrone Twizy vehicle and synchronised with Coordinated Universal Time (UTC) using the methods described in [OGC Testbed-19](https://www.ogc.org/initiatives/t-19/) D001 Engineering Report.

![Tracking vehicle from video](N5_Track_230425.jpg)

WebVMT content can be viewed in a web browser by loading video and VMT files into the [mobile demo webpage at webvmt.org](https://webvmt.org/demos/mobile).

All static camera video files can be downloaded by executing the [download_all_static_videos.sh](download_all_static_videos.sh) script.
