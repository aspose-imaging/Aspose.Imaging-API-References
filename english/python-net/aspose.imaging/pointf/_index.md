---
title: PointF Class
type: docs
weight: 6920
url: /python-net/aspose.imaging/pointf/
---

**Summary:** Represents an ordered pair of floating-point x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.PointF

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PointF()](#PointF__1) | Initializes a new instance of the PointF class |
| [PointF(x, y)](#PointF_x_y_2) | Initializes a new instance of the [PointF](/imaging/python-net/aspose.imaging/pointf/) structure with the specified coordinates. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| empty [static] | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Gets a new instance of the [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that has [PointF.x](/imaging/python-net/aspose.imaging/pointf/) and [PointF.y](/imaging/python-net/aspose.imaging/pointf/) values set to zero. |
| is_empty | bool | r | Gets a value indicating whether this [PointF](/imaging/python-net/aspose.imaging/pointf/) is empty. |
| x | float | r/w | Gets or sets the x-coordinate of this [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| y | float | r/w | Gets or sets the y-coordinate of this [PointF](/imaging/python-net/aspose.imaging/pointf/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | Translates a given [PointF](/imaging/python-net/aspose.imaging/pointf/) by the specified [Size](/imaging/python-net/aspose.imaging/size/). |
| [add(point, size)](#add_point_size_2) | Translates a given [PointF](/imaging/python-net/aspose.imaging/pointf/) by the specified [Size](/imaging/python-net/aspose.imaging/size/). |
| [add_size(point, size)](#add_size_point_size_3) | Translates a given [PointF](/imaging/python-net/aspose.imaging/pointf/) by the specified [Size](/imaging/python-net/aspose.imaging/size/). |
| [add_size_f(point, size)](#add_size_f_point_size_4) | Translates a given [PointF](/imaging/python-net/aspose.imaging/pointf/) by a specified [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| [subtract(point, size)](#subtract_point_size_5) | Translates a [PointF](/imaging/python-net/aspose.imaging/pointf/) by the negative of a specified size. |
| [subtract(point, size)](#subtract_point_size_6) | Translates a [PointF](/imaging/python-net/aspose.imaging/pointf/) by the negative of a specified size. |
| [subtract_size(point, size)](#subtract_size_point_size_7) | Translates a [PointF](/imaging/python-net/aspose.imaging/pointf/) by the negative of a specified size. |
| [subtract_size_f(point, size)](#subtract_size_f_point_size_8) | Translates a [PointF](/imaging/python-net/aspose.imaging/pointf/) by the negative of a specified size. |


### Constructor: PointF() {#PointF__1}


```
 PointF() 
```

Initializes a new instance of the PointF class

### Constructor: PointF(x, y) {#PointF_x_y_2}


```
 PointF(x, y) 
```

Initializes a new instance of the [PointF](/imaging/python-net/aspose.imaging/pointf/) structure with the specified coordinates.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The horizontal position of the point. |
| y | float | The vertical position of the point. |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

Translates a given [PointF](/imaging/python-net/aspose.imaging/pointf/) by the specified [Size](/imaging/python-net/aspose.imaging/size/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) to translate. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | The [Size](/imaging/python-net/aspose.imaging/size/) that specifies the numbers to add to the coordinates of _point_. |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | The translated [PointF](/imaging/python-net/aspose.imaging/pointf/). |


### Method: add(point, size)  [static] {#add_point_size_2}


```
 add(point, size) 
```

Translates a given [PointF](/imaging/python-net/aspose.imaging/pointf/) by the specified [Size](/imaging/python-net/aspose.imaging/size/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) to translate. |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | The [Size](/imaging/python-net/aspose.imaging/size/) that specifies the numbers to add to the coordinates of _point_. |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | The translated [PointF](/imaging/python-net/aspose.imaging/pointf/). |


### Method: add_size(point, size)  [static] {#add_size_point_size_3}


```
 add_size(point, size) 
```

Translates a given [PointF](/imaging/python-net/aspose.imaging/pointf/) by the specified [Size](/imaging/python-net/aspose.imaging/size/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) to translate. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | The [Size](/imaging/python-net/aspose.imaging/size/) that specifies the numbers to add to the coordinates of _point_. |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | The translated [PointF](/imaging/python-net/aspose.imaging/pointf/). |


### Method: add_size_f(point, size)  [static] {#add_size_f_point_size_4}


```
 add_size_f(point, size) 
```

Translates a given [PointF](/imaging/python-net/aspose.imaging/pointf/) by a specified [SizeF](/imaging/python-net/aspose.imaging/sizef/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) to translate. |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | The [SizeF](/imaging/python-net/aspose.imaging/sizef/) that specifies the numbers to add to the coordinates of _point_. |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | The translated [PointF](/imaging/python-net/aspose.imaging/pointf/). |


### Method: subtract(point, size)  [static] {#subtract_point_size_5}


```
 subtract(point, size) 
```

Translates a [PointF](/imaging/python-net/aspose.imaging/pointf/) by the negative of a specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) to translate. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | The [Size](/imaging/python-net/aspose.imaging/size/) that specifies the numbers to subtract from the coordinates of _point_. |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | The translated [PointF](/imaging/python-net/aspose.imaging/pointf/). |


### Method: subtract(point, size)  [static] {#subtract_point_size_6}


```
 subtract(point, size) 
```

Translates a [PointF](/imaging/python-net/aspose.imaging/pointf/) by the negative of a specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) to translate. |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | The [Size](/imaging/python-net/aspose.imaging/size/) that specifies the numbers to subtract from the coordinates of _point_. |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | The translated [PointF](/imaging/python-net/aspose.imaging/pointf/). |


### Method: subtract_size(point, size)  [static] {#subtract_size_point_size_7}


```
 subtract_size(point, size) 
```

Translates a [PointF](/imaging/python-net/aspose.imaging/pointf/) by the negative of a specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) to translate. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | The [Size](/imaging/python-net/aspose.imaging/size/) that specifies the numbers to subtract from the coordinates of _point_. |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | The translated [PointF](/imaging/python-net/aspose.imaging/pointf/). |


### Method: subtract_size_f(point, size)  [static] {#subtract_size_f_point_size_8}


```
 subtract_size_f(point, size) 
```

Translates a [PointF](/imaging/python-net/aspose.imaging/pointf/) by the negative of a specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) to translate. |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | The [SizeF](/imaging/python-net/aspose.imaging/sizef/) that specifies the numbers to subtract from the coordinates of _point_. |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | The translated [PointF](/imaging/python-net/aspose.imaging/pointf/). |


