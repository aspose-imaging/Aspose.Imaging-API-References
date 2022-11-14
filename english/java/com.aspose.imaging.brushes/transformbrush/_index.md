---
title: TransformBrush
second_title: Aspose.Imaging for Java API Reference
description: A Brush with transform capabilities.
type: docs
weight: 19
url: /java/com.aspose.imaging.brushes/transformbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public abstract class TransformBrush extends Brush
```

A `Brush` with transform capabilities.
## Constructors

| Constructor | Description |
| --- | --- |
| [TransformBrush()](#TransformBrush--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getWrapMode()](#getWrapMode--) | Gets or sets a `Aspose.Imaging.WrapMode` enumeration that indicates the wrap mode for this `TransformBrush`. |
| [setWrapMode(int value)](#setWrapMode-int-) | Gets or sets a `Aspose.Imaging.WrapMode` enumeration that indicates the wrap mode for this `TransformBrush`. |
| [getTransform()](#getTransform--) | Gets or sets a copy `Aspose.Imaging.Matrix` that defines a local geometric transform for this `TransformBrush`. |
| [setTransform(Matrix value)](#setTransform-com.aspose.imaging.Matrix-) | Gets or sets a copy `Aspose.Imaging.Matrix` that defines a local geometric transform for this `TransformBrush`. |
| [isTransformChanged()](#isTransformChanged--) | Gets a value indicating whether transformations were changed in some way. |
| [resetTransform()](#resetTransform--) | Resets the `TransformBrush.Transform` property to identity. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | Multiplies the `Aspose.Imaging.Matrix` that represents the local geometric transform of this `LinearGradientBrush` by the specified `Aspose.Imaging.Matrix` by prepending the specified `Aspose.Imaging.Matrix`. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | Multiplies the `Aspose.Imaging.Matrix` that represents the local geometric transform of this `LinearGradientBrush` by the specified `Aspose.Imaging.Matrix` in the specified order. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Translates the local geometric transform by the specified dimensions. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Translates the local geometric transform by the specified dimensions in the specified order. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Scales the local geometric transform by the specified amounts. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Scales the local geometric transform by the specified amounts in the specified order. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Rotates the local geometric transform by the specified amount. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Rotates the local geometric transform by the specified amount in the specified order. |
### TransformBrush() {#TransformBrush--}
```
public TransformBrush()
```


### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Gets or sets a `Aspose.Imaging.WrapMode` enumeration that indicates the wrap mode for this `TransformBrush`.

**Returns:**
int - A `Aspose.Imaging.WrapMode` that specifies how fills drawn with this `TransformBrush` are tiled.
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Gets or sets a `Aspose.Imaging.WrapMode` enumeration that indicates the wrap mode for this `TransformBrush`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Gets or sets a copy `Aspose.Imaging.Matrix` that defines a local geometric transform for this `TransformBrush`.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - A copy of the `Aspose.Imaging.Matrix` that defines a geometric transform that applies only to fills drawn with this `TransformBrush`.
### setTransform(Matrix value) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix value)
```


Gets or sets a copy `Aspose.Imaging.Matrix` that defines a local geometric transform for this `TransformBrush`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### isTransformChanged() {#isTransformChanged--}
```
public boolean isTransformChanged()
```


Gets a value indicating whether transformations were changed in some way. For example setting the transformation matrix or calling any of the methods altering the transformation matrix. The property is introduced for backward compatibility with GDI+.

Value: `True` if transformation was changed; otherwise, `false`.

**Returns:**
boolean
### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Resets the `TransformBrush.Transform` property to identity.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplies the `Aspose.Imaging.Matrix` that represents the local geometric transform of this `LinearGradientBrush` by the specified `Aspose.Imaging.Matrix` by prepending the specified `Aspose.Imaging.Matrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | The `Aspose.Imaging.Matrix` by which to multiply the geometric transform. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplies the `Aspose.Imaging.Matrix` that represents the local geometric transform of this `LinearGradientBrush` by the specified `Aspose.Imaging.Matrix` in the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | The `Aspose.Imaging.Matrix` by which to multiply the geometric transform. |
| order | int | A `Aspose.Imaging.MatrixOrder` that specifies in which order to multiply the two matrices. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Translates the local geometric transform by the specified dimensions in the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |
| order | int | The order (prepend or append) in which to apply the translation. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sx | float | The amount by which to scale the transform in the x-axis direction. |
| sy | float | The amount by which to scale the transform in the y-axis direction. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Scales the local geometric transform by the specified amounts in the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sx | float | The amount by which to scale the transform in the x-axis direction. |
| sy | float | The amount by which to scale the transform in the y-axis direction. |
| order | int | A `Aspose.Imaging.MatrixOrder` that specifies whether to append or prepend the scaling matrix. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | The angle of rotation. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Rotates the local geometric transform by the specified amount in the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | The angle of rotation. |
| order | int | A `Aspose.Imaging.MatrixOrder` that specifies whether to append or prepend the rotation matrix. |

