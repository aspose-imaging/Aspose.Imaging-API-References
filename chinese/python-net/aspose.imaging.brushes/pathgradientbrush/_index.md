---
title: "PathGradientBrush 类"
type: docs
weight: 50
url: /zh/python-net/aspose.imaging.brushes/pathgradientbrush/
---

**Summary:** Encapsulates a [Brush](/imaging/python-net/aspose.imaging/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.PathGradientBrush

**Inheritance:** PathGradientBrushBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [PathGradientBrush(path)](#PathGradientBrush_path_1) | 初始化 PathGradientBrush 类的新实例 |
| [PathGradientBrush(path_points)](#PathGradientBrush_path_points_2) | 初始化 PathGradientBrush 类的新实例 |
| [PathGradientBrush(path_points)](#PathGradientBrush_path_points_3) | 初始化 PathGradientBrush 类的新实例 |
| [PathGradientBrush(path_points, wrap_mode)](#PathGradientBrush_path_points_wrap_mode_4) | 初始化 PathGradientBrush 类的新实例 |
| [PathGradientBrush(path_points, wrap_mode)](#PathGradientBrush_path_points_wrap_mode_5) | 初始化 PathGradientBrush 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| blend | [Blend](/imaging/python-net/aspose.imaging/blend/) | r/w | 获取或设置一个 [Blend](/imaging/python-net/aspose.imaging/blend/) ，它指定用于定义渐变自定义衰减的位置信息和因子。 |
| center_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | 获取或设置路径渐变中心的颜色。 |
| center_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | 获取或设置路径渐变的中心点。 |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| focus_scales | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | 获取或设置渐变衰减的焦点。 |
| graphics_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r | 获取此画笔所基于的图形路径。 |
| interpolation_colors | [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | r/w | 获取或设置一个 [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/)，用于定义多颜色线性渐变。 |
| is_transform_changed | bool | r | 获取一个值，指示变换是否以某种方式被更改。例如设置变换矩阵或<br/>            调用任何修改变换矩阵的方法。此属性为向后兼容 GDI+ 而引入。 |
| opacity | float | r/w | 获取或设置画笔的不透明度。该值应在 0 到 1 之间。0 表示画笔完全可见，1 表示画笔完全不透明。 |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r | 获取此画笔所基于的路径点。 |
| surround_colors | [Color[]](/imaging/python-net/aspose.imaging/color/) | r/w | 获取或设置一个颜色数组，这些颜色对应于此 [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) 填充的路径中的点。 |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | 获取或设置一个 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 副本，用于定义此 [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/) 的局部几何变换。 |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | 获取或设置一个指示此 [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/) 的包装模式的 [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) 枚举。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_with_path(path)](#create_with_path_path_1) | 使用指定的路径初始化 [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) 类的新实例。 |
| [create_with_points(path_points)](#create_with_points_path_points_2) | 使用指定的点初始化 [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) 类的新实例。 |
| [create_with_points_f(path_points)](#create_with_points_f_path_points_3) | 使用指定的点初始化 [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) 类的新实例。 |
| [create_with_points_f_wrap_mode(path_points, wrap_mode)](#create_with_points_f_wrap_mode_path_points_wrap_mode_4) | 使用指定的点和包装模式初始化 [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) 类的新实例。 |
| [create_with_points_wrap_mode(path_points, wrap_mode)](#create_with_points_wrap_mode_path_points_wrap_mode_5) | 使用指定的点和包装模式初始化 [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) 类的新实例。 |
| [deep_clone()](#deep_clone__6) | 创建当前 [Brush](/imaging/python-net/aspose.imaging/brush/) 的新深度克隆。 |
| [multiply_transform(matrix)](#multiply_transform_matrix_7) | 将表示此 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 的本地几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 与指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 相乘，并在前面预置指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_8) | 将表示此 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 的本地几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 与指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 按指定顺序相乘。 |
| reset_transform() | 将 [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) 属性重置为单位矩阵。 |
| [rotate_transform(angle)](#rotate_transform_angle_9) | 按指定量旋转本地几何变换。此方法将在变换前预置旋转。 |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_10) | 按指定量并按指定顺序旋转本地几何变换。 |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_11) | 按指定的比例缩放本地几何变换。此方法将在变换前预置缩放矩阵。 |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_12) | 按指定的比例并按指定顺序缩放本地几何变换。 |
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_13) | 创建一个以中心颜色为起点、线性衰减至一种周围颜色的渐变。 |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_14) | 创建一个以中心颜色为起点、线性衰减至每种周围颜色的渐变。 |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_15) | 创建一个渐变画刷，使颜色从路径中心向外变化至路径边界。颜色之间的过渡基于钟形曲线。 |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_16) | 创建一个渐变画刷，使颜色从路径中心向外变化至路径边界。颜色之间的过渡基于钟形曲线。 |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_17) | 按指定的尺寸平移本地几何变换。此方法将在变换前预置平移。 |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_18) | 按指定的尺寸并按指定顺序平移本地几何变换。 |


### Constructor: PathGradientBrush(path) {#PathGradientBrush_path_1}


```
 PathGradientBrush(path) 
```

初始化 PathGradientBrush 类的新实例

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) |  |

### Constructor: PathGradientBrush(path_points) {#PathGradientBrush_path_points_2}


```
 PathGradientBrush(path_points) 
```

初始化 PathGradientBrush 类的新实例

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) |  |

### Constructor: PathGradientBrush(path_points) {#PathGradientBrush_path_points_3}


```
 PathGradientBrush(path_points) 
```

初始化 PathGradientBrush 类的新实例

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) |  |

### Constructor: PathGradientBrush(path_points, wrap_mode) {#PathGradientBrush_path_points_wrap_mode_4}


```
 PathGradientBrush(path_points, wrap_mode) 
```

初始化 PathGradientBrush 类的新实例

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) |  |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) |  |

### Constructor: PathGradientBrush(path_points, wrap_mode) {#PathGradientBrush_path_points_wrap_mode_5}


```
 PathGradientBrush(path_points, wrap_mode) 
```

初始化 PathGradientBrush 类的新实例

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) |  |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) |  |

### Method: create_with_path(path)  [static] {#create_with_path_path_1}


```
 create_with_path(path) 
```

使用指定的路径初始化 [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 定义此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 所定义的、由此 [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) 填充的区域。 |

**Returns**

| Type | Description |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: create_with_points(path_points)  [static] {#create_with_points_path_points_2}


```
 create_with_points(path_points) 
```

使用指定的点初始化 [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 一个由 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构组成的数组，表示构成路径顶点的点。 |

**Returns**

| Type | Description |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: create_with_points_f(path_points)  [static] {#create_with_points_f_path_points_3}


```
 create_with_points_f(path_points) 
```

使用指定的点初始化 [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 一个由 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构组成的数组，表示构成路径顶点的点。 |

**Returns**

| Type | Description |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: create_with_points_f_wrap_mode(path_points, wrap_mode)  [static] {#create_with_points_f_wrap_mode_path_points_wrap_mode_4}


```
 create_with_points_f_wrap_mode(path_points, wrap_mode) 
```

使用指定的点和包装模式初始化 [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 一个由 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构组成的数组，表示构成路径顶点的点。 |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | 指定使用此 [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) 如何平铺使用此 [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) 绘制的填充。 |

**Returns**

| Type | Description |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: create_with_points_wrap_mode(path_points, wrap_mode)  [static] {#create_with_points_wrap_mode_path_points_wrap_mode_5}


```
 create_with_points_wrap_mode(path_points, wrap_mode) 
```

使用指定的点和包装模式初始化 [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 一个由 [Point](/imaging/python-net/aspose.imaging/point/) 结构组成的数组，表示构成路径顶点的点。 |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | 指定使用此 [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) 如何平铺使用此 [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) 绘制的填充。 |

**Returns**

| Type | Description |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: deep_clone() {#deep_clone__6}


```
 deep_clone() 
```

创建当前 [Brush](/imaging/python-net/aspose.imaging/brush/) 的新深度克隆。

**Returns**

| Type | Description |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | 一个新的 [Brush](/imaging/python-net/aspose.imaging/brush/)，它是此 [Brush](/imaging/python-net/aspose.imaging/brush/) 实例的深度克隆。 |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_7}


```
 multiply_transform(matrix) 
```

将表示此 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 的本地几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 与指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 相乘，并在前面预置指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 用于乘以几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_8}


```
 multiply_transform(matrix, order) 
```

将表示此 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 的本地几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 与指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 按指定顺序相乘。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 用于乘以几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 指定两个矩阵相乘顺序的 [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/)。 |

### Method: rotate_transform(angle) {#rotate_transform_angle_9}


```
 rotate_transform(angle) 
```

按指定量旋转本地几何变换。此方法将在变换前预置旋转。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 角度 | float | 旋转角度。 |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_10}


```
 rotate_transform(angle, order) 
```

按指定量并按指定顺序旋转本地几何变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 角度 | float | 旋转角度。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 指定是追加还是预置旋转矩阵的 [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/)。 |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_11}


```
 scale_transform(sx, sy) 
```

按指定的比例缩放本地几何变换。此方法将在变换前预置缩放矩阵。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| sx | float | 在 x 轴方向上缩放变换的量。 |
| sy | float | 在 y 轴方向上缩放变换的量。 |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_12}


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

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_13}


```
 set_blend_triangular_shape(focus) 
```

创建一个以中心颜色为起点、线性衰减至一种周围颜色的渐变。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 焦点 | float | 一个取值范围为 0 到 1 的值，用于指定沿从路径中心到路径边界的任意径向，中心颜色在最高强度时的位置。取值为 1（默认）时，最高强度位于路径的中心。 |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_14}


```
 set_blend_triangular_shape(focus, scale) 
```

创建一个以中心颜色为起点、线性衰减至每种周围颜色的渐变。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 焦点 | float | 一个取值范围为 0 到 1 的值，用于指定沿从路径中心到路径边界的任意径向，中心颜色在最高强度时的位置。取值为 1（默认）时，最高强度位于路径的中心。 |
| 比例 | float | 一个取值范围为 0 到 1 的值，用于指定中心颜色与边界颜色混合时的最大强度。取值为 1 时会产生中心颜色的最高可能强度，这是默认值。 |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_15}


```
 set_sigma_bell_shape(focus) 
```

创建一个渐变画刷，使颜色从路径中心向外变化至路径边界。颜色之间的过渡基于钟形曲线。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 焦点 | float | 一个取值范围为 0 到 1 的值，用于指定沿从路径中心到路径边界的任意径向，中心颜色在最高强度时的位置。取值为 1（默认）时，最高强度位于路径的中心。 |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_16}


```
 set_sigma_bell_shape(focus, scale) 
```

创建一个渐变画刷，使颜色从路径中心向外变化至路径边界。颜色之间的过渡基于钟形曲线。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 焦点 | float | 一个取值范围为 0 到 1 的值，用于指定沿从路径中心到路径边界的任意径向，中心颜色在最高强度时的位置。取值为 1（默认）时，最高强度位于路径的中心。 |
| 比例 | float | 一个取值范围为 0 到 1 的值，用于指定中心颜色与边界颜色混合时的最大强度。取值为 1 时会产生中心颜色的最高可能强度，这是默认值。 |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_17}


```
 translate_transform(dx, dy) 
```

按指定的尺寸平移本地几何变换。此方法将在变换前预置平移。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dx | float | x 方向的平移值。 |
| dy | float | y 方向的平移值。 |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_18}


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

