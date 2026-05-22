---
title: "类 PathGradientBrushBase"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Brushes.PathGradientBrushBase 类。表示具有基础路径渐变功能的 Brush。"
type: docs
weight: 190
url: /zh/net/aspose.imaging.brushes/pathgradientbrushbase/
---
## PathGradientBrushBase class

表示具有基础路径渐变功能的[`Brush`](../../aspose.imaging/brush/)。

```csharp
public abstract class PathGradientBrushBase : TransformBrush
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [CenterPoint](../../aspose.imaging.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | 获取或设置路径渐变的中心点。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [FocusScales](../../aspose.imaging.brushes/pathgradientbrushbase/focusscales/) { get; set; } | 获取或设置渐变衰减的焦点。 |
| [GraphicsPath](../../aspose.imaging.brushes/pathgradientbrushbase/graphicspath/) { get; } | 获取此画刷所基于的图形路径。 |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged/) { get; } | 获取一个值，指示变换是否以某种方式被更改。例如设置变换矩阵或调用任何修改变换矩阵的方法。此属性为向后兼容 GDI+ 而引入。 |
| [Opacity](../../aspose.imaging/brush/opacity/) { get; set; } | 获取或设置画笔的不透明度。该值应在 0 到 1 之间。0 表示画笔完全透明，1 表示画笔完全不透明。 |
| [PathPoints](../../aspose.imaging.brushes/pathgradientbrushbase/pathpoints/) { get; } | 获取此画刷所基于的路径点。 |
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
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform/)(float, float) | 按指定尺寸平移本地几何变换。此方法将平移前置到变换中。 |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | 按指定顺序以指定尺寸平移本地几何变换。 |

## 备注

请注意，在创建 `PathGradientBrushBase` 类时，至少应使用 2 个点进行初始化。创建的内部路径始终是闭合图形，最后一点连接到第一点。该形状由此 `PathGradientBrushBase` 填充。GDI+ 实现会在传入空数组或点集合具有相同坐标时抛出 OutOfMemoryException。`PathGradientBrushBase` 在点数组少于 2 个点时会抛出异常，且在点数组不可接受时抛出 ArgumentException 而不是 OutOfMemoryException。默认情况下，中心点根据传入点的质心计算。用户可以稍后更改此点。焦点比例默认是空点 (0.0, 0.0)。

### 另请参见

* class [TransformBrush](../transformbrush/)
* namespace [Aspose.Imaging.Brushes](../../aspose.imaging.brushes/)
* assembly [Aspose.Imaging](../../)


