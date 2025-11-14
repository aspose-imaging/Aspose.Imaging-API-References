---
title: PathMulticolorGradientBrush Class
type: docs
weight: 70
url: /python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/
---

**Summary:** Encapsulates a [Brush](/imaging/python-net/aspose.imaging/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.PathMulticolorGradientBrush

**Inheritance:** PathGradientBrushBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PathMulticolorGradientBrush(path)](#PathMulticolorGradientBrush_path_1) | Initializes a new instance of the [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) class with the specified points. |
| [PathMulticolorGradientBrush(path_points)](#PathMulticolorGradientBrush_path_points_2) | Initializes a new instance of the [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) class with the specified points. |
| [PathMulticolorGradientBrush(path_points)](#PathMulticolorGradientBrush_path_points_3) | Initializes a new instance of the [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) class with the specified points. |
| [PathMulticolorGradientBrush(path_points, wrap_mode)](#PathMulticolorGradientBrush_path_points_wrap_mode_4) | Initializes a new instance of the [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) class with the specified points and wrap mode. |
| [PathMulticolorGradientBrush(path_points, wrap_mode)](#PathMulticolorGradientBrush_path_points_wrap_mode_5) | Initializes a new instance of the [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) class with the specified points and wrap mode. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| center_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Gets or sets the center point of the path gradient. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| focus_scales | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Gets or sets the focus point for the gradient falloff. |
| graphics_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r | Gets the graphics path this brush was build upon. |
| interpolation_colors | [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | r/w | Gets or sets a [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) that defines a multicolor linear gradient. |
| is_transform_changed | bool | r | Gets a value indicating whether transformations were changed in some way. For example setting the transformation matrix or<br/>            calling any of the methods altering the transformation matrix. The property is introduced for backward compatibility with GDI+. |
| opacity | float | r/w | Gets or sets the brush opacity. The value should be between 0 and 1. Value of 0 means that brush is fully visible, value of 1 means the brush is fully opaque. |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r | Gets the path points this brush was build upon. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Gets or sets a copy [Matrix](/imaging/python-net/aspose.imaging/matrix/) that defines a local geometric transform for this [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Gets or sets a [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) enumeration that indicates the wrap mode for this [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_path(path)](#create_with_path_path_1) | Initializes a new instance of the [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) class with the specified path. |
| [create_with_points(path_points)](#create_with_points_path_points_2) | Initializes a new instance of the [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) class with the specified points. |
| [create_with_points_f(path_points)](#create_with_points_f_path_points_3) | Initializes a new instance of the [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) class with the specified points. |
| [create_with_points_f_wrap_mode(path_points, wrap_mode)](#create_with_points_f_wrap_mode_path_points_wrap_mode_4) | Initializes a new instance of the [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) class with the specified points and wrap mode. |
| [create_with_points_wrap_mode(path_points, wrap_mode)](#create_with_points_wrap_mode_path_points_wrap_mode_5) | Initializes a new instance of the [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) class with the specified points and wrap mode. |
| [deep_clone()](#deep_clone__6) | Creates a new deep clone of the current [Brush](/imaging/python-net/aspose.imaging/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_7) | Multiplies the [Matrix](/imaging/python-net/aspose.imaging/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/) by prepending the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_8) | Multiplies the [Matrix](/imaging/python-net/aspose.imaging/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/) in the specified order. |
| reset_transform() | Resets the [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) property to identity. |
| [rotate_transform(angle)](#rotate_transform_angle_9) | Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_10) | Rotates the local geometric transform by the specified amount in the specified order. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_11) | Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_12) | Scales the local geometric transform by the specified amounts in the specified order. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_13) | Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_14) | Translates the local geometric transform by the specified dimensions in the specified order. |


### Constructor: PathMulticolorGradientBrush(path) {#PathMulticolorGradientBrush_path_1}


```
 PathMulticolorGradientBrush(path) 
```

Initializes a new instance of the [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) class with the specified points.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) |  |

### Constructor: PathMulticolorGradientBrush(path_points) {#PathMulticolorGradientBrush_path_points_2}


```
 PathMulticolorGradientBrush(path_points) 
```

Initializes a new instance of the [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) class with the specified points.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | An array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that represents the points that make up the vertices of the path. |

### Constructor: PathMulticolorGradientBrush(path_points) {#PathMulticolorGradientBrush_path_points_3}


```
 PathMulticolorGradientBrush(path_points) 
```

Initializes a new instance of the [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) class with the specified points.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | An array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that represents the points that make up the vertices of the path. |

### Constructor: PathMulticolorGradientBrush(path_points, wrap_mode) {#PathMulticolorGradientBrush_path_points_wrap_mode_4}


```
 PathMulticolorGradientBrush(path_points, wrap_mode) 
```

Initializes a new instance of the [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) class with the specified points and wrap mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | An array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that represents the points that make up the vertices of the path. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | A [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) that specifies how fills drawn with this [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) are tiled. |

### Constructor: PathMulticolorGradientBrush(path_points, wrap_mode) {#PathMulticolorGradientBrush_path_points_wrap_mode_5}


```
 PathMulticolorGradientBrush(path_points, wrap_mode) 
```

Initializes a new instance of the [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) class with the specified points and wrap mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | An array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that represents the points that make up the vertices of the path. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | A [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) that specifies how fills drawn with this [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) are tiled. |

### Method: create_with_path(path)  [static] {#create_with_path_path_1}


```
 create_with_path(path) 
```

Initializes a new instance of the [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) class with the specified path.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | The [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) that defines the area filled by this [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/). |

**Returns**

| Type | Description |
| :- | :- |
| [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) |  |


### Method: create_with_points(path_points)  [static] {#create_with_points_path_points_2}


```
 create_with_points(path_points) 
```

Initializes a new instance of the [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) class with the specified points.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | An array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that represents the points that make up the vertices of the path. |

**Returns**

| Type | Description |
| :- | :- |
| [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) |  |


### Method: create_with_points_f(path_points)  [static] {#create_with_points_f_path_points_3}


```
 create_with_points_f(path_points) 
```

Initializes a new instance of the [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) class with the specified points.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | An array of [Point](/imaging/python-net/aspose.imaging/point/) structures that represents the points that make up the vertices of the path. |

**Returns**

| Type | Description |
| :- | :- |
| [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) |  |


### Method: create_with_points_f_wrap_mode(path_points, wrap_mode)  [static] {#create_with_points_f_wrap_mode_path_points_wrap_mode_4}


```
 create_with_points_f_wrap_mode(path_points, wrap_mode) 
```

Initializes a new instance of the [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) class with the specified points and wrap mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | An array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that represents the points that make up the vertices of the path. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | A [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) that specifies how fills drawn with this [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) are tiled. |

**Returns**

| Type | Description |
| :- | :- |
| [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) |  |


### Method: create_with_points_wrap_mode(path_points, wrap_mode)  [static] {#create_with_points_wrap_mode_path_points_wrap_mode_5}


```
 create_with_points_wrap_mode(path_points, wrap_mode) 
```

Initializes a new instance of the [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) class with the specified points and wrap mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | An array of [Point](/imaging/python-net/aspose.imaging/point/) structures that represents the points that make up the vertices of the path. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | A [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) that specifies how fills drawn with this [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) are tiled. |

**Returns**

| Type | Description |
| :- | :- |
| [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) |  |


### Method: deep_clone() {#deep_clone__6}


```
 deep_clone() 
```

Creates a new deep clone of the current [Brush](/imaging/python-net/aspose.imaging/brush/).

**Returns**

| Type | Description |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | A new [Brush](/imaging/python-net/aspose.imaging/brush/) which is the deep clone of this [Brush](/imaging/python-net/aspose.imaging/brush/) instance. |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_7}


```
 multiply_transform(matrix) 
```

Multiplies the [Matrix](/imaging/python-net/aspose.imaging/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/) by prepending the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | The [Matrix](/imaging/python-net/aspose.imaging/matrix/) by which to multiply the geometric transform. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_8}


```
 multiply_transform(matrix, order) 
```

Multiplies the [Matrix](/imaging/python-net/aspose.imaging/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/) in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | The [Matrix](/imaging/python-net/aspose.imaging/matrix/) by which to multiply the geometric transform. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | A [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) that specifies in which order to multiply the two matrices. |

### Method: rotate_transform(angle) {#rotate_transform_angle_9}


```
 rotate_transform(angle) 
```

Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The angle of rotation. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_10}


```
 rotate_transform(angle, order) 
```

Rotates the local geometric transform by the specified amount in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The angle of rotation. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | A [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) that specifies whether to append or prepend the rotation matrix. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_11}


```
 scale_transform(sx, sy) 
```

Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| sx | float | The amount by which to scale the transform in the x-axis direction. |
| sy | float | The amount by which to scale the transform in the y-axis direction. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_12}


```
 scale_transform(sx, sy, order) 
```

Scales the local geometric transform by the specified amounts in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| sx | float | The amount by which to scale the transform in the x-axis direction. |
| sy | float | The amount by which to scale the transform in the y-axis direction. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | A [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) that specifies whether to append or prepend the scaling matrix. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_13}


```
 translate_transform(dx, dy) 
```

Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_14}


```
 translate_transform(dx, dy, order) 
```

Translates the local geometric transform by the specified dimensions in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | The order (prepend or append) in which to apply the translation. |

