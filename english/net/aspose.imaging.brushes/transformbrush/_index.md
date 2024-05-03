---
title: Class TransformBrush
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.Brushes.TransformBrush class. A Brush with transform capabilities
type: docs
weight: 230
url: /net/aspose.imaging.brushes/transformbrush/
---
## TransformBrush class

A [`Brush`](../../aspose.imaging/brush/) with transform capabilities.

```csharp
public abstract class TransformBrush : Brush
```

## Properties

| Name | Description |
| --- | --- |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged/) { get; } | Gets a value indicating whether transformations were changed in some way. For example setting the transformation matrix or calling any of the methods altering the transformation matrix. The property is introduced for backward compatibility with GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity/) { get; set; } | Gets or sets the brush opacity. The value should be between 0 and 1. Value of 0 means that brush is fully visible, value of 1 means the brush is fully opaque. |
| [Transform](../../aspose.imaging.brushes/transformbrush/transform/) { get; set; } | Gets or sets a copy [`Matrix`](../../aspose.imaging/matrix/) that defines a local geometric transform for this `TransformBrush`. |
| [WrapMode](../../aspose.imaging.brushes/transformbrush/wrapmode/) { get; set; } | Gets or sets a [`WrapMode`](../../aspose.imaging/wrapmode/) enumeration that indicates the wrap mode for this `TransformBrush`. |

## Methods

| Name | Description |
| --- | --- |
| virtual [DeepClone](../../aspose.imaging/brush/deepclone/)() | Creates a new deep clone of the current [`Brush`](../../aspose.imaging/brush/). |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | Disposes the current instance. |
| override [Equals](../../aspose.imaging/brush/equals/)(object) | Check if objects are equal. |
| override [GetHashCode](../../aspose.imaging/brush/gethashcode/)() | Get hash code of the current object. |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform/#multiplytransform)(Matrix) | Multiplies the [`Matrix`](../../aspose.imaging/matrix/) that represents the local geometric transform of this [`LinearGradientBrush`](../lineargradientbrush/) by the specified [`Matrix`](../../aspose.imaging/matrix/) by prepending the specified [`Matrix`](../../aspose.imaging/matrix/). |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Multiplies the [`Matrix`](../../aspose.imaging/matrix/) that represents the local geometric transform of this [`LinearGradientBrush`](../lineargradientbrush/) by the specified [`Matrix`](../../aspose.imaging/matrix/) in the specified order. |
| [ResetTransform](../../aspose.imaging.brushes/transformbrush/resettransform/)() | Resets the [`Transform`](./transform/) property to identity. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform/#rotatetransform)(float) | Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Rotates the local geometric transform by the specified amount in the specified order. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform/#scaletransform)(float, float) | Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Scales the local geometric transform by the specified amounts in the specified order. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform/#translatetransform)(float, float) | Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Translates the local geometric transform by the specified dimensions in the specified order. |

### See Also

* class [Brush](../../aspose.imaging/brush/)
* namespace [Aspose.Imaging.Brushes](../../aspose.imaging.brushes/)
* assembly [Aspose.Imaging](../../)


