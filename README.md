# slam_toolbox
slam_toolbox - The robot structure with ros2_control and slam_toolbox.<br />
The previous results (since 2016) using hector_slam could be found here <ins>github.com/tomng111/roskinetic_slam_results</ins>.
## Operating<br /> 
### Installation
- `sudo apt install ros-humble-slam-toolbox`<br />
### Termin 1
- `cd <your_workspace>`<br />
- `source install/setup.bash`<br />
- `ros2 launch mit_control launch_sim.launch.py`<br />
### Termin 2
- `rviz2`<br />
### Termin 3
- `ros2 launch slam_toolbox online_async_launch.py slam_params_file:=./src/mit_control/konfig/mapper_params_online_async.yaml use_sim_time:=true`<br />
### Termin 4
- `ros2 run teleop_twist_keyboard teleop_twist_keyboard --ros-args -r /cmd_vel:=/diff_cont/cmd_vel_unstamped`<br />
### rviz2
- Add a `RobotModel` display, with the topic set to `/robot_description`<br />
- Add a `Map` display, with the topic set to `/map`<br />
- Add a `Camera` display, with the topic set to `/camera/image_raw`<br />
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
  - gazebo_params.yaml<br/>
  - mapper_params_online_async.yaml<br/>
  - my_controllers.yaml<br />
- launch<br />
  - launch_sim.launch.py<br />
  - rsp.launch.py<br />
- src<br />
- CMakeLists.txt<br />
- package.xml<br />
