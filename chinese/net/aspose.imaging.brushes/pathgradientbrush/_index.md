---
title: "类 PathGradientBrush"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Brushes.PathGradientBrush 类。封装具有渐变的 Brush 对象。此类不可被继承。"
type: docs
weight: 180
url: /zh/net/aspose.imaging.brushes/pathgradientbrush/
---
## PathGradientBrush class

封装具有渐变的[`Brush`](../../aspose.imaging/brush/)对象。此类不可被继承。

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PathGradientBrush](pathgradientbrush/#constructor)(GraphicsPath) | 使用指定的路径初始化 `PathGradientBrush` 类的新实例。 |
| [PathGradientBrush](pathgradientbrush/#constructor_1)(PointF[]) | 使用指定的点初始化 `PathGradientBrush` 类的新实例。 |
| [PathGradientBrush](pathgradientbrush/#constructor_3)(Point[]) | 使用指定的点初始化 `PathGradientBrush` 类的新实例。 |
| [PathGradientBrush](pathgradientbrush/#constructor_2)(PointF[], WrapMode) | 使用指定的点和包装模式初始化 `PathGradientBrush` 类的新实例。 |
| [PathGradientBrush](pathgradientbrush/#constructor_4)(Point[], WrapMode) | 使用指定的点和包装模式初始化 `PathGradientBrush` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Blend](../../aspose.imaging.brushes/pathgradientbrush/blend/) { get; set; } | 获取或设置一个 [`Blend`](../../aspose.imaging/blend/) ，它指定用于定义渐变自定义衰减的位置信息和因子。 |
| [CenterColor](../../aspose.imaging.brushes/pathgradientbrush/centercolor/) { get; set; } | 获取或设置路径渐变中心的颜色。 |
| [CenterPoint](../../aspose.imaging.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | 获取或设置路径渐变的中心点。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [FocusScales](../../aspose.imaging.brushes/pathgradientbrushbase/focusscales/) { get; set; } | 获取或设置渐变衰减的焦点。 |
| [GraphicsPath](../../aspose.imaging.brushes/pathgradientbrushbase/graphicspath/) { get; } | 获取此画刷所基于的图形路径。 |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged/) { get; } | 获取一个值，指示变换是否以某种方式被更改。例如设置变换矩阵或调用任何修改变换矩阵的方法。此属性为向后兼容 GDI+ 而引入。 |
| [Opacity](../../aspose.imaging/brush/opacity/) { get; set; } | 获取或设置画笔的不透明度。该值应在 0 到 1 之间。0 表示画笔完全透明，1 表示画笔完全不透明。 |
| [PathPoints](../../aspose.imaging.brushes/pathgradientbrushbase/pathpoints/) { get; } | 获取此画刷所基于的路径点。 |
| [SurroundColors](../../aspose.imaging.brushes/pathgradientbrush/surroundcolors/) { get; set; } | 获取或设置一个颜色数组，该数组对应于此 `PathGradientBrush` 填充的路径中的点。 |
| [Transform](../../aspose.imaging.brushes/transformbrush/transform/) { get; set; } | 获取或设置此 [`TransformBrush`](../transformbrush/) 的本地几何变换的副本 [`Matrix`](../../aspose.imaging/matrix/)。 |
| [WrapMode](../../aspose.imaging.brushes/transformbrush/wrapmode/) { get; set; } | 获取或设置指示此 [`TransformBrush`](../transformbrush/) 包装模式的 [`WrapMode`](../../aspose.imaging/wrapmode/) 枚举。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [DeepClone](../../aspose.imaging/brush/deepclone/)() | 创建当前 [`Brush`](../../aspose.imaging/brush/) 的深度克隆副本。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| override [Equals](../../aspose.imaging/brush/equals/)(object) | 检查对象是否相等。 |
| override [GetHashCode](../../aspose.imaging/brush/gethashcode/)() | 获取当前对象的哈希码。 |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform/)(Matrix) | 将表示此 [`LinearGradientBrush`](../lineargradientbrush/) 本地几何变换的 [`Matrix`](../../aspose.imaging/matrix/) 与指定的 [`Matrix`](../../aspose.imaging/matrix/) 相乘，方法是将指定的 [`Matrix`](../../aspose.imaging/matrix/) 前置。 |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | 将表示此 [`LinearGradientBrush`](../lineargradientbrush/) 本地几何变换的 [`Matrix`](../../aspose.imaging/matrix/) 与指定的 [`Matrix`](../../aspose.imaging/matrix/) 相乘，顺序按指定顺序进行。 |
| [ResetTransform](../../aspose.imaging.brushes/transformbrush/resettransform/)() | 将 [`Transform`](../transformbrush/transform/) 属性重置为单位矩阵。 |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform/)(float) | 按指定角度旋转本地几何变换。此方法将旋转前置到变换中。 |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | 按指定顺序以指定角度旋转本地几何变换。 |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform/)(float, float) | 按指定比例缩放本地几何变换。此方法将缩放矩阵前置到变换中。 |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | 按指定顺序以指定比例缩放本地几何变换。 |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | 创建一个渐变，中心颜色为主色，线性衰减至一种周围颜色。 |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | 创建一个渐变，中心颜色为主色，线性衰减至每一种周围颜色。 |
| [SetSigmaBellShape](../../aspose.imaging.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape)(float) | 创建一个渐变画刷，从路径中心向外到路径边界改变颜色。颜色之间的过渡基于钟形曲线。 |
| [SetSigmaBellShape](../../aspose.imaging.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | 创建一个渐变画刷，从路径中心向外到路径边界改变颜色。颜色之间的过渡基于钟形曲线。 |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform/)(float, float) | 按指定尺寸平移本地几何变换。此方法将平移前置到变换中。 |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | 按指定顺序以指定尺寸平移本地几何变换。 |

## 备注

默认情况下，中心颜色为白色。用户可以随时更改此值。

默认情况下，环绕颜色数组以包含白色的单个元素初始化。环绕颜色可以稍后更改，但在设置环绕颜色时至少需要一个元素。

有关其初始化的更多详细信息，请参阅[`Blend`](./blend/)。

### 另请参见

* class [PathGradientBrushBase](../pathgradientbrushbase/)
* namespace [Aspose.Imaging.Brushes](../../aspose.imaging.brushes/)
* assembly [Aspose.Imaging](../../)


