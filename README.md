# KiCAD STM32F0 Nixie Tube Clock

This repository contains the design files and assembly files for my nixie tube
clock design. The code (firmware) can be located at
<https://github.com/bdebyl/stm32-nixieclock>

The assembly files and docs are kept up to date to the best of my abilities.

![Nixie tube clock](img/nixieclock.png)

## Requirements

To use these design files you will require KiCAD >= 5.99.0, or simply build and
install the latest KiCAD from their git repository.

Additionally, you will need my library files for proper viewing, and
modification of the symbols, footprints, and viewing of 3D models:

Import these as either project or global libraries when opening the KiCAD
project.

- [kicad-footprints](https://github.com/bdebyl/kicad-footprints/tree/bdebyl) @
  >= `24aded49`
- [kicad-symbols](https://github.com/bdebyl/kicad-symbols/tree/bdebyl) @ >=
  `2f7d2fdd`
- [kicad-packages3D](https://github.com/bdebyl/kicad-packages3D/tree/bdebyl) @
  >= `60a787a1`

