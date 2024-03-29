---
title: PdfCompliance
second_title: Aspose.Imaging for .NET API 参考
description: 获取或设置 PDF 合规性
type: docs
weight: 70
url: /zh/net/aspose.imaging.fileformats.pdf/pdfcoreoptions/pdfcompliance/
---
## PdfCoreOptions.PdfCompliance property

获取或设置 PDF 合规性。

```csharp
public PdfComplianceVersion PdfCompliance { get; set; }
```

### 适当的价值

PDF 合规性。

### 例子

使用 PostScript 渲染将 EPS 图像转换为 PDF。

```csharp
[C#]

using (var image = (EpsImage)Image.Load("Sample.eps"))
{
    var options = new PdfOptions
    {
        PdfCoreOptions = new PdfCoreOptions
        {
            PdfCompliance = PdfComplianceVersion.PdfA1b // 设置所需的 PDF 合规性
        }
    };
  
    image.Save("Sample.pdf", options);
}
```

### 也可以看看

* enum [PdfComplianceVersion](../../../aspose.imaging/pdfcomplianceversion)
* class [PdfCoreOptions](../../pdfcoreoptions)
* 命名空间 [Aspose.Imaging.FileFormats.Pdf](../../pdfcoreoptions)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
