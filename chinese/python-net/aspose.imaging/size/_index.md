---
title: "Size 类"
type: docs
weight: 7280
url: /zh/python-net/aspose.imaging/size/
---

**Summary:** Represents size.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Size

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [Size()](#Size__1) | 初始化 Size 类的新实例 |
| [Size(point)](#Size_point_2) | 从指定的 [Point](/imaging/python-net/aspose.imaging/point/) 初始化一个新的 [Size](/imaging/python-net/aspose.imaging/size/) 结构实例。 |
| [Size(width, height)](#Size_width_height_3) | 从指定的尺寸初始化一个新的 [Size](/imaging/python-net/aspose.imaging/size/) 结构实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| empty [static] | [Size](/imaging/python-net/aspose.imaging/size/) | r | 获取一个新的 [Size](/imaging/python-net/aspose.imaging/size/) 结构实例，其 [Size.width](/imaging/python-net/aspose.imaging/size/) 和 [Size.height](/imaging/python-net/aspose.imaging/size/) 值均为零。 |
| height | int | r/w | 获取或设置此 [Size](/imaging/python-net/aspose.imaging/size/) 的垂直分量。 |
| is_empty | bool | r | 获取一个值，指示此 [Size](/imaging/python-net/aspose.imaging/size/) 的宽度和高度是否为 0。 |
| width | int | r/w | 获取或设置此 [Size](/imaging/python-net/aspose.imaging/size/) 的水平分量。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | 将一个 [Size](/imaging/python-net/aspose.imaging/size/) 结构的宽度和高度添加到另一个 [Size](/imaging/python-net/aspose.imaging/size/) 结构的宽度和高度。 |
| [ceiling(size)](#ceiling_size_2) | 通过将指定的 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构的值四舍入到更高的整数，将其转换为 [Size](/imaging/python-net/aspose.imaging/size/) 结构。 |
| [round(size)](#round_size_3) | 通过将指定的 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构的值四舍五入到最近的整数，将其转换为 [Size](/imaging/python-net/aspose.imaging/size/) 结构。 |
| [subtract(size1, size2)](#subtract_size1_size2_4) | 从另一个 [Size](/imaging/python-net/aspose.imaging/size/) 结构的宽度和高度中减去一个 [Size](/imaging/python-net/aspose.imaging/size/) 结构的宽度和高度。 |
| [truncate(size)](#truncate_size_5) | 通过将指定的 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构的值截断为更低的整数，将其转换为 [Size](/imaging/python-net/aspose.imaging/size/) 结构。 |


### Constructor: Size() {#Size__1}


```
 Size() 
```

初始化 Size 类的新实例

### Constructor: Size(point) {#Size_point_2}


```
 Size(point) 
```

从指定的 [Point](/imaging/python-net/aspose.imaging/point/) 初始化一个新的 [Size](/imaging/python-net/aspose.imaging/size/) 结构实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | 用于初始化此 [Size](/imaging/python-net/aspose.imaging/size/) 的 [Point](/imaging/python-net/aspose.imaging/point/)。 |

### Constructor: Size(width, height) {#Size_width_height_3}


```
 Size(width, height) 
```

从指定的尺寸初始化一个新的 [Size](/imaging/python-net/aspose.imaging/size/) 结构实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| width | int | 新 [Size](/imaging/python-net/aspose.imaging/size/) 的宽度分量。 |
| height | int | 新 [Size](/imaging/python-net/aspose.imaging/size/) 的高度分量。 |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

将一个 [Size](/imaging/python-net/aspose.imaging/size/) 结构的宽度和高度添加到另一个 [Size](/imaging/python-net/aspose.imaging/size/) 结构的宽度和高度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| size1 | [Size](/imaging/python-net/aspose.imaging/size/) | 要添加的第一个 [Size](/imaging/python-net/aspose.imaging/size/)。 |
| size2 | [Size](/imaging/python-net/aspose.imaging/size/) | 要添加的第二个 [Size](/imaging/python-net/aspose.imaging/size/)。 |

**Returns**

| Type | Description |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | 一个 [Size](/imaging/python-net/aspose.imaging/size/) 结构，作为加法操作的结果。 |


### Method: ceiling(size)  [static] {#ceiling_size_2}


```
 ceiling(size) 
```

通过将指定的 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构的值四舍入到更高的整数，将其转换为 [Size](/imaging/python-net/aspose.imaging/size/) 结构。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | 要转换的 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构。 |

**Returns**

| Type | Description |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | 此方法转换为的 [Size](/imaging/python-net/aspose.imaging/size/) 结构。 |


### Method: round(size)  [static] {#round_size_3}


```
 round(size) 
```

通过将指定的 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构的值四舍五入到最近的整数，将其转换为 [Size](/imaging/python-net/aspose.imaging/size/) 结构。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | 要转换的 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构。 |

**Returns**

| Type | Description |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | 此方法转换为的 [Size](/imaging/python-net/aspose.imaging/size/) 结构。 |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

从另一个 [Size](/imaging/python-net/aspose.imaging/size/) 结构的宽度和高度中减去一个 [Size](/imaging/python-net/aspose.imaging/size/) 结构的宽度和高度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| size1 | [Size](/imaging/python-net/aspose.imaging/size/) | 减法运算符左侧的 [Size](/imaging/python-net/aspose.imaging/size/) 结构。 |
| size2 | [Size](/imaging/python-net/aspose.imaging/size/) | 减法运算符右侧的 [Size](/imaging/python-net/aspose.imaging/size/) 结构。 |

**Returns**

| Type | Description |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | 减法运算的结果所得到的 [Size](/imaging/python-net/aspose.imaging/size/) 结构。 |


### Method: truncate(size)  [static] {#truncate_size_5}


```
 truncate(size) 
```

通过将指定的 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构的值截断为更低的整数，将其转换为 [Size](/imaging/python-net/aspose.imaging/size/) 结构。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | 要转换的 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 结构。 |

**Returns**

| Type | Description |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | 此方法转换为的 [Size](/imaging/python-net/aspose.imaging/size/) 结构。 |


