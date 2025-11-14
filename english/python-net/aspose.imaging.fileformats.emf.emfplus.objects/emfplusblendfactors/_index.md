---
title: EmfPlusBlendFactors Class
type: docs
weight: 90
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/
---

**Summary:** The EmfPlusBlendFactors object specifies positions and factors for the blend pattern of a gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendFactors

**Inheritance:** EmfPlusBlendBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusBlendFactors()](#EmfPlusBlendFactors__1) | Initializes a new instance of the EmfPlusBlendFactors class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blend_factors | float[] | r/w | Gets or sets an array of PositionCount 32-bit floating point values that <br/>            specify proportions of colors at the positions defined in the BlendPositions field. <br/>            Each value MUST be a number between 0.0 and 1.0 inclusive. |
| blend_positions | float[] | r/w | Gets or sets blend positions<br/>            An array of PositionCount 32-bit floating-point values<br/>             that specify proportions of distance along the gradient line.<br/>            Each element MUST be a number between 0.0 and 1.0 inclusive. <br/>            For a linear gradient brush, 0.0 represents the starting point <br/>            and 1.0 represents the ending point. For a path gradient brush, <br/>            0.0 represents the midpoint and 1.0 represents an endpoint |


### Constructor: EmfPlusBlendFactors() {#EmfPlusBlendFactors__1}


```
 EmfPlusBlendFactors() 
```

Initializes a new instance of the EmfPlusBlendFactors class

