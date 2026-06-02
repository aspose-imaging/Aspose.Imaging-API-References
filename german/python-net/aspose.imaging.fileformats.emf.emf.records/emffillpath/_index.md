---
title: "EmfFillPath Klasse"
type: docs
weight: 490
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emffillpath/
---

**Summary:** The EMR_FILLPATH record closes any open figures in the current path and fills the path's interior by <br/>            using the current brush and polygon-filling mode.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfFillPath

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfFillPath()](#EmfFillPath__1) | Initialisiert eine neue Instanz der Klasse [EmfFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillpath/). |
| [EmfFillPath(source)](#EmfFillPath_source_2) | Initialisiert eine neue Instanz der Klasse [EmfFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillpath/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Liest oder schreibt ein 128‑Bit‑WMF‑RectL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, <br/>            das das Begrenzungsrechteck in Geräte‑Einheiten angibt. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfFillPath() {#EmfFillPath__1}


```
 EmfFillPath() 
```

Initialisiert eine neue Instanz der Klasse [EmfFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillpath/).

### Constructor: EmfFillPath(source) {#EmfFillPath_source_2}


```
 EmfFillPath(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillpath/).

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


