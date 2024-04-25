---
title: PixelDataFormat
second_title: Aspose.Imaging for .NET API 参考
description: 像素数据格式这是一个不可变的对象
type: docs
weight: 10720
url: /zh/aspose.imaging/pixeldataformat/
---
## PixelDataFormat class

像素数据格式。这是一个不可变的对象。

```csharp
public class PixelDataFormat
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| static [Cmyk](../../aspose.imaging/pixeldataformat/cmyk) { get; } | 获取[`PixelDataFormat`](../pixeldataformat)定义为每像素 32 位，青色、品红色、黄色和黑色各 8 位。 |
| static [Cmyka](../../aspose.imaging/pixeldataformat/cmyka) { get; } | 获取acmyk。 |
| static [Grayscale](../../aspose.imaging/pixeldataformat/grayscale) { get; } | 获取[`PixelDataFormat`](../pixeldataformat)定义为每像素 8 位，其中 8 位表示 0-255 区间内的灰度强度。 |
| static [GrayscaleAlpha](../../aspose.imaging/pixeldataformat/grayscalealpha) { get; } | 获取[`PixelDataFormat`](../pixeldataformat)定义为每像素 16 位，其中 8 位表示 0-255 间隔中的灰度强度和额外的 8 位 alpha 分量。 |
| static [Rgb16Bpp555](../../aspose.imaging/pixeldataformat/rgb16bpp555) { get; } | 获取[`PixelDataFormat`](../pixeldataformat)定义为每像素 16 位，红色、绿色和蓝色各 5 位，未定义 alpha。 |
| static [Rgb16Bpp565](../../aspose.imaging/pixeldataformat/rgb16bpp565) { get; } | 获取[`PixelDataFormat`](../pixeldataformat)定义为每像素 16 位，红色 5 位，绿色 6 位，蓝色 5 位，alpha 未定义。 |
| static [Rgb24Bpp](../../aspose.imaging/pixeldataformat/rgb24bpp) { get; } | 获取[`PixelDataFormat`](../pixeldataformat)定义为每像素 24 位，alpha、红色、绿色和蓝色各 8 位，alpha 未定义。 |
| static [Rgb24BppPng](../../aspose.imaging/pixeldataformat/rgb24bpppng) { get; } | 获取[`PixelDataFormat`](../pixeldataformat)定义为每像素 24 位，alpha、红色、绿色和蓝色各 8 位，alpha 未定义。 |
| static [Rgb32Bpp](../../aspose.imaging/pixeldataformat/rgb32bpp) { get; } | 获取[`PixelDataFormat`](../pixeldataformat)定义为每像素 32 位，alpha、红色、绿色和蓝色各 8 位。 |
| static [Rgba32Bpp](../../aspose.imaging/pixeldataformat/rgba32bpp) { get; } | 获取[`PixelDataFormat`](../pixeldataformat)定义为每像素 32 位，alpha、红色、绿色和蓝色各 8 位。 |
| static [RgbIndexed1Bpp](../../aspose.imaging/pixeldataformat/rgbindexed1bpp) { get; } | 获取[`PixelDataFormat`](../pixeldataformat)为每种颜色索引 1 位定义。 索引像素数据存储旨在允许在使用调色板的任何地方进行数据存储和检索。 谨慎使用，因为可能需要从一个调色板转换为另一种调色板或从 RGBA 转换为索引颜色模型. |
| static [RgbIndexed2Bpp](../../aspose.imaging/pixeldataformat/rgbindexed2bpp) { get; } | 获取[`PixelDataFormat`](../pixeldataformat)为每种颜色的索引 2 位定义。 索引像素数据存储旨在允许在使用调色板的任何地方进行数据存储和检索。 谨慎使用，因为可能需要从一个调色板转换为另一种调色板或从 RGBA 转换为索引颜色模型. |
| static [RgbIndexed4Bpp](../../aspose.imaging/pixeldataformat/rgbindexed4bpp) { get; } | 获取[`PixelDataFormat`](../pixeldataformat)为每种颜色的索引 4 位定义。 索引像素数据存储旨在允许在使用调色板的任何地方进行数据存储和检索。 谨慎使用，因为可能需要从一个调色板转换为另一种调色板或从 RGBA 转换为索引颜色模型. |
| static [RgbIndexed8Bpp](../../aspose.imaging/pixeldataformat/rgbindexed8bpp) { get; } | 获取[`PixelDataFormat`](../pixeldataformat)为每种颜色的索引 8 位定义。 索引像素数据存储旨在允许在使用调色板的任何地方进行数据存储和检索。 谨慎使用，因为可能需要从一个调色板转换为另一种调色板或从 RGBA 转换为索引颜色模型. |
| static [YCbCr](../../aspose.imaging/pixeldataformat/ycbcr) { get; } | 获取[`PixelDataFormat`](../pixeldataformat)定义为每个像素 24 位，每个像素 8 位用于亮度、蓝差和红差色度分量。 |
| static [Ycck](../../aspose.imaging/pixeldataformat/ycck) { get; } | 获取[`PixelDataFormat`](../pixeldataformat)定义为每个像素 32 位，每个像素 8 位用于亮度、蓝差、红差和黑色色度分量。 |
| [BitsPerPixel](../../aspose.imaging/pixeldataformat/bitsperpixel) { get; } | 获取每个像素的位数。 |
| [Caption](../../aspose.imaging/pixeldataformat/caption) { get; } | 获取像素数据格式标题。 |
| [ChannelBits](../../aspose.imaging/pixeldataformat/channelbits) { get; } | 获取每个通道的位数。 |
| [ChannelsCount](../../aspose.imaging/pixeldataformat/channelscount) { get; } | 获取通道数。 |
| [PixelFormat](../../aspose.imaging/pixeldataformat/pixelformat) { get; } | 获取像素格式。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [GetBgr](../../aspose.imaging/pixeldataformat/getbgr)(int) | 获取每个样本指定位数的 BGR 颜色。 |
| static [GetBgra](../../aspose.imaging/pixeldataformat/getbgra)(int) | 获取每个样本指定位数的 BGRA 颜色。 |
| static [GetCieLab](../../aspose.imaging/pixeldataformat/getcielab)(int, int, int) | 获取每个样本指定位数的 CIE Lab 颜色。 |
| static [GetCmyk](../../aspose.imaging/pixeldataformat/getcmyk#getcmyk)(int) | 获取每个样本指定位数的 CMYK 颜色。 |
| static [GetCmyk](../../aspose.imaging/pixeldataformat/getcmyk#getcmyk_1)(int, int, int, int) | 获取每个样本指定位数的 CMYK 颜色。 |
| static [GetCmyka](../../aspose.imaging/pixeldataformat/getcmyka)(int, int, int, int, int) | 获取每个样本指定位数的 CMYKA 颜色。 |
| static [GetGrayscale](../../aspose.imaging/pixeldataformat/getgrayscale)(int) | 获取每个样本指定位数的灰度颜色。 |
| static [GetGrayscaleAlpha](../../aspose.imaging/pixeldataformat/getgrayscalealpha#getgrayscalealpha)(int) | 获取每个样本指定位数的 GrayscaleAlpha 颜色。 |
| static [GetGrayscaleAlpha](../../aspose.imaging/pixeldataformat/getgrayscalealpha#getgrayscalealpha_1)(int, int) | 获取每个样本指定位数的 GrayscaleAlpha 颜色。 |
| static [GetRgb](../../aspose.imaging/pixeldataformat/getrgb#getrgb)(int) | 获取每个样本指定位数的 RGB 颜色。 |
| static [GetRgb](../../aspose.imaging/pixeldataformat/getrgb#getrgb_1)(int, int, int) | 获取每个样本指定位数的 RGB 颜色。 |
| static [GetRgba](../../aspose.imaging/pixeldataformat/getrgba#getrgba)(int) | 获取每个样本指定位数的 RGBA 颜色。 |
| static [GetRgba](../../aspose.imaging/pixeldataformat/getrgba#getrgba_1)(int, int, int, int) | 获取每个样本指定位数的 RGBA 颜色。 |
| static [GetRgbIndexed](../../aspose.imaging/pixeldataformat/getrgbindexed)(int) | 使用每个样本指定的位数获取 BGRA 索引颜色。 |
| static [GetYCbCr](../../aspose.imaging/pixeldataformat/getycbcr#getycbcr)(int) | 使用每个样本指定的位数获取 YCbCr 颜色。 |
| static [GetYCbCr](../../aspose.imaging/pixeldataformat/getycbcr#getycbcr_1)(int, int, int) | 使用每个样本指定的位数获取 YCbCr 颜色。 |
| static [GetYcck](../../aspose.imaging/pixeldataformat/getycck)(int) | 获取每个样本指定位数的 YCCK 颜色。 |
| override [Equals](../../aspose.imaging/pixeldataformat/equals)(object) | 判断是否指定Object等于这个实例。 |
| override [GetHashCode](../../aspose.imaging/pixeldataformat/gethashcode)() | 返回此实例的哈希码。 |
| override [ToString](../../aspose.imaging/pixeldataformat/tostring)() | 返回一个String代表这个实例。 |
| [operator ==](../../aspose.imaging/pixeldataformat/op_equality) | 返回两个相等的结果[`PixelDataFormat`](../pixeldataformat)类. |
| [operator !=](../../aspose.imaging/pixeldataformat/op_inequality) | 返回两个不相等的结果[`PixelDataFormat`](../pixeldataformat)类. |

### 也可以看看

* 命名空间 [Aspose.Imaging](../../aspose.imaging)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
