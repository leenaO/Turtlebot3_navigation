Turtlebot3 navigation
-------------------
after we create a map and save it (if you didn't do that check this first:https://github.com/leenaO/Turtlebot3.git) we can move to Turlebot navigation.

To do that follow these instructions:

1-Run navigation node: write these comands in the terminal.
     
    $ roscore
    $ export TURTLEBOT3_MODEL=burger
    $ roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml
    
you can do it with Gazebo simulation:
    
    $ roslaunch turtlebot3_gazebo turtlebot3_world.launch
     
 2- Estimate initial Pose:
   
   • Click the 2D Pose Estimate button in the RViz menu.
   
   • Click on the map where the actual robot is located and drag the large green arrow toward the direction where the robot is facing.
   
   
 3- Set navigational:
 
   • Click the 2D Nav Goal button in the RViz menu.
   
   • Click on the map to set the destination of the robot and drag the pink arrow toward the direction where the robot will be facing.
   
   
   TurtleBot3 will start moving to the destination immediately.
   
   see my navigation and try to do so!
   
   https://user-images.githubusercontent.com/46565265/124670027-1146c280-debc-11eb-927f-78c2c7446839.mp4
   
   refrence
   ----------
   https://emanual.robotis.com/docs/en/platform/turtlebot3/navigation/
