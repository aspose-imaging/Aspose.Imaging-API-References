---
title: "Classe EmfPolyPolygon"
type: docs
weight: 830
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/
---

**Summary:** The EMR_POLYPOLYGON record specifies a series of closed polygons.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyPolygon

**Inheritance:** EmfPolyPolyShape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPolyPolygon()](#EmfPolyPolygon__1) | Initialise une nouvelle instance de la classe [EmfPolyPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/). |
| [EmfPolyPolygon(source)](#EmfPolyPolygon_source_2) | Initialise une nouvelle instance de la classe [EmfPolyPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| a_points | [Point[][]](/imaging/python-net/aspose.imaging/point[]/) | r/w | Obtient ou définit un tableau d'objets WMF PointS, spécifié dans [MS-WMF] <br/>            section 2.2.2.16, qui spécifie le tableau de points. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un objet WMF RectL de 128 bits ([MS-WMF] section 2.2.2.19) qui spécifie le rectangle englobant, en unités de dispositif. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPolyPolygon() {#EmfPolyPolygon__1}


```
 EmfPolyPolygon() 
```

Initialise une nouvelle instance de la classe [EmfPolyPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/).

### Constructor: EmfPolyPolygon(source) {#EmfPolyPolygon_source_2}


```
 EmfPolyPolygon(source) 
```

Initialise une nouvelle instance de la classe [EmfPolyPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/).

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


