---
title: "EmfOffsetClipRgn Classe"
type: docs
weight: 690
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/
---

**Summary:** The EMR_OFFSETCLIPRGN record moves the current clipping region in the playback device context <br/>            by the specified offsets.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfOffsetClipRgn

**Inheritance:** EmfClippingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfOffsetClipRgn()](#EmfOffsetClipRgn__1) | Initialise une nouvelle instance de la classe [EmfOffsetClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/) . |
| [EmfOffsetClipRgn(source)](#EmfOffsetClipRgn_source_2) | Initialise une nouvelle instance de la classe [EmfOffsetClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| offset | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Obtient ou définit un objet WMF PointL ([MS-WMF] section 2.2.2.15) qui spécifie le <br/>            décalage horizontal et vertical en unités logiques. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfOffsetClipRgn() {#EmfOffsetClipRgn__1}


```
 EmfOffsetClipRgn() 
```

Initialise une nouvelle instance de la classe [EmfOffsetClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/) .

### Constructor: EmfOffsetClipRgn(source) {#EmfOffsetClipRgn_source_2}


```
 EmfOffsetClipRgn(source) 
```

Initialise une nouvelle instance de la classe [EmfOffsetClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/) .

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | La source. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | La source. |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | Le type d'enregistrement. |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


