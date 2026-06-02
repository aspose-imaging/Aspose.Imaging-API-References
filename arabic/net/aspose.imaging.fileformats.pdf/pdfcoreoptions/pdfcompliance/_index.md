---
title: "PdfCoreOptions.PdfCompliance"
second_title: "Aspose.Imaging for .NET API Reference"
description: "PdfCoreOptions الخاصية. يحصل أو يضبط توافق PDF"
type: docs
weight: 70
url: /ar/net/aspose.imaging.fileformats.pdf/pdfcoreoptions/pdfcompliance/
---
## PdfCoreOptions.PdfCompliance property

يحصل أو يعيّن توافق PDF.

```csharp
public PdfComplianceVersion PdfCompliance { get; set; }
```

### Property Value

توافق PDF.

## أمثلة

تحويل صورة EPS إلى PDF باستخدام عرض PostScript.

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

### انظر أيضًا

* enum [PdfComplianceVersion](../../../aspose.imaging/pdfcomplianceversion/)
* class [PdfCoreOptions](../)
* namespace [Aspose.Imaging.FileFormats.Pdf](../../pdfcoreoptions/)
* assembly [Aspose.Imaging](../../../)


