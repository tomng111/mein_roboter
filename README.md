# Mein Roboter
This is a fork of the original code from <ins>joshnewans/articubot_one</ins>, with some changes.<br />
I don't speak German, I just use some German words to avoid keywords (that's my habit) and to say thank you to the country where I studied (Deustchland).<br /><br />
ROS2 Humble - Gazebo.<br />
## Installation<br /> 
- `colcon build --symlink-install`<br />
- `cd <your_workspace>/src`<br />
- `ros2 pkg create --build-type amend_cmake mein_roboter`<br />
## Structure<br /> 
- beschreibung<br />
- include<br />
- konfig<br />
- launch<br />
- src<br />
- welten<br />
- CMakeLists.txt<br />
- package.xml<br />
## Branches<br /> 
- ohne_control - The robot structure without ros2_control<br />
- mit_control - The robot structure with ros2_control<br />
- slam_toolbox - The robot structure with ros2_control and slam_toolbox<br/>
