---
title: "EmfPlusInterpolationMode"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración InterpolationMode define formas de realizar escalado, incluyendo estiramiento y reducción."
type: docs
weight: 29
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusInterpolationMode extends System.Enum
```

La enumeración InterpolationMode define formas de realizar el escalado, incluyendo estiramiento y reducción.
## Campos

| Campo | Descripción |
| --- | --- |
| [InterpolationModeDefault](#InterpolationModeDefault) | Especifica el modo de interpolación predeterminado, que se define como InterpolationModeBilinear. |
| [InterpolationModeLowQuality](#InterpolationModeLowQuality) | Especifica un modo de interpolación de baja calidad, que se define como InterpolationModeNearestNeighbor. |
| [InterpolationModeHighQuality](#InterpolationModeHighQuality) | Especifica un modo de interpolación de alta calidad, que se define como InterpolationModeHighQualityBicubic. |
| [InterpolationModeBilinear](#InterpolationModeBilinear) | Especifica interpolación bilineal, que utiliza el vecindario 2x2 más cercano de píxeles conocidos que rodean al píxel interpolado. |
| [InterpolationModeBicubic](#InterpolationModeBicubic) | Especifica interpolación bicúbica, que utiliza el vecindario más cercano de 4x4 píxeles conocidos que rodean el píxel interpolado. |
| [InterpolationModeNearestNeighbor](#InterpolationModeNearestNeighbor) | Especifica interpolación de vecino más cercano, que utiliza solo el valor del píxel que está más cerca del píxel interpolado. |
| [InterpolationModeHighQualityBilinear](#InterpolationModeHighQualityBilinear) | Especifica interpolación bilineal con prefiltrado. |
| [InterpolationModeHighQualityBicubic](#InterpolationModeHighQualityBicubic) | Especifica interpolación bicúbica con prefiltrado, que produce el resultado de mayor calidad entre estas opciones. |
### InterpolationModeDefault {#InterpolationModeDefault}
```
public static final byte InterpolationModeDefault
```


Especifica el modo de interpolación predeterminado, que se define como InterpolationModeBilinear.

### InterpolationModeLowQuality {#InterpolationModeLowQuality}
```
public static final byte InterpolationModeLowQuality
```


Especifica un modo de interpolación de baja calidad, que se define como InterpolationModeNearestNeighbor.

### InterpolationModeHighQuality {#InterpolationModeHighQuality}
```
public static final byte InterpolationModeHighQuality
```


Especifica un modo de interpolación de alta calidad, que se define como InterpolationModeHighQualityBicubic.

### InterpolationModeBilinear {#InterpolationModeBilinear}
```
public static final byte InterpolationModeBilinear
```


Especifica interpolación bilineal, que utiliza el vecindario más cercano de 2x2 píxeles conocidos que rodean el píxel interpolado. El promedio ponderado de estos 4 valores de píxeles conocidos determina el valor a asignar al píxel interpolado. El resultado tiene un aspecto más suave que InterpolationModeNearestNeighbor.

### InterpolationModeBicubic {#InterpolationModeBicubic}
```
public static final byte InterpolationModeBicubic
```


Especifica interpolación bicúbica, que utiliza el vecindario más cercano de 4x4 píxeles conocidos que rodean el píxel interpolado. El promedio ponderado de estos 16 valores de píxeles conocidos determina el valor a asignar al píxel interpolado. Debido a que los píxeles conocidos pueden estar a distintas distancias del píxel interpolado, los píxeles más cercanos reciben un peso mayor en el cálculo. El resultado tiene un aspecto más suave que InterpolationModeBilinear.

### InterpolationModeNearestNeighbor {#InterpolationModeNearestNeighbor}
```
public static final byte InterpolationModeNearestNeighbor
```


Especifica interpolación de vecino más cercano, que utiliza solo el valor del píxel que está más cerca del píxel interpolado. Este modo simplemente duplica o elimina píxeles, produciendo el resultado de menor calidad entre estas opciones.

### InterpolationModeHighQualityBilinear {#InterpolationModeHighQualityBilinear}
```
public static final byte InterpolationModeHighQualityBilinear
```


Especifica interpolación bilineal con prefiltrado.

### InterpolationModeHighQualityBicubic {#InterpolationModeHighQualityBicubic}
```
public static final byte InterpolationModeHighQualityBicubic
```


Especifica interpolación bicúbica con prefiltrado, que produce el resultado de mayor calidad entre estas opciones.

