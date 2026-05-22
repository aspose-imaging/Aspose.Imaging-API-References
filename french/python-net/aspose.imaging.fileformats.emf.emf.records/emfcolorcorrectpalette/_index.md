---
title: "EmfColorCorrectPalette Classe"
type: docs
weight: 140
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfcolorcorrectpalette/
---

**Summary:** The EMR_COLORCORRECTPALETTE record specifies how to correct the entries of a logical palette<br/>            object using WCS 1.0 values.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfColorCorrectPalette

**Inheritance:** EmfObjectManipulationRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfColorCorrectPalette(source)](#EmfColorCorrectPalette_source_1) | Initialise une nouvelle instance de la classe [EmfColorCorrectPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcolorcorrectpalette/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| ih_palette | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index d'un objet palette logique<br/>            (section 2.2.17) dans la table d'objets EMF (section 3.1.1.1). |
| n_first_entry | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de la première entrée à corriger. |
| n_pal_entries | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre d'entrées de palette à corriger. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfColorCorrectPalette(source) {#EmfColorCorrectPalette_source_1}


```
 EmfColorCorrectPalette(source) 
```

Initialise une nouvelle instance de la classe [EmfColorCorrectPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcolorcorrectpalette/).

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


