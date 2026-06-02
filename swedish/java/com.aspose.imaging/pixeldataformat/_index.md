---
title: "PixelDataFormat"
second_title: "Aspose.Imaging för Java API-referens"
description: "Pixeldataformatet."
type: docs
weight: 84
url: /sv/java/com.aspose.imaging/pixeldataformat/
---
**Inheritance:**
java.lang.Object
```
public class PixelDataFormat
```

Pixeldataformatet. Detta är ett oföränderligt objekt.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Grayscale](#Grayscale) | Hämtar [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) definierad för 8 bitar per pixel med 8 bitar som representerar gråskaleintensitet i intervallet 0-255. |
| [Grayscale16](#Grayscale16) | Definierad för 16 bitar per pixel med upp till 16 bitar som representerar gråskaleintensitet. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRgb32Bpp()](#getRgb32Bpp--) | Hämtar `PixelDataFormat` definierad för 32 bitar per pixel med 8 bitar för varje av alfa, röd, grön och blå. |
| [getCmyk()](#getCmyk--) | Hämtar `PixelDataFormat` definierad för 32 bitar per pixel med 8 bitar för varje av cyan, magenta, gul och svart. |
| [getCmyka()](#getCmyka--) | Hämtar acmyk. |
| [getRgb24Bpp()](#getRgb24Bpp--) | Hämtar `PixelDataFormat` definierad för 24 bitar per pixel med 8 bitar för varje av alfa, röd, grön och blå, alfa är inte definierad. |
| [getRgb16Bpp555()](#getRgb16Bpp555--) | Hämtar `PixelDataFormat` definierad för 16 bitar per pixel med 5 bitar för varje av röd, grön och blå, alfa är inte definierad. |
| [getRgb16Bpp565()](#getRgb16Bpp565--) | Hämtar `PixelDataFormat` definierad för 16 bitar per pixel med 5 bitar för röd, 6 bitar för grön och 5 bitar för blå, alfa är inte definierad. |
| [getRgbIndexed8Bpp()](#getRgbIndexed8Bpp--) | Hämtar `PixelDataFormat` definierad för indexerad 8 bit per färg. |
| [getRgbIndexed4Bpp()](#getRgbIndexed4Bpp--) | Hämtar `PixelDataFormat` definierad för indexerad 4 bit per färg. |
| [getRgbIndexed2Bpp()](#getRgbIndexed2Bpp--) | Hämtar `PixelDataFormat` definierad för indexerad 2 bit per färg. |
| [getRgbIndexed1Bpp()](#getRgbIndexed1Bpp--) | Hämtar `PixelDataFormat` definierad för indexerad 1 bit per färg. |
| [getYCbCr()](#getYCbCr--) | Hämtar `PixelDataFormat` definierad för 24 bitar per pixel med 8 bitar för varje av luma, blå-differens och röd-differens kromakomponenter. |
| [getYcck()](#getYcck--) | Hämtar `PixelDataFormat` definierad för 32 bitar per pixel med 8 bitar för varje av luma, blå-differens, röd-differens och svart kromakomponenter. |
| [getRgba32Bpp()](#getRgba32Bpp--) | Hämtar `PixelDataFormat` definierad för 32 bitar per pixel med 8 bitar för varje av alfa, röd, grön och blå. |
| [getRgb24BppPng()](#getRgb24BppPng--) | Hämtar `PixelDataFormat` definierad för 24 bitar per pixel med 8 bitar för varje av alfa, röd, grön och blå, alfa är inte definierad. |
| [getGrayscaleAlpha()](#getGrayscaleAlpha--) | Hämtar `PixelDataFormat` definierad för 16 bitar per pixel med 8 bitar som representerar gråskaleintensitet i intervallet 0-255 och en extra 8 bit alfa-komponent. |
| [getPixelFormat()](#getPixelFormat--) | Hämtar pixelformatet. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämtar bitar per pixel. |
| [getChannelsCount()](#getChannelsCount--) | Hämtar kanalantalet. |
| [getChannelBits()](#getChannelBits--) | Hämtar bitantalet för varje kanal. |
| [getCaption()](#getCaption--) | Hämtar bilddataformatets rubrik. |
| [getGrayscale(int bitsPerSample)](#getGrayscale-int-) | Hämtar gråskala-färg med ett specificerat antal bitar per prov. |
| [getGrayscaleAlpha(int bitsPerSample)](#getGrayscaleAlpha-int-) | Hämtar GrayscaleAlpha-färg med ett specificerat antal bitar per prov. |
| [getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)](#getGrayscaleAlpha-int-int-) | Hämtar GrayscaleAlpha-färg med ett specificerat antal bitar per prov. |
| [getRgb(int bitsPerSample)](#getRgb-int-) | Hämtar RGB-färg med ett specificerat antal bitar per prov. |
| [getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)](#getRgb-int-int-int-) | Hämtar RGB-färg med ett specificerat antal bitar per prov. |
| [getRgba(int bitsPerSample)](#getRgba-int-) | Hämtar RGBA-färg med ett specificerat antal bitar per prov. |
| [getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)](#getRgba-int-int-int-int-) | Hämtar RGBA-färg med ett specificerat antal bitar per prov. |
| [getRgbIndexed(int bitsPerSample)](#getRgbIndexed-int-) | Hämtar BGRA-indexerad färg med ett specificerat antal bitar per prov. |
| [getBgra(int bitsPerSample)](#getBgra-int-) | Hämtar BGRA-färg med ett specificerat antal bitar per prov. |
| [getBgr(int bitsPerSample)](#getBgr-int-) | Hämtar BGR-färg med ett specificerat antal bitar per prov. |
| [getYCbCr(int bitsPerSample)](#getYCbCr-int-) | Hämtar YCbCr-färg med ett specificerat antal bitar per prov. |
| [getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)](#getYCbCr-int-int-int-) | Hämtar YCbCr-färg med ett specificerat antal bitar per prov. |
| [getCmyk(int bitsPerSample)](#getCmyk-int-) | Hämtar CMYK-färg med ett specificerat antal bitar per prov. |
| [getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)](#getCmyk-int-int-int-int-) | Hämtar CMYK-färg med ett specificerat antal bitar per prov. |
| [getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)](#getCmyka-int-int-int-int-int-) | Hämtar CMYKA-färg med ett specificerat antal bitar per prov. |
| [getYcck(int bitsPerSample)](#getYcck-int-) | Hämtar YCCK-färg med ett specificerat antal bitar per prov. |
| [getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)](#getCieLab-int-int-int-) | Hämtar CIE Lab-färg med ett specificerat antal bitar per prov. |
| [op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Inequality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-) | Returnerar resultatet av icke-likhet för två `PixelDataFormat`-klasser. |
| [op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Equality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-) | Returnerar resultatet av likhet för två `PixelDataFormat`-klasser. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om det specificerade `System.Object` är lika med denna instans. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för detta objekt. |
| [toString()](#toString--) | Returnerar en `System.String` som representerar denna instans. |
### Grayscale {#Grayscale}
```
public static final PixelDataFormat Grayscale
```


Hämtar [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) definierad för 8 bitar per pixel med 8 bitar som representerar gråskaleintensitet i intervallet 0-255.

Värde: Den [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) som definieras för 8 bitar per pixel med 8 bitar som representerar gråskaleintensitet i intervallet 0‑255.

### Grayscale16 {#Grayscale16}
```
public static final PixelDataFormat Grayscale16
```


Definierad för 16 bitar per pixel med upp till 16 bitar som representerar gråskaleintensitet.

### getRgb32Bpp() {#getRgb32Bpp--}
```
public static PixelDataFormat getRgb32Bpp()
```


Hämtar `PixelDataFormat` definierad för 32 bitar per pixel med 8 bitar för varje av alfa, röd, grön och blå.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getCmyk() {#getCmyk--}
```
public static PixelDataFormat getCmyk()
```


Hämtar `PixelDataFormat` definierad för 32 bitar per pixel med 8 bitar för varje av cyan, magenta, gul och svart.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.
### getCmyka() {#getCmyka--}
```
public static PixelDataFormat getCmyka()
```


Hämtar acmyk.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 40 bits per pixel with 8 bits for each of the alpha, cyan, magenta, yellow and black.
### getRgb24Bpp() {#getRgb24Bpp--}
```
public static PixelDataFormat getRgb24Bpp()
```


Hämtar `PixelDataFormat` definierad för 24 bitar per pixel med 8 bitar för varje av alfa, röd, grön och blå, alfa är inte definierad.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb16Bpp555() {#getRgb16Bpp555--}
```
public static PixelDataFormat getRgb16Bpp555()
```


Hämtar `PixelDataFormat` definierad för 16 bitar per pixel med 5 bitar för varje av röd, grön och blå, alfa är inte definierad.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.
### getRgb16Bpp565() {#getRgb16Bpp565--}
```
public static PixelDataFormat getRgb16Bpp565()
```


Hämtar `PixelDataFormat` definierad för 16 bitar per pixel med 5 bitar för röd, 6 bitar för grön och 5 bitar för blå, alfa är inte definierad.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.
### getRgbIndexed8Bpp() {#getRgbIndexed8Bpp--}
```
public static PixelDataFormat getRgbIndexed8Bpp()
```


Hämtar `PixelDataFormat` som definieras för indexerad 8-bit per färg. Den indexerade pixeldata lagringen är avsedd att möjliggöra datalagring och hämtning överallt där färgpaletten används. Använd med försiktighet, eftersom det kan kräva konvertering från en palett till en annan eller från RGBA till en indexerad färgmodell.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 8 bit per color.
### getRgbIndexed4Bpp() {#getRgbIndexed4Bpp--}
```
public static PixelDataFormat getRgbIndexed4Bpp()
```


Hämtar `PixelDataFormat` som definieras för indexerad 4-bit per färg. Den indexerade pixeldata lagringen är avsedd att möjliggöra datalagring och hämtning överallt där färgpaletten används. Använd med försiktighet, eftersom det kan kräva konvertering från en palett till en annan eller från RGBA till en indexerad färgmodell.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 4 bit per color.
### getRgbIndexed2Bpp() {#getRgbIndexed2Bpp--}
```
public static PixelDataFormat getRgbIndexed2Bpp()
```


Hämtar `PixelDataFormat` som definieras för indexerad 2-bit per färg. Den indexerade pixeldata lagringen är avsedd att möjliggöra datalagring och hämtning överallt där färgpaletten används. Använd med försiktighet, eftersom det kan kräva konvertering från en palett till en annan eller från RGBA till en indexerad färgmodell.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 2 bit per color.
### getRgbIndexed1Bpp() {#getRgbIndexed1Bpp--}
```
public static PixelDataFormat getRgbIndexed1Bpp()
```


Hämtar `PixelDataFormat` som definieras för indexerad 1-bit per färg. Den indexerade pixeldata lagringen är avsedd att möjliggöra datalagring och hämtning överallt där färgpaletten används. Använd med försiktighet, eftersom det kan kräva konvertering från en palett till en annan eller från RGBA till en indexerad färgmodell.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 1 bit per color.
### getYCbCr() {#getYCbCr--}
```
public static PixelDataFormat getYCbCr()
```


Hämtar `PixelDataFormat` definierad för 24 bitar per pixel med 8 bitar för varje av luma, blå-differens och röd-differens kromakomponenter.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.
### getYcck() {#getYcck--}
```
public static PixelDataFormat getYcck()
```


Hämtar `PixelDataFormat` definierad för 32 bitar per pixel med 8 bitar för varje av luma, blå-differens, röd-differens och svart kromakomponenter.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.
### getRgba32Bpp() {#getRgba32Bpp--}
```
public static PixelDataFormat getRgba32Bpp()
```


Hämtar `PixelDataFormat` definierad för 32 bitar per pixel med 8 bitar för varje av alfa, röd, grön och blå.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgb24BppPng() {#getRgb24BppPng--}
```
public static PixelDataFormat getRgb24BppPng()
```


Hämtar `PixelDataFormat` definierad för 24 bitar per pixel med 8 bitar för varje av alfa, röd, grön och blå, alfa är inte definierad.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getGrayscaleAlpha() {#getGrayscaleAlpha--}
```
public static PixelDataFormat getGrayscaleAlpha()
```


Hämtar `PixelDataFormat` definierad för 16 bitar per pixel med 8 bitar som representerar gråskaleintensitet i intervallet 0-255 och en extra 8 bit alfa-komponent.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Hämtar pixelformatet.

**Returns:**
int - Pixelformatet.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Hämtar bitar per pixel.

**Returns:**
int - Bit per pixel.
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Hämtar kanalantalet.

**Returns:**
int - Antalet kanaler.
### getChannelBits() {#getChannelBits--}
```
public int[] getChannelBits()
```


Hämtar bitantalet för varje kanal.

**Returns:**
int[] - Kanalbitarna.
### getCaption() {#getCaption--}
```
public String getCaption()
```


Hämtar bilddataformatets rubrik.

**Returns:**
java.lang.String
### getGrayscale(int bitsPerSample) {#getGrayscale-int-}
```
public static PixelDataFormat getGrayscale(int bitsPerSample)
```


Hämtar gråskala-färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerSample | int | Antalet bitar per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The Grayscale color.
### getGrayscaleAlpha(int bitsPerSample) {#getGrayscaleAlpha-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample)
```


Hämtar GrayscaleAlpha-färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerSample | int | Antalet bitar per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits) {#getGrayscaleAlpha-int-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)
```


Hämtar GrayscaleAlpha-färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerSample | int | Antalet bitar per sample. |
| alphaChannelBits | int | Antalet bitar per sample i alfakanalen. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The GrayscaleAlpha color.
### getRgb(int bitsPerSample) {#getRgb-int-}
```
public static PixelDataFormat getRgb(int bitsPerSample)
```


Hämtar RGB-färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerSample | int | Antalet bitar per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGB color.
### getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel) {#getRgb-int-int-int-}
```
public static PixelDataFormat getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)
```


Hämtar RGB-färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerRedChannel | int | Antalet bitar per Red kanal. |
| bitsPerGreenChannel | int | Antalet bitar per Green kanal. |
| bitsPerBlueChannel | int | Antalet bitar per Blue kanal. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGB color.
### getRgba(int bitsPerSample) {#getRgba-int-}
```
public static PixelDataFormat getRgba(int bitsPerSample)
```


Hämtar RGBA-färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerSample | int | Antalet bitar per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGBA color.
### getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel) {#getRgba-int-int-int-int-}
```
public static PixelDataFormat getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)
```


Hämtar RGBA-färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerRedChannel | int | Antalet bitar per Red kanal. |
| bitsPerGreenChannel | int | Antalet bitar per Green kanal. |
| bitsPerBlueChannel | int | Antalet bitar per Blue kanal. |
| bitsPerAlphaChannel | int | Antalet bitar per Alpha kanal. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGBA color.
### getRgbIndexed(int bitsPerSample) {#getRgbIndexed-int-}
```
public static PixelDataFormat getRgbIndexed(int bitsPerSample)
```


Hämtar BGRA-indexerad färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerSample | int | Antalet bitar per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGRA color.
### getBgra(int bitsPerSample) {#getBgra-int-}
```
public static PixelDataFormat getBgra(int bitsPerSample)
```


Hämtar BGRA-färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerSample | int | Antalet bitar per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGRA color.
### getBgr(int bitsPerSample) {#getBgr-int-}
```
public static PixelDataFormat getBgr(int bitsPerSample)
```


Hämtar BGR-färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerSample | int | Antalet bitar per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGR color.
### getYCbCr(int bitsPerSample) {#getYCbCr-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerSample)
```


Hämtar YCbCr-färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerSample | int | Antalet bitar per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCbCr color.
### getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr) {#getYCbCr-int-int-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)
```


Hämtar YCbCr-färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerY | int | Antalet bitar per Y kanal. |
| bitsPerCb | int | Antalet bitar per Cb kanal. |
| bitsPerCr | int | Antalet bitar per Cr kanal. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCbCr color.
### getCmyk(int bitsPerSample) {#getCmyk-int-}
```
public static PixelDataFormat getCmyk(int bitsPerSample)
```


Hämtar CMYK-färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerSample | int | Antalet bitar per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel) {#getCmyk-int-int-int-int-}
```
public static PixelDataFormat getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)
```


Hämtar CMYK-färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerCyanChannel | int | Antalet bitar per Cyan kanal. |
| bitsPerMagentaChannel | int | Antalet bitar per Magenta kanal. |
| bitsPerYellowChannel | int | Antalet bitar per Gul kanal. |
| bitsPerKeyChannel | int | Antalet bitar per Nyckel kanal. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel) {#getCmyka-int-int-int-int-int-}
```
public static PixelDataFormat getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)
```


Hämtar CMYKA-färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerCyanChannel | int | Antalet bitar per Cyan kanal. |
| bitsPerMagentaChannel | int | Antalet bitar per Magenta kanal. |
| bitsPerYellowChannel | int | Antalet bitar per Gul kanal. |
| bitsPerKeyChannel | int | Antalet bitar per Nyckel kanal. |
| bitsPerAlphaChannel | int | Antalet bitar per Alpha kanal. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getYcck(int bitsPerSample) {#getYcck-int-}
```
public static PixelDataFormat getYcck(int bitsPerSample)
```


Hämtar YCCK-färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerSample | int | Antalet bitar per sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCCK color.
### getCieLab(int bitsPerL, int bitsPerA, int bitsPerB) {#getCieLab-int-int-int-}
```
public static PixelDataFormat getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)
```


Hämtar CIE Lab-färg med ett specificerat antal bitar per prov.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitsPerL | int | Antalet bitar per L-kanal. |
| bitsPerA | int | Antalet bitar per A-kanal. |
| bitsPerB | int | Antalet bitar per B-kanal. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CIE Lab color.
### op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Inequality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public static boolean op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Returnerar resultatet av icke-likhet för två `PixelDataFormat`-klasser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Den första `PixelDataFormat` att jämföra. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Den andra `PixelDataFormat` att jämföra. |

**Returns:**
boolean - Sant om både `pixelFormat1` och `pixelFormat2` innehåller icke lika data eller en av parametrarna är null.
### op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Equality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public static boolean op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Returnerar resultatet av likhet för två `PixelDataFormat`-klasser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Den första `PixelDataFormat` att jämföra. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Den andra `PixelDataFormat` att jämföra. |

**Returns:**
boolean - Sant om både `pixelFormat1` och `pixelFormat2` innehåller lika data eller båda parametrarna är null.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om det specificerade `System.Object` är lika med denna instans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Den `System.Object` att jämföra med denna instans. |

**Returns:**
boolean - `true` om det angivna `System.Object` är lika med denna instans; annars `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för detta objekt.

**Returns:**
int - En hashkod för denna instans, lämplig för användning i hash-algoritmer och datastrukturer som en hash‑tabell.
### toString() {#toString--}
```
public String toString()
```


Returnerar en `System.String` som representerar denna instans.

**Returns:**
java.lang.String - En `System.String` som representerar denna instans.
