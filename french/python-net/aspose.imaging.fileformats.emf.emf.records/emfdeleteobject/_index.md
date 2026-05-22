---
title: "EmfDeleteObject Classe"
type: docs
weight: 340
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/
---

**Summary:** The EMR_DELETEOBJECT record deletes a graphics object, which is specified by its index in the EMF Object Table(section 3.1.1.1).

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfDeleteObject

**Inheritance:** EmfRecord

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfDeleteObject()](#EmfDeleteObject__1) | Initialise une nouvelle instance de la classe [EmfDeleteObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/). |
| [EmfDeleteObject(record)](#EmfDeleteObject_record_2) | Initialise une nouvelle instance de la classe [EmfDeleteObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| object_handle | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie soit l'index d'un objet graphique <br/>            dans la table d'objets EMF, soit l'index d'un objet prédéfini de l'énumération StockObject. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfDeleteObject() {#EmfDeleteObject__1}


```
 EmfDeleteObject() 
```

Initialise une nouvelle instance de la classe [EmfDeleteObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/).

### Constructor: EmfDeleteObject(record) {#EmfDeleteObject_record_2}


```
 EmfDeleteObject(record) 
```

Initialise une nouvelle instance de la classe [EmfDeleteObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/).

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


