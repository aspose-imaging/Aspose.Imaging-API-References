---
title: EmfComment
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistrement EMR_COMMENT contient des données privées arbitraires. Remarque Les champs qui ne sont pas décrits dans cette section sont spécifiés dans la section 2.3.3.
type: docs
weight: 3340
url: /fr/net/aspose.imaging.fileformats.emf.emf.records/emfcomment/
---
## EmfComment class

L'enregistrement EMR_COMMENT contient des données privées arbitraires. Remarque Les champs qui ne sont pas décrits dans cette section sont spécifiés dans la section 2.3.3.

```csharp
public sealed class EmfComment : EmfCommentRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfComment](emfcomment)(EmfRecord) | Initialise une nouvelle instance du[`EmfComment`](../emfcomment) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcomment/commentidentifier) { get; set; } | Obtient ou définit l'identifiant du commentaire. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie la taille, en octets, des champs CommentIdentifier et CommentRecordParm dans le champ RecordBuffer qui suit . Il NE DOIT PAS inclure la taille de lui-même ou la taille du champ AlignmentPadding, si present |
| [PrivateData](../../aspose.imaging.fileformats.emf.emf.records/emfcomment/privatedata) { get; set; } | Obtient ou définit un tableau facultatif d'octets qui spécifie les données privées. Le premier DWORD de ces données NE DOIT PAS être l'une des valeurs d'identifiant de commentaire prédéfinies spécifiées dans la section 2.3.3. Les données privées sont inconnues d'EMF ; il n'a de sens que pour les applications qui connaissent le format des données et comment les utiliser. Les enregistrements de données privées EMR_COMMENT PEUVENT être ignorés. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtient ou définit la taille de l'enregistrement |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtient ou définit le type. |

### Voir également

* class [EmfCommentRecordType](../emfcommentrecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->