---
title: RectangleF Class
type: docs
weight: 750
url: /python-net/aspose.imaging/rectanglef/
---

Stores a set of four floating-point numbers that represent the location and size of a rectangle.

**Namespace:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Class Name:** aspose.imaging.RectangleF

**Assembly:**  Aspose.Imaging Version: 23.6.0

The RectangleF type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|RectangleF(x, y, width, height)|Initializes a new instance of the RectangleF class|
|RectangleF(location, size)|Initializes a new instance of the RectangleF class|
|RectangleF()|Initializes a new instance of the RectangleF class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|empty|Gets a new instance of the [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that has [x](/imaging/python-net/aspose.imaging/rectanglef/), [y](/imaging/python-net/aspose.imaging/rectanglef/), [width](/imaging/python-net/aspose.imaging/rectanglef/) and [height](/imaging/python-net/aspose.imaging/rectanglef/) values set to zero.|
|location|Gets or sets the coordinates of the upper-left corner of this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.|
|size|Gets or sets the size of this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).|
|x|Gets or sets the x-coordinate of the upper-left corner of this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.|
|y|Gets or sets the y-coordinate of the upper-left corner of this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.|
|width|Gets or sets the width of this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.|
|height|Gets or sets the height of this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.|
|left|Gets or sets the x-coordinate of the left edge of this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.|
|top|Gets or sets the y-coordinate of the top edge of this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.|
|right|Gets or sets the x-coordinate that is the sum of [x](/imaging/python-net/aspose.imaging/rectanglef/) and [width](/imaging/python-net/aspose.imaging/rectanglef/) of this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.|
|bottom|Gets or sets the y-coordinate that is the sum of [y](/imaging/python-net/aspose.imaging/rectanglef/) and [height](/imaging/python-net/aspose.imaging/rectanglef/) of this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.|
|is_empty|Gets a value indicating whether the [width](/imaging/python-net/aspose.imaging/rectanglef/) or [height](/imaging/python-net/aspose.imaging/rectanglef/) property of this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) has a value of zero.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|inflate(rect, x, y)|Creates and returns an inflated copy of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. The copy is inflated by the specified amount. The original rectangle remains unmodified.|
|inflate(x, y)|Creates and returns an inflated copy of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. The copy is inflated by the specified amount. The original rectangle remains unmodified.|
|inflate(size)|Inflates this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) by the specified amount.|
|intersect(a, b)|Returns a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that represents the intersection of two rectangles. If there is no intersection, and empty [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) is returned.|
|intersect(rect)|Returns a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that represents the intersection of two rectangles. If there is no intersection, and empty [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) is returned.|
|contains(x, y)|Determines if the specified point is contained within this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.|
|contains(point)|Determines if the specified point is contained within this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.|
|contains(rect)|Determines if the specified point is contained within this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.|
|offset(pos)|Adjusts the location of this rectangle by the specified amount.|
|offset(x, y)|Adjusts the location of this rectangle by the specified amount.|
|from_points(point1, point2)|Creates a new [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) from two points specified. Two verticles of the created [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) will be equal to the passed|
|inflate_rect(rect, x, y)|Creates and returns an inflated copy of the specified [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. The copy is inflated by the specified amount. The original rectangle remains unmodified.|
|intersect_rects(a, b)|Returns a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that represents the intersection of two rectangles. If there is no intersection, and empty [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) is returned.|
|union(a, b)|Creates the smallest possible third rectangle that can contain both of two rectangles that form a union.|
|from_left_top_right_bottom(left, top, right, bottom)|Creates a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure with upper-left corner and lower-right corner at the specified locations.|
|normalize()|Normalizes the rectangle by making it's width and height positive, left less than right and top less than bottom.|
|contains_point_f(point)|Determines if the specified point is contained within this [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.|
|contains_rect_f(rect)|Determines if the rectangular region represented by|
|intersects_with(rect)|Determines if this rectangle intersects with|
