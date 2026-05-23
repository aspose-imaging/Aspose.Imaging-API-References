---
title: "Classe EmfPlusPathGradientBrushOptionalData"
type: docs
weight: 510
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/
---

**Summary:** The EmfPlusPathGradientBrushOptionalData object specifies optional data for a path gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusPathGradientBrushOptionalData()](#EmfPlusPathGradientBrushOptionalData__1) | Inizializza una nuova istanza della classe EmfPlusPathGradientBrushOptionalData |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| blend_pattern | [EmfPlusBlendBase](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/) | r/w | Ottiene o imposta un modello di fusione opzionale per il pennello a gradiente di percorso. Se questo campo è<br/>            presente, DEVE contenere o un oggetto EmfPlusBlendColors (sezione 2.2.4), <br/>            o un oggetto EmfPlusBlendFactors (sezione 2.2.5), ma NON DEVE contenere entrambi. <br/>            La tabella seguente mostra le combinazioni valide dei flag BrushData di EmfPlusPathGradientBrushData<br/>            e i relativi modelli di fusione: |
| focus_scale_data | [EmfPlusFocusScaleData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata/) | r/w | Ottiene o imposta un oggetto opzionale EmfPlusFocusScaleData (sezione 2.2.18) che specifica <br/>            le scale di messa a fuoco per il pennello a gradiente di percorso. Questo campo DEVE essere presente se il<br/>            flag BrushDataFocusScales è impostato nel campo BrushDataFlags dell'oggetto <br/>            EmfPlusPathGradientBrushData. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Ottiene o imposta un oggetto opzionale EmfPlusTransformMatrix (sezione 2.2.47) che specifica una trasformazione dallo spazio mondo allo spazio dispositivo per il pennello a gradiente di percorso. <br/>            Questo campo DEVE essere presente se il flag BrushDataTransform è impostato nel campo BrushDataFlags dell'oggetto EmfPlusPathGradientBrushData. |


### Constructor: EmfPlusPathGradientBrushOptionalData() {#EmfPlusPathGradientBrushOptionalData__1}


```
 EmfPlusPathGradientBrushOptionalData() 
```

Inizializza una nuova istanza della classe EmfPlusPathGradientBrushOptionalData

