---
title: "EllipseShape"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示椭圆形。"
type: docs
weight: 13
url: /zh/java/com.aspose.imaging.shapes/ellipseshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.RectangleProjectedShape](../../com.aspose.imaging.shapes/rectangleprojectedshape), [com.aspose.imaging.shapes.RectangleShape](../../com.aspose.imaging.shapes/rectangleshape)
```
public class EllipseShape extends RectangleShape
```

表示椭圆形。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EllipseShape()](#EllipseShape--) | 初始化 `EllipseShape` 类的新实例。 |
| [EllipseShape(RectangleF rectangle)](#EllipseShape-com.aspose.imaging.RectangleF-) | 初始化 `EllipseShape` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSegments()](#getSegments--) | 获取形状的段。 |

## Example: This example creates a new Image and draws a variety of shapes using Figures and GraphicsPath o...
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

### EllipseShape() {#EllipseShape--}
```
public EllipseShape()
```


初始化 `EllipseShape` 类的新实例。

### EllipseShape(RectangleF rectangle) {#EllipseShape-com.aspose.imaging.RectangleF-}
```
public EllipseShape(RectangleF rectangle)
```


初始化 `EllipseShape` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | 矩形。 |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


获取形状的段。

值：形状段。

**Returns:**
com.aspose.imaging.ShapeSegment[]
