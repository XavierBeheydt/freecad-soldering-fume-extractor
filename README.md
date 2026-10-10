# Soldering Fume Extractor

Personal project to design a 3D-printable USB soldering fume extractor in
FreeCAD: a fan housing powered over USB, with a rotary knob to adjust the fan
speed, that pulls solder fumes away from the work area.

<!--
  If this is a remake or remix, credit the original here, e.g.:

  This is a remake of [Model title](https://www.printables.com/model/...)
  by Author on Printables, redrawn from scratch in FreeCAD.
-->

## Project structure

```
cad/                     # FreeCAD source file (.FCStd)

exports/                 # 3MF exports for slicing and printing
├── project.3mf          # full assembly
└── project-Part.3mf     # one file per part

images/                  # renders, slicer screenshots and print photos
```

## Bill of materials

| Part | Specification | Source |
|---|---|---|
| Fan | 120 × 120 × 25 mm | [AliExpress](https://fr.aliexpress.com/item/1005007346540421.html) |

## Design

<!-- TODO: how the part is shaped and why (fan size, filter, knob/PWM controller placement). -->

| | |
|---|---|
| ![Isometric render](images/render-iso.png) | ![Slicer view](images/slicer.png) |

## Final print

<!-- TODO: how it was printed and validated. -->

| | |
|---|---|
| ![Print photo](images/print-1.png) | ![Print photo](images/print-2.png) |

## Status

Work in progress.
