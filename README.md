# Embedded_TASK_climate_control



## Embedded LAB TASK : Climate control

##### Task Description and Expected solution 

The existing climate control interface in Embedded systems Laboratories consists of three buttons/LEDs: Off, Heat, Cool. Besides the manual interaction possibility, a time schedule is actively controlling these modes. The assigned task is to override this time schedule by a fixed target temperature control.

So we need temperature sensor as measuring device and a Servo motor to control the temperature. The servo motor rotates clock-wise or Counter Clock-wise and is used to press either the "Heat" or the "Cold" button. The temperature sensor will measure the temperature of the room and its digital output is fed to the micro controller.

Additionally ,a turning knob( Potentiometer)is made available to SET the desired temperature. The analog output of the potentiometer is also fed to the micro-controller. A suitable logic is implemented as software in the micro controller to compare the two inputs ( i.e from Potentiometer and temperature sensor) and drive the servo motor to rotate servo motor in desired direction.

Programmable Features : 
1. The angle of rotation of servo motor
2. The Hysteresis range of room temperature ( i.e minimum and maximum offset from the set temperature ).
3. The duration for which the " HEAT " or "COLD" button is to be pressed.

**NOTE: No modifications to the existing appliance are allowed.**

#### Schematic diagram

![temperature_control_schematic_updated](https://user-images.githubusercontent.com/28274003/27994850-2185ed86-64b5-11e7-922e-107509c1cd3e.png)


#### Wiring Diagram


![temperature_control_wiring_updated](https://user-images.githubusercontent.com/28274003/27994848-1d386010-64b5-11e7-8f10-024aaadccbbf.png)

#### Components list


| Part Name                               |   Quantity       |
|-----------------------------------------|------------------|
| Arduino Uno (Rev3)                      |        1         |
| USB cable                               |        1         |
| Bread board                             |        1         |
| Wires , jumpers                         |     bunch        |
| Potentiometer                           |        1         |
| Temperature Sensor  (DFR0024 DFRobot )  |        1         |
| Servo motor                             |        1         |
| Touch LCD MI0283QT2                     |        1         |
| Green LED   (optional)                  |        1         |
| Red LED   (optional)                    |        1         |


#### Screen Shot 1

![code_1](https://user-images.githubusercontent.com/28274003/28129255-a7116000-6700-11e7-8089-b46401e16989.png)

#### Screen Shot 2

![code2](https://user-images.githubusercontent.com/28274003/28129262-abdaa632-6700-11e7-9c76-ef3a9dbc7948.png)

#### LCD Display 

The  LCD displays the current status of the system like "Set tmeprature" , "Current Temperature",  and the action taken like "Increasing  or decreasing the temperature".


![img_20170711_224020823-001](https://user-images.githubusercontent.com/28274003/28129505-8fc02eb2-6701-11e7-9178-42c432968e38.jpg)
