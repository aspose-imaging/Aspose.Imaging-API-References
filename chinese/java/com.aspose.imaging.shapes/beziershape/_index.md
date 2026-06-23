---
title: "BezierShape"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示贝塞尔样条。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.shapes/beziershape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.PolygonShape](../../com.aspose.imaging.shapes/polygonshape)
```
public final class BezierShape extends PolygonShape
```

表示贝塞尔样条。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BezierShape()](#BezierShape--) | 初始化 `BezierShape` 类的新实例。 |
| [BezierShape(PointF[] points)](#BezierShape-com.aspose.imaging.PointF---) | 初始化 `BezierShape` 类的新实例。 |
| [BezierShape(PointF[] points, boolean isClosed)](#BezierShape-com.aspose.imaging.PointF---boolean-) | 初始化 `BezierShape` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBounds()](#getBounds--) | 获取对象的边界。 |
| [getCenter()](#getCenter--) | 获取形状的中心。 |
| [getSegments()](#getSegments--) | 获取形状段。 |
| [hasSegments()](#hasSegments--) | 获取一个值，指示形状是否有段。 |
| [getEndPoint()](#getEndPoint--) | 获取结束形状点。 |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | 获取对象的边界。 |
### BezierShape() {#BezierShape--}
```
public BezierShape()
```


初始化 `BezierShape` 类的新实例。

### BezierShape(PointF[] points) {#BezierShape-com.aspose.imaging.PointF---}
```
public BezierShape(PointF[] points)
```


初始化 `BezierShape` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | 点数组。 |

### BezierShape(PointF[] points, boolean isClosed) {#BezierShape-com.aspose.imaging.PointF---boolean-}
```
public BezierShape(PointF[] points, boolean isClosed)
```


初始化 `BezierShape` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | 点数组。 |
| isClosed | boolean | 如果设置为 `true`，则贝塞尔样条闭合。 |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


获取对象的边界。

值：对象的边界。

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


获取形状的中心。

值：形状的中心。

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


获取形状段。

值：形状段。

**Returns:**
com.aspose.imaging.ShapeSegment[]
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


获取一个值，指示形状是否有段。

值：如果形状有段，则为 `True`；否则为 `false`。

**Returns:**
boolean
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


获取结束形状点。

值：结束形状点。

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


获取对象的边界。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | 将在边界之前应用的矩阵将被计算。 |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
