---
title: "EmfPlusBlendFactors-klass"
type: docs
weight: 90
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/
---

**Summary:** The EmfPlusBlendFactors object specifies positions and factors for the blend pattern of a gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendFactors

**Inheritance:** EmfPlusBlendBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusBlendFactors()](#EmfPlusBlendFactors__1) | Initierar en ny instans av EmfPlusBlendFactors-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blend_factors | float[] | r/w | Hämtar eller anger en matris av PositionCount 32‑bit flyttalsvärden som <br/>            specificerar färgproportioner vid de positioner som definieras i BlendPositions‑fältet. <br/>            Varje värde MÅSTE vara ett tal mellan 0.0 och 1.0 inklusive. |
| blend_positions | float[] | r/w | Hämtar eller anger blandningspositioner<br/>            En matris av PositionCount 32‑bit flyttalsvärden<br/>             som specificerar avståndsproportioner längs gradientlinjen.<br/>            Varje element MÅSTE vara ett tal mellan 0.0 och 1.0 inklusive. <br/>            För en linjär gradientpensel representerar 0.0 startpunkten <br/>            och 1.0 slutpunkten. För en bangradientpensel <br/>            representerar 0.0 mittpunkten och 1.0 ett slutpunkt. |


### Constructor: EmfPlusBlendFactors() {#EmfPlusBlendFactors__1}


```
 EmfPlusBlendFactors() 
```

Initierar en ny instans av EmfPlusBlendFactors-klassen

