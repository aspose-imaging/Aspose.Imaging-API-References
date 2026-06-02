---
title: "EmfArc Classe"
type: docs
weight: 40
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/
---

**Summary:** The EMR_ARC record specifies an elliptical arc.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfArc

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfArc()](#EmfArc__1) | Initialise une nouvelle instance de la classe [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/). |
| [EmfArc(source)](#EmfArc_source_2) | Initialise une nouvelle instance de la classe [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui <br/>            spécifie le rectangle englobant inclusif-inclusif. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Obtient ou définit un objet WMF PointL de 64 bits qui spécifie les coordonnées, en unités logiques, du <br/>            point final de la ligne radiale définissant le point final de l'arc. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Obtient ou définit un objet WMF PointL de 64 bits, spécifié dans [MS-WMF] section 2.2.2.15, qui <br/>            spécifie les coordonnées, en unités logiques, du point final de la ligne radiale définissant le <br/>            point de départ de l'arc. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfArc() {#EmfArc__1}


```
 EmfArc() 
```

Initialise une nouvelle instance de la classe [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/).

### Constructor: EmfArc(source) {#EmfArc_source_2}


```
 EmfArc(source) 
```

Initialise une nouvelle instance de la classe [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/).

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


