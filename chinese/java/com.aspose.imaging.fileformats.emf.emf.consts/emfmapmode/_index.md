---
title: "EmfMapMode"
second_title: "Aspose.Imaging for Java API 参考"
description: "MapMode 枚举用于定义将页面空间单位转换为设备空间单位的计量单位，以及定义绘图坐标轴的方向。"
type: docs
weight: 30
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.consts/emfmapmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfMapMode extends System.Enum
```

MapMode 枚举用于定义将页面空间单位转换为设备空间单位的计量单位，以及定义绘图坐标轴的方向。
## 字段

| 字段 | 描述 |
| --- | --- |
| [MM_TEXT](#MM-TEXT) | 每个逻辑单元映射到一个设备像素。 |
| [MM_LOMETRIC](#MM-LOMETRIC) | 每个逻辑单元映射到 0.1 毫米。 |
| [MM_HIMETRIC](#MM-HIMETRIC) | 每个逻辑单元映射到 0.01 毫米。 |
| [MM_LOENGLISH](#MM-LOENGLISH) | 每个逻辑单元映射到 0.01 英寸。 |
| [MM_HIENGLISH](#MM-HIENGLISH) | 每个逻辑单元映射到 0.001 英寸。 |
| [MM_TWIPS](#MM-TWIPS) | 每个逻辑单元映射到打印机点的二十分之一（1/1440 英寸，也称为 "twip"）。 |
| [MM_ISOTROPIC](#MM-ISOTROPIC) | 逻辑单元映射到具有等比例轴的任意单位；也就是说，x 轴上的一个单位等于 y 轴上的一个单位。 |
| [MM_ANISOTROPIC](#MM-ANISOTROPIC) | 逻辑单元映射到具有任意比例轴的任意单位。 |
### MM_TEXT {#MM-TEXT}
```
public static final int MM_TEXT
```


每个逻辑单元映射到一个设备像素。正 x 方向向右；正 y 方向向下。

### MM_LOMETRIC {#MM-LOMETRIC}
```
public static final int MM_LOMETRIC
```


每个逻辑单元映射到 0.1 毫米。正 x 方向向右；正 y 方向向上。

### MM_HIMETRIC {#MM-HIMETRIC}
```
public static final int MM_HIMETRIC
```


每个逻辑单位映射为 0.01 毫米。正 x 向右；正 y 向上。

### MM_LOENGLISH {#MM-LOENGLISH}
```
public static final int MM_LOENGLISH
```


每个逻辑单位映射为 0.01 英寸。正 x 向右；正 y 向上

### MM_HIENGLISH {#MM-HIENGLISH}
```
public static final int MM_HIENGLISH
```


每个逻辑单位映射为 0.001 英寸。正 x 向右；正 y 向上。

### MM_TWIPS {#MM-TWIPS}
```
public static final int MM_TWIPS
```


每个逻辑单位映射为打印机点的二十分之一（1/1440 英寸，也称为 “twip”）。正 x 向右；正 y 向上。

### MM_ISOTROPIC {#MM-ISOTROPIC}
```
public static final int MM_ISOTROPIC
```


逻辑单位映射为任意单位，且坐标轴等比例缩放；也就是说，x 轴上的一个单位等于 y 轴上的一个单位。应使用 EMR\_SETWINDOWEXTEX 和 EMR\_SETVIEWPORTEXTEX 记录来指定单位和坐标轴的方向。必要时必须进行调整，以确保 x 和 y 单位保持相同大小。例如，当设置窗口范围时，必须调整视口以保持单位各向同性。

### MM_ANISOTROPIC {#MM-ANISOTROPIC}
```
public static final int MM_ANISOTROPIC
```


逻辑单位映射为任意单位，且坐标轴任意比例缩放。应使用 EMR\_SETWINDOWEXTEX 和 EMR\_SETVIEWPORTEXTEX 记录来指定单位、方向和缩放。

