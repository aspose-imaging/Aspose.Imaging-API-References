---
title: BinarizeFixed
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Binarizzazione di unimmagine con soglia predefinita
type: docs
weight: 220
url: /it/net/aspose.imaging.fileformats.tiff/tiffimage/binarizefixed/
---
## TiffImage.BinarizeFixed method

Binarizzazione di un'immagine con soglia predefinita

```csharp
public override void BinarizeFixed(byte threshold)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threshold | Byte | Valore di soglia. Se il valore di grigio corrispondente di un pixel è maggiore della soglia, gli verrà assegnato un valore di 255, altrimenti 0. |

### Esempi

L'esempio seguente esegue il binarismo di un'immagine TIFF con la soglia predefinita. Le immagini binarie contengono solo 2 colori: bianco e nero.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Binarizza l'immagine con un valore di soglia di 127.
    // Se un valore di grigio corrispondente di un pixel è maggiore di 127, gli verrà assegnato un valore di 255, altrimenti 0.
    tiffImage.BinarizeFixed(127);
    tiffImage.Save(dir + "sample.BinarizeFixed.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Guarda anche

* class [TiffImage](../../tiffimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
