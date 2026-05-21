---
title: "EmfRectangle"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_RECTANGLE-posten ritar en rektangel."
type: docs
weight: 107
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfrectangle/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfRectangle extends EmfDrawingRecordType
```

EMR\_RECTANGLE-posten ritar en rektangel. Rektangeln kontureras med den aktuella pennan och fylls med den aktuella penseln.

Den aktuella positionen används inte och uppdateras inte av Rectangle. Om en PS\_NULL-penna används, är rektangelns dimensioner 1 pixel mindre i höjd och 1 pixel mindre i bredd.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfRectangle(EmfRecord source)](#EmfRectangle-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfRectangle`. |
| [EmfRectangle()](#EmfRectangle--) | Initierar en ny instans av klassen `EmfRectangle`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBox()](#getBox--) | Hämtar eller anger ett 128-bitars WMF RectL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som specificerar den inklusiva‑inklusiva rektangeln som ska ritas. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Hämtar eller anger ett 128-bitars WMF RectL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som specificerar den inklusiva‑inklusiva rektangeln som ska ritas. |
### EmfRectangle(EmfRecord source) {#EmfRectangle-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRectangle(EmfRecord source)
```


Initierar en ny instans av klassen `EmfRectangle`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfRectangle() {#EmfRectangle--}
```
public EmfRectangle()
```


Initierar en ny instans av klassen `EmfRectangle`.

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

