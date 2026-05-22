---
title: "PdfCoreOptions.PdfCompliance"
second_title: "Aspose.Imaging for .NET API 参考"
description: "PdfCoreOptions 属性。获取或设置 PDF 合规性"
type: docs
weight: 70
url: /zh/net/aspose.imaging.fileformats.pdf/pdfcoreoptions/pdfcompliance/
---
## PdfCoreOptions.PdfCompliance property

获取或设置 PDF 合规性。

```csharp
public PdfComplianceVersion PdfCompliance { get; set; }
```

### Property Value

PDF 合规性。

## 示例

使用 PostScript 渲染将 EPS 图像转换为 PDF。

```csharp
[C#]

using (var image = (EpsImage)Image.Load("Sample.eps"))
{
    var options = new PdfOptions
    {
        PdfCoreOptions = new PdfCoreOptions
        {
            PdfCompliance = PdfComplianceVersion.PdfA1b // Set required PDF compliance
        }
    };
  
    image.Save("Sample.pdf", options);
}
```

### 另请参见

* enum [PdfComplianceVersion](../../../aspose.imaging/pdfcomplianceversion/)
* class [PdfCoreOptions](../)
* namespace [Aspose.Imaging.FileFormats.Pdf](../../pdfcoreoptions/)
* assembly [Aspose.Imaging](../../../)


