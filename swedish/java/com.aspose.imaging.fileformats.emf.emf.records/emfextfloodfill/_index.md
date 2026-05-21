---
title: "EmfExtFloodFill"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_EXTFLOODFILL-posten fyller ett område på displayytan med den aktuella penseln"
type: docs
weight: 54
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfExtFloodFill extends EmfDrawingRecordType
```

Den EMR_EXTFLOODFILL-posten fyller ett område på displayytan med den aktuella penseln.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfExtFloodFill(EmfRecord source)](#EmfExtFloodFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfExtFloodFill`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getStart()](#getStart--) | Hämtar eller anger ett WMF PointL-objekt ([MS-WMF] avsnitt 2.2.2.15), som specificerar koordinaterna, i logiska enheter, där fyllning påbörjas. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Hämtar eller anger ett WMF PointL-objekt ([MS-WMF] avsnitt 2.2.2.15), som specificerar koordinaterna, i logiska enheter, där fyllning påbörjas. |
| [getArgb32Color()](#getArgb32Color--) | Hämtar eller anger ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8), som används med FloodFillMode för att bestämma området som ska fyllas. |
| [setArgb32Color(int value)](#setArgb32Color-int-) | Hämtar eller anger ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8), som används med FloodFillMode för att bestämma området som ska fyllas. |
| [getFloodFillMode()](#getFloodFillMode--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur färgvärdet ska användas för att bestämma området för flood fill‑operationen. |
| [setFloodFillMode(int value)](#setFloodFillMode-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur färgvärdet ska användas för att bestämma området för flood fill‑operationen. |
### EmfExtFloodFill(EmfRecord source) {#EmfExtFloodFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtFloodFill(EmfRecord source)
```


Initierar en ny instans av klassen `EmfExtFloodFill`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getStart() {#getStart--}
```
public Point getStart()
```


Hämtar eller anger ett WMF PointL-objekt ([MS-WMF] avsnitt 2.2.2.15), som specificerar koordinaterna, i logiska enheter, där fyllning påbörjas.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Hämtar eller anger ett WMF PointL-objekt ([MS-WMF] avsnitt 2.2.2.15), som specificerar koordinaterna, i logiska enheter, där fyllning påbörjas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getArgb32Color() {#getArgb32Color--}
```
public int getArgb32Color()
```


Hämtar eller anger ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8), som används med FloodFillMode för att bestämma området som ska fyllas.

**Returns:**
int
### setArgb32Color(int value) {#setArgb32Color-int-}
```
public void setArgb32Color(int value)
```


Hämtar eller anger ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8), som används med FloodFillMode för att bestämma området som ska fyllas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getFloodFillMode() {#getFloodFillMode--}
```
public int getFloodFillMode()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur färgvärdet ska användas för att bestämma området för flood fill‑operationen. Värdet MÅSTE finnas i FloodFill-enumerationen (avsnitt 2.1.13).

**Returns:**
int
### setFloodFillMode(int value) {#setFloodFillMode-int-}
```
public void setFloodFillMode(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur färgvärdet ska användas för att bestämma området för flood fill‑operationen. Värdet MÅSTE finnas i FloodFill-enumerationen (avsnitt 2.1.13).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

