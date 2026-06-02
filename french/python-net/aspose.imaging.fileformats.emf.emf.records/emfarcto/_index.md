---
title: "Classe EmfArcTo"
type: docs
weight: 50
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfarcto/
---

**Summary:** The EMR_ARCTO record specifies an elliptical arc. It resets the current position to the end point of the arc.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfArcTo

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfArcTo()](#EmfArcTo__1) | Initialise une nouvelle instance de la classe [EmfArcTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarcto/). |
| [EmfArcTo(source)](#EmfArcTo_source_2) | Initialise une nouvelle instance de la classe [EmfArcTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarcto/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans la section 2.2.2.19 de [MS-WMF], qui <br/>            spécifie le rectangle englobant. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Obtient ou définit un objet WMF PointL de 64 bits qui spécifie les coordonnées du deuxième point final radial <br/>            en unités logiques. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Obtient ou définit un objet WMF PointL de 64 bits, spécifié dans la section 2.2.2.15 de [MS-WMF], qui <br/>            spécifie les coordonnées du premier point final radial, en unités logiques. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfArcTo() {#EmfArcTo__1}


```
 EmfArcTo() 
```

Initialise une nouvelle instance de la classe [EmfArcTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarcto/).

### Constructor: EmfArcTo(source) {#EmfArcTo_source_2}


```
 EmfArcTo(source) 
```

Initialise une nouvelle instance de la classe [EmfArcTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarcto/).

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


