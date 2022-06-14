---
title: LinearMulticolorGradientBrush
second_title: Aspose.Imaging for .NET API 参考
description: 表示Brush../aspose.imaging/brush具有由多种颜色和适当位置定义的线性渐变这个类不能被继承
type: docs
weight: 170
url: /zh/net/aspose.imaging.brushes/linearmulticolorgradientbrush/
---
## LinearMulticolorGradientBrush class

表示[`Brush`](../../aspose.imaging/brush)具有由多种颜色和适当位置定义的线性渐变。这个类不能被继承。

```csharp
public sealed class LinearMulticolorGradientBrush : LinearGradientBrushBase
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor)() | 使用默认参数初始化[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush)类的新实例。 起始颜色为黑色，结束颜色为白色，角度为 45 度，矩形位于 (0,0)，大小为 (1,1)。 |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_1)(Point, Point) | 用指定的点初始化[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush)类的新实例。 |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_2)(PointF, PointF) | 用指定的点初始化[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush)类的新实例。 |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_3)(Rectangle, float) | 基于矩形和方向角初始化[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush)类的新实例。 |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_5)(RectangleF, float) | 基于矩形和方向角初始化[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush)类的新实例。 |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_4)(Rectangle, float, bool) | 基于矩形和方向角初始化[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush)类的新实例。 |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_6)(RectangleF, float, bool) | 基于矩形和方向角初始化[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Angle](../../aspose.imaging.brushes/lineargradientbrushbase/angle) { get; set; } | 获取或设置渐变角度。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | 获取一个值，该值指示该实例是否被释放。 |
| [GammaCorrection](../../aspose.imaging.brushes/lineargradientbrushbase/gammacorrection) { get; set; } | 获取或设置一个值，该值指示是否为此[`LinearGradientBrushBase`](../lineargradientbrushbase)启用伽马校正。 |
| [InterpolationColors](../../aspose.imaging.brushes/linearmulticolorgradientbrush/interpolationcolors) { get; set; } | 获取或设置定义多色线性渐变的[`ColorBlend`](../../aspose.imaging/colorblend)。 |
| [IsAngleScalable](../../aspose.imaging.brushes/lineargradientbrushbase/isanglescalable) { get; set; } | 获取或设置一个值，该值指示[`Angle`](../lineargradientbrushbase/angle)在使用此:::的转换期间是否更改R5:T:Aspose.Imaging.Brushes.LinearGradientBrushBase:::。 |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | 获取一个值，该值指示转换是否以某种方式更改。例如设置变换矩阵或 调用任何改变变换矩阵的方法。引入该属性是为了向后兼容 GDI+。 |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | 获取或设置画笔不透明度。该值应介于 0 和 1 之间。值 0 表示画笔完全可见，值 1 表示画笔完全不透明。 |
| [Rectangle](../../aspose.imaging.brushes/lineargradientbrushbase/rectangle) { get; set; } | 获取或设置定义渐变起点和终点的矩形区域。 |
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
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float) | 按指定尺寸平移局部几何变换。此方法将转换添加到转换之前。 |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | 以指定顺序将局部几何变换平移指定维度。 |

### 也可以看看

* class [LinearGradientBrushBase](../lineargradientbrushbase)
* 命名空间 [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
