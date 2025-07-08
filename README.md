# Arduino Traffic Light Project 🚦

A simple Arduino project that simulates a traffic light using three LEDs (red, yellow, green) and delay timing.

## 🧠 How it works

- Red LED turns on first for 1 second
- Then Yellow LED for 1 second
- Then Green LED for 1 second
- Loop repeats infinitely using `void loop()`

## 🔧 Components Used

- Arduino Uno
- Breadboard
- 3x LEDs (Red, Yellow, Green)
- 3x Resistors (220Ω)
- Jumper wires

## 🖼️ Circuit Diagram

![Circuit](images/circuit_diagram.png)

## 🧠 Code Overview

Code written in Arduino (C++) using:
- `pinMode()` for setting pins
- `digitalWrite()` for turning LEDs on/off
- `delay()` for timing

See [traffic_light.ino](traffic_light.ino) for full code.

## 📌 Next Steps / Improvements

- Add a pedestrian button
- Add buzzer/beep
- Improve realism with longer red phase
