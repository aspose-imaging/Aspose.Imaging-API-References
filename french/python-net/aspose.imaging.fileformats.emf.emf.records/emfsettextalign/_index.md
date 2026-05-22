---
title: "Classe EmfSetTextAlign"
type: docs
weight: 1300
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/
---

**Summary:** The EMR_SETTEXTALIGN record specifies text alignment.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetTextAlign

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetTextAlign()](#EmfSetTextAlign__1) | Initialise une nouvelle instance de la classe [EmfSetTextAlign](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/). |
| [EmfSetTextAlign(source)](#EmfSetTextAlign_source_2) | Initialise une nouvelle instance de la classe [EmfSetTextAlign](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| text_alignment_mode | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie l'alignement du texte en<br/>            utilisant un masque de drapeaux d'alignement du texte. Il s'agit soit de [WmfTextAlignmentModeFlags](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags/)<br/>            ([MS-WMF] section 2.1.2.3) pour le texte avec une ligne de base horizontale, soit de [WmfVerticalTextAlignmentModeFlags](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfverticaltextalignmentmodeflags/)<br/>            ([MS-WMF] section 2.1.2.4) pour le texte avec une ligne de base verticale<br/>            . Une seule valeur peut être choisie parmi celles qui affectent l'alignement horizontal et vertical. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetTextAlign() {#EmfSetTextAlign__1}


```
 EmfSetTextAlign() 
```

Initialise une nouvelle instance de la classe [EmfSetTextAlign](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/).

### Constructor: EmfSetTextAlign(source) {#EmfSetTextAlign_source_2}


```
 EmfSetTextAlign(source) 
```

Initialise une nouvelle instance de la classe [EmfSetTextAlign](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/).

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


