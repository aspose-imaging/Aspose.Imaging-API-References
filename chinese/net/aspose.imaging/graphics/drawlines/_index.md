---
title: "Graphics.DrawLines"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Graphics 方法。绘制一系列线段，将一个 Point 结构数组连接起来"
type: docs
weight: 270
url: /zh/net/aspose.imaging/graphics/drawlines/
---
## DrawLines(Pen, Point[]) {#drawlines_1}

绘制一系列线段，将一个 [`Point`](../../point/) 结构数组连接起来。

```csharp
public void DrawLines(Pen pen, Point[] points)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 用于确定线段的颜色、宽度和样式。 |
| points | Point[] | 由 [`Point`](../../point/) 结构组成的数组，表示要连接的点。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。-or- *points* 为 null。 |
| ArgumentException | 该 *points* 数组包含少于 2 个点。 |

### 另请参见

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawLines(Pen, PointF[]) {#drawlines}

绘制一系列线段，将一个 [`PointF`](../../pointf/) 结构数组连接起来。

```csharp
public void DrawLines(Pen pen, PointF[] points)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 用于确定线段的颜色、宽度和样式。 |
| points | PointF[] | 由 [`PointF`](../../pointf/) 结构组成的数组，表示要连接的点。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。-or- *points* 为 null。 |
| ArgumentException | 该 *points* 数组包含少于 2 个点。 |

### 另请参见

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)


