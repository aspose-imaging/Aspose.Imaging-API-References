---
title: "JpegLsInterleaveMode"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Define el modo de entrelazado para datos de píxeles de color multicomponente."
type: docs
weight: 15
url: /es/java/com.aspose.imaging.fileformats.jpeg/jpeglsinterleavemode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class JpegLsInterleaveMode extends System.Enum
```

Define el modo de intercalado para datos de píxeles multicomponente (color).
## Campos

| Campo | Descripción |
| --- | --- |
| [None](#None) | Los datos se codifican y almacenan como componente por componente: RRRGGGBBB. |
| [Line](#Line) | El modo de entrelazado es por línea. |
| [Sample](#Sample) | Los datos se codifican y almacenan por muestra. |
### None {#None}
```
public static final int None
```


Los datos se codifican y almacenan como componente por componente: RRRGGGBBB.

### Line {#Line}
```
public static final int Line
```


El modo de entrelazado es por línea. Una línea completa de cada componente se codifica antes de pasar a la siguiente línea.

### Sample {#Sample}
```
public static final int Sample
```


Los datos se codifican y almacenan por muestra. Para imágenes en color, este es el formato tipo RGBRGBRGB.

