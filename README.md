# RGB-LED-Faucet

A project I designed to take my knowledge of software programming to solidify my growing understanding of basic electronics, as well as begin thinking about design of systems as a mechanical engineer. 

# Purpose:
Create a sensor that changes the color of water according to the temperature of water leaving the faucet.

# Hardware:
-- Arduino Uno
-- AtTiny85 - similar to the Arduino Uno in function, but with significantly less I/O pins. Advantage: much smaller and cheaper.
-- PCB prototyping boards
-- 10k ohm, 0.5 watt NTC thermistors
-- RGB LED (Common Cathode)

# Software:
Arduino programming IDE was used to create a prototyped breadboard model as a proof of concepts. The same IDE was later used to program an AtTiny85 with the exact same code. Code was written in C, and the information on the Steinhart Equaiton was taken from http://www.circuitbasics.com/arduino-thermistor-temperature-sensor-tutorial/

# LESSONS LEARNED
-- In depth understanding of software Pulse Width Modulation (PWM)
-- How to better design a circuit/ electronic system. There will be a v2.0 eventually.
-- How NOT to solder a PCB Prototyping board
-- Functionality of tranforming analog signals into microprocessor-readable digital signals (Steinhart Equaiton)
-- MOST IMPORTANT: **To take more pictures next time (  Only thought to take pictures of finished product, not during the build :(  ) **
