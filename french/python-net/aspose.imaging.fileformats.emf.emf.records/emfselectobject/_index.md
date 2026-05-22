---
title: "Classe EmfSelectObject"
type: docs
weight: 1070
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/
---

**Summary:** The EMR_SELECTOBJECT record adds a graphics object to the current metafile playback device<br/>            context. The object is specified either by its index in the EMF Object Table(section 3.1.1.1) or by its<br/>            value from the StockObject enumeration(section 2.1.31).

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSelectObject

**Inheritance:** EmfRecord

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSelectObject()](#EmfSelectObject__1) | Initialise une nouvelle instance de la classe [EmfSelectObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/). |
| [EmfSelectObject(record)](#EmfSelectObject_record_2) | Initialise une nouvelle instance de la classe [EmfSelectObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| object_handle | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie soit l'index d'un objet graphique <br/>            dans la table d'objets EMF, soit l'index d'un objet prédéfini provenant de l'énumération [EmfStockObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfstockobject/). |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSelectObject() {#EmfSelectObject__1}


```
 EmfSelectObject() 
```

Initialise une nouvelle instance de la classe [EmfSelectObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/).

### Constructor: EmfSelectObject(record) {#EmfSelectObject_record_2}


```
 EmfSelectObject(record) 
```

Initialise une nouvelle instance de la classe [EmfSelectObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/).

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


