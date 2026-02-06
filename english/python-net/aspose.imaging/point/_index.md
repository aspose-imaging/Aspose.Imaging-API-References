---
title: Point Class
type: docs
weight: 6960
url: /python-net/aspose.imaging/point/
---

**Summary:** Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Point

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Point()](#Point__1) | Initializes a new instance of the Point class |
| [Point(dw)](#Point_dw_2) | Initializes a new instance of the [Point](/imaging/python-net/aspose.imaging/point/) structure using coordinates specified by an integer value. |
| [Point(size)](#Point_size_3) | Initializes a new instance of the [Point](/imaging/python-net/aspose.imaging/point/) structure from the [Size](/imaging/python-net/aspose.imaging/size/) structure. |
| [Point(x, y)](#Point_x_y_4) | Initializes a new instance of the [Point](/imaging/python-net/aspose.imaging/point/) structure with the specified coordinates. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| empty [static] | [Point](/imaging/python-net/aspose.imaging/point/) | r | Gets a new instance of the [Point](/imaging/python-net/aspose.imaging/point/) structure that has [Point.x](/imaging/python-net/aspose.imaging/point/) and [Point.y](/imaging/python-net/aspose.imaging/point/) values set to zero. |
| is_empty | bool | r | Gets a value indicating whether this [Point](/imaging/python-net/aspose.imaging/point/) is empty. |
| x | int | r/w | Gets or sets the x-coordinate of this [Point](/imaging/python-net/aspose.imaging/point/). |
| y | int | r/w | Gets or sets the y-coordinate of this [Point](/imaging/python-net/aspose.imaging/point/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | Adds the specified [Size](/imaging/python-net/aspose.imaging/size/) to the specified [Point](/imaging/python-net/aspose.imaging/point/). |
| [ceiling(point)](#ceiling_point_2) | Converts the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) to a [Point](/imaging/python-net/aspose.imaging/point/) by rounding the values of the [PointF](/imaging/python-net/aspose.imaging/pointf/) to the next higher integer values. |
| [create_from_d_word(dw)](#create_from_d_word_dw_3) | Initializes a new instance of the [Point](/imaging/python-net/aspose.imaging/point/) structure using coordinates specified by an integer value. |
| [create_from_size(size)](#create_from_size_size_4) | Initializes a new instance of the [Point](/imaging/python-net/aspose.imaging/point/) structure from the [Size](/imaging/python-net/aspose.imaging/size/) structure. |
| [from_long(packed_point, x, y)](#from_long_packed_point_x_y_5) | Deconstruct a Point object packed into a long object to separate X and Y int values. |
| [offset(dx, dy)](#offset_dx_dy_6) | Translates this [Point](/imaging/python-net/aspose.imaging/point/) by the specified amount. |
| [offset(point)](#offset_point_7) | Translates this [Point](/imaging/python-net/aspose.imaging/point/) by the specified [Point](/imaging/python-net/aspose.imaging/point/). |
| [round(point)](#round_point_8) | Converts the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) to a [Point](/imaging/python-net/aspose.imaging/point/) object by rounding the [Point](/imaging/python-net/aspose.imaging/point/) values to the nearest integer. |
| [subtract(point, size)](#subtract_point_size_9) | Returns the result of subtracting specified [Size](/imaging/python-net/aspose.imaging/size/) from the specified [Point](/imaging/python-net/aspose.imaging/point/). |
| [to_long()](#to_long__10) | Convert this Point to a single long value, containing X and Y coordinates in high and low bits. |
| [truncate(point)](#truncate_point_11) | Converts the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) to a [Point](/imaging/python-net/aspose.imaging/point/) by truncating the values of the [Point](/imaging/python-net/aspose.imaging/point/). |


### Constructor: Point() {#Point__1}


```
 Point() 
```

Initializes a new instance of the Point class

### Constructor: Point(dw) {#Point_dw_2}


```
 Point(dw) 
```

Initializes a new instance of the [Point](/imaging/python-net/aspose.imaging/point/) structure using coordinates specified by an integer value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dw | int | A 32-bit integer that specifies the coordinates for the new point. |

### Constructor: Point(size) {#Point_size_3}


```
 Point(size) 
```

Initializes a new instance of the [Point](/imaging/python-net/aspose.imaging/point/) structure from the [Size](/imaging/python-net/aspose.imaging/size/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Contains the new point coordinates. |

### Constructor: Point(x, y) {#Point_x_y_4}


```
 Point(x, y) 
```

Initializes a new instance of the [Point](/imaging/python-net/aspose.imaging/point/) structure with the specified coordinates.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The horizontal position of the point. |
| y | int | The vertical position of the point. |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

Adds the specified [Size](/imaging/python-net/aspose.imaging/size/) to the specified [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | The [Point](/imaging/python-net/aspose.imaging/point/) to add to. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | The [Size](/imaging/python-net/aspose.imaging/size/) to add to the _point_. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | The [Point](/imaging/python-net/aspose.imaging/point/) that is the result of the addition operation. |


### Method: ceiling(point)  [static] {#ceiling_point_2}


```
 ceiling(point) 
```

Converts the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) to a [Point](/imaging/python-net/aspose.imaging/point/) by rounding the values of the [PointF](/imaging/python-net/aspose.imaging/pointf/) to the next higher integer values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) to convert. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | The [Point](/imaging/python-net/aspose.imaging/point/) this method converts to. |


### Method: create_from_d_word(dw)  [static] {#create_from_d_word_dw_3}


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
| [Point](/imaging/python-net/aspose.imaging/point/) |  |


### Method: create_from_size(size)  [static] {#create_from_size_size_4}


```
 create_from_size(size) 
```

Initializes a new instance of the [Point](/imaging/python-net/aspose.imaging/point/) structure from the [Size](/imaging/python-net/aspose.imaging/size/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Contains the new point coordinates. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) |  |


### Method: from_long(packed_point, x, y)  [static] {#from_long_packed_point_x_y_5}


```
 from_long(packed_point, x, y) 
```

Deconstruct a Point object packed into a long object to separate X and Y int values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| packed_point | int | The Point object packed into one long value. |
| x | int[] | The extracted from the packed Point X value. |
| y | int[] | The extracted from the packed Point Y value. |

### Method: offset(dx, dy) {#offset_dx_dy_6}


```
 offset(dx, dy) 
```

Translates this [Point](/imaging/python-net/aspose.imaging/point/) by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | int | The amount to offset the x-coordinate. |
| dy | int | The amount to offset the y-coordinate. |

### Method: offset(point) {#offset_point_7}


```
 offset(point) 
```

Translates this [Point](/imaging/python-net/aspose.imaging/point/) by the specified [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | The [Point](/imaging/python-net/aspose.imaging/point/) used to offset this [Point](/imaging/python-net/aspose.imaging/point/). |

### Method: round(point)  [static] {#round_point_8}


```
 round(point) 
```

Converts the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) to a [Point](/imaging/python-net/aspose.imaging/point/) object by rounding the [Point](/imaging/python-net/aspose.imaging/point/) values to the nearest integer.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) to convert. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | The [Point](/imaging/python-net/aspose.imaging/point/) this method converts to. |


### Method: subtract(point, size)  [static] {#subtract_point_size_9}


```
 subtract(point, size) 
```

Returns the result of subtracting specified [Size](/imaging/python-net/aspose.imaging/size/) from the specified [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | The [Point](/imaging/python-net/aspose.imaging/point/) to be subtracted from. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | The [Size](/imaging/python-net/aspose.imaging/size/) to subtract from the _point_. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | The [Point](/imaging/python-net/aspose.imaging/point/) that is the result of the subtraction operation. |


### Method: to_long() {#to_long__10}


```
 to_long() 
```

Convert this Point to a single long value, containing X and Y coordinates in high and low bits.

**Returns**

| Type | Description |
| :- | :- |
| int | The Point object packed into one long value. |


### Method: truncate(point)  [static] {#truncate_point_11}


```
 truncate(point) 
```

Converts the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) to a [Point](/imaging/python-net/aspose.imaging/point/) by truncating the values of the [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) to convert. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | The [Point](/imaging/python-net/aspose.imaging/point/) this method converts to. |


