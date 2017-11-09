# Electropioneer Main Board 
This repo is dedicated to developing the new Main Board for the Electropioneer team
## Software
We are using KiCAD to develop the PCB
![Image1](https://github.com/Elektropioneer/MainBoardV2/blob/master/Output/board.png)
![Image2](https://github.com/Elektropioneer/MainBoardV2/blob/master/Output/top_view.png)
![Image3](https://github.com/Elektropioneer/MainBoardV2/blob/master/Output/bottom_view.png)
![SCHEMATIC PDF](https://github.com/Elektropioneer/MainBoardV2/blob/master/Output/Mainboard.pdf)

## Protection from reverse current
We are using the simplest way to protect out circuits, a P-Channel MOSFET.
The MOSFET won't turn on when the voltage on the gate is above 0 (exact voltage defined in the datasheet)
