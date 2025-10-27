# px4_gazebo11
自定义模型
## 模型和世界文件配置

### 模型替换
将 `models/` 目录下的新模型文件替换或添加到 PX4-Autopilot 的对应目录：
```
PX4-Autopilot/Tools/simulation/gazebo-classic/sitl_gazebo-classic/models/

```

### 世界文件替换  
将 `worlds/` 目录下的新世界文件替换或添加到 PX4-Autopilot 的对应目录：
```
PX4-Autopilot/Tools/simulation/gazebo-classic/sitl_gazebo-classic/worlds/
```

### 文件说明
- **models/**: 包含ArUco标记,门牌以及无人机模型
`无人机模型替换得看你选择自定义还是选择修改官方模型`

- **worlds/**: 包含仿真世界配置文件
