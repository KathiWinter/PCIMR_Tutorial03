
# PCIMR_Tutorial 03

Run the script with ``roslaunch pcimr_navigation navigation.launch``. </br>

Please switch on the robot_pose_probabilty in rviz, to see the actual robot pose. 

As the code still contained some bugs, I modified the algorithm like the following: </br>
- The robot only listens to north, west and south sensor data. </br>
- When the robot looses its position, the map is initialized with equal probabilities again. </br>




  
