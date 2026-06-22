# Contributing to qabd

Thanks for your interest. The project is in early development —
contributions of any kind are welcome.

## Ways to contribute

- **Hardware** — improvements to the KiCad schematics or PCB layout,
  alternative electrode configurations, enclosure designs in FreeCAD
- **Firmware** — Zig code for ESP32-S3: ADC sampling, I2C drivers,
  USB-HID, serial protocol
- **Host** — signal filtering, gesture classification, HID output,
  Unity/OpenXR integration
- **zig-emg** — the standalone EMG processing library is the most
  impactful place to contribute if you know Zig

## Getting started

1. Open an issue describing what you want to work on
2. Wait for a response before writing large amounts of code —
   the architecture is still evolving
3. Fork, branch, implement, open a pull request

## Code style

- Zig: follow the standard library conventions, `zig fmt` before committing
- Hardware: KiCad 8+, include both schematic and layout
- Commit messages: short imperative summary, present tense

## Questions

Open a Discussion on GitHub. No Discord yet.
