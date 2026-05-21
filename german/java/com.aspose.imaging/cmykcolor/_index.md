---
title: "CmykColor"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die CMYK-Farbe des Pixels."
type: docs
weight: 18
url: /de/java/com.aspose.imaging/cmykcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class CmykColor extends Struct<CmykColor>
```

Die CMYK-Farbe des Pixels.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CmykColor()](#CmykColor--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEmpty()](#getEmpty--) | Gibt das Leere zurück. |
| [fromParams(int cyan, int magenta, int yellow, int black)](#fromParams-int-int-int-int-) | Erstellt eine `CmykColor`-Struktur aus 32‑Bit‑Cyan-, Magenta-, Gelb- und Schwarzwerten. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | Die Konvertierung von 32‑Bit‑ARGB-Farbe zu CMYKColor. |
| [toColor(CmykColor[] cmykPixels)](#toColor-com.aspose.imaging.CmykColor---) | Die Konvertierung von CMYKColor zu Color mittels ICC-Konvertierung mit Standardprofilen. |
| [toArgb32(CmykColor[] cmykPixels)](#toArgb32-com.aspose.imaging.CmykColor---) | Die Konvertierung von CMYKColor zu 32‑Bit‑ARGB-Color mittels ICC-Konvertierung mit Standardprofilen. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | Die Konvertierung von 32‑Bit‑ARGB zu CMYKColor. |
| [toColor(CmykColor cmykPixel)](#toColor-com.aspose.imaging.CmykColor-) | Die Konvertierung von CMYKColor zu Color. |
| [toColorIcc(CmykColor[] cmykPixels)](#toColorIcc-com.aspose.imaging.CmykColor---) | Die Konvertierung von CMYKColor zu Color mittels ICC-Konvertierung mit Standardprofilen. |
| [toColorIcc(CmykColor cmykPixel)](#toColorIcc-com.aspose.imaging.CmykColor-) | Die Konvertierung von CMYKColor zu Color mittels ICC-Konvertierung mit Standardprofilen. |
| [toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.imaging.CmykColor---java.io.InputStream-java.io.InputStream-) | Die Konvertierung von CMYKColor zu Color mittels ICC-Konvertierung. |
| [toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.imaging.CmykColor-java.io.InputStream-java.io.InputStream-) | Die Konvertierung von CMYKColor zu Color mittels ICC-Konvertierung. |
| [isEquals(CmykColor obj1, CmykColor obj2)](#isEquals-com.aspose.imaging.CmykColor-com.aspose.imaging.CmykColor-) |  |
| [getC()](#getC--) | Gibt den Cyan-Komponentenwert dieser `com.com.aspose.imaging.Color`-Struktur zurück. |
| [getM()](#getM--) | Gibt den Magenta-Komponentenwert dieser `com.com.aspose.imaging.Color`-Struktur zurück. |
| [getY()](#getY--) | Gibt den Gelb-Komponentenwert dieser `com.com.aspose.imaging.Color`-Struktur zurück. |
| [getK()](#getK--) | Gibt den Schwarz-Komponentenwert dieser `com.com.aspose.imaging.Color`-Struktur zurück. |
| [isEmpty()](#isEmpty--) | Ermittelt einen Wert, der angibt, ob diese `com.com.aspose.imaging.Color`-Struktur nicht initialisiert ist. |
| [hashCode()](#hashCode--) | Der Hashcode wird abgerufen. |
| [toValue()](#toValue--) | Der Rückgabewert. |
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


Gibt das Leere zurück.

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor)
### fromParams(int cyan, int magenta, int yellow, int black) {#fromParams-int-int-int-int-}
```
public static CmykColor fromParams(int cyan, int magenta, int yellow, int black)
```


Erstellt eine `CmykColor`-Struktur aus 32‑Bit‑Cyan-, Magenta-, Gelb‑ und Schwarzwerten. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere CmykColorHelper\\#fromComponents(int, int, int, int).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Cyan | int | Die Cyan‑Komponente. Gültige Werte sind 0 bis 255. |
| Magenta | int | Die Magenta‑Komponente. Gültige Werte sind 0 bis 255. |
| Gelb | int | Die Gelb‑Komponente. Gültige Werte sind 0 bis 255. |
| Schwarz | int | Die Schwarz‑Komponente. Gültige Werte sind 0 bis 255. |

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor) - The `CmykColor`.
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static CmykColor[] toCmyk(int[] argbPixels)
```


Die Konvertierung von 32‑Bit‑ARGB‑Farbe zu CMYKColor. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere `CmykColorHelper.toCmyk(int[])`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| argbPixels | int[] | Die Pixel im 32‑Bit‑ARGB‑Format. |

**Returns:**
com.aspose.imaging.CmykColor[] - Das [CmykColor](../../com.aspose.imaging/cmykcolor)[].
### toColor(CmykColor[] cmykPixels) {#toColor-com.aspose.imaging.CmykColor---}
```
public static Color[] toColor(CmykColor[] cmykPixels)
```


Die Konvertierung von CMYKColor zu Color mittels ICC-Konvertierung mit Standardprofilen. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.toArgb(int)](../../com.aspose.imaging/cmykcolorhelper\\#toArgb-int-)\\}.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | Die Pixel des CMYKColor‑Typs im CMYK‑Format. |

**Returns:**
com.aspose.imaging.Color[] - Das Array der ARGB‑Farben.
### toArgb32(CmykColor[] cmykPixels) {#toArgb32-com.aspose.imaging.CmykColor---}
```
public static int[] toArgb32(CmykColor[] cmykPixels)
```


Die Konvertierung von CMYKColor zu 32‑Bit‑ARGB‑Color mittels ICC-Konvertierung mit Standardprofilen. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere `CmykColorHelper.toArgb32(int[])`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | Die Pixel des CMYKColor‑Typs im CMYK‑Format. |

**Returns:**
int[] - Das Array der 32‑Bit‑ARGB‑Farbe.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static CmykColor toCmyk(int argbPixel)
```


Die Konvertierung von 32‑Bit‑ARGB zu CMYKColor. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere `CmykColorHelper.toCmyk(int)`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| argbPixel | int | Der Pixel im 32‑Bit‑ARGB‑Format. |

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor) - The [CmykColor](../../com.aspose.imaging/cmykcolor).
### toColor(CmykColor cmykPixel) {#toColor-com.aspose.imaging.CmykColor-}
```
public static Color toColor(CmykColor cmykPixel)
```


Die Konvertierung von CMYKColor zu Color. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere `CmykColorHelper.toArgb(int)`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | Die Pixel des CMYKColor‑Typs im CMYK‑Format. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor[] cmykPixels) {#toColorIcc-com.aspose.imaging.CmykColor---}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels)
```


Die Konvertierung von CMYKColor zu Color mittels ICC-Konvertierung mit Standardprofilen. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere CmykColorHelper\\#toArgbIcc(int[]).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | Die Pixel des CMYKColor‑Typs im CMYK‑Format. |

**Returns:**
com.aspose.imaging.Color[] - Die `com.com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor cmykPixel) {#toColorIcc-com.aspose.imaging.CmykColor-}
```
public static Color toColorIcc(CmykColor cmykPixel)
```


Die Konvertierung von CMYKColor zu Color mittels ICC-Konvertierung mit Standardprofilen. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere `CmykColorHelper.toArgbIcc(int)`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | Der Pixel des CMYKColor‑Typs im CMYK‑Format. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `Color`.
### toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.imaging.CmykColor---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


Die Konvertierung von CMYKColor zu Color mittels ICC-Konvertierung. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere `CmykColorHelper.toArgbIcc(int[], InputStream, InputStream)`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | Die Pixel des CMYKColor‑Typs im CMYK‑Format. |
| cmykIccStream | java.io.InputStream | Der Stream, der das ICC-CMYK-Profil enthält. |
| rgbIccStream | java.io.InputStream | Der Stream, der das ICC-RGB-Profil enthält. |

**Returns:**
com.aspose.imaging.Color[] - Die `com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.imaging.CmykColor-java.io.InputStream-java.io.InputStream-}
```
public static Color toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


Die Konvertierung von CMYKColor zu Color mittels ICC-Konvertierung. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere `CmykColorHelper.toArgbIcc(int, Stream, Stream)`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | Der Pixel des CMYKColor‑Typs im CMYK‑Format. |
| cmykIccStream | java.io.InputStream | Der Stream, der das ICC-CMYK-Profil enthält. |
| rgbIccStream | java.io.InputStream | Der Stream, der das ICC-RGB-Profil enthält. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `Color`.
### isEquals(CmykColor obj1, CmykColor obj2) {#isEquals-com.aspose.imaging.CmykColor-com.aspose.imaging.CmykColor-}
```
public static boolean isEquals(CmykColor obj1, CmykColor obj2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj1 | [CmykColor](../../com.aspose.imaging/cmykcolor) |  |
| obj2 | [CmykColor](../../com.aspose.imaging/cmykcolor) |  |

**Returns:**
boolean
### getC() {#getC--}
```
public byte getC()
```


Gibt den Cyan-Komponentenwert dieser `com.com.aspose.imaging.Color`-Struktur zurück.

**Returns:**
byte - Der Cyan‑Komponentenwert dieses `com.com.aspose.imaging.Color`.
### getM() {#getM--}
```
public byte getM()
```


Gibt den Magenta-Komponentenwert dieser `com.com.aspose.imaging.Color`-Struktur zurück.

**Returns:**
byte - Der Magenta‑Komponentenwert dieses `com.com.aspose.imaging.Color`.
### getY() {#getY--}
```
public byte getY()
```


Gibt den Gelb-Komponentenwert dieser `com.com.aspose.imaging.Color`-Struktur zurück.

**Returns:**
byte - Der Gelb‑Komponentenwert dieses `com.com.aspose.imaging.Color`.
### getK() {#getK--}
```
public byte getK()
```


Gibt den Schwarz-Komponentenwert dieser `com.com.aspose.imaging.Color`-Struktur zurück.

Wert: Der Schwarz‑Komponentenwert dieses `com.com.aspose.imaging.Color`.

**Returns:**
byte
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Ermittelt einen Wert, der angibt, ob diese `com.com.aspose.imaging.Color`-Struktur nicht initialisiert ist.

**Returns:**
boolean - Diese Eigenschaft gibt wahr zurück, wenn diese Farbe nicht initialisiert ist; andernfalls falsch.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Der Hashcode wird abgerufen.

**Returns:**
int - Der `int`.
### toValue() {#toValue--}
```
public long toValue()
```


Der Rückgabewert.

**Returns:**
long - Der lange CMYK-Wert.
### CloneTo(CmykColor that) {#CloneTo-com.aspose.imaging.CmykColor-}
```
public void CloneTo(CmykColor that)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
