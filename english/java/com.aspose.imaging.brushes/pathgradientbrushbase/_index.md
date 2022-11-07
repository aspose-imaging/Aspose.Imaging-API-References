---
title: PathGradientBrushBase
second_title: Aspose.Imaging for Java API Reference
description: Represents a Brush with base path gradient functionality.
type: docs
weight: 15
url: /java/com.aspose.imaging.brushes/pathgradientbrushbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush)
```
public abstract class PathGradientBrushBase extends TransformBrush
```

Represents a `Brush` with base path gradient functionality.

Note that when creating the `PathGradientBrushBase` class it should be initialized with 2 points at least. The internal path created will always be a closed figure, the last point connects the first point. That shape is filled with this `PathGradientBrushBase`. The GDI+ implementation throws an `OutOfMemoryError` when passing in empty arrays or points set having the same coordinates. The `PathGradientBrushBase` throws an exception when points array contain less than 2 points, the `ArgumentException` is thrown rather than `OutOfMemoryError` when points array is unacceptable. The center point is calculated as a center of mass for the passed in points by default. A user can change this point later. The focus scales is an empty point (0.0, 0.0) by default.
## Methods

| Method | Description |
| --- | --- |
| [getPathPoints()](#getPathPoints--) | Gets the path points this brush was build upon. |
| [getGraphicsPath()](#getGraphicsPath--) | Gets the graphics path this brush was build upon. |
| [getCenterPoint()](#getCenterPoint--) | Gets or sets the center point of the path gradient. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.imaging.PointF-) | Gets or sets the center point of the path gradient. |
| [getFocusScales()](#getFocusScales--) | Gets the focus point for the gradient falloff. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.imaging.PointF-) | Gets or sets the focus point for the gradient falloff. |
### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


Gets the path points this brush was build upon.

**Returns:**
com.aspose.imaging.PointF[] - The path points.
### getGraphicsPath() {#getGraphicsPath--}
```
public GraphicsPath getGraphicsPath()
```


Gets the graphics path this brush was build upon.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The graphics path.
### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Gets or sets the center point of the path gradient.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `Aspose.Imaging.PointF` that represents the center point of the path gradient.
### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.imaging.PointF-}
```
public void setCenterPoint(PointF value)
```


Gets or sets the center point of the path gradient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | A `Aspose.Imaging.PointF` that represents the center point of the path gradient. |

### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Gets the focus point for the gradient falloff.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `Aspose.Imaging.PointF` that represents the focus point for the gradient falloff.
### setFocusScales(PointF value) {#setFocusScales-com.aspose.imaging.PointF-}
```
public void setFocusScales(PointF value)
```


Gets or sets the focus point for the gradient falloff.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | A `Aspose.Imaging.PointF` that represents the focus point for the gradient falloff. |

