# Hubo_ros
A ROS package for DRC-Hubo. Connects to Podo and uses the MELK AL to issue commands to hubo

# Setup
1. Create catkin workspace: http://wiki.ros.org/catkin/Tutorials/create_a_workspace
2. Copy hubo_ros package into src folder of catkin workspace
3. Run catkin build / catkin_make install
4. Cd into devel folder
5. Run source setup.bash to make package findable to the ros system
6. Start a ros_core node then you can now run the hubotalker node of the hubo_ros package with:  *rosrun hubo_ros hubotalker*
7. Run the example [example_script.py](https://github.com/benedictquartey/hubo_ros/blob/main/example_script.py) script
