---
title: Figure Class
type: docs
weight: 180
url: /python-net/aspose.imaging/figure/
---

The figure. A container for shapes.

**Namespace:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Class Name:** aspose.imaging.Figure

**Assembly:**  Aspose.Imaging Version: 23.6.0

The Figure type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|Figure()|Initializes a new [Figure](/imaging/python-net/aspose.imaging/figure/) instance.<br/>            A constructor required for a JSON deserialization.|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|bounds|Gets or sets the object's bounds.|
|shapes|Gets or sets the figure shapes.|
|is_closed|Gets or sets a value indicating whether this figure is closed. A closed figure will make a difference only in case where<br/>            the first and the last figure's shapes are continuous shapes. In such case the first point of the first shape will be<br/>            connected by a straight line from the last point of the last shape.|
|segments|Gets the whole figure segments.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|get_bounds(matrix)|Gets the object's bounds.|
|get_bounds(matrix, pen)|Gets the object's bounds.|
|transform(transform)|Applies the specified transformation to the shape.|
|add_shape(shape)|Adds a shape to the figure.|
|add_shapes(shapes)|Adds a range of shapes to the figure.|
|remove_shape(shape)|Removes a shape from the figure.|
|remove_shapes(shapes)|Removes a range of shapes from the figure.|
|reverse()|Reverses this figure shapes order and shapes point order.|
