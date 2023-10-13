# GPS and IMU Output

This directory contains data from the Inertial Navigation System (INS) that recorded during each of the runs. The INS is an [OxTS xNAV650](https://www.oxts.com/wp-content/uploads/2021/07/xNAV650-manual-210427-210730.pdf) and it can output x, y, z, roll, pitch and yaw.  The x, y and z are from a dual GPS antenna setup, and utilising RTK corrections from NTRIP we can get static accuracy of <1cm in x and y.

The data is presented at intervals of 10ms.  GPS status is included and is as follows:

|Code|Meaning|Typical Accuracy|
|----|-------|----------------|
|RTK Integer(6)|Full RTK Integer solution used.|<2cm|
|SPS (3)|Standard GPS positioning with no input from INS.|2-10 metres|
|gxSPS (21)|RTK solution lost, computed by combining raw pseudo-range measurements.|30cm - 5 metres.|

