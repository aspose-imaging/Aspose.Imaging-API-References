---
title: "EmfPie"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_PIE‑posten specificerar en pajformad kil som begränsas av skärningspunkten mellan en ellips och två radier."
type: docs
weight: 82
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPie extends EmfDrawingRecordType
```

EMR\_PIE‑posten specificerar en pajformad kil som begränsas av skärningspunkten mellan en ellips och två radier. Pajen avgränsas med den aktuella pennan och fylls med den aktuella penseln.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPie(EmfRecord source)](#EmfPie-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfPie`. |
| [EmfPie()](#EmfPie--) | Initierar en ny instans av klassen `EmfPie`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBox()](#getBox--) | Hämtar eller anger ett 128-bitars WMF RectL‑objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som specificerar den inklusiva avgränsande rektangeln. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Hämtar eller anger ett 128-bitars WMF RectL‑objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som specificerar den inklusiva avgränsande rektangeln. |
| [getStart()](#getStart--) | Hämtar eller anger ett 64‑bitars WMF PointL‑objekt, specificerat i [MS-WMF] avsnitt 2.2.2.15, som specificerar koordinaterna, i logiska enheter, för slutpunkten av den första radien. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Hämtar eller anger ett 64‑bitars WMF PointL‑objekt, specificerat i [MS-WMF] avsnitt 2.2.2.15, som specificerar koordinaterna, i logiska enheter, för slutpunkten av den första radien. |
| [getEnd()](#getEnd--) | Hämtar eller anger ett 64‑bitars PointL‑objekt som specificerar koordinaterna, i logiska enheter, för slutpunkten av den andra radien. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | Hämtar eller anger ett 64‑bitars PointL‑objekt som specificerar koordinaterna, i logiska enheter, för slutpunkten av den andra radien. |
### EmfPie(EmfRecord source) {#EmfPie-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPie(EmfRecord source)
```


Initierar en ny instans av klassen `EmfPie`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfPie() {#EmfPie--}
```
public EmfPie()
```


Initierar en ny instans av klassen `EmfPie`.

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


Hämtar eller anger ett 64‑bitars WMF PointL‑objekt, specificerat i [MS-WMF] avsnitt 2.2.2.15, som specificerar koordinaterna, i logiska enheter, för slutpunkten av den första radien.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Hämtar eller anger ett 64‑bitars WMF PointL‑objekt, specificerat i [MS-WMF] avsnitt 2.2.2.15, som specificerar koordinaterna, i logiska enheter, för slutpunkten av den första radien.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


Hämtar eller anger ett 64‑bitars PointL‑objekt som specificerar koordinaterna, i logiska enheter, för slutpunkten av den andra radien.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


Hämtar eller anger ett 64‑bitars PointL‑objekt som specificerar koordinaterna, i logiska enheter, för slutpunkten av den andra radien.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

