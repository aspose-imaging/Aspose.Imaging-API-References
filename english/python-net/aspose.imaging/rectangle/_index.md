---
title: Rectangle Class
type: docs
weight: 740
url: /python-net/aspose.imaging/rectangle/
---

Stores a set of four integers that represent the location and size of a rectangle.

**Namespace:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Class Name:** aspose.imaging.Rectangle

**Assembly:**  Aspose.Imaging Version: 23.5.0

The Rectangle type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|Rectangle(x, y, width, height)|Initializes a new instance of the Rectangle class|
|Rectangle(location, size)|Initializes a new instance of the Rectangle class|
|Rectangle()|Initializes a new instance of the Rectangle class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|empty|Gets a new instance of the [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that has [x](/imaging/python-net/aspose.imaging/rectangle/), [y](/imaging/python-net/aspose.imaging/rectangle/), [width](/imaging/python-net/aspose.imaging/rectangle/) and [height](/imaging/python-net/aspose.imaging/rectangle/) values set to zero.|
|location|Gets or sets the coordinates of the upper-left corner of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure.|
|size|Gets or sets the size of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).|
|x|Gets or sets the x-coordinate of the upper-left corner of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure.|
|y|Gets or sets the y-coordinate of the upper-left corner of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure.|
|width|Gets or sets the width of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure.|
|height|Gets or sets the height of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure.|
|left|Gets or sets the x-coordinate of the left edge of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure.|
|top|Gets or sets the y-coordinate of the top edge of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure.|
|right|Gets or sets the x-coordinate that is the sum of [x](/imaging/python-net/aspose.imaging/rectangle/) and [width](/imaging/python-net/aspose.imaging/rectangle/) property values of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure.|
|bottom|Gets or sets the y-coordinate that is the sum of the [y](/imaging/python-net/aspose.imaging/rectangle/) and [height](/imaging/python-net/aspose.imaging/rectangle/) property values of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure.|
|is_empty|Gets a value indicating whether all numeric properties of this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) have values of zero.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|inflate(rect, x, y)|Creates and returns an inflated copy of the specified [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. The copy is inflated by the specified amount. The original [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure remains unmodified.|
|inflate(width, height)|Creates and returns an inflated copy of the specified [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. The copy is inflated by the specified amount. The original [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure remains unmodified.|
|inflate(size)|Inflates this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) by the specified amount.|
|intersect(a, b)|Returns a third [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that represents the intersection of two other [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structures. If there is no intersection, an empty [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) is returned.|
|intersect(rect)|Returns a third [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that represents the intersection of two other [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structures. If there is no intersection, an empty [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) is returned.|
|contains(x, y)|Determines if the specified point is contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure.|
|contains(point)|Determines if the specified point is contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure.|
|contains(rect)|Determines if the specified point is contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure.|
|offset(pos)|Adjusts the location of this rectangle by the specified amount.|
|offset(x, y)|Adjusts the location of this rectangle by the specified amount.|
|from_points(point1, point2)|Creates a new [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) from two points specified. Two verticales of the created [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) will be equal to the passed|
|ceiling(value)|Converts the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure to a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure by rounding the [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) values to the next higher integer values.|
|truncate(value)|Converts the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) to a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) by truncating the [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) values.|
|round(value)|Converts the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) to a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) by rounding the [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) values to the nearest integer values.|
|inflate_rect(rect, x, y)|Creates and returns an inflated copy of the specified [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. The copy is inflated by the specified amount. The original [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure remains unmodified.|
|intersect_rects(a, b)|Returns a third [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that represents the intersection of two other [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structures. If there is no intersection, an empty [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) is returned.|
|union(a, b)|Gets a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that contains the union of two [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structures.|
|from_left_top_right_bottom(left, top, right, bottom)|Creates a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure with the specified edge locations.|
|contains_point(point)|Determines if the specified point is contained within this [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure.|
|contains_rect(rect)|Determines if the rectangular region represented by|
|intersects_with(rect)|Determines if this rectangle intersects with|
|normalize()|Normalizes the rectangle by making it's width and height positive, left less than right and top less than bottom.|
