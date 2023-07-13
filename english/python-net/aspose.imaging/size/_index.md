---
title: Size Class
type: docs
weight: 7070
url: /python-net/aspose.imaging/size/
---

Represents size.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Size

**Aspose.Imaging Version:** 23.6

The Size type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [Size(point)](#Size_point_0) | Initializes a new instance of the [Size](/imaging/python-net/aspose.imaging/size/) structure from the specified [Point](/imaging/python-net/aspose.imaging/point/). |
| [Size(width, height)](#Size_width_height_1) | Initializes a new instance of the [Size](/imaging/python-net/aspose.imaging/size/) structure from the specified dimensions. |
| [Size()](#Size__2) | Initializes a new instance of the Size class |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| empty [static] | [Size](/imaging/python-net/aspose.imaging/size) | r | Gets a new instance of the [Size](/imaging/python-net/aspose.imaging/size/) structure that has [width](/imaging/python-net/aspose.imaging/size/) and [height](/imaging/python-net/aspose.imaging/size/) values set to zero. |
| is_empty | bool | r | Gets a value indicating whether this [Size](/imaging/python-net/aspose.imaging/size/) has width and height of 0. |
| width | int | r/w | Gets or sets the horizontal component of this [Size](/imaging/python-net/aspose.imaging/size/). |
| height | int | r/w | Gets or sets the vertical component of this [Size](/imaging/python-net/aspose.imaging/size/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_3) | Adds the width and height of one [Size](/imaging/python-net/aspose.imaging/size/) structure to the width and height of another [Size](/imaging/python-net/aspose.imaging/size/) structure. |
| [ceiling(size)](#ceiling_size_4) | Converts the specified [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure to a [Size](/imaging/python-net/aspose.imaging/size/) structure by rounding the values of the [Size](/imaging/python-net/aspose.imaging/size/) structure to the next higher integer values. |
| [subtract(size1, size2)](#subtract_size1_size2_5) | Subtracts the width and height of one [Size](/imaging/python-net/aspose.imaging/size/) structure from the width and height of another [Size](/imaging/python-net/aspose.imaging/size/) structure. |
| [truncate(size)](#truncate_size_6) | Converts the specified [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure to a [Size](/imaging/python-net/aspose.imaging/size/) structure by truncating the values of the [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure to the next lower integer values. |
| [round(size)](#round_size_7) | Converts the specified [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure to a [Size](/imaging/python-net/aspose.imaging/size/) structure by rounding the values of the [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure to the nearest integer values. |

### Size(point) {#Size_point_0}


```
 Size(point) 
```

Initializes a new instance of the [Size](/imaging/python-net/aspose.imaging/size/) structure from the specified [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point) | The [Point](/imaging/python-net/aspose.imaging/point/) from which to initialize this [Size](/imaging/python-net/aspose.imaging/size/). |

### Size(width, height) {#Size_width_height_1}


```
 Size(width, height) 
```

Initializes a new instance of the [Size](/imaging/python-net/aspose.imaging/size/) structure from the specified dimensions.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| width | int | The width component of the new [Size](/imaging/python-net/aspose.imaging/size/). |
| height | int | The height component of the new [Size](/imaging/python-net/aspose.imaging/size/). |

### Size() {#Size__2}


```
 Size() 
```

Initializes a new instance of the Size class

### add(size1, size2)  [static] {#add_size1_size2_3}


```
 add(size1, size2) 
```

Adds the width and height of one [Size](/imaging/python-net/aspose.imaging/size/) structure to the width and height of another [Size](/imaging/python-net/aspose.imaging/size/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size1 | [Size](/imaging/python-net/aspose.imaging/size) | The first [Size](/imaging/python-net/aspose.imaging/size/) to add. |
| size2 | [Size](/imaging/python-net/aspose.imaging/size) | The second [Size](/imaging/python-net/aspose.imaging/size/) to add. |

**Returns**

| Type | Description |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size) | A [Size](/imaging/python-net/aspose.imaging/size/) structure that is the result of the addition operation. |


### ceiling(size)  [static] {#ceiling_size_4}


```
 ceiling(size) 
```

Converts the specified [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure to a [Size](/imaging/python-net/aspose.imaging/size/) structure by rounding the values of the [Size](/imaging/python-net/aspose.imaging/size/) structure to the next higher integer values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef) | The [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure to convert. |

**Returns**

| Type | Description |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size) | The [Size](/imaging/python-net/aspose.imaging/size/) structure this method converts to. |


### subtract(size1, size2)  [static] {#subtract_size1_size2_5}


```
 subtract(size1, size2) 
```

Subtracts the width and height of one [Size](/imaging/python-net/aspose.imaging/size/) structure from the width and height of another [Size](/imaging/python-net/aspose.imaging/size/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size1 | [Size](/imaging/python-net/aspose.imaging/size) | The [Size](/imaging/python-net/aspose.imaging/size/) structure on the left side of the subtraction operator. |
| size2 | [Size](/imaging/python-net/aspose.imaging/size) | The [Size](/imaging/python-net/aspose.imaging/size/) structure on the right side of the subtraction operator. |

**Returns**

| Type | Description |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size) | The [Size](/imaging/python-net/aspose.imaging/size/) that is a result of the subtraction operation. |


### truncate(size)  [static] {#truncate_size_6}


```
 truncate(size) 
```

Converts the specified [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure to a [Size](/imaging/python-net/aspose.imaging/size/) structure by truncating the values of the [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure to the next lower integer values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef) | The [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure to convert. |

**Returns**

| Type | Description |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size) | The [Size](/imaging/python-net/aspose.imaging/size/) structure this method converts to. |


### round(size)  [static] {#round_size_7}


```
 round(size) 
```

Converts the specified [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure to a [Size](/imaging/python-net/aspose.imaging/size/) structure by rounding the values of the [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure to the nearest integer values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef) | The [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure to convert. |

**Returns**

| Type | Description |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size) | The [Size](/imaging/python-net/aspose.imaging/size/) structure this method converts to. |


