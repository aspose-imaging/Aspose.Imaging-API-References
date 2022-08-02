---
title: PixelDataFormat
second_title: Справочник по Aspose.Imaging for .NET API
description: Формат данных пикселей. Это неизменяемый объект.
type: docs
weight: 10720
url: /ru/net/aspose.imaging/pixeldataformat/
---
## PixelDataFormat class

Формат данных пикселей. Это неизменяемый объект.

```csharp
public class PixelDataFormat
```

## Характеристики

| Имя | Описание |
| --- | --- |
| static [Cmyk](../../aspose.imaging/pixeldataformat/cmyk) { get; } | Получает[`PixelDataFormat`](../pixeldataformat) определяется для 32 бит на пиксель с 8 битами для каждого из голубого, пурпурного, желтого и черного. |
| static [Cmyka](../../aspose.imaging/pixeldataformat/cmyka) { get; } | Получает акмык. |
| static [Grayscale](../../aspose.imaging/pixeldataformat/grayscale) { get; } | Получает[`PixelDataFormat`](../pixeldataformat)определяется для 8 бит на пиксель, где 8 бит представляют интенсивность оттенков серого в интервале 0-255. |
| static [GrayscaleAlpha](../../aspose.imaging/pixeldataformat/grayscalealpha) { get; } | Получает[`PixelDataFormat`](../pixeldataformat) определено для 16 бит на пиксель с 8 битами, представляющими интенсивность оттенков серого в интервале 0–255, и дополнительным 8-битным альфа-компонентом. |
| static [Rgb16Bpp555](../../aspose.imaging/pixeldataformat/rgb16bpp555) { get; } | Получает[`PixelDataFormat`](../pixeldataformat) определено для 16 бит на пиксель с 5 битами для каждого из красного, зеленого и синего, альфа не определена. |
| static [Rgb16Bpp565](../../aspose.imaging/pixeldataformat/rgb16bpp565) { get; } | Получает[`PixelDataFormat`](../pixeldataformat) определяется для 16 бит на пиксель с 5 битами для красного, 6 битами для зеленого и 5 битами для синего, альфа не определена. |
| static [Rgb24Bpp](../../aspose.imaging/pixeldataformat/rgb24bpp) { get; } | Получает[`PixelDataFormat`](../pixeldataformat) определяется для 24 бит на пиксель с 8 битами для каждого из альфа, красного, зеленого и синего, альфа не определен. |
| static [Rgb24BppPng](../../aspose.imaging/pixeldataformat/rgb24bpppng) { get; } | Получает[`PixelDataFormat`](../pixeldataformat) определяется для 24 бит на пиксель с 8 битами для каждого из альфа, красного, зеленого и синего, альфа не определен. |
| static [Rgb32Bpp](../../aspose.imaging/pixeldataformat/rgb32bpp) { get; } | Получает[`PixelDataFormat`](../pixeldataformat) определяется для 32 бит на пиксель с 8 битами для каждого из альфа, красного, зеленого и синего. |
| static [Rgba32Bpp](../../aspose.imaging/pixeldataformat/rgba32bpp) { get; } | Получает[`PixelDataFormat`](../pixeldataformat) определяется для 32 бит на пиксель с 8 битами для каждого из альфа, красного, зеленого и синего. |
| static [RgbIndexed1Bpp](../../aspose.imaging/pixeldataformat/rgbindexed1bpp) { get; } | Получает[`PixelDataFormat`](../pixeldataformat) определено для индексированного 1 бита на цвет. Хранилище данных индексированного пикселя предназначено для хранения и извлечения данных везде, где используется цветовая палитра. Используйте с осторожностью, поскольку может потребоваться преобразование из одной палитры в другую или из RGBA в индексированную цветовую модель . |
| static [RgbIndexed2Bpp](../../aspose.imaging/pixeldataformat/rgbindexed2bpp) { get; } | Получает[`PixelDataFormat`](../pixeldataformat)определено для индексированного 2 бита на цвет. Хранилище данных индексированного пикселя предназначено для хранения и извлечения данных везде, где используется цветовая палитра. Используйте с осторожностью, поскольку может потребоваться преобразование из одной палитры в другую или из RGBA в индексированную цветовую модель . |
| static [RgbIndexed4Bpp](../../aspose.imaging/pixeldataformat/rgbindexed4bpp) { get; } | Получает[`PixelDataFormat`](../pixeldataformat) определено для индексированных 4 бит на цвет. Хранилище данных индексированных пикселей предназначено для хранения и извлечения данных везде, где используется цветовая палитра. Используйте с осторожностью, поскольку может потребоваться преобразование из одной палитры в другую или из RGBA в индексированную цветовую модель . |
| static [RgbIndexed8Bpp](../../aspose.imaging/pixeldataformat/rgbindexed8bpp) { get; } | Получает[`PixelDataFormat`](../pixeldataformat)определено для индексированных 8 бит на цвет. Хранилище данных индексированных пикселей предназначено для хранения и извлечения данных везде, где используется цветовая палитра. Используйте с осторожностью, поскольку может потребоваться преобразование из одной палитры в другую или из RGBA в индексированную цветовую модель . |
| static [YCbCr](../../aspose.imaging/pixeldataformat/ycbcr) { get; } | Получает[`PixelDataFormat`](../pixeldataformat) определяется для 24 бит на пиксель с 8 битами для каждого из компонентов яркости, синего и красного контраста цветности. |
| static [Ycck](../../aspose.imaging/pixeldataformat/ycck) { get; } | Получает[`PixelDataFormat`](../pixeldataformat) определяется для 32 бит на пиксель с 8 битами для каждого компонента яркости, синего, красного и черного цветных компонентов. |
| [BitsPerPixel](../../aspose.imaging/pixeldataformat/bitsperpixel) { get; } | Получает количество бит на пиксель. |
| [Caption](../../aspose.imaging/pixeldataformat/caption) { get; } | Получает заголовок формата пиксельных данных. |
| [ChannelBits](../../aspose.imaging/pixeldataformat/channelbits) { get; } | Получает количество битов для каждого канала. |
| [ChannelsCount](../../aspose.imaging/pixeldataformat/channelscount) { get; } | Получает количество каналов. |
| [PixelFormat](../../aspose.imaging/pixeldataformat/pixelformat) { get; } | Получает формат пикселей. |

## Методы

| Имя | Описание |
| --- | --- |
| static [GetBgr](../../aspose.imaging/pixeldataformat/getbgr)(int) | Получает цвет BGR с указанным количеством битов на выборку. |
| static [GetBgra](../../aspose.imaging/pixeldataformat/getbgra)(int) | Получает цвет BGRA с указанным количеством битов на выборку. |
| static [GetCieLab](../../aspose.imaging/pixeldataformat/getcielab)(int, int, int) | Получает цвет CIE Lab с указанным количеством битов на выборку. |
| static [GetCmyk](../../aspose.imaging/pixeldataformat/getcmyk#getcmyk)(int) | Получает цвет CMYK с указанным количеством битов на образец. |
| static [GetCmyk](../../aspose.imaging/pixeldataformat/getcmyk#getcmyk_1)(int, int, int, int) | Получает цвет CMYK с указанным количеством битов на образец. |
| static [GetCmyka](../../aspose.imaging/pixeldataformat/getcmyka)(int, int, int, int, int) | Получает цвет CMYKA с указанным количеством битов на образец. |
| static [GetGrayscale](../../aspose.imaging/pixeldataformat/getgrayscale)(int) | Получает цвет в градациях серого с указанным количеством битов на выборку. |
| static [GetGrayscaleAlpha](../../aspose.imaging/pixeldataformat/getgrayscalealpha#getgrayscalealpha)(int) | Получает цвет GrayscaleAlpha с указанным количеством битов на выборку. |
| static [GetGrayscaleAlpha](../../aspose.imaging/pixeldataformat/getgrayscalealpha#getgrayscalealpha_1)(int, int) | Получает цвет GrayscaleAlpha с указанным количеством битов на выборку. |
| static [GetRgb](../../aspose.imaging/pixeldataformat/getrgb#getrgb)(int) | Получает цвет RGB с указанным количеством битов на выборку. |
| static [GetRgb](../../aspose.imaging/pixeldataformat/getrgb#getrgb_1)(int, int, int) | Получает цвет RGB с указанным количеством битов на выборку. |
| static [GetRgba](../../aspose.imaging/pixeldataformat/getrgba#getrgba)(int) | Получает цвет RGBA с указанным количеством битов на выборку. |
| static [GetRgba](../../aspose.imaging/pixeldataformat/getrgba#getrgba_1)(int, int, int, int) | Получает цвет RGBA с указанным количеством битов на выборку. |
| static [GetRgbIndexed](../../aspose.imaging/pixeldataformat/getrgbindexed)(int) | Получает индексированный BGRA цвет с указанным количеством битов на выборку. |
| static [GetYCbCr](../../aspose.imaging/pixeldataformat/getycbcr#getycbcr)(int) | Получает цвет YCbCr с указанным количеством битов на выборку. |
| static [GetYCbCr](../../aspose.imaging/pixeldataformat/getycbcr#getycbcr_1)(int, int, int) | Получает цвет YCbCr с указанным количеством битов на выборку. |
| static [GetYcck](../../aspose.imaging/pixeldataformat/getycck)(int) | Получает цвет YCCK с указанным количеством битов на выборку. |
| override [Equals](../../aspose.imaging/pixeldataformat/equals)(object) | Определяет, является ли указанныйObject равен этому экземпляру. |
| override [GetHashCode](../../aspose.imaging/pixeldataformat/gethashcode)() | Возвращает хэш-код для этого экземпляра. |
| override [ToString](../../aspose.imaging/pixeldataformat/tostring)() | ВозвращаетString который представляет этот экземпляр. |
| [operator ==](../../aspose.imaging/pixeldataformat/op_equality) | Возвращает результат равенства для двух[`PixelDataFormat`](../pixeldataformat) классы. |
| [operator !=](../../aspose.imaging/pixeldataformat/op_inequality) | Возвращает результат неравноправия для двух[`PixelDataFormat`](../pixeldataformat) классы. |

### Смотрите также

* пространство имен [Aspose.Imaging](../../aspose.imaging)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
