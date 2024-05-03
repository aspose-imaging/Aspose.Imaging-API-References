---
title: Pen.CompoundArray
second_title: Aspose.Imaging for .NET API Reference
description: Pen property. Gets or sets an array of values that specifies a compound pen. A compound pen draws a compound line made up of parallel lines and spaces
type: docs
weight: 50
url: /net/aspose.imaging/pen/compoundarray/
---
## Pen.CompoundArray property

Gets or sets an array of values that specifies a compound pen. A compound pen draws a compound line made up of parallel lines and spaces.

```csharp
public float[] CompoundArray { get; set; }
```

### Property Value

An array of real numbers that specifies the compound array. The elements in the array must be in increasing order, not less than 0, and not greater than 1.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | The `CompoundArray` property is set on an immutable [`Pen`](../), such as those returned by the [`Pen`](../) class. |

### See Also

* class [Pen](../)
* namespace [Aspose.Imaging](../../pen/)
* assembly [Aspose.Imaging](../../../)


