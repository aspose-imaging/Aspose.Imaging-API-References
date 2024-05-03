---
title: PdfCoreOptions.PdfCompliance
second_title: Aspose.Imaging for .NET API Reference
description: PdfCoreOptions property. Gets or sets the PDF compliance
type: docs
weight: 70
url: /net/aspose.imaging.fileformats.pdf/pdfcoreoptions/pdfcompliance/
---
## PdfCoreOptions.PdfCompliance property

Gets or sets the PDF compliance.

```csharp
public PdfComplianceVersion PdfCompliance { get; set; }
```

### Property Value

The PDF compliance.

## Examples

Convert EPS image to PDF using PostScript rendering.

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

### See Also

* enum [PdfComplianceVersion](../../../aspose.imaging/pdfcomplianceversion/)
* class [PdfCoreOptions](../)
* namespace [Aspose.Imaging.FileFormats.Pdf](../../pdfcoreoptions/)
* assembly [Aspose.Imaging](../../../)


