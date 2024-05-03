---
title: Class Blend
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.Blend class. Defines a blend pattern. This class cannot be inherited
type: docs
weight: 120
url: /net/aspose.imaging/blend/
---
## Blend class

Defines a blend pattern. This class cannot be inherited.

```csharp
public sealed class Blend
```

## Constructors

| Name | Description |
| --- | --- |
| [Blend](blend/#constructor)() | Initializes a new instance of the `Blend` class. The number of elements in the factor and blend arrays will be equal to 1. |
| [Blend](blend/#constructor_1)(int) | Initializes a new instance of the `Blend` class with the specified number of factors and positions. |

## Properties

| Name | Description |
| --- | --- |
| [Factors](../../aspose.imaging/blend/factors/) { get; set; } | Gets or sets the array of blend factors for the gradient. |
| [Positions](../../aspose.imaging/blend/positions/) { get; set; } | Gets or sets the array of blend positions for the gradient. |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.imaging/blend/equals/)(object) | Tests whether the specified object is a `Blend` class and is equivalent to this `Blend` class. |
| override [GetHashCode](../../aspose.imaging/blend/gethashcode/)() | Returns a hash code for this instance. |

## Remarks

The typical blend class usage is defining a blend pattern for brush. And thus the blend properties should be initialized carefully. Null arrays are not allowed. The brush will throw the appropriate exception if blend factors or positions array are empty or their length is not the same. If there are two or more elements in the positions array then the first element should be 0 and the last should be 1.

### See Also

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


