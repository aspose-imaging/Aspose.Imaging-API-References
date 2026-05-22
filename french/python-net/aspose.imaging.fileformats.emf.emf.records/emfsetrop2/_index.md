---
title: "EmfSetRop2 Classe"
type: docs
weight: 1280
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/
---

**Summary:** The EMR_SETROP2 record defines a binary raster operation mode.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetRop2

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetRop2()](#EmfSetRop2__1) | Initialise une nouvelle instance de la classe [EmfSetRop2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/). |
| [EmfSetRop2(source)](#EmfSetRop2_source_2) | Initialise une nouvelle instance de la classe [EmfSetRop2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| rop_2_mode | [WmfBinaryRasterOperation](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfbinaryrasteroperation/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le mode d'opération raster et<br/>            DOIT se trouver dans l'énumération WMF Binary Raster Op ([MS-WMF] section 2.1.1.2). |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetRop2() {#EmfSetRop2__1}


```
 EmfSetRop2() 
```

Initialise une nouvelle instance de la classe [EmfSetRop2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/).

### Constructor: EmfSetRop2(source) {#EmfSetRop2_source_2}


```
 EmfSetRop2(source) 
```

Initialise une nouvelle instance de la classe [EmfSetRop2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/).

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


