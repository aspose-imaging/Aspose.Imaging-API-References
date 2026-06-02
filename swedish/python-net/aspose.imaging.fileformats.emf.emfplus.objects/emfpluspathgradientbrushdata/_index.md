---
title: "EmfPlusPathGradientBrushData klass"
type: docs
weight: 500
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/
---

**Summary:** The EmfPlusPathGradientBrushData object specifies a path gradient for a graphics brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushData

**Inheritance:** EmfPlusBaseBrushData

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusPathGradientBrushData()](#EmfPlusPathGradientBrushData__1) | Initierar en ny instans av klassen EmfPlusPathGradientBrushData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| boundary_data | [EmfPlusBoundaryBase](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase/) | r/w | Hämtar eller anger gränsen för path gradient-penseln, som specificeras antingen av en bana eller en sluten kardinal-spline. <br/>            Om BrushDataPath-flaggan är satt i BrushDataFlags-fältet, måste detta fält INNEHÅLLA ett EmfPlusBoundaryPathData-objekt (avsnitt 2.2.2.6); <br/>            annars måste detta fält INNEHÅLLA ett EmfPlusBoundaryPointData-objekt (avsnitt 2.2.2.7). |
| brush_data_flags | [EmfPlusBrushDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar data i OptionalData-fältet.<br/>            Detta värde MÅSTE bestå av BrushData-flaggor (avsnitt 2.1.2.1). Följande flaggor är relevanta för en path gradient-pensel: |
| center_argb_32_color | int | r/w | Hämtar eller anger EmfPlusARGB-objekt (avsnitt 2.2.2.1) som specificerar mittfärgen för <br/>            path gradient-penseln, vilket är färgen som visas vid penselns mittpunkt. <br/>            Penselns färg förändras gradvis från gränsfärgen <br/>            till mittfärgen när den rör sig från gränsen till mittpunkten. |
| center_point_f | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Hämtar eller anger EmfPlusARGB-objekt (avsnitt 2.2.2.1) som specificerar mittfärgen för path gradient-penseln, <br/>            vilket är färgen som visas vid penselns mittpunkt. Penselns färg förändras gradvis från gränsfärgen till mittfärgen när den rör sig<br/>            från gränsen till mittpunkten. |
| optional_data | [EmfPlusPathGradientBrushOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/) | r/w | Hämtar eller anger ett valfritt EmfPlusPathGradientBrushOptionalData-objekt (avsnitt 2.2.2.30) som <br/>            specificerar ytterligare data för path gradient-penseln. <br/>            Det specifika innehållet i detta fält bestäms av värdet i BrushDataFlags-fältet. |
| surrounding_argb_32_colors | int[] | r/w | Hämtar eller anger en array av SurroundingColorCount EmfPlusARGB-objekt <br/>            som specificerar färgerna för diskreta punkter på penselns gräns. |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | Hämtar eller anger ett 32-bitars signerat heltal från WrapMode-enumerationen (avsnitt 2.1.1.34) som specificerar<br/>            om området utanför penselns gräns ska målas. När man målar <br/>            utanför gränsen anger wrap-läget hur färggradienten upprepas |


### Constructor: EmfPlusPathGradientBrushData() {#EmfPlusPathGradientBrushData__1}


```
 EmfPlusPathGradientBrushData() 
```

Initierar en ny instans av klassen EmfPlusPathGradientBrushData

