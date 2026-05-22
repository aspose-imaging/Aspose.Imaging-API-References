---
title: "Classe EmfChord"
type: docs
weight: 110
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/
---

**Summary:** The EMR_CHORD record specifies a chord, which is a region bounded by the intersection of an <br/>            ellipse and a line segment, called a secant. The chord is outlined by using the current pen and filled <br/>            by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfChord

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfChord()](#EmfChord__1) | Initialise une nouvelle instance de la classe [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/). |
| [EmfChord(source)](#EmfChord_source_2) | Initialise une nouvelle instance de la classe [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui <br/>            spécifie le rectangle englobant inclusif-inclusif. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Obtient ou définit un objet WMF PointL de 64 bits qui spécifie les coordonnées logiques du <br/>            point final du rayon définissant la fin de la corde. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Obtient ou définit un objet WMF PointL de 64 bits, spécifié dans la section 2.2.2.15 de [MS-WMF], qui <br/>            spécifie les coordonnées logiques du point final du rayon définissant le début de la corde. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfChord() {#EmfChord__1}


```
 EmfChord() 
```

Initialise une nouvelle instance de la classe [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/).

### Constructor: EmfChord(source) {#EmfChord_source_2}


```
 EmfChord(source) 
```

Initialise une nouvelle instance de la classe [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/).

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


