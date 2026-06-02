---
title: "EmfSetBkMode Classe"
type: docs
weight: 1110
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/
---

**Summary:** The EMR_SETBKMODE record specifies the background mix mode of the playback device context.<br/>            The background mix mode is used with text, hatched brushes, and pen styles that are not solid lines.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetBkMode

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetBkMode()](#EmfSetBkMode__1) | Initialise une nouvelle instance de la classe [EmfSetBkMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/). |
| [EmfSetBkMode(source)](#EmfSetBkMode_source_2) | Initialise une nouvelle instance de la classe [EmfSetBkMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_mode | [EmfBackgroundMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfbackgroundmode/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le mode d'arrière-plan<br/>et DOIT appartenir à l'énumération BackgroundMode (section 2.1.4). |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetBkMode() {#EmfSetBkMode__1}


```
 EmfSetBkMode() 
```

Initialise une nouvelle instance de la classe [EmfSetBkMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/).

### Constructor: EmfSetBkMode(source) {#EmfSetBkMode_source_2}


```
 EmfSetBkMode(source) 
```

Initialise une nouvelle instance de la classe [EmfSetBkMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/).

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


