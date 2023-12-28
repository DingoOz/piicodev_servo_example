# piicodev_servo_example
An example of using the piicodev PCA9685 servo driver with the Raspberry Pi Pico using Arduino.

This example sweeps two servos attached to pin headers 1 and 2 on the board. [In the code pins 1 are servonum == 3, and the pins for servo 2 silkscreened on the board are servonum == 2] 

The piicodev servo control board is made by Core Electronics. The sample code provided is for Python only. This repo includes C based Arduino.

The build environment is Arduino IDE 2.2.1 and this has been tested on a Pico W.

Uses the following Arduino framework for the RP2040: https://github.com/earlephilhower/arduino-pico

To use this code, make sure you have installed the above framework, then install the Adafruit PCA9685 library. Then open the "servo.ino" file in the Arduino IDE and run.

"PiicoDev" and the PiicoDev Logo are trademarks of Core Electronics Pty Ltd.
