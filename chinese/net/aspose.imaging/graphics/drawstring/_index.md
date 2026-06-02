---
title: "Graphics.DrawString"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Graphics 方法。使用指定的 Brush 和 Font 对象在指定位置绘制指定的文本字符串。"
type: docs
weight: 330
url: /zh/net/aspose.imaging/graphics/drawstring/
---
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

在指定位置使用指定的 [`Brush`](../../brush/) 和 [`Font`](../../font/) 对象绘制指定的文本字符串。

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | String | 要绘制的字符串。 |
| font | Font | 定义字符串文本格式的 [`Font`](../../font/)。 |
| brush | Brush | 决定绘制文本颜色和纹理的 [`Brush`](../../brush/)。 |
| x | 单精度 | 绘制文本左上角的 x 坐标。 |
| y | 单精度 | 绘制文本左上角的 y 坐标。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。-or- *s* 为 null。 |

### 另请参见

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

在指定位置使用指定的 [`Brush`](../../brush/) 和 [`Font`](../../font/) 对象绘制指定的文本字符串。

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | String | 要绘制的字符串。 |
| font | Font | 定义字符串文本格式的 [`Font`](../../font/)。 |
| brush | Brush | 决定绘制文本颜色和纹理的 [`Brush`](../../brush/)。 |
| point | PointF | 指定绘制文本左上角的 [`PointF`](../../pointf/) 结构。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。-or- *s* 为 null。 |

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

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

使用指定的 [`StringFormat`](../../stringformat/) 的格式属性，在指定位置使用指定的 [`Brush`](../../brush/) 和 [`Font`](../../font/) 对象绘制指定的文本字符串。

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | String | 要绘制的字符串。 |
| font | Font | 定义字符串文本格式的 [`Font`](../../font/)。 |
| brush | Brush | 决定绘制文本颜色和纹理的 [`Brush`](../../brush/)。 |
| x | 单精度 | 绘制文本左上角的 x 坐标。 |
| y | 单精度 | 绘制文本左上角的 y 坐标。 |
| format | StringFormat | 指定绘制文本时使用的格式属性（如行间距和对齐方式）的 [`StringFormat`](../../stringformat/)。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。-or- *s* 为 null。 |

### 另请参见

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

使用指定的 [`StringFormat`](../../stringformat/) 的格式属性，在指定位置使用指定的 [`Brush`](../../brush/) 和 [`Font`](../../font/) 对象绘制指定的文本字符串。

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | String | 要绘制的字符串。 |
| font | Font | 定义字符串文本格式的 [`Font`](../../font/)。 |
| brush | Brush | 决定绘制文本颜色和纹理的 [`Brush`](../../brush/)。 |
| point | PointF | 指定绘制文本左上角的 [`PointF`](../../pointf/) 结构。 |
| format | StringFormat | 指定绘制文本时使用的格式属性（如行间距和对齐方式）的 [`StringFormat`](../../stringformat/)。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。-or- *s* 为 null。 |

### 另请参见

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

在指定的矩形中使用指定的 [`Brush`](../../brush/) 和 [`Font`](../../font/) 对象绘制指定的文本字符串。

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | String | 要绘制的字符串。 |
| font | Font | 定义字符串文本格式的 [`Font`](../../font/)。 |
| brush | Brush | 决定绘制文本颜色和纹理的 [`Brush`](../../brush/)。 |
| layoutRectangle | RectangleF | `[`RectangleF`](../../rectanglef/) 结构，指定绘制文本的位置。` |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。-or- *s* 为 null。 |

### 另请参见

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

在指定的矩形中使用指定的 [`Brush`](../../brush/) 和 [`Font`](../../font/) 对象，并使用指定的 [`StringFormat`](../../stringformat/) 的格式属性绘制指定的文本字符串。

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | String | 要绘制的字符串。 |
| font | Font | 定义字符串文本格式的 [`Font`](../../font/)。 |
| brush | Brush | 决定绘制文本颜色和纹理的 [`Brush`](../../brush/)。 |
| layoutRectangle | RectangleF | `[`RectangleF`](../../rectanglef/) 结构，指定绘制文本的位置。` |
| format | StringFormat | 指定绘制文本时使用的格式属性（如行间距和对齐方式）的 [`StringFormat`](../../stringformat/)。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。-or- *s* 为 null。-or- *brush* 为 null。 |

### 另请参见

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)


