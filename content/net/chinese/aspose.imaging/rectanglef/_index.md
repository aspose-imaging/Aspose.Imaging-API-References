---
title: RectangleF
second_title: Aspose.Imaging for .NET API 参考
description: 存储一组四个浮点数表示矩形的位置和大小
type: docs
weight: 10840
url: /zh/aspose.imaging/rectanglef/
---
## RectangleF structure

存储一组四个浮点数，表示矩形的位置和大小。

```csharp
public struct RectangleF
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [RectangleF](rectanglef#constructor)(PointF, SizeF) | 初始化[`RectangleF`](../rectanglef)具有指定位置和大小的结构。 |
| [RectangleF](rectanglef#constructor_1)(float, float, float, float) | 初始化[`RectangleF`](../rectanglef)具有指定位置和大小的结构。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| static [Empty](../../aspose.imaging/rectanglef/empty) { get; } | 获取一个新的实例[`RectangleF`](../rectanglef)具有的结构[`X`](./x) ,[`Y`](./y) ,[`Width`](./width)和[`Height`](./height)值设置为零。 |
| [Bottom](../../aspose.imaging/rectanglef/bottom) { get; set; } | 获取或设置 y 坐标，即[`Y`](./y)和[`Height`](./height)这个的[`RectangleF`](../rectanglef)结构. |
| [Height](../../aspose.imaging/rectanglef/height) { get; set; } | 获取或设置 this 的高度[`RectangleF`](../rectanglef)结构. |
| [IsEmpty](../../aspose.imaging/rectanglef/isempty) { get; } | 获取一个值，该值指示是否[`Width`](./width)或者[`Height`](./height)这个属性[`RectangleF`](../rectanglef)值为零。 |
| [Left](../../aspose.imaging/rectanglef/left) { get; set; } | 获取或设置 this 的左边缘的 x 坐标[`RectangleF`](../rectanglef)结构. |
| [Location](../../aspose.imaging/rectanglef/location) { get; set; } | 获取或设置this的左上角坐标[`RectangleF`](../rectanglef)结构. |
| [Right](../../aspose.imaging/rectanglef/right) { get; set; } | 获取或设置 x 坐标，它是[`X`](./x)和[`Width`](./width)这个的[`RectangleF`](../rectanglef)结构. |
| [Size](../../aspose.imaging/rectanglef/size) { get; set; } | 获取或设置 this 的大小[`RectangleF`](../rectanglef) . |
| [Top](../../aspose.imaging/rectanglef/top) { get; set; } | 获取或设置此顶部边缘的 y 坐标[`RectangleF`](../rectanglef)结构. |
| [Width](../../aspose.imaging/rectanglef/width) { get; set; } | 获取或设置 this 的宽度[`RectangleF`](../rectanglef)结构. |
| [X](../../aspose.imaging/rectanglef/x) { get; set; } | 获取或设置此对象左上角的x坐标[`RectangleF`](../rectanglef)结构. |
| [Y](../../aspose.imaging/rectanglef/y) { get; set; } | 获取或设置这个左上角的y坐标[`RectangleF`](../rectanglef)结构. |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.imaging/rectanglef/fromlefttoprightbottom)(float, float, float, float) | 创建一个[`RectangleF`](../rectanglef)在指定位置具有左上角和右下角的结构。 |
| static [FromPoints](../../aspose.imaging/rectanglef/frompoints)(PointF, PointF) | 创建一个新的[`Rectangle`](../rectangle)从指定的两点。创建的两个verticle[`Rectangle`](../rectangle)将等于通过*point1*和*point2*.这些通常是相反的顶点。 |
| static [Inflate](../../aspose.imaging/rectanglef/inflate)(RectangleF, float, float) | 创建并返回指定的膨胀副本[`RectangleF`](../rectanglef)结构体。副本按指定的数量膨胀。原始矩形保持不变。 |
| static [Intersect](../../aspose.imaging/rectanglef/intersect)(RectangleF, RectangleF) | 返回一个[`RectangleF`](../rectanglef)表示两个矩形相交的结构。如果没有交集，并且为空[`RectangleF`](../rectanglef)被退回。 |
| static [Union](../../aspose.imaging/rectanglef/union)(RectangleF, RectangleF) | 创建最小的第三个矩形，该矩形可以包含形成联合的两个矩形。 |
| [Contains](../../aspose.imaging/rectanglef/contains#contains)(PointF) | 确定指定点是否包含在此范围内[`RectangleF`](../rectanglef)结构. |
| [Contains](../../aspose.imaging/rectanglef/contains#contains_1)(RectangleF) | 确定矩形区域是否由*rect*完全包含在这个[`RectangleF`](../rectanglef)结构. |
| [Contains](../../aspose.imaging/rectanglef/contains#contains_2)(float, float) | 确定指定点是否包含在此范围内[`RectangleF`](../rectanglef)结构. |
| override [Equals](../../aspose.imaging/rectanglef/equals)(object) | 测试是否*obj*是一个[`RectangleF`](../rectanglef)与此相同的位置和大小[`RectangleF`](../rectanglef) . |
| override [GetHashCode](../../aspose.imaging/rectanglef/gethashcode)() | 获取此哈希码[`RectangleF`](../rectanglef)结构. |
| [Inflate](../../aspose.imaging/rectanglef/inflate#inflate)(SizeF) | 膨胀这个[`RectangleF`](../rectanglef)按指定数量。 |
| [Inflate](../../aspose.imaging/rectanglef/inflate#inflate_1)(float, float) | 膨胀这个[`RectangleF`](../rectanglef)指定数量的结构。 |
| [Intersect](../../aspose.imaging/rectanglef/intersect)(RectangleF) | 替换这个[`RectangleF`](../rectanglef)具有自身和指定的交集的结构[`RectangleF`](../rectanglef)结构. |
| [IntersectsWith](../../aspose.imaging/rectanglef/intersectswith)(RectangleF) | 确定此矩形是否与*rect* . |
| [Normalize](../../aspose.imaging/rectanglef/normalize)() | 通过使矩形的宽度和高度为正值、left 小于 right 和 top 小于 bottom 来规范化矩形。 |
| [Offset](../../aspose.imaging/rectanglef/offset#offset)(PointF) | 按指定量调整此矩形的位置。 |
| [Offset](../../aspose.imaging/rectanglef/offset#offset_1)(float, float) | 按指定量调整此矩形的位置。 |
| override [ToString](../../aspose.imaging/rectanglef/tostring)() | 转换 this 的属性[`RectangleF`](../rectanglef)到一个人类可读的字符串。 |
| [operator /](../../aspose.imaging/rectanglef/op_division) | 实现运算符 /. |
| [operator ==](../../aspose.imaging/rectanglef/op_equality) | 测试是否两个[`RectangleF`](../rectanglef)结构具有相同的位置和大小。 |
| [implicit operator](../../aspose.imaging/rectanglef/op_implicit) | 转换指定的[`Rectangle`](../rectangle)结构为[`RectangleF`](../rectanglef)结构. |
| [operator !=](../../aspose.imaging/rectanglef/op_inequality) | 测试是否两个[`RectangleF`](../rectanglef)结构的位置或大小不同。 |
| [operator *](../../aspose.imaging/rectanglef/op_multiply) | 实现运算符 *. |

### 也可以看看

* 命名空间 [Aspose.Imaging](../../aspose.imaging)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
