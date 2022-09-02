---
title: PixelDataFormat
second_title: Aspose.Imaging for .NET API Referansı
description: Piksel veri biçimi. Bu değişmez bir nesnedir.
type: docs
weight: 10720
url: /tr/net/aspose.imaging/pixeldataformat/
---
## PixelDataFormat class

Piksel veri biçimi. Bu değişmez bir nesnedir.

```csharp
public class PixelDataFormat
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| static [Cmyk](../../aspose.imaging/pixeldataformat/cmyk) { get; } | [`PixelDataFormat`](../pixeldataformat) camgöbeği, macenta, sarı ve siyahın her biri için 8 bit ile piksel başına 32 bit için tanımlanmıştır. |
| static [Cmyka](../../aspose.imaging/pixeldataformat/cmyka) { get; } | Acmyk'yi alır. |
| static [Grayscale](../../aspose.imaging/pixeldataformat/grayscale) { get; } | [`PixelDataFormat`](../pixeldataformat)0-255 aralığında gri tonlama yoğunluğunu temsil eden 8 bit ile piksel başına 8 bit için tanımlanmıştır. |
| static [GrayscaleAlpha](../../aspose.imaging/pixeldataformat/grayscalealpha) { get; } | [`PixelDataFormat`](../pixeldataformat) 0-255 aralığında gri tonlama yoğunluğunu temsil eden 8 bit ve ek 8 bit alfa bileşeni ile piksel başına 16 bit için tanımlanmıştır. |
| static [Rgb16Bpp555](../../aspose.imaging/pixeldataformat/rgb16bpp555) { get; } | [`PixelDataFormat`](../pixeldataformat) kırmızı, yeşil ve mavinin her biri için 5 bit olmak üzere piksel başına 16 bit için tanımlanmıştır, alfa tanımlanmamıştır. |
| static [Rgb16Bpp565](../../aspose.imaging/pixeldataformat/rgb16bpp565) { get; } | [`PixelDataFormat`](../pixeldataformat) kırmızı için 5 bit, yeşil için 6 bit ve mavi için 5 bit olmak üzere piksel başına 16 bit için tanımlanmıştır, alfa tanımlanmamıştır. |
| static [Rgb24Bpp](../../aspose.imaging/pixeldataformat/rgb24bpp) { get; } | [`PixelDataFormat`](../pixeldataformat) alfa, kırmızı, yeşil ve mavinin her biri için 8 bit olmak üzere piksel başına 24 bit için tanımlanmıştır, alfa tanımlanmamıştır. |
| static [Rgb24BppPng](../../aspose.imaging/pixeldataformat/rgb24bpppng) { get; } | [`PixelDataFormat`](../pixeldataformat) alfa, kırmızı, yeşil ve mavinin her biri için 8 bit olmak üzere piksel başına 24 bit için tanımlanmıştır, alfa tanımlanmamıştır. |
| static [Rgb32Bpp](../../aspose.imaging/pixeldataformat/rgb32bpp) { get; } | [`PixelDataFormat`](../pixeldataformat) alfa, kırmızı, yeşil ve mavinin her biri için 8 bit ile piksel başına 32 bit için tanımlanmıştır. |
| static [Rgba32Bpp](../../aspose.imaging/pixeldataformat/rgba32bpp) { get; } | [`PixelDataFormat`](../pixeldataformat) alfa, kırmızı, yeşil ve mavinin her biri için 8 bit ile piksel başına 32 bit için tanımlanmıştır. |
| static [RgbIndexed1Bpp](../../aspose.imaging/pixeldataformat/rgbindexed1bpp) { get; } | [`PixelDataFormat`](../pixeldataformat) her renk için indekslenmiş 1 bit için tanımlanmıştır. İndekslenmiş piksel veri depolamasının amacı, renk paletinin kullanıldığı her yerde veri depolamaya ve almaya izin vermektir. Dikkatli kullanın, çünkü bir paletten diğerine veya RGBA'dan indekslenmiş renk modeline dönüştürme gerektirebilir . |
| static [RgbIndexed2Bpp](../../aspose.imaging/pixeldataformat/rgbindexed2bpp) { get; } | [`PixelDataFormat`](../pixeldataformat)dizine alınmış renk başına 2 bit için tanımlanmıştır. Dizine alınmış piksel veri depolaması, renk paletinin kullanıldığı her yerde veri depolamasına ve alınmasına izin vermek için tasarlanmıştır. Dikkatli kullanın, çünkü bir paletten diğerine veya RGBA'dan dizinlenmiş renk modeline dönüştürme gerektirebilir . |
| static [RgbIndexed4Bpp](../../aspose.imaging/pixeldataformat/rgbindexed4bpp) { get; } | [`PixelDataFormat`](../pixeldataformat) her renk için indekslenmiş 4 bit için tanımlanmıştır. İndekslenmiş piksel veri depolamasının amacı, renk paletinin kullanıldığı her yerde veri depolamaya ve almaya izin vermektir. Dikkatli kullanın, çünkü bir paletten diğerine veya RGBA'dan indekslenmiş renk modeline dönüştürme gerektirebilir . |
| static [RgbIndexed8Bpp](../../aspose.imaging/pixeldataformat/rgbindexed8bpp) { get; } | [`PixelDataFormat`](../pixeldataformat)her renk için indekslenmiş 8 bit için tanımlanmıştır. İndekslenmiş piksel veri depolaması, renk paletinin kullanıldığı her yerde veri depolamaya ve almaya izin vermeyi amaçlar. Dikkatli kullanın, çünkü bir paletten diğerine veya RGBA'dan indekslenmiş renk modeline dönüştürme gerektirebilir . |
| static [YCbCr](../../aspose.imaging/pixeldataformat/ycbcr) { get; } | [`PixelDataFormat`](../pixeldataformat) luma, mavi fark ve kırmızı fark kroma bileşenlerinin her biri için 8 bit ile piksel başına 24 bit için tanımlanmıştır. |
| static [Ycck](../../aspose.imaging/pixeldataformat/ycck) { get; } | [`PixelDataFormat`](../pixeldataformat) luma, mavi fark, kırmızı fark ve siyah renk bileşenlerinin her biri için 8 bit ile piksel başına 32 bit için tanımlanmıştır. |
| [BitsPerPixel](../../aspose.imaging/pixeldataformat/bitsperpixel) { get; } | Piksel başına bitleri alır. |
| [Caption](../../aspose.imaging/pixeldataformat/caption) { get; } | Piksel veri biçimi başlığını alır. |
| [ChannelBits](../../aspose.imaging/pixeldataformat/channelbits) { get; } | Her kanal için bit sayısını alır. |
| [ChannelsCount](../../aspose.imaging/pixeldataformat/channelscount) { get; } | Kanal sayısını alır. |
| [PixelFormat](../../aspose.imaging/pixeldataformat/pixelformat) { get; } | Piksel biçimini alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [GetBgr](../../aspose.imaging/pixeldataformat/getbgr)(int) | Örnek başına belirli sayıda bit ile BGR rengini alır. |
| static [GetBgra](../../aspose.imaging/pixeldataformat/getbgra)(int) | Örnek başına belirli sayıda bit ile BGRA rengini alır. |
| static [GetCieLab](../../aspose.imaging/pixeldataformat/getcielab)(int, int, int) | Örnek başına belirli sayıda bit ile CIE Lab rengini alır. |
| static [GetCmyk](../../aspose.imaging/pixeldataformat/getcmyk#getcmyk)(int) | Örnek başına belirli sayıda bit ile CMYK rengini alır. |
| static [GetCmyk](../../aspose.imaging/pixeldataformat/getcmyk#getcmyk_1)(int, int, int, int) | Örnek başına belirli sayıda bit ile CMYK rengini alır. |
| static [GetCmyka](../../aspose.imaging/pixeldataformat/getcmyka)(int, int, int, int, int) | Örnek başına belirli sayıda bit ile CMYKA rengini alır. |
| static [GetGrayscale](../../aspose.imaging/pixeldataformat/getgrayscale)(int) | Örnek başına belirli sayıda bit ile Gri Tonlamalı renk alır. |
| static [GetGrayscaleAlpha](../../aspose.imaging/pixeldataformat/getgrayscalealpha#getgrayscalealpha)(int) | Örnek başına belirli sayıda bit ile GrayscaleAlpha rengini alır. |
| static [GetGrayscaleAlpha](../../aspose.imaging/pixeldataformat/getgrayscalealpha#getgrayscalealpha_1)(int, int) | Örnek başına belirli sayıda bit ile GrayscaleAlpha rengini alır. |
| static [GetRgb](../../aspose.imaging/pixeldataformat/getrgb#getrgb)(int) | Örnek başına belirli sayıda bit ile RGB rengini alır. |
| static [GetRgb](../../aspose.imaging/pixeldataformat/getrgb#getrgb_1)(int, int, int) | Örnek başına belirli sayıda bit ile RGB rengini alır. |
| static [GetRgba](../../aspose.imaging/pixeldataformat/getrgba#getrgba)(int) | Örnek başına belirli sayıda bit ile RGBA rengini alır. |
| static [GetRgba](../../aspose.imaging/pixeldataformat/getrgba#getrgba_1)(int, int, int, int) | Örnek başına belirli sayıda bit ile RGBA rengini alır. |
| static [GetRgbIndexed](../../aspose.imaging/pixeldataformat/getrgbindexed)(int) | Örnek başına belirli sayıda bit ile BGRA dizinlenmiş rengi alır. |
| static [GetYCbCr](../../aspose.imaging/pixeldataformat/getycbcr#getycbcr)(int) | Örnek başına belirli sayıda bit ile YCbCr rengini alır. |
| static [GetYCbCr](../../aspose.imaging/pixeldataformat/getycbcr#getycbcr_1)(int, int, int) | Örnek başına belirli sayıda bit ile YCbCr rengini alır. |
| static [GetYcck](../../aspose.imaging/pixeldataformat/getycck)(int) | Örnek başına belirli sayıda bit ile YCCK rengini alır. |
| override [Equals](../../aspose.imaging/pixeldataformat/equals)(object) | BelirtilenObject bu örneğe eşittir. |
| override [GetHashCode](../../aspose.imaging/pixeldataformat/gethashcode)() | Bu örnek için bir karma kod döndürür. |
| override [ToString](../../aspose.imaging/pixeldataformat/tostring)() | Bir döndürürString bu, bu örneği temsil eder. |
| [operator ==](../../aspose.imaging/pixeldataformat/op_equality) | İki kişilik eşitliğin sonucunu döndürür[`PixelDataFormat`](../pixeldataformat) sınıflar. |
| [operator !=](../../aspose.imaging/pixeldataformat/op_inequality) | İki kişilik eşitsizliğin sonucunu döndürür[`PixelDataFormat`](../pixeldataformat) sınıflar. |

### Ayrıca bakınız

* ad alanı [Aspose.Imaging](../../aspose.imaging)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
