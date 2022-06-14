---
title: RectangleF
second_title: Aspose.Imaging for .NET API 参考
description: 存储一组四个浮点数表示矩形的位置和大小
type: docs
weight: 10850
url: /zh/net/aspose.imaging/rectanglef/
---
## RectangleF structure

存储一组四个浮点数，表示矩形的位置和大小。

```csharp
public struct RectangleF
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [RectangleF](rectanglef#constructor)(PointF, SizeF) | 用指定的位置和大小初始化[`RectangleF`](../rectanglef)结构的新实例。 |
| [RectangleF](rectanglef#constructor_1)(float, float, float, float) | 用指定的位置和大小初始化[`RectangleF`](../rectanglef)结构的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| static [Empty](../../aspose.imaging/rectanglef/empty) { get; } | 获取[`RectangleF`](../rectanglef)结构的新实例，该结构具有X,[`Y`](./y),[`Width`](./width)和[`Height`](./height)值设置为零。 |
| [Bottom](../../aspose.imaging/rectanglef/bottom) { get; set; } | 获取或设置 y 坐标，它是[`Y`](./y)和:::R5 之和:P:Aspose.Imaging.RectangleF.Height:::这个[`RectangleF`](../rectanglef)结构。 |
| [Height](../../aspose.imaging/rectanglef/height) { get; set; } | 获取或设置此[`RectangleF`](../rectanglef)结构的高度。 |
| [IsEmpty](../../aspose.imaging/rectanglef/isempty) { get; } | 获取一个值，该值指示[`Width`](./width)还是Imaging。此R5:T:Aspose.Imaging.RectangleF:::的 RectangleF.Height:::属性的值为零。 |
| [Left](../../aspose.imaging/rectanglef/left) { get; set; } | 获取或设置此[`RectangleF`](../rectanglef)结构左边缘的 x 坐标。 |
| [Location](../../aspose.imaging/rectanglef/location) { get; set; } | 获取或设置此[`RectangleF`](../rectanglef)结构的左上角坐标。 |
| [Right](../../aspose.imaging/rectanglef/right) { get; set; } | 获取或设置 x 坐标，即[`X`](./x)和:::R5 之和:P:Aspose.Imaging.RectangleF.Width:::这个[`RectangleF`](../rectanglef)结构。 |
| [Size](../../aspose.imaging/rectanglef/size) { get; set; } | 获取或设置此[`RectangleF`](../rectanglef)的大小。 |
| [Top](../../aspose.imaging/rectanglef/top) { get; set; } | 获取或设置此[`RectangleF`](../rectanglef)结构上边缘的 y 坐标。 |
| [Width](../../aspose.imaging/rectanglef/width) { get; set; } | 获取或设置此[`RectangleF`](../rectanglef)结构的宽度。 |
| [X](../../aspose.imaging/rectanglef/x) { get; set; } | 获取或设置此[`RectangleF`](../rectanglef)结构左上角的 x 坐标。 |
| [Y](../../aspose.imaging/rectanglef/y) { get; set; } | 获取或设置此[`RectangleF`](../rectanglef)结构左上角的 y 坐标。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.imaging/rectanglef/fromlefttoprightbottom)(float, float, float, float) | 在指定位置创建具有左上角和右下角的[`RectangleF`](../rectanglef)结构。 |
| static [FromPoints](../../aspose.imaging/rectanglef/frompoints)(PointF, PointF) | 从指定的两个点创建一个新的[`Rectangle`](../rectangle)。创建的[`Rectangle`](../rectangle)的两个顶点将等于传递的*point1*和*point2*。这些通常是相反的顶点。 |
| static [Inflate](../../aspose.imaging/rectanglef/inflate)(RectangleF, float, float) | 创建并返回指定[`RectangleF`](../rectanglef)结构的膨胀副本。副本按指定的数量膨胀。原始矩形保持不变。 |
| static [Intersect](../../aspose.imaging/rectanglef/intersect)(RectangleF, RectangleF) | 返回一个[`RectangleF`](../rectanglef)结构，表示两个矩形的交集。如果没有交集，则返回空[`RectangleF`](../rectanglef)。 |
| static [Union](../../aspose.imaging/rectanglef/union)(RectangleF, RectangleF) | 创建最小的第三个矩形，该矩形可以包含形成联合的两个矩形。 |
| [Contains](../../aspose.imaging/rectanglef/contains#contains)(PointF) | 确定指定点是否包含在此[`RectangleF`](../rectanglef)结构中。 |
| [Contains](../../aspose.imaging/rectanglef/contains#contains_1)(RectangleF) | 确定*rect*表示的矩形区域是否完全包含在此:::R5:T:Aspose.Imaging.RectangleF::中:结构体。 |
| [Contains](../../aspose.imaging/rectanglef/contains#contains_2)(float, float) | 确定指定点是否包含在此[`RectangleF`](../rectanglef)结构中。 |
| override [Equals](../../aspose.imaging/rectanglef/equals)(object) | 测试*obj*是否是具有相同位置和大小的[`RectangleF`](../rectanglef)这[`RectangleF`](../rectanglef)。 |
| override [GetHashCode](../../aspose.imaging/rectanglef/gethashcode)() | 获取此[`RectangleF`](../rectanglef)结构的哈希码。 |
| [Inflate](../../aspose.imaging/rectanglef/inflate#inflate)(SizeF) | 将这个[`RectangleF`](../rectanglef)膨胀指定的量。 |
| [Inflate](../../aspose.imaging/rectanglef/inflate#inflate_1)(float, float) | 将这个[`RectangleF`](../rectanglef)结构膨胀指定的量。 |
| [Intersect](../../aspose.imaging/rectanglef/intersect)(RectangleF) | 将此[`RectangleF`](../rectanglef)结构替换为自身与指定RectangleF结构。 |
| [IntersectsWith](../../aspose.imaging/rectanglef/intersectswith)(RectangleF) | 确定此矩形是否与*rect*相交。 |
| [Normalize](../../aspose.imaging/rectanglef/normalize)() | 通过使矩形的宽度和高度为正值、left 小于 right 并且 top 小于 bottom 来规范化矩形。 |
| [Offset](../../aspose.imaging/rectanglef/offset#offset)(PointF) | 按指定量调整此矩形的位置。 |
| [Offset](../../aspose.imaging/rectanglef/offset#offset_1)(float, float) | 按指定量调整此矩形的位置。 |
| override [ToString](../../aspose.imaging/rectanglef/tostring)() | 将此[`RectangleF`](../rectanglef)的属性转换为人类可读的字符串。 |
| [operator /](../../aspose.imaging/rectanglef/op_division) | 实现运算符 /。 |
| [operator ==](../../aspose.imaging/rectanglef/op_equality) | 测试两个[`RectangleF`](../rectanglef)结构是否具有相同的位置和大小。 |
| [implicit operator](../../aspose.imaging/rectanglef/op_implicit) | 将指定的[`Rectangle`](../rectangle)结构转换为[`RectangleF`](../rectanglef)结构体。 |
| [operator !=](../../aspose.imaging/rectanglef/op_inequality) | 测试两个[`RectangleF`](../rectanglef)结构的位置或大小是否不同。 |
| [operator *](../../aspose.imaging/rectanglef/op_multiply) | 实现运算符 *。 |

### 也可以看看

* 命名空间 [Aspose.Imaging](../../aspose.imaging)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
