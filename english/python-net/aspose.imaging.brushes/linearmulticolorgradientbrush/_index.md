---
title: LinearMulticolorGradientBrush Class
type: docs
weight: 40
url: /python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/
---

Represents a [Brush](/imaging/python-net/aspose.imaging/brush/) with linear gradient defined by multiple colors and appropriate positions. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.LinearMulticolorGradientBrush

**Inheritance:** LinearGradientBrushBase

**Aspose.Imaging Version:** 23.6

The LinearMulticolorGradientBrush type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [LinearMulticolorGradientBrush()](#LinearMulticolorGradientBrush__0) | Initializes a new instance of the [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) class with default parameters.<br/>            The starting color is black, the ending color is white, the angle is 45 degrees and the rectangle is located in (0,0) with size (1,1). |
| [LinearMulticolorGradientBrush(point1, point2)](#LinearMulticolorGradientBrush_point1_point2_1) | Initializes a new instance of the LinearMulticolorGradientBrush class |
| [LinearMulticolorGradientBrush(point1, point2)](#LinearMulticolorGradientBrush_point1_point2_2) | Initializes a new instance of the LinearMulticolorGradientBrush class |
| [LinearMulticolorGradientBrush(rect, angle)](#LinearMulticolorGradientBrush_rect_angle_3) | Initializes a new instance of the LinearMulticolorGradientBrush class |
| [LinearMulticolorGradientBrush(rect, angle)](#LinearMulticolorGradientBrush_rect_angle_4) | Initializes a new instance of the LinearMulticolorGradientBrush class |
| [LinearMulticolorGradientBrush(rect, angle, is_angle_scalable)](#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_5) | Initializes a new instance of the LinearMulticolorGradientBrush class |
| [LinearMulticolorGradientBrush(rect, angle, is_angle_scalable)](#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_6) | Initializes a new instance of the LinearMulticolorGradientBrush class |
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
| interpolation_colors | [ColorBlend](/imaging/python-net/aspose.imaging/colorblend) | r/w | Gets or sets a [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) that defines a multicolor linear gradient. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [multiply_transform(matrix)](#multiply_transform_matrix_7) | Multiplies the [Matrix](/imaging/python-net/aspose.imaging/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/) by prepending the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_8) | Multiplies the [Matrix](/imaging/python-net/aspose.imaging/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/) in the specified order. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_9) | Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_10) | Translates the local geometric transform by the specified dimensions in the specified order. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_11) | Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_12) | Scales the local geometric transform by the specified amounts in the specified order. |
| [rotate_transform(angle)](#rotate_transform_angle_13) | Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_14) | Rotates the local geometric transform by the specified amount in the specified order. |
| [deep_clone()](#deep_clone__15) | Creates a new deep clone of the current [Brush](/imaging/python-net/aspose.imaging/brush/). |
| reset_transform() | Resets the [transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) property to identity. |
| [create_with_points(point1, point2)](#create_with_points_point1_point2_16) | Initializes a new instance of the [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) class with the specified points. |
| [create_with_points_f(point1, point2)](#create_with_points_f_point1_point2_17) | Initializes a new instance of the [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) class with the specified points. |
| [create_with_rect(rect, angle)](#create_with_rect_rect_angle_18) | Initializes a new instance of the [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) class based on a rectangle and an orientation angle. |
| [create_with_rect_f(rect, angle)](#create_with_rect_f_rect_angle_19) | Initializes a new instance of the [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) class based on a rectangle and an orientation angle. |
| [create_with_rect_angle_scalable(rect, angle, is_angle_scalable)](#create_with_rect_angle_scalable_rect_angle_is_angle_scalable_20) | Initializes a new instance of the [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) class based on a rectangle and an orientation angle. |
| [create_with_rect_f_angle_scalable(rect, angle, is_angle_scalable)](#create_with_rect_f_angle_scalable_rect_angle_is_angle_scalable_21) | Initializes a new instance of the [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) class based on a rectangle and an orientation angle. |

### LinearMulticolorGradientBrush() {#LinearMulticolorGradientBrush__0}


```
 LinearMulticolorGradientBrush() 
```

Initializes a new instance of the [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) class with default parameters.<br/>            The starting color is black, the ending color is white, the angle is 45 degrees and the rectangle is located in (0,0) with size (1,1).

### LinearMulticolorGradientBrush(point1, point2) {#LinearMulticolorGradientBrush_point1_point2_1}


```
 LinearMulticolorGradientBrush(point1, point2) 
```

Initializes a new instance of the LinearMulticolorGradientBrush class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point) |  |
| point2 | [Point](/imaging/python-net/aspose.imaging/point) |  |

### LinearMulticolorGradientBrush(point1, point2) {#LinearMulticolorGradientBrush_point1_point2_2}


```
 LinearMulticolorGradientBrush(point1, point2) 
```

Initializes a new instance of the LinearMulticolorGradientBrush class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf) |  |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf) |  |

### LinearMulticolorGradientBrush(rect, angle) {#LinearMulticolorGradientBrush_rect_angle_3}


```
 LinearMulticolorGradientBrush(rect, angle) 
```

Initializes a new instance of the LinearMulticolorGradientBrush class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) |  |
| angle | float |  |

### LinearMulticolorGradientBrush(rect, angle) {#LinearMulticolorGradientBrush_rect_angle_4}


```
 LinearMulticolorGradientBrush(rect, angle) 
```

Initializes a new instance of the LinearMulticolorGradientBrush class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) |  |
| angle | float |  |

### LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) {#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_5}


```
 LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) 
```

Initializes a new instance of the LinearMulticolorGradientBrush class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) |  |
| angle | float |  |
| is_angle_scalable | bool |  |

### LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) {#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_6}


```
 LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) 
```

Initializes a new instance of the LinearMulticolorGradientBrush class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) |  |
| angle | float |  |
| is_angle_scalable | bool |  |

### multiply_transform(matrix) {#multiply_transform_matrix_7}


```
 multiply_transform(matrix) 
```

Multiplies the [Matrix](/imaging/python-net/aspose.imaging/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/) by prepending the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix) | The [Matrix](/imaging/python-net/aspose.imaging/matrix/) by which to multiply the geometric transform. |

### multiply_transform(matrix, order) {#multiply_transform_matrix_order_8}


```
 multiply_transform(matrix, order) 
```

Multiplies the [Matrix](/imaging/python-net/aspose.imaging/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/) in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix) | The [Matrix](/imaging/python-net/aspose.imaging/matrix/) by which to multiply the geometric transform. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder) | A [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) that specifies in which order to multiply the two matrices. |

### translate_transform(dx, dy) {#translate_transform_dx_dy_9}


```
 translate_transform(dx, dy) 
```

Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |

### translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_10}


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

### scale_transform(sx, sy) {#scale_transform_sx_sy_11}


```
 scale_transform(sx, sy) 
```

Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| sx | float | The amount by which to scale the transform in the x-axis direction. |
| sy | float | The amount by which to scale the transform in the y-axis direction. |

### scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_12}


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

### rotate_transform(angle) {#rotate_transform_angle_13}


```
 rotate_transform(angle) 
```

Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The angle of rotation. |

### rotate_transform(angle, order) {#rotate_transform_angle_order_14}


```
 rotate_transform(angle, order) 
```

Rotates the local geometric transform by the specified amount in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The angle of rotation. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder) | A [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) that specifies whether to append or prepend the rotation matrix. |

### deep_clone() {#deep_clone__15}


```
 deep_clone() 
```

Creates a new deep clone of the current [Brush](/imaging/python-net/aspose.imaging/brush/).

**Returns**

| Type | Description |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush) | A new [Brush](/imaging/python-net/aspose.imaging/brush/) which is the deep clone of this [Brush](/imaging/python-net/aspose.imaging/brush/) instance. |


### create_with_points(point1, point2)  [static] {#create_with_points_point1_point2_16}


```
 create_with_points(point1, point2) 
```

Initializes a new instance of the [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) class with the specified points.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point) | A [Point](/imaging/python-net/aspose.imaging/point/) structure that represents the starting point of the linear gradient. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point) | A [Point](/imaging/python-net/aspose.imaging/point/) structure that represents the endpoint of the linear gradient. |

**Returns**

| Type | Description |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush) |  |


### create_with_points_f(point1, point2)  [static] {#create_with_points_f_point1_point2_17}


```
 create_with_points_f(point1, point2) 
```

Initializes a new instance of the [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) class with the specified points.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf) | A [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that represents the starting point of the linear gradient. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf) | A [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that represents the endpoint of the linear gradient. |

**Returns**

| Type | Description |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush) |  |


### create_with_rect(rect, angle)  [static] {#create_with_rect_rect_angle_18}


```
 create_with_rect(rect, angle) 
```

Initializes a new instance of the [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) class based on a rectangle and an orientation angle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | A [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that specifies the bounds of the linear gradient. |
| angle | float | The angle, measured in degrees clockwise from the x-axis, of the gradient's orientation line. |

**Returns**

| Type | Description |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush) |  |


### create_with_rect_f(rect, angle)  [static] {#create_with_rect_f_rect_angle_19}


```
 create_with_rect_f(rect, angle) 
```

Initializes a new instance of the [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) class based on a rectangle and an orientation angle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | A [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that specifies the bounds of the linear gradient. |
| angle | float | The angle, measured in degrees clockwise from the x-axis, of the gradient's orientation line. |

**Returns**

| Type | Description |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush) |  |


### create_with_rect_angle_scalable(rect, angle, is_angle_scalable)  [static] {#create_with_rect_angle_scalable_rect_angle_is_angle_scalable_20}


```
 create_with_rect_angle_scalable(rect, angle, is_angle_scalable) 
```

Initializes a new instance of the [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) class based on a rectangle and an orientation angle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | A [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that specifies the bounds of the linear gradient. |
| angle | float | The angle, measured in degrees clockwise from the x-axis, of the gradient's orientation line. |
| is_angle_scalable | bool | if set to <c>true</c> the angle is changed during transformations with this [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/). |

**Returns**

| Type | Description |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush) |  |


### create_with_rect_f_angle_scalable(rect, angle, is_angle_scalable)  [static] {#create_with_rect_f_angle_scalable_rect_angle_is_angle_scalable_21}


```
 create_with_rect_f_angle_scalable(rect, angle, is_angle_scalable) 
```

Initializes a new instance of the [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) class based on a rectangle and an orientation angle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | A [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that specifies the bounds of the linear gradient. |
| angle | float | The angle, measured in degrees clockwise from the x-axis, of the gradient's orientation line. |
| is_angle_scalable | bool | if set to <c>true</c> the angle is changed during transformations with this [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/). |

**Returns**

| Type | Description |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush) |  |


