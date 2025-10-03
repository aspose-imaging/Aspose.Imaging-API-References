---
title: Rectangle Class
type: docs
weight: 7060
url: /python-net/aspose.imaging/rectangle/
---

**Summary:** Stores a set of four integers that represent the location and size of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Rectangle

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Rectangle()](#Rectangle__1) | Initializes a new instance of the Rectangle class |
| [Rectangle(location, size)](#Rectangle_location_size_2) | Initializes a new instance of the [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure with the specified location and size. |
| [Rectangle(x, y, width, height)](#Rectangle_x_y_width_height_3) | Initializes a new instance of the [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure with the specified location and size. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bottom | int | r/w | Gets or sets the y-coordinate that is the sum of the [Rectangle.y](/imaging/python-net/aspose.imaging/rectangle/) and [Rectangle.height](/imaging/python-net/aspose.imaging/rectangle/) property values of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| empty [static] | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Gets a new instance of the [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that has [Rectangle.x](/imaging/python-net/aspose.imaging/rectangle/), [Rectangle.y](/imaging/python-net/aspose.imaging/rectangle/), [Rectangle.width](/imaging/python-net/aspose.imaging/rectangle/) and [Rectangle.height](/imaging/python-net/aspose.imaging/rectangle/) values set to zero. |
| height | int | r/w | Gets or sets the height of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| is_empty | bool | r | Gets a value indicating whether all numeric properties of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) have values of zero. |
| left | int | r/w | Gets or sets the x-coordinate of the left edge of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Gets or sets the coordinates of the upper-left corner of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| right | int | r/w | Gets or sets the x-coordinate that is the sum of [Rectangle.x](/imaging/python-net/aspose.imaging/rectangle/) and [Rectangle.width](/imaging/python-net/aspose.imaging/rectangle/) property values of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Gets or sets the size of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| top | int | r/w | Gets or sets the y-coordinate of the top edge of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| width | int | r/w | Gets or sets the width of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| x | int | r/w | Gets or sets the x-coordinate of the upper-left corner of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| y | int | r/w | Gets or sets the y-coordinate of the upper-left corner of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [ceiling(value)](#ceiling_value_1) | Converts the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure by rounding the [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) values to the next higher integer values. |
| [contains(point)](#contains_point_2) | Determines if the specified point is contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| [contains(rect)](#contains_rect_3) | Determines if the rectangular region represented by _rect_ is entirely contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| [contains(x, y)](#contains_x_y_4) | Determines if the specified point is contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| [contains_point(point)](#contains_point_point_5) | Determines if the specified point is contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| [contains_rect(rect)](#contains_rect_rect_6) | Determines if the rectangular region represented by _rect_ is entirely contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_7) | Creates a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure with the specified edge locations. |
| [from_points(point1, point2)](#from_points_point1_point2_8) | Creates a new [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) from two points specified. Two verticales of the created [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) will be equal to the passed _point1_ and _point2_. These would be typically the opposite vertices. |
| [inflate(rect, x, y)](#inflate_rect_x_y_9) | Creates and returns an inflated copy of the specified [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. The copy is inflated by the specified amount. The original [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure remains unmodified. |
| [inflate(size)](#inflate_size_10) | Inflates this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) by the specified amount. |
| [inflate(width, height)](#inflate_width_height_11) | Inflates this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) by the specified amount. |
| [inflate_rect(rect, x, y)](#inflate_rect_rect_x_y_12) | Creates and returns an inflated copy of the specified [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. The copy is inflated by the specified amount. The original [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure remains unmodified. |
| [intersect(a, b)](#intersect_a_b_13) | Returns a third [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that represents the intersection of two other [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structures. If there is no intersection, an empty [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) is returned. |
| [intersect(rect)](#intersect_rect_14) | Replaces this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) with the intersection of itself and the specified [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [intersect_rects(a, b)](#intersect_rects_a_b_15) | Returns a third [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that represents the intersection of two other [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structures. If there is no intersection, an empty [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) is returned. |
| [intersects_with(rect)](#intersects_with_rect_16) | Determines if this rectangle intersects with _rect_. |
| normalize() | Normalizes the rectangle by making it's width and height positive, left less than right and top less than bottom. |
| [offset(pos)](#offset_pos_17) | Adjusts the location of this rectangle by the specified amount. |
| [offset(x, y)](#offset_x_y_18) | Adjusts the location of this rectangle by the specified amount. |
| [round(value)](#round_value_19) | Converts the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) to a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) by rounding the [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) values to the nearest integer values. |
| [truncate(value)](#truncate_value_20) | Converts the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) to a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) by truncating the [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) values. |
| [union(a, b)](#union_a_b_21) | Gets a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that contains the union of two [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structures. |


### Constructor: Rectangle() {#Rectangle__1}


```
 Rectangle() 
```

Initializes a new instance of the Rectangle class

### Constructor: Rectangle(location, size) {#Rectangle_location_size_2}


```
 Rectangle(location, size) 
```

Initializes a new instance of the [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure with the specified location and size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | A [Point](/imaging/python-net/aspose.imaging/point/) that represents the upper-left corner of the rectangular region. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | A [Size](/imaging/python-net/aspose.imaging/size/) that represents the width and height of the rectangular region. |

### Constructor: Rectangle(x, y, width, height) {#Rectangle_x_y_width_height_3}


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

### Method: ceiling(value)  [static] {#ceiling_value_1}


```
 ceiling(value) 
```

Converts the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure by rounding the [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) values to the next higher integer values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to be converted. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Returns a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: contains(point) {#contains_point_2}


```
 contains(point) 
```

Determines if the specified point is contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | The [Point](/imaging/python-net/aspose.imaging/point/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the point represented by _point_ is contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure; otherwise false. |


### Method: contains(rect) {#contains_rect_3}


```
 contains(rect) 
```

Determines if the rectangular region represented by _rect_ is entirely contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the rectangular region represented by _rect_ is entirely contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure; otherwise false. |


### Method: contains(x, y) {#contains_x_y_4}


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
| bool | This method returns true if the point defined by _x_ and _y_ is contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure; otherwise false. |


### Method: contains_point(point) {#contains_point_point_5}


```
 contains_point(point) 
```

Determines if the specified point is contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | The [Point](/imaging/python-net/aspose.imaging/point/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the point represented by _point_ is contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure; otherwise false. |


### Method: contains_rect(rect) {#contains_rect_rect_6}


```
 contains_rect(rect) 
```

Determines if the rectangular region represented by _rect_ is entirely contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the rectangular region represented by _rect_ is entirely contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure; otherwise false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_7}


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
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The new [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) that this method creates. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_8}


```
 from_points(point1, point2) 
```

Creates a new [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) from two points specified. Two verticales of the created [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) will be equal to the passed _point1_ and _point2_. These would be typically the opposite vertices.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | The first [Point](/imaging/python-net/aspose.imaging/point/) for the new rectangle. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | The second [Point](/imaging/python-net/aspose.imaging/point/) for the new rectangle. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | A newly created [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_9}


```
 inflate(rect, x, y) 
```

Creates and returns an inflated copy of the specified [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. The copy is inflated by the specified amount. The original [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure remains unmodified.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) with which to start. This rectangle is not modified. |
| x | int | The amount to inflate this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) horizontally. |
| y | int | The amount to inflate this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) vertically. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The inflated [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: inflate(size) {#inflate_size_10}


```
 inflate(size) 
```

Inflates this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | The amount to inflate this rectangle. |

### Method: inflate(width, height) {#inflate_width_height_11}


```
 inflate(width, height) 
```

Inflates this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| width | int | The amount to inflate this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) horizontally. |
| height | int | The amount to inflate this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) vertically. |

### Method: inflate_rect(rect, x, y)  [static] {#inflate_rect_rect_x_y_12}


```
 inflate_rect(rect, x, y) 
```

Creates and returns an inflated copy of the specified [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. The copy is inflated by the specified amount. The original [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure remains unmodified.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) with which to start. This rectangle is not modified. |
| x | int | The amount to inflate this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) horizontally. |
| y | int | The amount to inflate this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) vertically. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The inflated [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: intersect(a, b)  [static] {#intersect_a_b_13}


```
 intersect(a, b) 
```

Returns a third [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that represents the intersection of two other [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structures. If there is no intersection, an empty [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) is returned.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | A first rectangle to intersect. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | A second rectangle to intersect. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | A [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) that represents the intersection of _a_ and _b_. |


### Method: intersect(rect) {#intersect_rect_14}


```
 intersect(rect) 
```

Replaces this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) with the intersection of itself and the specified [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) with which to intersect. |

### Method: intersect_rects(a, b)  [static] {#intersect_rects_a_b_15}


```
 intersect_rects(a, b) 
```

Returns a third [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that represents the intersection of two other [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structures. If there is no intersection, an empty [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) is returned.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | A first rectangle to intersect. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | A second rectangle to intersect. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | A [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) that represents the intersection of _a_ and _b_. |


### Method: intersects_with(rect) {#intersects_with_rect_16}


```
 intersects_with(rect) 
```

Determines if this rectangle intersects with _rect_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if there is any intersection, otherwise false. |


### Method: offset(pos) {#offset_pos_17}


```
 offset(pos) 
```

Adjusts the location of this rectangle by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pos | [Point](/imaging/python-net/aspose.imaging/point/) | Amount to offset the location. |

### Method: offset(x, y) {#offset_x_y_18}


```
 offset(x, y) 
```

Adjusts the location of this rectangle by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The horizontal offset. |
| y | int | The vertical offset. |

### Method: round(value)  [static] {#round_value_19}


```
 round(value) 
```

Converts the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) to a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) by rounding the [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) values to the nearest integer values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) to be converted. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | A new [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: truncate(value)  [static] {#truncate_value_20}


```
 truncate(value) 
```

Converts the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) to a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) by truncating the [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) to be converted. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | A new [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: union(a, b)  [static] {#union_a_b_21}


```
 union(a, b) 
```

Gets a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that contains the union of two [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | A first rectangle to union. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | A second rectangle to union. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | A [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that bounds the union of the two [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structures. |


