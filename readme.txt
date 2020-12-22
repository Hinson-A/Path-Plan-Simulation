1.下载程序并编译
Clone this repository to your catkin workspace and catkin_make.
  cd ${YOUR_WORKSPACE_PATH}/src
  git clone https://github.com/Hinson-A/Path-Plan-Simulation.git
  cd ../
  catkin_make
  
  2.运行程序
  rviz
  并加载配置~/catkin_ws/src/grid_path_searcher/launch/rviz_config/demo.rviz
   roslaunch grid_path_searcher demo.launch   
   便可看到A*和JPS的路径
   
  Reference: more detail 
  https://mesywang.github.io/2020/01/23/Dijkstra-and-Astar/
  https://mesywang.github.io/2020/01/26/Jump-Point-Search/ 