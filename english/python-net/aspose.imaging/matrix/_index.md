---
title: Matrix Class
type: docs
weight: 590
url: /python-net/api-reference/aspose.imaging/matrix/
---

Replaces the GDI+ Matrix.

**Namespace:** [aspose.imaging](/imaging/python-net/api-reference/aspose.imaging/)

**Full Class Name:** aspose.imaging.Matrix

**Assembly:**  Aspose.Imaging Version: 23.3.0

The Matrix type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|Matrix()|Initializes a new instance of the Matrix class as the identity matrix.|
|Matrix(m11, m12, m21, m22, m31, m32)|Initializes a new instance of the Matrix class|
|Matrix(rect, plgpts)|Initializes a new instance of the Matrix class|
|Matrix(rect, plgpts)|Initializes a new instance of the Matrix class|
|Matrix(origin)|Initializes a new instance of the Matrix class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|elements|Gets an array of floating-point values that represents the elements of this [Matrix](/imaging/python-net/api-reference/aspose.imaging/matrix/).|
|m11|Gets the matrix element at first row first column. Represents scale along X axis.|
|m12|Gets the matrix element at first row second column. Represents shear along Y axis.|
|m21|Gets the matrix element at second row first column. Represents shear along X axis.|
|m22|Gets the matrix element at second row second column. Represents scale along Y axis.|
|m31|Gets the matrix element at third row first column. Represents translation along X axis.|
|m32|Gets the matrix element at third row first column. Represents translation along Y axis.|
|TYPE_IDENTITY|An identity transform is one in which the output coordinates are<br/>            always the same as the input coordinates.<br/>            If this transform is anything other than the identity transform,<br/>            the type will either be the constant GENERAL_TRANSFORM or a<br/>            combination of the appropriate flag bits for the various coordinate<br/>            conversions that this transform performs.|
|TYPE_TRANSLATION|A translation moves the coordinates by a constant amount in x<br/>            and y without changing the length or angle of vectors.|
|TYPE_UNIFORM_SCALE|A uniform scale multiplies the length of vectors by the same amount<br/>            in both the x and y directions without changing the angle between<br/>            vectors.<br/>            This flag bit is mutually exclusive with the TypeGeneralScale flag.|
|TYPE_GENERAL_SCALE|A general scale multiplies the length of vectors by different<br/>            amounts in the x and y directions without changing the angle<br/>            between perpendicular vectors.<br/>            This flag bit is mutually exclusive with the TypeUniformScale flag.|
|TYPE_MASK_SCALE|This constant is a bit mask for any of the scale flag bits.|
|TYPE_FLIP|This flag bit indicates that the transform defined by this object<br/>            performs a mirror image flip about some axis which changes the<br/>            normally right handed coordinate system into a left handed<br/>            system in addition to the conversions indicated by other flag bits.<br/>            A right handed coordinate system is one where the positive X<br/>            axis rotates counterclockwise to overlay the positive Y axis<br/>            similar to the direction that the fingers on your right hand<br/>            curl when you stare end on at your thumb.<br/>            A left handed coordinate system is one where the positive X<br/>            axis rotates clockwise to overlay the positive Y axis similar<br/>            to the direction that the fingers on your left hand curl.<br/>            There is no mathematical way to determine the angle of the<br/>            original flipping or mirroring transformation since all angles<br/>            of flip are identical given an appropriate adjusting rotation.<br/>            NOTE: TypeFlip was added after GENERAL_TRANSFORM was in public<br/>            circulation and the flag bits could no longer be conveniently<br/>            renumbered without introducing binary incompatibility in outside<br/>            code.|
|TYPE_QUADRANT_ROTATION|This flag bit indicates that the transform defined by this object<br/>            performs a quadrant rotation by some multiple of 90 degrees in<br/>            addition to the conversions indicated by other flag bits.<br/>            A rotation changes the angles of vectors by the same amount<br/>            regardless of the original direction of the vector and without<br/>            changing the length of the vector.<br/>            This flag bit is mutually exclusive with the TypeGeneralRotation flag.|
|TYPE_GENERAL_ROTATION|This flag bit indicates that the transform defined by this object<br/>            performs a rotation by an arbitrary angle in addition to the<br/>            conversions indicated by other flag bits.<br/>            A rotation changes the angles of vectors by the same amount<br/>            regardless of the original direction of the vector and without<br/>            changing the length of the vector.<br/>            This flag bit is mutually exclusive with the|
|TYPE_MASK_ROTATION|This constant is a bit mask for any of the rotation flag bits.|
|TYPE_GENERAL_TRANSFORM|This constant indicates that the transform defined by this object<br/>            performs an arbitrary conversion of the input coordinates.<br/>            If this transform can be classified by any of the above constants,<br/>            the type will either be the constant TypeIdentity or a<br/>            combination of the appropriate flag bits for the various coordinate<br/>            conversions that this transform performs.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|scale(scale_x, scale_y, order)|Applies the specified scale vector (scaleX and scaleY) to this [Matrix](/imaging/python-net/api-reference/aspose.imaging/matrix/) using the specified order.|
|scale(sx, sy)|Applies the specified scale vector (scaleX and scaleY) to this [Matrix](/imaging/python-net/api-reference/aspose.imaging/matrix/) using the specified order.|
|translate(offset_x, offset_y, order)|Applies the specified translation vector to this Matrix in the specified order.|
|translate(tx, ty)|Applies the specified translation vector to this Matrix in the specified order.|
|multiply(tx, order)|Multiplies this Matrix by the matrix specified in the matrix parameter, and in the order specified in the order parameter.|
|multiply(tx)|Multiplies this Matrix by the matrix specified in the matrix parameter, and in the order specified in the order parameter.|
|rotate(angle, order)|Applies a clockwise rotation of an amount specified in the angle parameter, around the origin (zero x and y coordinates) for this Matrix in the specified order.|
|rotate(angle)|Applies a clockwise rotation of an amount specified in the angle parameter, around the origin (zero x and y coordinates) for this Matrix in the specified order.|
|rotate_at(angle, point, order)|Applies a clockwise rotation about the specified point to this Matrix in the specified order.|
|rotate_at(angle, point)|Applies a clockwise rotation about the specified point to this Matrix in the specified order.|
|create_with_rect_f(rect, plgpts)|Initializes a new instance of the [Matrix](/imaging/python-net/api-reference/aspose.imaging/matrix/) class to the geometric transform defined by the specified rectangle and array of points.|
|create_with_rect(rect, plgpts)|Initializes a new instance of the [Matrix](/imaging/python-net/api-reference/aspose.imaging/matrix/) class to the geometric transform defined by the specified rectangle and array of points.|
|get_elements()|Gets the copy of matrix elements.|
|transform_points(points)|Applies the geometric transform represented by this [Matrix](/imaging/python-net/api-reference/aspose.imaging/matrix/) to a specified array of points.|
|reset()|Resets this Matrix to have the elements of the identity matrix.|
