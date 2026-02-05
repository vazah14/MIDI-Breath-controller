# Breath-Controlled MIDI Input Device

## Creators
- **Ashton Vaz** – Project Manager, Firmware Development  
- **Ryani Fernandopulle** – Release Planning, Testing, Documentation
For questions or collaboration, please contact us via GitHub or email.

## Overview
This project is a **breath-controlled MIDI device** that allows musicians to control virtual instruments in Logic Pro using breath pressure. It uses an Arduino and a pressure sensor to replicate expressive qualities of woodwind instruments while providing digital flexibility.

---

## Features
- Converts breath pressure into MIDI signals in real time.  
- Dynamic control of volume, timbre, or modulation.  
- Portable, low-cost prototype.  
- Iterative design for easy testing and improvement.

---

## Hardware & Software
**Hardware:** Arduino Uno, pressure sensor, wires, breadboard, USB.  
**Software:** Arduino IDE (C++), MIDI Library, Logic Pro.  

---

## Usage
- Blow into the sensor to generate MIDI signals.  
- Logic Pro responds in real time, controlling the selected instrument.  
- Firmware allows adjustment of sensitivity and MIDI mapping.

---

## Development & Contribution
- Agile Iterative Prototyping: build, test, refine in short cycles.  
- GitHub Feature Branch workflow:  
  - `[feat]` – feature  
  - `[fix]` – bug fix  
  - `[doc]` – documentation  
- Pull Requests reviewed by the other team member before merging.

---

## Known Issues
- Sensor latency may vary.  
- No enclosure yet.  
- Manual MIDI channel configuration required.

---

## Future Improvements
- Multi-sensor support.  
- Tilt/accelerometer input.  
- User-friendly enclosure.  
- Visual feedback (LED/OLED).  

---

## License
This project is licensed under the **Apache License 2.0**. See [LICENSE](LICENSE) for details.

test