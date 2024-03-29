---
title: PdfCompliance
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene o establece el cumplimiento de PDF.
type: docs
weight: 70
url: /es/net/aspose.imaging.fileformats.pdf/pdfcoreoptions/pdfcompliance/
---
## PdfCoreOptions.PdfCompliance property

Obtiene o establece el cumplimiento de PDF.

```csharp
public PdfComplianceVersion PdfCompliance { get; set; }
```

### El valor de la propiedad

El cumplimiento de PDF.

### Ejemplos

Convierta una imagen EPS a PDF utilizando la representación PostScript.

```csharp
[C#]

using (var image = (EpsImage)Image.Load("Sample.eps"))
{
    var options = new PdfOptions
    {
        PdfCoreOptions = new PdfCoreOptions
        {
            PdfCompliance = PdfComplianceVersion.PdfA1b // Establecer el cumplimiento de PDF requerido
        }
    };
  
    image.Save("Sample.pdf", options);
}
```

### Ver también

* enum [PdfComplianceVersion](../../../aspose.imaging/pdfcomplianceversion)
* class [PdfCoreOptions](../../pdfcoreoptions)
* espacio de nombres [Aspose.Imaging.FileFormats.Pdf](../../pdfcoreoptions)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
