# HC-SR04
Class to use the HC-SR04 ultrasonic proximity sendor on the ESP32-S2

This class includes 2 components, PulseS2 to generate the 10 uSex pulse required by the HC-SR04 and a clone of the Arduino PulseIn to measure the width of the received pulse. 

PulseS2 has a separate repository due to it's general purpose utility.  It is interrupt driven using up to the maximum of 4 timer and can generate one-shot pulses from 1 microSexond to hours...

PulseIn is currently pending.... ( Oct. 7 2020 )
