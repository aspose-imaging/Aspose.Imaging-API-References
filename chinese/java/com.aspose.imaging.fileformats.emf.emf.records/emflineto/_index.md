---
title: "EmfLineTo"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_LINETO 记录指定了一条从当前位置信息到指定点（但不包括该点）的直线。它会将当前位置信息重置为指定的点。"
type: docs
weight: 68
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emflineto/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public final class EmfLineTo extends EmfRecord
```

EMR\_LINETO 记录指定一条从当前点到指定点（但不包括该点）的直线，并将当前点重置为指定点。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfLineTo(EmfRecord record)](#EmfLineTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfLineTo` 类的新实例。 |
| [EmfLineTo()](#EmfLineTo--) | 初始化 `EmfLineTo` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPoint()](#getPoint--) | 获取或设置 64 位 WMF PointL 对象（在 [MS-WMF] 第 2.2.2.15 节中指定），该对象指定线段终点的坐标。 |
| [setPoint(Point value)](#setPoint-com.aspose.imaging.Point-) | 获取或设置 64 位 WMF PointL 对象（在 [MS-WMF] 第 2.2.2.15 节中指定），该对象指定线段终点的坐标。 |
### EmfLineTo(EmfRecord record) {#EmfLineTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfLineTo(EmfRecord record)
```


初始化 `EmfLineTo` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 记录。 |

### EmfLineTo() {#EmfLineTo--}
```
public EmfLineTo()
```


初始化 `EmfLineTo` 类的新实例。

### getPoint() {#getPoint--}
```
public Point getPoint()
```


获取或设置 64 位 WMF PointL 对象（在 [MS-WMF] 第 2.2.2.15 节中指定），该对象指定线段终点的坐标。

**Returns:**
[Point](../../com.aspose.imaging/point)
### setPoint(Point value) {#setPoint-com.aspose.imaging.Point-}
```
public void setPoint(Point value)
```


获取或设置 64 位 WMF PointL 对象（在 [MS-WMF] 第 2.2.2.15 节中指定），该对象指定线段终点的坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

