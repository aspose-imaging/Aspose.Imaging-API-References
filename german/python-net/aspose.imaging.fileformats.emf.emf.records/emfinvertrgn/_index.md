---
title: "EmfInvertRgn Klasse"
type: docs
weight: 580
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfinvertrgn/
---

**Summary:** The EMR_INVERTRGN record inverts the colors in the specified region.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfInvertRgn

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfInvertRgn(source)](#EmfInvertRgn_source_1) | Initialisiert eine neue Instanz der Klasse [EmfInvertRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfinvertrgn/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Liest oder setzt ein 128‑Bit WMF RectL-Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19,<br/>            das das Begrenzungsrechteck angibt. |
| rgn_data | System.Byte | r/w | Liest oder setzt ein RgnDataSize‑langes Byte‑Array, das ein RegionData-Objekt in logischen Einheiten angibt. |
| rgn_data_size | int | r/w | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der die Größe der Regionsdaten in Bytes angibt. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfInvertRgn(source) {#EmfInvertRgn_source_1}


```
 EmfInvertRgn(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfInvertRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfinvertrgn/).

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


