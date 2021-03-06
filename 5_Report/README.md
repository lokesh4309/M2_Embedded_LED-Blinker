# Requirements
# Introduction
   Blinking of LED is a simple project in Embedded progamming world. There are several ways of making a blinking LED circuit. You can make one using relays. You can        make one using transistors. Or you can make one using components like an inverter, a 555 Timer or a microcontroller. Here swtich is used to blink the two LED using  ATmega328(a microcontroller).
# Objective
   The main objective is to blink the led using ATmega328 and a switch to controll two LED's.
# Components used
1.ATmega328   

2.Two LED 

3.Switch

4.Resistor
# software used
1.simulIDe

2.Visual Studie Code
# Research
   Atmega328 is an Atmel microcontroller, which is used in Arduino UNO board.Atmega328 has 28 pins in total. It has 3 Ports in total which are named as Port B,Port  C and Port D.Port C is an analogue Port and it has six pins in total. So, in simple words, ATmega328 has 6 analogue pins.Port B and Port D are digital ports and have 7 pins each.So, in total ATmega328 has 14 digital pins. It also supports Serial Communications, we can perform serial communication via Pin  2 (RX) and Pin 3 (TX).It also supports SPI Protocol.




# Features
   It has simple features.
       
    1.It can switch off the LED's when switch is in off state.
    2.It can switch on the LED's when switch is in on state.
# 4W's and 1 H's
   ## Why
    1.To blink two LED's using a switch in ATmega328.
    2.To understand basic concepts in ATmega328.
   ## Where
    1. It can be used anywhere.
    2. It can be used for understanding purposes in schools and colleges.
   ## Who
    1.It can be used by students.
    2.It can be used by anyone who are new to embedded programming language.
   ## When
    1.People are trying to learn an embedded programming language.
    2.In schools and colleges it can be implemented.
   ## How
    1.By using softwares to exceute the program.
    2.By loading the program in ATmega328.
# SWOT Analysis
   ## Strengths
    1.Simple program to understand.
    2.Cost effective.
   ## Weakness
    1.Basic program.
   ## Opportunities
    1.Program can be made more complex by adding more components.
   ## Threats
    1.There are advanced programs which are simple to learn is out already.
# High Level Requirements
| Id    	| Description     	| Status      	|
|-------	|-----------------	|-------------	|
| HLR_1 	| Microcontroller 	| Implemented 	|
| HlR_2 	| Swtich          	| Implemented 	|
| HLR_3 	| Two LED         	| Implemented 	|
| HLR_4 	| Software        	| Implemented 	|
# Low Level Requirements
| Id    	| Description              	| Status      	|
|-------	|--------------------------	|-------------	|
| LLR_1 	| ATmega328                	| Implemented 	|
| LLR_2 	| Swtich                   	| Implemented 	|
| LLR_3 	| Two LED                  	| Implemented 	|
| LLR_4 	| Visual studio & SimulIDE 	| Implemented 	|

# Design
 1.This project uses ATmega328.
 
 2.This system uses swtich to blink LED.
# Behavior Diagram

![Behaviour diag embd](https://user-images.githubusercontent.com/94420732/144303561-d73fc08d-5e21-429e-a302-0f40520f1f34.jpeg)

# Structural Diagram

![STRUCT DIAG EMBD](https://user-images.githubusercontent.com/94420732/144303585-1823a5ca-5182-4a4f-81b5-2ac1ce3a04eb.jpeg)

# Block Diagram

![BLOCK Diag](https://user-images.githubusercontent.com/94420732/144303608-aa866716-8aa0-4db4-be77-4f4cf87dcdb9.jpeg)

# Simulation

![switch off](https://user-images.githubusercontent.com/94420732/144376267-16bc55a4-4a4c-43b1-b676-fcb98c419cd8.png)

# Implementation
# Folder Structure
| Folder   |      Description     |
|----------|:-------------:|
| document | Doxygen documentation |
| inc | All header files |
| simulation | simulation files |
| src | Main source code for LED Blinker |

# Test Plan

## High Level Requirement
| Id    	| Description 	| Expected I/P 	| Expected O/P 	| Actual O/P 	| Type Of Test 	|
|-------	|-------------	|--------------	|--------------	|:----------:	|--------------	|
| HLR_1 	| Switch on   	| High power   	| LED On       	| LED On     	| Rquirement   	|
| HLR_2 	| Switch Off  	| No power     	| LED Off      	| LED Off    	| Requirement  	|

## Low Level Requirement
| Id    	| Description 	| Expected I/P 	| Expected O/P 	| Actual O/P 	| Type Of Test 	|
|-------	|-------------	|--------------	|--------------	|:----------:	|--------------	|
| LLR_1 	| Switch on   	| value 1      	| LED On       	| LED On     	| Rquirement   	|
| LLR_2 	| Switch Off  	| value 0      	| LED Off      	| LED Off    	| Requirement  	|


# SWITCH is OFF
![switch off](https://user-images.githubusercontent.com/94420732/144376447-d843c0b9-6b44-4941-89a7-04fcb88886d3.png)

# SWITCH is ON
![switch on 1](https://user-images.githubusercontent.com/94420732/144376500-90a4c127-8f55-45cd-8012-7e7b29983d72.png)

![switch on 2](https://user-images.githubusercontent.com/94420732/144376517-0f054288-5ea9-4bbd-8bf4-87ab22f94218.png)

![output 1](https://user-images.githubusercontent.com/94420732/144377263-2d5c9a89-9917-4e9e-ab77-7ff3a19820e0.gif)
