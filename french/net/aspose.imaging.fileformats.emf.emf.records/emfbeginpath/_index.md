---
title: EmfBeginPath
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Cet enregistrement ouvre une parenthèse de chemin dans le contexte de périphérique de lecture actuel. Une fois quune parenthèse de chemin est ouverte une application peut commencer à traiter les enregistrements pour définir les points qui se trouvent dans le chemin. Une application DOIT fermer une parenthèse de chemin ouverte en traitant lEMR_ENDPATH record. Lorsquune application traite lenregistrement EMR_BEGINPATH tous les chemins précédents DOIVENT être supprimés du contexte de périphérique de lecture.
type: docs
weight: 3240
url: /fr/net/aspose.imaging.fileformats.emf.emf.records/emfbeginpath/
---
## EmfBeginPath class

Cet enregistrement ouvre une parenthèse de chemin dans le contexte de périphérique de lecture actuel. Une fois qu'une parenthèse de chemin est ouverte, une application peut commencer à traiter les enregistrements pour définir les points qui se trouvent dans le chemin. Une application DOIT fermer une parenthèse de chemin ouverte en traitant l'EMR_ENDPATH record. Lorsqu'une application traite l'enregistrement EMR_BEGINPATH, tous les chemins précédents DOIVENT être supprimés du contexte de périphérique de lecture.

```csharp
public sealed class EmfBeginPath : EmfPathBracketRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfBeginPath](emfbeginpath)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtient ou définit la taille de l'enregistrement |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtient ou définit le type. |

### Voir également

* class [EmfPathBracketRecordType](../emfpathbracketrecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->