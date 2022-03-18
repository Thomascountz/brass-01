---
layout: default
title: Inspiration & Prior Art
nav_order: 3
parent: Pilot
---
# Inspiration & Prior Art

## Commercial Products

On the market today is the [**Tilt Hydrometer**](https://tilthydrometer.com/) (formally Brewometer), a "free floating digital hydrometer and thermometer for continuous real-time monitoring." It pairs with an iOS or Android app or a Raspberry Pi running Tilt Pi via Bluetooth and it’s through this connection that it is able to connect to the internet to do things like post logs to Google Sheets. There isn’t a lot of information about how Tilt works or how it’s built, however, more information can be found in [U.S. Patent \#US20140260607A1](https://patents.google.com/patent/US20140260607A1/en).

The "free floating" bit of marketing copy might be to distinguish the Tilt from the [**Brew Perfect**](https://www.brewperfect.com/) (formally Beer Bug?), which I think might have been rebranded or is possibly no longer in business. With the Brew Perfect, a submersible "torpedo" is attached to the device and hung into the fermentation vessel. I believe the device uses the relative weight to measure the buoyancy of the torpedo to determine the density and gravity of the liquid. Combined with a temperature probe, the kit logs data to a proprietary app via WiFi.

## Opensource Solutions

In the opensource world exists the [**iSpindel**](https://github.com/universam1/iSpindel) (and other variants thereof). This is a [well-documented digital hydrometer and thermometer](https://github.com/universam1/iSpindel/blob/master/docs/README_en.md). The principle behind the iSpindle is theoretically similar to the Tilt: a change in buoyancy will cause the unit to _tilt_ (rather than to only rise and sink like a traditional hydrometer or the Brew Perfect) in proportion to the sugar content of the liquid. By using an accelerometer and a thermometer, the gravity of the liquid can be calculated.

Thanks to the community behind the device, it’s this solution where I find the most inspiration. It uses easily accessible opensource software and hardware and relies on a "perform" PET bottle for its housing.

There a [HomeBrew Talk](https://www.homebrewtalk.com/threads/ispindle-diy-electronic-hydrometer.598187/) thread following along with it’s development that should be helpful for troubleshooting, but the overall design theory is relatively straightforward. My first approach will be to build a slightly pared-down implementation of the iSpindel.
