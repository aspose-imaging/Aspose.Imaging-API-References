---
title: "Classe EmfCommentPublicRecordType"
type: docs
weight: 220
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/
---

**Summary:** The EMR_COMMENT_PUBLIC record types specify extensions to EMF processing.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType

**Inheritance:** EmfCommentRecordType

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | Obtient ou définit un entier non signé de 32 bits qui identifie cet enregistrement de commentaire <br/>            comme spécifiant des données publiques. La valeur 0x43494447, qui est la chaîne ASCII "CIDG", identifie <br/>            ceci comme un enregistrement EMR_COMMENT_PUBLIC. |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille, en octets, des champs <br/>            CommentIdentifier et CommentRecordParm dans le champ RecordBuffer qui <br/>            suit. Il NE DOIT PAS inclure la taille de lui-même ni la taille du champ AlignmentPadding, le cas échéant. |
| public_comment_identifier | [EmfEmrComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/) | r/w | Obtient ou définit un entier non signé de 32 bits qui identifie le type de <br/>            enregistrement de commentaire public. Cette valeur DOIT être l'une des valeurs listées dans le tableau précédent, qui <br/>            sont spécifiées dans l'énumération EmrComment (section 2.1.10), sauf si des types supplémentaires d'enregistrements de commentaires publics ont été implémentés sur le serveur d'impression. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


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


