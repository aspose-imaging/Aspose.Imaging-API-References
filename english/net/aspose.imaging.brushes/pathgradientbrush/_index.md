---
title: PathGradientBrush
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 180
url: /net/aspose.imaging.brushes/pathgradientbrush/
---
## PathGradientBrush class

Encapsulates a [`Brush`](../../aspose.imaging/brush) object with a gradient. This class cannot be inherited.

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## Constructors

| Name | Description |
| --- | --- |
| [PathGradientBrush](pathgradientbrush)(GraphicsPath) | Initializes a new instance of the [`PathGradientBrush`](../pathgradientbrush) class with the specified path. |
| [PathGradientBrush](pathgradientbrush)(PointF[]) | Initializes a new instance of the [`PathGradientBrush`](../pathgradientbrush) class with the specified points. |
| [PathGradientBrush](pathgradientbrush)(Point[]) | Initializes a new instance of the [`PathGradientBrush`](../pathgradientbrush) class with the specified points. |
| [PathGradientBrush](pathgradientbrush)(PointF[], WrapMode) | Initializes a new instance of the [`PathGradientBrush`](../pathgradientbrush) class with the specified points and wrap mode. |
| [PathGradientBrush](pathgradientbrush)(Point[], WrapMode) | Initializes a new instance of the [`PathGradientBrush`](../pathgradientbrush) class with the specified points and wrap mode. |

## Properties

| Name | Description |
| --- | --- |
| [Blend](../../aspose.imaging.brushes/pathgradientbrush/blend) { get; set; } | Gets or sets a [`Blend`](../../aspose.imaging/blend) that specifies positions and factors that define a custom falloff for the gradient. |
| [CenterColor](../../aspose.imaging.brushes/pathgradientbrush/centercolor) { get; set; } | Gets or sets the color at the center of the path gradient. |
| [CenterPoint](../../aspose.imaging.brushes/pathgradientbrushbase/centerpoint) { get; set; } | Gets or sets the center point of the path gradient. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Gets a value indicating whether this instance is disposed. |
| [FocusScales](../../aspose.imaging.brushes/pathgradientbrushbase/focusscales) { get; set; } | Gets or sets the focus point for the gradient falloff. |
| [GraphicsPath](../../aspose.imaging.brushes/pathgradientbrushbase/graphicspath) { get; } | Gets the graphics path this brush was build upon. |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Gets a value indicating whether transformations were changed in some way. For example setting the transformation matrix or calling any of the methods altering the transformation matrix. The property is introduced for backward compatibility with GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Gets or sets the brush opacity. The value should be between 0 and 1. Value of 0 means that brush is fully visible, value of 1 means the brush is fully opaque. |
| [PathPoints](../../aspose.imaging.brushes/pathgradientbrushbase/pathpoints) { get; } | Gets the path points this brush was build upon. |
| [SurroundColors](../../aspose.imaging.brushes/pathgradientbrush/surroundcolors) { get; set; } | Gets or sets an array of colors that correspond to the points in the path this [`PathGradientBrush`](../pathgradientbrush) fills. |
| [Transform](../../aspose.imaging.brushes/transformbrush/transform) { get; set; } | Gets or sets a copy [`Matrix`](../../aspose.imaging/matrix) that defines a local geometric transform for this [`TransformBrush`](../transformbrush). |
| [WrapMode](../../aspose.imaging.brushes/transformbrush/wrapmode) { get; set; } | Gets or sets a [`WrapMode`](../../aspose.imaging/wrapmode) enumeration that indicates the wrap mode for this [`TransformBrush`](../transformbrush). |

## Methods

| Name | Description |
| --- | --- |
| virtual [DeepClone](../../aspose.imaging/brush/deepclone)() | Creates a new deep clone of the current [`Brush`](../../aspose.imaging/brush). |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Disposes the current instance. |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform)(Matrix) | Multiplies the [`Matrix`](../../aspose.imaging/matrix) that represents the local geometric transform of this [`LinearGradientBrush`](../lineargradientbrush) by the specified [`Matrix`](../../aspose.imaging/matrix) by prepending the specified [`Matrix`](../../aspose.imaging/matrix). |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform)(Matrix, MatrixOrder) | Multiplies the [`Matrix`](../../aspose.imaging/matrix) that represents the local geometric transform of this [`LinearGradientBrush`](../lineargradientbrush) by the specified [`Matrix`](../../aspose.imaging/matrix) in the specified order. |
| [ResetTransform](../../aspose.imaging.brushes/transformbrush/resettransform)() | Resets the [`Transform`](../transformbrush/transform) property to identity. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform)(float) | Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform)(float, MatrixOrder) | Rotates the local geometric transform by the specified amount in the specified order. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform)(float, float) | Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform)(float, float, MatrixOrder) | Scales the local geometric transform by the specified amounts in the specified order. |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/pathgradientbrush/setblendtriangularshape)(float) | Creates a gradient with a center color and a linear falloff to one surrounding color. |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/pathgradientbrush/setblendtriangularshape)(float, float) | Creates a gradient with a center color and a linear falloff to each surrounding color. |
| [SetSigmaBellShape](../../aspose.imaging.brushes/pathgradientbrush/setsigmabellshape)(float) | Creates a gradient brush that changes color starting from the center of the path outward to the path's boundary. The transition from one color to another is based on a bell-shaped curve. |
| [SetSigmaBellShape](../../aspose.imaging.brushes/pathgradientbrush/setsigmabellshape)(float, float) | Creates a gradient brush that changes color starting from the center of the path outward to the path's boundary. The transition from one color to another is based on a bell-shaped curve. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float) | Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | Translates the local geometric transform by the specified dimensions in the specified order. |

### Remarks

The center color is white by default. A user can changed this value at any time later.

The surround colors array is initialized by single element containing white color by default. The surround colors may be changed later, however at least single element is required when setting up the surround colors.

See the [`Blend`](./blend) for more details about its initialization.

### See Also

* class [PathGradientBrushBase](../pathgradientbrushbase)
* namespace [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
