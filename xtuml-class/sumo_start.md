# Getting started with sumo

## 1. Import the required projects

* Import `Sumo`, `Sumo Simulator`, and `MCLMShared` from the `models` repository.
* See [this guide](https://youtu.be/a0AD57W-jOk) to see how to import projects.
![sumo_start2.png](img/sumo_start2.png)

## 2. Build the Java simulator

* Open the Java perspective
![sumo_start3.png](img/sumo_start3.png)
* Select "Project > Build All"
![sumo_start11.png](img/sumo_start11.png)

## 3. Launch the simulator

* Open run configurations (triangle next to the play button > Run Configurations)
* Open the Java Applications group and select "Sumo Simulator" and click "Run"
![sumo_start4.png](img/sumo_start4.png)

## 4. Launch Verifier

* Open the xtUML Debugging perspective
![sumo_start5.png](img/sumo_start5.png)
* Open debug configurations (triangle next to the beetle > Debug Configurations)
* Open the xtUML eXecute Applications group and select "sumo" and click "Debug"
![sumo_start6.png](img/sumo_start6.png)
* Naviage to "Sumo > SumoRobotSimulator > Sumo::Library::Simulator > Sumo::Library::Simulator > Simulator > SumoSimulatorProxy > connect". Right click and select "Execute".
![sumo_start7.png](img/sumo_start7.png)
* Watch the simulation run.
* When you are done, click the red square to terminate the simulation.

## 5. Generate code

* Open the C/C++ perspective
![sumo_start8.png](img/sumo_start8.png)
* Select the "Sumo" project, right click, and select "Build Project"
![sumo_start9.png](img/sumo_start9.png)
* Expand the project, navigate to the "src" directory and browse the generated code
![sumo_start10.png](img/sumo_start10.png)
