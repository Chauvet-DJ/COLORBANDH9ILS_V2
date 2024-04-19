# COLORBANDH9ILS_V2

### This firmware is for Version 2 of the COLORband H9 ILS. If you have Version 1 of this product, please contact Customer Service for further instructions on how to update your unit.
&nbsp;  

## Firmware Update Instructions
1. Download the zip file onto your computer and extract the folder.
2. Transfer the contents from the zip file onto a USB thumb drive.
3. Hold down the menu button then power on the fixture to put it into upload mode.
4. Insert the USB thumb drive into the USB port on the rear of your fixture. The COLORband H9 ILS will automatically find the firmware and apply it.
5. The fixture will reset itself automatically and display the new firmware version during start up.
6. The USB thumb drive can be removed after the fixture restarts.

### Special Notes
* Do not use a thumb drive greater than 32GB.
* The thumb drive must be formatted to FAT32.
* The downloaded firmware file must be placed in the root directory on the thumb drive (no folders).
* Do not disconnect from power source until the update process is complete.

&nbsp;  

[V4.03 - COLORband H9 ILS](https://github.com/Chauvet-DJ/COLORBANDH9ILS_V2/blob/1468cb2b396f03ee32cbcdc0aa9a359bc7908a8b/Firmware/V4.03_04-02-24.zip)
- Fixed the bug that causes fixtures to not work properly in master/slave mode when controlled using RF remote
  * When you have multiple lights linked together in master/slave mode and you’re controlling them with the RF remote, when you try to dim the lights, only the master unit would respond. The software fix allows all the units to respond to the RF remote.
