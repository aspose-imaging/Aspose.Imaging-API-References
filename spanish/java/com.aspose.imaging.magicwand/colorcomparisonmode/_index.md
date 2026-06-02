---
title: "ColorComparisonMode"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Especifica cómo se comparan los colores durante el algoritmo Magic Wand."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.magicwand/colorcomparisonmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorComparisonMode extends System.Enum
```

Especifica cómo se comparan los colores durante el algoritmo Magic Wand.
## Campos

| Campo | Descripción |
| --- | --- |
| [RgbDefault](#RgbDefault) | Los colores se comparan en el espacio de color RGB. |
| [YuvDefault](#YuvDefault) | Los colores se comparan en el espacio de color YUV. |
| [YuvLessLumaSensitive](#YuvLessLumaSensitive) | Los colores se comparan en el espacio de color YUV. |
| [Custom](#Custom) | El algoritmo de comparación de color es definido por el usuario. |
### RgbDefault {#RgbDefault}
```
public static final int RgbDefault
```


Los colores se comparan en el espacio de color RGB. Cada diferencia de color debe cumplir el umbral.

### YuvDefault {#YuvDefault}
```
public static final int YuvDefault
```


Los colores se comparan en el espacio de color YUV. Cada diferencia de color debe cumplir el umbral.

### YuvLessLumaSensitive {#YuvLessLumaSensitive}
```
public static final int YuvLessLumaSensitive
```


Los colores se comparan en el espacio de color YUV. Las diferencias de información de color deben cumplir el umbral, el umbral para el componente de luminancia se duplica.

### Custom {#Custom}
```
public static final int Custom
```


El algoritmo de comparación de color es definido por el usuario.

