# StreetDrone Camera Capture ReadMe

As part of the Hillyfields capture we used a forward and rear-facing centrally mounted cameras.  These are Sekonix 2MP, 100 degree FoV SF3322 (with an Onsemi AR0231 image sensor) cameras.  The specification for these can be found in this directory.  Note that both the 100 and 60 degree FoV specs have been included as the StreetDrone has 6 other 60 degree FoV cameras, however just the 100 degree FoV cameras were used for this dataset.

The GMSL interface means that there is a high (up to 12 Gbps) throughput.  However, raw capture with multiple cameras resulted in inconsistent framerates, bottlenecked by writing to disk (SDD).  As a result, for runs 3 and 4 on 26/04/2023 we captured compressed video at 5fps.
