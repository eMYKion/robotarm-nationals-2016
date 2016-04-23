The compilation produces a groff output program called <test-integ-0> (as the initial version).
All other excecutive groff files are from vestigial testing.
The c++ source file with the main function is the <main.cpp> file.
The project was intended to be run off a Raspberry Pi computer with SPI reading enabled, as well as the WiringPi library installed.
The WiringPi project can be found here: (wiringpi.com/).

The current version does not use PID, it just rotates the elbow of the robot with a fixed duty cycle based on an error in potentiometer readings.
