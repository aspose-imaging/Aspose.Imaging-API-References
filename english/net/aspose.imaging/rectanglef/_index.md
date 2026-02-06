---
title: Struct RectangleF
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.RectangleF struct. Stores a set of four floatingpoint numbers that represent the location and size of a rectangle
type: docs
weight: 11410
url: /net/aspose.imaging/rectanglef/
---
## RectangleF structure

Stores a set of four floating-point numbers that represent the location and size of a rectangle.

```csharp
public struct RectangleF
```

## Constructors

| Name | Description |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | Initializes a new instance of the `RectangleF` structure with the specified location and size. |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | Initializes a new instance of the `RectangleF` structure with the specified location and size. |

## Properties

| Name | Description |
| --- | --- |
| static [Empty](../../aspose.imaging/rectanglef/empty/) { get; } | Gets a new instance of the `RectangleF` structure that has [`X`](./x/), [`Y`](./y/), [`Width`](./width/) and [`Height`](./height/) values set to zero. |
| [Bottom](../../aspose.imaging/rectanglef/bottom/) { get; set; } | Gets or sets the y-coordinate that is the sum of [`Y`](./y/) and [`Height`](./height/) of this `RectangleF` structure. |
| [Height](../../aspose.imaging/rectanglef/height/) { get; set; } | Gets or sets the height of this `RectangleF` structure. |
| [IsEmpty](../../aspose.imaging/rectanglef/isempty/) { get; } | Gets a value indicating whether the [`Width`](./width/) or [`Height`](./height/) property of this `RectangleF` has a value of zero. |
| [Left](../../aspose.imaging/rectanglef/left/) { get; set; } | Gets or sets the x-coordinate of the left edge of this `RectangleF` structure. |
| [Location](../../aspose.imaging/rectanglef/location/) { get; set; } | Gets or sets the coordinates of the upper-left corner of this `RectangleF` structure. |
| [Right](../../aspose.imaging/rectanglef/right/) { get; set; } | Gets or sets the x-coordinate that is the sum of [`X`](./x/) and [`Width`](./width/) of this `RectangleF` structure. |
| [Size](../../aspose.imaging/rectanglef/size/) { get; set; } | Gets or sets the size of this `RectangleF`. |
| [Top](../../aspose.imaging/rectanglef/top/) { get; set; } | Gets or sets the y-coordinate of the top edge of this `RectangleF` structure. |
| [Width](../../aspose.imaging/rectanglef/width/) { get; set; } | Gets or sets the width of this `RectangleF` structure. |
| [X](../../aspose.imaging/rectanglef/x/) { get; set; } | Gets or sets the x-coordinate of the upper-left corner of this `RectangleF` structure. |
| [Y](../../aspose.imaging/rectanglef/y/) { get; set; } | Gets or sets the y-coordinate of the upper-left corner of this `RectangleF` structure. |

## Methods

| Name | Description |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.imaging/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | Creates a `RectangleF` structure with upper-left corner and lower-right corner at the specified locations. |
| static [FromPoints](../../aspose.imaging/rectanglef/frompoints/)(PointF, PointF) | Creates a new [`Rectangle`](../rectangle/) from two points specified. Two verticles of the created [`Rectangle`](../rectangle/) will be equal to the passed *point1* and *point2*. These would be typically the opposite vertices. |
| static [Inflate](../../aspose.imaging/rectanglef/inflate/)(RectangleF, float, float) | Creates and returns an inflated copy of the specified `RectangleF` structure. The copy is inflated by the specified amount. The original rectangle remains unmodified. |
| static [Intersect](../../aspose.imaging/rectanglef/intersect/)(RectangleF, RectangleF) | Returns a `RectangleF` structure that represents the intersection of two rectangles. If there is no intersection, and empty `RectangleF` is returned. |
| static [Union](../../aspose.imaging/rectanglef/union/)(RectangleF, RectangleF) | Creates the smallest possible third rectangle that can contain both of two rectangles that form a union. |
| [Contains](../../aspose.imaging/rectanglef/contains/#contains)(PointF) | Determines if the specified point is contained within this `RectangleF` structure. |
| [Contains](../../aspose.imaging/rectanglef/contains/#contains_1)(RectangleF) | Determines if the rectangular region represented by *rect* is entirely contained within this `RectangleF` structure. |
| [Contains](../../aspose.imaging/rectanglef/contains/#contains_2)(float, float) | Determines if the specified point is contained within this `RectangleF` structure. |
| override [Equals](../../aspose.imaging/rectanglef/equals/)(object) | Tests whether *obj* is a `RectangleF` with the same location and size of this `RectangleF`. |
| override [GetHashCode](../../aspose.imaging/rectanglef/gethashcode/)() | Gets the hash code for this `RectangleF` structure. |
| [Inflate](../../aspose.imaging/rectanglef/inflate/#inflate)(SizeF) | Inflates this `RectangleF` by the specified amount. |
| [Inflate](../../aspose.imaging/rectanglef/inflate/#inflate_1)(float, float) | Inflates this `RectangleF` structure by the specified amount. |
| [Intersect](../../aspose.imaging/rectanglef/intersect/)(RectangleF) | Replaces this `RectangleF` structure with the intersection of itself and the specified `RectangleF` structure. |
| [IntersectsWith](../../aspose.imaging/rectanglef/intersectswith/)(RectangleF) | Determines if this rectangle intersects with *rect*. |
| [Normalize](../../aspose.imaging/rectanglef/normalize/)() | Normalizes the rectangle by making it's width and height positive, left less than right and top less than bottom. |
| [Offset](../../aspose.imaging/rectanglef/offset/#offset)(PointF) | Adjusts the location of this rectangle by the specified amount. |
| [Offset](../../aspose.imaging/rectanglef/offset/#offset_1)(float, float) | Adjusts the location of this rectangle by the specified amount. |
| override [ToString](../../aspose.imaging/rectanglef/tostring/)() | Converts the attributes of this `RectangleF` to a human-readable string. |
| [operator /](../../aspose.imaging/rectanglef/op_division/) | Implements the operator /. |
| [operator ==](../../aspose.imaging/rectanglef/op_equality/) | Tests whether two `RectangleF` structures have equal location and size. |
| [implicit operator](../../aspose.imaging/rectanglef/op_implicit/) | Converts the specified [`Rectangle`](../rectangle/) structure to a `RectangleF` structure. |
| [operator !=](../../aspose.imaging/rectanglef/op_inequality/) | Tests whether two `RectangleF` structures differ in location or size. |
| [operator *](../../aspose.imaging/rectanglef/op_multiply/) | Implements the operator *. |

### See Also

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


