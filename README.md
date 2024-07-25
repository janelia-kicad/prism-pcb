- [Repository Info](#orgd71b569)
- [Images](#org1905299)
- [Schematic](#org394e7dc)
- [PCB](#orgc50441d)
- [Bill of Materials](#org4ef8161)
- [Development](#org227fd69)

    <!-- This file is generated automatically from metadata -->
    <!-- File edits may be overwritten! -->


<a id="orgd71b569"></a>

# Repository Info

-   Project Name: prism-pcb
-   Synopsis: PCB for each prism in the Voigts Lab honeycomb maze.
-   Documentation Version: 1.0.0
-   Pcb Version: 1.0
-   Enclosure Version: 1.0
-   Supplemental BOM Version: 1.0
-   Release Date: 2024-07-25
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

![img](./documentation/pcb/pcb.png) ![img](./documentation/pcb/pcb-fan.png)


<a id="org1905299"></a>

# Images

<img src="./documentation/pcb/top.png" width="1920">

<img src="./documentation/pcb/bottom.png" width="1920">

<img src="./documentation/pcb/front.png" width="1920">

<img src="./documentation/pcb/back.png" width="1920">

<img src="./documentation/pcb/left.png" width="1920">

<img src="./documentation/pcb/right.png" width="1920">


<a id="org394e7dc"></a>

# Schematic

[./documentation/schematic/prism-pcb.pdf](./documentation/schematic/prism-pcb.pdf)

<img src="./documentation/schematic/prism-pcb.svg" width="1920">

<img src="./documentation/schematic/prism-pcb-assembly.svg" width="1920">

<img src="./documentation/schematic/prism-pcb-interface.svg" width="1920">

<img src="./documentation/schematic/prism-pcb-tmc5130.svg" width="1920">


<a id="orgc50441d"></a>

# PCB

<img src="./documentation/pcb/prism-pcb-User_Drawings.svg" width="1920">

<img src="./documentation/pcb/prism-pcb-F_Silkscreen.svg" width="1920">

<img src="./documentation/pcb/prism-pcb-B_Silkscreen.svg" width="1920">

<img src="./documentation/pcb/prism-pcb-F_Fab.svg" width="1920">

<img src="./documentation/pcb/prism-pcb-B_Fab.svg" width="1920">


<a id="org4ef8161"></a>

# Bill of Materials


## Board

| Item | Synopsis                          | Manufacturer Part Number | Manufacturer                         | Quantity | Reference(s)                  | Package         |
|---- |--------------------------------- |------------------------ |------------------------------------ |-------- |----------------------------- |--------------- |
| 1    | 50V 3.3uF                         | FS32X335K500EGG          | PSA(Prosperity Dielectrics)          | 1        | C301                          | 1210            |
| 2    | CAP CER 0.1UF 100V X5R            | GRM155R62A104KE14D       | Murata Electronics                   | 6        | C302 C401 C403 C404 C407 C410 | 0402            |
| 3    | CAP CER 1UF 25V X5R               | GRT155R61E105KE01D       | Murata Electronics                   | 2        | C303 C304                     | 0402            |
| 4    | CAP CER 0.022UF 100V X7R          | GCM188R72A223KA37D       | Murata Electronics                   | 1        | C402                          | 0603            |
| 5    | CAP CER 0.47UF 35V X5R            | GRT155R6YA474KE01D       | Murata Electronics                   | 1        | C405                          | 0402            |
| 6    | CAP CER 2.2UF 35V X5R             | C1005X5R1V225K050BC      | TDK Corporation                      | 1        | C406                          | 0402            |
| 7    | CAP CER 2.2UF 100V X7T 0805       | GRM21BD72A225KE01L       | Murata Electronics                   | 2        | C408 C411                     | 0805            |
| 8    | CAP ALUM 100UF 20% 50V SMD        | EEEHAH101UAP             | Panasonic Electronic Components      | 2        | C409 C412                     | SMD D8xL10.2mm  |
| 9    | CONN FFC FPC BOTTOM 10POS 1MM RA  | 1.0K-FX-10PWBG           | HDGC                                 | 1        | J301                          | SMD P=1mm       |
| 10   | CONN HEADER SMD R/A 4POS 1.5MM    | 0874380443               | Molex                                | 1        | J401                          | SMD             |
| 11   | RES SMD 100 OHM 1% 62.5mW         | 0402WGF1000TCE           | UNI-ROYAL(Uniroyal Elec)             | 1        | R301                          | 0402            |
| 12   | RES SMD 2.2 OHM 5% 1/10W          | ERJ-2GEJ2R2X             | Panasonic Electronic Components      | 1        | R401                          | 0402            |
| 13   | 0.12 750mW Current Sense Resistor | KRL1632E-M-R120-F-T5     | SUSUMU                               | 2        | R402 R403                     | 1206            |
| 14   | DC-DC 5V 600mA Output 3-65V Input | TPSM365R6V5RDNR          | Texas Instruments                    | 1        | U301                          | QFN-11(3.5x4.5) |
| 15   | IC MTR DRV BIPOLAR 5.5-46V        | TMC5130A-TA              | Analog Devices Inc./Maxim Integrated | 1        | U401                          | TQFP-48-EP(7x7) |
| 16   | XTAL OSC XO 16.0000MHZ HCMOS SMD  | ECS-2520S33-160-FN-TR    | ECS Inc.                             | 1        | X401                          | SMD2520-4P      |


## Supplemental

| Item | Synopsis                               | Manufacturer Part Number | Manufacturer        | Quantity | Cost  | Total |
|---- |-------------------------------------- |------------------------ |------------------- |-------- |----- |----- |
| 1    | CABLE FFC/FPC 10POS 1MM 12IN           | Molex                    | 0152670265          | 1        | 2.27  | 2.27  |
| 2    | FAN AXIAL 25X8MM 5VDC WIRE             | 255M                     | ebm-papst Inc.      | 1        | 33.47 | 33.47 |
| 3    | Hex Standoff Threaded M2 Brass 12.00mm | 970120244                | Würth Elektronik    | 3        | 0.71  | 2.13  |
| 4    | MACH SCREW PAN HEAD PHILLIPS M2 12mm   | MPMS 002 0012 PH         | B&F Fastener Supply | 3        | 0.32  | 0.96  |
| 5    | MACH SCREW PAN HEAD PHILLIPS M2 5mm    | MPMS 002 0005 PH         | B&F Fastener Supply | 3        | 0.17  | 0.51  |
|      | Supplemental BOM Version: 1.0          |                          |                     |          | Total | 39.34 |


<a id="org227fd69"></a>

# Development


## Install Guix

[Install Guix](https://guix.gnu.org/manual/en/html_node/Binary-Installation.html)


## Generate Output from KiCad


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


### Drill and Map Files

Output directory: ../documentation/fabrication/gerbers

Options:

-   Excellon drill file format
-   Check Use alternate drill mode for "Oval Holes Drill Mode".
-   Check Absolute for "Drill Origin".
-   Check Millimeters for "Drill Units".
-   Check Decimal format for "Zeros Format".
-   Gerber X2 map file format

Zip gerber files

    zip gerbers.zip gerbers/*


### BOM

Generate BOM from schematic editor using blank command line to create bom xml file.


### POS

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


## Edit metadata.org

    make metadata-edits


## Tangle metadata.org

    make metadata


## Edit project

    make kicad-edits
    exit
