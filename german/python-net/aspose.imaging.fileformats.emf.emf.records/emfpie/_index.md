---
title: "EmfPie Klasse"
type: docs
weight: 730
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/
---

**Summary:** The EMR_PIE record specifies a pie-shaped wedge bounded by the intersection of an ellipse and two <br/>            radials. The pie is outlined by using the current pen and filled by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPie

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPie()](#EmfPie__1) | Initialisiert eine neue Instanz der [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/) Klasse. |
| [EmfPie(source)](#EmfPie_source_2) | Initialisiert eine neue Instanz der [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Liest oder setzt ein 128‑Bit WMF RectL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, das <br/>            das inklusiv‑inklusiv Begrenzungsrechteck angibt. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Liest oder setzt ein 64‑Bit‑PointL‑Objekt, das die Koordinaten, in logischen Einheiten, des <br/>            Endpunkts des zweiten Radius angibt. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Liest oder setzt ein 64‑Bit‑WMF‑PointL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.15, das <br/>            die Koordinaten, in logischen Einheiten, des Endpunkts des ersten Radius angibt. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfPie() {#EmfPie__1}


```
 EmfPie() 
```

Initialisiert eine neue Instanz der [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/) Klasse.

### Constructor: EmfPie(source) {#EmfPie_source_2}


```
 EmfPie(source) 
```

Initialisiert eine neue Instanz der [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/) Klasse.

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


