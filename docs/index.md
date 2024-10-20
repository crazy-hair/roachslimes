---
title: Main Page
nav_order: 0
---

# roachslimes

A utilitarian tracker design for [SlimeVR](https://docs.slimevr.dev/), with the intention of using the cheapest parts available in the smallest form factor possible, while maintaining quality and usability.

<video src="videos/floatybouncy_mobo.mp4" width="512" height="512" autoplay loop muted></video>

## Printing Instructions

The print files, STLs, and Fusion source files are included in the `/3D Files/` directory. I highly recommend using the `.3mf` print files as a basis for your print, as there are manually painted supports and custom settings per object (there's one `.3mf` for PrusaSlicer and friends and one for OrcaSlicer and friends).

## Firmware

Firmware is pretty straightforward, though I did have an issue with the Butterscotch builder/installer - battery sense would always show 100 percent. Therefore, if you want all features to work, I'd recommend building it yourself - PlatformIO Tools for Visual Studio Code make it super easy. If you're compiling yourself, all you have to do is uncomment out `BATTERY_SHIELD_RESISTANCE 180` in `defines.h`, set `USE_6_AXIS false` in `debug.h`, and and change `BMI160_MAG_TYPE BMI160_MAG_TYPE_HMC` to `BMI160_MAG_TYPE BMI160_MAG_TYPE_QMC`in `defines_bmi160.h`. If that makes no sense to you, I've included compiled firmware in the releases section. 

## Gallery

![pcb_design](Images/mobo_front_small.png)![pcb_design](Images/mobo_back_small.png)

![pcb_design](Images/mobo_0.png)![pcb_design](Images/mobo_1.png)

![pcb_design](Images/mobo_2.png)![pcb_design](Images/mobo_3.png)

![pcb_design](Images/pcbnew_2024-10-07_12-21-47.png)![pcb_design](Images/pcbnew_2024-10-07_12-21-49.png)

![pcb_design](Images/pcbnew_2024-10-07_12-21-37.png)![pcb_design](Images/pcbnew_2024-10-07_12-21-40.png)

## Credits

List of models used:

| Model | Credit |
|--|--:|
| Wemos D1 Mini v4 | [FBMinis](https://grabcad.com/library/wemos-esp8266-lolin-d1-mini-v4-1) |
| TP-4056 | [Babu George](https://grabcad.com/library/03962a-hw107-lithium-battery-charging-module-1) |
| BMI160 | [Kouno](https://store.kouno.xyz/products/bmi270-breakout-board) |
| GY-271 | [Benas Griauzde](https://grabcad.com/library/gy-271-hmc5883l-triple-3-axis-digital-compass-magnetometer-sensor-module-1) |