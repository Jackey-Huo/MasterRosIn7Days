# ROS培训第三弹

本次编程实践的示例代码编译运行的方式如下

```bash
# 安装Navigation Stack
sudo apt-get install ros-kinetic-navigation

# 编译代码
git pull origin master
cd catkin_ws
catkin_make

# 运行实例文件
source devel/setup.bash
roslaunch simulation_launch gmapping_autolabor.launch
```

之后可以看到打开的rviz窗口
