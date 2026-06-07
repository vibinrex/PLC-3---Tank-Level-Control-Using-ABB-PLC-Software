# PLC-3---TANK-LEVEL-CONTROL-USING-ABB-PLC-Software

## Aim
To control the water level in a tank automatically using an ABB PLC by starting and stopping a pump based on level sensor signals.

## Apparatus Required
ABB PLC
ABB Automation Builder Software

## Theory
A tank level control system maintains the water level between predefined limits. Two level sensors are used:
Low Level Sensor (LSL): Detects minimum water level.
High Level Sensor (LSH): Detects maximum water level.
When the water level falls below the low-level sensor, the PLC starts the pump. When the water reaches the high-level sensor, the PLC stops the pump.

## I/O Assignment

<img width="468" height="113" alt="image" src="https://github.com/user-attachments/assets/ac56352b-f000-47b9-96d4-11ddd8cc8097" />


<img width="468" height="84" alt="image" src="https://github.com/user-attachments/assets/ba9502eb-ad48-4a96-a0bb-ef322aa55d14" />


## Logic
If Low Level Sensor is ON, Pump starts.
Pump remains ON through self-holding.
When High Level Sensor becomes ON, Pump stops.


## Procedure
Open ABB Automation Builder.
Create a new PLC project.
Configure PLC hardware and I/O addresses.
Develop the ladder logic program.
Compile the program and check for errors.
Download the program to the PLC.
Connect sensors and pump.
Run the PLC in online mode.
Observe the operation of the tank level control system.


## Observation
<img width="468" height="142" alt="image" src="https://github.com/user-attachments/assets/679c3df0-c884-4fcb-ab6f-5f07f14bc7fc" />







## Output


<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/efda790d-a4b6-433b-9408-59767838e3ed" />














## Result
The tank level was successfully controlled using the ABB PLC. The pump automatically starts when the water level falls below the minimum level and stops when the tank reaches the maximum level.

