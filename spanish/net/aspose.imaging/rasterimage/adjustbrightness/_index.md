---
title: AdjustBrightness
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Ajuste de un brillo para la imagen.
type: docs
weight: 190
url: /es/net/aspose.imaging/rasterimage/adjustbrightness/
---
## RasterImage.AdjustBrightness method

Ajuste de un brillo para la imagen.

```csharp
public virtual void AdjustBrightness(int brightness)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| brightness | Int32 | Valor de brillo. |

### Ejemplos

El siguiente ejemplo realiza la corrección de brillo de una imagen.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Establecer el valor de brillo. Los valores aceptados de brillo están en el rango [-255, 255].
    rasterImage.AdjustBrightness(50);
    rasterImage.Save(dir + "sample.AdjustBrightness.png");
}
```

### Ver también

* class [RasterImage](../../rasterimage)
* espacio de nombres [Aspose.Imaging](../../rasterimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
