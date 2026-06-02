---
title: "Classe EmfPaintRgn"
type: docs
weight: 710
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/
---

**Summary:** The EMR_PAINTRGN record paints the specified region by using the brush currently selected into the <br/>            playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPaintRgn

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPaintRgn()](#EmfPaintRgn__1) | Initialise une nouvelle instance de la classe [EmfPaintRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/). |
| [EmfPaintRgn(source)](#EmfPaintRgn_source_2) | Initialise une nouvelle instance de la classe [EmfPaintRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans la section 2.2.2.19 de [MS-WMF], <br/>            qui spécifie le rectangle englobant. |
| rgn_data | [EmfRegionData](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfregiondata/) | r/w | Obtient ou définit un tableau d'octets de longueur RgnDataSize qui spécifie un objet RegionData (section <br/>            2.2.24), en unités logiques. |
| rgn_data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille des données de région, en octets. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPaintRgn() {#EmfPaintRgn__1}


```
 EmfPaintRgn() 
```

Initialise une nouvelle instance de la classe [EmfPaintRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/).

### Constructor: EmfPaintRgn(source) {#EmfPaintRgn_source_2}


```
 EmfPaintRgn(source) 
```

Initialise une nouvelle instance de la classe [EmfPaintRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/).

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


