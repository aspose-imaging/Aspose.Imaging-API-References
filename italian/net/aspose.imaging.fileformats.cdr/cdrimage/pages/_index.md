---
title: Pages
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ottiene le pagine.
type: docs
weight: 90
url: /it/net/aspose.imaging.fileformats.cdr/cdrimage/pages/
---
## CdrImage.Pages property

Ottiene le pagine.

```csharp
public override Image[] Pages { get; }
```

### Valore della proprietà

Le pagine.

### Esempi

L'esempio seguente mostra come memorizzare nella cache tutte le pagine di un'immagine CDR.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine da un file CDR.
using (Aspose.Imaging.FileFormats.Cdr.CdrImage image = (Aspose.Imaging.FileFormats.Cdr.CdrImage)Aspose.Imaging.Image.Load(dir + "sample.cdr"))
{
    // Questa chiamata memorizza nella cache solo la pagina predefinita.
    image.CacheData();

    // Memorizza nella cache tutte le pagine in modo che non venga eseguito alcun caricamento di dati aggiuntivo dal flusso di dati sottostante.
    foreach (Aspose.Imaging.FileFormats.Cdr.CdrImagePage page in image.Pages)
    {
        page.CacheData();
    }
}
```

L'esempio seguente mostra come esportare una singola pagina di un documento CDR in PDF.

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

### Guarda anche

* class [Image](../../../aspose.imaging/image)
* class [CdrImage](../../cdrimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Cdr](../../cdrimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->