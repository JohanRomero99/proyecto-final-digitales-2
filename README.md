This repository contains the necessary software elements to control the filling of a water storage tank in any type of home, everything will be controlled by means of a pic16f15244.
To make its correct development possible, it is necessary to have a series of elements such as an ultra-sound sensor, a source for a breadboard, an i2c which allows us to save considerable space when mounting, because for esteem and space reduction is the best. The respective programming is directly in assambler with an xc8 compiler and c ++ programming language.
Libraries of other pic were searched since with the present work it is a very recent pic and makes the resolution of this project more complicated. A number of records were modified.
Finally, it is expected that the ultrasound sensor calculates a prudent distance of 2cm to activate the led, which represents a buzzer and this generates an alarm notifying the user that it has already been filled.
video: https://www.youtube.com/watch?v=yGglW_63IBQ
hardware requirements
* PIF16F15244 CURIOSITY NANO
*SENSOR ULTRASONICO HC SR04
*PANTALLA LCD Y CONVERTIDOR I2C
*TANQUE

SOFTWARE REQUIREMENTS
* MPLAB X
* COMPILADOR XC8
vaya a la pagina  https://www.microchip.com/en-us/development-tools-tools-and-software/mplab-x-ide descargue le mplab xide y luego busque el compliador xc8


how to run:

connect breadboard source to pc
press the source button
place the cap on the tank which contains the last probe
verify that the ultra sound is well calibrated
remove the tank cap and proceed to fill it
then look at the led in the pic which indicates that the tank is full

Autores:

universidad de Ibague - ingenieria electronica proyecto final digitales 2

Cristian Acosta 2420172023
Johan Romero 2420181055
