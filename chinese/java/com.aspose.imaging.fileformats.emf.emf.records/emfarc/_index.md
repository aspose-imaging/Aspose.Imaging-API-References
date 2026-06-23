---
title: "EmfArc"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_ARC 记录指定椭圆弧。"
type: docs
weight: 13
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfarc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfArc extends EmfDrawingRecordType
```

EMR\_ARC 记录指定椭圆弧。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfArc(EmfRecord source)](#EmfArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfArc` 类的新实例。 |
| [EmfArc()](#EmfArc--) | 初始化 `EmfArc` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBox()](#getBox--) | 获取或设置一个 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象以包含-包含的方式指定边界矩形。 |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | 获取或设置一个 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象以包含-包含的方式指定边界矩形。 |
| [getStart()](#getStart--) | 获取或设置一个 64 位 WMF PointL 对象（在 [MS-WMF] 第 2.2.2.15 节中指定），该对象以逻辑单位指定定义弧起始点的径向线的结束点坐标。 |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | 获取或设置一个 64 位 WMF PointL 对象（在 [MS-WMF] 第 2.2.2.15 节中指定），该对象以逻辑单位指定定义弧起始点的径向线的结束点坐标。 |
| [getEnd()](#getEnd--) | 获取或设置一个 64 位 WMF PointL 对象，该对象以逻辑单位指定定义弧结束点的径向线的结束点坐标。 |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | 获取或设置一个 64 位 WMF PointL 对象，该对象以逻辑单位指定定义弧结束点的径向线的结束点坐标。 |
### EmfArc(EmfRecord source) {#EmfArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfArc(EmfRecord source)
```


初始化 `EmfArc` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### EmfArc() {#EmfArc--}
```
public EmfArc()
```


初始化 `EmfArc` 类的新实例。

### getBox() {#getBox--}
```
public Rectangle getBox()
```


获取或设置一个 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象以包含-包含的方式指定边界矩形。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


获取或设置一个 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象以包含-包含的方式指定边界矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStart() {#getStart--}
```
public Point getStart()
```


获取或设置一个 64 位 WMF PointL 对象（在 [MS-WMF] 第 2.2.2.15 节中指定），该对象以逻辑单位指定定义弧起始点的径向线的结束点坐标。

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


获取或设置一个 64 位 WMF PointL 对象（在 [MS-WMF] 第 2.2.2.15 节中指定），该对象以逻辑单位指定定义弧起始点的径向线的结束点坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


获取或设置一个 64 位 WMF PointL 对象，该对象以逻辑单位指定定义弧结束点的径向线的结束点坐标。

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


获取或设置一个 64 位 WMF PointL 对象，该对象以逻辑单位指定定义弧结束点的径向线的结束点坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

