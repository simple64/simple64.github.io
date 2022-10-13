---
layout: default
---
simple64 is an emulator based on a heavily modified version of mupen64plus-core, and ParaLLEl RSP/RDP. It includes a GUI, netplay, automatic updater, controller configuration, and much more!

It should give you the best out-of-the-box experience available for N64 gaming. There are no plugins to download.

Some of the things that are different from regular mupen64plus:
* GUI with controller configuration
* VRU support
* Fully LLE boot process
* Instruction and data cache emulation
* Much more accurate CPU, RSP and interrupt cycle timing (no "CountPerOp" or "Counter Factor")
* 64DD cartridge port support (saving works)
* Native Vulkan rendering (no OpenGL)
* Better CPU/RSP synchronization, important for homebrew titles (libdragon games work)
* More accurate screen refresh rate timing
* Cloud based netplay (no port forwarding)
* Other stuff I may have forgotten

### FAQ and System Requirements ###

See the [FAQ](https://github.com/simple64/simple64/wiki/simple64-FAQ) on the Wiki for answers to common questions.

simple64 has higher system requirements than most N64 emulators. Your GPU needs to support Vulkan 1.1, and you need a fairly good CPU to run the games at full speed. If nothing happens when you go to start a game, it is likely because your GPU doesn't support Vulkan 1.1.

### Discord ###

Come chat with the community at: [https://discord.gg/tsR3RtYynZ](https://discord.gg/tsR3RtYynZ)

### Netplay ###

You can read the netplay wiki [here](https://github.com/simple64/simple64/wiki/Netplay-Guide)

simple64 now includes netplay! No need to worry about hosting a server. The server is hosted in the cloud. Netplay is free to use and is included in the latest builds of simple64.

Wanting to play online? Come join the #netplay channel on Discord: [https://discord.gg/tsR3RtYynZ](https://discord.gg/tsR3RtYynZ). New rooms are announced in this channel when they are created.

### Support The Project ###

You can support the project on Patreon [here](https://www.patreon.com/loganmc10)

You can support the project on GitHub [here](https://github.com/sponsors/loganmc10)

### Bug Reports ###

Bugs can be filed at [https://github.com/simple64/simple64/issues](https://github.com/simple64/simple64/issues).
