---
title: "Matrix 类"
type: docs
weight: 6070
url: /zh/python-net/aspose.imaging/matrix/
---

**Summary:** Replaces the GDI+ Matrix.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Matrix

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [Matrix()](#Matrix__1) | 将 Matrix 类的新实例初始化为单位矩阵。 |
| [Matrix(m11, m12, m21, m22, m31, m32)](#Matrix_m11_m12_m21_m22_m31_m32_2) | 将 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 类的新实例初始化。 |
| [Matrix(origin)](#Matrix_origin_3) | 复制 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 类。 |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_4) | 将 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 类的新实例初始化为由指定矩形和点数组定义的几何变换。 |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_5) | 将 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 类的新实例初始化为由指定矩形和点数组定义的几何变换。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| TYPE_FLIP [static] | int | r | 此标志位表示此对象定义的变换<br/>            执行关于某轴的镜像翻转，进而将通常的右手坐标系转换为左手坐标系<br/>            并且还会执行其他标志位指示的转换。<br/>            右手坐标系是指正 X 轴逆时针旋转以覆盖正 Y 轴，<br/>            类似于当你正面看向拇指时右手手指的卷曲方向。<br/>            左手坐标系是指正 X 轴顺时针旋转以覆盖正 Y 轴，<br/>            类似于左手手指的卷曲方向。<br/>            没有数学方法可以确定原始翻转或镜像变换的角度，因为在适当的调整旋转下，所有翻转角度都是相同的。<br/>            注意：TypeFlip 是在 GENERAL_TRANSFORM 已公开流通后添加的，<br/>            因此无法方便地重新编号标志位而不在外部代码中引入二进制不兼容。 |
| TYPE_GENERAL_ROTATION [static] | int | r | 此标志位表示此对象定义的变换<br/>            执行任意角度的旋转，并且还会执行其他标志位指示的转换。<br/>            旋转会以相同的量改变向量的角度，<br/>            与向量的原始方向无关且不改变向量的长度。<br/>            此标志位与 |
| TYPE_GENERAL_SCALE [static] | int | r | 通用缩放会在 x 和 y 方向上以不同的量乘以向量的长度，<br/>            而不改变垂直向量之间的角度。<br/>            此标志位与 TypeUniformScale 标志互斥。 |
| TYPE_GENERAL_TRANSFORM [static] | int | r | 此常量表示此对象定义的变换<br/>            对输入坐标执行任意转换。<br/>            如果此变换可以由上述任意常量分类，<br/>            类型将是常量 TypeIdentity，或是<br/>            适用于此变换执行的各种坐标转换的相应标志位的组合。 |
| TYPE_IDENTITY [static] | int | r | 恒等变换是指输出坐标始终与输入坐标相同的变换。<br/>            如果此变换不是恒等变换，<br/>            类型将是常量 GENERAL_TRANSFORM，或是<br/>            适用于此变换执行的各种坐标转换的相应标志位的组合。 |
| TYPE_MASK_ROTATION [static] | int | r | 此常量是用于任意旋转标志位的位掩码。 |
| TYPE_MASK_SCALE [static] | int | r | 此常量是用于任意缩放标志位的位掩码。 |
| TYPE_QUADRANT_ROTATION [static] | int | r | 此标志位表示此对象定义的变换<br/>            执行以 90 度的整数倍为单位的象限旋转，<br/>            并且还会执行其他标志位指示的转换。<br/>            旋转会以相同的量改变向量的角度，<br/>            与向量的原始方向无关且不改变向量的长度。<br/>            此标志位与 TypeGeneralRotation 标志互斥。 |
| TYPE_TRANSLATION [static] | int | r | 平移会在 x 和 y 方向上以恒定量移动坐标，<br/>            且不改变向量的长度或角度。 |
| TYPE_UNIFORM_SCALE [static] | int | r | 统一缩放会在 x 和 y 方向上以相同的量乘以向量的长度，<br/>            而不改变向量之间的角度。<br/>            此标志位与 TypeGeneralScale 标志互斥。 |
| elements | float[] | r | 获取一个浮点数数组，表示此 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 的元素。 |
| m11 | float | r | 获取矩阵第一行第一列的元素。表示沿 X 轴的缩放。 |
| m12 | float | r | 获取矩阵第一行第二列的元素。表示沿 Y 轴的剪切。 |
| m21 | float | r | 获取矩阵第二行第一列的元素。表示沿 X 轴的剪切。 |
| m22 | float | r | 获取矩阵第二行第二列的元素。表示沿 Y 轴的缩放。 |
| m31 | float | r | 获取矩阵第三行第一列的元素。表示沿 X 轴的平移。 |
| m32 | float | r | 获取矩阵第三行第一列的元素。表示沿 Y 轴的平移。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_with_rect(rect, plgpts)](#create_with_rect_rect_plgpts_1) | 将 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 类的新实例初始化为由指定矩形和点数组定义的几何变换。 |
| [create_with_rect_f(rect, plgpts)](#create_with_rect_f_rect_plgpts_2) | 将 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 类的新实例初始化为由指定矩形和点数组定义的几何变换。 |
| [get_elements()](#get_elements__3) | 获取矩阵元素的副本。 |
| [multiply(t_tx)](#multiply_t_tx_4) | 使用（默认）Prepend 顺序，将此 Matrix 与 matrix 参数中指定的矩阵相乘。 |
| [multiply(t_tx, order)](#multiply_t_tx_order_5) | 将此 Matrix 与 matrix 参数中指定的矩阵相乘，并按照 order 参数中指定的顺序进行。 |
| reset() | 将此 Matrix 重置为单位矩阵的元素。 |
| [rotate(angle)](#rotate_angle_6) | 在默认（Prepend）顺序下，对此 Matrix 应用以角度参数指定的量进行顺时针旋转，围绕原点（零 x 和 y 坐标）。 |
| [rotate(angle, order)](#rotate_angle_order_7) | 在指定的顺序下，对此 Matrix 应用以角度参数指定的量进行顺时针旋转，围绕原点（零 x 和 y 坐标）。 |
| [rotate_at(angle, point)](#rotate_at_angle_point_8) | 在默认（Prepend）顺序下，对此 Matrix 应用围绕指定点的顺时针旋转。 |
| [rotate_at(angle, point, order)](#rotate_at_angle_point_order_9) | 在指定的顺序下，对此 Matrix 应用围绕指定点的顺时针旋转。 |
| [scale(scale_x, scale_y, order)](#scale_scale_x_scale_y_order_10) | 使用指定的顺序，将指定的缩放向量（scaleX 和 scaleY）应用到此 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |
| [scale(sx, sy)](#scale_sx_sy_11) | 使用（默认）Prepend 顺序，将指定的缩放向量（scaleX 和 scaleY）应用到此 Matrix。 |
| [transform_points(points)](#transform_points_points_12) | 将此 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 所表示的几何变换应用于指定的点数组。 |
| [translate(offset_x, offset_y, order)](#translate_offset_x_offset_y_order_13) | 在指定的顺序下，将指定的平移向量应用到此 Matrix。 |
| [translate(tx, ty)](#translate_tx_ty_14) | 使用（默认）Prepend 顺序，将指定的平移向量应用到此 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |


### Constructor: Matrix() {#Matrix__1}


```
 Matrix() 
```

将 Matrix 类的新实例初始化为单位矩阵。

### Constructor: Matrix(m11, m12, m21, m22, m31, m32) {#Matrix_m11_m12_m21_m22_m31_m32_2}


```
 Matrix(m11, m12, m21, m22, m31, m32) 
```

将 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 类的新实例初始化。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| m11 | float | m00     M11     缩放 X |
| m12 | float | m10     M12     剪切 Y |
| m21 | float | m01     M21     剪切 X |
| m22 | float | m11     M22     缩放 Y |
| m31 | float | m02     M31     平移 X |
| m32 | float | m12     M32     平移 Y |

### Constructor: Matrix(origin) {#Matrix_origin_3}


```
 Matrix(origin) 
```

复制 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 类。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| origin | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 用于复制的基矩阵 |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_4}


```
 Matrix(rect, plgpts) 
```

将 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 类的新实例初始化为由指定矩形和点数组定义的几何变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 一个 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构，表示要进行变换的矩形。 |
| plgpts | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 一个包含三个 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构的数组，表示要将矩形的左上、右上和左下角变换到的平行四边形的三个点。平行四边形的右下角由前面三个角推断得到。 |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_5}


```
 Matrix(rect, plgpts) 
```

将 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 类的新实例初始化为由指定矩形和点数组定义的几何变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 一个 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构，表示要进行变换的矩形。 |
| plgpts | [Point[]](/imaging/python-net/aspose.imaging/point/) | 一个包含三个 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构的数组，表示要将矩形的左上、右上和左下角变换到的平行四边形的三个点。平行四边形的右下角由前面三个角推断得到。 |

### Method: create_with_rect(rect, plgpts)  [static] {#create_with_rect_rect_plgpts_1}


```
 create_with_rect(rect, plgpts) 
```

将 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 类的新实例初始化为由指定矩形和点数组定义的几何变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 一个 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构，表示要进行变换的矩形。 |
| plgpts | [Point[]](/imaging/python-net/aspose.imaging/point/) | 一个包含三个 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构的数组，表示要将矩形的左上、右上和左下角变换到的平行四边形的三个点。平行四边形的右下角由前面三个角推断得到。 |

**Returns**

| Type | Description |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) |  |


### Method: create_with_rect_f(rect, plgpts)  [static] {#create_with_rect_f_rect_plgpts_2}


```
 create_with_rect_f(rect, plgpts) 
```

将 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 类的新实例初始化为由指定矩形和点数组定义的几何变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 一个 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构，表示要进行变换的矩形。 |
| plgpts | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 一个包含三个 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构的数组，表示要将矩形的左上、右上和左下角变换到的平行四边形的三个点。平行四边形的右下角由前面三个角推断得到。 |

**Returns**

| Type | Description |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) |  |


### Method: get_elements() {#get_elements__3}


```
 get_elements() 
```

获取矩阵元素的副本。

**Returns**

| Type | Description |
| :- | :- |
| float[] | 矩阵元素的副本。 |


### Method: multiply(t_tx) {#multiply_t_tx_4}


```
 multiply(t_tx) 
```

使用（默认）Prepend 顺序，将此 Matrix 与 matrix 参数中指定的矩阵相乘。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| t_tx | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 用于相乘的矩阵。 |

### Method: multiply(t_tx, order) {#multiply_t_tx_order_5}


```
 multiply(t_tx, order) 
```

将此 Matrix 与 matrix 参数中指定的矩阵相乘，并按照 order 参数中指定的顺序进行。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| t_tx | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 该 tx. 该 tx. 该 tx. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 该 顺序. 该 顺序. 该 顺序. |

### Method: rotate(angle) {#rotate_angle_6}


```
 rotate(angle) 
```

在默认（Prepend）顺序下，对此 Matrix 应用以角度参数指定的量进行顺时针旋转，围绕原点（零 x 和 y 坐标）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 角度 | float | 该 旋转角度。 |

### Method: rotate(angle, order) {#rotate_angle_order_7}


```
 rotate(angle, order) 
```

在指定的顺序下，对此 Matrix 应用以角度参数指定的量进行顺时针旋转，围绕原点（零 x 和 y 坐标）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 角度 | float | 该 旋转角度。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 该 矩阵顺序。 |

### Method: rotate_at(angle, point) {#rotate_at_angle_point_8}


```
 rotate_at(angle, point) 
```

在默认（Prepend）顺序下，对此 Matrix 应用围绕指定点的顺时针旋转。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 角度 | float | 角度。 |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 该 点。 |

### Method: rotate_at(angle, point, order) {#rotate_at_angle_point_order_9}


```
 rotate_at(angle, point, order) 
```

在指定的顺序下，对此 Matrix 应用围绕指定点的顺时针旋转。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 角度 | float | 角度。 |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 该 点。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 该 顺序。 |

### Method: scale(scale_x, scale_y, order) {#scale_scale_x_scale_y_order_10}


```
 scale(scale_x, scale_y, order) 
```

使用指定的顺序，将指定的缩放向量（scaleX 和 scaleY）应用到此 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| scale_x | float | 该 X 缩放。 |
| scale_y | float | 该 Y 缩放。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 该 顺序。 |

### Method: scale(sx, sy) {#scale_sx_sy_11}


```
 scale(sx, sy) 
```

使用（默认）Prepend 顺序，将指定的缩放向量（scaleX 和 scaleY）应用到此 Matrix。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| sx | float | 该 sx. 该 sx. 该 sx. |
| sy | float | 该 sy. 该 sy. 该 sy. |

### Method: transform_points(points) {#transform_points_points_12}


```
 transform_points(points) 
```

将此 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 所表示的几何变换应用于指定的点数组。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 该 点。 |

### Method: translate(offset_x, offset_y, order) {#translate_offset_x_offset_y_order_13}


```
 translate(offset_x, offset_y, order) 
```

在指定的顺序下，将指定的平移向量应用到此 Matrix。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| offset_x | float | 该 X 偏移。 |
| offset_y | float | 该 Y 偏移。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 该 顺序。 |

### Method: translate(tx, ty) {#translate_tx_ty_14}


```
 translate(tx, ty) 
```

使用（默认）Prepend 顺序，将指定的平移向量应用到此 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| tx | float | 该 tx. 该 tx. 该 tx. |
| ty | float | 该 ty. 该 ty. 该 ty. |

