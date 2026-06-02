---
title: "CmykColorHelper"
second_title: "Aspose.Imaging för Java API-referens"
description: "Hjälpmetoder för att arbeta med CMYK-färg som presenteras som ett signerat 32-bitars heltalsvärde."
type: docs
weight: 19
url: /sv/java/com.aspose.imaging/cmykcolorhelper/
---
**Inheritance:**
java.lang.Object
```
public final class CmykColorHelper
```

Hjälpmetoder för att arbeta med CMYK-färg som presenteras som ett signerat 32-bitars heltalsvärde. Tillhandahåller ett liknande API som strukturen [CmykColor](../../com.aspose.imaging/cmykcolor). Den är mer lättviktig eftersom CMYK-färg presenteras bara som Int32 snarare än som en struktur med interna fält. Använd gärna de statiska metoderna i denna klass när det är möjligt istället för den föråldrade strukturen [CmykColor](../../com.aspose.imaging/cmykcolor).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getC(int cmyk)](#getC-int-) | Hämtar cyan-komponentens värde. |
| [getM(int cmyk)](#getM-int-) | Hämtar magenta-komponentens värde. |
| [getY(int cmyk)](#getY-int-) | Hämtar gul-komponentens värde. |
| [getK(int cmyk)](#getK-int-) | Hämtar svart-komponentens värde. |
| [fromComponents(int cyan, int magenta, int yellow, int black)](#fromComponents-int-int-int-int-) | Skapar CMYK från 32-bitars cyan-, magenta-, gul- och svartvärden. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | Konverteringen från ARGB-färger till CMYK-färger. |
| [toCmykBytes(int[] argbPixels, int startIndex, int length)](#toCmykBytes-int---int-int-) | Konverterar ARGB till CMYK. |
| [toCmykaBytes(int[] argbPixels, int startIndex, int length)](#toCmykaBytes-int---int-int-) | Konverterar ARGB till CMYKA (med transparens). |
| [toCmyk(int argbPixel)](#toCmyk-int-) | Konverteringen från ARGB-färg till CMYK-färg. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.imaging.Color-) | Konverteringen från ARGB-färg till CMYK-färg. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.imaging.Color---) | Konverteringen från ARGB-färger till CMYK-färger. |
| [toArgb(int[] cmykPixels)](#toArgb-int---) | Konverteringen från CMYK-färger till ARGB-färger. |
| [toArgb(int cmykPixel)](#toArgb-int-) | Konverteringen från CMYK-färg till ARGB-färg. |
| [toArgb32(int[] cmykPixels)](#toArgb32-int---) | Konverteringen från CMYK-färger till ARGB-färger. |
| [toArgb32(int[] cmykPixels, boolean reuseArray)](#toArgb32-int---boolean-) | Utför konvertering från CMYK-färger till ARGB-färger och lagrar dem i samma array om `reuseArray` är sant. |
| [toArgbIcc(int[] cmykPixels)](#toArgbIcc-int---) | Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och standardprofiler. |
| [toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int---java.io.InputStream-java.io.InputStream-) | Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och anpassade profiler. |
| [toArgbIcc(int cmykPixel)](#toArgbIcc-int-) | Konverteringen från CMYK-färg till ARGB-färg med Icc-konvertering och standardprofiler. |
| [toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int-java.io.InputStream-java.io.InputStream-) | Konverteringen från CMYK-färg till ARGB-färg med Icc-konvertering och anpassad profil. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.imaging.Color---java.io.InputStream-java.io.InputStream-) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler. |
| [toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-int---java.io.InputStream-java.io.InputStream-) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | Konverterar RGB till CMYK med anpassade ICC-profiler. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-) | Konverterar RGB till CMYK med anpassade ICC-profiler. |
| [toCmykaIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykaIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-) | Konverterar RGB till CMYKA (med alfa) med anpassade ICC-profiler. |
| [toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toPsdCmykIcc-int---java.io.InputStream-java.io.InputStream-) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler. |
| [toCmykaIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykaIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | Konverterar RGB till CMYKA (med alfa) med anpassade ICC-profiler. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.imaging.Color---) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och standardprofiler. |
| [toCmykIcc(int[] pixels)](#toCmykIcc-int---) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och standardprofiler. |
| [toPsdCmykIcc(int[] pixels)](#toPsdCmykIcc-int---) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och standardprofiler. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.imaging.Color-) | Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och standardprofiler. |
| [toCmykIcc(int argb)](#toCmykIcc-int-) | Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och standardprofiler. |
| [toPsdCmykIcc(int argb)](#toPsdCmykIcc-int-) | Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och standardprofiler. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.imaging.Color-java.io.InputStream-java.io.InputStream-) | Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och anpassade profiler. |
| [toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-int-java.io.InputStream-java.io.InputStream-) | Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och anpassade profiler. |
| [toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toPsdCmykIcc-int-java.io.InputStream-java.io.InputStream-) | Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och anpassade profiler. |
### getC(int cmyk) {#getC-int-}
```
public static int getC(int cmyk)
```


Hämtar cyan-komponentens värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmyk | int | CMYK-färgen presenteras som ett 32-bitars heltalsvärde. |

**Returns:**
int - Värdet för cyan-komponenten.

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

//Utdata ser ut så här:
//Konvertera RGB till CMYK utan att använda ICC-profiler.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getM(int cmyk) {#getM-int-}
```
public static int getM(int cmyk)
```


Hämtar magenta-komponentens värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmyk | int | CMYK-färgen presenteras som ett 32-bitars heltalsvärde. |

**Returns:**
int - Det magenta komponentvärdet.

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

//Utdata ser ut så här:
//Konvertera RGB till CMYK utan att använda ICC-profiler.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getY(int cmyk) {#getY-int-}
```
public static int getY(int cmyk)
```


Hämtar gul-komponentens värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmyk | int | CMYK-färgen presenteras som ett 32-bitars heltalsvärde. |

**Returns:**
int - Det gula komponentvärdet.

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

//Utdata ser ut så här:
//Konvertera RGB till CMYK utan att använda ICC-profiler.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getK(int cmyk) {#getK-int-}
```
public static int getK(int cmyk)
```


Hämtar svart-komponentens värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmyk | int | CMYK-färgen presenteras som ett 32-bitars heltalsvärde. |

**Returns:**
int - Det svarta komponentvärdet.

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

//Utdata ser ut så här:
//Konvertera RGB till CMYK utan att använda ICC-profiler.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### fromComponents(int cyan, int magenta, int yellow, int black) {#fromComponents-int-int-int-int-}
```
public static int fromComponents(int cyan, int magenta, int yellow, int black)
```


Skapar CMYK från 32-bitars cyan-, magenta-, gul- och svartvärden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cyan | int | Den cyan‑komponenten. Giltiga värden är 0 till 255. |
| magenta | int | Den magenta komponenten. Giltiga värden är 0 till 255. |
| gul | int | Den gula komponenten. Giltiga värden är 0 till 255. |
| svart | int | Den svarta komponenten. Giltiga värden är 0 till 255. |

**Returns:**
int - CMYK-färgen presenterad som ett 32‑bitars heltalsvärde.

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

//Utdata ser ut så här:
//Konvertera CMYK till RGB utan att använda ICC-profiler.
//CMYK(255,0,0,0)        => RGB(0,255,255)
//CMYK(0,255,0,0)        => RGB(255,0,255)
//CMYK(0,0,255,0)        => RGB(255,255,0)
//CMYK(0,0,0,255)        => RGB(0,0,0)
```

### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static int[] toCmyk(int[] argbPixels)
```


Konverteringen från ARGB-färger till CMYK-färger.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argbPixels | int[] | ARGB-färgerna presenterade som 32‑bitars heltalsvärden. |

**Returns:**
int[] - CMYK-färgerna presenterade som 32‑bitars heltalsvärden.
### toCmykBytes(int[] argbPixels, int startIndex, int length) {#toCmykBytes-int---int-int-}
```
public static byte[] toCmykBytes(int[] argbPixels, int startIndex, int length)
```


Konverterar ARGB till CMYK.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argbPixels | int[] | RGB-färgerna presenterade som 32‑bitars heltalsvärden. |
| startIndex | int | Startindex för RGB-färg. |
| längd | int | Antalet RGB-pixlar att konvertera. |

**Returns:**
byte[] - CMYK-färgerna presenterade som en byte-array.
### toCmykaBytes(int[] argbPixels, int startIndex, int length) {#toCmykaBytes-int---int-int-}
```
public static byte[] toCmykaBytes(int[] argbPixels, int startIndex, int length)
```


Konverterar ARGB till CMYKA (med transparens).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argbPixels | int[] | RGB-färgerna presenterade som 32‑bitars heltalsvärden. |
| startIndex | int | Startindex för RGB-färg. |
| längd | int | Antalet RGB-pixlar att konvertera. |

**Returns:**
byte[] - CMYK-färgerna presenterade som en byte-array.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static int toCmyk(int argbPixel)
```


Konverteringen från ARGB-färg till CMYK-färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argbPixel | int | ARGB-färgen presenterad som ett 32-bitars heltalsvärde. |

**Returns:**
int - CMYK-färgen presenterad som ett 32‑bitars heltalsvärde.
### toCmyk(Color pixel) {#toCmyk-com.aspose.imaging.Color-}
```
public static int toCmyk(Color pixel)
```


Konverteringen från ARGB-färg till CMYK-färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | ARGB-färgen. |

**Returns:**
int - CMYK-färgen presenterad som ett 32‑bitars heltalsvärde.

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

//Utdata ser ut så här:
//Konvertera RGB till CMYK utan att använda ICC-profiler.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### toCmyk(Color[] pixels) {#toCmyk-com.aspose.imaging.Color---}
```
public static int[] toCmyk(Color[] pixels)
```


Konverteringen från ARGB-färger till CMYK-färger.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | ARGB-färgerna. |

**Returns:**
int[] - CMYK-färgerna presenterade som 32‑bitars heltalsvärden.
### toArgb(int[] cmykPixels) {#toArgb-int---}
```
public static Color[] toArgb(int[] cmykPixels)
```


Konverteringen från CMYK-färger till ARGB-färger.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixels | int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |

**Returns:**
com.aspose.imaging.Color[] - ARGB-färgerna.
### toArgb(int cmykPixel) {#toArgb-int-}
```
public static Color toArgb(int cmykPixel)
```


Konverteringen från CMYK-färg till ARGB-färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixel | int | CMYK-färgen presenteras som ett 32-bitars heltalsvärde. |

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

//Utdata ser ut så här:
//Konvertera CMYK till RGB utan att använda ICC-profiler.
//CMYK(255,0,0,0)        => RGB(0,255,255)
//CMYK(0,255,0,0)        => RGB(255,0,255)
//CMYK(0,0,255,0)        => RGB(255,255,0)
//CMYK(0,0,0,255)        => RGB(0,0,0)
```

### toArgb32(int[] cmykPixels) {#toArgb32-int---}
```
public static int[] toArgb32(int[] cmykPixels)
```


Konverteringen från CMYK-färger till ARGB-färger.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixels | int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |

**Returns:**
int[] - ARGB-färgerna presenterade som 32-bitars heltalsvärden.
### toArgb32(int[] cmykPixels, boolean reuseArray) {#toArgb32-int---boolean-}
```
public static int[] toArgb32(int[] cmykPixels, boolean reuseArray)
```


Utför konvertering från CMYK-färger till ARGB-färger och lagrar dem i samma array om `reuseArray` är true. Annars kommer en ny array att allokeras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixels | int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |
| reuseArray | boolean | om `true` kommer den inmatade `cmykPixels`-arrayen att fyllas på med nya värden och returneras; annars kommer en ny array att allokeras och returneras. |

**Returns:**
int[] - Den nyallokerade arrayen eller `cmykPixels` fylld med ARGB-färger presenterade som 32-bitars heltalsvärden.
### toArgbIcc(int[] cmykPixels) {#toArgbIcc-int---}
```
public static Color[] toArgbIcc(int[] cmykPixels)
```


Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och standardprofiler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixels | int[] | CMYK-pixlarna presenterade som 32-bitars heltalsvärden. |

**Returns:**
com.aspose.imaging.Color[] - ARGB-färgerna.
### toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och anpassade profiler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixels | int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |
| cmykIccStream | java.io.InputStream | Strömmen som innehåller CMYK Icc-profilen. |
| rgbIccStream | java.io.InputStream | Strömmen som innehåller RGB Icc-profilen. |

**Returns:**
com.aspose.imaging.Color[] - ARGB-färgerna.
### toArgbIcc(int cmykPixel) {#toArgbIcc-int-}
```
public static Color toArgbIcc(int cmykPixel)
```


Konverteringen från CMYK-färg till ARGB-färg med Icc-konvertering och standardprofiler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixel | int | CMYK-färgen presenteras som ett 32-bitars heltalsvärde. |

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

// Ange din sökväg till anpassade RGB- och CMYK-ICC-profiler.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert CMYK to RGB using custom ICC profiles.");
// Läs alla byte från ICC-filer till minnet för att kunna återställa inmatningsprofilströmmen innan du anropar toCmykIcc
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

//Utdata ser ut så här:
//Konvertera CMYK till RGB med standard-ICC-profiler.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//CMYK(0,0,255,0)        => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
//Konvertera CMYK till RGB med anpassade ICC-profiler.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//(0,0,255,0)            => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
```

### toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static Color toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


Konverteringen från CMYK-färg till ARGB-färg med Icc-konvertering och anpassad profil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixel | int | CMYK-färgen presenteras som ett 32-bitars heltalsvärde. |
| cmykIccStream | java.io.InputStream | Strömmen som innehåller CMYK Icc-profilen. |
| rgbIccStream | java.io.InputStream | Strömmen som innehåller RGB Icc-profilen. |

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

// Ange din sökväg till anpassade RGB- och CMYK-ICC-profiler.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert CMYK to RGB using custom ICC profiles.");
// Läs alla byte från ICC-filer till minnet för att kunna återställa inmatningsprofilströmmen innan du anropar toCmykIcc
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

//Utdata ser ut så här:
//Konvertera CMYK till RGB med standard-ICC-profiler.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//CMYK(0,0,255,0)        => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
//Konvertera CMYK till RGB med anpassade ICC-profiler.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//(0,0,255,0)            => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
```

### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.imaging.Color---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | ARGB-färgerna. |
| rgbIccStream | java.io.InputStream | Strömmen som innehåller RGB Icc-profilen. |
| cmykIccStream | java.io.InputStream | Strömmen som innehåller CMYK Icc-profilen. |

**Returns:**
int[] - CMYK-färgerna presenterade som 32‑bitars heltalsvärden.
### toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixlar | int[] | ARGB-färgerna. |
| rgbIccStream | java.io.InputStream | Strömmen som innehåller RGB Icc-profilen. |
| cmykIccStream | java.io.InputStream | Strömmen som innehåller CMYK Icc-profilen. |

**Returns:**
int[] - CMYK-färgerna presenterade som 32‑bitars heltalsvärden.
### toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


Konverterar RGB till CMYK med anpassade ICC-profiler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixlar | int[] | RGB-färgerna presenterade som 32‑bitars heltalsvärden. |
| startIndex | int | Startindex för RGB-färg. |
| längd | int | Antalet RGB-pixlar att konvertera. |
| rgbIccStream | java.io.InputStream | RGB-profilströmmen. |
| cmykIccStream | java.io.InputStream | CMYK-profilströmmen. |

**Returns:**
byte[] - CMYK-färgerna presenterade som en byte-array.
### toCmykIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)
```


Konverterar RGB till CMYK med anpassade ICC-profiler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixlar | int[] | RGB-färgerna presenterade som 32‑bitars heltalsvärden. |
| startIndex | int | Startindex för RGB-färg. |
| längd | int | Antalet RGB-pixlar att konvertera. |
| cmykBytes | byte[] | Cmyk-byterna. |
| cmykOffset | int | `cmykBytes`-offseten. |
| rgbIccStream | java.io.InputStream | RGB-profilströmmen. |
| cmykIccStream | java.io.InputStream | CMYK-profilströmmen. |

**Returns:**
byte[] - CMYK-färgerna presenterade som en byte-array.
### toCmykaIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykaIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykaIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)
```


Konverterar RGB till CMYKA (med alfa) med anpassade ICC-profiler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixlar | int[] | RGB-färgerna presenterade som 32‑bitars heltalsvärden. |
| startIndex | int | Startindex för RGB-färg. |
| längd | int | Antalet RGB-pixlar att konvertera. |
| cmykBytes | byte[] | Cmyk-byterna. |
| cmykOffset | int | `cmykBytes`-offseten. |
| rgbIccStream | java.io.InputStream | RGB-profilströmmen. |
| cmykIccStream | java.io.InputStream | CMYK-profilströmmen. |

**Returns:**
byte[] - CMYK-färgerna presenterade som en byte-array.
### toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toPsdCmykIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static int[] toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler. Använder PSD CMYK-formatet KCMY-byteordning med inverterade kanalvärden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixlar | int[] | ARGB-färgerna. |
| rgbIccStream | java.io.InputStream | Strömmen som innehåller RGB Icc-profilen. |
| cmykIccStream | java.io.InputStream | Strömmen som innehåller CMYK Icc-profilen. |

**Returns:**
int[] - CMYK-färgerna presenterade som 32-bitars heltalsvärden i KCMY-byteordning med inverterade kanalvärden.
### toCmykaIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykaIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykaIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


Konverterar RGB till CMYKA (med alfa) med anpassade ICC-profiler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixlar | int[] | RGB-färgerna presenterade som 32‑bitars heltalsvärden. |
| startIndex | int | Startindex för RGB-färg. |
| längd | int | Antalet RGB-pixlar att konvertera. |
| rgbIccStream | java.io.InputStream | RGB-profilströmmen. |
| cmykIccStream | java.io.InputStream | CMYK-profilströmmen. |

**Returns:**
byte[] - CMYK-färgerna presenterade som en byte-array.
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.imaging.Color---}
```
public static int[] toCmykIcc(Color[] pixels)
```


Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och standardprofiler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | ARGB-färgerna. |

**Returns:**
int[] - CMYK-färgerna presenterade som 32‑bitars heltalsvärden.
### toCmykIcc(int[] pixels) {#toCmykIcc-int---}
```
public static int[] toCmykIcc(int[] pixels)
```


Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och standardprofiler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixlar | int[] | ARGB-färgerna. |

**Returns:**
int[] - CMYK-färgerna presenterade som 32‑bitars heltalsvärden.
### toPsdCmykIcc(int[] pixels) {#toPsdCmykIcc-int---}
```
public static int[] toPsdCmykIcc(int[] pixels)
```


Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och standardprofiler. Använder PSD CMYK-formatet KCMY-byteordning med inverterade kanalvärden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixlar | int[] | ARGB-färgerna. |

**Returns:**
int[] - CMYK-färgerna presenterade som 32-bitars heltalsvärden i KCMY-byteordning med inverterade kanalvärden.
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.imaging.Color-}
```
public static int toCmykIcc(Color pixel)
```


Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och standardprofiler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | ARGB-färgen. |

**Returns:**
int - CMYK-färgen presenterad som ett 32‑bitars heltalsvärde.

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

// Ange sökvägen till RGB- och CMYK-ICC-profilerna.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert RGB to CMYK using custom ICC profiles.");

// Läs alla byte från ICC-filer till minnet för att kunna återställa inmatningsprofilströmmen innan du anropar toCmykIcc
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

//Utdata ser ut så här:
//Konvertera RGB till CMYK med standard-ICC-profiler.
//RGB(255,0,0)        => CMYK(0,254,249,15)
//RGB(0,128,0)        => CMYK(247,21,254,85)
//RGB(0,0,255)        => CMYK(254,195,0,134)
//Konvertera RGB till CMYK med anpassade ICC-profiler.
//RGB(255,0,0)        => CMYK(0,207,219,0)
//RGB(0,128,0)        => CMYK(238,16,254,80)
//RGB(0,0,255)        => CMYK(242,182,0,0)
```

### toCmykIcc(int argb) {#toCmykIcc-int-}
```
public static int toCmykIcc(int argb)
```


Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och standardprofiler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argb | int | ARGB-färgen. |

**Returns:**
int - CMYK-färgen presenterad som ett 32‑bitars heltalsvärde.
### toPsdCmykIcc(int argb) {#toPsdCmykIcc-int-}
```
public static int toPsdCmykIcc(int argb)
```


Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och standardprofiler. Använder PSD CMYK-formatet KCMY-byteordning med inverterade kanalvärden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argb | int | ARGB-färgen. |

**Returns:**
int - CMYK‑färgen som presenteras som ett 32‑bitars heltalsvärde i KCMY‑byteordning med inverterade kanalvärden.
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.imaging.Color-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och anpassade profiler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | ARGB-färgen. |
| rgbIccStream | java.io.InputStream | Strömmen som innehåller RGB Icc-profilen. |
| cmykIccStream | java.io.InputStream | Strömmen som innehåller CMYK Icc-profilen. |

**Returns:**
int - CMYK-färgen presenterad som ett 32‑bitars heltalsvärde.

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

// Ange sökvägen till RGB- och CMYK-ICC-profilerna.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert RGB to CMYK using custom ICC profiles.");

// Läs alla byte från ICC-filer till minnet för att kunna återställa inmatningsprofilströmmen innan du anropar toCmykIcc
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

//Utdata ser ut så här:
//Konvertera RGB till CMYK med standard-ICC-profiler.
//RGB(255,0,0)        => CMYK(0,254,249,15)
//RGB(0,128,0)        => CMYK(247,21,254,85)
//RGB(0,0,255)        => CMYK(254,195,0,134)
//Konvertera RGB till CMYK med anpassade ICC-profiler.
//RGB(255,0,0)        => CMYK(0,207,219,0)
//RGB(0,128,0)        => CMYK(238,16,254,80)
//RGB(0,0,255)        => CMYK(242,182,0,0)
```

### toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream)
```


Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och anpassade profiler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argb | int | ARGB-färgen. |
| rgbIccStream | java.io.InputStream | Strömmen som innehåller RGB Icc-profilen. |
| cmykIccStream | java.io.InputStream | Strömmen som innehåller CMYK Icc-profilen. |

**Returns:**
int - CMYK-färgen presenterad som ett 32‑bitars heltalsvärde.
### toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toPsdCmykIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static int toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och anpassade profiler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixel | int | ARGB-färgen. |
| rgbIccStream | java.io.InputStream | Strömmen som innehåller RGB Icc-profilen. |
| cmykIccStream | java.io.InputStream | Strömmen som innehåller CMYK Icc-profilen. |

**Returns:**
int - CMYK‑färgerna som presenteras som 32‑bitars heltalsvärden i KCMY‑byteordning med inverterade kanalvärden.
