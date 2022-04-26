---
title: PixelDataFormat
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 10680
url: /net/aspose.imaging/pixeldataformat/
---
## PixelDataFormat class

The pixel data format. This is an immutable object.

```csharp
public class PixelDataFormat
```

## Properties

| Name | Description |
| --- | --- |
| static [Cmyk](cmyk) { get; } | Gets the [`PixelDataFormat`](../pixeldataformat) defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black. |
| static [Cmyka](cmyka) { get; } | Gets the acmyk. |
| static [Grayscale](grayscale) { get; } | Gets the [`PixelDataFormat`](../pixeldataformat) defined for 8 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval. |
| static [GrayscaleAlpha](grayscalealpha) { get; } | Gets the [`PixelDataFormat`](../pixeldataformat) defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component. |
| static [Rgb16Bpp555](rgb16bpp555) { get; } | Gets the [`PixelDataFormat`](../pixeldataformat) defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined. |
| static [Rgb16Bpp565](rgb16bpp565) { get; } | Gets the [`PixelDataFormat`](../pixeldataformat) defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined. |
| static [Rgb24Bpp](rgb24bpp) { get; } | Gets the [`PixelDataFormat`](../pixeldataformat) defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined. |
| static [Rgb24BppPng](rgb24bpppng) { get; } | Gets the [`PixelDataFormat`](../pixeldataformat) defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined. |
| static [Rgb32Bpp](rgb32bpp) { get; } | Gets the [`PixelDataFormat`](../pixeldataformat) defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue. |
| static [Rgba32Bpp](rgba32bpp) { get; } | Gets the [`PixelDataFormat`](../pixeldataformat) defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue. |
| static [RgbIndexed1Bpp](rgbindexed1bpp) { get; } | Gets the [`PixelDataFormat`](../pixeldataformat) defined for indexed 1 bit per color. The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used. Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model. |
| static [RgbIndexed2Bpp](rgbindexed2bpp) { get; } | Gets the [`PixelDataFormat`](../pixeldataformat) defined for indexed 2 bit per color. The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used. Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model. |
| static [RgbIndexed4Bpp](rgbindexed4bpp) { get; } | Gets the [`PixelDataFormat`](../pixeldataformat) defined for indexed 4 bit per color. The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used. Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model. |
| static [RgbIndexed8Bpp](rgbindexed8bpp) { get; } | Gets the [`PixelDataFormat`](../pixeldataformat) defined for indexed 8 bit per color. The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used. Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model. |
| static [YCbCr](ycbcr) { get; } | Gets the [`PixelDataFormat`](../pixeldataformat) defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components. |
| static [Ycck](ycck) { get; } | Gets the [`PixelDataFormat`](../pixeldataformat) defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components. |
| [BitsPerPixel](bitsperpixel) { get; } | Gets the bits per pixel. |
| [Caption](caption) { get; } | Gets the pixel data format caption. |
| [ChannelBits](channelbits) { get; } | Gets the bits count for each channel. |
| [ChannelsCount](channelscount) { get; } | Gets the channels count. |
| [PixelFormat](pixelformat) { get; } | Gets the pixel format. |

## Methods

| Name | Description |
| --- | --- |
| static [GetBgr](getbgr)(int) | Gets BGR color with a specified number of bits per sample. |
| static [GetBgra](getbgra)(int) | Gets BGRA color with a specified number of bits per sample. |
| static [GetCieLab](getcielab)(int, int, int) | Gets CIE Lab color with a specified number of bits per sample. |
| static [GetCmyk](getcmyk)(int) | Gets CMYK color with a specified number of bits per sample. |
| static [GetCmyk](getcmyk)(int, int, int, int) | Gets CMYK color with a specified number of bits per sample. |
| static [GetCmyka](getcmyka)(int, int, int, int, int) | Gets CMYKA color with a specified number of bits per sample. |
| static [GetGrayscale](getgrayscale)(int) | Gets Grayscale color with a specified number of bits per sample. |
| static [GetGrayscaleAlpha](getgrayscalealpha)(int) | Gets GrayscaleAlpha color with a specified number of bits per sample. |
| static [GetGrayscaleAlpha](getgrayscalealpha)(int, int) | Gets GrayscaleAlpha color with a specified number of bits per sample. |
| static [GetRgb](getrgb)(int) | Gets RGB color with a specified number of bits per sample. |
| static [GetRgb](getrgb)(int, int, int) | Gets RGB color with a specified number of bits per sample. |
| static [GetRgba](getrgba)(int) | Gets RGBA color with a specified number of bits per sample. |
| static [GetRgba](getrgba)(int, int, int, int) | Gets RGBA color with a specified number of bits per sample. |
| static [GetRgbIndexed](getrgbindexed)(int) | Gets BGRA indexed color with a specified number of bits per sample. |
| static [GetYCbCr](getycbcr)(int) | Gets YCbCr color with a specified number of bits per sample. |
| static [GetYCbCr](getycbcr)(int, int, int) | Gets YCbCr color with a specified number of bits per sample. |
| static [GetYcck](getycck)(int) | Gets YCCK color with a specified number of bits per sample. |
| override [Equals](equals)(object) | Determines whether the specified Object is equal to this instance. |
| override [GetHashCode](gethashcode)() | Returns a hash code for this instance. |
| override [ToString](tostring)() | Returns a String that represents this instance. |
| [operator ==](op_equality) | Returns result of equality for two [`PixelDataFormat`](../pixeldataformat) classes. |
| [operator !=](op_inequality) | Returns result of non-equality for two [`PixelDataFormat`](../pixeldataformat) classes. |

### See Also

* namespace [Aspose.Imaging](../../aspose.imaging)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
