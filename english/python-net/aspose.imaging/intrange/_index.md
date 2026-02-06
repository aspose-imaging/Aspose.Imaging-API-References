---
title: IntRange Class
type: docs
weight: 5810
url: /python-net/aspose.imaging/intrange/
---

**Summary:** Class for representing sequence of elements

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IntRange

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [IntRange(range)](#IntRange_range_1) | Initializes a new instance of the [IntRange](/imaging/python-net/aspose.imaging/intrange/) class. |
| [IntRange(start, count)](#IntRange_start_count_2) | Initializes a new instance of the [IntRange](/imaging/python-net/aspose.imaging/intrange/) class. |
| [IntRange(start, count, delta)](#IntRange_start_count_delta_3) | Initializes a new instance of the [IntRange](/imaging/python-net/aspose.imaging/intrange/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| range | int[] | r/w | Gets or sets the range. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_array_one_item_from_index(index)](#get_array_one_item_from_index_index_1) | Returns one item array from specified index |
| [get_range(start, count, delta)](#get_range_start_count_delta_2) | Gets the count range of int elements starting at start |


### Constructor: IntRange(range) {#IntRange_range_1}


```
 IntRange(range) 
```

Initializes a new instance of the [IntRange](/imaging/python-net/aspose.imaging/intrange/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| range | int[] | The range. |

### Constructor: IntRange(start, count) {#IntRange_start_count_2}


```
 IntRange(start, count) 
```

Initializes a new instance of the [IntRange](/imaging/python-net/aspose.imaging/intrange/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| start | int | The start. |
| count | int | The count. |

### Constructor: IntRange(start, count, delta) {#IntRange_start_count_delta_3}


```
 IntRange(start, count, delta) 
```

Initializes a new instance of the [IntRange](/imaging/python-net/aspose.imaging/intrange/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| start | int | The start. |
| count | int | The count. |
| delta | int | The delta. |

### Method: get_array_one_item_from_index(index) {#get_array_one_item_from_index_index_1}


```
 get_array_one_item_from_index(index) 
```

Returns one item array from specified index

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The range index. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | The array of string |


### Method: get_range(start, count, delta)  [static] {#get_range_start_count_delta_2}


```
 get_range(start, count, delta) 
```

Gets the count range of int elements starting at start

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| start | int | The start. |
| count | int | The count. |
| delta | int | The delta. |

**Returns**

| Type | Description |
| :- | :- |
| System.Collections.Generic.IEnumerable`1[[System.Int32]] | Array of items |


