---
title: CurveShape Class
type: docs
weight: 30
url: /python-net/api-reference/aspose.imaging.shapes/curveshape/
---

Represents a curved spline shape.

**Namespace:** [aspose.imaging.shapes](/imaging/python-net/api-reference/aspose.imaging.shapes/)

**Full Class Name:** aspose.imaging.shapes.CurveShape

**Assembly:**  Aspose.Imaging Version: 23.3.0

The CurveShape type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|CurveShape()|Initializes a new instance of the [CurveShape](/imaging/python-net/api-reference/aspose.imaging.shapes/curveshape/) class.|
|CurveShape(points)|Initializes a new instance of the CurveShape class|
|CurveShape(points, is_closed)|Initializes a new instance of the CurveShape class|
|CurveShape(points, tension)|Initializes a new instance of the CurveShape class|
|CurveShape(points, tension, is_closed)|Initializes a new instance of the CurveShape class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|bounds|Gets the object's bounds.|
|center|Gets the shape's center.|
|segments|Gets the shape segments.|
|has_segments|Gets a value indicating whether shape has segments.|
|points|Gets or sets the curve points.|
|is_closed|Gets or sets a value indicating whether shape is closed.|
|start_point|Gets the starting shape point.|
|end_point|Gets the ending shape point.|
|tension|Gets or sets the curve tension.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|get_bounds(matrix)|Gets the object's bounds.|
|get_bounds(matrix, pen)|Gets the object's bounds.|
|transform(transform)|Applies the specified transformation to the shape.|
|reverse()|Reverses the order of points for this shape.|
|create_with_point_fs_closed(points, is_closed)|Initializes a new instance of the [CurveShape](/imaging/python-net/api-reference/aspose.imaging.shapes/curveshape/) class. The default tension of 0.5 is used.|
|create_with_point_fs_tension(points, tension)|Initializes a new instance of the [CurveShape](/imaging/python-net/api-reference/aspose.imaging.shapes/curveshape/) class.|
