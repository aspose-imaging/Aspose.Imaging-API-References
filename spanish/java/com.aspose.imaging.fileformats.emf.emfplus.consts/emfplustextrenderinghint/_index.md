---
title: "EmfPlusTextRenderingHint"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración TextRenderingHint define tipos de ajuste de texto y suavizado que afectan la calidad del renderizado de texto."
type: docs
weight: 52
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusTextRenderingHint extends System.Enum
```

La enumeración TextRenderingHint define tipos de sugerencias de texto y anti-aliasing, lo que afecta la calidad del renderizado de texto.
## Campos

| Campo | Descripción |
| --- | --- |
| [TextRenderingHintSystemDefault](#TextRenderingHintSystemDefault) | Especifica que cada carácter de texto DEBERÍA dibujarse usando la configuración de suavizado de fuentes que esté configurada en el sistema operativo. |
| [TextRenderingHintSingleBitPerPixelGridFit](#TextRenderingHintSingleBitPerPixelGridFit) | Especifica que cada carácter de texto DEBERÍA dibujarse usando su mapa de bits de glifo. |
| [TextRenderingHintSingleBitPerPixel](#TextRenderingHintSingleBitPerPixel) | Especifica que cada carácter de texto DEBERÍA dibujarse usando su mapa de bits de glifo. |
| [TextRenderingHintAntialiasGridFit](#TextRenderingHintAntialiasGridFit) | Especifica que cada carácter de texto DEBERÍA dibujarse usando su mapa de bits de glifo anti-aliasado con suavizado. |
| [TextRenderingHintAntialias](#TextRenderingHintAntialias) | Especifica que cada carácter de texto se dibuja usando su mapa de bits de glifo anti-aliasado sin ajuste. |
| [TextRenderingHintClearTypeGridFit](#TextRenderingHintClearTypeGridFit) | Especifica que cada carácter de texto DEBERÍA dibujarse usando su mapa de bits de glifo ClearType con suavizado. |
### TextRenderingHintSystemDefault {#TextRenderingHintSystemDefault}
```
public static final byte TextRenderingHintSystemDefault
```


Especifica que cada carácter de texto DEBERÍA dibujarse usando la configuración de suavizado de fuentes que esté configurada en el sistema operativo.

### TextRenderingHintSingleBitPerPixelGridFit {#TextRenderingHintSingleBitPerPixelGridFit}
```
public static final byte TextRenderingHintSingleBitPerPixelGridFit
```


Especifica que cada carácter de texto DEBERÍA dibujarse usando su mapa de bits de glifo. El suavizado PUEDE usarse para mejorar la apariencia de los tallos y la curvatura de los glifos.

### TextRenderingHintSingleBitPerPixel {#TextRenderingHintSingleBitPerPixel}
```
public static final byte TextRenderingHintSingleBitPerPixel
```


Especifica que cada carácter de texto DEBERÍA dibujarse usando su mapa de bits de glifo. No se utiliza suavizado.

### TextRenderingHintAntialiasGridFit {#TextRenderingHintAntialiasGridFit}
```
public static final byte TextRenderingHintAntialiasGridFit
```


Especifica que cada carácter de texto DEBERÍA dibujarse usando su mapa de bits de glifo anti-aliasado con suavizado. El renderizado es de alta calidad gracias al anti-aliasing, pero con un mayor costo de rendimiento.

### TextRenderingHintAntialias {#TextRenderingHintAntialias}
```
public static final byte TextRenderingHintAntialias
```


Especifica que cada carácter de texto se dibuja usando su mapa de bits de glifo anti-aliasado sin ajuste. La mejor calidad proviene del anti-aliasing, pero las diferencias de ancho de tallo PUEDEN notarse porque el ajuste está desactivado.

### TextRenderingHintClearTypeGridFit {#TextRenderingHintClearTypeGridFit}
```
public static final byte TextRenderingHintClearTypeGridFit
```


Especifica que cada carácter de texto DEBERÍA dibujarse usando su mapa de bits de glifo ClearType con suavizado. Esta es la configuración de ajuste de texto de mayor calidad, que se utiliza para aprovechar las características de fuentes ClearType.

