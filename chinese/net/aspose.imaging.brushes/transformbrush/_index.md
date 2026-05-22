---
title: "类 TransformBrush"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Brushes.TransformBrush 类。具有变换功能的 Brush"
type: docs
weight: 230
url: /zh/net/aspose.imaging.brushes/transformbrush/
---
## TransformBrush class

一个具有变换功能的 [`Brush`](../../aspose.imaging/brush/)。

```csharp
public abstract class TransformBrush : Brush
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged/) { get; } | 获取一个值，指示变换是否以某种方式被更改。例如设置变换矩阵或调用任何修改变换矩阵的方法。此属性为向后兼容 GDI+ 而引入。 |
| [Opacity](../../aspose.imaging/brush/opacity/) { get; set; } | 获取或设置画笔的不透明度。该值应在 0 到 1 之间。0 表示画笔完全透明，1 表示画笔完全不透明。 |
| [Transform](../../aspose.imaging.brushes/transformbrush/transform/) { get; set; } | 获取或设置一个副本 [`Matrix`](../../aspose.imaging/matrix/)，它定义了此 `TransformBrush` 的本地几何变换。 |
| [WrapMode](../../aspose.imaging.brushes/transformbrush/wrapmode/) { get; set; } | 获取或设置一个 [`WrapMode`](../../aspose.imaging/wrapmode/) 枚举，指示此 `TransformBrush` 的包装模式。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [DeepClone](../../aspose.imaging/brush/deepclone/)() | 创建当前 [`Brush`](../../aspose.imaging/brush/) 的深度克隆副本。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| override [Equals](../../aspose.imaging/brush/equals/)(object) | 检查对象是否相等。 |
| override [GetHashCode](../../aspose.imaging/brush/gethashcode/)() | 获取当前对象的哈希码。 |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform/#multiplytransform)(Matrix) | 将表示此 [`LinearGradientBrush`](../lineargradientbrush/) 本地几何变换的 [`Matrix`](../../aspose.imaging/matrix/) 与指定的 [`Matrix`](../../aspose.imaging/matrix/) 相乘，方法是将指定的 [`Matrix`](../../aspose.imaging/matrix/) 前置。 |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | 将表示此 [`LinearGradientBrush`](../lineargradientbrush/) 本地几何变换的 [`Matrix`](../../aspose.imaging/matrix/) 与指定的 [`Matrix`](../../aspose.imaging/matrix/) 相乘，顺序按指定顺序进行。 |
| [ResetTransform](../../aspose.imaging.brushes/transformbrush/resettransform/)() | 将 [`Transform`](./transform/) 属性重置为单位矩阵。 |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform/#rotatetransform)(float) | 按指定角度旋转本地几何变换。此方法将旋转前置到变换中。 |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | 按指定顺序以指定角度旋转本地几何变换。 |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform/#scaletransform)(float, float) | 按指定比例缩放本地几何变换。此方法将缩放矩阵前置到变换中。 |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | 按指定顺序以指定比例缩放本地几何变换。 |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform/#translatetransform)(float, float) | 按指定尺寸平移本地几何变换。此方法将平移前置到变换中。 |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | 按指定顺序以指定尺寸平移本地几何变换。 |

### 另请参见

* class [Brush](../../aspose.imaging/brush/)
* namespace [Aspose.Imaging.Brushes](../../aspose.imaging.brushes/)
* assembly [Aspose.Imaging](../../)


