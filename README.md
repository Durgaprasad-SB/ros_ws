# ros_ws
Here with the help of this commands we will create ROS workspace to do ROS projects
##

source /opt/ros/kinetic/setup.bash

mkdir -p ~/catkin_ws/src

cd ~/catkin_ws/

catkin_make

source devel/setup.bash

echo $ROS_PACKAGE_PATH

##
