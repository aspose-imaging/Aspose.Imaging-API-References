---
title: BinarizeOtsu
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Binarizzazione di unimmagine con soglia Otsu
type: docs
weight: 230
url: /it/net/aspose.imaging.fileformats.tiff/tiffimage/binarizeotsu/
---
## TiffImage.BinarizeOtsu method

Binarizzazione di un'immagine con soglia Otsu

```csharp
public override void BinarizeOtsu()
```

### Esempi

L'esempio seguente esegue il binarismo di un'immagine TIFF con soglia Otsu. Le immagini binarie contengono solo 2 colori: bianco e nero.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Binarizza l'immagine con la soglia Otsu.
    tiffImage.BinarizeOtsu();
    tiffImage.Save(dir + "sample.BinarizeOtsu.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Guarda anche

* class [TiffImage](../../tiffimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->