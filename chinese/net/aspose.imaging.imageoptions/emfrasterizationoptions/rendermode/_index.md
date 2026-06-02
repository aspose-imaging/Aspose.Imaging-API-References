---
title: "EmfRasterizationOptions.RenderMode"
second_title: "Aspose.Imaging for .NET API 参考"
description: "EmfRasterizationOptions 属性。获取或设置渲染模式"
type: docs
weight: 20
url: /zh/net/aspose.imaging.imageoptions/emfrasterizationoptions/rendermode/
---
## EmfRasterizationOptions.RenderMode property

获取或设置渲染模式。

```csharp
public EmfRenderMode RenderMode { get; set; }
```

### Property Value

渲染模式。

## 示例

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

* enum [EmfRenderMode](../../../aspose.imaging.fileformats.emf/emfrendermode/)
* class [EmfRasterizationOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../emfrasterizationoptions/)
* assembly [Aspose.Imaging](../../../)


