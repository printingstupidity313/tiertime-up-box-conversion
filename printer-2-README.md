# Printer 2 — Original Build Plate

Tiertime UP Box Plus with the original stock build plate, retrofitted electronics.

## Specs

| Component | Spec |
|---|---|
| Base printer | Tiertime UP Box Plus |
| Build plate | Original (stock size) |
| Motherboard | Fly D5 (Mellow) |
| Hotend | Ender 3 |
| Stepper motors | Original (stock) |
| Host / OctoPrint | Raspberry Pi Zero |

## Modifications from Stock

- **Motherboard:** swapped stock control board for Fly D5, enabling Marlin firmware
- **Hotend:** replaced stock hotend with Ender 3 hotend *(note mount/adapter used, if any)*
- **Steppers:** kept original motors — *(note any driver current tuning required for Fly D5)*
- **Build plate:** unmodified, stock size

## Firmware

See [`firmware/`](./firmware) for the Marlin build/config used on the Fly D5.

## OctoPrint Setup (Raspberry Pi Zero)

See [`octoprint-setup.md`](./octoprint-setup.md) for how OctoPrint is running on the Pi Zero (image used, performance notes since the Zero is fairly limited).

## Known Issues / Notes

*(fill in — Pi Zero performance/streaming limitations, wiring gotchas, firmware limitations, etc.)*
