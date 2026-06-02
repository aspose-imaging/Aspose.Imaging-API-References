---
title: "EmfPlusBrushDataFlags Énumération"
type: docs
weight: 30
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---

Les indicateurs BrushData spécifient les propriétés des pinceaux graphiques, y compris la présence de champs de données optionnels. Ces indicateurs peuvent être combinés pour spécifier plusieurs options.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusBrushDataFlags

## **Members**
| **Nom du membre** | **Description** |
| :- | :- |
| BRUSH_DATA_BLEND_FACTORS_H | Ce drapeau est significatif dans les objets EmfPlusLinearGradientBrushData et EmfPlusPathGradientBrushData.<br/>            Si l'option est activée, un objet [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) (section 2.2.2.5) qui spécifie un motif de mélange le long d'un dégradé horizontal DOIT être indiqué dans le champ OptionalData de l'objet de données de brosse. |
| BRUSH_DATA_BLEND_FACTORS_V | Ce drapeau est significatif dans les objets EmfPlusLinearGradientBrushData.<br/>            Si l'option est activée, un objet EmfPlusBlendFactors qui spécifie un motif de mélange le long d'un dégradé vertical DOIT être indiqué dans le champ OptionalData de l'objet de données de brosse. |
| BRUSH_DATA_DO_NOT_TRANSFORM | Ce drapeau est significatif dans les objets EmfPlusTextureBrushData.<br/>            Si l'option est activée, une transformation de l'espace mondial vers l'espace dispositif NE DOIT PAS être appliquée à la brosse de texture. |
| BRUSH_DATA_FOCUS_SCALES | Ce drapeau est significatif dans les objets EmfPlusPathGradientBrushData.<br/>            Si l'option est activée, un objet [EmfPlusFocusScaleData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata/) (section 2.2.2.18) DOIT être indiqué dans le champ OptionalData de l'objet de données de brosse. |
| BRUSH_DATA_IS_GAMMA_CORRECTED | Ce drapeau est significatif dans les objets EmfPlusLinearGradientBrushData, EmfPlusPathGradientBrushData et EmfPlusTextureBrushData.<br/>            Si l'option est activée, la brosse DOIT déjà être corrigée gamma ; c’est‑à‑dire que la luminosité et l’intensité de sortie ont été corrigées pour correspondre à l’image d’entrée. |
| BRUSH_DATA_PATH | Ce drapeau est significatif dans les objets [EmfPlusPathGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/) (section 2.2.2.29).<br/>            Si l'option est activée, un objet [EmfPlusBoundaryPathData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata/) (section 2.2.2.6) DOIT être indiqué dans le champ BoundaryData de l'objet de données de brosse.<br/>            Si l'option est désactivée, un objet [EmfPlusBoundaryPointData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata/) (section 2.2.2.7) DOIT être indiqué dans le champ BoundaryData de l'objet de données de brosse. |
| BRUSH_DATA_PRESET_COLORS | Ce drapeau est significatif dans les objets EmfPlusLinearGradientBrushData et EmfPlusPathGradientBrushData.<br/>            Si l'option est activée, un objet [EmfPlusBlendColors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/) (section 2.2.2.4) DOIT être indiqué dans le champ OptionalData de l'objet de données de brosse. |
| BRUSH_DATA_TRANSFORM | Ce drapeau est significatif dans les objets [EmfPlusLinearGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata/) (section 2.2.2.24), [EmfPlusPathGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/) et [EmfPlusTextureBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/) (section 2.2.2.45).<br/>            Si l'option est activée, une matrice de transformation 2x3 de l'espace mondial vers l'espace dispositif DOIT être indiquée dans le champ OptionalData de l'objet de données de brosse. |
