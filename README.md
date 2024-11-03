# liosam-gazebo
gazebo仿真下的lio-sam建图
Ubuntu 20.04
ros-noetic

打开gazebo及机器人模型：
 ``` roslaunch scout_gazebo scout_gazebo.launch ``` 

地图保存位置：
``` robot_gazebo/LIO-SAM/config/params.yaml ``` 
打开params.yaml
 ``` savePCD: true ``` 
 ``` savePCDDirectory: "/robot_ws/src/pcd_maps/" ``` 

lio-sam 建图跟rviz界面:
 ``` roslaunch lio_sam run.launch ``` 

键盘控制节点：
 ``` rosrun teleop_twist_keyboard teleop_twist_keyboard.py ``` 

查看pcd图：
 ``` pcl_viewer xxx.pcd ``` 

演示视频：
``` https://www.bilibili.com/video/BV1JKS2YFE1h/``` 
