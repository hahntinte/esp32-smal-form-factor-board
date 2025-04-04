# esp32-small-form-factor-board
small form factor board for use in smart devices, fully buildable with a small CNC mill.
Originally, I created it for a smart watch with an st7789 display. 

![image](https://github.com/user-attachments/assets/1ed532c3-4b88-4be0-b009-ced4209f38e3)

Tips for making the board at home:
-the mp1700 voltage regulator is soldered sideways on the board, and its capicators are soldered directly to it (I just placed them to the other side of the boardwit cables going around the board, for a smaller formfactor)
-To program the board, you need an external programmer. I would just use a helping hand with jumper cables in contact with the TX Rx pads on the board. You could also solder pins to the board and connect jumper cables.
-To put the board into programming mode, just short the gpio 0 and en pads that look like they are for a diode. (Please don't install diodes on the pads.)
The battery management system is an off-the-shelf Tp 4056 module that I just glued to the backside of the board and connected wires directly to the MP1700.
-(If you mill it yourself) you can use wires wrapped around the board instead of the vias. It's easier to manufacture it this way.
