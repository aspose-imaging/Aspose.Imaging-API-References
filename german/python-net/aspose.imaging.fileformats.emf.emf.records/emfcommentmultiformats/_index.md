---
title: "EmfCommentMultiFormats Klasse"
type: docs
weight: 210
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/
---

**Summary:** The EMR_COMMENT_MULTIFORMATS record specifies an image in multiple graphics formats.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentMultiFormats

**Inheritance:** EmfCommentPublicRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfCommentMultiFormats(source)](#EmfCommentMultiFormats_source_1) | Initialisiert eine neue Instanz der [EmfCommentMultiFormats](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| a_formats | [EmfFormat[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfformat/) | r/w | Liest oder setzt ein CountFormats‑Längen‑Array von Grafikformaten, angegeben durch <br/>            EmrFormat‑Objekte (Abschnitt 2.2.4), in Reihenfolge der Präferenz. |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der diesen Kommentar‑Datensatz <br/>            als öffentliche Daten kennzeichnet. Der Wert 0x43494447, der die ASCII‑Zeichenkette "CIDG" ist, identifiziert <br/>            diesen als EMR_COMMENT_PUBLIC‑Datensatz. |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Größe in Bytes der <br/>            CommentIdentifier‑ und CommentRecordParm‑Felder im RecordBuffer‑Feld angibt, das <br/>            folgt. Sie DÜRFTEN NICHT die Größe von sich selbst oder die Größe des AlignmentPadding‑Feldes enthalten, falls <br/>            vorhanden. |
| format_data | System.Byte[] | r/w | Liest oder setzt ein variabel langes Byte‑Array mit Bilddaten für alle Grafikformate <br/>            die in diesem Datensatz enthalten sind. <br/>            Die Größe der Daten für jedes Bild wird durch das Feld DataSize im entsprechenden <br/>            EmrFormat‑Objekt bereitgestellt. Somit ist die Gesamtlänge dieses Feldes die Summe der DataSize‑Werte in allen <br/>            EmrFormat‑Objekten. <br/>            Das Grafikformat der Daten für jedes Bild wird durch das Feld Signature im <br/>            entsprechenden EmrFormat‑Objekt angegeben. |
| output_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Liest oder setzt ein WMF‑RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das <br/>            Ausgaberechteck in logischen Koordinaten angibt. |
| public_comment_identifier | [EmfEmrComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/) | r/w | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Typ des <br/>            öffentlichen Kommentar‑Datensatzes identifiziert. Dieser SOLLTE einer der in der vorherigen Tabelle aufgeführten Werte sein, die <br/>            in der EmrComment‑Aufzählung (Abschnitt 2.1.10) angegeben sind, sofern nicht zusätzliche öffentliche <br/>            Kommentar‑Datensatztypen auf dem Druckserver implementiert wurden. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfCommentMultiFormats(source) {#EmfCommentMultiFormats_source_1}


```
 EmfCommentMultiFormats(source) 
```

Initialisiert eine neue Instanz der [EmfCommentMultiFormats](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/) Klasse.

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


