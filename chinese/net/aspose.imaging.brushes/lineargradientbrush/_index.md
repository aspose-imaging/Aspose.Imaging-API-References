---
title: LinearGradientBrush
second_title: Aspose.Imaging for .NET API 参考
description: 用线性渐变封装Brush../aspose.imaging/brush这个类不能被继承
type: docs
weight: 150
url: /zh/net/aspose.imaging.brushes/lineargradientbrush/
---
## LinearGradientBrush class

用线性渐变封装[`Brush`](../../aspose.imaging/brush)。这个类不能被继承。

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush#constructor)() | 使用默认参数初始化[`LinearGradientBrush`](../lineargradientbrush)类的新实例。 起始颜色为黑色，结束颜色为白色，角度为 45 度，矩形位于 (0,0)，大小为 (1,1)。 |
| [LinearGradientBrush](lineargradientbrush#constructor_1)(Point, Point, Color, Color) | 使用指定的点和颜色初始化[`LinearGradientBrush`](../lineargradientbrush)类的新实例。 |
| [LinearGradientBrush](lineargradientbrush#constructor_2)(PointF, PointF, Color, Color) | 使用指定的点和颜色初始化[`LinearGradientBrush`](../lineargradientbrush)类的新实例。 |
| [LinearGradientBrush](lineargradientbrush#constructor_3)(Rectangle, Color, Color, float) | 基于矩形、开始和结束颜色以及一个方向角。 |
| [LinearGradientBrush](lineargradientbrush#constructor_5)(RectangleF, Color, Color, float) | 基于矩形、开始和结束颜色以及一个方向角。 |
| [LinearGradientBrush](lineargradientbrush#constructor_4)(Rectangle, Color, Color, float, bool) | 基于矩形、开始和结束颜色以及一个方向角。 |
| [LinearGradientBrush](lineargradientbrush#constructor_6)(RectangleF, Color, Color, float, bool) | 基于矩形、开始和结束颜色以及一个方向角。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Angle](../../aspose.imaging.brushes/lineargradientbrushbase/angle) { get; set; } | 获取或设置渐变角度。 |
| [Blend](../../aspose.imaging.brushes/lineargradientbrush/blend) { get; set; } | 获取或设置[`Blend`](../../aspose.imaging/blend)，它指定定义渐变自定义衰减的位置和因子。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | 获取一个值，该值指示该实例是否被释放。 |
| [EndColor](../../aspose.imaging.brushes/lineargradientbrush/endcolor) { get; set; } | 获取或设置结束渐变颜色。 |
| [GammaCorrection](../../aspose.imaging.brushes/lineargradientbrushbase/gammacorrection) { get; set; } | 获取或设置一个值，该值指示是否为此[`LinearGradientBrushBase`](../lineargradientbrushbase)启用伽马校正。 |
| [IsAngleScalable](../../aspose.imaging.brushes/lineargradientbrushbase/isanglescalable) { get; set; } | 获取或设置一个值，该值指示[`Angle`](../lineargradientbrushbase/angle)在使用此:::的转换期间是否更改R5:T:Aspose.Imaging.Brushes.LinearGradientBrushBase:::。 |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | 获取一个值，该值指示转换是否以某种方式更改。例如设置变换矩阵或 调用任何改变变换矩阵的方法。引入该属性是为了向后兼容 GDI+。 |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | 获取或设置画笔不透明度。该值应介于 0 和 1 之间。值 0 表示画笔完全可见，值 1 表示画笔完全不透明。 |
| [Rectangle](../../aspose.imaging.brushes/lineargradientbrushbase/rectangle) { get; set; } | 获取或设置定义渐变起点和终点的矩形区域。 |
| [StartColor](../../aspose.imaging.brushes/lineargradientbrush/startcolor) { get; set; } | 获取或设置起始渐变颜色。 |
| [Transform](../../aspose.imaging.brushes/transformbrush/transform) { get; set; } | 获取或设置一个副本[`Matrix`](../../aspose.imaging/matrix)为这个T定义一个局部几何变换:Aspose.Imaging.Brushes.TransformBrush。 |
| [WrapMode](../../aspose.imaging.brushes/transformbrush/wrapmode) { get; set; } | 获取或设置一个[`WrapMode`](../../aspose.imaging/wrapmode)枚举，指示此TransformBrush。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [DeepClone](../../aspose.imaging/brush/deepclone)() | 创建当前[`Brush`](../../aspose.imaging/brush)的新深度克隆。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | 释放当前实例。 |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform)(Matrix) | 乘以[`Matrix`](../../aspose.imaging/matrix)表示此LinearGradientBrush通过指定[`Matrix`](../../aspose.imaging/matrix)通过预先指定[`Matrix`](../../aspose.imaging/matrix)。 |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform)(Matrix, MatrixOrder) | 乘以[`Matrix`](../../aspose.imaging/matrix)表示此LinearGradientBrush由指定的[`Matrix`](../../aspose.imaging/matrix)以指定的顺序。 |
| [ResetTransform](../../aspose.imaging.brushes/transformbrush/resettransform)() | 将[`Transform`](../transformbrush/transform)属性重置为身份。 |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform)(float) | 将局部几何变换旋转指定的量。此方法将旋转添加到变换中。 |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform)(float, MatrixOrder) | 以指定顺序将局部几何变换旋转指定量。 |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform)(float, float) | 按指定量缩放局部几何变换。此方法将缩放矩阵添加到变换中。 |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform)(float, float, MatrixOrder) | 按指定顺序按指定量缩放局部几何变换。 |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/lineargradientbrush/setblendtriangularshape#setblendtriangularshape)(float) | 使用中心颜色创建线性渐变，两端线性衰减为单一颜色。 |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/lineargradientbrush/setblendtriangularshape#setblendtriangularshape_1)(float, float) | 使用中心颜色创建线性渐变，两端线性衰减为单一颜色。 |
| [SetSigmaBellShape](../../aspose.imaging.brushes/lineargradientbrush/setsigmabellshape#setsigmabellshape)(float) | 基于钟形曲线创建渐变衰减。 |
| [SetSigmaBellShape](../../aspose.imaging.brushes/lineargradientbrush/setsigmabellshape#setsigmabellshape_1)(float, float) | 基于钟形曲线创建渐变衰减。 |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float) | 按指定尺寸平移局部几何变换。此方法将转换添加到转换之前。 |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | 以指定顺序将局部几何变换平移指定维度。 |

### 也可以看看

* class [LinearGradientBrushBase](../lineargradientbrushbase)
* 命名空间 [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
