# LiDAR Capture ReadMe

The LiDAR capture was done with a Hesai Pandar XT-32. The user [https://www.oxts.com/wp-content/uploads/2021/01/Hesai-PandarXT_User_Manual.pdf] (technical specification) gives an overview of configuration and performance.

Packets were captured in pcap format, and converted to pcapng with WireShark.  Wireshark can also be used to open these files, though this might be of limited use other than problem diagnosis.  The files were used with 3rd party software to generate a georeferenced point cloud, however, they can also be used with software such as LiDARView to generate SLAM-based point cloud maps.

