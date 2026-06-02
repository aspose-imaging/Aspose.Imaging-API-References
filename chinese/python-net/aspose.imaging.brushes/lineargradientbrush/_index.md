---
title: "LinearGradientBrush 类"
type: docs
weight: 20
url: /zh/python-net/aspose.imaging.brushes/lineargradientbrush/
---

**Summary:** Encapsulates a [Brush](/imaging/python-net/aspose.imaging/brush/) with a linear gradient. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.LinearGradientBrush

**Inheritance:** LinearGradientBrushBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [LinearGradientBrush()](#LinearGradientBrush__1) | 使用默认参数初始化 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 类的新实例。<br/>            起始颜色为黑色，结束颜色为白色，角度为 45 度，矩形位于 (0,0)，大小为 (1,1)。 |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_2) | 初始化 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 类的新实例。 |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_3) | 初始化 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 类的新实例。 |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_4) | 初始化 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 类的新实例。 |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_5) | 初始化 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 类的新实例。 |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6) | 初始化 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 类的新实例。 |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7) | 初始化 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| 角度 | float | r/w | 获取或设置渐变角度。 |
| blend | [Blend](/imaging/python-net/aspose.imaging/blend/) | r/w | 获取或设置一个 [Blend](/imaging/python-net/aspose.imaging/blend/) ，它指定用于定义渐变自定义衰减的位置信息和因子。 |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| end_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | 获取或设置结束渐变颜色。 |
| gamma_correction | bool | r/w | 获取或设置一个值，指示是否为此 [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/) 启用了伽马校正。 |
| interpolation_colors | [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | r/w | 获取或设置一个 [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/)，用于定义多颜色线性渐变。 |
| is_angle_scalable | bool | r/w | 获取或设置一个值，指示在使用此 [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/) 进行变换时，是否更改了 [LinearGradientBrushBase.angle](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/)。 |
| is_transform_changed | bool | r | 获取一个值，指示变换是否以某种方式被更改。例如设置变换矩阵或<br/>            调用任何修改变换矩阵的方法。此属性为向后兼容 GDI+ 而引入。 |
| linear_colors | [Color[]](/imaging/python-net/aspose.imaging/color/) | r/w | 获取或设置渐变的起始和结束颜色。 |
| opacity | float | r/w | 获取或设置画笔的不透明度。该值应在 0 到 1 之间。0 表示画笔完全可见，1 表示画笔完全不透明。 |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | 获取或设置定义渐变起始和结束点的矩形区域。 |
| start_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | 获取或设置起始渐变颜色。 |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | 获取或设置一个 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 副本，用于定义此 [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/) 的局部几何变换。 |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | 获取或设置一个指示此 [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/) 的包装模式的 [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) 枚举。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_with_points(point1, point2, color1, color2)](#create_with_points_point1_point2_color1_color2_1) | 使用指定的点和颜色初始化 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 类的新实例。 |
| [create_with_points_f(point1, point2, color1, color2)](#create_with_points_f_point1_point2_color1_color2_2) | 使用指定的点和颜色初始化 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 类的新实例。 |
| [create_with_rect_colors_angle(rect, color1, color2, angle)](#create_with_rect_colors_angle_rect_color1_color2_angle_3) | 基于矩形、起始和结束颜色以及方向角度，初始化 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 类的新实例。 |
| [create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)](#create_with_rect_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_4) | 基于矩形、起始和结束颜色以及方向角度，初始化 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 类的新实例。 |
| [create_with_rect_f_colors_angle(rect, color1, color2, angle)](#create_with_rect_f_colors_angle_rect_color1_color2_angle_5) | 基于矩形、起始和结束颜色以及方向角度，初始化 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 类的新实例。 |
| [create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)](#create_with_rect_f_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_6) | 基于矩形、起始和结束颜色以及方向角度，初始化 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 类的新实例。 |
| [deep_clone()](#deep_clone__7) | 创建当前 [Brush](/imaging/python-net/aspose.imaging/brush/) 的新深度克隆。 |
| [multiply_transform(matrix)](#multiply_transform_matrix_8) | 将表示此 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 的本地几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 与指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 相乘，并在前面预置指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_9) | 将表示此 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 的本地几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 与指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 按指定顺序相乘。 |
| reset_transform() | 将 [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) 属性重置为单位矩阵。 |
| [rotate_transform(angle)](#rotate_transform_angle_10) | 按指定量旋转本地几何变换。此方法将在变换前预置旋转。 |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_11) | 按指定量并按指定顺序旋转本地几何变换。 |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_12) | 按指定的比例缩放本地几何变换。此方法将在变换前预置缩放矩阵。 |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_13) | 按指定的比例并按指定顺序缩放本地几何变换。 |
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_14) | 创建具有中心颜色并在两端线性衰减到单一颜色的线性渐变。 |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_15) | 创建具有中心颜色并在两端线性衰减到单一颜色的线性渐变。 |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_16) | 基于钟形曲线创建渐变衰减。 |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_17) | 基于钟形曲线创建渐变衰减。 |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_18) | 按指定的尺寸平移本地几何变换。此方法将在变换前预置平移。 |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_19) | 按指定的尺寸并按指定顺序平移本地几何变换。 |


### Constructor: LinearGradientBrush() {#LinearGradientBrush__1}


```
 LinearGradientBrush() 
```

使用默认参数初始化 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 类的新实例。<br/>            起始颜色为黑色，结束颜色为白色，角度为 45 度，矩形位于 (0,0)，大小为 (1,1)。

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_2}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

初始化 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 点1。 |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 点2。 |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | 颜色1。 |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | 颜色2。 |

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_3}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

初始化 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | 点1。 |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | 点2。 |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | 颜色1。 |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | 颜色2。 |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_4}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

初始化 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 矩形。 |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | 颜色1。 |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | 颜色2。 |
| 角度 | float | 角度。 |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_5}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

初始化 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 矩形。 |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | 颜色1。 |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | 颜色2。 |
| 角度 | float | 角度。 |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

初始化 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 矩形。 |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | 颜色1。 |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | 颜色2。 |
| 角度 | float | 角度。 |
| is_angle_scalable | bool | 如果设置为 <c>true</c> [is angle scalable]。 |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

初始化 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 矩形。 |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | 颜色1。 |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | 颜色2。 |
| 角度 | float | 角度。 |
| is_angle_scalable | bool | 如果设置为 <c>true</c> [is angle scalable]。 |

### Method: create_with_points(point1, point2, color1, color2)  [static] {#create_with_points_point1_point2_color1_color2_1}


```
 create_with_points(point1, point2, color1, color2) 
```

使用指定的点和颜色初始化 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | 表示线性渐变起始点的 [Point](/imaging/python-net/aspose.imaging/point/) 结构。 |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | 表示线性渐变终点的 [Point](/imaging/python-net/aspose.imaging/point/) 结构。 |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | 一个 [Color](/imaging/python-net/aspose.imaging/color/) 结构，表示线性渐变的起始颜色。 |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | 一个 [Color](/imaging/python-net/aspose.imaging/color/) 结构，表示线性渐变的结束颜色。 |

**Returns**

| Type | Description |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_points_f(point1, point2, color1, color2)  [static] {#create_with_points_f_point1_point2_color1_color2_2}


```
 create_with_points_f(point1, point2, color1, color2) 
```

使用指定的点和颜色初始化 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 表示线性渐变起始点的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构。 |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 表示线性渐变终点的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构。 |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | 一个 [Color](/imaging/python-net/aspose.imaging/color/) 结构，表示线性渐变的起始颜色。 |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | 一个 [Color](/imaging/python-net/aspose.imaging/color/) 结构，表示线性渐变的结束颜色。 |

**Returns**

| Type | Description |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_colors_angle(rect, color1, color2, angle)  [static] {#create_with_rect_colors_angle_rect_color1_color2_angle_3}


```
 create_with_rect_colors_angle(rect, color1, color2, angle) 
```

基于矩形、起始和结束颜色以及方向角度，初始化 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 指定线性渐变边界的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | 一个 [Color](/imaging/python-net/aspose.imaging/color/) 结构，表示渐变的起始颜色。 |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | 一个 [Color](/imaging/python-net/aspose.imaging/color/) 结构，表示渐变的结束颜色。 |
| 角度 | float | 梯度方向线相对于 x 轴顺时针测量的角度（以度为单位）。 |

**Returns**

| Type | Description |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)  [static] {#create_with_rect_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_4}


```
 create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable) 
```

基于矩形、起始和结束颜色以及方向角度，初始化 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 指定线性渐变边界的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | 一个 [Color](/imaging/python-net/aspose.imaging/color/) 结构，表示渐变的起始颜色。 |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | 一个 [Color](/imaging/python-net/aspose.imaging/color/) 结构，表示渐变的结束颜色。 |
| 角度 | float | 梯度方向线相对于 x 轴顺时针测量的角度（以度为单位）。 |
| is_angle_scalable | bool | 如果设置为 <c>true</c>，角度将在使用此 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 进行转换时被更改。 |

**Returns**

| Type | Description |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_f_colors_angle(rect, color1, color2, angle)  [static] {#create_with_rect_f_colors_angle_rect_color1_color2_angle_5}


```
 create_with_rect_f_colors_angle(rect, color1, color2, angle) 
```

基于矩形、起始和结束颜色以及方向角度，初始化 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 指定线性渐变边界的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | 一个 [Color](/imaging/python-net/aspose.imaging/color/) 结构，表示渐变的起始颜色。 |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | 一个 [Color](/imaging/python-net/aspose.imaging/color/) 结构，表示渐变的结束颜色。 |
| 角度 | float | 梯度方向线相对于 x 轴顺时针测量的角度（以度为单位）。 |

**Returns**

| Type | Description |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)  [static] {#create_with_rect_f_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_6}


```
 create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable) 
```

基于矩形、起始和结束颜色以及方向角度，初始化 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 指定线性渐变边界的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | 一个 [Color](/imaging/python-net/aspose.imaging/color/) 结构，表示渐变的起始颜色。 |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | 一个 [Color](/imaging/python-net/aspose.imaging/color/) 结构，表示渐变的结束颜色。 |
| 角度 | float | 梯度方向线相对于 x 轴顺时针测量的角度（以度为单位）。 |
| is_angle_scalable | bool | 如果设置为 <c>true</c>，角度将在使用此 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 进行转换时被更改。 |

**Returns**

| Type | Description |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


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

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_14}


```
 set_blend_triangular_shape(focus) 
```

创建具有中心颜色并在两端线性衰减到单一颜色的线性渐变。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 焦点 | float | 一个取值范围为 0 到 1 的值，指定渐变的中心（即渐变仅由结束颜色组成的点）。 |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_15}


```
 set_blend_triangular_shape(focus, scale) 
```

创建具有中心颜色并在两端线性衰减到单一颜色的线性渐变。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 焦点 | float | 一个取值范围为 0 到 1 的值，指定渐变的中心（即渐变仅由结束颜色组成的点）。 |
| 比例 | float | 一个取值范围为 0 到 1 的值，指定颜色从起始颜色到 _focus_（结束颜色）的衰减速度。 |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_16}


```
 set_sigma_bell_shape(focus) 
```

基于钟形曲线创建渐变衰减。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 焦点 | float | 一个取值范围为 0 到 1 的值，指定渐变的中心（即起始颜色和结束颜色等量混合的点）。 |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_17}


```
 set_sigma_bell_shape(focus, scale) 
```

基于钟形曲线创建渐变衰减。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 焦点 | float | 一个取值范围为 0 到 1 的值，指定渐变的中心（即渐变仅由结束颜色组成的点）。 |
| 比例 | float | 一个取值范围为 0 到 1 的值，指定颜色从 _focus_ 衰减的速度。 |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_18}


```
 translate_transform(dx, dy) 
```

按指定的尺寸平移本地几何变换。此方法将在变换前预置平移。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dx | float | x 方向的平移值。 |
| dy | float | y 方向的平移值。 |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_19}


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

