---
title: EmfPlusBrushDataFlags
second_title: Aspose.Imaging för .NET API-referens
description: BrushData-flaggorna anger egenskaper för grafikpenslar inklusive närvaron av valfria datafält. Dessa flaggor kan kombineras för att ange flera alternativ.
type: docs
weight: 4690
url: /sv/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---
## EmfPlusBrushDataFlags enumeration

BrushData-flaggorna anger egenskaper för grafikpenslar, inklusive närvaron av valfria datafält. Dessa flaggor kan kombineras för att ange flera alternativ.

```csharp
[Flags]
public enum EmfPlusBrushDataFlags
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| BrushDataPath | `1` | Den här flaggan är meningsfull i[`EmfPlusPathGradientBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) objekt (avsnitt 2.2.2.29). Om angivet, en[`EmfPlusBoundaryPathData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata) objekt (avsnitt 2.2.2.6) MÅSTE anges i BoundaryData-fältet för penseldataobjektet. Om det är klart, en[`EmfPlusBoundaryPointData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata) objekt (avsnitt 2.2.2.7) MÅSTE anges i fältet BoundaryData för penseldataobjektet. |
| BrushDataTransform | `2` | Den här flaggan är meningsfull i[`EmfPlusLinearGradientBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata) föremål (avsnitt 2.2.2.24),[`EmfPlusPathGradientBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) föremål och[`EmfPlusTextureBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata) objekt (avsnitt 2.2.2.45). Om det är inställt, MÅSTE en transformationsmatris på 2x3 världsutrymme till enhetsutrymme anges i fältet OptionalData för penseldataobjektet. |
| BrushDataPresetColors | `4` | Den här flaggan är meningsfull i EmfPlusLinearGradientBrushData- och EmfPlusPathGradientBrushData-objekt. Om inställt, en[`EmfPlusBlendColors`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors) objekt (avsnitt 2.2.2.4) MÅSTE anges i fältet OptionalData för penseldataobjektet. |
| BrushDataBlendFactorsH | `8` | Den här flaggan är meningsfull i EmfPlusLinearGradientBrushData- och EmfPlusPathGradientBrushData-objekt. Om inställt, en[`EmfPlusBlendFactors`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors) objekt (avsnitt 2.2.2.5) som anger ett blandningsmönster längs en horisontell gradient MÅSTE anges i fältet OptionalData för penseldataobjektet. |
| BrushDataBlendFactorsV | `10` | Den här flaggan är meningsfull i EmfPlusLinearGradientBrushData-objekt. Om det är inställt MÅSTE ett EmfPlusBlendFactors-objekt som specificerar ett blandningsmönster längs en vertikal gradient anges i fältet OptionalData för borstdataobjektet. |
| BrushDataFocusScales | `40` | Denna flagga är meningsfull i EmfPlusPathGradientBrushData-objekt. Om den är inställd, en[`EmfPlusFocusScaleData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata) objekt (avsnitt 2.2.2.18) MÅSTE anges i fältet OptionalData för penseldataobjektet. |
| BrushDataIsGammaCorrected | `80` | Den här flaggan är meningsfull i objekten EmfPlusLinearGradientBrushData, EmfPlusPathGradientBrushData och EmfPlusTextureBrushData. Om den är inställd MÅSTE borsten redan vara gammakorrigerad; det vill säga utgående ljusstyrka och intensitet har korrigerats för att matcha ingångsbilden. |
| BrushDataDoNotTransform | `100` | Den här flaggan är meningsfull i EmfPlusTextureBrushData-objekt. Om den är inställd SKA en transformation av världsutrymme till enhetsutrymme INTE tillämpas på texturborsten. |

### Se även

* namnutrymme [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
