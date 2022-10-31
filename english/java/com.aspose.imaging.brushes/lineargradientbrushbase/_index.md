---
title: LinearGradientBrushBase
second_title: Aspose.Imaging for Java API Reference
description: Represents a KKKCODEB BrushKKKCODEE with gradient capabilities and appropriate properties.
type: docs
weight: 12
url: /java/com.aspose.imaging.brushes/lineargradientbrushbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush)
```
public abstract class LinearGradientBrushBase extends TransformBrush
```

Represents a `Brush` with gradient capabilities and appropriate properties.
## Methods

| Method | Description |
| --- | --- |
| [getRectangle()](#getRectangle--) | Gets a rectangular region that defines the starting and ending points of the gradient. |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.imaging.RectangleF-) | Sets a rectangular region that defines the starting and ending points of the gradient. |
| [getAngle()](#getAngle--) | Gets the gradient angle. |
| [setAngle(float value)](#setAngle-float-) | Sets the gradient angle. |
| [isAngleScalable()](#isAngleScalable--) | Gets a value indicating whether `LinearGradientBrushBase.Angle` is changed during transformations with this `LinearGradientBrushBase`. |
| [setAngleScalable(boolean value)](#setAngleScalable-boolean-) | Sets a value indicating whether `LinearGradientBrushBase.Angle` is changed during transformations with this `LinearGradientBrushBase`. |
| [getGammaCorrection()](#getGammaCorrection--) | Gets a value indicating whether gamma correction is enabled for this `LinearGradientBrushBase`. |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Sets a value indicating whether gamma correction is enabled for this `LinearGradientBrushBase`. |
### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Gets a rectangular region that defines the starting and ending points of the gradient.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A `com.aspose.imaging.RectangleF` structure that specifies the starting and ending points of the gradient.
### setRectangle(RectangleF value) {#setRectangle-com.aspose.imaging.RectangleF-}
```
public void setRectangle(RectangleF value)
```


Sets a rectangular region that defines the starting and ending points of the gradient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | A `com.aspose.imaging.RectangleF` structure that specifies the starting and ending points of the gradient. |

### getAngle() {#getAngle--}
```
public float getAngle()
```


Gets the gradient angle.

**Returns:**
float - The gradient angle.
### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


Sets the gradient angle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The gradient angle. |

### isAngleScalable() {#isAngleScalable--}
```
public boolean isAngleScalable()
```


Gets a value indicating whether `LinearGradientBrushBase.Angle` is changed during transformations with this `LinearGradientBrushBase`.

**Returns:**
boolean - `true` if `LinearGradientBrushBase.Angle` is changed during transformations with this `LinearGradientBrushBase`; otherwise, `false`.
### setAngleScalable(boolean value) {#setAngleScalable-boolean-}
```
public void setAngleScalable(boolean value)
```


Sets a value indicating whether `LinearGradientBrushBase.Angle` is changed during transformations with this `LinearGradientBrushBase`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | `true` if `LinearGradientBrushBase.Angle` is changed during transformations with this `LinearGradientBrushBase`; otherwise, `false`. |

### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Gets a value indicating whether gamma correction is enabled for this `LinearGradientBrushBase`.

**Returns:**
boolean - The value is true if gamma correction is enabled for this `LinearGradientBrushBase`; otherwise, false.
### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Sets a value indicating whether gamma correction is enabled for this `LinearGradientBrushBase`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | The value is true if gamma correction is enabled for this `LinearGradientBrushBase`; otherwise, false. |

