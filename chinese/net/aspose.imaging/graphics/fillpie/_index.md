---
title: "Graphics.FillPie"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Graphics 方法。填充由 RectangleF 结构指定的椭圆以及两条径向线定义的饼形区域的内部。"
type: docs
weight: 380
url: /zh/net/aspose.imaging/graphics/fillpie/
---
## FillPie(Brush, Rectangle, float, float) {#fillpie}

填充由 [`RectangleF`](../../rectanglef/) 结构指定的椭圆以及两条径向线定义的饼形区域的内部。

```csharp
public void FillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/)，决定填充的特性。 |
| rect | Rectangle | [`Rectangle`](../../rectangle/) 结构，表示定义椭圆的边界矩形，该椭圆是饼形区域的来源。 |
| startAngle | 单精度 | 从 x 轴顺时针测量到饼形区域第一边的角度（度）。 |
| sweepAngle | 单精度 | 角度（以度为单位），沿顺时针方向从 *startAngle* 参数测量到饼图部分的第二侧。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。 |

## 示例

下面的示例展示了如何从单个 GIF 块组合成动画 GIF 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100 x 100 像素的 GIF 图像。
// 默认情况下，第一个块是全黑的。
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    // 第一个圆是红色的
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // 第二个圆是黑色的
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // 逐渐增加红色弧形的角度。
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

    // 逐渐增加黑色弧形的角度并抹去红色弧形。
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

### 另请参见

* class [Brush](../../brush/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## FillPie(Brush, RectangleF, float, float) {#fillpie_1}

填充由 [`RectangleF`](../../rectanglef/) 结构指定的椭圆以及两条径向线定义的饼形区域的内部。

```csharp
public void FillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/)，决定填充的特性。 |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) 结构，表示定义饼图部分所在椭圆的边界矩形。 |
| startAngle | 单精度 | 从 x 轴顺时针测量到饼形区域第一边的角度（度）。 |
| sweepAngle | 单精度 | 角度（以度为单位），沿顺时针方向从 *startAngle* 参数测量到饼图部分的第二侧。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。 |

### 另请参见

* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## FillPie(Brush, float, float, float, float, float, float) {#fillpie_3}

填充由一对坐标、宽度、高度以及两条径向线指定的椭圆定义的饼形区域的内部。

```csharp
public void FillPie(Brush brush, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/)，决定填充的特性。 |
| x | 单精度 | 定义饼图部分所在椭圆的边界矩形左上角的 x 坐标。 |
| y | 单精度 | 定义饼图部分所在椭圆的边界矩形左上角的 y 坐标。 |
| 宽度 | 单精度 | 定义饼图部分所在椭圆的边界矩形的宽度。 |
| 高度 | 单精度 | 定义饼图部分所在椭圆的边界矩形的高度。 |
| startAngle | 单精度 | 从 x 轴顺时针测量到饼形区域第一边的角度（度）。 |
| sweepAngle | 单精度 | 角度（以度为单位），沿顺时针方向从 *startAngle* 参数测量到饼图部分的第二侧。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。 |

### 另请参见

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## FillPie(Brush, int, int, int, int, int, int) {#fillpie_2}

填充由一对坐标、宽度、高度以及两条径向线指定的椭圆定义的饼形区域的内部。

```csharp
public void FillPie(Brush brush, int x, int y, int width, int height, int startAngle, 
    int sweepAngle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/)，决定填充的特性。 |
| x | Int32 | 定义饼图部分所在椭圆的边界矩形左上角的 x 坐标。 |
| y | Int32 | 定义饼图部分所在椭圆的边界矩形左上角的 y 坐标。 |
| 宽度 | Int32 | 定义饼图部分所在椭圆的边界矩形的宽度。 |
| 高度 | Int32 | 定义饼图部分所在椭圆的边界矩形的高度。 |
| startAngle | Int32 | 从 x 轴顺时针测量到饼形区域第一边的角度（度）。 |
| sweepAngle | Int32 | 角度（以度为单位），沿顺时针方向从 *startAngle* 参数测量到饼图部分的第二侧。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。 |

### 另请参见

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)


