- [Repository Info](#orge166407)
- [Images](#org110d773)
- [Schematic](#org8bf05d7)
- [PCB](#orgaf4de01)
- [Bill of Materials](#org7a509b2)
- [Development](#orgef895d0)

    <!-- This file is generated automatically from metadata -->
    <!-- File edits may be overwritten! -->


<a id="orge166407"></a>

# Repository Info

-   Project Name: prism-pcb
-   Synopsis: PCB for each prism in the Voigts Lab honeycomb maze.
-   Documentation Version: 2.1.0
-   Pcb Version: 2.1
-   Enclosure Version: 1.0
-   Supplemental BOM Version: 2.1.0
-   Release Date: 2024-10-22
-   Creation Date: 2024-06-27
-   Kicad Version: 7.0.11
-   License: BSD-3-Clause
-   URL: <https://github.com/janelia-kicad/prism-pcb>
-   Author: Peter Polidoro
-   Email: peter@polidoro.io
-   Copyright: 2024 Howard Hughes Medical Institute
-   References:
    -   [cluster-pcb](https://github.com/janelia-kicad/cluster-pcb)
    -   [TMC5130](https://www.analog.com/en/products/tmc5130.html)

![img](./documentation/pcb/pcb.png)


<a id="org110d773"></a>

# Images

<img src="./documentation/pcb/top.png" width="1920">

<img src="./documentation/pcb/bottom.png" width="1920">

<img src="./documentation/pcb/front.png" width="1920">

<img src="./documentation/pcb/back.png" width="1920">

<img src="./documentation/pcb/left.png" width="1920">

<img src="./documentation/pcb/right.png" width="1920">


<a id="org8bf05d7"></a>

# Schematic

[./documentation/schematic/prism-pcb.pdf](./documentation/schematic/prism-pcb.pdf)

<img src="./documentation/schematic/prism-pcb.svg" width="1920">

<img src="./documentation/schematic/prism-pcb-assembly.svg" width="1920">

<img src="./documentation/schematic/prism-pcb-interface.svg" width="1920">

<img src="./documentation/schematic/prism-pcb-tmc5130.svg" width="1920">


<a id="orgaf4de01"></a>

# PCB

<img src="./documentation/pcb/prism-pcb-User_Drawings.svg" width="1920">

<img src="./documentation/pcb/prism-pcb-F_Silkscreen.svg" width="1920">

<img src="./documentation/pcb/prism-pcb-B_Silkscreen.svg" width="1920">

<img src="./documentation/pcb/prism-pcb-F_Fab.svg" width="1920">

<img src="./documentation/pcb/prism-pcb-B_Fab.svg" width="1920">


<a id="org7a509b2"></a>

# Bill of Materials


## Board

| Item | Synopsis                          | Manufacturer Part Number | Manufacturer                         | Quantity | Reference(s)                            | Package          |
|---- |--------------------------------- |------------------------ |------------------------------------ |-------- |--------------------------------------- |---------------- |
| 1    | 50V 3.3uF                         | FS32X335K500EGG          | PSA(Prosperity Dielectrics)          | 1        | C301                                    | 1210             |
| 2    | CAP CER 0.1UF 100V X5R            | GRM155R62A104KE14D       | Murata Electronics                   | 8        | C302 C306 C307 C401 C403 C404 C407 C410 | 0402             |
| 3    | CAP CER 1UF 25V X5R               | GRT155R61E105KE01D       | Murata Electronics                   | 2        | C303 C304                               | 0402             |
| 4    | CAP CER 47UF 10V X5R              | CGA0805X5R476M100MT      | HRE                                  | 2        | C305 C406                               | 0805             |
| 5    | CAP CER 27pF 50V 5%               | 0402CG270J500NT          | FH (Guangdong Fenghua Advanced Tech) | 1        | C308                                    | 0402             |
| 6    | CAP CER 0.022UF 100V X7R          | GCM188R72A223KA37D       | Murata Electronics                   | 1        | C402                                    | 0603             |
| 7    | CAP CER 0.47UF 35V X5R            | GRT155R6YA474KE01D       | Murata Electronics                   | 1        | C405                                    | 0402             |
| 8    | CAP CER 2.2UF 100V X7T 0805       | GRM21BD72A225KE01L       | Murata Electronics                   | 2        | C408 C411                               | 0805             |
| 9    | CAP ALUM 100UF 20% 50V SMD        | EEEHAH101UAP             | Panasonic Electronic Components      | 2        | C409 C412                               | SMD D8xL10.2mm   |
| 10   | LED RED CLEAR CHIP SMD            | APHHS1005SURCK           | Kingbright                           | 1        | D301                                    | 0402             |
| 11   | DIODE GEN PURP 200V 2A            | ES2D                     | GOODWORK                             | 1        | D302                                    | SMA(DO-214AC)    |
| 12   | CMC 22UH 200MA 2LN 1.2KOHM SMD    | ACT45B-220-2P-TL003      | TDK                                  | 1        | FL301                                   | 1812             |
| 13   | USB Type-C 2.0 16P 5A             | GT-USB-7047C             | G-Switch                             | 1        | J301                                    | SMD              |
| 14   | CONN HEADER SMD R/A 4POS 1.5MM    | 0874380443               | Molex                                | 1        | J401                                    | SMD              |
| 15   | RES SMD 100 OHM 1% 62.5mW         | 0402WGF1000TCE           | UNI-ROYAL(Uniroyal Elec)             | 1        | R301                                    | 0402             |
| 16   | RA73F 2A 2K32 0.1% 5K RL          | RA73F2A2K32BTD           | TE Connectivity Passive Product      | 1        | R302                                    | 0805             |
| 17   | RES SMD 1.4K OHM 1% 62.5mW        | RC0402FR-071K4L          | YAGEO                                | 1        | R303                                    | 0402             |
| 18   | RES SMD 604 OHM 1% 100mW          | ERJ2RKF6040X             | PANASONIC                            | 1        | R304                                    | 0402             |
| 19   | RES SMD 1.8K OHM 5% 100mW         | ERJ2GEJ182X              | PANASONIC                            | 1        | R305                                    | 0402             |
| 20   | RES SMD 10 OHM 1% 62.5mW          | RC0402FR-0710RL          | YAGEO                                | 1        | R401                                    | 0402             |
| 21   | 0.12 750mW Current Sense Resistor | KRL1632E-M-R120-F-T5     | SUSUMU                               | 2        | R402 R403                               | 1206             |
| 22   | Pulse Transformer 120uH 1CT:1CT   | FB020G00                 | Dongguan Mentech Optical & Magnetic  | 1        | TR301                                   | SMD-6P 3.5x3.2mm |
| 23   | DC-DC 5V 600mA Output 3-65V Input | TPSM365R6V5RDNR          | Texas Instruments                    | 1        | U301                                    | QFN-11(3.5x4.5)  |
| 24   | SPI Isolator                      | LTC6820HMS#3ZZTRPBF      | Analog Devices                       | 1        | U302                                    | MSOP-16          |
| 25   | IC MTR DRV BIPOLAR 5.5-46V        | TMC5130A-TA              | Analog Devices Inc./Maxim Integrated | 1        | U401                                    | TQFP-48-EP(7x7)  |
| 26   | XTAL OSC XO 16MHZ 5V SMD          | S5D16.000000A20F30T      | Shenzhen SCTF Elec                   | 1        | X401                                    | SMD5032-4P       |


## Supplemental

| Item | Synopsis                           | Manufacturer Part Number | Manufacturer     | Quantity | Cost  | Total |
|---- |---------------------------------- |------------------------ |---------------- |-------- |----- |----- |
| 1    | USB 2.0 C Male to C Male 150mm     | DH-20UE0062-NH           | Cvilux USA       | 1        | 4.75  | 4.75  |
| 2    | USB 2.0 C Male to C Male 1m        | DH-20UE0063-NH           | Cvilux USA       | 1        | 5.74  | 5.74  |
| 3    | M3 Hex Standoff Male Female 10x5mm | 971100354                | Würth Elektronik | 4        | 0.63  | 2.52  |
| 4    | M3 Machine Screw 6mm               | RM3X6MM 2701             | APM Hexseal      | 4        | 0.58  | 2.32  |
| 5    | Supplemental BOM Version: 2.1.0    |                          |                  |          | Total | 15.33 |


<a id="orgef895d0"></a>

# Development


## Install Guix

[Install Guix](https://guix.gnu.org/manual/en/html_node/Binary-Installation.html)


## Generate Output from KiCad


### Remove previous versions

```sh
rm -rf ./documentation/3dmodels/* && rm -rf ./documentation/bom/* && rm -rf ./documentation/fabrication/* && rm -rf ./documentation/pcb/* && rm -rf ./documentation/schematic/*pcb
```


### Images

1.  3D Viewer

    Output directory: ../documentation/pcb
    
    -   pcb.png
    -   top.png
    -   bottom.png
    -   front.png
    -   back.png
    -   left.png
    -   right.png

2.  Trim

        make trimmed-images

3.  Schematic PDF

    File -> Plot
    
    Output directory: ../documentation/schematic
    
    Plot All Pages
    
    -   Output format PDF
    -   Page Size = Schematic size
    -   Plot drawing sheet
    -   Output mode = Color
    -   Color theme = KiCad Default
    -   Default line width = 0.006 in

4.  Schematic SVG

    File -> Plot
    
    Output directory: ../documentation/schematic
    
    Plot All Pages
    
    -   Output format SVG
    -   Page Size = Schematic size
    -   Plot drawing sheet
    -   Output mode = Color
    -   Color theme = Solarized Light
    -   Default line width = 0.012 in

5.  PCB SVG

    Add Edge.Cuts, holes, and dimensions to User.Drawings
    
    File -> Plot
    
    Output directory: ../documentation/pcb
    
    -   Plot format SVG
    -   Include Layers
        -   User.Drawings
        -   F.Silkscreen
        -   B.Silkscreen
        -   F.Fab
        -   B.Fab
    -   Plot on All Layers
        -   Edge.Cuts
    -   Plot footprint values
    -   Plot reference designators
    -   SVG Options
        -   Precision = 4
        -   Output mode = color
    
        make cropped-svg


### Fabrication Files

1.  Gerbers

    File -> Fabrication Outputs -> Gerbers (.gbr)
    
    Output directory: ../documentation/fabrication/gerbers
    
    Include Layers:
    
    -   F.Cu
    -   F.Paste
    -   F.Silks
    -   F.Mask
    -   F.Fab
    -   B.Cu
    -   B.Paste
    -   B.Silks
    -   B.Mask
    -   B.Fab
    -   Edge.Cuts - (contain the board outline/cutouts.)
    -   In1.Cu, In2.Cu … - (needed for 4/6 layer designs.)
    
    Options:
    
    -   Select Plot reference designators, otherwise designators will not appear on silkscreen layers.
    -   Select Check zone fills before plotting
    -   Select Use Protel filename extensions, this is recommended as JLCPCB prefers Protel filename extensions.
    -   Select Subtract soldermask from silkscreen, this ensures no silkscreen on pads.
    -   Coordinate format 4.6 unit mm

2.  Drill and Map Files

    Output directory: ../documentation/fabrication/gerbers
    
    Options:
    
    -   Excellon drill file format
    -   Check Use alternate drill mode for "Oval Holes Drill Mode".
    -   Check Absolute for "Drill Origin".
    -   Check Millimeters for "Drill Units".
    -   Check Decimal format for "Zeros Format".
    -   Gerber X2 map file format
    
    Zip gerber files
    
        zip ./documentation/fabrication/gerbers.zip ./documentation/fabrication/gerbers/*

3.  BOM

    Generate BOM from schematic editor using blank command line to create bom xml file.

4.  POS

    File -> Fabrication Outputs -> Component Placement (.pos)
    
    Output directory: ../documentation/fabrication/
    
    Settings:
    
    -   Format = CSV
    -   Units = Millimeters
    -   Files = Single file for board
    -   Do not use drill/place file origin
    
    Modify pos files:
    
    -   Ref -> Designator
    -   PosX -> Mid X
    -   PosY -> Mid Y
    -   Rot -> Rotation
    -   Side -> Layer

5.  Step

    File -> Export -> Step
    
    Output directory: ../documentation/3dmodels/pcb.step
    
    -   Drill/place file origin
    -   Overwrite old file
    -   Standard Board outline chaining tolerance


## Edit metadata.org

    make metadata-edits


## Tangle metadata.org

    make metadata


## Edit project

    make kicad-edits
    exit
