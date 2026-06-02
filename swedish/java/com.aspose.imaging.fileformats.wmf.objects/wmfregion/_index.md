---
title: "WmfRegion"
second_title: "Aspose.Imaging för Java API-referens"
description: "Region-objektet definierar en potentiellt icke-rektangulär form som definieras av en matris av skanningslinjer."
type: docs
weight: 62
url: /sv/java/com.aspose.imaging.fileformats.wmf.objects/wmfregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfRegion extends MetaObject
```

Region-objektet definierar en potentiellt icke-rektangulär form som definieras av en matris av scanlinjer.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WmfRegion()](#WmfRegion--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getNextInChain()](#getNextInChain--) | Hämtar eller anger nästa i kedjan. |
| [setNextInChain(short value)](#setNextInChain-short-) | Hämtar eller anger nästa i kedjan. |
| [getObjectType()](#getObjectType--) | Hämtar eller anger objektets typ. |
| [setObjectType(short value)](#setObjectType-short-) | Hämtar eller anger objektets typ. |
| [getObjectCount()](#getObjectCount--) | Hämtar eller anger objektantalet. |
| [setObjectCount(int value)](#setObjectCount-int-) | Hämtar eller anger objektantalet. |
| [getRegionSize()](#getRegionSize--) | Hämtar eller anger regionens storlek. |
| [setRegionSize(short value)](#setRegionSize-short-) | Hämtar eller anger regionens storlek. |
| [getScanCount()](#getScanCount--) | Hämtar eller anger antalet skanningar. |
| [setScanCount(short value)](#setScanCount-short-) | Hämtar eller anger antalet skanningar. |
| [getMaxScan()](#getMaxScan--) | Hämtar eller anger maximal skanning. |
| [setMaxScan(short value)](#setMaxScan-short-) | Hämtar eller anger maximal skanning. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Hämtar eller anger den omslutande rektangeln. |
| [setBoundingRectangle(Rectangle value)](#setBoundingRectangle-com.aspose.imaging.Rectangle-) | Hämtar eller anger den omslutande rektangeln. |
| [getAScans()](#getAScans--) | Hämtar eller anger en skanning. |
| [setAScans(WmfScanObject[] value)](#setAScans-com.aspose.imaging.fileformats.wmf.objects.WmfScanObject---) | Hämtar eller anger en skanning. |
### WmfRegion() {#WmfRegion--}
```
public WmfRegion()
```


### getNextInChain() {#getNextInChain--}
```
public short getNextInChain()
```


Hämtar eller anger nästa i kedjan.

Värde: Ett värde som MÅSTE ignoreras.

**Returns:**
short
### setNextInChain(short value) {#setNextInChain-short-}
```
public void setNextInChain(short value)
```


Hämtar eller anger nästa i kedjan.

Värde: Ett värde som MÅSTE ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getObjectType() {#getObjectType--}
```
public short getObjectType()
```


Hämtar eller anger objektets typ.

Värde: Regionens identifierare. Den MÅSTE vara 0x0006.

**Returns:**
short
### setObjectType(short value) {#setObjectType-short-}
```
public void setObjectType(short value)
```


Hämtar eller anger objektets typ.

Värde: Regionens identifierare. Den MÅSTE vara 0x0006.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getObjectCount() {#getObjectCount--}
```
public int getObjectCount()
```


Hämtar eller anger objektantalet.

Värde: Ett värde som MÅSTE ignoreras.

**Returns:**
int
### setObjectCount(int value) {#setObjectCount-int-}
```
public void setObjectCount(int value)
```


Hämtar eller anger objektantalet.

Värde: Ett värde som MÅSTE ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getRegionSize() {#getRegionSize--}
```
public short getRegionSize()
```


Hämtar eller anger regionens storlek.

Värde: Storleken på regionen i byte plus storleken på aScans i byte.

**Returns:**
short
### setRegionSize(short value) {#setRegionSize-short-}
```
public void setRegionSize(short value)
```


Hämtar eller anger regionens storlek.

Värde: Storleken på regionen i byte plus storleken på aScans i byte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getScanCount() {#getScanCount--}
```
public short getScanCount()
```


Hämtar eller anger antalet skanningar.

Värde: Antalet scanlinjer som utgör regionen.

**Returns:**
short
### setScanCount(short value) {#setScanCount-short-}
```
public void setScanCount(short value)
```


Hämtar eller anger antalet skanningar.

Värde: Antalet scanlinjer som utgör regionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getMaxScan() {#getMaxScan--}
```
public short getMaxScan()
```


Hämtar eller anger maximal skanning.

Värde: Det maximala antalet punkter i någon enskild skanning i denna region.

**Returns:**
short
### setMaxScan(short value) {#setMaxScan-short-}
```
public void setMaxScan(short value)
```


Hämtar eller anger maximal skanning.

Värde: Det maximala antalet punkter i någon enskild skanning i denna region.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rectangle getBoundingRectangle()
```


Hämtar eller anger den omslutande rektangeln.

Värde: Ett Rect-objekt (avsnitt 2.2.2.18) som definierar den omslutande rektangeln.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBoundingRectangle(Rectangle value) {#setBoundingRectangle-com.aspose.imaging.Rectangle-}
```
public void setBoundingRectangle(Rectangle value)
```


Hämtar eller anger den omslutande rektangeln.

Värde: Ett Rect-objekt (avsnitt 2.2.2.18) som definierar den omslutande rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAScans() {#getAScans--}
```
public WmfScanObject[] getAScans()
```


Hämtar eller anger en skanning.

Värde: En matris av Scan-objekt (avsnitt 2.2.2.21) som definierar scanlinjerna i regionen.

**Returns:**
com.aspose.imaging.fileformats.wmf.objects.WmfScanObject[]
### setAScans(WmfScanObject[] value) {#setAScans-com.aspose.imaging.fileformats.wmf.objects.WmfScanObject---}
```
public void setAScans(WmfScanObject[] value)
```


Hämtar eller anger en skanning.

Värde: En matris av Scan-objekt (avsnitt 2.2.2.21) som definierar scanlinjerna i regionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WmfScanObject\[\]](../../com.aspose.imaging.fileformats.wmf.objects/wmfscanobject) |  |

