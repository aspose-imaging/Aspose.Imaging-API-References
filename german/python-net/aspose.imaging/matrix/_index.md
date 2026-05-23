---
title: "Matrix-Klasse"
type: docs
weight: 6070
url: /de/python-net/aspose.imaging/matrix/
---

**Summary:** Replaces the GDI+ Matrix.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Matrix

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Matrix()](#Matrix__1) | Initialisiert eine neue Instanz der Matrix-Klasse als Einheitsmatrix. |
| [Matrix(m11, m12, m21, m22, m31, m32)](#Matrix_m11_m12_m21_m22_m31_m32_2) | Initialisiert eine neue Instanz der [Matrix](/imaging/python-net/aspose.imaging/matrix/) Klasse. |
| [Matrix(origin)](#Matrix_origin_3) | Erstellt eine Kopie der [Matrix](/imaging/python-net/aspose.imaging/matrix/) Klasse. |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_4) | Initialisiert eine neue Instanz der [Matrix](/imaging/python-net/aspose.imaging/matrix/) Klasse mit der geometrischen Transformation, die durch das angegebene Rechteck und das Punkte-Array definiert ist. |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_5) | Initialisiert eine neue Instanz der [Matrix](/imaging/python-net/aspose.imaging/matrix/) Klasse mit der geometrischen Transformation, die durch das angegebene Rechteck und das Punkte-Array definiert ist. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| TYPE_FLIP [statisch] | int | r | This flag bit indicates that the transform defined by this object<br/>            performs a mirror image flip about some axis which changes the<br/>            normally right handed coordinate system into a left handed<br/>            system in addition to the conversions indicated by other flag bits.<br/>            A right handed coordinate system is one where the positive X<br/>            axis rotates counterclockwise to overlay the positive Y axis<br/>            similar to the direction that the fingers on your right hand<br/>            curl when you stare end on at your thumb.<br/>            A left handed coordinate system is one where the positive X<br/>            axis rotates clockwise to overlay the positive Y axis similar<br/>            to the direction that the fingers on your left hand curl.<br/>            There is no mathematical way to determine the angle of the<br/>            original flipping or mirroring transformation since all angles<br/>            of flip are identical given an appropriate adjusting rotation.<br/>            NOTE: TypeFlip was added after GENERAL_TRANSFORM was in public<br/>            circulation and the flag bits could no longer be conveniently<br/>            renumbered without introducing binary incompatibility in outside<br/>            code. |
| TYPE_GENERAL_ROTATION [static] | int | r | This flag bit indicates that the transform defined by this object<br/>            performs a rotation by an arbitrary angle in addition to the<br/>            conversions indicated by other flag bits.<br/>            A rotation changes the angles of vectors by the same amount<br/>            regardless of the original direction of the vector and without<br/>            changing the length of the vector.<br/>            This flag bit is mutually exclusive with the |
| TYPE_GENERAL_SCALE [static] | int | r | A general scale multiplies the length of vectors by different<br/>            amounts in the x and y directions without changing the angle<br/>            between perpendicular vectors.<br/>            This flag bit is mutually exclusive with the TypeUniformScale flag. |
| TYPE_GENERAL_TRANSFORM [static] | int | r | This constant indicates that the transform defined by this object<br/>            performs an arbitrary conversion of the input coordinates.<br/>            If this transform can be classified by any of the above constants,<br/>            the type will either be the constant TypeIdentity or a<br/>            combination of the appropriate flag bits for the various coordinate<br/>            conversions that this transform performs. |
| TYPE_IDENTITY [static] | int | r | An identity transform is one in which the output coordinates are<br/>            always the same as the input coordinates.<br/>            If this transform is anything other than the identity transform,<br/>            the type will either be the constant GENERAL_TRANSFORM or a<br/>            combination of the appropriate flag bits for the various coordinate<br/>            conversions that this transform performs. |
| TYPE_MASK_ROTATION [static] | int | r | This constant is a bit mask for any of the rotation flag bits. |
| TYPE_MASK_SCALE [static] | int | r | This constant is a bit mask for any of the scale flag bits. |
| TYPE_QUADRANT_ROTATION [static] | int | r | This flag bit indicates that the transform defined by this object<br/>            performs a quadrant rotation by some multiple of 90 degrees in<br/>            addition to the conversions indicated by other flag bits.<br/>            A rotation changes the angles of vectors by the same amount<br/>            regardless of the original direction of the vector and without<br/>            changing the length of the vector.<br/>            This flag bit is mutually exclusive with the TypeGeneralRotation flag. |
| TYPE_TRANSLATION [static] | int | r | A translation moves the coordinates by a constant amount in x<br/>            and y without changing the length or angle of vectors. |
| TYPE_UNIFORM_SCALE [static] | int | r | A uniform scale multiplies the length of vectors by the same amount<br/>            in both the x and y directions without changing the angle between<br/>            vectors.<br/>            This flag bit is mutually exclusive with the TypeGeneralScale flag. |
| elements | float[] | r | Gets an array of floating-point values that represents the elements of this [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| m11 | float | r | Gets the matrix element at first row first column. Represents scale along X axis. |
| m12 | float | r | Gets the matrix element at first row second column. Represents shear along Y axis. |
| m21 | float | r | Liefert das Matrix-Element in der zweiten Zeile, ersten Spalte. Stellt eine Scherung entlang der X-Achse dar. |
| m22 | float | r | Liefert das Matrix-Element in der zweiten Zeile, zweiten Spalte. Stellt eine Skalierung entlang der Y-Achse dar. |
| m31 | float | r | Liefert das Matrix-Element in der dritten Zeile, ersten Spalte. Stellt eine Translation entlang der X-Achse dar. |
| m32 | float | r | Liefert das Matrix-Element in der dritten Zeile, ersten Spalte. Stellt eine Translation entlang der Y-Achse dar. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_with_rect(rect, plgpts)](#create_with_rect_rect_plgpts_1) | Initialisiert eine neue Instanz der [Matrix](/imaging/python-net/aspose.imaging/matrix/) Klasse mit der geometrischen Transformation, die durch das angegebene Rechteck und das Punkte-Array definiert ist. |
| [create_with_rect_f(rect, plgpts)](#create_with_rect_f_rect_plgpts_2) | Initialisiert eine neue Instanz der [Matrix](/imaging/python-net/aspose.imaging/matrix/) Klasse mit der geometrischen Transformation, die durch das angegebene Rechteck und das Punkte-Array definiert ist. |
| [get_elements()](#get_elements__3) | Liefert eine Kopie der Matrix-Elemente. |
| [multiply(t_tx)](#multiply_t_tx_4) | Multipliziert diese Matrix mit der im Matrix-Parameter angegebenen Matrix unter Verwendung der (default) Prepend‑Reihenfolge. |
| [multiply(t_tx, order)](#multiply_t_tx_order_5) | Multipliziert diese Matrix mit der im Matrix-Parameter angegebenen Matrix und in der im Order-Parameter angegebenen Reihenfolge. |
| reset() | Setzt diese Matrix zurück, sodass sie die Elemente der Einheitsmatrix enthält. |
| [rotate(angle)](#rotate_angle_6) | Wendet eine im Winkelparameter angegebene Drehung im Uhrzeigersinn um den Ursprung (null x‑ und y‑Koordinaten) für diese Matrix in der Standard‑(Prepend)‑Reihenfolge an. |
| [rotate(angle, order)](#rotate_angle_order_7) | Wendet eine im Winkelparameter angegebene Drehung im Uhrzeigersinn um den Ursprung (null x‑ und y‑Koordinaten) für diese Matrix in der angegebenen Reihenfolge an. |
| [rotate_at(angle, point)](#rotate_at_angle_point_8) | Wendet eine Drehung im Uhrzeigersinn um den angegebenen Punkt auf diese Matrix in der Standard‑(Prepend)‑Reihenfolge an. |
| [rotate_at(angle, point, order)](#rotate_at_angle_point_order_9) | Wendet eine Drehung im Uhrzeigersinn um den angegebenen Punkt auf diese Matrix in der angegebenen Reihenfolge an. |
| [scale(scale_x, scale_y, order)](#scale_scale_x_scale_y_order_10) | Wendet den angegebenen Skalierungsvektor (scaleX und scaleY) auf diese [Matrix](/imaging/python-net/aspose.imaging/matrix/) unter Verwendung der angegebenen Reihenfolge an. |
| [scale(sx, sy)](#scale_sx_sy_11) | Wendet den angegebenen Skalierungsvektor (scaleX und scaleY) auf diese Matrix unter Verwendung der (default) Prepend‑Reihenfolge an. |
| [transform_points(points)](#transform_points_points_12) | Wendet die von dieser [Matrix](/imaging/python-net/aspose.imaging/matrix/) dargestellte geometrische Transformation auf ein angegebenes Punktarray an. |
| [translate(offset_x, offset_y, order)](#translate_offset_x_offset_y_order_13) | Wendet den angegebenen Translationsvektor auf diese Matrix in der angegebenen Reihenfolge an. |
| [translate(tx, ty)](#translate_tx_ty_14) | Wendet den angegebenen Translationsvektor auf diese [Matrix](/imaging/python-net/aspose.imaging/matrix/) unter Verwendung der (default) Prepend‑Reihenfolge an. |


### Constructor: Matrix() {#Matrix__1}


```
 Matrix() 
```

Initialisiert eine neue Instanz der Matrix-Klasse als Einheitsmatrix.

### Constructor: Matrix(m11, m12, m21, m22, m31, m32) {#Matrix_m11_m12_m21_m22_m31_m32_2}


```
 Matrix(m11, m12, m21, m22, m31, m32) 
```

Initialisiert eine neue Instanz der [Matrix](/imaging/python-net/aspose.imaging/matrix/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| m11 | float | m00     M11     Skalierung X |
| m12 | float | m10     M12     Scherung Y |
| m21 | float | m01     M21     Scherung X |
| m22 | float | m11     M22     Skalierung Y |
| m31 | float | m02     M31     Translation X |
| m32 | float | m12     M32     Verschiebe Y |

### Constructor: Matrix(origin) {#Matrix_origin_3}


```
 Matrix(origin) 
```

Erstellt eine Kopie der [Matrix](/imaging/python-net/aspose.imaging/matrix/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| origin | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Eine Basismatrix zum Kopieren |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_4}


```
 Matrix(rect, plgpts) 
```

Initialisiert eine neue Instanz der [Matrix](/imaging/python-net/aspose.imaging/matrix/) Klasse mit der geometrischen Transformation, die durch das angegebene Rechteck und das Punkte-Array definiert ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die das zu transformierende Rechteck darstellt. |
| plgpts | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Ein Array von drei [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, das die Punkte eines Parallelogramms darstellt, zu dem die obere linke, obere rechte und untere linke Ecke des Rechtecks transformiert werden sollen. Die untere rechte Ecke des Parallelogramms wird durch die ersten drei Ecken impliziert. |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_5}


```
 Matrix(rect, plgpts) 
```

Initialisiert eine neue Instanz der [Matrix](/imaging/python-net/aspose.imaging/matrix/) Klasse mit der geometrischen Transformation, die durch das angegebene Rechteck und das Punkte-Array definiert ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die das zu transformierende Rechteck darstellt. |
| plgpts | [Point[]](/imaging/python-net/aspose.imaging/point/) | Ein Array von drei [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, das die Punkte eines Parallelogramms darstellt, zu dem die obere linke, obere rechte und untere linke Ecke des Rechtecks transformiert werden sollen. Die untere rechte Ecke des Parallelogramms wird durch die ersten drei Ecken impliziert. |

### Method: create_with_rect(rect, plgpts)  [static] {#create_with_rect_rect_plgpts_1}


```
 create_with_rect(rect, plgpts) 
```

Initialisiert eine neue Instanz der [Matrix](/imaging/python-net/aspose.imaging/matrix/) Klasse mit der geometrischen Transformation, die durch das angegebene Rechteck und das Punkte-Array definiert ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die das zu transformierende Rechteck darstellt. |
| plgpts | [Point[]](/imaging/python-net/aspose.imaging/point/) | Ein Array von drei [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, das die Punkte eines Parallelogramms darstellt, zu dem die obere linke, obere rechte und untere linke Ecke des Rechtecks transformiert werden sollen. Die untere rechte Ecke des Parallelogramms wird durch die ersten drei Ecken impliziert. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) |  |


### Method: create_with_rect_f(rect, plgpts)  [static] {#create_with_rect_f_rect_plgpts_2}


```
 create_with_rect_f(rect, plgpts) 
```

Initialisiert eine neue Instanz der [Matrix](/imaging/python-net/aspose.imaging/matrix/) Klasse mit der geometrischen Transformation, die durch das angegebene Rechteck und das Punkte-Array definiert ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die das zu transformierende Rechteck darstellt. |
| plgpts | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Ein Array von drei [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, das die Punkte eines Parallelogramms darstellt, zu dem die obere linke, obere rechte und untere linke Ecke des Rechtecks transformiert werden sollen. Die untere rechte Ecke des Parallelogramms wird durch die ersten drei Ecken impliziert. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) |  |


### Method: get_elements() {#get_elements__3}


```
 get_elements() 
```

Liefert eine Kopie der Matrix-Elemente.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| float[] | Eine Kopie der Matrixelemente. |


### Method: multiply(t_tx) {#multiply_t_tx_4}


```
 multiply(t_tx) 
```

Multipliziert diese Matrix mit der im Matrix-Parameter angegebenen Matrix unter Verwendung der (default) Prepend‑Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| t_tx | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Die Matrix, mit der multipliziert wird. |

### Method: multiply(t_tx, order) {#multiply_t_tx_order_5}


```
 multiply(t_tx, order) 
```

Multipliziert diese Matrix mit der im Matrix-Parameter angegebenen Matrix und in der im Order-Parameter angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| t_tx | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Der tx. Der tx. Der tx. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Die Reihenfolge. Die Reihenfolge. Die Reihenfolge. |

### Method: rotate(angle) {#rotate_angle_6}


```
 rotate(angle) 
```

Wendet eine im Winkelparameter angegebene Drehung im Uhrzeigersinn um den Ursprung (null x‑ und y‑Koordinaten) für diese Matrix in der Standard‑(Prepend)‑Reihenfolge an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel. |

### Method: rotate(angle, order) {#rotate_angle_order_7}


```
 rotate(angle, order) 
```

Wendet eine im Winkelparameter angegebene Drehung im Uhrzeigersinn um den Ursprung (null x‑ und y‑Koordinaten) für diese Matrix in der angegebenen Reihenfolge an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Die Matrixreihenfolge. |

### Method: rotate_at(angle, point) {#rotate_at_angle_point_8}


```
 rotate_at(angle, point) 
```

Wendet eine Drehung im Uhrzeigersinn um den angegebenen Punkt auf diese Matrix in der Standard‑(Prepend)‑Reihenfolge an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Winkel. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Der Punkt. |

### Method: rotate_at(angle, point, order) {#rotate_at_angle_point_order_9}


```
 rotate_at(angle, point, order) 
```

Wendet eine Drehung im Uhrzeigersinn um den angegebenen Punkt auf diese Matrix in der angegebenen Reihenfolge an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Winkel. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Der Punkt. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Die Reihenfolge. |

### Method: scale(scale_x, scale_y, order) {#scale_scale_x_scale_y_order_10}


```
 scale(scale_x, scale_y, order) 
```

Wendet den angegebenen Skalierungsvektor (scaleX und scaleY) auf diese [Matrix](/imaging/python-net/aspose.imaging/matrix/) unter Verwendung der angegebenen Reihenfolge an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| scale_x | float | Die Skalierung X. |
| scale_y | float | Die Skalierung Y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Die Reihenfolge. |

### Method: scale(sx, sy) {#scale_sx_sy_11}


```
 scale(sx, sy) 
```

Wendet den angegebenen Skalierungsvektor (scaleX und scaleY) auf diese Matrix unter Verwendung der (default) Prepend‑Reihenfolge an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| sx | float | Der sx. Der sx. Der sx. |
| sy | float | Der sy. Der sy. Der sy. |

### Method: transform_points(points) {#transform_points_points_12}


```
 transform_points(points) 
```

Wendet die von dieser [Matrix](/imaging/python-net/aspose.imaging/matrix/) dargestellte geometrische Transformation auf ein angegebenes Punktarray an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Die Punkte. |

### Method: translate(offset_x, offset_y, order) {#translate_offset_x_offset_y_order_13}


```
 translate(offset_x, offset_y, order) 
```

Wendet den angegebenen Translationsvektor auf diese Matrix in der angegebenen Reihenfolge an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| offset_x | float | Der Versatz X. |
| offset_y | float | Der Versatz Y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Die Reihenfolge. |

### Method: translate(tx, ty) {#translate_tx_ty_14}


```
 translate(tx, ty) 
```

Wendet den angegebenen Translationsvektor auf diese [Matrix](/imaging/python-net/aspose.imaging/matrix/) unter Verwendung der (default) Prepend‑Reihenfolge an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tx | float | Der tx. Der tx. Der tx. |
| ty | float | Der ty. Der ty. Der ty. |

