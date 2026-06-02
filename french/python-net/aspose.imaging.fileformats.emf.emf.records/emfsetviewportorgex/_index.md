---
title: "EmfSetViewportOrgEx Classe"
type: docs
weight: 1340
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/
---

**Summary:** The EMR_SETVIEWPORTORGEX record defines the viewport origin.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetViewportOrgEx

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetViewportOrgEx()](#EmfSetViewportOrgEx__1) | Initialise une nouvelle instance de la classe [EmfSetViewportOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/). |
| [EmfSetViewportOrgEx(source)](#EmfSetViewportOrgEx_source_2) | Initialise une nouvelle instance de la classe [EmfSetViewportOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Obtient ou définit un objet WMF PointL de 64 bits ([MS-WMF] section 2.2.2.15) qui spécifie le<br/>            point d'origine horizontal et vertical de la fenêtre en unités de dispositif. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetViewportOrgEx() {#EmfSetViewportOrgEx__1}


```
 EmfSetViewportOrgEx() 
```

Initialise une nouvelle instance de la classe [EmfSetViewportOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/).

### Constructor: EmfSetViewportOrgEx(source) {#EmfSetViewportOrgEx_source_2}


```
 EmfSetViewportOrgEx(source) 
```

Initialise une nouvelle instance de la classe [EmfSetViewportOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/).

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


