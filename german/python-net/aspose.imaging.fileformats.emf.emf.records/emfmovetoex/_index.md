---
title: "EmfMoveToEx Klasse"
type: docs
weight: 650
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfmovetoex/
---

**Summary:** The EMR_MOVETOEX record specifies coordinates of the new current position, in logical units.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMoveToEx

**Inheritance:** EmfRecord

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfMoveToEx()](#EmfMoveToEx__1) | Initialisiert eine neue Instanz der Klasse [EmfMoveToEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmovetoex/). |
| [EmfMoveToEx(record)](#EmfMoveToEx_record_2) | Initialisiert eine neue Instanz der Klasse [EmfMoveToEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmovetoex/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| offset | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Ruft ab oder legt fest ein 64‑Bit WMF PointL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.15, <br/>            das die Koordinaten der neuen aktuellen Position in logischen Einheiten angibt. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfMoveToEx() {#EmfMoveToEx__1}


```
 EmfMoveToEx() 
```

Initialisiert eine neue Instanz der Klasse [EmfMoveToEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmovetoex/).

### Constructor: EmfMoveToEx(record) {#EmfMoveToEx_record_2}


```
 EmfMoveToEx(record) 
```

Initialisiert eine neue Instanz der Klasse [EmfMoveToEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmovetoex/).

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


