This project establishes wireless communication between two Arduino boards using NRF24L01 modules to transmit ultrasonic distance measurements from one Arduino to another. An ultrasonic sensor on the transmitting Arduino detects object proximity, and the distance information is wirelessly relayed to the receiving Arduino, potentially enabling applications in obstacle avoidance, robotics, or remote monitoring.

Hardware Components:

2x Arduino Uno or compatible boards (e.g., Nano, Mega)
2x NRF24L01+ wireless transceiver modules
1x HC-SR04 ultrasonic sensor (or compatible)
Breadboard and jumper wires
2x 9V batteries with battery connectors
(Optional) Resistors (10kΩ for NRF24L01 CE and CSN pins)

Project Setup:

Install Libraries: Download and install the NRF24 library by maniacbug into your Arduino IDE. Refer to the library's documentation for specific installation instructions.


Code Structure:

The project will consist of two Arduino sketches:

Transmitter (sends ultrasonic distance):

Initializes NRF24L01 module for transmission.
Reads ultrasonic distance using the HC-SR04 sensor.
Transmits the distance data through the NRF24L01 module to the receiver.
Receiver (displays ultrasonic distance):

Initializes NRF24L01 module for reception.
Receives distance data from the transmitter.
Optionally displays the received distance on the serial monitor or via other means (e.g., LEDs, LCD).
