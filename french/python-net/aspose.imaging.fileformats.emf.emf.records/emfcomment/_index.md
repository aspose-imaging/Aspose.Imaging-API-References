---
title: "Classe EmfComment"
type: docs
weight: 160
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfcomment/
---

**Summary:** The EMR_COMMENT record contains arbitrary private data.<br/>            Note  Fields that are not described in this section are specified in section 2.3.3.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfComment

**Inheritance:** EmfCommentRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfComment(source)](#EmfComment_source_1) | Initialise une nouvelle instance de la classe [EmfComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcomment/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | Obtient ou définit l'identifiant du commentaire. |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille, en octets, des champs <br/>            CommentIdentifier et CommentRecordParm dans le champ RecordBuffer qui <br/>            suit. Il NE DOIT PAS inclure la taille de lui-même ni la taille du champ AlignmentPadding, le cas échéant. |
| private_data | System.Byte | r/w | Obtient ou définit un tableau d'octets optionnel qui spécifie les données privées. Le premier <br/>            DWORD de ces données NE DOIT PAS être l'une des valeurs d'identifiant de commentaire prédéfinies spécifiées <br/>            dans la section 2.3.3.<br/>            Les données privées sont inconnues d'EMF ; elles ne sont significatives que pour les applications qui connaissent le format des <br/>            données et comment les utiliser. Les enregistrements de données privées EMR_COMMENT PEUVENT être ignorés. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfComment(source) {#EmfComment_source_1}


```
 EmfComment(source) 
```

Initialise une nouvelle instance de la classe [EmfComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcomment/).

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


