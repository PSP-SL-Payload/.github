# PSP-SL Payload Team
Welcome to the official organization of the PSP-SL Payload team!
The goal of this organization is to store the Payload team's software + electrical work and to ensure knowledge is passed from year to year. With this in mind, **please make sure access to this repo gets passed down and updated each year!**


## Organization Scheme
Make repos as needed/desired. The work of old teams will be marked LEGACY and followed by the year. Use the work done on those as guidance for future endeavors.

## Technology Preferences
### Software
The team has had great success using Arduino with [PlatformIO](https://platformio.org/). PlatformIO makes it so much easier to develop, it is **highly** recommended you use this setup for the embedded side of things. It also supports non-Arduino frameworks like Mbed and such but we use Arduino as it's easiest for newcomers to learn.
Obviously your choice of how you use git is up to you. We mostly use the [Github Desktop App](https://desktop.github.com/) because it's easy for people to learn. You're also free to use bash or whatever else if that's what you like.
### Hardware
[KiCad](https://www.kicad.org/) has worked exceptionally well for the team. We use that for schematics and PCBs. 

## Software Setup
There are a lot of repos in this org which may seem overwhelming at first. For now, ignore all the LEGACY_xxx ones. Those are past repos we've had that are just here for reference if we have questions on what past teams have tried. For starters, read the brief descriptions of each repo. Many of these are small 'helper' repos that contain our libraries, utility functions, and other things that we want universal throughout all our projects. This way they can be updated independently of the main repos.

After that, follow these steps to setup and link all the repos:
1. Create an empty folder named 'PSP' in your C drive. This will be the root folder of all your PSP related repos
 ![image](https://user-images.githubusercontent.com/67335671/173953442-e841642a-dc49-4e82-a292-65fcd60e891c.png)
 &nbsp;
 &nbsp;
2. Launch the Github Desktop App
&nbsp;
&nbsp;
4. Start by cloning the 'utils' and 'libraries' repos into your new PSP directory (C:\PSP\). These are helper repos that our other repos will link against. 
![cloning2](https://user-images.githubusercontent.com/67335671/173955429-8815b907-e45f-4516-9b6c-2c6effbdac3e.gif)
&nbsp;
&nbsp;
5. Clone the main repositories that will be worked on. In this case I'm just doing GCS, but do whichever ones you will be working on.
![cloning3](https://user-images.githubusercontent.com/67335671/173982976-74d16ae6-841f-4a22-99df-84f195f0582c.gif)
&nbsp;
&nbsp;
6. If you followed the general scheme of placing the repos in the correct places, they will be already setup to link against each other and you will be able to compile them. Now, ensure that the project can still build. Open the root folder of the project you just cloned. (For GCS it needs to be SensorHub or ButtonHandler, since it needs a platformio.ini file in it).
![building](https://user-images.githubusercontent.com/67335671/173985598-f59468d3-58bd-41df-80b1-2a0cc77b2601.gif)


