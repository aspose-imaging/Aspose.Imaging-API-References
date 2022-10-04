---
title: EmfPolyTextOutW
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistrement EMR_POLYTEXTOUTW dessine une ou plusieurs chaînes de texte Unicode en utilisant la police et les couleurs de texte actuelles.
type: docs
weight: 4070
url: /fr/net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/
---
## EmfPolyTextOutW class

L'enregistrement EMR_POLYTEXTOUTW dessine une ou plusieurs chaînes de texte Unicode en utilisant la police et les couleurs de texte actuelles.

```csharp
public sealed class EmfPolyTextOutW : EmfDrawingRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfPolyTextOutW](emfpolytextoutw#constructor)() | Initialise une nouvelle instance du[`EmfPolyTextOutW`](../emfpolytextoutw) classe. |
| [EmfPolyTextOutW](emfpolytextoutw#constructor_1)(EmfRecord) | Initialise une nouvelle instance du[`EmfPolyTextOutW`](../emfpolytextoutw) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/bounds) { get; set; } | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19), qui spécifie le rectangle de délimitation en unités de périphérique. |
| [ExScale](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/exscale) { get; set; } | Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie l'échelle X des unités de page aux unités 0,01 mm si le mode graphique est GM_COMPATIBLE. |
| [EyScale](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/eyscale) { get; set; } | Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie l'échelle Y des unités de page aux unités 0,01 mm si le mode graphique est GM_COMPATIBLE. |
| [IGraphicsMode](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/igraphicsmode) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le mode graphique actuel, à partir de l'énumération GraphicsMode (section 2.1.16). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtient ou définit la taille de l'enregistrement |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtient ou définit le type. |
| [WEmrText](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/wemrtext) { get; set; } | Obtient ou définit un tableau d'objets EmrText (section 2.2.5) qui spécifient les chaînes de sortie en caractères Unicode UTF16-LE 16 bits, avec des attributs de texte et des valeurs d'espacement. Le nombre d'objets EmrText est spécifié par cStrings. |

### Remarques

Les couleurs de police et de texte utilisées pour la sortie sont spécifiées par les propriétés dans l'état actuel du contexte de périphérique de lecture . EMR_POLYTEXTOUTW DEVRAIT être émulé avec une série d'enregistrements EMR_EXTTEXTOUTW (section 2.3.5.7), un par chaîne.

### Voir également

* class [EmfDrawingRecordType](../emfdrawingrecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->