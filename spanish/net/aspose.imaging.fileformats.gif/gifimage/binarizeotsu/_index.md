---
title: BinarizeOtsu
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Binarización de una imagen con umbral Otsu
type: docs
weight: 280
url: /es/net/aspose.imaging.fileformats.gif/gifimage/binarizeotsu/
---
## GifImage.BinarizeOtsu method

Binarización de una imagen con umbral Otsu

```csharp
public override void BinarizeOtsu()
```

### Ejemplos

El siguiente ejemplo binariza una imagen GIF con el umbral de Otsu. Las imágenes binarizadas contienen solo 2 colores: blanco y negro.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // Binarizar la imagen con el umbral de Otsu.
    gifImage.BinarizeOtsu();
    gifImage.Save(dir + "sample.BinarizeOtsu.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Ver también

* class [GifImage](../../gifimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->