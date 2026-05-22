---
title: "Graphics.FillClosedCurve"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Graphics 方法。填充由 PointF 结构数组定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5 和 Alternate 填充模式。"
type: docs
weight: 350
url: /zh/net/aspose.imaging/graphics/fillclosedcurve/
---
## FillClosedCurve(Brush, PointF[]) {#fillclosedcurve}

填充由 [`PointF`](../../pointf/) 结构数组定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5 和 Alternate 填充模式。

```csharp
public void FillClosedCurve(Brush brush, PointF[] points)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/)，决定填充的特性。 |
| points | PointF[] | 定义样条的 [`PointF`](../../pointf/) 结构数组。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。-or- *points* 为 null。 |

### 另请参见

* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## FillClosedCurve(Brush, PointF[], FillMode) {#fillclosedcurve_1}

填充由 [`PointF`](../../pointf/) 结构数组定义的闭合基数样条曲线的内部，使用指定的填充模式。此方法使用默认张力 0.5。

```csharp
public void FillClosedCurve(Brush brush, PointF[] points, FillMode fillMode)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/)，决定填充的特性。 |
| points | PointF[] | 定义样条的 [`PointF`](../../pointf/) 结构数组。 |
| fillMode | FillMode | [`FillMode`](../../fillmode/) 枚举的成员，用于确定曲线的填充方式。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。-or- *points* 为 null。 |

### 另请参见

* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## FillClosedCurve(Brush, PointF[], FillMode, float) {#fillclosedcurve_2}

填充由 [`PointF`](../../pointf/) 结构数组定义的闭合基数样条曲线的内部，使用指定的填充模式和张力。

```csharp
public void FillClosedCurve(Brush brush, PointF[] points, FillMode fillmode, float tension)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | Brush | 一个决定填充特性的 [`Brush`](../../brush/)。 |
| points | PointF[] | 定义样条的 [`PointF`](../../pointf/) 结构数组。 |
| fillmode | FillMode | [`FillMode`](../../fillmode/) 枚举的成员，用于确定曲线的填充方式。 |
| 张力 | 单精度 | 大于或等于 0.0F 的值，用于指定曲线的张力。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。-or- *points* 为 null。 |

### 另请参见

* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## FillClosedCurve(Brush, Point[]) {#fillclosedcurve_3}

填充由 [`Point`](../../point/) 结构数组定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5 和 Alternate 填充模式。

```csharp
public void FillClosedCurve(Brush brush, Point[] points)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/)，决定填充的特性。 |
| points | Point[] | 定义样条曲线的 [`Point`](../../point/) 结构数组。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。-or- *points* 为 null。 |

### 另请参见

* class [Brush](../../brush/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## FillClosedCurve(Brush, Point[], FillMode) {#fillclosedcurve_4}

填充由 [`Point`](../../point/) 结构数组定义的闭合基数样条曲线的内部，使用指定的填充模式。此方法使用默认张力 0.5。

```csharp
public void FillClosedCurve(Brush brush, Point[] points, FillMode fillmode)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/)，决定填充的特性。 |
| points | Point[] | 定义样条曲线的 [`Point`](../../point/) 结构数组。 |
| fillmode | FillMode | [`FillMode`](../../fillmode/) 枚举的成员，用于确定曲线的填充方式。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。-or- *points* 为 null。 |

### 另请参见

* class [Brush](../../brush/)
* struct [Point](../../point/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## FillClosedCurve(Brush, Point[], FillMode, float) {#fillclosedcurve_5}

使用指定的填充模式和张力，填充由一组 [`Point`](../../point/) 结构定义的闭合基数样条曲线的内部。

```csharp
public void FillClosedCurve(Brush brush, Point[] points, FillMode fillmode, float tension)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/)，决定填充的特性。 |
| points | Point[] | 定义样条曲线的 [`Point`](../../point/) 结构数组。 |
| fillmode | FillMode | [`FillMode`](../../fillmode/) 枚举的成员，用于确定曲线的填充方式。 |
| 张力 | 单精度 | 大于或等于 0.0F 的值，用于指定曲线的张力。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。-or- *points* 为 null。 |

### 另请参见

* class [Brush](../../brush/)
* struct [Point](../../point/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)


