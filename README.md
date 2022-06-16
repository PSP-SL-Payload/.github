# INSTRUCTIONS

## Software Setup
1. Install [Visual Studio Code](https://code.visualstudio.com/download)

<br />

2. Install the Platformio extension for VSCode
<kbd>![installing platformio](https://user-images.githubusercontent.com/67335671/173987704-f05849cd-8c8c-4073-8ee9-9ca2ec6518bf.gif)</kbd>

<br /><br /><br />

3. Create an empty folder named 'PSP' in your C drive. This will be the root folder of all your PSP related repos
<kbd>![image](https://user-images.githubusercontent.com/67335671/173953442-e841642a-dc49-4e82-a292-65fcd60e891c.png)</kbd>

<br /><br /><br />

4. Launch the Github Desktop App

<br /><br /><br />

5. Start by cloning the 'utils' and 'libraries' repos into your new PSP directory (C:\PSP\). These are helper repos that our other repos will link against. 
<kbd>![cloning2](https://user-images.githubusercontent.com/67335671/173955429-8815b907-e45f-4516-9b6c-2c6effbdac3e.gif)</kbd>

<br /><br /><br /><br />

6. Clone the main repositories that will be worked on. In this case I'm just doing GCS, but do whichever ones you will be working on.
<kbd>![cloning3](https://user-images.githubusercontent.com/67335671/173982976-74d16ae6-841f-4a22-99df-84f195f0582c.gif)</kbd>

<br /><br /><br /><br />

7. If you've followed these instructions, this is how your file structure should look like. Verify that your directory looks like this
<kbd>![image](https://user-images.githubusercontent.com/67335671/173988163-71beb361-413f-4ca0-8bbc-dbd5f1d84043.png)</kbd>



7. If you followed the general scheme of placing the repos in the correct places, they will be already setup to link against each other and you will be able to compile them. Now, ensure that the project can still build. Open the root folder of the project you just cloned. (For GCS it needs to be SensorHub or ButtonHandler, since it needs a platformio.ini file in it).
<kbd>![building](https://user-images.githubusercontent.com/67335671/173985598-f59468d3-58bd-41df-80b1-2a0cc77b2601.gif)</kbd>

<br /><br /><br /><br />

8. If everything compiles just fine, congrats! You are now set up and ready to code!

## Hardware Setup
todo: Sean
