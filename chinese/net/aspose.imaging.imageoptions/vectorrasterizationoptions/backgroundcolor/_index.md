---
title: "VectorRasterizationOptions.BackgroundColor"
second_title: "Aspose.Imaging for .NET API 参考"
description: "VectorRasterizationOptions 属性。获取或设置背景颜色"
type: docs
weight: 20
url: /zh/net/aspose.imaging.imageoptions/vectorrasterizationoptions/backgroundcolor/
---
## VectorRasterizationOptions.BackgroundColor property

获取或设置背景颜色。

```csharp
public Color BackgroundColor { get; set; }
```

## 示例

此示例展示了如何使用 WmfRasterizationOptions 从文件加载 WMF 图像并将其转换为 SVG。

```csharp
[C#]

string dir = "c:\\temp\\";

// 使用 Aspose.Imaging.Image.Load 是加载包括 WMF 在内的所有类型图像的统一方式。
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "test.wmf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();
        
    // 文本将被转换为形状。
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.WmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions();

    // 绘图表面的背景颜色。
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

    // 页面大小。
    rasterizationOptions.PageSize = wmfImage.Size;

    // 如果存在嵌入的 emf，则渲染 emf；否则渲染 wmf。
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Wmf.WmfRenderMode.Auto;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    wmfImage.Save(dir + "test.output.svg", saveOptions);
}
```

此示例展示了如何使用 EmfRasterizationOptions 从文件加载 EMF 图像并将其转换为 SVG。

```csharp
[C#]

string dir = "c:\\temp\\";

// 使用 Aspose.Imaging.Image.Load 是加载包括 EMF 在内的所有类型图像的统一方式。
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();

    // 文本将被转换为形状。
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.EmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions();

    // 绘图表面的背景颜色。
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

    // 页面大小。
    rasterizationOptions.PageSize = emfImage.Size;

    // 如果存在嵌入的 emf，则渲染 emf；否则渲染 wmf。
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Emf.EmfRenderMode.Auto;

    // 设置水平边距
    rasterizationOptions.BorderX = 50;

    // 设置垂直边距
    rasterizationOptions.BorderY = 50;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    emfImage.Save(dir + "test.output.svg", saveOptions);
}
```

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

* struct [Color](../../../aspose.imaging/color/)
* class [VectorRasterizationOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../vectorrasterizationoptions/)
* assembly [Aspose.Imaging](../../../)


