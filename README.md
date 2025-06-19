# ReiNX-SE
[![License: GPL v2](https://img.shields.io/badge/License-GPL%20v2-blue.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)

*The (updated) modular switch custom firmware*

**WARNING: THIS IS A FORK OF REINX, IT'S NOT OFFICIALLY SUPPORTED, USE THIS AT YOUR OWN RISK**

**Usage:**

Put `ReiNX` folder on the root of your switch's SD card and run `ReiNX.bin` with your favorite fusee launcher.

**Compiling:**

You'll need devkitpro with devkitARM (along with the `devkitarm-rules` package) and run:
```
git clone https://github.com/Ricca665/ReiNX-SE.git
cd ReiNX-SE && make
```

**The Following features will maybe get implemented in future versions (no promises)**

```
* Modularity (doesn't rely on or require any SD files to run; customize SD files to your liking)

* Loads all KIPs from `/ReiNX/sysmodules/` directory

* Optional custom kernel/secmon/warmboot

* FS patches on the fly (NCA verify/cmac and optional nogc)

* Kernel patches on the fly (optional debug mode)

* Exclusive ReiNX sysmodules

* ES patch in RXP patch format (used with custom loader.kip)

* Support for switch firmware >10.x

* Support for the newer devkitARM package [DONE]
```

**Official thread:**

[HERE](https://gbatemp.net/threads/official-reinx-thread.512203/)

**Credits:**

 Naehrwert for hardware init code and generally being helpful!

 CTCaer and st4rk for their contribution to the hardware code aswell!

 SciresM for sysmodules!

 The community for your support!
