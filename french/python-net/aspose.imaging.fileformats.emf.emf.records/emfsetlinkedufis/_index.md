---
title: "Classe EmfSetLinkedUfis"
type: docs
weight: 1200
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetlinkedufis/
---

**Summary:** The EMR_SETLINKEDUFIS record sets the UniversalFontIds (section 2.2.27) of the linked fonts to<br/>            use during character lookup.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetLinkedUfis

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetLinkedUfis(source)](#EmfSetLinkedUfis_source_1) | Initialise une nouvelle instance de la classe [EmfSetLinkedUfis](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetlinkedufis/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
| ufis | [EmfUniversalFontId[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/) | r/w | Obtient ou définit un tableau d'éléments uNumLinkedUFI de type UniversalFontId, qui spécifie<br/>            les identifiants des polices liées. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetLinkedUfis(source) {#EmfSetLinkedUfis_source_1}


```
 EmfSetLinkedUfis(source) 
```

Initialise une nouvelle instance de la classe [EmfSetLinkedUfis](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetlinkedufis/).

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


