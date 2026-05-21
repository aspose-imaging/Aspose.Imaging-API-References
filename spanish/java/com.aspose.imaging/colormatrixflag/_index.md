---
title: "ColorMatrixFlag"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Especifica los tipos de imágenes y colores que se verán afectados por la configuración de ajuste de color y escala de grises de un ."
type: docs
weight: 27
url: /es/java/com.aspose.imaging/colormatrixflag/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorMatrixFlag extends System.Enum
```

Especifica los tipos de imágenes y colores que se verán afectados por la configuración de ajuste de color y escala de grises de un [ImageAttributes](../../com.aspose.imaging/imageattributes).
## Campos

| Campo | Descripción |
| --- | --- |
| [Default](#Default) | Todos los valores de color, incluidas las tonalidades de gris, se ajustan mediante la misma matriz de ajuste de color. |
| [SkipGrays](#SkipGrays) | Todos los colores se ajustan, pero las tonalidades de gris no se ajustan. |
| [AltGrays](#AltGrays) | Solo se ajustan las tonalidades de gris. |
### Default {#Default}
```
public static final int Default
```


Todos los valores de color, incluidas las tonalidades de gris, se ajustan mediante la misma matriz de ajuste de color.

### SkipGrays {#SkipGrays}
```
public static final int SkipGrays
```


Todos los colores se ajustan, pero las tonalidades de gris no se ajustan. Una tonalidad de gris es cualquier color que tiene el mismo valor para sus componentes rojo, verde y azul.

### AltGrays {#AltGrays}
```
public static final int AltGrays
```


Solo se ajustan las tonalidades de gris.

