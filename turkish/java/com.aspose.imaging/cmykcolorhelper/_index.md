---
title: "CmykColorHelper"
second_title: "Aspose.Imaging for Java API Referansı"
description: "İmzalı 32-bit tamsayı değeri olarak sunulan CMYK rengiyle çalışmak için yardımcı yöntemler."
type: docs
weight: 19
url: /tr/java/com.aspose.imaging/cmykcolorhelper/
---
**Inheritance:**
java.lang.Object
```
public final class CmykColorHelper
```

CMYK rengini imzalı 32-bit tamsayı değeri olarak çalışmak için yardımcı yöntemler. [CmykColor](../../com.aspose.imaging/cmykcolor) yapısı gibi benzer bir API sağlar. CMYK rengi sadece Int32 olarak sunulduğu için daha hafiftir, iç alanları olan bir yapı yerine. Mümkün olduğunda, kullanımdan kaldırılmış [CmykColor](../../com.aspose.imaging/cmykcolor) yapısı yerine bu sınıfın statik yöntemlerini tercih edin.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getC(int cmyk)](#getC-int-) | Cyan bileşen değerini alır. |
| [getM(int cmyk)](#getM-int-) | Magenta bileşen değerini alır. |
| [getY(int cmyk)](#getY-int-) | Sarı bileşen değerini alır. |
| [getK(int cmyk)](#getK-int-) | Siyah bileşen değerini alır. |
| [fromComponents(int cyan, int magenta, int yellow, int black)](#fromComponents-int-int-int-int-) | 32-bit cyan, magenta, yellow ve black değerlerinden CMYK oluşturur. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | ARGB renklerinden CMYK renklerine dönüşüm. |
| [toCmykBytes(int[] argbPixels, int startIndex, int length)](#toCmykBytes-int---int-int-) | ARGB'yi CMYK'ye dönüştürür. |
| [toCmykaBytes(int[] argbPixels, int startIndex, int length)](#toCmykaBytes-int---int-int-) | ARGB'yi CMYKA'ya (şeffaflık ile) dönüştürür. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | ARGB renginden CMYK rengine dönüşüm. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.imaging.Color-) | ARGB renginden CMYK rengine dönüşüm. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.imaging.Color---) | ARGB renklerinden CMYK renklerine dönüşüm. |
| [toArgb(int[] cmykPixels)](#toArgb-int---) | CMYK renklerinden ARGB renklerine dönüşüm. |
| [toArgb(int cmykPixel)](#toArgb-int-) | CMYK renginden ARGB rengine dönüşüm. |
| [toArgb32(int[] cmykPixels)](#toArgb32-int---) | CMYK renklerinden ARGB renklerine dönüşüm. |
| [toArgb32(int[] cmykPixels, boolean reuseArray)](#toArgb32-int---boolean-) | CMYK renklerinden ARGB renklerine dönüşüm gerçekleştirir ve `reuseArray` doğru ise aynı diziye kaydeder. |
| [toArgbIcc(int[] cmykPixels)](#toArgbIcc-int---) | CMYK renklerinden ARGB renklerine, varsayılan profillerle Icc dönüşümü kullanılarak dönüşüm. |
| [toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int---java.io.InputStream-java.io.InputStream-) | CMYK renklerinden ARGB renklerine, özel profillerle Icc dönüşümü kullanılarak dönüşüm. |
| [toArgbIcc(int cmykPixel)](#toArgbIcc-int-) | CMYK renginden ARGB rengine, varsayılan profillerle Icc dönüşümü kullanılarak dönüşüm. |
| [toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int-java.io.InputStream-java.io.InputStream-) | CMYK renginden ARGB rengine, özel profil ile Icc dönüşümü kullanılarak dönüşüm. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.imaging.Color---java.io.InputStream-java.io.InputStream-) | ARGB renklerinden CMYK renklerine, özel profillerle Icc dönüşümü kullanılarak dönüşüm. |
| [toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-int---java.io.InputStream-java.io.InputStream-) | ARGB renklerinden CMYK renklerine, özel profillerle Icc dönüşümü kullanılarak dönüşüm. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | RGB'yi özel ICC profilleri kullanarak CMYK'ye dönüştürür. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-) | RGB'yi özel ICC profilleri kullanarak CMYK'ye dönüştürür. |
| [toCmykaIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykaIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-) | RGB'yi (alfa ile) özel ICC profilleri kullanarak CMYKA'ya dönüştürür. |
| [toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toPsdCmykIcc-int---java.io.InputStream-java.io.InputStream-) | ARGB renklerinden CMYK renklerine, özel profillerle Icc dönüşümü kullanılarak dönüşüm. |
| [toCmykaIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykaIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | RGB'yi (alfa ile) özel ICC profilleri kullanarak CMYKA'ya dönüştürür. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.imaging.Color---) | ARGB renklerinden CMYK renklerine, varsayılan profillerle Icc dönüşümü kullanılarak dönüşüm. |
| [toCmykIcc(int[] pixels)](#toCmykIcc-int---) | ARGB renklerinden CMYK renklerine, varsayılan profillerle Icc dönüşümü kullanılarak dönüşüm. |
| [toPsdCmykIcc(int[] pixels)](#toPsdCmykIcc-int---) | ARGB renklerinden CMYK renklerine, varsayılan profillerle Icc dönüşümü kullanılarak dönüşüm. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.imaging.Color-) | ARGB renginden CMYK rengine, varsayılan profillerle Icc dönüşümü kullanılarak dönüşüm. |
| [toCmykIcc(int argb)](#toCmykIcc-int-) | ARGB renginden CMYK rengine, varsayılan profillerle Icc dönüşümü kullanılarak dönüşüm. |
| [toPsdCmykIcc(int argb)](#toPsdCmykIcc-int-) | ARGB renginden CMYK rengine, varsayılan profillerle Icc dönüşümü kullanılarak dönüşüm. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.imaging.Color-java.io.InputStream-java.io.InputStream-) | ARGB renginden CMYK rengine, özel profillerle Icc dönüşümü kullanılarak dönüşüm. |
| [toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-int-java.io.InputStream-java.io.InputStream-) | ARGB renginden CMYK rengine, özel profillerle Icc dönüşümü kullanılarak dönüşüm. |
| [toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toPsdCmykIcc-int-java.io.InputStream-java.io.InputStream-) | ARGB renginden CMYK rengine, özel profillerle Icc dönüşümü kullanılarak dönüşüm. |
### getC(int cmyk) {#getC-int-}
```
public static int getC(int cmyk)
```


Cyan bileşen değerini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmyk | int | CMYK rengi 32-bit tamsayı değeri olarak sunulur. |

**Returns:**
int - Camgöbeği bileşen değeri.

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

//Çıktı şu şekilde görünür:
//ICC profilleri kullanmadan RGB'yi CMYK'ye dönüştür.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getM(int cmyk) {#getM-int-}
```
public static int getM(int cmyk)
```


Magenta bileşen değerini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmyk | int | CMYK rengi 32-bit tamsayı değeri olarak sunulur. |

**Returns:**
int - Magenta bileşen değeri.

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

//Çıktı şu şekilde görünür:
//ICC profilleri kullanmadan RGB'yi CMYK'ye dönüştür.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getY(int cmyk) {#getY-int-}
```
public static int getY(int cmyk)
```


Sarı bileşen değerini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmyk | int | CMYK rengi 32-bit tamsayı değeri olarak sunulur. |

**Returns:**
int - Sarı bileşen değeri.

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

//Çıktı şu şekilde görünür:
//ICC profilleri kullanmadan RGB'yi CMYK'ye dönüştür.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getK(int cmyk) {#getK-int-}
```
public static int getK(int cmyk)
```


Siyah bileşen değerini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmyk | int | CMYK rengi 32-bit tamsayı değeri olarak sunulur. |

**Returns:**
int - Siyah bileşen değeri.

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

//Çıktı şu şekilde görünür:
//ICC profilleri kullanmadan RGB'yi CMYK'ye dönüştür.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### fromComponents(int cyan, int magenta, int yellow, int black) {#fromComponents-int-int-int-int-}
```
public static int fromComponents(int cyan, int magenta, int yellow, int black)
```


32-bit cyan, magenta, yellow ve black değerlerinden CMYK oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| camgöbeği | int | Camgöbeği bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| macenta | int | Macenta bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| sarı | int | Sarı bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| siyah | int | Siyah bileşeni. Geçerli değerler 0 ile 255 arasındadır. |

**Returns:**
int - CMYK rengi 32-bit tam sayı değeri olarak sunulur.

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

//Çıktı şu şekilde görünür:
//CMYK'yi ICC profilleri kullanmadan RGB'ye dönüştür.
//CMYK(255,0,0,0)        => RGB(0,255,255)
//CMYK(0,255,0,0)        => RGB(255,0,255)
//CMYK(0,0,255,0)        => RGB(255,255,0)
//CMYK(0,0,0,255)        => RGB(0,0,0)
```

### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static int[] toCmyk(int[] argbPixels)
```


ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argbPixels | int[] | ARGB renkleri 32-bit tam sayı değerleri olarak sunulur. |

**Returns:**
int[] - CMYK renkleri 32-bit tam sayı değerleri olarak sunulur.
### toCmykBytes(int[] argbPixels, int startIndex, int length) {#toCmykBytes-int---int-int-}
```
public static byte[] toCmykBytes(int[] argbPixels, int startIndex, int length)
```


ARGB'yi CMYK'ye dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argbPixels | int[] | RGB renkleri 32-bit tam sayı değerleri olarak sunulur. |
| startIndex | int | RGB renginin başlangıç indeksi. |
| length | int | Dönüştürülecek RGB piksel sayısı. |

**Returns:**
byte[] - CMYK renkleri bayt dizisi olarak sunulur.
### toCmykaBytes(int[] argbPixels, int startIndex, int length) {#toCmykaBytes-int---int-int-}
```
public static byte[] toCmykaBytes(int[] argbPixels, int startIndex, int length)
```


ARGB'yi CMYKA'ya (şeffaflık ile) dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argbPixels | int[] | RGB renkleri 32-bit tam sayı değerleri olarak sunulur. |
| startIndex | int | RGB renginin başlangıç indeksi. |
| length | int | Dönüştürülecek RGB piksel sayısı. |

**Returns:**
byte[] - CMYK renkleri bayt dizisi olarak sunulur.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static int toCmyk(int argbPixel)
```


ARGB renginden CMYK rengine dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argbPixel | int | ARGB rengi 32-bit tam sayı değeri olarak sunulur. |

**Returns:**
int - CMYK rengi 32-bit tam sayı değeri olarak sunulur.
### toCmyk(Color pixel) {#toCmyk-com.aspose.imaging.Color-}
```
public static int toCmyk(Color pixel)
```


ARGB renginden CMYK rengine dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | ARGB rengi. |

**Returns:**
int - CMYK rengi 32-bit tam sayı değeri olarak sunulur.

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

//Çıktı şu şekilde görünür:
//ICC profilleri kullanmadan RGB'yi CMYK'ye dönüştür.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### toCmyk(Color[] pixels) {#toCmyk-com.aspose.imaging.Color---}
```
public static int[] toCmyk(Color[] pixels)
```


ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | ARGB renkleri. |

**Returns:**
int[] - CMYK renkleri 32-bit tam sayı değerleri olarak sunulur.
### toArgb(int[] cmykPixels) {#toArgb-int---}
```
public static Color[] toArgb(int[] cmykPixels)
```


CMYK renklerinden ARGB renklerine dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixels | int[] | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |

**Returns:**
com.aspose.imaging.Color[] - ARGB renkleri.
### toArgb(int cmykPixel) {#toArgb-int-}
```
public static Color toArgb(int cmykPixel)
```


CMYK renginden ARGB rengine dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixel | int | CMYK rengi 32-bit tamsayı değeri olarak sunulur. |

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

//Çıktı şu şekilde görünür:
//CMYK'yi ICC profilleri kullanmadan RGB'ye dönüştür.
//CMYK(255,0,0,0)        => RGB(0,255,255)
//CMYK(0,255,0,0)        => RGB(255,0,255)
//CMYK(0,0,255,0)        => RGB(255,255,0)
//CMYK(0,0,0,255)        => RGB(0,0,0)
```

### toArgb32(int[] cmykPixels) {#toArgb32-int---}
```
public static int[] toArgb32(int[] cmykPixels)
```


CMYK renklerinden ARGB renklerine dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixels | int[] | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |

**Returns:**
int[] - ARGB renkleri 32-bit tam sayı değerleri olarak sunulur.
### toArgb32(int[] cmykPixels, boolean reuseArray) {#toArgb32-int---boolean-}
```
public static int[] toArgb32(int[] cmykPixels, boolean reuseArray)
```


CMYK renklerinden ARGB renklerine dönüşümü gerçekleştirir ve `reuseArray` true ise aynı diziye kaydeder. Aksi takdirde yeni dizi tahsis edilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixels | int[] | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |
| reuseArray | boolean | `true` ise giriş `cmykPixels` dizisi yeni değerlerle doldurulup döndürülür; aksi takdirde yeni bir dizi tahsis edilip döndürülür. |

**Returns:**
int[] - Yeni tahsis edilen dizi veya ARGB renkleriyle doldurulmuş `cmykPixels` dizisi, 32-bit tam sayı değerleri olarak sunulur.
### toArgbIcc(int[] cmykPixels) {#toArgbIcc-int---}
```
public static Color[] toArgbIcc(int[] cmykPixels)
```


CMYK renklerinden ARGB renklerine, varsayılan profillerle Icc dönüşümü kullanılarak dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixels | int[] | CMYK pikselleri 32-bit tam sayı değerleri olarak sunulur. |

**Returns:**
com.aspose.imaging.Color[] - ARGB renkleri.
### toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


CMYK renklerinden ARGB renklerine, özel profillerle Icc dönüşümü kullanılarak dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixels | int[] | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |
| cmykIccStream | java.io.InputStream | CMYK ICC profilini içeren akış. |
| rgbIccStream | java.io.InputStream | RGB ICC profilini içeren akış. |

**Returns:**
com.aspose.imaging.Color[] - ARGB renkleri.
### toArgbIcc(int cmykPixel) {#toArgbIcc-int-}
```
public static Color toArgbIcc(int cmykPixel)
```


CMYK renginden ARGB rengine, varsayılan profillerle Icc dönüşümü kullanılarak dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixel | int | CMYK rengi 32-bit tamsayı değeri olarak sunulur. |

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

// Özel RGB ve CMYK ICC profilleri için yolunuzu belirtin.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert CMYK to RGB using custom ICC profiles.");
// toCmykIcc çağrılmadan önce giriş profil akışını sıfırlama imkanı sağlamak için ICC dosyalarından tüm baytları belleğe okuyun.
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

//Çıktı şu şekilde görünür:
//CMYK'yi varsayılan ICC profilleriyle RGB'ye dönüştür.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//CMYK(0,0,255,0)        => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
//Özel ICC profilleri kullanarak CMYK'yi RGB'ye dönüştür.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//(0,0,255,0)            => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
```

### toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static Color toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


CMYK renginden ARGB rengine, özel profil ile Icc dönüşümü kullanılarak dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixel | int | CMYK rengi 32-bit tamsayı değeri olarak sunulur. |
| cmykIccStream | java.io.InputStream | CMYK ICC profilini içeren akış. |
| rgbIccStream | java.io.InputStream | RGB ICC profilini içeren akış. |

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

// Özel RGB ve CMYK ICC profilleri için yolunuzu belirtin.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert CMYK to RGB using custom ICC profiles.");
// toCmykIcc çağrılmadan önce giriş profil akışını sıfırlama imkanı sağlamak için ICC dosyalarından tüm baytları belleğe okuyun.
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

//Çıktı şu şekilde görünür:
//CMYK'yi varsayılan ICC profilleriyle RGB'ye dönüştür.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//CMYK(0,0,255,0)        => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
//Özel ICC profilleri kullanarak CMYK'yi RGB'ye dönüştür.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//(0,0,255,0)            => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
```

### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.imaging.Color---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


ARGB renklerinden CMYK renklerine, özel profillerle Icc dönüşümü kullanılarak dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | ARGB renkleri. |
| rgbIccStream | java.io.InputStream | RGB ICC profilini içeren akış. |
| cmykIccStream | java.io.InputStream | CMYK ICC profilini içeren akış. |

**Returns:**
int[] - CMYK renkleri 32-bit tam sayı değerleri olarak sunulur.
### toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


ARGB renklerinden CMYK renklerine, özel profillerle Icc dönüşümü kullanılarak dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pikseller | int[] | ARGB renkleri. |
| rgbIccStream | java.io.InputStream | RGB ICC profilini içeren akış. |
| cmykIccStream | java.io.InputStream | CMYK ICC profilini içeren akış. |

**Returns:**
int[] - CMYK renkleri 32-bit tam sayı değerleri olarak sunulur.
### toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


RGB'yi özel ICC profilleri kullanarak CMYK'ye dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pikseller | int[] | RGB renkleri 32-bit tam sayı değerleri olarak sunulur. |
| startIndex | int | RGB renginin başlangıç indeksi. |
| length | int | Dönüştürülecek RGB piksel sayısı. |
| rgbIccStream | java.io.InputStream | RGB profil akışı. |
| cmykIccStream | java.io.InputStream | CMYK profil akışı. |

**Returns:**
byte[] - CMYK renkleri bayt dizisi olarak sunulur.
### toCmykIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)
```


RGB'yi özel ICC profilleri kullanarak CMYK'ye dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pikseller | int[] | RGB renkleri 32-bit tam sayı değerleri olarak sunulur. |
| startIndex | int | RGB renginin başlangıç indeksi. |
| length | int | Dönüştürülecek RGB piksel sayısı. |
| cmykBytes | byte[] | Cmyk baytları. |
| cmykOffset | int | `cmykBytes` ofseti. |
| rgbIccStream | java.io.InputStream | RGB profil akışı. |
| cmykIccStream | java.io.InputStream | CMYK profil akışı. |

**Returns:**
byte[] - CMYK renkleri bayt dizisi olarak sunulur.
### toCmykaIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykaIccBytes-int---int-int-byte---int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykaIccBytes(int[] pixels, int startIndex, int length, byte[] cmykBytes, int cmykOffset, InputStream rgbIccStream, InputStream cmykIccStream)
```


RGB'yi (alfa ile) özel ICC profilleri kullanarak CMYKA'ya dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pikseller | int[] | RGB renkleri 32-bit tam sayı değerleri olarak sunulur. |
| startIndex | int | RGB renginin başlangıç indeksi. |
| length | int | Dönüştürülecek RGB piksel sayısı. |
| cmykBytes | byte[] | Cmyk baytları. |
| cmykOffset | int | `cmykBytes` ofseti. |
| rgbIccStream | java.io.InputStream | RGB profil akışı. |
| cmykIccStream | java.io.InputStream | CMYK profil akışı. |

**Returns:**
byte[] - CMYK renkleri bayt dizisi olarak sunulur.
### toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toPsdCmykIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static int[] toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


Özel profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm. Ters kanal değerleriyle PSD CMYK formatı KCMY bayt sırasını kullanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pikseller | int[] | ARGB renkleri. |
| rgbIccStream | java.io.InputStream | RGB ICC profilini içeren akış. |
| cmykIccStream | java.io.InputStream | CMYK ICC profilini içeren akış. |

**Returns:**
int[] - Ters kanal değerleriyle KCMY bayt sırasındaki 32-bit tamsayı değerleri olarak sunulan CMYK renkleri.
### toCmykaIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykaIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykaIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


RGB'yi (alfa ile) özel ICC profilleri kullanarak CMYKA'ya dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pikseller | int[] | RGB renkleri 32-bit tam sayı değerleri olarak sunulur. |
| startIndex | int | RGB renginin başlangıç indeksi. |
| length | int | Dönüştürülecek RGB piksel sayısı. |
| rgbIccStream | java.io.InputStream | RGB profil akışı. |
| cmykIccStream | java.io.InputStream | CMYK profil akışı. |

**Returns:**
byte[] - CMYK renkleri bayt dizisi olarak sunulur.
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.imaging.Color---}
```
public static int[] toCmykIcc(Color[] pixels)
```


ARGB renklerinden CMYK renklerine, varsayılan profillerle Icc dönüşümü kullanılarak dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | ARGB renkleri. |

**Returns:**
int[] - CMYK renkleri 32-bit tam sayı değerleri olarak sunulur.
### toCmykIcc(int[] pixels) {#toCmykIcc-int---}
```
public static int[] toCmykIcc(int[] pixels)
```


ARGB renklerinden CMYK renklerine, varsayılan profillerle Icc dönüşümü kullanılarak dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pikseller | int[] | ARGB renkleri. |

**Returns:**
int[] - CMYK renkleri 32-bit tam sayı değerleri olarak sunulur.
### toPsdCmykIcc(int[] pixels) {#toPsdCmykIcc-int---}
```
public static int[] toPsdCmykIcc(int[] pixels)
```


Varsayılan profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm. Ters kanal değerleriyle PSD CMYK formatı KCMY bayt sırasını kullanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pikseller | int[] | ARGB renkleri. |

**Returns:**
int[] - Ters kanal değerleriyle KCMY bayt sırasındaki 32-bit tamsayı değerleri olarak sunulan CMYK renkleri.
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.imaging.Color-}
```
public static int toCmykIcc(Color pixel)
```


ARGB renginden CMYK rengine, varsayılan profillerle Icc dönüşümü kullanılarak dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | ARGB rengi. |

**Returns:**
int - CMYK rengi 32-bit tam sayı değeri olarak sunulur.

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

// RGB ve CMYK ICC profillerine giden yolunuzu belirtin.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert RGB to CMYK using custom ICC profiles.");

// toCmykIcc çağrılmadan önce giriş profil akışını sıfırlama imkanı sağlamak için ICC dosyalarından tüm baytları belleğe okuyun.
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

//Çıktı şu şekilde görünür:
//Varsayılan ICC profilleri kullanarak RGB'yi CMYK'ye dönüştür.
//RGB(255,0,0)        => CMYK(0,254,249,15)
//RGB(0,128,0)        => CMYK(247,21,254,85)
//RGB(0,0,255)        => CMYK(254,195,0,134)
//Özel ICC profilleri kullanarak RGB'yi CMYK'ye dönüştür.
//RGB(255,0,0)        => CMYK(0,207,219,0)
//RGB(0,128,0)        => CMYK(238,16,254,80)
//RGB(0,0,255)        => CMYK(242,182,0,0)
```

### toCmykIcc(int argb) {#toCmykIcc-int-}
```
public static int toCmykIcc(int argb)
```


ARGB renginden CMYK rengine, varsayılan profillerle Icc dönüşümü kullanılarak dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argb | int | ARGB rengi. |

**Returns:**
int - CMYK rengi 32-bit tam sayı değeri olarak sunulur.
### toPsdCmykIcc(int argb) {#toPsdCmykIcc-int-}
```
public static int toPsdCmykIcc(int argb)
```


Varsayılan profillerle Icc dönüşümü kullanarak ARGB renginden CMYK rengine dönüşüm. Ters kanal değerleriyle PSD CMYK formatı KCMY bayt sırasını kullanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argb | int | ARGB rengi. |

**Returns:**
int - KCMY bayt sırasında ters kanal değerleriyle sunulan 32-bit tamsayı değeri olarak CMYK rengi.
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.imaging.Color-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


ARGB renginden CMYK rengine, özel profillerle Icc dönüşümü kullanılarak dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | ARGB rengi. |
| rgbIccStream | java.io.InputStream | RGB ICC profilini içeren akış. |
| cmykIccStream | java.io.InputStream | CMYK ICC profilini içeren akış. |

**Returns:**
int - CMYK rengi 32-bit tam sayı değeri olarak sunulur.

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

// RGB ve CMYK ICC profillerine giden yolunuzu belirtin.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert RGB to CMYK using custom ICC profiles.");

// toCmykIcc çağrılmadan önce giriş profil akışını sıfırlama imkanı sağlamak için ICC dosyalarından tüm baytları belleğe okuyun.
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

//Çıktı şu şekilde görünür:
//Varsayılan ICC profilleri kullanarak RGB'yi CMYK'ye dönüştür.
//RGB(255,0,0)        => CMYK(0,254,249,15)
//RGB(0,128,0)        => CMYK(247,21,254,85)
//RGB(0,0,255)        => CMYK(254,195,0,134)
//Özel ICC profilleri kullanarak RGB'yi CMYK'ye dönüştür.
//RGB(255,0,0)        => CMYK(0,207,219,0)
//RGB(0,128,0)        => CMYK(238,16,254,80)
//RGB(0,0,255)        => CMYK(242,182,0,0)
```

### toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream)
```


ARGB renginden CMYK rengine, özel profillerle Icc dönüşümü kullanılarak dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argb | int | ARGB rengi. |
| rgbIccStream | java.io.InputStream | RGB ICC profilini içeren akış. |
| cmykIccStream | java.io.InputStream | CMYK ICC profilini içeren akış. |

**Returns:**
int - CMYK rengi 32-bit tam sayı değeri olarak sunulur.
### toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toPsdCmykIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static int toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


ARGB renginden CMYK rengine, özel profillerle Icc dönüşümü kullanılarak dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| piksel | int | ARGB rengi. |
| rgbIccStream | java.io.InputStream | RGB ICC profilini içeren akış. |
| cmykIccStream | java.io.InputStream | CMYK ICC profilini içeren akış. |

**Returns:**
int - KCMY bayt sırasında ters kanal değerleriyle sunulan 32-bit tamsayı değerleri olarak CMYK renkleri.
