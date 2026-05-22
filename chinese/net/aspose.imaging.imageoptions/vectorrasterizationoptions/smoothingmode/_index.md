---
title: "VectorRasterizationOptions.SmoothingMode"
second_title: "Aspose.Imaging for .NET API 参考"
description: "VectorRasterizationOptions 属性。获取或设置平滑模式"
type: docs
weight: 120
url: /zh/net/aspose.imaging.imageoptions/vectorrasterizationoptions/smoothingmode/
---
## VectorRasterizationOptions.SmoothingMode property

获取或设置平滑模式。

```csharp
public SmoothingMode SmoothingMode { get; set; }
```

### Property Value

平滑模式。

## 示例

此示例展示了如何从文件加载 SVG 图像并使用各种选项将其光栅化为 PNG。

```csharp
[C#]

string dir = "c:\\temp\\";

// 使用 Aspose.Imaging.Image.Load 是加载图像的统一方式。
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = (Aspose.Imaging.FileFormats.Svg.SvgImage)Aspose.Imaging.Image.Load(dir + "test.svg"))
{
    // 为了光栅化 SVG，我们需要指定光栅化选项。
    Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();

    // 设置图像背景的默认颜色。默认值为白色。
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.Gray;

    // 设置页面大小
    rasterizationOptions.PageSize = svgImage.Size;

    // 对线条、曲线以及填充区域的边缘应用抗锯齿。
    rasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.AntiAlias;

    // 每个字符使用其抗锯齿的字形位图绘制，且不进行 hinting。
    rasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.AntiAlias;

    // 将图像尺寸缩小 10 倍，即输出尺寸为原始尺寸的 10%。
    rasterizationOptions.ScaleX = 0.1f;
    rasterizationOptions.ScaleY = 0.1f;

    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    // 保存为 PNG 文件
    svgImage.Save(dir + "test.output.png", saveOptions);
}
```

### 另请参见

* enum [SmoothingMode](../../../aspose.imaging/smoothingmode/)
* class [VectorRasterizationOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../vectorrasterizationoptions/)
* assembly [Aspose.Imaging](../../../)


