---
title: "CmykColorHelper"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Metodi di supporto per lavorare con il colore CMYK presentato come valore intero a 32 bit con segno."
type: docs
weight: 19
url: /it/java/com.aspose.imaging/cmykcolorhelper/
---
**Inheritance:**
java.lang.Object
```
public final class CmykColorHelper
```

Metodi di supporto per lavorare con il colore CMYK presentato come valore intero a 32 bit con segno. Fornisce un'API simile a quella della struttura [CmykColor](../../com.aspose.imaging/cmykcolor). È più leggero perché il colore CMYK è rappresentato semplicemente come Int32 anziché come una struttura con campi interni. Si consiglia di utilizzare i metodi statici di questa classe quando possibile, invece della struttura [CmykColor](../../com.aspose.imaging/cmykcolor) deprecata.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getC(int cmyk)](#getC-int-) | Restituisce il valore del componente ciano. |
| [getM(int cmyk)](#getM-int-) | Restituisce il valore del componente magenta. |
| [getY(int cmyk)](#getY-int-) | Restituisce il valore del componente giallo. |
| [getK(int cmyk)](#getK-int-) | Restituisce il valore del componente nero. |
| [fromComponents(int cyan, int magenta, int yellow, int black)](#fromComponents-int-int-int-int-) | Crea CMYK a partire da valori a 32 bit di ciano, magenta, giallo e nero. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | La conversione da colori ARGB a colori CMYK. |
| [toCmykBytes(int[] argbPixels, int startIndex, int length)](#toCmykBytes-int---int-int-) | Converte ARGB in CMYK. |
| [toCmykaBytes(int[] argbPixels, int startIndex, int length)](#toCmykaBytes-int---int-int-) | Converte ARGB in CMYKA (con trasparenza). |
| [toCmyk(int argbPixel)](#toCmyk-int-) | La conversione da colore ARGB a colore CMYK. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.imaging.Color-) | La conversione da colore ARGB a colore CMYK. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.imaging.Color---) | La conversione da colori ARGB a colori CMYK. |
| [toArgb(int[] cmykPixels)](#toArgb-int---) | La conversione da colori CMYK a colori ARGB. |
| [toArgb(int cmykPixel)](#toArgb-int-) | La conversione da colore CMYK a colore ARGB. |
| [toArgb32(int[] cmykPixels)](#toArgb32-int---) | La conversione da colori CMYK a colori ARGB. |
| [toArgb32(int[] cmykPixels, boolean reuseArray)](#toArgb32-int---boolean-) | Esegue la conversione da colori CMYK a colori ARGB e li memorizza nello stesso array se `reuseArray` è true. |
| [toArgbIcc(int[] cmykPixels)](#toArgbIcc-int---) | La conversione da colori CMYK a colori ARGB usando la conversione Icc con profili predefiniti. |
| [toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int---java.io.InputStream-java.io.InputStream-) | La conversione da colori CMYK a colori ARGB usando la conversione Icc con profili personalizzati. |
| [toArgbIcc(int cmykPixel)](#toArgbIcc-int-) | La conversione da colore CMYK a colore ARGB usando la conversione Icc con profili predefiniti. |
| [toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int-java.io.InputStream-java.io.InputStream-) | La conversione da colore CMYK a colore ARGB usando la conversione Icc con profilo personalizzato. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.imaging.Color---java.io.InputStream-java.io.InputStream-) | La conversione da colori ARGB a colori CMYK usando la conversione Icc con profili personalizzati. |
| [toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-int---java.io.InputStream-java.io.InputStream-) | La conversione da colori ARGB a colori CMYK usando la conversione Icc con profili personalizzati. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | Converte RGB in CMYK usando profili ICC personalizzati. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-) | Converte RGB in CMYK usando profili ICC personalizzati. |
| [toCmykaIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykaIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-) | Converte RGB in CMYKA (con alfa) usando profili ICC personalizzati. |
| [toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toPsdCmykIcc-int---java.io.InputStream-java.io.InputStream-) | La conversione da colori ARGB a colori CMYK usando la conversione Icc con profili personalizzati. |
| [toCmykaIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykaIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | Converte RGB in CMYKA (con alfa) usando profili ICC personalizzati. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.imaging.Color---) | La conversione da colori ARGB a colori CMYK usando la conversione Icc con profili predefiniti. |
| [toCmykIcc(int[] pixels)](#toCmykIcc-int---) | La conversione da colori ARGB a colori CMYK usando la conversione Icc con profili predefiniti. |
| [toPsdCmykIcc(int[] pixels)](#toPsdCmykIcc-int---) | La conversione da colori ARGB a colori CMYK usando la conversione Icc con profili predefiniti. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.imaging.Color-) | La conversione da colore ARGB a colore CMYK usando la conversione Icc con profili predefiniti. |
| [toCmykIcc(int argb)](#toCmykIcc-int-) | La conversione da colore ARGB a colore CMYK usando la conversione Icc con profili predefiniti. |
| [toPsdCmykIcc(int argb)](#toPsdCmykIcc-int-) | La conversione da colore ARGB a colore CMYK usando la conversione Icc con profili predefiniti. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.imaging.Color-java.io.InputStream-java.io.InputStream-) | La conversione da colore ARGB a colore CMYK usando la conversione Icc con profili personalizzati. |
| [toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-int-java.io.InputStream-java.io.InputStream-) | La conversione da colore ARGB a colore CMYK usando la conversione Icc con profili personalizzati. |
| [toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toPsdCmykIcc-int-java.io.InputStream-java.io.InputStream-) | La conversione da colore ARGB a colore CMYK usando la conversione Icc con profili personalizzati. |
### getC(int cmyk) {#getC-int-}
```
public static int getC(int cmyk)
```


Restituisce il valore del componente ciano.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmyk | int | Il colore CMYK presentato come valore intero a 32 bit. |

**Returns:**
int - Il valore del componente ciano.

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

//L'output appare così:
//Converti RGB in CMYK senza usare profili ICC.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getM(int cmyk) {#getM-int-}
```
public static int getM(int cmyk)
```


Restituisce il valore del componente magenta.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmyk | int | Il colore CMYK presentato come valore intero a 32 bit. |

**Returns:**
int - Il valore del componente magenta.

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

//L'output appare così:
//Converti RGB in CMYK senza usare profili ICC.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getY(int cmyk) {#getY-int-}
```
public static int getY(int cmyk)
```


Restituisce il valore del componente giallo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmyk | int | Il colore CMYK presentato come valore intero a 32 bit. |

**Returns:**
int - Il valore del componente giallo.

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

//L'output appare così:
//Converti RGB in CMYK senza usare profili ICC.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getK(int cmyk) {#getK-int-}
```
public static int getK(int cmyk)
```


Restituisce il valore del componente nero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmyk | int | Il colore CMYK presentato come valore intero a 32 bit. |

**Returns:**
int - Il valore del componente nero.

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

//L'output appare così:
//Converti RGB in CMYK senza usare profili ICC.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### fromComponents(int cyan, int magenta, int yellow, int black) {#fromComponents-int-int-int-int-}
```
public static int fromComponents(int cyan, int magenta, int yellow, int black)
```


Crea CMYK a partire da valori a 32 bit di ciano, magenta, giallo e nero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ciano | int | Il componente ciano. I valori validi sono da 0 a 255. |
| magenta | int | Il componente magenta. I valori validi sono da 0 a 255. |
| giallo | int | Il componente giallo. I valori validi sono da 0 a 255. |
| nero | int | Il componente nero. I valori validi sono da 0 a 255. |

**Returns:**
int - Il colore CMYK presentato come valore intero a 32 bit.

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

//L'output appare così:
//Converti CMYK in RGB senza usare profili ICC.
//CMYK(255,0,0,0)        => RGB(0,255,255)
//CMYK(0,255,0,0)        => RGB(255,0,255)
//CMYK(0,0,255,0)        => RGB(255,255,0)
//CMYK(0,0,0,255)        => RGB(0,0,0)
```

### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static int[] toCmyk(int[] argbPixels)
```


La conversione da colori ARGB a colori CMYK.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argbPixels | int[] | I colori ARGB presentati come valori interi a 32 bit. |

**Returns:**
int[] - I colori CMYK presentati come valori interi a 32 bit.
### toCmykBytes(int[] argbPixels, int startIndex, int length) {#toCmykBytes-int---int-int-}
```
public static byte[] toCmykBytes(int[] argbPixels, int startIndex, int length)
```


Converte ARGB in CMYK.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argbPixels | int[] | I colori RGB presentati come valori interi a 32 bit. |
| startIndex | int | L'indice di inizio del colore RGB. |
| length | int | Il numero di pixel RGB da convertire. |

**Returns:**
byte[] - I colori CMYK presentati come array di byte.
### toCmykaBytes(int[] argbPixels, int startIndex, int length) {#toCmykaBytes-int---int-int-}
```
public static byte[] toCmykaBytes(int[] argbPixels, int startIndex, int length)
```


Converte ARGB in CMYKA (con trasparenza).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argbPixels | int[] | I colori RGB presentati come valori interi a 32 bit. |
| startIndex | int | L'indice di inizio del colore RGB. |
| length | int | Il numero di pixel RGB da convertire. |

**Returns:**
byte[] - I colori CMYK presentati come array di byte.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static int toCmyk(int argbPixel)
```


La conversione da colore ARGB a colore CMYK.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argbPixel | int | Il colore ARGB presentato come valore intero a 32 bit. |

**Returns:**
int - Il colore CMYK presentato come valore intero a 32 bit.
### toCmyk(Color pixel) {#toCmyk-com.aspose.imaging.Color-}
```
public static int toCmyk(Color pixel)
```


La conversione da colore ARGB a colore CMYK.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | Il colore ARGB. |

**Returns:**
int - Il colore CMYK presentato come valore intero a 32 bit.

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

//L'output appare così:
//Converti RGB in CMYK senza usare profili ICC.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### toCmyk(Color[] pixels) {#toCmyk-com.aspose.imaging.Color---}
```
public static int[] toCmyk(Color[] pixels)
```


La conversione da colori ARGB a colori CMYK.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | I colori ARGB. |

**Returns:**
int[] - I colori CMYK presentati come valori interi a 32 bit.
### toArgb(int[] cmykPixels) {#toArgb-int---}
```
public static Color[] toArgb(int[] cmykPixels)
```


La conversione da colori CMYK a colori ARGB.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixels | int[] | I colori CMYK presentati come valori interi a 32 bit. |

**Returns:**
com.aspose.imaging.Color[] - I colori ARGB.
### toArgb(int cmykPixel) {#toArgb-int-}
```
public static Color toArgb(int cmykPixel)
```


La conversione da colore CMYK a colore ARGB.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixel | int | Il colore CMYK presentato come valore intero a 32 bit. |

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

//L'output appare così:
//Converti CMYK in RGB senza usare profili ICC.
//CMYK(255,0,0,0)        => RGB(0,255,255)
//CMYK(0,255,0,0)        => RGB(255,0,255)
//CMYK(0,0,255,0)        => RGB(255,255,0)
//CMYK(0,0,0,255)        => RGB(0,0,0)
```

### toArgb32(int[] cmykPixels) {#toArgb32-int---}
```
public static int[] toArgb32(int[] cmykPixels)
```


La conversione da colori CMYK a colori ARGB.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixels | int[] | I colori CMYK presentati come valori interi a 32 bit. |

**Returns:**
int[] - I colori ARGB presentati come valori interi a 32 bit.
### toArgb32(int[] cmykPixels, boolean reuseArray) {#toArgb32-int---boolean-}
```
public static int[] toArgb32(int[] cmykPixels, boolean reuseArray)
```


Esegue la conversione da colori CMYK a colori ARGB e li memorizza nello stesso array se `reuseArray` è true. Altrimenti, verrà allocato un nuovo array.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixels | int[] | I colori CMYK presentati come valori interi a 32 bit. |
| reuseArray | boolean | se `true` l'array di input `cmykPixels` verrà riempito con nuovi valori e restituito; altrimenti verrà allocato e restituito un nuovo array. |

**Returns:**
int[] - Il nuovo array allocato o `cmykPixels` riempito con colori ARGB presentati come valori interi a 32 bit.
### toArgbIcc(int[] cmykPixels) {#toArgbIcc-int---}
```
public static Color[] toArgbIcc(int[] cmykPixels)
```


La conversione da colori CMYK a colori ARGB usando la conversione Icc con profili predefiniti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixels | int[] | I pixel CMYK presentati come valori interi a 32 bit. |

**Returns:**
com.aspose.imaging.Color[] - I colori ARGB.
### toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


La conversione da colori CMYK a colori ARGB usando la conversione Icc con profili personalizzati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixels | int[] | I colori CMYK presentati come valori interi a 32 bit. |
| cmykIccStream | java.io.InputStream | Lo stream contenente il profilo Icc CMYK. |
| rgbIccStream | java.io.InputStream | Lo stream contenente il profilo Icc RGB. |

**Returns:**
com.aspose.imaging.Color[] - I colori ARGB.
### toArgbIcc(int cmykPixel) {#toArgbIcc-int-}
```
public static Color toArgbIcc(int cmykPixel)
```


La conversione da colore CMYK a colore ARGB usando la conversione Icc con profili predefiniti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixel | int | Il colore CMYK presentato come valore intero a 32 bit. |

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

// Specifica il percorso ai profili ICC personalizzati RGB e CMYK.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert CMYK to RGB using custom ICC profiles.");
// Leggi tutti i byte dai file ICC in memoria per avere la possibilità di reimpostare lo stream del profilo di input prima di chiamare toCmykIcc
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

//L'output appare così:
//Converti CMYK in RGB usando i profili ICC predefiniti.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//CMYK(0,0,255,0)        => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
//Converti CMYK in RGB usando profili ICC personalizzati.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//(0,0,255,0)            => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
```

### toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static Color toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


La conversione da colore CMYK a colore ARGB usando la conversione Icc con profilo personalizzato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixel | int | Il colore CMYK presentato come valore intero a 32 bit. |
| cmykIccStream | java.io.InputStream | Lo stream contenente il profilo Icc CMYK. |
| rgbIccStream | java.io.InputStream | Lo stream contenente il profilo Icc RGB. |

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

// Specifica il percorso ai profili ICC personalizzati RGB e CMYK.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert CMYK to RGB using custom ICC profiles.");
// Leggi tutti i byte dai file ICC in memoria per avere la possibilità di reimpostare lo stream del profilo di input prima di chiamare toCmykIcc
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

//L'output appare così:
//Converti CMYK in RGB usando i profili ICC predefiniti.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//CMYK(0,0,255,0)        => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
//Converti CMYK in RGB usando profili ICC personalizzati.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//(0,0,255,0)            => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
```

### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.imaging.Color---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversione da colori ARGB a colori CMYK usando la conversione Icc con profili personalizzati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | I colori ARGB. |
| rgbIccStream | java.io.InputStream | Lo stream contenente il profilo Icc RGB. |
| cmykIccStream | java.io.InputStream | Lo stream contenente il profilo Icc CMYK. |

**Returns:**
int[] - I colori CMYK presentati come valori interi a 32 bit.
### toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversione da colori ARGB a colori CMYK usando la conversione Icc con profili personalizzati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | int[] | I colori ARGB. |
| rgbIccStream | java.io.InputStream | Lo stream contenente il profilo Icc RGB. |
| cmykIccStream | java.io.InputStream | Lo stream contenente il profilo Icc CMYK. |

**Returns:**
int[] - I colori CMYK presentati come valori interi a 32 bit.
### toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


Converte RGB in CMYK usando profili ICC personalizzati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | int[] | I colori RGB presentati come valori interi a 32 bit. |
| startIndex | int | L'indice di inizio del colore RGB. |
| length | int | Il numero di pixel RGB da convertire. |
| rgbIccStream | java.io.InputStream | Il flusso del profilo RGB. |
| cmykIccStream | java.io.InputStream | Il flusso del profilo CMYK. |

**Returns:**
byte[] - I colori CMYK presentati come array di byte.
### toCmykIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)
```


Converte RGB in CMYK usando profili ICC personalizzati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | int[] | I colori RGB presentati come valori interi a 32 bit. |
| startIndex | int | L'indice di inizio del colore RGB. |
| length | int | Il numero di pixel RGB da convertire. |
| cmykBytes | byte[] | I byte Cmyk. |
| cmykOffset | int | L'offset `cmykBytes`. |
| rgbIccStream | java.io.InputStream | Il flusso del profilo RGB. |
| cmykIccStream | java.io.InputStream | Il flusso del profilo CMYK. |

**Returns:**
byte[] - I colori CMYK presentati come array di byte.
### toCmykaIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykaIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykaIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)
```


Converte RGB in CMYKA (con alfa) usando profili ICC personalizzati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | int[] | I colori RGB presentati come valori interi a 32 bit. |
| startIndex | int | L'indice di inizio del colore RGB. |
| length | int | Il numero di pixel RGB da convertire. |
| cmykBytes | byte[] | I byte Cmyk. |
| cmykOffset | int | L'offset `cmykBytes`. |
| rgbIccStream | java.io.InputStream | Il flusso del profilo RGB. |
| cmykIccStream | java.io.InputStream | Il flusso del profilo CMYK. |

**Returns:**
byte[] - I colori CMYK presentati come array di byte.
### toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toPsdCmykIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static int[] toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversione da colori ARGB a colori CMYK usando la conversione Icc con profili personalizzati. Utilizza il formato PSD CMYK con ordine di byte KCMY e valori di canale invertiti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | int[] | I colori ARGB. |
| rgbIccStream | java.io.InputStream | Lo stream contenente il profilo Icc RGB. |
| cmykIccStream | java.io.InputStream | Lo stream contenente il profilo Icc CMYK. |

**Returns:**
int[] - I colori CMYK presentati come valori interi a 32 bit in ordine di byte KCMY con valori di canale invertiti.
### toCmykaIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykaIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykaIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


Converte RGB in CMYKA (con alfa) usando profili ICC personalizzati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | int[] | I colori RGB presentati come valori interi a 32 bit. |
| startIndex | int | L'indice di inizio del colore RGB. |
| length | int | Il numero di pixel RGB da convertire. |
| rgbIccStream | java.io.InputStream | Il flusso del profilo RGB. |
| cmykIccStream | java.io.InputStream | Il flusso del profilo CMYK. |

**Returns:**
byte[] - I colori CMYK presentati come array di byte.
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.imaging.Color---}
```
public static int[] toCmykIcc(Color[] pixels)
```


La conversione da colori ARGB a colori CMYK usando la conversione Icc con profili predefiniti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | I colori ARGB. |

**Returns:**
int[] - I colori CMYK presentati come valori interi a 32 bit.
### toCmykIcc(int[] pixels) {#toCmykIcc-int---}
```
public static int[] toCmykIcc(int[] pixels)
```


La conversione da colori ARGB a colori CMYK usando la conversione Icc con profili predefiniti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | int[] | I colori ARGB. |

**Returns:**
int[] - I colori CMYK presentati come valori interi a 32 bit.
### toPsdCmykIcc(int[] pixels) {#toPsdCmykIcc-int---}
```
public static int[] toPsdCmykIcc(int[] pixels)
```


La conversione da colori ARGB a colori CMYK usando la conversione Icc con profili predefiniti. Utilizza il formato PSD CMYK con ordine di byte KCMY e valori di canale invertiti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | int[] | I colori ARGB. |

**Returns:**
int[] - I colori CMYK presentati come valori interi a 32 bit in ordine di byte KCMY con valori di canale invertiti.
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.imaging.Color-}
```
public static int toCmykIcc(Color pixel)
```


La conversione da colore ARGB a colore CMYK usando la conversione Icc con profili predefiniti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | Il colore ARGB. |

**Returns:**
int - Il colore CMYK presentato come valore intero a 32 bit.

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

// Specifica il percorso ai profili ICC RGB e CMYK.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert RGB to CMYK using custom ICC profiles.");

// Leggi tutti i byte dai file ICC in memoria per avere la possibilità di reimpostare lo stream del profilo di input prima di chiamare toCmykIcc
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

//L'output appare così:
//Converti RGB in CMYK usando profili ICC predefiniti.
//RGB(255,0,0)        => CMYK(0,254,249,15)
//RGB(0,128,0)        => CMYK(247,21,254,85)
//RGB(0,0,255)        => CMYK(254,195,0,134)
//Converti RGB in CMYK usando profili ICC personalizzati.
//RGB(255,0,0)        => CMYK(0,207,219,0)
//RGB(0,128,0)        => CMYK(238,16,254,80)
//RGB(0,0,255)        => CMYK(242,182,0,0)
```

### toCmykIcc(int argb) {#toCmykIcc-int-}
```
public static int toCmykIcc(int argb)
```


La conversione da colore ARGB a colore CMYK usando la conversione Icc con profili predefiniti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argb | int | Il colore ARGB. |

**Returns:**
int - Il colore CMYK presentato come valore intero a 32 bit.
### toPsdCmykIcc(int argb) {#toPsdCmykIcc-int-}
```
public static int toPsdCmykIcc(int argb)
```


La conversione da colore ARGB a colore CMYK usando la conversione Icc con profili predefiniti. Utilizza il formato PSD CMYK con ordine di byte KCMY e valori di canale invertiti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argb | int | Il colore ARGB. |

**Returns:**
int - Il colore CMYK presentato come valore intero a 32 bit in ordine byte KCMY con valori di canale invertiti.
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.imaging.Color-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversione da colore ARGB a colore CMYK usando la conversione Icc con profili personalizzati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | Il colore ARGB. |
| rgbIccStream | java.io.InputStream | Lo stream contenente il profilo Icc RGB. |
| cmykIccStream | java.io.InputStream | Lo stream contenente il profilo Icc CMYK. |

**Returns:**
int - Il colore CMYK presentato come valore intero a 32 bit.

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

// Specifica il percorso ai profili ICC RGB e CMYK.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert RGB to CMYK using custom ICC profiles.");

// Leggi tutti i byte dai file ICC in memoria per avere la possibilità di reimpostare lo stream del profilo di input prima di chiamare toCmykIcc
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

//L'output appare così:
//Converti RGB in CMYK usando profili ICC predefiniti.
//RGB(255,0,0)        => CMYK(0,254,249,15)
//RGB(0,128,0)        => CMYK(247,21,254,85)
//RGB(0,0,255)        => CMYK(254,195,0,134)
//Converti RGB in CMYK usando profili ICC personalizzati.
//RGB(255,0,0)        => CMYK(0,207,219,0)
//RGB(0,128,0)        => CMYK(238,16,254,80)
//RGB(0,0,255)        => CMYK(242,182,0,0)
```

### toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversione da colore ARGB a colore CMYK usando la conversione Icc con profili personalizzati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argb | int | Il colore ARGB. |
| rgbIccStream | java.io.InputStream | Lo stream contenente il profilo Icc RGB. |
| cmykIccStream | java.io.InputStream | Lo stream contenente il profilo Icc CMYK. |

**Returns:**
int - Il colore CMYK presentato come valore intero a 32 bit.
### toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toPsdCmykIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static int toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversione da colore ARGB a colore CMYK usando la conversione Icc con profili personalizzati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | int | Il colore ARGB. |
| rgbIccStream | java.io.InputStream | Lo stream contenente il profilo Icc RGB. |
| cmykIccStream | java.io.InputStream | Lo stream contenente il profilo Icc CMYK. |

**Returns:**
int - I colori CMYK presentati come valori interi a 32 bit in ordine byte KCMY con valori di canale invertiti.
