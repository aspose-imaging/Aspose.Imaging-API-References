---
title: Matrix
second_title: Aspose.Imaging for Java API Reference
description: Replaces the GDI Matrix.
type: docs
weight: 73
url: /java/com.aspose.imaging/matrix/
---
**Inheritance:**
java.lang.Object
```
public class Matrix
```

Replaces the GDI+ Matrix.

--------------------

Most algorithms taken from Sun's AffineTransform.java. Java's names for matrix elements used internally. Map of java names to .net ones to description: m00 M11 Scale X m10 M12 Shear Y m01 M21 Shear X m11 M22 Scale Y m02 M31 Translate X m12 M32 Translate Y
## Constructors

| Constructor | Description |
| --- | --- |
| [Matrix()](#Matrix--) | Initializes a new instance of the Matrix class as the identity matrix. |
| [Matrix(float m11, float m12, float m21, float m22, float m31, float m32)](#Matrix-float-float-float-float-float-float-) | Initializes a new instance of the [Matrix](../../com.aspose.imaging/matrix) class. |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.imaging.RectangleF-com.aspose.imaging.PointF---) | Initializes a new instance of the [Matrix](../../com.aspose.imaging/matrix) class to the geometric transform defined by the specified rectangle and array of points. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.imaging.Rectangle-com.aspose.imaging.Point---) | Initializes a new instance of the [Matrix](../../com.aspose.imaging/matrix) class to the geometric transform defined by the specified rectangle and array of points. |
| [Matrix(Matrix origin)](#Matrix-com.aspose.imaging.Matrix-) | Makes a copy of the [Matrix](../../com.aspose.imaging/matrix) class. |
## Fields

| Field | Description |
| --- | --- |
| [TYPE_IDENTITY](#TYPE-IDENTITY) | An identity transform is one in which the output coordinates are always the same as the input coordinates. |
| [TYPE_TRANSLATION](#TYPE-TRANSLATION) | A translation moves the coordinates by a constant amount in x and y without changing the length or angle of vectors. |
| [TYPE_UNIFORM_SCALE](#TYPE-UNIFORM-SCALE) | A uniform scale multiplies the length of vectors by the same amount in both the x and y directions without changing the angle between vectors. |
| [TYPE_GENERAL_SCALE](#TYPE-GENERAL-SCALE) | A general scale multiplies the length of vectors by different amounts in the x and y directions without changing the angle between perpendicular vectors. |
| [TYPE_MASK_SCALE](#TYPE-MASK-SCALE) | This constant is a bit mask for any of the scale flag bits. |
| [TYPE_FLIP](#TYPE-FLIP) | This flag bit indicates that the transform defined by this object performs a mirror image flip about some axis which changes the normally right handed coordinate system into a left handed system in addition to the conversions indicated by other flag bits. |
| [TYPE_QUADRANT_ROTATION](#TYPE-QUADRANT-ROTATION) | This flag bit indicates that the transform defined by this object performs a quadrant rotation by some multiple of 90 degrees in addition to the conversions indicated by other flag bits. |
| [TYPE_GENERAL_ROTATION](#TYPE-GENERAL-ROTATION) | This flag bit indicates that the transform defined by this object performs a rotation by an arbitrary angle in addition to the conversions indicated by other flag bits. |
| [TYPE_MASK_ROTATION](#TYPE-MASK-ROTATION) | This constant is a bit mask for any of the rotation flag bits. |
| [TYPE_GENERAL_TRANSFORM](#TYPE-GENERAL-TRANSFORM) | This constant indicates that the transform defined by this object performs an arbitrary conversion of the input coordinates. |
## Methods

| Method | Description |
| --- | --- |
| [isEquals(Matrix a, Matrix b)](#isEquals-com.aspose.imaging.Matrix-com.aspose.imaging.Matrix-) | Determines whether two matrices are equal. |
| [getM11()](#getM11--) | Gets the matrix element at first row first column. |
| [getM12()](#getM12--) | Gets the matrix element at first row second column. |
| [getM21()](#getM21--) | Gets the matrix element at second row first column. |
| [getM22()](#getM22--) | Gets the matrix element at second row second column. |
| [getM31()](#getM31--) | Gets the matrix element at third row first column. |
| [getM32()](#getM32--) | Gets the matrix element at third row first column. |
| [toString()](#toString--) | Returns a String that represents this instance. |
| [getElements()](#getElements--) | Gets the copy of matrix elements. |
| [transformPoints(PointF[] points)](#transformPoints-com.aspose.imaging.PointF---) | Applies the geometric transform represented by this [Matrix](../../com.aspose.imaging/matrix) to a specified array of points. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | Applies the specified scale vector (scaleX and scaleY) to this [Matrix](../../com.aspose.imaging/matrix) using the specified order. |
| [scale(float sx, float sy)](#scale-float-float-) | Applies the specified scale vector (scaleX and scaleY) to this Matrix using (default) Prepend order. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | Applies the specified translation vector to this Matrix in the specified order. |
| [translate(float tx, float ty)](#translate-float-float-) | Applies the specified translation vector to this [Matrix](../../com.aspose.imaging/matrix) using (default) Prepend order. |
| [multiply(Matrix tTx, int order)](#multiply-com.aspose.imaging.Matrix-int-) | Multiplies this Matrix by the matrix specified in the matrix parameter, and in the order specified in the order parameter. |
| [multiply(Matrix tTx)](#multiply-com.aspose.imaging.Matrix-) | Multiplies this Matrix by the matrix specified in the matrix parameter using (default) Prepend order. |
| [rotate(float angle, int order)](#rotate-float-int-) | Applies a clockwise rotation of an amount specified in the angle parameter, around the origin (zero x and y coordinates) for this Matrix in the specified order. |
| [rotate(float angle)](#rotate-float-) | Applies a clockwise rotation of an amount specified in the angle parameter, around the origin (zero x and y coordinates) for this Matrix in the default (Prepend) order. |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.imaging.PointF-int-) | Applies a clockwise rotation about the specified point to this Matrix in the specified order. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.imaging.PointF-) | Applies a clockwise rotation about the specified point to this Matrix in the default (Prepend) order. |
| [reset()](#reset--) | Resets this Matrix to have the elements of the identity matrix. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified `Object` is equal to this instance. |
| [isIdentity()](#isIdentity--) | Returns `true` if this `AffineTransform` is an identity transform. |
### Matrix() {#Matrix--}
```
public Matrix()
```


Initializes a new instance of the Matrix class as the identity matrix.

### Matrix(float m11, float m12, float m21, float m22, float m31, float m32) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```


Initializes a new instance of the [Matrix](../../com.aspose.imaging/matrix) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| m11 | float | m00 M11 Scale X |
| m12 | float | m10 M12 Shear Y |
| m21 | float | m01 M21 Shear X |
| m22 | float | m11 M22 Scale Y |
| m31 | float | m02 M31 Translate X |
| m32 | float | m12 M32 Translate Y |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.imaging.RectangleF-com.aspose.imaging.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Initializes a new instance of the [Matrix](../../com.aspose.imaging/matrix) class to the geometric transform defined by the specified rectangle and array of points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | A [RectangleF](../../com.aspose.imaging/rectanglef) structure that represents the rectangle to be transformed. |
| plgpts | [PointF\[\]](../../com.aspose.imaging/pointf) | An array of three [PointF](../../com.aspose.imaging/pointf) structures that represents the points of a parallelogram to which the upper-left, upper-right, and lower-left corners of the rectangle is to be transformed. The lower-right corner of the parallelogram is implied by the first three corners. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.imaging.Rectangle-com.aspose.imaging.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Initializes a new instance of the [Matrix](../../com.aspose.imaging/matrix) class to the geometric transform defined by the specified rectangle and array of points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | A [Rectangle](../../com.aspose.imaging/rectangle) structure that represents the rectangle to be transformed. |
| plgpts | [Point\[\]](../../com.aspose.imaging/point) | An array of three [Point](../../com.aspose.imaging/point) structures that represents the points of a parallelogram to which the upper-left, upper-right, and lower-left corners of the rectangle is to be transformed. The lower-right corner of the parallelogram is implied by the first three corners. |

### Matrix(Matrix origin) {#Matrix-com.aspose.imaging.Matrix-}
```
public Matrix(Matrix origin)
```


Makes a copy of the [Matrix](../../com.aspose.imaging/matrix) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| origin | [Matrix](../../com.aspose.imaging/matrix) | A base matrix for coping |

### TYPE_IDENTITY {#TYPE-IDENTITY}
```
public static final int TYPE_IDENTITY
```


An identity transform is one in which the output coordinates are always the same as the input coordinates. If this transform is anything other than the identity transform, the type will either be the constant GENERAL\_TRANSFORM or a combination of the appropriate flag bits for the various coordinate conversions that this transform performs.

### TYPE_TRANSLATION {#TYPE-TRANSLATION}
```
public static final int TYPE_TRANSLATION
```


A translation moves the coordinates by a constant amount in x and y without changing the length or angle of vectors.

### TYPE_UNIFORM_SCALE {#TYPE-UNIFORM-SCALE}
```
public static final int TYPE_UNIFORM_SCALE
```


A uniform scale multiplies the length of vectors by the same amount in both the x and y directions without changing the angle between vectors. This flag bit is mutually exclusive with the TypeGeneralScale flag.

### TYPE_GENERAL_SCALE {#TYPE-GENERAL-SCALE}
```
public static final int TYPE_GENERAL_SCALE
```


A general scale multiplies the length of vectors by different amounts in the x and y directions without changing the angle between perpendicular vectors. This flag bit is mutually exclusive with the TypeUniformScale flag.

### TYPE_MASK_SCALE {#TYPE-MASK-SCALE}
```
public static final int TYPE_MASK_SCALE
```


This constant is a bit mask for any of the scale flag bits.

### TYPE_FLIP {#TYPE-FLIP}
```
public static final int TYPE_FLIP
```


This flag bit indicates that the transform defined by this object performs a mirror image flip about some axis which changes the normally right handed coordinate system into a left handed system in addition to the conversions indicated by other flag bits. A right handed coordinate system is one where the positive X axis rotates counterclockwise to overlay the positive Y axis similar to the direction that the fingers on your right hand curl when you stare end on at your thumb. A left handed coordinate system is one where the positive X axis rotates clockwise to overlay the positive Y axis similar to the direction that the fingers on your left hand curl. There is no mathematical way to determine the angle of the original flipping or mirroring transformation since all angles of flip are identical given an appropriate adjusting rotation. NOTE: TypeFlip was added after GENERAL\_TRANSFORM was in public circulation and the flag bits could no longer be conveniently renumbered without introducing binary incompatibility in outside code.

### TYPE_QUADRANT_ROTATION {#TYPE-QUADRANT-ROTATION}
```
public static final int TYPE_QUADRANT_ROTATION
```


This flag bit indicates that the transform defined by this object performs a quadrant rotation by some multiple of 90 degrees in addition to the conversions indicated by other flag bits. A rotation changes the angles of vectors by the same amount regardless of the original direction of the vector and without changing the length of the vector. This flag bit is mutually exclusive with the TypeGeneralRotation flag.

### TYPE_GENERAL_ROTATION {#TYPE-GENERAL-ROTATION}
```
public static final int TYPE_GENERAL_ROTATION
```


This flag bit indicates that the transform defined by this object performs a rotation by an arbitrary angle in addition to the conversions indicated by other flag bits. A rotation changes the angles of vectors by the same amount regardless of the original direction of the vector and without changing the length of the vector. This flag bit is mutually exclusive with the

### TYPE_MASK_ROTATION {#TYPE-MASK-ROTATION}
```
public static final int TYPE_MASK_ROTATION
```


This constant is a bit mask for any of the rotation flag bits.

### TYPE_GENERAL_TRANSFORM {#TYPE-GENERAL-TRANSFORM}
```
public static final int TYPE_GENERAL_TRANSFORM
```


This constant indicates that the transform defined by this object performs an arbitrary conversion of the input coordinates. If this transform can be classified by any of the above constants, the type will either be the constant TypeIdentity or a combination of the appropriate flag bits for the various coordinate conversions that this transform performs.

### isEquals(Matrix a, Matrix b) {#isEquals-com.aspose.imaging.Matrix-com.aspose.imaging.Matrix-}
```
public static boolean isEquals(Matrix a, Matrix b)
```


Determines whether two matrices are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Matrix](../../com.aspose.imaging/matrix) | The first matrix to compare. |
| b | [Matrix](../../com.aspose.imaging/matrix) | The second matrix to compare. |

**Returns:**
boolean - True if matrices are equal.
### getM11() {#getM11--}
```
public final float getM11()
```


Gets the matrix element at first row first column. Represents scale along X axis.

**Returns:**
float - the matrix element at first row first column.
### getM12() {#getM12--}
```
public final float getM12()
```


Gets the matrix element at first row second column. Represents shear along Y axis.

**Returns:**
float - the matrix element at first row second column.
### getM21() {#getM21--}
```
public final float getM21()
```


Gets the matrix element at second row first column. Represents shear along X axis.

**Returns:**
float - the matrix element at second row first column.
### getM22() {#getM22--}
```
public final float getM22()
```


Gets the matrix element at second row second column. Represents scale along Y axis.

**Returns:**
float - the matrix element at second row second column.
### getM31() {#getM31--}
```
public final float getM31()
```


Gets the matrix element at third row first column. Represents translation along X axis.

**Returns:**
float - the matrix element at third row first column.
### getM32() {#getM32--}
```
public final float getM32()
```


Gets the matrix element at third row first column. Represents translation along Y axis.

**Returns:**
float - the matrix element at third row first column.
### toString() {#toString--}
```
public String toString()
```


Returns a String that represents this instance.

**Returns:**
java.lang.String - A String that represents this instance.
### getElements() {#getElements--}
```
public final float[] getElements()
```


Gets the copy of matrix elements.

**Returns:**
float[] - A matrix elements copy.
### transformPoints(PointF[] points) {#transformPoints-com.aspose.imaging.PointF---}
```
public final void transformPoints(PointF[] points)
```


Applies the geometric transform represented by this [Matrix](../../com.aspose.imaging/matrix) to a specified array of points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | The points. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public final void scale(float scaleX, float scaleY, int order)
```


Applies the specified scale vector (scaleX and scaleY) to this [Matrix](../../com.aspose.imaging/matrix) using the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scaleX | float | The scale X. |
| scaleY | float | The scale Y. |
| order | int | The order. |

### scale(float sx, float sy) {#scale-float-float-}
```
public final void scale(float sx, float sy)
```


Applies the specified scale vector (scaleX and scaleY) to this Matrix using (default) Prepend order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sx | float | The sx. The sx. The sx. |
| sy | float | The sy. The sy. The sy. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public final void translate(float offsetX, float offsetY, int order)
```


Applies the specified translation vector to this Matrix in the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| offsetX | float | The offset X. |
| offsetY | float | The offset Y. |
| order | int | The order. |

### translate(float tx, float ty) {#translate-float-float-}
```
public final void translate(float tx, float ty)
```


Applies the specified translation vector to this [Matrix](../../com.aspose.imaging/matrix) using (default) Prepend order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tx | float | The tx. The tx. The tx. |
| ty | float | The ty. The ty. The ty. |

### multiply(Matrix tTx, int order) {#multiply-com.aspose.imaging.Matrix-int-}
```
public final void multiply(Matrix tTx, int order)
```


Multiplies this Matrix by the matrix specified in the matrix parameter, and in the order specified in the order parameter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tTx | [Matrix](../../com.aspose.imaging/matrix) | The tx. The tx. The tx. |
| order | int | The order. The order. The order. |

### multiply(Matrix tTx) {#multiply-com.aspose.imaging.Matrix-}
```
public final void multiply(Matrix tTx)
```


Multiplies this Matrix by the matrix specified in the matrix parameter using (default) Prepend order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tTx | [Matrix](../../com.aspose.imaging/matrix) | The matrix to multiply with. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public final void rotate(float angle, int order)
```


Applies a clockwise rotation of an amount specified in the angle parameter, around the origin (zero x and y coordinates) for this Matrix in the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | The rotate angle. |
| order | int | The matrix order. |

### rotate(float angle) {#rotate-float-}
```
public final void rotate(float angle)
```


Applies a clockwise rotation of an amount specified in the angle parameter, around the origin (zero x and y coordinates) for this Matrix in the default (Prepend) order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | The rotate angle. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.imaging.PointF-int-}
```
public final void rotateAt(float angle, PointF point, int order)
```


Applies a clockwise rotation about the specified point to this Matrix in the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | The angle. |
| point | [PointF](../../com.aspose.imaging/pointf) | The point. |
| order | int | The order. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.imaging.PointF-}
```
public final void rotateAt(float angle, PointF point)
```


Applies a clockwise rotation about the specified point to this Matrix in the default (Prepend) order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | The angle. |
| point | [PointF](../../com.aspose.imaging/pointf) | The point. |

### reset() {#reset--}
```
public final void reset()
```


Resets this Matrix to have the elements of the identity matrix.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this instance.

**Returns:**
int - A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified `Object` is equal to this instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The `Object` to compare with this instance. |

**Returns:**
boolean - `true` if the specified `Object` is equal to this instance; otherwise, `false`.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


Returns `true` if this `AffineTransform` is an identity transform.

**Returns:**
boolean - `true` if this `AffineTransform` is an identity transform; `false` otherwise.
