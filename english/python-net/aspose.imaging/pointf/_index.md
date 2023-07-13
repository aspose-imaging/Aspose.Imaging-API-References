---
title: PointF Class
type: docs
weight: 6780
url: /python-net/aspose.imaging/pointf/
---

Represents an ordered pair of floating-point x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.PointF

**Aspose.Imaging Version:** 23.6

The PointF type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [PointF(x, y)](#PointF_x_y_0) | Initializes a new instance of the [PointF](/imaging/python-net/aspose.imaging/pointf/) structure with the specified coordinates. |
| [PointF()](#PointF__1) | Initializes a new instance of the PointF class |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| empty [static] | [PointF](/imaging/python-net/aspose.imaging/pointf) | r | Gets a new instance of the [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that has [x](/imaging/python-net/aspose.imaging/pointf/) and [y](/imaging/python-net/aspose.imaging/pointf/) values set to zero. |
| is_empty | bool | r | Gets a value indicating whether this [PointF](/imaging/python-net/aspose.imaging/pointf/) is empty. |
| x | float | r/w | Gets or sets the x-coordinate of this [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| y | float | r/w | Gets or sets the y-coordinate of this [PointF](/imaging/python-net/aspose.imaging/pointf/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(point, size)](#add_point_size_2) | Translates a given [PointF](/imaging/python-net/aspose.imaging/pointf/) by the specified [Size](/imaging/python-net/aspose.imaging/size/). |
| [add(point, size)](#add_point_size_3) | Translates a given [PointF](/imaging/python-net/aspose.imaging/pointf/) by the specified [Size](/imaging/python-net/aspose.imaging/size/). |
| [subtract(point, size)](#subtract_point_size_4) | Translates a [PointF](/imaging/python-net/aspose.imaging/pointf/) by the negative of a specified size. |
| [subtract(point, size)](#subtract_point_size_5) | Translates a [PointF](/imaging/python-net/aspose.imaging/pointf/) by the negative of a specified size. |
| [add_size(point, size)](#add_size_point_size_6) | Translates a given [PointF](/imaging/python-net/aspose.imaging/pointf/) by the specified [Size](/imaging/python-net/aspose.imaging/size/). |
| [subtract_size(point, size)](#subtract_size_point_size_7) | Translates a [PointF](/imaging/python-net/aspose.imaging/pointf/) by the negative of a specified size. |
| [add_size_f(point, size)](#add_size_f_point_size_8) | Translates a given [PointF](/imaging/python-net/aspose.imaging/pointf/) by a specified [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| [subtract_size_f(point, size)](#subtract_size_f_point_size_9) | Translates a [PointF](/imaging/python-net/aspose.imaging/pointf/) by the negative of a specified size. |

### PointF(x, y) {#PointF_x_y_0}


```
 PointF(x, y) 
```

Initializes a new instance of the [PointF](/imaging/python-net/aspose.imaging/pointf/) structure with the specified coordinates.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The horizontal position of the point. |
| y | float | The vertical position of the point. |

### PointF() {#PointF__1}


```
 PointF() 
```

Initializes a new instance of the PointF class

### add(point, size)  [static] {#add_point_size_2}


```
 add(point, size) 
```

Translates a given [PointF](/imaging/python-net/aspose.imaging/pointf/) by the specified [Size](/imaging/python-net/aspose.imaging/size/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) to translate. |
| size | [Size](/imaging/python-net/aspose.imaging/size) | The [Size](/imaging/python-net/aspose.imaging/size/) that specifies the numbers to add to the coordinates of <paramref name="point" />. |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf) | The translated [PointF](/imaging/python-net/aspose.imaging/pointf/). |


### add(point, size)  [static] {#add_point_size_3}


```
 add(point, size) 
```

Translates a given [PointF](/imaging/python-net/aspose.imaging/pointf/) by the specified [Size](/imaging/python-net/aspose.imaging/size/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) to translate. |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef) | The [Size](/imaging/python-net/aspose.imaging/size/) that specifies the numbers to add to the coordinates of <paramref name="point" />. |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf) | The translated [PointF](/imaging/python-net/aspose.imaging/pointf/). |


### subtract(point, size)  [static] {#subtract_point_size_4}


```
 subtract(point, size) 
```

Translates a [PointF](/imaging/python-net/aspose.imaging/pointf/) by the negative of a specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) to translate. |
| size | [Size](/imaging/python-net/aspose.imaging/size) | The [Size](/imaging/python-net/aspose.imaging/size/) that specifies the numbers to subtract from the coordinates of <paramref name="point" />. |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf) | The translated [PointF](/imaging/python-net/aspose.imaging/pointf/). |


### subtract(point, size)  [static] {#subtract_point_size_5}


```
 subtract(point, size) 
```

Translates a [PointF](/imaging/python-net/aspose.imaging/pointf/) by the negative of a specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) to translate. |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef) | The [Size](/imaging/python-net/aspose.imaging/size/) that specifies the numbers to subtract from the coordinates of <paramref name="point" />. |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf) | The translated [PointF](/imaging/python-net/aspose.imaging/pointf/). |


### add_size(point, size)  [static] {#add_size_point_size_6}


```
 add_size(point, size) 
```

Translates a given [PointF](/imaging/python-net/aspose.imaging/pointf/) by the specified [Size](/imaging/python-net/aspose.imaging/size/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) to translate. |
| size | [Size](/imaging/python-net/aspose.imaging/size) | The [Size](/imaging/python-net/aspose.imaging/size/) that specifies the numbers to add to the coordinates of <paramref name="point" />. |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf) | The translated [PointF](/imaging/python-net/aspose.imaging/pointf/). |


### subtract_size(point, size)  [static] {#subtract_size_point_size_7}


```
 subtract_size(point, size) 
```

Translates a [PointF](/imaging/python-net/aspose.imaging/pointf/) by the negative of a specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) to translate. |
| size | [Size](/imaging/python-net/aspose.imaging/size) | The [Size](/imaging/python-net/aspose.imaging/size/) that specifies the numbers to subtract from the coordinates of <paramref name="point" />. |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf) | The translated [PointF](/imaging/python-net/aspose.imaging/pointf/). |


### add_size_f(point, size)  [static] {#add_size_f_point_size_8}


```
 add_size_f(point, size) 
```

Translates a given [PointF](/imaging/python-net/aspose.imaging/pointf/) by a specified [SizeF](/imaging/python-net/aspose.imaging/sizef/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) to translate. |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef) | The [SizeF](/imaging/python-net/aspose.imaging/sizef/) that specifies the numbers to add to the coordinates of <paramref name="point" />. |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf) | The translated [PointF](/imaging/python-net/aspose.imaging/pointf/). |


### subtract_size_f(point, size)  [static] {#subtract_size_f_point_size_9}


```
 subtract_size_f(point, size) 
```

Translates a [PointF](/imaging/python-net/aspose.imaging/pointf/) by the negative of a specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) to translate. |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef) | The [SizeF](/imaging/python-net/aspose.imaging/sizef/) that specifies the numbers to subtract from the coordinates of <paramref name="point" />. |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf) | The translated [PointF](/imaging/python-net/aspose.imaging/pointf/). |


