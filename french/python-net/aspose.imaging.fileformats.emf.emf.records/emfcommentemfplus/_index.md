---
title: "EmfCommentEmfPlus Classe"
type: docs
weight: 180
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/
---

**Summary:** The EMR_COMMENT_EMFPLUS record contains embedded EMF+ records. <br/>            Note  Fields that are not described in this section are specified in section 2.3.3.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentEmfPlus

**Inheritance:** EmfCommentRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfCommentEmfPlus(source)](#EmfCommentEmfPlus_source_1) | Initialise une nouvelle instance de la classe [EmfCommentEmfPlus](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | Obtient ou définit un entier non signé de 32 bits qui identifie cet enregistrement de commentaire <br/>            comme contenant des enregistrements EMF+. La valeur 0x2B464D45, qui est la chaîne ASCII \"+FME\", <br/>            identifie ceci comme un enregistrement EMR_COMMENT_EMFPLUS. |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille, en octets, des champs <br/>            CommentIdentifier et CommentRecordParm dans le champ RecordBuffer qui <br/>            suit. Il NE DOIT PAS inclure la taille de lui-même ni la taille du champ AlignmentPadding, le cas échéant. |
| emf_plus_records | [EmfPlusRecord[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | r/w | Obtient ou définit un tableau d’octets qui contient un ou plusieurs enregistrements EMF+ ([MS-EMFPLUS] section 2.3.1). |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCommentEmfPlus(source) {#EmfCommentEmfPlus_source_1}


```
 EmfCommentEmfPlus(source) 
```

Initialise une nouvelle instance de la classe [EmfCommentEmfPlus](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/).

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


