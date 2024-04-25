---
title: TextureBrush
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 220
url: /aspose.imaging.brushes/texturebrush/
---
## TextureBrush class

Each property of the [`TextureBrush`](../texturebrush) class is a [`Brush`](../../aspose.imaging/brush) object that uses an image to fill the interior of a shape. This class cannot be inherited.

```csharp
public sealed class TextureBrush : TransformBrush
```

## Constructors

| Name | Description |
| --- | --- |
| [TextureBrush](texturebrush)(Image) | Initializes a new instance of the [`TextureBrush`](../texturebrush) class that uses the specified image. |
| [TextureBrush](texturebrush)(Image, Rectangle) | Initializes a new instance of the [`TextureBrush`](../texturebrush) class that uses the specified image and bounding rectangle. |
| [TextureBrush](texturebrush)(Image, RectangleF) | Initializes a new instance of the [`TextureBrush`](../texturebrush) class that uses the specified image and bounding rectangle. |
| [TextureBrush](texturebrush)(Image, WrapMode) | Initializes a new instance of the [`TextureBrush`](../texturebrush) class that uses the specified image and wrap mode. |
| [TextureBrush](texturebrush)(Image, Rectangle, ImageAttributes) | Initializes a new instance of the [`TextureBrush`](../texturebrush) class that uses the specified image, bounding rectangle, and image attributes. |
| [TextureBrush](texturebrush)(Image, RectangleF, ImageAttributes) | Initializes a new instance of the [`TextureBrush`](../texturebrush) class that uses the specified image, bounding rectangle, and image attributes. |
| [TextureBrush](texturebrush)(Image, WrapMode, Rectangle) | Initializes a new instance of the [`TextureBrush`](../texturebrush) class that uses the specified image, wrap mode, and bounding rectangle. |
| [TextureBrush](texturebrush)(Image, WrapMode, RectangleF) | Initializes a new instance of the [`TextureBrush`](../texturebrush) class that uses the specified image, wrap mode, and bounding rectangle. |

## Properties

| Name | Description |
| --- | --- |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Gets a value indicating whether this instance is disposed. |
| [Image](../../aspose.imaging.brushes/texturebrush/image) { get; } | Gets the [`Image`](../../aspose.imaging/image) object associated with this [`TextureBrush`](../texturebrush) object. |
| [ImageAttributes](../../aspose.imaging.brushes/texturebrush/imageattributes) { get; } | Gets the [`ImageAttributes`](./imageattributes) associated with this [`TextureBrush`](../texturebrush). |
| [ImageRectangle](../../aspose.imaging.brushes/texturebrush/imagerectangle) { get; } | Gets the [`Rectangle`](../../aspose.imaging/rectangle) associated with this [`TextureBrush`](../texturebrush). |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Gets a value indicating whether transformations were changed in some way. For example setting the transformation matrix or calling any of the methods altering the transformation matrix. The property is introduced for backward compatibility with GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Gets or sets the brush opacity. The value should be between 0 and 1. Value of 0 means that brush is fully visible, value of 1 means the brush is fully opaque. |
| [Transform](../../aspose.imaging.brushes/transformbrush/transform) { get; set; } | Gets or sets a copy [`Matrix`](../../aspose.imaging/matrix) that defines a local geometric transform for this [`TransformBrush`](../transformbrush). |
| [WrapMode](../../aspose.imaging.brushes/transformbrush/wrapmode) { get; set; } | Gets or sets a [`WrapMode`](../../aspose.imaging/wrapmode) enumeration that indicates the wrap mode for this [`TransformBrush`](../transformbrush). |

## Methods

| Name | Description |
| --- | --- |
| virtual [DeepClone](../../aspose.imaging/brush/deepclone)() | Creates a new deep clone of the current [`Brush`](../../aspose.imaging/brush). |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Disposes the current instance. |
| override [Equals](../../aspose.imaging/brush/equals)(object) | Check if objects are equal. |
| override [GetHashCode](../../aspose.imaging/brush/gethashcode)() | Get hash code of the current object. |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform)(Matrix) | Multiplies the [`Matrix`](../../aspose.imaging/matrix) that represents the local geometric transform of this [`LinearGradientBrush`](../lineargradientbrush) by the specified [`Matrix`](../../aspose.imaging/matrix) by prepending the specified [`Matrix`](../../aspose.imaging/matrix). |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform)(Matrix, MatrixOrder) | Multiplies the [`Matrix`](../../aspose.imaging/matrix) that represents the local geometric transform of this [`LinearGradientBrush`](../lineargradientbrush) by the specified [`Matrix`](../../aspose.imaging/matrix) in the specified order. |
| [ResetTransform](../../aspose.imaging.brushes/transformbrush/resettransform)() | Resets the [`Transform`](../transformbrush/transform) property to identity. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform)(float) | Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform)(float, MatrixOrder) | Rotates the local geometric transform by the specified amount in the specified order. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform)(float, float) | Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform)(float, float, MatrixOrder) | Scales the local geometric transform by the specified amounts in the specified order. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float) | Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | Translates the local geometric transform by the specified dimensions in the specified order. |

### See Also

* class [TransformBrush](../transformbrush)
* namespace [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
