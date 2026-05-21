---
title: "EmfExcludeClipRect"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_EXCLUDECLIPRECT-posten specificerar en ny beskärningsregion som består av den befintliga beskärningsregionen minus den angivna rektangeln."
type: docs
weight: 50
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfExcludeClipRect extends EmfClippingRecordType
```

EMR\_EXCLUDECLIPRECT-posten specificerar en ny beskärningsregion som består av den befintliga beskärningsregionen minus den angivna rektangeln. Observera att fält som inte beskrivs i detta avsnitt specificeras i avsnitt 2.3.2.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfExcludeClipRect(EmfRecord source)](#EmfExcludeClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfExcludeClipRect`. |
| [EmfExcludeClipRect()](#EmfExcludeClipRect--) | Initierar en ny instans av klassen `EmfExcludeClipRect`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getClip()](#getClip--) | Hämtar ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar beskärningsrektangeln i logiska enheter. |
| [setClip(Rectangle value)](#setClip-com.aspose.imaging.Rectangle-) | Anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar beskärningsrektangeln i logiska enheter. |
### EmfExcludeClipRect(EmfRecord source) {#EmfExcludeClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExcludeClipRect(EmfRecord source)
```


Initierar en ny instans av klassen `EmfExcludeClipRect`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfExcludeClipRect() {#EmfExcludeClipRect--}
```
public EmfExcludeClipRect()
```


Initierar en ny instans av klassen `EmfExcludeClipRect`.

### getClip() {#getClip--}
```
public Rectangle getClip()
```


Hämtar ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar beskärningsrektangeln i logiska enheter.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setClip(Rectangle value) {#setClip-com.aspose.imaging.Rectangle-}
```
public void setClip(Rectangle value)
```


Anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar beskärningsrektangeln i logiska enheter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

