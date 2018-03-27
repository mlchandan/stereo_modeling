# stereo_modeling
* launch the file

roslaunch stereo_modeling simple_robot_gazebo.launch 
* launch the stereo imaging

ROS_NAMESPACE=stereo rosrun stereo_image_proc stereo_image_proc

* check the disparity

rosrun image_view stereo_view stereo:=/stereo image:=image_rect_color

* to move robot

roslaunch stereo_modeling simple_tele_top.launch
