# How to build the Flake?

## Components

To build the flake you need the following materials

| Name                  | Count   | Remarks                                                     |
|:----------------------|:--------|:------------------------------------------------------------|
| PCB                   | 1 set   |                                                             |
| MX hot-swap sockets   | 40/46   |                                                             |
| Choc hot-swap sockets | 40/46   |                                                             |
| Diodes                | 40/46   | 1N4148W SOD-123                                             |
| Switches              | 40/46   | Choc V1/V2 or MX switches                                   |
| Keycaps               | 40/46   | Compatible with your switches                               |
| Controllers           | 2       | Any ProMicro compatible controller (nice!nano for instance) |
| USB-C ports           | 2       | Mid-mount with 6 pins                                       |
| Reset buttons         | 2       | TS-1289VE-4                                                 |
| Enclosure             | 1 set   |                                                             |
| Plates                | 1 set   | Required if you want to use MX switches                     |
| M2 Screws             | 8       | 7mm length (8mm should work too, but will stick out)        |
| M2 Hex nuts           | 8       |                                                             |
| Rubber feats          | 8       | 6x2mm                                                       |
| Battery sockets       | 2       | JST 1.25 with the straight needle                           |
| Batteries             | 2       | 402025 with JST 1.25 (302025 should work too)               |

> If you don't plan to use MX switches, you can skip the plates. If you will be using the keyboard only in wired mode, batteries can be skipped too.

## Build process

The first iterations of the PCB were not designed with ease of hand soldering in mind. It's definitely possible, as I've done one PCB myself, but the process was actually frustrating. I'm currently working on a new version of the PCB that will hopefully be much easier to solder with an iron.

But if you're confident enough in your soldering skills, you should be able to figure out how to assemble the PCB v0.1.1. The advice I can give is to place the 1/4 of the controller's legs into the controller's mounting holes and solder it that way. Using just solder without anything inside resulted in poor pin connections for me.