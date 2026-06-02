---
title: "EmfIntersectClipRect"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_INTERSECTCLIPRECT‑posten specificerar en ny klippningsregion från skärningspunkten mellan den aktuella klippningsregionen och den angivna rektangeln."
type: docs
weight: 66
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfintersectcliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfIntersectClipRect extends EmfClippingRecordType
```

EMR\_INTERSECTCLIPRECT‑posten specificerar en ny klippningsregion från skärningspunkten mellan den aktuella klippningsregionen och den angivna rektangeln. Observera att fält som inte beskrivs i detta avsnitt specificeras i avsnitt 2.3.2.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfIntersectClipRect(EmfRecord source)](#EmfIntersectClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfIntersectClipRect`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getClip()](#getClip--) | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar rektangeln i logiska enheter. |
| [setClip(Rectangle value)](#setClip-com.aspose.imaging.Rectangle-) | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar rektangeln i logiska enheter. |
### EmfIntersectClipRect(EmfRecord source) {#EmfIntersectClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfIntersectClipRect(EmfRecord source)
```


Initierar en ny instans av klassen `EmfIntersectClipRect`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getClip() {#getClip--}
```
public Rectangle getClip()
```


Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar rektangeln i logiska enheter.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setClip(Rectangle value) {#setClip-com.aspose.imaging.Rectangle-}
```
public void setClip(Rectangle value)
```


Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar rektangeln i logiska enheter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

