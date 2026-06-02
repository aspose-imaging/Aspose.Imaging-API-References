---
title: "EmfComment"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_COMMENT-posten innehåller godtycklig privat data."
type: docs
weight: 25
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfcomment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfComment extends EmfCommentRecordType
```

EMR\_COMMENT-posten innehåller godtycklig privat data. Observera att fält som inte beskrivs i detta avsnitt specificeras i avsnitt 2.3.3.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfComment(EmfRecord source)](#EmfComment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfComment`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPrivateData()](#getPrivateData--) | Hämtar eller anger en valfri bytearray som specificerar den privata datan. |
| [setPrivateData(byte[] value)](#setPrivateData-byte---) | Hämtar eller anger en valfri bytearray som specificerar den privata datan. |
| [getCommentIdentifier()](#getCommentIdentifier--) | Hämtar eller anger kommentarsidentifieraren. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Hämtar eller anger kommentarsidentifieraren. |
### EmfComment(EmfRecord source) {#EmfComment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfComment(EmfRecord source)
```


Initierar en ny instans av klassen `EmfComment`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getPrivateData() {#getPrivateData--}
```
public byte[] getPrivateData()
```


Hämtar eller anger en valfri bytearray som specificerar den privata datan. Det första DWORD‑värdet i denna data FÅR INTE vara ett av de fördefinierade kommentarsidentifierarvärdena som anges i avsnitt 2.3.3. Privat data är okänd för EMF; den är endast meningsfull för applikationer som känner till formatet på datan och hur den ska användas. EMR\_COMMENT‑poster med privat data KAN ignoreras.

**Returns:**
byte[]
### setPrivateData(byte[] value) {#setPrivateData-byte---}
```
public void setPrivateData(byte[] value)
```


Hämtar eller anger en valfri bytearray som specificerar den privata datan. Det första DWORD‑värdet i denna data FÅR INTE vara ett av de fördefinierade kommentarsidentifierarvärdena som anges i avsnitt 2.3.3. Privat data är okänd för EMF; den är endast meningsfull för applikationer som känner till formatet på datan och hur den ska användas. EMR\_COMMENT‑poster med privat data KAN ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Hämtar eller anger kommentarsidentifieraren.

Värde: Kommentarsidentifieraren.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Hämtar eller anger kommentarsidentifieraren.

Värde: Kommentarsidentifieraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

