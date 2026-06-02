---
title: "EmfAngleArc"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_ANGLEARC 记录指定弧线的线段。"
type: docs
weight: 12
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfanglearc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfAngleArc extends EmfDrawingRecordType
```

EMR\_ANGLEARC 记录指定弧线的线段。该线段从当前坐标绘制到弧线的起点。弧线沿给定半径和中心的圆周绘制。弧线的长度由给定的起始角度和扫掠角度决定。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfAngleArc(EmfRecord source)](#EmfAngleArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfAngleArc` 类的新实例。 |
| [EmfAngleArc()](#EmfAngleArc--) | 初始化 `EmfAngleArc` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCenter()](#getCenter--) | 获取或设置一个 64 位 WMF PointL 对象，该对象在 [MS-WMF] 第 2.2.2.15 节中指定，用于指定圆心的逻辑坐标。 |
| [setCenter(Point value)](#setCenter-com.aspose.imaging.Point-) | 获取或设置一个 64 位 WMF PointL 对象，该对象在 [MS-WMF] 第 2.2.2.15 节中指定，用于指定圆心的逻辑坐标。 |
| [getRadius()](#getRadius--) | 获取或设置一个 32 位无符号整数，指定圆的半径（逻辑单位）。 |
| [setRadius(int value)](#setRadius-int-) | 获取或设置一个 32 位无符号整数，指定圆的半径（逻辑单位）。 |
| [getStartAngle()](#getStartAngle--) | 获取或设置一个 32 位浮点数，指定弧的起始角度（度）。 |
| [setStartAngle(float value)](#setStartAngle-float-) | 获取或设置一个 32 位浮点数，指定弧的起始角度（度）。 |
| [getSweepAngle()](#getSweepAngle--) | 获取或设置一个 32 位浮点数，指定弧的扫掠角度（度）。 |
| [setSweepAngle(float value)](#setSweepAngle-float-) | 获取或设置一个 32 位浮点数，指定弧的扫掠角度（度）。 |
### EmfAngleArc(EmfRecord source) {#EmfAngleArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfAngleArc(EmfRecord source)
```


初始化 `EmfAngleArc` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### EmfAngleArc() {#EmfAngleArc--}
```
public EmfAngleArc()
```


初始化 `EmfAngleArc` 类的新实例。

### getCenter() {#getCenter--}
```
public Point getCenter()
```


获取或设置一个 64 位 WMF PointL 对象，该对象在 [MS-WMF] 第 2.2.2.15 节中指定，用于指定圆心的逻辑坐标。

**Returns:**
[Point](../../com.aspose.imaging/point)
### setCenter(Point value) {#setCenter-com.aspose.imaging.Point-}
```
public void setCenter(Point value)
```


获取或设置一个 64 位 WMF PointL 对象，该对象在 [MS-WMF] 第 2.2.2.15 节中指定，用于指定圆心的逻辑坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getRadius() {#getRadius--}
```
public int getRadius()
```


获取或设置一个 32 位无符号整数，指定圆的半径（逻辑单位）。

**Returns:**
int
### setRadius(int value) {#setRadius-int-}
```
public void setRadius(int value)
```


获取或设置一个 32 位无符号整数，指定圆的半径（逻辑单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


获取或设置一个 32 位浮点数，指定弧的起始角度（度）。

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


获取或设置一个 32 位浮点数，指定弧的起始角度（度）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


获取或设置一个 32 位浮点数，指定弧的扫掠角度（度）。

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


获取或设置一个 32 位浮点数，指定弧的扫掠角度（度）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

