---
title: "EmfPlusBrushDataFlags Enumeration"
type: docs
weight: 30
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---

BrushData‑flaggorna specificerar egenskaper för grafikpenslar, inklusive närvaron av valfria datafält. Dessa flaggor kan kombineras för att specificera flera alternativ.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusBrushDataFlags

## **Members**
| **Member name** | **Description** |
| :- | :- |
| BRUSH_DATA_BLEND_FACTORS_H | Denna flagga är meningsfull i EmfPlusLinearGradientBrushData- och EmfPlusPathGradientBrushData-objekt.<br/>            Om inställd, MÅSTE ett [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/)‑objekt (avsnitt 2.2.5) som specificerar ett blandningsmönster längs en horisontell gradient specificeras i OptionalData‑fältet för penseldatat. |
| BRUSH_DATA_BLEND_FACTORS_V | Denna flagga är meningsfull i EmfPlusLinearGradientBrushData-objekt.<br/>            Om inställd, MÅSTE ett EmfPlusBlendFactors‑objekt som specificerar ett blandningsmönster längs en vertikal gradient specificeras i OptionalData‑fältet för penseldatat. |
| BRUSH_DATA_DO_NOT_TRANSFORM | Denna flagga är meningsfull i EmfPlusTextureBrushData-objekt.<br/>            Om inställd, BÖR INTE en värld‑till‑enhet‑transform tillämpas på texturpenseln. |
| BRUSH_DATA_FOCUS_SCALES | Denna flagga är meningsfull i EmfPlusPathGradientBrushData-objekt.<br/>            Om inställd, MÅSTE ett[EmfPlusFocusScaleData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata/)‑objekt (avsnitt 2.2.2.18) specificeras i OptionalData‑fältet för penseldatat. |
| BRUSH_DATA_IS_GAMMA_CORRECTED | Denna flagga är meningsfull i EmfPlusLinearGradientBrushData-, EmfPlusPathGradientBrushData- och EmfPlusTextureBrushData-objekt.<br/>            Om inställd, MÅSTE penseln redan vara gamma‑korrigerad; det vill säga, utgångens ljusstyrka och intensitet har korrigerats för att matcha inmatningsbilden. |
| BRUSH_DATA_PATH | Denna flagga är meningsfull i [EmfPlusPathGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/)‑objekt (avsnitt 2.2.2.29).<br/>            Om inställd, MÅSTE ett [EmfPlusBoundaryPathData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata/)‑objekt (avsnitt 2.2.2.6) specificeras i BoundaryData‑fältet för penseldatat.<br/>            Om avaktiverad, MÅSTE ett [EmfPlusBoundaryPointData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata/)‑objekt (avsnitt 2.2.2.7) specificeras i BoundaryData‑fältet för penseldatat. |
| BRUSH_DATA_PRESET_COLORS | Denna flagga är meningsfull i EmfPlusLinearGradientBrushData- och EmfPlusPathGradientBrushData-objekt.<br/>            Om inställd, MÅSTE ett [EmfPlusBlendColors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/)‑objekt (avsnitt 2.2.2.4) specificeras i OptionalData‑fältet för penseldatat. |
| BRUSH_DATA_TRANSFORM | Denna flagga är meningsfull i [EmfPlusLinearGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata/)‑objekt (avsnitt 2.2.2.24), [EmfPlusPathGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/)‑objekt och [EmfPlusTextureBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/)‑objekt (avsnitt 2.2.2.45).<br/>            Om inställd, MÅSTE en 2x3‑värld‑till‑enhet‑transformmatris specificeras i OptionalData‑fältet för penseldatat. |
