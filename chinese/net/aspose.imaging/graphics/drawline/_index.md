---
title: DrawLine
second_title: Aspose.Imaging for .NET API 参考
description: 绘制一条连接两个Pointaspose.imaging/point结构的线
type: docs
weight: 250
url: /zh/net/aspose.imaging/graphics/drawline/
---
## DrawLine(Pen, Point, Point) {#drawline}

绘制一条连接两个[`Point`](../../point)结构的线。

```csharp
public void DrawLine(Pen pen, Point point1, Point point2)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)确定颜色、宽度和样式线。 |
| point1 | Point | [`Point`](../../point)结构，表示要连接的第一个点。 |
| point2 | Point | [`Point`](../../point)结构，表示要连接的第二个点。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 |

### 例子

此示例使用 Graphics 类在图像表面上创建原始形状。为了演示该操作，该示例创建一个 PNG 格式的新 Image，并使用 Graphics 类

```csharp
[C#]

//创建一个 FileStream
 的实例
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //创建一个PngOptions实例并设置它的各种属性
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

        //设置PngOptions
的源
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //创建一个Image
的实例
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        //创建并初始化一个Graphics class
的实例
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //清除图形surface
        graphics.Clear(Aspose.Imaging.Color.Wheat);

            //通过指定具有黑色的Pen对象绘制一个弧线，
            //一个围绕圆弧的矩形，起始角和扫角
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

            //通过指定具有蓝色和坐标点的Pen对象来绘制贝塞尔曲线。
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

            //通过指定具有绿色的 Pen 对象和 Points
 数组来绘制曲线
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        //使用 Pen 对象和周围的 Rectangle
 绘制一个椭圆
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //画一条线
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

            //画一个饼段
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

            //通过指定具有红色的 Pen 对象和 Points
 数组来绘制多边形
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        //画一个Rectangle
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

            //创建一个SolidBrush对象并设置它的各种属性
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        //使用 SolidBrush 对象和字体在特定的 Point
 处绘制一个字符串
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

## DrawLine(Pen, PointF, PointF) {#drawline_1}

绘制一条连接两个[`PointF`](../../pointf)结构的线。

```csharp
public void DrawLine(Pen pen, PointF point1, PointF point2)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)确定颜色、宽度和样式线。 |
| point1 | PointF | [`PointF`](../../pointf)结构，表示要连接的第一个点。 |
| point2 | PointF | [`PointF`](../../pointf)结构，表示要连接的第二个点。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 |

### 也可以看看

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.Imaging](../../graphics)
* 部件 [Aspose.Imaging](../../../)

---

## DrawLine(Pen, int, int, int, int) {#drawline_2}

绘制一条连接坐标对指定的两个点的线。

```csharp
public void DrawLine(Pen pen, int x1, int y1, int x2, int y2)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)确定颜色、宽度和样式线。 |
| x1 | Int32 | 第一个点的 x 坐标。 |
| y1 | Int32 | 第一个点的 y 坐标。 |
| x2 | Int32 | 第二个点的 x 坐标。 |
| y2 | Int32 | 第二个点的 y 坐标。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 |

### 也可以看看

* class [Pen](../../pen)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.Imaging](../../graphics)
* 部件 [Aspose.Imaging](../../../)

---

## DrawLine(Pen, float, float, float, float) {#drawline_3}

绘制一条连接坐标对指定的两个点的线。

```csharp
public void DrawLine(Pen pen, float x1, float y1, float x2, float y2)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)确定颜色、宽度和样式线。 |
| x1 | Single | 第一个点的 x 坐标。 |
| y1 | Single | 第一个点的 y 坐标。 |
| x2 | Single | 第二个点的 x 坐标。 |
| y2 | Single | 第二个点的 y 坐标。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 |

### 也可以看看

* class [Pen](../../pen)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.Imaging](../../graphics)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
