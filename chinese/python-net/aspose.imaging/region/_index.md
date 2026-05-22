---
title: "Region 类"
type: docs
weight: 7170
url: /zh/python-net/aspose.imaging/region/
---

**Summary:** Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Region

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [Region()](#Region__1) | 初始化一个新的 [Region](/imaging/python-net/aspose.imaging/region/)。 |
| [Region(path)](#Region_path_2) | 使用指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 初始化一个新的 [Region](/imaging/python-net/aspose.imaging/region/)。 |
| [Region(rect)](#Region_rect_3) | 使用指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构初始化一个新的 [Region](/imaging/python-net/aspose.imaging/region/)。 |
| [Region(rect)](#Region_rect_4) | 使用指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构初始化一个新的 [Region](/imaging/python-net/aspose.imaging/region/)。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [complement(path)](#complement_path_1) | 更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其包含指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 中未与此 [Region](/imaging/python-net/aspose.imaging/region/) 相交的部分。 |
| [complement(rect)](#complement_rect_2) | 更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其包含指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构中未与此 [Region](/imaging/python-net/aspose.imaging/region/) 相交的部分。 |
| [complement(rect)](#complement_rect_3) | 更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其包含指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构中未与此 [Region](/imaging/python-net/aspose.imaging/region/) 相交的部分。 |
| [complement(region)](#complement_region_4) | 更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其包含指定的 [Region](/imaging/python-net/aspose.imaging/region/) 中未与此 [Region](/imaging/python-net/aspose.imaging/region/) 相交的部分。 |
| [complement_path(path)](#complement_path_path_5) | 更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其包含指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 中未与此 [Region](/imaging/python-net/aspose.imaging/region/) 相交的部分。 |
| [complement_rect(rect)](#complement_rect_rect_6) | 更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其包含指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构中未与此 [Region](/imaging/python-net/aspose.imaging/region/) 相交的部分。 |
| [complement_rect_f(rect)](#complement_rect_f_rect_7) | 更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其包含指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构中未与此 [Region](/imaging/python-net/aspose.imaging/region/) 相交的部分。 |
| [complement_rgn(region)](#complement_rgn_region_8) | 更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其包含指定的 [Region](/imaging/python-net/aspose.imaging/region/) 中未与此 [Region](/imaging/python-net/aspose.imaging/region/) 相交的部分。 |
| [create_with_path(path)](#create_with_path_path_9) | 使用指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 初始化一个新的 [Region](/imaging/python-net/aspose.imaging/region/)。 |
| [create_with_rect(rect)](#create_with_rect_rect_10) | 使用指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构初始化一个新的 [Region](/imaging/python-net/aspose.imaging/region/)。 |
| [create_with_rect_f(rect)](#create_with_rect_f_rect_11) | 使用指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构初始化一个新的 [Region](/imaging/python-net/aspose.imaging/region/)。 |
| [deep_clone()](#deep_clone__12) | 创建此 [Region](/imaging/python-net/aspose.imaging/region/) 的精确深拷贝。 |
| [exclude(path)](#exclude_path_13) | 更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其仅包含其内部未与指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 相交的部分。 |
| [exclude(rect)](#exclude_rect_14) | 更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其仅包含其内部未与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构相交的部分。 |
| [exclude(rect)](#exclude_rect_15) | 更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其仅包含其内部未与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构相交的部分。 |
| [exclude(region)](#exclude_region_16) | 更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其仅包含其内部未与指定的 [Region](/imaging/python-net/aspose.imaging/region/) 相交的部分。 |
| [exclude_path(path)](#exclude_path_path_17) | 更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其仅包含其内部未与指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 相交的部分。 |
| [exclude_rect(rect)](#exclude_rect_rect_18) | 更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其仅包含其内部未与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构相交的部分。 |
| [exclude_rect_f(rect)](#exclude_rect_f_rect_19) | 更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其仅包含其内部未与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构相交的部分。 |
| [exclude_rgn(region)](#exclude_rgn_region_20) | 更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其仅包含其内部未与指定的 [Region](/imaging/python-net/aspose.imaging/region/) 相交的部分。 |
| [intersect(path)](#intersect_path_21) | 将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的交集。 |
| [intersect(rect)](#intersect_rect_22) | 将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的交集。 |
| [intersect(rect)](#intersect_rect_23) | 将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的交集。 |
| [intersect(region)](#intersect_region_24) | 将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [Region](/imaging/python-net/aspose.imaging/region/) 的交集。 |
| [intersect_path(path)](#intersect_path_path_25) | 将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的交集。 |
| [intersect_rect(rect)](#intersect_rect_rect_26) | 将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的交集。 |
| [intersect_rect_f(rect)](#intersect_rect_f_rect_27) | 将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的交集。 |
| [intersect_rgn(region)](#intersect_rgn_region_28) | 将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [Region](/imaging/python-net/aspose.imaging/region/) 的交集。 |
| [is_empty(g)](#is_empty_g_29) | 测试此 [Region](/imaging/python-net/aspose.imaging/region/) 在指定绘图表面上是否具有空的内部。 |
| [is_infinite(g)](#is_infinite_g_30) | 测试此 [Region](/imaging/python-net/aspose.imaging/region/) 在指定绘图表面上是否具有无限的内部。 |
| [is_visible(point)](#is_visible_point_31) | 测试指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible(point)](#is_visible_point_32) | 测试指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible(point, g)](#is_visible_point_g_33) | 测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible(point, g)](#is_visible_point_g_34) | 测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible(rect)](#is_visible_rect_35) | 测试指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible(rect)](#is_visible_rect_36) | 测试指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible(rect, g)](#is_visible_rect_g_37) | 测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible(rect, g)](#is_visible_rect_g_38) | 测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible(x, y)](#is_visible_x_y_39) | 测试指定的点是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible(x, y, g)](#is_visible_x_y_g_40) | 测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定的点是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible(x, y, g)](#is_visible_x_y_g_41) | 测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定的点是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_42) | 测试指定矩形的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_43) | 测试指定矩形的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_44) | 测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定矩形的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_45) | 测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定矩形的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible_f(x, y)](#is_visible_f_x_y_46) | 测试指定的点是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible_point(point)](#is_visible_point_point_47) | 测试指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible_point_f(point)](#is_visible_point_f_point_48) | 测试指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible_point_f_with_graphics(point, g)](#is_visible_point_f_with_graphics_point_g_49) | 测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible_point_with_graphics(point, g)](#is_visible_point_with_graphics_point_g_50) | 测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定的 [Point](/imaging/python-net/aspose.imaging/point/) 结构是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible_rect(rect)](#is_visible_rect_rect_51) | 测试指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible_rect_f(rect)](#is_visible_rect_f_rect_52) | 测试指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible_rect_f_with_graphics(rect, g)](#is_visible_rect_f_with_graphics_rect_g_53) | 测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible_rect_with_graphics(rect, g)](#is_visible_rect_with_graphics_rect_g_54) | 测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible_with_graphics(x, y, g)](#is_visible_with_graphics_x_y_g_55) | 测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定的点是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible_with_graphics_f(x, y, g)](#is_visible_with_graphics_f_x_y_g_56) | 测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定的点是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible_xywh(x, y, width, height)](#is_visible_xywh_x_y_width_height_57) | 测试指定矩形的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible_xywh_graphics(x, y, width, height, g)](#is_visible_xywh_graphics_x_y_width_height_g_58) | 测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定矩形的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible_xywh_graphics_f(x, y, width, height, g)](#is_visible_xywh_graphics_f_x_y_width_height_g_59) | 测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定矩形的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| [is_visible_xywhf(x, y, width, height)](#is_visible_xywhf_x_y_width_height_60) | 测试指定矩形的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。 |
| make_empty() | 将此 [Region](/imaging/python-net/aspose.imaging/region/) 初始化为空的内部。 |
| make_infinite() | 将此 [Region](/imaging/python-net/aspose.imaging/region/) 对象初始化为无限内部。 |
| [transform(matrix)](#transform_matrix_61) | 使用指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 对此 [Region](/imaging/python-net/aspose.imaging/region/) 进行变换。 |
| [translate(dx, dy)](#translate_dx_dy_62) | 按指定的量偏移此 [Region](/imaging/python-net/aspose.imaging/region/) 的坐标。 |
| [translate(dx, dy)](#translate_dx_dy_63) | 按指定的量偏移此 [Region](/imaging/python-net/aspose.imaging/region/) 的坐标。 |
| [translate_f(dx, dy)](#translate_f_dx_dy_64) | 按指定的量偏移此 [Region](/imaging/python-net/aspose.imaging/region/) 的坐标。 |
| [union(path)](#union_path_65) | 将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的并集。 |
| [union(rect)](#union_rect_66) | 将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的并集。 |
| [union(rect)](#union_rect_67) | 将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的并集。 |
| [union(region)](#union_region_68) | 将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [Region](/imaging/python-net/aspose.imaging/region/) 的并集。 |
| [union_path(path)](#union_path_path_69) | 将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的并集。 |
| [union_rect(rect)](#union_rect_rect_70) | 将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的并集。 |
| [union_rect_f(rect)](#union_rect_f_rect_71) | 将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的并集。 |
| [union_rgn(region)](#union_rgn_region_72) | 将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [Region](/imaging/python-net/aspose.imaging/region/) 的并集。 |
| [xor(path)](#xor_path_73) | 将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的并集减去交集。 |
| [xor(rect)](#xor_rect_74) | 将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的并集减去交集。 |
| [xor(rect)](#xor_rect_75) | 将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的并集减去交集。 |
| [xor(region)](#xor_region_76) | 将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [Region](/imaging/python-net/aspose.imaging/region/) 的并集减去交集。 |
| [xor_path(path)](#xor_path_path_77) | 将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的并集减去交集。 |
| [xor_rect(rect)](#xor_rect_rect_78) | 将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的并集减去交集。 |
| [xor_rect_f(rect)](#xor_rect_f_rect_79) | 将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的并集减去交集。 |
| [xor_rgn(region)](#xor_rgn_region_80) | 将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [Region](/imaging/python-net/aspose.imaging/region/) 的并集减去交集。 |


### Constructor: Region() {#Region__1}


```
 Region() 
```

初始化一个新的 [Region](/imaging/python-net/aspose.imaging/region/)。

### Constructor: Region(path) {#Region_path_2}


```
 Region(path) 
```

使用指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 初始化一个新的 [Region](/imaging/python-net/aspose.imaging/region/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 定义新 [Region](/imaging/python-net/aspose.imaging/region/) 的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)。 |

### Constructor: Region(rect) {#Region_rect_3}


```
 Region(rect) 
```

使用指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构初始化一个新的 [Region](/imaging/python-net/aspose.imaging/region/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 定义新 [Region](/imaging/python-net/aspose.imaging/region/) 内部的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Constructor: Region(rect) {#Region_rect_4}


```
 Region(rect) 
```

使用指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构初始化一个新的 [Region](/imaging/python-net/aspose.imaging/region/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 定义新 [Region](/imaging/python-net/aspose.imaging/region/) 内部的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: complement(path) {#complement_path_1}


```
 complement(path) 
```

更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其包含指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 中未与此 [Region](/imaging/python-net/aspose.imaging/region/) 相交的部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 用于补充此 [Region](/imaging/python-net/aspose.imaging/region/) 的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)。 |

### Method: complement(rect) {#complement_rect_2}


```
 complement(rect) 
```

更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其包含指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构中未与此 [Region](/imaging/python-net/aspose.imaging/region/) 相交的部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 用于补充此 [Region](/imaging/python-net/aspose.imaging/region/) 的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: complement(rect) {#complement_rect_3}


```
 complement(rect) 
```

更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其包含指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构中未与此 [Region](/imaging/python-net/aspose.imaging/region/) 相交的部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 用于补充此 [Region](/imaging/python-net/aspose.imaging/region/) 的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: complement(region) {#complement_region_4}


```
 complement(region) 
```

更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其包含指定的 [Region](/imaging/python-net/aspose.imaging/region/) 中未与此 [Region](/imaging/python-net/aspose.imaging/region/) 相交的部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | 用于补充此 [Region](/imaging/python-net/aspose.imaging/region/) 对象的 [Region](/imaging/python-net/aspose.imaging/region/) 对象。 |

### Method: complement_path(path) {#complement_path_path_5}


```
 complement_path(path) 
```

更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其包含指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 中未与此 [Region](/imaging/python-net/aspose.imaging/region/) 相交的部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 用于补充此 [Region](/imaging/python-net/aspose.imaging/region/) 的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)。 |

### Method: complement_rect(rect) {#complement_rect_rect_6}


```
 complement_rect(rect) 
```

更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其包含指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构中未与此 [Region](/imaging/python-net/aspose.imaging/region/) 相交的部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 用于补充此 [Region](/imaging/python-net/aspose.imaging/region/) 的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: complement_rect_f(rect) {#complement_rect_f_rect_7}


```
 complement_rect_f(rect) 
```

更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其包含指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构中未与此 [Region](/imaging/python-net/aspose.imaging/region/) 相交的部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 用于补充此 [Region](/imaging/python-net/aspose.imaging/region/) 的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: complement_rgn(region) {#complement_rgn_region_8}


```
 complement_rgn(region) 
```

更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其包含指定的 [Region](/imaging/python-net/aspose.imaging/region/) 中未与此 [Region](/imaging/python-net/aspose.imaging/region/) 相交的部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | 用于补充此 [Region](/imaging/python-net/aspose.imaging/region/) 对象的 [Region](/imaging/python-net/aspose.imaging/region/) 对象。 |

### Method: create_with_path(path)  [static] {#create_with_path_path_9}


```
 create_with_path(path) 
```

使用指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 初始化一个新的 [Region](/imaging/python-net/aspose.imaging/region/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 定义新 [Region](/imaging/python-net/aspose.imaging/region/) 的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)。 |

**Returns**

| Type | Description |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region/) |  |


### Method: create_with_rect(rect)  [static] {#create_with_rect_rect_10}


```
 create_with_rect(rect) 
```

使用指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构初始化一个新的 [Region](/imaging/python-net/aspose.imaging/region/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 定义新 [Region](/imaging/python-net/aspose.imaging/region/) 内部的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

**Returns**

| Type | Description |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region/) |  |


### Method: create_with_rect_f(rect)  [static] {#create_with_rect_f_rect_11}


```
 create_with_rect_f(rect) 
```

使用指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构初始化一个新的 [Region](/imaging/python-net/aspose.imaging/region/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 定义新 [Region](/imaging/python-net/aspose.imaging/region/) 内部的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

**Returns**

| Type | Description |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region/) |  |


### Method: deep_clone() {#deep_clone__12}


```
 deep_clone() 
```

创建此 [Region](/imaging/python-net/aspose.imaging/region/) 的精确深拷贝。

**Returns**

| Type | Description |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region/) | 此方法创建的 [Region](/imaging/python-net/aspose.imaging/region/)。 |


### Method: exclude(path) {#exclude_path_13}


```
 exclude(path) 
```

更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其仅包含其内部未与指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 相交的部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 要从此 [Region](/imaging/python-net/aspose.imaging/region/) 中排除的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)。 |

### Method: exclude(rect) {#exclude_rect_14}


```
 exclude(rect) 
```

更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其仅包含其内部未与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构相交的部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 要从此 [Region](/imaging/python-net/aspose.imaging/region/) 中排除的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: exclude(rect) {#exclude_rect_15}


```
 exclude(rect) 
```

更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其仅包含其内部未与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构相交的部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 要从此 [Region](/imaging/python-net/aspose.imaging/region/) 中排除的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: exclude(region) {#exclude_region_16}


```
 exclude(region) 
```

更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其仅包含其内部未与指定的 [Region](/imaging/python-net/aspose.imaging/region/) 相交的部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | 要从此 [Region](/imaging/python-net/aspose.imaging/region/) 中排除的 [Region](/imaging/python-net/aspose.imaging/region/)。 |

### Method: exclude_path(path) {#exclude_path_path_17}


```
 exclude_path(path) 
```

更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其仅包含其内部未与指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 相交的部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 要从此 [Region](/imaging/python-net/aspose.imaging/region/) 中排除的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)。 |

### Method: exclude_rect(rect) {#exclude_rect_rect_18}


```
 exclude_rect(rect) 
```

更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其仅包含其内部未与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构相交的部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 要从此 [Region](/imaging/python-net/aspose.imaging/region/) 中排除的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: exclude_rect_f(rect) {#exclude_rect_f_rect_19}


```
 exclude_rect_f(rect) 
```

更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其仅包含其内部未与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构相交的部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 要从此 [Region](/imaging/python-net/aspose.imaging/region/) 中排除的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: exclude_rgn(region) {#exclude_rgn_region_20}


```
 exclude_rgn(region) 
```

更新此 [Region](/imaging/python-net/aspose.imaging/region/)，使其仅包含其内部未与指定的 [Region](/imaging/python-net/aspose.imaging/region/) 相交的部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | 要从此 [Region](/imaging/python-net/aspose.imaging/region/) 中排除的 [Region](/imaging/python-net/aspose.imaging/region/)。 |

### Method: intersect(path) {#intersect_path_21}


```
 intersect(path) 
```

将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的交集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 与此 [Region](/imaging/python-net/aspose.imaging/region/) 相交的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)。 |

### Method: intersect(rect) {#intersect_rect_22}


```
 intersect(rect) 
```

将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的交集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 与此 [Region](/imaging/python-net/aspose.imaging/region/) 相交的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: intersect(rect) {#intersect_rect_23}


```
 intersect(rect) 
```

将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的交集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 与此 [Region](/imaging/python-net/aspose.imaging/region/) 相交的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: intersect(region) {#intersect_region_24}


```
 intersect(region) 
```

将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [Region](/imaging/python-net/aspose.imaging/region/) 的交集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | 与此 [Region](/imaging/python-net/aspose.imaging/region/) 相交的 [Region](/imaging/python-net/aspose.imaging/region/)。 |

### Method: intersect_path(path) {#intersect_path_path_25}


```
 intersect_path(path) 
```

将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的交集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 与此 [Region](/imaging/python-net/aspose.imaging/region/) 相交的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)。 |

### Method: intersect_rect(rect) {#intersect_rect_rect_26}


```
 intersect_rect(rect) 
```

将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的交集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 与此 [Region](/imaging/python-net/aspose.imaging/region/) 相交的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: intersect_rect_f(rect) {#intersect_rect_f_rect_27}


```
 intersect_rect_f(rect) 
```

将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的交集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 与此 [Region](/imaging/python-net/aspose.imaging/region/) 相交的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: intersect_rgn(region) {#intersect_rgn_region_28}


```
 intersect_rgn(region) 
```

将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [Region](/imaging/python-net/aspose.imaging/region/) 的交集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | 与此 [Region](/imaging/python-net/aspose.imaging/region/) 相交的 [Region](/imaging/python-net/aspose.imaging/region/)。 |

### Method: is_empty(g) {#is_empty_g_29}


```
 is_empty(g) 
```

测试此 [Region](/imaging/python-net/aspose.imaging/region/) 在指定绘图表面上是否具有空的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 表示绘图表面的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果在应用与 _g_ 关联的变换后，此 [Region](/imaging/python-net/aspose.imaging/region/) 的内部为空，则为 true；否则为 false。 |


### Method: is_infinite(g) {#is_infinite_g_30}


```
 is_infinite(g) 
```

测试此 [Region](/imaging/python-net/aspose.imaging/region/) 在指定绘图表面上是否具有无限的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 表示绘图表面的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果在应用与 _g_ 关联的变换后，此 [Region](/imaging/python-net/aspose.imaging/region/) 的内部为无限，则为 true；否则为 false。 |


### Method: is_visible(point) {#is_visible_point_31}


```
 is_visible(point) 
```

测试指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 要测试的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当 _point_ 位于此 [Region](/imaging/python-net/aspose.imaging/region/) 中时为 true；否则为 false。 |


### Method: is_visible(point) {#is_visible_point_32}


```
 is_visible(point) 
```

测试指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | 要测试的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当 _point_ 位于此 [Region](/imaging/python-net/aspose.imaging/region/) 中时为 true；否则为 false。 |


### Method: is_visible(point, g) {#is_visible_point_g_33}


```
 is_visible(point, g) 
```

测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 要测试的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构。 |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 表示图形上下文的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当 _point_ 位于此 [Region](/imaging/python-net/aspose.imaging/region/) 中时为 true；否则为 false。 |


### Method: is_visible(point, g) {#is_visible_point_g_34}


```
 is_visible(point, g) 
```

测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | 要测试的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构。 |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 表示图形上下文的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当 _point_ 位于此 [Region](/imaging/python-net/aspose.imaging/region/) 中时为 true；否则为 false。 |


### Method: is_visible(rect) {#is_visible_rect_35}


```
 is_visible(rect) 
```

测试指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 要测试的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当 _rect_ 的任何部分位于此 [Region](/imaging/python-net/aspose.imaging/region/) 中时为 true；否则为 false。 |


### Method: is_visible(rect) {#is_visible_rect_36}


```
 is_visible(rect) 
```

测试指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 要测试的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当 _rect_ 的任何部分位于此 [Region](/imaging/python-net/aspose.imaging/region/) 中时为 true；否则为 false。 |


### Method: is_visible(rect, g) {#is_visible_rect_g_37}


```
 is_visible(rect, g) 
```

测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 要测试的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 表示图形上下文的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当 _rect_ 位于此 [Region](/imaging/python-net/aspose.imaging/region/) 中时为 true；否则为 false。 |


### Method: is_visible(rect, g) {#is_visible_rect_g_38}


```
 is_visible(rect, g) 
```

测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 要测试的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 表示图形上下文的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当 _rect_ 位于此 [Region](/imaging/python-net/aspose.imaging/region/) 中时为 true；否则为 false。 |


### Method: is_visible(x, y) {#is_visible_x_y_39}


```
 is_visible(x, y) 
```

测试指定的点是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | float | 要测试的点的 x 坐标。 |
| y | float | 要测试的点的 y 坐标。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当指定的点位于此 [Region](/imaging/python-net/aspose.imaging/region/) 中时为 True；否则为 false。 |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_40}


```
 is_visible(x, y, g) 
```

测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定的点是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | float | 要测试的点的 x 坐标。 |
| y | float | 要测试的点的 y 坐标。 |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 表示图形上下文的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当指定的点位于此 [Region](/imaging/python-net/aspose.imaging/region/) 中时为 True；否则为 false。 |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_41}


```
 is_visible(x, y, g) 
```

测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定的点是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 要测试的点的 x 坐标。 |
| y | int | 要测试的点的 y 坐标。 |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 表示图形上下文的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当指定的点位于此 [Region](/imaging/python-net/aspose.imaging/region/) 中时为 True；否则为 false。 |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_42}


```
 is_visible(x, y, width, height) 
```

测试指定矩形的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | float | 要测试的矩形左上角的 x 坐标。 |
| y | float | 要测试的矩形左上角的 y 坐标。 |
| width | float | 要测试的矩形的宽度。 |
| height | float | 要测试的矩形的高度。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当指定矩形的任何部分位于此 [Region](/imaging/python-net/aspose.imaging/region/) 对象中时为 true；否则为 false。 |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_43}


```
 is_visible(x, y, width, height) 
```

测试指定矩形的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 要测试的矩形左上角的 x 坐标。 |
| y | int | 要测试的矩形左上角的 y 坐标。 |
| width | int | 要测试的矩形的宽度。 |
| height | int | 要测试的矩形的高度。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当指定矩形的任何部分位于此 [Region](/imaging/python-net/aspose.imaging/region/) 对象中时为 true；否则为 false。 |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_44}


```
 is_visible(x, y, width, height, g) 
```

测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定矩形的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | float | 要测试的矩形左上角的 x 坐标。 |
| y | float | 要测试的矩形左上角的 y 坐标。 |
| width | float | 要测试的矩形的宽度。 |
| height | float | 要测试的矩形的高度。 |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 表示图形上下文的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当指定矩形的任何部分位于此 [Region](/imaging/python-net/aspose.imaging/region/) 中时为 true；否则为 false。 |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_45}


```
 is_visible(x, y, width, height, g) 
```

测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定矩形的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 要测试的矩形左上角的 x 坐标。 |
| y | int | 要测试的矩形左上角的 y 坐标。 |
| width | int | 要测试的矩形的宽度。 |
| height | int | 要测试的矩形的高度。 |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 表示图形上下文的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当指定矩形的任何部分位于此 [Region](/imaging/python-net/aspose.imaging/region/) 中时为 true；否则为 false。 |


### Method: is_visible_f(x, y) {#is_visible_f_x_y_46}


```
 is_visible_f(x, y) 
```

测试指定的点是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | float | 要测试的点的 x 坐标。 |
| y | float | 要测试的点的 y 坐标。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当指定的点位于此 [Region](/imaging/python-net/aspose.imaging/region/) 中时为 True；否则为 false。 |


### Method: is_visible_point(point) {#is_visible_point_point_47}


```
 is_visible_point(point) 
```

测试指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | 要测试的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当 _point_ 位于此 [Region](/imaging/python-net/aspose.imaging/region/) 中时为 true；否则为 false。 |


### Method: is_visible_point_f(point) {#is_visible_point_f_point_48}


```
 is_visible_point_f(point) 
```

测试指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 要测试的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当 _point_ 位于此 [Region](/imaging/python-net/aspose.imaging/region/) 中时为 true；否则为 false。 |


### Method: is_visible_point_f_with_graphics(point, g) {#is_visible_point_f_with_graphics_point_g_49}


```
 is_visible_point_f_with_graphics(point, g) 
```

测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 要测试的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构。 |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 表示图形上下文的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当 _point_ 位于此 [Region](/imaging/python-net/aspose.imaging/region/) 中时为 true；否则为 false。 |


### Method: is_visible_point_with_graphics(point, g) {#is_visible_point_with_graphics_point_g_50}


```
 is_visible_point_with_graphics(point, g) 
```

测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定的 [Point](/imaging/python-net/aspose.imaging/point/) 结构是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | 要测试的 [Point](/imaging/python-net/aspose.imaging/point/) 结构。 |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 表示图形上下文的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当 _point_ 位于此 [Region](/imaging/python-net/aspose.imaging/region/) 中时为 true；否则为 false。 |


### Method: is_visible_rect(rect) {#is_visible_rect_rect_51}


```
 is_visible_rect(rect) 
```

测试指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 要测试的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当 _rect_ 的任何部分位于此 [Region](/imaging/python-net/aspose.imaging/region/) 中时为 true；否则为 false。 |


### Method: is_visible_rect_f(rect) {#is_visible_rect_f_rect_52}


```
 is_visible_rect_f(rect) 
```

测试指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 要测试的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当 _rect_ 的任何部分位于此 [Region](/imaging/python-net/aspose.imaging/region/) 中时为 true；否则为 false。 |


### Method: is_visible_rect_f_with_graphics(rect, g) {#is_visible_rect_f_with_graphics_rect_g_53}


```
 is_visible_rect_f_with_graphics(rect, g) 
```

测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 要测试的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 表示图形上下文的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当 _rect_ 位于此 [Region](/imaging/python-net/aspose.imaging/region/) 中时为 true；否则为 false。 |


### Method: is_visible_rect_with_graphics(rect, g) {#is_visible_rect_with_graphics_rect_g_54}


```
 is_visible_rect_with_graphics(rect, g) 
```

测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 要测试的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构。 |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 表示图形上下文的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当 _rect_ 的任何部分位于此 [Region](/imaging/python-net/aspose.imaging/region/) 中时为 true；否则为 false。 |


### Method: is_visible_with_graphics(x, y, g) {#is_visible_with_graphics_x_y_g_55}


```
 is_visible_with_graphics(x, y, g) 
```

测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定的点是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 要测试的点的 x 坐标。 |
| y | int | 要测试的点的 y 坐标。 |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 表示图形上下文的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当指定的点位于此 [Region](/imaging/python-net/aspose.imaging/region/) 中时为 True；否则为 false。 |


### Method: is_visible_with_graphics_f(x, y, g) {#is_visible_with_graphics_f_x_y_g_56}


```
 is_visible_with_graphics_f(x, y, g) 
```

测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定的点是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | float | 要测试的点的 x 坐标。 |
| y | float | 要测试的点的 y 坐标。 |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 表示图形上下文的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当指定的点位于此 [Region](/imaging/python-net/aspose.imaging/region/) 中时为 True；否则为 false。 |


### Method: is_visible_xywh(x, y, width, height) {#is_visible_xywh_x_y_width_height_57}


```
 is_visible_xywh(x, y, width, height) 
```

测试指定矩形的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 要测试的矩形左上角的 x 坐标。 |
| y | int | 要测试的矩形左上角的 y 坐标。 |
| width | int | 要测试的矩形的宽度。 |
| height | int | 要测试的矩形的高度。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当指定矩形的任何部分位于此 [Region](/imaging/python-net/aspose.imaging/region/) 对象中时为 true；否则为 false。 |


### Method: is_visible_xywh_graphics(x, y, width, height, g) {#is_visible_xywh_graphics_x_y_width_height_g_58}


```
 is_visible_xywh_graphics(x, y, width, height, g) 
```

测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定矩形的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 要测试的矩形左上角的 x 坐标。 |
| y | int | 要测试的矩形左上角的 y 坐标。 |
| width | int | 要测试的矩形的宽度。 |
| height | int | 要测试的矩形的高度。 |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 表示图形上下文的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当指定矩形的任何部分位于此 [Region](/imaging/python-net/aspose.imaging/region/) 中时为 true；否则为 false。 |


### Method: is_visible_xywh_graphics_f(x, y, width, height, g) {#is_visible_xywh_graphics_f_x_y_width_height_g_59}


```
 is_visible_xywh_graphics_f(x, y, width, height, g) 
```

测试在使用指定的 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 绘制时，指定矩形的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | float | 要测试的矩形左上角的 x 坐标。 |
| y | float | 要测试的矩形左上角的 y 坐标。 |
| width | float | 要测试的矩形的宽度。 |
| height | float | 要测试的矩形的高度。 |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 表示图形上下文的 [Graphics](/imaging/python-net/aspose.imaging/graphics/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当指定矩形的任何部分位于此 [Region](/imaging/python-net/aspose.imaging/region/) 中时为 true；否则为 false。 |


### Method: is_visible_xywhf(x, y, width, height) {#is_visible_xywhf_x_y_width_height_60}


```
 is_visible_xywhf(x, y, width, height) 
```

测试指定矩形的任何部分是否包含在此 [Region](/imaging/python-net/aspose.imaging/region/) 中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | float | 要测试的矩形左上角的 x 坐标。 |
| y | float | 要测试的矩形左上角的 y 坐标。 |
| width | float | 要测试的矩形的宽度。 |
| height | float | 要测试的矩形的高度。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 当指定矩形的任何部分位于此 [Region](/imaging/python-net/aspose.imaging/region/) 对象中时为 true；否则为 false。 |


### Method: transform(matrix) {#transform_matrix_61}


```
 transform(matrix) 
```

使用指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 对此 [Region](/imaging/python-net/aspose.imaging/region/) 进行变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 用于变换此 [Region](/imaging/python-net/aspose.imaging/region/) 的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |

### Method: translate(dx, dy) {#translate_dx_dy_62}


```
 translate(dx, dy) 
```

按指定的量偏移此 [Region](/imaging/python-net/aspose.imaging/region/) 的坐标。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dx | float | 此 [Region](/imaging/python-net/aspose.imaging/region/) 的水平偏移量。 |
| dy | float | 此 [Region](/imaging/python-net/aspose.imaging/region/) 的垂直偏移量。 |

### Method: translate(dx, dy) {#translate_dx_dy_63}


```
 translate(dx, dy) 
```

按指定的量偏移此 [Region](/imaging/python-net/aspose.imaging/region/) 的坐标。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dx | int | 此 [Region](/imaging/python-net/aspose.imaging/region/) 的水平偏移量。 |
| dy | int | 此 [Region](/imaging/python-net/aspose.imaging/region/) 的垂直偏移量。 |

### Method: translate_f(dx, dy) {#translate_f_dx_dy_64}


```
 translate_f(dx, dy) 
```

按指定的量偏移此 [Region](/imaging/python-net/aspose.imaging/region/) 的坐标。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dx | float | 此 [Region](/imaging/python-net/aspose.imaging/region/) 的水平偏移量。 |
| dy | float | 此 [Region](/imaging/python-net/aspose.imaging/region/) 的垂直偏移量。 |

### Method: union(path) {#union_path_65}


```
 union(path) 
```

将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的并集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 与此 [Region](/imaging/python-net/aspose.imaging/region/) 合并的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)。 |

### Method: union(rect) {#union_rect_66}


```
 union(rect) 
```

将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的并集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 与此 [Region](/imaging/python-net/aspose.imaging/region/) 合并的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: union(rect) {#union_rect_67}


```
 union(rect) 
```

将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的并集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 与此 [Region](/imaging/python-net/aspose.imaging/region/) 合并的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: union(region) {#union_region_68}


```
 union(region) 
```

将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [Region](/imaging/python-net/aspose.imaging/region/) 的并集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | 与此 [Region](/imaging/python-net/aspose.imaging/region/) 合并的 [Region](/imaging/python-net/aspose.imaging/region/)。 |

### Method: union_path(path) {#union_path_path_69}


```
 union_path(path) 
```

将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的并集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 与此 [Region](/imaging/python-net/aspose.imaging/region/) 合并的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)。 |

### Method: union_rect(rect) {#union_rect_rect_70}


```
 union_rect(rect) 
```

将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的并集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 与此 [Region](/imaging/python-net/aspose.imaging/region/) 合并的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: union_rect_f(rect) {#union_rect_f_rect_71}


```
 union_rect_f(rect) 
```

将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的并集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 与此 [Region](/imaging/python-net/aspose.imaging/region/) 合并的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: union_rgn(region) {#union_rgn_region_72}


```
 union_rgn(region) 
```

将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [Region](/imaging/python-net/aspose.imaging/region/) 的并集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | 与此 [Region](/imaging/python-net/aspose.imaging/region/) 合并的 [Region](/imaging/python-net/aspose.imaging/region/)。 |

### Method: xor(path) {#xor_path_73}


```
 xor(path) 
```

将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的并集减去交集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 与此 [Region](/imaging/python-net/aspose.imaging/region/) 进行异或的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)。 |

### Method: xor(rect) {#xor_rect_74}


```
 xor(rect) 
```

将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的并集减去交集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 与此 [Region](/imaging/python-net/aspose.imaging/region/) 进行异或的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: xor(rect) {#xor_rect_75}


```
 xor(rect) 
```

将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的并集减去交集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 与此 [Region](/imaging/python-net/aspose.imaging/region/) 进行异或的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: xor(region) {#xor_region_76}


```
 xor(region) 
```

将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [Region](/imaging/python-net/aspose.imaging/region/) 的并集减去交集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | 与此 [Region](/imaging/python-net/aspose.imaging/region/) 进行异或的 [Region](/imaging/python-net/aspose.imaging/region/)。 |

### Method: xor_path(path) {#xor_path_path_77}


```
 xor_path(path) 
```

将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 的并集减去交集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 与此 [Region](/imaging/python-net/aspose.imaging/region/) 进行异或的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)。 |

### Method: xor_rect(rect) {#xor_rect_rect_78}


```
 xor_rect(rect) 
```

将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的并集减去交集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 与此 [Region](/imaging/python-net/aspose.imaging/region/) 进行异或的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: xor_rect_f(rect) {#xor_rect_f_rect_79}


```
 xor_rect_f(rect) 
```

将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的并集减去交集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 与此 [Region](/imaging/python-net/aspose.imaging/region/) 进行异或的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: xor_rgn(region) {#xor_rgn_region_80}


```
 xor_rgn(region) 
```

将此 [Region](/imaging/python-net/aspose.imaging/region/) 更新为其自身与指定的 [Region](/imaging/python-net/aspose.imaging/region/) 的并集减去交集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | 与此 [Region](/imaging/python-net/aspose.imaging/region/) 进行异或的 [Region](/imaging/python-net/aspose.imaging/region/)。 |

