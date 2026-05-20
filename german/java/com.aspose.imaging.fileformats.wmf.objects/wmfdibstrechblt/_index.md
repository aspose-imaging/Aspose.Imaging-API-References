---
title: "WmfDibStrechBlt"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der META_DIBSTRETCHBLT-Datensatz gibt die Übertragung eines Blocks von Pixeln im geräteunabhängigen Format gemäß einer Rasteroperation mit möglicher Erweiterung oder Verkleinerung an."
type: docs
weight: 30
url: /de/java/com.aspose.imaging.fileformats.wmf.objects/wmfdibstrechblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfDibStrechBlt extends WmfObject
```

Der META\_DIBSTRETCHBLT-Datensatz gibt die Übertragung eines Pixelblocks im geräteunabhängigen Format gemäß einer Rasteroperation an, mit möglicher Vergrößerung oder Verkleinerung.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WmfDibStrechBlt()](#WmfDibStrechBlt--) | WMFs der Datensatz. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Liest oder setzt die Rasteroperation. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Liest oder setzt die Rasteroperation. |
| [getSrcHeight()](#getSrcHeight--) | Liest oder setzt die Höhe der Quelle. |
| [setSrcHeight(short value)](#setSrcHeight-short-) | Liest oder setzt die Höhe der Quelle. |
| [getSrcWidth()](#getSrcWidth--) | Ruft die Breite der Quelle ab oder legt sie fest. |
| [setSrcWidth(short value)](#setSrcWidth-short-) | Ruft die Breite der Quelle ab oder legt sie fest. |
| [getYSrc()](#getYSrc--) | Ruft die y-Quelle ab oder legt sie fest. |
| [setYSrc(short value)](#setYSrc-short-) | Ruft die y-Quelle ab oder legt sie fest. |
| [getXSrc()](#getXSrc--) | Ruft die x-Quelle ab oder legt sie fest. |
| [setXSrc(short value)](#setXSrc-short-) | Ruft die x-Quelle ab oder legt sie fest. |
| [getDestHeight()](#getDestHeight--) | Ruft die Höhe des Ziels ab oder legt sie fest. |
| [setDestHeight(short value)](#setDestHeight-short-) | Ruft die Höhe des Ziels ab oder legt sie fest. |
| [getDestWidth()](#getDestWidth--) | Ruft die Breite des Ziels ab oder legt sie fest. |
| [setDestWidth(short value)](#setDestWidth-short-) | Ruft die Breite des Ziels ab oder legt sie fest. |
| [getYDest()](#getYDest--) | Ruft das y-Ziel ab oder legt es fest. |
| [setYDest(short value)](#setYDest-short-) | Ruft das y-Ziel ab oder legt es fest. |
| [getXDest()](#getXDest--) | Ruft das x-Ziel ab oder legt es fest. |
| [setXDest(short value)](#setXDest-short-) | Ruft das x-Ziel ab oder legt es fest. |
| [getSourceBitmap()](#getSourceBitmap--) | Liest oder setzt das Quell-Bitmap. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Liest oder setzt das Quell-Bitmap. |
### WmfDibStrechBlt() {#WmfDibStrechBlt--}
```
public WmfDibStrechBlt()
```


WMFs der Datensatz.

### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Liest oder setzt die Rasteroperation.

Wert: Der aktuelle Pinsel im Wiedergabegeräte-Kontext, und die Zielpixel werden kombiniert, um das neue Bild zu erzeugen. Dieser Code MUSS einer der Werte in der Ternary Raster Operation Enumeration (Abschnitt 2.1.1.31) sein.

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Liest oder setzt die Rasteroperation.

Wert: Der aktuelle Pinsel im Wiedergabegeräte-Kontext, und die Zielpixel werden kombiniert, um das neue Bild zu erzeugen. Dieser Code MUSS einer der Werte in der Ternary Raster Operation Enumeration (Abschnitt 2.1.1.31) sein.

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

Wert: Die Breite des Quellrechtecks in logischen Einheiten

**Returns:**
short
### setSrcWidth(short value) {#setSrcWidth-short-}
```
public void setSrcWidth(short value)
```


Ruft die Breite der Quelle ab oder legt sie fest.

Wert: Die Breite des Quellrechtecks in logischen Einheiten

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getYSrc() {#getYSrc--}
```
public short getYSrc()
```


Ruft die y-Quelle ab oder legt sie fest.

Wert: Die y-Koordinate in logischen Einheiten der oberen linken Ecke des Quellrechtecks.

**Returns:**
short
### setYSrc(short value) {#setYSrc-short-}
```
public void setYSrc(short value)
```


Ruft die y-Quelle ab oder legt sie fest.

Wert: Die y-Koordinate in logischen Einheiten der oberen linken Ecke des Quellrechtecks.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getXSrc() {#getXSrc--}
```
public short getXSrc()
```


Ruft die x-Quelle ab oder legt sie fest.

Wert: Die x-Koordinate in logischen Einheiten der oberen linken Ecke des Quellrechtecks.

**Returns:**
short
### setXSrc(short value) {#setXSrc-short-}
```
public void setXSrc(short value)
```


Ruft die x-Quelle ab oder legt sie fest.

Wert: Die x-Koordinate in logischen Einheiten der oberen linken Ecke des Quellrechtecks.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

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

### getYDest() {#getYDest--}
```
public short getYDest()
```


Ruft das y-Ziel ab oder legt es fest.

Wert: Die y-Koordinate in logischen Einheiten der oberen linken Ecke des Zielrechtecks.

**Returns:**
short
### setYDest(short value) {#setYDest-short-}
```
public void setYDest(short value)
```


Ruft das y-Ziel ab oder legt es fest.

Wert: Die y-Koordinate in logischen Einheiten der oberen linken Ecke des Zielrechtecks.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getXDest() {#getXDest--}
```
public short getXDest()
```


Ruft das x-Ziel ab oder legt es fest.

Wert: Die x-Koordinate in logischen Einheiten der oberen linken Ecke des Zielrechtecks.

**Returns:**
short
### setXDest(short value) {#setXDest-short-}
```
public void setXDest(short value)
```


Ruft das x-Ziel ab oder legt es fest.

Wert: Die x-Koordinate in logischen Einheiten der oberen linken Ecke des Zielrechtecks.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Liest oder setzt das Quell-Bitmap.

Wert: Die Quell-Bitmap.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Liest oder setzt das Quell-Bitmap.

Wert: Die Quell-Bitmap.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

