# Hackclub Solder NixOS with a Maine Coon artwork

## Overview

A simple PCB design project (my first one ever), in the shape of the NixOS logo in purple (best colour), and a maine coon cat design, where the LEDs make up its eyes.

## PCB

![3D view top](3D%20view2%20top-rounded.png)
![3D view bottom](3D%20view2%20bottom-rounded.png)
![PCB design](PCB%20design2-rounded.png)
![Wiring design](Wiring%20design4.png)

## Circuit testing

![Circuit testing](Circuit%20waveform.png)

## Features

- Maine Coon cat design
- LED eyes
- NixOS logo PCB design (open source Linux distro logo)
- 555 timer to make the eyes blink
- Switch to control when it happens
- Photoresistor, so it only glows at night

## How to build

Just order the PCB & components, open up the EasyEDA file, and build it accordingly.

## BOM

| Name | Designator | Footprint | Qty | Manufacturer Part | LCSC Part | Price |
|---|---|---|---|---|---|---|
| 10uF | C1 | CAP-TH_BD5.0-P2.5-D0.5-FD | 1 | KM106M063D11RR0VH2FP0 | C32455 | $0.019 |
| LED-0603_R | LED1, LED2 | LED0603_RED | 2 | 19-217/R6C-AL1M2VY/3T | C72044 | $0.021 |
| 470 | R1, R3 | R_AXIAL-0.6 | 2 | | | |
| 47k | R2 | R_AXIAL-0.6 | 1 | | | |
| 4.7k | R4 | R_AXIAL-0.6 | 1 | | | |
| 3362P-1-103LF 10K Trimmer Bourns | R5 | 3362P_1 | 1 | | | |
| Switch-6x6x10 | SW1 | SW-TH_4P-L6.2-W6.2-P4.50-LS6.5 | 1 | | C71840 | |
| MY-2032-12-R | U1, U2 | BAT-SMD_MY-2032-12 | 2 | MY-2032-12-R | C964834 | $0.184 |
| Photoresistor-5528 | U3 | SNR2-3.0 | 1 | Photoresistor-5528 | | |
| NE555 | U4 | DIP08-KIT | 1 | | | |

---

Made by @maanavnagda2197 on slack  
Made as part of https://solder.hackclub.com
