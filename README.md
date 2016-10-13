# 2.12_robot_navigation
Discovering the ROS world based on MIT Robotics class 2.12

## Note: Update apriltags
apriltags/src/apriltags.cpp needs to be edited:  
1. delete `#include <opencv/cv.h>` and `#include <opencv/highgui.h>`  
2. add `#include <opencv2/opencv.hpp>`

## About procman (Process Manager)
You can clone from https://github.com/RobotLocomotion/libbot.git  
If you install it at ~/libbot/build, you need to add the following code in .bashrc  
`PATH=$PATH:~/libbot/build/bin`  
`export PATH`  
`alias pman='bot-procman-sheriff -l software/config/procman.pmd'`  
Then you can use procman just by typing pman.
