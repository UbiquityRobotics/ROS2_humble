# ROS2_humble
various nodes as converted to colcon build

for the magni_description, I copied it into a ros2_ws/src, edited CMake.txt and package.xml, and then 
built with colcon_build.

I used:

ros2 launch urdf_tutorial display.launch.py model:=/home/ubiqlap/magni_ws/src/magni_description/urdf/magni.urdf.xacro

to view the model

It is unknow if this will work with magni_bringup
