---
layout: post
title: tuNES
description: NES Emulator
---

All source code is found here - [tuNES Github](https://github.com/domlawlor/tuNES)

A NES emulator written in C++. It can play games like Zelda, Donkey Kong, Mario Bros, Metroid, ect.

A majority of this project was completed while at Uni in 2017 and 2018. 
I started because I played a lot of NES as a kid and thought it would be cool to make the same thing in code.
Also I wanted a substantial project to be able to show in future job interviews (I found out this is why I got my first games job!).
Though my biggest takeaway from this project was learning how assembly code actually made the NES hardware do everything. It's since made a lot of programming ideas easier to understand.

The emulator features a cycle accurate emulation of the 2A03 processor (2A07 in PAL regions) found in the NES. It's essentially a 6502 process without decimal mode, but with Audio generation logic inbuilt instead.   
All drawing is by the Picture processing unit(PPU), which renders all sprites and background tiles to a 256 x 240 pixel image.

I plan to return to this project in the near future to make it more feature complete. Fix up the missing implementations for cartridge hardware so more games work. Also want to work on the Audio Processing Unit(APU) for sound and music in game.


---
![Mario](/assets/images/tuNES/marioBros.png)
![Metroid](/assets/images/tuNES/metroid.png)
![Zelda](/assets/images/tuNES/zelda.png)
![Megaman](/assets/images/tuNES/megaman.png)