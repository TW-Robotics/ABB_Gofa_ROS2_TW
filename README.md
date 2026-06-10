# ABB_Gofa_ROS2_TW
Ros2 Package for ABB Gofa at UAS Technikum Wien



------------

0. Go to you ros2 workspace
1. ```git clone``` this repo in your ros2 workspace (tested with ros2 jazzy)
2. ```rosdep install --from-paths src --ignore-src -r -y```
3. ```colcon build && source install/setup.bash```
4. ```ros2 launch abb_bringup abb_control.launch.py description_package:=abb_crb15000_support description_file:=crb15000_5_95.xacro launch_rviz:=false use_fake_hardware:=false rws_ip:=192.168.125.1 rws_port:=443```
