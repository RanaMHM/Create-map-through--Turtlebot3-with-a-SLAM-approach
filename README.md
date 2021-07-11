
# Create map through Turtlebot3 with a SLAM approach

##  The map was created by use [TurtleBOT3](https://emanual.robotis.com/docs/en/platform/turtlebot3/overview/) with a SLAM approach in **Ubuntu 18.04**-**ROS melodic**.
<br>

  
 * **The work environment has been configured by opening [TurtleBOT3](https://emanual.robotis.com/docs/en/platform/turtlebot3/overview/)** <br>
* **then by clicking on **_Quick Start Guide_** and choose [PC Setup](https://emanual.robotis.com/docs/en/platform/turtlebot3/quick-start/)** <br>
**→ follow the steps and write the commands in the Terminal.** <br>
 * **Then choose Simulation:** <br>
[1. Gazebo Simulation](https://emanual.robotis.com/docs/en/platform/turtlebot3/simulation/#gazebo-simulation) :<br>
Do the written steps and then by choosing one of the simulation environments, Gazebo will open. ( Selected simulation environment: TurtleBot3 World)<br>
[2. SLAM Simulation](https://emanual.robotis.com/docs/en/platform/turtlebot3/slam_simulation/):<br>
Do the written steps and then a SLAM simulation will open in Rviz.<br><br>

![‏‏لقطة الشاشة (85)](https://user-images.githubusercontent.com/52053143/125205857-fd6cd900-e28c-11eb-8f09-ee4c32b9ecb4.png)<br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Figure 1- The map in Gazebo Simulation & SLAM Simulation <br><br>

## Run Teleoperation Node
* **The robot is moved to draw and illustrate the map in SLAM Simulation by the characters defined in Terminal until the map appears as in Figure2** <br><br>

![o](https://user-images.githubusercontent.com/52053143/125210916-4e8bc580-e2ab-11eb-8365-31024bd49590.png)


<br><br>
![‏‏لقطة الشاشة (990)](https://user-images.githubusercontent.com/52053143/125205782-9ea75f80-e28c-11eb-8793-62ea60ca6581.png)<br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Figure2-the map is created successfully

<br><br>
## Save Map
When the map is created successfully write` rosrun map_server map_saver -f ~/map` in Terminal.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![map](https://user-images.githubusercontent.com/52053143/125205984-74a26d00-e28d-11eb-8227-f4b571dde4a9.jpg)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Fiuger3- The saved map
<br><br>


