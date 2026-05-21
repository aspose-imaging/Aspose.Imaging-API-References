---
title: "CmykColor"
second_title: "Aspose.Imaging för Java API-referens"
description: "CMYK-färgen för pixeln."
type: docs
weight: 18
url: /sv/java/com.aspose.imaging/cmykcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class CmykColor extends Struct<CmykColor>
```

CMYK-färgen för pixeln.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [CmykColor()](#CmykColor--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEmpty()](#getEmpty--) | Hämtar den tomma. |
| [fromParams(int cyan, int magenta, int yellow, int black)](#fromParams-int-int-int-int-) | Skapar en `CmykColor`-struktur från 32-bitars cyan-, magenta-, gul- och svartvärden. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | Konverteringen från 32-bitars ARGB-färg till CMYKColor. |
| [toColor(CmykColor[] cmykPixels)](#toColor-com.aspose.imaging.CmykColor---) | Konverteringen från CMYKColor till Color med icc-konvertering och standardprofiler. |
| [toArgb32(CmykColor[] cmykPixels)](#toArgb32-com.aspose.imaging.CmykColor---) | Konverteringen från CMYKColor till 32-bitars ARGB Color med icc-konvertering och standardprofiler. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | Konverteringen från 32-bitars ARGB till CMYKColor. |
| [toColor(CmykColor cmykPixel)](#toColor-com.aspose.imaging.CmykColor-) | Konverteringen från CMYKColor till Color. |
| [toColorIcc(CmykColor[] cmykPixels)](#toColorIcc-com.aspose.imaging.CmykColor---) | Konverteringen från CMYKColor till Color med icc-konvertering och standardprofiler. |
| [toColorIcc(CmykColor cmykPixel)](#toColorIcc-com.aspose.imaging.CmykColor-) | Konverteringen från CMYKColor till Color med icc-konvertering och standardprofiler. |
| [toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.imaging.CmykColor---java.io.InputStream-java.io.InputStream-) | Konverteringen från CMYKColor till Color med icc-konvertering. |
| [toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.imaging.CmykColor-java.io.InputStream-java.io.InputStream-) | Konverteringen från CMYKColor till Color med icc-konvertering. |
| [isEquals(CmykColor obj1, CmykColor obj2)](#isEquals-com.aspose.imaging.CmykColor-com.aspose.imaging.CmykColor-) |  |
| [getC()](#getC--) | Hämtar cyan-komponentens värde för denna `com.com.aspose.imaging.Color`-struktur. |
| [getM()](#getM--) | Hämtar magenta-komponentens värde för denna `com.com.aspose.imaging.Color`-struktur. |
| [getY()](#getY--) | Hämtar gul-komponentens värde för denna `com.com.aspose.imaging.Color`-struktur. |
| [getK()](#getK--) | Hämtar svart-komponentens värde för denna `com.com.aspose.imaging.Color`-struktur. |
| [isEmpty()](#isEmpty--) | Hämtar ett värde som indikerar om denna `com.com.aspose.imaging.Color`-struktur är oinitierad. |
| [hashCode()](#hashCode--) | Hash‑koden för get. |
| [toValue()](#toValue--) | Värdet för to. |
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


Hämtar den tomma.

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor)
### fromParams(int cyan, int magenta, int yellow, int black) {#fromParams-int-int-int-int-}
```
public static CmykColor fromParams(int cyan, int magenta, int yellow, int black)
```


Skapar en `CmykColor`-struktur från 32‑bitars cyan-, magenta-, gul- och svartvärden. Denna metod är föråldrad. Använd mer effektiv CmykColorHelper\#fromComponents(int, int, int, int).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cyan | int | Den cyan‑komponenten. Giltiga värden är 0 till 255. |
| magenta | int | Den magenta komponenten. Giltiga värden är 0 till 255. |
| gul | int | Den gula komponenten. Giltiga värden är 0 till 255. |
| svart | int | Den svarta komponenten. Giltiga värden är 0 till 255. |

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor) - The `CmykColor`.
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static CmykColor[] toCmyk(int[] argbPixels)
```


Konverteringen från 32‑bitars ARGB‑färg till CMYKColor. Denna metod är föråldrad. Använd mer effektiv `CmykColorHelper.toCmyk(int[])`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argbPixels | int[] | Pixlarna i 32‑bitars ARGB‑format. |

**Returns:**
com.aspose.imaging.CmykColor[] - Den [CmykColor](../../com.aspose.imaging/cmykcolor)[].
### toColor(CmykColor[] cmykPixels) {#toColor-com.aspose.imaging.CmykColor---}
```
public static Color[] toColor(CmykColor[] cmykPixels)
```


Konverteringen från CMYKColor till Color med icc‑konvertering och standardprofiler. Denna metod är föråldrad. Använd mer effektiv [CmykColorHelper.toArgb(int)](../../com.aspose.imaging/cmykcolorhelper\#toArgb-int-)\}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | Pixlarna av typen CMYKColor i CMYK‑format. |

**Returns:**
com.aspose.imaging.Color[] - Arrayen av ARGB‑färgerna.
### toArgb32(CmykColor[] cmykPixels) {#toArgb32-com.aspose.imaging.CmykColor---}
```
public static int[] toArgb32(CmykColor[] cmykPixels)
```


Konverteringen från CMYKColor till 32‑bitars ARGB‑Color med icc‑konvertering och standardprofiler. Denna metod är föråldrad. Använd mer effektiv `CmykColorHelper.toArgb32(int[])`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | Pixlarna av typen CMYKColor i CMYK‑format. |

**Returns:**
int[] - Arrayen av den 32‑bitars ARGB‑färgen.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static CmykColor toCmyk(int argbPixel)
```


Konverteringen från 32‑bitars ARGB till CMYKColor. Denna metod är föråldrad. Använd mer effektiv `CmykColorHelper.toCmyk(int)`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argbPixel | int | Pixeln i 32‑bitars ARGB‑format. |

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor) - The [CmykColor](../../com.aspose.imaging/cmykcolor).
### toColor(CmykColor cmykPixel) {#toColor-com.aspose.imaging.CmykColor-}
```
public static Color toColor(CmykColor cmykPixel)
```


Konverteringen från CMYKColor till Color. Denna metod är föråldrad. Använd mer effektiv `CmykColorHelper.toArgb(int)`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | Pixlarna av typen CMYKColor i CMYK‑format. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor[] cmykPixels) {#toColorIcc-com.aspose.imaging.CmykColor---}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels)
```


Konverteringen från CMYKColor till Color med icc‑konvertering och standardprofiler. Denna metod är föråldrad. Använd mer effektiv CmykColorHelper\#toArgbIcc(int[]).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | Pixlarna av typen CMYKColor i CMYK‑format. |

**Returns:**
com.aspose.imaging.Color[] - `com.com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor cmykPixel) {#toColorIcc-com.aspose.imaging.CmykColor-}
```
public static Color toColorIcc(CmykColor cmykPixel)
```


Konverteringen från CMYKColor till Color med icc‑konvertering och standardprofiler. Denna metod är föråldrad. Använd mer effektiv `CmykColorHelper.toArgbIcc(int)`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | Pixeln av typen CMYKColor i CMYK‑format. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `Color`.
### toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.imaging.CmykColor---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


Konverteringen från CMYKColor till Color med icc‑konvertering. Denna metod är föråldrad. Använd mer effektiv `CmykColorHelper.toArgbIcc(int[], InputStream, InputStream)`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | Pixlarna av typen CMYKColor i CMYK‑format. |
| cmykIccStream | java.io.InputStream | Strömmen som innehåller icc cmyk-profilen. |
| rgbIccStream | java.io.InputStream | Strömmen som innehåller icc rgb-profilen. |

**Returns:**
com.aspose.imaging.Color[] - `com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.imaging.CmykColor-java.io.InputStream-java.io.InputStream-}
```
public static Color toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


Konverteringen från CMYKColor till Color med icc‑konvertering. Denna metod är föråldrad. Använd mer effektiv `CmykColorHelper.toArgbIcc(int, Stream, Stream)`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | Pixeln av typen CMYKColor i CMYK‑format. |
| cmykIccStream | java.io.InputStream | Strömmen som innehåller icc cmyk-profilen. |
| rgbIccStream | java.io.InputStream | Strömmen som innehåller icc rgb-profilen. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `Color`.
### isEquals(CmykColor obj1, CmykColor obj2) {#isEquals-com.aspose.imaging.CmykColor-com.aspose.imaging.CmykColor-}
```
public static boolean isEquals(CmykColor obj1, CmykColor obj2)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj1 | [CmykColor](../../com.aspose.imaging/cmykcolor) |  |
| obj2 | [CmykColor](../../com.aspose.imaging/cmykcolor) |  |

**Returns:**
boolean
### getC() {#getC--}
```
public byte getC()
```


Hämtar cyan-komponentens värde för denna `com.com.aspose.imaging.Color`-struktur.

**Returns:**
byte - Cyan‑komponentvärdet för detta `com.com.aspose.imaging.Color`.
### getM() {#getM--}
```
public byte getM()
```


Hämtar magenta-komponentens värde för denna `com.com.aspose.imaging.Color`-struktur.

**Returns:**
byte - Magenta‑komponentvärdet för detta `com.com.aspose.imaging.Color`.
### getY() {#getY--}
```
public byte getY()
```


Hämtar gul-komponentens värde för denna `com.com.aspose.imaging.Color`-struktur.

**Returns:**
byte - Gul‑komponentvärdet för detta `com.com.aspose.imaging.Color`.
### getK() {#getK--}
```
public byte getK()
```


Hämtar svart-komponentens värde för denna `com.com.aspose.imaging.Color`-struktur.

Värde: Det svarta komponentvärdet för detta `com.com.aspose.imaging.Color`.

**Returns:**
byte
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Hämtar ett värde som indikerar om denna `com.com.aspose.imaging.Color`-struktur är oinitierad.

**Returns:**
boolean - Denna egenskap returnerar sant om denna färg är oinitierad; annars falskt.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hash‑koden för get.

**Returns:**
int - Det `int`.
### toValue() {#toValue--}
```
public long toValue()
```


Värdet för to.

**Returns:**
long - Det långa CMYK‑värdet.
### CloneTo(CmykColor that) {#CloneTo-com.aspose.imaging.CmykColor-}
```
public void CloneTo(CmykColor that)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
