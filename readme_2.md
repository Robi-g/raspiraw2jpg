#############################################################################
Raspiraw2jpeg
A program to capture a series of jpeg images on (potentially) any MIPI / CSI2 
camera controlled by i2c.
Author: R. Gower - based on 6by9's raspiraw.
Proper documentation will be released in due time, because a lack of comments
was what annoyed me most about the original raspiraw.
#############################################################################

##########################
Things it does do:
##########################
* Send setup info over i2c to a sensor.
* Receive images over MIPI from a sensor.
* Converts these into lovely JPEG.
* Works with the same 3 sensors that raspiraw does (if you have an NDA for another 
  sensor, it's not too difficult to add your own).

##########################
Things it doesn't do:
##########################
Note - some of these are fixed, but yet to be copied over.
* Save to a user-settable location
* Give a preview and record (something to do with the MMAL splitter component).
* Allow setting of JPEG quality at runtime (compile time only atm).
* Make tea.


