---
title: DrawString
second_title: Aspose.Imaging for .NET API 参考
description: 在指定位置绘制指定文本字符串Brushaspose.imaging/brush和Fontaspose.imaging/font对象.
type: docs
weight: 320
url: /zh/aspose.imaging/graphics/drawstring/
---
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

在指定位置绘制指定文本字符串[`Brush`](../../brush)和[`Font`](../../font)对象.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| s | String | 要绘制的字符串。 |
| font | Font | [`Font`](../../font)定义字符串的文本格式。 |
| brush | Brush | [`Brush`](../../brush)它决定了绘制文本的颜色和纹理。 |
| x | Single | 绘制文本左上角的 x 坐标。 |
| y | Single | 绘制文本左上角的 y 坐标。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *brush*为空。 -或- *s*一片空白。 |

### 也可以看看

* class [Font](../../font)
* class [Brush](../../brush)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.Imaging](../../graphics)
* 部件 [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

在指定位置绘制指定文本字符串[`Brush`](../../brush)和[`Font`](../../font)对象.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| s | String | 要绘制的字符串。 |
| font | Font | [`Font`](../../font)定义字符串的文本格式。 |
| brush | Brush | [`Brush`](../../brush)它决定了绘制文本的颜色和纹理。 |
| point | PointF | [`PointF`](../../pointf)结构，指定绘制文本的左上角。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *brush*为空。 -或- *s*一片空白。 |

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

* class [Font](../../font)
* class [Brush](../../brush)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.Imaging](../../graphics)
* 部件 [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

在指定位置绘制指定文本字符串[`Brush`](../../brush)和[`Font`](../../font)使用指定格式属性的对象[`StringFormat`](../../stringformat) .

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| s | String | 要绘制的字符串。 |
| font | Font | [`Font`](../../font)定义字符串的文本格式。 |
| brush | Brush | [`Brush`](../../brush)它决定了绘制文本的颜色和纹理。 |
| x | Single | 绘制文本左上角的 x 坐标。 |
| y | Single | 绘制文本左上角的 y 坐标。 |
| format | StringFormat | [`StringFormat`](../../stringformat)指定应用于绘制文本的格式属性，例如行间距和对齐方式。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *brush*为空。 -或- *s*一片空白。 |

### 也可以看看

* class [Font](../../font)
* class [Brush](../../brush)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.Imaging](../../graphics)
* 部件 [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

在指定位置绘制指定文本字符串[`Brush`](../../brush)和[`Font`](../../font)使用指定格式属性的对象[`StringFormat`](../../stringformat) .

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| s | String | 要绘制的字符串。 |
| font | Font | [`Font`](../../font)定义字符串的文本格式。 |
| brush | Brush | [`Brush`](../../brush)它决定了绘制文本的颜色和纹理。 |
| point | PointF | [`PointF`](../../pointf)结构，指定绘制文本的左上角。 |
| format | StringFormat | [`StringFormat`](../../stringformat)指定应用于绘制文本的格式属性，例如行间距和对齐方式。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *brush*为空。 -或- *s*一片空白。 |

### 也可以看看

* class [Font](../../font)
* class [Brush](../../brush)
* struct [PointF](../../pointf)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.Imaging](../../graphics)
* 部件 [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

用指定的矩形在指定的矩形中绘制指定的文本字符串[`Brush`](../../brush)和[`Font`](../../font)对象.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| s | String | 要绘制的字符串。 |
| font | Font | [`Font`](../../font)定义字符串的文本格式。 |
| brush | Brush | [`Brush`](../../brush)它决定了绘制文本的颜色和纹理。 |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef)指定绘制文本位置的结构。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *brush*为空。 -或- *s*一片空白。 |

### 也可以看看

* class [Font](../../font)
* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.Imaging](../../graphics)
* 部件 [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

用指定的矩形在指定的矩形中绘制指定的文本字符串[`Brush`](../../brush)和[`Font`](../../font)使用指定格式属性的对象[`StringFormat`](../../stringformat) .

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| s | String | 要绘制的字符串。 |
| font | Font | [`Font`](../../font)定义字符串的文本格式。 |
| brush | Brush | [`Brush`](../../brush)它决定了绘制文本的颜色和纹理。 |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef)指定绘制文本位置的结构。 |
| format | StringFormat | [`StringFormat`](../../stringformat)指定应用于绘制文本的格式属性，例如行间距和对齐方式。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *brush*为空。 -或- *s*为空。 -或- *brush*一片空白。 |

### 也可以看看

* class [Font](../../font)
* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.Imaging](../../graphics)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
