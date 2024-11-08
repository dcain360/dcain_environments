To build the package:
run the following commands in the terminal in this order;
  source /opt/ros/humble/setup.bash

  if on mac:
    export WEBOTS_HOME=/Applications/Webots.app
    python3 local_simulation_server.py

  if on windows:
    export WEBOTS_HOME=/mnt/c/Program\ Files/Webots

  colcon build (make sure you are in the root directory)

  source install/setup.bash

  ros2 launch webots_ros2_homework1_python f23_robotics_1_launch.py

To launch the outdoor or indoor environment:
  use the command ros2 launch webots_ros2_homework1_python f23_robotics_1_launch.py
  if you wish to launch the indoor environment then the filename must be changed in the setup.py file and f23_robotics_1_launch.py, anywhere it says '15thSt.wbt' just change to 'project1-rodgers.wbt'
  As far as lighting and traffic controls, I don't think you can change it 
