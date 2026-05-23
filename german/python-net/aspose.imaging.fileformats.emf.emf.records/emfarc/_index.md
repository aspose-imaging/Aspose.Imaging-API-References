---
title: "EmfArc Klasse"
type: docs
weight: 40
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/
---

**Summary:** The EMR_ARC record specifies an elliptical arc.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfArc

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfArc()](#EmfArc__1) | Initialisiert eine neue Instanz der Klasse [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/). |
| [EmfArc(source)](#EmfArc_source_2) | Initialisiert eine neue Instanz der Klasse [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Liest oder setzt ein 128‑Bit WMF RectL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, das <br/>            das inklusiv‑inklusiv Begrenzungsrechteck angibt. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Liest oder setzt ein 64‑Bit WMF PointL‑Objekt, das die Koordinaten in logischen Einheiten des <br/>            Endpunkts der radialen Linie, die den Endpunkt des Bogens definiert, angibt. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Liest oder setzt ein 64‑Bit WMF PointL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.15, das <br/>            die Koordinaten in logischen Einheiten des Endpunkts der radialen Linie, die den <br/>            Startpunkt des Bogens definiert, angibt. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfArc() {#EmfArc__1}


```
 EmfArc() 
```

Initialisiert eine neue Instanz der Klasse [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/).

### Constructor: EmfArc(source) {#EmfArc_source_2}


```
 EmfArc(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/).

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


