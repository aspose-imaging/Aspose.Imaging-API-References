---
title: Region Class
type: docs
weight: 6960
url: /python-net/aspose.imaging/region/
---

Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Region

**Aspose.Imaging Version:** 23.6

The Region type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [Region()](#Region__0) | Initializes a new [Region](/imaging/python-net/aspose.imaging/region/). |
| [Region(rect)](#Region_rect_1) | Initializes a new instance of the Region class |
| [Region(rect)](#Region_rect_2) | Initializes a new instance of the Region class |
| [Region(path)](#Region_path_3) | Initializes a new instance of the Region class |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [intersect(rect)](#intersect_rect_4) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [intersect(rect)](#intersect_rect_5) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [intersect(path)](#intersect_path_6) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [intersect(region)](#intersect_region_7) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [Region](/imaging/python-net/aspose.imaging/region/). |
| [union(rect)](#union_rect_8) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [union(rect)](#union_rect_9) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [union(path)](#union_path_10) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [union(region)](#union_region_11) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [Region](/imaging/python-net/aspose.imaging/region/). |
| [xor(rect)](#xor_rect_12) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [xor(rect)](#xor_rect_13) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [xor(path)](#xor_path_14) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [xor(region)](#xor_region_15) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [Region](/imaging/python-net/aspose.imaging/region/). |
| [exclude(rect)](#exclude_rect_16) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [exclude(rect)](#exclude_rect_17) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [exclude(path)](#exclude_path_18) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [exclude(region)](#exclude_region_19) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement(rect)](#complement_rect_20) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement(rect)](#complement_rect_21) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement(path)](#complement_path_22) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement(region)](#complement_region_23) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [Region](/imaging/python-net/aspose.imaging/region/) that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |
| [translate(dx, dy)](#translate_dx_dy_24) | Offsets the coordinates of this [Region](/imaging/python-net/aspose.imaging/region/) by the specified amount. |
| [translate(dx, dy)](#translate_dx_dy_25) | Offsets the coordinates of this [Region](/imaging/python-net/aspose.imaging/region/) by the specified amount. |
| [is_visible(x, y)](#is_visible_x_y_26) | Tests whether the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(point)](#is_visible_point_27) | Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(x, y, g)](#is_visible_x_y_g_28) | Tests whether the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(point, g)](#is_visible_point_g_29) | Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_30) | Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(rect)](#is_visible_rect_31) | Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_32) | Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(rect, g)](#is_visible_rect_g_33) | Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(x, y, g)](#is_visible_x_y_g_34) | Tests whether the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(point)](#is_visible_point_35) | Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(point, g)](#is_visible_point_g_36) | Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_37) | Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(rect)](#is_visible_rect_38) | Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_39) | Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(rect, g)](#is_visible_rect_g_40) | Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [create_with_rect_f(rect)](#create_with_rect_f_rect_41) | Initializes a new [Region](/imaging/python-net/aspose.imaging/region/) from the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [create_with_rect(rect)](#create_with_rect_rect_42) | Initializes a new [Region](/imaging/python-net/aspose.imaging/region/) from the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [create_with_path(path)](#create_with_path_path_43) | Initializes a new [Region](/imaging/python-net/aspose.imaging/region/) with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [deep_clone()](#deep_clone__44) | Creates an exact deep copy of this [Region](/imaging/python-net/aspose.imaging/region/). |
| make_infinite() | Initializes this [Region](/imaging/python-net/aspose.imaging/region/) object to an infinite interior. |
| make_empty() | Initializes this [Region](/imaging/python-net/aspose.imaging/region/) to an empty interior. |
| [intersect_rect_f(rect)](#intersect_rect_f_rect_45) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [intersect_rect(rect)](#intersect_rect_rect_46) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [intersect_path(path)](#intersect_path_path_47) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [intersect_rgn(region)](#intersect_rgn_region_48) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [Region](/imaging/python-net/aspose.imaging/region/). |
| [union_rect_f(rect)](#union_rect_f_rect_49) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [union_rect(rect)](#union_rect_rect_50) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [union_path(path)](#union_path_path_51) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [union_rgn(region)](#union_rgn_region_52) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [Region](/imaging/python-net/aspose.imaging/region/). |
| [xor_rect_f(rect)](#xor_rect_f_rect_53) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [xor_rect(rect)](#xor_rect_rect_54) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [xor_path(path)](#xor_path_path_55) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [xor_rgn(region)](#xor_rgn_region_56) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [Region](/imaging/python-net/aspose.imaging/region/). |
| [exclude_rect_f(rect)](#exclude_rect_f_rect_57) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [exclude_rect(rect)](#exclude_rect_rect_58) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [exclude_path(path)](#exclude_path_path_59) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [exclude_rgn(region)](#exclude_rgn_region_60) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement_rect_f(rect)](#complement_rect_f_rect_61) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement_rect(rect)](#complement_rect_rect_62) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement_path(path)](#complement_path_path_63) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement_rgn(region)](#complement_rgn_region_64) | Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [Region](/imaging/python-net/aspose.imaging/region/) that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |
| [translate_f(dx, dy)](#translate_f_dx_dy_65) | Offsets the coordinates of this [Region](/imaging/python-net/aspose.imaging/region/) by the specified amount. |
| [transform(matrix)](#transform_matrix_66) | Transforms this [Region](/imaging/python-net/aspose.imaging/region/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [is_empty(g)](#is_empty_g_67) | Tests whether this [Region](/imaging/python-net/aspose.imaging/region/) has an empty interior on the specified drawing surface. |
| [is_infinite(g)](#is_infinite_g_68) | Tests whether this [Region](/imaging/python-net/aspose.imaging/region/) has an infinite interior on the specified drawing surface. |
| [is_visible_f(x, y)](#is_visible_f_x_y_69) | Tests whether the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_point_f(point)](#is_visible_point_f_point_70) | Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_with_graphics_f(x, y, g)](#is_visible_with_graphics_f_x_y_g_71) | Tests whether the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_point_f_with_graphics(point, g)](#is_visible_point_f_with_graphics_point_g_72) | Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_xywhf(x, y, width, height)](#is_visible_xywhf_x_y_width_height_73) | Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_rect_f(rect)](#is_visible_rect_f_rect_74) | Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_xywh_graphics_f(x, y, width, height, g)](#is_visible_xywh_graphics_f_x_y_width_height_g_75) | Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_rect_f_with_graphics(rect, g)](#is_visible_rect_f_with_graphics_rect_g_76) | Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_with_graphics(x, y, g)](#is_visible_with_graphics_x_y_g_77) | Tests whether the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_point(point)](#is_visible_point_point_78) | Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_point_with_graphics(point, g)](#is_visible_point_with_graphics_point_g_79) | Tests whether the specified [Point](/imaging/python-net/aspose.imaging/point/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_xywh(x, y, width, height)](#is_visible_xywh_x_y_width_height_80) | Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_rect(rect)](#is_visible_rect_rect_81) | Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_xywh_graphics(x, y, width, height, g)](#is_visible_xywh_graphics_x_y_width_height_g_82) | Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_rect_with_graphics(rect, g)](#is_visible_rect_with_graphics_rect_g_83) | Tests whether any portion of the specified [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/). |

### Region() {#Region__0}


```
 Region() 
```

Initializes a new [Region](/imaging/python-net/aspose.imaging/region/).

### Region(rect) {#Region_rect_1}


```
 Region(rect) 
```

Initializes a new instance of the Region class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) |  |

### Region(rect) {#Region_rect_2}


```
 Region(rect) 
```

Initializes a new instance of the Region class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) |  |

### Region(path) {#Region_path_3}


```
 Region(path) 
```

Initializes a new instance of the Region class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath) |  |

### intersect(rect) {#intersect_rect_4}


```
 intersect(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |

### intersect(rect) {#intersect_rect_5}


```
 intersect(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |

### intersect(path) {#intersect_path_6}


```
 intersect(path) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath) | The [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |

### intersect(region) {#intersect_region_7}


```
 intersect(region) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region) | The [Region](/imaging/python-net/aspose.imaging/region/) to intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |

### union(rect) {#union_rect_8}


```
 union(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to unite with this [Region](/imaging/python-net/aspose.imaging/region/). |

### union(rect) {#union_rect_9}


```
 union(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to unite with this [Region](/imaging/python-net/aspose.imaging/region/). |

### union(path) {#union_path_10}


```
 union(path) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath) | The [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to unite with this [Region](/imaging/python-net/aspose.imaging/region/). |

### union(region) {#union_region_11}


```
 union(region) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region) | The [Region](/imaging/python-net/aspose.imaging/region/) to unite with this [Region](/imaging/python-net/aspose.imaging/region/). |

### xor(rect) {#xor_rect_12}


```
 xor(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to xor with this [Region](/imaging/python-net/aspose.imaging/region/). |

### xor(rect) {#xor_rect_13}


```
 xor(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to xor with this [Region](/imaging/python-net/aspose.imaging/region/). |

### xor(path) {#xor_path_14}


```
 xor(path) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath) | The [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to xor with this [Region](/imaging/python-net/aspose.imaging/region/). |

### xor(region) {#xor_region_15}


```
 xor(region) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region) | The [Region](/imaging/python-net/aspose.imaging/region/) to xor with this [Region](/imaging/python-net/aspose.imaging/region/). |

### exclude(rect) {#exclude_rect_16}


```
 exclude(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to exclude from this [Region](/imaging/python-net/aspose.imaging/region/). |

### exclude(rect) {#exclude_rect_17}


```
 exclude(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to exclude from this [Region](/imaging/python-net/aspose.imaging/region/). |

### exclude(path) {#exclude_path_18}


```
 exclude(path) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath) | The [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to exclude from this [Region](/imaging/python-net/aspose.imaging/region/). |

### exclude(region) {#exclude_region_19}


```
 exclude(region) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region) | The [Region](/imaging/python-net/aspose.imaging/region/) to exclude from this [Region](/imaging/python-net/aspose.imaging/region/). |

### complement(rect) {#complement_rect_20}


```
 complement(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to complement this [Region](/imaging/python-net/aspose.imaging/region/). |

### complement(rect) {#complement_rect_21}


```
 complement(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to complement this [Region](/imaging/python-net/aspose.imaging/region/). |

### complement(path) {#complement_path_22}


```
 complement(path) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath) | The [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to complement this [Region](/imaging/python-net/aspose.imaging/region/). |

### complement(region) {#complement_region_23}


```
 complement(region) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [Region](/imaging/python-net/aspose.imaging/region/) that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region) | The [Region](/imaging/python-net/aspose.imaging/region/) object to complement this [Region](/imaging/python-net/aspose.imaging/region/) object. |

### translate(dx, dy) {#translate_dx_dy_24}


```
 translate(dx, dy) 
```

Offsets the coordinates of this [Region](/imaging/python-net/aspose.imaging/region/) by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | float | The amount to offset this [Region](/imaging/python-net/aspose.imaging/region/) horizontally. |
| dy | float | The amount to offset this [Region](/imaging/python-net/aspose.imaging/region/) vertically. |

### translate(dx, dy) {#translate_dx_dy_25}


```
 translate(dx, dy) 
```

Offsets the coordinates of this [Region](/imaging/python-net/aspose.imaging/region/) by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | int | The amount to offset this [Region](/imaging/python-net/aspose.imaging/region/) horizontally. |
| dy | int | The amount to offset this [Region](/imaging/python-net/aspose.imaging/region/) vertically. |

### is_visible(x, y) {#is_visible_x_y_26}


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


### is_visible(point) {#is_visible_point_27}


```
 is_visible(point) 
```

Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) structure to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when <paramref name="point" /> is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### is_visible(x, y, g) {#is_visible_x_y_g_28}


```
 is_visible(x, y, g) 
```

Tests whether the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | True when the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### is_visible(point, g) {#is_visible_point_g_29}


```
 is_visible(point, g) 
```

Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) structure to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when <paramref name="point" /> is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### is_visible(x, y, width, height) {#is_visible_x_y_width_height_30}


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


### is_visible(rect) {#is_visible_rect_31}


```
 is_visible(rect) 
```

Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of <paramref name="rect" /> is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_32}


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
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### is_visible(rect, g) {#is_visible_rect_g_33}


```
 is_visible(rect, g) 
```

Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when <paramref name="rect" /> is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### is_visible(x, y, g) {#is_visible_x_y_g_34}


```
 is_visible(x, y, g) 
```

Tests whether the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | True when the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### is_visible(point) {#is_visible_point_35}


```
 is_visible(point) 
```

Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) structure to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when <paramref name="point" /> is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### is_visible(point, g) {#is_visible_point_g_36}


```
 is_visible(point, g) 
```

Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) structure to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when <paramref name="point" /> is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### is_visible(x, y, width, height) {#is_visible_x_y_width_height_37}


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


### is_visible(rect) {#is_visible_rect_38}


```
 is_visible(rect) 
```

Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of <paramref name="rect" /> is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_39}


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
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### is_visible(rect, g) {#is_visible_rect_g_40}


```
 is_visible(rect, g) 
```

Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when <paramref name="rect" /> is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### create_with_rect_f(rect)  [static] {#create_with_rect_f_rect_41}


```
 create_with_rect_f(rect) 
```

Initializes a new [Region](/imaging/python-net/aspose.imaging/region/) from the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | A [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that defines the interior of the new [Region](/imaging/python-net/aspose.imaging/region/). |

**Returns**

| Type | Description |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region) |  |


### create_with_rect(rect)  [static] {#create_with_rect_rect_42}


```
 create_with_rect(rect) 
```

Initializes a new [Region](/imaging/python-net/aspose.imaging/region/) from the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | A [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that defines the interior of the new [Region](/imaging/python-net/aspose.imaging/region/). |

**Returns**

| Type | Description |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region) |  |


### create_with_path(path)  [static] {#create_with_path_path_43}


```
 create_with_path(path) 
```

Initializes a new [Region](/imaging/python-net/aspose.imaging/region/) with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath) | A [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) that defines the new [Region](/imaging/python-net/aspose.imaging/region/). |

**Returns**

| Type | Description |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region) |  |


### deep_clone() {#deep_clone__44}


```
 deep_clone() 
```

Creates an exact deep copy of this [Region](/imaging/python-net/aspose.imaging/region/).

**Returns**

| Type | Description |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region) | The [Region](/imaging/python-net/aspose.imaging/region/) that this method creates. |


### intersect_rect_f(rect) {#intersect_rect_f_rect_45}


```
 intersect_rect_f(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |

### intersect_rect(rect) {#intersect_rect_rect_46}


```
 intersect_rect(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |

### intersect_path(path) {#intersect_path_path_47}


```
 intersect_path(path) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath) | The [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |

### intersect_rgn(region) {#intersect_rgn_region_48}


```
 intersect_rgn(region) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the intersection of itself with the specified [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region) | The [Region](/imaging/python-net/aspose.imaging/region/) to intersect with this [Region](/imaging/python-net/aspose.imaging/region/). |

### union_rect_f(rect) {#union_rect_f_rect_49}


```
 union_rect_f(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to unite with this [Region](/imaging/python-net/aspose.imaging/region/). |

### union_rect(rect) {#union_rect_rect_50}


```
 union_rect(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to unite with this [Region](/imaging/python-net/aspose.imaging/region/). |

### union_path(path) {#union_path_path_51}


```
 union_path(path) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath) | The [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to unite with this [Region](/imaging/python-net/aspose.imaging/region/). |

### union_rgn(region) {#union_rgn_region_52}


```
 union_rgn(region) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union of itself and the specified [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region) | The [Region](/imaging/python-net/aspose.imaging/region/) to unite with this [Region](/imaging/python-net/aspose.imaging/region/). |

### xor_rect_f(rect) {#xor_rect_f_rect_53}


```
 xor_rect_f(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to xor with this [Region](/imaging/python-net/aspose.imaging/region/). |

### xor_rect(rect) {#xor_rect_rect_54}


```
 xor_rect(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to xor with this [Region](/imaging/python-net/aspose.imaging/region/). |

### xor_path(path) {#xor_path_path_55}


```
 xor_path(path) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath) | The [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to xor with this [Region](/imaging/python-net/aspose.imaging/region/). |

### xor_rgn(region) {#xor_rgn_region_56}


```
 xor_rgn(region) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to the union minus the intersection of itself with the specified [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region) | The [Region](/imaging/python-net/aspose.imaging/region/) to xor with this [Region](/imaging/python-net/aspose.imaging/region/). |

### exclude_rect_f(rect) {#exclude_rect_f_rect_57}


```
 exclude_rect_f(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to exclude from this [Region](/imaging/python-net/aspose.imaging/region/). |

### exclude_rect(rect) {#exclude_rect_rect_58}


```
 exclude_rect(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to exclude from this [Region](/imaging/python-net/aspose.imaging/region/). |

### exclude_path(path) {#exclude_path_path_59}


```
 exclude_path(path) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath) | The [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to exclude from this [Region](/imaging/python-net/aspose.imaging/region/). |

### exclude_rgn(region) {#exclude_rgn_region_60}


```
 exclude_rgn(region) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region) | The [Region](/imaging/python-net/aspose.imaging/region/) to exclude from this [Region](/imaging/python-net/aspose.imaging/region/). |

### complement_rect_f(rect) {#complement_rect_f_rect_61}


```
 complement_rect_f(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to complement this [Region](/imaging/python-net/aspose.imaging/region/). |

### complement_rect(rect) {#complement_rect_rect_62}


```
 complement_rect(rect) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to complement this [Region](/imaging/python-net/aspose.imaging/region/). |

### complement_path(path) {#complement_path_path_63}


```
 complement_path(path) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath) | The [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to complement this [Region](/imaging/python-net/aspose.imaging/region/). |

### complement_rgn(region) {#complement_rgn_region_64}


```
 complement_rgn(region) 
```

Updates this [Region](/imaging/python-net/aspose.imaging/region/) to contain the portion of the specified [Region](/imaging/python-net/aspose.imaging/region/) that does not intersect with this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region) | The [Region](/imaging/python-net/aspose.imaging/region/) object to complement this [Region](/imaging/python-net/aspose.imaging/region/) object. |

### translate_f(dx, dy) {#translate_f_dx_dy_65}


```
 translate_f(dx, dy) 
```

Offsets the coordinates of this [Region](/imaging/python-net/aspose.imaging/region/) by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | float | The amount to offset this [Region](/imaging/python-net/aspose.imaging/region/) horizontally. |
| dy | float | The amount to offset this [Region](/imaging/python-net/aspose.imaging/region/) vertically. |

### transform(matrix) {#transform_matrix_66}


```
 transform(matrix) 
```

Transforms this [Region](/imaging/python-net/aspose.imaging/region/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix) | The [Matrix](/imaging/python-net/aspose.imaging/matrix/) by which to transform this [Region](/imaging/python-net/aspose.imaging/region/). |

### is_empty(g) {#is_empty_g_67}


```
 is_empty(g) 
```

Tests whether this [Region](/imaging/python-net/aspose.imaging/region/) has an empty interior on the specified drawing surface.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a drawing surface. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true if the interior of this [Region](/imaging/python-net/aspose.imaging/region/) is empty when the transformation associated with <paramref name="g" /> is applied; otherwise, false. |


### is_infinite(g) {#is_infinite_g_68}


```
 is_infinite(g) 
```

Tests whether this [Region](/imaging/python-net/aspose.imaging/region/) has an infinite interior on the specified drawing surface.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a drawing surface. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true if the interior of this [Region](/imaging/python-net/aspose.imaging/region/) is infinite when the transformation associated with <paramref name="g" /> is applied; otherwise, false. |


### is_visible_f(x, y) {#is_visible_f_x_y_69}


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


### is_visible_point_f(point) {#is_visible_point_f_point_70}


```
 is_visible_point_f(point) 
```

Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) structure to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when <paramref name="point" /> is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### is_visible_with_graphics_f(x, y, g) {#is_visible_with_graphics_f_x_y_g_71}


```
 is_visible_with_graphics_f(x, y, g) 
```

Tests whether the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | True when the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### is_visible_point_f_with_graphics(point, g) {#is_visible_point_f_with_graphics_point_g_72}


```
 is_visible_point_f_with_graphics(point, g) 
```

Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) structure to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when <paramref name="point" /> is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### is_visible_xywhf(x, y, width, height) {#is_visible_xywhf_x_y_width_height_73}


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


### is_visible_rect_f(rect) {#is_visible_rect_f_rect_74}


```
 is_visible_rect_f(rect) 
```

Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of <paramref name="rect" /> is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### is_visible_xywh_graphics_f(x, y, width, height, g) {#is_visible_xywh_graphics_f_x_y_width_height_g_75}


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
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### is_visible_rect_f_with_graphics(rect, g) {#is_visible_rect_f_with_graphics_rect_g_76}


```
 is_visible_rect_f_with_graphics(rect, g) 
```

Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when <paramref name="rect" /> is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### is_visible_with_graphics(x, y, g) {#is_visible_with_graphics_x_y_g_77}


```
 is_visible_with_graphics(x, y, g) 
```

Tests whether the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | True when the specified point is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### is_visible_point(point) {#is_visible_point_point_78}


```
 is_visible_point(point) 
```

Tests whether the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) structure to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when <paramref name="point" /> is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### is_visible_point_with_graphics(point, g) {#is_visible_point_with_graphics_point_g_79}


```
 is_visible_point_with_graphics(point, g) 
```

Tests whether the specified [Point](/imaging/python-net/aspose.imaging/point/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point) | The [Point](/imaging/python-net/aspose.imaging/point/) structure to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when <paramref name="point" /> is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### is_visible_xywh(x, y, width, height) {#is_visible_xywh_x_y_width_height_80}


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


### is_visible_rect(rect) {#is_visible_rect_rect_81}


```
 is_visible_rect(rect) 
```

Tests whether any portion of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of <paramref name="rect" /> is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### is_visible_xywh_graphics(x, y, width, height, g) {#is_visible_xywh_graphics_x_y_width_height_g_82}


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
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of the specified rectangle is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


### is_visible_rect_with_graphics(rect, g) {#is_visible_rect_with_graphics_rect_g_83}


```
 is_visible_rect_with_graphics(rect, g) 
```

Tests whether any portion of the specified [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure is contained within this [Region](/imaging/python-net/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure to test. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics) | A [Graphics](/imaging/python-net/aspose.imaging/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of the <paramref name="rect" /> is contained within this [Region](/imaging/python-net/aspose.imaging/region/); otherwise, false. |


