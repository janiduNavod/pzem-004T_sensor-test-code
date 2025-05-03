# ESP32 Energy Monitoring with PZEM-004T v3.0

This project reads and displays electrical parameters such as voltage, current, power, energy, frequency, and power factor using the PZEM-004T v3.0 module connected to an ESP32.

## 📟 Components Used
- ESP32 development board
- PZEM-004T v3.0 energy monitor
- Jumper wires
- AC load (e.g., bulb or appliance)

## 🔌 Wiring (ESP32 ↔ PZEM-004T v3.0)
| PZEM-004T v3.0 | ESP32 Pin |
|----------------|------------|
| TX             | GPIO16     |
| RX             | GPIO17     |
| VCC            | 5V         |
| GND            | GND        |

> ⚠️ Connect the PZEM’s TX to ESP32’s RX (GPIO17), and PZEM’s RX to ESP32’s TX (GPIO16).

## 🧠 Features
- Reads voltage in volts (V)
- Reads current in milliamps (mA)
- Reads active power in watts (W)
- Reads total energy consumed in kilowatt-hours (kWh)
- Reads AC frequency (Hz)
- Reads power factor (PF)


