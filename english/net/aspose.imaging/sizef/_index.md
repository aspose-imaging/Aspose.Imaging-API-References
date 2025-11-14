---
title: Struct SizeF
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.SizeF struct. Stores an ordered pair of floatingpoint numbers typically the width and height of a rectangle
type: docs
weight: 11570
url: /net/aspose.imaging/sizef/
---
## SizeF structure

Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

```csharp
public struct SizeF
```

## Constructors

| Name | Description |
| --- | --- |
| [SizeF](sizef/#constructor)(PointF) | Initializes a new instance of the `SizeF` structure from the specified [`PointF`](../pointf/). |
| [SizeF](sizef/#constructor_1)(SizeF) | Initializes a new instance of the `SizeF` structure from the specified `SizeF`. |
| [SizeF](sizef/#constructor_2)(float, float) | Initializes a new instance of the `SizeF` structure from the specified dimensions. |

## Properties

| Name | Description |
| --- | --- |
| static [Empty](../../aspose.imaging/sizef/empty/) { get; } | Gets a new instance of the `SizeF` structure that has [`Width`](./width/) and [`Height`](./height/) values set to zero. |
| [Height](../../aspose.imaging/sizef/height/) { get; set; } | Gets or sets the vertical component of this `SizeF`. |
| [IsEmpty](../../aspose.imaging/sizef/isempty/) { get; } | Gets a value indicating whether this `SizeF` has zero width and height. |
| [Width](../../aspose.imaging/sizef/width/) { get; set; } | Gets or sets the horizontal component of this `SizeF`. |

## Methods

| Name | Description |
| --- | --- |
| static [Add](../../aspose.imaging/sizef/add/)(SizeF, SizeF) | Adds the width and height of one `SizeF` structure to the width and height of another `SizeF` structure. |
| static [Subtract](../../aspose.imaging/sizef/subtract/)(SizeF, SizeF) | Subtracts the width and height of one `SizeF` structure from the width and height of another `SizeF` structure. |
| override [Equals](../../aspose.imaging/sizef/equals/)(object) | Tests to see whether the specified object is a `SizeF` with the same dimensions as this `SizeF`. |
| override [GetHashCode](../../aspose.imaging/sizef/gethashcode/)() | Returns a hash code for this [`Size`](../size/) structure. |
| [ToPointF](../../aspose.imaging/sizef/topointf/)() | Converts a `SizeF` to a [`PointF`](../pointf/). |
| [ToSize](../../aspose.imaging/sizef/tosize/)() | Converts a `SizeF` to a [`Size`](../size/) structure with truncated size values. |
| override [ToString](../../aspose.imaging/sizef/tostring/)() | Creates a human-readable string that represents this `SizeF`. |
| [operator +](../../aspose.imaging/sizef/op_addition/) | Adds the width and height of one `SizeF` structure to the width and height of another `SizeF` structure. |
| [operator ==](../../aspose.imaging/sizef/op_equality/) | Tests whether two `SizeF` structures are equal. |
| [explicit operator](../../aspose.imaging/sizef/op_explicit/) | Converts the specified `SizeF` to a [`PointF`](../pointf/). |
| [operator !=](../../aspose.imaging/sizef/op_inequality/) | Tests whether two `SizeF` structures are different. |
| [operator -](../../aspose.imaging/sizef/op_subtraction/) | Subtracts the width and height of one `SizeF` structure from the width and height of another `SizeF` structure. |

### See Also

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


