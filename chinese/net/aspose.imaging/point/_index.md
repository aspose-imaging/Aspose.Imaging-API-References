---
title: "结构体 Point"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Point 结构体。表示整数 x 和 y 坐标的有序对，定义二维平面中的点"
type: docs
weight: 11310
url: /zh/net/aspose.imaging/point/
---
## Point structure

表示整数 x 和 y 坐标的有序对，定义二维平面上的一点。

```csharp
public struct Point
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Point](point/#constructor_1)(int) | 使用整数值指定的坐标初始化 `Point` 结构的新实例。 |
| [Point](point/#constructor)(Size) | 从 [`Size`](../size/) 结构初始化 `Point` 结构的新实例。 |
| [Point](point/#constructor_2)(int, int) | 使用指定的坐标初始化 `Point` 结构的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| static [Empty](../../aspose.imaging/point/empty/) { get; } | 获取一个 `Point` 结构的新实例，其 [`X`](./x/) 和 [`Y`](./y/) 值设为零。 |
| [IsEmpty](../../aspose.imaging/point/isempty/) { get; } | 获取一个值，指示此 `Point` 是否为空。 |
| [X](../../aspose.imaging/point/x/) { get; set; } | 获取或设置此 `Point` 的 x 坐标。 |
| [Y](../../aspose.imaging/point/y/) { get; set; } | 获取或设置此 `Point` 的 y 坐标。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Add](../../aspose.imaging/point/add/)(Point, Size) | 将指定的 [`Size`](../size/) 添加到指定的 `Point`。 |
| static [Ceiling](../../aspose.imaging/point/ceiling/)(PointF) | 通过将指定的 [`PointF`](../pointf/) 的值向上取整到下一个更高的整数，将其转换为 `Point`。 |
| static [Round](../../aspose.imaging/point/round/)(PointF) | 通过将指定的 [`PointF`](../pointf/) 的值四舍五入到最近的整数，将其转换为 `Point` 对象。 |
| static [Subtract](../../aspose.imaging/point/subtract/)(Point, Size) | 返回从指定的 `Point` 中减去指定的 [`Size`](../size/) 的结果。 |
| static [Truncate](../../aspose.imaging/point/truncate/)(PointF) | 通过截断 `Point` 的值，将指定的 [`PointF`](../pointf/) 转换为 `Point`。 |
| override [Equals](../../aspose.imaging/point/equals/)(object) | 指定此 `Point` 是否包含与指定对象相同的坐标。 |
| override [GetHashCode](../../aspose.imaging/point/gethashcode/)() | 返回此 `Point` 的哈希码。 |
| [Offset](../../aspose.imaging/point/offset/#offset)(Point) | 按指定的 `Point` 平移此 `Point`。 |
| [Offset](../../aspose.imaging/point/offset/#offset_1)(int, int) | 按指定的量平移此 `Point`。 |
| [ToLong](../../aspose.imaging/point/tolong/)() | 将此 Point 转换为单个 long 值，其中高位和低位分别包含 X 和 Y 坐标。 |
| override [ToString](../../aspose.imaging/point/tostring/)() | 将此 `Point` 转换为人类可读的字符串。 |
| static [FromLong](../../aspose.imaging/point/fromlong/)(long, out int, out int) | 将打包在 long 对象中的 Point 对象解构为单独的 X 和 Y 整型值。 |
| [operator +](../../aspose.imaging/point/op_addition/) | 按给定的 [`Size`](../size/) 平移 `Point`。 |
| [operator ==](../../aspose.imaging/point/op_equality/) | 比较两个 `Point` 对象。结果指定两个 `Point` 对象的 [`X`](./x/) 和 [`Y`](./y/) 属性值是否相等。 |
| [explicit operator](../../aspose.imaging/point/op_explicit/) | 将指定的 `Point` 结构转换为 [`Size`](../size/) 结构。 |
| [implicit operator](../../aspose.imaging/point/op_implicit/) | 将指定的 `Point` 结构转换为 [`PointF`](../pointf/) 结构。 |
| [operator !=](../../aspose.imaging/point/op_inequality/) | 比较两个 `Point` 对象。结果指定两个 `Point` 对象的 [`X`](./x/) 或 [`Y`](./y/) 属性值是否不相等。 |
| [operator -](../../aspose.imaging/point/op_subtraction/) | 按给定 [`Size`](../size/) 的负值平移 `Point`。 |

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


