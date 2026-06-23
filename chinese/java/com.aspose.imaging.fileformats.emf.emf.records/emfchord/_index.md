---
title: "EmfChord"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_CHORD 记录指定一个弦，该弦是由椭圆与称为割线的线段相交形成的区域。"
type: docs
weight: 20
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfchord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfChord extends EmfDrawingRecordType
```

EMR\\_CHORD 记录指定一个弦，该弦是由椭圆与线段（称为割线）相交形成的区域。弦使用当前笔进行描边，并使用当前画刷进行填充。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfChord(EmfRecord source)](#EmfChord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfChord` 类的新实例。 |
| [EmfChord()](#EmfChord--) | 初始化 `EmfChord` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBox()](#getBox--) | 获取或设置一个 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象以包含-包含的方式指定边界矩形。 |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | 获取或设置一个 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象以包含-包含的方式指定边界矩形。 |
| [getStart()](#getStart--) | 获取或设置一个 64 位 WMF PointL 对象（在 [MS-WMF] 第 2.2.2.15 节中指定），该对象指定定义弦起始端点的辐射的逻辑坐标。 |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | 获取或设置一个 64 位 WMF PointL 对象（在 [MS-WMF] 第 2.2.2.15 节中指定），该对象指定定义弦起始端点的辐射的逻辑坐标。 |
| [getEnd()](#getEnd--) | 获取或设置一个 64 位 WMF PointL 对象，指定定义弦结束端点的辐射的逻辑坐标。 |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | 获取或设置一个 64 位 WMF PointL 对象，指定定义弦结束端点的辐射的逻辑坐标。 |
### EmfChord(EmfRecord source) {#EmfChord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfChord(EmfRecord source)
```


初始化 `EmfChord` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### EmfChord() {#EmfChord--}
```
public EmfChord()
```


初始化 `EmfChord` 类的新实例。

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


获取或设置一个 64 位 WMF PointL 对象（在 [MS-WMF] 第 2.2.2.15 节中指定），该对象指定定义弦起始端点的辐射的逻辑坐标。

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


获取或设置一个 64 位 WMF PointL 对象（在 [MS-WMF] 第 2.2.2.15 节中指定），该对象指定定义弦起始端点的辐射的逻辑坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


获取或设置一个 64 位 WMF PointL 对象，指定定义弦结束端点的辐射的逻辑坐标。

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


获取或设置一个 64 位 WMF PointL 对象，指定定义弦结束端点的辐射的逻辑坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

