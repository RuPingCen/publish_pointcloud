# publish_pointcloud
this code can be used for transfom the pointcloud into octomap
# 使用方法
## 下载到ROS工作空间

   cd catkin_ws/src

   git clone https://github.com/RuPingCen/publish_pointcloud.git

   cd ..

   catkin_make

 将文件夹data目录下的test.pcd文件放在catkin_ws目录下，并修改launch文件指定test.pcd存放的目录
   
## 启动转化节点
   
    roslaunch publish_pointcloud demo.launch

