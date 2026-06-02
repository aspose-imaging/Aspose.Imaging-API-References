---
title: "EmfScaleWindowExtex Classe"
type: docs
weight: 1050
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/
---

**Summary:** The EMR_SCALEWINDOWEXTEX record respecifies the window for a playback device context by<br/>            using the ratios formed by the specified multiplicands and divisors.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfScaleWindowExtex

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfScaleWindowExtex()](#EmfScaleWindowExtex__1) | Initialise une nouvelle instance de la classe [EmfScaleWindowExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/) |
| [EmfScaleWindowExtex(source)](#EmfScaleWindowExtex_source_2) | Initialise une nouvelle instance de la classe [EmfScaleWindowExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/) |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
| x_denom | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie le diviseur horizontal. NE DOIT PAS être zéro. |
| x_num | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie le multiplicateur horizontal. NE DOIT PAS être zéro. |
| y_denom | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie le diviseur vertical. DOIT NE PAS être zéro. |
| y_num | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie le multiplicateur vertical. DOIT NE PAS être zéro. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfScaleWindowExtex() {#EmfScaleWindowExtex__1}


```
 EmfScaleWindowExtex() 
```

Initialise une nouvelle instance de la classe [EmfScaleWindowExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/)

### Constructor: EmfScaleWindowExtex(source) {#EmfScaleWindowExtex_source_2}


```
 EmfScaleWindowExtex(source) 
```

Initialise une nouvelle instance de la classe [EmfScaleWindowExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/)

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


