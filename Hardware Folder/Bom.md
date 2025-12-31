# Bill of Materials (BOM) – Voice Controlled Robotic Car

This document lists all hardware components required to build the Voice Controlled Robotic Car, including specifications, quantity, and purpose.

---

## 📌 Component Summary Table

| Sl.No | Component | Specification / Details | Quantity | Purpose |
|------|-----------|-------------------------|---------|--------|
| 1 | Arduino UNO R3 | ATmega328P | 1 | Main microcontroller |
| 2 | HC-06 Bluetooth Module | Serial Communication | 1 | Wireless voice command communication |
| 3 | L293D Motor Driver | Dual H-Bridge Driver | 1 | Controls motor direction & speed |
| 4 | DC Gear Motors | 6V–12V | 4 | Movement of robot |
| 5 | Robot Car Chassis | Acrylic / Metal | 1 | Mechanical body |
| 6 | Wheels | Compatible with DC motors | 4 | Locomotion |
| 7 | Battery | 7.4V Li-ion / 9V | 1 | Power supply |
| 8 | Battery Holder | 2×18650 holder / 9V clip | 1 | Secure battery mounting |
| 9 | Jumper Wires | Male–Male / Male–Female | — | Circuit connections |
|10 | Power Switch | ON/OFF toggle | 1 | Power control |
|11 | Breadboard / PCB | Optional | 1 | Circuit interface |
|12 | Resistors | 220Ω / 1kΩ (if needed) | Few | Signal conditioning |
|13 | Screws + Nuts | Standard kit hardware | Few | Assembly |

---

## 🔌 Power Supply Requirements
- Arduino UNO: 5V (USB or regulator)
- Motors: Preferably 6V–12V

Recommended:
- 2 × 18650 Lithium batteries  
  or  
- 9V battery (for small builds)

---

## 🔧 Assembly Notes
- Use separate power for Arduino and Motors if possible to avoid resets.
- Ensure common ground between Bluetooth, Arduino, and Motor Driver.
- Secure HC-06 wiring to avoid connection drop.
- Tighten chassis screws to reduce vibration.

---

##  Safety Notes
- Do not reverse battery polarity.
- Avoid short-circuiting terminals.
- Prevent overheating while soldering.
- Ensure driver IC does not overheat.
