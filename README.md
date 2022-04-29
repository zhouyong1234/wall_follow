# wall_follower

## 沿墙搜索算法
### 接收融合后的2D激光数据,将激光数据划分为不同区域,通过不同区域测到的激光与障碍物的距离给出不同的运动指令,使机器人始终靠着右侧的墙壁运动
#### wall_follower.launch为启动节点
#### Subscribed Topics
 - topic: /combined_scan
 - type: sensor_msgs/LaserScan
#### Published Topics
 - topic: /cmd_vel
 - type: geometry_msgs/Twist

