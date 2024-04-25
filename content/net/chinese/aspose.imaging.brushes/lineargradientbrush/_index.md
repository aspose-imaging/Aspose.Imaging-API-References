---
title: LinearGradientBrush
second_title: Aspose.Imaging for .NET API 参考
description: 封装一个Brush../aspose.imaging/brush具有线性渐变这个类不能被继承
type: docs
weight: 150
url: /zh/aspose.imaging.brushes/lineargradientbrush/
---
## LinearGradientBrush class

封装一个[`Brush`](../../aspose.imaging/brush)具有线性渐变。这个类不能被继承。

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush#constructor)() | 初始化[`LinearGradientBrush`](../lineargradientbrush)具有默认参数的类。 起始颜色为黑色，结束颜色为白色，角度为 45 度，矩形位于 (0,0)，大小为 (1,1)。 |
| [LinearGradientBrush](lineargradientbrush#constructor_1)(Point, Point, Color, Color) | 初始化[`LinearGradientBrush`](../lineargradientbrush)具有指定点和颜色的类。 |
| [LinearGradientBrush](lineargradientbrush#constructor_2)(PointF, PointF, Color, Color) | 初始化[`LinearGradientBrush`](../lineargradientbrush)具有指定点和颜色的类。 |
| [LinearGradientBrush](lineargradientbrush#constructor_3)(Rectangle, Color, Color, float) | 初始化[`LinearGradientBrush`](../lineargradientbrush)基于矩形、开始和结束颜色以及方向角的类。 |
| [LinearGradientBrush](lineargradientbrush#constructor_5)(RectangleF, Color, Color, float) | 初始化[`LinearGradientBrush`](../lineargradientbrush)基于矩形、开始和结束颜色以及方向角的类。 |
| [LinearGradientBrush](lineargradientbrush#constructor_4)(Rectangle, Color, Color, float, bool) | 初始化[`LinearGradientBrush`](../lineargradientbrush)基于矩形、开始和结束颜色以及方向角的类。 |
| [LinearGradientBrush](lineargradientbrush#constructor_6)(RectangleF, Color, Color, float, bool) | 初始化[`LinearGradientBrush`](../lineargradientbrush)基于矩形、开始和结束颜色以及方向角的类。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Angle](../../aspose.imaging.brushes/lineargradientbrushbase/angle) { get; set; } | 获取或设置渐变角度。 |
| [Blend](../../aspose.imaging.brushes/lineargradientbrush/blend) { get; set; } | 获取或设置一个[`Blend`](../../aspose.imaging/blend)指定为渐变定义自定义衰减的位置和因子。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | 获取一个值，该值指示此实例是否被释放。 |
| [EndColor](../../aspose.imaging.brushes/lineargradientbrush/endcolor) { get; set; } | 获取或设置结束渐变颜色。 |
| [GammaCorrection](../../aspose.imaging.brushes/lineargradientbrushbase/gammacorrection) { get; set; } | 获取或设置一个值，该值指示是否为此启用伽马校正[`LinearGradientBrushBase`](../lineargradientbrushbase) . |
| [IsAngleScalable](../../aspose.imaging.brushes/lineargradientbrushbase/isanglescalable) { get; set; } | 获取或设置一个值，指示是否[`Angle`](../lineargradientbrushbase/angle)在转换过程中改变了这个[`LinearGradientBrushBase`](../lineargradientbrushbase) . |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | 获取一个值，该值指示转换是否以某种方式更改。例如设置变换矩阵或 调用任何改变变换矩阵的方法。引入该属性是为了向后兼容 GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | 获取或设置画笔不透明度。该值应介于 0 和 1 之间。值 0 表示画笔完全可见，值 1 表示画笔完全不透明。 |
| [Rectangle](../../aspose.imaging.brushes/lineargradientbrushbase/rectangle) { get; set; } | 获取或设置定义渐变起点和终点的矩形区域。 |
| [StartColor](../../aspose.imaging.brushes/lineargradientbrush/startcolor) { get; set; } | 获取或设置起始渐变颜色。 |
| [Transform](../../aspose.imaging.brushes/transformbrush/transform) { get; set; } | 获取或设置一个副本[`Matrix`](../../aspose.imaging/matrix)它为此定义了一个局部几何变换[`TransformBrush`](../transformbrush) . |
| [WrapMode](../../aspose.imaging.brushes/transformbrush/wrapmode) { get; set; } | 获取或设置一个[`WrapMode`](../../aspose.imaging/wrapmode)指示此包装模式的枚举[`TransformBrush`](../transformbrush) . |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [DeepClone](../../aspose.imaging/brush/deepclone)() | 创建当前的新深层克隆[`Brush`](../../aspose.imaging/brush) . |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | 处理当前实例。 |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform)(Matrix) | 乘以[`Matrix`](../../aspose.imaging/matrix)表示这个的局部几何变换[`LinearGradientBrush`](../lineargradientbrush)由指定的[`Matrix`](../../aspose.imaging/matrix)通过预先指定[`Matrix`](../../aspose.imaging/matrix) . |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform)(Matrix, MatrixOrder) | 乘以[`Matrix`](../../aspose.imaging/matrix)表示这个的局部几何变换[`LinearGradientBrush`](../lineargradientbrush)由指定的[`Matrix`](../../aspose.imaging/matrix)按指定顺序。 |
| [ResetTransform](../../aspose.imaging.brushes/transformbrush/resettransform)() | 重置[`Transform`](../transformbrush/transform)身份的属性. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform)(float) | 将局部几何变换旋转指定的量。此方法将旋转添加到 transform. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform)(float, MatrixOrder) | 以指定顺序将局部几何变换旋转指定量。 |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform)(float, float) | 按指定量缩放局部几何变换。此方法将缩放矩阵添加到 transform. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform)(float, float, MatrixOrder) | 按指定顺序按指定量缩放局部几何变换。 |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/lineargradientbrush/setblendtriangularshape#setblendtriangularshape)(float) | 创建一个具有中心颜色的线性渐变，并在两端线性衰减为单一颜色。 |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/lineargradientbrush/setblendtriangularshape#setblendtriangularshape_1)(float, float) | 创建一个具有中心颜色的线性渐变，并在两端线性衰减为单一颜色。 |
| [SetSigmaBellShape](../../aspose.imaging.brushes/lineargradientbrush/setsigmabellshape#setsigmabellshape)(float) | 基于钟形曲线创建渐变衰减。 |
| [SetSigmaBellShape](../../aspose.imaging.brushes/lineargradientbrush/setsigmabellshape#setsigmabellshape_1)(float, float) | 基于钟形曲线创建渐变衰减。 |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float) | 按指定尺寸平移局部几何变换。此方法将转换添加到 transform. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | 以指定顺序按指定维度平移局部几何变换。 |

### 也可以看看

* class [LinearGradientBrushBase](../lineargradientbrushbase)
* 命名空间 [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
