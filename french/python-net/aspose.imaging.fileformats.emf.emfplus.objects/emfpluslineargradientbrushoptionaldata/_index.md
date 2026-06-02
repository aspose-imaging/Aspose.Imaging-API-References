---
title: "Classe EmfPlusLinearGradientBrushOptionalData"
type: docs
weight: 450
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/
---

**Summary:** The EmfPlusLinearGradientBrushOptionalData object specifies optional data for a linear gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusLinearGradientBrushOptionalData()](#EmfPlusLinearGradientBrushOptionalData__1) | Initialise une nouvelle instance de la classe EmfPlusLinearGradientBrushOptionalData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blend_pattern | [EmfPlusBlendBase[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/) | r/w | Obtient ou définit un motif de mélange optionnel pour le pinceau à dégradé linéaire. Si ce champ est présent, <br/>            il DOIT contenir soit un objet EmfPlusBlendColors (section 2.2.2.4), <br/>            soit un ou deux objets EmfPlusBlendFactors (section 2.2.2.5), <br/>            mais il NE DOIT PAS contenir les deux. Le tableau ci‑dessous montre les combinaisons valides de <br/>            indicateurs BrushData de EmfPlusLinearGradientBrushData et les motifs de mélange correspondants :<br/>            EmfPlusBlendFactors |
| blend_pattern_as_blend_factors_h | [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) | r | Obtient le motif de mélange sous forme de facteurs de mélange h. |
| blend_pattern_as_blend_factors_v | [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) | r | Obtient le motif de mélange sous forme de facteurs de mélange v. |
| blend_pattern_as_preset_colors | [EmfPlusBlendColors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/) | r | Obtient le motif de mélange sous forme de couleurs prédéfinies. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtient ou définit un objet optionnel EmfPlusTransformMatrix (section 2.2.2.47) qui spécifie une<br/>            transformation de l'espace monde vers l'espace dispositif pour le pinceau à dégradé linéaire. <br/>            Ce champ DOIT être présent si le drapeau BrushDataTransform est défini dans le<br/>            champ BrushDataFlags de l'objet EmfPlusLinearGradientBrushData. |


### Constructor: EmfPlusLinearGradientBrushOptionalData() {#EmfPlusLinearGradientBrushOptionalData__1}


```
 EmfPlusLinearGradientBrushOptionalData() 
```

Initialise une nouvelle instance de la classe EmfPlusLinearGradientBrushOptionalData

