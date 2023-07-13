---
title: IntRange Class
type: docs
weight: 5620
url: /python-net/aspose.imaging/intrange/
---

Class for representing sequence of elements

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IntRange

**Aspose.Imaging Version:** 23.6

The IntRange type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [IntRange(start, count)](#IntRange_start_count_0) | Initializes a new instance of the [IntRange](/imaging/python-net/aspose.imaging/intrange/) class. |
| [IntRange(start, count, delta)](#IntRange_start_count_delta_1) | Initializes a new instance of the [IntRange](/imaging/python-net/aspose.imaging/intrange/) class. |
| [IntRange(range)](#IntRange_range_2) | Initializes a new instance of the [IntRange](/imaging/python-net/aspose.imaging/intrange/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| range | int | r/w | Gets or sets the range. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_array_one_item_from_index(index)](#get_array_one_item_from_index_index_3) | Returns one item array from specified index |
| [get_range(start, count, delta)](#get_range_start_count_delta_4) | Gets the count range of int elements starting at start |

### IntRange(start, count) {#IntRange_start_count_0}


```
 IntRange(start, count) 
```

Initializes a new instance of the [IntRange](/imaging/python-net/aspose.imaging/intrange/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| start | int | The start. |
| count | int | The count. |

### IntRange(start, count, delta) {#IntRange_start_count_delta_1}


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

### IntRange(range) {#IntRange_range_2}


```
 IntRange(range) 
```

Initializes a new instance of the [IntRange](/imaging/python-net/aspose.imaging/intrange/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| range | int | The range. |

### get_array_one_item_from_index(index) {#get_array_one_item_from_index_index_3}


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
| int | The array of <see cref="T:int" /> |


### get_range(start, count, delta)  [static] {#get_range_start_count_delta_4}


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
| System.Collections.Generic.IEnumerable<int> | Array of items |


