# projects
This repository contains all personal/class computer engineering projects

##########################################################################################################################
FPGA: TUG OF WAR - Digital Systems Design Course Project

Authors: Matthew Labrador, Mikaylo Santiago

This project will simulate the game — Tug of War — using the DE2-115 board as the score tracker, number
keypad for user input, and a VGA monitor for visual interface. The language used to simulate the project will be in
System Verilog as the device may have up to two users to interact with the number keypad to play. The system will
compare the number of inputs from each player to determine the change in each player’s position on the VGA display
within a given clock cycle. The system will consist of two major modules: player type initialization and game session.
The goal of this project was to gain a better understanding of System Verilog, VGA code, and code for external 
periphals - matrix numberpad.

##########################################################################################################################

Smart Parking System - Internet of Things Course Project

Author: Mikaylo Santiago

This project utilizes the Arduino Yun and Arduino MKR1000 along with LEDs and ultrasonic sensors to implement a smart parking
lot by using wireless connection to pass data from a local network to cloud database. The objective of this project is to make
a node equipped with LEDs and ultrasonic sensors - a presence detector - to set onto a parking spot to detect whether an object
is occupying the monitored lot or if the lot is vacant. Once the presence detector senses an object - or car - nearby, the sensor
readings are sent to the cloud through a coordinator node which collects all data from each sensor to one point and sends it to
the cloud by WiFi connection. Once the data is stored and analyzed in the cloud, the data analytics are visualized on a web-based
application for users to view what parking slots are available. The goal of this project was to create a prototype device that
monitors a parking spot's status (vacant/occupied) and can send the parking spot's status to a cloud database which sets up
a visual representation of the parking spot's status through a mobile application. Furthermore, the data sent from the local
network is communicated in real time. This project proposes a solution that potentially reduces traffic congestion in parking 
lost as well as reduce travel time when a user is seeking a vacant parking space, hence the user being able to see available 
parking spots ahead of time.

##########################################################################################################################
