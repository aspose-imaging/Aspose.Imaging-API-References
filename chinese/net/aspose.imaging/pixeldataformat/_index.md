---
title: "类 PixelDataFormat"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.PixelDataFormat 类。像素数据格式。这是一个不可变对象。"
type: docs
weight: 11290
url: /zh/net/aspose.imaging/pixeldataformat/
---
## PixelDataFormat class

像素数据格式。这是不可变对象。

```csharp
public class PixelDataFormat
```

## 属性

| 名称 | 描述 |
| --- | --- |
| static [Cmyk](../../aspose.imaging/pixeldataformat/cmyk/) { get; } | 获取为每像素 32 位、每种青色、品红、黄色和黑色各 8 位定义的 `PixelDataFormat`。 |
| static [Cmyka](../../aspose.imaging/pixeldataformat/cmyka/) { get; } | 获取 acmyk。 |
| static [GrayscaleAlpha](../../aspose.imaging/pixeldataformat/grayscalealpha/) { get; } | 获取为每像素 16 位、8 位表示 0-255 区间灰度强度且附加 8 位 alpha 分量定义的 `PixelDataFormat`。 |
| static [Rgb16Bpp555](../../aspose.imaging/pixeldataformat/rgb16bpp555/) { get; } | 获取为每像素 16 位、红、绿、蓝各 5 位且未定义 alpha 的 `PixelDataFormat`。 |
| static [Rgb16Bpp565](../../aspose.imaging/pixeldataformat/rgb16bpp565/) { get; } | 获取为每像素 16 位定义的 `PixelDataFormat`，其中红色 5 位，绿色 6 位，蓝色 5 位，未定义 alpha。 |
| static [Rgb24Bpp](../../aspose.imaging/pixeldataformat/rgb24bpp/) { get; } | 获取为每像素 24 位定义的 `PixelDataFormat`，其中 alpha、红色、绿色和蓝色各占 8 位，alpha 未定义。 |
| static [Rgb24BppPng](../../aspose.imaging/pixeldataformat/rgb24bpppng/) { get; } | 获取为每像素 24 位定义的 `PixelDataFormat`，其中 alpha、红色、绿色和蓝色各占 8 位，alpha 未定义。 |
| static [Rgb32Bpp](../../aspose.imaging/pixeldataformat/rgb32bpp/) { get; } | 获取为每像素 32 位定义的 `PixelDataFormat`，其中 alpha、红色、绿色和蓝色各 8 位。 |
| static [Rgba32Bpp](../../aspose.imaging/pixeldataformat/rgba32bpp/) { get; } | 获取为每像素 32 位定义的 `PixelDataFormat`，其中 alpha、红色、绿色和蓝色各 8 位。 |
| static [RgbIndexed1Bpp](../../aspose.imaging/pixeldataformat/rgbindexed1bpp/) { get; } | 获取为每种颜色 1 位索引定义的 `PixelDataFormat`。索引像素数据存储旨在在使用调色板的所有地方实现数据的存储和检索。使用时请谨慎，因为可能需要将一个调色板转换为另一个调色板，或将 RGBA 转换为索引颜色模型。 |
| static [RgbIndexed2Bpp](../../aspose.imaging/pixeldataformat/rgbindexed2bpp/) { get; } | 获取为每种颜色 2 位索引定义的 `PixelDataFormat`。索引像素数据存储旨在在使用调色板的所有地方实现数据的存储和检索。使用时请谨慎，因为可能需要将一个调色板转换为另一个调色板，或将 RGBA 转换为索引颜色模型。 |
| static [RgbIndexed4Bpp](../../aspose.imaging/pixeldataformat/rgbindexed4bpp/) { get; } | 获取为每种颜色 4 位索引定义的 `PixelDataFormat`。索引像素数据存储旨在在使用调色板的所有地方实现数据的存储和检索。使用时请谨慎，因为可能需要将一个调色板转换为另一个调色板，或将 RGBA 转换为索引颜色模型。 |
| static [RgbIndexed8Bpp](../../aspose.imaging/pixeldataformat/rgbindexed8bpp/) { get; } | 获取为每种颜色 8 位索引定义的 `PixelDataFormat`。索引像素数据存储旨在在使用调色板的所有地方实现数据的存储和检索。使用时请谨慎，因为可能需要将一个调色板转换为另一个调色板，或将 RGBA 转换为索引颜色模型。 |
| static [YCbCr](../../aspose.imaging/pixeldataformat/ycbcr/) { get; } | 获取为每像素 24 位定义的 `PixelDataFormat`，其中亮度、蓝差和红差色度分量各占 8 位。 |
| static [Ycck](../../aspose.imaging/pixeldataformat/ycck/) { get; } | 获取为每像素 32 位定义的 `PixelDataFormat`，其中亮度、蓝差、红差和黑色色度分量各占 8 位。 |
| [BitsPerPixel](../../aspose.imaging/pixeldataformat/bitsperpixel/) { get; } | 获取每像素的位数。 |
| [Caption](../../aspose.imaging/pixeldataformat/caption/) { get; } | 获取像素数据格式的标题。 |
| [ChannelBits](../../aspose.imaging/pixeldataformat/channelbits/) { get; } | 获取每个通道的位数。 |
| [ChannelsCount](../../aspose.imaging/pixeldataformat/channelscount/) { get; } | 获取通道数量。 |
| [PixelFormat](../../aspose.imaging/pixeldataformat/pixelformat/) { get; } | 获取像素格式。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [GetBgr](../../aspose.imaging/pixeldataformat/getbgr/)(int) | 获取具有指定每样本位数的 BGR 颜色。 |
| static [GetBgra](../../aspose.imaging/pixeldataformat/getbgra/)(int) | 获取具有指定每样本位数的 BGRA 颜色。 |
| static [GetCieLab](../../aspose.imaging/pixeldataformat/getcielab/)(int, int, int) | 获取具有指定每样本位数的 CIE Lab 颜色。 |
| static [GetCmyk](../../aspose.imaging/pixeldataformat/getcmyk/#getcmyk)(int) | 获取具有指定每样本位数的 CMYK 颜色。 |
| static [GetCmyk](../../aspose.imaging/pixeldataformat/getcmyk/#getcmyk_1)(int, int, int, int) | 获取具有指定每样本位数的 CMYK 颜色。 |
| static [GetCmyka](../../aspose.imaging/pixeldataformat/getcmyka/)(int, int, int, int, int) | 获取具有指定每样本位数的 CMYKA 颜色。 |
| static [GetGrayscale](../../aspose.imaging/pixeldataformat/getgrayscale/)(int) | 获取具有指定每样本位数的灰度颜色。 |
| static [GetGrayscaleAlpha](../../aspose.imaging/pixeldataformat/getgrayscalealpha/#getgrayscalealpha)(int) | 获取具有指定每样本位数的灰度 Alpha 颜色。 |
| static [GetGrayscaleAlpha](../../aspose.imaging/pixeldataformat/getgrayscalealpha/#getgrayscalealpha_1)(int, int) | 获取具有指定每样本位数的灰度 Alpha 颜色。 |
| static [GetRgb](../../aspose.imaging/pixeldataformat/getrgb/#getrgb)(int) | 获取具有指定每样本位数的 RGB 颜色。 |
| static [GetRgb](../../aspose.imaging/pixeldataformat/getrgb/#getrgb_1)(int, int, int) | 获取具有指定每样本位数的 RGB 颜色。 |
| static [GetRgba](../../aspose.imaging/pixeldataformat/getrgba/#getrgba)(int) | 获取具有指定每样本位数的 RGBA 颜色。 |
| static [GetRgba](../../aspose.imaging/pixeldataformat/getrgba/#getrgba_1)(int, int, int, int) | 获取具有指定每样本位数的 RGBA 颜色。 |
| static [GetRgbIndexed](../../aspose.imaging/pixeldataformat/getrgbindexed/)(int) | 获取具有指定每样本位数的 BGRA 索引颜色。 |
| static [GetYCbCr](../../aspose.imaging/pixeldataformat/getycbcr/#getycbcr)(int) | 获取具有指定每样本位数的 YCbCr 颜色。 |
| static [GetYCbCr](../../aspose.imaging/pixeldataformat/getycbcr/#getycbcr_1)(int, int, int) | 获取具有指定每样本位数的 YCbCr 颜色。 |
| static [GetYcck](../../aspose.imaging/pixeldataformat/getycck/)(int) | 获取具有指定每样本位数的 YCCK 颜色。 |
| override [Equals](../../aspose.imaging/pixeldataformat/equals/)(object) | 确定指定的 Object 是否等于此实例。 |
| override [GetHashCode](../../aspose.imaging/pixeldataformat/gethashcode/)() | 返回此实例的哈希码。 |
| override [ToString](../../aspose.imaging/pixeldataformat/tostring/)() | 返回表示此实例的 String。 |
| [operator ==](../../aspose.imaging/pixeldataformat/op_equality/) | 返回两个 `PixelDataFormat` 类相等的结果。 |
| [operator !=](../../aspose.imaging/pixeldataformat/op_inequality/) | 返回两个 `PixelDataFormat` 类不相等的结果。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| static [Grayscale](../../aspose.imaging/pixeldataformat/grayscale/) | 获取为每像素 8 位定义的 `PixelDataFormat`，其中 8 位表示 0-255 区间的灰度强度。 |
| static readonly [Grayscale16](../../aspose.imaging/pixeldataformat/grayscale16/) | 为每像素 16 位定义，最多使用 16 位表示灰度强度。 |

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


