---
title: "EmfPlusPixelOffsetMode"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración PixelOffsetMode define cómo se desplazan los píxeles, lo que especifica el compromiso entre la velocidad de renderizado y la calidad."
type: docs
weight: 44
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPixelOffsetMode extends System.Enum
```

La enumeración PixelOffsetMode define cómo se desplazan los píxeles, lo que especifica el compromiso entre la velocidad de renderizado y la calidad.
## Campos

| Campo | Descripción |
| --- | --- |
| [PixelOffsetModeDefault](#PixelOffsetModeDefault) | Los píxeles se centran en coordenadas enteras, priorizando la velocidad sobre la calidad. |
| [PixelOffsetModeHighSpeed](#PixelOffsetModeHighSpeed) | Los píxeles se centran en coordenadas enteras, como con PixelOffsetModeNone. |
| [PixelOffsetModeHighQuality](#PixelOffsetModeHighQuality) | Los píxeles se centran en coordenadas medio-enteras, como con PixelOffsetModeHalf. |
| [PixelOffsetModeNone](#PixelOffsetModeNone) | Los píxeles se centran en el origen, lo que significa que el píxel cubre el área de -0.5 a 0.5 en ambos ejes x e y y su centro está en (0,0). |
| [PixelOffsetModeHalf](#PixelOffsetModeHalf) | Los píxeles se centran en coordenadas medio-enteras, lo que significa que el píxel cubre el área de 0 a 1 en ambos ejes x e y y su centro está en (0.5,0.5). |
### PixelOffsetModeDefault {#PixelOffsetModeDefault}
```
public static final byte PixelOffsetModeDefault
```


Los píxeles se centran en coordenadas enteras, priorizando la velocidad sobre la calidad.

### PixelOffsetModeHighSpeed {#PixelOffsetModeHighSpeed}
```
public static final byte PixelOffsetModeHighSpeed
```


Los píxeles se centran en coordenadas enteras, como con PixelOffsetModeNone. Se especifica mayor velocidad a costa de la calidad.

### PixelOffsetModeHighQuality {#PixelOffsetModeHighQuality}
```
public static final byte PixelOffsetModeHighQuality
```


Los píxeles se centran en coordenadas medio-enteras, como con PixelOffsetModeHalf. Se especifica mayor calidad a costa de la velocidad.

### PixelOffsetModeNone {#PixelOffsetModeNone}
```
public static final byte PixelOffsetModeNone
```


Los píxeles se centran en el origen, lo que significa que el píxel cubre el área de -0.5 a 0.5 en ambos ejes x e y y su centro está en (0,0).

### PixelOffsetModeHalf {#PixelOffsetModeHalf}
```
public static final byte PixelOffsetModeHalf
```


Los píxeles se centran en coordenadas medio-enteras, lo que significa que el píxel cubre el área de 0 a 1 en ambos ejes x e y y su centro está en (0.5,0.5). Al desplazar los píxeles durante el renderizado, la calidad del renderizado puede mejorarse a costa de la velocidad de renderizado.

