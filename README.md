# ECE 528/L - Robotics and Embedded Systems Lab
**CSU Northridge**

**Department of Electrical and Computer Engineering**

## GPIO Lab
The GPIO lab interfaces with the following:

* User buttons and LEDs of the TI MSP432 LaunchPad
* PMOD SWT (4 Slide Switches) - [Product Link](https://digilent.com/reference/pmod/pmodswt/start)
* PMOD 8LD (8 LEDs) - [Product Link](https://digilent.com/shop/pmod-8ld-eight-high-brightness-leds/)

## Overview: 
This Lab introduces us to the General Purpose Input/Output interface of the MSP432 LauchPad. During this lab we learned how to utilize the PMOD SWT and PMOD 8LD together with the MSP432 LauchPad to generate different patterns with the LEDS on the board and PMOD 8LD.

## Components Used:
In this Lab we used the following Components:

* PMOD SWT
* PMOD 8LD 
* MSP432 LaunchPad

## Analysis and Results:
To start of this lab the procedure tasked us with connecting the PMOD SWT and PMOD 8LD to our MSP432 LaunchPad, after the proper connections were made we built and flashed the code to the board and tested to make sure the components worked. After doing that we moved onto the debugging portion of this Lab, this portion made us check how different registers would update when certain functions are called within the code. We were required to take 4 screenshots. These screenshots can be found in the images folder. Moving on from this we were required to complete 5 different tasks. They were to update the LED_Pattern_1 function, create a function for a binary down counter, creating two different functions for a ring counter to the left and a ring counter to the right and finally one for a johnson counter. We were able to verify our results with the instructor.

## Known Issues or Limitations:
In this Lab we did not encounter any limitations or issues.

## Author Contribution:
For this lab my partner and I worked on our own code however we shared how we did certain tasks with each other. As for the required screenshots these were taken by Gil Gandionco

## References:

* MSP432P4xx SimpleLink™ Microcontrollers
Technical Reference Manual
* MSP432P401R Datasheet [link](https://www.ti.com/lit/ds/slas826e/slas826e.pdf)