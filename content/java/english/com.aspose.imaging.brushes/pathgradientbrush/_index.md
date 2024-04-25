---
title: PathGradientBrush
second_title: Aspose.Imaging for Java API Reference
description: Encapsulates a Aspose.Imaging.Brush object with a gradient.
type: docs
weight: 14
url: /com.aspose.imaging.brushes/pathgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.PathGradientBrushBase](../../com.aspose.imaging.brushes/pathgradientbrushbase)
```
public final class PathGradientBrush extends PathGradientBrushBase
```

Encapsulates a `Aspose.Imaging.Brush` object with a gradient. This class cannot be inherited.

The center color is white by default. A user can changed this value at any time later.

The surround colors array is initialized by single element containing white color by default. The surround colors may be changed later, however at least single element is required when setting up the surround colors.

See the `Blend` for more details about its initialization.
## Constructors

| Constructor | Description |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.imaging.PointF---) | Initializes a new instance of the `PathGradientBrush` class with the specified points. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.imaging.PointF---int-) | Initializes a new instance of the `PathGradientBrush` class with the specified points and wrap mode. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.imaging.Point---) | Initializes a new instance of the `PathGradientBrush` class with the specified points. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.imaging.Point---int-) | Initializes a new instance of the `PathGradientBrush` class with the specified points and wrap mode. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.imaging.GraphicsPath-) | Initializes a new instance of the `PathGradientBrush` class with the specified path. |
## Methods

| Method | Description |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Gets a `com.aspose.imaging.ColorBlend` that defines a multicolor linear gradient. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Sets a `com.aspose.imaging.ColorBlend` that defines a multicolor linear gradient. |
| [getCenterColor()](#getCenterColor--) | Gets the color at the center of the path gradient. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.imaging.Color-) | Sets the color at the center of the path gradient. |
| [getSurroundColors()](#getSurroundColors--) | Gets an array of colors that correspond to the points in the path this `PathGradientBrush` fills. |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.imaging.Color---) | Sets an array of colors that correspond to the points in the path this `PathGradientBrush` fills. |
| [getBlend()](#getBlend--) | Gets a `Aspose.Imaging.Blend` that specifies positions and factors that define a custom falloff for the gradient. |
| [setBlend(Blend value)](#setBlend-com.aspose.imaging.Blend-) | Sets a `Aspose.Imaging.Blend` that specifies positions and factors that define a custom falloff for the gradient. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Creates a gradient brush that changes color starting from the center of the path outward to the path's boundary. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Creates a gradient brush that changes color starting from the center of the path outward to the path's boundary. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Creates a gradient with a center color and a linear falloff to one surrounding color. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Creates a gradient with a center color and a linear falloff to each surrounding color. |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.imaging.PointF---}
```
public PathGradientBrush(PointF[] points)
```


Initializes a new instance of the `PathGradientBrush` class with the specified points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | An array of `Aspose.Imaging.PointF` structures that represents the points that make up the vertices of the path. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.imaging.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


Initializes a new instance of the `PathGradientBrush` class with the specified points and wrap mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | An array of `Aspose.Imaging.PointF` structures that represents the points that make up the vertices of the path. |
| wrapMode | int | A `Aspose.Imaging.WrapMode` that specifies how fills drawn with this `PathGradientBrush` are tiled. |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.imaging.Point---}
```
public PathGradientBrush(Point[] points)
```


Initializes a new instance of the `PathGradientBrush` class with the specified points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | An array of `Aspose.Imaging.Point` structures that represents the points that make up the vertices of the path. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.imaging.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


Initializes a new instance of the `PathGradientBrush` class with the specified points and wrap mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | An array of `Aspose.Imaging.Point` structures that represents the points that make up the vertices of the path. |
| wrapMode | int | A `Aspose.Imaging.WrapMode` that specifies how fills drawn with this `PathGradientBrush` are tiled. |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.imaging.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


Initializes a new instance of the `PathGradientBrush` class with the specified path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | The `GraphicsPath` that defines the area filled by this `PathGradientBrush`. |

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Gets a `com.aspose.imaging.ColorBlend` that defines a multicolor linear gradient.

**Returns:**
[ColorBlend](../../com.aspose.imaging/colorblend) - A `com.aspose.imaging.ColorBlend` that defines a multicolor linear gradient.
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.imaging.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Sets a `com.aspose.imaging.ColorBlend` that defines a multicolor linear gradient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.imaging/colorblend) | A `com.aspose.imaging.ColorBlend` that defines a multicolor linear gradient. |

### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


Gets the color at the center of the path gradient.

**Returns:**
[Color](../../com.aspose.imaging/color) - A `com.aspose.imaging.Color` that represents the color at the center of the path gradient.
### setCenterColor(Color value) {#setCenterColor-com.aspose.imaging.Color-}
```
public void setCenterColor(Color value)
```


Sets the color at the center of the path gradient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | A `com.aspose.imaging.Color` that represents the color at the center of the path gradient. |

### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


Gets an array of colors that correspond to the points in the path this `PathGradientBrush` fills.

**Returns:**
com.aspose.imaging.Color[] - An array of `com.aspose.imaging.Color` structures that represents the colors associated with each point in the path this `PathGradientBrush` fills.
### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.imaging.Color---}
```
public void setSurroundColors(Color[] value)
```


Sets an array of colors that correspond to the points in the path this `PathGradientBrush` fills.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.imaging/color) | An array of `com.aspose.imaging.Color` structures that represents the colors associated with each point in the path this `PathGradientBrush` fills. |

### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Gets a `Aspose.Imaging.Blend` that specifies positions and factors that define a custom falloff for the gradient.

**Returns:**
[Blend](../../com.aspose.imaging/blend) - A `Aspose.Imaging.Blend` that represents a custom falloff for the gradient.
### setBlend(Blend value) {#setBlend-com.aspose.imaging.Blend-}
```
public void setBlend(Blend value)
```


Sets a `Aspose.Imaging.Blend` that specifies positions and factors that define a custom falloff for the gradient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Blend](../../com.aspose.imaging/blend) | A `Aspose.Imaging.Blend` that represents a custom falloff for the gradient. |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Creates a gradient brush that changes color starting from the center of the path outward to the path's boundary. The transition from one color to another is based on a bell-shaped curve.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| focus | float | A value from 0 through 1 that specifies where, along any radial from the center of the path to the path's boundary, the center color will be at its highest intensity. A value of 1 (the default) places the highest intensity at the center of the path. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Creates a gradient brush that changes color starting from the center of the path outward to the path's boundary. The transition from one color to another is based on a bell-shaped curve.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| focus | float | A value from 0 through 1 that specifies where, along any radial from the center of the path to the path's boundary, the center color will be at its highest intensity. A value of 1 (the default) places the highest intensity at the center of the path. |
| scale | float | A value from 0 through 1 that specifies the maximum intensity of the center color that gets blended with the boundary color. A value of 1 causes the highest possible intensity of the center color, and it is the default value. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Creates a gradient with a center color and a linear falloff to one surrounding color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| focus | float | A value from 0 through 1 that specifies where, along any radial from the center of the path to the path's boundary, the center color will be at its highest intensity. A value of 1 (the default) places the highest intensity at the center of the path. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Creates a gradient with a center color and a linear falloff to each surrounding color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| focus | float | A value from 0 through 1 that specifies where, along any radial from the center of the path to the path's boundary, the center color will be at its highest intensity. A value of 1 (the default) places the highest intensity at the center of the path. |
| scale | float | A value from 0 through 1 that specifies the maximum intensity of the center color that gets blended with the boundary color. A value of 1 causes the highest possible intensity of the center color, and it is the default value. |

