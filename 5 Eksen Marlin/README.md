![boot512](https://user-images.githubusercontent.com/42382799/155085783-a728ebfd-b664-4e8a-ac36-37466c8ed0cd.png)


# 4 Axes Foam Cutter firmware forked from Marlin2ForPipetBot

To be able to use a 4 axes CNC Foam Cutter without the need of a attached computer.
The Status screen has been modifed by DerAndere1 to show the axes XYUV with a few minor tweaks by myself. Many thanks.
This is still in the testing phase with CNC Foam Cutter using an Arduino Mega 2560 and a RAMPS 1.4. 
Please use with caution until this has been completed.
More details here https://rckeith.co.uk/4-axis-cnc-foam-cutter-using-marlin-3d-printer-firmware/

[![4 Axes Foam Cutter firmware forked from Marlin2ForPipetBot](https://img.youtube.com/vi/ys1kgXrevF4/0.jpg)](https://www.youtube.com/watch?v=ys1kgXrevF4)


# MKS GEN L V2.1
If you use the MKS GEN L V2.1 board change line 99 in Configuration.h 

#define MOTHERBOARD BOARD_MKS_GEN_L_V21

Pin D42 can't be used on this board so pin D19 is used for the U-axis endstop
D19 is the Z-MAX pin which isn't used.  Thanks to Anthony Gilbert for testing this.

# Additional documentation can be found in the 
repository [DerAndere1/Marlin at https://github.com](https://github.com/DerAndere1/Marlin/tree/Marlin2ForPipetBot), the [Wiki](https://github.com/DerAndere1/Marlin/wiki)

# CNC Foam Cutter build
Please check my website for the build and electronics used in my 4 Axes CNC Foam cutter https://rckeith.co.uk


