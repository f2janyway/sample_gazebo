# Samle Gazebo 
(made by ai)

All below command should do in `ros2_ws` not in `rose_ws/src/`

Put this repo in `ros2_ws/src` 

> this sample just check for rviz,gazebo sync with action(teleop_twist_keyboard)

### terminal 1
```
  colcon build --packages-select mentorpi_description
  . install/setup.zsh
  ros2 launch mentorpi_description gazebo.launch.py
```

### terminal 2
```
  ros2 run teleop_twist_keyboard teleop_twist_keyboard
```
