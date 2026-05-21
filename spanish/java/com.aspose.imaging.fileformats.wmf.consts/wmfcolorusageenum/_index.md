---
title: "WmfColorUsageEnum"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración ColorUsage especifica si existe una tabla de colores en un bitmap independiente del dispositivo DIB y cómo interpretar sus valores."
type: docs
weight: 15
url: /es/java/com.aspose.imaging.fileformats.wmf.consts/wmfcolorusageenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfColorUsageEnum extends System.Enum
```

La enumeración ColorUsage especifica si existe una tabla de colores en un mapa de bits independiente del dispositivo (DIB) y cómo interpretar sus valores.
## Campos

| Campo | Descripción |
| --- | --- |
| [DIB_RGB_COLORS](#DIB-RGB-COLORS) | La tabla de colores contiene valores RGB especificados por objetos RGBQuad (sección 2.2.2.20). |
| [DIB_PAL_COLORS](#DIB-PAL-COLORS) | La tabla de colores contiene índices de 16 bits en la paleta lógica actual del contexto del dispositivo de reproducción. |
| [DIB_PAL_INDICES](#DIB-PAL-INDICES) | No existe tabla de colores. |
### DIB_RGB_COLORS {#DIB-RGB-COLORS}
```
public static final int DIB_RGB_COLORS
```


La tabla de colores contiene valores RGB especificados por objetos RGBQuad (sección 2.2.2.20).

### DIB_PAL_COLORS {#DIB-PAL-COLORS}
```
public static final int DIB_PAL_COLORS
```


La tabla de colores contiene índices de 16 bits en la paleta lógica actual del contexto del dispositivo de reproducción.

### DIB_PAL_INDICES {#DIB-PAL-INDICES}
```
public static final int DIB_PAL_INDICES
```


No existe tabla de colores. Los píxeles en el DIB son índices a la paleta lógica actual en el contexto del dispositivo de reproducción.

