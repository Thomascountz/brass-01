---
layout: default
title: Calibration & Balance
nav_order: 2
parent: Mechanical Design & Characterization
grand_parent: Pilot
---

# Calibration & Balance

In order for the hydrometer’s tilt to be sensitive to changes in density of the fluid, and in order for us to calculate gravity from the tilt angle, we must calibrate the hydrometer’s physical design. To do this, we should place the hydrometer in pure water at `20ºC` with `1.000 SG`, and use ballasts (small weights like nuts or inert pellets), to ensure the center of mass is concentrated towards the bottom, but also that the device will list at an angle (`20º +/- 5º` [as recommended by the iSpindle documentation](https://github.com/universam1/iSpindel/blob/master/docs/FAQ-en.md)). This is likely so that at (or near) the lowest gravity readings, the hydrometer will still float and tilt at a measurable angle. Once the device is physically balanced, we can then begin to calibrate the devices firmware to correlate the angle of heel to the gravity of the fluid. This is covered later.
