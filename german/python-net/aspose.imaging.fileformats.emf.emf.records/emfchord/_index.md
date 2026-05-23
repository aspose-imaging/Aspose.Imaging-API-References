---
title: "EmfChord Klasse"
type: docs
weight: 110
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/
---

**Summary:** The EMR_CHORD record specifies a chord, which is a region bounded by the intersection of an <br/>            ellipse and a line segment, called a secant. The chord is outlined by using the current pen and filled <br/>            by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfChord

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfChord()](#EmfChord__1) | Initialisiert eine neue Instanz der Klasse [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/). |
| [EmfChord(source)](#EmfChord_source_2) | Initialisiert eine neue Instanz der Klasse [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Liest oder setzt ein 128‑Bit WMF RectL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, das <br/>            das inklusiv‑inklusiv Begrenzungsrechteck angibt. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Liest oder setzt ein 64‑Bit WMF PointL‑Objekt, das die logischen Koordinaten des <br/>            Endpunkts des Radials, das das Ende der Sehne definiert, angibt. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Liest oder setzt ein 64‑Bit WMF PointL‑Objekt, das in [MS-WMF] Abschnitt 2.2.2.15 angegeben ist und <br/>            die logischen Koordinaten des Endpunkts des Radials, das den Anfang der Sehne definiert, spezifiziert. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfChord() {#EmfChord__1}


```
 EmfChord() 
```

Initialisiert eine neue Instanz der Klasse [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/).

### Constructor: EmfChord(source) {#EmfChord_source_2}


```
 EmfChord(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/).

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


