---
title: "WmfStretchDib"
second_title: "Aspose.Imaging för Java API-referens"
description: "wmf Stretch DIB-objektet."
type: docs
weight: 94
url: /sv/java/com.aspose.imaging.fileformats.wmf.objects/wmfstretchdib/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfStretchDib extends WmfObject
```

wmf Stretch DIB-objektet.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WmfStretchDib()](#WmfStretchDib--) | WMFs-posten. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Hämtar eller anger rasteroperationen. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Hämtar eller anger rasteroperationen. |
| [getColorUsage()](#getColorUsage--) | Hämtar eller anger färganvändningen. |
| [setColorUsage(int value)](#setColorUsage-int-) | Hämtar eller anger färganvändningen. |
| [getSrcHeight()](#getSrcHeight--) | Hämtar eller anger höjden på källan. |
| [setSrcHeight(short value)](#setSrcHeight-short-) | Hämtar eller anger höjden på källan. |
| [getSrcWidth()](#getSrcWidth--) | Hämtar eller anger bredden på källan. |
| [setSrcWidth(short value)](#setSrcWidth-short-) | Hämtar eller anger bredden på källan. |
| [getYSrc()](#getYSrc--) | Hämtar eller anger y-källan. |
| [setYSrc(short value)](#setYSrc-short-) | Hämtar eller anger y-källan. |
| [getXSrc()](#getXSrc--) | Hämtar eller anger x-källan. |
| [setXSrc(short value)](#setXSrc-short-) | Hämtar eller anger x-källan. |
| [getDestHeight()](#getDestHeight--) | Hämtar eller anger höjden på dest. |
| [setDestHeight(short value)](#setDestHeight-short-) | Hämtar eller anger höjden på dest. |
| [getDestWidth()](#getDestWidth--) | Hämtar eller anger bredden på dest. |
| [setDestWidth(short value)](#setDestWidth-short-) | Hämtar eller anger bredden på dest. |
| [getYDest()](#getYDest--) | Hämtar eller anger y dest. |
| [setYDest(short value)](#setYDest-short-) | Hämtar eller anger y dest. |
| [getXDest()](#getXDest--) | Hämtar eller anger x dest. |
| [setXDest(short value)](#setXDest-short-) | Hämtar eller anger x dest. |
| [getSourceBitmap()](#getSourceBitmap--) | Hämtar eller anger käll‑bitmapen. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Hämtar eller anger käll‑bitmapen. |
### WmfStretchDib() {#WmfStretchDib--}
```
public WmfStretchDib()
```


WMFs-posten.

### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Hämtar eller anger rasteroperationen.

Värde: Den aktuella penseln i uppspelningsenhetens kontext, och destinationspixlarna ska kombineras för att bilda den nya bilden. Denna kod MÅSTE vara ett av värdena i Ternary Raster Operation Enumeration (avsnitt 2.1.1.31).

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Hämtar eller anger rasteroperationen.

Värde: Den aktuella penseln i uppspelningsenhetens kontext, och destinationspixlarna ska kombineras för att bilda den nya bilden. Denna kod MÅSTE vara ett av värdena i Ternary Raster Operation Enumeration (avsnitt 2.1.1.31).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getColorUsage() {#getColorUsage--}
```
public int getColorUsage()
```


Hämtar eller anger färganvändningen.

Värde:

Fältet Colors i DIB innehåller explicita RGB‑värden eller index i en palett. Detta värde MÅSTE vara i `com.aspose.imaging.fileFormats.wmf.objects.wmfStretchDib.ColorUsage`

Enumeration (avsnitt 2.1.1.6).

**Returns:**
int
### setColorUsage(int value) {#setColorUsage-int-}
```
public void setColorUsage(int value)
```


Hämtar eller anger färganvändningen.

Värde:

Fältet Colors i DIB innehåller explicita RGB‑värden eller index i en palett. Detta värde MÅSTE vara i `com.aspose.imaging.fileFormats.wmf.objects.wmfStretchDib.ColorUsage`

Enumeration (avsnitt 2.1.1.6).

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

Värde: Bredden, i logiska enheter, för källrektangeln

**Returns:**
short
### setSrcWidth(short value) {#setSrcWidth-short-}
```
public void setSrcWidth(short value)
```


Hämtar eller anger bredden på källan.

Värde: Bredden, i logiska enheter, för källrektangeln

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getYSrc() {#getYSrc--}
```
public short getYSrc()
```


Hämtar eller anger y-källan.

Värde: Y-koordinaten, i logiska enheter, för det övre vänstra hörnet av källrektangeln.

**Returns:**
short
### setYSrc(short value) {#setYSrc-short-}
```
public void setYSrc(short value)
```


Hämtar eller anger y-källan.

Värde: Y-koordinaten, i logiska enheter, för det övre vänstra hörnet av källrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getXSrc() {#getXSrc--}
```
public short getXSrc()
```


Hämtar eller anger x-källan.

Värde: X-koordinaten, i logiska enheter, för det övre vänstra hörnet av källrektangeln.

**Returns:**
short
### setXSrc(short value) {#setXSrc-short-}
```
public void setXSrc(short value)
```


Hämtar eller anger x-källan.

Värde: X-koordinaten, i logiska enheter, för det övre vänstra hörnet av källrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

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

### getYDest() {#getYDest--}
```
public short getYDest()
```


Hämtar eller anger y dest.

Värde: Y-koordinaten, i logiska enheter, för det övre vänstra hörnet av destinationsrektangeln.

**Returns:**
short
### setYDest(short value) {#setYDest-short-}
```
public void setYDest(short value)
```


Hämtar eller anger y dest.

Värde: Y-koordinaten, i logiska enheter, för det övre vänstra hörnet av destinationsrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getXDest() {#getXDest--}
```
public short getXDest()
```


Hämtar eller anger x dest.

Värde: X-koordinaten, i logiska enheter, för det övre vänstra hörnet av destinationsrektangeln.

**Returns:**
short
### setXDest(short value) {#setXDest-short-}
```
public void setXDest(short value)
```


Hämtar eller anger x dest.

Värde: X-koordinaten, i logiska enheter, för det övre vänstra hörnet av destinationsrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Hämtar eller anger käll‑bitmapen.

Värde: Källbitmapen.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Hämtar eller anger käll‑bitmapen.

Värde: Källbitmapen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

