# ROSbot-Color-Detection

OpenCV and ROS Color Detection
This package is originally modified from penghou's package for OpenCV and ROS Color Detection: https://github.com/penghou620/ros_color_detection

This package was tailored for the Husarion ROSbot.

# Installation

```
 mkdir -p ~/ros/
 export ROS_PACKAGE_PATH=~/ros/:$ROS_PACKAGE_PATH
 cd ~/ros/
 git clone https://github.com/sabrinamkb/ROSbot-Color-Detection.git
 rospack profile
```

# Configuration

```
cd ~/ros/ros_color_detection
source setup.sh
rosmake
```

# Run 

```
roslaunch ros_color_detection color_detection.launch
```

