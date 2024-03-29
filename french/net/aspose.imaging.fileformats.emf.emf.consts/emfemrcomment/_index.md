---
title: EmfEmrComment
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lénumération EmrComment définit les types de données quun enregistrement de commentaire public peut contenir comme spécifié dans la section 2.3.3.4.
type: docs
weight: 2620
url: /fr/net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/
---
## EmfEmrComment enumeration

L'énumération EmrComment définit les types de données qu'un enregistrement de commentaire public peut contenir, comme spécifié dans la section 2.3.3.4.

```csharp
public enum EmfEmrComment : uint
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| EMR_COMMENT_WINDOWS_METAFILE | `2147483649` | Cet enregistrement de commentaire contient une spécification d'une image dans WMF. Voir [MS-WMF] pour plus d'informations |
| EMR_COMMENT_BEGINGROUP | `2` | Cet enregistrement de commentaire identifie le début d'un groupe d'enregistrements de dessin. Il identifie un objet dans un métafichier EMF |
| EMR_COMMENT_ENDGROUP | `3` | Cet enregistrement de commentaire identifie la fin d'un groupe d'enregistrements de dessin. Pour chaque enregistrement EMR_COMMENT_BEGINGROUP , un enregistrement EMR_COMMENT_ENDGROUP DOIT être inclus dans le métafichier, et ils PEUVENT être imbriqués. |
| EMR_COMMENT_MULTIFORMATS | `1073741828` | Cet enregistrement de commentaire permet d'inclure plusieurs définitions d'une image dans le métafichier. En utilisant ce commentaire, par exemple, une application peut inclure du texte PostScript encapsulé ainsi qu'une définition EMF d'une image. |
| EMR_COMMENT_UNICODE_STRING | `64` | Cet enregistrement de commentaire est réservé et NE DOIT PAS être utilisé dans un métafichier EMF |
| EMR_COMMENT_UNICODE_END | `128` | Cet enregistrement de commentaire est réservé et NE DOIT PAS être utilisé dans un métafichier EMF |

### Voir également

* espace de noms [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
