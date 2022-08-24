# PSP-SL Payload Team
Welcome to the official organization of the PSP-SL Payload team!
The goal of this organization is to store the Payload team's software + electrical work and to ensure knowledge is passed from year to year. With this in mind, **please make sure access to this repo gets passed down and updated each year!**


## Organization Scheme
Make repos as needed/desired.
- LEGACY_xxx: denotes repos that past teams have used and are no longer supported. These are kept for reference and guidance on what past teams have done.
- Template_xxx: denotes repos that are 'templates'. Use them to create new repos when you need to do that
- Docs_xxx: denots repos that are meant for holding the documentation for the code repos

## Technology Preferences
### Software
The team has had great success using Arduino with [PlatformIO](https://platformio.org/). PlatformIO makes it so much easier to develop, it is **highly** recommended you use this setup for the embedded side of things. It also supports non-Arduino frameworks like Mbed and such but we use Arduino as it's easiest for newcomers to learn.
Obviously your choice of how you use git is up to you. As a cherry on top, it's a plugin for VSCode. 

We mostly use the [Github Desktop App](https://desktop.github.com/) to interact with github because it's easy for people to learn. You're also free to use bash or whatever else if that's what you like.

For all documentation, we use a tool called [Doxygen](https://www.doxygen.nl/download.html) to automatically generate it for us. 
### Hardware
[KiCad](https://www.kicad.org/) has worked exceptionally well for the team. We use that for schematics and PCBs. 

## Software Setup
There are a lot of repos in this org which may seem overwhelming at first. For now, ignore all the LEGACY_xxx ones. Those are past repos we've had that are just here for reference if we have questions on what past teams have tried. For starters, read the brief descriptions of each repo. Many of these are small 'helper' repos that contain our libraries, utility functions, and other things that we want universal throughout all our projects. This way they can be updated independently of the main repos.


After that, follow the [Software Developers Setup Guide](https://github.com/PSP-SL-Payload/InstructionsAndProcedures/blob/main/SoftwareSetup/README.md) to setup and link all the repos

## For New Members
1. Start by reading the `Software Setup` section above and set up the software it tells you to.
2. Next, familiarize yourself with our primary repos by reading the READMEs and maybe taking a brief look at the documentation
    - [GCS](https://github.com/PSP-SL-Payload/GCS)  
    - [libraries](https://github.com/PSP-SL-Payload/libraries)  
    - [InstructionsAndProcedures](https://github.com/PSP-SL-Payload/InstructionsAndProcedures/blob/main/README.md)
3. Finally, look around at anything else that looks interesting!

## Any More Questions?
If you have any more questions, or want to check out some of the team's procedures, check out our [Instructions and Procedures Repository](https://github.com/PSP-SL-Payload/InstructionsAndProcedures/blob/main/README.md).


## Miscellaneous Quick Links
- [Creating a new payload repo](https://github.com/PSP-SL-Payload/InstructionsAndProcedures/tree/main/MakingNewRepo#using-template_payload-repo)
- [How do Pull Requests work?](https://github.com/PSP-SL-Payload/InstructionsAndProcedures/tree/main/PullRequests)
