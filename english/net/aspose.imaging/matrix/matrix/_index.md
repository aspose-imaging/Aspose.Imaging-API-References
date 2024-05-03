---
title: Matrix.Matrix
second_title: Aspose.Imaging for .NET API Reference
description: Matrix constructor. Initializes a new instance of the Matrix class as the identity matrix
type: docs
weight: 10
url: /net/aspose.imaging/matrix/matrix/
---
## Matrix() {#constructor}

Initializes a new instance of the Matrix class as the identity matrix.

```csharp
public Matrix()
```

### See Also

* class [Matrix](../)
* namespace [Aspose.Imaging](../../matrix/)
* assembly [Aspose.Imaging](../../../)

---

## Matrix(float, float, float, float, float, float) {#constructor_4}

Initializes a new instance of the [`Matrix`](../) class.

```csharp
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```

| Parameter | Type | Description |
| --- | --- | --- |
| m11 | Single | m00 M11 Scale X |
| m12 | Single | m10 M12 Shear Y |
| m21 | Single | m01 M21 Shear X |
| m22 | Single | m11 M22 Scale Y |
| m31 | Single | m02 M31 Translate X |
| m32 | Single | m12 M32 Translate Y |

### See Also

* class [Matrix](../)
* namespace [Aspose.Imaging](../../matrix/)
* assembly [Aspose.Imaging](../../../)

---

## Matrix(RectangleF, PointF[]) {#constructor_3}

Initializes a new instance of the [`Matrix`](../) class to the geometric transform defined by the specified rectangle and array of points.

```csharp
public Matrix(RectangleF rect, PointF[] plgpts)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | RectangleF | A [`RectangleF`](../../rectanglef/) structure that represents the rectangle to be transformed. |
| plgpts | PointF[] | An array of three [`PointF`](../../pointf/) structures that represents the points of a parallelogram to which the upper-left, upper-right, and lower-left corners of the rectangle is to be transformed. The lower-right corner of the parallelogram is implied by the first three corners. |

### See Also

* struct [RectangleF](../../rectanglef/)
* struct [PointF](../../pointf/)
* class [Matrix](../)
* namespace [Aspose.Imaging](../../matrix/)
* assembly [Aspose.Imaging](../../../)

---

## Matrix(Rectangle, Point[]) {#constructor_2}

Initializes a new instance of the [`Matrix`](../) class to the geometric transform defined by the specified rectangle and array of points.

```csharp
public Matrix(Rectangle rect, Point[] plgpts)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | A [`Rectangle`](../../rectangle/) structure that represents the rectangle to be transformed. |
| plgpts | Point[] | An array of three [`Point`](../../point/) structures that represents the points of a parallelogram to which the upper-left, upper-right, and lower-left corners of the rectangle is to be transformed. The lower-right corner of the parallelogram is implied by the first three corners. |

### See Also

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [Matrix](../)
* namespace [Aspose.Imaging](../../matrix/)
* assembly [Aspose.Imaging](../../../)

---

## Matrix(Matrix) {#constructor_1}

Makes a copy of the [`Matrix`](../) class.

```csharp
public Matrix(Matrix origin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| origin | Matrix | A base matrix for coping |

### See Also

* class [Matrix](../)
* namespace [Aspose.Imaging](../../matrix/)
* assembly [Aspose.Imaging](../../../)


