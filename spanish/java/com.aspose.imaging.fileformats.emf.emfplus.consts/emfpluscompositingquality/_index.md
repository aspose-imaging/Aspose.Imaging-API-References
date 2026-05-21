---
title: "EmfPlusCompositingQuality"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración CompositingQuality define niveles de calidad para crear imágenes compuestas"
type: docs
weight: 15
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingquality/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusCompositingQuality extends System.Enum
```

La enumeración CompositingQuality define niveles de calidad para crear imágenes compuestas
## Campos

| Campo | Descripción |
| --- | --- |
| [CompositingQualityDefault](#CompositingQualityDefault) | No se realiza corrección gamma. |
| [CompositingQualityHighSpeed](#CompositingQualityHighSpeed) | No se realiza corrección gamma. |
| [CompositingQualityHighQuality](#CompositingQualityHighQuality) | Se realiza corrección gamma. |
| [CompositingQualityGammaCorrected](#CompositingQualityGammaCorrected) | Habilite la corrección gamma para una composición de mayor calidad con menor velocidad. |
| [CompositingQualityAssumeLinear](#CompositingQualityAssumeLinear) | No se realiza corrección gamma; sin embargo, usar valores lineales produce mejor calidad que el valor predeterminado a una velocidad ligeramente menor. |
### CompositingQualityDefault {#CompositingQualityDefault}
```
public static final byte CompositingQualityDefault
```


No se realiza corrección gamma. La corrección gamma controla el brillo y contraste generales de una imagen. Sin corrección gamma, las imágenes compuestas pueden aparecer demasiado claras o demasiado oscuras.

### CompositingQualityHighSpeed {#CompositingQualityHighSpeed}
```
public static final byte CompositingQualityHighSpeed
```


No se realiza corrección gamma. Se prioriza la velocidad de composición a expensas de la calidad. En cuanto al resultado, no hay diferencia entre este valor y CompositingQualityDefault.

### CompositingQualityHighQuality {#CompositingQualityHighQuality}
```
public static final byte CompositingQualityHighQuality
```


Se realiza corrección gamma. Se prioriza la calidad de composición a expensas de la velocidad.

### CompositingQualityGammaCorrected {#CompositingQualityGammaCorrected}
```
public static final byte CompositingQualityGammaCorrected
```


Habilite la corrección gamma para una composición de mayor calidad con menor velocidad. En cuanto al resultado, no hay diferencia entre este valor y CompositingQualityHighQuality.

### CompositingQualityAssumeLinear {#CompositingQualityAssumeLinear}
```
public static final byte CompositingQualityAssumeLinear
```


No se realiza corrección gamma; sin embargo, usar valores lineales produce mejor calidad que el valor predeterminado a una velocidad ligeramente menor.

