---
title: PathGradientBrush
second_title: Aspose.Imaging for .NET API 参考
description: 用渐变封装Brush../aspose.imaging/brush对象这个类不能被继承
type: docs
weight: 180
url: /zh/net/aspose.imaging.brushes/pathgradientbrush/
---
## PathGradientBrush class

用渐变封装[`Brush`](../../aspose.imaging/brush)对象。这个类不能被继承。

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PathGradientBrush](pathgradientbrush#constructor)(GraphicsPath) | 使用指定路径初始化[`PathGradientBrush`](../pathgradientbrush)类的新实例。 |
| [PathGradientBrush](pathgradientbrush#constructor_1)(PointF[]) | 用指定的点初始化[`PathGradientBrush`](../pathgradientbrush)类的新实例。 |
| [PathGradientBrush](pathgradientbrush#constructor_3)(Point[]) | 用指定的点初始化[`PathGradientBrush`](../pathgradientbrush)类的新实例。 |
| [PathGradientBrush](pathgradientbrush#constructor_2)(PointF[], WrapMode) | 使用指定的点和环绕模式初始化[`PathGradientBrush`](../pathgradientbrush)类的新实例。 |
| [PathGradientBrush](pathgradientbrush#constructor_4)(Point[], WrapMode) | 使用指定的点和环绕模式初始化[`PathGradientBrush`](../pathgradientbrush)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Blend](../../aspose.imaging.brushes/pathgradientbrush/blend) { get; set; } | 获取或设置[`Blend`](../../aspose.imaging/blend)，它指定定义渐变自定义衰减的位置和因子。 |
| [CenterColor](../../aspose.imaging.brushes/pathgradientbrush/centercolor) { get; set; } | 获取或设置路径渐变中心的颜色。 |
| [CenterPoint](../../aspose.imaging.brushes/pathgradientbrushbase/centerpoint) { get; set; } | 获取或设置路径渐变的中心点。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | 获取一个值，该值指示该实例是否被释放。 |
| [FocusScales](../../aspose.imaging.brushes/pathgradientbrushbase/focusscales) { get; set; } | 获取或设置渐变衰减的焦点。 |
| [GraphicsPath](../../aspose.imaging.brushes/pathgradientbrushbase/graphicspath) { get; } | 获取此画笔所基于的图形路径。 |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | 获取一个值，该值指示转换是否以某种方式更改。例如设置变换矩阵或 调用任何改变变换矩阵的方法。引入该属性是为了向后兼容 GDI+。 |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | 获取或设置画笔不透明度。该值应介于 0 和 1 之间。值 0 表示画笔完全可见，值 1 表示画笔完全不透明。 |
| [PathPoints](../../aspose.imaging.brushes/pathgradientbrushbase/pathpoints) { get; } | 获取此画笔所基于的路径点。 |
| [SurroundColors](../../aspose.imaging.brushes/pathgradientbrush/surroundcolors) { get; set; } | 获取或设置与路径中的点对应的颜色数组[`PathGradientBrush`](../pathgradientbrush)填充。 |
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
| [SetBlendTriangularShape](../../aspose.imaging.brushes/pathgradientbrush/setblendtriangularshape#setblendtriangularshape)(float) | 创建具有中心颜色和线性衰减到一种周围颜色的渐变。 |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/pathgradientbrush/setblendtriangularshape#setblendtriangularshape_1)(float, float) | 创建一个具有中心颜色的渐变，以及对每个周围颜色的线性衰减。 |
| [SetSigmaBellShape](../../aspose.imaging.brushes/pathgradientbrush/setsigmabellshape#setsigmabellshape)(float) | 创建一个渐变画笔，从路径中心向外改变颜色到路径边界。从一种颜色到另一种颜色的过渡基于钟形曲线。 |
| [SetSigmaBellShape](../../aspose.imaging.brushes/pathgradientbrush/setsigmabellshape#setsigmabellshape_1)(float, float) | 创建一个渐变画笔，从路径中心向外改变颜色到路径边界。从一种颜色到另一种颜色的过渡基于钟形曲线。 |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float) | 按指定尺寸平移局部几何变换。此方法将转换添加到转换之前。 |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | 以指定顺序将局部几何变换平移指定维度。 |

### 评论

中心颜色默认为白色。用户可以在以后随时更改此值。

默认情况下，环绕颜色数组由包含白色的单个元素初始化。环绕颜色可以稍后更改，但是在设置环绕颜色时至少需要一个元素。

有关其初始化的更多详细信息，请参见[`Blend`](./blend)。

### 也可以看看

* class [PathGradientBrushBase](../pathgradientbrushbase)
* 命名空间 [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
