---
title: "WmfPolygon"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "多边形对象"
type: docs
weight: 58
url: /zh/java/com.aspose.imaging.fileformats.wmf.objects/wmfpolygon/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfPolygon extends WmfObject
```

多边形对象
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WmfPolygon()](#WmfPolygon--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getNumberOfPoint()](#getNumberOfPoint--) | 获取或设置点的数量。 |
| [setNumberOfPoint(short value)](#setNumberOfPoint-short-) | 获取或设置点的数量。 |
| [getAPoints()](#getAPoints--) | 获取或设置点。 |
| [setAPoints(Point[] value)](#setAPoints-com.aspose.imaging.Point---) | 获取或设置点。 |
### WmfPolygon() {#WmfPolygon--}
```
public WmfPolygon()
```


### getNumberOfPoint() {#getNumberOfPoint--}
```
public short getNumberOfPoint()
```


获取或设置点的数量。一个 16 位有符号整数，定义数组中点的数量。

值：点的数量。

**Returns:**
short
### setNumberOfPoint(short value) {#setNumberOfPoint-short-}
```
public void setNumberOfPoint(short value)
```


获取或设置点的数量。一个 16 位有符号整数，定义数组中点的数量。

值：点的数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

### getAPoints() {#getAPoints--}
```
public Point[] getAPoints()
```


获取或设置点。一个 NumberOfPoints 数组，包含 32 位 PointS 对象（第 2.2.2.16 节），单位为逻辑单位。

值：点。

**Returns:**
com.aspose.imaging.Point[]
### setAPoints(Point[] value) {#setAPoints-com.aspose.imaging.Point---}
```
public void setAPoints(Point[] value)
```


获取或设置点。一个 NumberOfPoints 数组，包含 32 位 PointS 对象（第 2.2.2.16 节），单位为逻辑单位。

值：点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

