---
title: BinarizeOtsu
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Binarización de una imagen con umbral Otsu
type: docs
weight: 70
url: /es/net/aspose.imaging/rastercachedimage/binarizeotsu/
---
## RasterCachedImage.BinarizeOtsu method

Binarización de una imagen con umbral Otsu

```csharp
public override void BinarizeOtsu()
```

### Ejemplos

El siguiente ejemplo binariza una imagen ráster almacenada en caché con el umbral de Otsu. Las imágenes binarizadas contienen solo 2 colores: blanco y negro.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // Binarizar la imagen con el umbral de Otsu.
    rasterImage.BinarizeOtsu();
    rasterImage.Save(dir + "sample.BinarizeOtsu.png");
}
```

### Ver también

* class [RasterCachedImage](../../rastercachedimage)
* espacio de nombres [Aspose.Imaging](../../rastercachedimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->