Append the Contents of boards.txt to  '$(Arduino_Installation_Directory)/hardware/arduino/boards.txt'

Copy the 'mega16' Directory to '$(Arduino_Installation_Directory)/hardware/arduino/variants'

Install USBasp Driver for Adventduino
 
Restart the Arduino IDE 

Select Board from Tools Menu and Opt for 'Adventduino-Atmega16@16MHz'
 
 For Programming the Board, Switch ON the Sliding Switch named 'BOOT'
 RESET the Controller Once, and the Target is ready to be Programmed
 In the Arduino IDE Choose the Programmer from Tools Menu and opt for 'USBasp'
 
 Flash your Sketch either by using 'Upload' or 'Upload using Programmer' as both does the same.
  
  Once Flashed the Controller Resets on its own (done in Bootloader Firmware), for further Programming a simple Manual reset using Push Button is enough Provided the BOOT Switch is ON 
  ( if not Slide the Switch towards ON and Press RESET, as the Controller is ready to be Programmed)