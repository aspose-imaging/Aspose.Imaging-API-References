---
title: "WmfRasterizationOptions.RenderMode"
second_title: "Aspose.Imaging for .NET API 参考"
description: "WmfRasterizationOptions 属性。获取或设置 WMF 渲染模式。"
type: docs
weight: 20
url: /zh/net/aspose.imaging.imageoptions/wmfrasterizationoptions/rendermode/
---
## WmfRasterizationOptions.RenderMode property

获取或设置 WMF 渲染模式。

```csharp
public WmfRenderMode RenderMode { get; set; }
```

### Property Value

WMF 渲染模式。

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

### 另请参见

* enum [WmfRenderMode](../../../aspose.imaging.fileformats.wmf/wmfrendermode/)
* class [WmfRasterizationOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../wmfrasterizationoptions/)
* assembly [Aspose.Imaging](../../../)


