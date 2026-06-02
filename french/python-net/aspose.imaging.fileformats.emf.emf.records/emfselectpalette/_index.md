---
title: "Classe EmfSelectPalette"
type: docs
weight: 1080
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectpalette/
---

**Summary:** The EMR_SELECTPALETTE record specifies a logical palette for the playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSelectPalette

**Inheritance:** EmfObjectManipulationRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSelectPalette(source)](#EmfSelectPalette_source_1) | Initialise une nouvelle instance de la classe [EmfSelectPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectpalette/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| ih_pal | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie soit l'index d'un objet LogPalette<br/>            (section 2.2.17) dans la table d'objets EMF, soit la valeur DEFAULT_PALETTE, qui est l'index<br/>            d'une palette d'objet stockée de l'énumération StockObject (section 2.1.31). |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSelectPalette(source) {#EmfSelectPalette_source_1}


```
 EmfSelectPalette(source) 
```

Initialise une nouvelle instance de la classe [EmfSelectPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectpalette/).

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


