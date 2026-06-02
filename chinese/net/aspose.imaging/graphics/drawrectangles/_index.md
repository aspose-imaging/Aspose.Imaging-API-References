---
title: "Graphics.DrawRectangles"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Graphics 方法。绘制一系列由 RectangleF 结构指定的矩形。"
type: docs
weight: 320
url: /zh/net/aspose.imaging/graphics/drawrectangles/
---
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

绘制一系列由 [`RectangleF`](../../rectanglef/) 结构指定的矩形。

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 用于确定矩形轮廓的颜色、宽度和样式。 |
| rects | RectangleF[] | [`RectangleF`](../../rectanglef/) 结构数组，表示要绘制的矩形。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。-or- *rects* 为 null。 |

### 另请参见

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

绘制一系列由 [`Rectangle`](../../rectangle/) 结构指定的矩形。

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 用于确定矩形轮廓的颜色、宽度和样式。 |
| rects | Rectangle[] | [`Rectangle`](../../rectangle/) 结构数组，表示要绘制的矩形。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。-or- *rects* 为 null。 |

## 示例

此示例展示了 Pen 对象的创建和使用。示例创建了一个新的 Image 并在图像表面绘制矩形。

```csharp
[C#]

//创建 BmpOptions 的实例并设置其各种属性
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//创建 FileCreateSource 的实例并将其指定为 BmpOptions 实例的 Source
//第二个 Boolean 参数决定要创建的文件是否为 IsTemporal
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\sample.bmp", false);

//在指定路径创建 Image 的实例
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //创建 Graphics 的实例并使用 Image 对象进行初始化
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    //使用白色清除 Graphics 表面
    graphics.Clear(Aspose.Imaging.Color.White);

    //创建颜色为 Red、宽度为 5 的 Pen 实例
    Aspose.Imaging.Pen pen = new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 5f);

    //创建 HatchBrush 的实例并设置其属性
    Aspose.Imaging.Brushes.HatchBrush brush = new Aspose.Imaging.Brushes.HatchBrush();
    brush.BackgroundColor = Aspose.Imaging.Color.Wheat;
    brush.ForegroundColor = Aspose.Imaging.Color.Red;

    //创建 Pen 的实例
    //使用 HatchBrush 对象和宽度进行初始化
    Aspose.Imaging.Pen brusedpen = new Pen(brush, 5);

    //通过指定 Pen 对象绘制矩形
    graphics.DrawRectangles(pen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(210, 210), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 310), new Aspose.Imaging.Size(100, 100))
    });

    //通过指定 Pen 对象绘制矩形
    graphics.DrawRectangles(brusedpen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 310), new Aspose.Imaging.Size(100, 100))
    });

    // 保存所有更改。
    image.Save();
}
```

### 另请参见

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)


