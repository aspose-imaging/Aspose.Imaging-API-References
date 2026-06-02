---
title: "BezierKnotRecord"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "Bezier Knot 记录类"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.core.vectorpaths/bezierknotrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/vectorpathrecord)
```
public class BezierKnotRecord extends VectorPathRecord
```

Bezier Knot 记录类
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BezierKnotRecord()](#BezierKnotRecord--) | 初始化 [BezierKnotRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/bezierknotrecord) 类的新实例。 |
| [BezierKnotRecord(byte[] data)](#BezierKnotRecord-byte---) | 初始化 [BezierKnotRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/bezierknotrecord) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPathPoints()](#getPathPoints--) | 获取路径点。 |
| [setPathPoints(PointF[] value)](#setPathPoints-com.aspose.imaging.PointF---) | 设置路径点。 |
| [getPoints()](#getPoints--) | 获取点。 |
| [setPoints(Point[] value)](#setPoints-com.aspose.imaging.Point---) | 设置点。 |
| [isClosed()](#isClosed--) | 获取一个指示此实例是否已关闭的值。 |
| [setClosed(boolean value)](#setClosed-boolean-) | 设置一个指示此实例是否已关闭的值。 |
| [isLinked()](#isLinked--) | 获取一个指示此实例是否已链接的值。 |
| [setLinked(boolean value)](#setLinked-boolean-) | 设置一个指示此实例是否已链接的值。 |
| [isOpen()](#isOpen--) | 获取一个指示此实例是否已打开的值。 |
| [setOpen(boolean value)](#setOpen-boolean-) | 设置一个指示此实例是否已打开的值。 |
| [getType()](#getType--) | 获取类型。 |
### BezierKnotRecord() {#BezierKnotRecord--}
```
public BezierKnotRecord()
```


初始化 [BezierKnotRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/bezierknotrecord) 类的新实例。

### BezierKnotRecord(byte[] data) {#BezierKnotRecord-byte---}
```
public BezierKnotRecord(byte[] data)
```


初始化 [BezierKnotRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/bezierknotrecord) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | byte[] | 记录数据。 |

### getPathPoints() {#getPathPoints--}
```
public final PointF[] getPathPoints()
```


获取路径点。

值：路径点。

**Returns:**
com.aspose.imaging.PointF[] - 路径点。
### setPathPoints(PointF[] value) {#setPathPoints-com.aspose.imaging.PointF---}
```
public final void setPathPoints(PointF[] value)
```


设置路径点。

值：路径点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) | 路径点。 |

### getPoints() {#getPoints--}
```
public final Point[] getPoints()
```


获取点。

**Returns:**
com.aspose.imaging.Point[] - 点。
### setPoints(Point[] value) {#setPoints-com.aspose.imaging.Point---}
```
public final void setPoints(Point[] value)
```


设置点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) | 点。 |

### isClosed() {#isClosed--}
```
public final boolean isClosed()
```


获取一个指示此实例是否已关闭的值。

值：`true` 表示此实例已关闭；否则为 `false`。

**Returns:**
boolean - 指示此实例是否已关闭的值。
### setClosed(boolean value) {#setClosed-boolean-}
```
public final void setClosed(boolean value)
```


设置一个指示此实例是否已关闭的值。

值：`true` 表示此实例已关闭；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 指示此实例是否已关闭的值。 |

### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


获取一个指示此实例是否已链接的值。

值：`true` 表示此实例已链接；否则为 `false`。

**Returns:**
boolean - 指示此实例是否已链接的值。
### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


设置一个指示此实例是否已链接的值。

值：`true` 表示此实例已链接；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 指示此实例是否已链接的值。 |

### isOpen() {#isOpen--}
```
public final boolean isOpen()
```


获取一个指示此实例是否已打开的值。

值：`true` 表示此实例已打开；否则为 `false`。

**Returns:**
boolean - 指示此实例是否已打开的值。
### setOpen(boolean value) {#setOpen-boolean-}
```
public final void setOpen(boolean value)
```


设置一个指示此实例是否已打开的值。

值：`true` 表示此实例已打开；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 指示此实例是否已打开的值。 |

### getType() {#getType--}
```
public short getType()
```


获取类型。

值：类型。

**Returns:**
short - 类型。
