---
title: "Figure"
second_title: "Aspose.Imaging for Java API 参考"
description: "图形。"
type: docs
weight: 44
url: /zh/java/com.aspose.imaging/figure/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public class Figure extends ObjectWithBounds
```

该图形。形状的容器。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Figure()](#Figure--) | 初始化一个新的 [Figure](../../com.aspose.imaging/figure) 实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getShapes()](#getShapes--) | 获取图形形状。 |
| [getBounds()](#getBounds--) | 获取或设置对象的边界。 |
| [isClosed()](#isClosed--) | 获取指示此图形是否闭合的值。 |
| [setClosed(boolean value)](#setClosed-boolean-) | 设置指示此图形是否闭合的值。 |
| [getSegments()](#getSegments--) | 获取整个图形的段。 |
| [addShape(Shape shape)](#addShape-com.aspose.imaging.Shape-) | 向图形添加形状。 |
| [addShapes(Shape[] shapes)](#addShapes-com.aspose.imaging.Shape---) | 向图形添加一系列形状。 |
| [removeShape(Shape shape)](#removeShape-com.aspose.imaging.Shape-) | 从图形中移除形状。 |
| [removeShapes(Shape[] shapes)](#removeShapes-com.aspose.imaging.Shape---) | 从图形中移除一系列形状。 |
| [reverse()](#reverse--) | 反转此图形的形状顺序和形状点顺序。 |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | 获取对象的边界。 |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | 获取对象的边界。 |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | 对形状应用指定的变换。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的对象是否等于当前对象。 |
| [hashCode()](#hashCode--) | 用作默认的哈希函数。 |

## Example: This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface.
此示例使用 GraphicsPath 和 Graphics 类在 Image 表面上创建和操作 Figure。示例创建一个新的 Image（类型为 Tiff），并借助 GraphicsPath 类绘制路径。最后调用 Graphics 类提供的 DrawPath 方法在表面上渲染路径。
``` java
// 创建 FileStream 的实例
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.tif", com.aspose.imaging.system.io.FileMode.Create);
try {
    // 创建 TiffOptions 的实例并设置其各种属性
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

    // 为 ImageOptions 实例设置源
    tiffOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // 创建 Image 的实例
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(tiffOptions, 500, 500);
    try {
        // 创建并初始化 Graphics 类的实例
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // 清除 Graphics 表面
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // 创建 GraphicsPath 类的实例
        com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

        // 创建 Figure 类的实例
        com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();

        // 向 Figure 对象添加形状
        figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300)));
        figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
        figure.addShape(
                new com.aspose.imaging.shapes.PieShape(new com.aspose.imaging.RectangleF(
                        new com.aspose.imaging.PointF(250, 250),
                        new com.aspose.imaging.SizeF(200, 200)),
                        0, 45));

        // 将 Figure 对象添加到 GraphicsPath
        graphicspath.addFigure(figure);

        // 使用颜色为 Black 的 Pen 对象绘制路径
        graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

        // 保存所有更改。
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### Figure() {#Figure--}
```
public Figure()
```


初始化一个新的 [Figure](../../com.aspose.imaging/figure) 实例。此构造函数用于 JSON 反序列化。

### getShapes() {#getShapes--}
```
public Shape[] getShapes()
```


获取图形形状。

**Returns:**
com.aspose.imaging.Shape[] - Figure 的形状。
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


获取或设置对象的边界。

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The object's bounds.
### isClosed() {#isClosed--}
```
public boolean isClosed()
```


获取一个值，指示此 Figure 是否闭合。闭合的 Figure 仅在首尾 Figure 的形状是连续形状的情况下才会产生差异。在这种情况下，首个形状的起点将通过一条直线与最后一个形状的终点相连。

**Returns:**
boolean - 如果此 Figure 闭合则为 `True`；否则为 `false`。
### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


设置一个值，指示此 Figure 是否闭合。闭合的 Figure 仅在首尾 Figure 的形状是连续形状的情况下才会产生差异。在这种情况下，首个形状的起点将通过一条直线与最后一个形状的终点相连。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | `True` 如果此 Figure 闭合；否则为 `false`。 |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


获取整个图形的段。

**Returns:**
com.aspose.imaging.ShapeSegment[] - Figure 的段。
### addShape(Shape shape) {#addShape-com.aspose.imaging.Shape-}
```
public void addShape(Shape shape)
```


向图形添加形状。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.imaging/shape) | 要添加的形状。 |


**Example: This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface.**
此示例使用 GraphicsPath 和 Graphics 类在 Image 表面上创建和操作 Figure。示例创建一个新的 Image（类型为 Tiff），并借助 GraphicsPath 类绘制路径。最后调用 Graphics 类提供的 DrawPath 方法在表面上渲染路径。
``` java
// 创建 FileStream 的实例
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.tif", com.aspose.imaging.system.io.FileMode.Create);
try {
    // 创建 TiffOptions 的实例并设置其各种属性
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

    // 为 ImageOptions 实例设置源
    tiffOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // 创建 Image 的实例
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(tiffOptions, 500, 500);
    try {
        // 创建并初始化 Graphics 类的实例
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // 清除 Graphics 表面
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // 创建 GraphicsPath 类的实例
        com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

        // 创建 Figure 类的实例
        com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();

        // 向 Figure 对象添加形状
        figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300)));
        figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
        figure.addShape(
                new com.aspose.imaging.shapes.PieShape(new com.aspose.imaging.RectangleF(
                        new com.aspose.imaging.PointF(250, 250),
                        new com.aspose.imaging.SizeF(200, 200)),
                        0, 45));

        // 将 Figure 对象添加到 GraphicsPath
        graphicspath.addFigure(figure);

        // 使用颜色为 Black 的 Pen 对象绘制路径
        graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

        // 保存所有更改。
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### addShapes(Shape[] shapes) {#addShapes-com.aspose.imaging.Shape---}
```
public void addShapes(Shape[] shapes)
```


向图形添加一系列形状。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.imaging/shape) | 要添加的形状。 |

### removeShape(Shape shape) {#removeShape-com.aspose.imaging.Shape-}
```
public void removeShape(Shape shape)
```


从图形中移除形状。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.imaging/shape) | 要移除的形状。 |

### removeShapes(Shape[] shapes) {#removeShapes-com.aspose.imaging.Shape---}
```
public void removeShapes(Shape[] shapes)
```


从图形中移除一系列形状。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.imaging/shape) | 要移除的形状范围。 |

### reverse() {#reverse--}
```
public void reverse()
```


反转此图形的形状顺序和形状点顺序。

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
