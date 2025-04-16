# Welcome To VRC Haptics
This is a project dedicated to creating cheap, versitile, and performant haptics available for everyone.

This project was started with the goal of elimintating annoying bugs in already existing setups and lowering overall barriers to entry. These goals have not changed, but the scope has temporarily been limited to VRChat (VRC). This is so that a functioning ecosystem can be assembled with the goal of supporting further devolpment and expansion to provide more coverage as time goes on.

# Directory:
Currently there are five main repositories:
 - [Server](https://github.com/VRC-Haptics/VRCH-GUI): Application for handling game to device communication.
 - [Unity Installer](https://vrc-haptics.github.io/Unity-Haptics-Installer/): Easily generate and install haptics integrations to VRC avatars from a config file.
 - [Firmware](https://github.com/VRC-Haptics/VRCH-Firmware): Hosts the source code for the official ESP32 firmware.
 - [Firmware Installer] (Under construction): Install compiled binaries to boards and configure firmware settings.
 - [Configuration Generator] (under construction): Generate configuration json's for use in the rest of the project.

# What's next:
Goals left for a V1.0-alpha:
 1. Configuration Generator (in unity for now)
 2.  Support for other games
    1. Finish implementing bHaptics Support in the Server. (just need to finish the Server)

Goals for V1.5-alpha
 1. Documentation website.
     - Server -> Device Communication Protocols
     - VRC -> Server protocols
     - config format.
     - Full Unity installation Guide
     - Custom Design Build Guide.
 1. automatic config distribution system
 1. Update Prefabs and VRCFury integration (loose Fury maybe?)
 2. Support for bluetooth connected haptics.
 1. Easier Firmware Upload/Upgrade
 1. Further Integrations with VRC
 1. Support for other games
    - Finish implementing bHaptics Support in the Server.
    - Support for bluetooth connected haptics.
    - Support for other currently existing "standards" 


