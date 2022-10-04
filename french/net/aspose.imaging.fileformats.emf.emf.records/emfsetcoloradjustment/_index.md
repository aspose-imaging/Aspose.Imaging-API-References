---
title: EmfSetColorAdjustment
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistrement EMR_SETCOLORADJUSTMENT spécifie les propriétés de réglage des couleurs dans le contexte de lappareil playback .
type: docs
weight: 4310
url: /fr/net/aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/
---
## EmfSetColorAdjustment class

L'enregistrement EMR_SETCOLORADJUSTMENT spécifie les propriétés de réglage des couleurs dans le contexte de l'appareil playback .

```csharp
public sealed class EmfSetColorAdjustment : EmfStateRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfSetColorAdjustment](emfsetcoloradjustment)(EmfRecord) | Initialise une nouvelle instance du[`EmfSetColorAdjustment`](../emfsetcoloradjustment) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [ColorAdjustment](../../aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/coloradjustment) { get; set; } | Obtient ou définit un objet ColorAdjustment (section 2.2.2) qui spécifie les valeurs de réglage color . |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtient ou définit la taille de l'enregistrement |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtient ou définit le type. |

### Remarques

Les valeurs de réglage des couleurs sont utilisées pour ajuster la couleur d'entrée du bitmap source pour les opérations graphiques effectuées par les enregistrements EMR_STRETCHBLT et EMR_STRETCHDIBITS lorsque le mode STRETCH_HALFTONE est défini à partir de l'énumération StretchMode (section 2.1.32). L'objet ColorAdjustment spécifié par cet enregistrement DOIT être utilisé dans les opérations graphiques qui nécessitent un objet ColorAdjustment, jusqu'à ce qu'un autre objet ColorAdjustment soit spécifié par un autre enregistrement EMR_SETCOLORADJUSTMENT, ou jusqu'à ce que l'objet soit supprimé par un enregistrement EMR_DELETEOBJECT .

### Voir également

* class [EmfStateRecordType](../emfstaterecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->