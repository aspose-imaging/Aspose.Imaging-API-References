---
title: RectangleF
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 10800
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
| [RectangleF](rectanglef)(PointF, SizeF) | Initializes a new instance of the [`RectangleF`](../rectanglef) structure with the specified location and size. |
| [RectangleF](rectanglef)(float, float, float, float) | Initializes a new instance of the [`RectangleF`](../rectanglef) structure with the specified location and size. |

## Properties

| Name | Description |
| --- | --- |
| static [Empty](empty) { get; } | Gets a new instance of the [`RectangleF`](../rectanglef) structure that has [`X`](./x), [`Y`](./y), [`Width`](./width) and [`Height`](./height) values set to zero. |
| [Bottom](bottom) { get; set; } | Gets or sets the y-coordinate that is the sum of [`Y`](./y) and [`Height`](./height) of this [`RectangleF`](../rectanglef) structure. |
| [Height](height) { get; set; } | Gets or sets the height of this [`RectangleF`](../rectanglef) structure. |
| [IsEmpty](isempty) { get; } | Gets a value indicating whether the [`Width`](./width) or [`Height`](./height) property of this [`RectangleF`](../rectanglef) has a value of zero. |
| [Left](left) { get; set; } | Gets or sets the x-coordinate of the left edge of this [`RectangleF`](../rectanglef) structure. |
| [Location](location) { get; set; } | Gets or sets the coordinates of the upper-left corner of this [`RectangleF`](../rectanglef) structure. |
| [Right](right) { get; set; } | Gets or sets the x-coordinate that is the sum of [`X`](./x) and [`Width`](./width) of this [`RectangleF`](../rectanglef) structure. |
| [Size](size) { get; set; } | Gets or sets the size of this [`RectangleF`](../rectanglef). |
| [Top](top) { get; set; } | Gets or sets the y-coordinate of the top edge of this [`RectangleF`](../rectanglef) structure. |
| [Width](width) { get; set; } | Gets or sets the width of this [`RectangleF`](../rectanglef) structure. |
| [X](x) { get; set; } | Gets or sets the x-coordinate of the upper-left corner of this [`RectangleF`](../rectanglef) structure. |
| [Y](y) { get; set; } | Gets or sets the y-coordinate of the upper-left corner of this [`RectangleF`](../rectanglef) structure. |

## Methods

| Name | Description |
| --- | --- |
| static [FromLeftTopRightBottom](fromlefttoprightbottom)(float, float, float, float) | Creates a [`RectangleF`](../rectanglef) structure with upper-left corner and lower-right corner at the specified locations. |
| static [FromPoints](frompoints)(PointF, PointF) | Creates a new [`Rectangle`](../rectangle) from two points specified. Two verticles of the created [`Rectangle`](../rectangle) will be equal to the passed *point1* and *point2*. These would be typically the opposite vertices. |
| static [Inflate](inflate)(RectangleF, float, float) | Creates and returns an inflated copy of the specified [`RectangleF`](../rectanglef) structure. The copy is inflated by the specified amount. The original rectangle remains unmodified. |
| static [Intersect](intersect)(RectangleF, RectangleF) | Returns a [`RectangleF`](../rectanglef) structure that represents the intersection of two rectangles. If there is no intersection, and empty [`RectangleF`](../rectanglef) is returned. |
| static [Union](union)(RectangleF, RectangleF) | Creates the smallest possible third rectangle that can contain both of two rectangles that form a union. |
| [Contains](contains)(PointF) | Determines if the specified point is contained within this [`RectangleF`](../rectanglef) structure. |
| [Contains](contains)(RectangleF) | Determines if the rectangular region represented by *rect* is entirely contained within this [`RectangleF`](../rectanglef) structure. |
| [Contains](contains)(float, float) | Determines if the specified point is contained within this [`RectangleF`](../rectanglef) structure. |
| override [Equals](equals)(object) | Tests whether *obj* is a [`RectangleF`](../rectanglef) with the same location and size of this [`RectangleF`](../rectanglef). |
| override [GetHashCode](gethashcode)() | Gets the hash code for this [`RectangleF`](../rectanglef) structure. |
| [Inflate](inflate)(SizeF) | Inflates this [`RectangleF`](../rectanglef) by the specified amount. |
| [Inflate](inflate)(float, float) | Inflates this [`RectangleF`](../rectanglef) structure by the specified amount. |
| [Intersect](intersect)(RectangleF) | Replaces this [`RectangleF`](../rectanglef) structure with the intersection of itself and the specified [`RectangleF`](../rectanglef) structure. |
| [IntersectsWith](intersectswith)(RectangleF) | Determines if this rectangle intersects with *rect*. |
| [Normalize](normalize)() | Normalizes the rectangle by making it's width and height positive, left less than right and top less than bottom. |
| [Offset](offset)(PointF) | Adjusts the location of this rectangle by the specified amount. |
| [Offset](offset)(float, float) | Adjusts the location of this rectangle by the specified amount. |
| override [ToString](tostring)() | Converts the attributes of this [`RectangleF`](../rectanglef) to a human-readable string. |
| [operator /](op_division) | Implements the operator /. |
| [operator ==](op_equality) | Tests whether two [`RectangleF`](../rectanglef) structures have equal location and size. |
| [implicit operator](op_implicit) | Converts the specified [`Rectangle`](../rectangle) structure to a [`RectangleF`](../rectanglef) structure. |
| [operator !=](op_inequality) | Tests whether two [`RectangleF`](../rectanglef) structures differ in location or size. |
| [operator *](op_multiply) | Implements the operator *. |

### See Also

* namespace [Aspose.Imaging](../../aspose.imaging)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
