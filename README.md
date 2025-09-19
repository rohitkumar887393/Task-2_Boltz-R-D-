# Task-2_Boltz-R-D-
This project demonstrates a simple temperature-controlled fan system built with an Arduino Uno and a 10k NTC thermistor. A DC fan (simulated by an LED) is controlled using PWM on digital pin 13 with the help of the SoftPWM library
, since pin 13 on Arduino Uno does not support hardware PWM.


Features:-

Reads real-time temperature from a 10k NTC thermistor connected to A0.
Controls a fan (or LED) connected to pin 13 with different speeds:

Temperature < 25 °C → Fan OFF
25 °C ≤ Temp < 30 °C → Fan runs at 50% speed (PWM)
Temp ≥ 30 °C → Fan runs at 100% speed
Prints live temperature readings and fan state on the Arduino Serial Monitor.

Uses SoftPWM to simulate PWM on pin 13.
