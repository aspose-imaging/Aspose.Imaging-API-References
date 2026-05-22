---
title: "Classe EmfLineTo"
type: docs
weight: 590
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emflineto/
---

**Summary:** The EMR_LINETO record specifies a line from the current position up to, but not including, the<br/>            specified point.It resets the current position to the specified point.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfLineTo

**Inheritance:** EmfRecord

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfLineTo()](#EmfLineTo__1) | Initialise une nouvelle instance de la classe [EmfLineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emflineto/). |
| [EmfLineTo(record)](#EmfLineTo_record_2) | Initialise une nouvelle instance de la classe [EmfLineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emflineto/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Obtient ou définit un objet WMF PointL de 64 bits, spécifié dans [MS-WMF] section 2.2.2.15, <br/>            qui spécifie les coordonnées du point final de la ligne. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfLineTo() {#EmfLineTo__1}


```
 EmfLineTo() 
```

Initialise une nouvelle instance de la classe [EmfLineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emflineto/).

### Constructor: EmfLineTo(record) {#EmfLineTo_record_2}


```
 EmfLineTo(record) 
```

Initialise une nouvelle instance de la classe [EmfLineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emflineto/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | L'enregistrement. |

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


