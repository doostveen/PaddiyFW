# PadDIY Leak Tester Firmware Updates

This is the official changelog for the PadDIY Leak Tester firmware.

---

## 🔧 26176 — Fixes & Improvements
- **FIX**: The new pressure sensors v3.2 were not detected.
  The firmware now scans the entire I²C bus instead of using hard‑coded sensor addresses.

---

## 🔧 26148 — Stability Improvements
- **FIX**: Pump sometimes failed to start due to slow PWM ramp‑up.  
- **ADD**: MAC address is now displayed on startup in the serial console.

---

## 🔧 26054 — Enhancements
- **ADD**: Menu option to enable or disable Bluetooth.  
- **ADD**: Companion device always plays audio when connected.  
- **IMPROVED**: Flow percentage now resets instantly.

---

## 🔧 26034 — Enhancements & Fixes
- **ADD**: During measurement, the rotary knob now adjusts the audio threshold percentage.  
- **FIX**: Improved BLE detection.  
  Device names now always start with `Paddiy_` and include a random suffix.


