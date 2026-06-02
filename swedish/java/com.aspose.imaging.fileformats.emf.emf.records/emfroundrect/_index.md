---
title: "EmfRoundRect"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_ROUNDRECT-posten specificerar en rektangel med rundade hörn."
type: docs
weight: 111
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfroundrect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfRoundRect extends EmfDrawingRecordType
```

EMR\_ROUNDRECT-posten specificerar en rektangel med rundade hörn. Rektangeln kontureras med den aktuella pennan och fylls med den aktuella penseln.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfRoundRect(EmfRecord source)](#EmfRoundRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfRoundRect`. |
| [EmfRoundRect()](#EmfRoundRect--) | Initierar en ny instans av klassen [EmfRoundRect](../../com.aspose.imaging.fileformats.emf.emf.records/emfroundrect). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBox()](#getBox--) | Hämtar eller anger ett 128-bitars WMF RectL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som specificerar den inklusiva‑inklusiva rektangeln som ska ritas. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Hämtar eller anger ett 128-bitars WMF RectL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som specificerar den inklusiva‑inklusiva rektangeln som ska ritas. |
| [getCorner()](#getCorner--) | Hämtar eller anger ett 64-bitars WMF SizeL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.22, som specificerar bredden och höjden, i logiska koordinater, för ellipsen som används för att rita de avrundade hörnen. |
| [setCorner(Size value)](#setCorner-com.aspose.imaging.Size-) | Hämtar eller anger ett 64-bitars WMF SizeL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.22, som specificerar bredden och höjden, i logiska koordinater, för ellipsen som används för att rita de avrundade hörnen. |
### EmfRoundRect(EmfRecord source) {#EmfRoundRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRoundRect(EmfRecord source)
```


Initierar en ny instans av klassen `EmfRoundRect`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfRoundRect() {#EmfRoundRect--}
```
public EmfRoundRect()
```


Initierar en ny instans av klassen [EmfRoundRect](../../com.aspose.imaging.fileformats.emf.emf.records/emfroundrect).

### getBox() {#getBox--}
```
public Rectangle getBox()
```


Hämtar eller anger ett 128-bitars WMF RectL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som specificerar den inklusiva‑inklusiva rektangeln som ska ritas.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


Hämtar eller anger ett 128-bitars WMF RectL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som specificerar den inklusiva‑inklusiva rektangeln som ska ritas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getCorner() {#getCorner--}
```
public Size getCorner()
```


Hämtar eller anger ett 64-bitars WMF SizeL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.22, som specificerar bredden och höjden, i logiska koordinater, för ellipsen som används för att rita de avrundade hörnen.

**Returns:**
[Size](../../com.aspose.imaging/size)
### setCorner(Size value) {#setCorner-com.aspose.imaging.Size-}
```
public void setCorner(Size value)
```


Hämtar eller anger ett 64-bitars WMF SizeL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.22, som specificerar bredden och höjden, i logiska koordinater, för ellipsen som används för att rita de avrundade hörnen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

