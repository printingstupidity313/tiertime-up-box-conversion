# Printer 1 — 256x256 Build Plate

Modified Tiertime UP Box Plus with an upgraded 256x256 build plate.

## Specs

| Component | Spec |
|---|---|
| Base printer | Tiertime UP Box Plus |
| Build plate | Modified, 256x256mm |
| Motherboard | Fly D5 (Mellow) |
| Hotend | Ender 3 |
| Stepper motors | Original (stock) |
| Host / mainsail | raspberry pi zero |
## Modifications from Stock

- **Build plate:** replaced/modified to 256x256mm *(add details: mounting changes, leveling, bed surface used)*
- **Motherboard:** swapped stock control board for Fly D5, enabling Marlin firmware
- **Hotend:** replaced stock hotend with Ender 3 hotend *(note mount/adapter used, if any)*
- **Steppers:** kept original motors — *(note any driver current tuning required for Fly D5)*

## Firmware

See [`firmware/`](./firmware) for the Marlin build/config used on the Fly D5.

## OctoPrint Setup (Galaxy S9+)

See [`octoprint-setup.md`](./octoprint-setup.md) for how OctoPrint is running on the Galaxy S9+.

## Known Issues / Notes

*(fill in — bed leveling quirks, wiring gotchas, firmware limitations, etc.)*
