---
title: EmfPlusBlendFactors Class
type: docs
weight: 90
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/
---

The EmfPlusBlendFactors object specifies positions and factors for the blend pattern of a gradient brush.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendFactors

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfPlusBlendFactors type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusBlendFactors()|Initializes a new instance of the EmfPlusBlendFactors class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|blend_positions|Gets or sets blend positions<br/>            An array of PositionCount 32-bit floating-point values<br/>             that specify proportions of distance along the gradient line.<br/>            Each element MUST be a number between 0.0 and 1.0 inclusive. <br/>            For a linear gradient brush, 0.0 represents the starting point <br/>            and 1.0 represents the ending point. For a path gradient brush, <br/>            0.0 represents the midpoint and 1.0 represents an endpoint|
|blend_factors|Gets or sets an array of PositionCount 32-bit floating point values that <br/>            specify proportions of colors at the positions defined in the BlendPositions field. <br/>            Each value MUST be a number between 0.0 and 1.0 inclusive.|
