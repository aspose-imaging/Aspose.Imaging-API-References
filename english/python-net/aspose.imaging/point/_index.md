---
title: Point Class
type: docs
weight: 680
url: /python-net/aspose.imaging/point/
---

Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

**Namespace:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Class Name:** aspose.imaging.Point

**Assembly:**  Aspose.Imaging Version: 23.5.6

The Point type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|Point(x, y)|Initializes a new instance of the Point class|
|Point(size)|Initializes a new instance of the Point class|
|Point(dw)|Initializes a new instance of the Point class|
|Point()|Initializes a new instance of the Point class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|empty|Gets a new instance of the [Point](/imaging/python-net/aspose.imaging/point/) structure that has [x](/imaging/python-net/aspose.imaging/point/) and [y](/imaging/python-net/aspose.imaging/point/) values set to zero.|
|is_empty|Gets a value indicating whether this [Point](/imaging/python-net/aspose.imaging/point/) is empty.|
|x|Gets or sets the x-coordinate of this [Point](/imaging/python-net/aspose.imaging/point/).|
|y|Gets or sets the y-coordinate of this [Point](/imaging/python-net/aspose.imaging/point/).|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|offset(point)|Translates this [Point](/imaging/python-net/aspose.imaging/point/) by the specified [Point](/imaging/python-net/aspose.imaging/point/).|
|offset(dx, dy)|Translates this [Point](/imaging/python-net/aspose.imaging/point/) by the specified [Point](/imaging/python-net/aspose.imaging/point/).|
|create_from_size(size)|Initializes a new instance of the [Point](/imaging/python-net/aspose.imaging/point/) structure from the [Size](/imaging/python-net/aspose.imaging/size/) structure.|
|create_from_d_word(dw)|Initializes a new instance of the [Point](/imaging/python-net/aspose.imaging/point/) structure using coordinates specified by an integer value.|
|add(point, size)|Adds the specified [Size](/imaging/python-net/aspose.imaging/size/) to the specified [Point](/imaging/python-net/aspose.imaging/point/).|
|subtract(point, size)|Returns the result of subtracting specified [Size](/imaging/python-net/aspose.imaging/size/) from the specified [Point](/imaging/python-net/aspose.imaging/point/).|
|ceiling(point)|Converts the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) to a [Point](/imaging/python-net/aspose.imaging/point/) by rounding the values of the [PointF](/imaging/python-net/aspose.imaging/pointf/) to the next higher integer values.|
|round(point)|Converts the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) to a [Point](/imaging/python-net/aspose.imaging/point/) object by rounding the [Point](/imaging/python-net/aspose.imaging/point/) values to the nearest integer.|
|truncate(point)|Converts the specified [PointF](/imaging/python-net/aspose.imaging/pointf/) to a [Point](/imaging/python-net/aspose.imaging/point/) by truncating the values of the [Point](/imaging/python-net/aspose.imaging/point/).|
|to_long()|Convert this Point to a single long value, containing X and Y coordinates in high and low bits.|
|from_long(packed_point, x, y)|Deconstruct a Point object packed into a long object to separate X and Y int values.|
