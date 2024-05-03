---
title: ImageAttributes.SetThreshold
second_title: Aspose.Imaging for .NET API Reference
description: ImageAttributes method. Sets the threshold transparency range for the default category
type: docs
weight: 200
url: /net/aspose.imaging/imageattributes/setthreshold/
---
## SetThreshold(float) {#setthreshold}

Sets the threshold (transparency range) for the default category.

```csharp
public void SetThreshold(float threshold)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threshold | Single | A real number that specifies the threshold value. |

### See Also

* class [ImageAttributes](../)
* namespace [Aspose.Imaging](../../imageattributes/)
* assembly [Aspose.Imaging](../../../)

---

## SetThreshold(float, ColorAdjustType) {#setthreshold_1}

Sets the threshold (transparency range) for a specified category.

```csharp
public void SetThreshold(float threshold, ColorAdjustType type)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threshold | Single | A threshold value from 0.0 to 1.0 that is used as a breakpoint to sort colors that will be mapped to either a maximum or a minimum value. |
| type | ColorAdjustType | An element of [`ColorAdjustType`](../../coloradjusttype/) that specifies the category for which the color threshold is set. |

### See Also

* enum [ColorAdjustType](../../coloradjusttype/)
* class [ImageAttributes](../)
* namespace [Aspose.Imaging](../../imageattributes/)
* assembly [Aspose.Imaging](../../../)


