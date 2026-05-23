---
title: "EmfPlusLinearGradientBrushOptionalData Classe"
type: docs
weight: 450
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/
---

**Summary:** The EmfPlusLinearGradientBrushOptionalData object specifies optional data for a linear gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusLinearGradientBrushOptionalData()](#EmfPlusLinearGradientBrushOptionalData__1) | Inizializza una nuova istanza della classe EmfPlusLinearGradientBrushOptionalData |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| blend_pattern | [EmfPlusBlendBase[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/) | r/w | Ottiene o imposta un modello di fusione opzionale per il pennello a gradiente lineare. Se questo campo è presente, <br/>            DEVE contenere o un oggetto EmfPlusBlendColors (sezione 2.2.2.4), <br/>            o uno o due oggetti EmfPlusBlendFactors (sezione 2.2.2.5), <br/>            ma NON DEVE contenere entrambi. La tabella seguente mostra le combinazioni valide di <br/>            flag BrushData di EmfPlusLinearGradientBrushData e i corrispondenti modelli di fusione:<br/>            EmfPlusBlendFactors |
| blend_pattern_as_blend_factors_h | [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) | r | Restituisce il modello di fusione come fattori di fusione h. |
| blend_pattern_as_blend_factors_v | [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) | r | Restituisce il modello di fusione come fattori di fusione v. |
| blend_pattern_as_preset_colors | [EmfPlusBlendColors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/) | r | Ottiene il modello di fusione come colori predefiniti. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Ottiene o imposta un oggetto opzionale EmfPlusTransformMatrix (sezione 2.2.2.47) che specifica una<br/>            trasformazione dallo spazio mondo allo spazio dispositivo per il pennello a gradiente lineare. <br/>            Questo campo DEVE essere presente se il flag BrushDataTransform è impostato nel<br/>            campo BrushDataFlags dell'oggetto EmfPlusLinearGradientBrushData. |


### Constructor: EmfPlusLinearGradientBrushOptionalData() {#EmfPlusLinearGradientBrushOptionalData__1}


```
 EmfPlusLinearGradientBrushOptionalData() 
```

Inizializza una nuova istanza della classe EmfPlusLinearGradientBrushOptionalData

