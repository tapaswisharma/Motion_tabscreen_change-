This project establishes wireless communication between two Arduino boards using NRF24L01 modules to transmit ultrasonic distance measurements from one Arduino to another. An ultrasonic sensor on the transmitting Arduino detects object proximity, and the distance information is wirelessly relayed to the receiving Arduino, potentially enabling applications in obstacle avoidance, robotics, or remote monitoring.

## MODELS

A) when only 1 Arduino is used :
when we use only 1 Arduino which is connected to the ultrasonic sensor whenever there is motion detected in the serial port it directly fetches the command which we saved via AutoHotkey and runs the command 
for this working model we need to use 
serial.py and transmitter.cpp programme

B) when 2 Arduino used :

this model uses both the transmitter and receiver programming with a javascript file(Node.js) 
working process is similar to the 1st model 

## working process

1. Connect the circuit as shown
2. Download AutoHotkey add the given command and save it with.ahk file
3. Upload the transmitter code in Arduino IDE connect it to the PC and upload it to the Transmitter ARDUINO (after uploading remove the PC connection)
4. Now open VS code and save the javascript file and python file (//use js file for single Arduino Model // use python file for double Arduino model)
5. Upload the receiver code in Arduino IDE connect it to the PC and upload the code into the Receiver Arduino (//keep the receiver arduino connected to the PC)
6. Now whenever motion is detected it will fetch the AutoHoteky command and change the screen tab
   
  


 ### //TRANSMITTER CIRCUIT :

<img src ="https://github.com/tapaswisharma/Motion_tabscreen_change-/assets/130048461/8ed56d79-8ccd-4eef-8839-3c3c766e5a30.type" width= "500" height="500">

### //RECEIVER CIRCUIT:
<img src ="https://github.com/tapaswisharma/Motion_tabscreen_change-/assets/130048461/34c05cd8-ebac-46cb-bcc6-ffd12f62f64c.type" width= "500" height="500">


## Hardware Components:


2x Arduino Uno or compatible boards (e.g., Nano, Mega)
2x NRF24L01+ wireless transceiver modules
1x HC-SR04 ultrasonic sensor (or compatible)
Breadboard and jumper wires
2x 9V batteries with battery connectors
(Optional) Resistors (10kΩ for NRF24L01 CE and CSN pins)



## Installation :
Install Libraries: Download and install the NRF24 library by maniac-bug into your Arduino IDE. Refer to the library's documentation for specific installation instructions.

Arduino IDE (https://www.arduino.cc/en/software)

NRF24 library (https://github.com/nRF24) by maniacbug (https://github.com/maniacbug)

AutoHotkey : https://www.autohotkey.com/





