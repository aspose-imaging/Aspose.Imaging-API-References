---
title: Struct Point
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.Point struct. Represents an ordered pair of integer x and ycoordinates that defines a point in a twodimensional plane
type: docs
weight: 11220
url: /net/aspose.imaging/point/
---
## Point structure

Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

```csharp
public struct Point
```

## Constructors

| Name | Description |
| --- | --- |
| [Point](point/#constructor_1)(int) | Initializes a new instance of the `Point` structure using coordinates specified by an integer value. |
| [Point](point/#constructor)(Size) | Initializes a new instance of the `Point` structure from the [`Size`](../size/) structure. |
| [Point](point/#constructor_2)(int, int) | Initializes a new instance of the `Point` structure with the specified coordinates. |

## Properties

| Name | Description |
| --- | --- |
| static [Empty](../../aspose.imaging/point/empty/) { get; } | Gets a new instance of the `Point` structure that has [`X`](./x/) and [`Y`](./y/) values set to zero. |
| [IsEmpty](../../aspose.imaging/point/isempty/) { get; } | Gets a value indicating whether this `Point` is empty. |
| [X](../../aspose.imaging/point/x/) { get; set; } | Gets or sets the x-coordinate of this `Point`. |
| [Y](../../aspose.imaging/point/y/) { get; set; } | Gets or sets the y-coordinate of this `Point`. |

## Methods

| Name | Description |
| --- | --- |
| static [Add](../../aspose.imaging/point/add/)(Point, Size) | Adds the specified [`Size`](../size/) to the specified `Point`. |
| static [Ceiling](../../aspose.imaging/point/ceiling/)(PointF) | Converts the specified [`PointF`](../pointf/) to a `Point` by rounding the values of the [`PointF`](../pointf/) to the next higher integer values. |
| static [Round](../../aspose.imaging/point/round/)(PointF) | Converts the specified [`PointF`](../pointf/) to a `Point` object by rounding the `Point` values to the nearest integer. |
| static [Subtract](../../aspose.imaging/point/subtract/)(Point, Size) | Returns the result of subtracting specified [`Size`](../size/) from the specified `Point`. |
| static [Truncate](../../aspose.imaging/point/truncate/)(PointF) | Converts the specified [`PointF`](../pointf/) to a `Point` by truncating the values of the `Point`. |
| override [Equals](../../aspose.imaging/point/equals/)(object) | Specifies whether this `Point` contains the same coordinates as the specified Object. |
| override [GetHashCode](../../aspose.imaging/point/gethashcode/)() | Returns a hash code for this `Point`. |
| [Offset](../../aspose.imaging/point/offset/#offset)(Point) | Translates this `Point` by the specified `Point`. |
| [Offset](../../aspose.imaging/point/offset/#offset_1)(int, int) | Translates this `Point` by the specified amount. |
| [ToLong](../../aspose.imaging/point/tolong/)() | Convert this Point to a single long value, containing X and Y coordinates in high and low bits. |
| override [ToString](../../aspose.imaging/point/tostring/)() | Converts this `Point` to a human-readable string. |
| static [FromLong](../../aspose.imaging/point/fromlong/)(long, out int, out int) | Deconstruct a Point object packed into a long object to separate X and Y int values. |
| [operator +](../../aspose.imaging/point/op_addition/) | Translates a `Point` by a given [`Size`](../size/). |
| [operator ==](../../aspose.imaging/point/op_equality/) | Compares two `Point` objects. The result specifies whether the values of the [`X`](./x/) and [`Y`](./y/) properties of the two `Point` objects are equal. |
| [explicit operator](../../aspose.imaging/point/op_explicit/) | Converts the specified `Point` structure to a [`Size`](../size/) structure. |
| [implicit operator](../../aspose.imaging/point/op_implicit/) | Converts the specified `Point` structure to the [`PointF`](../pointf/) structure. |
| [operator !=](../../aspose.imaging/point/op_inequality/) | Compares two `Point` objects. The result specifies whether the values of the [`X`](./x/) or [`Y`](./y/) properties of the two `Point` objects are unequal. |
| [operator -](../../aspose.imaging/point/op_subtraction/) | Translates a `Point` by the negative of a given [`Size`](../size/). |

### See Also

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


