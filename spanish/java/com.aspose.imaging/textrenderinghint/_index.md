---
title: "TextRenderingHint"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Especifica la calidad del renderizado de texto."
type: docs
weight: 115
url: /es/java/com.aspose.imaging/textrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextRenderingHint extends System.Enum
```

Especifica la calidad del renderizado de texto.
## Campos

| Campo | Descripción |
| --- | --- |
| [SystemDefault](#SystemDefault) | Cada carácter se dibuja usando su mapa de bits de glifo, con la sugerencia de renderizado predeterminada del sistema. |
| [SingleBitPerPixelGridFit](#SingleBitPerPixelGridFit) | Cada carácter se dibuja usando su mapa de bits de glifo. |
| [SingleBitPerPixel](#SingleBitPerPixel) | Cada carácter se dibuja usando su mapa de bits de glifo. |
| [AntiAliasGridFit](#AntiAliasGridFit) | Cada carácter se dibuja usando su mapa de bits de glifo antialiasado con hinting. |
| [AntiAlias](#AntiAlias) | Cada carácter se dibuja usando su mapa de bits de glifo antialiasado sin hinting. |
| [ClearTypeGridFit](#ClearTypeGridFit) | Cada carácter se dibuja usando su mapa de bits de glifo ClearType con hinting. |
### SystemDefault {#SystemDefault}
```
public static final int SystemDefault
```


Cada carácter se dibuja usando su mapa de bits de glifo, con la sugerencia de renderizado predeterminada del sistema. El texto se dibujará usando cualquier configuración de suavizado de fuentes que el usuario haya seleccionado para el sistema.

### SingleBitPerPixelGridFit {#SingleBitPerPixelGridFit}
```
public static final int SingleBitPerPixelGridFit
```


Cada carácter se dibuja usando su mapa de bits de glifo. Se utiliza hinting para mejorar la apariencia de los caracteres en los tallos y la curvatura.

### SingleBitPerPixel {#SingleBitPerPixel}
```
public static final int SingleBitPerPixel
```


Cada carácter se dibuja usando su mapa de bits de glifo. No se utiliza hinting.

### AntiAliasGridFit {#AntiAliasGridFit}
```
public static final int AntiAliasGridFit
```


Cada carácter se dibuja usando su mapa de bits de glifo antialiasado con hinting. Mucha mejor calidad gracias al antialiasing, pero con un mayor costo de rendimiento.

### AntiAlias {#AntiAlias}
```
public static final int AntiAlias
```


Cada carácter se dibuja usando su mapa de bits de glifo antialiasado sin hinting. Mejor calidad gracias al antialiasing. Las diferencias de ancho de los tallos pueden ser perceptibles porque el hinting está desactivado.

### ClearTypeGridFit {#ClearTypeGridFit}
```
public static final int ClearTypeGridFit
```


Cada carácter se dibuja usando su mapa de bits de glifo ClearType con hinting. La configuración de mayor calidad. Se utiliza para aprovechar las características de fuentes ClearType.

