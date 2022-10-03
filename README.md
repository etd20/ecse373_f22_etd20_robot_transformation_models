# How to use
## Compile & Run
```
source /opt/ros/noetic/setup.bash
cd catkin_ws
catkin_make
source devel/setup.bash
roscore &
```
# Options
## Wheels without Gui
```
cd src/navvis_decription/launch
roslaunch display.launch use_xacro:=true use_gui:=false
```
## Wheels with Gui
```
cd src/navvis_decription/launch
roslaunch display.launch use_xacro:=true
```