---
title: EmfPlusBrushDataFlags
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: I flag BrushData specificano le proprietà dei pennelli grafici inclusa la presenza di campi dati opzionali. Questi flag possono essere combinati per specificare più opzioni.
type: docs
weight: 4690
url: /it/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---
## EmfPlusBrushDataFlags enumeration

I flag BrushData specificano le proprietà dei pennelli grafici, inclusa la presenza di campi dati opzionali. Questi flag possono essere combinati per specificare più opzioni.

```csharp
[Flags]
public enum EmfPlusBrushDataFlags
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| BrushDataPath | `1` | Questo flag è significativo in[`EmfPlusPathGradientBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) oggetti (sezione 2.2.2.29). Se impostato, an[`EmfPlusBoundaryPathData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata) oggetto (sezione 2.2.2.6) DEVE essere specificato nel campo BoundaryData dell'oggetto dati pennello. Se deselezionato, un[`EmfPlusBoundaryPointData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata) oggetto (sezione 2.2.2.7) DEVE essere specificato nel campo BoundaryData dell'oggetto dati pennello. |
| BrushDataTransform | `2` | Questo flag è significativo in[`EmfPlusLinearGradientBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata) oggetti (sezione 2.2.2.24),[`EmfPlusPathGradientBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) oggetti, e[`EmfPlusTextureBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata) oggetti (sezione 2.2.2.45). Se impostata, una matrice di trasformazione da spazio mondo 2x3 a spazio dispositivo DEVE essere specificata nel campo OptionalData dell'oggetto dati pennello. |
| BrushDataPresetColors | `4` | Questo flag è significativo negli oggetti EmfPlusLinearGradientBrushData e EmfPlusPathGradientBrushData. Se impostato, un[`EmfPlusBlendColors`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors) oggetto (sezione 2.2.2.4) DEVE essere specificato nel campo OptionalData dell'oggetto dati pennello. |
| BrushDataBlendFactorsH | `8` | Questo flag è significativo negli oggetti EmfPlusLinearGradientBrushData e EmfPlusPathGradientBrushData. Se impostato, un[`EmfPlusBlendFactors`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors) oggetto (sezione 2.2.2.5) che specifica un modello di fusione lungo un gradiente orizzontale DEVE essere specificato nel campo OptionalData dell'oggetto dati pennello. |
| BrushDataBlendFactorsV | `10` | Questo flag è significativo negli oggetti EmfPlusLinearGradientBrushData. Se impostato, un oggetto EmfPlusBlendFactors che specifica un modello di fusione lungo un gradiente verticale DEVE essere specificato nel campo OptionalData dell'oggetto dati pennello. |
| BrushDataFocusScales | `40` | Questo flag è significativo negli oggetti EmfPlusPathGradientBrushData. Se impostato, un[`EmfPlusFocusScaleData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata) oggetto (sezione 2.2.2.18) DEVE essere specificato nel campo OptionalData dell'oggetto dati pennello. |
| BrushDataIsGammaCorrected | `80` | Questo flag è significativo negli oggetti EmfPlusLinearGradientBrushData, EmfPlusPathGradientBrushData e EmfPlusTextureBrushData. Se impostato, il pennello DEVE essere già corretto in gamma; ovvero, la luminosità e l'intensità dell'output sono state corrette per corrispondere all'immagine di input. |
| BrushDataDoNotTransform | `100` | Questo flag è significativo negli oggetti EmfPlusTextureBrushData. Se impostato, una trasformazione da spazio mondiale a spazio dispositivo NON DEVE essere applicata al pennello texture. |

### Guarda anche

* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
