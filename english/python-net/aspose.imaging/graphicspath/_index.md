---
title: GraphicsPath Class
type: docs
weight: 4950
url: /python-net/aspose.imaging/graphicspath/
---

**Summary:** Represents a series of connected lines and curves. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.GraphicsPath

**Inheritance:** ObjectWithBounds

**Aspose.Imaging Version:** 23.6

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GraphicsPath()](#GraphicsPath__1) | Initializes a new instance of the [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) class. |
| [GraphicsPath(figures)](#GraphicsPath_figures_2) | Initializes a new instance of the [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) class. |
| [GraphicsPath(figures, fill_mode)](#GraphicsPath_figures_fill_mode_3) | Initializes a new instance of the [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) class. |
| [GraphicsPath(fill_mode)](#GraphicsPath_fill_mode_4) | Initializes a new instance of the [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | r | Gets or sets the object's bounds. |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure) | r | Gets the path figures. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode) | r/w | Gets or sets a [FillMode](/imaging/python-net/aspose.imaging/fillmode/) enumeration that determines how the interiors of shapes in this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) are filled. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_figure(figure)](#add_figure_figure_1) | Adds a new figure. |
| [add_figures(figures)](#add_figures_figures_2) | Adds new figures. |
| [add_path(adding_path)](#add_path_adding_path_3) | Appends the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to this path. |
| [add_path(adding_path, connect)](#add_path_adding_path_connect_4) | Appends the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to this path. |
| [deep_clone()](#deep_clone__5) | Performs a deep clone of this graphics path. |
| flatten() | Converts each curve in this path into a sequence of connected line segments. |
| [flatten(matrix)](#flatten_matrix_6) | Applies the specified transform and then converts each curve in this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) into a sequence of connected line segments. |
| [flatten(matrix, flatness)](#flatten_matrix_flatness_7) | Converts each curve in this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) into a sequence of connected line segments. |
| [get_bounds(matrix)](#get_bounds_matrix_8) | Gets the object's bounds. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_9) | Gets the object's bounds. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_10) | Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_11) | Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_12) | Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/) and using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_13) | Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/) and using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_14) | Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_15) | Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_16) | Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/) and using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_17) | Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/) and using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible_point(point, pen)](#is_outline_visible_point_point_pen_18) | Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible_point_f(point, pen)](#is_outline_visible_point_f_point_pen_19) | Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible_point_f_graphics(pt, pen, graphics)](#is_outline_visible_point_f_graphics_pt_pen_graphics_20) | Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/) and using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible_point_graphics(pt, pen, graphics)](#is_outline_visible_point_graphics_pt_pen_graphics_21) | Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/) and using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible_xy(x, y, pen)](#is_outline_visible_xy_x_y_pen_22) | Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible_xy_graphics(x, y, pen, graphics)](#is_outline_visible_xy_graphics_x_y_pen_graphics_23) | Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/) and using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible_xyf(x, y, pen)](#is_outline_visible_xyf_x_y_pen_24) | Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible_xyf_graphics(x, y, pen, graphics)](#is_outline_visible_xyf_graphics_x_y_pen_graphics_25) | Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/) and using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(point)](#is_visible_point_26) | Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(point)](#is_visible_point_27) | Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_28) | Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_29) | Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_30) | Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_31) | Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_32) | Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) in the visible clip region of the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_33) | Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) in the visible clip region of the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_point(point)](#is_visible_point_point_34) | Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_point_f(point)](#is_visible_point_f_point_35) | Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_point_f_graphics(pt, graphics)](#is_visible_point_f_graphics_pt_graphics_36) | Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_point_graphics(pt, graphics)](#is_visible_point_graphics_pt_graphics_37) | Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_xy(x, y)](#is_visible_xy_x_y_38) | Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_xy_graphics(x, y, graphics)](#is_visible_xy_graphics_x_y_graphics_39) | Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_xyf(x, y)](#is_visible_xyf_x_y_40) | Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_xyf_graphics(x, y, graphics)](#is_visible_xyf_graphics_x_y_graphics_41) | Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) in the visible clip region of the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [remove_figure(figure)](#remove_figure_figure_42) | Removes a figure. |
| [remove_figures(figures)](#remove_figures_figures_43) | Removes figures. |
| reset() | Empties the graphics path and sets the [FillMode](/imaging/python-net/aspose.imaging/fillmode/) to [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| reverse() | Reverses the order of figures, shapes, and points in each shape of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [transform(transform)](#transform_transform_44) | Applies the specified transformation to the shape. |
| [warp(dest_points, src_rect)](#warp_dest_points_src_rect_45) | Applies a warp transform, defined by a rectangle and a parallelogram, to this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [warp(dest_points, src_rect, matrix)](#warp_dest_points_src_rect_matrix_46) | Applies a warp transform, defined by a rectangle and a parallelogram, to this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode)](#warp_dest_points_src_rect_matrix_warp_mode_47) | Applies a warp transform, defined by a rectangle and a parallelogram, to this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode, flatness)](#warp_dest_points_src_rect_matrix_warp_mode_flatness_48) | Applies a warp transform, defined by a rectangle and a parallelogram, to this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [widen(pen)](#widen_pen_49) | Adds an additional outline to the path. |
| [widen(pen, matrix)](#widen_pen_matrix_50) | Adds an additional outline to the [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [widen(pen, matrix, flatness)](#widen_pen_matrix_flatness_51) | Replaces this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) with curves that enclose the area that is filled when this path is drawn by the specified pen. |


### Constructor: GraphicsPath() {#GraphicsPath__1}


```
 GraphicsPath() 
```

Initializes a new instance of the [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) class.

### Constructor: GraphicsPath(figures) {#GraphicsPath_figures_2}


```
 GraphicsPath(figures) 
```

Initializes a new instance of the [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure) | The figures to initialize from. |

### Constructor: GraphicsPath(figures, fill_mode) {#GraphicsPath_figures_fill_mode_3}


```
 GraphicsPath(figures, fill_mode) 
```

Initializes a new instance of the [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure) | The figures to initialize from. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode) | The fill mode. |

### Constructor: GraphicsPath(fill_mode) {#GraphicsPath_fill_mode_4}


```
 GraphicsPath(fill_mode) 
```

Initializes a new instance of the [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode) | The fill mode. |

### Method: add_figure(figure) {#add_figure_figure_1}


```
 add_figure(figure) 
```

Adds a new figure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| figure | [Figure](/imaging/python-net/aspose.imaging/figure) | The figure to add. |

### Method: add_figures(figures) {#add_figures_figures_2}


```
 add_figures(figures) 
```

Adds new figures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure) | The figures to add. |

### Method: add_path(adding_path) {#add_path_adding_path_3}


```
 add_path(adding_path) 
```

Appends the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to this path.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| adding_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath) | The [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to add. |

### Method: add_path(adding_path, connect) {#add_path_adding_path_connect_4}


```
 add_path(adding_path, connect) 
```

Appends the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to this path.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| adding_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath) | The [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to add. |
| connect | bool | A Boolean value that specifies whether the first figure in the added path is part of the last figure in this path. A value of true specifies that the first figure in the added path is part of the last figure in this path. A value of false specifies that the first figure in the added path is separate from the last figure in this path. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Performs a deep clone of this graphics path.

**Returns**

| Type | Description |
| :- | :- |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath) | A deep clone of the graphics path. |


### Method: flatten(matrix) {#flatten_matrix_6}


```
 flatten(matrix) 
```

Applies the specified transform and then converts each curve in this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) into a sequence of connected line segments.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix) | A [Matrix](/imaging/python-net/aspose.imaging/matrix/) by which to transform this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) before flattening. |

### Method: flatten(matrix, flatness) {#flatten_matrix_flatness_7}


```
 flatten(matrix, flatness) 
```

Converts each curve in this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) into a sequence of connected line segments.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix) | A [Matrix](/imaging/python-net/aspose.imaging/matrix/) by which to transform this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) before flattening. |
| flatness | float | Specifies the maximum permitted error between the curve and its flattened approximation. A value of 0.25 is the default. Reducing the flatness value will increase the number of line segments in the approximation. |

### Method: get_bounds(matrix) {#get_bounds_matrix_8}


```
 get_bounds(matrix) 
```

Gets the object's bounds.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix) | The matrix to apply before bounds will be calculated. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | The estimated object's bounds. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_9}


```
 get_bounds(matrix, pen) 
```

Gets the object's bounds.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix) | The matrix to apply before bounds will be calculated. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | The pen to use for object. This can influence the object's bounds size. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | The estimated object's bounds. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_10}


```
 is_outline_visible(point, pen) 
```

Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf) | A [PointF](/imaging/python-net/aspose.imaging/pointf/) that specifies the location to test. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | The [Pen](/imaging/python-net/aspose.imaging/pen/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/); otherwise, false. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_11}


```
 is_outline_visible(point, pen) 
```

Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point) | A [PointF](/imaging/python-net/aspose.imaging/pointf/) that specifies the location to test. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | The [Pen](/imaging/python-net/aspose.imaging/pen/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/); otherwise, false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_12}


```
 is_outline_visible(pt, pen, graphics) 
```

Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/) and using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf) | A [PointF](/imaging/python-net/aspose.imaging/pointf/) that specifies the location to test. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | The [Pen](/imaging/python-net/aspose.imaging/pen/) to test. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics) | The [Graphics](/imaging/python-net/aspose.imaging/graphics/) for which to test visibility. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) as drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/); otherwise, false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_13}


```
 is_outline_visible(pt, pen, graphics) 
```

Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/) and using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point) | A [PointF](/imaging/python-net/aspose.imaging/pointf/) that specifies the location to test. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | The [Pen](/imaging/python-net/aspose.imaging/pen/) to test. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics) | The [Graphics](/imaging/python-net/aspose.imaging/graphics/) for which to test visibility. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) as drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/); otherwise, false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_14}


```
 is_outline_visible(x, y, pen) 
```

Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | The [Pen](/imaging/python-net/aspose.imaging/pen/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/); otherwise, false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_15}


```
 is_outline_visible(x, y, pen) 
```

Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | The [Pen](/imaging/python-net/aspose.imaging/pen/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/); otherwise, false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_16}


```
 is_outline_visible(x, y, pen, graphics) 
```

Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/) and using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | The [Pen](/imaging/python-net/aspose.imaging/pen/) to test. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics) | The [Graphics](/imaging/python-net/aspose.imaging/graphics/) for which to test visibility. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) as drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/); otherwise, false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_17}


```
 is_outline_visible(x, y, pen, graphics) 
```

Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/) and using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | The [Pen](/imaging/python-net/aspose.imaging/pen/) to test. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics) | The [Graphics](/imaging/python-net/aspose.imaging/graphics/) for which to test visibility. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) as drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/); otherwise, false. |


### Method: is_outline_visible_point(point, pen) {#is_outline_visible_point_point_pen_18}


```
 is_outline_visible_point(point, pen) 
```

Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point) | A [PointF](/imaging/python-net/aspose.imaging/pointf/) that specifies the location to test. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | The [Pen](/imaging/python-net/aspose.imaging/pen/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/); otherwise, false. |


### Method: is_outline_visible_point_f(point, pen) {#is_outline_visible_point_f_point_pen_19}


```
 is_outline_visible_point_f(point, pen) 
```

Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf) | A [PointF](/imaging/python-net/aspose.imaging/pointf/) that specifies the location to test. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | The [Pen](/imaging/python-net/aspose.imaging/pen/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/); otherwise, false. |


### Method: is_outline_visible_point_f_graphics(pt, pen, graphics) {#is_outline_visible_point_f_graphics_pt_pen_graphics_20}


```
 is_outline_visible_point_f_graphics(pt, pen, graphics) 
```

Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/) and using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf) | A [PointF](/imaging/python-net/aspose.imaging/pointf/) that specifies the location to test. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | The [Pen](/imaging/python-net/aspose.imaging/pen/) to test. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics) | The [Graphics](/imaging/python-net/aspose.imaging/graphics/) for which to test visibility. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) as drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/); otherwise, false. |


### Method: is_outline_visible_point_graphics(pt, pen, graphics) {#is_outline_visible_point_graphics_pt_pen_graphics_21}


```
 is_outline_visible_point_graphics(pt, pen, graphics) 
```

Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/) and using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point) | A [Point](/imaging/python-net/aspose.imaging/point/) that specifies the location to test. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | The [Pen](/imaging/python-net/aspose.imaging/pen/) to test. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics) | The [Graphics](/imaging/python-net/aspose.imaging/graphics/) for which to test visibility. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) as drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/); otherwise, false. |


### Method: is_outline_visible_xy(x, y, pen) {#is_outline_visible_xy_x_y_pen_22}


```
 is_outline_visible_xy(x, y, pen) 
```

Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | The [Pen](/imaging/python-net/aspose.imaging/pen/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/); otherwise, false. |


### Method: is_outline_visible_xy_graphics(x, y, pen, graphics) {#is_outline_visible_xy_graphics_x_y_pen_graphics_23}


```
 is_outline_visible_xy_graphics(x, y, pen, graphics) 
```

Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/) and using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | The [Pen](/imaging/python-net/aspose.imaging/pen/) to test. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics) | The [Graphics](/imaging/python-net/aspose.imaging/graphics/) for which to test visibility. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) as drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/); otherwise, false. |


### Method: is_outline_visible_xyf(x, y, pen) {#is_outline_visible_xyf_x_y_pen_24}


```
 is_outline_visible_xyf(x, y, pen) 
```

Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | The [Pen](/imaging/python-net/aspose.imaging/pen/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/); otherwise, false. |


### Method: is_outline_visible_xyf_graphics(x, y, pen, graphics) {#is_outline_visible_xyf_graphics_x_y_pen_graphics_25}


```
 is_outline_visible_xyf_graphics(x, y, pen, graphics) 
```

Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/) and using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | The [Pen](/imaging/python-net/aspose.imaging/pen/) to test. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics) | The [Graphics](/imaging/python-net/aspose.imaging/graphics/) for which to test visibility. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) as drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/); otherwise, false. |


### Method: is_visible(point) {#is_visible_point_26}


```
 is_visible(point) 
```

Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf) | A [PointF](/imaging/python-net/aspose.imaging/pointf/) that represents the point to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); otherwise, false. |


### Method: is_visible(point) {#is_visible_point_27}


```
 is_visible(point) 
```

Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point) | A [PointF](/imaging/python-net/aspose.imaging/pointf/) that represents the point to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); otherwise, false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_28}


```
 is_visible(pt, graphics) 
```

Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf) | A [PointF](/imaging/python-net/aspose.imaging/pointf/) that represents the point to test. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics) | The [Graphics](/imaging/python-net/aspose.imaging/graphics/) for which to test visibility. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within this; otherwise, false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_29}


```
 is_visible(pt, graphics) 
```

Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point) | A [PointF](/imaging/python-net/aspose.imaging/pointf/) that represents the point to test. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics) | The [Graphics](/imaging/python-net/aspose.imaging/graphics/) for which to test visibility. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within this; otherwise, false. |


### Method: is_visible(x, y) {#is_visible_x_y_30}


```
 is_visible(x, y) 
```

Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); otherwise, false. |


### Method: is_visible(x, y) {#is_visible_x_y_31}


```
 is_visible(x, y) 
```

Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); otherwise, false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_32}


```
 is_visible(x, y, graphics) 
```

Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) in the visible clip region of the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics) | The [Graphics](/imaging/python-net/aspose.imaging/graphics/) for which to test visibility. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); otherwise, false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_33}


```
 is_visible(x, y, graphics) 
```

Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) in the visible clip region of the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics) | The [Graphics](/imaging/python-net/aspose.imaging/graphics/) for which to test visibility. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); otherwise, false. |


### Method: is_visible_point(point) {#is_visible_point_point_34}


```
 is_visible_point(point) 
```

Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point) | A [PointF](/imaging/python-net/aspose.imaging/pointf/) that represents the point to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); otherwise, false. |


### Method: is_visible_point_f(point) {#is_visible_point_f_point_35}


```
 is_visible_point_f(point) 
```

Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf) | A [PointF](/imaging/python-net/aspose.imaging/pointf/) that represents the point to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); otherwise, false. |


### Method: is_visible_point_f_graphics(pt, graphics) {#is_visible_point_f_graphics_pt_graphics_36}


```
 is_visible_point_f_graphics(pt, graphics) 
```

Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf) | A [PointF](/imaging/python-net/aspose.imaging/pointf/) that represents the point to test. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics) | The [Graphics](/imaging/python-net/aspose.imaging/graphics/) for which to test visibility. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within this; otherwise, false. |


### Method: is_visible_point_graphics(pt, graphics) {#is_visible_point_graphics_pt_graphics_37}


```
 is_visible_point_graphics(pt, graphics) 
```

Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point) | A [Point](/imaging/python-net/aspose.imaging/point/) that represents the point to test. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics) | The [Graphics](/imaging/python-net/aspose.imaging/graphics/) for which to test visibility. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); otherwise, false. |


### Method: is_visible_xy(x, y) {#is_visible_xy_x_y_38}


```
 is_visible_xy(x, y) 
```

Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); otherwise, false. |


### Method: is_visible_xy_graphics(x, y, graphics) {#is_visible_xy_graphics_x_y_graphics_39}


```
 is_visible_xy_graphics(x, y, graphics) 
```

Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics) | The [Graphics](/imaging/python-net/aspose.imaging/graphics/) for which to test visibility. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); otherwise, false. |


### Method: is_visible_xyf(x, y) {#is_visible_xyf_x_y_40}


```
 is_visible_xyf(x, y) 
```

Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); otherwise, false. |


### Method: is_visible_xyf_graphics(x, y, graphics) {#is_visible_xyf_graphics_x_y_graphics_41}


```
 is_visible_xyf_graphics(x, y, graphics) 
```

Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) in the visible clip region of the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics) | The [Graphics](/imaging/python-net/aspose.imaging/graphics/) for which to test visibility. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); otherwise, false. |


### Method: remove_figure(figure) {#remove_figure_figure_42}


```
 remove_figure(figure) 
```

Removes a figure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| figure | [Figure](/imaging/python-net/aspose.imaging/figure) | The figure to remove. |

### Method: remove_figures(figures) {#remove_figures_figures_43}


```
 remove_figures(figures) 
```

Removes figures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure) | The figures to remove. |

### Method: transform(transform) {#transform_transform_44}


```
 transform(transform) 
```

Applies the specified transformation to the shape.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix) | The transformation to apply. |

### Method: warp(dest_points, src_rect) {#warp_dest_points_src_rect_45}


```
 warp(dest_points, src_rect) 
```

Applies a warp transform, defined by a rectangle and a parallelogram, to this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf) | An array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that define a parallelogram to which the rectangle defined by <paramref name="srcRect" /> is transformed. The array can contain either three or four elements. If the array contains three elements, the lower-right corner of the parallelogram is implied by the first three points. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | A [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) that represents the rectangle that is transformed to the parallelogram defined by <paramref name="destPoints" />. |

### Method: warp(dest_points, src_rect, matrix) {#warp_dest_points_src_rect_matrix_46}


```
 warp(dest_points, src_rect, matrix) 
```

Applies a warp transform, defined by a rectangle and a parallelogram, to this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf) | An array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that define a parallelogram to which the rectangle defined by <paramref name="srcRect" /> is transformed. The array can contain either three or four elements. If the array contains three elements, the lower-right corner of the parallelogram is implied by the first three points. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | A [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) that represents the rectangle that is transformed to the parallelogram defined by <paramref name="destPoints" />. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix) | A [Matrix](/imaging/python-net/aspose.imaging/matrix/) that specifies a geometric transform to apply to the path. |

### Method: warp(dest_points, src_rect, matrix, warp_mode) {#warp_dest_points_src_rect_matrix_warp_mode_47}


```
 warp(dest_points, src_rect, matrix, warp_mode) 
```

Applies a warp transform, defined by a rectangle and a parallelogram, to this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf) | An array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that defines a parallelogram to which the rectangle defined by <paramref name="srcRect" /> is transformed. The array can contain either three or four elements. If the array contains three elements, the lower-right corner of the parallelogram is implied by the first three points. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | A [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) that represents the rectangle that is transformed to the parallelogram defined by <paramref name="destPoints" />. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix) | A [Matrix](/imaging/python-net/aspose.imaging/matrix/) that specifies a geometric transform to apply to the path. |
| warp_mode | [WarpMode](/imaging/python-net/aspose.imaging/warpmode) | A [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) enumeration that specifies whether this warp operation uses perspective or bilinear mode. |

### Method: warp(dest_points, src_rect, matrix, warp_mode, flatness) {#warp_dest_points_src_rect_matrix_warp_mode_flatness_48}


```
 warp(dest_points, src_rect, matrix, warp_mode, flatness) 
```

Applies a warp transform, defined by a rectangle and a parallelogram, to this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf) | An array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that define a parallelogram to which the rectangle defined by <paramref name="srcRect" /> is transformed. The array can contain either three or four elements. If the array contains three elements, the lower-right corner of the parallelogram is implied by the first three points. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | A [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) that represents the rectangle that is transformed to the parallelogram defined by <paramref name="destPoints" />. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix) | A [Matrix](/imaging/python-net/aspose.imaging/matrix/) that specifies a geometric transform to apply to the path. |
| warp_mode | [WarpMode](/imaging/python-net/aspose.imaging/warpmode) | A [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) enumeration that specifies whether this warp operation uses perspective or bilinear mode. |
| flatness | float | A value from 0 through 1 that specifies how flat the resulting path is. For more information, see the [GraphicsPath.flatten()](/imaging/python-net/aspose.imaging/graphicspath/) methods. |

### Method: widen(pen) {#widen_pen_49}


```
 widen(pen) 
```

Adds an additional outline to the path.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | A [Pen](/imaging/python-net/aspose.imaging/pen/) that specifies the width between the original outline of the path and the new outline this method creates. |

### Method: widen(pen, matrix) {#widen_pen_matrix_50}


```
 widen(pen, matrix) 
```

Adds an additional outline to the [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | A [Pen](/imaging/python-net/aspose.imaging/pen/) that specifies the width between the original outline of the path and the new outline this method creates. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix) | A [Matrix](/imaging/python-net/aspose.imaging/matrix/) that specifies a transform to apply to the path before widening. |

### Method: widen(pen, matrix, flatness) {#widen_pen_matrix_flatness_51}


```
 widen(pen, matrix, flatness) 
```

Replaces this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) with curves that enclose the area that is filled when this path is drawn by the specified pen.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | A [Pen](/imaging/python-net/aspose.imaging/pen/) that specifies the width between the original outline of the path and the new outline this method creates. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix) | A [Matrix](/imaging/python-net/aspose.imaging/matrix/) that specifies a transform to apply to the path before widening. |
| flatness | float | A value that specifies the flatness for curves. |

