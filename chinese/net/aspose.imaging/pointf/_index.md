---
title: "结构体 PointF"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.PointF 结构体。表示定义二维平面中点的有序浮点数 x 和 y 坐标对"
type: docs
weight: 11320
url: /zh/net/aspose.imaging/pointf/
---
## PointF structure

表示浮点数 x 和 y 坐标的有序对，定义二维平面上的一点。

```csharp
public struct PointF
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PointF](pointf/)(float, float) | 使用指定坐标初始化 `PointF` 结构的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| static [Empty](../../aspose.imaging/pointf/empty/) { get; } | 获取一个 `PointF` 结构的新实例，其 [`X`](./x/) 和 [`Y`](./y/) 值设为零。 |
| [IsEmpty](../../aspose.imaging/pointf/isempty/) { get; } | 获取一个值，指示此 `PointF` 是否为空。 |
| [X](../../aspose.imaging/pointf/x/) { get; set; } | 获取或设置此 `PointF` 的 x 坐标。 |
| [Y](../../aspose.imaging/pointf/y/) { get; set; } | 获取或设置此 `PointF` 的 y 坐标。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Add](../../aspose.imaging/pointf/add/#add)(PointF, Size) | 按指定的 [`Size`](../size/) 平移给定的 `PointF`。 |
| static [Add](../../aspose.imaging/pointf/add/#add_1)(PointF, SizeF) | 按指定的 [`SizeF`](../sizef/) 平移给定的 `PointF`。 |
| static [Subtract](../../aspose.imaging/pointf/subtract/#subtract)(PointF, Size) | 按指定尺寸的相反方向平移 `PointF`。 |
| static [Subtract](../../aspose.imaging/pointf/subtract/#subtract_1)(PointF, SizeF) | 按指定尺寸的相反方向平移 `PointF`。 |
| override [Equals](../../aspose.imaging/pointf/equals/)(object) | 指定此 `PointF` 是否包含与指定对象相同的坐标。 |
| override [GetHashCode](../../aspose.imaging/pointf/gethashcode/)() | 返回此 `PointF` 结构的哈希码。 |
| override [ToString](../../aspose.imaging/pointf/tostring/)() | 将此 `PointF` 转换为可读的字符串。 |
| [operator +](../../aspose.imaging/pointf/op_addition/#op_addition) | 按给定的 [`Size`](../size/) 平移 `PointF`。（2 个运算符） |
| [operator ==](../../aspose.imaging/pointf/op_equality/) | 比较两个 `PointF` 结构。结果指定两个 `PointF` 结构的 [`X`](./x/) 和 [`Y`](./y/) 属性值是否相等。 |
| [operator !=](../../aspose.imaging/pointf/op_inequality/) | 确定指定点的坐标是否不相等。 |
| [operator -](../../aspose.imaging/pointf/op_subtraction/#op_subtraction) | 通过给定的[`Size`](../size/)的负值平移 `PointF`。（2 个运算符） |

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


