---
title: "Matrix.Matrix"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Matrix 构造函数。将 Matrix 类的新实例初始化为单位矩阵"
type: docs
weight: 10
url: /zh/net/aspose.imaging/matrix/matrix/
---
## Matrix() {#constructor}

将 Matrix 类初始化为单位矩阵的新实例。

```csharp
public Matrix()
```

### 另请参见

* class [Matrix](../)
* namespace [Aspose.Imaging](../../matrix/)
* assembly [Aspose.Imaging](../../../)

---

## Matrix(float, float, float, float, float, float) {#constructor_4}

初始化一个 [`Matrix`](../) 类的新实例。

```csharp
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| m11 | 单精度 | m00 M11 缩放 X |
| m12 | 单精度 | m10 M12 剪切 Y |
| m21 | 单精度 | m01 M21 剪切 X |
| m22 | 单精度 | m11 M22 缩放 Y |
| m31 | 单精度 | m02 M31 平移 X |
| m32 | 单精度 | m12 M32 平移 Y |

### 另请参见

* class [Matrix](../)
* namespace [Aspose.Imaging](../../matrix/)
* assembly [Aspose.Imaging](../../../)

---

## Matrix(RectangleF, PointF[]) {#constructor_3}

初始化一个新的 [`Matrix`](../) 类实例，以进行由指定矩形和点数组定义的几何变换。

```csharp
public Matrix(RectangleF rect, PointF[] plgpts)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | RectangleF | 一个表示待变换矩形的 [`RectangleF`](../../rectanglef/) 结构体。 |
| plgpts | PointF[] | 一个包含三个 [`PointF`](../../pointf/) 结构体的数组，表示要将矩形的左上、右上和左下角变换到的平行四边形的三个点。平行四边形的右下角由前面三个角隐含。 |

### 另请参见

* struct [RectangleF](../../rectanglef/)
* struct [PointF](../../pointf/)
* class [Matrix](../)
* namespace [Aspose.Imaging](../../matrix/)
* assembly [Aspose.Imaging](../../../)

---

## Matrix(Rectangle, Point[]) {#constructor_2}

初始化一个新的 [`Matrix`](../) 类实例，以进行由指定矩形和点数组定义的几何变换。

```csharp
public Matrix(Rectangle rect, Point[] plgpts)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 一个表示待变换矩形的 [`Rectangle`](../../rectangle/) 结构体。 |
| plgpts | Point[] | 一个包含三个 [`Point`](../../point/) 结构体的数组，表示要将矩形的左上、右上和左下角变换到的平行四边形的三个点。平行四边形的右下角由前面三个角隐含。 |

### 另请参见

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [Matrix](../)
* namespace [Aspose.Imaging](../../matrix/)
* assembly [Aspose.Imaging](../../../)

---

## Matrix(Matrix) {#constructor_1}

创建 [`Matrix`](../) 类的副本。

```csharp
public Matrix(Matrix origin)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| origin | 矩阵 | 用于复制的基础矩阵。 |

### 另请参见

* class [Matrix](../)
* namespace [Aspose.Imaging](../../matrix/)
* assembly [Aspose.Imaging](../../../)


