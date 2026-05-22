---
title: "Classe EmfMoveToEx"
type: docs
weight: 650
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfmovetoex/
---

**Summary:** The EMR_MOVETOEX record specifies coordinates of the new current position, in logical units.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMoveToEx

**Inheritance:** EmfRecord

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfMoveToEx()](#EmfMoveToEx__1) | Initialise une nouvelle instance de la classe [EmfMoveToEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmovetoex/). |
| [EmfMoveToEx(record)](#EmfMoveToEx_record_2) | Initialise une nouvelle instance de la classe [EmfMoveToEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmovetoex/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| offset | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Obtient ou définit un objet WMF PointL de 64 bits, spécifié dans la section 2.2.2.15 de [MS-WMF], <br/>            qui spécifie les coordonnées de la nouvelle position actuelle en unités logiques. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfMoveToEx() {#EmfMoveToEx__1}


```
 EmfMoveToEx() 
```

Initialise une nouvelle instance de la classe [EmfMoveToEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmovetoex/).

### Constructor: EmfMoveToEx(record) {#EmfMoveToEx_record_2}


```
 EmfMoveToEx(record) 
```

Initialise une nouvelle instance de la classe [EmfMoveToEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmovetoex/).

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


