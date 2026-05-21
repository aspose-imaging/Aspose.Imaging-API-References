---
title: "PixelDataFormat"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Формат данных пикселей."
type: docs
weight: 84
url: /ru/java/com.aspose.imaging/pixeldataformat/
---
**Inheritance:**
java.lang.Object
```
public class PixelDataFormat
```

Формат данных пикселя. Это неизменяемый объект.
## Поля

| Поле | Описание |
| --- | --- |
| [Grayscale](#Grayscale) | Получает [PixelDataFormat](../../com.aspose.imaging/pixeldataformat), определённый для 8 бит на пиксель, где 8 бит представляют интенсивность в градациях серого в диапазоне 0‑255. |
| [Grayscale16](#Grayscale16) | Определён для 16 бит на пиксель, где до 16 бит представляют интенсивность в градациях серого. |
## Методы

| Метод | Описание |
| --- | --- |
| [getRgb32Bpp()](#getRgb32Bpp--) | Получает `PixelDataFormat`, определённый для 32 бит на пиксель, где по 8 бит для альфа‑канала, красного, зелёного и синего. |
| [getCmyk()](#getCmyk--) | Получает `PixelDataFormat`, определённый для 32 бит на пиксель, где по 8 бит для голубого, пурпурного, жёлтого и чёрного. |
| [getCmyka()](#getCmyka--) | Получает acmyk. |
| [getRgb24Bpp()](#getRgb24Bpp--) | Получает `PixelDataFormat`, определённый для 24 бит на пиксель, где по 8 бит для альфа‑канала, красного, зелёного и синего, альфа‑канал не определён. |
| [getRgb16Bpp555()](#getRgb16Bpp555--) | Получает `PixelDataFormat`, определённый для 16 бит на пиксель, где по 5 бит для красного, зелёного и синего, альфа‑канал не определён. |
| [getRgb16Bpp565()](#getRgb16Bpp565--) | Получает `PixelDataFormat`, определённый для 16 бит на пиксель, где 5 бит для красного, 6 бит для зелёного и 5 бит для синего, альфа‑канал не определён. |
| [getRgbIndexed8Bpp()](#getRgbIndexed8Bpp--) | Получает `PixelDataFormat`, определённый для индексированного 8‑битного цвета. |
| [getRgbIndexed4Bpp()](#getRgbIndexed4Bpp--) | Получает `PixelDataFormat`, определённый для индексированного 4‑битного цвета. |
| [getRgbIndexed2Bpp()](#getRgbIndexed2Bpp--) | Получает `PixelDataFormat`, определённый для индексированного 2‑битного цвета. |
| [getRgbIndexed1Bpp()](#getRgbIndexed1Bpp--) | Получает `PixelDataFormat`, определённый для индексированного 1‑битного цвета. |
| [getYCbCr()](#getYCbCr--) | Получает `PixelDataFormat`, определённый для 24 бит на пиксель, где по 8 бит для каждого из компонентов яркости (luma), разницы синего (blue-difference) и разницы красного (red-difference). |
| [getYcck()](#getYcck--) | Получает `PixelDataFormat`, определённый для 32 бит на пиксель, где по 8 бит для каждого из компонентов яркости (luma), разницы синего (blue-difference), разницы красного (red-difference) и чёрного хрома. |
| [getRgba32Bpp()](#getRgba32Bpp--) | Получает `PixelDataFormat`, определённый для 32 бит на пиксель, где по 8 бит для альфа‑канала, красного, зелёного и синего. |
| [getRgb24BppPng()](#getRgb24BppPng--) | Получает `PixelDataFormat`, определённый для 24 бит на пиксель, где по 8 бит для альфа‑канала, красного, зелёного и синего, альфа‑канал не определён. |
| [getGrayscaleAlpha()](#getGrayscaleAlpha--) | Получает `PixelDataFormat`, определённый для 16 бит на пиксель, где 8 бит представляют интенсивность в градациях серого в диапазоне 0‑255 и дополнительно 8‑битный альфа‑канал. |
| [getPixelFormat()](#getPixelFormat--) | Получает формат пикселя. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получает количество бит на пиксель. |
| [getChannelsCount()](#getChannelsCount--) | Получает количество каналов. |
| [getChannelBits()](#getChannelBits--) | Получает количество бит для каждого канала. |
| [getCaption()](#getCaption--) | Получает подпись формата данных пикселя. |
| [getGrayscale(int bitsPerSample)](#getGrayscale-int-) | Получает оттенок серого с указанным количеством бит на образец. |
| [getGrayscaleAlpha(int bitsPerSample)](#getGrayscaleAlpha-int-) | Получает цвет GrayscaleAlpha с указанным количеством бит на образец. |
| [getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)](#getGrayscaleAlpha-int-int-) | Получает цвет GrayscaleAlpha с указанным количеством бит на образец. |
| [getRgb(int bitsPerSample)](#getRgb-int-) | Получает цвет RGB с указанным количеством бит на образец. |
| [getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)](#getRgb-int-int-int-) | Получает цвет RGB с указанным количеством бит на образец. |
| [getRgba(int bitsPerSample)](#getRgba-int-) | Получает цвет RGBA с указанным количеством бит на образец. |
| [getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)](#getRgba-int-int-int-int-) | Получает цвет RGBA с указанным количеством бит на образец. |
| [getRgbIndexed(int bitsPerSample)](#getRgbIndexed-int-) | Получает индексированный цвет BGRA с указанным количеством бит на образец. |
| [getBgra(int bitsPerSample)](#getBgra-int-) | Получает цвет BGRA с указанным количеством бит на образец. |
| [getBgr(int bitsPerSample)](#getBgr-int-) | Получает цвет BGR с указанным количеством бит на образец. |
| [getYCbCr(int bitsPerSample)](#getYCbCr-int-) | Получает цвет YCbCr с указанным количеством бит на образец. |
| [getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)](#getYCbCr-int-int-int-) | Получает цвет YCbCr с указанным количеством бит на образец. |
| [getCmyk(int bitsPerSample)](#getCmyk-int-) | Получает цвет CMYK с указанным количеством бит на образец. |
| [getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)](#getCmyk-int-int-int-int-) | Получает цвет CMYK с указанным количеством бит на образец. |
| [getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)](#getCmyka-int-int-int-int-int-) | Получает цвет CMYKA с указанным количеством бит на образец. |
| [getYcck(int bitsPerSample)](#getYcck-int-) | Получает цвет YCCK с указанным количеством бит на образец. |
| [getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)](#getCieLab-int-int-int-) | Получает цвет CIE Lab с указанным количеством бит на образец. |
| [op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Inequality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-) | Возвращает результат неравенства для двух классов `PixelDataFormat`. |
| [op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Equality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-) | Возвращает результат равенства для двух классов `PixelDataFormat`. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный `System.Object` этому экземпляру. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
| [toString()](#toString--) | Возвращает `System.String`, представляющий этот экземпляр. |
### Grayscale {#Grayscale}
```
public static final PixelDataFormat Grayscale
```


Получает [PixelDataFormat](../../com.aspose.imaging/pixeldataformat), определённый для 8 бит на пиксель, где 8 бит представляют интенсивность в градациях серого в диапазоне 0‑255.

Значение: [PixelDataFormat](../../com.aspose.imaging/pixeldataformat), определённый для 8 бит на пиксель, где 8 бит представляют интенсивность оттенка серого в диапазоне 0‑255.

### Grayscale16 {#Grayscale16}
```
public static final PixelDataFormat Grayscale16
```


Определён для 16 бит на пиксель, где до 16 бит представляют интенсивность в градациях серого.

### getRgb32Bpp() {#getRgb32Bpp--}
```
public static PixelDataFormat getRgb32Bpp()
```


Получает `PixelDataFormat`, определённый для 32 бит на пиксель, где по 8 бит для альфа‑канала, красного, зелёного и синего.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getCmyk() {#getCmyk--}
```
public static PixelDataFormat getCmyk()
```


Получает `PixelDataFormat`, определённый для 32 бит на пиксель, где по 8 бит для голубого, пурпурного, жёлтого и чёрного.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.
### getCmyka() {#getCmyka--}
```
public static PixelDataFormat getCmyka()
```


Получает acmyk.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 40 bits per pixel with 8 bits for each of the alpha, cyan, magenta, yellow and black.
### getRgb24Bpp() {#getRgb24Bpp--}
```
public static PixelDataFormat getRgb24Bpp()
```


Получает `PixelDataFormat`, определённый для 24 бит на пиксель, где по 8 бит для альфа‑канала, красного, зелёного и синего, альфа‑канал не определён.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb16Bpp555() {#getRgb16Bpp555--}
```
public static PixelDataFormat getRgb16Bpp555()
```


Получает `PixelDataFormat`, определённый для 16 бит на пиксель, где по 5 бит для красного, зелёного и синего, альфа‑канал не определён.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.
### getRgb16Bpp565() {#getRgb16Bpp565--}
```
public static PixelDataFormat getRgb16Bpp565()
```


Получает `PixelDataFormat`, определённый для 16 бит на пиксель, где 5 бит для красного, 6 бит для зелёного и 5 бит для синего, альфа‑канал не определён.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.
### getRgbIndexed8Bpp() {#getRgbIndexed8Bpp--}
```
public static PixelDataFormat getRgbIndexed8Bpp()
```


Получает `PixelDataFormat`, определённый для индексированных 8 бит на цвет. Индексированное хранение данных пикселей предназначено для обеспечения хранения и извлечения данных везде, где используется цветовая палитра. Используйте с осторожностью, так как может потребоваться преобразование из одной палитры в другую или из RGBA в индексированную цветовую модель.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 8 bit per color.
### getRgbIndexed4Bpp() {#getRgbIndexed4Bpp--}
```
public static PixelDataFormat getRgbIndexed4Bpp()
```


Получает `PixelDataFormat`, определённый для индексированных 4 бит на цвет. Индексированное хранение данных пикселей предназначено для обеспечения хранения и извлечения данных везде, где используется цветовая палитра. Используйте с осторожностью, так как может потребоваться преобразование из одной палитры в другую или из RGBA в индексированную цветовую модель.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 4 bit per color.
### getRgbIndexed2Bpp() {#getRgbIndexed2Bpp--}
```
public static PixelDataFormat getRgbIndexed2Bpp()
```


Получает `PixelDataFormat`, определённый для индексированных 2 бит на цвет. Индексированное хранение данных пикселей предназначено для обеспечения хранения и извлечения данных везде, где используется цветовая палитра. Используйте с осторожностью, так как может потребоваться преобразование из одной палитры в другую или из RGBA в индексированную цветовую модель.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 2 bit per color.
### getRgbIndexed1Bpp() {#getRgbIndexed1Bpp--}
```
public static PixelDataFormat getRgbIndexed1Bpp()
```


Получает `PixelDataFormat`, определённый для индексированных 1 бит на цвет. Индексированное хранение данных пикселей предназначено для обеспечения хранения и извлечения данных везде, где используется цветовая палитра. Используйте с осторожностью, так как может потребоваться преобразование из одной палитры в другую или из RGBA в индексированную цветовую модель.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 1 bit per color.
### getYCbCr() {#getYCbCr--}
```
public static PixelDataFormat getYCbCr()
```


Получает `PixelDataFormat`, определённый для 24 бит на пиксель, где по 8 бит для каждого из компонентов яркости (luma), разницы синего (blue-difference) и разницы красного (red-difference).

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.
### getYcck() {#getYcck--}
```
public static PixelDataFormat getYcck()
```


Получает `PixelDataFormat`, определённый для 32 бит на пиксель, где по 8 бит для каждого из компонентов яркости (luma), разницы синего (blue-difference), разницы красного (red-difference) и чёрного хрома.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.
### getRgba32Bpp() {#getRgba32Bpp--}
```
public static PixelDataFormat getRgba32Bpp()
```


Получает `PixelDataFormat`, определённый для 32 бит на пиксель, где по 8 бит для альфа‑канала, красного, зелёного и синего.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgb24BppPng() {#getRgb24BppPng--}
```
public static PixelDataFormat getRgb24BppPng()
```


Получает `PixelDataFormat`, определённый для 24 бит на пиксель, где по 8 бит для альфа‑канала, красного, зелёного и синего, альфа‑канал не определён.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getGrayscaleAlpha() {#getGrayscaleAlpha--}
```
public static PixelDataFormat getGrayscaleAlpha()
```


Получает `PixelDataFormat`, определённый для 16 бит на пиксель, где 8 бит представляют интенсивность в градациях серого в диапазоне 0‑255 и дополнительно 8‑битный альфа‑канал.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Получает формат пикселя.

**Returns:**
int - Формат пикселя.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Получает количество бит на пиксель.

**Returns:**
int - Количество бит на пиксель.
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Получает количество каналов.

**Returns:**
int - Количество каналов.
### getChannelBits() {#getChannelBits--}
```
public int[] getChannelBits()
```


Получает количество бит для каждого канала.

**Returns:**
int[] - Биты канала.
### getCaption() {#getCaption--}
```
public String getCaption()
```


Получает подпись формата данных пикселя.

**Returns:**
java.lang.String
### getGrayscale(int bitsPerSample) {#getGrayscale-int-}
```
public static PixelDataFormat getGrayscale(int bitsPerSample)
```


Получает оттенок серого с указанным количеством бит на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerSample | int | Количество бит на образец. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The Grayscale color.
### getGrayscaleAlpha(int bitsPerSample) {#getGrayscaleAlpha-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample)
```


Получает цвет GrayscaleAlpha с указанным количеством бит на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerSample | int | Количество бит на образец. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits) {#getGrayscaleAlpha-int-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)
```


Получает цвет GrayscaleAlpha с указанным количеством бит на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerSample | int | Количество бит на образец. |
| alphaChannelBits | int | Количество бит на образец в альфа-канале. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The GrayscaleAlpha color.
### getRgb(int bitsPerSample) {#getRgb-int-}
```
public static PixelDataFormat getRgb(int bitsPerSample)
```


Получает цвет RGB с указанным количеством бит на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerSample | int | Количество бит на образец. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGB color.
### getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel) {#getRgb-int-int-int-}
```
public static PixelDataFormat getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)
```


Получает цвет RGB с указанным количеством бит на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerRedChannel | int | Количество бит на красный канал. |
| bitsPerGreenChannel | int | Количество бит на зелёный канал. |
| bitsPerBlueChannel | int | Количество бит на синий канал. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGB color.
### getRgba(int bitsPerSample) {#getRgba-int-}
```
public static PixelDataFormat getRgba(int bitsPerSample)
```


Получает цвет RGBA с указанным количеством бит на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerSample | int | Количество бит на образец. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGBA color.
### getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel) {#getRgba-int-int-int-int-}
```
public static PixelDataFormat getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)
```


Получает цвет RGBA с указанным количеством бит на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerRedChannel | int | Количество бит на красный канал. |
| bitsPerGreenChannel | int | Количество бит на зелёный канал. |
| bitsPerBlueChannel | int | Количество бит на синий канал. |
| bitsPerAlphaChannel | int | Количество бит на альфа-канал. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGBA color.
### getRgbIndexed(int bitsPerSample) {#getRgbIndexed-int-}
```
public static PixelDataFormat getRgbIndexed(int bitsPerSample)
```


Получает индексированный цвет BGRA с указанным количеством бит на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerSample | int | Количество бит на образец. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGRA color.
### getBgra(int bitsPerSample) {#getBgra-int-}
```
public static PixelDataFormat getBgra(int bitsPerSample)
```


Получает цвет BGRA с указанным количеством бит на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerSample | int | Количество бит на образец. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGRA color.
### getBgr(int bitsPerSample) {#getBgr-int-}
```
public static PixelDataFormat getBgr(int bitsPerSample)
```


Получает цвет BGR с указанным количеством бит на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerSample | int | Количество бит на образец. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGR color.
### getYCbCr(int bitsPerSample) {#getYCbCr-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerSample)
```


Получает цвет YCbCr с указанным количеством бит на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerSample | int | Количество бит на образец. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCbCr color.
### getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr) {#getYCbCr-int-int-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)
```


Получает цвет YCbCr с указанным количеством бит на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerY | int | Количество бит на канал Y. |
| bitsPerCb | int | Количество бит на канал Cb. |
| bitsPerCr | int | Количество бит на канал Cr. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCbCr color.
### getCmyk(int bitsPerSample) {#getCmyk-int-}
```
public static PixelDataFormat getCmyk(int bitsPerSample)
```


Получает цвет CMYK с указанным количеством бит на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerSample | int | Количество бит на образец. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel) {#getCmyk-int-int-int-int-}
```
public static PixelDataFormat getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)
```


Получает цвет CMYK с указанным количеством бит на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerCyanChannel | int | Количество бит на канал циан. |
| bitsPerMagentaChannel | int | Количество бит на канал маджента. |
| bitsPerYellowChannel | int | Количество бит на желтый канал. |
| bitsPerKeyChannel | int | Количество бит на ключевой канал. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel) {#getCmyka-int-int-int-int-int-}
```
public static PixelDataFormat getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)
```


Получает цвет CMYKA с указанным количеством бит на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerCyanChannel | int | Количество бит на канал циан. |
| bitsPerMagentaChannel | int | Количество бит на канал маджента. |
| bitsPerYellowChannel | int | Количество бит на желтый канал. |
| bitsPerKeyChannel | int | Количество бит на ключевой канал. |
| bitsPerAlphaChannel | int | Количество бит на альфа-канал. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getYcck(int bitsPerSample) {#getYcck-int-}
```
public static PixelDataFormat getYcck(int bitsPerSample)
```


Получает цвет YCCK с указанным количеством бит на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerSample | int | Количество бит на образец. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCCK color.
### getCieLab(int bitsPerL, int bitsPerA, int bitsPerB) {#getCieLab-int-int-int-}
```
public static PixelDataFormat getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)
```


Получает цвет CIE Lab с указанным количеством бит на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitsPerL | int | Количество бит на канал L. |
| bitsPerA | int | Количество бит на канал A. |
| bitsPerB | int | Количество бит на канал B. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CIE Lab color.
### op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Inequality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public static boolean op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Возвращает результат неравенства для двух классов `PixelDataFormat`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Первый `PixelDataFormat` для сравнения. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Второй `PixelDataFormat` для сравнения. |

**Returns:**
boolean - true, если оба `pixelFormat1` и `pixelFormat2` содержат неравные данные или один из параметров равен null.
### op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Equality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public static boolean op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Возвращает результат равенства для двух классов `PixelDataFormat`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Первый `PixelDataFormat` для сравнения. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Второй `PixelDataFormat` для сравнения. |

**Returns:**
boolean - true, если оба `pixelFormat1` и `pixelFormat2` содержат одинаковые данные или оба параметра равны null.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный `System.Object` этому экземпляру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект `System.Object` для сравнения с этим экземпляром. |

**Returns:**
boolean - `true`, если указанный `System.Object` равен этому экземпляру; иначе `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра.

**Returns:**
int — хеш-код для этого экземпляра, пригодный для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица.
### toString() {#toString--}
```
public String toString()
```


Возвращает `System.String`, представляющий этот экземпляр.

**Returns:**
java.lang.String - `System.String`, представляющая этот экземпляр.
