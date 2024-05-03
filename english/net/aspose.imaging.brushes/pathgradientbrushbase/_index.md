---
title: Class PathGradientBrushBase
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.Brushes.PathGradientBrushBase class. Represents a Brush with base path gradient functionality
type: docs
weight: 190
url: /net/aspose.imaging.brushes/pathgradientbrushbase/
---
## PathGradientBrushBase class

Represents a [`Brush`](../../aspose.imaging/brush/) with base path gradient functionality.

```csharp
public abstract class PathGradientBrushBase : TransformBrush
```

## Properties

| Name | Description |
| --- | --- |
| [CenterPoint](../../aspose.imaging.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | Gets or sets the center point of the path gradient. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [FocusScales](../../aspose.imaging.brushes/pathgradientbrushbase/focusscales/) { get; set; } | Gets or sets the focus point for the gradient falloff. |
| [GraphicsPath](../../aspose.imaging.brushes/pathgradientbrushbase/graphicspath/) { get; } | Gets the graphics path this brush was build upon. |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged/) { get; } | Gets a value indicating whether transformations were changed in some way. For example setting the transformation matrix or calling any of the methods altering the transformation matrix. The property is introduced for backward compatibility with GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity/) { get; set; } | Gets or sets the brush opacity. The value should be between 0 and 1. Value of 0 means that brush is fully visible, value of 1 means the brush is fully opaque. |
| [PathPoints](../../aspose.imaging.brushes/pathgradientbrushbase/pathpoints/) { get; } | Gets the path points this brush was build upon. |
| [Transform](../../aspose.imaging.brushes/transformbrush/transform/) { get; set; } | Gets or sets a copy [`Matrix`](../../aspose.imaging/matrix/) that defines a local geometric transform for this [`TransformBrush`](../transformbrush/). |
| [WrapMode](../../aspose.imaging.brushes/transformbrush/wrapmode/) { get; set; } | Gets or sets a [`WrapMode`](../../aspose.imaging/wrapmode/) enumeration that indicates the wrap mode for this [`TransformBrush`](../transformbrush/). |

## Methods

| Name | Description |
| --- | --- |
| virtual [DeepClone](../../aspose.imaging/brush/deepclone/)() | Creates a new deep clone of the current [`Brush`](../../aspose.imaging/brush/). |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | Disposes the current instance. |
| override [Equals](../../aspose.imaging/brush/equals/)(object) | Check if objects are equal. |
| override [GetHashCode](../../aspose.imaging/brush/gethashcode/)() | Get hash code of the current object. |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform/)(Matrix) | Multiplies the [`Matrix`](../../aspose.imaging/matrix/) that represents the local geometric transform of this [`LinearGradientBrush`](../lineargradientbrush/) by the specified [`Matrix`](../../aspose.imaging/matrix/) by prepending the specified [`Matrix`](../../aspose.imaging/matrix/). |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Multiplies the [`Matrix`](../../aspose.imaging/matrix/) that represents the local geometric transform of this [`LinearGradientBrush`](../lineargradientbrush/) by the specified [`Matrix`](../../aspose.imaging/matrix/) in the specified order. |
| [ResetTransform](../../aspose.imaging.brushes/transformbrush/resettransform/)() | Resets the [`Transform`](../transformbrush/transform/) property to identity. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform/)(float) | Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Rotates the local geometric transform by the specified amount in the specified order. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform/)(float, float) | Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Scales the local geometric transform by the specified amounts in the specified order. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform/)(float, float) | Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Translates the local geometric transform by the specified dimensions in the specified order. |

## Remarks

Note that when creating the `PathGradientBrushBase` class it should be initialized with 2 points at least. The internal path created will always be a closed figure, the last point connects the first point. That shape is filled with this `PathGradientBrushBase`. The GDI+ implementation throws an OutOfMemoryException when passing in empty arrays or points set having the same coordinates. The `PathGradientBrushBase` throws an exception when points array contain less than 2 points, the ArgumentException is thrown rather than OutOfMemoryException when points array is unacceptable. The center point is calculated as a center of mass for the passed in points by default. A user can change this point later. The focus scales is an empty point (0.0, 0.0) by default.

### See Also

* class [TransformBrush](../transformbrush/)
* namespace [Aspose.Imaging.Brushes](../../aspose.imaging.brushes/)
* assembly [Aspose.Imaging](../../)


