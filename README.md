# Sonic Robo Blast 2

[![Build status](https://ci.appveyor.com/api/projects/status/399d4hcw9yy7hg2y?svg=true)](https://ci.appveyor.com/project/STJr/srb2)
[![Build status](https://travis-ci.org/STJr/SRB2.svg?branch=master)](https://travis-ci.org/STJr/SRB2)
[![CircleCI](https://circleci.com/gh/STJr/SRB2/tree/master.svg?style=svg)](https://circleci.com/gh/STJr/SRB2/tree/master)

[Sonic Robo Blast 2](https://srb2.org/) is a 3D Sonic the Hedgehog fangame based on a modified version of [Doom Legacy](http://doomlegacy.sourceforge.net/).

This fork aims to support the Nintendo Switch.

## Dependencies
- NASM (x86 builds only)
- SDL2 (Linux/OS X only)
- SDL2-Mixer (Linux/OS X only)
- libupnp (Linux/OS X only)
- libgme (Linux/OS X only)

## Compiling

See [SRB2 Wiki/Source code compiling](http://wiki.srb2.org/wiki/Source_code_compiling)

### Switch

Follow the instructions [here](http://wiki.srb2.org/wiki/Source_code_compiling/Makefiles), using the following make command:
```
make -C src/ SWITCH=1
```
Or, if you want to enable network debugging:
```
make -C src/ SWITCH=1 ENABLE_NXLINK=1
```
If you plan on switching flags, make sure to run `make clean` first.

More complete build instructions coming soon(TM).

## Disclaimer
Sonic Team Junior is in no way affiliated with SEGA or Sonic Team. We do not claim ownership of any of SEGA's intellectual property used in SRB2.

I (heyjoeway), STJr, or the SRB2MB are in no way responsible if this port somehow manages to break your Switch.
