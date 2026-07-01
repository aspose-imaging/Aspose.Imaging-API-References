---
title: "RectangleProjectedShape"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示投影到矩形上并旋转至特定方向的形状。"
type: docs
weight: 16
url: /zh/java/com.aspose.imaging.shapes/rectangleprojectedshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape)
```
public abstract class RectangleProjectedShape extends Shape
```

表示一个投射在矩形上并转向特定方向的形状。由四个点指定，这些点可以在空间中旋转，保持相同的边长且相邻边之间保持 90 度。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLeftTop()](#getLeftTop--) | 获取左上矩形点。 |
| [getRightTop()](#getRightTop--) | 获取右上矩形点。 |
| [getLeftBottom()](#getLeftBottom--) | 获取左下矩形点。 |
| [getRightBottom()](#getRightBottom--) | 获取右下矩形点。 |
| [getCenter()](#getCenter--) | 获取形状的中心。 |
| [getBounds()](#getBounds--) | 获取对象的边界。 |
| [getRectangleWidth()](#getRectangleWidth--) | 获取矩形宽度。 |
| [getRectangleHeight()](#getRectangleHeight--) | 获取矩形高度。 |
| [hasSegments()](#hasSegments--) | 获取一个值，指示形状是否有段。 |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | 获取对象的边界。 |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | 获取对象的边界。 |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | 对形状应用指定的变换。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 `Object` 是否等于此实例。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


获取左上矩形点。

值：左上矩形点。

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


获取右上矩形点。

值：右上矩形点。

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getLeftBottom() {#getLeftBottom--}
```
public PointF getLeftBottom()
```


获取左下矩形点。

值：左下矩形点。

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


获取右下矩形点。

值：右下矩形点。

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


获取形状的中心。

值：形状的中心。

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


获取对象的边界。

值：对象的边界。

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getRectangleWidth() {#getRectangleWidth--}
```
public double getRectangleWidth()
```


获取矩形宽度。

值：矩形宽度。

**Returns:**
double
### getRectangleHeight() {#getRectangleHeight--}
```
public double getRectangleHeight()
```


获取矩形高度。

值：矩形高度。

**Returns:**
double
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


获取一个值，指示形状是否有段。

值：如果形状有段，则为 `True`；否则为 `false`。

**Returns:**
boolean
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
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


获取对象的边界。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | 将在边界之前应用的矩阵将被计算。 |
| pen | [Pen](../../com.aspose.imaging/pen) | 用于对象的笔。它可能会影响对象的边界大小。 |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


对形状应用指定的变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | 要应用的变换。 |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的 `Object` 是否等于此实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的 `Object`。 |

**Returns:**
布尔值 - 如果指定的 `Object` 等于此实例，则为 `true`；否则为 `false`。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和哈希表等数据结构。
