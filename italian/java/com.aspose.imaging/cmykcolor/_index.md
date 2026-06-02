---
title: "CmykColor"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il colore CMYK del pixel."
type: docs
weight: 18
url: /it/java/com.aspose.imaging/cmykcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class CmykColor extends Struct<CmykColor>
```

Il colore CMYK del pixel.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CmykColor()](#CmykColor--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEmpty()](#getEmpty--) | Restituisce il valore vuoto. |
| [fromParams(int cyan, int magenta, int yellow, int black)](#fromParams-int-int-int-int-) | Crea una struttura `CmykColor` a partire da valori a 32 bit di ciano, magenta, giallo e nero. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | La conversione da colore ARGB a 32 bit a CMYKColor. |
| [toColor(CmykColor[] cmykPixels)](#toColor-com.aspose.imaging.CmykColor---) | La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti. |
| [toArgb32(CmykColor[] cmykPixels)](#toArgb32-com.aspose.imaging.CmykColor---) | La conversione da CMYKColor a colore ARGB a 32 bit usando la conversione icc con profili predefiniti. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | La conversione da colore ARGB a 32 bit a CMYKColor. |
| [toColor(CmykColor cmykPixel)](#toColor-com.aspose.imaging.CmykColor-) | La conversione da CMYKColor a Color. |
| [toColorIcc(CmykColor[] cmykPixels)](#toColorIcc-com.aspose.imaging.CmykColor---) | La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti. |
| [toColorIcc(CmykColor cmykPixel)](#toColorIcc-com.aspose.imaging.CmykColor-) | La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti. |
| [toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.imaging.CmykColor---java.io.InputStream-java.io.InputStream-) | La conversione da CMYKColor a Color usando la conversione icc. |
| [toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.imaging.CmykColor-java.io.InputStream-java.io.InputStream-) | La conversione da CMYKColor a Color usando la conversione icc. |
| [isEquals(CmykColor obj1, CmykColor obj2)](#isEquals-com.aspose.imaging.CmykColor-com.aspose.imaging.CmykColor-) |  |
| [getC()](#getC--) | Restituisce il valore del componente ciano di questa struttura `com.com.aspose.imaging.Color`. |
| [getM()](#getM--) | Restituisce il valore del componente magenta di questa struttura `com.com.aspose.imaging.Color`. |
| [getY()](#getY--) | Restituisce il valore del componente giallo di questa struttura `com.com.aspose.imaging.Color`. |
| [getK()](#getK--) | Restituisce il valore del componente nero di questa struttura `com.com.aspose.imaging.Color`. |
| [isEmpty()](#isEmpty--) | Restituisce un valore che indica se questa struttura `com.com.aspose.imaging.Color` è non inizializzata. |
| [hashCode()](#hashCode--) | Il metodo get hash code. |
| [toValue()](#toValue--) | Il valore to. |
| [CloneTo(CmykColor that)](#CloneTo-com.aspose.imaging.CmykColor-) |  |
| [Clone()](#Clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
### CmykColor() {#CmykColor--}
```
public CmykColor()
```


### getEmpty() {#getEmpty--}
```
public static CmykColor getEmpty()
```


Restituisce il valore vuoto.

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor)
### fromParams(int cyan, int magenta, int yellow, int black) {#fromParams-int-int-int-int-}
```
public static CmykColor fromParams(int cyan, int magenta, int yellow, int black)
```


Crea una struttura `CmykColor` a partire da valori ciano, magenta, giallo e nero a 32 bit. Questo metodo è deprecato. Si prega di utilizzare il più efficace CmykColorHelper\#fromComponents(int, int, int, int).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ciano | int | Il componente ciano. I valori validi sono da 0 a 255. |
| magenta | int | Il componente magenta. I valori validi sono da 0 a 255. |
| giallo | int | Il componente giallo. I valori validi sono da 0 a 255. |
| nero | int | Il componente nero. I valori validi sono da 0 a 255. |

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor) - The `CmykColor`.
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static CmykColor[] toCmyk(int[] argbPixels)
```


La conversione da colore ARGB a 32 bit a CMYKColor. Questo metodo è deprecato. Si prega di utilizzare il più efficace `CmykColorHelper.toCmyk(int[])`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argbPixels | int[] | I pixel del formato ARGB a 32 bit. |

**Returns:**
com.aspose.imaging.CmykColor[] - Il [CmykColor](../../com.aspose.imaging/cmykcolor)[].
### toColor(CmykColor[] cmykPixels) {#toColor-com.aspose.imaging.CmykColor---}
```
public static Color[] toColor(CmykColor[] cmykPixels)
```


La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti. Questo metodo è deprecato. Si prega di utilizzare il più efficace [CmykColorHelper.toArgb(int)](../../com.aspose.imaging/cmykcolorhelper\#toArgb-int-)\}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | I pixel del tipo CMYKColor in formato CMYK. |

**Returns:**
com.aspose.imaging.Color[] - L'array dei colori ARGB.
### toArgb32(CmykColor[] cmykPixels) {#toArgb32-com.aspose.imaging.CmykColor---}
```
public static int[] toArgb32(CmykColor[] cmykPixels)
```


La conversione da CMYKColor a colore ARGB a 32 bit usando la conversione icc con profili predefiniti. Questo metodo è deprecato. Si prega di utilizzare il più efficace `CmykColorHelper.toArgb32(int[])`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | I pixel del tipo CMYKColor in formato CMYK. |

**Returns:**
int[] - L'array del colore ARGB a 32 bit.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static CmykColor toCmyk(int argbPixel)
```


La conversione da ARGB a 32 bit a CMYKColor. Questo metodo è deprecato. Si prega di utilizzare il più efficace `CmykColorHelper.toCmyk(int)`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argbPixel | int | Il pixel del formato ARGB a 32 bit. |

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor) - The [CmykColor](../../com.aspose.imaging/cmykcolor).
### toColor(CmykColor cmykPixel) {#toColor-com.aspose.imaging.CmykColor-}
```
public static Color toColor(CmykColor cmykPixel)
```


La conversione da CMYKColor a Color. Questo metodo è deprecato. Si prega di utilizzare il più efficace `CmykColorHelper.toArgb(int)`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | I pixel del tipo CMYKColor in formato CMYK. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor[] cmykPixels) {#toColorIcc-com.aspose.imaging.CmykColor---}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels)
```


La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti. Questo metodo è deprecato. Si prega di utilizzare il più efficace CmykColorHelper\#toArgbIcc(int[]).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | I pixel del tipo CMYKColor in formato CMYK. |

**Returns:**
com.aspose.imaging.Color[] - Il `com.com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor cmykPixel) {#toColorIcc-com.aspose.imaging.CmykColor-}
```
public static Color toColorIcc(CmykColor cmykPixel)
```


La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti. Questo metodo è deprecato. Si prega di utilizzare il più efficace `CmykColorHelper.toArgbIcc(int)`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | Il pixel del tipo CMYKColor in formato CMYK. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `Color`.
### toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.imaging.CmykColor---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


La conversione da CMYKColor a Color usando la conversione icc. Questo metodo è deprecato. Si prega di utilizzare il più efficace `CmykColorHelper.toArgbIcc(int[], InputStream, InputStream)`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | I pixel del tipo CMYKColor in formato CMYK. |
| cmykIccStream | java.io.InputStream | Il flusso contenente il profilo icc cmyk. |
| rgbIccStream | java.io.InputStream | Il flusso contenente il profilo icc rgb. |

**Returns:**
com.aspose.imaging.Color[] - Il `com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.imaging.CmykColor-java.io.InputStream-java.io.InputStream-}
```
public static Color toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


La conversione da CMYKColor a Color usando la conversione icc. Questo metodo è deprecato. Si prega di utilizzare il più efficace `CmykColorHelper.toArgbIcc(int, Stream, Stream)`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | Il pixel del tipo CMYKColor in formato CMYK. |
| cmykIccStream | java.io.InputStream | Il flusso contenente il profilo icc cmyk. |
| rgbIccStream | java.io.InputStream | Il flusso contenente il profilo icc rgb. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `Color`.
### isEquals(CmykColor obj1, CmykColor obj2) {#isEquals-com.aspose.imaging.CmykColor-com.aspose.imaging.CmykColor-}
```
public static boolean isEquals(CmykColor obj1, CmykColor obj2)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj1 | [CmykColor](../../com.aspose.imaging/cmykcolor) |  |
| obj2 | [CmykColor](../../com.aspose.imaging/cmykcolor) |  |

**Returns:**
boolean
### getC() {#getC--}
```
public byte getC()
```


Restituisce il valore del componente ciano di questa struttura `com.com.aspose.imaging.Color`.

**Returns:**
byte - Il valore del componente ciano di questo `com.com.aspose.imaging.Color`.
### getM() {#getM--}
```
public byte getM()
```


Restituisce il valore del componente magenta di questa struttura `com.com.aspose.imaging.Color`.

**Returns:**
byte - Il valore del componente magenta di questo `com.com.aspose.imaging.Color`.
### getY() {#getY--}
```
public byte getY()
```


Restituisce il valore del componente giallo di questa struttura `com.com.aspose.imaging.Color`.

**Returns:**
byte - Il valore del componente giallo di questo `com.com.aspose.imaging.Color`.
### getK() {#getK--}
```
public byte getK()
```


Restituisce il valore del componente nero di questa struttura `com.com.aspose.imaging.Color`.

Valore: Il valore del componente nero di questo `com.com.aspose.imaging.Color`.

**Returns:**
byte
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Restituisce un valore che indica se questa struttura `com.com.aspose.imaging.Color` è non inizializzata.

**Returns:**
boolean - Questa proprietà restituisce true se questo colore non è inizializzato; altrimenti, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Il metodo get hash code.

**Returns:**
int - Il `int`.
### toValue() {#toValue--}
```
public long toValue()
```


Il valore to.

**Returns:**
long - Il valore CMYK long.
### CloneTo(CmykColor that) {#CloneTo-com.aspose.imaging.CmykColor-}
```
public void CloneTo(CmykColor that)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| that | [CmykColor](../../com.aspose.imaging/cmykcolor) |  |

### Clone() {#Clone--}
```
public CmykColor Clone()
```




**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
