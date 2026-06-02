---
title: "EmfArcTo Klasse"
type: docs
weight: 50
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfarcto/
---

**Summary:** The EMR_ARCTO record specifies an elliptical arc. It resets the current position to the end point of the arc.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfArcTo

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfArcTo()](#EmfArcTo__1) | Initialisiert eine neue Instanz der Klasse [EmfArcTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarcto/). |
| [EmfArcTo(source)](#EmfArcTo_source_2) | Initialisiert eine neue Instanz der Klasse [EmfArcTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarcto/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Liest oder setzt ein 128‑Bit WMF RectL‑Objekt, das in [MS-WMF] Abschnitt 2.2.2.19 angegeben ist und <br/>            das Begrenzungsrechteck spezifiziert. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Liest oder setzt ein 64‑Bit WMF PointL‑Objekt, das die Koordinaten des zweiten radialen <br/>            Endpunkts in logischen Einheiten angibt. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Liest oder setzt ein 64‑Bit WMF PointL‑Objekt, das in [MS-WMF] Abschnitt 2.2.2.15 angegeben ist und <br/>            die Koordinaten des ersten radialen Endpunkts in logischen Einheiten angibt. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfArcTo() {#EmfArcTo__1}


```
 EmfArcTo() 
```

Initialisiert eine neue Instanz der Klasse [EmfArcTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarcto/).

### Constructor: EmfArcTo(source) {#EmfArcTo_source_2}


```
 EmfArcTo(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfArcTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarcto/).

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


