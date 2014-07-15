infragram-ps
============

Contents of the SD card to be used on the Infragram Point and Shoot - an open hardware multispectral camera developed by Public Lab: http://infragram.org

****

##Instructions

(copied from http://publiclab.org/wiki/infragram-point-shoot on July 15, 2014)

The Infragram Point & Shoot is a handheld, battery powered mini camera (a modified Mobius Action Cam) for doing plant analysis. For any information, support, or troubleshooting not covered here, please look to [this epic thread about the Mobius Action Cam at RCGroups.com](http://www.rcgroups.com/forums/showthread.php?t=1904559)

An official manual for the Mobius Action Cam can also be found here: http://mobius-actioncam.com/softwareuser-guide/

###Installing config file

If your camera did not ship with a config file or you are using a new SD card, follow these steps to get your Infragram Point & Shoot to take properly white-balanced images, necessary for post processing at [Infragram.org](http://infragram.org). This is also relevant for anyone who has a Mobius Action Cam and wants to script or customize its settings. 
R
Note: The WB setting in the config file should be "7" but occasionally we've found that some cameras require an "8" -- if you have trouble, please [post to the plots-infrared list](/lists).

1. turn the camera on with the "Power" button *while* also pressing "Mode" until the red light blinks 3 times (5-6 secons) to generate a config
2. plug it in via USB and wait for the disk to appear
3. replace the generated config file with this one in the home directory: 
<a href="http://i.publiclab.org/system/images/photos/000/005/225/original/SYSCFG.TXT"><i class="icon icon-file"></i> SYSCFG.TXT</a>


4. repeat turn on pressing mode.

###Updating firmware

v1.20 firmware: 

<a href="http://i.publiclab.org/system/images/photos/000/005/103/original/Mobius_FW_V1.20.zip"><i class="icon icon-file"></i> Mobius_FW_V1.20.zip</a>

Excerpted from [RCGroups.com](http://www.rcgroups.com/forums/showthread.php?t=1904559):

    1. Download the firmware .zip archive file and un-zip it. Copy the actual firmware file (always named FWTLCAM.BIN as noted above) from it's identifying folder into the camera's flash card root directory (the one that opens when the camera connects as a removable drive). This can be done with the card in the camera connected to the computer as a Removable Drive, or externally in a card reader. But do NOT rename the file. If you do, the camera will not install it!
    2. Disconnect the camera and turn it off.
    3. Insert the flash card containing the new firmware file into the camera (if not already in the camera).
    4. Press the Power button until the BLUE LED turns on and begins to flash. RELEASE THE POWER BUTTON AS SOON AS LED FLASHING BEGINS! If you keep pressing it longer, you may turn off the camera before the update process is done. DO NOT PRESS ANY BUTTONS WHILE THE INSTALLATION IS IN PROGRESS (about 20 sec. to complete)
    5. To confirm the firmware is being loaded into the camera, the BLUE LED will continue to blink during the upload process.
    6. When the FW installation is complete, the BLUE LED will turn off for about 2 sec. and the YELLOW LED will then turn on solid, indicating the FW file is has been automatically deleted from the memory card.
    7. You're done! The camera will be in the normal start-up standby mode ready for use.`
