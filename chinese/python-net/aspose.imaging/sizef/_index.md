---
title: "SizeF 类"
type: docs
weight: 7290
url: /zh/python-net/aspose.imaging/sizef/
---

**Summary:** Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.SizeF

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [SizeF()](#SizeF__1) | 初始化 SizeF 类的新实例 |
| [SizeF(point)](#SizeF_point_2) | 根据指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 初始化 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构的新实例。 |
| [SizeF(size)](#SizeF_size_3) | 从指定的 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 初始化一个新的 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构实例。 |
| [SizeF(width, height)](#SizeF_width_height_4) | 从指定的尺寸初始化一个新的 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| empty [static] | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r | 获取一个新的 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构实例，其 [SizeF.width](/imaging/python-net/aspose.imaging/sizef/) 和 [SizeF.height](/imaging/python-net/aspose.imaging/sizef/) 值均为零。 |
| height | float | r/w | 获取或设置此 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 的垂直分量。 |
| is_empty | bool | r | 获取一个值，指示此 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 是否具有零宽度和高度。 |
| width | float | r/w | 获取或设置此 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 的水平分量。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | 将一个 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构的宽度和高度添加到另一个 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构的宽度和高度。 |
| [create_from_point_f(point)](#create_from_point_f_point_2) | 根据指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 初始化 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构的新实例。 |
| [create_from_size_f(size)](#create_from_size_f_size_3) | 从指定的 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 初始化一个新的 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构实例。 |
| [subtract(size1, size2)](#subtract_size1_size2_4) | 从另一个 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构的宽度和高度中减去一个 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构的宽度和高度。 |
| [to_point_f()](#to_point_f__5) | 将 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 转换为 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |
| [to_size()](#to_size__6) | 将 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 转换为具有截断尺寸值的 [Size](/imaging/python-net/aspose.imaging/size/) 结构。 |


### Constructor: SizeF() {#SizeF__1}


```
 SizeF() 
```

初始化 SizeF 类的新实例

### Constructor: SizeF(point) {#SizeF_point_2}


```
 SizeF(point) 
```

根据指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 初始化 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 用于初始化此 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |

### Constructor: SizeF(size) {#SizeF_size_3}


```
 SizeF(size) 
```

从指定的 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 初始化一个新的 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | 用于创建新 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 的 [SizeF](/imaging/python-net/aspose.imaging/sizef/)。 |

### Constructor: SizeF(width, height) {#SizeF_width_height_4}


```
 SizeF(width, height) 
```

从指定的尺寸初始化一个新的 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| width | float | 新 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 的宽度分量。 |
| height | float | 新 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 的高度分量。 |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

将一个 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构的宽度和高度添加到另一个 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构的宽度和高度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| size1 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | 要相加的第一个 [SizeF](/imaging/python-net/aspose.imaging/sizef/)。 |
| size2 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | 要相加的第二个 [SizeF](/imaging/python-net/aspose.imaging/sizef/)。 |

**Returns**

| Type | Description |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | 加法运算结果的 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构。 |


### Method: create_from_point_f(point)  [static] {#create_from_point_f_point_2}


```
 create_from_point_f(point) 
```

根据指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 初始化 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 用于初始化此 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 的 [PointF](/imaging/python-net/aspose.imaging/pointf/)。 |

**Returns**

| Type | Description |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) |  |


### Method: create_from_size_f(size)  [static] {#create_from_size_f_size_3}


```
 create_from_size_f(size) 
```

从指定的 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 初始化一个新的 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | 用于创建新 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 的 [SizeF](/imaging/python-net/aspose.imaging/sizef/)。 |

**Returns**

| Type | Description |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) |  |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

从另一个 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构的宽度和高度中减去一个 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构的宽度和高度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| size1 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | 减法运算符左侧的 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构。 |
| size2 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | 减法运算符右侧的 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构。 |

**Returns**

| Type | Description |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | 减法运算结果的 [SizeF](/imaging/python-net/aspose.imaging/sizef/)。 |


### Method: to_point_f() {#to_point_f__5}


```
 to_point_f() 
```

将 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 转换为 [PointF](/imaging/python-net/aspose.imaging/pointf/)。

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | 返回一个 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构。 |


### Method: to_size() {#to_size__6}


```
 to_size() 
```

将 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 转换为具有截断尺寸值的 [Size](/imaging/python-net/aspose.imaging/size/) 结构。

**Returns**

| Type | Description |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | 返回一个 [Size](/imaging/python-net/aspose.imaging/size/) 结构。 |


