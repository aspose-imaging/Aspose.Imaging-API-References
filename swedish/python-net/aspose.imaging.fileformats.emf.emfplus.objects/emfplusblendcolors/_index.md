---
title: "EmfPlusBlendColors klass"
type: docs
weight: 80
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/
---

**Summary:** The EmfPlusBlendColors object specifies positions and colors for the blend pattern of a gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendColors

**Inheritance:** EmfPlusBlendBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusBlendColors()](#EmfPlusBlendColors__1) | Initierar en ny instans av EmfPlusBlendColors‑klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blend_argb_32_colors | int[] | r/w | Hämtar eller anger en array av PositionCount EmfPlusARGB‑objekt (avsnitt 2.2.2.1) som <br/>            specificerar färger vid de positioner som definieras i BlendPositions‑fältet. |
| blend_positions | float[] | r/w | Hämtar eller anger blandningspositioner<br/>            En matris av PositionCount 32‑bit flyttalsvärden<br/>             som specificerar avståndsproportioner längs gradientlinjen.<br/>            Varje element MÅSTE vara ett tal mellan 0.0 och 1.0 inklusive. <br/>            För en linjär gradientpensel representerar 0.0 startpunkten <br/>            och 1.0 slutpunkten. För en bangradientpensel <br/>            representerar 0.0 mittpunkten och 1.0 ett slutpunkt. |


### Constructor: EmfPlusBlendColors() {#EmfPlusBlendColors__1}


```
 EmfPlusBlendColors() 
```

Initierar en ny instans av EmfPlusBlendColors‑klassen

