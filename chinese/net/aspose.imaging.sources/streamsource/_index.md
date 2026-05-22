---
title: "类 StreamSource"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Sources.StreamSource 类。表示流源"
type: docs
weight: 11700
url: /zh/net/aspose.imaging.sources/streamsource/
---
## StreamSource class

表示流源。

```csharp
public sealed class StreamSource : Source
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [StreamSource](streamsource/#constructor)() | 初始化 `StreamSource` 类的新实例。 |
| [StreamSource](streamsource/#constructor_1)(Stream) | 初始化 `StreamSource` 类的新实例。 |
| [StreamSource](streamsource/#constructor_2)(Stream, bool) | 初始化 `StreamSource` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [DisposeStream](../../aspose.imaging.sources/streamsource/disposestream/) { get; } | 获取一个值，指示是否在容器被释放时处置流。 |
| [Stream](../../aspose.imaging.sources/streamsource/stream/) { get; } | 获取流。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [GetStreamContainer](../../aspose.imaging.sources/streamsource/getstreamcontainer/)() | 获取流容器。 |

## 示例

此示例演示了使用 System.IO.Stream 创建新图像文件（JPEG 类型）。

```csharp
[C#]

//创建 JpegOptions 的实例并设置其各种属性。
Aspose.Imaging.ImageOptions.JpegOptions jpegOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

//创建 System.IO.Stream 的实例。
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.jpeg", System.IO.FileMode.Create);

//为 JpegOptions 实例定义 source 属性。
//第二个布尔参数决定在超出作用域后是否释放 Stream。
jpegOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream, true);

//创建 Image 的实例，并使用 JpegOptions 作为参数调用 Create 方法来初始化 Image 对象。
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(jpegOptions, 500, 500))
{
    //进行一些图像处理
}
```

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

* class [Source](../../aspose.imaging/source/)
* namespace [Aspose.Imaging.Sources](../../aspose.imaging.sources/)
* assembly [Aspose.Imaging](../../)


