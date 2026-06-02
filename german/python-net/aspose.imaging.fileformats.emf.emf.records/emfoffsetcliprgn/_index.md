---
title: "EmfOffsetClipRgn Klasse"
type: docs
weight: 690
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/
---

**Summary:** The EMR_OFFSETCLIPRGN record moves the current clipping region in the playback device context <br/>            by the specified offsets.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfOffsetClipRgn

**Inheritance:** EmfClippingRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfOffsetClipRgn()](#EmfOffsetClipRgn__1) | Initialisiert eine neue Instanz der [EmfOffsetClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/) Klasse. |
| [EmfOffsetClipRgn(source)](#EmfOffsetClipRgn_source_2) | Initialisiert eine neue Instanz der [EmfOffsetClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| offset | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Liest oder setzt ein WMF PointL‑Objekt ([MS-WMF] Abschnitt 2.2.2.15), das die <br/>            horizontalen und vertikalen Versätze in logischen Einheiten angibt. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfOffsetClipRgn() {#EmfOffsetClipRgn__1}


```
 EmfOffsetClipRgn() 
```

Initialisiert eine neue Instanz der [EmfOffsetClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/) Klasse.

### Constructor: EmfOffsetClipRgn(source) {#EmfOffsetClipRgn_source_2}


```
 EmfOffsetClipRgn(source) 
```

Initialisiert eine neue Instanz der [EmfOffsetClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/) Klasse.

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


