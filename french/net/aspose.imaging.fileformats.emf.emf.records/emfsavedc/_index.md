---
title: EmfSaveDc
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Enregistre létat actuel du contexte de périphérique de lecture sur une pile détats enregistrés par les enregistrements EMR_SAVEDC précédents le cas échéant. Létat se compose de propriétés graphiques et dobjets y compris le bitmap actuellement sélectionné le pinceau  la palette la police le stylo et la région. Un enregistrement EMR_RESTOREDC est utilisé pour restaurer létat. Cet enregistrement EMF ne spécifie aucun paramètre.
type: docs
weight: 4210
url: /fr/net/aspose.imaging.fileformats.emf.emf.records/emfsavedc/
---
## EmfSaveDc class

Enregistre l'état actuel du contexte de périphérique de lecture sur une pile d'états enregistrés par les enregistrements EMR_SAVEDC précédents, le cas échéant. L'état se compose de propriétés graphiques et d'objets, y compris le bitmap actuellement sélectionné, le pinceau , la palette, la police, le stylo et la région. Un enregistrement EMR_RESTOREDC est utilisé pour restaurer l'état. Cet enregistrement EMF ne spécifie aucun paramètre.

```csharp
public sealed class EmfSaveDc : EmfStateRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfSaveDc](emfsavedc#constructor)() | Initialise une nouvelle instance du[`EmfSaveDc`](../emfsavedc) classe. |
| [EmfSaveDc](emfsavedc#constructor_1)(EmfRecord) | Initialise une nouvelle instance du[`EmfSaveDc`](../emfsavedc) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtient ou définit la taille de l'enregistrement |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtient ou définit le type. |

### Remarques

La pile peut contenir des informations d'état pour plusieurs instances du contexte de périphérique de lecture. Quand un état est restauré, toutes les instances d'état qui ont été enregistrées plus récemment DOIVENT être supprimées.

### Voir également

* class [EmfStateRecordType](../emfstaterecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->