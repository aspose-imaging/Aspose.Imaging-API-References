---
title: "Matrix"
second_title: "Aspose.Imaging for Java API 参考"
description: "替换 GDI 矩阵。"
type: docs
weight: 72
url: /zh/java/com.aspose.imaging/matrix/
---
**Inheritance:**
java.lang.Object
```
public class Matrix
```

替代 GDI+ 矩阵。

--------------------

大多数算法取自 Sun 的 AffineTransform.java。内部使用 Java 的矩阵元素名称。Java 名称到 .net 名称的映射及说明：m00 M11 缩放 X m10 M12 剪切 Y m01 M21 剪切 X m11 M22 缩放 Y m02 M31 平移 X m12 M32 平移 Y
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Matrix()](#Matrix--) | 将 Matrix 类初始化为单位矩阵的新实例。 |
| [Matrix(float m11, float m12, float m21, float m22, float m31, float m32)](#Matrix-float-float-float-float-float-float-) | 将 [Matrix](../../com.aspose.imaging/matrix) 类初始化为新实例。 |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.imaging.RectangleF-com.aspose.imaging.PointF---) | 将 [Matrix](../../com.aspose.imaging/matrix) 类初始化为由指定矩形和点数组定义的几何变换的新实例。 |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.imaging.Rectangle-com.aspose.imaging.Point---) | 将 [Matrix](../../com.aspose.imaging/matrix) 类初始化为由指定矩形和点数组定义的几何变换的新实例。 |
| [Matrix(Matrix origin)](#Matrix-com.aspose.imaging.Matrix-) | 创建 [Matrix](../../com.aspose.imaging/matrix) 类的副本。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [TYPE_IDENTITY](#TYPE-IDENTITY) | 单位变换是指输出坐标始终与输入坐标相同的变换。 |
| [TYPE_TRANSLATION](#TYPE-TRANSLATION) | 平移在 x 和 y 方向上以恒定量移动坐标，而不改变向量的长度或角度。 |
| [TYPE_UNIFORM_SCALE](#TYPE-UNIFORM-SCALE) | 均匀缩放在 x 和 y 方向上以相同的比例乘以向量的长度，而不改变向量之间的角度。 |
| [TYPE_GENERAL_SCALE](#TYPE-GENERAL-SCALE) | 一般缩放在 x 和 y 方向上以不同的比例乘以向量的长度，而不改变垂直向量之间的角度。 |
| [TYPE_MASK_SCALE](#TYPE-MASK-SCALE) | 此常量是用于任意缩放标志位的位掩码。 |
| [TYPE_FLIP](#TYPE-FLIP) | 此标志位表示此对象定义的变换在某轴上执行镜像翻转，除了其他标志位指示的转换外，还将通常的右手坐标系转换为左手坐标系。 |
| [TYPE_QUADRANT_ROTATION](#TYPE-QUADRANT-ROTATION) | 此标志位表示此对象定义的变换在执行某个 90 度倍数的象限旋转，除了其他标志位指示的转换外。 |
| [TYPE_GENERAL_ROTATION](#TYPE-GENERAL-ROTATION) | 此标志位表示此对象定义的变换在执行任意角度的旋转，除了其他标志位指示的转换外。 |
| [TYPE_MASK_ROTATION](#TYPE-MASK-ROTATION) | 此常量是用于任意旋转标志位的位掩码。 |
| [TYPE_GENERAL_TRANSFORM](#TYPE-GENERAL-TRANSFORM) | 此常量表示此对象定义的变换对输入坐标执行任意转换。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [isEquals(Matrix a, Matrix b)](#isEquals-com.aspose.imaging.Matrix-com.aspose.imaging.Matrix-) | 确定两个矩阵是否相等。 |
| [getM11()](#getM11--) | 获取第一行第一列的矩阵元素。 |
| [getM12()](#getM12--) | 获取第一行第二列的矩阵元素。 |
| [getM21()](#getM21--) | 获取第二行第一列的矩阵元素。 |
| [getM22()](#getM22--) | 获取第二行第二列的矩阵元素。 |
| [getM31()](#getM31--) | 获取第三行第一列的矩阵元素。 |
| [getM32()](#getM32--) | 获取第三行第一列的矩阵元素。 |
| [toString()](#toString--) | 返回表示此实例的字符串。 |
| [getElements()](#getElements--) | 获取矩阵元素的副本。 |
| [transformPoints(PointF[] points)](#transformPoints-com.aspose.imaging.PointF---) | 对指定的点数组应用此 [Matrix](../../com.aspose.imaging/matrix) 所表示的几何变换。 |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | 使用指定的顺序将指定的缩放向量（scaleX 和 scaleY）应用于此 [Matrix](../../com.aspose.imaging/matrix)。 |
| [scale(float sx, float sy)](#scale-float-float-) | 使用（默认）Prepend 顺序将指定的缩放向量（scaleX 和 scaleY）应用于此 Matrix。 |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | 在指定顺序下，将指定的平移向量应用于此 Matrix。 |
| [translate(float tx, float ty)](#translate-float-float-) | 在（默认）Prepend 顺序下，将指定的平移向量应用于此 [Matrix](../../com.aspose.imaging/matrix)。 |
| [multiply(Matrix tTx, int order)](#multiply-com.aspose.imaging.Matrix-int-) | 将此 Matrix 与 matrix 参数中指定的矩阵相乘，并按 order 参数中指定的顺序进行。 |
| [multiply(Matrix tTx)](#multiply-com.aspose.imaging.Matrix-) | 在（默认）Prepend 顺序下，将此 Matrix 与 matrix 参数中指定的矩阵相乘。 |
| [rotate(float angle, int order)](#rotate-float-int-) | 在指定顺序下，对此 Matrix 进行顺时针旋转，旋转角度由 angle 参数指定，围绕原点（零 x 和 y 坐标）进行。 |
| [rotate(float angle)](#rotate-float-) | 在默认（Prepend）顺序下，对此 Matrix 进行顺时针旋转，旋转角度由 angle 参数指定，围绕原点（零 x 和 y 坐标）进行。 |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.imaging.PointF-int-) | 在指定顺序下，对此 Matrix 进行关于指定点的顺时针旋转。 |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.imaging.PointF-) | 在默认（Prepend）顺序下，对此 Matrix 进行关于指定点的顺时针旋转。 |
| [reset()](#reset--) | 将此 Matrix 重置为单位矩阵。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 `Object` 是否等于此实例。 |
| [isIdentity()](#isIdentity--) | 如果此 `AffineTransform` 是单位变换，则返回 `true`。 |
### Matrix() {#Matrix--}
```
public Matrix()
```


将 Matrix 类初始化为单位矩阵的新实例。

### Matrix(float m11, float m12, float m21, float m22, float m31, float m32) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```


将 [Matrix](../../com.aspose.imaging/matrix) 类初始化为新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| m11 | float | m00 M11 缩放 X |
| m12 | float | m10 M12 剪切 Y |
| m21 | float | m01 M21 剪切 X |
| m22 | float | m11 M22 缩放 Y |
| m31 | float | m02 M31 平移 X |
| m32 | float | m12 M32 平移 Y |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.imaging.RectangleF-com.aspose.imaging.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


将 [Matrix](../../com.aspose.imaging/matrix) 类初始化为由指定矩形和点数组定义的几何变换的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | 一个表示要转换的矩形的 [RectangleF](../../com.aspose.imaging/rectanglef) 结构。 |
| plgpts | [PointF\[\]](../../com.aspose.imaging/pointf) | 一个包含三个 [PointF](../../com.aspose.imaging/pointf) 结构的数组，表示用于将矩形的左上角、右上角和左下角转换后的平行四边形的点。平行四边形的右下角由前面三个角隐含。 |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.imaging.Rectangle-com.aspose.imaging.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


将 [Matrix](../../com.aspose.imaging/matrix) 类初始化为由指定矩形和点数组定义的几何变换的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | 表示要转换的矩形的 [Rectangle](../../com.aspose.imaging/rectangle) 结构。 |
| plgpts | [Point\[\]](../../com.aspose.imaging/point) | 一个包含三个 [Point](../../com.aspose.imaging/point) 结构的数组，表示要将矩形的左上、右上和左下角转换到的平行四边形的三个顶点。平行四边形的右下角由前面三个顶点隐含。 |

### Matrix(Matrix origin) {#Matrix-com.aspose.imaging.Matrix-}
```
public Matrix(Matrix origin)
```


创建 [Matrix](../../com.aspose.imaging/matrix) 类的副本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| origin | [Matrix](../../com.aspose.imaging/matrix) | 用于配合的基矩阵。 |

### TYPE_IDENTITY {#TYPE-IDENTITY}
```
public static final int TYPE_IDENTITY
```


恒等变换是指输出坐标始终与输入坐标相同的变换。如果该变换不是恒等变换，则其类型将是常量 GENERAL\_TRANSFORM，或是针对该变换执行的各种坐标转换的相应标志位的组合。

### TYPE_TRANSLATION {#TYPE-TRANSLATION}
```
public static final int TYPE_TRANSLATION
```


平移在 x 和 y 方向上以恒定量移动坐标，而不改变向量的长度或角度。

### TYPE_UNIFORM_SCALE {#TYPE-UNIFORM-SCALE}
```
public static final int TYPE_UNIFORM_SCALE
```


统一缩放在 x 和 y 方向上以相同的比例乘以向量的长度，且不改变向量之间的角度。此标志位与 TypeGeneralScale 标志互斥。

### TYPE_GENERAL_SCALE {#TYPE-GENERAL-SCALE}
```
public static final int TYPE_GENERAL_SCALE
```


通用缩放在 x 和 y 方向上以不同的比例乘以向量的长度，且不改变垂直向量之间的角度。此标志位与 TypeUniformScale 标志互斥。

### TYPE_MASK_SCALE {#TYPE-MASK-SCALE}
```
public static final int TYPE_MASK_SCALE
```


此常量是用于任意缩放标志位的位掩码。

### TYPE_FLIP {#TYPE-FLIP}
```
public static final int TYPE_FLIP
```


此标志位表示由该对象定义的变换在某一轴上执行镜像翻转，除了其他标志位指示的转换外，还将通常的右手坐标系转换为左手坐标系。右手坐标系指正 X 轴逆时针旋转以覆盖正 Y 轴，类似于右手拇指指向观察方向时手指的卷曲方向。左手坐标系指正 X 轴顺时针旋转以覆盖正 Y 轴，类似于左手拇指指向观察方向时手指的卷曲方向。由于在适当的调整旋转下所有翻转角度相同，无法通过数学方式确定原始翻转或镜像变换的角度。注意：TypeFlip 是在 GENERAL\_TRANSFORM 已公开流通后添加的，因而无法方便地重新编号标志位，否则会在外部代码中引入二进制不兼容。

### TYPE_QUADRANT_ROTATION {#TYPE-QUADRANT-ROTATION}
```
public static final int TYPE_QUADRANT_ROTATION
```


此标志位表示由该对象定义的变换在执行其他标志位指示的转换之外，还进行以 90 度的整数倍为单位的象限旋转。旋转会以相同的角度改变向量的方向，而不改变向量的长度。此标志位与 TypeGeneralRotation 标志互斥。

### TYPE_GENERAL_ROTATION {#TYPE-GENERAL-ROTATION}
```
public static final int TYPE_GENERAL_ROTATION
```


此标志位表示由该对象定义的变换在执行其他标志位指示的转换之外，还进行任意角度的旋转。旋转会以相同的角度改变向量的方向，而不改变向量的长度。此标志位与

### TYPE_MASK_ROTATION {#TYPE-MASK-ROTATION}
```
public static final int TYPE_MASK_ROTATION
```


此常量是用于任意旋转标志位的位掩码。

### TYPE_GENERAL_TRANSFORM {#TYPE-GENERAL-TRANSFORM}
```
public static final int TYPE_GENERAL_TRANSFORM
```


此常量表示由该对象定义的变换对输入坐标进行任意转换。如果该变换可以归类于上述任意常量，则其类型将是常量 TypeIdentity，或是针对该变换执行的各种坐标转换的相应标志位的组合。

### isEquals(Matrix a, Matrix b) {#isEquals-com.aspose.imaging.Matrix-com.aspose.imaging.Matrix-}
```
public static boolean isEquals(Matrix a, Matrix b)
```


确定两个矩阵是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Matrix](../../com.aspose.imaging/matrix) | 要比较的第一个矩阵。 |
| b | [Matrix](../../com.aspose.imaging/matrix) | 要比较的第二个矩阵。 |

**Returns:**
boolean - 如果矩阵相等则为 True。
### getM11() {#getM11--}
```
public final float getM11()
```


获取第一行第一列的矩阵元素。表示沿 X 轴的缩放。

**Returns:**
float - 第一行第一列的矩阵元素。
### getM12() {#getM12--}
```
public final float getM12()
```


获取第一行第二列的矩阵元素。表示沿 Y 轴的剪切。

**Returns:**
float - 第一行第二列的矩阵元素。
### getM21() {#getM21--}
```
public final float getM21()
```


获取第二行第一列的矩阵元素。表示沿 X 轴的剪切。

**Returns:**
float - 第二行第一列的矩阵元素。
### getM22() {#getM22--}
```
public final float getM22()
```


获取第二行第二列的矩阵元素。表示沿 Y 轴的缩放。

**Returns:**
float - 第二行第二列的矩阵元素。
### getM31() {#getM31--}
```
public final float getM31()
```


获取第三行第一列的矩阵元素。表示沿 X 轴的平移。

**Returns:**
float - 第三行第一列的矩阵元素。
### getM32() {#getM32--}
```
public final float getM32()
```


获取第三行第一列的矩阵元素。表示沿 Y 轴的平移。

**Returns:**
float - 第三行第一列的矩阵元素。
### toString() {#toString--}
```
public String toString()
```


返回表示此实例的字符串。

**Returns:**
java.lang.String - 表示此实例的字符串。
### getElements() {#getElements--}
```
public final float[] getElements()
```


获取矩阵元素的副本。

**Returns:**
float[] - 矩阵元素的副本。
### transformPoints(PointF[] points) {#transformPoints-com.aspose.imaging.PointF---}
```
public final void transformPoints(PointF[] points)
```


对指定的点数组应用此 [Matrix](../../com.aspose.imaging/matrix) 所表示的几何变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | 这些点。 |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public final void scale(float scaleX, float scaleY, int order)
```


使用指定的顺序将指定的缩放向量（scaleX 和 scaleY）应用于此 [Matrix](../../com.aspose.imaging/matrix)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scaleX | float | X 轴比例。 |
| scaleY | float | Y 轴比例。 |
| order | int | 顺序。 |

### scale(float sx, float sy) {#scale-float-float-}
```
public final void scale(float sx, float sy)
```


使用（默认）Prepend 顺序将指定的缩放向量（scaleX 和 scaleY）应用于此 Matrix。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sx | float | 该 sx。该 sx。该 sx。 |
| sy | float | 该 sy。该 sy。该 sy。 |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public final void translate(float offsetX, float offsetY, int order)
```


在指定顺序下，将指定的平移向量应用于此 Matrix。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| offsetX | float | X 偏移。 |
| offsetY | float | Y 偏移。 |
| order | int | 顺序。 |

### translate(float tx, float ty) {#translate-float-float-}
```
public final void translate(float tx, float ty)
```


在（默认）Prepend 顺序下，将指定的平移向量应用于此 [Matrix](../../com.aspose.imaging/matrix)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tx | float | 该 tx。该 tx。该 tx。 |
| ty | float | 该 ty。该 ty。该 ty。 |

### multiply(Matrix tTx, int order) {#multiply-com.aspose.imaging.Matrix-int-}
```
public final void multiply(Matrix tTx, int order)
```


将此 Matrix 与 matrix 参数中指定的矩阵相乘，并按 order 参数中指定的顺序进行。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tTx | [Matrix](../../com.aspose.imaging/matrix) | 该 tx。该 tx。该 tx。 |
| order | int | 顺序。顺序。顺序。 |

### multiply(Matrix tTx) {#multiply-com.aspose.imaging.Matrix-}
```
public final void multiply(Matrix tTx)
```


在（默认）Prepend 顺序下，将此 Matrix 与 matrix 参数中指定的矩阵相乘。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tTx | [Matrix](../../com.aspose.imaging/matrix) | 用于相乘的矩阵。 |

### rotate(float angle, int order) {#rotate-float-int-}
```
public final void rotate(float angle, int order)
```


在指定顺序下，对此 Matrix 进行顺时针旋转，旋转角度由 angle 参数指定，围绕原点（零 x 和 y 坐标）进行。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| angle | float | 旋转角度。 |
| order | int | 矩阵顺序。 |

### rotate(float angle) {#rotate-float-}
```
public final void rotate(float angle)
```


在默认（Prepend）顺序下，对此 Matrix 进行顺时针旋转，旋转角度由 angle 参数指定，围绕原点（零 x 和 y 坐标）进行。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| angle | float | 旋转角度。 |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.imaging.PointF-int-}
```
public final void rotateAt(float angle, PointF point, int order)
```


在指定顺序下，对此 Matrix 进行关于指定点的顺时针旋转。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| angle | float | 角度。 |
| point | [PointF](../../com.aspose.imaging/pointf) | 该点。 |
| order | int | 顺序。 |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.imaging.PointF-}
```
public final void rotateAt(float angle, PointF point)
```


在默认（Prepend）顺序下，对此 Matrix 进行关于指定点的顺时针旋转。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| angle | float | 角度。 |
| point | [PointF](../../com.aspose.imaging/pointf) | 该点。 |

### reset() {#reset--}
```
public final void reset()
```


将此 Matrix 重置为单位矩阵。

### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和哈希表等数据结构。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的 `Object` 是否等于此实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的 `Object`。 |

**Returns:**
布尔值 - 如果指定的 `Object` 等于此实例，则为 `true`；否则为 `false`。
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


如果此 `AffineTransform` 是单位变换，则返回 `true`。

**Returns:**
布尔值 - 如果此 `AffineTransform` 是恒等变换，则为 `true`；否则为 `false`。
