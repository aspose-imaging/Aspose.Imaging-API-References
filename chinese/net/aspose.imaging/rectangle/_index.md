---
title: "结构体 Rectangle"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Rectangle 结构体。存储一组四个整数，表示矩形的位置和大小。"
type: docs
weight: 11410
url: /zh/net/aspose.imaging/rectangle/
---
## Rectangle structure

存储四个整数，表示矩形的位置和大小。

```csharp
public struct Rectangle
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Rectangle](rectangle/#constructor)(Point, Size) | 使用指定的位置和大小初始化 `Rectangle` 结构的新实例。 |
| [Rectangle](rectangle/#constructor_1)(int, int, int, int) | 使用指定的位置和大小初始化 `Rectangle` 结构的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| static [Empty](../../aspose.imaging/rectangle/empty/) { get; } | 获取一个 `Rectangle` 结构的新实例，其 [`X`](./x/)、[`Y`](./y/)、[`Width`](./width/) 和 [`Height`](./height/) 值均设为零。 |
| [Bottom](../../aspose.imaging/rectangle/bottom/) { get; set; } | 获取或设置此 `Rectangle` 结构的 y 坐标，该坐标为 [`Y`](./y/) 和 [`Height`](./height/) 属性值之和。 |
| [Height](../../aspose.imaging/rectangle/height/) { get; set; } | 获取或设置此 `Rectangle` 结构的高度。 |
| [IsEmpty](../../aspose.imaging/rectangle/isempty/) { get; } | 获取一个值，指示此 `Rectangle` 的所有数值属性是否均为零。 |
| [Left](../../aspose.imaging/rectangle/left/) { get; set; } | 获取或设置此 `Rectangle` 结构左边缘的 x 坐标。 |
| [Location](../../aspose.imaging/rectangle/location/) { get; set; } | 获取或设置此 `Rectangle` 结构左上角的坐标。 |
| [Right](../../aspose.imaging/rectangle/right/) { get; set; } | 获取或设置此 `Rectangle` 结构的 x 坐标，该坐标为 [`X`](./x/) 和 [`Width`](./width/) 属性值之和。 |
| [Size](../../aspose.imaging/rectangle/size/) { get; set; } | 获取或设置此 `Rectangle` 的大小。 |
| [Top](../../aspose.imaging/rectangle/top/) { get; set; } | 获取或设置此 `Rectangle` 结构顶部边缘的 y 坐标。 |
| [Width](../../aspose.imaging/rectangle/width/) { get; set; } | 获取或设置此 `Rectangle` 结构的宽度。 |
| [X](../../aspose.imaging/rectangle/x/) { get; set; } | 获取或设置此 `Rectangle` 结构左上角的 x 坐标。 |
| [Y](../../aspose.imaging/rectangle/y/) { get; set; } | 获取或设置此 `Rectangle` 结构左上角的 y 坐标。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Ceiling](../../aspose.imaging/rectangle/ceiling/)(RectangleF) | 通过将指定的[`RectangleF`](../rectanglef/)值向上取整为下一个更大的整数，将其转换为 `Rectangle` 结构。 |
| static [FromLeftTopRightBottom](../../aspose.imaging/rectangle/fromlefttoprightbottom/)(int, int, int, int) | 使用指定的边缘位置创建 `Rectangle` 结构。 |
| static [FromPoints](../../aspose.imaging/rectangle/frompoints/)(Point, Point) | 根据指定的两个点创建一个新的 `Rectangle`。创建的 `Rectangle` 的两个垂直边将等于传入的 *point1* 和 *point2*，通常它们是相对的顶点。 |
| static [Inflate](../../aspose.imaging/rectangle/inflate/)(Rectangle, int, int) | 创建并返回指定 `Rectangle` 结构的膨胀副本。副本按指定的量进行膨胀，原始 `Rectangle` 结构保持不变。 |
| static [Intersect](../../aspose.imaging/rectangle/intersect/)(Rectangle, Rectangle) | 返回一个第三个 `Rectangle` 结构，表示两个其他 `Rectangle` 结构的交集。如果没有交集，则返回一个空的 `Rectangle`。 |
| static [Round](../../aspose.imaging/rectangle/round/)(RectangleF) | 通过将指定的[`RectangleF`](../rectanglef/)值四舍五入到最近的整数，将其转换为 `Rectangle`。 |
| static [Truncate](../../aspose.imaging/rectangle/truncate/)(RectangleF) | 通过截断指定的[`RectangleF`](../rectanglef/)值，将其转换为 `Rectangle`。 |
| static [Union](../../aspose.imaging/rectangle/union/)(Rectangle, Rectangle) | 获取一个包含两个 `Rectangle` 结构并集的 `Rectangle` 结构。 |
| [Contains](../../aspose.imaging/rectangle/contains/#contains)(Point) | 确定指定的点是否包含在此 `Rectangle` 结构中。 |
| [Contains](../../aspose.imaging/rectangle/contains/#contains_1)(Rectangle) | 确定由 *rect* 表示的矩形区域是否完全包含在此 `Rectangle` 结构中。 |
| [Contains](../../aspose.imaging/rectangle/contains/#contains_2)(int, int) | 确定指定的点是否包含在此 `Rectangle` 结构中。 |
| override [Equals](../../aspose.imaging/rectangle/equals/)(object) | 测试 *obj* 是否为具有与此 `Rectangle` 结构相同位置和大小的 `Rectangle` 结构。 |
| override [GetHashCode](../../aspose.imaging/rectangle/gethashcode/)() | 返回此 `Rectangle` 结构的哈希码。 |
| [Inflate](../../aspose.imaging/rectangle/inflate/#inflate)(Size) | 按指定的量扩展此 `Rectangle`。 |
| [Inflate](../../aspose.imaging/rectangle/inflate/#inflate_1)(int, int) | 按指定的量扩展此 `Rectangle`。 |
| [Intersect](../../aspose.imaging/rectangle/intersect/)(Rectangle) | 用此 `Rectangle` 与指定的 `Rectangle` 的交集替换此 `Rectangle`。 |
| [IntersectsWith](../../aspose.imaging/rectangle/intersectswith/)(Rectangle) | 确定此矩形是否与 *rect* 相交。 |
| [Normalize](../../aspose.imaging/rectangle/normalize/)() | 通过使宽度和高度为正、左侧小于右侧、顶部小于底部来规范化矩形。 |
| [Offset](../../aspose.imaging/rectangle/offset/#offset)(Point) | 按指定量调整此矩形的位置。 |
| [Offset](../../aspose.imaging/rectangle/offset/#offset_1)(int, int) | 按指定量调整此矩形的位置。 |
| override [ToString](../../aspose.imaging/rectangle/tostring/)() | 将此 `Rectangle` 的属性转换为可读的字符串。 |
| [operator ==](../../aspose.imaging/rectangle/op_equality/) | 测试两个 `Rectangle` 结构的位置和大小是否相等。 |
| [operator !=](../../aspose.imaging/rectangle/op_inequality/) | 测试两个 `Rectangle` 结构的位置或大小是否不同。 |

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


