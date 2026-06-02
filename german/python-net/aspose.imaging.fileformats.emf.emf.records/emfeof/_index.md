---
title: "EmfEof Klasse"
type: docs
weight: 390
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/
---

**Summary:** The EMR_EOF record indicates the end of the metafile and specifies a palette.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfEof

**Inheritance:** EmfControlRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfEof()](#EmfEof__1) | Initialisiert eine neue Instanz der [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/) Klasse. |
| [EmfEof(record)](#EmfEof_record_2) | Initialisiert eine neue Instanz der [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| palette_argb_32_entries | int[] | r/w | Liest oder setzt einen optionalen Puffer, der Palettendaten enthält und nicht <br/>            zwingend zusammenhängend mit dem festen Teil des EMR_EOF‑<br/>            Datensatzes sein muss. Dementsprechend sind Felder in diesem Puffer, die mit <br/>            "UndefinedSpace" gekennzeichnet sind, optional und MÜSSEN ignoriert werden. <br/>            Die Größe dieses Feldes MUSS ein Vielfaches von 4 Bytes sein. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| size_last | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die MÜSSEN dem Wert von Size entsprechen und MÜSSEN das letzte <br/>            Feld des Datensatzes und damit der Metadatei sein. LogPaletteEntry‑Objekte, falls vorhanden, MÜSSEN diesem Feld vorausgehen. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfEof() {#EmfEof__1}


```
 EmfEof() 
```

Initialisiert eine neue Instanz der [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/) Klasse.

### Constructor: EmfEof(record) {#EmfEof_record_2}


```
 EmfEof(record) 
```

Initialisiert eine neue Instanz der [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Der Datensatz. |

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


