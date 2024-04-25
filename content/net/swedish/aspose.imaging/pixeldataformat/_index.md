---
title: PixelDataFormat
second_title: Aspose.Imaging för .NET API-referens
description: Pixeldataformatet. Detta är ett oföränderligt objekt.
type: docs
weight: 10720
url: /sv/aspose.imaging/pixeldataformat/
---
## PixelDataFormat class

Pixeldataformatet. Detta är ett oföränderligt objekt.

```csharp
public class PixelDataFormat
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| static [Cmyk](../../aspose.imaging/pixeldataformat/cmyk) { get; } | Får[`PixelDataFormat`](../pixeldataformat) definieras för 32 bitar per pixel med 8 bitar för var och en av cyan, magenta, gul och svart. |
| static [Cmyka](../../aspose.imaging/pixeldataformat/cmyka) { get; } | Får acmyken. |
| static [Grayscale](../../aspose.imaging/pixeldataformat/grayscale) { get; } | Får[`PixelDataFormat`](../pixeldataformat)definierad för 8 bitar per pixel med 8 bitar som representerar gråskaleintensitet i intervallet 0-255. |
| static [GrayscaleAlpha](../../aspose.imaging/pixeldataformat/grayscalealpha) { get; } | Får[`PixelDataFormat`](../pixeldataformat) definierad för 16 bitar per pixel med 8 bitar som representerar gråskaleintensitet i intervallet 0-255 och ytterligare 8 bitars alfakomponent. |
| static [Rgb16Bpp555](../../aspose.imaging/pixeldataformat/rgb16bpp555) { get; } | Får[`PixelDataFormat`](../pixeldataformat) definierad för 16 bitar per pixel med 5 bitar för var och en av de röda, gröna och blå, alfa är inte definierad. |
| static [Rgb16Bpp565](../../aspose.imaging/pixeldataformat/rgb16bpp565) { get; } | Får[`PixelDataFormat`](../pixeldataformat) definierad för 16 bitar per pixel med 5 bitar för rött, 6 bitar för grönt och 5 bitar för blått, alfa är inte definierat. |
| static [Rgb24Bpp](../../aspose.imaging/pixeldataformat/rgb24bpp) { get; } | Får[`PixelDataFormat`](../pixeldataformat) definieras för 24 bitar per pixel med 8 bitar för var och en av alfa, röd, grön och blå, alfa är inte definierad. |
| static [Rgb24BppPng](../../aspose.imaging/pixeldataformat/rgb24bpppng) { get; } | Får[`PixelDataFormat`](../pixeldataformat) definieras för 24 bitar per pixel med 8 bitar för var och en av alfa, röd, grön och blå, alfa är inte definierad. |
| static [Rgb32Bpp](../../aspose.imaging/pixeldataformat/rgb32bpp) { get; } | Får[`PixelDataFormat`](../pixeldataformat) definieras för 32 bitar per pixel med 8 bitar för var och en av alfa, röd, grön och blå. |
| static [Rgba32Bpp](../../aspose.imaging/pixeldataformat/rgba32bpp) { get; } | Får[`PixelDataFormat`](../pixeldataformat) definieras för 32 bitar per pixel med 8 bitar för var och en av alfa, röd, grön och blå. |
| static [RgbIndexed1Bpp](../../aspose.imaging/pixeldataformat/rgbindexed1bpp) { get; } | Får[`PixelDataFormat`](../pixeldataformat) definierad för indexerad 1 bit per färg. Den indexerade pixeldatalagringen är avsedd att möjliggöra datalagring och hämtning överallt där färgpaletten används. Använd med försiktighet, eftersom det kan kräva konvertering från en palett till en annan eller från RGBA till indexerad färgmodell . |
| static [RgbIndexed2Bpp](../../aspose.imaging/pixeldataformat/rgbindexed2bpp) { get; } | Får[`PixelDataFormat`](../pixeldataformat)definierad för indexerad 2 bitar per färg. Den indexerade pixeldatalagringen är avsedd att tillåta datalagring och hämtning överallt där färgpaletten används. Använd med försiktighet, eftersom det kan kräva konvertering från en palett till en annan eller från RGBA till indexerad färgmodell . |
| static [RgbIndexed4Bpp](../../aspose.imaging/pixeldataformat/rgbindexed4bpp) { get; } | Får[`PixelDataFormat`](../pixeldataformat) definierad för indexerad 4 bitar per färg. Den indexerade pixeldatalagringen är avsedd att tillåta datalagring och hämtning överallt där färgpaletten används. Använd med försiktighet, eftersom det kan kräva konvertering från en palett till en annan eller från RGBA till indexerad färgmodell . |
| static [RgbIndexed8Bpp](../../aspose.imaging/pixeldataformat/rgbindexed8bpp) { get; } | Får[`PixelDataFormat`](../pixeldataformat)definierad för indexerad 8 bitar per färg. Den indexerade pixeldatalagringen är avsedd att möjliggöra datalagring och hämtning överallt där färgpaletten används. Använd med försiktighet, eftersom det kan kräva konvertering från en palett till en annan eller från RGBA till indexerad färgmodell . |
| static [YCbCr](../../aspose.imaging/pixeldataformat/ycbcr) { get; } | Får[`PixelDataFormat`](../pixeldataformat) definierad för 24 bitar per pixel med 8 bitar för var och en av luma-, blåskillnads- och rödskillnads-chroma-komponenterna. |
| static [Ycck](../../aspose.imaging/pixeldataformat/ycck) { get; } | Får[`PixelDataFormat`](../pixeldataformat) definierad för 32 bitar per pixel med 8 bitar för var och en av komponenterna luma, blå-skillnad, röd-skillnad och svart chroma. |
| [BitsPerPixel](../../aspose.imaging/pixeldataformat/bitsperpixel) { get; } | Hämtar bitarna per pixel. |
| [Caption](../../aspose.imaging/pixeldataformat/caption) { get; } | Hämtar bildtexten för pixeldataformat. |
| [ChannelBits](../../aspose.imaging/pixeldataformat/channelbits) { get; } | Får antalet bitar för varje kanal. |
| [ChannelsCount](../../aspose.imaging/pixeldataformat/channelscount) { get; } | Får antalet kanaler. |
| [PixelFormat](../../aspose.imaging/pixeldataformat/pixelformat) { get; } | Hämtar pixelformatet. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [GetBgr](../../aspose.imaging/pixeldataformat/getbgr)(int) | Får BGR-färg med ett specificerat antal bitar per sampel. |
| static [GetBgra](../../aspose.imaging/pixeldataformat/getbgra)(int) | Får BGRA-färg med ett specificerat antal bitar per sampel. |
| static [GetCieLab](../../aspose.imaging/pixeldataformat/getcielab)(int, int, int) | Får CIE Lab-färg med ett specificerat antal bitar per sampel. |
| static [GetCmyk](../../aspose.imaging/pixeldataformat/getcmyk#getcmyk)(int) | Får CMYK-färg med ett specificerat antal bitar per sampel. |
| static [GetCmyk](../../aspose.imaging/pixeldataformat/getcmyk#getcmyk_1)(int, int, int, int) | Får CMYK-färg med ett specificerat antal bitar per sampel. |
| static [GetCmyka](../../aspose.imaging/pixeldataformat/getcmyka)(int, int, int, int, int) | Får CMYKA-färg med ett specificerat antal bitar per sampel. |
| static [GetGrayscale](../../aspose.imaging/pixeldataformat/getgrayscale)(int) | Får gråskalefärg med ett specificerat antal bitar per sampel. |
| static [GetGrayscaleAlpha](../../aspose.imaging/pixeldataformat/getgrayscalealpha#getgrayscalealpha)(int) | Får GrayscaleAlpha-färg med ett specificerat antal bitar per sampel. |
| static [GetGrayscaleAlpha](../../aspose.imaging/pixeldataformat/getgrayscalealpha#getgrayscalealpha_1)(int, int) | Får GrayscaleAlpha-färg med ett specificerat antal bitar per sampel. |
| static [GetRgb](../../aspose.imaging/pixeldataformat/getrgb#getrgb)(int) | Får RGB-färg med ett specificerat antal bitar per sampel. |
| static [GetRgb](../../aspose.imaging/pixeldataformat/getrgb#getrgb_1)(int, int, int) | Får RGB-färg med ett specificerat antal bitar per sampel. |
| static [GetRgba](../../aspose.imaging/pixeldataformat/getrgba#getrgba)(int) | Får RGBA-färg med ett specificerat antal bitar per sampel. |
| static [GetRgba](../../aspose.imaging/pixeldataformat/getrgba#getrgba_1)(int, int, int, int) | Får RGBA-färg med ett specificerat antal bitar per sampel. |
| static [GetRgbIndexed](../../aspose.imaging/pixeldataformat/getrgbindexed)(int) | Får BGRA-indexerad färg med ett specificerat antal bitar per sampel. |
| static [GetYCbCr](../../aspose.imaging/pixeldataformat/getycbcr#getycbcr)(int) | Får YCbCr-färg med ett specificerat antal bitar per sampel. |
| static [GetYCbCr](../../aspose.imaging/pixeldataformat/getycbcr#getycbcr_1)(int, int, int) | Får YCbCr-färg med ett specificerat antal bitar per sampel. |
| static [GetYcck](../../aspose.imaging/pixeldataformat/getycck)(int) | Får YCCK-färg med ett specificerat antal bitar per sampel. |
| override [Equals](../../aspose.imaging/pixeldataformat/equals)(object) | Bestämmer om den angivnaObject är lika med denna instans. |
| override [GetHashCode](../../aspose.imaging/pixeldataformat/gethashcode)() | Returnerar en hash-kod för denna instans. |
| override [ToString](../../aspose.imaging/pixeldataformat/tostring)() | Returnerar enString som representerar denna instans. |
| [operator ==](../../aspose.imaging/pixeldataformat/op_equality) | Returnerar resultatet av likhet för två[`PixelDataFormat`](../pixeldataformat) klasser. |
| [operator !=](../../aspose.imaging/pixeldataformat/op_inequality) | Returnerar resultatet av icke-likhet för två[`PixelDataFormat`](../pixeldataformat) klasser. |

### Se även

* namnutrymme [Aspose.Imaging](../../aspose.imaging)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
