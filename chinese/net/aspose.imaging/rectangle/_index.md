---
title: Rectangle
second_title: Aspose.Imaging for .NET API 参考
description: 存储一组四个整数表示矩形的位置和大小
type: docs
weight: 10840
url: /zh/net/aspose.imaging/rectangle/
---
## Rectangle structure

存储一组四个整数，表示矩形的位置和大小。

```csharp
public struct Rectangle
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Rectangle](rectangle#constructor)(Point, Size) | 用指定的位置和大小初始化[`Rectangle`](../rectangle)结构的新实例。 |
| [Rectangle](rectangle#constructor_1)(int, int, int, int) | 用指定的位置和大小初始化[`Rectangle`](../rectangle)结构的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| static [Empty](../../aspose.imaging/rectangle/empty) { get; } | 获取[`Rectangle`](../rectangle)结构的新实例，该结构具有X,[`Y`](./y),[`Width`](./width)和[`Height`](./height)值设置为零。 |
| [Bottom](../../aspose.imaging/rectangle/bottom) { get; set; } | 获取或设置 y 坐标，它是[`Y`](./y)和:::R5 之和:P:Aspose.Imaging.Rectangle.Height:::这个[`Rectangle`](../rectangle)结构的属性值。 |
| [Height](../../aspose.imaging/rectangle/height) { get; set; } | 获取或设置此[`Rectangle`](../rectangle)结构的高度。 |
| [IsEmpty](../../aspose.imaging/rectangle/isempty) { get; } | 获取一个值，该值指示此[`Rectangle`](../rectangle)的所有数值属性是否具有零值。 |
| [Left](../../aspose.imaging/rectangle/left) { get; set; } | 获取或设置此[`Rectangle`](../rectangle)结构左边缘的 x 坐标。 |
| [Location](../../aspose.imaging/rectangle/location) { get; set; } | 获取或设置此[`Rectangle`](../rectangle)结构的左上角坐标。 |
| [Right](../../aspose.imaging/rectangle/right) { get; set; } | 获取或设置 x 坐标，它是[`X`](./x)和:::R5 之和:P:Aspose.Imaging.Rectangle.Width:::这个[`Rectangle`](../rectangle)结构的属性值。 |
| [Size](../../aspose.imaging/rectangle/size) { get; set; } | 获取或设置此[`Rectangle`](../rectangle)的大小。 |
| [Top](../../aspose.imaging/rectangle/top) { get; set; } | 获取或设置此[`Rectangle`](../rectangle)结构上边缘的 y 坐标。 |
| [Width](../../aspose.imaging/rectangle/width) { get; set; } | 获取或设置此[`Rectangle`](../rectangle)结构的宽度。 |
| [X](../../aspose.imaging/rectangle/x) { get; set; } | 获取或设置此[`Rectangle`](../rectangle)结构左上角的 x 坐标。 |
| [Y](../../aspose.imaging/rectangle/y) { get; set; } | 获取或设置此[`Rectangle`](../rectangle)结构左上角的 y 坐标。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [Ceiling](../../aspose.imaging/rectangle/ceiling)(RectangleF) | 将指定的[`RectangleF`](../rectanglef)结构转换为[`Rectangle`](../rectangle)通过将[`RectangleF`](../rectanglef)值四舍五入到下一个更高的整数值来构建结构。 |
| static [FromLeftTopRightBottom](../../aspose.imaging/rectangle/fromlefttoprightbottom)(int, int, int, int) | 创建具有指定边缘位置的[`Rectangle`](../rectangle)结构。 |
| static [FromPoints](../../aspose.imaging/rectangle/frompoints)(Point, Point) | 从指定的两个点创建一个新的[`Rectangle`](../rectangle)。创建的[`Rectangle`](../rectangle)的两个垂直将等于传递的*point1*和*point2*。这些通常是相反的顶点。 |
| static [Inflate](../../aspose.imaging/rectangle/inflate)(Rectangle, int, int) | 创建并返回指定[`Rectangle`](../rectangle)结构的膨胀副本。副本按指定的数量膨胀。原始[`Rectangle`](../rectangle)结构保持不变。 |
| static [Intersect](../../aspose.imaging/rectangle/intersect)(Rectangle, Rectangle) | 返回第三个[`Rectangle`](../rectangle)结构，表示两个其他Rectangle结构。如果没有交集，则返回一个空的[`Rectangle`](../rectangle)。 |
| static [Round](../../aspose.imaging/rectangle/round)(RectangleF) | 将指定的[`RectangleF`](../rectanglef)转换为[`Rectangle`](../rectangle)通过将[`RectangleF`](../rectanglef)值四舍五入为最接近的整数值。 |
| static [Truncate](../../aspose.imaging/rectangle/truncate)(RectangleF) | 将指定的[`RectangleF`](../rectanglef)转换为[`Rectangle`](../rectangle)通过截断[`RectangleF`](../rectanglef)值。 |
| static [Union](../../aspose.imaging/rectangle/union)(Rectangle, Rectangle) | 获取一个[`Rectangle`](../rectangle)结构，该结构包含两个Imaging的联合。矩形结构。 |
| [Contains](../../aspose.imaging/rectangle/contains#contains)(Point) | 确定指定点是否包含在此[`Rectangle`](../rectangle)结构中。 |
| [Contains](../../aspose.imaging/rectangle/contains#contains_1)(Rectangle) | 确定*rect*表示的矩形区域是否完全包含在此:::R5:T:Aspose.Imaging.Rectangle::中:结构体。 |
| [Contains](../../aspose.imaging/rectangle/contains#contains_2)(int, int) | 确定指定点是否包含在此[`Rectangle`](../rectangle)结构中。 |
| override [Equals](../../aspose.imaging/rectangle/equals)(object) | 测试*obj*是否是具有相同位置和大小的[`Rectangle`](../rectangle)结构这个[`Rectangle`](../rectangle)结构。 |
| override [GetHashCode](../../aspose.imaging/rectangle/gethashcode)() | 返回此[`Rectangle`](../rectangle)结构的哈希码。 |
| [Inflate](../../aspose.imaging/rectangle/inflate#inflate)(Size) | 将这个[`Rectangle`](../rectangle)膨胀指定的量。 |
| [Inflate](../../aspose.imaging/rectangle/inflate#inflate_1)(int, int) | 将这个[`Rectangle`](../rectangle)膨胀指定的量。 |
| [Intersect](../../aspose.imaging/rectangle/intersect)(Rectangle) | 将此[`Rectangle`](../rectangle)替换为自身与指定Imaging的交集。长方形。 |
| [IntersectsWith](../../aspose.imaging/rectangle/intersectswith)(Rectangle) | 确定此矩形是否与*rect*相交。 |
| [Normalize](../../aspose.imaging/rectangle/normalize)() | 通过使矩形的宽度和高度为正值、left 小于 right 并且 top 小于 bottom 来规范化矩形。 |
| [Offset](../../aspose.imaging/rectangle/offset#offset)(Point) | 按指定量调整此矩形的位置。 |
| [Offset](../../aspose.imaging/rectangle/offset#offset_1)(int, int) | 按指定量调整此矩形的位置。 |
| override [ToString](../../aspose.imaging/rectangle/tostring)() | 将此[`Rectangle`](../rectangle)的属性转换为人类可读的字符串。 |
| [operator ==](../../aspose.imaging/rectangle/op_equality) | 测试两个[`Rectangle`](../rectangle)结构是否具有相同的位置和大小。 |
| [operator !=](../../aspose.imaging/rectangle/op_inequality) | 测试两个[`Rectangle`](../rectangle)结构的位置或大小是否不同。 |

### 也可以看看

* 命名空间 [Aspose.Imaging](../../aspose.imaging)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
