---
title: "EmfPlusPathPointTypeRle"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusPathPointTypeRle-objektet specificerar typvärden som är associerade med punkter på en grafikväg med RLE-komprimering."
type: docs
weight: 62
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype)
```
public final class EmfPlusPathPointTypeRle extends EmfPlusBasePointType
```

Objektet EmfPlusPathPointTypeRle specificerar typvärden som är associerade med punkter på en grafikbana med RLE-komprimering. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 B|1|RunCount | PointType | B (1 bit): Om satt är bana‑punkterna på en Bézier‑kurva. Om rensad är bana‑punkterna på en grafiklinje. RunCount (6 bitar): Antalet körningar, vilket är antalet bana‑punkter som ska associeras med typen i PointType‑fältet. PointType (1 byte): Ett EmfPlusPathPointType‑objekt (avsnitt 2.2.2.31) som specificerar typen att associera med bana‑punkterna.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusPathPointTypeRle()](#EmfPlusPathPointTypeRle--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getData()](#getData--) | Hämtar eller anger data. |
| [setData(int value)](#setData-int-) | Hämtar eller anger data. |
| [getBezier()](#getBezier--) | Hämtar eller anger ett värde som indikerar om detta `EmfPlusPathPointTypeRle` är en Bézier. |
| [setBezier(boolean value)](#setBezier-boolean-) | Hämtar eller anger ett värde som indikerar om detta `EmfPlusPathPointTypeRle` är en Bézier. |
| [getRunCount()](#getRunCount--) | Hämtar eller anger körantalet. |
| [setRunCount(byte value)](#setRunCount-byte-) | Hämtar eller anger körantalet. |
| [getPointType()](#getPointType--) | Hämtar eller anger punkttypen. |
| [setPointType(EmfPlusPathPointType value)](#setPointType-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointType-) | Hämtar eller anger punkttypen. |
### EmfPlusPathPointTypeRle() {#EmfPlusPathPointTypeRle--}
```
public EmfPlusPathPointTypeRle()
```


### getData() {#getData--}
```
public int getData()
```


Hämtar eller anger data.

Värde: Data.

**Returns:**
int
### setData(int value) {#setData-int-}
```
public void setData(int value)
```


Hämtar eller anger data.

Värde: Data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getBezier() {#getBezier--}
```
public boolean getBezier()
```


Hämtar eller anger ett värde som indikerar om detta `EmfPlusPathPointTypeRle` är en Bézier. Om satt är bana‑punkterna på en Bézier‑kurva. Om rensad är bana‑punkterna på en grafiklinje.

Värde: `true` om Bézier; annars `false`.

**Returns:**
boolean
### setBezier(boolean value) {#setBezier-boolean-}
```
public void setBezier(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta `EmfPlusPathPointTypeRle` är en Bézier. Om satt är bana‑punkterna på en Bézier‑kurva. Om rensad är bana‑punkterna på en grafiklinje.

Värde: `true` om Bézier; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getRunCount() {#getRunCount--}
```
public byte getRunCount()
```


Hämtar eller anger körantalet. RunCount (6 bitar): Körantalet, vilket är antalet bana‑punkter som ska associeras med typen i PointType‑fältet

Värde: Körantalet.

**Returns:**
byte
### setRunCount(byte value) {#setRunCount-byte-}
```
public void setRunCount(byte value)
```


Hämtar eller anger körantalet. RunCount (6 bitar): Körantalet, vilket är antalet bana‑punkter som ska associeras med typen i PointType‑fältet

Värde: Körantalet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getPointType() {#getPointType--}
```
public EmfPlusPathPointType getPointType()
```


Hämtar eller anger punkttypen. PointType (1 byte): Ett EmfPlusPathPointType‑objekt (avsnitt 2.2.2.31) som specificerar typen att associera med bana‑punkterna.

Värde: Punkttypen.

**Returns:**
[EmfPlusPathPointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype)
### setPointType(EmfPlusPathPointType value) {#setPointType-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointType-}
```
public void setPointType(EmfPlusPathPointType value)
```


Hämtar eller anger punkttypen. PointType (1 byte): Ett EmfPlusPathPointType‑objekt (avsnitt 2.2.2.31) som specificerar typen att associera med bana‑punkterna.

Värde: Punkttypen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusPathPointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype) |  |

