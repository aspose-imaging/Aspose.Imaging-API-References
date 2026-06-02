---
title: "WmfStretchBlt"
second_title: "Aspose.Imaging för Java API-referens"
description: "META_STRETCHBLT‑posten specificerar överföringen av ett block pixlar enligt en rasteroperation med möjlig expansion eller sammandragning."
type: docs
weight: 93
url: /sv/java/com.aspose.imaging.fileformats.wmf.objects/wmfstretchblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfStretchBlt extends WmfObject
```

META\_STRETCHBLT-posten specificerar överföringen av ett block av pixlar enligt en rasteroperation, med möjlig expansion eller sammandragning.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WmfStretchBlt()](#WmfStretchBlt--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Hämtar eller anger rasteroperationen. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Hämtar eller anger rasteroperationen. |
| [getSrcHeight()](#getSrcHeight--) | Hämtar eller anger höjden på källan. |
| [setSrcHeight(short value)](#setSrcHeight-short-) | Hämtar eller anger höjden på källan. |
| [getSrcWidth()](#getSrcWidth--) | Hämtar eller anger bredden på källan. |
| [setSrcWidth(short value)](#setSrcWidth-short-) | Hämtar eller anger bredden på källan. |
| [getSrcPosition()](#getSrcPosition--) | Hämtar eller anger källpositionen. |
| [setSrcPosition(Point value)](#setSrcPosition-com.aspose.imaging.Point-) | Hämtar eller anger källpositionen. |
| [getDestHeight()](#getDestHeight--) | Hämtar eller anger höjden på dest. |
| [setDestHeight(short value)](#setDestHeight-short-) | Hämtar eller anger höjden på dest. |
| [getDestWidth()](#getDestWidth--) | Hämtar eller anger bredden på dest. |
| [setDestWidth(short value)](#setDestWidth-short-) | Hämtar eller anger bredden på dest. |
| [getDstPosition()](#getDstPosition--) | Hämtar eller anger DST‑positionen. |
| [setDstPosition(Point value)](#setDstPosition-com.aspose.imaging.Point-) | Hämtar eller anger DST‑positionen. |
| [getReserved()](#getReserved--) | Hämtar eller anger reserverade. |
| [setReserved(short value)](#setReserved-short-) | Hämtar eller anger reserverade. |
| [getBitmap()](#getBitmap--) | Hämtar eller anger bitmapen. |
| [setBitmap(WmfBitmap16 value)](#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-) | Hämtar eller anger bitmapen. |
### WmfStretchBlt() {#WmfStretchBlt--}
```
public WmfStretchBlt()
```


### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Hämtar eller anger rasteroperationen.

Värde: Källpixlarna, den aktuella penseln i uppspelningsenhetens kontext och målpixlarna ska kombineras för att bilda den nya bilden. Denna kod MÅSTE vara ett av värdena i Ternary Raster Operation Enumeration

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Hämtar eller anger rasteroperationen.

Värde: Källpixlarna, den aktuella penseln i uppspelningsenhetens kontext och målpixlarna ska kombineras för att bilda den nya bilden. Denna kod MÅSTE vara ett av värdena i Ternary Raster Operation Enumeration

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getSrcHeight() {#getSrcHeight--}
```
public short getSrcHeight()
```


Hämtar eller anger höjden på källan.

Värde: Höjden, i logiska enheter, för källrektangeln.

**Returns:**
short
### setSrcHeight(short value) {#setSrcHeight-short-}
```
public void setSrcHeight(short value)
```


Hämtar eller anger höjden på källan.

Värde: Höjden, i logiska enheter, för källrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getSrcWidth() {#getSrcWidth--}
```
public short getSrcWidth()
```


Hämtar eller anger bredden på källan.

Värde: Bredden, i logiska enheter, på källrektangeln.

**Returns:**
short
### setSrcWidth(short value) {#setSrcWidth-short-}
```
public void setSrcWidth(short value)
```


Hämtar eller anger bredden på källan.

Värde: Bredden, i logiska enheter, på källrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getSrcPosition() {#getSrcPosition--}
```
public Point getSrcPosition()
```


Hämtar eller anger källpositionen.

Värde: Källpositionen.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setSrcPosition(Point value) {#setSrcPosition-com.aspose.imaging.Point-}
```
public void setSrcPosition(Point value)
```


Hämtar eller anger källpositionen.

Värde: Källpositionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getDestHeight() {#getDestHeight--}
```
public short getDestHeight()
```


Hämtar eller anger höjden på dest.

Värde: Höjden, i logiska enheter, för destinationsrektangeln.

**Returns:**
short
### setDestHeight(short value) {#setDestHeight-short-}
```
public void setDestHeight(short value)
```


Hämtar eller anger höjden på dest.

Värde: Höjden, i logiska enheter, för destinationsrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getDestWidth() {#getDestWidth--}
```
public short getDestWidth()
```


Hämtar eller anger bredden på dest.

Värde: Bredden, i logiska enheter, för destinationsrektangeln.

**Returns:**
short
### setDestWidth(short value) {#setDestWidth-short-}
```
public void setDestWidth(short value)
```


Hämtar eller anger bredden på dest.

Värde: Bredden, i logiska enheter, för destinationsrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getDstPosition() {#getDstPosition--}
```
public Point getDstPosition()
```


Hämtar eller anger DST‑positionen.

Värde: DST‑positionen.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDstPosition(Point value) {#setDstPosition-com.aspose.imaging.Point-}
```
public void setDstPosition(Point value)
```


Hämtar eller anger DST‑positionen.

Värde: DST‑positionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getReserved() {#getReserved--}
```
public short getReserved()
```


Hämtar eller anger reserverade.

Värde: Det reserverade. Detta fält MÅSTE ignoreras.

**Returns:**
short
### setReserved(short value) {#setReserved-short-}
```
public void setReserved(short value)
```


Hämtar eller anger reserverade.

Värde: Det reserverade. Detta fält MÅSTE ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getBitmap() {#getBitmap--}
```
public WmfBitmap16 getBitmap()
```


Hämtar eller anger bitmapen.

Värde: Bitmappen.

**Returns:**
[WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16)
### setBitmap(WmfBitmap16 value) {#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-}
```
public void setBitmap(WmfBitmap16 value)
```


Hämtar eller anger bitmapen.

Värde: Bitmappen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16) |  |

