---
title: "SvgOptions.TextAsShapes"
second_title: "Aspose.Imaging for .NET API 参考"
description: "SvgOptions 属性。获取或设置一个值，指示文本是否必须渲染为形状"
type: docs
weight: 50
url: /zh/net/aspose.imaging.imageoptions/svgoptions/textasshapes/
---
## SvgOptions.TextAsShapes property

获取或设置一个值，指示文本是否必须渲染为形状。

```csharp
public bool TextAsShapes { get; set; }
```

### Property Value

`true` 表示在转换过程中所有文本都被转换为 SVG 形状；否则为 `false`。

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

### 另请参见

* class [SvgOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../svgoptions/)
* assembly [Aspose.Imaging](../../../)


