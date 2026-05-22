---
title: "类 LinearGradientBrush"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Brushes.LinearGradientBrush 类。封装具有线性渐变的 Brush。此类不可被继承"
type: docs
weight: 150
url: /zh/net/aspose.imaging.brushes/lineargradientbrush/
---
## LinearGradientBrush class

封装具有线性渐变的 [`Brush`](../../aspose.imaging/brush/)。此类不可被继承。

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush/#constructor)() | 使用默认参数初始化 `LinearGradientBrush` 类的新实例。起始颜色为黑色，结束颜色为白色，角度为 45 度，矩形位于 (0,0)，大小为 (1,1)。 |
| [LinearGradientBrush](lineargradientbrush/#constructor_1)(Point, Point, Color, Color) | 初始化 `LinearGradientBrush` 类的新实例。 |
| [LinearGradientBrush](lineargradientbrush/#constructor_2)(PointF, PointF, Color, Color) | 初始化 `LinearGradientBrush` 类的新实例。 |
| [LinearGradientBrush](lineargradientbrush/#constructor_3)(Rectangle, Color, Color, float) | 初始化 `LinearGradientBrush` 类的新实例。 |
| [LinearGradientBrush](lineargradientbrush/#constructor_5)(RectangleF, Color, Color, float) | 初始化 `LinearGradientBrush` 类的新实例。 |
| [LinearGradientBrush](lineargradientbrush/#constructor_4)(Rectangle, Color, Color, float, bool) | 初始化 `LinearGradientBrush` 类的新实例。 |
| [LinearGradientBrush](lineargradientbrush/#constructor_6)(RectangleF, Color, Color, float, bool) | 初始化 `LinearGradientBrush` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Angle](../../aspose.imaging.brushes/lineargradientbrushbase/angle/) { get; set; } | 获取或设置渐变角度。 |
| [Blend](../../aspose.imaging.brushes/lineargradientbrush/blend/) { get; set; } | 获取或设置一个 [`Blend`](../../aspose.imaging/blend/) ，它指定用于定义渐变自定义衰减的位置信息和因子。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [EndColor](../../aspose.imaging.brushes/lineargradientbrush/endcolor/) { get; set; } | 获取或设置结束渐变颜色。 |
| [GammaCorrection](../../aspose.imaging.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | 获取或设置一个值，指示是否为此 [`LinearGradientBrushBase`](../lineargradientbrushbase/) 启用伽马校正。 |
| [IsAngleScalable](../../aspose.imaging.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | 获取或设置一个值，指示在使用此 [`LinearGradientBrushBase`](../lineargradientbrushbase/) 进行变换时，[`Angle`](../lineargradientbrushbase/angle/) 是否被更改。 |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged/) { get; } | 获取一个值，指示变换是否以某种方式被更改。例如设置变换矩阵或调用任何修改变换矩阵的方法。此属性为向后兼容 GDI+ 而引入。 |
| [Opacity](../../aspose.imaging/brush/opacity/) { get; set; } | 获取或设置画笔的不透明度。该值应在 0 到 1 之间。0 表示画笔完全透明，1 表示画笔完全不透明。 |
| [Rectangle](../../aspose.imaging.brushes/lineargradientbrushbase/rectangle/) { get; set; } | 获取或设置定义渐变起始点和结束点的矩形区域。 |
| [StartColor](../../aspose.imaging.brushes/lineargradientbrush/startcolor/) { get; set; } | 获取或设置起始渐变颜色。 |
| [Transform](../../aspose.imaging.brushes/transformbrush/transform/) { get; set; } | 获取或设置此 [`TransformBrush`](../transformbrush/) 的本地几何变换的副本 [`Matrix`](../../aspose.imaging/matrix/)。 |
| [WrapMode](../../aspose.imaging.brushes/transformbrush/wrapmode/) { get; set; } | 获取或设置指示此 [`TransformBrush`](../transformbrush/) 包装模式的 [`WrapMode`](../../aspose.imaging/wrapmode/) 枚举。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [DeepClone](../../aspose.imaging/brush/deepclone/)() | 创建当前 [`Brush`](../../aspose.imaging/brush/) 的深度克隆副本。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| override [Equals](../../aspose.imaging/brush/equals/)(object) | 检查对象是否相等。 |
| override [GetHashCode](../../aspose.imaging/brush/gethashcode/)() | 获取当前对象的哈希码。 |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform/)(Matrix) | 将表示此 `LinearGradientBrush` 的局部几何变换的[`Matrix`](../../aspose.imaging/matrix/) 与指定的[`Matrix`](../../aspose.imaging/matrix/)相乘，并在前面预置指定的[`Matrix`](../../aspose.imaging/matrix/)。 |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | 将表示此 `LinearGradientBrush` 的局部几何变换的[`Matrix`](../../aspose.imaging/matrix/) 与指定的[`Matrix`](../../aspose.imaging/matrix/)相乘，顺序如指定。 |
| [ResetTransform](../../aspose.imaging.brushes/transformbrush/resettransform/)() | 将 [`Transform`](../transformbrush/transform/) 属性重置为单位矩阵。 |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform/)(float) | 按指定角度旋转本地几何变换。此方法将旋转前置到变换中。 |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | 按指定顺序以指定角度旋转本地几何变换。 |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform/)(float, float) | 按指定比例缩放本地几何变换。此方法将缩放矩阵前置到变换中。 |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | 按指定顺序以指定比例缩放本地几何变换。 |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | 创建一个线性渐变，中心颜色为主色，两端线性衰减至单一颜色。 |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | 创建一个线性渐变，中心颜色为主色，两端线性衰减至单一颜色。 |
| [SetSigmaBellShape](../../aspose.imaging.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape)(float) | 创建基于钟形曲线的渐变衰减。 |
| [SetSigmaBellShape](../../aspose.imaging.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | 创建基于钟形曲线的渐变衰减。 |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform/)(float, float) | 按指定尺寸平移本地几何变换。此方法将平移前置到变换中。 |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | 按指定顺序以指定尺寸平移本地几何变换。 |

### 另请参见

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* namespace [Aspose.Imaging.Brushes](../../aspose.imaging.brushes/)
* assembly [Aspose.Imaging](../../)


