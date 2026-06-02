---
title: "EmfSetPaletteEntries Classe"
type: docs
weight: 1250
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/
---

**Summary:** The EMR_SETPALETTEENTRIES record defines RGB color values in a range of entries for an existing<br/>            LogPalette (section 2.2.17) object.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetPaletteEntries

**Inheritance:** EmfObjectManipulationRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetPaletteEntries(source)](#EmfSetPaletteEntries_source_1) | Initialise une nouvelle instance de la classe [EmfSetPaletteEntries](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_pal_entries | int[] | r/w | Obtient ou définit un tableau d'objets LogPaletteEntry (section 2.2.18), de longueur <br/>            NumberOfEntries, qui spécifie les données des entrées de la palette. Les membres Values ne<br/>            contiennent aucune valeur. |
| ih_pal | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de la table d'objets EMF de la palette. |
| numberof_entries | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre d'entrées. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| start | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de la première entrée à définir. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetPaletteEntries(source) {#EmfSetPaletteEntries_source_1}


```
 EmfSetPaletteEntries(source) 
```

Initialise une nouvelle instance de la classe [EmfSetPaletteEntries](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/) .

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


