This repo serves as the configuration backup (./printer_data/config) for Voron 2.5511 and Box Turtle BT-108. While this repo is public and you are free to pull configurations and macros to use for your own printer, please proceed at your own risk when doing so as it applies specifically to my printer. Not every printer, even ones that are built with the same specifications, share the same configuration.

![Voron 2.5511 and Box Turtle BT-108](https://skyperspectivemedia.com/wp-content/uploads/2025/02/IMG_1307.jpg)

The configuration files used on this Voron 2.4 has the following specifications/modifications:

**Hardware:**

- LDO Motors Voron 2.4R2 Rev C 350mm kit
  - Voron Stealthburner toolhead
    - Clockwork 2 extruder
    - FilamAtrix filament cutter (single pre-extruder sensor)
    - Phaetus Rapido HF hotend
    - BTT SB2209 CAN Bus toolhead board (can0 via Octopus RJ11 USB-CAN Bridge)
    - CNC aluminum Cartographer toolhead carriage
    - Cartographer induction probe (can0 via SB2209 CAN output)
  - BTT Octopus v1.1 MCU with BTT TMC2209 stepper drivers (sensorless homing)
  - BTT U2C v2.1 USB CAN adapter (can1)
  - Raspberry Pi 5 host
  - Logitech C920 webcam
  - Fysetc Blobifier filament purge waste system (servo and sensors connected to BLTouch header)
  - 3mm ACM side, top, and rear panels with 80mil (2mm) butyl rubber sound deadening insulation liner
  - LDO Motors Clicky Clacky fridge door with magnetic latches
  - 'The Filter' bed recirculation fans (center and right side units only)
  - Voxel HULA anti-vibration printer feet
 
- LDO Motors Box Turtle AFC kit (Batch 2 with AFC Lite v1.1 MCU, can1 via U2C)
  - Standard TN buffer (JST connector mod)
  - SB2209/2240 CAN toolhead cable with CNLinko LP-12 bulkhead connector

**Software:**

- [Kalico fork Klipper firmware](https://github.com/KalicoCrew/kalico) 
- [AFC Klipper Add-On](https://github.com/ArmoredTurtle/AFC-Klipper-Add-On)
- [Cartographer Klipper Add-On](https://github.com/Cartographer3D/cartographer-klipper)

[Discord](https://discordapp.com/users/152998269113466881)
