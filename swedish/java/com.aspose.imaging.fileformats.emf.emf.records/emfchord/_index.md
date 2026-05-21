---
title: "EmfChord"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_CHORD‑posten specificerar en kord som är ett område avgränsat av skärningspunkten mellan en ellips och ett linjesegment som kallas en sekant."
type: docs
weight: 20
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfchord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfChord extends EmfDrawingRecordType
```

EMR\_CHORD‑posten specificerar en kord, som är ett område avgränsat av skärningspunkten mellan en ellips och ett linjesegment, kallat en sekant. Korden avgränsas med den aktuella pennan och fylls med den aktuella penseln.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfChord(EmfRecord source)](#EmfChord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfChord`. |
| [EmfChord()](#EmfChord--) | Initierar en ny instans av klassen `EmfChord`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBox()](#getBox--) | Hämtar eller anger ett 128-bitars WMF RectL‑objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som specificerar den inklusiva avgränsande rektangeln. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Hämtar eller anger ett 128-bitars WMF RectL‑objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som specificerar den inklusiva avgränsande rektangeln. |
| [getStart()](#getStart--) | Hämtar eller anger ett 64-bitars WMF PointL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.15, som specificerar de logiska koordinaterna för radieändpunkten som definierar början av korden. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Hämtar eller anger ett 64-bitars WMF PointL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.15, som specificerar de logiska koordinaterna för radieändpunkten som definierar början av korden. |
| [getEnd()](#getEnd--) | Hämtar eller anger ett 64-bitars WMF PointL-objekt som specificerar de logiska koordinaterna för radieändpunkten som definierar slutet av korden. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | Hämtar eller anger ett 64-bitars WMF PointL-objekt som specificerar de logiska koordinaterna för radieändpunkten som definierar slutet av korden. |
### EmfChord(EmfRecord source) {#EmfChord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfChord(EmfRecord source)
```


Initierar en ny instans av klassen `EmfChord`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfChord() {#EmfChord--}
```
public EmfChord()
```


Initierar en ny instans av klassen `EmfChord`.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


Hämtar eller anger ett 128-bitars WMF RectL‑objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som specificerar den inklusiva avgränsande rektangeln.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


Hämtar eller anger ett 128-bitars WMF RectL‑objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som specificerar den inklusiva avgränsande rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStart() {#getStart--}
```
public Point getStart()
```


Hämtar eller anger ett 64-bitars WMF PointL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.15, som specificerar de logiska koordinaterna för radieändpunkten som definierar början av korden.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Hämtar eller anger ett 64-bitars WMF PointL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.15, som specificerar de logiska koordinaterna för radieändpunkten som definierar början av korden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


Hämtar eller anger ett 64-bitars WMF PointL-objekt som specificerar de logiska koordinaterna för radieändpunkten som definierar slutet av korden.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


Hämtar eller anger ett 64-bitars WMF PointL-objekt som specificerar de logiska koordinaterna för radieändpunkten som definierar slutet av korden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

