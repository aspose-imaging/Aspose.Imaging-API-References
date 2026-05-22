---
title: "RectangleF 类"
type: docs
weight: 7130
url: /zh/python-net/aspose.imaging/rectanglef/
---

**Summary:** Stores a set of four floating-point numbers that represent the location and size of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.RectangleF

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [RectangleF()](#RectangleF__1) | 初始化 RectangleF 类的新实例 |
| [RectangleF(location, size)](#RectangleF_location_size_2) | 使用指定的位置和大小初始化 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的新实例。 |
| [RectangleF(x, y, width, height)](#RectangleF_x_y_width_height_3) | 使用指定的位置和大小初始化 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bottom | float | r/w | 获取或设置此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的 y 坐标，该坐标为 [RectangleF.y](/imaging/python-net/aspose.imaging/rectanglef/) 与 [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) 的和。 |
| empty [static] | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | 获取一个新的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构实例，其 [RectangleF.x](/imaging/python-net/aspose.imaging/rectanglef/)、[RectangleF.y](/imaging/python-net/aspose.imaging/rectanglef/)、[RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) 和 [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) 的值均为零。 |
| height | float | r/w | 获取或设置此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的高度。 |
| is_empty | bool | r | 获取一个值，指示此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 的 [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) 或 [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) 属性是否为零。 |
| left | float | r/w | 获取或设置此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构左边缘的 x 坐标。 |
| location | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | 获取或设置此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构左上角的坐标。 |
| right | float | r/w | 获取或设置此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的 x 坐标，该坐标为 [RectangleF.x](/imaging/python-net/aspose.imaging/rectanglef/) 与 [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) 的和。 |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | 获取或设置此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 的大小。 |
| top | float | r/w | 获取或设置此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构顶部边缘的 y 坐标。 |
| width | float | r/w | 获取或设置此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的宽度。 |
| x | float | r/w | 获取或设置此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构左上角的 x 坐标。 |
| y | float | r/w | 获取或设置此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构左上角的 y 坐标。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [contains(point)](#contains_point_1) | 确定指定的点是否包含在此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构中。 |
| [contains(rect)](#contains_rect_2) | 确定由 _rect_ 表示的矩形区域是否完全包含在此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构中。 |
| [contains(x, y)](#contains_x_y_3) | 确定指定的点是否包含在此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构中。 |
| [contains_point_f(point)](#contains_point_f_point_4) | 确定指定的点是否包含在此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构中。 |
| [contains_rect_f(rect)](#contains_rect_f_rect_5) | 确定由 _rect_ 表示的矩形区域是否完全包含在此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构中。 |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_6) | 创建一个 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构，其左上角和右下角位于指定位置。 |
| [from_points(point1, point2)](#from_points_point1_point2_7) | 从指定的两个点创建一个新的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 。创建的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 的两个顶点将等于传入的 _point1_ 和 _point2_。这些通常是相对的顶点。 |
| [inflate(rect, x, y)](#inflate_rect_x_y_8) | 创建并返回指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的膨胀副本。该副本按指定量进行膨胀。原始矩形保持不变。 |
| [inflate(size)](#inflate_size_9) | 按指定量膨胀此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)。 |
| [inflate(x, y)](#inflate_x_y_10) | 按指定量膨胀此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |
| [inflate_rect(rect, x, y)](#inflate_rect_rect_x_y_11) | 创建并返回指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的膨胀副本。该副本按指定量进行膨胀。原始矩形保持不变。 |
| [intersect(a, b)](#intersect_a_b_12) | 返回一个表示两个矩形交集的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。如果没有交集，则返回一个空的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)。 |
| [intersect(rect)](#intersect_rect_13) | 用自身与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的交集替换此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |
| [intersect_rects(a, b)](#intersect_rects_a_b_14) | 返回一个表示两个矩形交集的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。如果没有交集，则返回一个空的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)。 |
| [intersects_with(rect)](#intersects_with_rect_15) | 确定此矩形是否与 _rect_ 相交。 |
| normalize() | 通过使宽度和高度为正、左侧小于右侧、顶部小于底部来规范化矩形。 |
| [offset(pos)](#offset_pos_16) | 按指定量调整此矩形的位置。 |
| [offset(x, y)](#offset_x_y_17) | 按指定量调整此矩形的位置。 |
| [union(a, b)](#union_a_b_18) | 创建能够包含两个矩形（形成并集）的最小可能的第三个矩形。 |


### Constructor: RectangleF() {#RectangleF__1}


```
 RectangleF() 
```

初始化 RectangleF 类的新实例

### Constructor: RectangleF(location, size) {#RectangleF_location_size_2}


```
 RectangleF(location, size) 
```

使用指定的位置和大小初始化 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| location | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 一个表示矩形区域左上角的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | 一个表示矩形区域宽度和高度的 [SizeF](/imaging/python-net/aspose.imaging/sizef/)。 |

### Constructor: RectangleF(x, y, width, height) {#RectangleF_x_y_width_height_3}


```
 RectangleF(x, y, width, height) 
```

使用指定的位置和大小初始化 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | float | 矩形左上角的 x 坐标。 |
| y | float | 矩形左上角的 y 坐标。 |
| width | float | 矩形的宽度。 |
| height | float | 矩形的高度。 |

### Method: contains(point) {#contains_point_1}


```
 contains(point) 
```

确定指定的点是否包含在此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 要测试的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果 _point_ 参数表示的点包含在此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构中，则此方法返回 true；否则返回 false。 |


### Method: contains(rect) {#contains_rect_2}


```
 contains(rect) 
```

确定由 _rect_ 表示的矩形区域是否完全包含在此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 要测试的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果由 _rect_ 表示的矩形区域完全包含在由此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 表示的矩形区域中，则此方法返回 true；否则返回 false。 |


### Method: contains(x, y) {#contains_x_y_3}


```
 contains(x, y) 
```

确定指定的点是否包含在此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | float | 要测试的点的 x 坐标。 |
| y | float | 要测试的点的 y 坐标。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果由 _x_ 和 _y_ 定义的点包含在此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构中，则此方法返回 true；否则返回 false。 |


### Method: contains_point_f(point) {#contains_point_f_point_4}


```
 contains_point_f(point) 
```

确定指定的点是否包含在此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 要测试的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果 _point_ 参数表示的点包含在此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构中，则此方法返回 true；否则返回 false。 |


### Method: contains_rect_f(rect) {#contains_rect_f_rect_5}


```
 contains_rect_f(rect) 
```

确定由 _rect_ 表示的矩形区域是否完全包含在此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 要测试的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果由 _rect_ 表示的矩形区域完全包含在由此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 表示的矩形区域中，则此方法返回 true；否则返回 false。 |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_6}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

创建一个 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构，其左上角和右下角位于指定位置。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 左 | float | 矩形区域左上角的 x 坐标。 |
| 上 | float | 矩形区域左上角的 y 坐标。 |
| 右 | float | 矩形区域右下角的 x 坐标。 |
| 下 | float | 矩形区域右下角的 y 坐标。 |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 此方法创建的新的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)。 |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_7}


```
 from_points(point1, point2) 
```

从指定的两个点创建一个新的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 。创建的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 的两个顶点将等于传入的 _point1_ 和 _point2_。这些通常是相对的顶点。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 新矩形的第一个 [Point](/imaging/python-net/aspose.imaging/point/)。 |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 新矩形的第二个 [Point](/imaging/python-net/aspose.imaging/point/)。 |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 新创建的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。 |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_8}


```
 inflate(rect, x, y) 
```

创建并返回指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的膨胀副本。该副本按指定量进行膨胀。原始矩形保持不变。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 要复制的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)。此矩形不会被修改。 |
| x | float | 水平膨胀矩形副本的量。 |
| y | float | 垂直膨胀矩形副本的量。 |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 膨胀后的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)。 |


### Method: inflate(size) {#inflate_size_9}


```
 inflate(size) 
```

按指定量膨胀此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | 膨胀此矩形的量。 |

### Method: inflate(x, y) {#inflate_x_y_10}


```
 inflate(x, y) 
```

按指定量膨胀此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | float | 水平膨胀此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的量。 |
| y | float | 垂直膨胀此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的量。 |

### Method: inflate_rect(rect, x, y)  [static] {#inflate_rect_rect_x_y_11}


```
 inflate_rect(rect, x, y) 
```

创建并返回指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的膨胀副本。该副本按指定量进行膨胀。原始矩形保持不变。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 要复制的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)。此矩形不会被修改。 |
| x | float | 水平膨胀矩形副本的量。 |
| y | float | 垂直膨胀矩形副本的量。 |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 膨胀后的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)。 |


### Method: intersect(a, b)  [static] {#intersect_a_b_12}


```
 intersect(a, b) 
```

返回一个表示两个矩形交集的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。如果没有交集，则返回一个空的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 第一个要相交的矩形。 |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 第二个要相交的矩形。 |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 第三个 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构，其大小表示两个指定矩形的重叠区域。 |


### Method: intersect(rect) {#intersect_rect_13}


```
 intersect(rect) 
```

用自身与指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构的交集替换此 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 要相交的矩形。 |

### Method: intersect_rects(a, b)  [static] {#intersect_rects_a_b_14}


```
 intersect_rects(a, b) 
```

返回一个表示两个矩形交集的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。如果没有交集，则返回一个空的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 第一个要相交的矩形。 |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 第二个要相交的矩形。 |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 第三个 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构，其大小表示两个指定矩形的重叠区域。 |


### Method: intersects_with(rect) {#intersects_with_rect_15}


```
 intersects_with(rect) 
```

确定此矩形是否与 _rect_ 相交。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 要测试的矩形。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果存在任何交集，此方法返回 true。 |


### Method: offset(pos) {#offset_pos_16}


```
 offset(pos) 
```

按指定量调整此矩形的位置。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pos | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 位置的偏移量。 |

### Method: offset(x, y) {#offset_x_y_17}


```
 offset(x, y) 
```

按指定量调整此矩形的位置。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | float | 水平偏移位置的量。 |
| y | float | 垂直偏移位置的量。 |

### Method: union(a, b)  [static] {#union_a_b_18}


```
 union(a, b) 
```

创建能够包含两个矩形（形成并集）的最小可能的第三个矩形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 第一个用于合并的矩形。 |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 第二个用于合并的矩形。 |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 第三个 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构，包含形成合并的两个矩形。 |


