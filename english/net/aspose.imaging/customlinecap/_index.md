---
title: Class CustomLineCap
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.CustomLineCap class. Encapsulates a custom userdefined line cap
type: docs
weight: 770
url: /net/aspose.imaging/customlinecap/
---
## CustomLineCap class

Encapsulates a custom user-defined line cap.

```csharp
public class CustomLineCap
```

## Constructors

| Name | Description |
| --- | --- |
| [CustomLineCap](customlinecap/#constructor)(GraphicsPath, GraphicsPath) | Initializes a new instance of the `CustomLineCap` class with the specified outline and fill. |
| [CustomLineCap](customlinecap/#constructor_1)(GraphicsPath, GraphicsPath, LineCap) | Initializes a new instance of the `CustomLineCap` class from the specified existing [`LineCap`](../linecap/) enumeration with the specified outline and fill. |
| [CustomLineCap](customlinecap/#constructor_2)(GraphicsPath, GraphicsPath, LineCap, float) | Initializes a new instance of the `CustomLineCap` class from the specified existing [`LineCap`](../linecap/) enumeration with the specified outline, fill, and inset. |

## Properties

| Name | Description |
| --- | --- |
| [BaseCap](../../aspose.imaging/customlinecap/basecap/) { get; set; } | Gets or sets the [`LineCap`](../linecap/) enumeration on which this `CustomLineCap` is based. |
| [BaseInset](../../aspose.imaging/customlinecap/baseinset/) { get; set; } | Gets or sets the distance between the cap and the line. |
| [FillPath](../../aspose.imaging/customlinecap/fillpath/) { get; set; } | Gets or sets the object that defines the fill for the custom cap. |
| [StrokeJoin](../../aspose.imaging/customlinecap/strokejoin/) { get; set; } | Gets or sets the [`LineJoin`](../linejoin/) enumeration that determines how lines that compose this `CustomLineCap` object are joined. |
| [StrokePath](../../aspose.imaging/customlinecap/strokepath/) { get; set; } | Gets or sets the object that defines the outline of the custom cap. |
| [WidthScale](../../aspose.imaging/customlinecap/widthscale/) { get; set; } | Gets or sets the amount by which to scale this `CustomLineCap` Class object with respect to the width of the Pen object. |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.imaging/customlinecap/equals/)(object) | Check if objects are equal. |
| override [GetHashCode](../../aspose.imaging/customlinecap/gethashcode/)() | Get hash code of the current object. |
| [GetStrokeCaps](../../aspose.imaging/customlinecap/getstrokecaps/)(out LineCap, out LineCap) | Gets the caps used to start and end lines that make up this custom cap. |
| [SetStrokeCaps](../../aspose.imaging/customlinecap/setstrokecaps/)(LineCap, LineCap) | Sets the caps used to start and end lines that make up this custom cap. |

### See Also

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


