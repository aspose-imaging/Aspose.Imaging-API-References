---
title: "GraphicsPath 类"
type: docs
weight: 5040
url: /zh/python-net/aspose.imaging/graphicspath/
---

**Summary:** Represents a series of connected lines and curves. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.GraphicsPath

**Inheritance:** ObjectWithBounds

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [GraphicsPath()](#GraphicsPath__1) | 初始化 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 类的新实例。 |
| [GraphicsPath(figures)](#GraphicsPath_figures_2) | 初始化 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 类的新实例。 |
| [GraphicsPath(figures, fill_mode)](#GraphicsPath_figures_fill_mode_3) | 初始化 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 类的新实例。 |
| [GraphicsPath(fill_mode)](#GraphicsPath_fill_mode_4) | 初始化 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | 获取或设置对象的边界。 |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | r | 获取路径图形。 |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | r/w | 获取或设置一个 [FillMode](/imaging/python-net/aspose.imaging/fillmode/) 枚举，用于确定此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 中形状内部的填充方式。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [add_figure(figure)](#add_figure_figure_1) | 添加一个新图形。 |
| [add_figures(figures)](#add_figures_figures_2) | 添加新图形。 |
| [add_path(adding_path)](#add_path_adding_path_3) | 将指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 追加到此路径。 |
| [add_path(adding_path, connect)](#add_path_adding_path_connect_4) | 将指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 追加到此路径。 |
| [deep_clone()](#deep_clone__5) | 执行此图形路径的深度克隆。 |
| flatten() | 将此路径中的每条曲线转换为一系列相连的线段。 |
| [flatten(matrix)](#flatten_matrix_6) | 应用指定的变换，然后将此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 中的每条曲线转换为一系列相连的线段。 |
| [flatten(matrix, flatness)](#flatten_matrix_flatness_7) | 将此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 中的每条曲线转换为一系列相连的线段。 |
| [get_bounds(matrix)](#get_bounds_matrix_8) | 获取对象的边界。 |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_9) | 获取对象的边界。 |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_10) | 指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。 |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_11) | 指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。 |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_12) | 指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制并使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。 |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_13) | 指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制并使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。 |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_14) | 指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。 |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_15) | 指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。 |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_16) | 指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制并使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。 |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_17) | 指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制并使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。 |
| [is_outline_visible_point(point, pen)](#is_outline_visible_point_point_pen_18) | 指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。 |
| [is_outline_visible_point_f(point, pen)](#is_outline_visible_point_f_point_pen_19) | 指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。 |
| [is_outline_visible_point_f_graphics(pt, pen, graphics)](#is_outline_visible_point_f_graphics_pt_pen_graphics_20) | 指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制并使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。 |
| [is_outline_visible_point_graphics(pt, pen, graphics)](#is_outline_visible_point_graphics_pt_pen_graphics_21) | 指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制并使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。 |
| [is_outline_visible_xy(x, y, pen)](#is_outline_visible_xy_x_y_pen_22) | 指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。 |
| [is_outline_visible_xy_graphics(x, y, pen, graphics)](#is_outline_visible_xy_graphics_x_y_pen_graphics_23) | 指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制并使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。 |
| [is_outline_visible_xyf(x, y, pen)](#is_outline_visible_xyf_x_y_pen_24) | 指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。 |
| [is_outline_visible_xyf_graphics(x, y, pen, graphics)](#is_outline_visible_xyf_graphics_x_y_pen_graphics_25) | 指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制并使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。 |
| [is_visible(point)](#is_visible_point_26) | 指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 内部。 |
| [is_visible(point)](#is_visible_point_27) | 指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 内部。 |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_28) | 指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 内部。 |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_29) | 指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 内部。 |
| [is_visible(x, y)](#is_visible_x_y_30) | 指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 内部。 |
| [is_visible(x, y)](#is_visible_x_y_31) | 指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 内部。 |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_32) | 指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 在指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 可见裁剪区域内。 |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_33) | 指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 在指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 可见裁剪区域内。 |
| [is_visible_point(point)](#is_visible_point_point_34) | 指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 内部。 |
| [is_visible_point_f(point)](#is_visible_point_f_point_35) | 指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 内部。 |
| [is_visible_point_f_graphics(pt, graphics)](#is_visible_point_f_graphics_pt_graphics_36) | 指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 内部。 |
| [is_visible_point_graphics(pt, graphics)](#is_visible_point_graphics_pt_graphics_37) | 指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 内部。 |
| [is_visible_xy(x, y)](#is_visible_xy_x_y_38) | 指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 内部。 |
| [is_visible_xy_graphics(x, y, graphics)](#is_visible_xy_graphics_x_y_graphics_39) | 指示使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 内部。 |
| [is_visible_xyf(x, y)](#is_visible_xyf_x_y_40) | 指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 内部。 |
| [is_visible_xyf_graphics(x, y, graphics)](#is_visible_xyf_graphics_x_y_graphics_41) | 指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 在指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 可见裁剪区域内。 |
| [remove_figure(figure)](#remove_figure_figure_42) | 移除一个图形。 |
| [remove_figures(figures)](#remove_figures_figures_43) | 删除图形。 |
| reset() | 清空图形路径并将 [FillMode](/imaging/python-net/aspose.imaging/fillmode/) 设置为 [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/)。 |
| reverse() | 反转此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 中每个形状的图形、形状和点的顺序。 |
| [transform(transform)](#transform_transform_44) | 对形状应用指定的变换。 |
| [warp(dest_points, src_rect)](#warp_dest_points_src_rect_45) | 对该 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 应用由矩形和平行四边形定义的扭曲变换。 |
| [warp(dest_points, src_rect, matrix)](#warp_dest_points_src_rect_matrix_46) | 对该 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 应用由矩形和平行四边形定义的扭曲变换。 |
| [warp(dest_points, src_rect, matrix, warp_mode)](#warp_dest_points_src_rect_matrix_warp_mode_47) | 对该 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 应用由矩形和平行四边形定义的扭曲变换。 |
| [warp(dest_points, src_rect, matrix, warp_mode, flatness)](#warp_dest_points_src_rect_matrix_warp_mode_flatness_48) | 对该 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 应用由矩形和平行四边形定义的扭曲变换。 |
| [widen(pen)](#widen_pen_49) | 为路径添加额外的轮廓。 |
| [widen(pen, matrix)](#widen_pen_matrix_50) | 为 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 添加额外的轮廓。 |
| [widen(pen, matrix, flatness)](#widen_pen_matrix_flatness_51) | 用在使用指定笔绘制此路径时填充的区域的曲线替换此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)。 |


### Constructor: GraphicsPath() {#GraphicsPath__1}


```
 GraphicsPath() 
```

初始化 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 类的新实例。


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Constructor: GraphicsPath(figures) {#GraphicsPath_figures_2}


```
 GraphicsPath(figures) 
```

初始化 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | 用于初始化的图形。 |

### Constructor: GraphicsPath(figures, fill_mode) {#GraphicsPath_figures_fill_mode_3}


```
 GraphicsPath(figures, fill_mode) 
```

初始化 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | 用于初始化的图形。 |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | 填充模式。 |

### Constructor: GraphicsPath(fill_mode) {#GraphicsPath_fill_mode_4}


```
 GraphicsPath(fill_mode) 
```

初始化 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | 填充模式。 |

### Method: add_figure(figure) {#add_figure_figure_1}


```
 add_figure(figure) 
```

添加一个新图形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| figure | [Figure](/imaging/python-net/aspose.imaging/figure/) | 要添加的图形。 |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: add_figures(figures) {#add_figures_figures_2}


```
 add_figures(figures) 
```

添加新图形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | 要添加的图形。 |


**See also:**

**[Example # 1](#example_16)**: This example creates a new Image and draws a variety of shapes using figures ...


### Method: add_path(adding_path) {#add_path_adding_path_3}


```
 add_path(adding_path) 
```

将指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 追加到此路径。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| adding_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 要添加的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)。 |

### Method: add_path(adding_path, connect) {#add_path_adding_path_connect_4}


```
 add_path(adding_path, connect) 
```

将指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 追加到此路径。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| adding_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 要添加的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)。 |
| 连接 | bool | 一个布尔值，指定要添加的路径中的第一个图形是否是此路径中最后一个图形的一部分。值为 true 表示第一个图形是此路径中最后一个图形的一部分。值为 false 表示第一个图形与此路径中最后一个图形分离。 |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

执行此图形路径的深度克隆。

**Returns**

| Type | Description |
| :- | :- |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 图形路径的深度克隆。 |


### Method: flatten(matrix) {#flatten_matrix_6}


```
 flatten(matrix) 
```

应用指定的变换，然后将此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 中的每条曲线转换为一系列相连的线段。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 在展平之前，用于转换此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |

### Method: flatten(matrix, flatness) {#flatten_matrix_flatness_7}


```
 flatten(matrix, flatness) 
```

将此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 中的每条曲线转换为一系列相连的线段。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 在展平之前，用于转换此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |
| 平整度 | float | 指定曲线与其平面化近似之间允许的最大误差。默认值为 0.25。降低平整度值会增加近似中的线段数量。 |

### Method: get_bounds(matrix) {#get_bounds_matrix_8}


```
 get_bounds(matrix) 
```

获取对象的边界。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 在计算边界之前要应用的矩阵。 |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 估计的对象边界。 |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_9}


```
 get_bounds(matrix, pen) 
```

获取对象的边界。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 在计算边界之前要应用的矩阵。 |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于对象的笔。这可能会影响对象边界的大小。 |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 估计的对象边界。 |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_10}


```
 is_outline_visible(point, pen) 
```

指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 指定要测试位置的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于测试的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内，则此方法返回 true；否则返回 false。 |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_11}


```
 is_outline_visible(point, pen) 
```

指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | 指定要测试位置的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于测试的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内，则此方法返回 true；否则返回 false。 |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_12}


```
 is_outline_visible(pt, pen, graphics) 
```

指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制并使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 指定要测试位置的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于测试的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 用于测试可见性的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓（下方）内，则此方法返回 true；否则返回 false。 |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_13}


```
 is_outline_visible(pt, pen, graphics) 
```

指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制并使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | 指定要测试位置的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于测试的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 用于测试可见性的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓（下方）内，则此方法返回 true；否则返回 false。 |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_14}


```
 is_outline_visible(x, y, pen) 
```

指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | float | 要测试的点的 x 坐标。 |
| y | float | 要测试的点的 y 坐标。 |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于测试的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内，则此方法返回 true；否则返回 false。 |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_15}


```
 is_outline_visible(x, y, pen) 
```

指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 要测试的点的 x 坐标。 |
| y | int | 要测试的点的 y 坐标。 |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于测试的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内，则此方法返回 true；否则返回 false。 |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_16}


```
 is_outline_visible(x, y, pen, graphics) 
```

指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制并使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | float | 要测试的点的 x 坐标。 |
| y | float | 要测试的点的 y 坐标。 |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于测试的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 用于测试可见性的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓（下方）内，则此方法返回 true；否则返回 false。 |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_17}


```
 is_outline_visible(x, y, pen, graphics) 
```

指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制并使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 要测试的点的 x 坐标。 |
| y | int | 要测试的点的 y 坐标。 |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于测试的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 用于测试可见性的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓（下方）内，则此方法返回 true；否则返回 false。 |


### Method: is_outline_visible_point(point, pen) {#is_outline_visible_point_point_pen_18}


```
 is_outline_visible_point(point, pen) 
```

指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | 指定要测试位置的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于测试的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内，则此方法返回 true；否则返回 false。 |


### Method: is_outline_visible_point_f(point, pen) {#is_outline_visible_point_f_point_pen_19}


```
 is_outline_visible_point_f(point, pen) 
```

指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 指定要测试位置的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于测试的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内，则此方法返回 true；否则返回 false。 |


### Method: is_outline_visible_point_f_graphics(pt, pen, graphics) {#is_outline_visible_point_f_graphics_pt_pen_graphics_20}


```
 is_outline_visible_point_f_graphics(pt, pen, graphics) 
```

指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制并使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 指定要测试位置的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于测试的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 用于测试可见性的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓（下方）内，则此方法返回 true；否则返回 false。 |


### Method: is_outline_visible_point_graphics(pt, pen, graphics) {#is_outline_visible_point_graphics_pt_pen_graphics_21}


```
 is_outline_visible_point_graphics(pt, pen, graphics) 
```

指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制并使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | 指定要测试位置的 [Point](/imaging/python-net/aspose.imaging/point/)。 |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于测试的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 用于测试可见性的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内，则此方法返回 true；否则返回 false。 |


### Method: is_outline_visible_xy(x, y, pen) {#is_outline_visible_xy_x_y_pen_22}


```
 is_outline_visible_xy(x, y, pen) 
```

指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 要测试的点的 x 坐标。 |
| y | int | 要测试的点的 y 坐标。 |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于测试的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内，则此方法返回 true；否则返回 false。 |


### Method: is_outline_visible_xy_graphics(x, y, pen, graphics) {#is_outline_visible_xy_graphics_x_y_pen_graphics_23}


```
 is_outline_visible_xy_graphics(x, y, pen, graphics) 
```

指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制并使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 要测试的点的 x 坐标。 |
| y | int | 要测试的点的 y 坐标。 |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于测试的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 用于测试可见性的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内，则此方法返回 true；否则返回 false。 |


### Method: is_outline_visible_xyf(x, y, pen) {#is_outline_visible_xyf_x_y_pen_24}


```
 is_outline_visible_xyf(x, y, pen) 
```

指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | float | 要测试的点的 x 坐标。 |
| y | float | 要测试的点的 y 坐标。 |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于测试的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内，则此方法返回 true；否则返回 false。 |


### Method: is_outline_visible_xyf_graphics(x, y, pen, graphics) {#is_outline_visible_xyf_graphics_x_y_pen_graphics_25}


```
 is_outline_visible_xyf_graphics(x, y, pen, graphics) 
```

指示在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制并使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓内部（下方）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | float | 要测试的点的 x 坐标。 |
| y | float | 要测试的点的 y 坐标。 |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于测试的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 用于测试可见性的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点在使用指定的 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制时位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的轮廓（下方）内，则此方法返回 true；否则返回 false。 |


### Method: is_visible(point) {#is_visible_point_26}


```
 is_visible(point) 
```

指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 表示要测试的点的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 中，则此方法返回 true；否则返回 false。 |


### Method: is_visible(point) {#is_visible_point_27}


```
 is_visible(point) 
```

指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | 表示要测试的点的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 中，则此方法返回 true；否则返回 false。 |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_28}


```
 is_visible(pt, graphics) 
```

指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 表示要测试的点的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 用于测试可见性的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点位于此对象中，则此方法返回 true；否则返回 false。 |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_29}


```
 is_visible(pt, graphics) 
```

指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | 表示要测试的点的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 用于测试可见性的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点位于此对象中，则此方法返回 true；否则返回 false。 |


### Method: is_visible(x, y) {#is_visible_x_y_30}


```
 is_visible(x, y) 
```

指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | float | 要测试的点的 x 坐标。 |
| y | float | 要测试的点的 y 坐标。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 中，则此方法返回 true；否则返回 false。 |


### Method: is_visible(x, y) {#is_visible_x_y_31}


```
 is_visible(x, y) 
```

指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 要测试的点的 x 坐标。 |
| y | int | 要测试的点的 y 坐标。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 中，则此方法返回 true；否则返回 false。 |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_32}


```
 is_visible(x, y, graphics) 
```

指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 在指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 可见裁剪区域内。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | float | 要测试的点的 x 坐标。 |
| y | float | 要测试的点的 y 坐标。 |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 用于测试可见性的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 中，则此方法返回 true；否则返回 false。 |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_33}


```
 is_visible(x, y, graphics) 
```

指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 在指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 可见裁剪区域内。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 要测试的点的 x 坐标。 |
| y | int | 要测试的点的 y 坐标。 |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 用于测试可见性的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 中，则此方法返回 true；否则返回 false。 |


### Method: is_visible_point(point) {#is_visible_point_point_34}


```
 is_visible_point(point) 
```

指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | 表示要测试的点的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 中，则此方法返回 true；否则返回 false。 |


### Method: is_visible_point_f(point) {#is_visible_point_f_point_35}


```
 is_visible_point_f(point) 
```

指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 表示要测试的点的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 中，则此方法返回 true；否则返回 false。 |


### Method: is_visible_point_f_graphics(pt, graphics) {#is_visible_point_f_graphics_pt_graphics_36}


```
 is_visible_point_f_graphics(pt, graphics) 
```

指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 表示要测试的点的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 用于测试可见性的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点位于此对象中，则此方法返回 true；否则返回 false。 |


### Method: is_visible_point_graphics(pt, graphics) {#is_visible_point_graphics_pt_graphics_37}


```
 is_visible_point_graphics(pt, graphics) 
```

指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | 表示要测试的点的 [Point](/imaging/python-net/aspose.imaging/point/)。 |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 用于测试可见性的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 中，则此方法返回 true；否则返回 false。 |


### Method: is_visible_xy(x, y) {#is_visible_xy_x_y_38}


```
 is_visible_xy(x, y) 
```

指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 要测试的点的 x 坐标。 |
| y | int | 要测试的点的 y 坐标。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 中，则此方法返回 true；否则返回 false。 |


### Method: is_visible_xy_graphics(x, y, graphics) {#is_visible_xy_graphics_x_y_graphics_39}


```
 is_visible_xy_graphics(x, y, graphics) 
```

指示使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 时，指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 要测试的点的 x 坐标。 |
| y | int | 要测试的点的 y 坐标。 |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 用于测试可见性的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 中，则此方法返回 true；否则返回 false。 |


### Method: is_visible_xyf(x, y) {#is_visible_xyf_x_y_40}


```
 is_visible_xyf(x, y) 
```

指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | float | 要测试的点的 x 坐标。 |
| y | float | 要测试的点的 y 坐标。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 中，则此方法返回 true；否则返回 false。 |


### Method: is_visible_xyf_graphics(x, y, graphics) {#is_visible_xyf_graphics_x_y_graphics_41}


```
 is_visible_xyf_graphics(x, y, graphics) 
```

指示指定的点是否位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 在指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 可见裁剪区域内。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | float | 要测试的点的 x 坐标。 |
| y | float | 要测试的点的 y 坐标。 |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 用于测试可见性的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定的点位于此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 中，则此方法返回 true；否则返回 false。 |


### Method: remove_figure(figure) {#remove_figure_figure_42}


```
 remove_figure(figure) 
```

移除一个图形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| figure | [Figure](/imaging/python-net/aspose.imaging/figure/) | 要删除的图形。 |

### Method: remove_figures(figures) {#remove_figures_figures_43}


```
 remove_figures(figures) 
```

删除图形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | 要删除的图形。 |

### Method: transform(transform) {#transform_transform_44}


```
 transform(transform) 
```

对形状应用指定的变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 要应用的变换。 |

### Method: warp(dest_points, src_rect) {#warp_dest_points_src_rect_45}


```
 warp(dest_points, src_rect) 
```

对该 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 应用由矩形和平行四边形定义的扭曲变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 一个由 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构组成的数组，用于定义一个平行四边形，矩形由 _srcRect_ 定义并被转换到该平行四边形。数组可以包含三或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点隐含。 |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 表示被转换为由 _destPoints_ 定义的平行四边形的矩形的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)。 |

### Method: warp(dest_points, src_rect, matrix) {#warp_dest_points_src_rect_matrix_46}


```
 warp(dest_points, src_rect, matrix) 
```

对该 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 应用由矩形和平行四边形定义的扭曲变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 一个由 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构组成的数组，用于定义一个平行四边形，矩形由 _srcRect_ 定义并被转换到该平行四边形。数组可以包含三或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点隐含。 |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 表示被转换为由 _destPoints_ 定义的平行四边形的矩形的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)。 |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 指定要应用于路径的几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |

### Method: warp(dest_points, src_rect, matrix, warp_mode) {#warp_dest_points_src_rect_matrix_warp_mode_47}


```
 warp(dest_points, src_rect, matrix, warp_mode) 
```

对该 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 应用由矩形和平行四边形定义的扭曲变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 一个由 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构组成的数组，用于定义一个平行四边形，矩形由 _srcRect_ 定义并被转换到该平行四边形。数组可以包含三或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点隐含。 |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 表示被转换为由 _destPoints_ 定义的平行四边形的矩形的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)。 |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 指定要应用于路径的几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |
| warp_mode | [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) | 指定此扭曲操作使用透视模式还是双线性模式的 [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) 枚举。 |

### Method: warp(dest_points, src_rect, matrix, warp_mode, flatness) {#warp_dest_points_src_rect_matrix_warp_mode_flatness_48}


```
 warp(dest_points, src_rect, matrix, warp_mode, flatness) 
```

对该 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 应用由矩形和平行四边形定义的扭曲变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 一个由 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构组成的数组，用于定义一个平行四边形，矩形由 _srcRect_ 定义并被转换到该平行四边形。数组可以包含三或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点隐含。 |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 表示被转换为由 _destPoints_ 定义的平行四边形的矩形的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)。 |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 指定要应用于路径的几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |
| warp_mode | [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) | 指定此扭曲操作使用透视模式还是双线性模式的 [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) 枚举。 |
| flatness | float | 一个介于 0 到 1 之间的值，用于指定生成的路径的平坦程度。更多信息请参阅 [GraphicsPath.flatten()](/imaging/python-net/aspose.imaging/graphicspath/) 方法。 |

### Method: widen(pen) {#widen_pen_49}


```
 widen(pen) 
```

为路径添加额外的轮廓。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 指定路径原始轮廓与此方法创建的新轮廓之间宽度的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |

### Method: widen(pen, matrix) {#widen_pen_matrix_50}


```
 widen(pen, matrix) 
```

为 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 添加额外的轮廓。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 指定路径原始轮廓与此方法创建的新轮廓之间宽度的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 指定在加宽路径之前要应用的变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |

### Method: widen(pen, matrix, flatness) {#widen_pen_matrix_flatness_51}


```
 widen(pen, matrix, flatness) 
```

用在使用指定笔绘制此路径时填充的区域的曲线替换此 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 指定路径原始轮廓与此方法创建的新轮廓之间宽度的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 指定在加宽路径之前要应用的变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |
| 平整度 | float | 指定曲线平坦度的值。 |

## **Examples**
### This examples make use of GraphicsPath and Graphics classes to create and manipulate figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end `draw_path` method exposed by Graphics class is called to render the paths on surface. {#example_13}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, PointF, SizeF
from aspose.imaging import Pen
from aspose.imaging.sources import StreamSource
from aspose.imaging.imageoptions import TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from aspose.imaging.shapes import RectangleShape, EllipseShape, PieShape


# 创建文件流的实例
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# 创建 TiffOptions 的实例并设置其各种属性
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# 为 ImageOptions 实例设置源
	tiffOptions.source = StreamSource(stream)
	# 创建 Image 的实例
	with Image.create(tiffOptions, 500, 500) as image:
		# 创建并初始化 Graphics 类的实例
		graphics = Graphics(image)
		# 清除 Graphics 表面
		graphics.clear(Color.wheat);
		# 创建 GraphicsPath 类的实例
		graphics_path = GraphicsPath()
		# 创建 Figure 类的实例
		figure = Figure()
		# 向 Figure 对象添加形状
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# 将 Figure 对象添加到 GraphicsPath
		graphics_path.add_figure(figure)
		# 使用颜色为 Black 的 Pen 对象绘制路径
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# 保存所有更改。
		image.save()


```

### This example creates a new Image and draws a variety of shapes using figures and `GraphicsPath` on the `Image` surface {#example_16}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, Rectangle, Size
from aspose.imaging import Point, PointF, Pen
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource
from aspose.imaging.shapes import EllipseShape, PieShape, ArcShape, PolygonShape, RectangleShape
from os.path import join as path_join

#创建 BmpOptions 的实例并设置其各种属性            
with BmpOptions() as bmpOptions:
	bmpOptions.bits_per_pixel = 24
	#创建 FileCreateSource 的实例并将其分配为 BmpOptions 实例的 Source
	#第二个布尔参数决定要创建的文件是否为临时文件
	bmpOptions.source = FileCreateSource(r"c:\temp\output.bmp", False)
	#创建 Image 实例
	with Image.create(bmpOptions, 500, 500) as image:
		# 创建并初始化 Graphics 类的实例
		graphics = Graphics(image)
		# 清除 Graphics 表面
		graphics.clear(Color.wheat)
		# 创建 GraphicsPath 类的实例
		graphicspath = GraphicsPath()
		#创建 Figure 类的实例
		figure1 = Figure()
		# 向 Figure 对象添加形状
		figure1.add_shape(EllipseShape(RectangleF(50, 50, 300, 300)))
		figure1.add_shape(PieShape(Rectangle(Point(110, 110), Size(200, 200)), 0, 90))
		# 创建 Figure 类的实例
		figure2 = Figure()
		# 向 Figure 对象添加形状
		figure2.add_shape(ArcShape(RectangleF(10, 10, 300, 300), 0, 45))
		figure2.add_shape(
			PolygonShape([PointF(150, 10), PointF(150, 200), PointF(250, 300), PointF(350, 400)], True))
		figure2.add_shape(RectangleShape(RectangleF(Point(250, 250), Size(200, 200))))
		# 将 Figure 对象添加到 GraphicsPath
		graphicspath.add_figures([figure1, figure2])
		# 使用颜色为 Black 的 Pen 对象绘制路径
		graphics.draw_path(Pen(Color.black, 2.0), graphicspath)
		# 保存所有更改。
		image.save()


```

