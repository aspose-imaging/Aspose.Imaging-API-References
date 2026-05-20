---
title: "BitmapInfoHeader"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Gibt BITMAPINFOHEADER an."
type: docs
weight: 12
url: /de/java/com.aspose.imaging.fileformats.bmp/bitmapinfoheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader)
```
public class BitmapInfoHeader extends BitmapCoreHeader
```

Gibt BITMAPINFOHEADER an. Betriebssystemunterstützung: Windows NT, 3.1x oder später. Funktionen: Fügt 16-bpp- und 32-bpp-Formate hinzu. Fügt RLE-Kompression hinzu.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBitmapCompression()](#getBitmapCompression--) | Liefert die Bitmap-Kompression. |
| [setBitmapCompression(long value)](#setBitmapCompression-long-) | Legt die Bitmap-Kompression fest. |
| [getBitmapImageSize()](#getBitmapImageSize--) | Liefert die angegebene Rohdaten-Größe der Bitmap in Bytes. |
| [setBitmapImageSize(long value)](#setBitmapImageSize-long-) | Legt die angegebene Rohdaten-Größe der Bitmap in Bytes fest. |
| [getBitmapXPelsPerMeter()](#getBitmapXPelsPerMeter--) | Liefert die horizontale Auflösung in Pixeln. |
| [setBitmapXPelsPerMeter(int value)](#setBitmapXPelsPerMeter-int-) | Liefert oder legt die horizontale Auflösung in Pixeln fest. |
| [getBitmapYPelsPerMeter()](#getBitmapYPelsPerMeter--) | Liefert oder legt die vertikale Auflösung in Pixeln fest. |
| [setBitmapYPelsPerMeter(int value)](#setBitmapYPelsPerMeter-int-) | Liefert oder legt die vertikale Auflösung in Pixeln fest. |
| [getBitmapColorsUsed()](#getBitmapColorsUsed--) | Liefert die Anzahl der verwendeten Palettenfarben. |
| [setBitmapColorsUsed(long value)](#setBitmapColorsUsed-long-) | Liefert oder legt die Anzahl der verwendeten Palettenfarben fest. |
| [getBitmapColorsImportant()](#getBitmapColorsImportant--) | Liefert oder legt die Anzahl der wichtigen Palettenfarben fest. |
| [setBitmapColorsImportant(long value)](#setBitmapColorsImportant-long-) | Liefert oder legt die Anzahl der wichtigen Palettenfarben fest. |
| [getExtraBitMasks()](#getExtraBitMasks--) | Liefert oder legt die zusätzlichen Bitmasken fest. |
| [setExtraBitMasks(int[] value)](#setExtraBitMasks-int---) | Liefert oder legt die zusätzlichen Bitmasken fest. |
### getBitmapCompression() {#getBitmapCompression--}
```
public long getBitmapCompression()
```


Liefert die Bitmap-Kompression.

**Returns:**
long - Bitmap-Kompression.
### setBitmapCompression(long value) {#setBitmapCompression-long-}
```
public void setBitmapCompression(long value)
```


Legt die Bitmap-Kompression fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long | Bitmap-Kompression. |

### getBitmapImageSize() {#getBitmapImageSize--}
```
public long getBitmapImageSize()
```


Liefert die angegebene Rohdaten-Größe der Bitmap in Bytes.

**Returns:**
long - Rohdaten-Größe der Bitmap in Bytes.
### setBitmapImageSize(long value) {#setBitmapImageSize-long-}
```
public void setBitmapImageSize(long value)
```


Legt die angegebene Rohdaten-Größe der Bitmap in Bytes fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long | Rohdaten-Größe der Bitmap in Bytes. |

### getBitmapXPelsPerMeter() {#getBitmapXPelsPerMeter--}
```
public int getBitmapXPelsPerMeter()
```


Liefert die horizontale Auflösung in Pixeln.

**Returns:**
int - horizontale Auflösung in Pixeln.
### setBitmapXPelsPerMeter(int value) {#setBitmapXPelsPerMeter-int-}
```
public void setBitmapXPelsPerMeter(int value)
```


Liefert oder legt die horizontale Auflösung in Pixeln fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | horizontale Auflösung in Pixeln. |

### getBitmapYPelsPerMeter() {#getBitmapYPelsPerMeter--}
```
public int getBitmapYPelsPerMeter()
```


Liefert oder legt die vertikale Auflösung in Pixeln fest.

**Returns:**
int - vertikale Auflösung in Pixeln.
### setBitmapYPelsPerMeter(int value) {#setBitmapYPelsPerMeter-int-}
```
public void setBitmapYPelsPerMeter(int value)
```


Liefert oder legt die vertikale Auflösung in Pixeln fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | vertikale Auflösung in Pixeln. |

### getBitmapColorsUsed() {#getBitmapColorsUsed--}
```
public long getBitmapColorsUsed()
```


Liefert die Anzahl der verwendeten Palettenfarben.

**Returns:**
long - Anzahl der verwendeten Palettenfarben.
### setBitmapColorsUsed(long value) {#setBitmapColorsUsed-long-}
```
public void setBitmapColorsUsed(long value)
```


Liefert oder legt die Anzahl der verwendeten Palettenfarben fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long | Anzahl der verwendeten Palettenfarben. |

### getBitmapColorsImportant() {#getBitmapColorsImportant--}
```
public long getBitmapColorsImportant()
```


Liefert oder legt die Anzahl der wichtigen Palettenfarben fest.

**Returns:**
long - Anzahl der wichtigen Palettenfarben.
### setBitmapColorsImportant(long value) {#setBitmapColorsImportant-long-}
```
public void setBitmapColorsImportant(long value)
```


Liefert oder legt die Anzahl der wichtigen Palettenfarben fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long | Anzahl wichtiger Palettenfarben. |

### getExtraBitMasks() {#getExtraBitMasks--}
```
public int[] getExtraBitMasks()
```


Liest oder setzt die zusätzlichen Bitmasken. Nur vorhanden, wenn der DIB-Header BITMAPINFOHEADER ist und die `BitmapCompression` entweder auf `BitmapCompression.Bitfields` (RGB) oder `BitmapCompression.AlphaBitfields` (RGBA) gesetzt ist.

**Returns:**
int[] - die zusätzlichen Bitmasken.
### setExtraBitMasks(int[] value) {#setExtraBitMasks-int---}
```
public void setExtraBitMasks(int[] value)
```


Liest oder setzt die zusätzlichen Bitmasken. Nur vorhanden, wenn der DIB-Header BITMAPINFOHEADER ist und die `BitmapCompression` entweder auf `BitmapCompression.Bitfields` (RGB) oder `BitmapCompression.AlphaBitfields` (RGBA) gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] | die zusätzlichen Bitmasken. |

