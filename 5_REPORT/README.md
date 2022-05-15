# WIPER CONTROL SYSTEM
## ABSTRACT

Wiper is an essential component that used to wipe raindrops or any water from the vehicle’s windscreen.
The previous system
used to activate the wiper manually and the process of pulling up the wiper is difficult to be handled. Thus, this system is
proposed to solve these problems. The objectives of this project are to upgrade the older cars system by providing automatic
wiping system, to improve the system by using STM32F4xx-discovery board. Most car wipers have a DC motor that controls their action, but the STM32F4xx-discovery does not have any motor, so we are considering LEDs for this application.

As the wiper control system, there are four LEDs and a Push Button on the STM32F4xx-discovery board. These LEDs are orange, green, red, and blue in color.With the Discovery board GPIO pins of STM32F407VG microcontroller will be configured as digital input pins to enable a push button to operate with STM32F4. If you press the user button and hold it for two seconds, the Red LED turns on which indicates the ignition key is positioned at the ACC. In addition, the LEDs will blink, which indicates the wipers are ON.

Wiper is ON: Initially, the wiper is off. On pressing the user input, Blue, Green, and Orange LEDs blink one at a time with the set frequency. The frequency changes with each alternate key press (key means push button). When the 1st key is pressed, the LED blinks at 1 sec per key, and when the 2nd key is pressed, the LED blinks at 0.25 sec per key press, and when the 3rd key is pressed, the LED blinks at 0.125 sec per key press. Wiper is OFF: Wiper is ON: The LED glow pattern stops after the fourth press; the wiper action begins after the second press onwards as explained in step 2. If the user button is pressed and held for 2 seconds, the red LED is off at the lock position.

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

## ARCHITECTURE
### BEHAVIOURAL DIAGRAMS
![B1](https://user-images.githubusercontent.com/68106099/168480755-9cd46649-823d-44fa-bd8c-4bf3b47d6bf5.jpeg)

### FLOW CHART
![FLOW](https://user-images.githubusercontent.com/68106099/168480771-5938fd93-e9f9-4100-91ed-e7733b763cda.jpeg)

### BLOCK DIAGRAM
![BD](https://user-images.githubusercontent.com/68106099/168481008-c42f4ec8-53b6-400d-bccc-a3edf763daed.jpeg)

### STRUCTURAL DIAGRAM
![ST](https://user-images.githubusercontent.com/68106099/168480946-3db6ce90-37c1-4bef-8e40-c707a161f6f5.jpeg)


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

## Best Methods Followed
* Exact Mapping of code to avoid confusions
* Mentioning of both High level and Low level Behavioral and structural diagrams for better understanding
* Followed the exact symbols to make the understanding easier
* Detailed explanation in Low level Behavioural and Structural Diagrams

# OUTPUT

## STM BOARD
![STM BOARD](https://user-images.githubusercontent.com/68106099/168479850-9fe80859-4dac-4ec3-9049-e0c0cc4159e7.png)

## Ignition Key Position at ACC
![RED LED ON](https://user-images.githubusercontent.com/68106099/168479890-1da5f8d4-d720-4da0-ad00-69c89687fba5.png)

## WIPER ON STATE
### AT 1HZ FREQUENCY
![BLUE LED ON](https://user-images.githubusercontent.com/68106099/168479970-4ff5ae87-16eb-434c-8e59-56ac691b0b83.png)

### AT 4HZ FREQUENCY
![GREEN LED ON](https://user-images.githubusercontent.com/68106099/168479980-c65b9824-e661-48e1-a5bd-2035146d7d37.png)

### AT 8HZ FREQUENCY
![ORANGE LED ON](https://user-images.githubusercontent.com/68106099/168479991-e1de74ac-940f-41c8-9ad9-b3624dd234a4.png)

## WIPER OFF STATE
![RED LED ON](https://user-images.githubusercontent.com/68106099/168480011-2d293bdf-7c48-46d0-b049-3cd124ababb8.png)

## Ignition Key Position at Lock
![STM BOARD](https://user-images.githubusercontent.com/68106099/168480042-438510d1-cbbc-4927-ac06-c02a77cd0964.png)

