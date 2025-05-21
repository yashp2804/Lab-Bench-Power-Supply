# Lab-Bench-Power-Supply

## What is it?
A lab bench power supply that has both a variable and constant voltage output. The variable output is between 24 volts to 1 volts. There are three different fixed voltage outputs at 3.3 volts, 5 volts, and 12 volts. 

![Image](https://github.com/user-attachments/assets/44e12e32-c17f-4802-8624-00b559aad972)

## Table of Contents

- [Chassis](#chassis)
- [Circuit Diagram](#circuit-diagram)
- [Bill of Material](#bill-of-material)

## Chassis

Part Labels 
![Image](https://github.com/user-attachments/assets/2ab2d942-4c63-4bbf-a29e-2c8f60b880a3) 

Fully Assemble 
![Image](https://github.com/user-attachments/assets/76dd0ce3-775c-4afb-b1f3-6f0e68f42456)

## Circuit Diagram

Schematic
![Image](https://github.com/user-attachments/assets/9b475e80-6cff-46f1-94d9-532394ece95e)

Circuit wiring
![Image](https://github.com/user-attachments/assets/a1667548-c95d-4786-8034-9a9232be4986)

## Bill of Material

| Component                               | # of Components  | Description                                                          |
|-----------------------------------------|--------------|--------------------------------------------------------------------------|
| Transformer                             | 1            | Used to convert 120 AC to 24 AC voltage                                  |
| Full Bridge Rectifier                   | 1            | Used to make the 24 AC into a positive single                            |
| 3300uF 80V Capacitor                    | 1            | Need a large capcacitor to make the 24 AC single into a fixed DC single  |
| Voltage Regulator (LM317)               | 3            | Helps to drop the voltage to a desired value                             |
| Heatsinks                               | 3            | Helps keep the voltage regulators at a stable temperture                 |
| 40mm Brushless Fan                      | 1            | Helps keep the entire case cold                                          |
| Volt & Ammeter Screen                   | 2            | Used to read the voltage output and current draw, which is then displayed|
| Binding Posts                           | 4 or 8       | Used to get an output                                                    |
| 10 Turn 10K Potentiometer               | 1            | Used to selected a voltage output from 24v to 1v                         |
| 20 Turn 10K Trimpots                    | 4            | Used to adjust the variable voltage output (3.3v, 5v, 12v)               |
| Power Plug                              | 1            | Provides power from the outlet to the transformer                        |
| 10uF 50V                                | 2            | Used to stabilize the voltage output                                     |
| 100nF                                   | 3            | USed to stabilize the voltage going into the voltage regulator           |
| switchs                                 | 2            | Used to turn the voltage off for both constant and fixed supply          |
| SP10T                                   | 1            | Used to selected the constant voltage output (3.3v, 5v, 12v)             |




