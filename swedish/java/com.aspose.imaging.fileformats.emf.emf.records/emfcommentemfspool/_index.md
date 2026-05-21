---
title: "EmfCommentEmfSpool"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_COMMENT_EMFSPOOL-posten innehåller inbäddade EMFSPOOL-poster."
type: docs
weight: 28
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfCommentEmfSpool extends EmfCommentRecordType
```

EMR\\_COMMENT\\_EMFSPOOL-posten innehåller inbäddade EMFSPOOL-poster. Observera att fält som inte beskrivs i detta avsnitt specificeras i avsnitt 2.3.3.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfCommentEmfSpool(EmfRecord source)](#EmfCommentEmfSpool-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfCommentEmfSpool`. |
| [EmfCommentEmfSpool()](#EmfCommentEmfSpool--) | Initierar en ny instans av klassen `EmfCommentEmfSpool`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Hämtar eller anger ett 32-bitars osignerat heltal som identifierar denna kommentarpost som innehållande EMFSPOOL-poster. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som identifierar denna kommentarpost som innehållande EMFSPOOL-poster. |
| [getEmfSpoolRecordIdentifier()](#getEmfSpoolRecordIdentifier--) | Hämtar eller anger ett 32-bitars osignerat heltal som identifierar typen av EMR\\_COMMENT\\_EMFSPOOL-posten. |
| [setEmfSpoolRecordIdentifier(int value)](#setEmfSpoolRecordIdentifier-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som identifierar typen av EMR\\_COMMENT\\_EMFSPOOL-posten. |
| [getEmfSpoolRecords()](#getEmfSpoolRecords--) | Hämtar eller anger en variabel‑längds bytearray som innehåller en eller flera EMFSPOOL-typsnittsdefinitionsposter ([MS-EMFSPOOL] avsnitt 2.2.3.3). |
| [setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value)](#setEmfSpoolRecords-com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType---) | Hämtar eller anger en variabel‑längds bytearray som innehåller en eller flera EMFSPOOL-typsnittsdefinitionsposter ([MS-EMFSPOOL] avsnitt 2.2.3.3). |
### EmfCommentEmfSpool(EmfRecord source) {#EmfCommentEmfSpool-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentEmfSpool(EmfRecord source)
```


Initierar en ny instans av klassen `EmfCommentEmfSpool`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfCommentEmfSpool() {#EmfCommentEmfSpool--}
```
public EmfCommentEmfSpool()
```


Initierar en ny instans av klassen `EmfCommentEmfSpool`.

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Hämtar eller anger ett 32-bitars osignerat heltal som identifierar denna kommentarpost som innehållande EMFSPOOL-poster. Värdet 0x00000000 identifierar detta som en EMR\\_COMMENT\\_EMFSPOOL-post.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som identifierar denna kommentarpost som innehållande EMFSPOOL-poster. Värdet 0x00000000 identifierar detta som en EMR\\_COMMENT\\_EMFSPOOL-post.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getEmfSpoolRecordIdentifier() {#getEmfSpoolRecordIdentifier--}
```
public int getEmfSpoolRecordIdentifier()
```


Hämtar eller anger ett 32-bitars osignerat heltal som identifierar typen av EMR\\_COMMENT\\_EMFSPOOL-posten.

**Returns:**
int
### setEmfSpoolRecordIdentifier(int value) {#setEmfSpoolRecordIdentifier-int-}
```
public void setEmfSpoolRecordIdentifier(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som identifierar typen av EMR\\_COMMENT\\_EMFSPOOL-posten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getEmfSpoolRecords() {#getEmfSpoolRecords--}
```
public EmfSpoolFontDefinitionRecordType[] getEmfSpoolRecords()
```


Hämtar eller anger en variabel‑längds bytearray som innehåller en eller flera EMFSPOOL-typsnittsdefinitionsposter ([MS-EMFSPOOL] avsnitt 2.2.3.3).

**Returns:**
com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType[]
### setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value) {#setEmfSpoolRecords-com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType---}
```
public void setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value)
```


Hämtar eller anger en variabel‑längds bytearray som innehåller en eller flera EMFSPOOL-typsnittsdefinitionsposter ([MS-EMFSPOOL] avsnitt 2.2.3.3).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfSpoolFontDefinitionRecordType\[\]](../../com.aspose.imaging.fileformats.emf.emfspool.records/emfspoolfontdefinitionrecordtype) |  |

