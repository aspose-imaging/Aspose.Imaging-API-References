---
title: "Classe EmfCommentWindowsMetaFile"
type: docs
weight: 240
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/
---

**Summary:** The EMR_COMMENT_WINDOWS_METAFILE record specifies an image in an embedded WMF metafile.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentWindowsMetaFile

**Inheritance:** EmfCommentPublicRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfCommentWindowsMetaFile(source)](#EmfCommentWindowsMetaFile_source_1) | Initialise une nouvelle instance de la classe [EmfCommentWindowsMetaFile](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| somme de contrôle | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie la somme de contrôle pour cet enregistrement. |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | Obtient ou définit un entier non signé de 32 bits qui identifie cet enregistrement de commentaire <br/>            comme spécifiant des données publiques. La valeur 0x43494447, qui est la chaîne ASCII "CIDG", identifie <br/>            ceci comme un enregistrement EMR_COMMENT_PUBLIC. |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille, en octets, des champs <br/>            CommentIdentifier et CommentRecordParm dans le champ RecordBuffer qui <br/>            suit. Il NE DOIT PAS inclure la taille de lui-même ni la taille du champ AlignmentPadding, le cas échéant. |
| flags | int | r/w | Obtient ou définit une valeur de 32 bits qui DOIT être 0x00000000 et DOIT être ignorée. |
| public_comment_identifier | [EmfEmrComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/) | r/w | Obtient ou définit un entier non signé de 32 bits qui identifie le type de <br/>            enregistrement de commentaire public. Cette valeur DOIT être l'une des valeurs listées dans le tableau précédent, qui <br/>            sont spécifiées dans l'énumération EmrComment (section 2.1.10), sauf si des types supplémentaires d'enregistrements de commentaires publics ont été implémentés sur le serveur d'impression. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
| version | [WmfMetafileVersion](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileversion/) | r/w | Obtient ou définit un entier non signé de 16 bits qui spécifie la version du métafichier WMF en termes <br/>            de prise en charge des bitmaps indépendants du dispositif (DIB), provenant de l'énumération WMF MetafileVersion <br/>            ([MS-WMF] section 2.1.1.19). |
| win_metafile | [MetaImage](/imaging/python-net/aspose.imaging.fileformats.emf/metaimage/) | r/w | Obtient ou définit un tampon qui contient le métafichier WMF. |
| win_metafile_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille, en octets, du <br/>            métafichier WMF dans le champ WinMetafile. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCommentWindowsMetaFile(source) {#EmfCommentWindowsMetaFile_source_1}


```
 EmfCommentWindowsMetaFile(source) 
```

Initialise une nouvelle instance de la classe [EmfCommentWindowsMetaFile](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/) .

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


