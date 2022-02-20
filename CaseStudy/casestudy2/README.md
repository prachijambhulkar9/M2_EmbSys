# Case Study 2: Complex Embedded System

# Washing Machine



## Introduction / Purpose:

Washing machine is a very useful appliance which is used in homes for washing and drying cloths. It reduces lot of human efforts of cleaning laundry.
Input: User will select the command from key pad which he/she required according cloths.
Output: we will know the cloths are washed through LCD display which shows time and buzzer gives signal after the washing.



## Block Diagram:

Following is the block diagram of washing machine.

 ![washing ](https://user-images.githubusercontent.com/99121577/154841821-a3f9b137-aedc-41be-b6d5-16c7f0107473.jpg)




## Components:

1.	Key pad – It is used to give the input operations.

2.	EEPROM – It is used to erase and reprogram stored data repeatedly in machine.

3.	Amplifier + ADC – Amplifier is used to increase the power of signals which are getting from the weight, humidity, and current sensors. ADC is to convert analog to 	   digital signal.

4.	Relay/TRIAC – It is used to control switching operations.

5.	Microcontroller – It is used for controlling all the operations.

6.	Temperature sensor – it is required to sense the temperature.

7.	Motor control – It consists of drum and pump where pump is required to take water and gives it in drum. Inside drum all the operations of washing, spinning, rinsing happens.

8.	Clock – It sets the timer.

9.	LCD Display – It shows the timing, and operations which are going on inside machine.

10.	Buzzer – It gives signal after the completion of operation.

|Name	|Description|
|:------------------------------------------------------------------------------------------------------:|:---------------------:|
|Microcontroller	|8051|
|Temperature sensor	|RTD, Thermistor|
|LCD Display|	16*2|
|Buzzer|	5v|



## High Level Requirements:


1.	System Should wash cloths properly by spinning, rinsing, drying.
2.	System should dry cloths after washing.
3.	It should take water according to the weight or number of cloths.
4.	System should have friendly user interface (key pad from which we select operation should easy to use for everybody) it should contain program select knob where every 	       functions given according to the requirements for example if you are washing daily cloths the normal option should be there, for heavy and very dirty cloths heavy 	  option should be there, for soft/silk cloths delicate option should be there any so many options according to the need. 
5.	If in case of any interruption like power off during machine is on in that situation it should resume working from the time it gets pause.
6.	Energy Consumption and water consumption.




## Low Level Requirements:

1.	User should select proper functions.
2.	Design of washing machine whether it is front loaded or top loaded.
3.	Size and Capacity of machine (for example - 6kg,7kg,7.5kg washing machines).



## Application: 

A washing machine is a home appliance used to wash laundry.



                                                                                                               
