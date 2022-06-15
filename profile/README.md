# PSP-SL Payload Team
Welcome to the official organization of the PSP-SL Payload team!
The goal of this organization is to store the Payload team's software + electrical work and to ensure knowledge is passed from year to year. With this in mind, **please make sure access to this repo gets passed down and updated each year!**


## Organization Scheme
Make repos as needed/desired. The work of old teams will be marked LEGACY and followed by the year. Use the work done on those as guidance for future endeavors.

## Technology Preferences
### Software
The team has had great success using Arduino with [PlatformIO](https://platformio.org/). PlatformIO makes it so much easier to develop, it is **highly** recommended you use this setup for the embedded side of things. It also supports non-Arduino frameworks like Mbed and such but we use Arduino as it's easiest for newcomers to learn
### Hardware
[KiCad](https://www.kicad.org/) has worked exceptionally well for the team. We use that for schematics and PCBs. 

## Software Setup
There are a lot of repos in this org which may seem overwhelming at first. For now, ignore all the LEGACY_xxx ones. Those are past repos we've had that are just here for reference if we have questions on what past teams have tried. For starters, read the brief descriptions of each repo. Many of these are small 'helper' repos that contain our libraries, utility functions, and other things that we want universal throughout all our projects. This way they can be updated independently of the main repos.

After that, follow these steps to setup and link all the repos:
1.