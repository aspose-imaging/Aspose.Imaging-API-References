---
title: RectangleF Class
type: docs
weight: 7130
url: /python-net/aspose.imaging/rectanglef/
---

**Summary:** Stores a set of four floating-point numbers that represent the location and size of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.RectangleF

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RectangleF()](#RectangleF__1) | Initializes a new instance of the RectangleF class |
| [RectangleF(location, size)](#RectangleF_location_size_2) | Initializes a new instance of the [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure with the specified location and size. |
| [RectangleF(x, y, width, height)](#RectangleF_x_y_width_height_3) | Initializes a new instance of the [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure with the specified location and size. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bottom | float | r/w | Gets or sets the y-coordinate that is the sum of [RectangleF.y](/imaging/python-net/aspose.imaging/rectanglef/) and [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) of this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| empty [static] | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Gets a new instance of the [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that has [RectangleF.x](/imaging/python-net/aspose.imaging/rectanglef/), [RectangleF.y](/imaging/python-net/aspose.imaging/rectanglef/), [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) and [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) values set to zero. |
| height | float | r/w | Gets or sets the height of this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| is_empty | bool | r | Gets a value indicating whether the [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) or [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) property of this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) has a value of zero. |
| left | float | r/w | Gets or sets the x-coordinate of the left edge of this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| location | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Gets or sets the coordinates of the upper-left corner of this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| right | float | r/w | Gets or sets the x-coordinate that is the sum of [RectangleF.x](/imaging/python-net/aspose.imaging/rectanglef/) and [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) of this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Gets or sets the size of this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| top | float | r/w | Gets or sets the y-coordinate of the top edge of this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| width | float | r/w | Gets or sets the width of this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| x | float | r/w | Gets or sets the x-coordinate of the upper-left corner of this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| y | float | r/w | Gets or sets the y-coordinate of the upper-left corner of this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [contains(point)](#contains_point_1) | Determines if the specified point is contained within this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [contains(rect)](#contains_rect_2) | Determines if the rectangular region represented by _rect_ is entirely contained within this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [contains(x, y)](#contains_x_y_3) | Determines if the specified point is contained within this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [contains_point_f(point)](#contains_point_f_point_4) | Determines if the specified point is contained within this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [contains_rect_f(rect)](#contains_rect_f_rect_5) | Determines if the rectangular region represented by _rect_ is entirely contained within this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_6) | Creates a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure with upper-left corner and lower-right corner at the specified locations. |
| [from_points(point1, point2)](#from_points_point1_point2_7) | Creates a new [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) from two points specified. Two verticles of the created [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) will be equal to the passed _point1_ and _point2_. These would be typically the opposite vertices. |
| [inflate(rect, x, y)](#inflate_rect_x_y_8) | Creates and returns an inflated copy of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. The copy is inflated by the specified amount. The original rectangle remains unmodified. |
| [inflate(size)](#inflate_size_9) | Inflates this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) by the specified amount. |
| [inflate(x, y)](#inflate_x_y_10) | Inflates this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure by the specified amount. |
| [inflate_rect(rect, x, y)](#inflate_rect_rect_x_y_11) | Creates and returns an inflated copy of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. The copy is inflated by the specified amount. The original rectangle remains unmodified. |
| [intersect(a, b)](#intersect_a_b_12) | Returns a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that represents the intersection of two rectangles. If there is no intersection, and empty [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) is returned. |
| [intersect(rect)](#intersect_rect_13) | Replaces this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure with the intersection of itself and the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [intersect_rects(a, b)](#intersect_rects_a_b_14) | Returns a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that represents the intersection of two rectangles. If there is no intersection, and empty [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) is returned. |
| [intersects_with(rect)](#intersects_with_rect_15) | Determines if this rectangle intersects with _rect_. |
| normalize() | Normalizes the rectangle by making it's width and height positive, left less than right and top less than bottom. |
| [offset(pos)](#offset_pos_16) | Adjusts the location of this rectangle by the specified amount. |
| [offset(x, y)](#offset_x_y_17) | Adjusts the location of this rectangle by the specified amount. |
| [union(a, b)](#union_a_b_18) | Creates the smallest possible third rectangle that can contain both of two rectangles that form a union. |


### Constructor: RectangleF() {#RectangleF__1}


```
 RectangleF() 
```

Initializes a new instance of the RectangleF class

### Constructor: RectangleF(location, size) {#RectangleF_location_size_2}


```
 RectangleF(location, size) 
```

Initializes a new instance of the [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure with the specified location and size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| location | [PointF](/imaging/python-net/aspose.imaging/pointf/) | A [PointF](/imaging/python-net/aspose.imaging/pointf/) that represents the upper-left corner of the rectangular region. |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | A [SizeF](/imaging/python-net/aspose.imaging/sizef/) that represents the width and height of the rectangular region. |

### Constructor: RectangleF(x, y, width, height) {#RectangleF_x_y_width_height_3}


```
 RectangleF(x, y, width, height) 
```

Initializes a new instance of the [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure with the specified location and size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the upper-left corner of the rectangle. |
| y | float | The y-coordinate of the upper-left corner of the rectangle. |
| width | float | The width of the rectangle. |
| height | float | The height of the rectangle. |

### Method: contains(point) {#contains_point_1}


```
 contains(point) 
```

Determines if the specified point is contained within this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the point represented by the _point_ parameter is contained within this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure; otherwise false. |


### Method: contains(rect) {#contains_rect_2}


```
 contains(rect) 
```

Determines if the rectangular region represented by _rect_ is entirely contained within this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the rectangular region represented by _rect_ is entirely contained within the rectangular region represented by this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); otherwise false. |


### Method: contains(x, y) {#contains_x_y_3}


```
 contains(x, y) 
```

Determines if the specified point is contained within this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the point defined by _x_ and _y_ is contained within this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure; otherwise false. |


### Method: contains_point_f(point) {#contains_point_f_point_4}


```
 contains_point_f(point) 
```

Determines if the specified point is contained within this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The [PointF](/imaging/python-net/aspose.imaging/pointf/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the point represented by the _point_ parameter is contained within this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure; otherwise false. |


### Method: contains_rect_f(rect) {#contains_rect_f_rect_5}


```
 contains_rect_f(rect) 
```

Determines if the rectangular region represented by _rect_ is entirely contained within this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the rectangular region represented by _rect_ is entirely contained within the rectangular region represented by this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); otherwise false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_6}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Creates a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure with upper-left corner and lower-right corner at the specified locations.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| left | float | The x-coordinate of the upper-left corner of the rectangular region. |
| top | float | The y-coordinate of the upper-left corner of the rectangular region. |
| right | float | The x-coordinate of the lower-right corner of the rectangular region. |
| bottom | float | The y-coordinate of the lower-right corner of the rectangular region. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The new [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) that this method creates. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_7}


```
 from_points(point1, point2) 
```

Creates a new [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) from two points specified. Two verticles of the created [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) will be equal to the passed _point1_ and _point2_. These would be typically the opposite vertices.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The first [Point](/imaging/python-net/aspose.imaging/point/) for the new rectangle. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The second [Point](/imaging/python-net/aspose.imaging/point/) for the new rectangle. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | A newly created [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_8}


```
 inflate(rect, x, y) 
```

Creates and returns an inflated copy of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. The copy is inflated by the specified amount. The original rectangle remains unmodified.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) to be copied. This rectangle is not modified. |
| x | float | The amount to inflate the copy of the rectangle horizontally. |
| y | float | The amount to inflate the copy of the rectangle vertically. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The inflated [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |


### Method: inflate(size) {#inflate_size_9}


```
 inflate(size) 
```

Inflates this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | The amount to inflate this rectangle. |

### Method: inflate(x, y) {#inflate_x_y_10}


```
 inflate(x, y) 
```

Inflates this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The amount to inflate this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure horizontally. |
| y | float | The amount to inflate this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure vertically. |

### Method: inflate_rect(rect, x, y)  [static] {#inflate_rect_rect_x_y_11}


```
 inflate_rect(rect, x, y) 
```

Creates and returns an inflated copy of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. The copy is inflated by the specified amount. The original rectangle remains unmodified.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) to be copied. This rectangle is not modified. |
| x | float | The amount to inflate the copy of the rectangle horizontally. |
| y | float | The amount to inflate the copy of the rectangle vertically. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The inflated [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |


### Method: intersect(a, b)  [static] {#intersect_a_b_12}


```
 intersect(a, b) 
```

Returns a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that represents the intersection of two rectangles. If there is no intersection, and empty [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) is returned.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | A first rectangle to intersect. |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | A second rectangle to intersect. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | A third [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure the size of which represents the overlapped area of the two specified rectangles. |


### Method: intersect(rect) {#intersect_rect_13}


```
 intersect(rect) 
```

Replaces this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure with the intersection of itself and the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The rectangle to intersect. |

### Method: intersect_rects(a, b)  [static] {#intersect_rects_a_b_14}


```
 intersect_rects(a, b) 
```

Returns a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that represents the intersection of two rectangles. If there is no intersection, and empty [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) is returned.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | A first rectangle to intersect. |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | A second rectangle to intersect. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | A third [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure the size of which represents the overlapped area of the two specified rectangles. |


### Method: intersects_with(rect) {#intersects_with_rect_15}


```
 intersects_with(rect) 
```

Determines if this rectangle intersects with _rect_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The rectangle to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if there is any intersection. |


### Method: offset(pos) {#offset_pos_16}


```
 offset(pos) 
```

Adjusts the location of this rectangle by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pos | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The amount to offset the location. |

### Method: offset(x, y) {#offset_x_y_17}


```
 offset(x, y) 
```

Adjusts the location of this rectangle by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The amount to offset the location horizontally. |
| y | float | The amount to offset the location vertically. |

### Method: union(a, b)  [static] {#union_a_b_18}


```
 union(a, b) 
```

Creates the smallest possible third rectangle that can contain both of two rectangles that form a union.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | A first rectangle to union. |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | A second rectangle to union. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | A third [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that contains both of the two rectangles that form the union. |


