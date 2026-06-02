---
title: "EmfStrokeAndFillPath Classe"
type: docs
weight: 1420
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfstrokeandfillpath/
---

**Summary:** The EMR_STROKEANDFILLPATH record closes any open figures in a path, strokes the outline of the<br/>            path by using the current pen, and fills its interior by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfStrokeAndFillPath

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfStrokeAndFillPath()](#EmfStrokeAndFillPath__1) | Initialise une nouvelle instance de la classe [EmfStrokeAndFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstrokeandfillpath/). |
| [EmfStrokeAndFillPath(source)](#EmfStrokeAndFillPath_source_2) | Initialise une nouvelle instance de la classe [EmfStrokeAndFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstrokeandfillpath/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un objet RectL WMF de 128 bits ([MS-WMF] section 2.2.2.19) qui spécifie<br/>            le rectangle englobant, en unités de dispositif. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfStrokeAndFillPath() {#EmfStrokeAndFillPath__1}


```
 EmfStrokeAndFillPath() 
```

Initialise une nouvelle instance de la classe [EmfStrokeAndFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstrokeandfillpath/).

### Constructor: EmfStrokeAndFillPath(source) {#EmfStrokeAndFillPath_source_2}


```
 EmfStrokeAndFillPath(source) 
```

Initialise une nouvelle instance de la classe [EmfStrokeAndFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstrokeandfillpath/).

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


