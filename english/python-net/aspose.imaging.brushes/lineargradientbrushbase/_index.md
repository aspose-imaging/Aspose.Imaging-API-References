---
title: LinearGradientBrushBase Class
type: docs
weight: 30
url: /python-net/aspose.imaging.brushes/lineargradientbrushbase/
---

Represents a [Brush](/imaging/python-net/aspose.imaging/brush/) with gradient capabilities and appropriate properties.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.LinearGradientBrushBase

**Inheritance:** TransformBrush

**Aspose.Imaging Version:** 23.6

The LinearGradientBrushBase type exposes the following members:
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| opacity | float | r/w | Gets or sets the brush opacity. The value should be between 0 and 1. Value of 0 means that brush is fully visible, value of 1 means the brush is fully opaque. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode) | r/w | Gets or sets a [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) enumeration that indicates the wrap mode for this [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix) | r/w | Gets or sets a copy [Matrix](/imaging/python-net/aspose.imaging/matrix/) that defines a local geometric transform for this [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| is_transform_changed | bool | r | Gets a value indicating whether transformations were changed in some way. For example setting the transformation matrix or<br/>            calling any of the methods altering the transformation matrix. The property is introduced for backward compatibility with GDI+. |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | r/w | Gets or sets a rectangular region that defines the starting and ending points of the gradient. |
| angle | float | r/w | Gets or sets the gradient angle. |
| is_angle_scalable | bool | r/w | Gets or sets a value indicating whether [angle](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/) is changed during trasnformations with this [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/). |
| gamma_correction | bool | r/w | Gets or sets a value indicating whether gamma correction is enabled for this [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [multiply_transform(matrix)](#multiply_transform_matrix_0) | Multiplies the [Matrix](/imaging/python-net/aspose.imaging/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/) by prepending the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_1) | Multiplies the [Matrix](/imaging/python-net/aspose.imaging/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/) in the specified order. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_2) | Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_3) | Translates the local geometric transform by the specified dimensions in the specified order. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_4) | Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_5) | Scales the local geometric transform by the specified amounts in the specified order. |
| [rotate_transform(angle)](#rotate_transform_angle_6) | Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_7) | Rotates the local geometric transform by the specified amount in the specified order. |
| [deep_clone()](#deep_clone__8) | Creates a new deep clone of the current [Brush](/imaging/python-net/aspose.imaging/brush/). |
| reset_transform() | Resets the [transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) property to identity. |

### multiply_transform(matrix) {#multiply_transform_matrix_0}


```
 multiply_transform(matrix) 
```

Multiplies the [Matrix](/imaging/python-net/aspose.imaging/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/) by prepending the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix) | The [Matrix](/imaging/python-net/aspose.imaging/matrix/) by which to multiply the geometric transform. |

### multiply_transform(matrix, order) {#multiply_transform_matrix_order_1}


```
 multiply_transform(matrix, order) 
```

Multiplies the [Matrix](/imaging/python-net/aspose.imaging/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/) in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix) | The [Matrix](/imaging/python-net/aspose.imaging/matrix/) by which to multiply the geometric transform. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder) | A [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) that specifies in which order to multiply the two matrices. |

### translate_transform(dx, dy) {#translate_transform_dx_dy_2}


```
 translate_transform(dx, dy) 
```

Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |

### translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_3}


```
 translate_transform(dx, dy, order) 
```

Translates the local geometric transform by the specified dimensions in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder) | The order (prepend or append) in which to apply the translation. |

### scale_transform(sx, sy) {#scale_transform_sx_sy_4}


```
 scale_transform(sx, sy) 
```

Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| sx | float | The amount by which to scale the transform in the x-axis direction. |
| sy | float | The amount by which to scale the transform in the y-axis direction. |

### scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_5}


```
 scale_transform(sx, sy, order) 
```

Scales the local geometric transform by the specified amounts in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| sx | float | The amount by which to scale the transform in the x-axis direction. |
| sy | float | The amount by which to scale the transform in the y-axis direction. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder) | A [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) that specifies whether to append or prepend the scaling matrix. |

### rotate_transform(angle) {#rotate_transform_angle_6}


```
 rotate_transform(angle) 
```

Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The angle of rotation. |

### rotate_transform(angle, order) {#rotate_transform_angle_order_7}


```
 rotate_transform(angle, order) 
```

Rotates the local geometric transform by the specified amount in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The angle of rotation. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder) | A [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) that specifies whether to append or prepend the rotation matrix. |

### deep_clone() {#deep_clone__8}


```
 deep_clone() 
```

Creates a new deep clone of the current [Brush](/imaging/python-net/aspose.imaging/brush/).

**Returns**

| Type | Description |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush) | A new [Brush](/imaging/python-net/aspose.imaging/brush/) which is the deep clone of this [Brush](/imaging/python-net/aspose.imaging/brush/) instance. |


