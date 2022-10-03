---
title: RectangleF
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 10870
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
| static [Empty](../../aspose.imaging/rectanglef/empty) { get; } | Gets a new instance of the [`RectangleF`](../rectanglef) structure that has [`X`](./x), [`Y`](./y), [`Width`](./width) and [`Height`](./height) values set to zero. |
| [Bottom](../../aspose.imaging/rectanglef/bottom) { get; set; } | Gets or sets the y-coordinate that is the sum of [`Y`](./y) and [`Height`](./height) of this [`RectangleF`](../rectanglef) structure. |
| [Height](../../aspose.imaging/rectanglef/height) { get; set; } | Gets or sets the height of this [`RectangleF`](../rectanglef) structure. |
| [IsEmpty](../../aspose.imaging/rectanglef/isempty) { get; } | Gets a value indicating whether the [`Width`](./width) or [`Height`](./height) property of this [`RectangleF`](../rectanglef) has a value of zero. |
| [Left](../../aspose.imaging/rectanglef/left) { get; set; } | Gets or sets the x-coordinate of the left edge of this [`RectangleF`](../rectanglef) structure. |
| [Location](../../aspose.imaging/rectanglef/location) { get; set; } | Gets or sets the coordinates of the upper-left corner of this [`RectangleF`](../rectanglef) structure. |
| [Right](../../aspose.imaging/rectanglef/right) { get; set; } | Gets or sets the x-coordinate that is the sum of [`X`](./x) and [`Width`](./width) of this [`RectangleF`](../rectanglef) structure. |
| [Size](../../aspose.imaging/rectanglef/size) { get; set; } | Gets or sets the size of this [`RectangleF`](../rectanglef). |
| [Top](../../aspose.imaging/rectanglef/top) { get; set; } | Gets or sets the y-coordinate of the top edge of this [`RectangleF`](../rectanglef) structure. |
| [Width](../../aspose.imaging/rectanglef/width) { get; set; } | Gets or sets the width of this [`RectangleF`](../rectanglef) structure. |
| [X](../../aspose.imaging/rectanglef/x) { get; set; } | Gets or sets the x-coordinate of the upper-left corner of this [`RectangleF`](../rectanglef) structure. |
| [Y](../../aspose.imaging/rectanglef/y) { get; set; } | Gets or sets the y-coordinate of the upper-left corner of this [`RectangleF`](../rectanglef) structure. |

## Methods

| Name | Description |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.imaging/rectanglef/fromlefttoprightbottom)(float, float, float, float) | Creates a [`RectangleF`](../rectanglef) structure with upper-left corner and lower-right corner at the specified locations. |
| static [FromPoints](../../aspose.imaging/rectanglef/frompoints)(PointF, PointF) | Creates a new [`Rectangle`](../rectangle) from two points specified. Two verticles of the created [`Rectangle`](../rectangle) will be equal to the passed *point1* and *point2*. These would be typically the opposite vertices. |
| static [Inflate](../../aspose.imaging/rectanglef/inflate)(RectangleF, float, float) | Creates and returns an inflated copy of the specified [`RectangleF`](../rectanglef) structure. The copy is inflated by the specified amount. The original rectangle remains unmodified. |
| static [Intersect](../../aspose.imaging/rectanglef/intersect)(RectangleF, RectangleF) | Returns a [`RectangleF`](../rectanglef) structure that represents the intersection of two rectangles. If there is no intersection, and empty [`RectangleF`](../rectanglef) is returned. |
| static [Union](../../aspose.imaging/rectanglef/union)(RectangleF, RectangleF) | Creates the smallest possible third rectangle that can contain both of two rectangles that form a union. |
| [Contains](../../aspose.imaging/rectanglef/contains)(PointF) | Determines if the specified point is contained within this [`RectangleF`](../rectanglef) structure. |
| [Contains](../../aspose.imaging/rectanglef/contains)(RectangleF) | Determines if the rectangular region represented by *rect* is entirely contained within this [`RectangleF`](../rectanglef) structure. |
| [Contains](../../aspose.imaging/rectanglef/contains)(float, float) | Determines if the specified point is contained within this [`RectangleF`](../rectanglef) structure. |
| override [Equals](../../aspose.imaging/rectanglef/equals)(object) | Tests whether *obj* is a [`RectangleF`](../rectanglef) with the same location and size of this [`RectangleF`](../rectanglef). |
| override [GetHashCode](../../aspose.imaging/rectanglef/gethashcode)() | Gets the hash code for this [`RectangleF`](../rectanglef) structure. |
| [Inflate](../../aspose.imaging/rectanglef/inflate)(SizeF) | Inflates this [`RectangleF`](../rectanglef) by the specified amount. |
| [Inflate](../../aspose.imaging/rectanglef/inflate)(float, float) | Inflates this [`RectangleF`](../rectanglef) structure by the specified amount. |
| [Intersect](../../aspose.imaging/rectanglef/intersect)(RectangleF) | Replaces this [`RectangleF`](../rectanglef) structure with the intersection of itself and the specified [`RectangleF`](../rectanglef) structure. |
| [IntersectsWith](../../aspose.imaging/rectanglef/intersectswith)(RectangleF) | Determines if this rectangle intersects with *rect*. |
| [Normalize](../../aspose.imaging/rectanglef/normalize)() | Normalizes the rectangle by making it's width and height positive, left less than right and top less than bottom. |
| [Offset](../../aspose.imaging/rectanglef/offset)(PointF) | Adjusts the location of this rectangle by the specified amount. |
| [Offset](../../aspose.imaging/rectanglef/offset)(float, float) | Adjusts the location of this rectangle by the specified amount. |
| override [ToString](../../aspose.imaging/rectanglef/tostring)() | Converts the attributes of this [`RectangleF`](../rectanglef) to a human-readable string. |
| [operator /](../../aspose.imaging/rectanglef/op_division) | Implements the operator /. |
| [operator ==](../../aspose.imaging/rectanglef/op_equality) | Tests whether two [`RectangleF`](../rectanglef) structures have equal location and size. |
| [implicit operator](../../aspose.imaging/rectanglef/op_implicit) | Converts the specified [`Rectangle`](../rectangle) structure to a [`RectangleF`](../rectanglef) structure. |
| [operator !=](../../aspose.imaging/rectanglef/op_inequality) | Tests whether two [`RectangleF`](../rectanglef) structures differ in location or size. |
| [operator *](../../aspose.imaging/rectanglef/op_multiply) | Implements the operator *. |

### See Also

* namespace [Aspose.Imaging](../../aspose.imaging)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
