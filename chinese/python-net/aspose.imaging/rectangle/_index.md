---
title: "Rectangle 类"
type: docs
weight: 7120
url: /zh/python-net/aspose.imaging/rectangle/
---

**Summary:** Stores a set of four integers that represent the location and size of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Rectangle

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [Rectangle()](#Rectangle__1) | 初始化 Rectangle 类的新实例 |
| [Rectangle(location, size)](#Rectangle_location_size_2) | 使用指定的位置和大小初始化 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构的新实例。 |
| [Rectangle(x, y, width, height)](#Rectangle_x_y_width_height_3) | 使用指定的位置和大小初始化 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bottom | int | r/w | 获取或设置此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构的 y 坐标，该坐标为 [Rectangle.y](/imaging/python-net/aspose.imaging/rectangle/) 与 [Rectangle.height](/imaging/python-net/aspose.imaging/rectangle/) 属性值之和。 |
| empty [static] | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | 获取一个新的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构实例，其 [Rectangle.x](/imaging/python-net/aspose.imaging/rectangle/)、[Rectangle.y](/imaging/python-net/aspose.imaging/rectangle/)、[Rectangle.width](/imaging/python-net/aspose.imaging/rectangle/) 和 [Rectangle.height](/imaging/python-net/aspose.imaging/rectangle/) 的值均为零。 |
| height | int | r/w | 获取或设置此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构的高度。 |
| is_empty | bool | r | 获取一个值，指示此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 的所有数值属性是否全部为零。 |
| left | int | r/w | 获取或设置此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构左边缘的 x 坐标。 |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | 获取或设置此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构左上角的坐标。 |
| right | int | r/w | 获取或设置此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构的 x 坐标，该坐标为 [Rectangle.x](/imaging/python-net/aspose.imaging/rectangle/) 与 [Rectangle.width](/imaging/python-net/aspose.imaging/rectangle/) 属性值之和。 |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | 获取或设置此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 的大小。 |
| top | int | r/w | 获取或设置此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构顶部边缘的 y 坐标。 |
| width | int | r/w | 获取或设置此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构的宽度。 |
| x | int | r/w | 获取或设置此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构左上角的 x 坐标。 |
| y | int | r/w | 获取或设置此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构左上角的 y 坐标。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [ceiling(value)](#ceiling_value_1) | 将指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构转换为 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构，方法是将 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 的值向上取整为下一个整数。 |
| [contains(point)](#contains_point_2) | 确定指定的点是否位于此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构内部。 |
| [contains(rect)](#contains_rect_3) | 确定由 _rect_ 表示的矩形区域是否完全包含在此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构中。 |
| [contains(x, y)](#contains_x_y_4) | 确定指定的点是否位于此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构内部。 |
| [contains_point(point)](#contains_point_point_5) | 确定指定的点是否位于此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构内部。 |
| [contains_rect(rect)](#contains_rect_rect_6) | 确定由 _rect_ 表示的矩形区域是否完全包含在此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构中。 |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_7) | 使用指定的边缘位置创建一个 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构。 |
| [from_points(point1, point2)](#from_points_point1_point2_8) | 根据指定的两个点创建一个新的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。创建的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 的两个顶点将等于传入的 _point1_ 和 _point2_，通常它们是相对的顶点。 |
| [inflate(rect, x, y)](#inflate_rect_x_y_9) | 创建并返回指定的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构的膨胀副本。该副本按指定的量进行膨胀，原始的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构保持不变。 |
| [inflate(size)](#inflate_size_10) | 按指定的量膨胀此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。 |
| [inflate(width, height)](#inflate_width_height_11) | 按指定的量膨胀此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。 |
| [inflate_rect(rect, x, y)](#inflate_rect_rect_x_y_12) | 创建并返回指定的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构的膨胀副本。该副本按指定的量进行膨胀，原始的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构保持不变。 |
| [intersect(a, b)](#intersect_a_b_13) | 返回一个第三个 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构，表示另外两个 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构的交集。如果没有交集，则返回一个空的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。 |
| [intersect(rect)](#intersect_rect_14) | 用自身与指定的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 的交集替换此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。 |
| [intersect_rects(a, b)](#intersect_rects_a_b_15) | 返回一个第三个 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构，表示另外两个 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构的交集。如果没有交集，则返回一个空的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。 |
| [intersects_with(rect)](#intersects_with_rect_16) | 确定此矩形是否与 _rect_ 相交。 |
| normalize() | 通过使宽度和高度为正、左侧小于右侧、顶部小于底部来规范化矩形。 |
| [offset(pos)](#offset_pos_17) | 按指定量调整此矩形的位置。 |
| [offset(x, y)](#offset_x_y_18) | 按指定量调整此矩形的位置。 |
| [round(value)](#round_value_19) | 将指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 转换为 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)，方法是将 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 的值四舍五入到最近的整数。 |
| [truncate(value)](#truncate_value_20) | 将指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 转换为 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)，方法是截断 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 的值。 |
| [union(a, b)](#union_a_b_21) | 获取一个包含两个 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构并集的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构。 |


### Constructor: Rectangle() {#Rectangle__1}


```
 Rectangle() 
```

初始化 Rectangle 类的新实例

### Constructor: Rectangle(location, size) {#Rectangle_location_size_2}


```
 Rectangle(location, size) 
```

使用指定的位置和大小初始化 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | 表示矩形区域左上角的 [Point](/imaging/python-net/aspose.imaging/point/)。 |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | 表示矩形区域宽度和高度的 [Size](/imaging/python-net/aspose.imaging/size/)。 |

### Constructor: Rectangle(x, y, width, height) {#Rectangle_x_y_width_height_3}


```
 Rectangle(x, y, width, height) 
```

使用指定的位置和大小初始化 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 矩形左上角的 x 坐标。 |
| y | int | 矩形左上角的 y 坐标。 |
| width | int | 矩形的宽度。 |
| height | int | 矩形的高度。 |

### Method: ceiling(value)  [static] {#ceiling_value_1}


```
 ceiling(value) 
```

将指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构转换为 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构，方法是将 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 的值向上取整为下一个整数。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 待转换的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 返回一个 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。 |


### Method: contains(point) {#contains_point_2}


```
 contains(point) 
```

确定指定的点是否位于此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | 待测试的 [Point](/imaging/python-net/aspose.imaging/point/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果由 _point_ 表示的点位于此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构内部，则此方法返回 true；否则返回 false。 |


### Method: contains(rect) {#contains_rect_3}


```
 contains(rect) 
```

确定由 _rect_ 表示的矩形区域是否完全包含在此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 要测试的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果由 _rect_ 表示的矩形区域完全位于此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构内部，则此方法返回 true；否则返回 false。 |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

确定指定的点是否位于此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 要测试的点的 x 坐标。 |
| y | int | 要测试的点的 y 坐标。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果由 _x_ 和 _y_ 定义的点位于此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构内部，则此方法返回 true；否则返回 false。 |


### Method: contains_point(point) {#contains_point_point_5}


```
 contains_point(point) 
```

确定指定的点是否位于此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | 待测试的 [Point](/imaging/python-net/aspose.imaging/point/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果由 _point_ 表示的点位于此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构内部，则此方法返回 true；否则返回 false。 |


### Method: contains_rect(rect) {#contains_rect_rect_6}


```
 contains_rect(rect) 
```

确定由 _rect_ 表示的矩形区域是否完全包含在此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 要测试的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果由 _rect_ 表示的矩形区域完全位于此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构内部，则此方法返回 true；否则返回 false。 |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_7}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

使用指定的边缘位置创建一个 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| left | int | 此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构左上角的 x 坐标。 |
| top | int | 此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构左上角的 y 坐标。 |
| right | int | 此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构右下角的 x 坐标。 |
| bottom | int | 此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构右下角的 y 坐标。 |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 此方法创建的新 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。 |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_8}


```
 from_points(point1, point2) 
```

根据指定的两个点创建一个新的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。创建的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 的两个顶点将等于传入的 _point1_ 和 _point2_，通常它们是相对的顶点。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | 新矩形的第一个 [Point](/imaging/python-net/aspose.imaging/point/)。 |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | 新矩形的第二个 [Point](/imaging/python-net/aspose.imaging/point/)。 |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 新创建的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。 |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_9}


```
 inflate(rect, x, y) 
```

创建并返回指定的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构的膨胀副本。该副本按指定的量进行膨胀，原始的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构保持不变。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 用于开始的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。此矩形不会被修改。 |
| x | int | 水平膨胀此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 的量。 |
| y | int | 垂直膨胀此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 的量。 |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 膨胀后的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。 |


### Method: inflate(size) {#inflate_size_10}


```
 inflate(size) 
```

按指定的量膨胀此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | 膨胀此矩形的量。 |

### Method: inflate(width, height) {#inflate_width_height_11}


```
 inflate(width, height) 
```

按指定的量膨胀此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| width | int | 水平膨胀此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 的量。 |
| height | int | 垂直膨胀此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 的量。 |

### Method: inflate_rect(rect, x, y)  [static] {#inflate_rect_rect_x_y_12}


```
 inflate_rect(rect, x, y) 
```

创建并返回指定的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构的膨胀副本。该副本按指定的量进行膨胀，原始的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构保持不变。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 用于开始的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。此矩形不会被修改。 |
| x | int | 水平膨胀此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 的量。 |
| y | int | 垂直膨胀此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 的量。 |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 膨胀后的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。 |


### Method: intersect(a, b)  [static] {#intersect_a_b_13}


```
 intersect(a, b) 
```

返回一个第三个 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构，表示另外两个 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构的交集。如果没有交集，则返回一个空的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 第一个要相交的矩形。 |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 第二个要相交的矩形。 |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 表示 _a_ 与 _b_ 交集的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。 |


### Method: intersect(rect) {#intersect_rect_14}


```
 intersect(rect) 
```

用自身与指定的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 的交集替换此 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 用于求交的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。 |

### Method: intersect_rects(a, b)  [static] {#intersect_rects_a_b_15}


```
 intersect_rects(a, b) 
```

返回一个第三个 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构，表示另外两个 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构的交集。如果没有交集，则返回一个空的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 第一个要相交的矩形。 |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 第二个要相交的矩形。 |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 表示 _a_ 与 _b_ 交集的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。 |


### Method: intersects_with(rect) {#intersects_with_rect_16}


```
 intersects_with(rect) 
```

确定此矩形是否与 _rect_ 相交。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 要测试的矩形。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果存在任何交集，则此方法返回 true；否则返回 false。 |


### Method: offset(pos) {#offset_pos_17}


```
 offset(pos) 
```

按指定量调整此矩形的位置。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pos | [Point](/imaging/python-net/aspose.imaging/point/) | 位置的偏移量。 |

### Method: offset(x, y) {#offset_x_y_18}


```
 offset(x, y) 
```

按指定量调整此矩形的位置。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 水平偏移量。 |
| y | int | 垂直偏移量。 |

### Method: round(value)  [static] {#round_value_19}


```
 round(value) 
```

将指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 转换为 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)，方法是将 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 的值四舍五入到最近的整数。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 要转换的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)。 |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 一个新的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。 |


### Method: truncate(value)  [static] {#truncate_value_20}


```
 truncate(value) 
```

将指定的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 转换为 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)，方法是截断 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 的值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 要转换的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)。 |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 一个新的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。 |


### Method: union(a, b)  [static] {#union_a_b_21}


```
 union(a, b) 
```

获取一个包含两个 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构并集的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 第一个用于合并的矩形。 |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 第二个用于合并的矩形。 |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 一个 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构，界定两个 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构的并集。 |


