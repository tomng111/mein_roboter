# mit_control
mit_control - The robot structure with ros2_control.<br />
## Operating<br /> 
### Termin 1
- `cd <your_workspace>`<br />
- `source install/setup.bash`<br />
- `ros2 launch mit_control launch_sim.launch.py`<br />
### Termin 2
- `rviz2`<br />
### Termin 3
- `ros2 run teleop_twist_keyboard teleop_twist_keyboard --ros-args -r /cmd_vel:=/diff_cont/cmd_vel_unstamped`<br />
## Structure<br /> 
- beschreibung<br />
  - camera.xacro<br />
  - gazebo_control.xacro<br />
  - inertial_macros.xacro<br />
  - lidar.xacro<br />
  - robot_core.xacro<br />
  - robot.urdf.xacro<br />
  - ros2_control.xacro<br />
- include<br />
- konfig<br />
  - my_controllers.yaml<br />
- launch<br />
  - launch_sim.launch.py<br />
  - rsp.launch.py<br />
- src<br />
- CMakeLists.txt<br />
- package.xml<br />
