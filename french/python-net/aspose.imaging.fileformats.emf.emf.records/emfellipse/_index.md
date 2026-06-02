---
title: "EmfEllipse Classe"
type: docs
weight: 370
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfellipse/
---

**Summary:** The EMR_ELLIPSE record specifies an ellipse. The center of the ellipse is the center of the specified <br/>            bounding rectangle. The ellipse is outlined by using the current pen and is filled by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfEllipse

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfEllipse()](#EmfEllipse__1) | Initialise une nouvelle instance de la classe [EmfEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfellipse/). |
| [EmfEllipse(source)](#EmfEllipse_source_2) | Initialise une nouvelle instance de la classe [EmfEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfellipse/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un objet RectL de 128 bits (WMF), spécifié dans [MS-WMF] section 2.2.2.19, qui <br/>            spécifie le rectangle englobant inclusif-inclusif. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfEllipse() {#EmfEllipse__1}


```
 EmfEllipse() 
```

Initialise une nouvelle instance de la classe [EmfEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfellipse/).

### Constructor: EmfEllipse(source) {#EmfEllipse_source_2}


```
 EmfEllipse(source) 
```

Initialise une nouvelle instance de la classe [EmfEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfellipse/).

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


