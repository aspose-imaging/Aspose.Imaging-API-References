---
title: "GraphicsPath"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示一系列相连的直线和曲线。"
type: docs
weight: 52
url: /zh/java/com.aspose.imaging/graphicspath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public final class GraphicsPath extends ObjectWithBounds
```

表示一系列相连的直线和曲线。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GraphicsPath()](#GraphicsPath--) | 初始化 `GraphicsPath` 类的新实例。 |
| [GraphicsPath(Figure[] figures)](#GraphicsPath-com.aspose.imaging.Figure---) | 初始化 `GraphicsPath` 类的新实例。 |
| [GraphicsPath(Figure[] figures, int fillMode)](#GraphicsPath-com.aspose.imaging.Figure---int-) | 初始化 `GraphicsPath` 类的新实例。 |
| [GraphicsPath(int fillMode)](#GraphicsPath-int-) | 初始化 `GraphicsPath` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFillMode()](#getFillMode--) | 获取 `com.aspose.imaging.FillMode` 枚举，用于确定此 `com.aspose.imaging.GraphicsPath` 中形状内部的填充方式。 |
| [setFillMode(int value)](#setFillMode-int-) | 设置一个 `com.aspose.imaging.FillMode` 枚举，用于确定此 `com.aspose.imaging.GraphicsPath` 中形状内部的填充方式。 |
| [getFigures()](#getFigures--) | 获取路径图形。 |
| [getBounds()](#getBounds--) | 获取或设置对象的边界。 |
| [reset()](#reset--) | 清空图形路径并将 `com.aspose.imaging.FillMode` 设置为 `F:com.aspose.imaging.fillMode.alternate`。 |
| [reverse()](#reverse--) | 反转此 `com.aspose.imaging.graphicsPath` 中每个形状的图形、形状和点的顺序。 |
| [isVisible(float x, float y)](#isVisible-float-float-) | 指示指定的点是否位于此 `com.aspose.imaging.graphicsPath` 内部。 |
| [isVisible(PointF point)](#isVisible-com.aspose.imaging.PointF-) | 指示指定的点是否位于此 `com.aspose.imaging.graphicsPath` 内部。 |
| [isVisible(int x, int y)](#isVisible-int-int-) | 指示指定的点是否位于此 `com.aspose.imaging.graphicsPath` 内部。 |
| [isVisible(Point point)](#isVisible-com.aspose.imaging.Point-) | 指示指定的点是否位于此 `com.aspose.imaging.graphicsPath` 内部。 |
| [isVisible(float x, float y, Graphics graphics)](#isVisible-float-float-com.aspose.imaging.Graphics-) | 指示指定的点是否位于此 `com.aspose.imaging.GraphicsPath` 中，并且在指定 `com.aspose.imaging.graphics` 的可见裁剪区域内。 |
| [isVisible(PointF pt, Graphics graphics)](#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-) | 指示指定的点是否位于此 `com.aspose.imaging.graphicsPath` 内部。 |
| [isVisible(int x, int y, Graphics graphics)](#isVisible-int-int-com.aspose.imaging.Graphics-) | 指示指定的点是否位于此 `com.aspose.imaging.GraphicsPath` 内部，使用指定的 `com.aspose.imaging.graphics`。 |
| [isVisible(Point pt, Graphics graphics)](#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-) | 指示指定的点是否位于此 `com.aspose.imaging.graphicsPath` 内部。 |
| [isOutlineVisible(float x, float y, Pen pen)](#isOutlineVisible-float-float-com.aspose.imaging.Pen-) | 指示在使用指定的 `com.aspose.imaging.pen` 绘制时，指定的点是否位于此 `com.aspose.imaging.GraphicsPath` 的轮廓（下方）内。 |
| [isOutlineVisible(PointF point, Pen pen)](#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-) | 指示在使用指定的 `com.aspose.imaging.pen` 绘制时，指定的点是否位于此 `com.aspose.imaging.GraphicsPath` 的轮廓（下方）内。 |
| [isOutlineVisible(float x, float y, Pen pen, Graphics graphics)](#isOutlineVisible-float-float-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | 指示在使用指定的 `com.aspose.imaging.Pen` 并使用指定的 `com.aspose.imaging.graphics` 绘制时，指定的点是否位于此 `com.aspose.imaging.GraphicsPath` 的轮廓（下方）内。 |
| [isOutlineVisible(PointF pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | 指示在使用指定的 `com.aspose.imaging.Pen` 并使用指定的 `com.aspose.imaging.graphics` 绘制时，指定的点是否位于此 `com.aspose.imaging.GraphicsPath` 的轮廓（下方）内。 |
| [isOutlineVisible(int x, int y, Pen pen)](#isOutlineVisible-int-int-com.aspose.imaging.Pen-) | 指示在使用指定的 `com.aspose.imaging.pen` 绘制时，指定的点是否位于此 `com.aspose.imaging.GraphicsPath` 的轮廓（下方）内。 |
| [isOutlineVisible(Point point, Pen pen)](#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-) | 指示在使用指定的 `com.aspose.imaging.pen` 绘制时，指定的点是否位于此 `com.aspose.imaging.GraphicsPath` 的轮廓（下方）内。 |
| [isOutlineVisible(int x, int y, Pen pen, Graphics graphics)](#isOutlineVisible-int-int-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | 指示在使用指定的 `com.aspose.imaging.Pen` 并使用指定的 `com.aspose.imaging.graphics` 绘制时，指定的点是否位于此 `com.aspose.imaging.GraphicsPath` 的轮廓（下方）内。 |
| [isOutlineVisible(Point pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | 指示在使用指定的 `com.aspose.imaging.Pen` 并使用指定的 `com.aspose.imaging.graphics` 绘制时，指定的点是否位于此 `com.aspose.imaging.GraphicsPath` 的轮廓（下方）内。 |
| [flatten()](#flatten--) | 将此路径中的每条曲线转换为一系列相连的线段。 |
| [flatten(Matrix matrix)](#flatten-com.aspose.imaging.Matrix-) | 应用指定的变换，然后将此 `com.aspose.imaging.GraphicsPath` 中的每条曲线转换为一系列相连的线段。 |
| [flatten(Matrix matrix, float flatness)](#flatten-com.aspose.imaging.Matrix-float-) | 将此 `com.aspose.imaging.GraphicsPath` 中的每条曲线转换为一系列相连的线段。 |
| [widen(Pen pen)](#widen-com.aspose.imaging.Pen-) | 向路径添加额外的轮廓。 |
| [widen(Pen pen, Matrix matrix)](#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-) | 向 `com.aspose.imaging.graphicsPath` 添加额外的轮廓。 |
| [widen(Pen pen, Matrix matrix, float flatness)](#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-float-) | 用在使用指定笔绘制此路径时填充的区域所包围的曲线替换此 `com.aspose.imaging.GraphicsPath`。 |
| [warp(PointF[] destPoints, RectangleF srcRect)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-) | 对该 `com.aspose.imaging.graphicsPath` 应用由矩形和平行四边形定义的扭曲变换。 |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-) | 对该 `com.aspose.imaging.graphicsPath` 应用由矩形和平行四边形定义的扭曲变换。 |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-) | 对该 `com.aspose.imaging.graphicsPath` 应用由矩形和平行四边形定义的扭曲变换。 |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-float-) | 对该 `com.aspose.imaging.graphicsPath` 应用由矩形和平行四边形定义的扭曲变换。 |
| [addFigure(Figure figure)](#addFigure-com.aspose.imaging.Figure-) | 添加一个新图形。 |
| [addFigures(Figure[] figures)](#addFigures-com.aspose.imaging.Figure---) | 添加新图形。 |
| [removeFigure(Figure figure)](#removeFigure-com.aspose.imaging.Figure-) | 移除一个图形。 |
| [removeFigures(Figure[] figures)](#removeFigures-com.aspose.imaging.Figure---) | 移除图形。 |
| [addPath(GraphicsPath addingPath)](#addPath-com.aspose.imaging.GraphicsPath-) | 将指定的 `com.aspose.imaging.GraphicsPath` 追加到此路径。 |
| [addPath(GraphicsPath addingPath, boolean connect)](#addPath-com.aspose.imaging.GraphicsPath-boolean-) | 将指定的 `com.aspose.imaging.GraphicsPath` 追加到此路径。 |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | 获取对象的边界。 |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | 获取对象的边界。 |
| [deepClone()](#deepClone--) | 对该图形路径执行深度克隆。 |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | 对形状应用指定的变换。 |
| [equals(Object o)](#equals-java.lang.Object-) | 检查对象是否相等。 |
| [hashCode()](#hashCode--) | 获取当前对象的哈希码。 |

## Example: This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface.
这些示例使用 GraphicsPath 和 Graphics 类在 Image 表面上创建和操作图形。示例创建一个新的 Image（类型为 Tiff），并借助 GraphicsPath 类绘制路径。最后调用 Graphics 类提供的 DrawPath 方法在表面上渲染路径。
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

### GraphicsPath() {#GraphicsPath--}
```
public GraphicsPath()
```


初始化 `GraphicsPath` 类的新实例。

### GraphicsPath(Figure[] figures) {#GraphicsPath-com.aspose.imaging.Figure---}
```
public GraphicsPath(Figure[] figures)
```


初始化 `GraphicsPath` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | 用于初始化的图形。 |

### GraphicsPath(Figure[] figures, int fillMode) {#GraphicsPath-com.aspose.imaging.Figure---int-}
```
public GraphicsPath(Figure[] figures, int fillMode)
```


初始化 `GraphicsPath` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | 用于初始化的图形。 |
| fillMode | int | 填充模式。 |

### GraphicsPath(int fillMode) {#GraphicsPath-int-}
```
public GraphicsPath(int fillMode)
```


初始化 `GraphicsPath` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fillMode | int | 填充模式。 |

### getFillMode() {#getFillMode--}
```
public int getFillMode()
```


获取 `com.aspose.imaging.FillMode` 枚举，用于确定此 `com.aspose.imaging.GraphicsPath` 中形状内部的填充方式。

**Returns:**
int - 填充模式。一个 `com.aspose.imaging.FillMode` 枚举，指定此 `com.aspose.imaging.GraphicsPath` 中形状内部的填充方式。
### setFillMode(int value) {#setFillMode-int-}
```
public void setFillMode(int value)
```


设置一个 `com.aspose.imaging.FillMode` 枚举，用于确定此 `com.aspose.imaging.GraphicsPath` 中形状内部的填充方式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 填充模式。 |

### getFigures() {#getFigures--}
```
public Figure[] getFigures()
```


获取路径图形。

**Returns:**
com.aspose.imaging.Figure[] - 路径图形。
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


获取或设置对象的边界。

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The object's bounds.
### reset() {#reset--}
```
public void reset()
```


清空图形路径并将 `com.aspose.imaging.FillMode` 设置为 `F:com.aspose.imaging.fillMode.alternate`。

### reverse() {#reverse--}
```
public void reverse()
```


反转此 `com.aspose.imaging.graphicsPath` 中每个形状的图形、形状和点的顺序。

### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


指示指定的点是否位于此 `com.aspose.imaging.graphicsPath` 内部。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 要测试的点的 x 坐标。 |
| y | float | 要测试的点的 y 坐标。 |

**Returns:**
boolean - 如果指定的点位于此 `com.aspose.imaging.GraphicsPath` 内部，则此方法返回 true；否则返回 false。
### isVisible(PointF point) {#isVisible-com.aspose.imaging.PointF-}
```
public boolean isVisible(PointF point)
```


指示指定的点是否位于此 `com.aspose.imaging.graphicsPath` 内部。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | 一个表示要测试的点的 `com.aspose.imaging.PointF`。 |

**Returns:**
boolean - 如果指定的点位于此 `com.aspose.imaging.GraphicsPath` 内部，则此方法返回 true；否则返回 false。
### isVisible(int x, int y) {#isVisible-int-int-}
```
public boolean isVisible(int x, int y)
```


指示指定的点是否位于此 `com.aspose.imaging.graphicsPath` 内部。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 要测试的点的 x 坐标。 |
| y | int | 要测试的点的 y 坐标。 |

**Returns:**
boolean - 如果指定的点位于此 `com.aspose.imaging.GraphicsPath` 内部，则此方法返回 true；否则返回 false。
### isVisible(Point point) {#isVisible-com.aspose.imaging.Point-}
```
public boolean isVisible(Point point)
```


指示指定的点是否位于此 `com.aspose.imaging.graphicsPath` 内部。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | 一个表示要测试的点的 `com.aspose.imaging.Point`。 |

**Returns:**
boolean - 如果指定的点位于此 `com.aspose.imaging.GraphicsPath` 内部，则此方法返回 true；否则返回 false。
### isVisible(float x, float y, Graphics graphics) {#isVisible-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, Graphics graphics)
```


指示指定的点是否位于此 `com.aspose.imaging.GraphicsPath` 中，并且在指定 `com.aspose.imaging.graphics` 的可见裁剪区域内。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 要测试的点的 x 坐标。 |
| y | float | 要测试的点的 y 坐标。 |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | 用于测试可见性的 `com.aspose.imaging.Graphics`。 |

**Returns:**
boolean - 如果指定的点位于此 `com.aspose.imaging.GraphicsPath` 内部，则此方法返回 true；否则返回 false。
### isVisible(PointF pt, Graphics graphics) {#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(PointF pt, Graphics graphics)
```


指示指定的点是否位于此 `com.aspose.imaging.graphicsPath` 内部。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.imaging/pointf) | 一个表示要测试的点的 `com.aspose.imaging.PointF`。 |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | 用于测试可见性的 `com.aspose.imaging.Graphics`。 |

**Returns:**
boolean - 如果指定的点位于此对象内部，则此方法返回 true；否则返回 false。
### isVisible(int x, int y, Graphics graphics) {#isVisible-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, Graphics graphics)
```


指示指定的点是否位于此 `com.aspose.imaging.GraphicsPath` 内部，使用指定的 `com.aspose.imaging.graphics`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 要测试的点的 x 坐标。 |
| y | int | 要测试的点的 y 坐标。 |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | 用于测试可见性的 `com.aspose.imaging.Graphics`。 |

**Returns:**
boolean - 如果指定的点位于此 `com.aspose.imaging.GraphicsPath` 内部，则此方法返回 true；否则返回 false。
### isVisible(Point pt, Graphics graphics) {#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Point pt, Graphics graphics)
```


指示指定的点是否位于此 `com.aspose.imaging.graphicsPath` 内部。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pt | [Point](../../com.aspose.imaging/point) | 一个表示要测试的点的 `com.aspose.imaging.Point`。 |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | 用于测试可见性的 `com.aspose.imaging.Graphics`。 |

**Returns:**
boolean - 如果指定的点位于此 `com.aspose.imaging.GraphicsPath` 内部，则此方法返回 true；否则返回 false。
### isOutlineVisible(float x, float y, Pen pen) {#isOutlineVisible-float-float-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(float x, float y, Pen pen)
```


指示在使用指定的 `com.aspose.imaging.pen` 绘制时，指定的点是否位于此 `com.aspose.imaging.GraphicsPath` 的轮廓（下方）内。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 要测试的点的 x 坐标。 |
| y | float | 要测试的点的 y 坐标。 |
| pen | [Pen](../../com.aspose.imaging/pen) | 用于测试的 `com.aspose.imaging.Pen`。 |

**Returns:**
boolean - 如果指定的点位于使用指定的 `com.aspose.imaging.Pen` 绘制的此 `com.aspose.imaging.GraphicsPath` 的轮廓内部，则此方法返回 true；否则返回 false。
### isOutlineVisible(PointF point, Pen pen) {#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(PointF point, Pen pen)
```


指示在使用指定的 `com.aspose.imaging.pen` 绘制时，指定的点是否位于此 `com.aspose.imaging.GraphicsPath` 的轮廓（下方）内。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | 一个指定要测试位置的 `com.aspose.imaging.PointF`。 |
| pen | [Pen](../../com.aspose.imaging/pen) | 用于测试的 `com.aspose.imaging.Pen`。 |

**Returns:**
boolean - 如果指定的点位于使用指定的 `com.aspose.imaging.Pen` 绘制的此 `com.aspose.imaging.GraphicsPath` 的轮廓内部，则此方法返回 true；否则返回 false。
### isOutlineVisible(float x, float y, Pen pen, Graphics graphics) {#isOutlineVisible-float-float-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(float x, float y, Pen pen, Graphics graphics)
```


指示在使用指定的 `com.aspose.imaging.Pen` 并使用指定的 `com.aspose.imaging.graphics` 绘制时，指定的点是否位于此 `com.aspose.imaging.GraphicsPath` 的轮廓（下方）内。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 要测试的点的 x 坐标。 |
| y | float | 要测试的点的 y 坐标。 |
| pen | [Pen](../../com.aspose.imaging/pen) | 用于测试的 `com.aspose.imaging.Pen`。 |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | 用于测试可见性的 `com.aspose.imaging.Graphics`。 |

**Returns:**
boolean - 如果指定的点位于使用指定的 `com.aspose.imaging.Pen` 绘制的此 `com.aspose.imaging.GraphicsPath` 的轮廓（下方）内部，则此方法返回 true；否则返回 false。
### isOutlineVisible(PointF pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(PointF pt, Pen pen, Graphics graphics)
```


指示在使用指定的 `com.aspose.imaging.Pen` 并使用指定的 `com.aspose.imaging.graphics` 绘制时，指定的点是否位于此 `com.aspose.imaging.GraphicsPath` 的轮廓（下方）内。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.imaging/pointf) | 一个指定要测试位置的 `com.aspose.imaging.PointF`。 |
| pen | [Pen](../../com.aspose.imaging/pen) | 用于测试的 `com.aspose.imaging.Pen`。 |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | 用于测试可见性的 `com.aspose.imaging.Graphics`。 |

**Returns:**
boolean - 如果指定的点位于使用指定的 `com.aspose.imaging.Pen` 绘制的此 `com.aspose.imaging.GraphicsPath` 的轮廓（下方）内部，则此方法返回 true；否则返回 false。
### isOutlineVisible(int x, int y, Pen pen) {#isOutlineVisible-int-int-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(int x, int y, Pen pen)
```


指示在使用指定的 `com.aspose.imaging.pen` 绘制时，指定的点是否位于此 `com.aspose.imaging.GraphicsPath` 的轮廓（下方）内。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 要测试的点的 x 坐标。 |
| y | int | 要测试的点的 y 坐标。 |
| pen | [Pen](../../com.aspose.imaging/pen) | 用于测试的 `com.aspose.imaging.Pen`。 |

**Returns:**
boolean - 如果指定的点位于使用指定的 `com.aspose.imaging.Pen` 绘制的此 `com.aspose.imaging.GraphicsPath` 的轮廓内部，则此方法返回 true；否则返回 false。
### isOutlineVisible(Point point, Pen pen) {#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(Point point, Pen pen)
```


指示在使用指定的 `com.aspose.imaging.pen` 绘制时，指定的点是否位于此 `com.aspose.imaging.GraphicsPath` 的轮廓（下方）内。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | 一个指定要测试位置的 `com.aspose.imaging.Point`。 |
| pen | [Pen](../../com.aspose.imaging/pen) | 用于测试的 `com.aspose.imaging.Pen`。 |

**Returns:**
boolean - 如果指定的点位于使用指定的 `com.aspose.imaging.Pen` 绘制的此 `com.aspose.imaging.GraphicsPath` 的轮廓内部，则此方法返回 true；否则返回 false。
### isOutlineVisible(int x, int y, Pen pen, Graphics graphics) {#isOutlineVisible-int-int-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(int x, int y, Pen pen, Graphics graphics)
```


指示在使用指定的 `com.aspose.imaging.Pen` 并使用指定的 `com.aspose.imaging.graphics` 绘制时，指定的点是否位于此 `com.aspose.imaging.GraphicsPath` 的轮廓（下方）内。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 要测试的点的 x 坐标。 |
| y | int | 要测试的点的 y 坐标。 |
| pen | [Pen](../../com.aspose.imaging/pen) | 用于测试的 `com.aspose.imaging.Pen`。 |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | 用于测试可见性的 `com.aspose.imaging.Graphics`。 |

**Returns:**
boolean - 如果指定的点位于使用指定的 `com.aspose.imaging.Pen` 绘制的此 `com.aspose.imaging.GraphicsPath` 的轮廓内部，则此方法返回 true；否则返回 false。
### isOutlineVisible(Point pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(Point pt, Pen pen, Graphics graphics)
```


指示在使用指定的 `com.aspose.imaging.Pen` 并使用指定的 `com.aspose.imaging.graphics` 绘制时，指定的点是否位于此 `com.aspose.imaging.GraphicsPath` 的轮廓（下方）内。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pt | [Point](../../com.aspose.imaging/point) | 一个指定要测试位置的 `com.aspose.imaging.Point`。 |
| pen | [Pen](../../com.aspose.imaging/pen) | 用于测试的 `com.aspose.imaging.Pen`。 |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | 用于测试可见性的 `com.aspose.imaging.Graphics`。 |

**Returns:**
boolean - 如果指定的点位于使用指定的 `com.aspose.imaging.Pen` 绘制的此 `com.aspose.imaging.GraphicsPath` 的轮廓内部，则此方法返回 true；否则返回 false。
### flatten() {#flatten--}
```
public void flatten()
```


将此路径中的每条曲线转换为一系列相连的线段。

### flatten(Matrix matrix) {#flatten-com.aspose.imaging.Matrix-}
```
public void flatten(Matrix matrix)
```


应用指定的变换，然后将此 `com.aspose.imaging.GraphicsPath` 中的每条曲线转换为一系列相连的线段。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | 一个用于在扁平化之前转换此 `com.aspose.imaging.GraphicsPath` 的 `com.aspose.imaging.Matrix`。 |

### flatten(Matrix matrix, float flatness) {#flatten-com.aspose.imaging.Matrix-float-}
```
public void flatten(Matrix matrix, float flatness)
```


将此 `com.aspose.imaging.GraphicsPath` 中的每条曲线转换为一系列相连的线段。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | 一个用于在扁平化之前转换此 `com.aspose.imaging.GraphicsPath` 的 `com.aspose.imaging.Matrix`。 |
| 平整度 | float | 指定曲线与其扁平化近似之间允许的最大误差。默认值为 0.25。降低平整度值会增加近似中的线段数量。 |

### widen(Pen pen) {#widen-com.aspose.imaging.Pen-}
```
public void widen(Pen pen)
```


向路径添加额外的轮廓。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | 一个指定路径原始轮廓与此方法创建的新轮廓之间宽度的 `com.aspose.imaging.Pen`。 |

### widen(Pen pen, Matrix matrix) {#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-}
```
public void widen(Pen pen, Matrix matrix)
```


向 `com.aspose.imaging.graphicsPath` 添加额外的轮廓。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | 一个指定路径原始轮廓与此方法创建的新轮廓之间宽度的 `com.aspose.imaging.Pen`。 |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | 一个指定在加宽之前应用于路径的变换的 `com.aspose.imaging.Matrix`。 |

### widen(Pen pen, Matrix matrix, float flatness) {#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-float-}
```
public void widen(Pen pen, Matrix matrix, float flatness)
```


用在使用指定笔绘制此路径时填充的区域所包围的曲线替换此 `com.aspose.imaging.GraphicsPath`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | 一个指定路径原始轮廓与此方法创建的新轮廓之间宽度的 `com.aspose.imaging.Pen`。 |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | 一个指定在加宽之前应用于路径的变换的 `com.aspose.imaging.Matrix`。 |
| 平整度 | float | 指定曲线平整度的值。 |

### warp(PointF[] destPoints, RectangleF srcRect) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-}
```
public void warp(PointF[] destPoints, RectangleF srcRect)
```


对该 `com.aspose.imaging.graphicsPath` 应用由矩形和平行四边形定义的扭曲变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | 一个 `com.aspose.imaging.PointF` 结构数组，定义一个平行四边形，矩形 `srcRect` 将被转换到该平行四边形。数组可以包含三或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点隐含。 |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | 一个表示被转换为 `destPoints` 定义的平行四边形的矩形的 `com.aspose.imaging.RectangleF`。 |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```


对该 `com.aspose.imaging.graphicsPath` 应用由矩形和平行四边形定义的扭曲变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | 一个 `com.aspose.imaging.PointF` 结构数组，定义一个平行四边形，矩形 `srcRect` 将被转换到该平行四边形。数组可以包含三或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点隐含。 |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | 一个表示被转换为 `destPoints` 定义的平行四边形的矩形的 `com.aspose.imaging.RectangleF`。 |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | 一个指定要应用于路径的几何变换的 `com.aspose.imaging.Matrix`。 |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)
```


对该 `com.aspose.imaging.graphicsPath` 应用由矩形和平行四边形定义的扭曲变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | 一个 `com.aspose.imaging.PointF` 结构数组，定义一个平行四边形，矩形 `srcRect` 将被转换到该平行四边形。数组可以包含三或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点隐含。 |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | 一个表示被转换为 `destPoints` 定义的平行四边形的矩形的 `com.aspose.imaging.RectangleF`。 |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | 一个指定要应用于路径的几何变换的 `com.aspose.imaging.Matrix`。 |
| 变形模式 | int | 一个 `com.aspose.imaging.WarpMode` 枚举，指定此变形操作是使用透视模式还是双线性模式。 |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-float-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)
```


对该 `com.aspose.imaging.graphicsPath` 应用由矩形和平行四边形定义的扭曲变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | 一个 `com.aspose.imaging.PointF` 结构数组，定义一个平行四边形，矩形 `srcRect` 将被转换到该平行四边形。数组可以包含三或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点隐含。 |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | 一个表示被转换为 `destPoints` 定义的平行四边形的矩形的 `com.aspose.imaging.RectangleF`。 |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | 一个指定要应用于路径的几何变换的 `com.aspose.imaging.Matrix`。 |
| 变形模式 | int | 一个 `com.aspose.imaging.WarpMode` 枚举，指定此变形操作是使用透视模式还是双线性模式。 |
| 平整度 | float | 一个介于 0 到 1 之间的值，用于指定生成路径的平坦程度。欲了解更多信息，请参阅 `com.aspose.imaging.GraphicsPath.flatten` 方法。 |

### addFigure(Figure figure) {#addFigure-com.aspose.imaging.Figure-}
```
public void addFigure(Figure figure)
```


添加一个新图形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.imaging/figure) | 要添加的图形。 |


**Example: This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface.**
这些示例使用 GraphicsPath 和 Graphics 类在 Image 表面上创建和操作图形。示例创建一个新的 Image（类型为 Tiff），并借助 GraphicsPath 类绘制路径。最后调用 Graphics 类提供的 DrawPath 方法在表面上渲染路径。
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

### addFigures(Figure[] figures) {#addFigures-com.aspose.imaging.Figure---}
```
public void addFigures(Figure[] figures)
```


添加新图形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | 要添加的图形。 |


**Example: This example creates a new Image and draws a variety of shapes using Figures and GraphicsPath o...**
此示例创建一个新的 Image 并在图像表面使用 Figures 和 GraphicsPath 绘制各种形状。
``` java
//创建一个 BmpOptions 实例并设置其各种属性。
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//创建 FileCreateSource 的实例并将其指定为 BmpOptions 实例的 Source。
//第二个布尔参数决定要创建的文件是否为 IsTemporal。
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

    //向 Figure 对象添加 Shape。
    figure1.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
    figure1.addShape(new com.aspose.imaging.shapes.PieShape(
            new com.aspose.imaging.RectangleF(
                    new com.aspose.imaging.PointF(110, 110),
                    new com.aspose.imaging.SizeF(200, 200)), 0, 90));

    //创建 Figure 类的实例
    com.aspose.imaging.Figure figure2 = new com.aspose.imaging.Figure();

    //向 Figure 对象添加 Shape。
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

### removeFigure(Figure figure) {#removeFigure-com.aspose.imaging.Figure-}
```
public void removeFigure(Figure figure)
```


移除一个图形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.imaging/figure) | 要移除的图形。 |

### removeFigures(Figure[] figures) {#removeFigures-com.aspose.imaging.Figure---}
```
public void removeFigures(Figure[] figures)
```


移除图形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | 要移除的图形。 |

### addPath(GraphicsPath addingPath) {#addPath-com.aspose.imaging.GraphicsPath-}
```
public void addPath(GraphicsPath addingPath)
```


将指定的 `com.aspose.imaging.GraphicsPath` 追加到此路径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | 要添加的 `com.aspose.imaging.GraphicsPath`。 |

### addPath(GraphicsPath addingPath, boolean connect) {#addPath-com.aspose.imaging.GraphicsPath-boolean-}
```
public void addPath(GraphicsPath addingPath, boolean connect)
```


将指定的 `com.aspose.imaging.GraphicsPath` 追加到此路径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | 要添加的 `com.aspose.imaging.GraphicsPath`。 |
| 连接 | boolean | 一个布尔值，指定添加路径中的第一个图形是否是此路径中最后一个图形的一部分。true 表示添加路径中的第一个图形是此路径中最后一个图形的一部分。false 表示添加路径中的第一个图形与此路径中最后一个图形分离。 |

### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


获取对象的边界。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | 在计算边界之前要应用的矩阵。 |

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
| matrix | [Matrix](../../com.aspose.imaging/matrix) | 在计算边界之前要应用的矩阵。 |
| pen | [Pen](../../com.aspose.imaging/pen) | 用于对象的笔。它可能影响对象的边界尺寸。 |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### deepClone() {#deepClone--}
```
public GraphicsPath deepClone()
```


对该图形路径执行深度克隆。

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - A deep clone of the graphics path.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


对形状应用指定的变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | 要应用的转换。 |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


检查对象是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| o | java.lang.Object | 其他对象。 |

**Returns:**
boolean - 相等比较结果。
### hashCode() {#hashCode--}
```
public int hashCode()
```


获取当前对象的哈希码。

**Returns:**
int - 哈希码。
