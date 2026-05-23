---
title: "EmfCommentEmfPlus Klasse"
type: docs
weight: 180
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/
---

**Summary:** The EMR_COMMENT_EMFPLUS record contains embedded EMF+ records. <br/>            Note  Fields that are not described in this section are specified in section 2.3.3.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentEmfPlus

**Inheritance:** EmfCommentRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfCommentEmfPlus(source)](#EmfCommentEmfPlus_source_1) | Initialisiert eine neue Instanz der Klasse [EmfCommentEmfPlus](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die diesen Kommentar‑Datensatz <br/>            als EMF+‑Datensätze enthaltend identifiziert. Der Wert 0x2B464D45, der die ASCII‑Zeichenkette \"+FME\" ist, <br/>            identifiziert ihn als EMR_COMMENT_EMFPLUS‑Datensatz. |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Größe in Bytes der <br/>            CommentIdentifier‑ und CommentRecordParm‑Felder im RecordBuffer‑Feld angibt, das <br/>            folgt. Sie DÜRFTEN NICHT die Größe von sich selbst oder die Größe des AlignmentPadding‑Feldes enthalten, falls <br/>            vorhanden. |
| emf_plus_records | [EmfPlusRecord[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | r/w | Liest oder setzt ein Byte‑Array, das einen oder mehrere EMF+‑Datensätze enthält ([MS‑EMFPLUS] Abschnitt 2.3.1). |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfCommentEmfPlus(source) {#EmfCommentEmfPlus_source_1}


```
 EmfCommentEmfPlus(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfCommentEmfPlus](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/).

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


