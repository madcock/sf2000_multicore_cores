# SF2000 Multicore (Libretro cores)
These Libretro cores have been modified to work on the SF2000 multicore loader.

## About the platform
More information about the SF2000 handheld gaming system can be found [here](https://vonmillhausen.github.io/sf2000/).

## Status
Some cores build and work well, others build and have issues (no sound, slowness, etc.), some build but do not currently work, and others do not build at all. For current information on the state of each core, please see the [spreadsheet](https://docs.google.com/spreadsheets/d/1BDPqLwRcY2cN7tObuyW7RzLw8oGyY9XGLS1D4jLgz2Q/edit?usp=sharing).

## How to build
The top level project that this repo should go under is here: https://gitlab.com/kobily/sf2000_multicore
- choose a directory ro contain all this
- `git clone --recursive https://gitlab.com/kobily/sf2000_multicore`
- `mkdir cores; cd cores`
- `git clone --recursive https://github.com/madcock/sf2000_multicore_cores`
- `cd ..`
- edit the Makefile as necessary to point to the core(s) you want to build

If you don't want to build all the cores, you can just grab individual repos. All of them are independent.

I plan to make a repo here on github that I can keep in sync with this project, and provide an updated Makefile to make it easier to build without editing anything.

## Discussion
All the latest information can be found in the [dev channel on Discord](https://discord.com/channels/741895796315914271/1099465777825972347) which is part of [Retro Handhelds](https://discord.gg/retrohandhelds).
