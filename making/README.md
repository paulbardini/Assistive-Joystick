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

<img src=https://github.com/paulbardini/Assistive-Joystick/blob/master/img/Making/Image00004%20smaller.jpg>

This will allow the header to plug into the earth - pin13 - pin12 - pin11 of the Arduino. Keeping things neat and tidy.

<img src=https://github.com/paulbardini/Assistive-Joystick/blob/master/img/Making/Image00005%20smaller.jpg>

<h2> Step 3</h2>

<h2> Soldering the joystick.</h2>

The joystick I purchase had header pin pre-connected, this cause problem so I removed them and solder wires straight into the module.
There are 5 connections Earth and VCC (5 volts) X out Y out and the internal switch of the Joystick. 

<img src=https://github.com/paulbardini/Assistive-Joystick/blob/master/img/Making/Image00008%20smaller.jpg>

After soldering the header onto the joystick wires, I used a pair of pliers to remove the platic spacer. This allowed me to bend the header to 90 degrees. There is little room to move with this design, so need to make everyting a tight as possible. As seen in the image below.

<img src=https://github.com/paulbardini/Assistive-Joystick/blob/master/img/Making/Image00015%20smaller.jpg>

<h2> Step 4</h2>

<h2> Stuffing it all in</h2>

I did say it was tight, but it does fit. Find a handfull of screw to attach the joystick module to the bottom plate. Be careful, because of the laminating direction of the print, if you use too larger screw it can break/separate the print layer. You also need to pull the joystick module as flat as you can. Be patient - find the rigth screw.

<img src=https://github.com/paulbardini/Assistive-Joystick/blob/master/img/Making/Image00018%20smaller.jpg>

<h2> Step 5</h2>

<h2> Sticking it down</h2>

I can't say I am a fan of the hot glue gun - overrated in my opinion - but for this case, it works a treat.

Organise your wiring and get everything in the right place before you get glue rage.
I started with the middle button and worked my way round. 

<img src=https://github.com/paulbardini/Assistive-Joystick/blob/master/img/Making/Image00020%20smaller.jpg>
<img src=https://github.com/paulbardini/Assistive-Joystick/blob/master/img/Making/Image00021%20smaller.jpg>

A bit more glue to hold the wires in place

<img src=https://github.com/paulbardini/Assistive-Joystick/blob/master/img/Making/Image00022%20smaller.jpg>

Now stand back - tend to your burns from the glue gun - and see what you have created.

Behold:

<img src=https://github.com/paulbardini/Assistive-Joystick/blob/master/img/Making/Image00023%20smaller.jpg>

<h2> Step 6</h2>

<h2> Puting the lid on</h2>

I did have to shave the lip on the base so the top would sit properly. Once the unit is programmed and working I will hot glue a cable in possition and the lid closed. This is what I like about Hot Glue - the ability to get things apart again.

<img src=https://github.com/paulbardini/Assistive-Joystick/blob/master/img/Making/Image00025%20smaller.jpg>
