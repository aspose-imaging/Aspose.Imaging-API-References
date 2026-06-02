---
title: "EmfDibColors"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración DIBColors define cómo interpretar los valores en la tabla de colores de un DIB."
type: docs
weight: 17
url: /es/java/com.aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfDibColors extends System.Enum
```

La enumeración DIBColors define cómo interpretar los valores en la tabla de colores de un DIB.
## Campos

| Campo | Descripción |
| --- | --- |
| [DIB_RGB_COLORS](#DIB-RGB-COLORS) | La tabla de colores contiene valores RGB literales |
| [DIB_PAL_COLORS](#DIB-PAL-COLORS) | La tabla de colores consiste en una matriz de índices de 16 bits al objeto LogPalette (sección 2.2.17) que está actualmente definido en el contexto del dispositivo de reproducción. |
| [DIB_PAL_INDICES](#DIB-PAL-INDICES) | No existe tabla de colores. |
### DIB_RGB_COLORS {#DIB-RGB-COLORS}
```
public static final int DIB_RGB_COLORS
```


La tabla de colores contiene valores RGB literales

### DIB_PAL_COLORS {#DIB-PAL-COLORS}
```
public static final int DIB_PAL_COLORS
```


La tabla de colores consiste en una matriz de índices de 16 bits al objeto LogPalette (sección 2.2.17) que está actualmente definido en el contexto del dispositivo de reproducción.

### DIB_PAL_INDICES {#DIB-PAL-INDICES}
```
public static final int DIB_PAL_INDICES
```


No existe tabla de colores. Los píxeles en el DIB son índices a la paleta lógica actual en el contexto del dispositivo de reproducción.

