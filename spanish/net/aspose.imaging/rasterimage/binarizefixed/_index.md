---
title: BinarizeFixed
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Binarización de una imagen con umbral predefinido
type: docs
weight: 230
url: /es/net/aspose.imaging/rasterimage/binarizefixed/
---
## RasterImage.BinarizeFixed method

Binarización de una imagen con umbral predefinido

```csharp
public virtual void BinarizeFixed(byte threshold)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| threshold | Byte | Valor umbral. Si el valor de gris correspondiente de un píxel es mayor que el umbral, se le asignará un valor de 255, 0 de lo contrario. |

### Ejemplos

El siguiente ejemplo binariza una imagen ráster con el umbral predefinido. Las imágenes binarizadas contienen solo 2 colores: blanco y negro.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Binarizar la imagen con un valor de umbral de 127.
    // Si el valor de gris correspondiente de un píxel es mayor que 127, se le asignará un valor de 255, 0 en caso contrario.
    rasterImage.BinarizeFixed(127);
    rasterImage.Save(dir + "sample.BinarizeFixed.png");
}
```

### Ver también

* class [RasterImage](../../rasterimage)
* espacio de nombres [Aspose.Imaging](../../rasterimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
