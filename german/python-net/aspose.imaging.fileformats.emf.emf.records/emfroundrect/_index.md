---
title: "EmfRoundRect Klasse"
type: docs
weight: 1020
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfroundrect/
---

**Summary:** The EMR_ROUNDRECT record specifies a rectangle with rounded corners. The rectangle is outlined <br/>            by using the current pen and filled by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfRoundRect

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfRoundRect()](#EmfRoundRect__1) | Initialisiert eine neue Instanz der Klasse [EmfRoundRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfroundrect/). |
| [EmfRoundRect(source)](#EmfRoundRect_source_2) | Initialisiert eine neue Instanz der Klasse [EmfRoundRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfroundrect/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Liest oder setzt ein 128‑Bit WMF RectL‑Objekt, das in [MS-WMF] Abschnitt 2.2.2.19 angegeben ist und <br/>            das inklusive‑inklusive Rechteck zum Zeichnen spezifiziert. |
| corner | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Liest oder setzt ein 64‑Bit WMF SizeL‑Objekt, das in [MS-WMF] Abschnitt 2.2.22 angegeben ist und <br/>            die Breite und Höhe in logischen Koordinaten der Ellipse, die zum Zeichnen der abgerundeten Ecken verwendet wird, spezifiziert. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfRoundRect() {#EmfRoundRect__1}


```
 EmfRoundRect() 
```

Initialisiert eine neue Instanz der Klasse [EmfRoundRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfroundrect/).

### Constructor: EmfRoundRect(source) {#EmfRoundRect_source_2}


```
 EmfRoundRect(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfRoundRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfroundrect/).

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


