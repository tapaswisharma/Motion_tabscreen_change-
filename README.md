This project establishes wireless communication between two Arduino boards using NRF24L01 modules to transmit ultrasonic distance measurements from one Arduino to another. An ultrasonic sensor on the transmitting Arduino detects object proximity, and the distance information is wirelessly relayed to the receiving Arduino, potentially enabling applications in obstacle avoidance, robotics, or remote monitoring.

## Hardware Components:


2x Arduino Uno or compatible boards (e.g., Nano, Mega)
2x NRF24L01+ wireless transceiver modules
1x HC-SR04 ultrasonic sensor (or compatible)
Breadboard and jumper wires
2x 9V batteries with battery connectors
(Optional) Resistors (10kΩ for NRF24L01 CE and CSN pins)

 ### //TRANSMITTER CIRCUIT :

![transmitter png](https://github.com/tapaswisharma/Motion_tabscreen_change-/assets/130048461/8ed56d79-8ccd-4eef-8839-3c3c766e5a30)

### //RECEIVER CIRCUIT:
![receiver png](https://github.com/tapaswisharma/Motion_tabscreen_change-/assets/130048461/34c05cd8-ebac-46cb-bcc6-ffd12f62f64c)






Install Libraries: Download and install the NRF24 library by maniac-bug into your Arduino IDE. Refer to the library's documentation for specific installation instructions.
Arduino IDE (https://www.arduino.cc/en/software)
NRF24 library (https://github.com/nRF24) by maniacbug (https://github.com/maniacbug)
AutoHotkey : https://www.autohotkey.com/



