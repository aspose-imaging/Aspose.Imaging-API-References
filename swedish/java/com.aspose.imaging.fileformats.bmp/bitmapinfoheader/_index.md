---
title: "BitmapInfoHeader"
second_title: "Aspose.Imaging för Java API-referens"
description: "Anger BITMAPINFOHEADER."
type: docs
weight: 12
url: /sv/java/com.aspose.imaging.fileformats.bmp/bitmapinfoheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader)
```
public class BitmapInfoHeader extends BitmapCoreHeader
```

Anger BITMAPINFOHEADER. OS-stöd: Windows NT, 3.1x eller senare. Funktioner: Lägger till 16 bpp- och 32 bpp-format. Lägger till RLE-komprimering.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBitmapCompression()](#getBitmapCompression--) | Hämtar bitmap-komprimering. |
| [setBitmapCompression(long value)](#setBitmapCompression-long-) | Ställer in bitmap-komprimering. |
| [getBitmapImageSize()](#getBitmapImageSize--) | Hämtar den specificerade bitmap‑rådatastorleken i byte. |
| [setBitmapImageSize(long value)](#setBitmapImageSize-long-) | Ställer in den specificerade bitmap‑rådatastorleken i byte. |
| [getBitmapXPelsPerMeter()](#getBitmapXPelsPerMeter--) | Hämtar horisontell pixelupplösning. |
| [setBitmapXPelsPerMeter(int value)](#setBitmapXPelsPerMeter-int-) | Hämtar eller ställer in horisontell pixelupplösning. |
| [getBitmapYPelsPerMeter()](#getBitmapYPelsPerMeter--) | Hämtar eller ställer in vertikal pixelupplösning. |
| [setBitmapYPelsPerMeter(int value)](#setBitmapYPelsPerMeter-int-) | Hämtar eller ställer in vertikal pixelupplösning. |
| [getBitmapColorsUsed()](#getBitmapColorsUsed--) | Hämtar antal palettfärger som används. |
| [setBitmapColorsUsed(long value)](#setBitmapColorsUsed-long-) | Hämtar eller ställer in antal palettfärger som används. |
| [getBitmapColorsImportant()](#getBitmapColorsImportant--) | Hämtar eller ställer in antal viktiga palettfärger. |
| [setBitmapColorsImportant(long value)](#setBitmapColorsImportant-long-) | Hämtar eller ställer in antal viktiga palettfärger. |
| [getExtraBitMasks()](#getExtraBitMasks--) | Hämtar eller ställer in de extra bitmaskerna. |
| [setExtraBitMasks(int[] value)](#setExtraBitMasks-int---) | Hämtar eller ställer in de extra bitmaskerna. |
### getBitmapCompression() {#getBitmapCompression--}
```
public long getBitmapCompression()
```


Hämtar bitmap-komprimering.

**Returns:**
long - bitmap-komprimering.
### setBitmapCompression(long value) {#setBitmapCompression-long-}
```
public void setBitmapCompression(long value)
```


Ställer in bitmap-komprimering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long | bitmap-komprimering. |

### getBitmapImageSize() {#getBitmapImageSize--}
```
public long getBitmapImageSize()
```


Hämtar den specificerade bitmap‑rådatastorleken i byte.

**Returns:**
long - bitmap‑rådatastorlek i byte.
### setBitmapImageSize(long value) {#setBitmapImageSize-long-}
```
public void setBitmapImageSize(long value)
```


Ställer in den specificerade bitmap‑rådatastorleken i byte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long | bitmap‑rådatastorlek i byte. |

### getBitmapXPelsPerMeter() {#getBitmapXPelsPerMeter--}
```
public int getBitmapXPelsPerMeter()
```


Hämtar horisontell pixelupplösning.

**Returns:**
int - horisontell pixelupplösning.
### setBitmapXPelsPerMeter(int value) {#setBitmapXPelsPerMeter-int-}
```
public void setBitmapXPelsPerMeter(int value)
```


Hämtar eller ställer in horisontell pixelupplösning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | horisontell pixelupplösning. |

### getBitmapYPelsPerMeter() {#getBitmapYPelsPerMeter--}
```
public int getBitmapYPelsPerMeter()
```


Hämtar eller ställer in vertikal pixelupplösning.

**Returns:**
int - vertikal pixelupplösning.
### setBitmapYPelsPerMeter(int value) {#setBitmapYPelsPerMeter-int-}
```
public void setBitmapYPelsPerMeter(int value)
```


Hämtar eller ställer in vertikal pixelupplösning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | vertikal pixelupplösning. |

### getBitmapColorsUsed() {#getBitmapColorsUsed--}
```
public long getBitmapColorsUsed()
```


Hämtar antal palettfärger som används.

**Returns:**
long - antal palettfärger som används.
### setBitmapColorsUsed(long value) {#setBitmapColorsUsed-long-}
```
public void setBitmapColorsUsed(long value)
```


Hämtar eller ställer in antal palettfärger som används.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long | antal palettfärger som används. |

### getBitmapColorsImportant() {#getBitmapColorsImportant--}
```
public long getBitmapColorsImportant()
```


Hämtar eller ställer in antal viktiga palettfärger.

**Returns:**
long - antal viktiga palettfärger.
### setBitmapColorsImportant(long value) {#setBitmapColorsImportant-long-}
```
public void setBitmapColorsImportant(long value)
```


Hämtar eller ställer in antal viktiga palettfärger.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long | antalet viktiga palettfärger. |

### getExtraBitMasks() {#getExtraBitMasks--}
```
public int[] getExtraBitMasks()
```


Hämtar eller anger de extra bitmaskerna. Förekommer endast om DIB-huvudet är BITMAPINFOHEADER och `BitmapCompression` är inställt på antingen `BitmapCompression.Bitfields` (RGB) eller `BitmapCompression.AlphaBitfields` (RGBA).

**Returns:**
int[] - de extra bitmaskerna.
### setExtraBitMasks(int[] value) {#setExtraBitMasks-int---}
```
public void setExtraBitMasks(int[] value)
```


Hämtar eller anger de extra bitmaskerna. Förekommer endast om DIB-huvudet är BITMAPINFOHEADER och `BitmapCompression` är inställt på antingen `BitmapCompression.Bitfields` (RGB) eller `BitmapCompression.AlphaBitfields` (RGBA).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] | de extra bitmaskerna. |

