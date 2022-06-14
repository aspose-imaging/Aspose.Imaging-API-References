---
title: Region
second_title: Aspose.Imaging for .NET API 参考
description: 描述由矩形和路径组成的图形形状的内部这个类不能被继承
type: docs
weight: 10860
url: /zh/net/aspose.imaging/region/
---
## Region class

描述由矩形和路径组成的图形形状的内部。这个类不能被继承。

```csharp
public sealed class Region
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Region](region#constructor)() | 初始化一个新的[`Region`](../region)。 |
| [Region](region#constructor_1)(GraphicsPath) | 用指定的GraphicsPath::初始化一个新的R5:T:Aspose.Imaging.Region::::. |
| [Region](region#constructor_2)(Rectangle) | 从指定的Rectangle::初始化一个新的R5:T:Aspose.Imaging.Region::::结构体。 |
| [Region](region#constructor_3)(RectangleF) | 从指定的RectangleF::初始化一个新的R5:T:Aspose.Imaging.Region::::结构体。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Complement](../../aspose.imaging/region/complement#complement)(GraphicsPath) | 更新此[`Region`](../region)以包含指定Imaging的部分。GraphicsPath不与此[`Region`](../region)相交。 |
| [Complement](../../aspose.imaging/region/complement#complement_1)(Rectangle) | 更新此[`Region`](../region)以包含指定Imaging的部分。与此R5:T:Aspose.Imaging.Region:::不相交的 Rectangle:::结构。 |
| [Complement](../../aspose.imaging/region/complement#complement_2)(RectangleF) | 更新此[`Region`](../region)以包含指定Imaging的部分。与此R5:T:Aspose.Imaging.Region:::不相交的 RectangleF:::结构。 |
| [Complement](../../aspose.imaging/region/complement#complement_3)(Region) | 更新此[`Region`](../region)以包含指定Imaging的部分。Region不与此[`Region`](../region)相交。 |
| [DeepClone](../../aspose.imaging/region/deepclone)() | 创建此[`Region`](../region)的精确深层副本。 |
| [Equals](../../aspose.imaging/region/equals#equals)(Region, Graphics) | 测试指定的[`Region`](../region)是否与此Region相同在指定的绘图表面上。 |
| [Exclude](../../aspose.imaging/region/exclude#exclude)(GraphicsPath) | 更新此[`Region`](../region)以仅包含其内部不与指定:::相交的部分R5:T:Aspose.Imaging.GraphicsPath:::。 |
| [Exclude](../../aspose.imaging/region/exclude#exclude_1)(Rectangle) | 更新此[`Region`](../region)以仅包含其内部不与指定:::相交的部分R5:T:Aspose.Imaging.Rectangle:::结构。 |
| [Exclude](../../aspose.imaging/region/exclude#exclude_2)(RectangleF) | 更新此[`Region`](../region)以仅包含其内部不与指定:::相交的部分R5:T:Aspose.Imaging.RectangleF:::结构。 |
| [Exclude](../../aspose.imaging/region/exclude#exclude_3)(Region) | 更新此[`Region`](../region)以仅包含其内部不与指定:::相交的部分R5:T:Aspose.Imaging.Region:::。 |
| [Intersect](../../aspose.imaging/region/intersect#intersect)(GraphicsPath) | 将此[`Region`](../region)更新为自身与指定GraphicsPath。 |
| [Intersect](../../aspose.imaging/region/intersect#intersect_1)(Rectangle) | 将此[`Region`](../region)更新为自身与指定Rectangle结构。 |
| [Intersect](../../aspose.imaging/region/intersect#intersect_2)(RectangleF) | 将此[`Region`](../region)更新为自身与指定RectangleF结构。 |
| [Intersect](../../aspose.imaging/region/intersect#intersect_3)(Region) | 将此[`Region`](../region)更新为自身与指定Imaging的交集。地区。 |
| [IsEmpty](../../aspose.imaging/region/isempty)(Graphics) | 测试此[`Region`](../region)在指定绘图表面上是否有一个空的内部。 |
| [IsInfinite](../../aspose.imaging/region/isinfinite)(Graphics) | 测试此[`Region`](../region)在指定绘图表面上是否具有无限内部。 |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible)(Point) | 测试指定的[`Point`](../point)结构是否包含在此Imaging中。地区。 |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_2)(PointF) | 测试指定的[`PointF`](../pointf)结构是否包含在此Imaging中。地区。 |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_4)(Rectangle) | 测试指定[`Rectangle`](../rectangle)结构的任何部分是否包含在此区域。 |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_6)(RectangleF) | 测试指定[`RectangleF`](../rectanglef)结构的任何部分是否包含在此区域。 |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_11)(float, float) | 测试指定点是否包含在此[`Region`](../region)中。 |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_1)(Point, Graphics) | 测试指定的[`Point`](../point)结构是否包含在此Imaging中。Region使用指定的[`Graphics`](../graphics)绘制时。 |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_3)(PointF, Graphics) | 测试指定的[`PointF`](../pointf)结构是否包含在此Imaging中。Region使用指定的[`Graphics`](../graphics)绘制时。 |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_5)(Rectangle, Graphics) | 测试指定[`Rectangle`](../rectangle)结构的任何部分是否包含在此Region使用指定的[`Graphics`](../graphics)绘制时。 |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_7)(RectangleF, Graphics) | 测试指定[`RectangleF`](../rectanglef)结构的任何部分是否包含在此Region使用指定的[`Graphics`](../graphics)绘制时。 |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_12)(float, float, Graphics) | 使用指定T绘制时，测试指定点是否包含在此R5:T:Aspose.Imaging.Region:::中:Aspose.Imaging.Graphics:::。 |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_8)(int, int, Graphics) | 使用指定的:::R5 绘制时，测试指定的点是否包含在此[`Region`](../region)对象中:T:Aspose.Imaging.Graphics:::对象。 |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_13)(float, float, float, float) | 测试指定矩形的任何部分是否包含在此[`Region`](../region)中。 |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_9)(int, int, int, int) | 测试指定矩形的任何部分是否包含在此[`Region`](../region)中。 |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_14)(float, float, float, float, Graphics) | 测试指定矩形的任何部分是否包含在此[`Region`](../region)中，当使用指定的:::绘制时R5:T:Aspose.Imaging.Graphics:::。 |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_10)(int, int, int, int, Graphics) | 测试指定矩形的任何部分是否包含在此[`Region`](../region)中，当使用指定的:::绘制时R5:T:Aspose.Imaging.Graphics:::。 |
| [MakeEmpty](../../aspose.imaging/region/makeempty)() | 将此[`Region`](../region)初始化为空的内部。 |
| [MakeInfinite](../../aspose.imaging/region/makeinfinite)() | 将此[`Region`](../region)对象初始化为无限内部。 |
| [Transform](../../aspose.imaging/region/transform)(Matrix) | 将这个[`Region`](../region)转换为指定的[`Matrix`](../matrix). |
| [Translate](../../aspose.imaging/region/translate#translate_1)(float, float) | 将此[`Region`](../region)的坐标偏移指定量。 |
| [Translate](../../aspose.imaging/region/translate#translate)(int, int) | 将此[`Region`](../region)的坐标偏移指定量。 |
| [Union](../../aspose.imaging/region/union#union)(GraphicsPath) | 将此[`Region`](../region)更新为自身与指定GraphicsPath。 |
| [Union](../../aspose.imaging/region/union#union_1)(Rectangle) | 将此[`Region`](../region)更新为自身与指定Rectangle结构。 |
| [Union](../../aspose.imaging/region/union#union_2)(RectangleF) | 将此[`Region`](../region)更新为自身与指定RectangleF结构。 |
| [Union](../../aspose.imaging/region/union#union_3)(Region) | 将此[`Region`](../region)更新为自身与指定Imaging的并集。地区。 |
| [Xor](../../aspose.imaging/region/xor#xor)(GraphicsPath) | 将此[`Region`](../region)更新为联合减去其自身与指定T的交集:Aspose.Imaging.GraphicsPath。 |
| [Xor](../../aspose.imaging/region/xor#xor_1)(Rectangle) | 将此[`Region`](../region)更新为联合减去其自身与指定T的交集:Aspose.Imaging.Rectangle结构。 |
| [Xor](../../aspose.imaging/region/xor#xor_2)(RectangleF) | 将此[`Region`](../region)更新为联合减去其自身与指定T的交集:Aspose.Imaging.RectangleF结构。 |
| [Xor](../../aspose.imaging/region/xor#xor_3)(Region) | 将此[`Region`](../region)更新为联合减去其自身与指定T的交集:Aspose.Imaging.Region。 |

### 也可以看看

* 命名空间 [Aspose.Imaging](../../aspose.imaging)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
