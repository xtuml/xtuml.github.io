# Set up EV3RT Dev Environment Homework ![sumo robot](../img/sumo_robot.jpg)


1) Build the EV3 LEGO sumo robot following [these instructions](../../sumo/).  

<br/>

2) Set up your EV3RT development workspace following 
[this guide](http://ev3rt-git.github.io/get_started/). Go ahead and run the 
sample program.   
  * **Note 1:** In "Step 0: Check your environment" you will need to follow the 
  instructions to install Cygwin on Windows.  In step 10 of those instructions, 
  do not download gcc-arm version 2014q3. Instead navigate to the GCC ARM page 
  and download the version containing string "2016q3".  It is newer and better.  

![gcc](../img/ev3_gcc_help.png)  

  * **Note 2:** In "Step 2: Prepare the configurator", simply download the pre-built
  binaries rather than compiling from the sources.  
<br/>

3) Generate code for the Sumo application. Follow [the instructions here](https://xtuml.github.io/xtuml-class/sumo_start.html) 
to get started with Verifier and code gen. Assure that you are using the 
[MCLM version of BridgePoint](https://s3.amazonaws.com/xtuml-releases/lego-build/buildfiles.html).   

<br/>

4) Make a new directory inside the EV3 repo: `mkdir -p <ev3_repo>/sdk/workspace/sumo`. 
Copy the contents of the `src/` folder of your Sumo project into this new 
`sumo/` folder. Copy `Makefile.inc` and `app.cfg` from the `gen/` folder into 
this directory as well.

<br/>

5) Build the app and copy it onto the SD card. You should have done this already 
in step 2 with the example app, so you shouldn't need any further instructions.

<br/>

6) Test the robot on a sumo ring. 
 
<br/>
<br/>
[Back to homework list](../homework)  
