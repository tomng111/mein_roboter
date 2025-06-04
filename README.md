# Mein Roboter
This is a fork of the original code from joshnewans/articubot_one, with some changes.<br />
I don't speak German, I just use some German words to avoid keywords (that's my habit).<br /><br />
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
- ohneControl - The robot structure without ros2_control<br />
- mitControl - The robot structure with ros2_control<br />
