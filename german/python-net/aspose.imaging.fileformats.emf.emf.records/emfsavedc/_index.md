---
title: "EmfSaveDc Klasse"
type: docs
weight: 1030
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfsavedc/
---

**Summary:** Saves the current state of playback device context on a<br/>            stack of states saved by preceding EMR_SAVEDC<br/>            records, if any. The state consists of graphics properties<br/>            and objects, including the currently selected bitmap,<br/>            brush, palette, font, pen, and region. An<br/>            EMR_RESTOREDC record is used to restore the state.<br/>            This EMF record specifies no parameters.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSaveDc

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfSaveDc()](#EmfSaveDc__1) | Initialisiert eine neue Instanz der [EmfSaveDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsavedc/) Klasse. |
| [EmfSaveDc(source)](#EmfSaveDc_source_2) | Initialisiert eine neue Instanz der [EmfSaveDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsavedc/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfSaveDc() {#EmfSaveDc__1}


```
 EmfSaveDc() 
```

Initialisiert eine neue Instanz der [EmfSaveDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsavedc/) Klasse.

### Constructor: EmfSaveDc(source) {#EmfSaveDc_source_2}


```
 EmfSaveDc(source) 
```

Initialisiert eine neue Instanz der [EmfSaveDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsavedc/) Klasse.

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


