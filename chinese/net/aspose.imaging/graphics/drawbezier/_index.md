---
title: "Graphics.DrawBezier"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Graphics 方法。绘制由四对有序坐标点定义的 Bézier 样条曲线。"
type: docs
weight: 180
url: /zh/net/aspose.imaging/graphics/drawbezier/
---
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

绘制由四对有序坐标点（表示点）定义的贝塞尔样条。

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 用于确定曲线的颜色、宽度和样式。 |
| x1 | 单精度 | 曲线起始点的 x 坐标。 |
| y1 | 单精度 | 曲线起始点的 y 坐标。 |
| x2 | 单精度 | 曲线第一个控制点的 x 坐标。 |
| y2 | 单精度 | 曲线第一个控制点的 y 坐标。 |
| x3 | 单精度 | 曲线第二个控制点的 x 坐标。 |
| y3 | 单精度 | 曲线第二个控制点的 y 坐标。 |
| x4 | 单精度 | 曲线结束点的 x 坐标。 |
| y4 | 单精度 | 曲线结束点的 y 坐标。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。 |

### 另请参见

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

绘制由四个 [`PointF`](../../pointf/) 结构定义的 Bézier 样条。

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 用于确定曲线的颜色、宽度和样式。 |
| pt1 | PointF | [`PointF`](../../pointf/) 结构，表示曲线的起始点。 |
| pt2 | PointF | [`PointF`](../../pointf/) 结构，表示曲线的第一个控制点。 |
| pt3 | PointF | [`PointF`](../../pointf/) 结构，表示曲线的第二个控制点。 |
| pt4 | PointF | [`PointF`](../../pointf/) 结构，表示曲线的结束点。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。 |

### 另请参见

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

绘制由四个 [`Point`](../../point/) 结构定义的 Bézier 样条。

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 结构，决定曲线的颜色、宽度和样式。 |
| pt1 | Point | [`Point`](../../point/) 结构，表示曲线的起始点。 |
| pt2 | Point | [`Point`](../../point/) 结构，表示曲线的第一个控制点。 |
| pt3 | Point | [`Point`](../../point/) 结构，表示曲线的第二个控制点。 |
| pt4 | Point | [`Point`](../../point/) 结构，表示曲线的结束点。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。 |

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


