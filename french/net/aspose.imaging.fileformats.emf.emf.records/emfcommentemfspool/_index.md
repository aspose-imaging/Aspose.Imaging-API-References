---
title: EmfCommentEmfSpool
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistrement EMR_COMMENT_EMFSPOOL contient des enregistrements EMFSPOOL intégrés. Remarque Les champs qui ne sont pas décrits dans cette section sont spécifiés dans la section 2.3.3.
type: docs
weight: 3370
url: /fr/net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/
---
## EmfCommentEmfSpool class

L'enregistrement EMR_COMMENT_EMFSPOOL contient des enregistrements EMFSPOOL intégrés. Remarque Les champs qui ne sont pas décrits dans cette section sont spécifiés dans la section 2.3.3.

```csharp
public sealed class EmfCommentEmfSpool : EmfCommentRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfCommentEmfSpool](emfcommentemfspool#constructor)() | Initialise une nouvelle instance du[`EmfCommentEmfSpool`](../emfcommentemfspool) classe. |
| [EmfCommentEmfSpool](emfcommentemfspool#constructor_1)(EmfRecord) | Initialise une nouvelle instance du[`EmfCommentEmfSpool`](../emfcommentemfspool) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/commentidentifier) { get; set; } | Obtient ou définit un entier non signé 32 bits qui identifie cet enregistrement de commentaire comme contenant des enregistrements EMFSPOOL. La valeur 0x00000000 l'identifie comme un enregistrement EMR_COMMENT_EMFSPOOL. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie la taille, en octets, des champs CommentIdentifier et CommentRecordParm dans le champ RecordBuffer qui suit . Il NE DOIT PAS inclure la taille de lui-même ou la taille du champ AlignmentPadding, si present |
| [EmfSpoolRecordIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/emfspoolrecordidentifier) { get; set; } | Obtient ou définit un entier non signé 32 bits qui identifie le type d'enregistrement EMR_COMMENT_EMFSPOOL. |
| [EmfSpoolRecords](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/emfspoolrecords) { get; set; } | Obtient ou définit un tableau d'octets de longueur variable qui contient un ou plusieurs enregistrements de définition de police EMFSPOOL ([MS-EMFSPOOL] section 2.2.3.3). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtient ou définit la taille de l'enregistrement |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtient ou définit le type. |

### Voir également

* class [EmfCommentRecordType](../emfcommentrecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->