---
title: Class CurveShape
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.Shapes.CurveShape class. Represents a curved spline shape
type: docs
weight: 11490
url: /net/aspose.imaging.shapes/curveshape/
---
## CurveShape class

Represents a curved spline shape.

```csharp
public sealed class CurveShape : PolygonShape
```

## Constructors

| Name | Description |
| --- | --- |
| [CurveShape](curveshape/#constructor)() | Initializes a new instance of the `CurveShape` class. |
| [CurveShape](curveshape/#constructor_1)(PointF[]) | Initializes a new instance of the `CurveShape` class. The default tension of 0.5 is used. |
| [CurveShape](curveshape/#constructor_2)(PointF[], bool) | Initializes a new instance of the `CurveShape` class. The default tension of 0.5 is used. |
| [CurveShape](curveshape/#constructor_3)(PointF[], float) | Initializes a new instance of the `CurveShape` class. |
| [CurveShape](curveshape/#constructor_4)(PointF[], float, bool) | Initializes a new instance of the `CurveShape` class. |

## Properties

| Name | Description |
| --- | --- |
| override [Bounds](../../aspose.imaging.shapes/curveshape/bounds/) { get; } | Gets the object's bounds. |
| override [Center](../../aspose.imaging.shapes/curveshape/center/) { get; } | Gets the shape's center. |
| virtual [EndPoint](../../aspose.imaging.shapes/polygonshape/endpoint/) { get; } | Gets the ending shape point. |
| override [HasSegments](../../aspose.imaging.shapes/polygonshape/hassegments/) { get; } | Gets a value indicating whether shape has segments. |
| [IsClosed](../../aspose.imaging.shapes/polygonshape/isclosed/) { get; set; } | Gets or sets a value indicating whether shape is closed. |
| [Points](../../aspose.imaging.shapes/polygonshape/points/) { get; set; } | Gets or sets the curve points. |
| override [Segments](../../aspose.imaging.shapes/curveshape/segments/) { get; } | Gets the shape segments. |
| virtual [StartPoint](../../aspose.imaging.shapes/polygonshape/startpoint/) { get; } | Gets the starting shape point. |
| [Tension](../../aspose.imaging.shapes/curveshape/tension/) { get; set; } | Gets or sets the curve tension. |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.imaging.shapes/curveshape/equals/)(object) | Check if objects are equal. |
| override [GetBounds](../../aspose.imaging.shapes/curveshape/getbounds/#getbounds)(Matrix) | Gets the object's bounds. |
| override [GetBounds](../../aspose.imaging.shapes/curveshape/getbounds/#getbounds_1)(Matrix, Pen) | Gets the object's bounds. |
| override [GetHashCode](../../aspose.imaging.shapes/curveshape/gethashcode/)() | Get hash code of the current object. |
| [Reverse](../../aspose.imaging.shapes/polygonshape/reverse/)() | Reverses the order of points for this shape. |
| override [Transform](../../aspose.imaging.shapes/polygonshape/transform/)(Matrix) | Applies the specified transformation to the shape. |

### See Also

* class [PolygonShape](../polygonshape/)
* namespace [Aspose.Imaging.Shapes](../../aspose.imaging.shapes/)
* assembly [Aspose.Imaging](../../)


