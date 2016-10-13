# 2.12_robot_navigation
Discovering the ROS world based on MIT Robotics class 2.12

apriltags/src/apriltags.cpp needs to be edited:
1. delete #include <opencv/cv.h> and #include <opencv/highgui.h>
2. add #include <opencv2/opencv.hpp>
