---
title: Region
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 10810
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
| [Region](region)() | Initializes a new [`Region`](../region). |
| [Region](region)(GraphicsPath) | Initializes a new [`Region`](../region) with the specified [`GraphicsPath`](../graphicspath). |
| [Region](region)(Rectangle) | Initializes a new [`Region`](../region) from the specified [`Rectangle`](../rectangle) structure. |
| [Region](region)(RectangleF) | Initializes a new [`Region`](../region) from the specified [`RectangleF`](../rectanglef) structure. |

## Methods

| Name | Description |
| --- | --- |
| [Complement](complement)(GraphicsPath) | Updates this [`Region`](../region) to contain the portion of the specified [`GraphicsPath`](../graphicspath) that does not intersect with this [`Region`](../region). |
| [Complement](complement)(Rectangle) | Updates this [`Region`](../region) to contain the portion of the specified [`Rectangle`](../rectangle) structure that does not intersect with this [`Region`](../region). |
| [Complement](complement)(RectangleF) | Updates this [`Region`](../region) to contain the portion of the specified [`RectangleF`](../rectanglef) structure that does not intersect with this [`Region`](../region). |
| [Complement](complement)(Region) | Updates this [`Region`](../region) to contain the portion of the specified [`Region`](../region) that does not intersect with this [`Region`](../region). |
| [DeepClone](deepclone)() | Creates an exact deep copy of this [`Region`](../region). |
| [Equals](equals)(Region, Graphics) | Tests whether the specified [`Region`](../region) is identical to this [`Region`](../region) on the specified drawing surface. |
| [Exclude](exclude)(GraphicsPath) | Updates this [`Region`](../region) to contain only the portion of its interior that does not intersect with the specified [`GraphicsPath`](../graphicspath). |
| [Exclude](exclude)(Rectangle) | Updates this [`Region`](../region) to contain only the portion of its interior that does not intersect with the specified [`Rectangle`](../rectangle) structure. |
| [Exclude](exclude)(RectangleF) | Updates this [`Region`](../region) to contain only the portion of its interior that does not intersect with the specified [`RectangleF`](../rectanglef) structure. |
| [Exclude](exclude)(Region) | Updates this [`Region`](../region) to contain only the portion of its interior that does not intersect with the specified [`Region`](../region). |
| [Intersect](intersect)(GraphicsPath) | Updates this [`Region`](../region) to the intersection of itself with the specified [`GraphicsPath`](../graphicspath). |
| [Intersect](intersect)(Rectangle) | Updates this [`Region`](../region) to the intersection of itself with the specified [`Rectangle`](../rectangle) structure. |
| [Intersect](intersect)(RectangleF) | Updates this [`Region`](../region) to the intersection of itself with the specified [`RectangleF`](../rectanglef) structure. |
| [Intersect](intersect)(Region) | Updates this [`Region`](../region) to the intersection of itself with the specified [`Region`](../region). |
| [IsEmpty](isempty)(Graphics) | Tests whether this [`Region`](../region) has an empty interior on the specified drawing surface. |
| [IsInfinite](isinfinite)(Graphics) | Tests whether this [`Region`](../region) has an infinite interior on the specified drawing surface. |
| [IsVisible](isvisible)(Point) | Tests whether the specified [`Point`](../point) structure is contained within this [`Region`](../region). |
| [IsVisible](isvisible)(PointF) | Tests whether the specified [`PointF`](../pointf) structure is contained within this [`Region`](../region). |
| [IsVisible](isvisible)(Rectangle) | Tests whether any portion of the specified [`Rectangle`](../rectangle) structure is contained within this [`Region`](../region). |
| [IsVisible](isvisible)(RectangleF) | Tests whether any portion of the specified [`RectangleF`](../rectanglef) structure is contained within this [`Region`](../region). |
| [IsVisible](isvisible)(float, float) | Tests whether the specified point is contained within this [`Region`](../region). |
| [IsVisible](isvisible)(Point, Graphics) | Tests whether the specified [`Point`](../point) structure is contained within this [`Region`](../region) when drawn using the specified [`Graphics`](../graphics). |
| [IsVisible](isvisible)(PointF, Graphics) | Tests whether the specified [`PointF`](../pointf) structure is contained within this [`Region`](../region) when drawn using the specified [`Graphics`](../graphics). |
| [IsVisible](isvisible)(Rectangle, Graphics) | Tests whether any portion of the specified [`Rectangle`](../rectangle) structure is contained within this [`Region`](../region) when drawn using the specified [`Graphics`](../graphics). |
| [IsVisible](isvisible)(RectangleF, Graphics) | Tests whether any portion of the specified [`RectangleF`](../rectanglef) structure is contained within this [`Region`](../region) when drawn using the specified [`Graphics`](../graphics). |
| [IsVisible](isvisible)(float, float, Graphics) | Tests whether the specified point is contained within this [`Region`](../region) when drawn using the specified [`Graphics`](../graphics). |
| [IsVisible](isvisible)(int, int, Graphics) | Tests whether the specified point is contained within this [`Region`](../region) object when drawn using the specified [`Graphics`](../graphics) object. |
| [IsVisible](isvisible)(float, float, float, float) | Tests whether any portion of the specified rectangle is contained within this [`Region`](../region). |
| [IsVisible](isvisible)(int, int, int, int) | Tests whether any portion of the specified rectangle is contained within this [`Region`](../region). |
| [IsVisible](isvisible)(float, float, float, float, Graphics) | Tests whether any portion of the specified rectangle is contained within this [`Region`](../region) when drawn using the specified [`Graphics`](../graphics). |
| [IsVisible](isvisible)(int, int, int, int, Graphics) | Tests whether any portion of the specified rectangle is contained within this [`Region`](../region) when drawn using the specified [`Graphics`](../graphics). |
| [MakeEmpty](makeempty)() | Initializes this [`Region`](../region) to an empty interior. |
| [MakeInfinite](makeinfinite)() | Initializes this [`Region`](../region) object to an infinite interior. |
| [Transform](transform)(Matrix) | Transforms this [`Region`](../region) by the specified [`Matrix`](../matrix). |
| [Translate](translate)(float, float) | Offsets the coordinates of this [`Region`](../region) by the specified amount. |
| [Translate](translate)(int, int) | Offsets the coordinates of this [`Region`](../region) by the specified amount. |
| [Union](union)(GraphicsPath) | Updates this [`Region`](../region) to the union of itself and the specified [`GraphicsPath`](../graphicspath). |
| [Union](union)(Rectangle) | Updates this [`Region`](../region) to the union of itself and the specified [`Rectangle`](../rectangle) structure. |
| [Union](union)(RectangleF) | Updates this [`Region`](../region) to the union of itself and the specified [`RectangleF`](../rectanglef) structure. |
| [Union](union)(Region) | Updates this [`Region`](../region) to the union of itself and the specified [`Region`](../region). |
| [Xor](xor)(GraphicsPath) | Updates this [`Region`](../region) to the union minus the intersection of itself with the specified [`GraphicsPath`](../graphicspath). |
| [Xor](xor)(Rectangle) | Updates this [`Region`](../region) to the union minus the intersection of itself with the specified [`Rectangle`](../rectangle) structure. |
| [Xor](xor)(RectangleF) | Updates this [`Region`](../region) to the union minus the intersection of itself with the specified [`RectangleF`](../rectanglef) structure. |
| [Xor](xor)(Region) | Updates this [`Region`](../region) to the union minus the intersection of itself with the specified [`Region`](../region). |

### See Also

* namespace [Aspose.Imaging](../../aspose.imaging)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
