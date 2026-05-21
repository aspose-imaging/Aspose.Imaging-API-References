---
title: "WmfDibBitBlt"
second_title: "Aspose.Imaging för Java API-referens"
description: "Posten META_DIBBITBLT specificerar överföringen av ett block av pixlar i enhetsoberoende format enligt en rasteroperation."
type: docs
weight: 28
url: /sv/java/com.aspose.imaging.fileformats.wmf.objects/wmfdibbitblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfDibBitBlt extends WmfObject
```

META\_DIBBITBLT-posten specificerar överföringen av ett block pixlar i enhetsoberoende format enligt en rasteroperation.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WmfDibBitBlt()](#WmfDibBitBlt--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Hämtar eller anger rasteroperationen. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Hämtar eller anger rasteroperationen. |
| [getSrcPos()](#getSrcPos--) | Hämtar eller anger källpositionen. |
| [setSrcPos(Point value)](#setSrcPos-com.aspose.imaging.Point-) | Hämtar eller anger källpositionen. |
| [getHeight()](#getHeight--) | Hämtar eller anger höjden. |
| [setHeight(short value)](#setHeight-short-) | Hämtar eller anger höjden. |
| [getWidth()](#getWidth--) | Hämtar eller anger bredden. |
| [setWidth(short value)](#setWidth-short-) | Hämtar eller anger bredden. |
| [getDstPos()](#getDstPos--) | Hämtar eller anger DST‑positionen. |
| [setDstPos(Point value)](#setDstPos-com.aspose.imaging.Point-) | Hämtar eller anger DST‑positionen. |
| [getReserved()](#getReserved--) | Hämtar eller anger reserverade. |
| [setReserved(int value)](#setReserved-int-) | Hämtar eller anger reserverade. |
| [getSource()](#getSource--) | Hämtar eller anger källan. |
| [setSource(WmfDeviceIndependentBitmap value)](#setSource-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Hämtar eller anger källan. |
### WmfDibBitBlt() {#WmfDibBitBlt--}
```
public WmfDibBitBlt()
```


### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Hämtar eller anger rasteroperationen.

Värde: Källpixlarna, den aktuella penseln i uppspelnings‑enhetskontexten och destinationspixlarna ska kombineras för att bilda den nya bilden. Denna kod MÅSTE vara ett av värdena i Ternary Raster Operation‑enumerationen (avsnitt 2.1.1.31).

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Hämtar eller anger rasteroperationen.

Värde: Källpixlarna, den aktuella penseln i uppspelnings‑enhetskontexten och destinationspixlarna ska kombineras för att bilda den nya bilden. Denna kod MÅSTE vara ett av värdena i Ternary Raster Operation‑enumerationen (avsnitt 2.1.1.31).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getSrcPos() {#getSrcPos--}
```
public Point getSrcPos()
```


Hämtar eller anger källpositionen.

Värde: Koordinaterna, i logiska enheter, för källrektangeln.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setSrcPos(Point value) {#setSrcPos-com.aspose.imaging.Point-}
```
public void setSrcPos(Point value)
```


Hämtar eller anger källpositionen.

Värde: Koordinaterna, i logiska enheter, för källrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getHeight() {#getHeight--}
```
public short getHeight()
```


Hämtar eller anger höjden.

Värde: Höjden, i logiska enheter, för käll‑ och destinationsrektanglarna.

**Returns:**
short
### setHeight(short value) {#setHeight-short-}
```
public void setHeight(short value)
```


Hämtar eller anger höjden.

Värde: Höjden, i logiska enheter, för käll‑ och destinationsrektanglarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getWidth() {#getWidth--}
```
public short getWidth()
```


Hämtar eller anger bredden.

Värde: Bredden, i logiska enheter, för käll‑ och destinationsrektanglarna.

**Returns:**
short
### setWidth(short value) {#setWidth-short-}
```
public void setWidth(short value)
```


Hämtar eller anger bredden.

Värde: Bredden, i logiska enheter, för käll‑ och destinationsrektanglarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getDstPos() {#getDstPos--}
```
public Point getDstPos()
```


Hämtar eller anger DST‑positionen.

Värde: Koordinaterna, i logiska enheter, för det övre vänstra hörnet av destinationsrektangeln.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDstPos(Point value) {#setDstPos-com.aspose.imaging.Point-}
```
public void setDstPos(Point value)
```


Hämtar eller anger DST‑positionen.

Värde: Koordinaterna, i logiska enheter, för det övre vänstra hörnet av destinationsrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getReserved() {#getReserved--}
```
public int getReserved()
```


Hämtar eller anger reserverade.

Värde: Reserverade.

**Returns:**
int
### setReserved(int value) {#setReserved-int-}
```
public void setReserved(int value)
```


Hämtar eller anger reserverade.

Värde: Reserverade.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getSource() {#getSource--}
```
public WmfDeviceIndependentBitmap getSource()
```


Hämtar eller anger källan.

Värde: Ett variabelstort DeviceIndependentBitmap‑objekt (avsnitt 2.2.2.9) som definierar bildinnehåll. Detta objekt MÅSTE specificeras, även om rasteroperationen inte kräver en källa.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSource(WmfDeviceIndependentBitmap value) {#setSource-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSource(WmfDeviceIndependentBitmap value)
```


Hämtar eller anger källan.

Värde: Ett variabelstort DeviceIndependentBitmap‑objekt (avsnitt 2.2.2.9) som definierar bildinnehåll. Detta objekt MÅSTE specificeras, även om rasteroperationen inte kräver en källa.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

