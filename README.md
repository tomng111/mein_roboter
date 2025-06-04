# ohne_control
ohne_control - The robot structure without ros2_control.<br />
## Operating<br /> 
### Termin 1
- `cd <your_workspace>`<br />
- `source install/setup.bash`<br />
- `ros2 launch ohne_control launch_sim.launch.py`<br />
### Termin 2
- `rviz2`<br />
### Termin 3
- `ros2 run teleop_twist_keyboard teleop_twist_keyboard`<br />
## Structure<br /> 
- beschreibung<br />
  - camera.xacro<br />
  - gazebo_control.xacro<br />
  - inertial_macros.xacro<br />
  - lidar.xacro<br />
  - robot_core.xacro<br />
  - robot.urdf.xacro<br />
- include<br />
- launch<br />
  - launch_sim.launch.py<br />
  - rsp.launch.py<br />
- src<br />
- CMakeLists.txt<br />
- package.xml<br />
