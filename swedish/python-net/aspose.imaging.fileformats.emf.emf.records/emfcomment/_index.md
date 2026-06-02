---
title: "EmfComment-klass"
type: docs
weight: 160
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfcomment/
---

**Summary:** The EMR_COMMENT record contains arbitrary private data.<br/>            Note  Fields that are not described in this section are specified in section 2.3.3.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfComment

**Inheritance:** EmfCommentRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfComment(source)](#EmfComment_source_1) | Initierar en ny instans av klassen [EmfComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcomment/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | Hämtar eller anger kommentarsidentifieraren. |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken, i byte, för fälten CommentIdentifier och CommentRecordParm i RecordBuffer-fältet som <br/>            följer. Det FÅR INTE inkludera sin egen storlek eller storleken på AlignmentPadding-fältet, om <br/>            närvarande |
| private_data | System.Byte | r/w | Hämtar eller anger en valfri bytearray som specificerar den privata datan. Den första <br/>            DWORD av denna data FÅR INTE vara ett av de fördefinierade kommentarsidentifierarvärdena som anges <br/>            i avsnitt 2.3.3.<br/>            Privat data är okänd för EMF; den är meningsfull endast för applikationer som känner till formatet på <br/>            datan och hur den ska användas. EMR_COMMENT privata datapost KAN ignoreras. |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfComment(source) {#EmfComment_source_1}


```
 EmfComment(source) 
```

Initierar en ny instans av klassen [EmfComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcomment/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Källan. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Källan. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | Posttypen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


