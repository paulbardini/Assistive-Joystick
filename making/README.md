Hardware

<h1> THIS IS AN ONGOING PROJECT AND I AM ASKING FOR HELP TO FURTHER THIS TECHNOLOGY.</h1>
To Create the Joystick you will require the following materials.

Materials

- Arduino Leonardo - requires the mouse emulator
  - https://www.arduino.cc/en/main/arduinoBoardLeonardo
- Joystick
- 3 tactile push buttons
- hook up cable
- Male Headers

<img src=https://github.com/paulbardini/Assistive-Joystick/blob/master/img/Making/Image00001%20smaller.jpg>

Tools

- A 3D Printer - or someone to print this for you 
  - Link to STL Files - https://github.com/paulbardini/Assistive-Joystick/tree/master/CAD%20files
  - Link To Thingiverse - http://www.thingiverse.com/thing:1104178/#comment-1287946
  - On-Shape CAD link - https://cad.onshape.com/documents/931052d5d0573c68088a0b20/w/b2adfe2d1f8098bca9e43ab1/e/50dc9f8685308ad67deea490
  
- soldering iron + solder
- wire cutters
- Hot glue gun
- various screws
- screw drivers

<h2> 3D Printing</h2>
You can download the stl file from this link.
https://github.com/paulbardini/Assistive-Joystick/tree/master/CAD%20files

There are two main part to print for the body of the Joystick. I recommend you print these separatley, they take time to print and if it fails then better to loose 1 part and minimal filament.
Both parts will need support, the main body needs a lot of support as most of the body is an overhang. I have done this with an UP Box and the supoort was briliant, much better than my original print as seen on Thingiverse.
I have also printed this in PLA and ABS. Concideration when choosing filament; the mechanical flex in the part is what make the button function.

<h2> Building the electronics</h2>

The joystick uses a Arduino Leonardo - this arduino allows for an intergrated USB HID - in other words it acts like a mouse (or keyboard) 
Attached is 3 tactile buttons and 1 electronic joystick modules. As seen in the picture above.

<h2> Step 1</h2>

Solder wire onto the Tactile buttons and tie one side together - this will be the button earth/common connection.
<img src=https://github.com/paulbardini/Assistive-Joystick/blob/master/img/Making/Image00002%20smaller.jpg>

<h2> Step 2</h2>
Solder all the button wire to a header in order - Common - Button 1 - Button 2 - Button 3.
this will allow the header to plug into the earth - pin13 - pin12 - pin11 of the Arduino. Keeping things neat and tidy.
<img src=https://github.com/paulbardini/Assistive-Joystick/blob/master/img/Making/Image00004%20smaller.jpg>

