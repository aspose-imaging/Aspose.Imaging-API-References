---
title: Class Region
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.Region class. Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited
type: docs
weight: 11340
url: /net/aspose.imaging/region/
---
## Region class

Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited.

```csharp
public sealed class Region
```

## Constructors

| Name | Description |
| --- | --- |
| [Region](region/#constructor)() | Initializes a new `Region`. |
| [Region](region/#constructor_1)(GraphicsPath) | Initializes a new `Region` with the specified [`GraphicsPath`](../graphicspath/). |
| [Region](region/#constructor_2)(Rectangle) | Initializes a new `Region` from the specified [`Rectangle`](../rectangle/) structure. |
| [Region](region/#constructor_3)(RectangleF) | Initializes a new `Region` from the specified [`RectangleF`](../rectanglef/) structure. |

## Methods

| Name | Description |
| --- | --- |
| [Complement](../../aspose.imaging/region/complement/#complement)(GraphicsPath) | Updates this `Region` to contain the portion of the specified [`GraphicsPath`](../graphicspath/) that does not intersect with this `Region`. |
| [Complement](../../aspose.imaging/region/complement/#complement_1)(Rectangle) | Updates this `Region` to contain the portion of the specified [`Rectangle`](../rectangle/) structure that does not intersect with this `Region`. |
| [Complement](../../aspose.imaging/region/complement/#complement_2)(RectangleF) | Updates this `Region` to contain the portion of the specified [`RectangleF`](../rectanglef/) structure that does not intersect with this `Region`. |
| [Complement](../../aspose.imaging/region/complement/#complement_3)(Region) | Updates this `Region` to contain the portion of the specified `Region` that does not intersect with this `Region`. |
| [DeepClone](../../aspose.imaging/region/deepclone/)() | Creates an exact deep copy of this `Region`. |
| override [Equals](../../aspose.imaging/region/equals/#equals_1)(object) | Check if objects are equal. |
| [Equals](../../aspose.imaging/region/equals/#equals)(Region, Graphics) | Tests whether the specified `Region` is identical to this `Region` on the specified drawing surface. |
| [Exclude](../../aspose.imaging/region/exclude/#exclude)(GraphicsPath) | Updates this `Region` to contain only the portion of its interior that does not intersect with the specified [`GraphicsPath`](../graphicspath/). |
| [Exclude](../../aspose.imaging/region/exclude/#exclude_1)(Rectangle) | Updates this `Region` to contain only the portion of its interior that does not intersect with the specified [`Rectangle`](../rectangle/) structure. |
| [Exclude](../../aspose.imaging/region/exclude/#exclude_2)(RectangleF) | Updates this `Region` to contain only the portion of its interior that does not intersect with the specified [`RectangleF`](../rectanglef/) structure. |
| [Exclude](../../aspose.imaging/region/exclude/#exclude_3)(Region) | Updates this `Region` to contain only the portion of its interior that does not intersect with the specified `Region`. |
| override [GetHashCode](../../aspose.imaging/region/gethashcode/)() | Get hash code of the current object. |
| [Intersect](../../aspose.imaging/region/intersect/#intersect)(GraphicsPath) | Updates this `Region` to the intersection of itself with the specified [`GraphicsPath`](../graphicspath/). |
| [Intersect](../../aspose.imaging/region/intersect/#intersect_1)(Rectangle) | Updates this `Region` to the intersection of itself with the specified [`Rectangle`](../rectangle/) structure. |
| [Intersect](../../aspose.imaging/region/intersect/#intersect_2)(RectangleF) | Updates this `Region` to the intersection of itself with the specified [`RectangleF`](../rectanglef/) structure. |
| [Intersect](../../aspose.imaging/region/intersect/#intersect_3)(Region) | Updates this `Region` to the intersection of itself with the specified `Region`. |
| [IsEmpty](../../aspose.imaging/region/isempty/)(Graphics) | Tests whether this `Region` has an empty interior on the specified drawing surface. |
| [IsInfinite](../../aspose.imaging/region/isinfinite/)(Graphics) | Tests whether this `Region` has an infinite interior on the specified drawing surface. |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible)(Point) | Tests whether the specified [`Point`](../point/) structure is contained within this `Region`. |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_2)(PointF) | Tests whether the specified [`PointF`](../pointf/) structure is contained within this `Region`. |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_4)(Rectangle) | Tests whether any portion of the specified [`Rectangle`](../rectangle/) structure is contained within this `Region`. |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_6)(RectangleF) | Tests whether any portion of the specified [`RectangleF`](../rectanglef/) structure is contained within this `Region`. |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_11)(float, float) | Tests whether the specified point is contained within this `Region`. |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_1)(Point, Graphics) | Tests whether the specified [`Point`](../point/) structure is contained within this `Region` when drawn using the specified [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_3)(PointF, Graphics) | Tests whether the specified [`PointF`](../pointf/) structure is contained within this `Region` when drawn using the specified [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_5)(Rectangle, Graphics) | Tests whether any portion of the specified [`Rectangle`](../rectangle/) structure is contained within this `Region` when drawn using the specified [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_7)(RectangleF, Graphics) | Tests whether any portion of the specified [`RectangleF`](../rectanglef/) structure is contained within this `Region` when drawn using the specified [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_12)(float, float, Graphics) | Tests whether the specified point is contained within this `Region` when drawn using the specified [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_8)(int, int, Graphics) | Tests whether the specified point is contained within this `Region` object when drawn using the specified [`Graphics`](../graphics/) object. |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_13)(float, float, float, float) | Tests whether any portion of the specified rectangle is contained within this `Region`. |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_9)(int, int, int, int) | Tests whether any portion of the specified rectangle is contained within this `Region`. |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_14)(float, float, float, float, Graphics) | Tests whether any portion of the specified rectangle is contained within this `Region` when drawn using the specified [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_10)(int, int, int, int, Graphics) | Tests whether any portion of the specified rectangle is contained within this `Region` when drawn using the specified [`Graphics`](../graphics/). |
| [MakeEmpty](../../aspose.imaging/region/makeempty/)() | Initializes this `Region` to an empty interior. |
| [MakeInfinite](../../aspose.imaging/region/makeinfinite/)() | Initializes this `Region` object to an infinite interior. |
| [Transform](../../aspose.imaging/region/transform/)(Matrix) | Transforms this `Region` by the specified [`Matrix`](../matrix/). |
| [Translate](../../aspose.imaging/region/translate/#translate_1)(float, float) | Offsets the coordinates of this `Region` by the specified amount. |
| [Translate](../../aspose.imaging/region/translate/#translate)(int, int) | Offsets the coordinates of this `Region` by the specified amount. |
| [Union](../../aspose.imaging/region/union/#union)(GraphicsPath) | Updates this `Region` to the union of itself and the specified [`GraphicsPath`](../graphicspath/). |
| [Union](../../aspose.imaging/region/union/#union_1)(Rectangle) | Updates this `Region` to the union of itself and the specified [`Rectangle`](../rectangle/) structure. |
| [Union](../../aspose.imaging/region/union/#union_2)(RectangleF) | Updates this `Region` to the union of itself and the specified [`RectangleF`](../rectanglef/) structure. |
| [Union](../../aspose.imaging/region/union/#union_3)(Region) | Updates this `Region` to the union of itself and the specified `Region`. |
| [Xor](../../aspose.imaging/region/xor/#xor)(GraphicsPath) | Updates this `Region` to the union minus the intersection of itself with the specified [`GraphicsPath`](../graphicspath/). |
| [Xor](../../aspose.imaging/region/xor/#xor_1)(Rectangle) | Updates this `Region` to the union minus the intersection of itself with the specified [`Rectangle`](../rectangle/) structure. |
| [Xor](../../aspose.imaging/region/xor/#xor_2)(RectangleF) | Updates this `Region` to the union minus the intersection of itself with the specified [`RectangleF`](../rectanglef/) structure. |
| [Xor](../../aspose.imaging/region/xor/#xor_3)(Region) | Updates this `Region` to the union minus the intersection of itself with the specified `Region`. |

### See Also

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


