# Electropioneer Main Board 
This repo is dedicated to developing the new Main Board for the Electropioneer team
## Software
We are using KiCAD to develop the PCB
![3D image](https://github.com/Elektropioneer/MainBoardV2/blob/master/Pics/3d.png)
![PCB PDF](https://github.com/Elektropioneer/MainBoardV2/blob/master/PDF/mainboard_pcb.pdf)
![SCHEMATIC PDF](https://github.com/Elektropioneer/MainBoardV2/blob/master/PDF/mainboard.pdf)

## Protection from reverse current
We are using the simplest way to protect out circuits, a P-Channel MOSFET.
The MOSFET won't turn on when the voltage on the gate is above 0 (exact voltage defined in the datasheet)
![Protection](https://github.com/Elektropioneer/MainBoardV2/blob/master/Pics/protection_mosfet.jpg)
