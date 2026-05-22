---
title: "Graphics.DrawCurve"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Graphics 方法。通过指定的 PointF 结构数组绘制基数样条曲线。此方法使用默认张力 0.5。"
type: docs
weight: 210
url: /zh/net/aspose.imaging/graphics/drawcurve/
---
## DrawCurve(Pen, PointF[]) {#drawcurve}

通过指定的 [`PointF`](../../pointf/) 结构数组绘制基数样条曲线。此方法使用默认张力 0.5。

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 决定曲线的颜色、宽度和高度。 |
| points | PointF[] | 定义样条的 [`PointF`](../../pointf/) 结构数组。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。-or- *points* 为 null。 |

### 另请参见

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

使用指定的张力，通过指定的 [`PointF`](../../pointf/) 结构数组绘制基数样条曲线。

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 决定曲线的颜色、宽度和高度。 |
| points | PointF[] | 表示定义曲线的点的 [`PointF`](../../pointf/) 结构数组。 |
| 张力 | 单精度 | 大于或等于 0.0F 的值，用于指定曲线的张力。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。-or- *points* 为 null。 |

### 另请参见

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

通过指定的 [`PointF`](../../pointf/) 结构数组绘制基数样条曲线。绘制从数组的起始位置偏移开始。此方法使用默认张力 0.5。

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 决定曲线的颜色、宽度和高度。 |
| points | PointF[] | 定义样条的 [`PointF`](../../pointf/) 结构数组。 |
| 偏移 | Int32 | 从 *points* 参数数组的第一个元素到曲线起始点的偏移量。 |
| numberOfSegments | Int32 | 起始点之后要包含在曲线中的段数。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。-or- *points* 为 null。 |

### 另请参见

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

通过使用指定张力的指定 [`PointF`](../../pointf/) 结构数组绘制基数样条曲线。绘制从数组的起始位置偏移开始。

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 决定曲线的颜色、宽度和高度。 |
| points | PointF[] | 定义样条的 [`PointF`](../../pointf/) 结构数组。 |
| 偏移 | Int32 | 从 *points* 参数数组的第一个元素到曲线起始点的偏移量。 |
| numberOfSegments | Int32 | 起始点之后要包含在曲线中的段数。 |
| 张力 | 单精度 | 大于或等于 0.0F 的值，用于指定曲线的张力。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。-or- *points* 为 null。 |

### 另请参见

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

通过指定的 [`Point`](../../point/) 结构数组绘制基数样条曲线。

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 决定曲线的颜色、宽度和高度。 |
| points | Point[] | 定义样条曲线的 [`Point`](../../point/) 结构数组。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。-or- *points* 为 null。 |

## 示例

此示例使用 Graphics 类在 Image 表面创建基本形状。为了演示操作，示例创建一个 PNG 格式的新 Image，并使用 Graphics 类提供的 Draw 方法在 Image 表面绘制基本形状。

```csharp
[C#]

//创建 FileStream 的实例
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //创建 PngOptions 的实例并设置其各种属性
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    //为 PngOptions 设置 Source
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //创建 Image 的实例
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        //创建并初始化 Graphics 类的实例
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //清除 Graphics 表面
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        //通过指定具有黑色的 Pen 对象绘制弧线，
        //一个围绕弧线的 Rectangle、起始角度和扫掠角度
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        //通过指定具有蓝色的 Pen 对象和坐标点绘制贝塞尔曲线。
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        //通过指定具有绿色的 Pen 对象和点数组绘制曲线
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        //使用 Pen 对象和围绕的 Rectangle 绘制椭圆
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //绘制直线
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        //绘制饼图扇形
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        //通过指定具有红色的 Pen 对象和点数组绘制多边形
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        //绘制矩形
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        //创建 SolidBrush 对象并设置其各种属性
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        //使用 SolidBrush 对象和 Font 在特定点绘制字符串
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // 保存所有更改。
        image.Save();
    }
}
```

### 另请参见

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

使用指定张力，通过指定的 [`Point`](../../point/) 结构数组绘制基数样条曲线。

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 决定曲线的颜色、宽度和高度。 |
| points | Point[] | 定义样条曲线的 [`Point`](../../point/) 结构数组。 |
| 张力 | 单精度 | 大于或等于 0.0F 的值，用于指定曲线的张力。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。-or- *points* 为 null。 |

### 另请参见

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

使用指定张力，通过指定的 [`Point`](../../point/) 结构数组绘制基数样条曲线。

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 决定曲线的颜色、宽度和高度。 |
| points | Point[] | 定义样条曲线的 [`Point`](../../point/) 结构数组。 |
| 偏移 | Int32 | 从 *points* 参数数组的第一个元素到曲线起始点的偏移量。 |
| numberOfSegments | Int32 | 起始点之后要包含在曲线中的段数。 |
| 张力 | 单精度 | 大于或等于 0.0F 的值，用于指定曲线的张力。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。-or- *points* 为 null。 |

### 另请参见

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)


