# Servo Sweep with Arduino

This Arduino sketch demonstrates how to control a servo motor using the built-in `Servo` library. The servo sweeps back and forth from 0° to 180° and then returns to 0°, pausing briefly at each step.

## 📜 Description

This code is based on the original example by **BARRAGAN** and modified by **Scott Fitzgerald**. It showcases how to:
- Initialize a servo motor
- Attach it to a digital pin
- Move the servo smoothly between angles

## 🔧 Requirements

- Arduino board (Uno, Nano, Mega, etc.)
- Servo motor
- Jumper wires
- External power source (recommended if using multiple servos)
- Arduino IDE

## 📦 Libraries Used

- [`Servo`](https://www.arduino.cc/en/Reference/Servo) (pre-installed with the Arduino IDE)

## ⚡ Wiring

| Servo Wire     | Connects To      |
|----------------|------------------|
| Red (VCC)      | 5V on Arduino     |
| Brown/Black (GND) | GND on Arduino |
| Yellow/Orange (Signal) | Digital Pin 9 |

## 💻 How to Use

1. Open the Arduino IDE.
2. Copy and paste the code into a new sketch.
3. Connect your servo as shown above.
4. Select your board and port from **Tools > Board** and **Tools > Port**.
5. Upload the sketch to your Arduino.
6. Watch the servo sweep from 0° to 180° and back.

## 🧠 Code Overview

```cpp
myservo.attach(9); // Attaches the servo to pin 9
