---
title: Rectangle Class
type: docs
weight: 6910
url: /python-net/aspose.imaging/rectangle/
---

Stores a set of four integers that represent the location and size of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Rectangle

**Aspose.Imaging Version:** 23.6

The Rectangle type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [Rectangle(x, y, width, height)](#Rectangle_x_y_width_height_0) | Initializes a new instance of the [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure with the specified location and size. |
| [Rectangle(location, size)](#Rectangle_location_size_1) | Initializes a new instance of the [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure with the specified location and size. |
| [Rectangle()](#Rectangle__2) | Initializes a new instance of the Rectangle class |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| empty [static] | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | r | Gets a new instance of the [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that has [x](/imaging/python-net/aspose.imaging/rectangle/), [y](/imaging/python-net/aspose.imaging/rectangle/), [width](/imaging/python-net/aspose.imaging/rectangle/) and [height](/imaging/python-net/aspose.imaging/rectangle/) values set to zero. |
| location | [Point](/imaging/python-net/aspose.imaging/point) | r/w | Gets or sets the coordinates of the upper-left corner of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| size | [Size](/imaging/python-net/aspose.imaging/size) | r/w | Gets or sets the size of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| x | int | r/w | Gets or sets the x-coordinate of the upper-left corner of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| y | int | r/w | Gets or sets the y-coordinate of the upper-left corner of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| width | int | r/w | Gets or sets the width of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| height | int | r/w | Gets or sets the height of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| left | int | r/w | Gets or sets the x-coordinate of the left edge of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| top | int | r/w | Gets or sets the y-coordinate of the top edge of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| right | int | r/w | Gets or sets the x-coordinate that is the sum of [x](/imaging/python-net/aspose.imaging/rectangle/) and [width](/imaging/python-net/aspose.imaging/rectangle/) property values of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| bottom | int | r/w | Gets or sets the y-coordinate that is the sum of the [y](/imaging/python-net/aspose.imaging/rectangle/) and [height](/imaging/python-net/aspose.imaging/rectangle/) property values of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| is_empty | bool | r | Gets a value indicating whether all numeric properties of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) have values of zero. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [inflate(rect, x, y)](#inflate_rect_x_y_3) | Creates and returns an inflated copy of the specified [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. The copy is inflated by the specified amount. The original [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure remains unmodified. |
| [inflate(width, height)](#inflate_width_height_4) | Inflates this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) by the specified amount. |
| [inflate(size)](#inflate_size_5) | Inflates this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) by the specified amount. |
| [intersect(a, b)](#intersect_a_b_6) | Returns a third [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that represents the intersection of two other [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structures. If there is no intersection, an empty [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) is returned. |
| [intersect(rect)](#intersect_rect_7) | Replaces this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) with the intersection of itself and the specified [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [contains(x, y)](#contains_x_y_8) | Determines if the specified point is contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| [contains(point)](#contains_point_9) | Determines if the specified point is contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| [contains(rect)](#contains_rect_10) | Determines if the rectangular region represented by <paramref name="rect" /> is entirely contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| [offset(pos)](#offset_pos_11) | Adjusts the location of this rectangle by the specified amount. |
| [offset(x, y)](#offset_x_y_12) | Adjusts the location of this rectangle by the specified amount. |
| [from_points(point1, point2)](#from_points_point1_point2_13) | Creates a new [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) from two points specified. Two verticales of the created [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) will be equal to the passed <paramref name="point1" /> and <paramref name="point2" />. These would be typically the opposite vertices. |
| [ceiling(value)](#ceiling_value_14) | Converts the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure by rounding the [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) values to the next higher integer values. |
| [truncate(value)](#truncate_value_15) | Converts the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) to a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) by truncating the [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) values. |
| [round(value)](#round_value_16) | Converts the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) to a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) by rounding the [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) values to the nearest integer values. |
| [inflate_rect(rect, x, y)](#inflate_rect_rect_x_y_17) | Creates and returns an inflated copy of the specified [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. The copy is inflated by the specified amount. The original [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure remains unmodified. |
| [intersect_rects(a, b)](#intersect_rects_a_b_18) | Returns a third [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that represents the intersection of two other [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structures. If there is no intersection, an empty [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) is returned. |
| [union(a, b)](#union_a_b_19) | Gets a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that contains the union of two [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structures. |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_20) | Creates a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure with the specified edge locations. |
| [contains_point(point)](#contains_point_point_21) | Determines if the specified point is contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| [contains_rect(rect)](#contains_rect_rect_22) | Determines if the rectangular region represented by <paramref name="rect" /> is entirely contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| [intersects_with(rect)](#intersects_with_rect_23) | Determines if this rectangle intersects with <paramref name="rect" />. |
| normalize() | Normalizes the rectangle by making it's width and height positive, left less than right and top less than bottom. |

### Rectangle(x, y, width, height) {#Rectangle_x_y_width_height_0}


```
 Rectangle(x, y, width, height) 
```

Initializes a new instance of the [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure with the specified location and size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the upper-left corner of the rectangle. |
| y | int | The y-coordinate of the upper-left corner of the rectangle. |
| width | int | The width of the rectangle. |
| height | int | The height of the rectangle. |

### Rectangle(location, size) {#Rectangle_location_size_1}


```
 Rectangle(location, size) 
```

Initializes a new instance of the [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure with the specified location and size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| location | [Point](/imaging/python-net/aspose.imaging/point) | A [Point](/imaging/python-net/aspose.imaging/point/) that represents the upper-left corner of the rectangular region. |
| size | [Size](/imaging/python-net/aspose.imaging/size) | A [Size](/imaging/python-net/aspose.imaging/size/) that represents the width and height of the rectangular region. |

### Rectangle() {#Rectangle__2}


```
 Rectangle() 
```

Initializes a new instance of the Rectangle class

### inflate(rect, x, y)  [static] {#inflate_rect_x_y_3}


```
 inflate(rect, x, y) 
```

Creates and returns an inflated copy of the specified [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. The copy is inflated by the specified amount. The original [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure remains unmodified.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) with which to start. This rectangle is not modified. |
| x | int | The amount to inflate this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) horizontally. |
| y | int | The amount to inflate this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) vertically. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The inflated [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### inflate(width, height) {#inflate_width_height_4}


```
 inflate(width, height) 
```

Inflates this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| width | int | The amount to inflate this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) horizontally. |
| height | int | The amount to inflate this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) vertically. |

### inflate(size) {#inflate_size_5}


```
 inflate(size) 
```

Inflates this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size) | The amount to inflate this rectangle. |

### intersect(a, b)  [static] {#intersect_a_b_6}


```
 intersect(a, b) 
```

Returns a third [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that represents the intersection of two other [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structures. If there is no intersection, an empty [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) is returned.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | A first rectangle to intersect. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | A second rectangle to intersect. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | A [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) that represents the intersection of <paramref name="a" /> and <paramref name="b" />. |


### intersect(rect) {#intersect_rect_7}


```
 intersect(rect) 
```

Replaces this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) with the intersection of itself and the specified [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) with which to intersect. |

### contains(x, y) {#contains_x_y_8}


```
 contains(x, y) 
```

Determines if the specified point is contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the point defined by <paramref name="x" /> and <paramref name="y" /> is contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure; otherwise false. |


### contains(point) {#contains_point_9}


```
 contains(point) 
```

Determines if the specified point is contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point) | The [Point](/imaging/python-net/aspose.imaging/point/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the point represented by <paramref name="point" /> is contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure; otherwise false. |


### contains(rect) {#contains_rect_10}


```
 contains(rect) 
```

Determines if the rectangular region represented by <paramref name="rect" /> is entirely contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the rectangular region represented by <paramref name="rect" /> is entirely contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure; otherwise false. |


### offset(pos) {#offset_pos_11}


```
 offset(pos) 
```

Adjusts the location of this rectangle by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pos | [Point](/imaging/python-net/aspose.imaging/point) | Amount to offset the location. |

### offset(x, y) {#offset_x_y_12}


```
 offset(x, y) 
```

Adjusts the location of this rectangle by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The horizontal offset. |
| y | int | The vertical offset. |

### from_points(point1, point2)  [static] {#from_points_point1_point2_13}


```
 from_points(point1, point2) 
```

Creates a new [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) from two points specified. Two verticales of the created [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) will be equal to the passed <paramref name="point1" /> and <paramref name="point2" />. These would be typically the opposite vertices.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point) | The first [Point](/imaging/python-net/aspose.imaging/point/) for the new rectangle. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point) | The second [Point](/imaging/python-net/aspose.imaging/point/) for the new rectangle. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | A newly created [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### ceiling(value)  [static] {#ceiling_value_14}


```
 ceiling(value) 
```

Converts the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure by rounding the [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) values to the next higher integer values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to be converted. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | Returns a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### truncate(value)  [static] {#truncate_value_15}


```
 truncate(value) 
```

Converts the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) to a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) by truncating the [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) to be converted. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | A new [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### round(value)  [static] {#round_value_16}


```
 round(value) 
```

Converts the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) to a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) by rounding the [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) values to the nearest integer values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) to be converted. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | A new [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### inflate_rect(rect, x, y)  [static] {#inflate_rect_rect_x_y_17}


```
 inflate_rect(rect, x, y) 
```

Creates and returns an inflated copy of the specified [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. The copy is inflated by the specified amount. The original [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure remains unmodified.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) with which to start. This rectangle is not modified. |
| x | int | The amount to inflate this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) horizontally. |
| y | int | The amount to inflate this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) vertically. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The inflated [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### intersect_rects(a, b)  [static] {#intersect_rects_a_b_18}


```
 intersect_rects(a, b) 
```

Returns a third [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that represents the intersection of two other [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structures. If there is no intersection, an empty [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) is returned.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | A first rectangle to intersect. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | A second rectangle to intersect. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | A [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) that represents the intersection of <paramref name="a" /> and <paramref name="b" />. |


### union(a, b)  [static] {#union_a_b_19}


```
 union(a, b) 
```

Gets a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that contains the union of two [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | A first rectangle to union. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | A second rectangle to union. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | A [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that bounds the union of the two [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structures. |


### from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_20}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Creates a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure with the specified edge locations.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| left | int | The x-coordinate of the upper-left corner of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| top | int | The y-coordinate of the upper-left corner of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| right | int | The x-coordinate of the lower-right corner of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| bottom | int | The y-coordinate of the lower-right corner of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The new [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) that this method creates. |


### contains_point(point) {#contains_point_point_21}


```
 contains_point(point) 
```

Determines if the specified point is contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point) | The [Point](/imaging/python-net/aspose.imaging/point/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the point represented by <paramref name="point" /> is contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure; otherwise false. |


### contains_rect(rect) {#contains_rect_rect_22}


```
 contains_rect(rect) 
```

Determines if the rectangular region represented by <paramref name="rect" /> is entirely contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the rectangular region represented by <paramref name="rect" /> is entirely contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure; otherwise false. |


### intersects_with(rect) {#intersects_with_rect_23}


```
 intersects_with(rect) 
```

Determines if this rectangle intersects with <paramref name="rect" />.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if there is any intersection, otherwise false. |


