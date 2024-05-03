---
title: Region.Equals
second_title: Aspose.Imaging for .NET API Reference
description: Region method. Check if objects are equal
type: docs
weight: 40
url: /net/aspose.imaging/region/equals/
---
## Equals(object) {#equals_1}

Check if objects are equal.

```csharp
public override bool Equals(object obj)
```

| Parameter | Type | Description |
| --- | --- | --- |
| obj | Object | The other object. |

### Return Value

The equality comparison result.

### See Also

* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)

---

## Equals(Region, Graphics) {#equals}

Tests whether the specified [`Region`](../) is identical to this [`Region`](../) on the specified drawing surface.

```csharp
public bool Equals(Region region, Graphics g)
```

| Parameter | Type | Description |
| --- | --- | --- |
| region | Region | The [`Region`](../) to test. |
| g | Graphics | A [`Graphics`](../../graphics/) that represents a drawing surface. |

### Return Value

True if the interior of region is identical to the interior of this region when the transformation associated with the *g* parameter is applied; otherwise, false.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *g *or* region* is null. |

### See Also

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)


