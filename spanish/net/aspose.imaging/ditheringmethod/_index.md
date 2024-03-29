---
title: DitheringMethod
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Método de tramado.
type: docs
weight: 840
url: /es/net/aspose.imaging/ditheringmethod/
---
## DitheringMethod enumeration

Método de tramado.

```csharp
public enum DitheringMethod
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| ThresholdDithering | `0` | Difuminado de umbral. Algoritmo de tramado más simple y rápido. |
| FloydSteinbergDithering | `1` | El tramado de Floyd-Steinberg. Un algoritmo de tramado más complejo, utiliza los valores de intensidad de los vecinos más cercanos. |

### Ejemplos

El siguiente ejemplo carga una imagen ráster y realiza dithering de umbral y floyd usando diferentes profundidades de paleta.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Realice dithering de umbral utilizando una paleta de colores de 4 bits que contiene 16 colores.
    // Cuantos más bits se especifican, mayor calidad y mayor tamaño de la imagen de salida.
    // Tenga en cuenta que, por el momento, solo se admiten paletas de 1, 4 y 8 bits.
    rasterImage.Dither(Aspose.Imaging.DitheringMethod.ThresholdDithering, 4);

    rasterImage.Save(dir + "sample.ThresholdDithering4.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Realice el tramado de floyd utilizando una paleta de colores de 1 bit que contiene solo 2 colores: blanco y negro.
    // Cuantos más bits se especifican, mayor calidad y mayor tamaño de la imagen de salida.
    // Tenga en cuenta que, por el momento, solo se admiten paletas de 1, 4 y 8 bits.
    rasterImage.Dither(Aspose.Imaging.DitheringMethod.FloydSteinbergDithering, 1);

    rasterImage.Save(dir + "sample.FloydSteinbergDithering1.png");
}
```

### Ver también

* espacio de nombres [Aspose.Imaging](../../aspose.imaging)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
