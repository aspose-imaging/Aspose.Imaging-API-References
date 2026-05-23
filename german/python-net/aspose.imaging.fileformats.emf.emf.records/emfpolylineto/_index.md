---
title: "EmfPolylineTo Klasse"
type: docs
weight: 940
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto/
---

**Summary:** The EMR_POLYLINETO record specifies one or more straight lines based upon the current position.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolylineTo

**Inheritance:** EmfPolyShape

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPolylineTo()](#EmfPolylineTo__1) | Initialisiert eine neue Instanz der [EmfPolylineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto/) Klasse. |
| [EmfPolylineTo(source)](#EmfPolylineTo_source_2) | Initialisiert eine neue Instanz der [EmfPolylineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| a_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | Liest oder setzt ein Array von WMF‑PointL‑Objekten ([MS-WMF] Abschnitt 2.2.15), das die Punktdaten in logischen Einheiten angibt. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Liest oder setzt ein 128‑Bit WMF RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das Begrenzungsrechteck in Geräte‑Einheiten angibt. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfPolylineTo() {#EmfPolylineTo__1}


```
 EmfPolylineTo() 
```

Initialisiert eine neue Instanz der [EmfPolylineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto/) Klasse.

### Constructor: EmfPolylineTo(source) {#EmfPolylineTo_source_2}


```
 EmfPolylineTo(source) 
```

Initialisiert eine neue Instanz der [EmfPolylineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto/) Klasse.

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


