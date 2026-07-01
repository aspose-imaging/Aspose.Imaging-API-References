---
title: "EmfPlusPath"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusPath 对象指定形成图形路径的线段和曲线段序列。"
type: docs
weight: 58
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusPath extends EmfPlusGraphicsObjectType
```

EmfPlusPath 对象指定一系列形成图形路径的直线和曲线段。Bezier 数据点的顺序为起始点、控制点 1、控制点 2 和结束点。更多信息请参见[MSDN - DrawBeziers]。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusPath()](#EmfPlusPath--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPathPointFlags()](#getPathPointFlags--) | 获取或设置路径点计数，一个 32 位无符号整数，指定如何解释此对象定义的点及其关联的点类型。 |
| [setPathPointFlags(short value)](#setPathPointFlags-short-) | 获取或设置路径点计数，一个 32 位无符号整数，指定如何解释此对象定义的点及其关联的点类型。 |
| [getPathPoints()](#getPathPoints--) | 获取或设置路径点数组，一个由 PathPointCount 个点组成的数组，用于指定路径。 |
| [setPathPoints(PointF[] value)](#setPathPoints-com.aspose.imaging.PointF---) | 获取或设置路径点数组，一个由 PathPointCount 个点组成的数组，用于指定路径。 |
| [getPathPointTypes()](#getPathPointTypes--) | 获取或设置一个数组，指定 PathPoints 字段中的点如何用于绘制路径。 |
| [setPathPointTypes(EmfPlusBasePointType[] value)](#setPathPointTypes-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType---) | 获取或设置一个数组，指定 PathPoints 字段中的点如何用于绘制路径。 |
### EmfPlusPath() {#EmfPlusPath--}
```
public EmfPlusPath()
```


### getPathPointFlags() {#getPathPointFlags--}
```
public short getPathPointFlags()
```


获取或设置路径点计数，一个 32 位无符号整数，指定如何解释此对象定义的点及其关联的点类型。

**Returns:**
短
### setPathPointFlags(short value) {#setPathPointFlags-short-}
```
public void setPathPointFlags(short value)
```


获取或设置路径点计数，一个 32 位无符号整数，指定如何解释此对象定义的点及其关联的点类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


获取或设置路径点数组，一个由 PathPointCount 个点组成的数组，用于指定路径。该数组中的对象类型由 PathPointFlags 字段指定，如下：如果设置了 P 标志，则点为相对位置，由 EmfPlusPointR 对象指定（第 2.2.2.37 节）。如果未设置 P 标志且设置了 C 标志，则点为绝对位置，由 EmfPlusPoint 对象指定（第 2.2.2.35 节）。如果 P 标志和 C 标志均未设置，则点为绝对位置，由 EmfPlusPointF 对象指定（第 2.2.2.36 节）。

**Returns:**
com.aspose.imaging.PointF[]
### setPathPoints(PointF[] value) {#setPathPoints-com.aspose.imaging.PointF---}
```
public void setPathPoints(PointF[] value)
```


获取或设置路径点数组，一个由 PathPointCount 个点组成的数组，用于指定路径。该数组中的对象类型由 PathPointFlags 字段指定，如下：如果设置了 P 标志，则点为相对位置，由 EmfPlusPointR 对象指定（第 2.2.2.37 节）。如果未设置 P 标志且设置了 C 标志，则点为绝对位置，由 EmfPlusPoint 对象指定（第 2.2.2.35 节）。如果 P 标志和 C 标志均未设置，则点为绝对位置，由 EmfPlusPointF 对象指定（第 2.2.2.36 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### getPathPointTypes() {#getPathPointTypes--}
```
public EmfPlusBasePointType[] getPathPointTypes()
```


获取或设置一个数组，指定 PathPoints 字段中的点如何用于绘制路径。该数组中对象的类型由 PathPointFlags 字段中的 R 标志指定。

值：路径点类型。

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType[]
### setPathPointTypes(EmfPlusBasePointType[] value) {#setPathPointTypes-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType---}
```
public void setPathPointTypes(EmfPlusBasePointType[] value)
```


获取或设置一个数组，指定 PathPoints 字段中的点如何用于绘制路径。该数组中对象的类型由 PathPointFlags 字段中的 R 标志指定。

值：路径点类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusBasePointType\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype) |  |

