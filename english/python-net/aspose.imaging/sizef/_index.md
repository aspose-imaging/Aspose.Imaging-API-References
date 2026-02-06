---
title: SizeF Class
type: docs
weight: 7280
url: /python-net/aspose.imaging/sizef/
---

**Summary:** Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.SizeF

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SizeF()](#SizeF__1) | Initializes a new instance of the SizeF class |
| [SizeF(point)](#SizeF_point_2) | Initializes a new instance of the [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure from the specified [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [SizeF(size)](#SizeF_size_3) | Initializes a new instance of the [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure from the specified [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| [SizeF(width, height)](#SizeF_width_height_4) | Initializes a new instance of the [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure from the specified dimensions. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| empty [static] | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r | Gets a new instance of the [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure that has [SizeF.width](/imaging/python-net/aspose.imaging/sizef/) and [SizeF.height](/imaging/python-net/aspose.imaging/sizef/) values set to zero. |
| height | float | r/w | Gets or sets the vertical component of this [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| is_empty | bool | r | Gets a value indicating whether this [SizeF](/imaging/python-net/aspose.imaging/sizef/) has zero width and height. |
| width | float | r/w | Gets or sets the horizontal component of this [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Adds the width and height of one [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure to the width and height of another [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure. |
| [create_from_point_f(point)](#create_from_point_f_point_2) | Initializes a new instance of the [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure from the specified [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [create_from_size_f(size)](#create_from_size_f_size_3) | Initializes a new instance of the [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure from the specified [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| [subtract(size1, size2)](#subtract_size1_size2_4) | Subtracts the width and height of one [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure from the width and height of another [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure. |
| [to_point_f()](#to_point_f__5) | Converts a [SizeF](/imaging/python-net/aspose.imaging/sizef/) to a [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [to_size()](#to_size__6) | Converts a [SizeF](/imaging/python-net/aspose.imaging/sizef/) to a [Size](/imaging/python-net/aspose.imaging/size/) structure with truncated size values. |


### Constructor: SizeF() {#SizeF__1}


```
 SizeF() 
```

Initializes a new instance of the SizeF class

### Constructor: SizeF(point) {#SizeF_point_2}


```
 SizeF(point) 
```

Initializes a new instance of the [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure from the specified [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) from which to initialize this [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

### Constructor: SizeF(size) {#SizeF_size_3}


```
 SizeF(size) 
```

Initializes a new instance of the [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure from the specified [SizeF](/imaging/python-net/aspose.imaging/sizef/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | The [SizeF](/imaging/python-net/aspose.imaging/sizef/) from which to create the new [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

### Constructor: SizeF(width, height) {#SizeF_width_height_4}


```
 SizeF(width, height) 
```

Initializes a new instance of the [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure from the specified dimensions.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| width | float | The width component of the new [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| height | float | The height component of the new [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Adds the width and height of one [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure to the width and height of another [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size1 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | The first [SizeF](/imaging/python-net/aspose.imaging/sizef/) to add. |
| size2 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | The second [SizeF](/imaging/python-net/aspose.imaging/sizef/) to add. |

**Returns**

| Type | Description |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | A [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure that is the result of the addition operation. |


### Method: create_from_point_f(point)  [static] {#create_from_point_f_point_2}


```
 create_from_point_f(point) 
```

Initializes a new instance of the [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure from the specified [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) from which to initialize this [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

**Returns**

| Type | Description |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) |  |


### Method: create_from_size_f(size)  [static] {#create_from_size_f_size_3}


```
 create_from_size_f(size) 
```

Initializes a new instance of the [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure from the specified [SizeF](/imaging/python-net/aspose.imaging/sizef/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | The [SizeF](/imaging/python-net/aspose.imaging/sizef/) from which to create the new [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

**Returns**

| Type | Description |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) |  |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

Subtracts the width and height of one [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure from the width and height of another [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size1 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | The [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure on the left side of the subtraction operator. |
| size2 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | The [SizeF](/imaging/python-net/aspose.imaging/sizef/) structure on the right side of the subtraction operator. |

**Returns**

| Type | Description |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | The [SizeF](/imaging/python-net/aspose.imaging/sizef/) that is a result of the subtraction operation. |


### Method: to_point_f() {#to_point_f__5}


```
 to_point_f() 
```

Converts a [SizeF](/imaging/python-net/aspose.imaging/sizef/) to a [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | Returns a [PointF](/imaging/python-net/aspose.imaging/pointf/) structure. |


### Method: to_size() {#to_size__6}


```
 to_size() 
```

Converts a [SizeF](/imaging/python-net/aspose.imaging/sizef/) to a [Size](/imaging/python-net/aspose.imaging/size/) structure with truncated size values.

**Returns**

| Type | Description |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | Returns a [Size](/imaging/python-net/aspose.imaging/size/) structure. |


