# Hitachi MCU Dumper
Dumper for Hitachi H8/300 family, HD6301Y0 and HD6301X0 microcontrollers.

This project aims to provide different PCBs, for the implementation of the internal ROM dumping system of different Hitachi MCUs, developed by Sean Riddle.

Original project by Sean Riddle: http://www.seanriddle.com/h8/300/

There you can find the firmware, explanations on how it works, etc.

PCBs designed by me so far:

- ROM Dumper circuit
- HAT for HD6301Y0 & HD6301X0 with SDIP-64 package
- HAT for HD6301Y0 & HD6301X0 with FP-64 package
- HAT for H8/300 with SDIP-64 package
- HAT for H8/300 with FP-64A package

If you need a different HAT, do not hesitate to contact me.

[b]Note:[/b] I have been asked how to use a 27C512. It is very simple. As pin 1 of the EPROM socket is tied HIGH, just program the binary code starting at 0x8000 instead of the default 0x0000.  There is no need to make any modifications to the main PCB.



![3D_rendering](https://github.com/berger1920/Hitachi_MCU_Dumper/blob/main/Hitachi_H8_and_HD6301_ROMdumper_3D.jpg)

![3D_rendering](https://github.com/berger1920/Hitachi_MCU_Dumper/blob/main/Hitachi_HD6301X0-Y0_SDIP-64_HAT_3D.jpg)

![3D_rendering](https://github.com/berger1920/Hitachi_MCU_Dumper/blob/main/Hitachi_H8_FP-64_HAT_3D.jpg)
