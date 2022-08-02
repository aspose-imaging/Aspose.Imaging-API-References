---
title: EmfPlusInterpolationMode
second_title: Aspose.Imaging para la referencia de la API de .NET
description: La enumeración InterpolationMode define formas de realizar el escalado incluido el estiramiento y la reducción.
type: docs
weight: 4870
url: /es/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/
---
## EmfPlusInterpolationMode enumeration

La enumeración InterpolationMode define formas de realizar el escalado, incluido el estiramiento y la reducción.

```csharp
public enum EmfPlusInterpolationMode : byte
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| InterpolationModeDefault | `0` | Especifica el modo de interpolación predeterminado, que se define como InterpolationModeBilinear. |
| InterpolationModeLowQuality | `1` | Especifica un modo de interpolación de baja calidad, que se define como InterpolationModeNearestNeighbor. |
| InterpolationModeHighQuality | `2` | Especifica un modo de interpolación de alta calidad, que se define como InterpolationModeHighQualityBicubic. |
| InterpolationModeBilinear | `3` | Especifica la interpolación bilineal, que utiliza la vecindad 2x2 más cercana de píxeles conocidos que rodean el píxel interpolado. El promedio ponderado de estos 4 valores de píxel conocidos determina el valor a asignar al píxel interpolado. El resultado tiene una apariencia más suave que InterpolationModeNearestNeighbor. |
| InterpolationModeBicubic | `4` | Especifica la interpolación bicúbica, que utiliza la vecindad 4x4 más cercana de píxeles conocidos que rodean el píxel interpolado. El promedio ponderado de estos 16 valores de píxeles conocidos determina el valor que se asigna al píxel interpolado. Debido a que es probable que los píxeles conocidos se encuentren a distancias variables del píxel interpolado, los píxeles más cercanos reciben una mayor ponderación en el cálculo. El resultado tiene un aspecto más suave que InterpolationModeBilinear. |
| InterpolationModeNearestNeighbor | `5` | Especifica la interpolación del vecino más cercano, que usa solo el valor del píxel más cercano al píxel interpolado. Este modo simplemente duplica o elimina píxeles, produciendo el resultado de menor calidad entre estas opciones. |
| InterpolationModeHighQualityBilinear | `6` | Especifica la interpolación bilineal con filtrado previo. |
| InterpolationModeHighQualityBicubic | `7` | Especifica la interpolación bicúbica con filtrado previo, que produce el resultado de mayor calidad entre estas opciones. |

### Ver también

* espacio de nombres [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->