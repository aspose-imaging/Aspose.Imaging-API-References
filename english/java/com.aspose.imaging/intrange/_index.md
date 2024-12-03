---
title: IntRange
second_title: Aspose.Imaging for Java API Reference
description: Class for representing sequence of elements
type: docs
weight: 64
url: /java/com.aspose.imaging/intrange/
---
**Inheritance:**
java.lang.Object
```
public class IntRange
```

Class for representing sequence of elements
## Constructors

| Constructor | Description |
| --- | --- |
| [IntRange(int start, int count)](#IntRange-int-int-) | Initializes a new instance of the `IntRange` class. |
| [IntRange(int start, int count, int delta)](#IntRange-int-int-int-) | Initializes a new instance of the `IntRange` class. |
| [IntRange(int[] range)](#IntRange-int---) | Initializes a new instance of the `IntRange` class. |
## Methods

| Method | Description |
| --- | --- |
| [getRange()](#getRange--) | Gets the range. |
| [setRange(int[] value)](#setRange-int---) | Sets the range. |
| [getArrayOneItemFromIndex(int index)](#getArrayOneItemFromIndex-int-) | Returns one item array from specified index |
| [getRange(int start, int count, int delta)](#getRange-int-int-int-) | Gets the count range of int elements starting at start |
### IntRange(int start, int count) {#IntRange-int-int-}
```
public IntRange(int start, int count)
```


Initializes a new instance of the `IntRange` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| start | int | The start. |
| count | int | The count. |

### IntRange(int start, int count, int delta) {#IntRange-int-int-int-}
```
public IntRange(int start, int count, int delta)
```


Initializes a new instance of the `IntRange` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| start | int | The start. |
| count | int | The count. |
| delta | int | The delta. |

### IntRange(int[] range) {#IntRange-int---}
```
public IntRange(int[] range)
```


Initializes a new instance of the `IntRange` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| range | int[] | The range. |

### getRange() {#getRange--}
```
public int[] getRange()
```


Gets the range.

**Returns:**
int[] - The range.
### setRange(int[] value) {#setRange-int---}
```
public void setRange(int[] value)
```


Sets the range.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | The range. |

### getArrayOneItemFromIndex(int index) {#getArrayOneItemFromIndex-int-}
```
public int[] getArrayOneItemFromIndex(int index)
```


Returns one item array from specified index

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The range index. |

**Returns:**
int[] - The array of `System.Int32`
### getRange(int start, int count, int delta) {#getRange-int-int-int-}
```
public static int[] getRange(int start, int count, int delta)
```


Gets the count range of int elements starting at start

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| start | int | The start. |
| count | int | The count. |
| delta | int | The delta. |

**Returns:**
int[] - Array of items
