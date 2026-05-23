---
title: "EmfPolyPolyline Klasse"
type: docs
weight: 850
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline/
---

**Summary:** The EMR_POLYPOLYLINE record specifies multiple series of connected line segments.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyPolyline

**Inheritance:** EmfPolyPolyShape

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPolyPolyline()](#EmfPolyPolyline__1) | Initialisiert eine neue Instanz der [EmfPolyPolyline](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline/) Klasse. |
| [EmfPolyPolyline(source)](#EmfPolyPolyline_source_2) | Initialisiert eine neue Instanz der [EmfPolyPolyline](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| a_points | [Point[][]](/imaging/python-net/aspose.imaging/point[]/) | r/w | Liest oder setzt ein Array von WMF PointS-Objekten, angegeben in [MS-WMF] <br/>            Abschnitt 2.2.2.16, das das Array von Punkten spezifiziert. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Liest oder setzt ein 128‑Bit WMF RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das Begrenzungsrechteck in Geräte‑Einheiten angibt. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfPolyPolyline() {#EmfPolyPolyline__1}


```
 EmfPolyPolyline() 
```

Initialisiert eine neue Instanz der [EmfPolyPolyline](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline/) Klasse.

### Constructor: EmfPolyPolyline(source) {#EmfPolyPolyline_source_2}


```
 EmfPolyPolyline(source) 
```

Initialisiert eine neue Instanz der [EmfPolyPolyline](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline/) Klasse.

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


