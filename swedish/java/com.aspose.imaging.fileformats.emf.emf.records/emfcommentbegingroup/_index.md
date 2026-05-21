---
title: "EmfCommentBeginGroup"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_COMMENT_BEGINGROUP-posten specificerar början på en grupp av ritningsposter."
type: docs
weight: 26
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentBeginGroup extends EmfCommentPublicRecordType
```

EMR\_COMMENT\_BEGINGROUP-posten specificerar början av en grupp ritposteringar.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfCommentBeginGroup(EmfRecord source)](#EmfCommentBeginGroup-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfCommentBeginGroup`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRectangle()](#getRectangle--) | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar utdatarektangeln i logiska koordinater. |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.imaging.Rectangle-) | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar utdatarektangeln i logiska koordinater. |
| [getNDescription()](#getNDescription--) | Hämtar eller anger antalet Unicode-tecken i den valfria beskrivningssträngen som följer. |
| [setNDescription(int value)](#setNDescription-int-) | Hämtar eller anger antalet Unicode-tecken i den valfria beskrivningssträngen som följer. |
| [getDescription()](#getDescription--) | Hämtar eller anger en valfri, nullterminerad Unicode-sträng som beskriver denna grupp av poster. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Hämtar eller anger en valfri, nullterminerad Unicode-sträng som beskriver denna grupp av poster. |
### EmfCommentBeginGroup(EmfRecord source) {#EmfCommentBeginGroup-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentBeginGroup(EmfRecord source)
```


Initierar en ny instans av klassen `EmfCommentBeginGroup`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar utdatarektangeln i logiska koordinater.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setRectangle(Rectangle value) {#setRectangle-com.aspose.imaging.Rectangle-}
```
public void setRectangle(Rectangle value)
```


Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar utdatarektangeln i logiska koordinater.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getNDescription() {#getNDescription--}
```
public int getNDescription()
```


Hämtar eller anger antalet Unicode-tecken i den valfria beskrivningssträngen som följer.

**Returns:**
int
### setNDescription(int value) {#setNDescription-int-}
```
public void setNDescription(int value)
```


Hämtar eller anger antalet Unicode-tecken i den valfria beskrivningssträngen som följer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getDescription() {#getDescription--}
```
public String getDescription()
```


Hämtar eller anger en valfri, nullterminerad Unicode-sträng som beskriver denna grupp av poster.

**Returns:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


Hämtar eller anger en valfri, nullterminerad Unicode-sträng som beskriver denna grupp av poster.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

