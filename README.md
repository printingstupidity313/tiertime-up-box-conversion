# Tiertime UP Box Plus — Modified Builds

Documentation for two modified Tiertime UP Box Plus 3D printers, retrofitted with upgraded electronics and hotends.

## Overview

The stock Tiertime UP Box Plus ships with proprietary control boards and hotends that limit compatibility with open-source firmware and slicers. Both units in this repo have been retrofitted with Fly D5 (Mellow) motherboards and Ender 3 hotends to enable standard Marlin firmware and full OctoPrint control, while keeping the original stepper motors.

## The Two Builds

| | [Printer 1](./printer-1-256-plate) | [Printer 2](./printer-2-original-plate) |
|---|---|---|
| Build plate | Modified, 256x256 | Original (stock size) |
| Motherboard | Fly D5 | Fly D5 |
| Hotend | Ender 3 | Ender 3 |
| Steppers | Original | Original |
| Host / OctoPrint | RASPBERRY PI ZERO W| GALAXY S9+ |

## Repo Structure

- [`printer-1-256-plate/`](./printer-1-256-plate) — full build docs for the 256x256 unit
- [`printer-2-original-plate/`](./printer-2-original-plate) — full build docs for the original-plate unit
- [`shared/`](./shared) — wiring, BOM, and mods common to both printers

## Why

Notes here on the motivation for these builds — reviving old hardware, cost vs buying new, etc. *(fill in your own context)*

## License

*(add your preferred license)*
