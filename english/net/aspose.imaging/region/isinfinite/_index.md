---
title: Region.IsInfinite
second_title: Aspose.Imaging for .NET API Reference
description: Region method. Tests whether this Region has an infinite interior on the specified drawing surface
type: docs
weight: 90
url: /net/aspose.imaging/region/isinfinite/
---
## Region.IsInfinite method

Tests whether this [`Region`](../) has an infinite interior on the specified drawing surface.

```csharp
public bool IsInfinite(Graphics g)
```

| Parameter | Type | Description |
| --- | --- | --- |
| g | Graphics | A [`Graphics`](../../graphics/) that represents a drawing surface. |

### Return Value

true if the interior of this [`Region`](../) is infinite when the transformation associated with *g* is applied; otherwise, false.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *g* is null. |

### See Also

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)


