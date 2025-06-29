# OpenQGIS-models
QGIS常用模型分享
## 1.1 Joy-Plot​

叠嶂图生成 [model3 - 下载](https://github.com/OpenQGIS/OpenQGIS-models/blob/main/model/Joy-Plot%E2%80%8B.model3)

![叠嶂图](https://github.com/OpenQGIS/OpenQGIS-models/blob/main/pictures/Joy-Plot.png "叠嶂图")

> **DEM** -- 输入的栅格图层
> 
> **CRS** -- 生成的网格坐标系（必须为投影坐标）
> 
> **X-Distance（km）**-- 横向山脊线转折点的间距（千米）
> 
> **Y-Distance（km）**-- 纵向每一个山脊线的间距（千米）
> 
> **Scale** -- 夸张系数，数值越大越立体
>
> **BottomPoint_height（km）** -- 基座高度（千米）


## 1.2 Joy-Plot​-Line
叠嶂图（不规则线）生成 [model3 - 下载](https://github.com/OpenQGIS/OpenQGIS-models)

> **Boundary** -- 不规则矢量范围


---

## 2. Aspect_reclassify

优化后朝向分析 [model3 - 下载](https://github.com/OpenQGIS/OpenQGIS-models/blob/main/model/Aspect_reclassify.model3)

![QGIS风格朝向分析](https://github.com/OpenQGIS/OpenQGIS-models/blob/main/pictures/Aspect_QGIS-style.png.png "QGIS风格朝向分析")

![ArcGIS风格朝向分析](https://github.com/OpenQGIS/OpenQGIS-models/blob/main/pictures/Aspect_ArcMAP-style.png "ArcGIS风格朝向分析")

> **DEM** -- 输入的栅格图层
> 
> **qml** -- 对应的样式文件
>
> 以下为qml样式文件
 >> [栅格朝向分析_QGIS_1201(-1~8).qml](https://github.com/OpenQGIS/OpenQGIS-models/blob/main/qml/%E6%A0%85%E6%A0%BC%E6%9C%9D%E5%90%91%E5%88%86%E6%9E%90_QGIS_1201(-1~8).qml)
 >> 
 >> [栅格朝向分析_QGIS_1201(-1~8)_ArcGIS-style](https://github.com/OpenQGIS/OpenQGIS-models/blob/main/qml/%E6%A0%85%E6%A0%BC%E6%9C%9D%E5%90%91%E5%88%86%E6%9E%90_QGIS_1201(-1~8)_ArcGIS-style.qml)
