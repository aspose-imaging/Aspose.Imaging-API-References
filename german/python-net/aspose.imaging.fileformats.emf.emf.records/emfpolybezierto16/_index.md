---
title: "EmfPolyBezierTo16 Klasse"
type: docs
weight: 790
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolybezierto16/
---

**Summary:** The EMR_POLYBEZIERTO16 record specifies one or more Bezier curves based on the current position.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyBezierTo16

**Inheritance:** EmfPolyShape

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPolyBezierTo16()](#EmfPolyBezierTo16__1) | Initialisiert eine neue Instanz der [EmfPolyBezierTo16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolybezierto16/) Klasse. |
| [EmfPolyBezierTo16(record)](#EmfPolyBezierTo16_record_2) | Initialisiert eine neue Instanz der [EmfPolyBezierTo16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolybezierto16/) Klasse. |
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


### Constructor: EmfPolyBezierTo16() {#EmfPolyBezierTo16__1}


```
 EmfPolyBezierTo16() 
```

Initialisiert eine neue Instanz der [EmfPolyBezierTo16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolybezierto16/) Klasse.

### Constructor: EmfPolyBezierTo16(record) {#EmfPolyBezierTo16_record_2}


```
 EmfPolyBezierTo16(record) 
```

Initialisiert eine neue Instanz der [EmfPolyBezierTo16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolybezierto16/) Klasse.

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


