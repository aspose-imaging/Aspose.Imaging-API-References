---
title: "Point 类"
type: docs
weight: 6960
url: /zh/python-net/aspose.imaging/point/
---

**Summary:** Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Point

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [Point()](#Point__1) | 初始化 Point 类的新实例 |
| [Point(dw)](#Point_dw_2) | 使用整数值指定的坐标初始化 [Point](/imaging/python-net/aspose.imaging/point/) 结构的新实例。 |
| [Point(size)](#Point_size_3) | 从 [Size](/imaging/python-net/aspose.imaging/size/) 结构初始化 [Point](/imaging/python-net/aspose.imaging/point/) 结构的新实例。 |
| [Point(x, y)](#Point_x_y_4) | 使用指定的坐标初始化 [Point](/imaging/python-net/aspose.imaging/point/) 结构的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| empty [static] | [Point](/imaging/python-net/aspose.imaging/point/) | r | 获取一个新的 [Point](/imaging/python-net/aspose.imaging/point/) 结构实例，其 [Point.x](/imaging/python-net/aspose.imaging/point/) 和 [Point.y](/imaging/python-net/aspose.imaging/point/) 值均为零。 |
| is_empty | bool | r | 获取一个值，指示此 [Point](/imaging/python-net/aspose.imaging/point/) 是否为空。 |
| x | int | r/w | 获取或设置此 [Point](/imaging/python-net/aspose.imaging/point/) 的 x 坐标。 |
| y | int | r/w | 获取或设置此 [Point](/imaging/python-net/aspose.imaging/point/) 的 y 坐标。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | 将指定的 [Size](/imaging/python-net/aspose.imaging/size/) 添加到指定的 [Point](/imaging/python-net/aspose.imaging/point/)。 |
| [ceiling(point)](#ceiling_point_2) | 通过将指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 的值四舍五入到更高的整数，将其转换为 [Point](/imaging/python-net/aspose.imaging/point/)。 |
| [create_from_d_word(dw)](#create_from_d_word_dw_3) | 使用整数值指定的坐标初始化 [Point](/imaging/python-net/aspose.imaging/point/) 结构的新实例。 |
| [create_from_size(size)](#create_from_size_size_4) | 从 [Size](/imaging/python-net/aspose.imaging/size/) 结构初始化 [Point](/imaging/python-net/aspose.imaging/point/) 结构的新实例。 |
| [from_long(packed_point, x, y)](#from_long_packed_point_x_y_5) | 将打包在 long 对象中的 Point 对象解构为单独的 X 和 Y 整数值。 |
| [offset(dx, dy)](#offset_dx_dy_6) | 按指定的量平移此 [Point](/imaging/python-net/aspose.imaging/point/)。 |
| [offset(point)](#offset_point_7) | 按指定的 [Point](/imaging/python-net/aspose.imaging/point/) 平移此 [Point](/imaging/python-net/aspose.imaging/point/)。 |
| [round(point)](#round_point_8) | 通过将 [Point](/imaging/python-net/aspose.imaging/point/) 的值四舍五入到最近的整数，将指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 转换为 [Point](/imaging/python-net/aspose.imaging/point/) 对象。 |
| [subtract(point, size)](#subtract_point_size_9) | 返回从指定的 [Point](/imaging/python-net/aspose.imaging/point/) 中减去指定的 [Size](/imaging/python-net/aspose.imaging/size/) 的结果。 |
| [to_long()](#to_long__10) | 将此 Point 转换为单个 long 值，其中高位和低位分别包含 X 和 Y 坐标。 |
| [truncate(point)](#truncate_point_11) | 通过截断 [Point](/imaging/python-net/aspose.imaging/point/) 的值，将指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 转换为 [Point](/imaging/python-net/aspose.imaging/point/)。 |


### Constructor: Point() {#Point__1}


```
 Point() 
```

初始化 Point 类的新实例

### Constructor: Point(dw) {#Point_dw_2}


```
 Point(dw) 
```

使用整数值指定的坐标初始化 [Point](/imaging/python-net/aspose.imaging/point/) 结构的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dw | int | 一个 32 位整数，指定新点的坐标。 |

### Constructor: Point(size) {#Point_size_3}


```
 Point(size) 
```

从 [Size](/imaging/python-net/aspose.imaging/size/) 结构初始化 [Point](/imaging/python-net/aspose.imaging/point/) 结构的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | 包含新点坐标。 |

### Constructor: Point(x, y) {#Point_x_y_4}


```
 Point(x, y) 
```

使用指定的坐标初始化 [Point](/imaging/python-net/aspose.imaging/point/) 结构的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 点的水平位置。 |
| y | int | 点的垂直位置。 |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

将指定的 [Size](/imaging/python-net/aspose.imaging/size/) 添加到指定的 [Point](/imaging/python-net/aspose.imaging/point/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | 要添加到的 [Point](/imaging/python-net/aspose.imaging/point/)。 |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | 要添加到 _point_ 的 [Size](/imaging/python-net/aspose.imaging/size/)。 |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | 加法运算结果的 [Point](/imaging/python-net/aspose.imaging/point/)。 |


### Method: ceiling(point)  [static] {#ceiling_point_2}


```
 ceiling(point) 
```

通过将指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 的值四舍五入到更高的整数，将其转换为 [Point](/imaging/python-net/aspose.imaging/point/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 用于转换的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | 此方法转换为的 [Point](/imaging/python-net/aspose.imaging/point/)。 |


### Method: create_from_d_word(dw)  [static] {#create_from_d_word_dw_3}


```
 create_from_d_word(dw) 
```

使用整数值指定的坐标初始化 [Point](/imaging/python-net/aspose.imaging/point/) 结构的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dw | int | 一个 32 位整数，指定新点的坐标。 |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) |  |


### Method: create_from_size(size)  [static] {#create_from_size_size_4}


```
 create_from_size(size) 
```

从 [Size](/imaging/python-net/aspose.imaging/size/) 结构初始化 [Point](/imaging/python-net/aspose.imaging/point/) 结构的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | 包含新点坐标。 |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) |  |


### Method: from_long(packed_point, x, y)  [static] {#from_long_packed_point_x_y_5}


```
 from_long(packed_point, x, y) 
```

将打包在 long 对象中的 Point 对象解构为单独的 X 和 Y 整数值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| packed_point | int | 已打包为一个长整数值的 Point 对象。 |
| x | int[] | 从打包的 Point 中提取的 X 值。 |
| y | int[] | 从打包的 Point 中提取的 Y 值。 |

### Method: offset(dx, dy) {#offset_dx_dy_6}


```
 offset(dx, dy) 
```

按指定的量平移此 [Point](/imaging/python-net/aspose.imaging/point/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dx | int | 用于偏移 x 坐标的量。 |
| dy | int | 用于偏移 y 坐标的量。 |

### Method: offset(point) {#offset_point_7}


```
 offset(point) 
```

按指定的 [Point](/imaging/python-net/aspose.imaging/point/) 平移此 [Point](/imaging/python-net/aspose.imaging/point/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | 用于偏移此 [Point](/imaging/python-net/aspose.imaging/point/) 的 [Point](/imaging/python-net/aspose.imaging/point/)。 |

### Method: round(point)  [static] {#round_point_8}


```
 round(point) 
```

通过将 [Point](/imaging/python-net/aspose.imaging/point/) 的值四舍五入到最近的整数，将指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 转换为 [Point](/imaging/python-net/aspose.imaging/point/) 对象。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 用于转换的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | 此方法转换为的 [Point](/imaging/python-net/aspose.imaging/point/)。 |


### Method: subtract(point, size)  [static] {#subtract_point_size_9}


```
 subtract(point, size) 
```

返回从指定的 [Point](/imaging/python-net/aspose.imaging/point/) 中减去指定的 [Size](/imaging/python-net/aspose.imaging/size/) 的结果。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | 要从中减去的 [Point](/imaging/python-net/aspose.imaging/point/)。 |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | 从 _point_ 中减去的 [Size](/imaging/python-net/aspose.imaging/size/)。 |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | 减法运算结果的 [Point](/imaging/python-net/aspose.imaging/point/)。 |


### Method: to_long() {#to_long__10}


```
 to_long() 
```

将此 Point 转换为单个 long 值，其中高位和低位分别包含 X 和 Y 坐标。

**Returns**

| Type | Description |
| :- | :- |
| int | 已打包为一个长整数值的 Point 对象。 |


### Method: truncate(point)  [static] {#truncate_point_11}


```
 truncate(point) 
```

通过截断 [Point](/imaging/python-net/aspose.imaging/point/) 的值，将指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 转换为 [Point](/imaging/python-net/aspose.imaging/point/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 用于转换的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | 此方法转换为的 [Point](/imaging/python-net/aspose.imaging/point/)。 |


