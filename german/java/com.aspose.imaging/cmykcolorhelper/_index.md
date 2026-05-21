---
title: "CmykColorHelper"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Hilfsmethoden zur Arbeit mit CMYK-Farbe, dargestellt als vorzeichenbehafteter 32-Bit-Integerwert."
type: docs
weight: 19
url: /de/java/com.aspose.imaging/cmykcolorhelper/
---
**Inheritance:**
java.lang.Object
```
public final class CmykColorHelper
```

Hilfsmethoden zur Arbeit mit CMYK-Farben, die als vorzeichenbehafteter 32‑Bit‑Integerwert dargestellt werden. Bietet eine ähnliche API wie die Struktur [CmykColor](../../com.aspose.imaging/cmykcolor). Sie ist leichter, weil die CMYK‑Farbe nur als Int32 und nicht als Struktur mit internen Feldern dargestellt wird. Bitte verwenden Sie nach Möglichkeit die statischen Methoden dieser Klasse anstelle der veralteten Struktur [CmykColor](../../com.aspose.imaging/cmykcolor).
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getC(int cmyk)](#getC-int-) | Gibt den Cyan‑Komponentenwert zurück. |
| [getM(int cmyk)](#getM-int-) | Gibt den Magenta‑Komponentenwert zurück. |
| [getY(int cmyk)](#getY-int-) | Gibt den Gelb‑Komponentenwert zurück. |
| [getK(int cmyk)](#getK-int-) | Gibt den Schwarz‑Komponentenwert zurück. |
| [fromComponents(int cyan, int magenta, int yellow, int black)](#fromComponents-int-int-int-int-) | Erstellt CMYK aus 32‑Bit‑Cyan-, Magenta-, Gelb- und Schwarzwerten. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | Die Umwandlung von ARGB-Farben zu CMYK-Farben. |
| [toCmykBytes(int[] argbPixels, int startIndex, int length)](#toCmykBytes-int---int-int-) | Konvertiert ARGB zu CMYK. |
| [toCmykaBytes(int[] argbPixels, int startIndex, int length)](#toCmykaBytes-int---int-int-) | Konvertiert ARGB zu CMYKA (mit Transparenz). |
| [toCmyk(int argbPixel)](#toCmyk-int-) | Die Umwandlung von ARGB-Farbe zu CMYK-Farbe. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.imaging.Color-) | Die Umwandlung von ARGB-Farbe zu CMYK-Farbe. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.imaging.Color---) | Die Umwandlung von ARGB-Farben zu CMYK-Farben. |
| [toArgb(int[] cmykPixels)](#toArgb-int---) | Die Umwandlung von CMYK-Farben zu ARGB-Farben. |
| [toArgb(int cmykPixel)](#toArgb-int-) | Die Umwandlung von CMYK-Farbe zu ARGB-Farbe. |
| [toArgb32(int[] cmykPixels)](#toArgb32-int---) | Die Umwandlung von CMYK-Farben zu ARGB-Farben. |
| [toArgb32(int[] cmykPixels, boolean reuseArray)](#toArgb32-int---boolean-) | Führt die Umwandlung von CMYK-Farben zu ARGB-Farben durch und speichert sie im selben Array, wenn `reuseArray` wahr ist. |
| [toArgbIcc(int[] cmykPixels)](#toArgbIcc-int---) | Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit Standardprofilen. |
| [toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int---java.io.InputStream-java.io.InputStream-) | Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| [toArgbIcc(int cmykPixel)](#toArgbIcc-int-) | Die Umwandlung von CMYK-Farbe zu ARGB-Farbe mittels Icc-Konvertierung mit Standardprofilen. |
| [toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int-java.io.InputStream-java.io.InputStream-) | Die Umwandlung von CMYK-Farbe zu ARGB-Farbe mittels Icc-Konvertierung mit benutzerdefiniertem Profil. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.imaging.Color---java.io.InputStream-java.io.InputStream-) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| [toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-int---java.io.InputStream-java.io.InputStream-) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | Konvertiert RGB zu CMYK mit benutzerdefinierten ICC-Profilen. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-) | Konvertiert RGB zu CMYK mit benutzerdefinierten ICC-Profilen. |
| [toCmykaIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykaIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-) | Konvertiert RGB zu CMYKA (mit Alpha) mit benutzerdefinierten ICC-Profilen. |
| [toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toPsdCmykIcc-int---java.io.InputStream-java.io.InputStream-) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| [toCmykaIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykaIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | Konvertiert RGB zu CMYKA (mit Alpha) mit benutzerdefinierten ICC-Profilen. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.imaging.Color---) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit Standardprofilen. |
| [toCmykIcc(int[] pixels)](#toCmykIcc-int---) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit Standardprofilen. |
| [toPsdCmykIcc(int[] pixels)](#toPsdCmykIcc-int---) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit Standardprofilen. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.imaging.Color-) | Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit Standardprofilen. |
| [toCmykIcc(int argb)](#toCmykIcc-int-) | Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit Standardprofilen. |
| [toPsdCmykIcc(int argb)](#toPsdCmykIcc-int-) | Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit Standardprofilen. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.imaging.Color-java.io.InputStream-java.io.InputStream-) | Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| [toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-int-java.io.InputStream-java.io.InputStream-) | Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| [toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toPsdCmykIcc-int-java.io.InputStream-java.io.InputStream-) | Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
### getC(int cmyk) {#getC-int-}
```
public static int getC(int cmyk)
```


Gibt den Cyan‑Komponentenwert zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmyk | int | Die CMYK-Farbe dargestellt als 32‑Bit‑Ganzzahlwert. |

**Returns:**
int – Der Cyan‑Komponentenwert.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts without applying ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK without using ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmyk(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(@%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

//Die Ausgabe sieht folgendermaßen aus:
//Konvertiere RGB zu CMYK ohne ICC-Profile zu verwenden.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getM(int cmyk) {#getM-int-}
```
public static int getM(int cmyk)
```


Gibt den Magenta‑Komponentenwert zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmyk | int | Die CMYK-Farbe dargestellt als 32‑Bit‑Ganzzahlwert. |

**Returns:**
int - Der Magenta‑Komponentenwert.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts without applying ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK without using ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmyk(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(@%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

//Die Ausgabe sieht folgendermaßen aus:
//Konvertiere RGB zu CMYK ohne ICC-Profile zu verwenden.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getY(int cmyk) {#getY-int-}
```
public static int getY(int cmyk)
```


Gibt den Gelb‑Komponentenwert zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmyk | int | Die CMYK-Farbe dargestellt als 32‑Bit‑Ganzzahlwert. |

**Returns:**
int - Der Gelb‑Komponentenwert.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts without applying ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK without using ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmyk(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(@%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

//Die Ausgabe sieht folgendermaßen aus:
//Konvertiere RGB zu CMYK ohne ICC-Profile zu verwenden.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getK(int cmyk) {#getK-int-}
```
public static int getK(int cmyk)
```


Gibt den Schwarz‑Komponentenwert zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmyk | int | Die CMYK-Farbe dargestellt als 32‑Bit‑Ganzzahlwert. |

**Returns:**
int - Der Schwarz‑Komponentenwert.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts without applying ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK without using ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmyk(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(@%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

//Die Ausgabe sieht folgendermaßen aus:
//Konvertiere RGB zu CMYK ohne ICC-Profile zu verwenden.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### fromComponents(int cyan, int magenta, int yellow, int black) {#fromComponents-int-int-int-int-}
```
public static int fromComponents(int cyan, int magenta, int yellow, int black)
```


Erstellt CMYK aus 32‑Bit‑Cyan-, Magenta-, Gelb- und Schwarzwerten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Cyan | int | Die Cyan‑Komponente. Gültige Werte sind 0 bis 255. |
| Magenta | int | Die Magenta‑Komponente. Gültige Werte sind 0 bis 255. |
| Gelb | int | Die Gelb‑Komponente. Gültige Werte sind 0 bis 255. |
| Schwarz | int | Die Schwarz‑Komponente. Gültige Werte sind 0 bis 255. |

**Returns:**
int - Die CMYK‑Farbe, dargestellt als 32‑Bit‑Ganzzahlwert.

**Example: The following example shows how to convert CMYK colors to their RGB counterparts in a fast manner following straightforward formulas without using ICC profiles.**

``` java
int[] cmykColors = new int[]
        {
                com.aspose.imaging.CmykColorHelper.fromComponents(255, 0, 0, 0),   // Cyan
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 255, 0, 0),   // Magenta
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 255, 0),   // Yellow
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 0, 255),   // Black
        };

System.out.println("Convert CMYK to RGB without using ICC profiles.");
for (int cmykColor : cmykColors) {
    com.aspose.imaging.Color rgbColor = com.aspose.imaging.CmykColorHelper.toArgb(cmykColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmykColor);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmykColor);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmykColor);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmykColor);

    System.out.printf("CMYK(%s,%s,%s,%s)\t\t=> RGB(%s,%s,%s)\r\n", c, m, y, k, rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, (int) rgbColor.getB() & 0xff);
}

//Die Ausgabe sieht folgendermaßen aus:
//Konvertiere CMYK zu RGB ohne Verwendung von ICC‑Profilen.
//CMYK(255,0,0,0)        => RGB(0,255,255)
//CMYK(0,255,0,0)        => RGB(255,0,255)
//CMYK(0,0,255,0)        => RGB(255,255,0)
//CMYK(0,0,0,255)        => RGB(0,0,0)
```

### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static int[] toCmyk(int[] argbPixels)
```


Die Umwandlung von ARGB-Farben zu CMYK-Farben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| argbPixels | int[] | Die ARGB‑Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |

**Returns:**
int[] - Die CMYK‑Farben, dargestellt als 32‑Bit‑Ganzzahlwerte.
### toCmykBytes(int[] argbPixels, int startIndex, int length) {#toCmykBytes-int---int-int-}
```
public static byte[] toCmykBytes(int[] argbPixels, int startIndex, int length)
```


Konvertiert ARGB zu CMYK.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| argbPixels | int[] | Die RGB‑Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |
| startIndex | int | Der Startindex der RGB‑Farbe. |
| length | int | Die Anzahl der zu konvertierenden RGB‑Pixel. |

**Returns:**
byte[] - Die CMYK-Farben, dargestellt als Byte-Array.
### toCmykaBytes(int[] argbPixels, int startIndex, int length) {#toCmykaBytes-int---int-int-}
```
public static byte[] toCmykaBytes(int[] argbPixels, int startIndex, int length)
```


Konvertiert ARGB zu CMYKA (mit Transparenz).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| argbPixels | int[] | Die RGB‑Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |
| startIndex | int | Der Startindex der RGB‑Farbe. |
| length | int | Die Anzahl der zu konvertierenden RGB‑Pixel. |

**Returns:**
byte[] - Die CMYK-Farben, dargestellt als Byte-Array.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static int toCmyk(int argbPixel)
```


Die Umwandlung von ARGB-Farbe zu CMYK-Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| argbPixel | int | Die ARGB-Farbe, dargestellt als 32-Bit-Ganzzahlwert. |

**Returns:**
int - Die CMYK‑Farbe, dargestellt als 32‑Bit‑Ganzzahlwert.
### toCmyk(Color pixel) {#toCmyk-com.aspose.imaging.Color-}
```
public static int toCmyk(Color pixel)
```


Die Umwandlung von ARGB-Farbe zu CMYK-Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | Die ARGB-Farbe. |

**Returns:**
int - Die CMYK‑Farbe, dargestellt als 32‑Bit‑Ganzzahlwert.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts without applying ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK without using ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmyk(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(@%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

//Die Ausgabe sieht folgendermaßen aus:
//Konvertiere RGB zu CMYK ohne ICC-Profile zu verwenden.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### toCmyk(Color[] pixels) {#toCmyk-com.aspose.imaging.Color---}
```
public static int[] toCmyk(Color[] pixels)
```


Die Umwandlung von ARGB-Farben zu CMYK-Farben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | Die ARGB-Farben. |

**Returns:**
int[] - Die CMYK‑Farben, dargestellt als 32‑Bit‑Ganzzahlwerte.
### toArgb(int[] cmykPixels) {#toArgb-int---}
```
public static Color[] toArgb(int[] cmykPixels)
```


Die Umwandlung von CMYK-Farben zu ARGB-Farben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixels | int[] | Die CMYK-Farben, dargestellt als 32-Bit-Ganzzahlwerte. |

**Returns:**
com.aspose.imaging.Color[] - Die ARGB-Farben.
### toArgb(int cmykPixel) {#toArgb-int-}
```
public static Color toArgb(int cmykPixel)
```


Die Umwandlung von CMYK-Farbe zu ARGB-Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixel | int | Die CMYK-Farbe dargestellt als 32‑Bit‑Ganzzahlwert. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The ARGB color.

**Example: The following example shows how to convert CMYK colors to their RGB counterparts in a fast manner following straightforward formulas without using ICC profiles.**

``` java
int[] cmykColors = new int[]
        {
                com.aspose.imaging.CmykColorHelper.fromComponents(255, 0, 0, 0),   // Cyan
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 255, 0, 0),   // Magenta
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 255, 0),   // Yellow
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 0, 255),   // Black
        };

System.out.println("Convert CMYK to RGB without using ICC profiles.");
for (int cmykColor : cmykColors) {
    com.aspose.imaging.Color rgbColor = com.aspose.imaging.CmykColorHelper.toArgb(cmykColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmykColor);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmykColor);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmykColor);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmykColor);

    System.out.printf("CMYK(%s,%s,%s,%s)\t\t=> RGB(%s,%s,%s)\r\n", c, m, y, k, rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, (int) rgbColor.getB() & 0xff);
}

//Die Ausgabe sieht folgendermaßen aus:
//Konvertiere CMYK zu RGB ohne Verwendung von ICC‑Profilen.
//CMYK(255,0,0,0)        => RGB(0,255,255)
//CMYK(0,255,0,0)        => RGB(255,0,255)
//CMYK(0,0,255,0)        => RGB(255,255,0)
//CMYK(0,0,0,255)        => RGB(0,0,0)
```

### toArgb32(int[] cmykPixels) {#toArgb32-int---}
```
public static int[] toArgb32(int[] cmykPixels)
```


Die Umwandlung von CMYK-Farben zu ARGB-Farben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixels | int[] | Die CMYK-Farben, dargestellt als 32-Bit-Ganzzahlwerte. |

**Returns:**
int[] - Die ARGB-Farben, dargestellt als 32-Bit-Ganzzahlwerte.
### toArgb32(int[] cmykPixels, boolean reuseArray) {#toArgb32-int---boolean-}
```
public static int[] toArgb32(int[] cmykPixels, boolean reuseArray)
```


Führt die Umwandlung von CMYK-Farben zu ARGB-Farben durch und speichert sie im selben Array, wenn `reuseArray` true ist. Andernfalls wird ein neues Array alloziert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixels | int[] | Die CMYK-Farben, dargestellt als 32-Bit-Ganzzahlwerte. |
| reuseArray | boolean | wenn `true` wird das Eingabe-Array `cmykPixels` mit neuen Werten neu befüllt und zurückgegeben; andernfalls wird ein neues Array alloziert und zurückgegeben. |

**Returns:**
int[] - Das neu alloziierte Array oder `cmykPixels`, gefüllt mit ARGB-Farben, dargestellt als 32-Bit-Ganzzahlwerte.
### toArgbIcc(int[] cmykPixels) {#toArgbIcc-int---}
```
public static Color[] toArgbIcc(int[] cmykPixels)
```


Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit Standardprofilen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixels | int[] | Die CMYK-Pixel, dargestellt als 32-Bit-Ganzzahlwerte. |

**Returns:**
com.aspose.imaging.Color[] - Die ARGB-Farben.
### toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixels | int[] | Die CMYK-Farben, dargestellt als 32-Bit-Ganzzahlwerte. |
| cmykIccStream | java.io.InputStream | Der Stream, der das CMYK-ICC-Profil enthält. |
| rgbIccStream | java.io.InputStream | Der Stream, der das RGB-ICC-Profil enthält. |

**Returns:**
com.aspose.imaging.Color[] - Die ARGB-Farben.
### toArgbIcc(int cmykPixel) {#toArgbIcc-int-}
```
public static Color toArgbIcc(int cmykPixel)
```


Die Umwandlung von CMYK-Farbe zu ARGB-Farbe mittels Icc-Konvertierung mit Standardprofilen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixel | int | Die CMYK-Farbe dargestellt als 32‑Bit‑Ganzzahlwert. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The ARGB color.

**Example: The following example shows how to convert CMYK colors to their RGB counterparts using ICC profiles.**

``` java
int[] cmykColors = new int[]
        {
                com.aspose.imaging.CmykColorHelper.fromComponents(255, 0, 0, 0),   // Cyan
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 255, 0, 0),   // Magenta
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 255, 0),   // Yellow
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 0, 255),   // Black
        };

System.out.println("Convert CMYK to RGB using default ICC profiles.");
for (int cmykColor : cmykColors) {
    com.aspose.imaging.Color rgbColor = com.aspose.imaging.CmykColorHelper.toArgbIcc(cmykColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmykColor);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmykColor);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmykColor);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmykColor);

    System.out.printf("CMYK(%s,%s,%s,%s)\t\t=> RGB(%s,%s,%s)\r\n", c, m, y, k, rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff);
}

// Geben Sie Ihren Pfad zu benutzerdefinierten RGB- und CMYK-ICC-Profilen an.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert CMYK to RGB using custom ICC profiles.");
// Lesen Sie alle Bytes aus ICC-Dateien in den Speicher, um die Möglichkeit zu haben, den Eingabe-Profil-Stream zurückzusetzen, bevor toCmykIcc aufgerufen wird.
byte[] rgbProfileBytes;
java.io.RandomAccessFile rgbProfile = new java.io.RandomAccessFile(dir + "eciRGB_v2.icc", "r");
try {
    rgbProfileBytes = new byte[(int) rgbProfile.length()];
    rgbProfile.readFully(rgbProfileBytes);
} finally {
    rgbProfile.close();
}

byte[] cmykProfileBytes;
java.io.RandomAccessFile cmykProfile = new java.io.RandomAccessFile(dir + "ISOcoated_v2_FullGamut4.icc", "r");
try {
    cmykProfileBytes = new byte[(int) cmykProfile.length()];
    cmykProfile.readFully(cmykProfileBytes);
} finally {
    cmykProfile.close();
}

java.io.InputStream rgbProfileStream = new java.io.ByteArrayInputStream(rgbProfileBytes);
java.io.InputStream cmykProfileStream = new java.io.ByteArrayInputStream(cmykProfileBytes);
try {
    for (int cmykColor : cmykColors) {
        com.aspose.imaging.Color rgbColor = com.aspose.imaging.CmykColorHelper.toArgbIcc(cmykColor);
        int c = com.aspose.imaging.CmykColorHelper.getC(cmykColor);
        int m = com.aspose.imaging.CmykColorHelper.getM(cmykColor);
        int y = com.aspose.imaging.CmykColorHelper.getY(cmykColor);
        int k = com.aspose.imaging.CmykColorHelper.getK(cmykColor);

        System.out.printf("CMYK(%s,%s,%s,%s)\t\t=> RGB(%s,%s,%s)\r\n", c, m, y, k, rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff);
    }
} finally {
    cmykProfileStream.close();
    rgbProfileStream.close();
}

//Die Ausgabe sieht folgendermaßen aus:
//Konvertieren Sie CMYK zu RGB unter Verwendung der Standard-ICC-Profile.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//CMYK(0,0,255,0)        => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
//Konvertiere CMYK nach RGB mit benutzerdefinierten ICC-Profilen.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//(0,0,255,0)            => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
```

### toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static Color toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


Die Umwandlung von CMYK-Farbe zu ARGB-Farbe mittels Icc-Konvertierung mit benutzerdefiniertem Profil.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixel | int | Die CMYK-Farbe dargestellt als 32‑Bit‑Ganzzahlwert. |
| cmykIccStream | java.io.InputStream | Der Stream, der das CMYK-ICC-Profil enthält. |
| rgbIccStream | java.io.InputStream | Der Stream, der das RGB-ICC-Profil enthält. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The ARGB color.

**Example: The following example shows how to convert CMYK colors to their RGB counterparts using ICC profiles.**

``` java
int[] cmykColors = new int[]
        {
                com.aspose.imaging.CmykColorHelper.fromComponents(255, 0, 0, 0),   // Cyan
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 255, 0, 0),   // Magenta
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 255, 0),   // Yellow
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 0, 255),   // Black
        };

System.out.println("Convert CMYK to RGB using default ICC profiles.");
for (int cmykColor : cmykColors) {
    com.aspose.imaging.Color rgbColor = com.aspose.imaging.CmykColorHelper.toArgbIcc(cmykColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmykColor);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmykColor);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmykColor);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmykColor);

    System.out.printf("CMYK(%s,%s,%s,%s)\t\t=> RGB(%s,%s,%s)\r\n", c, m, y, k, rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff);
}

// Geben Sie Ihren Pfad zu benutzerdefinierten RGB- und CMYK-ICC-Profilen an.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert CMYK to RGB using custom ICC profiles.");
// Lesen Sie alle Bytes aus ICC-Dateien in den Speicher, um die Möglichkeit zu haben, den Eingabe-Profil-Stream zurückzusetzen, bevor toCmykIcc aufgerufen wird.
byte[] rgbProfileBytes;
java.io.RandomAccessFile rgbProfile = new java.io.RandomAccessFile(dir + "eciRGB_v2.icc", "r");
try {
    rgbProfileBytes = new byte[(int) rgbProfile.length()];
    rgbProfile.readFully(rgbProfileBytes);
} finally {
    rgbProfile.close();
}

byte[] cmykProfileBytes;
java.io.RandomAccessFile cmykProfile = new java.io.RandomAccessFile(dir + "ISOcoated_v2_FullGamut4.icc", "r");
try {
    cmykProfileBytes = new byte[(int) cmykProfile.length()];
    cmykProfile.readFully(cmykProfileBytes);
} finally {
    cmykProfile.close();
}

java.io.InputStream rgbProfileStream = new java.io.ByteArrayInputStream(rgbProfileBytes);
java.io.InputStream cmykProfileStream = new java.io.ByteArrayInputStream(cmykProfileBytes);
try {
    for (int cmykColor : cmykColors) {
        com.aspose.imaging.Color rgbColor = com.aspose.imaging.CmykColorHelper.toArgbIcc(cmykColor);
        int c = com.aspose.imaging.CmykColorHelper.getC(cmykColor);
        int m = com.aspose.imaging.CmykColorHelper.getM(cmykColor);
        int y = com.aspose.imaging.CmykColorHelper.getY(cmykColor);
        int k = com.aspose.imaging.CmykColorHelper.getK(cmykColor);

        System.out.printf("CMYK(%s,%s,%s,%s)\t\t=> RGB(%s,%s,%s)\r\n", c, m, y, k, rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff);
    }
} finally {
    cmykProfileStream.close();
    rgbProfileStream.close();
}

//Die Ausgabe sieht folgendermaßen aus:
//Konvertieren Sie CMYK zu RGB unter Verwendung der Standard-ICC-Profile.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//CMYK(0,0,255,0)        => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
//Konvertiere CMYK nach RGB mit benutzerdefinierten ICC-Profilen.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//(0,0,255,0)            => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
```

### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.imaging.Color---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | Die ARGB-Farben. |
| rgbIccStream | java.io.InputStream | Der Stream, der das RGB-ICC-Profil enthält. |
| cmykIccStream | java.io.InputStream | Der Stream, der das CMYK-ICC-Profil enthält. |

**Returns:**
int[] - Die CMYK‑Farben, dargestellt als 32‑Bit‑Ganzzahlwerte.
### toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pixel | int[] | Die ARGB-Farben. |
| rgbIccStream | java.io.InputStream | Der Stream, der das RGB-ICC-Profil enthält. |
| cmykIccStream | java.io.InputStream | Der Stream, der das CMYK-ICC-Profil enthält. |

**Returns:**
int[] - Die CMYK‑Farben, dargestellt als 32‑Bit‑Ganzzahlwerte.
### toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


Konvertiert RGB zu CMYK mit benutzerdefinierten ICC-Profilen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pixel | int[] | Die RGB‑Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |
| startIndex | int | Der Startindex der RGB‑Farbe. |
| length | int | Die Anzahl der zu konvertierenden RGB‑Pixel. |
| rgbIccStream | java.io.InputStream | Der RGB-Profil-Stream. |
| cmykIccStream | java.io.InputStream | Der CMYK-Profil-Stream. |

**Returns:**
byte[] - Die CMYK-Farben, dargestellt als Byte-Array.
### toCmykIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)
```


Konvertiert RGB zu CMYK mit benutzerdefinierten ICC-Profilen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pixel | int[] | Die RGB‑Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |
| startIndex | int | Der Startindex der RGB‑Farbe. |
| length | int | Die Anzahl der zu konvertierenden RGB‑Pixel. |
| cmykBytes | byte[] | Die Cmyk-Bytes. |
| cmykOffset | int | Der `cmykBytes`-Offset. |
| rgbIccStream | java.io.InputStream | Der RGB-Profil-Stream. |
| cmykIccStream | java.io.InputStream | Der CMYK-Profil-Stream. |

**Returns:**
byte[] - Die CMYK-Farben, dargestellt als Byte-Array.
### toCmykaIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykaIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykaIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)
```


Konvertiert RGB zu CMYKA (mit Alpha) mit benutzerdefinierten ICC-Profilen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pixel | int[] | Die RGB‑Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |
| startIndex | int | Der Startindex der RGB‑Farbe. |
| length | int | Die Anzahl der zu konvertierenden RGB‑Pixel. |
| cmykBytes | byte[] | Die Cmyk-Bytes. |
| cmykOffset | int | Der `cmykBytes`-Offset. |
| rgbIccStream | java.io.InputStream | Der RGB-Profil-Stream. |
| cmykIccStream | java.io.InputStream | Der CMYK-Profil-Stream. |

**Returns:**
byte[] - Die CMYK-Farben, dargestellt als Byte-Array.
### toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toPsdCmykIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static int[] toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


Die Konvertierung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen. Verwendet das PSD-CMYK-Format KCMY-Byte-Reihenfolge mit invertierten Kanalwerten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pixel | int[] | Die ARGB-Farben. |
| rgbIccStream | java.io.InputStream | Der Stream, der das RGB-ICC-Profil enthält. |
| cmykIccStream | java.io.InputStream | Der Stream, der das CMYK-ICC-Profil enthält. |

**Returns:**
int[] - Die CMYK-Farben dargestellt als 32‑Bit‑Ganzzahlen im KCMY‑Byte‑Reihenfolge mit invertierten Kanalwerten.
### toCmykaIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykaIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykaIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


Konvertiert RGB zu CMYKA (mit Alpha) mit benutzerdefinierten ICC-Profilen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pixel | int[] | Die RGB‑Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |
| startIndex | int | Der Startindex der RGB‑Farbe. |
| length | int | Die Anzahl der zu konvertierenden RGB‑Pixel. |
| rgbIccStream | java.io.InputStream | Der RGB-Profil-Stream. |
| cmykIccStream | java.io.InputStream | Der CMYK-Profil-Stream. |

**Returns:**
byte[] - Die CMYK-Farben, dargestellt als Byte-Array.
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.imaging.Color---}
```
public static int[] toCmykIcc(Color[] pixels)
```


Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit Standardprofilen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | Die ARGB-Farben. |

**Returns:**
int[] - Die CMYK‑Farben, dargestellt als 32‑Bit‑Ganzzahlwerte.
### toCmykIcc(int[] pixels) {#toCmykIcc-int---}
```
public static int[] toCmykIcc(int[] pixels)
```


Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit Standardprofilen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pixel | int[] | Die ARGB-Farben. |

**Returns:**
int[] - Die CMYK‑Farben, dargestellt als 32‑Bit‑Ganzzahlwerte.
### toPsdCmykIcc(int[] pixels) {#toPsdCmykIcc-int---}
```
public static int[] toPsdCmykIcc(int[] pixels)
```


Die Konvertierung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit Standardprofilen. Verwendet das PSD-CMYK-Format KCMY-Byte-Reihenfolge mit invertierten Kanalwerten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pixel | int[] | Die ARGB-Farben. |

**Returns:**
int[] - Die CMYK-Farben dargestellt als 32‑Bit‑Ganzzahlen im KCMY‑Byte‑Reihenfolge mit invertierten Kanalwerten.
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.imaging.Color-}
```
public static int toCmykIcc(Color pixel)
```


Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit Standardprofilen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | Die ARGB-Farbe. |

**Returns:**
int - Die CMYK‑Farbe, dargestellt als 32‑Bit‑Ganzzahlwert.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts using ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK using default ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmykIcc(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

// Geben Sie den Pfad zu den RGB- und CMYK-ICC-Profilen an.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert RGB to CMYK using custom ICC profiles.");

// Lesen Sie alle Bytes aus ICC-Dateien in den Speicher, um die Möglichkeit zu haben, den Eingabe-Profil-Stream zurückzusetzen, bevor toCmykIcc aufgerufen wird.
byte[] rgbProfileBytes;
java.io.RandomAccessFile rgbProfile = new java.io.RandomAccessFile(dir + "eciRGB_v2.icc", "r");
try {
    rgbProfileBytes = new byte[(int) rgbProfile.length()];
    rgbProfile.readFully(rgbProfileBytes);
} finally {
    rgbProfile.close();
}

byte[] cmykProfileBytes;
java.io.RandomAccessFile cmykProfile = new java.io.RandomAccessFile(dir + "ISOcoated_v2_FullGamut4.icc", "r");
try {
    cmykProfileBytes = new byte[(int) cmykProfile.length()];
    cmykProfile.readFully(cmykProfileBytes);
} finally {
    cmykProfile.close();
}

java.io.InputStream rgbProfileStream = new java.io.ByteArrayInputStream(rgbProfileBytes);
java.io.InputStream cmykProfileStream = new java.io.ByteArrayInputStream(cmykProfileBytes);
try {
    for (com.aspose.imaging.Color rgbColor : rgbColors) {

        int cmyk = com.aspose.imaging.CmykColorHelper.toCmykIcc(rgbColor, rgbProfileStream, cmykProfileStream);
        int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
        int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
        int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
        int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

        System.out.printf("RGB(%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
    }
} finally {
    cmykProfileStream.close();
    rgbProfileStream.close();
}

//Die Ausgabe sieht folgendermaßen aus:
//Konvertiere RGB nach CMYK mit Standard-ICC-Profilen.
//RGB(255,0,0)        => CMYK(0,254,249,15)
//RGB(0,128,0)        => CMYK(247,21,254,85)
//RGB(0,0,255)        => CMYK(254,195,0,134)
//Konvertiere RGB nach CMYK mit benutzerdefinierten ICC-Profilen.
//RGB(255,0,0)        => CMYK(0,207,219,0)
//RGB(0,128,0)        => CMYK(238,16,254,80)
//RGB(0,0,255)        => CMYK(242,182,0,0)
```

### toCmykIcc(int argb) {#toCmykIcc-int-}
```
public static int toCmykIcc(int argb)
```


Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit Standardprofilen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| argb | int | Die ARGB-Farbe. |

**Returns:**
int - Die CMYK‑Farbe, dargestellt als 32‑Bit‑Ganzzahlwert.
### toPsdCmykIcc(int argb) {#toPsdCmykIcc-int-}
```
public static int toPsdCmykIcc(int argb)
```


Die Konvertierung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit Standardprofilen. Verwendet das PSD-CMYK-Format KCMY-Byte-Reihenfolge mit invertierten Kanalwerten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| argb | int | Die ARGB-Farbe. |

**Returns:**
int - Die CMYK-Farbe wird als 32‑Bit‑Ganzzahlwert in KCMY-Byte‑Reihenfolge mit invertierten Kanalwerten dargestellt.
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.imaging.Color-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit benutzerdefinierten Profilen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | Die ARGB-Farbe. |
| rgbIccStream | java.io.InputStream | Der Stream, der das RGB-ICC-Profil enthält. |
| cmykIccStream | java.io.InputStream | Der Stream, der das CMYK-ICC-Profil enthält. |

**Returns:**
int - Die CMYK‑Farbe, dargestellt als 32‑Bit‑Ganzzahlwert.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts using ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK using default ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmykIcc(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

// Geben Sie den Pfad zu den RGB- und CMYK-ICC-Profilen an.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert RGB to CMYK using custom ICC profiles.");

// Lesen Sie alle Bytes aus ICC-Dateien in den Speicher, um die Möglichkeit zu haben, den Eingabe-Profil-Stream zurückzusetzen, bevor toCmykIcc aufgerufen wird.
byte[] rgbProfileBytes;
java.io.RandomAccessFile rgbProfile = new java.io.RandomAccessFile(dir + "eciRGB_v2.icc", "r");
try {
    rgbProfileBytes = new byte[(int) rgbProfile.length()];
    rgbProfile.readFully(rgbProfileBytes);
} finally {
    rgbProfile.close();
}

byte[] cmykProfileBytes;
java.io.RandomAccessFile cmykProfile = new java.io.RandomAccessFile(dir + "ISOcoated_v2_FullGamut4.icc", "r");
try {
    cmykProfileBytes = new byte[(int) cmykProfile.length()];
    cmykProfile.readFully(cmykProfileBytes);
} finally {
    cmykProfile.close();
}

java.io.InputStream rgbProfileStream = new java.io.ByteArrayInputStream(rgbProfileBytes);
java.io.InputStream cmykProfileStream = new java.io.ByteArrayInputStream(cmykProfileBytes);
try {
    for (com.aspose.imaging.Color rgbColor : rgbColors) {

        int cmyk = com.aspose.imaging.CmykColorHelper.toCmykIcc(rgbColor, rgbProfileStream, cmykProfileStream);
        int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
        int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
        int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
        int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

        System.out.printf("RGB(%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
    }
} finally {
    cmykProfileStream.close();
    rgbProfileStream.close();
}

//Die Ausgabe sieht folgendermaßen aus:
//Konvertiere RGB nach CMYK mit Standard-ICC-Profilen.
//RGB(255,0,0)        => CMYK(0,254,249,15)
//RGB(0,128,0)        => CMYK(247,21,254,85)
//RGB(0,0,255)        => CMYK(254,195,0,134)
//Konvertiere RGB nach CMYK mit benutzerdefinierten ICC-Profilen.
//RGB(255,0,0)        => CMYK(0,207,219,0)
//RGB(0,128,0)        => CMYK(238,16,254,80)
//RGB(0,0,255)        => CMYK(242,182,0,0)
```

### toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream)
```


Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit benutzerdefinierten Profilen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| argb | int | Die ARGB-Farbe. |
| rgbIccStream | java.io.InputStream | Der Stream, der das RGB-ICC-Profil enthält. |
| cmykIccStream | java.io.InputStream | Der Stream, der das CMYK-ICC-Profil enthält. |

**Returns:**
int - Die CMYK‑Farbe, dargestellt als 32‑Bit‑Ganzzahlwert.
### toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toPsdCmykIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static int toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit benutzerdefinierten Profilen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pixel | int | Die ARGB-Farbe. |
| rgbIccStream | java.io.InputStream | Der Stream, der das RGB-ICC-Profil enthält. |
| cmykIccStream | java.io.InputStream | Der Stream, der das CMYK-ICC-Profil enthält. |

**Returns:**
int - Die CMYK-Farben werden als 32‑Bit‑Ganzzahlwerte in KCMY-Byte‑Reihenfolge mit invertierten Kanalwerten dargestellt.
