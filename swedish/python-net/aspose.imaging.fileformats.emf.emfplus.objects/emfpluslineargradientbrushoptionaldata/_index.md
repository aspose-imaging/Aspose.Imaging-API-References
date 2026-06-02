---
title: "EmfPlusLinearGradientBrushOptionalData-klass"
type: docs
weight: 450
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/
---

**Summary:** The EmfPlusLinearGradientBrushOptionalData object specifies optional data for a linear gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusLinearGradientBrushOptionalData()](#EmfPlusLinearGradientBrushOptionalData__1) | Initierar en ny instans av klassen EmfPlusLinearGradientBrushOptionalData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blend_pattern | [EmfPlusBlendBase[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/) | r/w | Hämtar eller anger ett valfritt blandningsmönster för den linjära gradientpenseln. Om detta fält är närvarande, <br/>            MÅSTE det innehålla antingen ett EmfPlusBlendColors-objekt (avsnitt 2.2.2.4), <br/>            eller ett eller två EmfPlusBlendFactors-objekt (avsnitt 2.2.2.5), <br/>            men det MÅSTE INTE innehålla båda. Tabellen nedan visar de giltiga kombinationerna av <br/>            EmfPlusLinearGradientBrushData BrushData-flaggor och motsvarande blandningsmönster:<br/>            EmfPlusBlendFactors |
| blend_pattern_as_blend_factors_h | [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) | r | Hämtar blandningsmönstret som blandningsfaktorer h. |
| blend_pattern_as_blend_factors_v | [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) | r | Hämtar blandningsmönstret som blandningsfaktorer v. |
| blend_pattern_as_preset_colors | [EmfPlusBlendColors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/) | r | Hämtar blandningsmönstret som förinställda färger. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Hämtar eller anger ett valfritt EmfPlusTransformMatrix-objekt (avsnitt 2.2.2.47) som specificerar en<br/>            världstillägg till enhetstilläggstransformation för den linjära gradientpenseln. <br/>            Detta fält MÅSTE vara närvarande om BrushDataTransform-flaggan är satt i<br/>            BrushDataFlags-fältet i EmfPlusLinearGradientBrushData-objektet. |


### Constructor: EmfPlusLinearGradientBrushOptionalData() {#EmfPlusLinearGradientBrushOptionalData__1}


```
 EmfPlusLinearGradientBrushOptionalData() 
```

Initierar en ny instans av klassen EmfPlusLinearGradientBrushOptionalData

