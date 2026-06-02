---
title: "EmfRestoreDc Klasse"
type: docs
weight: 1000
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/
---

**Summary:** The EMR_RESTOREDC record restores the playback device context to the specified state. The<br/>            playback device context is restored by popping state information off a stack that was created by<br/>            prior EMR_SAVEDC records (section 2.3.11).

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfRestoreDc

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfRestoreDc()](#EmfRestoreDc__1) | Initialisiert eine neue Instanz der [EmfRestoreDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/) Klasse. |
| [EmfRestoreDc(source)](#EmfRestoreDc_source_2) | Initialisiert eine neue Instanz der [EmfRestoreDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| saved_dc | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die den zu restaurierenden gespeicherten Zustand relativ zum<br/> aktuellen Zustand angibt. Dieser Wert MÜSSEN negativ sein; –1 steht für den zuletzt auf dem Stapel gespeicherten Zustand, –2 für den davor usw. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfRestoreDc() {#EmfRestoreDc__1}


```
 EmfRestoreDc() 
```

Initialisiert eine neue Instanz der [EmfRestoreDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/) Klasse.

### Constructor: EmfRestoreDc(source) {#EmfRestoreDc_source_2}


```
 EmfRestoreDc(source) 
```

Initialisiert eine neue Instanz der [EmfRestoreDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/) Klasse.

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


