# AUTOMATIC SEAT HEATER SYSTEM

![image](https://github.com/Varsha-5/M2_Project_2022/blob/main/Heated-Car-Seats-3.jpg)

# OBJECTIVE

  * To design an automatic seat heater system which is smart enough to heat the seat when so ever is needed.
  * To conserve the energy by making the system operate at needed times.
 
# Introduction
  
  * Automatic Seat Heater System transfers heat directly to the user rather than warming up the interior of the automobiles like car.
  * Because of this, these seats can actually conserve energy (and gas).
  * Moreover,the user you might not need the heater on at all times.
  * This system is intelligent enough that is has the ability to make the heater ON and OFF as per the requirement. 

# Construction

  * The embedded system is constructed by using Atmega 328 Microcontroller.
  * The micrcontroller is responsible for co-ordinating and controlling  the functionalities assosiated with the system.
  * The LED is used as a General Purpose Input Output(GPIO).
  * The Pulse Width Modulation(PWM) is made by varying the duty cycles.
  * The UART is also tested.

# Hardware Components
   
  * Atmega328 Microcontroller.
  * LED
  * Power Supply
  * Potentiometer(Analog Sensor)
  

# Softwares Used
* Visula Studio Code
* Aurdino IDE
* SimulIDE


# Component Description

## Microcontroller:
- It is responsible for coordinating and controlling all the functionalities of the designed system.

## Potentiometer
- It acts as an anolog sensor which is able to provide varied inputs.

## Switch
- It is used to control the operation.

## LED
- It is used as an indication of a particular event.

## Power Supply
 - It is used to  power the system.

--------------------------------------

# SWOT

## Strengths

- Easy to understand the application and use it
- User friendly gadget
## Weakness 

- Implementation of existing system.

## Opportunities

- Used in automobiles.
- It can also be used in cooler places like living rooms by making slight modification.

## Threats

- Prolonged exposure of it may lead to some health issues.


 # 4W's and 1'H 
 
 ## Who:- 
   This is developed by the embedded engineers.
   
 ## Where:-
   It can be used in automobiles,Cooler places.
   
 ## When:-
   It is used to have a warmer environmnet.
   
 ## Why:-
   Designed for cooler scenarios where warming is needed.
   
 ## How:-
   It is designed by using Atmega 328 Microcontroller and it is programmed by using embedded C.

# DETAIL REQUIREMENTS

## High Level Requirements

|ID	        | Description	                                |Status
| :---         |     :---:      |          ---: |
|HL01	|To provide a better user interface |Implemented|
|HL02	|To detect whether the person is seated or not |Implemented|  

## Low Level Requirements

| ID	       | DESCRIPTION    | STATUS        |
| :---         |     :---:      |          ---: |
|LLR1	       |  Interface switch(for seat detection) with ATMega328 |Implemented    |
|LLR2	       |  Interface LED With ATMega328p   | Implemented  |
|LLR3	       |  Interface Potentiometer with ATMega328  |Implemented   |
