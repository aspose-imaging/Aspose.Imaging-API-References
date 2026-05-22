---
title: "IntRange 类"
type: docs
weight: 5810
url: /zh/python-net/aspose.imaging/intrange/
---

**Summary:** Class for representing sequence of elements

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IntRange

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [IntRange(range)](#IntRange_range_1) | 初始化一个新的 [IntRange](/imaging/python-net/aspose.imaging/intrange/) 类实例。 |
| [IntRange(start, count)](#IntRange_start_count_2) | 初始化一个新的 [IntRange](/imaging/python-net/aspose.imaging/intrange/) 类实例。 |
| [IntRange(start, count, delta)](#IntRange_start_count_delta_3) | 初始化一个新的 [IntRange](/imaging/python-net/aspose.imaging/intrange/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| 范围 | int[] | r/w | 获取或设置范围。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [get_array_one_item_from_index(index)](#get_array_one_item_from_index_index_1) | 从指定索引返回包含一个项目的数组 |
| [get_range(start, count, delta)](#get_range_start_count_delta_2) | 获取从 start 开始的 int 元素计数范围 |


### Constructor: IntRange(range) {#IntRange_range_1}


```
 IntRange(range) 
```

初始化一个新的 [IntRange](/imaging/python-net/aspose.imaging/intrange/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 范围 | int[] | 范围。 |

### Constructor: IntRange(start, count) {#IntRange_start_count_2}


```
 IntRange(start, count) 
```

初始化一个新的 [IntRange](/imaging/python-net/aspose.imaging/intrange/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 起始 | int | 起始。 |
| count | int | 计数。 |

### Constructor: IntRange(start, count, delta) {#IntRange_start_count_delta_3}


```
 IntRange(start, count, delta) 
```

初始化一个新的 [IntRange](/imaging/python-net/aspose.imaging/intrange/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 起始 | int | 起始。 |
| count | int | 计数。 |
| 增量 | int | 增量。 |

### Method: get_array_one_item_from_index(index) {#get_array_one_item_from_index_index_1}


```
 get_array_one_item_from_index(index) 
```

从指定索引返回包含一个项目的数组

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| index | int | 范围索引。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | 字符串数组 |


### Method: get_range(start, count, delta)  [static] {#get_range_start_count_delta_2}


```
 get_range(start, count, delta) 
```

获取从 start 开始的 int 元素计数范围

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 起始 | int | 起始。 |
| count | int | 计数。 |
| 增量 | int | 增量。 |

**Returns**

| Type | Description |
| :- | :- |
| System.Collections.Generic.IEnumerable`1[[System.Int32]] | 项目数组 |


