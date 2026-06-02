---
title: "WmfDibBitBlt"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der META_DIBBITBLT‑Datensatz gibt die Übertragung eines Pixelblocks im geräteunabhängigen Format gemäß einer Rasteroperation an."
type: docs
weight: 28
url: /de/java/com.aspose.imaging.fileformats.wmf.objects/wmfdibbitblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfDibBitBlt extends WmfObject
```

Der META\_DIBBITBLT-Datensatz gibt die Übertragung eines Pixelblocks im geräteunabhängigen Format gemäß einer Rasteroperation an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WmfDibBitBlt()](#WmfDibBitBlt--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Liest oder setzt die Rasteroperation. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Liest oder setzt die Rasteroperation. |
| [getSrcPos()](#getSrcPos--) | Liest oder setzt die Quellposition. |
| [setSrcPos(Point value)](#setSrcPos-com.aspose.imaging.Point-) | Liest oder setzt die Quellposition. |
| [getHeight()](#getHeight--) | Liest oder setzt die Höhe. |
| [setHeight(short value)](#setHeight-short-) | Liest oder setzt die Höhe. |
| [getWidth()](#getWidth--) | Liest oder setzt die Breite. |
| [setWidth(short value)](#setWidth-short-) | Liest oder setzt die Breite. |
| [getDstPos()](#getDstPos--) | Liest oder setzt die Zielposition. |
| [setDstPos(Point value)](#setDstPos-com.aspose.imaging.Point-) | Liest oder setzt die Zielposition. |
| [getReserved()](#getReserved--) | Liest oder setzt das Reservierte. |
| [setReserved(int value)](#setReserved-int-) | Liest oder setzt das Reservierte. |
| [getSource()](#getSource--) | Liest oder setzt die Quelle. |
| [setSource(WmfDeviceIndependentBitmap value)](#setSource-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Liest oder setzt die Quelle. |
### WmfDibBitBlt() {#WmfDibBitBlt--}
```
public WmfDibBitBlt()
```


### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Liest oder setzt die Rasteroperation.

Wert: Die Quellpixel, der aktuelle Pinsel im Wiedergabegeräte‑Kontext und die Zielpixel werden kombiniert, um das neue Bild zu erzeugen. Dieser Code MUSS einer der Werte in der Ternary Raster Operation‑Aufzählung (Abschnitt 2.1.1.31) sein.

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Liest oder setzt die Rasteroperation.

Wert: Die Quellpixel, der aktuelle Pinsel im Wiedergabegeräte‑Kontext und die Zielpixel werden kombiniert, um das neue Bild zu erzeugen. Dieser Code MUSS einer der Werte in der Ternary Raster Operation‑Aufzählung (Abschnitt 2.1.1.31) sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSrcPos() {#getSrcPos--}
```
public Point getSrcPos()
```


Liest oder setzt die Quellposition.

Wert: Die Koordinaten des Quellrechtecks in logischen Einheiten.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setSrcPos(Point value) {#setSrcPos-com.aspose.imaging.Point-}
```
public void setSrcPos(Point value)
```


Liest oder setzt die Quellposition.

Wert: Die Koordinaten des Quellrechtecks in logischen Einheiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getHeight() {#getHeight--}
```
public short getHeight()
```


Liest oder setzt die Höhe.

Wert: Die Höhe des Quell- und Zielrechtecks in logischen Einheiten.

**Returns:**
short
### setHeight(short value) {#setHeight-short-}
```
public void setHeight(short value)
```


Liest oder setzt die Höhe.

Wert: Die Höhe des Quell- und Zielrechtecks in logischen Einheiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getWidth() {#getWidth--}
```
public short getWidth()
```


Liest oder setzt die Breite.

Wert: Die Breite des Quell- und Zielrechtecks in logischen Einheiten.

**Returns:**
short
### setWidth(short value) {#setWidth-short-}
```
public void setWidth(short value)
```


Liest oder setzt die Breite.

Wert: Die Breite des Quell- und Zielrechtecks in logischen Einheiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getDstPos() {#getDstPos--}
```
public Point getDstPos()
```


Liest oder setzt die Zielposition.

Wert: Die Koordinaten der oberen linken Ecke des Zielrechtecks in logischen Einheiten.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDstPos(Point value) {#setDstPos-com.aspose.imaging.Point-}
```
public void setDstPos(Point value)
```


Liest oder setzt die Zielposition.

Wert: Die Koordinaten der oberen linken Ecke des Zielrechtecks in logischen Einheiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getReserved() {#getReserved--}
```
public int getReserved()
```


Liest oder setzt das Reservierte.

Wert: Das Reservierte.

**Returns:**
int
### setReserved(int value) {#setReserved-int-}
```
public void setReserved(int value)
```


Liest oder setzt das Reservierte.

Wert: Das Reservierte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSource() {#getSource--}
```
public WmfDeviceIndependentBitmap getSource()
```


Liest oder setzt die Quelle.

Wert: Ein variabelgroßes DeviceIndependentBitmap‑Objekt (Abschnitt 2.2.2.9), das den Bildinhalt definiert. Dieses Objekt MUSS angegeben werden, selbst wenn die Rasteroperation keine Quelle erfordert.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSource(WmfDeviceIndependentBitmap value) {#setSource-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSource(WmfDeviceIndependentBitmap value)
```


Liest oder setzt die Quelle.

Wert: Ein variabelgroßes DeviceIndependentBitmap‑Objekt (Abschnitt 2.2.2.9), das den Bildinhalt definiert. Dieses Objekt MUSS angegeben werden, selbst wenn die Rasteroperation keine Quelle erfordert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

