---
title: "SolidBrush"
second_title: "Aspose.Imaging for Java API 参考"
description: "实心画刷用于使用特定颜色连续绘制。"
type: docs
weight: 17
url: /zh/java/com.aspose.imaging.brushes/solidbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public final class SolidBrush extends Brush
```

SolidBrush 用于使用特定颜色连续绘图。此类不可继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SolidBrush()](#SolidBrush--) | 初始化 `SolidBrush` 类的新实例。 |
| [SolidBrush(Color color)](#SolidBrush-com.aspose.imaging.Color-) | 初始化 `SolidBrush` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColor()](#getColor--) | 获取或设置画刷颜色。 |
| [setColor(Color value)](#setColor-com.aspose.imaging.Color-) | 获取或设置画刷颜色。 |
| [hashCode()](#hashCode--) |  |
| [equals(Object object)](#equals-java.lang.Object-) |  |

## Example: This example uses Graphics class to create primitive shapes on the Image surface.
此示例使用 Graphics 类在 Image 表面创建基本形状。为演示该操作，示例创建一个 PNG 格式的新 Image，并使用 Graphics 类提供的 Draw 方法在 Image 表面绘制基本形状。
``` java
// 创建 FileStream 的实例
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.png", com.aspose.imaging.system.io.FileMode.Create);
try {
    // 创建 PngOptions 的实例并设置其各种属性
    com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // 为 PngOptions 设置 Source
    pngOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // 创建 Image 的实例
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 500);
    try {
        // 创建并初始化 Graphics 类的实例
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // 清除 Graphics 表面
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // 通过指定具有 Black com.aspose.imaging.Color 的 Pen 对象来绘制弧线，
        // 一个围绕弧线的 Rectangle、起始角度和扫掠角度
        graphics.drawArc(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2),
                new com.aspose.imaging.Rectangle(200, 200, 100, 200),
                0,
                300);

        // 通过指定具有 Blue com.aspose.imaging.Color 的 Pen 对象以及坐标点来绘制贝塞尔曲线。
        graphics.drawBezier(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
                new com.aspose.imaging.Point(250, 100),
                new com.aspose.imaging.Point(300, 30),
                new com.aspose.imaging.Point(450, 100),
                new com.aspose.imaging.Point(235, 25));

        // 通过指定具有 Green com.aspose.imaging.Color 的 Pen 对象和点数组来绘制曲线
        graphics.drawCurve(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(100, 200),
                                new com.aspose.imaging.Point(100, 350),
                                new com.aspose.imaging.Point(200, 450)
                        });

        // 使用 Pen 对象和围绕的 Rectangle 绘制椭圆
        graphics.drawEllipse(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getYellow(), 2),
                new com.aspose.imaging.Rectangle(300, 300, 100, 100));

        // 绘制直线
        graphics.drawLine(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getViolet(), 2),
                new com.aspose.imaging.Point(100, 100),
                new com.aspose.imaging.Point(200, 200));

        // 绘制一个饼图段
        graphics.drawPie(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getSilver(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(200, 20), new com.aspose.imaging.Size(200, 200)),
                0,
                45);

        // 通过指定具有红色 com.aspose.imaging.Color 的 Pen 对象和一个 Points 数组来绘制多边形
        graphics.drawPolygon(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(20, 100),
                                new com.aspose.imaging.Point(20, 200),
                                new com.aspose.imaging.Point(220, 20)
                        });

        // 绘制矩形
        graphics.drawRectangle(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(250, 250), new com.aspose.imaging.Size(100, 100)));

        // 创建 SolidBrush 对象并设置其各种属性
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush();
        brush.setColor(com.aspose.imaging.Color.getPurple());

        // 使用 SolidBrush 对象和 Font 在特定的 Point 绘制字符串
        graphics.drawString(
                "This image is created by Aspose.Imaging API",
                new com.aspose.imaging.Font("Times New Roman", 16),
                brush,
                new com.aspose.imaging.PointF(50, 400));

        // 保存所有更改。
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### SolidBrush() {#SolidBrush--}
```
public SolidBrush()
```


初始化 `SolidBrush` 类的新实例。

### SolidBrush(Color color) {#SolidBrush-com.aspose.imaging.Color-}
```
public SolidBrush(Color color)
```


初始化 `SolidBrush` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | 实心画刷的颜色。 |

### getColor() {#getColor--}
```
public Color getColor()
```


获取或设置画刷颜色。

值：画刷的颜色。

**Returns:**
[Color](../../com.aspose.imaging/color)

**Example: This example uses Graphics class to create primitive shapes on the Image surface.**
此示例使用 Graphics 类在 Image 表面创建基本形状。为演示该操作，示例创建一个 PNG 格式的新 Image，并使用 Graphics 类提供的 Draw 方法在 Image 表面绘制基本形状。
``` java
// 创建 FileStream 的实例
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.png", com.aspose.imaging.system.io.FileMode.Create);
try {
    // 创建 PngOptions 的实例并设置其各种属性
    com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // 为 PngOptions 设置 Source
    pngOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // 创建 Image 的实例
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 500);
    try {
        // 创建并初始化 Graphics 类的实例
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // 清除 Graphics 表面
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // 通过指定具有 Black com.aspose.imaging.Color 的 Pen 对象来绘制弧线，
        // 一个围绕弧线的 Rectangle、起始角度和扫掠角度
        graphics.drawArc(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2),
                new com.aspose.imaging.Rectangle(200, 200, 100, 200),
                0,
                300);

        // 通过指定具有 Blue com.aspose.imaging.Color 的 Pen 对象以及坐标点来绘制贝塞尔曲线。
        graphics.drawBezier(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
                new com.aspose.imaging.Point(250, 100),
                new com.aspose.imaging.Point(300, 30),
                new com.aspose.imaging.Point(450, 100),
                new com.aspose.imaging.Point(235, 25));

        // 通过指定具有 Green com.aspose.imaging.Color 的 Pen 对象和点数组来绘制曲线
        graphics.drawCurve(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(100, 200),
                                new com.aspose.imaging.Point(100, 350),
                                new com.aspose.imaging.Point(200, 450)
                        });

        // 使用 Pen 对象和围绕的 Rectangle 绘制椭圆
        graphics.drawEllipse(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getYellow(), 2),
                new com.aspose.imaging.Rectangle(300, 300, 100, 100));

        // 绘制直线
        graphics.drawLine(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getViolet(), 2),
                new com.aspose.imaging.Point(100, 100),
                new com.aspose.imaging.Point(200, 200));

        // 绘制一个饼图段
        graphics.drawPie(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getSilver(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(200, 20), new com.aspose.imaging.Size(200, 200)),
                0,
                45);

        // 通过指定具有红色 com.aspose.imaging.Color 的 Pen 对象和一个 Points 数组来绘制多边形
        graphics.drawPolygon(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(20, 100),
                                new com.aspose.imaging.Point(20, 200),
                                new com.aspose.imaging.Point(220, 20)
                        });

        // 绘制矩形
        graphics.drawRectangle(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(250, 250), new com.aspose.imaging.Size(100, 100)));

        // 创建 SolidBrush 对象并设置其各种属性
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush();
        brush.setColor(com.aspose.imaging.Color.getPurple());

        // 使用 SolidBrush 对象和 Font 在特定的 Point 绘制字符串
        graphics.drawString(
                "This image is created by Aspose.Imaging API",
                new com.aspose.imaging.Font("Times New Roman", 16),
                brush,
                new com.aspose.imaging.PointF(50, 400));

        // 保存所有更改。
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### setColor(Color value) {#setColor-com.aspose.imaging.Color-}
```
public void setColor(Color value)
```


获取或设置画刷颜色。

值：画刷的颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### hashCode() {#hashCode--}
```
public int hashCode()
```


获取当前对象的哈希码。

**Returns:**
int
### equals(Object object) {#equals-java.lang.Object-}
```
public boolean equals(Object object)
```


检查对象是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 对象 | java.lang.Object |  |

**Returns:**
boolean
