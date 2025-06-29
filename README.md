# CD321x VDM Support

Extension of the tipd kernel module for VDM functionality on M chipset Macs. Allows for rebooting and enabling UART on supported target Mac devices (and some iPads/iPhones).

## Currently working:
	* Target reboot
	* Unlocking CD321x with key derived from device tree
 	* Verified sending generic VDMs to target (DFU Mode, SWD, etc)
  	* Reading VDM message replies at 0x4d i2c register (latter not in this repo)
  

## TODO:
	* Need access to another M1 macbook to fully test serial mode



 


