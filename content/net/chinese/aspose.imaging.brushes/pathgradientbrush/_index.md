---
title: PathGradientBrush
second_title: Aspose.Imaging for .NET API 参考
description: 封装一个Brush../aspose.imaging/brush带有渐变的对象这个类不能被继承
type: docs
weight: 180
url: /zh/aspose.imaging.brushes/pathgradientbrush/
---
## PathGradientBrush class

封装一个[`Brush`](../../aspose.imaging/brush)带有渐变的对象。这个类不能被继承。

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PathGradientBrush](pathgradientbrush#constructor)(GraphicsPath) | 初始化[`PathGradientBrush`](../pathgradientbrush)具有指定路径的类。 |
| [PathGradientBrush](pathgradientbrush#constructor_1)(PointF[]) | 初始化[`PathGradientBrush`](../pathgradientbrush)具有指定点的类。 |
| [PathGradientBrush](pathgradientbrush#constructor_3)(Point[]) | 初始化[`PathGradientBrush`](../pathgradientbrush)具有指定点的类。 |
| [PathGradientBrush](pathgradientbrush#constructor_2)(PointF[], WrapMode) | 初始化[`PathGradientBrush`](../pathgradientbrush)具有指定点和环绕模式的类。 |
| [PathGradientBrush](pathgradientbrush#constructor_4)(Point[], WrapMode) | 初始化[`PathGradientBrush`](../pathgradientbrush)具有指定点和环绕模式的类。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Blend](../../aspose.imaging.brushes/pathgradientbrush/blend) { get; set; } | 获取或设置一个[`Blend`](../../aspose.imaging/blend)指定为渐变定义自定义衰减的位置和因子。 |
| [CenterColor](../../aspose.imaging.brushes/pathgradientbrush/centercolor) { get; set; } | 获取或设置路径渐变中心的颜色。 |
| [CenterPoint](../../aspose.imaging.brushes/pathgradientbrushbase/centerpoint) { get; set; } | 获取或设置路径渐变的中心点。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | 获取一个值，该值指示此实例是否被释放。 |
| [FocusScales](../../aspose.imaging.brushes/pathgradientbrushbase/focusscales) { get; set; } | 获取或设置渐变衰减的焦点。 |
| [GraphicsPath](../../aspose.imaging.brushes/pathgradientbrushbase/graphicspath) { get; } | 获取此画笔所基于的图形路径。 |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | 获取一个值，该值指示转换是否以某种方式更改。例如设置变换矩阵或 调用任何改变变换矩阵的方法。引入该属性是为了向后兼容 GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | 获取或设置画笔不透明度。该值应介于 0 和 1 之间。值 0 表示画笔完全可见，值 1 表示画笔完全不透明。 |
| [PathPoints](../../aspose.imaging.brushes/pathgradientbrushbase/pathpoints) { get; } | 获取此画笔所基于的路径点。 |
| [SurroundColors](../../aspose.imaging.brushes/pathgradientbrush/surroundcolors) { get; set; } | 获取或设置与此路径中的点相对应的颜色数组[`PathGradientBrush`](../pathgradientbrush)填充. |
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
| [SetBlendTriangularShape](../../aspose.imaging.brushes/pathgradientbrush/setblendtriangularshape#setblendtriangularshape)(float) | 创建具有中心颜色和线性衰减到一种周围颜色的渐变。 |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/pathgradientbrush/setblendtriangularshape#setblendtriangularshape_1)(float, float) | 创建一个具有中心颜色的渐变和对每个周围颜色的线性衰减。 |
| [SetSigmaBellShape](../../aspose.imaging.brushes/pathgradientbrush/setsigmabellshape#setsigmabellshape)(float) | 创建一个渐变画笔，从路径中心向外更改颜色到路径边界。从一种颜色到另一种颜色的过渡基于钟形曲线。 |
| [SetSigmaBellShape](../../aspose.imaging.brushes/pathgradientbrush/setsigmabellshape#setsigmabellshape_1)(float, float) | 创建一个渐变画笔，从路径中心向外更改颜色到路径边界。从一种颜色到另一种颜色的过渡基于钟形曲线。 |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float) | 按指定尺寸平移局部几何变换。此方法将转换添加到 transform. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | 以指定顺序按指定维度平移局部几何变换。 |

### 评论

中心颜色默认为白色。用户可以在以后随时更改此值。

默认情况下，环绕颜色数组由包含白色的单个元素初始化。环绕颜色可以稍后更改，但是在设置环绕颜色时至少需要一个元素。

见[`Blend`](./blend)有关其初始化的更多详细信息。

### 也可以看看

* class [PathGradientBrushBase](../pathgradientbrushbase)
* 命名空间 [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
