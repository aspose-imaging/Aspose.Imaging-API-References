---
title: FillPie
second_title: Aspose.Imaging for .NET API 参考
description: 填充由 a 指定的椭圆定义的饼图部分的内部RectangleFaspose.imaging/rectanglef结构和两条径向线
type: docs
weight: 370
url: /zh/net/aspose.imaging/graphics/fillpie/
---
## FillPie(Brush, Rectangle, float, float) {#fillpie}

填充由 a 指定的椭圆定义的饼图部分的内部[`RectangleF`](../../rectanglef)结构和两条径向线。

```csharp
public void FillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush)这决定了填充的特性。 |
| rect | Rectangle | [`Rectangle`](../../rectangle)表示边界矩形的结构，该边界矩形定义了饼图部分来自的椭圆。 |
| startAngle | Single | 从 x 轴到饼图部分的第一侧顺时针测量的角度（以度为单位）。 |
| sweepAngle | Single | 以度为单位顺时针测量的角度*startAngle*参数到饼图部分的第二边。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *brush*一片空白。 |

### 例子

以下示例显示如何从单个 GIF 块组成动画 GIF 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100 x 100 像素的 GIF 图片。
// 默认情况下，第一个块是全黑的。
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    // 第一个圆圈是红色的
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    //第二个圆圈是黑色的
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // 逐渐增加红色弧形的角度。
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

    // 逐渐增加黑色弧线的角度，将红色弧线抹去。
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush2, block.Bounds, 0, angle);
        gr.FillPie(brush1, block.Bounds, angle, 360 - angle);

        gifImage.AddBlock(block);
    }

    gifImage.Save(dir + "animated_radar.gif");
}
```

### 也可以看看

* class [Brush](../../brush)
* struct [Rectangle](../../rectangle)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.Imaging](../../graphics)
* 部件 [Aspose.Imaging](../../../)

---

## FillPie(Brush, RectangleF, float, float) {#fillpie_1}

填充由 a 指定的椭圆定义的饼图部分的内部[`RectangleF`](../../rectanglef)结构和两条径向线。

```csharp
public void FillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush)这决定了填充的特性。 |
| rect | RectangleF | [`RectangleF`](../../rectanglef)表示边界矩形的结构，该边界矩形定义了饼图部分来自的椭圆。 |
| startAngle | Single | 从 x 轴到饼图部分的第一侧顺时针测量的角度（以度为单位）。 |
| sweepAngle | Single | 以度为单位顺时针测量的角度*startAngle*参数到饼图部分的第二边。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *brush*一片空白。 |

### 也可以看看

* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.Imaging](../../graphics)
* 部件 [Aspose.Imaging](../../../)

---

## FillPie(Brush, float, float, float, float, float, float) {#fillpie_3}

填充由一对坐标、宽度、高度和两条径向线指定的椭圆定义的饼图部分的内部。

```csharp
public void FillPie(Brush brush, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush)这决定了填充的特性。 |
| x | Single | 边界矩形左上角的 x 坐标，用于定义饼图部分所在的椭圆。 |
| y | Single | 边界矩形左上角的 y 坐标，用于定义饼图部分所在的椭圆。 |
| width | Single | 边界矩形的宽度，用于定义饼图部分所在的椭圆。 |
| height | Single | 边界矩形的高度，它定义了饼图部分来自的椭圆。 |
| startAngle | Single | 从 x 轴到饼图部分的第一侧顺时针测量的角度（以度为单位）。 |
| sweepAngle | Single | 以度为单位顺时针测量的角度*startAngle*参数到饼图部分的第二边。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *brush*一片空白。 |

### 也可以看看

* class [Brush](../../brush)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.Imaging](../../graphics)
* 部件 [Aspose.Imaging](../../../)

---

## FillPie(Brush, int, int, int, int, int, int) {#fillpie_2}

填充由一对坐标、宽度、高度和两条径向线指定的椭圆定义的饼图部分的内部。

```csharp
public void FillPie(Brush brush, int x, int y, int width, int height, int startAngle, 
    int sweepAngle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush)这决定了填充的特性。 |
| x | Int32 | 边界矩形左上角的 x 坐标，用于定义饼图部分所在的椭圆。 |
| y | Int32 | 边界矩形左上角的 y 坐标，用于定义饼图部分所在的椭圆。 |
| width | Int32 | 边界矩形的宽度，用于定义饼图部分所在的椭圆。 |
| height | Int32 | 边界矩形的高度，它定义了饼图部分来自的椭圆。 |
| startAngle | Int32 | 从 x 轴到饼图部分的第一侧顺时针测量的角度（以度为单位）。 |
| sweepAngle | Int32 | 以度为单位顺时针测量的角度*startAngle*参数到饼图部分的第二边。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *brush*一片空白。 |

### 也可以看看

* class [Brush](../../brush)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.Imaging](../../graphics)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
