# Turtlebot3 with Gazebo with Navigation
test-patch
Install dependencies:
`rosdep install --from-paths src --ignore-src --rosdistro=melodic -y`

Use these commands to run the program:
```bash
export TURTLEBOT3_MODEL=waffle
roslaunch turtlebot3_training turtlebot3_training_gazebo.launch
roslaunch turtlebot3_training turtlebot3_training_teb_planner.launch
```

TF:

- [x] Robot URDF
- [x] Base_link to lidar frame
- [x] Odom -> base_link: gazebo
- [x] Map -> odom



Topics published

- [x] Odom: gazebo `/odom`
- [x] Laserscan: gazebo `\scan`



Topics subscribed

- [x] Base Controller: gazebo `cmd_vel`
