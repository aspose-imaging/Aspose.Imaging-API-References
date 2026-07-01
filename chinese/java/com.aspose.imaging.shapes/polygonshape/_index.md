---
title: "PolygonShape"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示多边形形状。"
type: docs
weight: 15
url: /zh/java/com.aspose.imaging.shapes/polygonshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape)

**All Implemented Interfaces:**
[com.aspose.imaging.IOrderedShape](../../com.aspose.imaging/iorderedshape)
```
public class PolygonShape extends Shape implements IOrderedShape
```

表示多边形形状。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PolygonShape()](#PolygonShape--) | 初始化 `PolygonShape` 类的新实例。 |
| [PolygonShape(PointF[] points)](#PolygonShape-com.aspose.imaging.PointF---) | 初始化 `PolygonShape` 类的新实例。 |
| [PolygonShape(PointF[] points, boolean isClosed)](#PolygonShape-com.aspose.imaging.PointF---boolean-) | 初始化 `PolygonShape` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPoints()](#getPoints--) | 获取或设置曲线点。 |
| [setPoints(PointF[] value)](#setPoints-com.aspose.imaging.PointF---) | 获取或设置曲线点。 |
| [isClosed()](#isClosed--) | 获取或设置指示形状是否闭合的值。 |
| [setClosed(boolean value)](#setClosed-boolean-) | 获取或设置指示形状是否闭合的值。 |
| [getBounds()](#getBounds--) | 获取对象的边界。 |
| [getCenter()](#getCenter--) | 获取形状的中心。 |
| [getSegments()](#getSegments--) | 获取形状段。 |
| [hasSegments()](#hasSegments--) | 获取一个值，指示形状是否有段。 |
| [getStartPoint()](#getStartPoint--) | 获取起始形状点。 |
| [getEndPoint()](#getEndPoint--) | 获取结束形状点。 |
| [reverse()](#reverse--) | 反转此形状的点顺序。 |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | 获取对象的边界。 |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | 获取对象的边界。 |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | 对形状应用指定的变换。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的对象是否等于当前对象。 |
| [hashCode()](#hashCode--) | 用作默认的哈希函数。 |

## Example: This example creates a new Image and draws a variety of shapes using Figures and GraphicsPath o...
此示例创建一个新 Image，并在 Image 表面使用 Figures 和 GraphicsPath 绘制各种形状
``` java
//创建一个 BmpOptions 实例并设置其各种属性
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//创建 FileCreateSource 的实例并将其指定为 BmpOptions 实例的 Source
//第二个 Boolean 参数决定要创建的文件是否为 IsTemporal。
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\output.bmp", false));

//创建 Image 的实例
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //创建并初始化 Graphics 类的实例
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //清除 Graphics 表面
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //创建 GraphicsPath 类的实例
    com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

    //创建 Figure 类的实例
    com.aspose.imaging.Figure figure1 = new com.aspose.imaging.Figure();

    //向 Figure 对象添加 Shape
    figure1.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
    figure1.addShape(new com.aspose.imaging.shapes.PieShape(
            new com.aspose.imaging.RectangleF(
                    new com.aspose.imaging.PointF(110, 110),
                    new com.aspose.imaging.SizeF(200, 200)), 0, 90));

    //创建 Figure 类的实例
    com.aspose.imaging.Figure figure2 = new com.aspose.imaging.Figure();

    //向 Figure 对象添加 Shape
    figure2.addShape(new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300), 0, 45));
    figure2.addShape(new com.aspose.imaging.shapes.PolygonShape(
            new com.aspose.imaging.PointF[]
                    {
                            new com.aspose.imaging.PointF(150, 10),
                            new com.aspose.imaging.PointF(150, 200),
                            new com.aspose.imaging.PointF(250, 300),
                            new com.aspose.imaging.PointF(350, 400)}, true));
    figure2.addShape(new com.aspose.imaging.shapes.RectangleShape(
            new com.aspose.imaging.RectangleF(
                    new com.aspose.imaging.PointF(250, 250),
                    new com.aspose.imaging.SizeF(200, 200))));

    //将 Figure 对象添加到 GraphicsPath
    graphicspath.addFigures(new com.aspose.imaging.Figure[]{figure1, figure2});

    //使用颜色为 Black 的 Pen 对象绘制路径
    graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

    // 保存所有更改。
    image.save();
} finally {
    image.dispose();
}
```

### PolygonShape() {#PolygonShape--}
```
public PolygonShape()
```


初始化 `PolygonShape` 类的新实例。

### PolygonShape(PointF[] points) {#PolygonShape-com.aspose.imaging.PointF---}
```
public PolygonShape(PointF[] points)
```


初始化 `PolygonShape` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | 点数组。 |

### PolygonShape(PointF[] points, boolean isClosed) {#PolygonShape-com.aspose.imaging.PointF---boolean-}
```
public PolygonShape(PointF[] points, boolean isClosed)
```


初始化 `PolygonShape` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | 点数组。 |
| isClosed | boolean | 如果设置为 `true`，多边形将闭合。 |

### getPoints() {#getPoints--}
```
public PointF[] getPoints()
```


获取或设置曲线点。

值：曲线点。

**Returns:**
com.aspose.imaging.PointF[]
### setPoints(PointF[] value) {#setPoints-com.aspose.imaging.PointF---}
```
public void setPoints(PointF[] value)
```


获取或设置曲线点。

值：曲线点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### isClosed() {#isClosed--}
```
public boolean isClosed()
```


获取或设置指示形状是否闭合的值。

值：如果形状闭合则为 `true`；否则为 `false`。

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


获取或设置指示形状是否闭合的值。

值：如果形状闭合则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

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
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


获取起始形状点。

值：起始形状点。

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


获取结束形状点。

值：结束形状点。

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### reverse() {#reverse--}
```
public void reverse()
```


反转此形状的点顺序。

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


确定指定的对象是否等于当前对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 被比较的对象。 |

**Returns:**
boolean - equals 的结果
### hashCode() {#hashCode--}
```
public int hashCode()
```


用作默认的哈希函数。

**Returns:**
int - 当前对象的哈希码。
