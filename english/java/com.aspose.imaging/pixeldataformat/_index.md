---
title: PixelDataFormat
second_title: Aspose.Imaging for Java API Reference
description: The pixel data format.
type: docs
weight: 85
url: /java/com.aspose.imaging/pixeldataformat/
---
**Inheritance:**
java.lang.Object
```
public class PixelDataFormat
```

The pixel data format. This is an immutable object.
## Fields

| Field | Description |
| --- | --- |
| [Grayscale](#Grayscale) | Gets the [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) defined for 8 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval. |
| [Grayscale16](#Grayscale16) | Defined for 16 bits per pixel with up to 16 bits representing grayscale intensity. |
## Methods

| Method | Description |
| --- | --- |
| [getRgb32Bpp()](#getRgb32Bpp--) | Gets the `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue. |
| [getCmyk()](#getCmyk--) | Gets the `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black. |
| [getCmyka()](#getCmyka--) | Gets the acmyk. |
| [getRgb24Bpp()](#getRgb24Bpp--) | Gets the `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined. |
| [getRgb16Bpp555()](#getRgb16Bpp555--) | Gets the `PixelDataFormat` defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined. |
| [getRgb16Bpp565()](#getRgb16Bpp565--) | Gets the `PixelDataFormat` defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined. |
| [getRgbIndexed8Bpp()](#getRgbIndexed8Bpp--) | Gets the `PixelDataFormat` defined for indexed 8 bit per color. |
| [getRgbIndexed4Bpp()](#getRgbIndexed4Bpp--) | Gets the `PixelDataFormat` defined for indexed 4 bit per color. |
| [getRgbIndexed2Bpp()](#getRgbIndexed2Bpp--) | Gets the `PixelDataFormat` defined for indexed 2 bit per color. |
| [getRgbIndexed1Bpp()](#getRgbIndexed1Bpp--) | Gets the `PixelDataFormat` defined for indexed 1 bit per color. |
| [getYCbCr()](#getYCbCr--) | Gets the `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components. |
| [getYcck()](#getYcck--) | Gets the `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components. |
| [getRgba32Bpp()](#getRgba32Bpp--) | Gets the `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue. |
| [getRgb24BppPng()](#getRgb24BppPng--) | Gets the `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined. |
| [getGrayscaleAlpha()](#getGrayscaleAlpha--) | Gets the `PixelDataFormat` defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component. |
| [getPixelFormat()](#getPixelFormat--) | Gets the pixel format. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gets the bits per pixel. |
| [getChannelsCount()](#getChannelsCount--) | Gets the channels count. |
| [getChannelBits()](#getChannelBits--) | Gets the bits count for each channel. |
| [getCaption()](#getCaption--) | Gets the pixel data format caption. |
| [getGrayscale(int bitsPerSample)](#getGrayscale-int-) | Gets Grayscale color with a specified number of bits per sample. |
| [getGrayscaleAlpha(int bitsPerSample)](#getGrayscaleAlpha-int-) | Gets GrayscaleAlpha color with a specified number of bits per sample. |
| [getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)](#getGrayscaleAlpha-int-int-) | Gets GrayscaleAlpha color with a specified number of bits per sample. |
| [getRgb(int bitsPerSample)](#getRgb-int-) | Gets RGB color with a specified number of bits per sample. |
| [getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)](#getRgb-int-int-int-) | Gets RGB color with a specified number of bits per sample. |
| [getRgba(int bitsPerSample)](#getRgba-int-) | Gets RGBA color with a specified number of bits per sample. |
| [getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)](#getRgba-int-int-int-int-) | Gets RGBA color with a specified number of bits per sample. |
| [getRgbIndexed(int bitsPerSample)](#getRgbIndexed-int-) | Gets BGRA indexed color with a specified number of bits per sample. |
| [getBgra(int bitsPerSample)](#getBgra-int-) | Gets BGRA color with a specified number of bits per sample. |
| [getBgr(int bitsPerSample)](#getBgr-int-) | Gets BGR color with a specified number of bits per sample. |
| [getYCbCr(int bitsPerSample)](#getYCbCr-int-) | Gets YCbCr color with a specified number of bits per sample. |
| [getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)](#getYCbCr-int-int-int-) | Gets YCbCr color with a specified number of bits per sample. |
| [getCmyk(int bitsPerSample)](#getCmyk-int-) | Gets CMYK color with a specified number of bits per sample. |
| [getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)](#getCmyk-int-int-int-int-) | Gets CMYK color with a specified number of bits per sample. |
| [getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)](#getCmyka-int-int-int-int-int-) | Gets CMYKA color with a specified number of bits per sample. |
| [getYcck(int bitsPerSample)](#getYcck-int-) | Gets YCCK color with a specified number of bits per sample. |
| [getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)](#getCieLab-int-int-int-) | Gets CIE Lab color with a specified number of bits per sample. |
| [op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Inequality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-) | Returns result of non-equality for two `PixelDataFormat` classes. |
| [op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Equality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-) | Returns result of equality for two `PixelDataFormat` classes. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified `System.Object` is equal to this instance. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
| [toString()](#toString--) | Returns a `System.String` that represents this instance. |
### Grayscale {#Grayscale}
```
public static final PixelDataFormat Grayscale
```


Gets the [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) defined for 8 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval.

Value: The [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) defined for 8 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval.

### Grayscale16 {#Grayscale16}
```
public static final PixelDataFormat Grayscale16
```


Defined for 16 bits per pixel with up to 16 bits representing grayscale intensity.

### getRgb32Bpp() {#getRgb32Bpp--}
```
public static PixelDataFormat getRgb32Bpp()
```


Gets the `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getCmyk() {#getCmyk--}
```
public static PixelDataFormat getCmyk()
```


Gets the `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.
### getCmyka() {#getCmyka--}
```
public static PixelDataFormat getCmyka()
```


Gets the acmyk.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 40 bits per pixel with 8 bits for each of the alpha, cyan, magenta, yellow and black.
### getRgb24Bpp() {#getRgb24Bpp--}
```
public static PixelDataFormat getRgb24Bpp()
```


Gets the `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb16Bpp555() {#getRgb16Bpp555--}
```
public static PixelDataFormat getRgb16Bpp555()
```


Gets the `PixelDataFormat` defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.
### getRgb16Bpp565() {#getRgb16Bpp565--}
```
public static PixelDataFormat getRgb16Bpp565()
```


Gets the `PixelDataFormat` defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.
### getRgbIndexed8Bpp() {#getRgbIndexed8Bpp--}
```
public static PixelDataFormat getRgbIndexed8Bpp()
```


Gets the `PixelDataFormat` defined for indexed 8 bit per color. The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used. Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 8 bit per color.
### getRgbIndexed4Bpp() {#getRgbIndexed4Bpp--}
```
public static PixelDataFormat getRgbIndexed4Bpp()
```


Gets the `PixelDataFormat` defined for indexed 4 bit per color. The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used. Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 4 bit per color.
### getRgbIndexed2Bpp() {#getRgbIndexed2Bpp--}
```
public static PixelDataFormat getRgbIndexed2Bpp()
```


Gets the `PixelDataFormat` defined for indexed 2 bit per color. The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used. Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 2 bit per color.
### getRgbIndexed1Bpp() {#getRgbIndexed1Bpp--}
```
public static PixelDataFormat getRgbIndexed1Bpp()
```


Gets the `PixelDataFormat` defined for indexed 1 bit per color. The indexed pixel data storage is intended to allow data storage and retrieval everywhere the color palette is used. Use with caution, because may require conversion from one palette to another or from RGBA to indexed color model.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 1 bit per color.
### getYCbCr() {#getYCbCr--}
```
public static PixelDataFormat getYCbCr()
```


Gets the `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.
### getYcck() {#getYcck--}
```
public static PixelDataFormat getYcck()
```


Gets the `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.
### getRgba32Bpp() {#getRgba32Bpp--}
```
public static PixelDataFormat getRgba32Bpp()
```


Gets the `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgb24BppPng() {#getRgb24BppPng--}
```
public static PixelDataFormat getRgb24BppPng()
```


Gets the `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getGrayscaleAlpha() {#getGrayscaleAlpha--}
```
public static PixelDataFormat getGrayscaleAlpha()
```


Gets the `PixelDataFormat` defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Gets the pixel format.

**Returns:**
int - The pixel format.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Gets the bits per pixel.

**Returns:**
int - The bits per pixel.
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Gets the channels count.

**Returns:**
int - The channels count.
### getChannelBits() {#getChannelBits--}
```
public int[] getChannelBits()
```


Gets the bits count for each channel.

**Returns:**
int[] - The channel bits.
### getCaption() {#getCaption--}
```
public String getCaption()
```


Gets the pixel data format caption.

**Returns:**
java.lang.String
### getGrayscale(int bitsPerSample) {#getGrayscale-int-}
```
public static PixelDataFormat getGrayscale(int bitsPerSample)
```


Gets Grayscale color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | The number of bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The Grayscale color.
### getGrayscaleAlpha(int bitsPerSample) {#getGrayscaleAlpha-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample)
```


Gets GrayscaleAlpha color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | The number of bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits) {#getGrayscaleAlpha-int-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)
```


Gets GrayscaleAlpha color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | The number of bits per sample. |
| alphaChannelBits | int | The number of bits per sample in the alpha channel. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The GrayscaleAlpha color.
### getRgb(int bitsPerSample) {#getRgb-int-}
```
public static PixelDataFormat getRgb(int bitsPerSample)
```


Gets RGB color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | The number of bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGB color.
### getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel) {#getRgb-int-int-int-}
```
public static PixelDataFormat getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)
```


Gets RGB color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerRedChannel | int | The number of bits per Red channel. |
| bitsPerGreenChannel | int | The number of bits per Green channel. |
| bitsPerBlueChannel | int | The number of bits per Blue channel. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGB color.
### getRgba(int bitsPerSample) {#getRgba-int-}
```
public static PixelDataFormat getRgba(int bitsPerSample)
```


Gets RGBA color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | The number of bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGBA color.
### getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel) {#getRgba-int-int-int-int-}
```
public static PixelDataFormat getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)
```


Gets RGBA color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerRedChannel | int | The number of bits per Red channel. |
| bitsPerGreenChannel | int | The number of bits per Green channel. |
| bitsPerBlueChannel | int | The number of bits per Blue channel. |
| bitsPerAlphaChannel | int | The number of bits per Alpha channel. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGBA color.
### getRgbIndexed(int bitsPerSample) {#getRgbIndexed-int-}
```
public static PixelDataFormat getRgbIndexed(int bitsPerSample)
```


Gets BGRA indexed color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | The number of bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGRA color.
### getBgra(int bitsPerSample) {#getBgra-int-}
```
public static PixelDataFormat getBgra(int bitsPerSample)
```


Gets BGRA color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | The number of bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGRA color.
### getBgr(int bitsPerSample) {#getBgr-int-}
```
public static PixelDataFormat getBgr(int bitsPerSample)
```


Gets BGR color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | The number of bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGR color.
### getYCbCr(int bitsPerSample) {#getYCbCr-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerSample)
```


Gets YCbCr color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | The number of bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCbCr color.
### getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr) {#getYCbCr-int-int-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)
```


Gets YCbCr color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerY | int | The number of bits per Y channel. |
| bitsPerCb | int | The number of bits per Cb channel. |
| bitsPerCr | int | The number of bits per Cr channel. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCbCr color.
### getCmyk(int bitsPerSample) {#getCmyk-int-}
```
public static PixelDataFormat getCmyk(int bitsPerSample)
```


Gets CMYK color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | The number of bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel) {#getCmyk-int-int-int-int-}
```
public static PixelDataFormat getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)
```


Gets CMYK color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerCyanChannel | int | The number of bits per Cyan channel. |
| bitsPerMagentaChannel | int | The number of bits per Magenta channel. |
| bitsPerYellowChannel | int | The number of bits per Yellow channel. |
| bitsPerKeyChannel | int | The number of bits per Key channel. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel) {#getCmyka-int-int-int-int-int-}
```
public static PixelDataFormat getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)
```


Gets CMYKA color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerCyanChannel | int | The number of bits per Cyan channel. |
| bitsPerMagentaChannel | int | The number of bits per Magenta channel. |
| bitsPerYellowChannel | int | The number of bits per Yellow channel. |
| bitsPerKeyChannel | int | The number of bits per Key channel. |
| bitsPerAlphaChannel | int | The number of bits per Alpha channel. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getYcck(int bitsPerSample) {#getYcck-int-}
```
public static PixelDataFormat getYcck(int bitsPerSample)
```


Gets YCCK color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | The number of bits per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCCK color.
### getCieLab(int bitsPerL, int bitsPerA, int bitsPerB) {#getCieLab-int-int-int-}
```
public static PixelDataFormat getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)
```


Gets CIE Lab color with a specified number of bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitsPerL | int | The number of bits per L channel. |
| bitsPerA | int | The number of bits per A channel. |
| bitsPerB | int | The number of bits per B channel. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CIE Lab color.
### op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Inequality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public static boolean op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Returns result of non-equality for two `PixelDataFormat` classes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | The first `PixelDataFormat` to compare. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | The second `PixelDataFormat` to compare. |

**Returns:**
boolean - True if both `pixelFormat1` and `pixelFormat2` contain non-equal data or one of the parameters is null.
### op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Equality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public static boolean op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Returns result of equality for two `PixelDataFormat` classes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | The first `PixelDataFormat` to compare. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | The second `PixelDataFormat` to compare. |

**Returns:**
boolean - True if both `pixelFormat1` and `pixelFormat2` contain equal data or both parameters are null.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified `System.Object` is equal to this instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The `System.Object` to compare with this instance. |

**Returns:**
boolean - `true` if the specified `System.Object` is equal to this instance; otherwise, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this instance.

**Returns:**
int - A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.
### toString() {#toString--}
```
public String toString()
```


Returns a `System.String` that represents this instance.

**Returns:**
java.lang.String - A `System.String` that represents this instance.
