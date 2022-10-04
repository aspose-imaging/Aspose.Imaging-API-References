---
title: EmfPlusBrushDataFlags
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Les drapeaux BrushData spécifient les propriétés des pinceaux graphiques y compris la présence de champs de données facultatifs. Ces drapeaux peuvent être combinés pour spécifier plusieurs options.
type: docs
weight: 4690
url: /fr/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---
## EmfPlusBrushDataFlags enumeration

Les drapeaux BrushData spécifient les propriétés des pinceaux graphiques, y compris la présence de champs de données facultatifs. Ces drapeaux peuvent être combinés pour spécifier plusieurs options.

```csharp
[Flags]
public enum EmfPlusBrushDataFlags
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| BrushDataPath | `1` | Ce drapeau est significatif dans[`EmfPlusPathGradientBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) objets (section 2.2.2.29). Si défini, un[`EmfPlusBoundaryPathData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata) (section 2.2.2.6) DOIT être spécifié dans le champ BoundaryData de l'objet de données brush. Si clair, un[`EmfPlusBoundaryPointData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata) object (section 2.2.2.7) DOIT être spécifié dans le champ BoundaryData de l'objet de données brush. |
| BrushDataTransform | `2` | Ce drapeau est significatif dans[`EmfPlusLinearGradientBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata) objets (section 2.2.2.24),[`EmfPlusPathGradientBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) des objets, et[`EmfPlusTextureBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata) objets (section 2.2.2.45). Si elle est définie, une matrice de transformation espace monde 2x3 vers espace périphérique DOIT être spécifiée dans le champ OptionalData de l'objet de données brush. |
| BrushDataPresetColors | `4` | Cet indicateur est significatif dans les objets EmfPlusLinearGradientBrushData et EmfPlusPathGradientBrushData. S'il est défini, un[`EmfPlusBlendColors`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors) object (section 2.2.2.4) DOIT être spécifié dans le champ OptionalData de l'objet de données brush. |
| BrushDataBlendFactorsH | `8` | Cet indicateur est significatif dans les objets EmfPlusLinearGradientBrushData et EmfPlusPathGradientBrushData. S'il est défini, un[`EmfPlusBlendFactors`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors) objet (section 2.2.2.5) qui spécifie un motif de mélange le long d'un dégradé horizontal DOIT être spécifié dans le champ OptionalData de l'objet de données de pinceau. |
| BrushDataBlendFactorsV | `10` | Cet indicateur est significatif dans les objets EmfPlusLinearGradientBrushData. S'il est défini, un objet EmfPlusBlendFactors qui spécifie un motif de mélange le long d'un dégradé vertical DOIT être spécifié dans le champ OptionalData de l'objet de données de pinceau. |
| BrushDataFocusScales | `40` | Cet indicateur est significatif dans les objets EmfPlusPathGradientBrushData. S'il est défini, un[`EmfPlusFocusScaleData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata) object (section 2.2.2.18) DOIT être spécifié dans le champ OptionalData de l'objet de données brush. |
| BrushDataIsGammaCorrected | `80` | Cet indicateur est significatif dans les objets EmfPlusLinearGradientBrushData, EmfPlusPathGradientBrushData et EmfPlusTextureBrushData. S'il est défini, le pinceau DOIT déjà être corrigé gamma ; c'est-à-dire que la luminosité et l'intensité de sortie ont été corrigées pour correspondre à l'image d'entrée. |
| BrushDataDoNotTransform | `100` | Cet indicateur est significatif dans les objets EmfPlusTextureBrushData. S'il est défini, une transformation de l'espace universel en espace périphérique NE DOIT PAS être appliquée au pinceau de texture. |

### Voir également

* espace de noms [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->