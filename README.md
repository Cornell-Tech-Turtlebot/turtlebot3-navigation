# turtlebot3-navigation
Navigation Stack for Turtlebot3

Modified from original at https://github.com/ROBOTIS-GIT/turtlebot3/tree/master/turtlebot3_navigation.

## Use

1. Run  ```export TURTLEBOT3_MODEL=waffle_pi```.

2. Launch a world of your choice in Gazebo. For an example on how to do this check https://github.com/Cornell-Tech-Turtlebot/maze-simulation/blob/master/README.md

3. Run ```roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml```

If you haven't created a map.yaml file prior to this go through the tutorial at https://emanual.robotis.com/docs/en/platform/turtlebot3/slam/#save-map before using the navigation commands. You can also run navigation together with SLAM instead of using an already existing map.

Here is a link to a navigation stack tutorial: https://docs.google.com/document/d/1NgH18AEk5IcU71uUCusiCgquB4ukdcuLuI3CgIAP4Qk 
