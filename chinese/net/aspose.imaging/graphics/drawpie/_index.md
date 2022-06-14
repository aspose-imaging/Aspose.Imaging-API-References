---
title: DrawPie
second_title: Aspose.Imaging for .NET API 参考
description: 绘制由RectangleFaspose.imaging/rectanglef结构和两条径向线指定的椭圆定义的饼形
type: docs
weight: 280
url: /zh/net/aspose.imaging/graphics/drawpie/
---
## DrawPie(Pen, RectangleF, float, float) {#drawpie_1}

绘制由[`RectangleF`](../../rectanglef)结构和两条径向线指定的椭圆定义的饼形。

```csharp
public void DrawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)确定颜色、宽度和样式馅饼的形状。 |
| rect | RectangleF | [`RectangleF`](../../rectanglef)结构，表示定义椭圆形的矩形边界。 |
| startAngle | Single | 从 x 轴到饼形第一边顺时针测量的角度。 |
| sweepAngle | Single | 从*startAngle*参数顺时针测量到饼形第二边的角度。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 |

### 也可以看看

* class [Pen](../../pen)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.Imaging](../../graphics)
* 部件 [Aspose.Imaging](../../../)

---

## DrawPie(Pen, float, float, float, float, float, float) {#drawpie_3}

绘制由坐标对、宽度、高度和两条径向线指定的椭圆定义的饼形。

```csharp
public void DrawPie(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)确定颜色、宽度和样式馅饼的形状。 |
| x | Single | 边界矩形左上角的 x 坐标，该边界矩形定义了饼形所在的椭圆。 |
| y | Single | 边界矩形左上角的 y 坐标，该边界矩形定义了饼形所在的椭圆。 |
| width | Single | 边界矩形的宽度，该矩形定义了饼形所来自的椭圆。 |
| height | Single | 边界矩形的高度，它定义了饼形所来自的椭圆。 |
| startAngle | Single | 从 x 轴到饼形第一边顺时针测量的角度。 |
| sweepAngle | Single | 从*startAngle*参数顺时针测量到饼形第二边的角度。 |

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

## DrawPie(Pen, Rectangle, float, float) {#drawpie}

绘制由[`Rectangle`](../../rectangle)结构和两条径向线指定的椭圆定义的饼形。

```csharp
public void DrawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)确定颜色、宽度和样式馅饼的形状。 |
| rect | Rectangle | [`Rectangle`](../../rectangle)结构，表示定义椭圆的边界矩形，饼图来自该矩形。 |
| startAngle | Single | 从 x 轴到饼形第一边顺时针测量的角度。 |
| sweepAngle | Single | 从*startAngle*参数顺时针测量到饼形第二边的角度。 |

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
* struct [Rectangle](../../rectangle)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.Imaging](../../graphics)
* 部件 [Aspose.Imaging](../../../)

---

## DrawPie(Pen, int, int, int, int, int, int) {#drawpie_2}

绘制由坐标对、宽度、高度和两条径向线指定的椭圆定义的饼形。

```csharp
public void DrawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)确定颜色、宽度和样式馅饼的形状。 |
| x | Int32 | 边界矩形左上角的 x 坐标，该边界矩形定义了饼形所在的椭圆。 |
| y | Int32 | 边界矩形左上角的 y 坐标，该边界矩形定义了饼形所在的椭圆。 |
| width | Int32 | 边界矩形的宽度，该矩形定义了饼形所来自的椭圆。 |
| height | Int32 | 边界矩形的高度，它定义了饼形所来自的椭圆。 |
| startAngle | Int32 | 从 x 轴到饼形第一边顺时针测量的角度。 |
| sweepAngle | Int32 | 从*startAngle*参数顺时针测量到饼形第二边的角度。 |

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
