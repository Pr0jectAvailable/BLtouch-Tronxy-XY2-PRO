# BLtouch-Tronxy-XY2-PRO
How to install BLtouch on Tronxy-XY2

When installing the bltouch on my printer, I encountered a problem. It would pop out on its own and intermittently fail to engage.

![Image alt](https://github.com/Pr0jectAvailable/BLtouch-Tronxy-XY2-PRO/raw/main/photo.jpg)

Here's what I did and what ultimately helped:

I installed ferrite filters, shielded cable, made a passive filter on the bltouch side, and soldered all the contacts, but in the end, I needed the following:

Desolder the filter capacitors on the main board side near the limit switch connectors and install a shielded 4-wire cable.

You can see the sensor connection in the attached video. The brown signal is for the limit switch, and the orange signal is for the sensor commands.

You can see the Marlin firmware settings for this configuration in my other repository: https://github.com/Pr0jectAvailable/Marlin-Tronxy-XY2-PRO-config. 