---
title: "EmfSetBkMode Klasse"
type: docs
weight: 1110
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/
---

**Summary:** The EMR_SETBKMODE record specifies the background mix mode of the playback device context.<br/>            The background mix mode is used with text, hatched brushes, and pen styles that are not solid lines.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetBkMode

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfSetBkMode()](#EmfSetBkMode__1) | Initialisiert eine neue Instanz der Klasse [EmfSetBkMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/). |
| [EmfSetBkMode(source)](#EmfSetBkMode_source_2) | Initialisiert eine neue Instanz der Klasse [EmfSetBkMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| background_mode | [EmfBackgroundMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfbackgroundmode/) | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Hintergrundmodus angibt<br/>            und MUSS im Enumerationswert BackgroundMode (Abschnitt 2.1.4) enthalten sein. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfSetBkMode() {#EmfSetBkMode__1}


```
 EmfSetBkMode() 
```

Initialisiert eine neue Instanz der Klasse [EmfSetBkMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/).

### Constructor: EmfSetBkMode(source) {#EmfSetBkMode_source_2}


```
 EmfSetBkMode(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfSetBkMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/).

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


