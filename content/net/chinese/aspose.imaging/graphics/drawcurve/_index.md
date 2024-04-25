---
title: DrawCurve
second_title: Aspose.Imaging for .NET API 参考
description: 通过指定的数组绘制基数样条PointFaspose.imaging/pointf结构此方法使用默认张力 0.5.
type: docs
weight: 200
url: /zh/aspose.imaging/graphics/drawcurve/
---
## DrawCurve(Pen, PointF[]) {#drawcurve}

通过指定的数组绘制基数样条[`PointF`](../../pointf)结构。此方法使用默认张力 0.5.

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)它决定了曲线的颜色、宽度和高度。 |
| points | PointF[] | 数组[`PointF`](../../pointf)定义样条的结构。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 -或- *points*一片空白。 |

### 也可以看看

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.Imaging](../../graphics)
* 部件 [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

通过指定的数组绘制基数样条[`PointF`](../../pointf)使用指定张力的结构。

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)它决定了曲线的颜色、宽度和高度。 |
| points | PointF[] | 数组[`PointF`](../../pointf)表示定义曲线的点的结构。 |
| tension | Single | 大于或等于 0.0F 的值指定曲线的张力。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 -或- *points*一片空白。 |

### 也可以看看

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.Imaging](../../graphics)
* 部件 [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

通过指定的数组绘制基数样条[`PointF`](../../pointf)结构。绘图从数组的开头偏移开始。 此方法使用默认张力 0.5.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)它决定了曲线的颜色、宽度和高度。 |
| points | PointF[] | 数组[`PointF`](../../pointf)定义样条的结构。 |
| offset | Int32 | 与数组中第一个元素的偏移量*points*参数到曲线的起点。 |
| numberOfSegments | Int32 | 要包含在曲线中的起点之后的段数。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 -或- *points*一片空白。 |

### 也可以看看

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.Imaging](../../graphics)
* 部件 [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

通过指定的数组绘制基数样条[`PointF`](../../pointf)使用指定张力的结构。绘图从数组的开头偏移开始。

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)它决定了曲线的颜色、宽度和高度。 |
| points | PointF[] | 数组[`PointF`](../../pointf)定义样条的结构。 |
| offset | Int32 | 与数组中第一个元素的偏移量*points*参数到曲线的起点。 |
| numberOfSegments | Int32 | 要包含在曲线中的起点之后的段数。 |
| tension | Single | 大于或等于 0.0F 的值指定曲线的张力。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 -或- *points*一片空白。 |

### 也可以看看

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.Imaging](../../graphics)
* 部件 [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

通过指定的数组绘制基数样条[`Point`](../../point)结构.

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)它决定了曲线的颜色、宽度和高度。 |
| points | Point[] | 数组[`Point`](../../point)定义样条的结构。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 -或- *points*一片空白。 |

### 例子

此示例使用 Graphics 类在 Image 表面上创建原始形状。为了演示该操作，该示例创建一个 PNG 格式的新图像，并使用 Graphics 类公开的 Draw 方法在图像表面上绘制原始形状

```csharp
[C#]

//创建一个FileStream实例
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //创建一个PngOptions实例并设置它的各种属性
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    //设置PngOptions的来源
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //创建一个Image实例 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        //创建并初始化一个Graphics类的实例
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //清除图形表面
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        //通过指定具有黑色颜色的Pen对象来绘制弧线， 
        //一个围绕圆弧的矩形，起始角和扫角
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        //通过指定具有蓝色和坐标点的 Pen 对象来绘制 Bezier。
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        //通过指定具有绿色的 Pen 对象和点数组来绘制曲线
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        //使用 Pen 对象和周围的 Rectangle 绘制一个椭圆
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //画一条线 
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        //画一个饼段
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        //通过指定具有红色的 Pen 对象和点数组来绘制多边形
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        //画一个矩形
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        //创建一个SolidBrush对象并设置它的各种属性
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        //使用 SolidBrush 对象和字体在特定点绘制一个字符串
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // 保存所有更改。
        image.Save();
    }
}
```

### 也可以看看

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.Imaging](../../graphics)
* 部件 [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

通过指定的数组绘制基数样条[`Point`](../../point)使用指定张力的结构。

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)它决定了曲线的颜色、宽度和高度。 |
| points | Point[] | 数组[`Point`](../../point)定义样条的结构。 |
| tension | Single | 大于或等于 0.0F 的值指定曲线的张力。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 -或- *points*一片空白。 |

### 也可以看看

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.Imaging](../../graphics)
* 部件 [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

通过指定的数组绘制基数样条[`Point`](../../point)使用指定张力的结构。

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)它决定了曲线的颜色、宽度和高度。 |
| points | Point[] | 数组[`Point`](../../point)定义样条的结构。 |
| offset | Int32 | 与数组中第一个元素的偏移量*points*参数到曲线的起点。 |
| numberOfSegments | Int32 | 要包含在曲线中的起点之后的段数。 |
| tension | Single | 大于或等于 0.0F 的值指定曲线的张力。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 -或- *points*一片空白。 |

### 也可以看看

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.Imaging](../../graphics)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
