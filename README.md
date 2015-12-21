# Open-ArdBir-NANO-
Repository for HW design file (PCB, schematic)  of ArdBir board based on arduino NANO version

Open Ardbir is an open source SW (up to release 2.8.3) to control and automate beer brewing process
The SW have been developed based on Arduino UNO board (Atmega328 MCU) with few surroundings HW component to drive and interface external element (PUMP, Heating element , LCD, push button etc.)

There are few open source HW board available supporting the SW either designed as  shield on top of Arduino Board or stand alone board (all in one board)

In the repository you can find my personal design of a board based on Arduino NANO V3 version with few additional features (not all supported by current SW version)
•	2 x DB18B20 temp probe
•	2 x 12v SSR/Relay out
•	2 x 12V power out (3A) 
•	Push button/LED/buzzer

The mapping of pinout is completely compatible with all other version (1 x DS18B20,SSR,PUM) while the second set of input is for future applications
The 12V power output can drive directly small pump (like solar project) and/or solenoid valve

The board has been designed in a very compact size to be mounted front panel
•	double side PCB
•	Trough Hole Component
•	No SMD

Two version of PCB are available depending on the LCD mounting

•	LCD solder side: the LCD is mounted on the copper side leaving the components accessible
•	LCD on component side : LCD is mounted on the same side of components 


In the repository you can find two folders, one for each version, containing PCB and schematic in eagle forma and BoM

Enjoy and feel free to modify/fork the project
