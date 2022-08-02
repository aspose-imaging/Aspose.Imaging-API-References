---
title: Crop
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Recortando la imagen.
type: docs
weight: 90
url: /es/net/aspose.imaging/rastercachedimage/crop/
---
## RasterCachedImage.Crop method

Recortando la imagen.

```csharp
public override void Crop(Rectangle rectangle)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rectangle | Rectangle | el rectángulo |

### Ejemplos

El siguiente ejemplo recorta una imagen ráster almacenada en caché. El área de recorte se especifica a través de Aspose.Imaging.Rectangle.

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // Recortar la imagen. El área de recorte es el área central rectangular de la imagen.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    rasterImage.Crop(area);

    // Guardar la imagen recortada en PNG
    rasterImage.Save(dir + "sample.Crop.png");
}
```

### Ver también

* struct [Rectangle](../../rectangle)
* class [RasterCachedImage](../../rastercachedimage)
* espacio de nombres [Aspose.Imaging](../../rastercachedimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->