---
title: LinearMulticolorGradientBrush
second_title: Aspose.Imaging for .NET API 参考
description: 代表一个Brush../aspose.imaging/brush具有由多种颜色和适当位置定义的线性渐变这个类不能被继承
type: docs
weight: 170
url: /zh/net/aspose.imaging.brushes/linearmulticolorgradientbrush/
---
## LinearMulticolorGradientBrush class

代表一个[`Brush`](../../aspose.imaging/brush)具有由多种颜色和适当位置定义的线性渐变。这个类不能被继承。

```csharp
public sealed class LinearMulticolorGradientBrush : LinearGradientBrushBase
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor)() | 初始化[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush)具有默认参数的类。 起始颜色为黑色，结束颜色为白色，角度为 45 度，矩形位于 (0,0)，大小为 (1,1)。 |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_1)(Point, Point) | 初始化[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush)具有指定点的类。 |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_2)(PointF, PointF) | 初始化[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush)具有指定点的类。 |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_3)(Rectangle, float) | 初始化[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush)基于矩形和方向角的类。 |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_5)(RectangleF, float) | 初始化[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush)基于矩形和方向角的类。 |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_4)(Rectangle, float, bool) | 初始化[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush)基于矩形和方向角的类。 |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_6)(RectangleF, float, bool) | 初始化[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush)基于矩形和方向角的类。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Angle](../../aspose.imaging.brushes/lineargradientbrushbase/angle) { get; set; } | 获取或设置渐变角度。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | 获取一个值，该值指示此实例是否被释放。 |
| [GammaCorrection](../../aspose.imaging.brushes/lineargradientbrushbase/gammacorrection) { get; set; } | 获取或设置一个值，该值指示是否为此启用伽马校正[`LinearGradientBrushBase`](../lineargradientbrushbase) . |
| [InterpolationColors](../../aspose.imaging.brushes/linearmulticolorgradientbrush/interpolationcolors) { get; set; } | 获取或设置一个[`ColorBlend`](../../aspose.imaging/colorblend)定义多色线性渐变。 |
| [IsAngleScalable](../../aspose.imaging.brushes/lineargradientbrushbase/isanglescalable) { get; set; } | 获取或设置一个值，指示是否[`Angle`](../lineargradientbrushbase/angle)在转换过程中改变了这个[`LinearGradientBrushBase`](../lineargradientbrushbase) . |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | 获取一个值，该值指示转换是否以某种方式更改。例如设置变换矩阵或 调用任何改变变换矩阵的方法。引入该属性是为了向后兼容 GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | 获取或设置画笔不透明度。该值应介于 0 和 1 之间。值 0 表示画笔完全可见，值 1 表示画笔完全不透明。 |
| [Rectangle](../../aspose.imaging.brushes/lineargradientbrushbase/rectangle) { get; set; } | 获取或设置定义渐变起点和终点的矩形区域。 |
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
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float) | 按指定尺寸平移局部几何变换。此方法将转换添加到 transform. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | 以指定顺序按指定维度平移局部几何变换。 |

### 也可以看看

* class [LinearGradientBrushBase](../lineargradientbrushbase)
* 命名空间 [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
