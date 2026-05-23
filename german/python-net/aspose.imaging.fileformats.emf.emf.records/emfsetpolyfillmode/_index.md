---
title: "EmfSetPolyFillMode Klasse"
type: docs
weight: 1270
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/
---

**Summary:** The EMR_SETPOLYFILLMODE record defines polygon fill mode.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetPolyFillMode

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfSetPolyFillMode()](#EmfSetPolyFillMode__1) | Initialisiert eine neue Instanz der [EmfSetPolyFillMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/) Klasse. |
| [EmfSetPolyFillMode(source)](#EmfSetPolyFillMode_source_2) | Initialisiert eine neue Instanz der [EmfSetPolyFillMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| polygon_fill_mode | [EmfPolygonFillMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfpolygonfillmode/) | r/w | Liest oder setzt eine 32‑Bit‑unsigned Integer, die den Polygon‑Füllmodus angibt und<br/>            MUSS in der PolygonFillMode (Abschnitt 2.1.27) Aufzählung enthalten sein. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfSetPolyFillMode() {#EmfSetPolyFillMode__1}


```
 EmfSetPolyFillMode() 
```

Initialisiert eine neue Instanz der [EmfSetPolyFillMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/) Klasse.

### Constructor: EmfSetPolyFillMode(source) {#EmfSetPolyFillMode_source_2}


```
 EmfSetPolyFillMode(source) 
```

Initialisiert eine neue Instanz der [EmfSetPolyFillMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/) Klasse.

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


