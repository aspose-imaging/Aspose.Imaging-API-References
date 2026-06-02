---
title: "CmykColor"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Pikselin CMYK rengi."
type: docs
weight: 18
url: /tr/java/com.aspose.imaging/cmykcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class CmykColor extends Struct<CmykColor>
```

Pikselin CMYK rengi.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CmykColor()](#CmykColor--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEmpty()](#getEmpty--) | Boş olanı alır. |
| [fromParams(int cyan, int magenta, int yellow, int black)](#fromParams-int-int-int-int-) | `CmykColor` yapısını 32 bit cyan, magenta, yellow ve black değerlerinden oluşturur. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | 32 bit ARGB renginden CMYKColor'a dönüşüm. |
| [toColor(CmykColor[] cmykPixels)](#toColor-com.aspose.imaging.CmykColor---) | CMYKColor'dan Color'a, varsayılan profillerle icc dönüşümü kullanılarak yapılan dönüşüm. |
| [toArgb32(CmykColor[] cmykPixels)](#toArgb32-com.aspose.imaging.CmykColor---) | CMYKColor'dan 32 bit ARGB Color'a, varsayılan profillerle icc dönüşümü kullanılarak yapılan dönüşüm. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | 32 bit ARGB'den CMYKColor'a dönüşüm. |
| [toColor(CmykColor cmykPixel)](#toColor-com.aspose.imaging.CmykColor-) | CMYKColor'dan Color'a dönüşüm. |
| [toColorIcc(CmykColor[] cmykPixels)](#toColorIcc-com.aspose.imaging.CmykColor---) | CMYKColor'dan Color'a, varsayılan profillerle icc dönüşümü kullanılarak yapılan dönüşüm. |
| [toColorIcc(CmykColor cmykPixel)](#toColorIcc-com.aspose.imaging.CmykColor-) | CMYKColor'dan Color'a, varsayılan profillerle icc dönüşümü kullanılarak yapılan dönüşüm. |
| [toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.imaging.CmykColor---java.io.InputStream-java.io.InputStream-) | CMYKColor'dan Color'a icc dönüşümü kullanılarak yapılan dönüşüm. |
| [toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.imaging.CmykColor-java.io.InputStream-java.io.InputStream-) | CMYKColor'dan Color'a icc dönüşümü kullanılarak yapılan dönüşüm. |
| [isEquals(CmykColor obj1, CmykColor obj2)](#isEquals-com.aspose.imaging.CmykColor-com.aspose.imaging.CmykColor-) |  |
| [getC()](#getC--) | Bu `com.com.aspose.imaging.Color` yapısının cyan bileşen değerini alır. |
| [getM()](#getM--) | Bu `com.com.aspose.imaging.Color` yapısının magenta bileşen değerini alır. |
| [getY()](#getY--) | Bu `com.com.aspose.imaging.Color` yapısının yellow bileşen değerini alır. |
| [getK()](#getK--) | Bu `com.com.aspose.imaging.Color` yapısının black bileşen değerini alır. |
| [isEmpty()](#isEmpty--) | Bu `com.com.aspose.imaging.Color` yapısının başlatılmamış olup olmadığını gösteren bir değer alır. |
| [hashCode()](#hashCode--) | Hash kodunu al. |
| [toValue()](#toValue--) | Değere dön. |
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


Boş olanı alır.

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor)
### fromParams(int cyan, int magenta, int yellow, int black) {#fromParams-int-int-int-int-}
```
public static CmykColor fromParams(int cyan, int magenta, int yellow, int black)
```


32 bit cyan, magenta, yellow ve black değerlerinden bir `CmykColor` yapısı oluşturur. Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili CmykColorHelper\#fromComponents(int, int, int, int) kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| camgöbeği | int | Camgöbeği bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| macenta | int | Macenta bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| sarı | int | Sarı bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| siyah | int | Siyah bileşeni. Geçerli değerler 0 ile 255 arasındadır. |

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor) - The `CmykColor`.
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static CmykColor[] toCmyk(int[] argbPixels)
```


32 bit ARGB renginden CMYKColor'a dönüşüm. Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili `CmykColorHelper.toCmyk(int[])` kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argbPixels | int[] | 32 bit ARGB formatındaki pikseller. |

**Returns:**
com.aspose.imaging.CmykColor[] - [CmykColor](../../com.aspose.imaging/cmykcolor)[]
### toColor(CmykColor[] cmykPixels) {#toColor-com.aspose.imaging.CmykColor---}
```
public static Color[] toColor(CmykColor[] cmykPixels)
```


CMYKColor'dan Color'a, varsayılan profillerle icc dönüşümü kullanarak dönüşüm. Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili [CmykColorHelper.toArgb(int)](../../com.aspose.imaging/cmykcolorhelper\#toArgb-int-)\} kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | CMYK formatındaki CMYKColor tipindeki pikseller. |

**Returns:**
com.aspose.imaging.Color[] - ARGB renklerinin dizisi.
### toArgb32(CmykColor[] cmykPixels) {#toArgb32-com.aspose.imaging.CmykColor---}
```
public static int[] toArgb32(CmykColor[] cmykPixels)
```


CMYKColor'dan 32 bit ARGB Color'a, varsayılan profillerle icc dönüşümü kullanarak dönüşüm. Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili `CmykColorHelper.toArgb32(int[])` kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | CMYK formatındaki CMYKColor tipindeki pikseller. |

**Returns:**
int[] - 32 bit ARGB renginin dizisi.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static CmykColor toCmyk(int argbPixel)
```


32 bit ARGB'den CMYKColor'a dönüşüm. Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili `CmykColorHelper.toCmyk(int)` kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argbPixel | int | 32 bit ARGB formatındaki piksel. |

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor) - The [CmykColor](../../com.aspose.imaging/cmykcolor).
### toColor(CmykColor cmykPixel) {#toColor-com.aspose.imaging.CmykColor-}
```
public static Color toColor(CmykColor cmykPixel)
```


CMYKColor'dan Color'a dönüşüm. Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili `CmykColorHelper.toArgb(int)` kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | CMYK formatındaki CMYKColor tipindeki pikseller. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor[] cmykPixels) {#toColorIcc-com.aspose.imaging.CmykColor---}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels)
```


CMYKColor'dan Color'a, varsayılan profillerle icc dönüşümü kullanarak dönüşüm. Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili CmykColorHelper\#toArgbIcc(int[]) kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | CMYK formatındaki CMYKColor tipindeki pikseller. |

**Returns:**
com.aspose.imaging.Color[] - `com.com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor cmykPixel) {#toColorIcc-com.aspose.imaging.CmykColor-}
```
public static Color toColorIcc(CmykColor cmykPixel)
```


CMYKColor'dan Color'a, varsayılan profillerle icc dönüşümü kullanarak dönüşüm. Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili `CmykColorHelper.toArgbIcc(int)` kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | CMYK formatındaki CMYKColor tipindeki piksel. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `Color`.
### toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.imaging.CmykColor---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


CMYKColor'dan Color'a icc dönüşümü kullanarak dönüşüm. Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili `CmykColorHelper.toArgbIcc(int[], InputStream, InputStream)` kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | CMYK formatındaki CMYKColor tipindeki pikseller. |
| cmykIccStream | java.io.InputStream | icc cmyk profilini içeren akış. |
| rgbIccStream | java.io.InputStream | icc rgb profilini içeren akış. |

**Returns:**
com.aspose.imaging.Color[] - `com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.imaging.CmykColor-java.io.InputStream-java.io.InputStream-}
```
public static Color toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


CMYKColor'dan Color'a icc dönüşümü kullanarak dönüşüm. Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili `CmykColorHelper.toArgbIcc(int, Stream, Stream)` kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | CMYK formatındaki CMYKColor tipindeki piksel. |
| cmykIccStream | java.io.InputStream | icc cmyk profilini içeren akış. |
| rgbIccStream | java.io.InputStream | icc rgb profilini içeren akış. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `Color`.
### isEquals(CmykColor obj1, CmykColor obj2) {#isEquals-com.aspose.imaging.CmykColor-com.aspose.imaging.CmykColor-}
```
public static boolean isEquals(CmykColor obj1, CmykColor obj2)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj1 | [CmykColor](../../com.aspose.imaging/cmykcolor) |  |
| obj2 | [CmykColor](../../com.aspose.imaging/cmykcolor) |  |

**Returns:**
boolean
### getC() {#getC--}
```
public byte getC()
```


Bu `com.com.aspose.imaging.Color` yapısının cyan bileşen değerini alır.

**Returns:**
byte - Bu `com.com.aspose.imaging.Color` nesnesinin cyan bileşen değeri.
### getM() {#getM--}
```
public byte getM()
```


Bu `com.com.aspose.imaging.Color` yapısının magenta bileşen değerini alır.

**Returns:**
byte - Bu `com.com.aspose.imaging.Color` nesnesinin magenta bileşen değeri.
### getY() {#getY--}
```
public byte getY()
```


Bu `com.com.aspose.imaging.Color` yapısının yellow bileşen değerini alır.

**Returns:**
byte - Bu `com.com.aspose.imaging.Color` nesnesinin yellow bileşen değeri.
### getK() {#getK--}
```
public byte getK()
```


Bu `com.com.aspose.imaging.Color` yapısının black bileşen değerini alır.

Değer: Bu `com.com.aspose.imaging.Color` nesnesinin black bileşen değeri.

**Returns:**
byte
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Bu `com.com.aspose.imaging.Color` yapısının başlatılmamış olup olmadığını gösteren bir değer alır.

**Returns:**
boolean - Bu özellik, renk başlatılmamışsa true; aksi takdirde false döndürür.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hash kodunu al.

**Returns:**
int - Bu `int`.
### toValue() {#toValue--}
```
public long toValue()
```


Değere dön.

**Returns:**
long - Uzun CMYK değeri.
### CloneTo(CmykColor that) {#CloneTo-com.aspose.imaging.CmykColor-}
```
public void CloneTo(CmykColor that)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
