---
title: "EmfFrameRgn Classe"
type: docs
weight: 530
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/
---

**Summary:** The EMR_FRAMERGN record draws a border around the specified region using the specified brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfFrameRgn

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfFrameRgn()](#EmfFrameRgn__1) | Initialise une nouvelle instance de la classe [EmfFrameRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/) . |
| [EmfFrameRgn(source)](#EmfFrameRgn_source_2) | Initialise une nouvelle instance de la classe [EmfFrameRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui <br/>            spécifie le rectangle englobant. |
| height | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur du trait du pinceau horizontal <br/>            en unités logiques. |
| ih_brush | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de la table d'objets EMF du pinceau. |
| rgn_data | [EmfRegionData](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfregiondata/) | r/w | Obtient ou définit un tableau d'octets de longueur RgnDataSize qui spécifie un objet RegionData, <br/>            en unités logiques |
| rgn_data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille des données de région, en octets. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
| width | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la largeur du trait du pinceau vertical, en unités logiques. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfFrameRgn() {#EmfFrameRgn__1}


```
 EmfFrameRgn() 
```

Initialise une nouvelle instance de la classe [EmfFrameRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/) .

### Constructor: EmfFrameRgn(source) {#EmfFrameRgn_source_2}


```
 EmfFrameRgn(source) 
```

Initialise une nouvelle instance de la classe [EmfFrameRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/) .

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


