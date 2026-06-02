---
title: "PixelDataFormat"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Piksel veri biçimi."
type: docs
weight: 84
url: /tr/java/com.aspose.imaging/pixeldataformat/
---
**Inheritance:**
java.lang.Object
```
public class PixelDataFormat
```

Piksel veri biçimi. Bu değiştirilemez bir nesnedir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Grayscale](#Grayscale) | 8 bit/piksel için tanımlanan ve 0-255 aralığında gri ton yoğunluğunu temsil eden 8 bit içeren [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) öğesini alır. |
| [Grayscale16](#Grayscale16) | 16 bit/piksel için tanımlanmıştır ve gri ton yoğunluğunu temsil eden en fazla 16 bit içerir. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRgb32Bpp()](#getRgb32Bpp--) | Alfa, kırmızı, yeşil ve mavi için her biri 8 bit olan 32 bit/piksel için tanımlanan `PixelDataFormat` öğesini alır. |
| [getCmyk()](#getCmyk--) | Camgöbeği, macenta, sarı ve siyah için her biri 8 bit olan 32 bit/piksel için tanımlanan `PixelDataFormat` öğesini alır. |
| [getCmyka()](#getCmyka--) | acmyk öğesini alır. |
| [getRgb24Bpp()](#getRgb24Bpp--) | Alfa, kırmızı, yeşil ve mavi için her biri 8 bit olan 24 bit/piksel için tanımlanan `PixelDataFormat` öğesini alır, alfa tanımlı değildir. |
| [getRgb16Bpp555()](#getRgb16Bpp555--) | Kırmızı, yeşil ve mavi için her biri 5 bit olan 16 bit/piksel için tanımlanan `PixelDataFormat` öğesini alır, alfa tanımlı değildir. |
| [getRgb16Bpp565()](#getRgb16Bpp565--) | Kırmızı için 5 bit, yeşil için 6 bit ve mavi için 5 bit olan 16 bit/piksel için tanımlanan `PixelDataFormat` öğesini alır, alfa tanımlı değildir. |
| [getRgbIndexed8Bpp()](#getRgbIndexed8Bpp--) | Renk başına indeksli 8 bit için tanımlanan `PixelDataFormat` öğesini alır. |
| [getRgbIndexed4Bpp()](#getRgbIndexed4Bpp--) | Renk başına indeksli 4 bit için tanımlanan `PixelDataFormat` öğesini alır. |
| [getRgbIndexed2Bpp()](#getRgbIndexed2Bpp--) | Renk başına indeksli 2 bit için tanımlanan `PixelDataFormat` öğesini alır. |
| [getRgbIndexed1Bpp()](#getRgbIndexed1Bpp--) | Renk başına indeksli 1 bit için tanımlanan `PixelDataFormat` öğesini alır. |
| [getYCbCr()](#getYCbCr--) | Luma, mavi-fark ve kırmızı-fark renk bileşenleri için her biri 8 bit olan 24 bit/piksel için tanımlanan `PixelDataFormat` öğesini alır. |
| [getYcck()](#getYcck--) | Luma, mavi-fark, kırmızı-fark ve siyah renk bileşenleri için her biri 8 bit olan 32 bit/piksel için tanımlanan `PixelDataFormat` öğesini alır. |
| [getRgba32Bpp()](#getRgba32Bpp--) | Alfa, kırmızı, yeşil ve mavi için her biri 8 bit olan 32 bit/piksel için tanımlanan `PixelDataFormat` öğesini alır. |
| [getRgb24BppPng()](#getRgb24BppPng--) | Alfa, kırmızı, yeşil ve mavi için her biri 8 bit olan 24 bit/piksel için tanımlanan `PixelDataFormat` öğesini alır, alfa tanımlı değildir. |
| [getGrayscaleAlpha()](#getGrayscaleAlpha--) | 0-255 aralığında gri ton yoğunluğunu temsil eden 8 bit ve ek 8 bit alfa bileşeni içeren 16 bit/piksel için tanımlanan `PixelDataFormat` öğesini alır. |
| [getPixelFormat()](#getPixelFormat--) | Piksel biçimini alır. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Piksel başına bit sayısını alır. |
| [getChannelsCount()](#getChannelsCount--) | Kanal sayısını alır. |
| [getChannelBits()](#getChannelBits--) | Her kanal için bit sayısını alır. |
| [getCaption()](#getCaption--) | Piksel veri formatı başlığını alır. |
| [getGrayscale(int bitsPerSample)](#getGrayscale-int-) | Belirtilen örnek başına bit sayısı ile Gri tonlamalı rengi alır. |
| [getGrayscaleAlpha(int bitsPerSample)](#getGrayscaleAlpha-int-) | Belirtilen örnek başına bit sayısı ile Gri tonlamalı Alfa rengini alır. |
| [getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)](#getGrayscaleAlpha-int-int-) | Belirtilen örnek başına bit sayısı ile Gri tonlamalı Alfa rengini alır. |
| [getRgb(int bitsPerSample)](#getRgb-int-) | Belirtilen örnek başına bit sayısı ile RGB rengini alır. |
| [getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)](#getRgb-int-int-int-) | Belirtilen örnek başına bit sayısı ile RGB rengini alır. |
| [getRgba(int bitsPerSample)](#getRgba-int-) | Belirtilen örnek başına bit sayısı ile RGBA rengini alır. |
| [getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)](#getRgba-int-int-int-int-) | Belirtilen örnek başına bit sayısı ile RGBA rengini alır. |
| [getRgbIndexed(int bitsPerSample)](#getRgbIndexed-int-) | Belirtilen örnek başına bit sayısı ile BGRA indeksli rengini alır. |
| [getBgra(int bitsPerSample)](#getBgra-int-) | Belirtilen örnek başına bit sayısı ile BGRA rengini alır. |
| [getBgr(int bitsPerSample)](#getBgr-int-) | Belirtilen örnek başına bit sayısı ile BGR rengini alır. |
| [getYCbCr(int bitsPerSample)](#getYCbCr-int-) | Belirtilen örnek başına bit sayısı ile YCbCr rengini alır. |
| [getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)](#getYCbCr-int-int-int-) | Belirtilen örnek başına bit sayısı ile YCbCr rengini alır. |
| [getCmyk(int bitsPerSample)](#getCmyk-int-) | Belirtilen örnek başına bit sayısı ile CMYK rengini alır. |
| [getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)](#getCmyk-int-int-int-int-) | Belirtilen örnek başına bit sayısı ile CMYK rengini alır. |
| [getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)](#getCmyka-int-int-int-int-int-) | Belirtilen örnek başına bit sayısı ile CMYKA rengini alır. |
| [getYcck(int bitsPerSample)](#getYcck-int-) | Belirtilen örnek başına bit sayısı ile YCCK rengini alır. |
| [getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)](#getCieLab-int-int-int-) | Belirtilen örnek başına bit sayısı ile CIE Lab rengini alır. |
| [op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Inequality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-) | `PixelDataFormat` sınıfları için eşit olmama sonucunu döndürür. |
| [op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Equality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-) | `PixelDataFormat` sınıfları için eşitlik sonucunu döndürür. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen `System.Object`'in bu örnek ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Bu örnek için bir karma kodu döndürür. |
| [toString()](#toString--) | Bu örneği temsil eden bir `System.String` döndürür. |
### Grayscale {#Grayscale}
```
public static final PixelDataFormat Grayscale
```


8 bit/piksel için tanımlanan ve 0-255 aralığında gri ton yoğunluğunu temsil eden 8 bit içeren [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) öğesini alır.

Değer: 0-255 aralığında gri ton yoğunluğunu temsil eden 8 bit ile piksel başına 8 bit olarak tanımlanan [PixelDataFormat](../../com.aspose.imaging/pixeldataformat).

### Grayscale16 {#Grayscale16}
```
public static final PixelDataFormat Grayscale16
```


16 bit/piksel için tanımlanmıştır ve gri ton yoğunluğunu temsil eden en fazla 16 bit içerir.

### getRgb32Bpp() {#getRgb32Bpp--}
```
public static PixelDataFormat getRgb32Bpp()
```


Alfa, kırmızı, yeşil ve mavi için her biri 8 bit olan 32 bit/piksel için tanımlanan `PixelDataFormat` öğesini alır.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getCmyk() {#getCmyk--}
```
public static PixelDataFormat getCmyk()
```


Camgöbeği, macenta, sarı ve siyah için her biri 8 bit olan 32 bit/piksel için tanımlanan `PixelDataFormat` öğesini alır.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.
### getCmyka() {#getCmyka--}
```
public static PixelDataFormat getCmyka()
```


acmyk öğesini alır.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 40 bits per pixel with 8 bits for each of the alpha, cyan, magenta, yellow and black.
### getRgb24Bpp() {#getRgb24Bpp--}
```
public static PixelDataFormat getRgb24Bpp()
```


Alfa, kırmızı, yeşil ve mavi için her biri 8 bit olan 24 bit/piksel için tanımlanan `PixelDataFormat` öğesini alır, alfa tanımlı değildir.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb16Bpp555() {#getRgb16Bpp555--}
```
public static PixelDataFormat getRgb16Bpp555()
```


Kırmızı, yeşil ve mavi için her biri 5 bit olan 16 bit/piksel için tanımlanan `PixelDataFormat` öğesini alır, alfa tanımlı değildir.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.
### getRgb16Bpp565() {#getRgb16Bpp565--}
```
public static PixelDataFormat getRgb16Bpp565()
```


Kırmızı için 5 bit, yeşil için 6 bit ve mavi için 5 bit olan 16 bit/piksel için tanımlanan `PixelDataFormat` öğesini alır, alfa tanımlı değildir.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.
### getRgbIndexed8Bpp() {#getRgbIndexed8Bpp--}
```
public static PixelDataFormat getRgbIndexed8Bpp()
```


`PixelDataFormat`'i renk başına indeksli 8 bit olarak tanımlar. İndeksli piksel veri depolama, renk paletinin kullanıldığı her yerde veri depolamayı ve geri almayı sağlamak amacıyla tasarlanmıştır. Dikkatli kullanın, çünkü bir paletten diğerine veya RGBA'dan indeksli renk modeline dönüşüm gerektirebilir.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 8 bit per color.
### getRgbIndexed4Bpp() {#getRgbIndexed4Bpp--}
```
public static PixelDataFormat getRgbIndexed4Bpp()
```


`PixelDataFormat`'i renk başına indeksli 4 bit olarak tanımlar. İndeksli piksel veri depolama, renk paletinin kullanıldığı her yerde veri depolamayı ve geri almayı sağlamak amacıyla tasarlanmıştır. Dikkatli kullanın, çünkü bir paletten diğerine veya RGBA'dan indeksli renk modeline dönüşüm gerektirebilir.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 4 bit per color.
### getRgbIndexed2Bpp() {#getRgbIndexed2Bpp--}
```
public static PixelDataFormat getRgbIndexed2Bpp()
```


`PixelDataFormat`'i renk başına indeksli 2 bit olarak tanımlar. İndeksli piksel veri depolama, renk paletinin kullanıldığı her yerde veri depolamayı ve geri almayı sağlamak amacıyla tasarlanmıştır. Dikkatli kullanın, çünkü bir paletten diğerine veya RGBA'dan indeksli renk modeline dönüşüm gerektirebilir.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 2 bit per color.
### getRgbIndexed1Bpp() {#getRgbIndexed1Bpp--}
```
public static PixelDataFormat getRgbIndexed1Bpp()
```


`PixelDataFormat`'i renk başına indeksli 1 bit olarak tanımlar. İndeksli piksel veri depolama, renk paletinin kullanıldığı her yerde veri depolamayı ve geri almayı sağlamak amacıyla tasarlanmıştır. Dikkatli kullanın, çünkü bir paletten diğerine veya RGBA'dan indeksli renk modeline dönüşüm gerektirebilir.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 1 bit per color.
### getYCbCr() {#getYCbCr--}
```
public static PixelDataFormat getYCbCr()
```


Luma, mavi-fark ve kırmızı-fark renk bileşenleri için her biri 8 bit olan 24 bit/piksel için tanımlanan `PixelDataFormat` öğesini alır.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.
### getYcck() {#getYcck--}
```
public static PixelDataFormat getYcck()
```


Luma, mavi-fark, kırmızı-fark ve siyah renk bileşenleri için her biri 8 bit olan 32 bit/piksel için tanımlanan `PixelDataFormat` öğesini alır.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.
### getRgba32Bpp() {#getRgba32Bpp--}
```
public static PixelDataFormat getRgba32Bpp()
```


Alfa, kırmızı, yeşil ve mavi için her biri 8 bit olan 32 bit/piksel için tanımlanan `PixelDataFormat` öğesini alır.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgb24BppPng() {#getRgb24BppPng--}
```
public static PixelDataFormat getRgb24BppPng()
```


Alfa, kırmızı, yeşil ve mavi için her biri 8 bit olan 24 bit/piksel için tanımlanan `PixelDataFormat` öğesini alır, alfa tanımlı değildir.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getGrayscaleAlpha() {#getGrayscaleAlpha--}
```
public static PixelDataFormat getGrayscaleAlpha()
```


0-255 aralığında gri ton yoğunluğunu temsil eden 8 bit ve ek 8 bit alfa bileşeni içeren 16 bit/piksel için tanımlanan `PixelDataFormat` öğesini alır.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Piksel biçimini alır.

**Returns:**
int - Piksel formatı.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Piksel başına bit sayısını alır.

**Returns:**
int - Piksel başına bit sayısı.
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Kanal sayısını alır.

**Returns:**
int - Kanal sayısı.
### getChannelBits() {#getChannelBits--}
```
public int[] getChannelBits()
```


Her kanal için bit sayısını alır.

**Returns:**
int[] - Kanal bitleri.
### getCaption() {#getCaption--}
```
public String getCaption()
```


Piksel veri formatı başlığını alır.

**Returns:**
java.lang.String
### getGrayscale(int bitsPerSample) {#getGrayscale-int-}
```
public static PixelDataFormat getGrayscale(int bitsPerSample)
```


Belirtilen örnek başına bit sayısı ile Gri tonlamalı rengi alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerSample | int | Örnek başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The Grayscale color.
### getGrayscaleAlpha(int bitsPerSample) {#getGrayscaleAlpha-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample)
```


Belirtilen örnek başına bit sayısı ile Gri tonlamalı Alfa rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerSample | int | Örnek başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits) {#getGrayscaleAlpha-int-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)
```


Belirtilen örnek başına bit sayısı ile Gri tonlamalı Alfa rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerSample | int | Örnek başına bit sayısı. |
| alphaChannelBits | int | Alfa kanaldaki örnek başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The GrayscaleAlpha color.
### getRgb(int bitsPerSample) {#getRgb-int-}
```
public static PixelDataFormat getRgb(int bitsPerSample)
```


Belirtilen örnek başına bit sayısı ile RGB rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerSample | int | Örnek başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGB color.
### getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel) {#getRgb-int-int-int-}
```
public static PixelDataFormat getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)
```


Belirtilen örnek başına bit sayısı ile RGB rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerRedChannel | int | Kırmızı kanal başına bit sayısı. |
| bitsPerGreenChannel | int | Yeşil kanal başına bit sayısı. |
| bitsPerBlueChannel | int | Mavi kanal başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGB color.
### getRgba(int bitsPerSample) {#getRgba-int-}
```
public static PixelDataFormat getRgba(int bitsPerSample)
```


Belirtilen örnek başına bit sayısı ile RGBA rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerSample | int | Örnek başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGBA color.
### getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel) {#getRgba-int-int-int-int-}
```
public static PixelDataFormat getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)
```


Belirtilen örnek başına bit sayısı ile RGBA rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerRedChannel | int | Kırmızı kanal başına bit sayısı. |
| bitsPerGreenChannel | int | Yeşil kanal başına bit sayısı. |
| bitsPerBlueChannel | int | Mavi kanal başına bit sayısı. |
| bitsPerAlphaChannel | int | Alfa kanal başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGBA color.
### getRgbIndexed(int bitsPerSample) {#getRgbIndexed-int-}
```
public static PixelDataFormat getRgbIndexed(int bitsPerSample)
```


Belirtilen örnek başına bit sayısı ile BGRA indeksli rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerSample | int | Örnek başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGRA color.
### getBgra(int bitsPerSample) {#getBgra-int-}
```
public static PixelDataFormat getBgra(int bitsPerSample)
```


Belirtilen örnek başına bit sayısı ile BGRA rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerSample | int | Örnek başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGRA color.
### getBgr(int bitsPerSample) {#getBgr-int-}
```
public static PixelDataFormat getBgr(int bitsPerSample)
```


Belirtilen örnek başına bit sayısı ile BGR rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerSample | int | Örnek başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGR color.
### getYCbCr(int bitsPerSample) {#getYCbCr-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerSample)
```


Belirtilen örnek başına bit sayısı ile YCbCr rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerSample | int | Örnek başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCbCr color.
### getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr) {#getYCbCr-int-int-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)
```


Belirtilen örnek başına bit sayısı ile YCbCr rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerY | int | Y kanal başına bit sayısı. |
| bitsPerCb | int | Cb kanal başına bit sayısı. |
| bitsPerCr | int | Cr kanal başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCbCr color.
### getCmyk(int bitsPerSample) {#getCmyk-int-}
```
public static PixelDataFormat getCmyk(int bitsPerSample)
```


Belirtilen örnek başına bit sayısı ile CMYK rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerSample | int | Örnek başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel) {#getCmyk-int-int-int-int-}
```
public static PixelDataFormat getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)
```


Belirtilen örnek başına bit sayısı ile CMYK rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerCyanChannel | int | Cyan kanal başına bit sayısı. |
| bitsPerMagentaChannel | int | Magenta kanal başına bit sayısı. |
| bitsPerYellowChannel | int | Sarı kanal başına bit sayısı. |
| bitsPerKeyChannel | int | Anahtar kanal başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel) {#getCmyka-int-int-int-int-int-}
```
public static PixelDataFormat getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)
```


Belirtilen örnek başına bit sayısı ile CMYKA rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerCyanChannel | int | Cyan kanal başına bit sayısı. |
| bitsPerMagentaChannel | int | Magenta kanal başına bit sayısı. |
| bitsPerYellowChannel | int | Sarı kanal başına bit sayısı. |
| bitsPerKeyChannel | int | Anahtar kanal başına bit sayısı. |
| bitsPerAlphaChannel | int | Alfa kanal başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getYcck(int bitsPerSample) {#getYcck-int-}
```
public static PixelDataFormat getYcck(int bitsPerSample)
```


Belirtilen örnek başına bit sayısı ile YCCK rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerSample | int | Örnek başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCCK color.
### getCieLab(int bitsPerL, int bitsPerA, int bitsPerB) {#getCieLab-int-int-int-}
```
public static PixelDataFormat getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)
```


Belirtilen örnek başına bit sayısı ile CIE Lab rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitsPerL | int | L kanalı başına bit sayısı. |
| bitsPerA | int | A kanalı başına bit sayısı. |
| bitsPerB | int | B kanalı başına bit sayısı. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CIE Lab color.
### op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Inequality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public static boolean op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


`PixelDataFormat` sınıfları için eşit olmama sonucunu döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Karşılaştırılacak ilk `PixelDataFormat`. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Karşılaştırılacak ikinci `PixelDataFormat`. |

**Returns:**
boolean - `pixelFormat1` ve `pixelFormat2` her ikisi de eşit olmayan veri içeriyorsa veya parametrelerden biri null ise True.
### op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Equality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public static boolean op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


`PixelDataFormat` sınıfları için eşitlik sonucunu döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Karşılaştırılacak ilk `PixelDataFormat`. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Karşılaştırılacak ikinci `PixelDataFormat`. |

**Returns:**
boolean - `pixelFormat1` ve `pixelFormat2` her ikisi de eşit veri içeriyorsa veya her iki parametre de null ise True.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen `System.Object`'in bu örnek ile eşit olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnek ile karşılaştırılacak `System.Object`. |

**Returns:**
boolean - belirtilen `System.Object` bu örnek ile eşitse `true`; aksi takdirde `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için bir karma kodu döndürür.

**Returns:**
int - Bu örnek için bir karma kodu, karma algoritmaları ve hash tablosu gibi veri yapılarında kullanılmaya uygundur.
### toString() {#toString--}
```
public String toString()
```


Bu örneği temsil eden bir `System.String` döndürür.

**Returns:**
java.lang.String - Bu örneği temsil eden bir `System.String`.
