---
title: "结构体大小"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Size struct. 表示尺寸"
type: docs
weight: 11630
url: /zh/net/aspose.imaging/size/
---
## Size structure

表示尺寸。

```csharp
public struct Size
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Size](size/#constructor)(Point) | 从指定的 [`Point`](../point/) 初始化 `Size` 结构的新实例。 |
| [Size](size/#constructor_1)(int, int) | 从指定的尺寸初始化 `Size` 结构的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| static [Empty](../../aspose.imaging/size/empty/) { get; } | 获取一个 `Size` 结构的新实例，其 [`Width`](./width/) 和 [`Height`](./height/) 值设为零。 |
| [Height](../../aspose.imaging/size/height/) { get; set; } | 获取或设置此 `Size` 的垂直分量。 |
| [IsEmpty](../../aspose.imaging/size/isempty/) { get; } | 获取一个值，指示此 `Size` 的宽度和高度是否为 0。 |
| [Width](../../aspose.imaging/size/width/) { get; set; } | 获取或设置此 `Size` 的水平分量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Add](../../aspose.imaging/size/add/)(Size, Size) | 将一个 `Size` 结构的宽度和高度加到另一个 `Size` 结构的宽度和高度上。 |
| static [Ceiling](../../aspose.imaging/size/ceiling/)(SizeF) | 通过将指定的 [`SizeF`](../sizef/) 结构的值向上取整为下一个更大的整数，将其转换为 `Size` 结构。 |
| static [Round](../../aspose.imaging/size/round/)(SizeF) | 通过将指定的 [`SizeF`](../sizef/) 结构的值四舍五入为最近的整数，将其转换为 `Size` 结构。 |
| static [Subtract](../../aspose.imaging/size/subtract/)(Size, Size) | 从另一个 `Size` 结构的宽度和高度中减去一个 `Size` 结构的宽度和高度。 |
| static [Truncate](../../aspose.imaging/size/truncate/)(SizeF) | 通过将指定的 [`SizeF`](../sizef/) 结构的值截断为下一个更低的整数，将其转换为 `Size` 结构。 |
| override [Equals](../../aspose.imaging/size/equals/)(object) | 测试指定的对象是否为具有与此 `Size` 相同尺寸的 `Size`。 |
| override [GetHashCode](../../aspose.imaging/size/gethashcode/)() | 返回此 `Size` 结构的哈希码。 |
| override [ToString](../../aspose.imaging/size/tostring/)() | 创建一个可读的字符串来表示此 `Size`。 |
| [operator +](../../aspose.imaging/size/op_addition/) | 将一个 `Size` 结构的宽度和高度加到另一个 `Size` 结构的宽度和高度上。 |
| [operator ==](../../aspose.imaging/size/op_equality/) | 测试两个 `Size` 结构是否相等。 |
| [explicit operator](../../aspose.imaging/size/op_explicit/) | 将指定的 `Size` 转换为 [`Point`](../point/)。 |
| [implicit operator](../../aspose.imaging/size/op_implicit/) | 将指定的 `Size` 转换为 [`SizeF`](../sizef/)。 |
| [operator !=](../../aspose.imaging/size/op_inequality/) | 测试两个 `Size` 结构是否不同。 |
| [operator -](../../aspose.imaging/size/op_subtraction/) | 从另一个 `Size` 结构的宽度和高度中减去一个 `Size` 结构的宽度和高度。 |

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


