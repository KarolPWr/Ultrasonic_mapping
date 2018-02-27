# Ultrasonic mapping with Arduino + HC-SR04 controlled by LabView
Mapping surroundings using ultrasonic HC-SR04 sensor. 
This project was compiled for LV 2012. For it to work, you must install Arduino LIFA (from vi package manager). 
Also serial drivers for labview might be needed.
As of now servo is rotating in 180 degrees range. It wasn't tested for 360, but it should also work. 

Steps towards success:
- Hook up everything according to the schematic
- Clone this repository
- Install Labview and all necessary dependencies (LIFA, serial drivers, etc.)
- Upload modified LIFA firmware to Arduino board (in LIFA_Base folder)
- Run project (main.vi)

Big thanks to Nathan_B who was responsible for creating LIFA lib for ultrasonic sensor. 
