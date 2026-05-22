---
title: "EmfEof Classe"
type: docs
weight: 390
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/
---

**Summary:** The EMR_EOF record indicates the end of the metafile and specifies a palette.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfEof

**Inheritance:** EmfControlRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfEof()](#EmfEof__1) | Initialise une nouvelle instance de la classe [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/) |
| [EmfEof(record)](#EmfEof_record_2) | Initialise une nouvelle instance de la classe [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/) |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| palette_argb_32_entries | int[] | r/w | Obtient ou définit un tampon optionnel contenant les données de palette, qui n'est pas <br/>            requis d'être contigu avec la partie fixe de l'enregistrement EMR_EOF <br/>            . En conséquence, les champs de ce tampon qui sont libellés <br/>            "UndefinedSpace" sont optionnels et DOIVENT être ignorés. <br/>            La taille de ce champ DOIT être un multiple de 4 octets |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| size_last | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT être identique à Size et DOIT être le dernier <br/>            champ de l'enregistrement et donc du métafichier. Les objets LogPaletteEntry, s'ils <br/>            existent, DOIVENT précéder ce champ. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfEof() {#EmfEof__1}


```
 EmfEof() 
```

Initialise une nouvelle instance de la classe [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/)

### Constructor: EmfEof(record) {#EmfEof_record_2}


```
 EmfEof(record) 
```

Initialise une nouvelle instance de la classe [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/)

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | L'enregistrement. |

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


