---
title: "StretchMode"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La Enumeración especifica el modo de estiramiento de bitmap que define cómo el sistema combina filas o columnas de un bitmap con los píxeles existentes."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.wmf.consts/stretchmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StretchMode extends System.Enum
```

La Enumeración [StretchMode](../../com.aspose.imaging.fileformats.wmf.consts/stretchmode) especifica el modo de estiramiento de bitmap, que define cómo el sistema combina filas o columnas de un bitmap con los píxeles existentes.
## Campos

| Campo | Descripción |
| --- | --- |
| [BlackOnWhite](#BlackOnWhite) | Realiza una operación Boolean AND utilizando los valores de color de los píxeles eliminados y existentes. |
| [WhiteOnBlack](#WhiteOnBlack) | Realiza una operación Boolean OR utilizando los valores de color de los píxeles eliminados y existentes. |
| [ColorOnColor](#ColorOnColor) | Elimina los píxeles. |
| [HalfTone](#HalfTone) | Mapea los píxeles del rectángulo de origen a bloques de píxeles en el rectángulo de destino. |
### BlackOnWhite {#BlackOnWhite}
```
public static final int BlackOnWhite
```


Realiza una operación Boolean AND utilizando los valores de color de los píxeles eliminados y existentes. Si el bitmap es monocromo, este modo conserva los píxeles negros a costa de los píxeles blancos.

### WhiteOnBlack {#WhiteOnBlack}
```
public static final int WhiteOnBlack
```


Realiza una operación Boolean OR utilizando los valores de color de los píxeles eliminados y existentes. Si el bitmap es monocromo, este modo conserva los píxeles blancos a costa de los píxeles negros.

### ColorOnColor {#ColorOnColor}
```
public static final int ColorOnColor
```


Elimina los píxeles. Este modo elimina todas las líneas de píxeles eliminadas sin intentar conservar su información.

### HalfTone {#HalfTone}
```
public static final int HalfTone
```


Mapea los píxeles del rectángulo de origen a bloques de píxeles en el rectángulo de destino. El color promedio del bloque de píxeles de destino aproxima el color de los píxeles de origen.

