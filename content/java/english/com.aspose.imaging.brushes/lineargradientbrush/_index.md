---
title: LinearGradientBrush
second_title: Aspose.Imaging for Java API Reference
description: Encapsulates a Aspose.Imaging.Brush with a linear gradient.
type: docs
weight: 11
url: /com.aspose.imaging.brushes/lineargradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.LinearGradientBrushBase](../../com.aspose.imaging.brushes/lineargradientbrushbase)
```
public final class LinearGradientBrush extends LinearGradientBrushBase
```

Encapsulates a `Aspose.Imaging.Brush` with a linear gradient. This class cannot be inherited.
## Constructors

| Constructor | Description |
| --- | --- |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-) | Initializes a new instance of the [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) class. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-) | Initializes a new instance of the [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) class. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-) | Initializes a new instance of the [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) class. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-) | Initializes a new instance of the [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) class. |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.Color-com.aspose.imaging.Color-) | Initializes a new instance of the [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) class. |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Color-com.aspose.imaging.Color-) | Initializes a new instance of the [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) class. |
| [LinearGradientBrush()](#LinearGradientBrush--) | Initializes a new instance of the [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) class with default parameters. |
## Methods

| Method | Description |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Gets a `com.aspose.imaging.ColorBlend` that defines a multicolor linear gradient. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Sets a `com.aspose.imaging.ColorBlend` that defines a multicolor linear gradient. |
| [getLinearColors()](#getLinearColors--) | Gets the starting and ending colors of the gradient. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.imaging.Color---) | Sets the starting and ending colors of the gradient. |
| [getStartColor()](#getStartColor--) | Gets the starting gradient color. |
| [setStartColor(Color value)](#setStartColor-com.aspose.imaging.Color-) | Sets the starting gradient color. |
| [getEndColor()](#getEndColor--) | Gets the ending gradient color. |
| [setEndColor(Color value)](#setEndColor-com.aspose.imaging.Color-) | Sets the ending gradient color. |
| [getBlend()](#getBlend--) | Gets a `Aspose.Imaging.Blend` that specifies positions and factors that define a custom falloff for the gradient. |
| [setBlend(Blend value)](#setBlend-com.aspose.imaging.Blend-) | Sets a `Aspose.Imaging.Blend` that specifies positions and factors that define a custom falloff for the gradient. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Creates a gradient falloff based on a bell-shaped curve. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Creates a gradient falloff based on a bell-shaped curve. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Creates a linear gradient with a center color and a linear falloff to a single color on both ends. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Creates a linear gradient with a center color and a linear falloff to a single color on both ends. |
### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Initializes a new instance of the [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | The rectangle. |
| color1 | [Color](../../com.aspose.imaging/color) | The color1. |
| color2 | [Color](../../com.aspose.imaging/color) | The color2. |
| angle | float | The angle. |
| isAngleScalable | boolean | if set to `true` [is angle scalable]. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Initializes a new instance of the [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | The rectangle. |
| color1 | [Color](../../com.aspose.imaging/color) | The color1. |
| color2 | [Color](../../com.aspose.imaging/color) | The color2. |
| angle | float | The angle. |
| isAngleScalable | boolean | if set to `true` [is angle scalable]. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


Initializes a new instance of the [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | The rectangle. |
| color1 | [Color](../../com.aspose.imaging/color) | The color1. |
| color2 | [Color](../../com.aspose.imaging/color) | The color2. |
| angle | float | The angle. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


Initializes a new instance of the [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | The rectangle. |
| color1 | [Color](../../com.aspose.imaging/color) | The color1. |
| color2 | [Color](../../com.aspose.imaging/color) | The color2. |
| angle | float | The angle. |

### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.Color-com.aspose.imaging.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


Initializes a new instance of the [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | The point1. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | The point2. |
| color1 | [Color](../../com.aspose.imaging/color) | The color1. |
| color2 | [Color](../../com.aspose.imaging/color) | The color2. |

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Color-com.aspose.imaging.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


Initializes a new instance of the [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | The point1. |
| point2 | [Point](../../com.aspose.imaging/point) | The point2. |
| color1 | [Color](../../com.aspose.imaging/color) | The color1. |
| color2 | [Color](../../com.aspose.imaging/color) | The color2. |

### LinearGradientBrush() {#LinearGradientBrush--}
```
public LinearGradientBrush()
```


Initializes a new instance of the [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) class with default parameters. The starting color is black, the ending color is white, the angle is 45 degrees and the rectangle is located in (0,0) with size (1,1).

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

### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


Gets the starting and ending colors of the gradient.

**Returns:**
com.aspose.imaging.Color[] - An array of two `Color` structures that represents the starting and ending colors of the gradient.
### setLinearColors(Color[] value) {#setLinearColors-com.aspose.imaging.Color---}
```
public void setLinearColors(Color[] value)
```


Sets the starting and ending colors of the gradient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.imaging/color) | An array of two `Color` structures that represents the starting and ending colors of the gradient. |

### getStartColor() {#getStartColor--}
```
public Color getStartColor()
```


Gets the starting gradient color.

**Returns:**
[Color](../../com.aspose.imaging/color) - The starting gradient color.
### setStartColor(Color value) {#setStartColor-com.aspose.imaging.Color-}
```
public void setStartColor(Color value)
```


Sets the starting gradient color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | The starting gradient color. |

### getEndColor() {#getEndColor--}
```
public Color getEndColor()
```


Gets the ending gradient color.

**Returns:**
[Color](../../com.aspose.imaging/color) - The ending gradient color.
### setEndColor(Color value) {#setEndColor-com.aspose.imaging.Color-}
```
public void setEndColor(Color value)
```


Sets the ending gradient color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | The ending gradient color. |

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


Creates a gradient falloff based on a bell-shaped curve.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| focus | float | A value from 0 through 1 that specifies the center of the gradient (the point where the starting color and ending color are blended equally). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Creates a gradient falloff based on a bell-shaped curve.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| focus | float | A value from 0 through 1 that specifies the center of the gradient (the point where the gradient is composed of only the ending color). |
| scale | float | A value from 0 through 1 that specifies how fast the colors falloff from the `focus`. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Creates a linear gradient with a center color and a linear falloff to a single color on both ends.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| focus | float | A value from 0 through 1 that specifies the center of the gradient (the point where the gradient is composed of only the ending color). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Creates a linear gradient with a center color and a linear falloff to a single color on both ends.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| focus | float | A value from 0 through 1 that specifies the center of the gradient (the point where the gradient is composed of only the ending color). |
| scale | float | A value from 0 through1 that specifies how fast the colors falloff from the starting color to `focus` (ending color) |

