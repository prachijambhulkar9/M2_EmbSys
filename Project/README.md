## Table of Content:
* Introduction/Abstract
* Objective
* SWOT ANALYSIS
    1. Strenght
    2. Weakness
    3. Opportunities
    4. Threats
* WWWWH
    1. Who
    2. What
    3. When
    4. Where
    5. How
* Requirements
    1. High Level Requirements
    2 Low level Requirements
* Block Diagram
    1. Push Button
    2. ATmega328
    3. L293

## Introduction/Abstract :-
Speed control of motors is very essential there are so many examples where speed control of DC motor is required For example- In Robotic application – Dc motor used to change direction and speed of moving robot. In Industrial application – Dc motor to change direction and speed of rotating machinery· In Domestic application – It is used to vary speed of portable fan, Mixer,Pumps etc and there are so many areas where speed control of Dc motor is required. So this project demonstrates how to vary the speed and change the direction of DC motor using AVR microcontroller ATmega328.

## Objective
The main objective of this project is:

* To change the speed of the motor as per the need.
* To change the direction of rotation of the motor as per the need.
* To save the energy of the battery.
* To increase the life of the battery.


## SWOT ANALYSIS

1.Strength
* It can change the speed of the motor as per the need.
* It can change the direction of rotation of the motor as per the need.

2.weakness
* It is only limited to small ratings dc motor.
* Sudden stoppage of the motor is not possible.

3.Opportunities
* A wide range of speed controllers can be made for high rating of a motor.
* Multiple motors can be controlled.

4.Threats
* A wide range of speed controller for the high rating of a motor is already available in the market.

## 4W's and 1H's
1.Who:
* The person who has basic knowledge of speed controlling.
* The person who wants to change the speed of appliances on which he working.

2.What:
* To get controllable speed.
* To change direction and speed of moving robot.

3.When:
* When there is a need for a change in speed.
* When there is a need to control speed and direction of motor as per requirement.

4.Where:
* For domestic purposes.
* For Industrial purposes.
* For defense purposes.

5.How:
* Using ATmega328 as a controller to control the speed and direction of dc motor.
* Detail requirements

## Requirements:

1.High Level Requirements:

|ID|	Description|	Status|
|:--:|:------------------------------------------------------:|:---------:|
|HR_1|	Rotate motor in clockwise direction|	Sucess|
|HR_2|	Rotate motor in anticlockwise direction|	Sucess|
|HR_3|	Change the speed of motor in clockwise direction|	Sucess|
|HR_4|	Change the speed of motor in anticlockwise direction|	Sucess|
|HR_5|	Sudden stoppage of the motor|	Future|

2.Low level Requirements:

|ID|	Description|	Status|
|:--:|:------------------------------------------------------:|:---------:|
|LR_1	|Speed at 25% duity cycle	|Sucess|
|LR_2|	Speed at 50% duty cycle	|Sucess|
|LR_3|	Speed at 75% duty cycle	|Sucess|
|LR_4|	Speed at 100% duty cycle|	Sucess|

## Block Diagram :

![speed control-page-001 2](https://user-images.githubusercontent.com/99121577/155692743-18e0afa2-3b7e-480a-85fc-4f2fe7814e3a.jpg)


1. Push Button :- The push button switch is usually used to turn on and off the control circuit.

2. ATmega328 :- The ATmega328 microcontroller combines 32 KB ISP flash memory with read-while-write capabilities, 1 KB EEPROM, 2 KB SRAM, 23 general-purpose I/O lines, 32 general-purpose working registers, 3 flexible timer/counters with compare modes, internal and external interrupts, serial programmable USART, a byte-oriented 2-wire serial interface, SPI serial port, 6-channel 10-bit A/D converter (8 channels in TQFP and QFN/MLF packages), programmable watchdog timer with internal oscillator, and 5 software-selectable power-saving modes. The device operates between 1.8 and 5.5 volts. The device achieves throughput approaching 1 MIPS/MHz


* Parallel program mode

|Programming signal|	Pin Name|	I/O	Function|
|:--:|:------------------------------------------------------:|:---------:|
|RDY/BSY|	PD1	O|	High means the MCU is ready for a new command, otherwise busy.|
|OE|	PD2	I|	Output enable (active low)|
|WR	|PD3	I	|Write pulse (active low)|
|BS1|	PD4	I	|Byte select 1 ("0" = Low byte, "1" = High byte)|
|XA0	|PD5	I	|XTAL action bit 0|
|XA1|	PD6	I	|XTAL action bit 1|
|PAGEL	|PD7	I	|Program memory and EEPROM data page load|
|BS2|	PC2	I|	Byte select 2 ("0" = low byte, "1" = 2nd high byte)|
|DATA|	PC[1:0]:PB[5:0]	|I/O	Bi-directional data bus (output when OE is low)|


* Serial program mode

|Serial| programming|
|:--:|:------------------------------------------------------:|
|Symbol|	Pins|	I/O	Description|
|MOSI	|PB3	I	|Serial data in|
|MISO|	PB4	O | Serial Data out|
|SCK	|PB5	I	|Serial Clock|

3. L293 :- The L293D is a 16-pin Motor Driver IC which can control a set of two DC motors simultaneously in any direction. The L293D is designed to provide bidirectional drive currents of up to 600 mA (per channel) at voltages from 4.5 V to 36 V (at pin 8!). You can use it to control small dc motors

