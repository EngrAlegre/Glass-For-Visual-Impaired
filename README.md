# Glass-For-Visual-Impaired

This repository contains firmware and a web application for an ESP32-based assistive device designed to help visually impaired individuals. The project includes:

## Folders & Files

- **esp32-wroom.ino**: Main Arduino sketch for the ESP32 device.
- **esp32-vl53l1x-single-test/**: Test code for the VL53L1X distance sensor.
- **esp32-wroom/**: ESP32 firmware, wiring guide, and documentation.
- **website/**: Web application built with Vite, React, Tailwind CSS, and Firebase for device management and data visualization.

## Quick Start

1. **Firmware**: Upload the appropriate `.ino` file to your ESP32 device using the Arduino IDE.
2. **Website**:
   - Navigate to the `website` folder.
   - Run `npm install` to install dependencies.
   - Run `npm run dev` to start the development server.

## Notes
- The `website/.env` file contains sensitive Firebase credentials and is excluded from version control.
- See the `WIRING-GUIDE.md` and `FIRMWARE-EXPLAINED.md` in the `esp32-wroom` folder for hardware setup and firmware details.

---

**Author:** EngrAlegre
