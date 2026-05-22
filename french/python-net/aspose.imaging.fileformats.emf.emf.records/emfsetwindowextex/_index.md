---
title: "EmfSetWindowExtEx Classe"
type: docs
weight: 1350
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindowextex/
---

**Summary:** The EMR_SETWINDOWEXTEX record defines the window extent.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetWindowExtEx

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetWindowExtEx()](#EmfSetWindowExtEx__1) | Initialise une nouvelle instance de la classe [EmfSetWindowExtEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindowextex/). |
| [EmfSetWindowExtEx(source)](#EmfSetWindowExtEx_source_2) | Initialise une nouvelle instance de la classe [EmfSetWindowExtEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindowextex/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| extent | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Obtient ou définit un objet WMF SizeL 64 bits ([MS-WMF] section 2.2.2.22) qui spécifie les<br/>            étendues horizontales et verticales en unités logiques. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetWindowExtEx() {#EmfSetWindowExtEx__1}


```
 EmfSetWindowExtEx() 
```

Initialise une nouvelle instance de la classe [EmfSetWindowExtEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindowextex/).

### Constructor: EmfSetWindowExtEx(source) {#EmfSetWindowExtEx_source_2}


```
 EmfSetWindowExtEx(source) 
```

Initialise une nouvelle instance de la classe [EmfSetWindowExtEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindowextex/).

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


