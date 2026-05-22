---
title: "Graphics.DrawBeziers"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Graphics 方法。从 Point 结构数组绘制一系列 Bézier 样条曲线"
type: docs
weight: 190
url: /zh/net/aspose.imaging/graphics/drawbeziers/
---
## DrawBeziers(Pen, Point[]) {#drawbeziers_1}

从 [`Point`](../../point/) 结构数组绘制一系列 Bézier 样条曲线。

```csharp
public void DrawBeziers(Pen pen, Point[] points)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 用于确定曲线的颜色、宽度和样式。 |
| points | Point[] | 由 [`Point`](../../point/) 结构组成的数组，表示决定曲线的点。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。-or- *points* 为 null。 |

### 另请参见

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawBeziers(Pen, PointF[]) {#drawbeziers}

从 [`PointF`](../../pointf/) 结构数组绘制一系列 Bézier 样条曲线。

```csharp
public void DrawBeziers(Pen pen, PointF[] points)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 用于确定曲线的颜色、宽度和样式。 |
| points | PointF[] | 由 [`PointF`](../../pointf/) 结构组成的数组，表示决定曲线的点。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。-or- *points* 为 null。 |

### 另请参见

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)


