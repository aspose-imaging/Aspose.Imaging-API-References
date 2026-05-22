---
title: "VectorRasterizationOptions.Positioning"
second_title: "Aspose.Imaging for .NET API 参考"
description: "VectorRasterizationOptions 属性。获取或设置定位"
type: docs
weight: 100
url: /zh/net/aspose.imaging.imageoptions/vectorrasterizationoptions/positioning/
---
## VectorRasterizationOptions.Positioning property

获取或设置定位。

```csharp
public PositioningTypes Positioning { get; set; }
```

### Property Value

定位。

## 示例

以下示例展示了在加载 CMX 图像时如何设置内存限制。内存限制是所有内部缓冲区的最大允许大小（以兆字节为单位）。

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3419\\";
    
// 为目标加载的图像设置 10 兆字节的内存限制。
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "example.cmx", new Aspose.Imaging.LoadOptions() { BufferSizeHint = 10 }))
{
    image.Save(dir + "output.png",
        new Aspose.Imaging.ImageOptions.PngOptions()
        {
            VectorRasterizationOptions =
                    new Aspose.Imaging.ImageOptions.CmxRasterizationOptions
                    {
                        TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel,
                        SmoothingMode = Aspose.Imaging.SmoothingMode.AntiAlias,
                        Positioning = Aspose.Imaging.ImageOptions.PositioningTypes.DefinedByDocument
                    }
        });
}
```

以下示例展示了如何将 CDR 文档的所有页面导出为 PDF。

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3635\\testdata\\3570";
string inputCdrFileName = System.IO.Path.Combine(dir, "tiger.cdr");
string outputPdfFileName = System.IO.Path.Combine(dir, "tiger.cdr.pdf");

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputCdrFileName))
{
    Aspose.Imaging.ImageOptions.PdfOptions pdfOptions = new Aspose.Imaging.ImageOptions.PdfOptions();
    Aspose.Imaging.ImageOptions.CdrRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.CdrRasterizationOptions
    {
        TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel,
        SmoothingMode = Aspose.Imaging.SmoothingMode.None,
        Positioning = Aspose.Imaging.ImageOptions.PositioningTypes.DefinedByDocument
    };

    pdfOptions.VectorRasterizationOptions = rasterizationOptions;
    image.Save(outputPdfFileName, pdfOptions);
}
```

### 另请参见

* enum [PositioningTypes](../../positioningtypes/)
* class [VectorRasterizationOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../vectorrasterizationoptions/)
* assembly [Aspose.Imaging](../../../)


