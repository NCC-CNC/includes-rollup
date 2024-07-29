# Includes
Workflow for generating standardized 1km existing conservation layers.

### Source
1. NCC fee simple and conservation agreement lands (current to July 2024)
2. CPCAD terrestrial/freshwater biomes (current to December 2023)

### High-level methods
NCC and CPCAD vector data is filtered, merged and intersected with the 1km standardized vector grid. Intersected data is rasterized into a continuous layer and binary Where To Work include (50% cut-off).

![extent](https://github.com/NCC-CNC/includes-rollup/blob/main/cons.jpg)
