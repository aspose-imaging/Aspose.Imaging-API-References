---
title: "EllipseShape.EllipseShape"
second_title: "Aspose.Imaging for .NET API 参考"
description: "EllipseShape 构造函数。初始化 EllipseShape 类的新实例"
type: docs
weight: 10
url: /zh/net/aspose.imaging.shapes/ellipseshape/ellipseshape/
---
## EllipseShape() {#constructor}

初始化 [`EllipseShape`](../) 类的新实例。

```csharp
public EllipseShape()
```

### 另请参见

* class [EllipseShape](../)
* namespace [Aspose.Imaging.Shapes](../../ellipseshape/)
* assembly [Aspose.Imaging](../../../)

---

## EllipseShape(RectangleF) {#constructor_1}

初始化 [`EllipseShape`](../) 类的新实例。

```csharp
public EllipseShape(RectangleF rectangle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 矩形 | RectangleF | 矩形。 |

## 示例

此示例使用 GraphicsPath 和 Graphics 类在图像表面上创建和操作图形。示例创建一个新的 Image（Tiff 类型），清除表面并借助 GraphicsPath 类绘制路径。最后调用 Graphics 类公开的 DrawPath 方法在表面上渲染这些路径。

```csharp
[C#]

//创建 FileStream 的实例
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    //创建 TiffOptions 的实例并设置其各种属性
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    //为 ImageOptions 实例设置源
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //创建 Image 的实例
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        //创建并初始化 Graphics 类的实例
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //清除 Graphics 表面
        graphics.Clear(Color.Wheat);

        //创建 GraphicsPath 类的实例
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        //创建 Figure 类的实例
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        //向 Figure 对象添加形状
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        //将 Figure 对象添加到 GraphicsPath
        graphicspath.AddFigure(figure);

        //使用颜色为 Black 的 Pen 对象绘制路径
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // 保存所有更改。
        image.Save();
    }
}
```

### 另请参见

* struct [RectangleF](../../../aspose.imaging/rectanglef/)
* class [EllipseShape](../)
* namespace [Aspose.Imaging.Shapes](../../ellipseshape/)
* assembly [Aspose.Imaging](../../../)


