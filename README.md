Arduino Noise Detection System
Overview
An Arduino-based experimental system that measures relative sound intensity and records noise events. A small vibration motor provides brief feedback on a test model.

Hardware
Arduino Uno
Analog microphone sensor
Small vibration motor
Suitable transistor or motor driver
Breadboard and jumper wires
How It Works
The microphone sensor captures sound signals.
Arduino measures the peak-to-peak signal amplitude.
The measured level is compared with a configurable threshold.
A short vibration pulse is generated on the experimental model when a qualifying event is detected.
Measurements are sent to the Serial Monitor for analysis.
Data Collection
The serial output contains:

Elapsed time in milliseconds
Relative sound level
Event classification
Limitations
The sensor readings are relative values, not calibrated dB measurements.
The threshold depends on the sensor, environment, and wiring.
The vibration output is intended for a small experimental model only.
Future Improvements
Calibrate sound measurements against a sound level meter.
Store measurements and visualize them using Python.
Analyze repeated impact patterns.
Compare sensor readings under different experimental conditions.
