---
title: "Classe EmfPie"
type: docs
weight: 730
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/
---

**Summary:** The EMR_PIE record specifies a pie-shaped wedge bounded by the intersection of an ellipse and two <br/>            radials. The pie is outlined by using the current pen and filled by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPie

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPie()](#EmfPie__1) | Initialise une nouvelle instance de la classe [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/). |
| [EmfPie(source)](#EmfPie_source_2) | Initialise une nouvelle instance de la classe [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui <br/>            spécifie le rectangle englobant inclusif-inclusif. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Obtient ou définit un objet PointL de 64 bits qui spécifie les coordonnées, en unités logiques, du <br/>            point final du second rayon. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Obtient ou définit des objets WMF PointL de 64 bits, spécifiés dans [MS-WMF] section 2.2.2.15, qui <br/>            spécifient les coordonnées, en unités logiques, du point final du premier rayon. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPie() {#EmfPie__1}


```
 EmfPie() 
```

Initialise une nouvelle instance de la classe [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/).

### Constructor: EmfPie(source) {#EmfPie_source_2}


```
 EmfPie(source) 
```

Initialise une nouvelle instance de la classe [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/).

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


