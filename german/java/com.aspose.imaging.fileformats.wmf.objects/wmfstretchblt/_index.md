---
title: "WmfStretchBlt"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der META_STRETCHBLT‑Datensatz gibt die Übertragung eines Pixelblocks gemäß einer Rasteroperation mit möglicher Vergrößerung oder Verkleinerung an."
type: docs
weight: 93
url: /de/java/com.aspose.imaging.fileformats.wmf.objects/wmfstretchblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfStretchBlt extends WmfObject
```

Der META\_STRETCHBLT-Datensatz spezifiziert die Übertragung eines Pixelblocks gemäß einer Rasteroperation, mit möglicher Vergrößerung oder Verkleinerung.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WmfStretchBlt()](#WmfStretchBlt--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Liest oder setzt die Rasteroperation. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Liest oder setzt die Rasteroperation. |
| [getSrcHeight()](#getSrcHeight--) | Liest oder setzt die Höhe der Quelle. |
| [setSrcHeight(short value)](#setSrcHeight-short-) | Liest oder setzt die Höhe der Quelle. |
| [getSrcWidth()](#getSrcWidth--) | Ruft die Breite der Quelle ab oder legt sie fest. |
| [setSrcWidth(short value)](#setSrcWidth-short-) | Ruft die Breite der Quelle ab oder legt sie fest. |
| [getSrcPosition()](#getSrcPosition--) | Liest oder setzt die Quellposition. |
| [setSrcPosition(Point value)](#setSrcPosition-com.aspose.imaging.Point-) | Liest oder setzt die Quellposition. |
| [getDestHeight()](#getDestHeight--) | Ruft die Höhe des Ziels ab oder legt sie fest. |
| [setDestHeight(short value)](#setDestHeight-short-) | Ruft die Höhe des Ziels ab oder legt sie fest. |
| [getDestWidth()](#getDestWidth--) | Ruft die Breite des Ziels ab oder legt sie fest. |
| [setDestWidth(short value)](#setDestWidth-short-) | Ruft die Breite des Ziels ab oder legt sie fest. |
| [getDstPosition()](#getDstPosition--) | Liest oder setzt die Zielposition. |
| [setDstPosition(Point value)](#setDstPosition-com.aspose.imaging.Point-) | Liest oder setzt die Zielposition. |
| [getReserved()](#getReserved--) | Liest oder setzt das Reservierte. |
| [setReserved(short value)](#setReserved-short-) | Liest oder setzt das Reservierte. |
| [getBitmap()](#getBitmap--) | Liest oder setzt das Bitmap. |
| [setBitmap(WmfBitmap16 value)](#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-) | Liest oder setzt das Bitmap. |
### WmfStretchBlt() {#WmfStretchBlt--}
```
public WmfStretchBlt()
```


### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Liest oder setzt die Rasteroperation.

Wert: Die Quellpixel, der aktuelle Pinsel im Wiedergabegeräte‑Kontext und die Zielpixel werden kombiniert, um das neue Bild zu erzeugen. Dieser Code MUSS einer der Werte in der Ternary Raster Operation‑Aufzählung sein.

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Liest oder setzt die Rasteroperation.

Wert: Die Quellpixel, der aktuelle Pinsel im Wiedergabegeräte‑Kontext und die Zielpixel werden kombiniert, um das neue Bild zu erzeugen. Dieser Code MUSS einer der Werte in der Ternary Raster Operation‑Aufzählung sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSrcHeight() {#getSrcHeight--}
```
public short getSrcHeight()
```


Liest oder setzt die Höhe der Quelle.

Wert: Die Höhe des Quellrechtecks in logischen Einheiten.

**Returns:**
short
### setSrcHeight(short value) {#setSrcHeight-short-}
```
public void setSrcHeight(short value)
```


Liest oder setzt die Höhe der Quelle.

Wert: Die Höhe des Quellrechtecks in logischen Einheiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getSrcWidth() {#getSrcWidth--}
```
public short getSrcWidth()
```


Ruft die Breite der Quelle ab oder legt sie fest.

Wert: Die Breite des Quellrechtecks in logischen Einheiten.

**Returns:**
short
### setSrcWidth(short value) {#setSrcWidth-short-}
```
public void setSrcWidth(short value)
```


Ruft die Breite der Quelle ab oder legt sie fest.

Wert: Die Breite des Quellrechtecks in logischen Einheiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getSrcPosition() {#getSrcPosition--}
```
public Point getSrcPosition()
```


Liest oder setzt die Quellposition.

Wert: Die Quellposition.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setSrcPosition(Point value) {#setSrcPosition-com.aspose.imaging.Point-}
```
public void setSrcPosition(Point value)
```


Liest oder setzt die Quellposition.

Wert: Die Quellposition.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getDestHeight() {#getDestHeight--}
```
public short getDestHeight()
```


Ruft die Höhe des Ziels ab oder legt sie fest.

Wert: Die Höhe des Zielrechtecks in logischen Einheiten.

**Returns:**
short
### setDestHeight(short value) {#setDestHeight-short-}
```
public void setDestHeight(short value)
```


Ruft die Höhe des Ziels ab oder legt sie fest.

Wert: Die Höhe des Zielrechtecks in logischen Einheiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getDestWidth() {#getDestWidth--}
```
public short getDestWidth()
```


Ruft die Breite des Ziels ab oder legt sie fest.

Wert: Die Breite des Zielrechtecks in logischen Einheiten.

**Returns:**
short
### setDestWidth(short value) {#setDestWidth-short-}
```
public void setDestWidth(short value)
```


Ruft die Breite des Ziels ab oder legt sie fest.

Wert: Die Breite des Zielrechtecks in logischen Einheiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getDstPosition() {#getDstPosition--}
```
public Point getDstPosition()
```


Liest oder setzt die Zielposition.

Wert: Die DST‑Position.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDstPosition(Point value) {#setDstPosition-com.aspose.imaging.Point-}
```
public void setDstPosition(Point value)
```


Liest oder setzt die Zielposition.

Wert: Die DST‑Position.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getReserved() {#getReserved--}
```
public short getReserved()
```


Liest oder setzt das Reservierte.

Wert: Das reservierte. Dieses Feld MUSS ignoriert werden.

**Returns:**
short
### setReserved(short value) {#setReserved-short-}
```
public void setReserved(short value)
```


Liest oder setzt das Reservierte.

Wert: Das reservierte. Dieses Feld MUSS ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getBitmap() {#getBitmap--}
```
public WmfBitmap16 getBitmap()
```


Liest oder setzt das Bitmap.

Wert: Die Bitmap.

**Returns:**
[WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16)
### setBitmap(WmfBitmap16 value) {#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-}
```
public void setBitmap(WmfBitmap16 value)
```


Liest oder setzt das Bitmap.

Wert: Die Bitmap.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16) |  |

