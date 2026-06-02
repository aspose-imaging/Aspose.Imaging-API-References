---
title: "EmfExtFloodFill Klasse"
type: docs
weight: 450
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/
---

**Summary:** The EMR_EXTFLOODFILL record fills an area of the display surface with the current brush

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtFloodFill

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfExtFloodFill(source)](#EmfExtFloodFill_source_1) | Initialisiert eine neue Instanz der [EmfExtFloodFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| argb_32_color | int | r/w | Liest oder setzt ein WMF ColorRef-Objekt ([MS-WMF] Abschnitt 2.2.2.8), das zusammen mit dem <br/>            FloodFillMode verwendet wird, um den zu füllenden Bereich zu bestimmen. |
| flood_fill_mode | [EmfFloodFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emffloodfill/) | r/w | Liest oder setzt eine 32‑Bit‑unsigned Integer, die angibt, wie der Farbwert <br/>            verwendet wird, um den Bereich für die Flood‑Fill‑Operation zu bestimmen. Der Wert MUSS in der FloodFill <br/>            Aufzählung (Abschnitt 2.1.13) enthalten sein. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Liest oder setzt ein WMF PointL-Objekt ([MS-WMF] Abschnitt 2.2.2.15), das die <br/>            Koordinaten in logischen Einheiten angibt, an denen das Füllen beginnt. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfExtFloodFill(source) {#EmfExtFloodFill_source_1}


```
 EmfExtFloodFill(source) 
```

Initialisiert eine neue Instanz der [EmfExtFloodFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/) Klasse.

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


