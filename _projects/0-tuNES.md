---
layout: post
title: tuNES
description: NES Emulator
---

All source code is found here - [tuNES Github](https://github.com/domlawlor/tuNES)

A NES emulator written in C++ that can play games like Zelda, Donkey Kong, Mario Bros, and Metroid

A majority of this project was completed while at Uni in 2017 and 2018. More recently(Decemeber 2022) I implemented the Audio Processing Unit(APU) and rewrote parts of the cpu. 
Inspiration for the cpu/ppu timing and APU was from the Mesen emulator.

I begun this project because I played a lot of NES as a kid and thought it would be cool to make the same thing in code.
Also I wanted a substantial project to be able to show in future job interviews (I found out this is why I got my first games job!).
Though my biggest takeaway from this project was learning how assembly code actually made the NES hardware do everything. It's since made a lot of programming ideas easier to understand.

The emulator features a cycle accurate emulation of the 2A03 processor (2A07 in PAL regions) found in the NES. It's essentially a 6502 process without decimal mode, but with Audio generation logic inbuilt instead.   
All drawing is by the Picture processing unit(PPU), which renders all sprites and background tiles to a 256 x 240 pixel image.

---
![Mario](/assets/images/tuNES/marioBros.png)
![Metroid](/assets/images/tuNES/metroid.png)
![Zelda](/assets/images/tuNES/zelda.png)
![Megaman](/assets/images/tuNES/megaman.png)