# RC_MAP

ROBOCON 仿生足式挑战赛地图。

## 地图预览

### 整体地图

<img src="images/map.png" width="700" alt="ROBOCON仿生足式挑战赛地图">

### 地图俯视

<img src="images/map1.png" width="700" alt="地图细节1">

### 地图侧面 

<img src="images/map2.png" width="700" alt="地图细节2">

## 使用方法

在 MuJoCo 中替换 `scene_terrain.xml`，并在自己机器人模型中修改 `base` 出生位置为：

```xml
<worldbody>
    <body name="base_link" pos="3.7 -9.0 0.6">
```
