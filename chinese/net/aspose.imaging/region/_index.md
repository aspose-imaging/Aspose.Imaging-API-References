---
title: "类 Region"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Region 类。描述由矩形和路径组成的图形形状的内部。此类不能被继承"
type: docs
weight: 11430
url: /zh/net/aspose.imaging/region/
---
## Region class

描述由矩形和路径组成的图形形状的内部。此类不可被继承。

```csharp
public sealed class Region
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Region](region/#constructor)() | 初始化一个新的 `Region`。 |
| [Region](region/#constructor_1)(GraphicsPath) | 使用指定的 [`GraphicsPath`](../graphicspath/) 初始化一个新的 `Region`。 |
| [Region](region/#constructor_2)(Rectangle) | 从指定的 [`Rectangle`](../rectangle/) 结构初始化一个新的 `Region`。 |
| [Region](region/#constructor_3)(RectangleF) | 从指定的 [`RectangleF`](../rectanglef/) 结构初始化一个新的 `Region`。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Complement](../../aspose.imaging/region/complement/#complement)(GraphicsPath) | 更新此 `Region`，使其包含指定的 [`GraphicsPath`](../graphicspath/) 中未与此 `Region` 相交的部分。 |
| [Complement](../../aspose.imaging/region/complement/#complement_1)(Rectangle) | 更新此 `Region`，使其包含指定的 [`Rectangle`](../rectangle/) 结构中未与此 `Region` 相交的部分。 |
| [Complement](../../aspose.imaging/region/complement/#complement_2)(RectangleF) | 更新此 `Region`，使其包含指定的 [`RectangleF`](../rectanglef/) 结构中未与此 `Region` 相交的部分。 |
| [Complement](../../aspose.imaging/region/complement/#complement_3)(Region) | 更新此 `Region`，使其包含指定的 `Region` 中未与此 `Region` 相交的部分。 |
| [DeepClone](../../aspose.imaging/region/deepclone/)() | 创建此 `Region` 的精确深拷贝。 |
| override [Equals](../../aspose.imaging/region/equals/#equals_1)(object) | 检查对象是否相等。 |
| [Equals](../../aspose.imaging/region/equals/#equals)(Region, Graphics) | 测试指定的 `Region` 在指定的绘图表面上是否与此 `Region` 完全相同。 |
| [Exclude](../../aspose.imaging/region/exclude/#exclude)(GraphicsPath) | 更新此 `Region`，仅保留其内部未与指定的 [`GraphicsPath`](../graphicspath/) 相交的部分。 |
| [Exclude](../../aspose.imaging/region/exclude/#exclude_1)(Rectangle) | 更新此 `Region`，仅保留其内部未与指定的 [`Rectangle`](../rectangle/) 结构相交的部分。 |
| [Exclude](../../aspose.imaging/region/exclude/#exclude_2)(RectangleF) | 更新此 `Region`，仅保留其内部未与指定的 [`RectangleF`](../rectanglef/) 结构相交的部分。 |
| [Exclude](../../aspose.imaging/region/exclude/#exclude_3)(Region) | 更新此 `Region`，仅保留其内部未与指定的 `Region` 相交的部分。 |
| override [GetHashCode](../../aspose.imaging/region/gethashcode/)() | 获取当前对象的哈希码。 |
| [Intersect](../../aspose.imaging/region/intersect/#intersect)(GraphicsPath) | 更新此 `Region`，使其与指定的 [`GraphicsPath`](../graphicspath/) 取交集。 |
| [Intersect](../../aspose.imaging/region/intersect/#intersect_1)(Rectangle) | 更新此 `Region`，使其与指定的 [`Rectangle`](../rectangle/) 结构取交集。 |
| [Intersect](../../aspose.imaging/region/intersect/#intersect_2)(RectangleF) | 更新此 `Region`，使其与指定的 [`RectangleF`](../rectanglef/) 结构取交集。 |
| [Intersect](../../aspose.imaging/region/intersect/#intersect_3)(Region) | 更新此 `Region`，使其与指定的 `Region` 取交集。 |
| [IsEmpty](../../aspose.imaging/region/isempty/)(Graphics) | 测试此 `Region` 在指定的绘图表面上是否具有空的内部。 |
| [IsInfinite](../../aspose.imaging/region/isinfinite/)(Graphics) | 测试此 `Region` 在指定的绘图表面上是否具有无限的内部。 |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible)(Point) | 测试指定的 [`Point`](../point/) 结构是否包含在此 `Region` 中。 |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_2)(PointF) | 测试指定的 [`PointF`](../pointf/) 结构是否包含在此 `Region` 中。 |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_4)(Rectangle) | 测试指定的 [`Rectangle`](../rectangle/) 结构的任何部分是否包含在此 `Region` 中。 |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_6)(RectangleF) | 测试指定的 [`RectangleF`](../rectanglef/) 结构的任何部分是否包含在此 `Region` 中。 |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_11)(float, float) | 测试指定的点是否包含在此 `Region` 中。 |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_1)(Point, Graphics) | 测试在使用指定的 [`Graphics`](../graphics/) 绘制时，指定的 [`Point`](../point/) 结构是否包含在此 `Region` 中。 |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_3)(PointF, Graphics) | 测试在使用指定的 [`Graphics`](../graphics/) 绘制时，指定的 [`PointF`](../pointf/) 结构是否包含在此 `Region` 中。 |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_5)(Rectangle, Graphics) | 测试在使用指定的 [`Graphics`](../graphics/) 绘制时，指定的 [`Rectangle`](../rectangle/) 结构的任何部分是否包含在此 `Region` 中。 |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_7)(RectangleF, Graphics) | 测试在使用指定的 [`Graphics`](../graphics/) 绘制时，指定的 [`RectangleF`](../rectanglef/) 结构的任何部分是否包含在此 `Region` 中。 |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_12)(float, float, Graphics) | 测试在使用指定的 [`Graphics`](../graphics/) 绘制时，指定的点是否包含在此 `Region` 中。 |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_8)(int, int, Graphics) | 测试在使用指定的 [`Graphics`](../graphics/) 对象绘制时，指定的点是否包含在此 `Region` 对象中。 |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_13)(float, float, float, float) | 测试指定的矩形的任何部分是否包含在此 `Region` 中。 |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_9)(int, int, int, int) | 测试指定的矩形的任何部分是否包含在此 `Region` 中。 |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_14)(float, float, float, float, Graphics) | 测试在使用指定的 [`Graphics`](../graphics/) 绘制时，指定的矩形的任何部分是否包含在此 `Region` 中。 |
| [IsVisible](../../aspose.imaging/region/isvisible/#isvisible_10)(int, int, int, int, Graphics) | 测试在使用指定的 [`Graphics`](../graphics/) 绘制时，指定的矩形的任何部分是否包含在此 `Region` 中。 |
| [MakeEmpty](../../aspose.imaging/region/makeempty/)() | 将此 `Region` 初始化为空内部。 |
| [MakeInfinite](../../aspose.imaging/region/makeinfinite/)() | 将此 `Region` 对象初始化为无限内部。 |
| [Transform](../../aspose.imaging/region/transform/)(Matrix) | 使用指定的 [`Matrix`](../matrix/) 对此 `Region` 进行变换。 |
| [Translate](../../aspose.imaging/region/translate/#translate_1)(float, float) | 按指定的量偏移此 `Region` 的坐标。 |
| [Translate](../../aspose.imaging/region/translate/#translate)(int, int) | 按指定的量偏移此 `Region` 的坐标。 |
| [Union](../../aspose.imaging/region/union/#union)(GraphicsPath) | 将此 `Region` 更新为自身与指定的 [`GraphicsPath`](../graphicspath/) 的并集。 |
| [Union](../../aspose.imaging/region/union/#union_1)(Rectangle) | 将此 `Region` 更新为自身与指定的 [`Rectangle`](../rectangle/) 结构的并集。 |
| [Union](../../aspose.imaging/region/union/#union_2)(RectangleF) | 将此 `Region` 更新为自身与指定的 [`RectangleF`](../rectanglef/) 结构的并集。 |
| [Union](../../aspose.imaging/region/union/#union_3)(Region) | 将此 `Region` 更新为自身与指定的 `Region` 的并集。 |
| [Xor](../../aspose.imaging/region/xor/#xor)(GraphicsPath) | 将此 `Region` 更新为自身与指定的 [`GraphicsPath`](../graphicspath/) 的交集的差集（并集减去交集）。 |
| [Xor](../../aspose.imaging/region/xor/#xor_1)(Rectangle) | 将此 `Region` 更新为自身与指定的 [`Rectangle`](../rectangle/) 结构的交集的差集（并集减去交集）。 |
| [Xor](../../aspose.imaging/region/xor/#xor_2)(RectangleF) | 将此 `Region` 更新为自身与指定的 [`RectangleF`](../rectanglef/) 结构的交集的差集（并集减去交集）。 |
| [Xor](../../aspose.imaging/region/xor/#xor_3)(Region) | 将此 `Region` 更新为自身与指定的 `Region` 的交集的差集（并集减去交集）。 |

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


