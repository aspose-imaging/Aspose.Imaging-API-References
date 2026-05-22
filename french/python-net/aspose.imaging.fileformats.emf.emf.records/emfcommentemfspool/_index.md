---
title: "Classe EmfCommentEmfSpool"
type: docs
weight: 190
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/
---

**Summary:** The EMR_COMMENT_EMFSPOOL record contains embedded EMFSPOOL records. <br/>            Note  Fields that are not described in this section are specified in section 2.3.3.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentEmfSpool

**Inheritance:** EmfCommentRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfCommentEmfSpool()](#EmfCommentEmfSpool__1) | Initialise une nouvelle instance de la classe [EmfCommentEmfSpool](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/). |
| [EmfCommentEmfSpool(source)](#EmfCommentEmfSpool_source_2) | Initialise une nouvelle instance de la classe [EmfCommentEmfSpool](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | Obtient ou définit un entier non signé de 32 bits qui identifie cet enregistrement de commentaire <br/>            comme contenant des enregistrements EMFSPOOL. La valeur 0x00000000 identifie cela comme un <br/>            enregistrement EMR_COMMENT_EMFSPOOL. |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille, en octets, des champs <br/>            CommentIdentifier et CommentRecordParm dans le champ RecordBuffer qui <br/>            suit. Il NE DOIT PAS inclure la taille de lui-même ni la taille du champ AlignmentPadding, le cas échéant. |
| emf_spool_record_identifier | [EmfCommentEmfSpool+EmfSpoolRecordIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool+emfspoolrecordidentifierenum/) | r/w | Obtient ou définit un entier non signé de 32 bits qui identifie le type de <br/>            enregistrement EMR_COMMENT_EMFSPOOL. |
| emf_spool_records | [EmfSpoolFontDefinitionRecordType[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfspool.records/emfspoolfontdefinitionrecordtype/) | r/w | Obtient ou définit un tableau d'octets de longueur variable qui contient un ou plusieurs <br/>            enregistrements de définition de police EMFSPOOL ([MS-EMFSPOOL] section 2.2.3.3). |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCommentEmfSpool() {#EmfCommentEmfSpool__1}


```
 EmfCommentEmfSpool() 
```

Initialise une nouvelle instance de la classe [EmfCommentEmfSpool](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/).

### Constructor: EmfCommentEmfSpool(source) {#EmfCommentEmfSpool_source_2}


```
 EmfCommentEmfSpool(source) 
```

Initialise une nouvelle instance de la classe [EmfCommentEmfSpool](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/).

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


