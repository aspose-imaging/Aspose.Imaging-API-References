---
title: "EmfPlusPathGradientBrushOptionalData klass"
type: docs
weight: 510
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/
---

**Summary:** The EmfPlusPathGradientBrushOptionalData object specifies optional data for a path gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusPathGradientBrushOptionalData()](#EmfPlusPathGradientBrushOptionalData__1) | Initierar en ny instans av EmfPlusPathGradientBrushOptionalData‑klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blend_pattern | [EmfPlusBlendBase](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/) | r/w | Hämtar eller anger ett valfritt blandningsmönster för bangradientpenseln. Om detta fält är<br/>            närvarande MÅSTE det innehålla antingen ett EmfPlusBlendColors‑objekt (avsnitt 2.2.2.4), <br/>            eller ett EmfPlusBlendFactors‑objekt (avsnitt 2.2.2.5), men det MÅSTE INTE innehålla båda. <br/>            Tabellen nedan visar de giltiga kombinationerna av EmfPlusPathGradientBrushData<br/>            BrushData‑flaggor och motsvarande blandningsmönster: |
| focus_scale_data | [EmfPlusFocusScaleData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata/) | r/w | Hämtar eller anger ett valfritt EmfPlusFocusScaleData‑objekt (avsnitt 2.2.2.18) som specificerar <br/>            fokusskalor för bangradientpenseln. Detta fält MÅSTE vara närvarande om<br/>            BrushDataFocusScales‑flaggan är satt i BrushDataFlags‑fältet i <br/>            EmfPlusPathGradientBrushData‑objektet. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Hämtar eller anger ett valfritt EmfPlusTransformMatrix‑objekt (avsnitt 2.2.2.47) som specificerar en transform från världsrummet till enhetsrummet för bangradientpenseln. <br/>            Detta fält MÅSTE vara närvarande om BrushDataTransform‑flaggan är satt i BrushDataFlags‑fältet i EmfPlusPathGradientBrushData‑objektet. |


### Constructor: EmfPlusPathGradientBrushOptionalData() {#EmfPlusPathGradientBrushOptionalData__1}


```
 EmfPlusPathGradientBrushOptionalData() 
```

Initierar en ny instans av EmfPlusPathGradientBrushOptionalData‑klassen

