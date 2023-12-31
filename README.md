# SF2000 Multicore (Libretro cores)
These Libretro cores have been modified to work on the SF2000 multicore loader.

## About the platform
More information about the SF2000 handheld gaming system can be found [here](https://vonmillhausen.github.io/sf2000/).

## Status
Some cores build and work well, others build and have issues (no sound, slowness, etc.), some build but do not currently work, and others do not build at all. For current information on the state of each core, please see the [spreadsheet](https://docs.google.com/spreadsheets/d/1BDPqLwRcY2cN7tObuyW7RzLw8oGyY9XGLS1D4jLgz2Q/edit?usp=sharing).

## How to build
The top level project is here: https://github.com/madcock/sf2000_multicore
Please see that repo for information on how to build the cores. All of the cores are independent submodules, forked from their original libretro repos.

## Discussion
All the latest information can be found in the [dev channel on Discord](https://discord.com/channels/741895796315914271/1099465777825972347) which is part of [Retro Handhelds](https://discord.gg/retrohandhelds).

## Notes
Most of the cores are forked from the official libretro repos in github. These are the exceptions:
- meg4 https://gitlab.com/bztsrc/meg4
- Potator https://git.libretro.com/libretro/potator
- VeMUlator https://git.libretro.com/libretro/vemulator-libretro

Since they are forked from gitlab, updates are handled differently.
