---
title: FillPie
second_title: Aspose.Imaging for .NET API 参考
description: 填充由RectangleFaspose.imaging/rectanglef结构和两条径向线指定的椭圆定义的饼图部分的内部
type: docs
weight: 370
url: /zh/net/aspose.imaging/graphics/fillpie/
---
## FillPie(Brush, Rectangle, float, float) {#fillpie}

填充由[`RectangleF`](../../rectanglef)结构和两条径向线指定的椭圆定义的饼图部分的内部。

```csharp
public void FillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush)决定了填充的特性。 |
| rect | Rectangle | [`Rectangle`](../../rectangle)结构，表示定义饼图部分所来自的椭圆的边界矩形。 |
| startAngle | Single | 从 x 轴到饼图部分第一侧顺时针测量的角度。 |
| sweepAngle | Single | 从*startAngle*参数顺时针测量到饼图部分第二侧的角度。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *brush*为空。 |

### 例子

以下示例展示了如何从单个 GIF 块组成动画 GIF 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

    // 创建一个 100 x 100 像素的 GIF 图片。
    // 第一个块默认是全黑的
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
        // 第一个圆圈是red
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

        //第二个圆圈是black
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

        // 逐渐增加红色圆弧形状的角度。
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

        // 逐渐增加黑弧的角度，抹去红弧。
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

填充由[`RectangleF`](../../rectanglef)结构和两条径向线指定的椭圆定义的饼图部分的内部。

```csharp
public void FillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush)决定了填充的特性。 |
| rect | RectangleF | [`RectangleF`](../../rectanglef)结构，表示定义饼图部分所在椭圆的边界矩形。 |
| startAngle | Single | 从 x 轴到饼图部分第一侧顺时针测量的角度。 |
| sweepAngle | Single | 从*startAngle*参数顺时针测量到饼图部分第二侧的角度。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *brush*为空。 |

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
| brush | Brush | [`Brush`](../../brush)决定了填充的特性。 |
| x | Single | 边界矩形左上角的 x 坐标，该边界矩形定义了饼图部分来自的椭圆。 |
| y | Single | 边界矩形左上角的 y 坐标，该边界矩形定义了饼图部分来自的椭圆。 |
| width | Single | 定义饼图部分所在椭圆的边界矩形的宽度。 |
| height | Single | 定义饼图部分所在椭圆的边界矩形的高度。 |
| startAngle | Single | 从 x 轴到饼图部分第一侧顺时针测量的角度。 |
| sweepAngle | Single | 从*startAngle*参数顺时针测量到饼图部分第二侧的角度。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *brush*为空。 |

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
| brush | Brush | [`Brush`](../../brush)决定了填充的特性。 |
| x | Int32 | 边界矩形左上角的 x 坐标，该边界矩形定义了饼图部分来自的椭圆。 |
| y | Int32 | 边界矩形左上角的 y 坐标，该边界矩形定义了饼图部分来自的椭圆。 |
| width | Int32 | 定义饼图部分所在椭圆的边界矩形的宽度。 |
| height | Int32 | 定义饼图部分所在椭圆的边界矩形的高度。 |
| startAngle | Int32 | 从 x 轴到饼图部分第一侧顺时针测量的角度。 |
| sweepAngle | Int32 | 从*startAngle*参数顺时针测量到饼图部分第二侧的角度。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *brush*为空。 |

### 也可以看看

* class [Brush](../../brush)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.Imaging](../../graphics)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
