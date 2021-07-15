# Turtlebot-Charging-Base001
this is for ros melodic ubuntu 18.04 
$ export TURTLEBOT3_MODEL=burger 
$ roslaunch turtlebot3_gazebo turtlebot3_world.launch 
then Run Navigation Node in another terminal :- 
$ export TURTLEBOT3_MODEL=burger 
$ roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml
and for controlling panel , open another terminal then run :- 
 $ roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch
