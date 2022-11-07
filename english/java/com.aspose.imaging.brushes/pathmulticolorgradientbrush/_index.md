---
title: PathMulticolorGradientBrush
second_title: Aspose.Imaging for Java API Reference
description: Encapsulates a Aspose.Imaging.Brush object with a gradient.
type: docs
weight: 16
url: /java/com.aspose.imaging.brushes/pathmulticolorgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.PathGradientBrushBase](../../com.aspose.imaging.brushes/pathgradientbrushbase)
```
public final class PathMulticolorGradientBrush extends PathGradientBrushBase
```

Encapsulates a `Aspose.Imaging.Brush` object with a gradient. This class cannot be inherited.
## Constructors

| Constructor | Description |
| --- | --- |
| [PathMulticolorGradientBrush(PointF[] points)](#PathMulticolorGradientBrush-com.aspose.imaging.PointF---) | Initializes a new instance of the `PathMulticolorGradientBrush` class with the specified points. |
| [PathMulticolorGradientBrush(PointF[] points, int wrapMode)](#PathMulticolorGradientBrush-com.aspose.imaging.PointF---int-) | Initializes a new instance of the `PathMulticolorGradientBrush` class with the specified points and wrap mode. |
| [PathMulticolorGradientBrush(Point[] points)](#PathMulticolorGradientBrush-com.aspose.imaging.Point---) | Initializes a new instance of the `PathMulticolorGradientBrush` class with the specified points. |
| [PathMulticolorGradientBrush(Point[] points, int wrapMode)](#PathMulticolorGradientBrush-com.aspose.imaging.Point---int-) | Initializes a new instance of the `PathMulticolorGradientBrush` class with the specified points and wrap mode. |
| [PathMulticolorGradientBrush(GraphicsPath path)](#PathMulticolorGradientBrush-com.aspose.imaging.GraphicsPath-) | Initializes a new instance of the `PathMulticolorGradientBrush` class with the specified path. |
## Methods

| Method | Description |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Gets or sets a `com.aspose.imaging.ColorBlend` that defines a multicolor linear gradient. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Gets or sets a `com.aspose.imaging.ColorBlend` that defines a multicolor linear gradient. |
### PathMulticolorGradientBrush(PointF[] points) {#PathMulticolorGradientBrush-com.aspose.imaging.PointF---}
```
public PathMulticolorGradientBrush(PointF[] points)
```


Initializes a new instance of the `PathMulticolorGradientBrush` class with the specified points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | An array of `Aspose.Imaging.PointF` structures that represents the points that make up the vertices of the path. |

### PathMulticolorGradientBrush(PointF[] points, int wrapMode) {#PathMulticolorGradientBrush-com.aspose.imaging.PointF---int-}
```
public PathMulticolorGradientBrush(PointF[] points, int wrapMode)
```


Initializes a new instance of the `PathMulticolorGradientBrush` class with the specified points and wrap mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | An array of `Aspose.Imaging.PointF` structures that represents the points that make up the vertices of the path. |
| wrapMode | int | A `Aspose.Imaging.WrapMode` that specifies how fills drawn with this `PathMulticolorGradientBrush` are tiled. |

### PathMulticolorGradientBrush(Point[] points) {#PathMulticolorGradientBrush-com.aspose.imaging.Point---}
```
public PathMulticolorGradientBrush(Point[] points)
```


Initializes a new instance of the `PathMulticolorGradientBrush` class with the specified points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | An array of `Aspose.Imaging.Point` structures that represents the points that make up the vertices of the path. |

### PathMulticolorGradientBrush(Point[] points, int wrapMode) {#PathMulticolorGradientBrush-com.aspose.imaging.Point---int-}
```
public PathMulticolorGradientBrush(Point[] points, int wrapMode)
```


Initializes a new instance of the `PathMulticolorGradientBrush` class with the specified points and wrap mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | An array of `Aspose.Imaging.Point` structures that represents the points that make up the vertices of the path. |
| wrapMode | int | A `Aspose.Imaging.WrapMode` that specifies how fills drawn with this `PathMulticolorGradientBrush` are tiled. |

### PathMulticolorGradientBrush(GraphicsPath path) {#PathMulticolorGradientBrush-com.aspose.imaging.GraphicsPath-}
```
public PathMulticolorGradientBrush(GraphicsPath path)
```


Initializes a new instance of the `PathMulticolorGradientBrush` class with the specified path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | The `GraphicsPath` that defines the area filled by this `PathMulticolorGradientBrush`. |

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Gets or sets a `com.aspose.imaging.ColorBlend` that defines a multicolor linear gradient.

Value: A `com.aspose.imaging.ColorBlend` that defines a multicolor linear gradient.

**Returns:**
[ColorBlend](../../com.aspose.imaging/colorblend)
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.imaging.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Gets or sets a `com.aspose.imaging.ColorBlend` that defines a multicolor linear gradient.

Value: A `com.aspose.imaging.ColorBlend` that defines a multicolor linear gradient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.imaging/colorblend) |  |

