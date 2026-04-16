# ESP32 Custom PCB — Team Circuitrix

A custom ESP32 PCB designed in KiCad.

## Repository Structure

```
ESP32_custom/       # KiCad schematic and PCB design files
  ├── *.kicad_sch   # Schematic
  ├── *.kicad_pcb   # PCB layout
  ├── *.kicad_pro   # Project file
  ├── *.kicad_dru   # Design rules
  └── Gerber File/  # Manufacturing files (Gerber + drill)
Bill of Materials/  # BOM in CSV and XLSX formats
demo/               # 3D board view video and PCB renders
```

## Demo

| Top View | Bottom View |
|----------|-------------|
| ![Top View](demo/Top%20View.png) | ![Bottom View](demo/Bottom%20View.png) |

A 3D walkthrough of the board is available in [demo/3D view of the Board.mp4](demo/3D%20view%20of%20the%20Board.mp4).

## Reference Datasheets

- [ESP32-WROOM-32E Datasheet](https://www.espressif.com/sites/default/files/documentation/esp32-wroom-32e_esp32-wroom-32ue_datasheet_en.pdf)
- [ESP32-S2-DevKitM-1 Schematic](https://dl.espressif.com/dl/schematics/ESP32-S2-DevKitM-1_V1_Schematics.pdf)
- [ESP32-DevKitC V4 Schematic](https://dl.espressif.com/dl/schematics/esp32_devkitc_v4-sch.pdf)
