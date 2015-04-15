<h1> AtomCNC</h1>
<img src='http://atomsofttech.com/AtomWiki/images/thumb/c/cc/Layout.png/500px-Layout.png'>

<h1>Introduction</h1>

AtomCNC is a CNC Controller based on GRBL. It can control up to 4 axis in 2 different configurations. Either a XYZA type config where you have 4 separate axis or a XYYZ configurations where you have 4 axis but it behaves as if there are only 3 by cloning the Y axis onto a secondary Y2 stepper. This allows for doubling of the steppers on Y axis for a more stable solution in some CNC models.<br>
<br>
<BR><br>
<br>
<br>
<br>
<br>
<BR><br>
<br>
<br>
The AtomCNC is customizable and easy to use. It has a nice CLEAR easy to read silk screen, so there is no need to pick up a manual or open a PDF to wire this board up. The board uses 4x A4988 controllers from Pololu to control the stepper motors. The layout allows the controllers to be replaced with no soldering skills if a problem should arise. AtomCNC also includes a on board 10A 125v relay to switch on and off the spindle.<br>
<br>
<BR><br>
<br>
<br>
<br>
<br>
<BR><br>
<br>
<br>
Since the main MCU is a Atmega328 you can rest assured there will always be stock if needed to be replaced and it uses the Arduino Uno Bootloader. Which means there is no programmer needed for future firmware upgrades.<br>
<br>
<BR><br>
<br>
<br>
<br>
<br>
<BR><br>
<br>
<br>
Here are some features:<br>
<br>
<BR><br>
<br>
<br>
<br>
<br>
<BR><br>
<br>
<br>
1) Atmeg328 - Main controller (NO PROGRAMMER REQUIRED!)<br>
<br>
<BR><br>
<br>
<br>
2) 4x A4988 - Stepper Controllers (X,Y(Y2),Z,A)<br>
<br>
<BR><br>
<br>
<br>
3) 125v @10A relay for spindle control<br>
<br>
<BR><br>
<br>
<br>
4) CP2102 - USB to UART for Programming and Control via PC/Linux<br>
<br>
<BR><br>
<br>
<br>
5) XYZ Homing / Limits<br>
<br>
<BR><br>
<br>
<br>
6) 3 GPIO ports for custom attachments<br>
<br>
<BR><br>
<br>
<br>
7) Selectable at time of purchase a TYPE B or MINI B connector. (default is Type B)<br>
8) Sturdy Terminals to connect your steppers.<br>
<br>
<BR><br>
<br>
<br>
<br>
Be sure to check out the <a href='https://code.google.com/p/atomcnc/w/list'>Wiki</a>!