---
title: "PixelDataFormat"
second_title: "Aspose.Imaging for Java API 参考"
description: "像素数据格式。"
type: docs
weight: 84
url: /zh/java/com.aspose.imaging/pixeldataformat/
---
**Inheritance:**
java.lang.Object
```
public class PixelDataFormat
```

像素数据格式。这是一个不可变对象。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Grayscale](#Grayscale) | 获取为每像素 8 位且 8 位表示 0-255 区间灰度强度的 [PixelDataFormat](../../com.aspose.imaging/pixeldataformat)。 |
| [Grayscale16](#Grayscale16) | 为每像素 16 位且最多 16 位表示灰度强度而定义。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRgb32Bpp()](#getRgb32Bpp--) | 获取为每像素 32 位且每个 alpha、红色、绿色和蓝色各占 8 位的 `PixelDataFormat`。 |
| [getCmyk()](#getCmyk--) | 获取为每像素 32 位且每个青色、品红、黄色和黑色各占 8 位的 `PixelDataFormat`。 |
| [getCmyka()](#getCmyka--) | 获取 acmyk。 |
| [getRgb24Bpp()](#getRgb24Bpp--) | 获取为每像素 24 位且每个 alpha、红色、绿色和蓝色各占 8 位的 `PixelDataFormat`，其中未定义 alpha。 |
| [getRgb16Bpp555()](#getRgb16Bpp555--) | 获取为每像素 16 位且每个红色、绿色和蓝色各占 5 位的 `PixelDataFormat`，其中未定义 alpha。 |
| [getRgb16Bpp565()](#getRgb16Bpp565--) | 获取为每像素 16 位且红色占 5 位、绿色占 6 位、蓝色占 5 位的 `PixelDataFormat`，其中未定义 alpha。 |
| [getRgbIndexed8Bpp()](#getRgbIndexed8Bpp--) | 获取为每种颜色索引 8 位的 `PixelDataFormat`。 |
| [getRgbIndexed4Bpp()](#getRgbIndexed4Bpp--) | 获取为每种颜色索引 4 位的 `PixelDataFormat`。 |
| [getRgbIndexed2Bpp()](#getRgbIndexed2Bpp--) | 获取为每种颜色索引 2 位的 `PixelDataFormat`。 |
| [getRgbIndexed1Bpp()](#getRgbIndexed1Bpp--) | 获取为每种颜色索引 1 位的 `PixelDataFormat`。 |
| [getYCbCr()](#getYCbCr--) | 获取为每像素 24 位且亮度、蓝差和红差色度分量各占 8 位的 `PixelDataFormat`。 |
| [getYcck()](#getYcck--) | 获取为每像素 32 位且亮度、蓝差、红差和黑色色度分量各占 8 位的 `PixelDataFormat`。 |
| [getRgba32Bpp()](#getRgba32Bpp--) | 获取为每像素 32 位且每个 alpha、红色、绿色和蓝色各占 8 位的 `PixelDataFormat`。 |
| [getRgb24BppPng()](#getRgb24BppPng--) | 获取为每像素 24 位且每个 alpha、红色、绿色和蓝色各占 8 位的 `PixelDataFormat`，其中未定义 alpha。 |
| [getGrayscaleAlpha()](#getGrayscaleAlpha--) | 获取为每像素 16 位且 8 位表示 0-255 区间灰度强度，并附加 8 位 alpha 分量的 `PixelDataFormat`。 |
| [getPixelFormat()](#getPixelFormat--) | 获取像素格式。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | 获取每像素位数。 |
| [getChannelsCount()](#getChannelsCount--) | 获取通道数。 |
| [getChannelBits()](#getChannelBits--) | 获取每个通道的位数。 |
| [getCaption()](#getCaption--) | 获取像素数据格式标题。 |
| [getGrayscale(int bitsPerSample)](#getGrayscale-int-) | 获取具有指定每样本位数的灰度颜色。 |
| [getGrayscaleAlpha(int bitsPerSample)](#getGrayscaleAlpha-int-) | 获取具有指定每样本位数的灰度Alpha颜色。 |
| [getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)](#getGrayscaleAlpha-int-int-) | 获取具有指定每样本位数的灰度Alpha颜色。 |
| [getRgb(int bitsPerSample)](#getRgb-int-) | 获取具有指定每样本位数的RGB颜色。 |
| [getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)](#getRgb-int-int-int-) | 获取具有指定每样本位数的RGB颜色。 |
| [getRgba(int bitsPerSample)](#getRgba-int-) | 获取具有指定每样本位数的RGBA颜色。 |
| [getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)](#getRgba-int-int-int-int-) | 获取具有指定每样本位数的RGBA颜色。 |
| [getRgbIndexed(int bitsPerSample)](#getRgbIndexed-int-) | 获取具有指定每样本位数的BGRA索引颜色。 |
| [getBgra(int bitsPerSample)](#getBgra-int-) | 获取具有指定每样本位数的BGRA颜色。 |
| [getBgr(int bitsPerSample)](#getBgr-int-) | 获取具有指定每样本位数的BGR颜色。 |
| [getYCbCr(int bitsPerSample)](#getYCbCr-int-) | 获取具有指定每样本位数的YCbCr颜色。 |
| [getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)](#getYCbCr-int-int-int-) | 获取具有指定每样本位数的YCbCr颜色。 |
| [getCmyk(int bitsPerSample)](#getCmyk-int-) | 获取具有指定每样本位数的CMYK颜色。 |
| [getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)](#getCmyk-int-int-int-int-) | 获取具有指定每样本位数的CMYK颜色。 |
| [getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)](#getCmyka-int-int-int-int-int-) | 获取具有指定每样本位数的CMYKA颜色。 |
| [getYcck(int bitsPerSample)](#getYcck-int-) | 获取具有指定每样本位数的YCCK颜色。 |
| [getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)](#getCieLab-int-int-int-) | 获取具有指定每样本位数的CIE Lab颜色。 |
| [op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Inequality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-) | 返回两个 `PixelDataFormat` 类不相等的结果。 |
| [op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Equality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-) | 返回两个 `PixelDataFormat` 类相等的结果。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 `System.Object` 是否等于此实例。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [toString()](#toString--) | 返回表示此实例的 `System.String`。 |
### Grayscale {#Grayscale}
```
public static final PixelDataFormat Grayscale
```


获取为每像素 8 位且 8 位表示 0-255 区间灰度强度的 [PixelDataFormat](../../com.aspose.imaging/pixeldataformat)。

值：在每像素8位且8位表示0-255区间内灰度强度的情况下，定义的 [PixelDataFormat](../../com.aspose.imaging/pixeldataformat)。

### Grayscale16 {#Grayscale16}
```
public static final PixelDataFormat Grayscale16
```


为每像素 16 位且最多 16 位表示灰度强度而定义。

### getRgb32Bpp() {#getRgb32Bpp--}
```
public static PixelDataFormat getRgb32Bpp()
```


获取为每像素 32 位且每个 alpha、红色、绿色和蓝色各占 8 位的 `PixelDataFormat`。

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getCmyk() {#getCmyk--}
```
public static PixelDataFormat getCmyk()
```


获取为每像素 32 位且每个青色、品红、黄色和黑色各占 8 位的 `PixelDataFormat`。

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.
### getCmyka() {#getCmyka--}
```
public static PixelDataFormat getCmyka()
```


获取 acmyk。

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 40 bits per pixel with 8 bits for each of the alpha, cyan, magenta, yellow and black.
### getRgb24Bpp() {#getRgb24Bpp--}
```
public static PixelDataFormat getRgb24Bpp()
```


获取为每像素 24 位且每个 alpha、红色、绿色和蓝色各占 8 位的 `PixelDataFormat`，其中未定义 alpha。

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb16Bpp555() {#getRgb16Bpp555--}
```
public static PixelDataFormat getRgb16Bpp555()
```


获取为每像素 16 位且每个红色、绿色和蓝色各占 5 位的 `PixelDataFormat`，其中未定义 alpha。

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.
### getRgb16Bpp565() {#getRgb16Bpp565--}
```
public static PixelDataFormat getRgb16Bpp565()
```


获取为每像素 16 位且红色占 5 位、绿色占 6 位、蓝色占 5 位的 `PixelDataFormat`，其中未定义 alpha。

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.
### getRgbIndexed8Bpp() {#getRgbIndexed8Bpp--}
```
public static PixelDataFormat getRgbIndexed8Bpp()
```


获取为每种颜色8位索引定义的 `PixelDataFormat`。索引像素数据存储旨在在使用调色板的所有地方允许数据存储和检索。使用时需谨慎，因为可能需要从一个调色板转换到另一个调色板，或从RGBA转换到索引颜色模型。

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 8 bit per color.
### getRgbIndexed4Bpp() {#getRgbIndexed4Bpp--}
```
public static PixelDataFormat getRgbIndexed4Bpp()
```


获取为每种颜色4位索引定义的 `PixelDataFormat`。索引像素数据存储旨在在使用调色板的所有地方允许数据存储和检索。使用时需谨慎，因为可能需要从一个调色板转换到另一个调色板，或从RGBA转换到索引颜色模型。

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 4 bit per color.
### getRgbIndexed2Bpp() {#getRgbIndexed2Bpp--}
```
public static PixelDataFormat getRgbIndexed2Bpp()
```


获取为每种颜色2位索引定义的 `PixelDataFormat`。索引像素数据存储旨在在使用调色板的所有地方允许数据存储和检索。使用时需谨慎，因为可能需要从一个调色板转换到另一个调色板，或从RGBA转换到索引颜色模型。

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 2 bit per color.
### getRgbIndexed1Bpp() {#getRgbIndexed1Bpp--}
```
public static PixelDataFormat getRgbIndexed1Bpp()
```


获取为每种颜色1位索引定义的 `PixelDataFormat`。索引像素数据存储旨在在使用调色板的所有地方允许数据存储和检索。使用时需谨慎，因为可能需要从一个调色板转换到另一个调色板，或从RGBA转换到索引颜色模型。

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 1 bit per color.
### getYCbCr() {#getYCbCr--}
```
public static PixelDataFormat getYCbCr()
```


获取为每像素 24 位且亮度、蓝差和红差色度分量各占 8 位的 `PixelDataFormat`。

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.
### getYcck() {#getYcck--}
```
public static PixelDataFormat getYcck()
```


获取为每像素 32 位且亮度、蓝差、红差和黑色色度分量各占 8 位的 `PixelDataFormat`。

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.
### getRgba32Bpp() {#getRgba32Bpp--}
```
public static PixelDataFormat getRgba32Bpp()
```


获取为每像素 32 位且每个 alpha、红色、绿色和蓝色各占 8 位的 `PixelDataFormat`。

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgb24BppPng() {#getRgb24BppPng--}
```
public static PixelDataFormat getRgb24BppPng()
```


获取为每像素 24 位且每个 alpha、红色、绿色和蓝色各占 8 位的 `PixelDataFormat`，其中未定义 alpha。

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getGrayscaleAlpha() {#getGrayscaleAlpha--}
```
public static PixelDataFormat getGrayscaleAlpha()
```


获取为每像素 16 位且 8 位表示 0-255 区间灰度强度，并附加 8 位 alpha 分量的 `PixelDataFormat`。

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


获取像素格式。

**Returns:**
int - 像素格式。
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


获取每像素位数。

**Returns:**
int - 每像素的位数。
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


获取通道数。

**Returns:**
int - 通道计数。
### getChannelBits() {#getChannelBits--}
```
public int[] getChannelBits()
```


获取每个通道的位数。

**Returns:**
int[] - 通道位数。
### getCaption() {#getCaption--}
```
public String getCaption()
```


获取像素数据格式标题。

**Returns:**
java.lang.String
### getGrayscale(int bitsPerSample) {#getGrayscale-int-}
```
public static PixelDataFormat getGrayscale(int bitsPerSample)
```


获取具有指定每样本位数的灰度颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bitsPerSample | int | 每个样本的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The Grayscale color.
### getGrayscaleAlpha(int bitsPerSample) {#getGrayscaleAlpha-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample)
```


获取具有指定每样本位数的灰度Alpha颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bitsPerSample | int | 每个样本的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits) {#getGrayscaleAlpha-int-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)
```


获取具有指定每样本位数的灰度Alpha颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bitsPerSample | int | 每个样本的位数。 |
| alphaChannelBits | int | Alpha 通道中每个样本的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The GrayscaleAlpha color.
### getRgb(int bitsPerSample) {#getRgb-int-}
```
public static PixelDataFormat getRgb(int bitsPerSample)
```


获取具有指定每样本位数的RGB颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bitsPerSample | int | 每个样本的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGB color.
### getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel) {#getRgb-int-int-int-}
```
public static PixelDataFormat getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)
```


获取具有指定每样本位数的RGB颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bitsPerRedChannel | int | Red 通道的位数。 |
| bitsPerGreenChannel | int | Green 通道的位数。 |
| bitsPerBlueChannel | int | Blue 通道的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGB color.
### getRgba(int bitsPerSample) {#getRgba-int-}
```
public static PixelDataFormat getRgba(int bitsPerSample)
```


获取具有指定每样本位数的RGBA颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bitsPerSample | int | 每个样本的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGBA color.
### getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel) {#getRgba-int-int-int-int-}
```
public static PixelDataFormat getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)
```


获取具有指定每样本位数的RGBA颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bitsPerRedChannel | int | Red 通道的位数。 |
| bitsPerGreenChannel | int | Green 通道的位数。 |
| bitsPerBlueChannel | int | Blue 通道的位数。 |
| bitsPerAlphaChannel | int | Alpha 通道的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGBA color.
### getRgbIndexed(int bitsPerSample) {#getRgbIndexed-int-}
```
public static PixelDataFormat getRgbIndexed(int bitsPerSample)
```


获取具有指定每样本位数的BGRA索引颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bitsPerSample | int | 每个样本的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGRA color.
### getBgra(int bitsPerSample) {#getBgra-int-}
```
public static PixelDataFormat getBgra(int bitsPerSample)
```


获取具有指定每样本位数的BGRA颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bitsPerSample | int | 每个样本的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGRA color.
### getBgr(int bitsPerSample) {#getBgr-int-}
```
public static PixelDataFormat getBgr(int bitsPerSample)
```


获取具有指定每样本位数的BGR颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bitsPerSample | int | 每个样本的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGR color.
### getYCbCr(int bitsPerSample) {#getYCbCr-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerSample)
```


获取具有指定每样本位数的YCbCr颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bitsPerSample | int | 每个样本的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCbCr color.
### getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr) {#getYCbCr-int-int-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)
```


获取具有指定每样本位数的YCbCr颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bitsPerY | int | Y 通道的位数。 |
| bitsPerCb | int | Cb 通道的位数。 |
| bitsPerCr | int | Cr 通道的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCbCr color.
### getCmyk(int bitsPerSample) {#getCmyk-int-}
```
public static PixelDataFormat getCmyk(int bitsPerSample)
```


获取具有指定每样本位数的CMYK颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bitsPerSample | int | 每个样本的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel) {#getCmyk-int-int-int-int-}
```
public static PixelDataFormat getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)
```


获取具有指定每样本位数的CMYK颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bitsPerCyanChannel | int | Cyan 通道的位数。 |
| bitsPerMagentaChannel | int | Magenta 通道的位数。 |
| bitsPerYellowChannel | int | 每个 Yellow 通道的位数。 |
| bitsPerKeyChannel | int | 每个 Key 通道的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel) {#getCmyka-int-int-int-int-int-}
```
public static PixelDataFormat getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)
```


获取具有指定每样本位数的CMYKA颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bitsPerCyanChannel | int | Cyan 通道的位数。 |
| bitsPerMagentaChannel | int | Magenta 通道的位数。 |
| bitsPerYellowChannel | int | 每个 Yellow 通道的位数。 |
| bitsPerKeyChannel | int | 每个 Key 通道的位数。 |
| bitsPerAlphaChannel | int | Alpha 通道的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getYcck(int bitsPerSample) {#getYcck-int-}
```
public static PixelDataFormat getYcck(int bitsPerSample)
```


获取具有指定每样本位数的YCCK颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bitsPerSample | int | 每个样本的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCCK color.
### getCieLab(int bitsPerL, int bitsPerA, int bitsPerB) {#getCieLab-int-int-int-}
```
public static PixelDataFormat getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)
```


获取具有指定每样本位数的CIE Lab颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bitsPerL | int | 每个 L 通道的位数。 |
| bitsPerA | int | 每个 A 通道的位数。 |
| bitsPerB | int | 每个 B 通道的位数。 |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CIE Lab color.
### op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Inequality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public static boolean op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


返回两个 `PixelDataFormat` 类不相等的结果。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | 要比较的第一个 `PixelDataFormat`。 |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | 要比较的第二个 `PixelDataFormat`。 |

**Returns:**
boolean - 如果 `pixelFormat1` 和 `pixelFormat2` 都包含不相等的数据，或其中一个参数为 null，则为 True。
### op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Equality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public static boolean op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


返回两个 `PixelDataFormat` 类相等的结果。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | 要比较的第一个 `PixelDataFormat`。 |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | 要比较的第二个 `PixelDataFormat`。 |

**Returns:**
boolean - 如果 `pixelFormat1` 和 `pixelFormat2` 都包含相等的数据，或两个参数均为 null，则为 True。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的 `System.Object` 是否等于此实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要与此实例比较的 `System.Object`。 |

**Returns:**
boolean - 如果指定的 `System.Object` 等于此实例，则为 `true`；否则，为 `false`。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和哈希表等数据结构。
### toString() {#toString--}
```
public String toString()
```


返回表示此实例的 `System.String`。

**Returns:**
java.lang.String - 表示此实例的 `System.String`。
