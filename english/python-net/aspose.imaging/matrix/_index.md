---
title: Matrix Class
type: docs
weight: 5850
url: /python-net/aspose.imaging/matrix/
---

Replaces the GDI+ Matrix.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Matrix

**Aspose.Imaging Version:** 23.6

The Matrix type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [Matrix()](#Matrix__0) | Initializes a new instance of the Matrix class as the identity matrix. |
| [Matrix(m11, m12, m21, m22, m31, m32)](#Matrix_m11_m12_m21_m22_m31_m32_1) | Initializes a new instance of the [Matrix](/imaging/python-net/aspose.imaging/matrix/) class. |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_2) | Initializes a new instance of the Matrix class |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_3) | Initializes a new instance of the Matrix class |
| [Matrix(origin)](#Matrix_origin_4) | Makes a copy of the [Matrix](/imaging/python-net/aspose.imaging/matrix/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| elements | float | r | Gets an array of floating-point values that represents the elements of this [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| m11 | float | r | Gets the matrix element at first row first column. Represents scale along X axis. |
| m12 | float | r | Gets the matrix element at first row second column. Represents shear along Y axis. |
| m21 | float | r | Gets the matrix element at second row first column. Represents shear along X axis. |
| m22 | float | r | Gets the matrix element at second row second column. Represents scale along Y axis. |
| m31 | float | r | Gets the matrix element at third row first column. Represents translation along X axis. |
| m32 | float | r | Gets the matrix element at third row first column. Represents translation along Y axis. |
| TYPE_IDENTITY [static] | int | r | An identity transform is one in which the output coordinates are<br/>            always the same as the input coordinates.<br/>            If this transform is anything other than the identity transform,<br/>            the type will either be the constant GENERAL_TRANSFORM or a<br/>            combination of the appropriate flag bits for the various coordinate<br/>            conversions that this transform performs. |
| TYPE_TRANSLATION [static] | int | r | A translation moves the coordinates by a constant amount in x<br/>            and y without changing the length or angle of vectors. |
| TYPE_UNIFORM_SCALE [static] | int | r | A uniform scale multiplies the length of vectors by the same amount<br/>            in both the x and y directions without changing the angle between<br/>            vectors.<br/>            This flag bit is mutually exclusive with the TypeGeneralScale flag. |
| TYPE_GENERAL_SCALE [static] | int | r | A general scale multiplies the length of vectors by different<br/>            amounts in the x and y directions without changing the angle<br/>            between perpendicular vectors.<br/>            This flag bit is mutually exclusive with the TypeUniformScale flag. |
| TYPE_MASK_SCALE [static] | int | r | This constant is a bit mask for any of the scale flag bits. |
| TYPE_FLIP [static] | int | r | This flag bit indicates that the transform defined by this object<br/>            performs a mirror image flip about some axis which changes the<br/>            normally right handed coordinate system into a left handed<br/>            system in addition to the conversions indicated by other flag bits.<br/>            A right handed coordinate system is one where the positive X<br/>            axis rotates counterclockwise to overlay the positive Y axis<br/>            similar to the direction that the fingers on your right hand<br/>            curl when you stare end on at your thumb.<br/>            A left handed coordinate system is one where the positive X<br/>            axis rotates clockwise to overlay the positive Y axis similar<br/>            to the direction that the fingers on your left hand curl.<br/>            There is no mathematical way to determine the angle of the<br/>            original flipping or mirroring transformation since all angles<br/>            of flip are identical given an appropriate adjusting rotation.<br/>            NOTE: TypeFlip was added after GENERAL_TRANSFORM was in public<br/>            circulation and the flag bits could no longer be conveniently<br/>            renumbered without introducing binary incompatibility in outside<br/>            code. |
| TYPE_QUADRANT_ROTATION [static] | int | r | This flag bit indicates that the transform defined by this object<br/>            performs a quadrant rotation by some multiple of 90 degrees in<br/>            addition to the conversions indicated by other flag bits.<br/>            A rotation changes the angles of vectors by the same amount<br/>            regardless of the original direction of the vector and without<br/>            changing the length of the vector.<br/>            This flag bit is mutually exclusive with the TypeGeneralRotation flag. |
| TYPE_GENERAL_ROTATION [static] | int | r | This flag bit indicates that the transform defined by this object<br/>            performs a rotation by an arbitrary angle in addition to the<br/>            conversions indicated by other flag bits.<br/>            A rotation changes the angles of vectors by the same amount<br/>            regardless of the original direction of the vector and without<br/>            changing the length of the vector.<br/>            This flag bit is mutually exclusive with the |
| TYPE_MASK_ROTATION [static] | int | r | This constant is a bit mask for any of the rotation flag bits. |
| TYPE_GENERAL_TRANSFORM [static] | int | r | This constant indicates that the transform defined by this object<br/>            performs an arbitrary conversion of the input coordinates.<br/>            If this transform can be classified by any of the above constants,<br/>            the type will either be the constant TypeIdentity or a<br/>            combination of the appropriate flag bits for the various coordinate<br/>            conversions that this transform performs. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [scale(scale_x, scale_y, order)](#scale_scale_x_scale_y_order_5) | Applies the specified scale vector (scaleX and scaleY) to this [Matrix](/imaging/python-net/aspose.imaging/matrix/) using the specified order. |
| [scale(sx, sy)](#scale_sx_sy_6) | Applies the specified scale vector (scaleX and scaleY) to this Matrix using (default) Prepend order. |
| [translate(offset_x, offset_y, order)](#translate_offset_x_offset_y_order_7) | Applies the specified translation vector to this Matrix in the specified order. |
| [translate(tx, ty)](#translate_tx_ty_8) | Applies the specified translation vector to this [Matrix](/imaging/python-net/aspose.imaging/matrix/) using (default) Prepend order. |
| [multiply(tx, order)](#multiply_tx_order_9) | Multiplies this Matrix by the matrix specified in the matrix parameter, and in the order specified in the order parameter. |
| [multiply(tx)](#multiply_tx_10) | Multiplies this Matrix by the matrix specified in the matrix parameter using (default) Prepend order. |
| [rotate(angle, order)](#rotate_angle_order_11) | Applies a clockwise rotation of an amount specified in the angle parameter, around the origin (zero x and y coordinates) for this Matrix in the specified order. |
| [rotate(angle)](#rotate_angle_12) | Applies a clockwise rotation of an amount specified in the angle parameter, around the origin (zero x and y coordinates) for this Matrix in the default (Prepend) order. |
| [rotate_at(angle, point, order)](#rotate_at_angle_point_order_13) | Applies a clockwise rotation about the specified point to this Matrix in the specified order. |
| [rotate_at(angle, point)](#rotate_at_angle_point_14) | Applies a clockwise rotation about the specified point to this Matrix in the default (Prepend) order. |
| [create_with_rect_f(rect, plgpts)](#create_with_rect_f_rect_plgpts_15) | Initializes a new instance of the [Matrix](/imaging/python-net/aspose.imaging/matrix/) class to the geometric transform defined by the specified rectangle and array of points. |
| [create_with_rect(rect, plgpts)](#create_with_rect_rect_plgpts_16) | Initializes a new instance of the [Matrix](/imaging/python-net/aspose.imaging/matrix/) class to the geometric transform defined by the specified rectangle and array of points. |
| [get_elements()](#get_elements__17) | Gets the copy of matrix elements. |
| [transform_points(points)](#transform_points_points_18) | Applies the geometric transform represented by this [Matrix](/imaging/python-net/aspose.imaging/matrix/) to a specified array of points. |
| reset() | Resets this Matrix to have the elements of the identity matrix. |

### Matrix() {#Matrix__0}


```
 Matrix() 
```

Initializes a new instance of the Matrix class as the identity matrix.

### Matrix(m11, m12, m21, m22, m31, m32) {#Matrix_m11_m12_m21_m22_m31_m32_1}


```
 Matrix(m11, m12, m21, m22, m31, m32) 
```

Initializes a new instance of the [Matrix](/imaging/python-net/aspose.imaging/matrix/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| m11 | float | m00     M11     Scale X |
| m12 | float | m10     M12     Shear Y |
| m21 | float | m01     M21     Shear X |
| m22 | float | m11     M22     Scale Y |
| m31 | float | m02     M31     Translate X |
| m32 | float | m12     M32     Translate Y |

### Matrix(rect, plgpts) {#Matrix_rect_plgpts_2}


```
 Matrix(rect, plgpts) 
```

Initializes a new instance of the Matrix class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) |  |
| plgpts | [PointF[]](/imaging/python-net/aspose.imaging/pointf) |  |

### Matrix(rect, plgpts) {#Matrix_rect_plgpts_3}


```
 Matrix(rect, plgpts) 
```

Initializes a new instance of the Matrix class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) |  |
| plgpts | [Point[]](/imaging/python-net/aspose.imaging/point) |  |

### Matrix(origin) {#Matrix_origin_4}


```
 Matrix(origin) 
```

Makes a copy of the [Matrix](/imaging/python-net/aspose.imaging/matrix/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| origin | [Matrix](/imaging/python-net/aspose.imaging/matrix) | A base matrix for coping |

### scale(scale_x, scale_y, order) {#scale_scale_x_scale_y_order_5}


```
 scale(scale_x, scale_y, order) 
```

Applies the specified scale vector (scaleX and scaleY) to this [Matrix](/imaging/python-net/aspose.imaging/matrix/) using the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| scale_x | float | The scale X. |
| scale_y | float | The scale Y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder) | The order. |

### scale(sx, sy) {#scale_sx_sy_6}


```
 scale(sx, sy) 
```

Applies the specified scale vector (scaleX and scaleY) to this Matrix using (default) Prepend order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| sx | float | The sx. The sx. The sx. |
| sy | float | The sy. The sy. The sy. |

### translate(offset_x, offset_y, order) {#translate_offset_x_offset_y_order_7}


```
 translate(offset_x, offset_y, order) 
```

Applies the specified translation vector to this Matrix in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| offset_x | float | The offset X. |
| offset_y | float | The offset Y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder) | The order. |

### translate(tx, ty) {#translate_tx_ty_8}


```
 translate(tx, ty) 
```

Applies the specified translation vector to this [Matrix](/imaging/python-net/aspose.imaging/matrix/) using (default) Prepend order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tx | float | The tx. The tx. The tx. |
| ty | float | The ty. The ty. The ty. |

### multiply(tx, order) {#multiply_tx_order_9}


```
 multiply(tx, order) 
```

Multiplies this Matrix by the matrix specified in the matrix parameter, and in the order specified in the order parameter.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tx | [Matrix](/imaging/python-net/aspose.imaging/matrix) | The tx. The tx. The tx. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder) | The order. The order. The order. |

### multiply(tx) {#multiply_tx_10}


```
 multiply(tx) 
```

Multiplies this Matrix by the matrix specified in the matrix parameter using (default) Prepend order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tx | [Matrix](/imaging/python-net/aspose.imaging/matrix) | The matrix to multiply with. |

### rotate(angle, order) {#rotate_angle_order_11}


```
 rotate(angle, order) 
```

Applies a clockwise rotation of an amount specified in the angle parameter, around the origin (zero x and y coordinates) for this Matrix in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The rotate angle. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder) | The matrix order. |

### rotate(angle) {#rotate_angle_12}


```
 rotate(angle) 
```

Applies a clockwise rotation of an amount specified in the angle parameter, around the origin (zero x and y coordinates) for this Matrix in the default (Prepend) order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The rotate angle. |

### rotate_at(angle, point, order) {#rotate_at_angle_point_order_13}


```
 rotate_at(angle, point, order) 
```

Applies a clockwise rotation about the specified point to this Matrix in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The angle. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf) | The point. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder) | The order. |

### rotate_at(angle, point) {#rotate_at_angle_point_14}


```
 rotate_at(angle, point) 
```

Applies a clockwise rotation about the specified point to this Matrix in the default (Prepend) order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The angle. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf) | The point. |

### create_with_rect_f(rect, plgpts)  [static] {#create_with_rect_f_rect_plgpts_15}


```
 create_with_rect_f(rect, plgpts) 
```

Initializes a new instance of the [Matrix](/imaging/python-net/aspose.imaging/matrix/) class to the geometric transform defined by the specified rectangle and array of points.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | A [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that represents the rectangle to be transformed. |
| plgpts | [PointF[]](/imaging/python-net/aspose.imaging/pointf) | An array of three [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that represents the points of a parallelogram to which the upper-left, upper-right, and lower-left corners of the rectangle is to be transformed. The lower-right corner of the parallelogram is implied by the first three corners. |

**Returns**

| Type | Description |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix) |  |


### create_with_rect(rect, plgpts)  [static] {#create_with_rect_rect_plgpts_16}


```
 create_with_rect(rect, plgpts) 
```

Initializes a new instance of the [Matrix](/imaging/python-net/aspose.imaging/matrix/) class to the geometric transform defined by the specified rectangle and array of points.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | A [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that represents the rectangle to be transformed. |
| plgpts | [Point[]](/imaging/python-net/aspose.imaging/point) | An array of three [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that represents the points of a parallelogram to which the upper-left, upper-right, and lower-left corners of the rectangle is to be transformed. The lower-right corner of the parallelogram is implied by the first three corners. |

**Returns**

| Type | Description |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix) |  |


### get_elements() {#get_elements__17}


```
 get_elements() 
```

Gets the copy of matrix elements.

**Returns**

| Type | Description |
| :- | :- |
| float | A matrix elements copy. |


### transform_points(points) {#transform_points_points_18}


```
 transform_points(points) 
```

Applies the geometric transform represented by this [Matrix](/imaging/python-net/aspose.imaging/matrix/) to a specified array of points.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf) | The points. |

