---
title: "结构体 RectangleF"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.RectangleF 结构体。存储一组四个浮点数，表示矩形的位置和大小。"
type: docs
weight: 11420
url: /zh/net/aspose.imaging/rectanglef/
---
## RectangleF structure

存储四个浮点数，表示矩形的位置和大小。

```csharp
public struct RectangleF
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | 使用指定的位置和大小初始化 `RectangleF` 结构的新实例。 |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | 使用指定的位置和大小初始化 `RectangleF` 结构的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| static [Empty](../../aspose.imaging/rectanglef/empty/) { get; } | 获取一个新的 `RectangleF` 结构实例，其 [`X`](./x/)、[`Y`](./y/)、[`Width`](./width/) 和 [`Height`](./height/) 值均设为零。 |
| [Bottom](../../aspose.imaging/rectanglef/bottom/) { get; set; } | 获取或设置此 `RectangleF` 结构的 y 坐标，该坐标为 [`Y`](./y/) 与 [`Height`](./height/) 的和。 |
| [Height](../../aspose.imaging/rectanglef/height/) { get; set; } | 获取或设置此 `RectangleF` 结构的高度。 |
| [IsEmpty](../../aspose.imaging/rectanglef/isempty/) { get; } | 获取一个值，指示此 `RectangleF` 的 [`Width`](./width/) 或 [`Height`](./height/) 属性是否为零。 |
| [Left](../../aspose.imaging/rectanglef/left/) { get; set; } | 获取或设置此 `RectangleF` 结构左边缘的 x 坐标。 |
| [Location](../../aspose.imaging/rectanglef/location/) { get; set; } | 获取或设置此 `RectangleF` 结构左上角的坐标。 |
| [Right](../../aspose.imaging/rectanglef/right/) { get; set; } | 获取或设置此 `RectangleF` 结构的 x 坐标，该坐标为 [`X`](./x/) 与 [`Width`](./width/) 的和。 |
| [Size](../../aspose.imaging/rectanglef/size/) { get; set; } | 获取或设置此 `RectangleF` 的大小。 |
| [Top](../../aspose.imaging/rectanglef/top/) { get; set; } | 获取或设置此 `RectangleF` 结构顶部边缘的 y 坐标。 |
| [Width](../../aspose.imaging/rectanglef/width/) { get; set; } | 获取或设置此 `RectangleF` 结构的宽度。 |
| [X](../../aspose.imaging/rectanglef/x/) { get; set; } | 获取或设置此 `RectangleF` 结构左上角的 x 坐标。 |
| [Y](../../aspose.imaging/rectanglef/y/) { get; set; } | 获取或设置此 `RectangleF` 结构左上角的 y 坐标。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.imaging/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | 在指定位置创建一个 `RectangleF` 结构，其左上角和右下角位于指定位置。 |
| static [FromPoints](../../aspose.imaging/rectanglef/frompoints/)(PointF, PointF) | 从两个指定点创建一个新的 [`Rectangle`](../rectangle/)。创建的 [`Rectangle`](../rectangle/) 的两个顶点将等于传入的 *point1* 和 *point2*。这些通常是相对的顶点。 |
| static [Inflate](../../aspose.imaging/rectanglef/inflate/)(RectangleF, float, float) | 创建并返回指定 `RectangleF` 结构的膨胀副本。该副本按指定量进行膨胀。原始矩形保持不变。 |
| static [Intersect](../../aspose.imaging/rectanglef/intersect/)(RectangleF, RectangleF) | 返回一个表示两个矩形交集的 `RectangleF` 结构。如果没有交集，则返回一个空的 `RectangleF`。 |
| static [Union](../../aspose.imaging/rectanglef/union/)(RectangleF, RectangleF) | 创建能够容纳这两个矩形并形成并集的最小可能的第三个矩形。 |
| [Contains](../../aspose.imaging/rectanglef/contains/#contains)(PointF) | 确定指定的点是否包含在此 `RectangleF` 结构中。 |
| [Contains](../../aspose.imaging/rectanglef/contains/#contains_1)(RectangleF) | 确定由 *rect* 表示的矩形区域是否完全包含在此 `RectangleF` 结构中。 |
| [Contains](../../aspose.imaging/rectanglef/contains/#contains_2)(float, float) | 确定指定的点是否包含在此 `RectangleF` 结构中。 |
| override [Equals](../../aspose.imaging/rectanglef/equals/)(object) | 测试 *obj* 是否为具有与此 `RectangleF` 相同位置和大小的 `RectangleF`。 |
| override [GetHashCode](../../aspose.imaging/rectanglef/gethashcode/)() | 获取此 `RectangleF` 结构的哈希码。 |
| [Inflate](../../aspose.imaging/rectanglef/inflate/#inflate)(SizeF) | 按指定量膨胀此 `RectangleF`。 |
| [Inflate](../../aspose.imaging/rectanglef/inflate/#inflate_1)(float, float) | 按指定量膨胀此 `RectangleF` 结构。 |
| [Intersect](../../aspose.imaging/rectanglef/intersect/)(RectangleF) | 用此 `RectangleF` 与指定 `RectangleF` 结构的交集替换此 `RectangleF` 结构。 |
| [IntersectsWith](../../aspose.imaging/rectanglef/intersectswith/)(RectangleF) | 确定此矩形是否与 *rect* 相交。 |
| [Normalize](../../aspose.imaging/rectanglef/normalize/)() | 通过使宽度和高度为正、左侧小于右侧、顶部小于底部来规范化矩形。 |
| [Offset](../../aspose.imaging/rectanglef/offset/#offset)(PointF) | 按指定量调整此矩形的位置。 |
| [Offset](../../aspose.imaging/rectanglef/offset/#offset_1)(float, float) | 按指定量调整此矩形的位置。 |
| override [ToString](../../aspose.imaging/rectanglef/tostring/)() | 将此 `RectangleF` 的属性转换为人类可读的字符串。 |
| [operator /](../../aspose.imaging/rectanglef/op_division/) | 实现运算符 /。 |
| [operator ==](../../aspose.imaging/rectanglef/op_equality/) | 测试两个 `RectangleF` 结构的位置信息和大小是否相等。 |
| [implicit operator](../../aspose.imaging/rectanglef/op_implicit/) | 将指定的 [`Rectangle`](../rectangle/) 结构转换为 `RectangleF` 结构。 |
| [operator !=](../../aspose.imaging/rectanglef/op_inequality/) | 测试两个 `RectangleF` 结构在位置或大小上是否不同。 |
| [operator *](../../aspose.imaging/rectanglef/op_multiply/) | 实现运算符 *。 |

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


