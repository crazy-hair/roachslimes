---
title: Main Page
nav_order: 0
---

This documentation is a work in progress! If you have any questions, feel free to send me a message request on discord at `crazy.hair`.

# roachslimes

A utilitarian DIY tracker design for [SlimeVR](https://docs.slimevr.dev/), with the intention of using the cheapest parts available in the smallest form factor possible, while maintaining quality, usability, and the ability to be built by hand.

Check out the sidebar for more information on building them yourself!

**NEW!** Revision 2 motherboards have been added, removing the BMI160-QMC5883 IMU-Magnetometer combo, and replacing it with an [LSM6DSR](https://moffshop.deyta.de/products/lsm6dsr) board which has a magnetometer built in. Technically, the LSM6DSR board is pin-compatible with the BMI160 (and therefore is compatible with the old rev 1 boards), but this new design allows for much easier direct mounting (instead of using pin headers) and frees up space for a battery connector, instead of directly soldering the battery to the board. They're currently untested, still waiting for my batch to arrive, so use at your own risk!

<img style="width:49%" src="images/mobo_assembled_3.webp"> <img style="width:49%" src="images/dabo_assembled_1.webp"> <br>

Feel free to take the boards for a spin, they're 3D models!

<iframe src="rendering/mobo_viewer.html" name="mobo_viewer" scrolling="no" frameborder="1" marginheight="0px" marginwidth="0px" style="width:49%; aspect-ratio:1/1; border-width: 0" allowfullscreen></iframe>
<iframe src="rendering/dabo_viewer.html" name="dabo_viewer" scrolling="no" frameborder="1" marginheight="0px" marginwidth="0px" style="width:49%; aspect-ratio:1/1; border-width: 0" allowfullscreen></iframe>