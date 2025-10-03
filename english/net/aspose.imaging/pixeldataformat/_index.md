---
title: Class PixelDataFormat
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.PixelDataFormat class. The pixel data format. This is an immutable object
type: docs
weight: 11200
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
| static [Cmyk](../../aspose.imaging/pixeldataformat/cmyk/) { get; } | Gets the `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black. |
| static [Cmyka](../../aspose.imaging/pixeldataformat/cmyka/) { get; } | Gets the acmyk. |
| static [GrayscaleAlpha](../../aspose.imaging/pixeldataformat/grayscalealpha/) { get; } | Gets the `PixelDataFormat` defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component. |
| static [Rgb16Bpp555](../../aspose.imaging/pixeldataformat/rgb16bpp555/) { get; } | Gets the `PixelDataFormat` defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined. |
| static [Rgb16Bpp565](../../aspose.imaging/pixeldataformat/rgb16bpp565/) { get; } | Gets the `PixelDataFormat` defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined. |
| static [Rgb24Bpp](../../aspose.imaging/pixeldataformat/rgb24bpp/) { get; } | Gets the `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined. |
| static [Rgb24BppPng](../../aspose.imaging/pixeldataformat/rgb24bpppng/) { get; } | Gets the `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined. |
| static [Rgb32Bpp](../../aspose.imaging/pixeldataformat/rgb32bpp/) { get; } | Gets the `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue. |
| static [Rgba32Bpp](../../aspose.imaging/pixeldataformat/rgba32bpp/) { get; } | Gets the `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue. |
| static [RgbIndexed1Bpp](../../aspose.imaging/pixeldataformat/rgbindexed1bpp/) { get; } | Gets the `PixelDataFormat` defined for indexed 1 bit per color. The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used. Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model. |
| static [RgbIndexed2Bpp](../../aspose.imaging/pixeldataformat/rgbindexed2bpp/) { get; } | Gets the `PixelDataFormat` defined for indexed 2 bit per color. The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used. Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model. |
| static [RgbIndexed4Bpp](../../aspose.imaging/pixeldataformat/rgbindexed4bpp/) { get; } | Gets the `PixelDataFormat` defined for indexed 4 bit per color. The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used. Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model. |
| static [RgbIndexed8Bpp](../../aspose.imaging/pixeldataformat/rgbindexed8bpp/) { get; } | Gets the `PixelDataFormat` defined for indexed 8 bit per color. The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used. Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model. |
| static [YCbCr](../../aspose.imaging/pixeldataformat/ycbcr/) { get; } | Gets the `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components. |
| static [Ycck](../../aspose.imaging/pixeldataformat/ycck/) { get; } | Gets the `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components. |
| [BitsPerPixel](../../aspose.imaging/pixeldataformat/bitsperpixel/) { get; } | Gets the bits per pixel. |
| [Caption](../../aspose.imaging/pixeldataformat/caption/) { get; } | Gets the pixel data format caption. |
| [ChannelBits](../../aspose.imaging/pixeldataformat/channelbits/) { get; } | Gets the bits count for each channel. |
| [ChannelsCount](../../aspose.imaging/pixeldataformat/channelscount/) { get; } | Gets the channels count. |
| [PixelFormat](../../aspose.imaging/pixeldataformat/pixelformat/) { get; } | Gets the pixel format. |

## Methods

| Name | Description |
| --- | --- |
| static [GetBgr](../../aspose.imaging/pixeldataformat/getbgr/)(int) | Gets BGR color with a specified number of bits per sample. |
| static [GetBgra](../../aspose.imaging/pixeldataformat/getbgra/)(int) | Gets BGRA color with a specified number of bits per sample. |
| static [GetCieLab](../../aspose.imaging/pixeldataformat/getcielab/)(int, int, int) | Gets CIE Lab color with a specified number of bits per sample. |
| static [GetCmyk](../../aspose.imaging/pixeldataformat/getcmyk/#getcmyk)(int) | Gets CMYK color with a specified number of bits per sample. |
| static [GetCmyk](../../aspose.imaging/pixeldataformat/getcmyk/#getcmyk_1)(int, int, int, int) | Gets CMYK color with a specified number of bits per sample. |
| static [GetCmyka](../../aspose.imaging/pixeldataformat/getcmyka/)(int, int, int, int, int) | Gets CMYKA color with a specified number of bits per sample. |
| static [GetGrayscale](../../aspose.imaging/pixeldataformat/getgrayscale/)(int) | Gets Grayscale color with a specified number of bits per sample. |
| static [GetGrayscaleAlpha](../../aspose.imaging/pixeldataformat/getgrayscalealpha/#getgrayscalealpha)(int) | Gets GrayscaleAlpha color with a specified number of bits per sample. |
| static [GetGrayscaleAlpha](../../aspose.imaging/pixeldataformat/getgrayscalealpha/#getgrayscalealpha_1)(int, int) | Gets GrayscaleAlpha color with a specified number of bits per sample. |
| static [GetRgb](../../aspose.imaging/pixeldataformat/getrgb/#getrgb)(int) | Gets RGB color with a specified number of bits per sample. |
| static [GetRgb](../../aspose.imaging/pixeldataformat/getrgb/#getrgb_1)(int, int, int) | Gets RGB color with a specified number of bits per sample. |
| static [GetRgba](../../aspose.imaging/pixeldataformat/getrgba/#getrgba)(int) | Gets RGBA color with a specified number of bits per sample. |
| static [GetRgba](../../aspose.imaging/pixeldataformat/getrgba/#getrgba_1)(int, int, int, int) | Gets RGBA color with a specified number of bits per sample. |
| static [GetRgbIndexed](../../aspose.imaging/pixeldataformat/getrgbindexed/)(int) | Gets BGRA indexed color with a specified number of bits per sample. |
| static [GetYCbCr](../../aspose.imaging/pixeldataformat/getycbcr/#getycbcr)(int) | Gets YCbCr color with a specified number of bits per sample. |
| static [GetYCbCr](../../aspose.imaging/pixeldataformat/getycbcr/#getycbcr_1)(int, int, int) | Gets YCbCr color with a specified number of bits per sample. |
| static [GetYcck](../../aspose.imaging/pixeldataformat/getycck/)(int) | Gets YCCK color with a specified number of bits per sample. |
| override [Equals](../../aspose.imaging/pixeldataformat/equals/)(object) | Determines whether the specified Object is equal to this instance. |
| override [GetHashCode](../../aspose.imaging/pixeldataformat/gethashcode/)() | Returns a hash code for this instance. |
| override [ToString](../../aspose.imaging/pixeldataformat/tostring/)() | Returns a String that represents this instance. |
| [operator ==](../../aspose.imaging/pixeldataformat/op_equality/) | Returns result of equality for two `PixelDataFormat` classes. |
| [operator !=](../../aspose.imaging/pixeldataformat/op_inequality/) | Returns result of non-equality for two `PixelDataFormat` classes. |

## Fields

| Name | Description |
| --- | --- |
| static [Grayscale](../../aspose.imaging/pixeldataformat/grayscale/) | Gets the `PixelDataFormat` defined for 8 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval. |
| static readonly [Grayscale16](../../aspose.imaging/pixeldataformat/grayscale16/) | Defined for 16 bits per pixel with up to 16 bits representing grayscale intensity. |

### See Also

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


