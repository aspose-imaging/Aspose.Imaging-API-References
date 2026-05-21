---
title: "EmfExtFloodFill"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_EXTFLOODFILL 记录使用当前画笔填充显示表面的区域。"
type: docs
weight: 54
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfExtFloodFill extends EmfDrawingRecordType
```

EMR_EXTFLOODFILL 记录使用当前画刷填充显示表面的区域。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfExtFloodFill(EmfRecord source)](#EmfExtFloodFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfExtFloodFill` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getStart()](#getStart--) | 获取或设置一个 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），指定填充开始的坐标（逻辑单位）。 |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | 获取或设置一个 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），指定填充开始的坐标（逻辑单位）。 |
| [getArgb32Color()](#getArgb32Color--) | 获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象与 FloodFillMode 一起用于确定填充区域。 |
| [setArgb32Color(int value)](#setArgb32Color-int-) | 获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象与 FloodFillMode 一起用于确定填充区域。 |
| [getFloodFillMode()](#getFloodFillMode--) | 获取或设置一个 32 位无符号整数，指定如何使用颜色值来确定洪水填充操作的区域。 |
| [setFloodFillMode(int value)](#setFloodFillMode-int-) | 获取或设置一个 32 位无符号整数，指定如何使用颜色值来确定洪水填充操作的区域。 |
### EmfExtFloodFill(EmfRecord source) {#EmfExtFloodFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtFloodFill(EmfRecord source)
```


初始化 `EmfExtFloodFill` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### getStart() {#getStart--}
```
public Point getStart()
```


获取或设置一个 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），指定填充开始的坐标（逻辑单位）。

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


获取或设置一个 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），指定填充开始的坐标（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getArgb32Color() {#getArgb32Color--}
```
public int getArgb32Color()
```


获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象与 FloodFillMode 一起用于确定填充区域。

**Returns:**
int
### setArgb32Color(int value) {#setArgb32Color-int-}
```
public void setArgb32Color(int value)
```


获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象与 FloodFillMode 一起用于确定填充区域。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFloodFillMode() {#getFloodFillMode--}
```
public int getFloodFillMode()
```


获取或设置一个 32 位无符号整数，指定如何使用颜色值来确定洪水填充操作的区域。该值必须属于 FloodFill 枚举（第 2.1.13 节）。

**Returns:**
int
### setFloodFillMode(int value) {#setFloodFillMode-int-}
```
public void setFloodFillMode(int value)
```


获取或设置一个 32 位无符号整数，指定如何使用颜色值来确定洪水填充操作的区域。该值必须属于 FloodFill 枚举（第 2.1.13 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

