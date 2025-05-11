# Automatic Gate Demo Kit

A simple Arduino Uno project that simulates an automatic gate using an ultrasonic sensor, servo motor, LEDs, and a buzzer.

## How It Works

* Detects objects within 50 cm using an HC-SR04 sensor.
* Opens the gate (servo to 90°) when an object is detected.
* Closes the gate (servo to 0°) after 5 seconds of no detection.
* 🔴 Red LED = Gate closed
* 🔵 Blue LED + 🔊 Buzzer = Gate open

## Components

* Arduino Uno
* Ultrasonic Sensor (HC-SR04)
* Servo Motor (SG90)
* Red & Blue LEDs
* Buzzer
* Breadboard + Jumper Wires
