# 天空工场ROS暑期培训第一弹

## ROS 安装攻略

http://wiki.ros.org/kinetic/Installation/Ubuntu

TODO：详细攻略和tuna支持

## 第一节课编程实践代码运行方式

```bash
cd MasterRosIn7Days/catkin_ws
catkin_make
source devel/setup.bash
rosrun autolabor_simulation_base simulation_base_node
# open a new terminal
cd MasterRosIn7Days/catkin_ws
source devel/setup.bash
rosrun autolabor_simulation_base autolabor_teleop.py /autolabor_teleop/cmd_vel:=/cmd_vel
# open another new terminal
cd MasterRosIn7Days/catkin_ws
source devel/setup.bash
roslaunch simulation_launch minimal.launch
```

之后我们可以看到弹出的rviz窗口和三个终端，打开autolabor_teleop.py所在的终端，按照屏幕输出的指示长按ijkl等键
就可以控制我们的小车移动啦^_^

