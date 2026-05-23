---
title: "EmfPolyBezierTo Klasse"
type: docs
weight: 780
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolybezierto/
---

**Summary:** The EMR_POLYBEZIERTO record specifies one or more Bezier curves based upon the current position.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyBezierTo

**Inheritance:** EmfPolyShape

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPolyBezierTo()](#EmfPolyBezierTo__1) | Initialisiert eine neue Instanz der Klasse [EmfPolyBezierTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolybezierto/). |
| [EmfPolyBezierTo(source)](#EmfPolyBezierTo_source_2) | Initialisiert eine neue Instanz der Klasse [EmfPolyBezierTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolybezierto/). |
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


### Constructor: EmfPolyBezierTo() {#EmfPolyBezierTo__1}


```
 EmfPolyBezierTo() 
```

Initialisiert eine neue Instanz der Klasse [EmfPolyBezierTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolybezierto/).

### Constructor: EmfPolyBezierTo(source) {#EmfPolyBezierTo_source_2}


```
 EmfPolyBezierTo(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfPolyBezierTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolybezierto/).

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


