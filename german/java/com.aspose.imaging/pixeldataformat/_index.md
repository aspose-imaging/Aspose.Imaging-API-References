---
title: "PixelDataFormat"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das Pixel‑Datenformat."
type: docs
weight: 84
url: /de/java/com.aspose.imaging/pixeldataformat/
---
**Inheritance:**
java.lang.Object
```
public class PixelDataFormat
```

Das Pixel-Datenformat. Dies ist ein unveränderliches Objekt.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Grayscale](#Grayscale) | Liefert das [PixelDataFormat](../../com.aspose.imaging/pixeldataformat), definiert für 8 Bit pro Pixel mit 8 Bit, die die Graustufenintensität im Intervall 0‑255 darstellen. |
| [Grayscale16](#Grayscale16) | Definiert für 16 Bit pro Pixel mit bis zu 16 Bit, die die Graustufenintensität darstellen. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRgb32Bpp()](#getRgb32Bpp--) | Liefert das `PixelDataFormat`, definiert für 32 Bit pro Pixel mit je 8 Bit für Alpha, Rot, Grün und Blau. |
| [getCmyk()](#getCmyk--) | Liefert das `PixelDataFormat`, definiert für 32 Bit pro Pixel mit je 8 Bit für Cyan, Magenta, Gelb und Schwarz. |
| [getCmyka()](#getCmyka--) | Liefert das acmyk. |
| [getRgb24Bpp()](#getRgb24Bpp--) | Liefert das `PixelDataFormat`, definiert für 24 Bit pro Pixel mit je 8 Bit für Alpha, Rot, Grün und Blau, Alpha ist nicht definiert. |
| [getRgb16Bpp555()](#getRgb16Bpp555--) | Liefert das `PixelDataFormat`, definiert für 16 Bit pro Pixel mit je 5 Bit für Rot, Grün und Blau, Alpha ist nicht definiert. |
| [getRgb16Bpp565()](#getRgb16Bpp565--) | Liefert das `PixelDataFormat`, definiert für 16 Bit pro Pixel mit 5 Bit für Rot, 6 Bit für Grün und 5 Bit für Blau, Alpha ist nicht definiert. |
| [getRgbIndexed8Bpp()](#getRgbIndexed8Bpp--) | Liefert das `PixelDataFormat`, definiert für indizierte 8‑Bit pro Farbe. |
| [getRgbIndexed4Bpp()](#getRgbIndexed4Bpp--) | Liefert das `PixelDataFormat`, definiert für indizierte 4‑Bit pro Farbe. |
| [getRgbIndexed2Bpp()](#getRgbIndexed2Bpp--) | Liefert das `PixelDataFormat`, definiert für indizierte 2‑Bit pro Farbe. |
| [getRgbIndexed1Bpp()](#getRgbIndexed1Bpp--) | Liefert das `PixelDataFormat`, definiert für indizierte 1‑Bit pro Farbe. |
| [getYCbCr()](#getYCbCr--) | Liefert das `PixelDataFormat`, definiert für 24 Bit pro Pixel mit je 8 Bit für die Luma-, Blau‑Differenz‑ und Rot‑Differenz‑Chromakomponenten. |
| [getYcck()](#getYcck--) | Liefert das `PixelDataFormat`, definiert für 32 Bit pro Pixel mit je 8 Bit für die Luma-, Blau‑Differenz‑, Rot‑Differenz‑ und Schwarz‑Chromakomponenten. |
| [getRgba32Bpp()](#getRgba32Bpp--) | Liefert das `PixelDataFormat`, definiert für 32 Bit pro Pixel mit je 8 Bit für Alpha, Rot, Grün und Blau. |
| [getRgb24BppPng()](#getRgb24BppPng--) | Liefert das `PixelDataFormat`, definiert für 24 Bit pro Pixel mit je 8 Bit für Alpha, Rot, Grün und Blau, Alpha ist nicht definiert. |
| [getGrayscaleAlpha()](#getGrayscaleAlpha--) | Liefert das `PixelDataFormat`, definiert für 16 Bit pro Pixel mit 8 Bit, die die Graustufenintensität im Intervall 0‑255 darstellen, sowie einem zusätzlichen 8‑Bit‑Alpha‑Komponente. |
| [getPixelFormat()](#getPixelFormat--) | Liefert das Pixel-Format. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Liefert die Bits pro Pixel. |
| [getChannelsCount()](#getChannelsCount--) | Liefert die Kanalanzahl. |
| [getChannelBits()](#getChannelBits--) | Ermittelt die Bitanzahl für jeden Kanal. |
| [getCaption()](#getCaption--) | Ermittelt die Beschriftung des Pixel-Datenformats. |
| [getGrayscale(int bitsPerSample)](#getGrayscale-int-) | Ermittelt Graustufenfarbe mit einer angegebenen Bitanzahl pro Sample. |
| [getGrayscaleAlpha(int bitsPerSample)](#getGrayscaleAlpha-int-) | Ermittelt Graustufen‑Alpha‑Farbe mit einer angegebenen Bitanzahl pro Sample. |
| [getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)](#getGrayscaleAlpha-int-int-) | Ermittelt Graustufen‑Alpha‑Farbe mit einer angegebenen Bitanzahl pro Sample. |
| [getRgb(int bitsPerSample)](#getRgb-int-) | Ermittelt RGB‑Farbe mit einer angegebenen Bitanzahl pro Sample. |
| [getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)](#getRgb-int-int-int-) | Ermittelt RGB‑Farbe mit einer angegebenen Bitanzahl pro Sample. |
| [getRgba(int bitsPerSample)](#getRgba-int-) | Ermittelt RGBA‑Farbe mit einer angegebenen Bitanzahl pro Sample. |
| [getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)](#getRgba-int-int-int-int-) | Ermittelt RGBA‑Farbe mit einer angegebenen Bitanzahl pro Sample. |
| [getRgbIndexed(int bitsPerSample)](#getRgbIndexed-int-) | Ermittelt indizierte BGRA‑Farbe mit einer angegebenen Bitanzahl pro Sample. |
| [getBgra(int bitsPerSample)](#getBgra-int-) | Ermittelt BGRA‑Farbe mit einer angegebenen Bitanzahl pro Sample. |
| [getBgr(int bitsPerSample)](#getBgr-int-) | Ermittelt BGR‑Farbe mit einer angegebenen Bitanzahl pro Sample. |
| [getYCbCr(int bitsPerSample)](#getYCbCr-int-) | Ermittelt YCbCr‑Farbe mit einer angegebenen Bitanzahl pro Sample. |
| [getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)](#getYCbCr-int-int-int-) | Ermittelt YCbCr‑Farbe mit einer angegebenen Bitanzahl pro Sample. |
| [getCmyk(int bitsPerSample)](#getCmyk-int-) | Ermittelt CMYK‑Farbe mit einer angegebenen Bitanzahl pro Sample. |
| [getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)](#getCmyk-int-int-int-int-) | Ermittelt CMYK‑Farbe mit einer angegebenen Bitanzahl pro Sample. |
| [getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)](#getCmyka-int-int-int-int-int-) | Ermittelt CMYKA‑Farbe mit einer angegebenen Bitanzahl pro Sample. |
| [getYcck(int bitsPerSample)](#getYcck-int-) | Ermittelt YCCK‑Farbe mit einer angegebenen Bitanzahl pro Sample. |
| [getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)](#getCieLab-int-int-int-) | Ermittelt CIE‑Lab‑Farbe mit einer angegebenen Bitanzahl pro Sample. |
| [op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Inequality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-) | Gibt das Ergebnis der Ungleichheit für zwei `PixelDataFormat`‑Klassen zurück. |
| [op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Equality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-) | Gibt das Ergebnis der Gleichheit für zwei `PixelDataFormat`‑Klassen zurück. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene `System.Object` gleich dieser Instanz ist. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese Instanz zurück. |
| [toString()](#toString--) | Gibt einen `System.String` zurück, der diese Instanz darstellt. |
### Grayscale {#Grayscale}
```
public static final PixelDataFormat Grayscale
```


Liefert das [PixelDataFormat](../../com.aspose.imaging/pixeldataformat), definiert für 8 Bit pro Pixel mit 8 Bit, die die Graustufenintensität im Intervall 0‑255 darstellen.

Wert: Das [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) definiert für 8 Bit pro Pixel, wobei 8 Bit die Graustufenintensität im Intervall 0‑255 darstellen.

### Grayscale16 {#Grayscale16}
```
public static final PixelDataFormat Grayscale16
```


Definiert für 16 Bit pro Pixel mit bis zu 16 Bit, die die Graustufenintensität darstellen.

### getRgb32Bpp() {#getRgb32Bpp--}
```
public static PixelDataFormat getRgb32Bpp()
```


Liefert das `PixelDataFormat`, definiert für 32 Bit pro Pixel mit je 8 Bit für Alpha, Rot, Grün und Blau.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getCmyk() {#getCmyk--}
```
public static PixelDataFormat getCmyk()
```


Liefert das `PixelDataFormat`, definiert für 32 Bit pro Pixel mit je 8 Bit für Cyan, Magenta, Gelb und Schwarz.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.
### getCmyka() {#getCmyka--}
```
public static PixelDataFormat getCmyka()
```


Liefert das acmyk.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 40 bits per pixel with 8 bits for each of the alpha, cyan, magenta, yellow and black.
### getRgb24Bpp() {#getRgb24Bpp--}
```
public static PixelDataFormat getRgb24Bpp()
```


Liefert das `PixelDataFormat`, definiert für 24 Bit pro Pixel mit je 8 Bit für Alpha, Rot, Grün und Blau, Alpha ist nicht definiert.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb16Bpp555() {#getRgb16Bpp555--}
```
public static PixelDataFormat getRgb16Bpp555()
```


Liefert das `PixelDataFormat`, definiert für 16 Bit pro Pixel mit je 5 Bit für Rot, Grün und Blau, Alpha ist nicht definiert.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.
### getRgb16Bpp565() {#getRgb16Bpp565--}
```
public static PixelDataFormat getRgb16Bpp565()
```


Liefert das `PixelDataFormat`, definiert für 16 Bit pro Pixel mit 5 Bit für Rot, 6 Bit für Grün und 5 Bit für Blau, Alpha ist nicht definiert.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.
### getRgbIndexed8Bpp() {#getRgbIndexed8Bpp--}
```
public static PixelDataFormat getRgbIndexed8Bpp()
```


Ermittelt das `PixelDataFormat`, das für indizierte 8‑Bit pro Farbe definiert ist. Der indizierte Pixel‑Datenspeicher ist dafür vorgesehen, Daten überall dort zu speichern und abzurufen, wo die Farbpalette verwendet wird. Vorsicht bei der Verwendung, da möglicherweise eine Konvertierung von einer Palette zur anderen oder von RGBA zu einem indizierten Farbmodell erforderlich ist.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 8 bit per color.
### getRgbIndexed4Bpp() {#getRgbIndexed4Bpp--}
```
public static PixelDataFormat getRgbIndexed4Bpp()
```


Ermittelt das `PixelDataFormat`, das für indizierte 4‑Bit pro Farbe definiert ist. Der indizierte Pixel‑Datenspeicher ist dafür vorgesehen, Daten überall dort zu speichern und abzurufen, wo die Farbpalette verwendet wird. Vorsicht bei der Verwendung, da möglicherweise eine Konvertierung von einer Palette zur anderen oder von RGBA zu einem indizierten Farbmodell erforderlich ist.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 4 bit per color.
### getRgbIndexed2Bpp() {#getRgbIndexed2Bpp--}
```
public static PixelDataFormat getRgbIndexed2Bpp()
```


Ermittelt das `PixelDataFormat`, das für indizierte 2‑Bit pro Farbe definiert ist. Der indizierte Pixel‑Datenspeicher ist dafür vorgesehen, Daten überall dort zu speichern und abzurufen, wo die Farbpalette verwendet wird. Vorsicht bei der Verwendung, da möglicherweise eine Konvertierung von einer Palette zur anderen oder von RGBA zu einem indizierten Farbmodell erforderlich ist.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 2 bit per color.
### getRgbIndexed1Bpp() {#getRgbIndexed1Bpp--}
```
public static PixelDataFormat getRgbIndexed1Bpp()
```


Ermittelt das `PixelDataFormat`, das für indizierte 1‑Bit pro Farbe definiert ist. Der indizierte Pixel‑Datenspeicher ist dafür vorgesehen, Daten überall dort zu speichern und abzurufen, wo die Farbpalette verwendet wird. Vorsicht bei der Verwendung, da möglicherweise eine Konvertierung von einer Palette zur anderen oder von RGBA zu einem indizierten Farbmodell erforderlich ist.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 1 bit per color.
### getYCbCr() {#getYCbCr--}
```
public static PixelDataFormat getYCbCr()
```


Liefert das `PixelDataFormat`, definiert für 24 Bit pro Pixel mit je 8 Bit für die Luma-, Blau‑Differenz‑ und Rot‑Differenz‑Chromakomponenten.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.
### getYcck() {#getYcck--}
```
public static PixelDataFormat getYcck()
```


Liefert das `PixelDataFormat`, definiert für 32 Bit pro Pixel mit je 8 Bit für die Luma-, Blau‑Differenz‑, Rot‑Differenz‑ und Schwarz‑Chromakomponenten.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.
### getRgba32Bpp() {#getRgba32Bpp--}
```
public static PixelDataFormat getRgba32Bpp()
```


Liefert das `PixelDataFormat`, definiert für 32 Bit pro Pixel mit je 8 Bit für Alpha, Rot, Grün und Blau.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgb24BppPng() {#getRgb24BppPng--}
```
public static PixelDataFormat getRgb24BppPng()
```


Liefert das `PixelDataFormat`, definiert für 24 Bit pro Pixel mit je 8 Bit für Alpha, Rot, Grün und Blau, Alpha ist nicht definiert.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getGrayscaleAlpha() {#getGrayscaleAlpha--}
```
public static PixelDataFormat getGrayscaleAlpha()
```


Liefert das `PixelDataFormat`, definiert für 16 Bit pro Pixel mit 8 Bit, die die Graustufenintensität im Intervall 0‑255 darstellen, sowie einem zusätzlichen 8‑Bit‑Alpha‑Komponente.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Liefert das Pixel-Format.

**Returns:**
int – Das Pixel-Format.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Liefert die Bits pro Pixel.

**Returns:**
int – Die Bits pro Pixel.
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Liefert die Kanalanzahl.

**Returns:**
int - Die Kanalanzahl.
### getChannelBits() {#getChannelBits--}
```
public int[] getChannelBits()
```


Ermittelt die Bitanzahl für jeden Kanal.

**Returns:**
int[] - Die Kanalbits.
### getCaption() {#getCaption--}
```
public String getCaption()
```


Ermittelt die Beschriftung des Pixel-Datenformats.

**Returns:**
java.lang.String
### getGrayscale(int bitsPerSample) {#getGrayscale-int-}
```
public static PixelDataFormat getGrayscale(int bitsPerSample)
```


Ermittelt Graustufenfarbe mit einer angegebenen Bitanzahl pro Sample.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerSample | int | Die Anzahl der Bits pro Sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The Grayscale color.
### getGrayscaleAlpha(int bitsPerSample) {#getGrayscaleAlpha-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample)
```


Ermittelt Graustufen‑Alpha‑Farbe mit einer angegebenen Bitanzahl pro Sample.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerSample | int | Die Anzahl der Bits pro Sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits) {#getGrayscaleAlpha-int-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)
```


Ermittelt Graustufen‑Alpha‑Farbe mit einer angegebenen Bitanzahl pro Sample.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerSample | int | Die Anzahl der Bits pro Sample. |
| alphaChannelBits | int | Die Anzahl der Bits pro Sample im Alpha-Kanal. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The GrayscaleAlpha color.
### getRgb(int bitsPerSample) {#getRgb-int-}
```
public static PixelDataFormat getRgb(int bitsPerSample)
```


Ermittelt RGB‑Farbe mit einer angegebenen Bitanzahl pro Sample.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerSample | int | Die Anzahl der Bits pro Sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGB color.
### getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel) {#getRgb-int-int-int-}
```
public static PixelDataFormat getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)
```


Ermittelt RGB‑Farbe mit einer angegebenen Bitanzahl pro Sample.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerRedChannel | int | Die Anzahl der Bits pro Rot-Kanal. |
| bitsPerGreenChannel | int | Die Anzahl der Bits pro Grün-Kanal. |
| bitsPerBlueChannel | int | Die Anzahl der Bits pro Blau-Kanal. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGB color.
### getRgba(int bitsPerSample) {#getRgba-int-}
```
public static PixelDataFormat getRgba(int bitsPerSample)
```


Ermittelt RGBA‑Farbe mit einer angegebenen Bitanzahl pro Sample.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerSample | int | Die Anzahl der Bits pro Sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGBA color.
### getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel) {#getRgba-int-int-int-int-}
```
public static PixelDataFormat getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)
```


Ermittelt RGBA‑Farbe mit einer angegebenen Bitanzahl pro Sample.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerRedChannel | int | Die Anzahl der Bits pro Rot-Kanal. |
| bitsPerGreenChannel | int | Die Anzahl der Bits pro Grün-Kanal. |
| bitsPerBlueChannel | int | Die Anzahl der Bits pro Blau-Kanal. |
| bitsPerAlphaChannel | int | Die Anzahl der Bits pro Alpha-Kanal. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGBA color.
### getRgbIndexed(int bitsPerSample) {#getRgbIndexed-int-}
```
public static PixelDataFormat getRgbIndexed(int bitsPerSample)
```


Ermittelt indizierte BGRA‑Farbe mit einer angegebenen Bitanzahl pro Sample.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerSample | int | Die Anzahl der Bits pro Sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGRA color.
### getBgra(int bitsPerSample) {#getBgra-int-}
```
public static PixelDataFormat getBgra(int bitsPerSample)
```


Ermittelt BGRA‑Farbe mit einer angegebenen Bitanzahl pro Sample.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerSample | int | Die Anzahl der Bits pro Sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGRA color.
### getBgr(int bitsPerSample) {#getBgr-int-}
```
public static PixelDataFormat getBgr(int bitsPerSample)
```


Ermittelt BGR‑Farbe mit einer angegebenen Bitanzahl pro Sample.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerSample | int | Die Anzahl der Bits pro Sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGR color.
### getYCbCr(int bitsPerSample) {#getYCbCr-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerSample)
```


Ermittelt YCbCr‑Farbe mit einer angegebenen Bitanzahl pro Sample.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerSample | int | Die Anzahl der Bits pro Sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCbCr color.
### getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr) {#getYCbCr-int-int-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)
```


Ermittelt YCbCr‑Farbe mit einer angegebenen Bitanzahl pro Sample.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerY | int | Die Anzahl der Bits pro Y-Kanal. |
| bitsPerCb | int | Die Anzahl der Bits pro Cb-Kanal. |
| bitsPerCr | int | Die Anzahl der Bits pro Cr-Kanal. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCbCr color.
### getCmyk(int bitsPerSample) {#getCmyk-int-}
```
public static PixelDataFormat getCmyk(int bitsPerSample)
```


Ermittelt CMYK‑Farbe mit einer angegebenen Bitanzahl pro Sample.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerSample | int | Die Anzahl der Bits pro Sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel) {#getCmyk-int-int-int-int-}
```
public static PixelDataFormat getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)
```


Ermittelt CMYK‑Farbe mit einer angegebenen Bitanzahl pro Sample.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerCyanChannel | int | Die Anzahl der Bits pro Cyan-Kanal. |
| bitsPerMagentaChannel | int | Die Anzahl der Bits pro Magenta-Kanal. |
| bitsPerYellowChannel | int | Die Anzahl der Bits pro Gelbkanal. |
| bitsPerKeyChannel | int | Die Anzahl der Bits pro Schlüsselkanal. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel) {#getCmyka-int-int-int-int-int-}
```
public static PixelDataFormat getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)
```


Ermittelt CMYKA‑Farbe mit einer angegebenen Bitanzahl pro Sample.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerCyanChannel | int | Die Anzahl der Bits pro Cyan-Kanal. |
| bitsPerMagentaChannel | int | Die Anzahl der Bits pro Magenta-Kanal. |
| bitsPerYellowChannel | int | Die Anzahl der Bits pro Gelbkanal. |
| bitsPerKeyChannel | int | Die Anzahl der Bits pro Schlüsselkanal. |
| bitsPerAlphaChannel | int | Die Anzahl der Bits pro Alpha-Kanal. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getYcck(int bitsPerSample) {#getYcck-int-}
```
public static PixelDataFormat getYcck(int bitsPerSample)
```


Ermittelt YCCK‑Farbe mit einer angegebenen Bitanzahl pro Sample.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerSample | int | Die Anzahl der Bits pro Sample. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCCK color.
### getCieLab(int bitsPerL, int bitsPerA, int bitsPerB) {#getCieLab-int-int-int-}
```
public static PixelDataFormat getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)
```


Ermittelt CIE‑Lab‑Farbe mit einer angegebenen Bitanzahl pro Sample.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bitsPerL | int | Die Anzahl der Bits pro L-Kanal. |
| bitsPerA | int | Die Anzahl der Bits pro A-Kanal. |
| bitsPerB | int | Die Anzahl der Bits pro B-Kanal. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CIE Lab color.
### op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Inequality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public static boolean op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Gibt das Ergebnis der Ungleichheit für zwei `PixelDataFormat`‑Klassen zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Das erste `PixelDataFormat` zum Vergleichen. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Das zweite `PixelDataFormat` zum Vergleichen. |

**Returns:**
boolean - Wahr, wenn sowohl `pixelFormat1` als auch `pixelFormat2` ungleiche Daten enthalten oder einer der Parameter null ist.
### op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Equality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public static boolean op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Gibt das Ergebnis der Gleichheit für zwei `PixelDataFormat`‑Klassen zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Das erste `PixelDataFormat` zum Vergleichen. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Das zweite `PixelDataFormat` zum Vergleichen. |

**Returns:**
boolean - Wahr, wenn sowohl `pixelFormat1` als auch `pixelFormat2` gleiche Daten enthalten oder beide Parameter null sind.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene `System.Object` gleich dieser Instanz ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das `System.Object` zum Vergleich mit dieser Instanz. |

**Returns:**
boolean - `true`, wenn das angegebene `System.Object` dieser Instanz gleich ist; andernfalls `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diese Instanz zurück.

**Returns:**
int – Ein Hashcode für diese Instanz, geeignet für den Einsatz in Hash‑Algorithmen und Datenstrukturen wie einer Hashtabelle.
### toString() {#toString--}
```
public String toString()
```


Gibt einen `System.String` zurück, der diese Instanz darstellt.

**Returns:**
java.lang.String - Ein `System.String`, der diese Instanz darstellt.
