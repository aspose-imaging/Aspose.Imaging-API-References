---
title: Region Class
type: docs
weight: 7170
url: /python-net/aspose.imaging/region/
---

**Summary:** Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Region

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Region()](#Region__1) | Initializes a new [Region](/imaging/python-net/aspose.imaging/region/). |
| [Region(path)](#Region_path_2) | Initializes a new [Region](/imaging/python-net/aspose.imaging/region/) with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [Region(rect)](#Region_rect_3) | Initializes a new [Region](/imaging/python-net/aspose.imaging/region/) from the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [Region(rect)](#Region_rect_4) | Initializes a new [Region](/imaging/python-net/aspose.imaging/region/) from the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [complement(path)](#complement_path_1) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement(rect)](#complement_rect_2) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement(rect)](#complement_rect_3) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement(region)](#complement_region_4) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [Region](/imaging/python-net/aspose.imaging/region/) that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement_path(path)](#complement_path_path_5) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement_rect(rect)](#complement_rect_rect_6) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement_rect_f(rect)](#complement_rect_f_rect_7) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement_rgn(region)](#complement_rgn_region_8) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [Region](/imaging/python-net/aspose.imaging/region/) that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |
| [create_with_path(path)](#create_with_path_path_9) | Initializes a new [Region](/imaging/python-net/aspose.imaging/region/) with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [create_with_rect(rect)](#create_with_rect_rect_10) | Initializes a new [Region](/imaging/python-net/aspose.imaging/region/) from the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [create_with_rect_f(rect)](#create_with_rect_f_rect_11) | Initializes a new [Region](/imaging/python-net/aspose.imaging/region/) from the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [deep_clone()](#deep_clone__12) | Creates an exact deep copy of this [Region](/imaging/python-net/aspose.imaging/region/). |
| [exclude(path)](#exclude_path_13) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [exclude(rect)](#exclude_rect_14) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [exclude(rect)](#exclude_rect_15) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [exclude(region)](#exclude_region_16) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [Region](/imaging/python-net/aspose.imaging/region/). |
| [exclude_path(path)](#exclude_path_path_17) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [exclude_rect(rect)](#exclude_rect_rect_18) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [exclude_rect_f(rect)](#exclude_rect_f_rect_19) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [exclude_rgn(region)](#exclude_rgn_region_20) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [Region](/imaging/python-net/aspose.imaging/region/). |
| [intersect(path)](#intersect_path_21) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [intersect(rect)](#intersect_rect_22) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [intersect(rect)](#intersect_rect_23) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [intersect(region)](#intersect_region_24) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [Region](/imaging/python-net/aspose.imaging/region/). |
| [intersect_path(path)](#intersect_path_path_25) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [intersect_rect(rect)](#intersect_rect_rect_26) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [intersect_rect_f(rect)](#intersect_rect_f_rect_27) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [intersect_rgn(region)](#intersect_rgn_region_28) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_empty(g)](#is_empty_g_29) | Tests whether this [Region](/imaging/python-net/aspose.imaging/region/) has an empty interior on the specified drawing surface. |
| [is_infinite(g)](#is_infinite_g_30) | Tests whether this [Region](/imaging/python-net/aspose.imaging/region/) has an infinite interior on the specified drawing surface. |
| [is_visible(point)](#is_visible_point_31) | Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(point)](#is_visible_point_32) | Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(point, g)](#is_visible_point_g_33) | Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(point, g)](#is_visible_point_g_34) | Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(rect)](#is_visible_rect_35) | Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(rect)](#is_visible_rect_36) | Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(rect, g)](#is_visible_rect_g_37) | Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(rect, g)](#is_visible_rect_g_38) | Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(x, y)](#is_visible_x_y_39) | Tests whether the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(x, y, g)](#is_visible_x_y_g_40) | Tests whether the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(x, y, g)](#is_visible_x_y_g_41) | Tests whether the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_42) | Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_43) | Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_44) | Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_45) | Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_f(x, y)](#is_visible_f_x_y_46) | Tests whether the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_point(point)](#is_visible_point_point_47) | Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_point_f(point)](#is_visible_point_f_point_48) | Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_point_f_with_graphics(point, g)](#is_visible_point_f_with_graphics_point_g_49) | Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_point_with_graphics(point, g)](#is_visible_point_with_graphics_point_g_50) | Tests whether the specified [Point](/imaging/python-net/aspose.imaging/point/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_rect(rect)](#is_visible_rect_rect_51) | Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_rect_f(rect)](#is_visible_rect_f_rect_52) | Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_rect_f_with_graphics(rect, g)](#is_visible_rect_f_with_graphics_rect_g_53) | Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_rect_with_graphics(rect, g)](#is_visible_rect_with_graphics_rect_g_54) | Tests whether any portion of the specified [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_with_graphics(x, y, g)](#is_visible_with_graphics_x_y_g_55) | Tests whether the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_with_graphics_f(x, y, g)](#is_visible_with_graphics_f_x_y_g_56) | Tests whether the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_xywh(x, y, width, height)](#is_visible_xywh_x_y_width_height_57) | Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_xywh_graphics(x, y, width, height, g)](#is_visible_xywh_graphics_x_y_width_height_g_58) | Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_xywh_graphics_f(x, y, width, height, g)](#is_visible_xywh_graphics_f_x_y_width_height_g_59) | Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_xywhf(x, y, width, height)](#is_visible_xywhf_x_y_width_height_60) | Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| make_empty() | Initializes this [Region](/imaging/python-net/aspose.imaging/region/) to an empty interior. |
| make_infinite() | Initializes this [Region](/imaging/python-net/aspose.imaging/region/) object to an infinite interior. |
| [transform(matrix)](#transform_matrix_61) | Transforms this [Region](/imaging/python-net/aspose.imaging/region/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [translate(dx, dy)](#translate_dx_dy_62) | Offsets the coordinates of this [Region](/imaging/python-net/aspose.imaging/region/) by the specified amount. |
| [translate(dx, dy)](#translate_dx_dy_63) | Offsets the coordinates of this [Region](/imaging/python-net/aspose.imaging/region/) by the specified amount. |
| [translate_f(dx, dy)](#translate_f_dx_dy_64) | Offsets the coordinates of this [Region](/imaging/python-net/aspose.imaging/region/) by the specified amount. |
| [union(path)](#union_path_65) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [union(rect)](#union_rect_66) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [union(rect)](#union_rect_67) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [union(region)](#union_region_68) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [Region](/imaging/python-net/aspose.imaging/region/). |
| [union_path(path)](#union_path_path_69) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [union_rect(rect)](#union_rect_rect_70) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [union_rect_f(rect)](#union_rect_f_rect_71) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [union_rgn(region)](#union_rgn_region_72) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [Region](/imaging/python-net/aspose.imaging/region/). |
| [xor(path)](#xor_path_73) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [xor(rect)](#xor_rect_74) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [xor(rect)](#xor_rect_75) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [xor(region)](#xor_region_76) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [Region](/imaging/python-net/aspose.imaging/region/). |
| [xor_path(path)](#xor_path_path_77) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [xor_rect(rect)](#xor_rect_rect_78) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [xor_rect_f(rect)](#xor_rect_f_rect_79) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [xor_rgn(region)](#xor_rgn_region_80) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [Region](/imaging/python-net/aspose.imaging/region/). |


### Constructor: Region() {#Region__1}


```
 Region() 
```

Initializes a new [Region](/imaging/python-net/aspose.imaging/region/).

### Constructor: Region(path) {#Region_path_2}


```
 Region(path) 
```

Initializes a new [Region](/imaging/python-net/aspose.imaging/region/) with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | A [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) that defines the new [Region](/imaging/python-net/aspose.imaging/region/). |

### Constructor: Region(rect) {#Region_rect_3}


```
 Region(rect) 
```

Initializes a new [Region](/imaging/python-net/aspose.imaging/region/) from the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | A [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that defines the interior of the new [Region](/imaging/python-net/aspose.imaging/region/). |

### Constructor: Region(rect) {#Region_rect_4}


```
 Region(rect) 
```

Initializes a new [Region](/imaging/python-net/aspose.imaging/region/) from the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | A [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that defines the interior of the new [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement(path) {#complement_path_1}


```
 complement(path) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | The [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to complement this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement(rect) {#complement_rect_2}


```
 complement(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to complement this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement(rect) {#complement_rect_3}


```
 complement(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to complement this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement(region) {#complement_region_4}


```
 complement(region) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [Region](/imaging/python-net/aspose.imaging/region/) that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | The [Region](/imaging/python-net/aspose.imaging/region/) object to complement this [Region](/imaging/python-net/aspose.imaging/region/) object. |

### Method: complement_path(path) {#complement_path_path_5}


```
 complement_path(path) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | The [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to complement this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement_rect(rect) {#complement_rect_rect_6}


```
 complement_rect(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to complement this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement_rect_f(rect) {#complement_rect_f_rect_7}


```
 complement_rect_f(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to complement this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement_rgn(region) {#complement_rgn_region_8}


```
 complement_rgn(region) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [Region](/imaging/python-net/aspose.imaging/region/) that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | The [Region](/imaging/python-net/aspose.imaging/region/) object to complement this [Region](/imaging/python-net/aspose.imaging/region/) object. |

### Method: create_with_path(path)  [static] {#create_with_path_path_9}


```
 create_with_path(path) 
```

Initializes a new [Region](/imaging/python-net/aspose.imaging/region/) with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | A [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) that defines the new [Region](/imaging/python-net/aspose.imaging/region/). |

**Returns**

| Type | Description |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region/) |  |


### Method: create_with_rect(rect)  [static] {#create_with_rect_rect_10}


```
 create_with_rect(rect) 
```

Initializes a new [Region](/imaging/python-net/aspose.imaging/region/) from the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | A [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that defines the interior of the new [Region](/imaging/python-net/aspose.imaging/region/). |

**Returns**

| Type | Description |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region/) |  |


### Method: create_with_rect_f(rect)  [static] {#create_with_rect_f_rect_11}


```
 create_with_rect_f(rect) 
```

Initializes a new [Region](/imaging/python-net/aspose.imaging/region/) from the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | A [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that defines the interior of the new [Region](/imaging/python-net/aspose.imaging/region/). |

**Returns**

| Type | Description |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region/) |  |


### Method: deep_clone() {#deep_clone__12}


```
 deep_clone() 
```

Creates an exact deep copy of this [Region](/imaging/python-net/aspose.imaging/region/).

**Returns**

| Type | Description |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region/) | The [Region](/imaging/python-net/aspose.imaging/region/) that this method creates. |


### Method: exclude(path) {#exclude_path_13}


```
 exclude(path) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | The [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to exclude from this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude(rect) {#exclude_rect_14}


```
 exclude(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to exclude from this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude(rect) {#exclude_rect_15}


```
 exclude(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to exclude from this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude(region) {#exclude_region_16}


```
 exclude(region) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | The [Region](/imaging/python-net/aspose.imaging/region/) to exclude from this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude_path(path) {#exclude_path_path_17}


```
 exclude_path(path) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | The [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to exclude from this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude_rect(rect) {#exclude_rect_rect_18}


```
 exclude_rect(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to exclude from this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude_rect_f(rect) {#exclude_rect_f_rect_19}


```
 exclude_rect_f(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to exclude from this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude_rgn(region) {#exclude_rgn_region_20}


```
 exclude_rgn(region) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | The [Region](/imaging/python-net/aspose.imaging/region/) to exclude from this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect(path) {#intersect_path_21}


```
 intersect(path) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | The [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect(rect) {#intersect_rect_22}


```
 intersect(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect(rect) {#intersect_rect_23}


```
 intersect(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect(region) {#intersect_region_24}


```
 intersect(region) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | The [Region](/imaging/python-net/aspose.imaging/region/) to intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect_path(path) {#intersect_path_path_25}


```
 intersect_path(path) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | The [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect_rect(rect) {#intersect_rect_rect_26}


```
 intersect_rect(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect_rect_f(rect) {#intersect_rect_f_rect_27}


```
 intersect_rect_f(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect_rgn(region) {#intersect_rgn_region_28}


```
 intersect_rgn(region) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | The [Region](/imaging/python-net/aspose.imaging/region/) to intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: is_empty(g) {#is_empty_g_29}


```
 is_empty(g) 
```

Tests whether this [Region](/imaging/python-net/aspose.imaging/region/) has an empty interior on the specified drawing surface.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a drawing surface. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true if the interior of this [Region](/imaging/python-net/aspose.imaging/region/) is empty when the transformation associated with _g_ is applied; otherwise, false. |


### Method: is_infinite(g) {#is_infinite_g_30}


```
 is_infinite(g) 
```

Tests whether this [Region](/imaging/python-net/aspose.imaging/region/) has an infinite interior on the specified drawing surface.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a drawing surface. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true if the interior of this [Region](/imaging/python-net/aspose.imaging/region/) is infinite when the transformation associated with _g_ is applied; otherwise, false. |


### Method: is_visible(point) {#is_visible_point_31}


```
 is_visible(point) 
```

Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) structure to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when _point_ is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### Method: is_visible(point) {#is_visible_point_32}


```
 is_visible(point) 
```

Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) structure to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when _point_ is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### Method: is_visible(point, g) {#is_visible_point_g_33}


```
 is_visible(point, g) 
```

Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) structure to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when _point_ is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### Method: is_visible(point, g) {#is_visible_point_g_34}


```
 is_visible(point, g) 
```

Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) structure to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when _point_ is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### Method: is_visible(rect) {#is_visible_rect_35}


```
 is_visible(rect) 
```

Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of _rect_ is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### Method: is_visible(rect) {#is_visible_rect_36}


```
 is_visible(rect) 
```

Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of _rect_ is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### Method: is_visible(rect, g) {#is_visible_rect_g_37}


```
 is_visible(rect, g) 
```

Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when _rect_ is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### Method: is_visible(rect, g) {#is_visible_rect_g_38}


```
 is_visible(rect, g) 
```

Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when _rect_ is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### Method: is_visible(x, y) {#is_visible_x_y_39}


```
 is_visible(x, y) 
```

Tests whether the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | True when the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_40}


```
 is_visible(x, y, g) 
```

Tests whether the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | True when the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_41}


```
 is_visible(x, y, g) 
```

Tests whether the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | True when the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_42}


```
 is_visible(x, y, width, height) 
```

Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the upper-left corner of the rectangle to test. |
| y | float | The y-coordinate of the upper-left corner of the rectangle to test. |
| width | float | The width of the rectangle to test. |
| height | float | The height of the rectangle to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/) object; otherwise, false. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_43}


```
 is_visible(x, y, width, height) 
```

Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the upper-left corner of the rectangle to test. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to test. |
| width | int | The width of the rectangle to test. |
| height | int | The height of the rectangle to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/) object; otherwise, false. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_44}


```
 is_visible(x, y, width, height, g) 
```

Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the upper-left corner of the rectangle to test. |
| y | float | The y-coordinate of the upper-left corner of the rectangle to test. |
| width | float | The width of the rectangle to test. |
| height | float | The height of the rectangle to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_45}


```
 is_visible(x, y, width, height, g) 
```

Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the upper-left corner of the rectangle to test. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to test. |
| width | int | The width of the rectangle to test. |
| height | int | The height of the rectangle to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### Method: is_visible_f(x, y) {#is_visible_f_x_y_46}


```
 is_visible_f(x, y) 
```

Tests whether the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | True when the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### Method: is_visible_point(point) {#is_visible_point_point_47}


```
 is_visible_point(point) 
```

Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) structure to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when _point_ is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### Method: is_visible_point_f(point) {#is_visible_point_f_point_48}


```
 is_visible_point_f(point) 
```

Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) structure to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when _point_ is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### Method: is_visible_point_f_with_graphics(point, g) {#is_visible_point_f_with_graphics_point_g_49}


```
 is_visible_point_f_with_graphics(point, g) 
```

Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) structure to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when _point_ is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### Method: is_visible_point_with_graphics(point, g) {#is_visible_point_with_graphics_point_g_50}


```
 is_visible_point_with_graphics(point, g) 
```

Tests whether the specified [Point](/imaging/python-net/aspose.imaging/point/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | The [Point](/imaging/python-net/aspose.imaging/point/) structure to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when _point_ is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### Method: is_visible_rect(rect) {#is_visible_rect_rect_51}


```
 is_visible_rect(rect) 
```

Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of _rect_ is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### Method: is_visible_rect_f(rect) {#is_visible_rect_f_rect_52}


```
 is_visible_rect_f(rect) 
```

Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of _rect_ is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### Method: is_visible_rect_f_with_graphics(rect, g) {#is_visible_rect_f_with_graphics_rect_g_53}


```
 is_visible_rect_f_with_graphics(rect, g) 
```

Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when _rect_ is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### Method: is_visible_rect_with_graphics(rect, g) {#is_visible_rect_with_graphics_rect_g_54}


```
 is_visible_rect_with_graphics(rect, g) 
```

Tests whether any portion of the specified [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of the _rect_ is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### Method: is_visible_with_graphics(x, y, g) {#is_visible_with_graphics_x_y_g_55}


```
 is_visible_with_graphics(x, y, g) 
```

Tests whether the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | True when the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### Method: is_visible_with_graphics_f(x, y, g) {#is_visible_with_graphics_f_x_y_g_56}


```
 is_visible_with_graphics_f(x, y, g) 
```

Tests whether the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | True when the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### Method: is_visible_xywh(x, y, width, height) {#is_visible_xywh_x_y_width_height_57}


```
 is_visible_xywh(x, y, width, height) 
```

Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the upper-left corner of the rectangle to test. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to test. |
| width | int | The width of the rectangle to test. |
| height | int | The height of the rectangle to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/) object; otherwise, false. |


### Method: is_visible_xywh_graphics(x, y, width, height, g) {#is_visible_xywh_graphics_x_y_width_height_g_58}


```
 is_visible_xywh_graphics(x, y, width, height, g) 
```

Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the upper-left corner of the rectangle to test. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to test. |
| width | int | The width of the rectangle to test. |
| height | int | The height of the rectangle to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### Method: is_visible_xywh_graphics_f(x, y, width, height, g) {#is_visible_xywh_graphics_f_x_y_width_height_g_59}


```
 is_visible_xywh_graphics_f(x, y, width, height, g) 
```

Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the upper-left corner of the rectangle to test. |
| y | float | The y-coordinate of the upper-left corner of the rectangle to test. |
| width | float | The width of the rectangle to test. |
| height | float | The height of the rectangle to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### Method: is_visible_xywhf(x, y, width, height) {#is_visible_xywhf_x_y_width_height_60}


```
 is_visible_xywhf(x, y, width, height) 
```

Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the upper-left corner of the rectangle to test. |
| y | float | The y-coordinate of the upper-left corner of the rectangle to test. |
| width | float | The width of the rectangle to test. |
| height | float | The height of the rectangle to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/) object; otherwise, false. |


### Method: transform(matrix) {#transform_matrix_61}


```
 transform(matrix) 
```

Transforms this [Region](/imaging/python-net/aspose.imaging/region/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | The [Matrix](/imaging/python-net/aspose.imaging/matrix/) by which to transform this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: translate(dx, dy) {#translate_dx_dy_62}


```
 translate(dx, dy) 
```

Offsets the coordinates of this [Region](/imaging/python-net/aspose.imaging/region/) by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | float | The amount to offset this [Region](/imaging/python-net/aspose.imaging/region/) horizontally. |
| dy | float | The amount to offset this [Region](/imaging/python-net/aspose.imaging/region/) vertically. |

### Method: translate(dx, dy) {#translate_dx_dy_63}


```
 translate(dx, dy) 
```

Offsets the coordinates of this [Region](/imaging/python-net/aspose.imaging/region/) by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | int | The amount to offset this [Region](/imaging/python-net/aspose.imaging/region/) horizontally. |
| dy | int | The amount to offset this [Region](/imaging/python-net/aspose.imaging/region/) vertically. |

### Method: translate_f(dx, dy) {#translate_f_dx_dy_64}


```
 translate_f(dx, dy) 
```

Offsets the coordinates of this [Region](/imaging/python-net/aspose.imaging/region/) by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | float | The amount to offset this [Region](/imaging/python-net/aspose.imaging/region/) horizontally. |
| dy | float | The amount to offset this [Region](/imaging/python-net/aspose.imaging/region/) vertically. |

### Method: union(path) {#union_path_65}


```
 union(path) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | The [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to unite with this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union(rect) {#union_rect_66}


```
 union(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to unite with this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union(rect) {#union_rect_67}


```
 union(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to unite with this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union(region) {#union_region_68}


```
 union(region) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | The [Region](/imaging/python-net/aspose.imaging/region/) to unite with this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union_path(path) {#union_path_path_69}


```
 union_path(path) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | The [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to unite with this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union_rect(rect) {#union_rect_rect_70}


```
 union_rect(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to unite with this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union_rect_f(rect) {#union_rect_f_rect_71}


```
 union_rect_f(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to unite with this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union_rgn(region) {#union_rgn_region_72}


```
 union_rgn(region) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | The [Region](/imaging/python-net/aspose.imaging/region/) to unite with this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor(path) {#xor_path_73}


```
 xor(path) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | The [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to xor with this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor(rect) {#xor_rect_74}


```
 xor(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to xor with this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor(rect) {#xor_rect_75}


```
 xor(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to xor with this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor(region) {#xor_region_76}


```
 xor(region) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | The [Region](/imaging/python-net/aspose.imaging/region/) to xor with this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor_path(path) {#xor_path_path_77}


```
 xor_path(path) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | The [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to xor with this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor_rect(rect) {#xor_rect_rect_78}


```
 xor_rect(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to xor with this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor_rect_f(rect) {#xor_rect_f_rect_79}


```
 xor_rect_f(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to xor with this [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor_rgn(region) {#xor_rgn_region_80}


```
 xor_rgn(region) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | The [Region](/imaging/python-net/aspose.imaging/region/) to xor with this [Region](/imaging/python-net/aspose.imaging/region/). |

