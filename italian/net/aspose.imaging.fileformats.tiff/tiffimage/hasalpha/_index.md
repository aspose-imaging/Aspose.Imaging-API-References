---
title: HasAlpha
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ottiene il canale alfa Has.
type: docs
weight: 70
url: /it/net/aspose.imaging.fileformats.tiff/tiffimage/hasalpha/
---
## TiffImage.HasAlpha property

Ottiene il canale alfa Has.

```csharp
public override bool HasAlpha { get; }
```

### Valore della proprietà

Il canale alfa Ha.

### Esempi

L'esempio seguente carica un'immagine TIFF e stampa le informazioni sul formato dei dati grezzi e sul canale alfa.

```csharp
[C#]

string dir = "c:\\temp\\";

string fileName = dir + "sample.tif";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(fileName))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Se il frame TIFF attivo ha un canale alfa, l'intera immagine TIFF viene considerata come un canale alfa.
    System.Console.WriteLine("ImageFile={0}, FileFormat={1}, HasAlpha={2}", fileName, tiffImage.RawDataFormat, tiffImage.HasAlpha);

    int i = 0;
    foreach (Aspose.Imaging.FileFormats.Tiff.TiffFrame frame in tiffImage.Frames)
    {
        System.Console.WriteLine("Frame={0}, FileFormat={1}, HasAlpha={2}", ++i, frame.RawDataFormat, frame.HasAlpha);
    }
}

// L'output potrebbe essere simile a questo:
// ImageFile=c:\temp\sample.tif, FileFormat=RgbIndexed1Bpp, canali utilizzati: 1, HasAlpha=False
// Frame=1, FileFormat=RgbIndexed1Bpp, canali utilizzati: 1, HasAlpha=False
// Frame=2, FileFormat=RgbIndexed1Bpp, canali utilizzati: 1, HasAlpha=False
```

### Guarda anche

* class [TiffImage](../../tiffimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
