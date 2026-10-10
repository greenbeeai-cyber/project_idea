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
1. 필요한 부품
Getting Started with Arduino: Controlling an LED with a Simple Blink Sketch via USB | by Mohamad Mahmood | Apr, 2026 | Medium
① 아두이노 우노(Arduino Uno R3)

1개 · 메인 제어 보드

센서에서 값을 읽고 진동 모터와 LED를 제어해.

KY-038 Sound Sensor Module – Easyelecmodule
② 마이크 소리 감지 센서

1개 · 아날로그 출력 AO가 있는 제품

주변 소리의 변화를 감지해. 제품에 따라 KY-038, MAX4466 등으로 선택할 수 있어.

How to Build a Vibration Motor Circuit
③ 소형 진동 모터와 구동 회로

각 1개

모형 바닥에 진동을 발생시켜. 모터 전류에 맞는 트랜지스터 또는 모터 드라이버를 함께 사용해야 해.

Arduino Starter Kit with Breadboard, Cables, Oman | Ubuy
④ 브레드보드와 점퍼선

각 1세트

부품을 납땜하지 않고 연결할 때 사용해.

エルパ LED 5mm 赤 HK-LED5H R
⑤ LED와 저항

LED 1개, 220~330Ω 저항 1개

소음 감지 시 불이 켜지도록 표시하는 용도야. 아두이노 보드의 내장 LED만 사용해도 돼.

Cable for Arduino UNO/MEGA (USB A to B) - 1 Meter
 – QuartzComponents
⑥ USB 케이블과 컴퓨터

각 1개

코드를 업로드하고 센서 측정값을 확인할 때 필요해.
