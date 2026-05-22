---
title: "EmfScaleViewportExtex Classe"
type: docs
weight: 1040
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/
---

**Summary:** The EMR_SCALEVIEWPORTEXTEX record respecifies the viewport for a device context by using the<br/>            ratios formed by the specified multiplicands and divisors.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfScaleViewportExtex

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfScaleViewportExtex()](#EmfScaleViewportExtex__1) | Initialise une nouvelle instance de la classe [EmfScaleViewportExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/). |
| [EmfScaleViewportExtex(source)](#EmfScaleViewportExtex_source_2) | Initialise une nouvelle instance de la classe [EmfScaleViewportExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
| x_denom | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie le diviseur horizontal. Ne peut pas être zéro. |
| x_num | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie le multiplicande horizontal. Ne peut pas être zéro. |
| y_denom | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie le diviseur vertical. Ne peut pas être zéro. |
| y_num | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie le multiplicande vertical. Ne peut pas être zéro. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfScaleViewportExtex() {#EmfScaleViewportExtex__1}


```
 EmfScaleViewportExtex() 
```

Initialise une nouvelle instance de la classe [EmfScaleViewportExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/).

### Constructor: EmfScaleViewportExtex(source) {#EmfScaleViewportExtex_source_2}


```
 EmfScaleViewportExtex(source) 
```

Initialise une nouvelle instance de la classe [EmfScaleViewportExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/).

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


