---
title: "Classe EmfPlusPathGradientBrushOptionalData"
type: docs
weight: 510
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/
---

**Summary:** The EmfPlusPathGradientBrushOptionalData object specifies optional data for a path gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusPathGradientBrushOptionalData()](#EmfPlusPathGradientBrushOptionalData__1) | Initialise une nouvelle instance de la classe EmfPlusPathGradientBrushOptionalData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blend_pattern | [EmfPlusBlendBase](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/) | r/w | Obtient ou définit un motif de mélange optionnel pour le pinceau de dégradé de chemin. Si ce champ est<br/>            présent, il DOIT contenir soit un objet EmfPlusBlendColors (section 2.2.2.4), <br/>            soit un objet EmfPlusBlendFactors (section 2.2.2.5), mais il NE DOIT PAS contenir les deux. <br/>            Le tableau ci‑dessous montre les combinaisons valides des indicateurs EmfPlusPathGradientBrushData<br/>            BrushData et les motifs de mélange correspondants : |
| focus_scale_data | [EmfPlusFocusScaleData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata/) | r/w | Obtient ou définit un objet optionnel EmfPlusFocusScaleData (section 2.2.2.18) qui spécifie <br/>            les échelles de mise au point pour le pinceau de dégradé de chemin. Ce champ DOIT être présent si le<br/>            indicateur BrushDataFocusScales est défini dans le champ BrushDataFlags de l<br/>            objet EmfPlusPathGradientBrushData. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtient ou définit un objet optionnel EmfPlusTransformMatrix (section 2.2.2.47) qui spécifie une transformation de l'espace monde vers l'espace dispositif pour le pinceau de dégradé de chemin. <br/>            Ce champ DOIT être présent si l'indicateur BrushDataTransform est défini dans le champ BrushDataFlags de l'objet EmfPlusPathGradientBrushData. |


### Constructor: EmfPlusPathGradientBrushOptionalData() {#EmfPlusPathGradientBrushOptionalData__1}


```
 EmfPlusPathGradientBrushOptionalData() 
```

Initialise une nouvelle instance de la classe EmfPlusPathGradientBrushOptionalData

