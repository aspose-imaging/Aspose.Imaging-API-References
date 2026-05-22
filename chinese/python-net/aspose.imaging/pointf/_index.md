---
title: "PointF 类"
type: docs
weight: 6980
url: /zh/python-net/aspose.imaging/pointf/
---

**Summary:** Represents an ordered pair of floating-point x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.PointF

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [PointF()](#PointF__1) | 初始化 PointF 类的新实例 |
| [PointF(x, y)](#PointF_x_y_2) | 使用指定的坐标初始化 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| empty [static] | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | 获取一个新的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构实例，其 [PointF.x](/imaging/python-net/aspose.imaging/pointf/) 和 [PointF.y](/imaging/python-net/aspose.imaging/pointf/) 的值均为零。 |
| is_empty | bool | r | 获取一个值，指示此 [PointF](/imaging/python-net/aspose.imaging/pointf/) 是否为空。 |
| x | float | r/w | 获取或设置此 [PointF](/imaging/python-net/aspose.imaging/pointf/) 的 x 坐标。 |
| y | float | r/w | 获取或设置此 [PointF](/imaging/python-net/aspose.imaging/pointf/) 的 y 坐标。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | 按指定的 [Size](/imaging/python-net/aspose.imaging/size/) 平移给定的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |
| [add(point, size)](#add_point_size_2) | 按指定的 [Size](/imaging/python-net/aspose.imaging/size/) 平移给定的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |
| [add_size(point, size)](#add_size_point_size_3) | 按指定的 [Size](/imaging/python-net/aspose.imaging/size/) 平移给定的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |
| [add_size_f(point, size)](#add_size_f_point_size_4) | 按指定的 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 平移给定的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |
| [subtract(point, size)](#subtract_point_size_5) | 按指定尺寸的相反方向平移 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |
| [subtract(point, size)](#subtract_point_size_6) | 按指定尺寸的相反方向平移 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |
| [subtract_size(point, size)](#subtract_size_point_size_7) | 按指定尺寸的相反方向平移 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |
| [subtract_size_f(point, size)](#subtract_size_f_point_size_8) | 按指定尺寸的相反方向平移 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |


### Constructor: PointF() {#PointF__1}


```
 PointF() 
```

初始化 PointF 类的新实例

### Constructor: PointF(x, y) {#PointF_x_y_2}


```
 PointF(x, y) 
```

使用指定的坐标初始化 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | float | 点的水平位置。 |
| y | float | 点的垂直位置。 |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

按指定的 [Size](/imaging/python-net/aspose.imaging/size/) 平移给定的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 要平移的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | 指定要加到 _point_ 坐标的数值的 [Size](/imaging/python-net/aspose.imaging/size/)。 |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | 平移后的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |


### Method: add(point, size)  [static] {#add_point_size_2}


```
 add(point, size) 
```

按指定的 [Size](/imaging/python-net/aspose.imaging/size/) 平移给定的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 要平移的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | 指定要加到 _point_ 坐标的数值的 [Size](/imaging/python-net/aspose.imaging/size/)。 |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | 平移后的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |


### Method: add_size(point, size)  [static] {#add_size_point_size_3}


```
 add_size(point, size) 
```

按指定的 [Size](/imaging/python-net/aspose.imaging/size/) 平移给定的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 要平移的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | 指定要加到 _point_ 坐标的数值的 [Size](/imaging/python-net/aspose.imaging/size/)。 |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | 平移后的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |


### Method: add_size_f(point, size)  [static] {#add_size_f_point_size_4}


```
 add_size_f(point, size) 
```

按指定的 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 平移给定的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 要平移的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | 指定要加到 _point_ 坐标的数值的 [SizeF](/imaging/python-net/aspose.imaging/sizef/)。 |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | 平移后的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |


### Method: subtract(point, size)  [static] {#subtract_point_size_5}


```
 subtract(point, size) 
```

按指定尺寸的相反方向平移 [PointF](/imaging/python-net/aspose.imaging/pointf/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 要平移的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | 指定要从 _point_ 坐标中减去的数值的 [Size](/imaging/python-net/aspose.imaging/size/)。 |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | 平移后的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |


### Method: subtract(point, size)  [static] {#subtract_point_size_6}


```
 subtract(point, size) 
```

按指定尺寸的相反方向平移 [PointF](/imaging/python-net/aspose.imaging/pointf/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 要平移的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | 指定要从 _point_ 坐标中减去的数值的 [Size](/imaging/python-net/aspose.imaging/size/)。 |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | 平移后的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |


### Method: subtract_size(point, size)  [static] {#subtract_size_point_size_7}


```
 subtract_size(point, size) 
```

按指定尺寸的相反方向平移 [PointF](/imaging/python-net/aspose.imaging/pointf/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 要平移的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | 指定要从 _point_ 坐标中减去的数值的 [Size](/imaging/python-net/aspose.imaging/size/)。 |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | 平移后的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |


### Method: subtract_size_f(point, size)  [static] {#subtract_size_f_point_size_8}


```
 subtract_size_f(point, size) 
```

按指定尺寸的相反方向平移 [PointF](/imaging/python-net/aspose.imaging/pointf/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 要平移的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | 指定要从 _point_ 坐标中减去的数值的 [SizeF](/imaging/python-net/aspose.imaging/sizef/)。 |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | 平移后的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |


