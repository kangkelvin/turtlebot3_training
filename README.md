# Turtlebot3 with Gazebo with Navigation

```bash
export TURTLEBOT3_MODEL=waffle
roslaunch turtlebot3_training turtlebot3_training_gazebo.launch
roslaunch turtlebot3_training turtlebot3_training_navigation.launch
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