## Introduction
Automobiles used in the cold regions must have seat heater along with the air-conditioning system.
This ensures more comfort to the driver by adjusting the environment temperature close to nominal body temperature.
### Advantages
* Comfortable driving experience.
* Faster heating of seats and reduced dependancy of AC heater.
### Disadvantages
* Should be adjusted manually and cause distraction.
## SWOT Analysis
### Strength
* Ability to change temperature setting through the code
* Manual control of temperature adjustment
* Manual switching operation
* Limited temperature range
### Weakness
* No feedback loop to check temperature
* Fails to detect malfunction
### Opportunity
* To adapt with the AC environment settings
* To detect error if malfunctions
### Threat
* Excessive heating can damage the seat
## 4 W's and 1 H
### Who
* The driver and passengers.
### What
* Heated seats for more comfort.
### When
* Very effective during cold winters.
### Where
* In the seats of the automobile.
### How
* Heating system within the seat.

## High Level Requirements
| ID | Description | Status (Implemented/Future) |
| --- | --- | --- |
| HR01 | Supply PWM signals based on the required temperature | Implemented |
| HR02 | Should only be activated when the driver is seated | Implemented |
| HR03 | Should be able to turn OFF manually | Implemented |

## Low Level Requirement
| ID | Description | Status (Implemented/Future) |
| --- | --- | --- |
| LR01 (HR01) | Specify the duty cycles based on the temperature | Implemented |
| LR02 (HR02) | Reliability of the switch connected to the seat | Implemented |
| LR03 (HR03) | Switch to manually turn ON and turn OFF the seat heater | Implemented |


## Block Diagram

![diagramproject](https://user-images.githubusercontent.com/94305490/144293871-4a08c073-3ee0-430a-8db0-5597a8feb310.png)


## Flow chart

![projectdiagram](https://user-images.githubusercontent.com/94305490/144293951-978efe91-5e07-4926-8043-1749c311f18f.png)


# Implementation
## Introduction
This folder conatins all the coding files as well as the resources and testing files neede for proper execution of program
## Instructions to execute
1. Clone my repository
2. Go to 3_Implementation folder
3. Make sure your system meets all software and hardware requirements
4. Run "make run" command in terminal for main code execution
5. Run "make run_test" command in terminal for test code execution
| Folder | Description |
| --- | --- |
| inc | Contains header files |
| src | Contains additional source file for compilation |

