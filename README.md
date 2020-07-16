# Sonic Robo Blast 2 NetPlus
[Sonic Robo Blast 2](https://srb2.org/) is a 3D Sonic the Hedgehog fangame based on a modified version of [Doom Legacy](http://doomlegacy.sourceforge.net/).

This repo is a WIP fork of LXShades/SRB2/netplus branch. Expect things to be broken.
Uses variable automatic [Time Fudge](https://imgur.com/BfCtayM), enabled with "netvariabletime" console variable (default is "-1" (disabled)).

## Known issues
- Huge memory usage during simulations (over 7-12GB of RAM). x86 (32bit) builds are unusable at the moment.
- BLUA is not simulated. Client-side LUAs work.
- Camera (locamaiming) does not synch well with character's angle. This branch has a workaround to always fix your camera towards the character's angle.

## Dependencies
- NASM (x86 builds only)
- SDL2 (Linux/OS X only)
- SDL2-Mixer (Linux/OS X only)
- libupnp (Linux/OS X only)
- libgme (Linux/OS X only)
- libopenmpt (Linux/OS X only)

## Compiling

See [SRB2 Wiki/Source code compiling](http://wiki.srb2.org/wiki/Source_code_compiling)
For Windows and cross-compiling from Linux, I recommend MinGW-w64.
For Linux, use whatever you want.

## Disclaimer
Sonic Team Junior is in no way affiliated with SEGA or Sonic Team. We do not claim ownership of any of SEGA's intellectual property used in SRB2.
