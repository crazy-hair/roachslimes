---
title: Firmware Setup
nav_order: 4
---

# Firmware

Firmware is pretty straightforward, though I did have an issue with the Butterscotch builder/installer - battery sense would always show 100 percent. Therefore, if you want all features to work, I'd recommend building it yourself - PlatformIO Tools for Visual Studio Code make it super easy. If you're compiling yourself, all you have to do is uncomment out `BATTERY_SHIELD_RESISTANCE 180` in `defines.h`, set `USE_6_AXIS false` in `debug.h`, and and change `BMI160_MAG_TYPE BMI160_MAG_TYPE_HMC` to `BMI160_MAG_TYPE BMI160_MAG_TYPE_QMC`in `defines_bmi160.h`.

Once the firmware is installed, simply start the SlimeVR Server, connect the D1 Mini to your computer, and enter the WIFI credentials when prompted.