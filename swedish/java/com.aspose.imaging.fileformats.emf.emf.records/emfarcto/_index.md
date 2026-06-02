---
title: "EmfArcTo"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_ARCTO‑posten specificerar en elliptisk båge."
type: docs
weight: 14
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfarcto/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfArcTo extends EmfDrawingRecordType
```

EMR\_ARCTO‑posten specificerar en elliptisk båge. Den återställer den aktuella positionen till bågens slutpunkt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfArcTo(EmfRecord source)](#EmfArcTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfArcTo`. |
| [EmfArcTo()](#EmfArcTo--) | Initierar en ny instans av klassen `EmfArcTo`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBox()](#getBox--) | Hämtar eller anger ett 128-bitars WMF RectL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som specificerar den omgivande rektangeln. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Hämtar eller anger ett 128-bitars WMF RectL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som specificerar den omgivande rektangeln. |
| [getStart()](#getStart--) | Hämtar eller anger ett 64-bitars WMF PointL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.15, som specificerar koordinaterna för den första radieändpunkten, i logiska enheter. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Hämtar eller anger ett 64-bitars WMF PointL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.15, som specificerar koordinaterna för den första radieändpunkten, i logiska enheter. |
| [getEnd()](#getEnd--) | Hämtar eller anger ett 64-bitars WMF PointL-objekt som specificerar koordinaterna för den andra radiala slutpunkten, i logiska enheter. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | Hämtar eller anger ett 64-bitars WMF PointL-objekt som specificerar koordinaterna för den andra radiala slutpunkten, i logiska enheter. |
### EmfArcTo(EmfRecord source) {#EmfArcTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfArcTo(EmfRecord source)
```


Initierar en ny instans av klassen `EmfArcTo`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfArcTo() {#EmfArcTo--}
```
public EmfArcTo()
```


Initierar en ny instans av klassen `EmfArcTo`.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


Hämtar eller anger ett 128-bitars WMF RectL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som specificerar den omgivande rektangeln.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


Hämtar eller anger ett 128-bitars WMF RectL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som specificerar den omgivande rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStart() {#getStart--}
```
public Point getStart()
```


Hämtar eller anger ett 64-bitars WMF PointL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.15, som specificerar koordinaterna för den första radieändpunkten, i logiska enheter.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Hämtar eller anger ett 64-bitars WMF PointL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.15, som specificerar koordinaterna för den första radieändpunkten, i logiska enheter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


Hämtar eller anger ett 64-bitars WMF PointL-objekt som specificerar koordinaterna för den andra radiala slutpunkten, i logiska enheter.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


Hämtar eller anger ett 64-bitars WMF PointL-objekt som specificerar koordinaterna för den andra radiala slutpunkten, i logiska enheter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

