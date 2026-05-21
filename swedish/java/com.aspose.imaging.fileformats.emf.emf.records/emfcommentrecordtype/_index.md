---
title: "EmfCommentRecordType"
second_title: "Aspose.Imaging för Java API-referens"
description: "Kommentarposttyperna definierar format för att specificera godtyckliga privata data‑inbäddningsposter i andra metafilformat och för att lägga till nya eller specialändamålskommandon."
type: docs
weight: 32
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public abstract class EmfCommentRecordType extends EmfRecord
```

Kommentarposttyperna definierar format för att ange godtycklig privat data, bädda in poster i andra metafilformat och lägga till nya eller specialsyftade kommandon.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDataSize()](#getDataSize--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken, i byte, för fälten CommentIdentifier och CommentRecordParm i RecordBuffer‑fältet som följer. |
| [setDataSize(int value)](#setDataSize-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken, i byte, för fälten CommentIdentifier och CommentRecordParm i RecordBuffer‑fältet som följer. |
| [getCommentIdentifier()](#getCommentIdentifier--) | Hämtar eller anger kommentarsidentifieraren. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Hämtar eller anger kommentarsidentifieraren. |
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken, i byte, för fälten CommentIdentifier och CommentRecordParm i RecordBuffer‑fältet som följer. Det FÅR INTE inkludera sin egen storlek eller storleken på AlignmentPadding‑fältet, om det finns.

**Returns:**
int
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken, i byte, för fälten CommentIdentifier och CommentRecordParm i RecordBuffer‑fältet som följer. Det FÅR INTE inkludera sin egen storlek eller storleken på AlignmentPadding‑fältet, om det finns.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

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

