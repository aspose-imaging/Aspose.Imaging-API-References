---
title: Class Matrix
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.Matrix class. Replaces the GDI Matrix
type: docs
weight: 11090
url: /net/aspose.imaging/matrix/
---
## Matrix class

Replaces the GDI+ Matrix.

```csharp
public class Matrix
```

## Constructors

| Name | Description |
| --- | --- |
| [Matrix](matrix/#constructor)() | Initializes a new instance of the Matrix class as the identity matrix. |
| [Matrix](matrix/#constructor_1)(Matrix) | Makes a copy of the `Matrix` class. |
| [Matrix](matrix/#constructor_2)(Rectangle, Point[]) | Initializes a new instance of the `Matrix` class to the geometric transform defined by the specified rectangle and array of points. |
| [Matrix](matrix/#constructor_3)(RectangleF, PointF[]) | Initializes a new instance of the `Matrix` class to the geometric transform defined by the specified rectangle and array of points. |
| [Matrix](matrix/#constructor_4)(float, float, float, float, float, float) | Initializes a new instance of the `Matrix` class. |

## Properties

| Name | Description |
| --- | --- |
| [Elements](../../aspose.imaging/matrix/elements/) { get; } | Gets an array of floating-point values that represents the elements of this `Matrix`. |
| [M11](../../aspose.imaging/matrix/m11/) { get; } | Gets the matrix element at first row first column. Represents scale along X axis. |
| [M12](../../aspose.imaging/matrix/m12/) { get; } | Gets the matrix element at first row second column. Represents shear along Y axis. |
| [M21](../../aspose.imaging/matrix/m21/) { get; } | Gets the matrix element at second row first column. Represents shear along X axis. |
| [M22](../../aspose.imaging/matrix/m22/) { get; } | Gets the matrix element at second row second column. Represents scale along Y axis. |
| [M31](../../aspose.imaging/matrix/m31/) { get; } | Gets the matrix element at third row first column. Represents translation along X axis. |
| [M32](../../aspose.imaging/matrix/m32/) { get; } | Gets the matrix element at third row first column. Represents translation along Y axis. |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.imaging/matrix/equals/)(object) | Determines whether the specified Object is equal to this instance. |
| [GetElements](../../aspose.imaging/matrix/getelements/)() | Gets the copy of matrix elements. |
| override [GetHashCode](../../aspose.imaging/matrix/gethashcode/)() | Returns a hash code for this instance. |
| [Multiply](../../aspose.imaging/matrix/multiply/#multiply)(Matrix) | Multiplies this Matrix by the matrix specified in the matrix parameter using (default) Prepend order. |
| [Multiply](../../aspose.imaging/matrix/multiply/#multiply_1)(Matrix, MatrixOrder) | Multiplies this Matrix by the matrix specified in the matrix parameter, and in the order specified in the order parameter. |
| [Reset](../../aspose.imaging/matrix/reset/)() | Resets this Matrix to have the elements of the identity matrix. |
| [Rotate](../../aspose.imaging/matrix/rotate/#rotate)(float) | Applies a clockwise rotation of an amount specified in the angle parameter, around the origin (zero x and y coordinates) for this Matrix in the default (Prepend) order. |
| [Rotate](../../aspose.imaging/matrix/rotate/#rotate_1)(float, MatrixOrder) | Applies a clockwise rotation of an amount specified in the angle parameter, around the origin (zero x and y coordinates) for this Matrix in the specified order. |
| [RotateAt](../../aspose.imaging/matrix/rotateat/#rotateat)(float, PointF) | Applies a clockwise rotation about the specified point to this Matrix in the default (Prepend) order. |
| [RotateAt](../../aspose.imaging/matrix/rotateat/#rotateat_1)(float, PointF, MatrixOrder) | Applies a clockwise rotation about the specified point to this Matrix in the specified order. |
| [Scale](../../aspose.imaging/matrix/scale/#scale)(float, float) | Applies the specified scale vector (scaleX and scaleY) to this Matrix using (default) Prepend order. |
| [Scale](../../aspose.imaging/matrix/scale/#scale_1)(float, float, MatrixOrder) | Applies the specified scale vector (scaleX and scaleY) to this `Matrix` using the specified order. |
| override [ToString](../../aspose.imaging/matrix/tostring/)() | Returns a String that represents this instance. |
| [TransformPoints](../../aspose.imaging/matrix/transformpoints/)(PointF[]) | Applies the geometric transform represented by this `Matrix` to a specified array of points. |
| [Translate](../../aspose.imaging/matrix/translate/#translate)(float, float) | Applies the specified translation vector to this `Matrix` using (default) Prepend order. |
| [Translate](../../aspose.imaging/matrix/translate/#translate_1)(float, float, MatrixOrder) | Applies the specified translation vector to this Matrix in the specified order. |
| static [Equals](../../aspose.imaging/matrix/equals/)(Matrix, Matrix) | Determines whether two matrixes are equal. |

## Fields

| Name | Description |
| --- | --- |
| const [TypeFlip](../../aspose.imaging/matrix/typeflip/) | This flag bit indicates that the transform defined by this object performs a mirror image flip about some axis which changes the normally right handed coordinate system into a left handed system in addition to the conversions indicated by other flag bits. A right handed coordinate system is one where the positive X axis rotates counterclockwise to overlay the positive Y axis similar to the direction that the fingers on your right hand curl when you stare end on at your thumb. A left handed coordinate system is one where the positive X axis rotates clockwise to overlay the positive Y axis similar to the direction that the fingers on your left hand curl. There is no mathematical way to determine the angle of the original flipping or mirroring transformation since all angles of flip are identical given an appropriate adjusting rotation. NOTE: TypeFlip was added after GENERAL_TRANSFORM was in public circulation and the flag bits could no longer be conveniently renumbered without introducing binary incompatibility in outside code. |
| const [TypeGeneralRotation](../../aspose.imaging/matrix/typegeneralrotation/) | This flag bit indicates that the transform defined by this object performs a rotation by an arbitrary angle in addition to the conversions indicated by other flag bits. A rotation changes the angles of vectors by the same amount regardless of the original direction of the vector and without changing the length of the vector. This flag bit is mutually exclusive with the |
| const [TypeGeneralScale](../../aspose.imaging/matrix/typegeneralscale/) | A general scale multiplies the length of vectors by different amounts in the x and y directions without changing the angle between perpendicular vectors. This flag bit is mutually exclusive with the TypeUniformScale flag. |
| const [TypeGeneralTransform](../../aspose.imaging/matrix/typegeneraltransform/) | This constant indicates that the transform defined by this object performs an arbitrary conversion of the input coordinates. If this transform can be classified by any of the above constants, the type will either be the constant TypeIdentity or a combination of the appropriate flag bits for the various coordinate conversions that this transform performs. |
| const [TypeIdentity](../../aspose.imaging/matrix/typeidentity/) | An identity transform is one in which the output coordinates are always the same as the input coordinates. If this transform is anything other than the identity transform, the type will either be the constant GENERAL_TRANSFORM or a combination of the appropriate flag bits for the various coordinate conversions that this transform performs. |
| const [TypeMaskRotation](../../aspose.imaging/matrix/typemaskrotation/) | This constant is a bit mask for any of the rotation flag bits. |
| const [TypeMaskScale](../../aspose.imaging/matrix/typemaskscale/) | This constant is a bit mask for any of the scale flag bits. |
| const [TypeQuadrantRotation](../../aspose.imaging/matrix/typequadrantrotation/) | This flag bit indicates that the transform defined by this object performs a quadrant rotation by some multiple of 90 degrees in addition to the conversions indicated by other flag bits. A rotation changes the angles of vectors by the same amount regardless of the original direction of the vector and without changing the length of the vector. This flag bit is mutually exclusive with the TypeGeneralRotation flag. |
| const [TypeTranslation](../../aspose.imaging/matrix/typetranslation/) | A translation moves the coordinates by a constant amount in x and y without changing the length or angle of vectors. |
| const [TypeUniformScale](../../aspose.imaging/matrix/typeuniformscale/) | A uniform scale multiplies the length of vectors by the same amount in both the x and y directions without changing the angle between vectors. This flag bit is mutually exclusive with the TypeGeneralScale flag. |

## Remarks

Most algorithms taken from Sun's AffineTransform.java. Java's names for matrix elements used internally. Map of java names to .net ones to description: m00 M11 Scale X m10 M12 Shear Y m01 M21 Shear X m11 M22 Scale Y m02 M31 Translate X m12 M32 Translate Y

### See Also

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


