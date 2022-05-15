# REQUIREMENTS

## INTRODUCTION

A wiper speed control system for an automotive wiper controls the operational speed of a wiper in accordance with rain conditions. The control system includes a rain sensor (30) detecting rain conditions to produce . an analog signal having an amplitude depending upon the detected rain conditions. The analog sensor signal is converted into a digital pulse signal by a converter (12) for application to a digital circuit system. A control signal is produced by digitally processing the pulse signal. The control signal is applied to a wiper driver circuit to adjust the operational speed or timing in accordance with the control signal.

## Features

* Changes the wiper speed according to rain intensity.
* Avoids accidents during rain.
* Ensures human safety.
* Doesn't require driver to change the speed manually.

## COMPONENTS
![image](https://user-images.githubusercontent.com/68106099/168474350-ed272c84-3381-48d2-8be5-d27e08c5033f.png)

The STM32F407/417 lines are designed for medical, industrial and consumer applications where the high level of integration and performance, embedded memories and rich peripheral set inside packages as small as 10 x 10 mm are required.
The STM32F407/417 offers the performance of the Cortex™-M4 core (with floating point unit) running at 168 MHz.

Performance: At 168 MHz, the STM32F407/417 deliver 210 DMIPS/566 CoreMark performance executing from Flash memory, with 0-wait states using ST’s ART Accelerator. The DSP instructions and the floating point unit enlarge the range of addressable applications.

Power efficiency: ST’s 90 nm process, ART Accelerator and the dynamic power scaling enables the current consumption in run mode and executing from Flash memory to be as low as 238 µA/MHz at 168 MHz.

Rich connectivity: Superior and innovative peripherals: Compared to the STM32F4x5 series, the STM32F407/417 product lines feature Ethernet MAC10/100 with IEEE 1588 v2 support and a 8- to 14-bit parallel camera interface to connect a CMOS camera sensor.

## 4W'S and 1H:
### What?
* Wiper Control system where the Wiper of a car is controlled by a wireless key. Wiper status will be Indicated through LED's.
### WHY?
* To know the principle behind a Wiper system and to manipulate its speed with respect to user's need. 
### WHERE?
* Anywhere the user wants to use the feautures provided.
### WHO?
*  People who are all having Car.
### HOW?
* Through a Simple and single Button.

## SWOT ANALYSIS:
### Strength:
- No need of Human Interaction.
- Wiper system of Different cars can be Interfaced and handled.
- Easy handle and usage of features through a simple User Button.
- Cost efficient.
### Weakness:
- Limited usage Range.
- Less User privacy and security.
- Timers/Interrupts can be a better approach instead using Delays.
### Opportunity:
- Wide Scope in the Future of Automobiles Wiper Managemnet and Control System.
- Cost efficient.
- Since advanced features can increase Car value.
### Threat:
- Now there are many new developing devices for competition in the Automobiles advancement sector.

## High Level Requirements
| ID | Description | Category | 
| ----- | ----- | ------- | 
|HL01|User should able to view intensity of rainfall on LCD|technical|  
|HL02|User should be given alert incase of heavy rainfall |technical|
|HL03|User should able to TURN ON wiper system |technical|  
|HL04|The system sould able automatically switch the speed of wipers |technical|
|HL05|The system should work accurately|technical|  


## Low Level Requirements 
| ID | Description | Category | 
| ----- | ----- | ------- | 
|LL01|User should able to TURN ON wiper system |technical|  
|LL02|The system sould able automatically switch the speed of wipers |technical|
|LL03|The system should work accurately|technical|  
