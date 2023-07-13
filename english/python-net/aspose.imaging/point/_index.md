---
title: Point Class
type: docs
weight: 6750
url: /python-net/aspose.imaging/point/
---

Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Point

**Aspose.Imaging Version:** 23.6

The Point type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [Point(x, y)](#Point_x_y_0) | Initializes a new instance of the [Point](/imaging/python-net/aspose.imaging/point/) structure with the specified coordinates. |
| [Point(size)](#Point_size_1) | Initializes a new instance of the Point class |
| [Point(dw)](#Point_dw_2) | Initializes a new instance of the Point class |
| [Point()](#Point__3) | Initializes a new instance of the Point class |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| empty [static] | [Point](/imaging/python-net/aspose.imaging/point) | r | Gets a new instance of the [Point](/imaging/python-net/aspose.imaging/point/) structure that has [x](/imaging/python-net/aspose.imaging/point/) and [y](/imaging/python-net/aspose.imaging/point/) values set to zero. |
| is_empty | bool | r | Gets a value indicating whether this [Point](/imaging/python-net/aspose.imaging/point/) is empty. |
| x | int | r/w | Gets or sets the x-coordinate of this [Point](/imaging/python-net/aspose.imaging/point/). |
| y | int | r/w | Gets or sets the y-coordinate of this [Point](/imaging/python-net/aspose.imaging/point/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [offset(point)](#offset_point_4) | Translates this [Point](/imaging/python-net/aspose.imaging/point/) by the specified [Point](/imaging/python-net/aspose.imaging/point/). |
| [offset(dx, dy)](#offset_dx_dy_5) | Translates this [Point](/imaging/python-net/aspose.imaging/point/) by the specified amount. |
| [create_from_size(size)](#create_from_size_size_6) | Initializes a new instance of the [Point](/imaging/python-net/aspose.imaging/point/) structure from the [Size](/imaging/python-net/aspose.imaging/size/) structure. |
| [create_from_d_word(dw)](#create_from_d_word_dw_7) | Initializes a new instance of the [Point](/imaging/python-net/aspose.imaging/point/) structure using coordinates specified by an integer value. |
| [add(point, size)](#add_point_size_8) | Adds the specified [Size](/imaging/python-net/aspose.imaging/size/) to the specified [Point](/imaging/python-net/aspose.imaging/point/). |
| [subtract(point, size)](#subtract_point_size_9) | Returns the result of subtracting specified [Size](/imaging/python-net/aspose.imaging/size/) from the specified [Point](/imaging/python-net/aspose.imaging/point/). |
| [ceiling(point)](#ceiling_point_10) | Converts the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) to a [Point](/imaging/python-net/aspose.imaging/point/) by rounding the values of the [PointF](/imaging/python-net/aspose.imaging/pointf/) to the next higher integer values. |
| [round(point)](#round_point_11) | Converts the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) to a [Point](/imaging/python-net/aspose.imaging/point/) object by rounding the [Point](/imaging/python-net/aspose.imaging/point/) values to the nearest integer. |
| [truncate(point)](#truncate_point_12) | Converts the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) to a [Point](/imaging/python-net/aspose.imaging/point/) by truncating the values of the [Point](/imaging/python-net/aspose.imaging/point/). |
| [to_long()](#to_long__13) | Convert this Point to a single long value, containing X and Y coordinates in high and low bits. |
| [from_long(packed_point, x, y)](#from_long_packed_point_x_y_14) | Deconstruct a Point object packed into a long object to separate X and Y int values. |

### Point(x, y) {#Point_x_y_0}


```
 Point(x, y) 
```

Initializes a new instance of the [Point](/imaging/python-net/aspose.imaging/point/) structure with the specified coordinates.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The horizontal position of the point. |
| y | int | The vertical position of the point. |

### Point(size) {#Point_size_1}


```
 Point(size) 
```

Initializes a new instance of the Point class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size) |  |

### Point(dw) {#Point_dw_2}


```
 Point(dw) 
```

Initializes a new instance of the Point class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dw | int |  |

### Point() {#Point__3}


```
 Point() 
```

Initializes a new instance of the Point class

### offset(point) {#offset_point_4}


```
 offset(point) 
```

Translates this [Point](/imaging/python-net/aspose.imaging/point/) by the specified [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point) | The [Point](/imaging/python-net/aspose.imaging/point/) used to offset this [Point](/imaging/python-net/aspose.imaging/point/). |

### offset(dx, dy) {#offset_dx_dy_5}


```
 offset(dx, dy) 
```

Translates this [Point](/imaging/python-net/aspose.imaging/point/) by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | int | The amount to offset the x-coordinate. |
| dy | int | The amount to offset the y-coordinate. |

### create_from_size(size)  [static] {#create_from_size_size_6}


```
 create_from_size(size) 
```

Initializes a new instance of the [Point](/imaging/python-net/aspose.imaging/point/) structure from the [Size](/imaging/python-net/aspose.imaging/size/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size) | Contains the new point coordinates. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point) |  |


### create_from_d_word(dw)  [static] {#create_from_d_word_dw_7}


```
 create_from_d_word(dw) 
```

Initializes a new instance of the [Point](/imaging/python-net/aspose.imaging/point/) structure using coordinates specified by an integer value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dw | int | A 32-bit integer that specifies the coordinates for the new point. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point) |  |


### add(point, size)  [static] {#add_point_size_8}


```
 add(point, size) 
```

Adds the specified [Size](/imaging/python-net/aspose.imaging/size/) to the specified [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point) | The [Point](/imaging/python-net/aspose.imaging/point/) to add to. |
| size | [Size](/imaging/python-net/aspose.imaging/size) | The [Size](/imaging/python-net/aspose.imaging/size/) to add to the <paramref name="point" />. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point) | The [Point](/imaging/python-net/aspose.imaging/point/) that is the result of the addition operation. |


### subtract(point, size)  [static] {#subtract_point_size_9}


```
 subtract(point, size) 
```

Returns the result of subtracting specified [Size](/imaging/python-net/aspose.imaging/size/) from the specified [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point) | The [Point](/imaging/python-net/aspose.imaging/point/) to be subtracted from. |
| size | [Size](/imaging/python-net/aspose.imaging/size) | The [Size](/imaging/python-net/aspose.imaging/size/) to subtract from the <paramref name="point" />. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point) | The [Point](/imaging/python-net/aspose.imaging/point/) that is the result of the subtraction operation. |


### ceiling(point)  [static] {#ceiling_point_10}


```
 ceiling(point) 
```

Converts the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) to a [Point](/imaging/python-net/aspose.imaging/point/) by rounding the values of the [PointF](/imaging/python-net/aspose.imaging/pointf/) to the next higher integer values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) to convert. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point) | The [Point](/imaging/python-net/aspose.imaging/point/) this method converts to. |


### round(point)  [static] {#round_point_11}


```
 round(point) 
```

Converts the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) to a [Point](/imaging/python-net/aspose.imaging/point/) object by rounding the [Point](/imaging/python-net/aspose.imaging/point/) values to the nearest integer.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) to convert. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point) | The [Point](/imaging/python-net/aspose.imaging/point/) this method converts to. |


### truncate(point)  [static] {#truncate_point_12}


```
 truncate(point) 
```

Converts the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) to a [Point](/imaging/python-net/aspose.imaging/point/) by truncating the values of the [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) to convert. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point) | The [Point](/imaging/python-net/aspose.imaging/point/) this method converts to. |


### to_long() {#to_long__13}


```
 to_long() 
```

Convert this Point to a single long value, containing X and Y coordinates in high and low bits.

**Returns**

| Type | Description |
| :- | :- |
| long | The Point object packed into one long value. |


### from_long(packed_point, x, y)  [static] {#from_long_packed_point_x_y_14}


```
 from_long(packed_point, x, y) 
```

Deconstruct a Point object packed into a long object to separate X and Y int values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| packed_point | long | The Point object packed into one long value. |
| x | int[] | The extracted from the packed Point X value. |
| y | int[] | The extracted from the packed Point Y value. |

