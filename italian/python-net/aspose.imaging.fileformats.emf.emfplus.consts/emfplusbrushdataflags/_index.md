---
title: "EmfPlusBrushDataFlags Enumerazione"
type: docs
weight: 30
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---

I flag BrushData specificano le proprietà dei pennelli grafici, inclusa la presenza di campi dati opzionali. Questi flag possono essere combinati per specificare più opzioni.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusBrushDataFlags

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| BRUSH_DATA_BLEND_FACTORS_H | Questo flag è significativo negli oggetti EmfPlusLinearGradientBrushData e EmfPlusPathGradientBrushData.<br/>            Se impostato, un oggetto [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) (sezione 2.2.2.5) che specifica un modello di fusione lungo un gradiente orizzontale DEVE essere specificato nel campo OptionalData dell'oggetto dati del pennello. |
| BRUSH_DATA_BLEND_FACTORS_V | Questo flag è significativo negli oggetti EmfPlusLinearGradientBrushData.<br/>            Se impostato, un oggetto EmfPlusBlendFactors che specifica un modello di fusione lungo un gradiente verticale DEVE essere specificato nel campo OptionalData dell'oggetto dati del pennello. |
| BRUSH_DATA_DO_NOT_TRANSFORM | Questo flag è significativo negli oggetti EmfPlusTextureBrushData.<br/>            Se impostato, una trasformazione dallo spazio mondo allo spazio dispositivo NON DOVREBBE essere applicata al pennello texture. |
| BRUSH_DATA_FOCUS_SCALES | Questo flag è significativo negli oggetti EmfPlusPathGradientBrushData.<br/>            Se impostato, un[EmfPlusFocusScaleData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata/) (sezione 2.2.2.18) DEVE essere specificato nel campo OptionalData dell'oggetto dati del pennello. |
| BRUSH_DATA_IS_GAMMA_CORRECTED | Questo flag è significativo negli oggetti EmfPlusLinearGradientBrushData, EmfPlusPathGradientBrushData e EmfPlusTextureBrushData.<br/>            Se impostato, il pennello DEVE già essere corretto gamma; cioè, la luminosità e l'intensità dell'output sono state corrette per corrispondere all'immagine di input. |
| BRUSH_DATA_PATH | Questo flag è significativo negli oggetti [EmfPlusPathGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/) (sezione 2.2.2.29).<br/>            Se impostato, un oggetto [EmfPlusBoundaryPathData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata/) (sezione 2.2.2.6) DEVE essere specificato nel campo BoundaryData dell'oggetto dati del pennello.<br/>            Se non impostato, un oggetto [EmfPlusBoundaryPointData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata/) (sezione 2.2.2.7) DEVE essere specificato nel campo BoundaryData dell'oggetto dati del pennello. |
| BRUSH_DATA_PRESET_COLORS | Questo flag è significativo negli oggetti EmfPlusLinearGradientBrushData e EmfPlusPathGradientBrushData.<br/>            Se impostato, un oggetto [EmfPlusBlendColors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/) (sezione 2.2.2.4) DEVE essere specificato nel campo OptionalData dell'oggetto dati del pennello. |
| BRUSH_DATA_TRANSFORM | Questo flag è significativo negli oggetti [EmfPlusLinearGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata/) (sezione 2.2.2.24), [EmfPlusPathGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/) e [EmfPlusTextureBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/) (sezione 2.2.2.45).<br/>            Se impostato, una matrice di trasformazione 2x3 dallo spazio mondo allo spazio dispositivo DEVE essere specificata nel campo OptionalData dell'oggetto dati del pennello. |
