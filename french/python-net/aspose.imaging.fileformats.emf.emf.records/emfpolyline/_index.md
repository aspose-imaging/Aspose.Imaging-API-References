---
title: "EmfPolyline Classe"
type: docs
weight: 920
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolyline/
---

**Summary:** The EMR_POLYLINE record specifies a series of line segments by connecting the points in the<br/>            specified array.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyline

**Inheritance:** EmfPolyShape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPolyline()](#EmfPolyline__1) | Initialise une nouvelle instance de la classe [EmfPolyline](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolyline/). |
| [EmfPolyline(source)](#EmfPolyline_source_2) | Initialise une nouvelle instance de la classe [EmfPolyline](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolyline/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| a_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | Obtient ou définit un tableau d'objets WMF PointL ([MS-WMF] section 2.2.15) qui spécifie les données de points, en unités logiques. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un objet WMF RectL de 128 bits ([MS-WMF] section 2.2.2.19) qui spécifie le rectangle englobant, en unités de dispositif. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPolyline() {#EmfPolyline__1}


```
 EmfPolyline() 
```

Initialise une nouvelle instance de la classe [EmfPolyline](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolyline/).

### Constructor: EmfPolyline(source) {#EmfPolyline_source_2}


```
 EmfPolyline(source) 
```

Initialise une nouvelle instance de la classe [EmfPolyline](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolyline/).

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


