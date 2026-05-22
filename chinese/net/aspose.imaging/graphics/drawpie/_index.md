---
title: "Graphics.DrawPie"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Graphics 方法。绘制由 RectangleF 结构指定的椭圆以及两条径向线定义的饼形。"
type: docs
weight: 290
url: /zh/net/aspose.imaging/graphics/drawpie/
---
## DrawPie(Pen, RectangleF, float, float) {#drawpie_1}

绘制由 [`RectangleF`](../../rectanglef/) 结构指定的椭圆以及两条径向线定义的饼形。

```csharp
public void DrawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 用于确定饼形的颜色、宽度和样式。 |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) 结构，表示定义饼形所来源椭圆的边界矩形。 |
| startAngle | 单精度 | 角度，以度为单位，顺时针从 x 轴测量到饼形的第一条边。 |
| sweepAngle | 单精度 | 角度，以度为单位，顺时针从 *startAngle* 参数测量到饼形的第二条边。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。 |

### 另请参见

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawPie(Pen, float, float, float, float, float, float) {#drawpie_3}

绘制由坐标对、宽度、高度以及两条径向线指定的椭圆定义的饼形。

```csharp
public void DrawPie(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 用于确定饼形的颜色、宽度和样式。 |
| x | 单精度 | 定义饼形来源椭圆的边界矩形左上角的 x 坐标。 |
| y | 单精度 | 定义饼形来源椭圆的边界矩形左上角的 y 坐标。 |
| 宽度 | 单精度 | 定义饼形来源椭圆的边界矩形的宽度。 |
| 高度 | 单精度 | 定义饼形来源椭圆的边界矩形的高度。 |
| startAngle | 单精度 | 角度，以度为单位，顺时针从 x 轴测量到饼形的第一条边。 |
| sweepAngle | 单精度 | 角度，以度为单位，顺时针从 *startAngle* 参数测量到饼形的第二条边。 |

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

## DrawPie(Pen, Rectangle, float, float) {#drawpie}

绘制由 [`Rectangle`](../../rectangle/) 结构指定的椭圆以及两条径向线定义的饼形。

```csharp
public void DrawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 用于确定饼形的颜色、宽度和样式。 |
| rect | Rectangle | [`Rectangle`](../../rectangle/) 结构，表示定义饼形来源椭圆的边界矩形。 |
| startAngle | 单精度 | 角度，以度为单位，顺时针从 x 轴测量到饼形的第一条边。 |
| sweepAngle | 单精度 | 角度，以度为单位，顺时针从 *startAngle* 参数测量到饼形的第二条边。 |

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
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawPie(Pen, int, int, int, int, int, int) {#drawpie_2}

绘制由坐标对、宽度、高度以及两条径向线指定的椭圆定义的饼形。

```csharp
public void DrawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 用于确定饼形的颜色、宽度和样式。 |
| x | Int32 | 定义饼形来源椭圆的边界矩形左上角的 x 坐标。 |
| y | Int32 | 定义饼形来源椭圆的边界矩形左上角的 y 坐标。 |
| 宽度 | Int32 | 定义饼形来源椭圆的边界矩形的宽度。 |
| 高度 | Int32 | 定义饼形来源椭圆的边界矩形的高度。 |
| startAngle | Int32 | 角度，以度为单位，顺时针从 x 轴测量到饼形的第一条边。 |
| sweepAngle | Int32 | 角度，以度为单位，顺时针从 *startAngle* 参数测量到饼形的第二条边。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。 |

### 另请参见

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)


