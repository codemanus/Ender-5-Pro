# ZeroG Mercury One.1
Klipper configurations and overall mods to the Stock Ender 5 Pro for the ZeroG Mercury One.1 conversion

## Current Mods
| Mod      | Product | Link     |
| :--- | :----: | ---: |
| Hotend:| Traingle Lab/Phaetus Rapido HF      |  [West3D](https://west3d.com/products/rapido-hot-end-high-flow-tl-phaetus?_pos=9&_sid=5dd5e8355&_ss=r)|
| Extruder: | LDO Oribiter v2.0 | [West3D](https://west3d.com/products/ldo-orbiter-extruder-v2-0) | 
| Mainboard | BTT Ocotpus v1.1 | [KB-3D](https://kb-3d.com/store/controllers-displays-drivers/783-bigtreetech-octopus-controller-main-board-v11-1674341175490.html) |
| Motor Drivers: | BTT TMC2209 v1.3 | [KB-3D](https://kb-3d.com/store/controllers-displays-drivers/785-bigtreetech-tmc2209-stepper-motor-driver-v13-1674350131784.html) |
| CANBus Toolhead: | BTT EBB36 | [KB-3D](https://kb-3d.com/store/controllers-displays-drivers/787-7680-bigtreetech-ebb36-ebb42-v12-can-bus-expansion-board-multiple-styles-1674360588875.html#/922-bttmodel-ebb36) |
| CANBus USB Adapter: | BTT U2C v2.1 | [KB-3D](https://kb-3d.com/store/controllers-displays-drivers/788-bigtreetech-u2c-v21-usb-to-can-bus-adapter-pcb-1674401555972.html)  |
| CAN Cabling: | Linneo CAN Harness w/ MOLEX| [KB-3D](https://kb-3d.com/store/wiring-connectors/809-linneo-fep-can-tool-head-wire-harness-molex-1677347067992.html)|
| Conversion Kit: | ZeroG Mercury One w/SS Rails| [Fabreeko](https://www.fabreeko.com/collections/zero-g/products/mercury-one-kit?variant=42031744614655) |
| Probe: | Klicky | Self-Sourced BOM: [Github](https://github.com/jlas1/Klicky-Probe) |
| Bed: | Spring steel PEI Sheet 235mmx235mm    |  [Amazon](https://www.amazon.com/dp/B0BRCRX6T9?psc=1&ref=ppx_yo2ov_dt_b_product_details)|
| Reverse Bowden setup: | Capricorn Bowden PTFE Tubing 1M XS Series| [Amazon](https://www.amazon.com/Creality-Capricorn-Filament-Pneumatic-Fittings/dp/B086YPDHMF/ref=sr_1_4?keywords=capricorn+bowden+tubing&s=industrial&sr=1-4) |

## Printed Mods
| Mod      | Description | Link     |
| :--- | :----: | ---: |
| Printed Bed Supports:| Bed reinforcement brackets for the Ender 5 and Ender 5 Pro in order to reduce vibrations and make the bed more stable.  | [Printables](https://www.printables.com/model/309847-bed-supports-ender-5-ender-5-pro)|
| Ender 5 Pro Front bar relocation:| Better clearance to get to the bed than the original allowed. This bolts into place using the same factory bolts and the result is a square corner. | [Thingiverse](https://www.thingiverse.com/thing:4573655)|

# Hydra Conversion  Collected parts to date - 04-27-2023

### Bolts

#### Self sourcing bolts

| Size  | Type                              | Amount |                         Sourced?                          |
|:------|:----------------------------------|:------:|:-------------------------------------------------------:|
| M3X6  | <nobr>ISO 10642 / DIN 7991</nobr> |   6    | :white_check_mark: |
| M3X8  | <nobr>ISO 4762 / DIN 912</nobr>   |   85   | :white_check_mark: |
| M3X10 | <nobr>ISO 4762 / DIN 912</nobr>   |   3    | :white_check_mark: |
| M4X16 | <nobr>ISO 4762 / DIN 912</nobr>   |   3    | :white_check_mark: |
| M5X8  | <nobr>ISO 7380 / DIN 7380</nobr>  |   4    | :white_check_mark: |
| M5X10 | <nobr>ISO 4762 / DIN 912</nobr>   |   18   | :white_check_mark: |

### T-Nuts

| Size | Type                               | Amount |                            Sourced?                            |
|:-----|:-----------------------------------|:------:|:------------------------------------------------------------:|
| M3   | <nobr>Roll in spring loaded</nobr> |   24   | :white_check_mark: |
| M5   | <nobr>Roll in spring loaded</nobr> |   22   | :white_check_mark: |

### Extrusion

| Printer       | Size  | Type                        | Amount |                            Sourced?                             |
|:--------------|:------|:----------------------------|:------:|:------------------------------------------------------------:|
| Ender 5 (Pro) | 400mm | <nobr>2020 Extrusion</nobr> |   1    | :white_check_mark: |

### Linear rails

| Printer       | Size  | Type                                 | Amount |                          Sourced?                            |
|:--------------|:------|:-------------------------------------|:------:|:---------------------------------------------------------:|
| X             | 100mm | <nobr>MGN9C</nobr>                   |   3    | :white_large_square: |
| Ender 5 (Pro) | 400mm | <nobr>MGN12C <b>OR</b> MGN12H</nobr> |   3    | :white_large_square: |

### Leadscrew

| Printer       | Size Range    | Type                       | Amount |                           Sourced?                             |
|:--------------|:--------------|:---------------------------|:------:|:-----------------------------------------------------------:|
| Ender 5 (Pro) | 350mm / 370mm | <nobr>TR8 Leadscrew</nobr> |   3    | :white_large_square: |

### Magnet

| Size             | Type                                                                    | Amount |                            Sourced?                             |
|:-----------------|:------------------------------------------------------------------------|:------:|:------------------------------------------------------------:|
| 12x5mm or 12x4mm | <nobr>4mm hole Neodymium</nobr><br><nobr>Countersunk Ring Magnet</nobr> |   3    | :white_check_mark: |

### Bed

| Printer       | Size          | Type                           | Amount |                          Sourced?                           |
|:--------------|:--------------|:-------------------------------|:------:|:--------------------------------------------------------:|
| Ender 5 (Pro) | 255/275mm     | <nobr>Bed heater</nobr>        |   1    | :white_check_mark: |
| Ender 5 (Pro) | 255/275mm     | <nobr>Aluminum bed</nobr>      |   1    | :white_check_mark: |
| X             | Case specific | <nobr>Solid State Relay</nobr> |   1    |  :white_large_square:   |

### Misc

| Size                          | Type                                                             | Amount |                              Sourced?                                |
|:------------------------------|:-----------------------------------------------------------------|:------:|:-----------------------------------------------------------------:|
| 2020                          | <nobr>2020 Corner bracket</nobr>                                 |   2    | :white_large_square: |
| <nobr>M3 X D5.0 X L4.0</nobr> | Heatset insert                                                   |   39   |  :white_check_mark:  |
| M3 Washer                     | <nobr>Normal grade A M3 </nobr><br><nobr>Stainless Steel </nobr> |   12   |  :white_check_mark:  |
| M4 X 8 X L8                   | Spacer                                                           |   3    |   :white_check_mark:   |
| 10mm M4                       | Kossel ball                                                      |   3    |  :white_check_mark: |
| 10x11mm - 1 Meter             | R18 Drag chain                                                   |   1    | :white_large_square:  |
| Nema17                        | Stepper motor                                                    |   3    | :white_large_square:   |
| 5mm-8mm                       | Shaft Coupling                                                   |   3    |  :white_large_square:  |
| OPTIONAL                      | Oldham Coupling                                                  |   3    | :white_large_square: |