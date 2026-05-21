---
title: "EmfCommentEmfPlus"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_COMMENT_EMFPLUS-posten innehåller inbäddade EMF-poster."
type: docs
weight: 27
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfCommentEmfPlus extends EmfCommentRecordType
```

EMR\_COMMENT\_EMFPLUS-posten innehåller inbäddade EMF+-poster. Observera att fält som inte beskrivs i detta avsnitt specificeras i avsnitt 2.3.3.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfCommentEmfPlus(EmfRecord source)](#EmfCommentEmfPlus-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfCommentEmfPlus`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Hämtar eller anger ett 32-bitars osignerat heltal som identifierar denna kommentarpost som innehållande EMF+-poster. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som identifierar denna kommentarpost som innehållande EMF+-poster. |
| [getEmfPlusRecords()](#getEmfPlusRecords--) | Hämtar eller anger en bytearray som innehåller en eller flera EMF+-poster ([MS-EMFPLUS] avsnitt 2.3.1). |
| [setEmfPlusRecords(EmfPlusRecord[] value)](#setEmfPlusRecords-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord---) | Hämtar eller anger en bytearray som innehåller en eller flera EMF+-poster ([MS-EMFPLUS] avsnitt 2.3.1). |
### EmfCommentEmfPlus(EmfRecord source) {#EmfCommentEmfPlus-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentEmfPlus(EmfRecord source)
```


Initierar en ny instans av klassen `EmfCommentEmfPlus`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Hämtar eller anger ett 32-bitars osignerat heltal som identifierar denna kommentarpost som innehållande EMF+-poster. Värdet 0x2B464D45, som är ASCII-strängen \"+FME\", identifierar detta som en EMR\_COMMENT\_EMFPLUS-post.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som identifierar denna kommentarpost som innehållande EMF+-poster. Värdet 0x2B464D45, som är ASCII-strängen \"+FME\", identifierar detta som en EMR\_COMMENT\_EMFPLUS-post.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getEmfPlusRecords() {#getEmfPlusRecords--}
```
public EmfPlusRecord[] getEmfPlusRecords()
```


Hämtar eller anger en bytearray som innehåller en eller flera EMF+-poster ([MS-EMFPLUS] avsnitt 2.3.1).

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord[]
### setEmfPlusRecords(EmfPlusRecord[] value) {#setEmfPlusRecords-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord---}
```
public void setEmfPlusRecords(EmfPlusRecord[] value)
```


Hämtar eller anger en bytearray som innehåller en eller flera EMF+-poster ([MS-EMFPLUS] avsnitt 2.3.1).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusRecord\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) |  |

