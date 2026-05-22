---
title: "PngOptions.FilterType"
second_title: "Aspose.Imaging for .NET API 参考"
description: "PngOptions 属性。获取或设置在 PNG 文件保存过程中使用的过滤器类型"
type: docs
weight: 40
url: /zh/net/aspose.imaging.imageoptions/pngoptions/filtertype/
---
## PngOptions.FilterType property

获取或设置在 png 文件保存过程中使用的过滤器类型。

```csharp
public PngFilterType FilterType { get; set; }
```

## 示例

此示例展示了如何使用指定的选项创建 PNG 图像，填充线性渐变颜色并将其保存到文件。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();

// 每个颜色通道的位数
createOptions.BitDepth = 8;

// 每个像素是一个 (红, 绿, 蓝) 三元组，后跟 alpha 分量。
createOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

// 最大压缩级别。
createOptions.CompressionLevel = 9;

// 使用过滤器可以更有效地压缩连续色调图像。
createOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Sub;

// 使用渐进式加载
createOptions.Progressive = true;

// 使用自定义参数创建 PNG 图像。
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(createOptions, 100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // 用半透明渐变填充图像。
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    // 保存到文件。
    pngImage.Save(dir + "output.explicitoptions.png");
}
```

以下示例展示了不同过滤器类型如何影响输出 PNG 图像的大小。

```csharp
[C#]

Aspose.Imaging.FileFormats.Png.PngFilterType[] filterTypes = new Aspose.Imaging.FileFormats.Png.PngFilterType[]
{
    Aspose.Imaging.FileFormats.Png.PngFilterType.None,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Up,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Sub,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Paeth,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Avg,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Adaptive,
};

foreach (Aspose.Imaging.FileFormats.Png.PngFilterType filterType in filterTypes)
{
    Aspose.Imaging.ImageOptions.PngOptions options = new Aspose.Imaging.ImageOptions.PngOptions();

    using (Aspose.Imaging.Image image = Image.Load("c:\\temp\\sample.png"))
    {
        // 设置过滤器类型
        options.FilterType = filterType;

        using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
        {
            image.Save(stream, options);
            System.Console.WriteLine("The filter type is {0}, the output image size is {1} bytes.", filterType, stream.Length);
        }
    }
}

//输出可能如下所示：
//过滤类型为 None，输出图像大小为 116845 字节。
//过滤类型为 Up，输出图像大小为 86360 字节。
//过滤类型为 Sub，输出图像大小为 94907 字节。
//过滤类型为 Paeth，输出图像大小为 86403 字节。
//过滤类型为 Avg，输出图像大小为 89956 字节。
//过滤类型为 Adaptive，输出图像大小为 97248 字节。
```

以下示例展示了如何使用各种选项将图像保存为 PNG 格式。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100x100 像素的 PNG 图像。
// 您也可以从文件或流中加载任何受支持格式的图像。
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // 用蓝色透明渐变填充图像。
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    // 渐进式加载。
    saveOptions.Progressive = true;

    // 将水平和垂直分辨率设置为每英寸 96 像素。
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    // 每个像素是一个 (红, 绿, 蓝) 三元组，后跟 alpha 通道。
    saveOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

    // 设置最高压缩级别。
    saveOptions.CompressionLevel = 9;

    // 这是最佳压缩，但执行时间最慢。
    // 自适应过滤意味着保存过程会为每一行数据选择最合适的过滤器。
    saveOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Adaptive;

    // 每个通道的位数。
    saveOptions.BitDepth = 8;

    // 保存到文件。
    pngImage.Save(dir + "output.png", saveOptions);
}
```

### 另请参见

* enum [PngFilterType](../../../aspose.imaging.fileformats.png/pngfiltertype/)
* class [PngOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../pngoptions/)
* assembly [Aspose.Imaging](../../../)


