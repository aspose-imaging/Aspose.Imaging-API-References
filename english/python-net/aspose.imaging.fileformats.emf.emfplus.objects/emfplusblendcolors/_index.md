---
title: EmfPlusBlendColors Class
type: docs
weight: 80
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/
---

**Summary:** The EmfPlusBlendColors object specifies positions and colors for the blend pattern of a gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendColors

**Inheritance:** EmfPlusBlendBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusBlendColors()](#EmfPlusBlendColors__1) | Initializes a new instance of the EmfPlusBlendColors class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blend_argb_32_colors | int[] | r/w | Gets or sets an array of PositionCount EmfPlusARGB objects (section 2.2.2.1) that <br/>            specify colors at the positions defined in the BlendPositions field. |
| blend_positions | float[] | r/w | Gets or sets blend positions<br/>            An array of PositionCount 32-bit floating-point values<br/>             that specify proportions of distance along the gradient line.<br/>            Each element MUST be a number between 0.0 and 1.0 inclusive. <br/>            For a linear gradient brush, 0.0 represents the starting point <br/>            and 1.0 represents the ending point. For a path gradient brush, <br/>            0.0 represents the midpoint and 1.0 represents an endpoint |


### Constructor: EmfPlusBlendColors() {#EmfPlusBlendColors__1}


```
 EmfPlusBlendColors() 
```

Initializes a new instance of the EmfPlusBlendColors class

