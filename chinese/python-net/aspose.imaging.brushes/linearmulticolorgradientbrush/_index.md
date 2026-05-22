---
title: "LinearMulticolorGradientBrush 类"
type: docs
weight: 40
url: /zh/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/
---

**Summary:** Represents a [Brush](/imaging/python-net/aspose.imaging/brush/) with linear gradient defined by multiple colors and appropriate positions. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.LinearMulticolorGradientBrush

**Inheritance:** LinearGradientBrushBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [LinearMulticolorGradientBrush()](#LinearMulticolorGradientBrush__1) | 使用默认参数初始化 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 类的新实例。<br/>            起始颜色为黑色，结束颜色为白色，角度为 45 度，矩形位于 (0,0)，大小为 (1,1)。 |
| [LinearMulticolorGradientBrush(point1, point2)](#LinearMulticolorGradientBrush_point1_point2_2) | 使用指定的点初始化 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 类的新实例。 |
| [LinearMulticolorGradientBrush(point1, point2)](#LinearMulticolorGradientBrush_point1_point2_3) | 使用指定的点初始化 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 类的新实例。 |
| [LinearMulticolorGradientBrush(rect, angle)](#LinearMulticolorGradientBrush_rect_angle_4) | 基于矩形和方向角初始化 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 类的新实例。 |
| [LinearMulticolorGradientBrush(rect, angle)](#LinearMulticolorGradientBrush_rect_angle_5) | 基于矩形和方向角初始化 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 类的新实例。 |
| [LinearMulticolorGradientBrush(rect, angle, is_angle_scalable)](#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_6) | 基于矩形和方向角初始化 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 类的新实例。 |
| [LinearMulticolorGradientBrush(rect, angle, is_angle_scalable)](#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_7) | 基于矩形和方向角初始化 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| 角度 | float | r/w | 获取或设置渐变角度。 |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| gamma_correction | bool | r/w | 获取或设置一个值，指示是否为此 [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/) 启用了伽马校正。 |
| interpolation_colors | [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | r/w | 获取或设置一个 [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/)，用于定义多颜色线性渐变。 |
| is_angle_scalable | bool | r/w | 获取或设置一个值，指示在使用此 [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/) 进行变换时，是否更改了 [LinearGradientBrushBase.angle](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/)。 |
| is_transform_changed | bool | r | 获取一个值，指示变换是否以某种方式被更改。例如设置变换矩阵或<br/>            调用任何修改变换矩阵的方法。此属性为向后兼容 GDI+ 而引入。 |
| opacity | float | r/w | 获取或设置画笔的不透明度。该值应在 0 到 1 之间。0 表示画笔完全可见，1 表示画笔完全不透明。 |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | 获取或设置定义渐变起始和结束点的矩形区域。 |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | 获取或设置一个 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 副本，用于定义此 [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/) 的局部几何变换。 |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | 获取或设置一个指示此 [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/) 的包装模式的 [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) 枚举。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_with_points(point1, point2)](#create_with_points_point1_point2_1) | 使用指定的点初始化 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 类的新实例。 |
| [create_with_points_f(point1, point2)](#create_with_points_f_point1_point2_2) | 使用指定的点初始化 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 类的新实例。 |
| [create_with_rect(rect, angle)](#create_with_rect_rect_angle_3) | 基于矩形和方向角初始化 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 类的新实例。 |
| [create_with_rect_angle_scalable(rect, angle, is_angle_scalable)](#create_with_rect_angle_scalable_rect_angle_is_angle_scalable_4) | 基于矩形和方向角初始化 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 类的新实例。 |
| [create_with_rect_f(rect, angle)](#create_with_rect_f_rect_angle_5) | 基于矩形和方向角初始化 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 类的新实例。 |
| [create_with_rect_f_angle_scalable(rect, angle, is_angle_scalable)](#create_with_rect_f_angle_scalable_rect_angle_is_angle_scalable_6) | 基于矩形和方向角初始化 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 类的新实例。 |
| [deep_clone()](#deep_clone__7) | 创建当前 [Brush](/imaging/python-net/aspose.imaging/brush/) 的新深度克隆。 |
| [multiply_transform(matrix)](#multiply_transform_matrix_8) | 将表示此 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 的本地几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 与指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 相乘，并在前面预置指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_9) | 将表示此 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 的本地几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 与指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 按指定顺序相乘。 |
| reset_transform() | 将 [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) 属性重置为单位矩阵。 |
| [rotate_transform(angle)](#rotate_transform_angle_10) | 按指定量旋转本地几何变换。此方法将在变换前预置旋转。 |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_11) | 按指定量并按指定顺序旋转本地几何变换。 |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_12) | 按指定的比例缩放本地几何变换。此方法将在变换前预置缩放矩阵。 |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_13) | 按指定的比例并按指定顺序缩放本地几何变换。 |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_14) | 按指定的尺寸平移本地几何变换。此方法将在变换前预置平移。 |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_15) | 按指定的尺寸并按指定顺序平移本地几何变换。 |


### Constructor: LinearMulticolorGradientBrush() {#LinearMulticolorGradientBrush__1}


```
 LinearMulticolorGradientBrush() 
```

使用默认参数初始化 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 类的新实例。<br/>            起始颜色为黑色，结束颜色为白色，角度为 45 度，矩形位于 (0,0)，大小为 (1,1)。

### Constructor: LinearMulticolorGradientBrush(point1, point2) {#LinearMulticolorGradientBrush_point1_point2_2}


```
 LinearMulticolorGradientBrush(point1, point2) 
```

使用指定的点初始化 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | 表示线性渐变起始点的 [Point](/imaging/python-net/aspose.imaging/point/) 结构。 |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | 表示线性渐变终点的 [Point](/imaging/python-net/aspose.imaging/point/) 结构。 |

### Constructor: LinearMulticolorGradientBrush(point1, point2) {#LinearMulticolorGradientBrush_point1_point2_3}


```
 LinearMulticolorGradientBrush(point1, point2) 
```

使用指定的点初始化 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 表示线性渐变起始点的 [Point](/imaging/python-net/aspose.imaging/point/) 结构。 |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 表示线性渐变终点的 [Point](/imaging/python-net/aspose.imaging/point/) 结构。 |

### Constructor: LinearMulticolorGradientBrush(rect, angle) {#LinearMulticolorGradientBrush_rect_angle_4}


```
 LinearMulticolorGradientBrush(rect, angle) 
```

基于矩形和方向角初始化 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 指定线性渐变边界的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |
| 角度 | float | 梯度方向线相对于 x 轴顺时针测量的角度（以度为单位）。 |

### Constructor: LinearMulticolorGradientBrush(rect, angle) {#LinearMulticolorGradientBrush_rect_angle_5}


```
 LinearMulticolorGradientBrush(rect, angle) 
```

基于矩形和方向角初始化 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 指定线性渐变边界的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |
| 角度 | float | 梯度方向线相对于 x 轴顺时针测量的角度（以度为单位）。 |

### Constructor: LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) {#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_6}


```
 LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) 
```

基于矩形和方向角初始化 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 指定线性渐变边界的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |
| 角度 | float | 梯度方向线相对于 x 轴顺时针测量的角度（以度为单位）。 |
| is_angle_scalable | bool | 如果设置为 <c>true</c>，则在使用此 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 进行变换时角度会被更改。 |

### Constructor: LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) {#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_7}


```
 LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) 
```

基于矩形和方向角初始化 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 指定线性渐变边界的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |
| 角度 | float | 梯度方向线相对于 x 轴顺时针测量的角度（以度为单位）。 |
| is_angle_scalable | bool | 如果设置为 <c>true</c>，则在使用此 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 进行变换时角度会被更改。 |

### Method: create_with_points(point1, point2)  [static] {#create_with_points_point1_point2_1}


```
 create_with_points(point1, point2) 
```

使用指定的点初始化 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | 表示线性渐变起始点的 [Point](/imaging/python-net/aspose.imaging/point/) 结构。 |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | 表示线性渐变终点的 [Point](/imaging/python-net/aspose.imaging/point/) 结构。 |

**Returns**

| Type | Description |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) |  |


### Method: create_with_points_f(point1, point2)  [static] {#create_with_points_f_point1_point2_2}


```
 create_with_points_f(point1, point2) 
```

使用指定的点初始化 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 表示线性渐变起始点的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构。 |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 表示线性渐变终点的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构。 |

**Returns**

| Type | Description |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) |  |


### Method: create_with_rect(rect, angle)  [static] {#create_with_rect_rect_angle_3}


```
 create_with_rect(rect, angle) 
```

基于矩形和方向角初始化 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 指定线性渐变边界的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |
| 角度 | float | 梯度方向线相对于 x 轴顺时针测量的角度（以度为单位）。 |

**Returns**

| Type | Description |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) |  |


### Method: create_with_rect_angle_scalable(rect, angle, is_angle_scalable)  [static] {#create_with_rect_angle_scalable_rect_angle_is_angle_scalable_4}


```
 create_with_rect_angle_scalable(rect, angle, is_angle_scalable) 
```

基于矩形和方向角初始化 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 指定线性渐变边界的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |
| 角度 | float | 梯度方向线相对于 x 轴顺时针测量的角度（以度为单位）。 |
| is_angle_scalable | bool | 如果设置为 <c>true</c>，则在使用此 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 进行变换时角度会被更改。 |

**Returns**

| Type | Description |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) |  |


### Method: create_with_rect_f(rect, angle)  [static] {#create_with_rect_f_rect_angle_5}


```
 create_with_rect_f(rect, angle) 
```

基于矩形和方向角初始化 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 指定线性渐变边界的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |
| 角度 | float | 梯度方向线相对于 x 轴顺时针测量的角度（以度为单位）。 |

**Returns**

| Type | Description |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) |  |


### Method: create_with_rect_f_angle_scalable(rect, angle, is_angle_scalable)  [static] {#create_with_rect_f_angle_scalable_rect_angle_is_angle_scalable_6}


```
 create_with_rect_f_angle_scalable(rect, angle, is_angle_scalable) 
```

基于矩形和方向角初始化 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 指定线性渐变边界的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |
| 角度 | float | 梯度方向线相对于 x 轴顺时针测量的角度（以度为单位）。 |
| is_angle_scalable | bool | 如果设置为 <c>true</c>，则在使用此 [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) 进行变换时角度会被更改。 |

**Returns**

| Type | Description |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) |  |


### Method: deep_clone() {#deep_clone__7}


```
 deep_clone() 
```

创建当前 [Brush](/imaging/python-net/aspose.imaging/brush/) 的新深度克隆。

**Returns**

| Type | Description |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | 一个新的 [Brush](/imaging/python-net/aspose.imaging/brush/)，它是此 [Brush](/imaging/python-net/aspose.imaging/brush/) 实例的深度克隆。 |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_8}


```
 multiply_transform(matrix) 
```

将表示此 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 的本地几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 与指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 相乘，并在前面预置指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 用于乘以几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_9}


```
 multiply_transform(matrix, order) 
```

将表示此 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 的本地几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 与指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 按指定顺序相乘。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 用于乘以几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 指定两个矩阵相乘顺序的 [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/)。 |

### Method: rotate_transform(angle) {#rotate_transform_angle_10}


```
 rotate_transform(angle) 
```

按指定量旋转本地几何变换。此方法将在变换前预置旋转。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 角度 | float | 旋转角度。 |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_11}


```
 rotate_transform(angle, order) 
```

按指定量并按指定顺序旋转本地几何变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 角度 | float | 旋转角度。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 指定是追加还是预置旋转矩阵的 [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/)。 |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_12}


```
 scale_transform(sx, sy) 
```

按指定的比例缩放本地几何变换。此方法将在变换前预置缩放矩阵。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| sx | float | 在 x 轴方向上缩放变换的量。 |
| sy | float | 在 y 轴方向上缩放变换的量。 |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_13}


```
 scale_transform(sx, sy, order) 
```

按指定的比例并按指定顺序缩放本地几何变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| sx | float | 在 x 轴方向上缩放变换的量。 |
| sy | float | 在 y 轴方向上缩放变换的量。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 一个 [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) 用于指定是追加还是预先追加缩放矩阵。 |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_14}


```
 translate_transform(dx, dy) 
```

按指定的尺寸平移本地几何变换。此方法将在变换前预置平移。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dx | float | x 方向的平移值。 |
| dy | float | y 方向的平移值。 |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_15}


```
 translate_transform(dx, dy, order) 
```

按指定的尺寸并按指定顺序平移本地几何变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dx | float | x 方向的平移值。 |
| dy | float | y 方向的平移值。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 应用平移的顺序（预先追加或追加）。 |

