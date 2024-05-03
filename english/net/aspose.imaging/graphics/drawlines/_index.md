---
title: Graphics.DrawLines
second_title: Aspose.Imaging for .NET API Reference
description: Graphics method. Draws a series of line segments that connect an array of Point structures
type: docs
weight: 270
url: /net/aspose.imaging/graphics/drawlines/
---
## DrawLines(Pen, Point[]) {#drawlines_1}

Draws a series of line segments that connect an array of [`Point`](../../point/) structures.

```csharp
public void DrawLines(Pen pen, Point[] points)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) that determines the color, width, and style of the line segments. |
| points | Point[] | Array of [`Point`](../../point/) structures that represent the points to connect. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* is null. -or- *points* is null. |
| ArgumentException | The *points* array contains less than 2 points. |

### See Also

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawLines(Pen, PointF[]) {#drawlines}

Draws a series of line segments that connect an array of [`PointF`](../../pointf/) structures.

```csharp
public void DrawLines(Pen pen, PointF[] points)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) that determines the color, width, and style of the line segments. |
| points | PointF[] | Array of [`PointF`](../../pointf/) structures that represent the points to connect. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* is null. -or- *points* is null. |
| ArgumentException | The *points* array contains less than 2 points. |

### See Also

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)


