---
title: "EmfPolygon16 Classe"
type: docs
weight: 910
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon16/
---

**Summary:** The EMR_POLYGON16 record specifies a polygon consisting of two or more vertexes connected by <br/>            straight lines. The polygon is outlined by using the current pen and filled by using the current brush <br/>            and polygon fill mode. The polygon is closed automatically by drawing a line from the last vertex to the first.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolygon16

**Inheritance:** EmfPolyShape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPolygon16()](#EmfPolygon16__1) | Initialise une nouvelle instance de la classe [EmfPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon16/). |
| [EmfPolygon16(source)](#EmfPolygon16_source_2) | Initialise une nouvelle instance de la classe [EmfPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon16/). |
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


### Constructor: EmfPolygon16() {#EmfPolygon16__1}


```
 EmfPolygon16() 
```

Initialise une nouvelle instance de la classe [EmfPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon16/).

### Constructor: EmfPolygon16(source) {#EmfPolygon16_source_2}


```
 EmfPolygon16(source) 
```

Initialise une nouvelle instance de la classe [EmfPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon16/).

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


