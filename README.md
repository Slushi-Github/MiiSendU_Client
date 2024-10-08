# information about this fork

* When a connection is initiated, the brightness of the Wii U Gamepad goes to level 1, to save battery life, returning to value 4 when you exit the app.
* data sending is done every 8 ms, instead of 10 ms.
* New logo and image when starting the app.
  ![](https://github.com/Slushi-Github/MiiSendU_Client/blob/master/DRCImage.png)

# MiisendU Wii U

[![GitHub Badge](https://github.com/Crayon2000/MiisendU-Wii-U/workflows/Continuous%20Integration/badge.svg)](https://github.com/Crayon2000/MiisendU-Wii-U/actions)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/35c5a21659da4701bce75bf6015632fb)](https://app.codacy.com/gh/Crayon2000/MiisendU-Wii-U/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)

This homebrew for the Wii U is a UsendMii client application.
The button states from the Wii U GamePad, the Wii U Pro Controllers and the Wii Remotes will be sent to the server.

## Build

Prerequisites:

* Packages in the wiiu-dev group and ppc-jansson from devkitpro

To compile:

```bash
/opt/devkitpro/portlibs/wiiu/bin/powerpc-eabi-cmake -B build
cmake --build build
```
