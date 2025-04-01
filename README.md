# TONK

**TONK** is a custom-built game controller project designed for players with a heavy hand. Focused on durability, precision, and low-latency performance, TONK is ideal for those who frequently overpower standard input hardware.

![KiCad](https://img.shields.io/badge/pcb-KiCad-blue)

---

## Project Structure

```dir
TONK/
├── code/       # Firmware and microcontroller logic
├── docs/       # Specs, diagrams, and internal documentation
├── models/     # 3D models and housing designs
├── pcb/        # KiCad project files for PCB design
├── workflows/  # GitHub Actions and project automation
```

---

## Goals

- USB-C wired interface
- Hall Effect thumbsticks
- Linear analog triggers
- 500g tactile buttons
- Modular daughterboards
- Built to survive strong input forces
- Compatible with PC + ReWASD
- Ultra-low latency
- No unnecessary features (gyro, vibration, audio, etc.)

---

## Status

- ✅ Hardware planning in progress
- ✅ Project structure initialized
- ⬜ PCB routing
- ⬜ Shell prototyping
- ⬜ Firmware development

---

## 🛠️ License

This project is primarily licensed under the [MIT License](./LICENSE), which covers all code, documentation, and firmware.

### Hardware + Design Files

The hardware and design assets in this repo are licensed separately:

- 📐 [PCB schematics and board layouts](./docs/LICENSE-PCB.md):
  Licensed under the **CERN Open Hardware License v2 – Weakly Reciprocal (CERN-OHL-W)**

- 🧩 [3D models and mechanical design files](./docs/LICENSE-3D.md):
  Licensed under the **CERN Open Hardware License v2 – Weakly Reciprocal (CERN-OHL-W)**

For third-party libraries and symbol/footprint attribution, see [docs/README.md](./docs/README.md).
