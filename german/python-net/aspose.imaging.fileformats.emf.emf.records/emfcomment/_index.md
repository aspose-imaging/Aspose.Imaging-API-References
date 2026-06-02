---
title: "EmfComment Klasse"
type: docs
weight: 160
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfcomment/
---

**Summary:** The EMR_COMMENT record contains arbitrary private data.<br/>            Note  Fields that are not described in this section are specified in section 2.3.3.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfComment

**Inheritance:** EmfCommentRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfComment(source)](#EmfComment_source_1) | Initialisiert eine neue Instanz der [EmfComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcomment/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | Liest oder setzt den Kommentarbezeichner. |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Größe in Bytes der <br/>            CommentIdentifier‑ und CommentRecordParm‑Felder im RecordBuffer‑Feld angibt, das <br/>            folgt. Sie DÜRFTEN NICHT die Größe von sich selbst oder die Größe des AlignmentPadding‑Feldes enthalten, falls <br/>            vorhanden. |
| private_data | System.Byte | r/w | Liest oder setzt ein optionales Byte‑Array, das die privaten Daten angibt. Das erste <br/>            DWORD dieser Daten DÜRFTEN NICHT einer der vordefinierten Kommentarbezeichnerwerte entsprechen, die in Abschnitt 2.3.3 angegeben sind.<br/>            Private Daten sind EMF unbekannt; sie sind nur für Anwendungen von Bedeutung, die das Format der <br/>            Daten kennen und wissen, wie sie zu verwenden sind. EMR_COMMENT‑Privatdatensätze KÖNNTEN ignoriert werden. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfComment(source) {#EmfComment_source_1}


```
 EmfComment(source) 
```

Initialisiert eine neue Instanz der [EmfComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcomment/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Die Quelle. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Die Quelle. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | Der Datensatztyp. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


