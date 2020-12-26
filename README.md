# Sonic Robo Blast 2

[Sonic Robo Blast 2](https://srb2.org/) is a 3D Sonic the Hedgehog fangame based on a modified version of [Doom Legacy](http://doomlegacy.sourceforge.net/).

This repo is a WIP fork of LXShades/SRB2/netplus branch. Expect things to be broken.

## Known issues
- BACKUPTICS reduced from 1024 to 96 to combat memory heap overflow on x86 builds
- BLUA is not properly simulated. Client-side LUAs work.
- Camera (locamaiming) does not synch immediatelly when it's being changed during simulations.

## Dependencies
- NASM (x86 builds only)
- SDL2 (Linux/OS X only)
- SDL2-Mixer (Linux/OS X only)
- libupnp (Linux/OS X only)
- libgme (Linux/OS X only)
- libopenmpt (Linux/OS X only)

## Compiling

See [SRB2 Wiki/Source code compiling](http://wiki.srb2.org/wiki/Source_code_compiling)

## Disclaimer
Sonic Team Junior is in no way affiliated with SEGA or Sonic Team. We do not claim ownership of any of SEGA's intellectual property used in SRB2.
