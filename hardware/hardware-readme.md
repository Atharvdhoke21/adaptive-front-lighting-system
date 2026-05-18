# Hardware Implementation

## Overview

The hardware section of the Adaptive Front Lighting System consists of an embedded control unit, steering input mechanism, servo motor-based headlight adjustment system, and power supply circuitry.

The prototype demonstrates automatic headlight direction control based on steering movement to improve visibility during vehicle turns.

---

## Hardware Components Used

| Component | Description |
|---|---|
| Microcontroller | Controls the adaptive lighting logic |
| Servo Motor | Rotates the headlights according to steering input |
| LEDs / Headlights | Simulates vehicle front lighting |
| Potentiometer / Steering Input | Simulates steering wheel movement |
| Power Supply | Provides operating voltage to the system |
| Connecting Wires | Hardware interconnections |
| Rf and Tx module 433Mhz | UART Communication |

---

## Hardware Working

1. Steering input is provided using a potentiometer or steering mechanism.
2. The microcontroller reads the steering position.
3. Based on steering direction, PWM signals are generated.
4. Servo motor rotates the headlights accordingly.
5. The lighting angle changes dynamically during turns.

---

## Hardware Features

- Real-time headlight adjustment
- Embedded control implementation
- Compact prototype design
- Low power operation
- Improved turning visibility
---

## Future Hardware Improvements

- Automotive-grade sensors
- CAN bus integration
- High-power LED driver circuit
- Camera-based adaptive lighting
- Automatic brightness adjustment

---

## Author

Atharv Dhoke
