---
title: "CdrImage.Pages"
second_title: "Aspose.Imaging for .NET API 参考"
description: "CdrImage 属性。使用此直观属性无缝检索图像的页面。适用于希望访问和操作多页图像中各个页面的开发者，确保高效的导航和处理。"
type: docs
weight: 80
url: /zh/net/aspose.imaging.fileformats.cdr/cdrimage/pages/
---
## CdrImage.Pages property

无缝检索图像的页面，使用此直观属性。适用于希望访问和操作多页图像中各个页面的开发者，确保高效的导航和处理。

```csharp
public override Image[] Pages { get; }
```

### Property Value

这些页面。

## 示例

以下示例展示了如何缓存 CDR 图像的所有页面。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从 CDR 文件加载图像。
using (Aspose.Imaging.FileFormats.Cdr.CdrImage image = (Aspose.Imaging.FileFormats.Cdr.CdrImage)Aspose.Imaging.Image.Load(dir + "sample.cdr"))
{
    // 此调用仅缓存默认页面。
    image.CacheData();

    // 缓存所有页面，以便不再从底层数据流执行额外的数据加载。
    foreach (Aspose.Imaging.FileFormats.Cdr.CdrImagePage page in image.Pages)
    {
        page.CacheData();
    }
}
```

以下示例展示了如何将 CDR 文档的单页导出为 PDF。

```csharp
[C#]

int pageNumber = 0;
string dir = "c:\\aspose.imaging\\issues\\net\\3635\\testdata\\3570";
string inputCdrFileName = System.IO.Path.Combine(dir, "tiger.cdr");
string outputPdfFileName = System.IO.Path.Combine(dir, "tiger.cdr.page" + pageNumber + ".pdf");

using (Aspose.Imaging.FileFormats.Cdr.CdrImage image = (Aspose.Imaging.FileFormats.Cdr.CdrImage) Aspose.Imaging.Image.Load(inputCdrFileName))
{
    Aspose.Imaging.FileFormats.Cdr.CdrImagePage imagePage = (Aspose.Imaging.FileFormats.Cdr.CdrImagePage) image.Pages[pageNumber];

    Aspose.Imaging.ImageOptions.PdfOptions pdfOptions = new Aspose.Imaging.ImageOptions.PdfOptions();
    Aspose.Imaging.ImageOptions.CdrRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.CdrRasterizationOptions()
    {
        TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel,
        SmoothingMode = Aspose.Imaging.SmoothingMode.None
    };

    pdfOptions.VectorRasterizationOptions = rasterizationOptions;
    pdfOptions.VectorRasterizationOptions.PageWidth = imagePage.Width;
    pdfOptions.VectorRasterizationOptions.PageHeight = imagePage.Height;

    imagePage.Save(outputPdfFileName, pdfOptions);
}
```

### 另请参见

* class [Image](../../../aspose.imaging/image/)
* class [CdrImage](../)
* namespace [Aspose.Imaging.FileFormats.Cdr](../../cdrimage/)
* assembly [Aspose.Imaging](../../../)


