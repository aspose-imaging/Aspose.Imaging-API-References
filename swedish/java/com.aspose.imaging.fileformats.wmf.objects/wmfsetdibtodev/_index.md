---
title: "WmfSetDibToDev"
second_title: "Aspose.Imaging för Java API-referens"
description: "META_SETDIBTODEV-posten ställer in ett block med pixlar i uppspelningsenhetens kontext med enhetsoberoende färgdata."
type: docs
weight: 75
url: /sv/java/com.aspose.imaging.fileformats.wmf.objects/wmfsetdibtodev/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfSetDibToDev extends WmfObject
```

META\_SETDIBTODEV-posten ställer in ett block med pixlar i uppspelningsenhetens kontext med enhetsoberoende färgdata. Källan till färgdata är en DIB.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WmfSetDibToDev()](#WmfSetDibToDev--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getColorUsage()](#getColorUsage--) | Hämtar eller anger färganvändningen. |
| [setColorUsage(int value)](#setColorUsage-int-) | Hämtar eller anger färganvändningen. |
| [getScanCount()](#getScanCount--) | Hämtar eller anger antalet skanningar. |
| [setScanCount(int value)](#setScanCount-int-) | Hämtar eller anger antalet skanningar. |
| [getStartScan()](#getStartScan--) | Hämtar eller anger startskanningen. |
| [setStartScan(int value)](#setStartScan-int-) | Hämtar eller anger startskanningen. |
| [getDibPos()](#getDibPos--) | Hämtar eller anger DIB-positionen. |
| [setDibPos(Point value)](#setDibPos-com.aspose.imaging.Point-) | Hämtar eller anger DIB-positionen. |
| [getHeight()](#getHeight--) | Hämtar eller anger höjden. |
| [setHeight(int value)](#setHeight-int-) | Hämtar eller anger höjden. |
| [getWidth()](#getWidth--) | Hämtar eller anger bredden. |
| [setWidth(int value)](#setWidth-int-) | Hämtar eller anger bredden. |
| [getDestPos()](#getDestPos--) | Hämtar eller anger destinationspositionen. |
| [setDestPos(Point value)](#setDestPos-com.aspose.imaging.Point-) | Hämtar eller anger destinationspositionen. |
| [getDib()](#getDib--) | Hämtar eller anger DIB. |
| [setDib(WmfDeviceIndependentBitmap value)](#setDib-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Hämtar eller anger DIB. |
### WmfSetDibToDev() {#WmfSetDibToDev--}
```
public WmfSetDibToDev()
```


### getColorUsage() {#getColorUsage--}
```
public int getColorUsage()
```


Hämtar eller anger färganvändningen.

Värde: Fältet Colors i DIB innehåller explicita RGB‑värden eller index i en palett. Detta MÅSTE vara ett av värdena i `com.aspose.imaging.fileFormats.wmf.objects.wmfSetDibToDev.ColorUsage`‑enumerationen (avsnitt 2.1.1.6).

**Returns:**
int
### setColorUsage(int value) {#setColorUsage-int-}
```
public void setColorUsage(int value)
```


Hämtar eller anger färganvändningen.

Värde: Fältet Colors i DIB innehåller explicita RGB‑värden eller index i en palett. Detta MÅSTE vara ett av värdena i `com.aspose.imaging.fileFormats.wmf.objects.wmfSetDibToDev.ColorUsage`‑enumerationen (avsnitt 2.1.1.6).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getScanCount() {#getScanCount--}
```
public int getScanCount()
```


Hämtar eller anger antalet skanningar.

Värde: Antalet scanlinjer i källan.

**Returns:**
int
### setScanCount(int value) {#setScanCount-int-}
```
public void setScanCount(int value)
```


Hämtar eller anger antalet skanningar.

Värde: Antalet scanlinjer i källan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getStartScan() {#getStartScan--}
```
public int getStartScan()
```


Hämtar eller anger startskanningen.

Värde: Startscanlinjen i källan.

**Returns:**
int
### setStartScan(int value) {#setStartScan-int-}
```
public void setStartScan(int value)
```


Hämtar eller anger startskanningen.

Värde: Startscanlinjen i källan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getDibPos() {#getDibPos--}
```
public Point getDibPos()
```


Hämtar eller anger DIB-positionen.

Värde: Koordinaterna, i logiska enheter, för källrektangeln.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDibPos(Point value) {#setDibPos-com.aspose.imaging.Point-}
```
public void setDibPos(Point value)
```


Hämtar eller anger DIB-positionen.

Värde: Koordinaterna, i logiska enheter, för källrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämtar eller anger höjden.

Värde: Höjden, i logiska enheter, för käll‑ och destinationsrektanglarna.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Hämtar eller anger höjden.

Värde: Höjden, i logiska enheter, för käll‑ och destinationsrektanglarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämtar eller anger bredden.

Värde: Bredden, i logiska enheter, för käll‑ och destinationsrektanglarna.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Hämtar eller anger bredden.

Värde: Bredden, i logiska enheter, för käll‑ och destinationsrektanglarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getDestPos() {#getDestPos--}
```
public Point getDestPos()
```


Hämtar eller anger destinationspositionen.

Värde: Koordinaterna, i logiska enheter, för det övre vänstra hörnet av destinationsrektangeln.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDestPos(Point value) {#setDestPos-com.aspose.imaging.Point-}
```
public void setDestPos(Point value)
```


Hämtar eller anger destinationspositionen.

Värde: Koordinaterna, i logiska enheter, för det övre vänstra hörnet av destinationsrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getDib() {#getDib--}
```
public WmfDeviceIndependentBitmap getDib()
```


Hämtar eller anger DIB.

Värde: y‑koordinaten, i logiska enheter, för det övre vänstra hörnet av destinationsrektangeln.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setDib(WmfDeviceIndependentBitmap value) {#setDib-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setDib(WmfDeviceIndependentBitmap value)
```


Hämtar eller anger DIB.

Värde: y‑koordinaten, i logiska enheter, för det övre vänstra hörnet av destinationsrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

