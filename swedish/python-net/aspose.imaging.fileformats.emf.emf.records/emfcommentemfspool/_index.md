---
title: "EmfCommentEmfSpool-klass"
type: docs
weight: 190
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/
---

**Summary:** The EMR_COMMENT_EMFSPOOL record contains embedded EMFSPOOL records. <br/>            Note  Fields that are not described in this section are specified in section 2.3.3.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentEmfSpool

**Inheritance:** EmfCommentRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfCommentEmfSpool()](#EmfCommentEmfSpool__1) | Initierar en ny instans av klassen [EmfCommentEmfSpool](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/). |
| [EmfCommentEmfSpool(source)](#EmfCommentEmfSpool_source_2) | Initierar en ny instans av klassen [EmfCommentEmfSpool](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som identifierar denna kommentarspost <br/>            som innehåller EMFSPOOL‑poster. Värdet 0x00000000 identifierar detta som en <br/>            EMR_COMMENT_EMFSPOOL‑post. |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken, i byte, för fälten CommentIdentifier och CommentRecordParm i RecordBuffer-fältet som <br/>            följer. Det FÅR INTE inkludera sin egen storlek eller storleken på AlignmentPadding-fältet, om <br/>            närvarande |
| emf_spool_record_identifier | [EmfCommentEmfSpool+EmfSpoolRecordIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool+emfspoolrecordidentifierenum/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som identifierar typen av <br/>            EMR_COMMENT_EMFSPOOL‑post. |
| emf_spool_records | [EmfSpoolFontDefinitionRecordType[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfspool.records/emfspoolfontdefinitionrecordtype/) | r/w | Hämtar eller anger en variabel‑längds bytearray som innehåller en eller flera <br/>            EMFSPOOL‑teckensnittdefinitionsposter ([MS-EMFSPOOL] avsnitt 2.2.3.3). |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCommentEmfSpool() {#EmfCommentEmfSpool__1}


```
 EmfCommentEmfSpool() 
```

Initierar en ny instans av klassen [EmfCommentEmfSpool](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/).

### Constructor: EmfCommentEmfSpool(source) {#EmfCommentEmfSpool_source_2}


```
 EmfCommentEmfSpool(source) 
```

Initierar en ny instans av klassen [EmfCommentEmfSpool](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/).

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


