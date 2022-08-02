---
title: Region
second_title: Aspose.Imaging for .NET API 参考
description: 描述由矩形和路径组成的图形形状的内部这个类不能被继承
type: docs
weight: 10850
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
| [Region](region#constructor)() | 初始化一个新的[`Region`](../region) . |
| [Region](region#constructor_1)(GraphicsPath) | 初始化一个新的[`Region`](../region)与指定[`GraphicsPath`](../graphicspath) . |
| [Region](region#constructor_2)(Rectangle) | 初始化一个新的[`Region`](../region)从指定的[`Rectangle`](../rectangle)结构. |
| [Region](region#constructor_3)(RectangleF) | 初始化一个新的[`Region`](../region)从指定的[`RectangleF`](../rectanglef)结构. |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Complement](../../aspose.imaging/region/complement#complement)(GraphicsPath) | 更新这个[`Region`](../region)包含指定的部分[`GraphicsPath`](../graphicspath)与此不相交[`Region`](../region) . |
| [Complement](../../aspose.imaging/region/complement#complement_1)(Rectangle) | 更新这个[`Region`](../region)包含指定的部分[`Rectangle`](../rectangle)与此不相交的结构[`Region`](../region) . |
| [Complement](../../aspose.imaging/region/complement#complement_2)(RectangleF) | 更新这个[`Region`](../region)包含指定的部分[`RectangleF`](../rectanglef)与此不相交的结构[`Region`](../region) . |
| [Complement](../../aspose.imaging/region/complement#complement_3)(Region) | 更新这个[`Region`](../region)包含指定的部分[`Region`](../region)与此不相交[`Region`](../region) . |
| [DeepClone](../../aspose.imaging/region/deepclone)() | 创建一个精确的深拷贝[`Region`](../region) . |
| [Equals](../../aspose.imaging/region/equals#equals)(Region, Graphics) | 测试是否指定[`Region`](../region)与此相同[`Region`](../region)在指定的绘图表面上。 |
| [Exclude](../../aspose.imaging/region/exclude#exclude)(GraphicsPath) | 更新这个[`Region`](../region)仅包含其内部不与指定的部分相交的部分[`GraphicsPath`](../graphicspath) . |
| [Exclude](../../aspose.imaging/region/exclude#exclude_1)(Rectangle) | 更新这个[`Region`](../region)仅包含其内部不与指定的部分相交的部分[`Rectangle`](../rectangle)结构. |
| [Exclude](../../aspose.imaging/region/exclude#exclude_2)(RectangleF) | 更新这个[`Region`](../region)仅包含其内部不与指定的部分相交的部分[`RectangleF`](../rectanglef)结构. |
| [Exclude](../../aspose.imaging/region/exclude#exclude_3)(Region) | 更新这个[`Region`](../region)仅包含其内部不与指定的部分相交的部分[`Region`](../region) . |
| [Intersect](../../aspose.imaging/region/intersect#intersect)(GraphicsPath) | 更新这个[`Region`](../region)到自身与指定的交点[`GraphicsPath`](../graphicspath) . |
| [Intersect](../../aspose.imaging/region/intersect#intersect_1)(Rectangle) | 更新这个[`Region`](../region)到自身与指定的交点[`Rectangle`](../rectangle)结构. |
| [Intersect](../../aspose.imaging/region/intersect#intersect_2)(RectangleF) | 更新这个[`Region`](../region)到自身与指定的交点[`RectangleF`](../rectanglef)结构. |
| [Intersect](../../aspose.imaging/region/intersect#intersect_3)(Region) | 更新这个[`Region`](../region)到自身与指定的交点[`Region`](../region) . |
| [IsEmpty](../../aspose.imaging/region/isempty)(Graphics) | 测试这是否[`Region`](../region)在指定的绘图表面上有一个空的内部。 |
| [IsInfinite](../../aspose.imaging/region/isinfinite)(Graphics) | 测试这是否[`Region`](../region)在指定的绘图表面上有一个无限的内部。 |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible)(Point) | 测试是否指定[`Point`](../point)结构包含在这个[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_2)(PointF) | 测试是否指定[`PointF`](../pointf)结构包含在这个[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_4)(Rectangle) | 测试指定的任何部分是否[`Rectangle`](../rectangle)结构包含在这个[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_6)(RectangleF) | 测试指定的任何部分是否[`RectangleF`](../rectanglef)结构包含在这个[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_11)(float, float) | 测试指定的点是否包含在这个[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_1)(Point, Graphics) | 测试是否指定[`Point`](../point)结构包含在这个[`Region`](../region)使用指定绘制时[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_3)(PointF, Graphics) | 测试是否指定[`PointF`](../pointf)结构包含在这个[`Region`](../region)使用指定绘制时[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_5)(Rectangle, Graphics) | 测试指定的任何部分是否[`Rectangle`](../rectangle)结构包含在这个[`Region`](../region)使用指定绘制时[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_7)(RectangleF, Graphics) | 测试指定的任何部分是否[`RectangleF`](../rectanglef)结构包含在这个[`Region`](../region)使用指定绘制时[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_12)(float, float, Graphics) | 测试指定的点是否包含在这个[`Region`](../region)使用指定绘制时[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_8)(int, int, Graphics) | 测试指定的点是否包含在这个[`Region`](../region)使用指定的对象绘制时[`Graphics`](../graphics)对象. |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_13)(float, float, float, float) | 测试指定矩形的任何部分是否包含在此[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_9)(int, int, int, int) | 测试指定矩形的任何部分是否包含在此[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_14)(float, float, float, float, Graphics) | 测试指定矩形的任何部分是否包含在此[`Region`](../region)使用指定绘制时[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_10)(int, int, int, int, Graphics) | 测试指定矩形的任何部分是否包含在此[`Region`](../region)使用指定绘制时[`Graphics`](../graphics) . |
| [MakeEmpty](../../aspose.imaging/region/makeempty)() | 初始化这个[`Region`](../region)到一个空的内部。 |
| [MakeInfinite](../../aspose.imaging/region/makeinfinite)() | 初始化这个[`Region`](../region)反对无限的内部。 |
| [Transform](../../aspose.imaging/region/transform)(Matrix) | 转换这个[`Region`](../region)由指定的[`Matrix`](../matrix) . |
| [Translate](../../aspose.imaging/region/translate#translate_1)(float, float) | 偏移 this 的坐标[`Region`](../region)按指定数量。 |
| [Translate](../../aspose.imaging/region/translate#translate)(int, int) | 偏移 this 的坐标[`Region`](../region)按指定数量。 |
| [Union](../../aspose.imaging/region/union#union)(GraphicsPath) | 更新这个[`Region`](../region)到自身和指定的联合[`GraphicsPath`](../graphicspath) . |
| [Union](../../aspose.imaging/region/union#union_1)(Rectangle) | 更新这个[`Region`](../region)到自身和指定的联合[`Rectangle`](../rectangle)结构. |
| [Union](../../aspose.imaging/region/union#union_2)(RectangleF) | 更新这个[`Region`](../region)到自身和指定的联合[`RectangleF`](../rectanglef)结构. |
| [Union](../../aspose.imaging/region/union#union_3)(Region) | 更新这个[`Region`](../region)到自身和指定的联合[`Region`](../region) . |
| [Xor](../../aspose.imaging/region/xor#xor)(GraphicsPath) | 更新这个[`Region`](../region)到并集减去自身与指定的交集[`GraphicsPath`](../graphicspath) . |
| [Xor](../../aspose.imaging/region/xor#xor_1)(Rectangle) | 更新这个[`Region`](../region)到并集减去自身与指定的交集[`Rectangle`](../rectangle)结构. |
| [Xor](../../aspose.imaging/region/xor#xor_2)(RectangleF) | 更新这个[`Region`](../region)到并集减去自身与指定的交集[`RectangleF`](../rectanglef)结构. |
| [Xor](../../aspose.imaging/region/xor#xor_3)(Region) | 更新这个[`Region`](../region)到并集减去自身与指定的交集[`Region`](../region) . |

### 也可以看看

* 命名空间 [Aspose.Imaging](../../aspose.imaging)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
