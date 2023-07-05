---
title: GraphicsPath Class
type: docs
weight: 230
url: /python-net/aspose.imaging/graphicspath/
---

Represents a series of connected lines and curves. This class cannot be inherited.

**Namespace:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Class Name:** aspose.imaging.GraphicsPath

**Assembly:**  Aspose.Imaging Version: 23.6.0

The GraphicsPath type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|GraphicsPath()|Initializes a new instance of the [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) class.|
|GraphicsPath(figures)|Initializes a new instance of the GraphicsPath class|
|GraphicsPath(figures, fill_mode)|Initializes a new instance of the GraphicsPath class|
|GraphicsPath(fill_mode)|Initializes a new instance of the GraphicsPath class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|bounds|Gets or sets the object's bounds.|
|fill_mode|Gets or sets a [FillMode](/imaging/python-net/aspose.imaging/fillmode/) enumeration that determines how the interiors of shapes in this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) are filled.|
|figures|Gets the path figures.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|get_bounds(matrix)|Gets the object's bounds.|
|get_bounds(matrix, pen)|Gets the object's bounds.|
|is_visible(x, y)|Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).|
|is_visible(point)|Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).|
|is_visible(x, y)|Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).|
|is_visible(point)|Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).|
|is_visible(x, y, graphics)|Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).|
|is_visible(pt, graphics)|Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).|
|is_visible(x, y, graphics)|Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).|
|is_visible(pt, graphics)|Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).|
|is_outline_visible(x, y, pen)|Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/).|
|is_outline_visible(point, pen)|Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/).|
|is_outline_visible(x, y, pen, graphics)|Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/).|
|is_outline_visible(pt, pen, graphics)|Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/).|
|is_outline_visible(x, y, pen)|Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/).|
|is_outline_visible(point, pen)|Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/).|
|is_outline_visible(x, y, pen, graphics)|Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/).|
|is_outline_visible(pt, pen, graphics)|Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/).|
|flatten()|Converts each curve in this path into a sequence of connected line segments.|
|flatten(matrix)|Applies the specified transform and then converts each curve in this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) into a sequence of connected line segments.|
|flatten(matrix, flatness)|Converts each curve in this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) into a sequence of connected line segments.|
|widen(pen)|Adds an additional outline to the path.|
|widen(pen, matrix)|Adds an additional outline to the [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).|
|widen(pen, matrix, flatness)|Replaces this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) with curves that enclose the area that is filled when this path is drawn by the specified pen.|
|warp(dest_points, src_rect)|Applies a warp transform, defined by a rectangle and a parallelogram, to this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).|
|warp(dest_points, src_rect, matrix)|Applies a warp transform, defined by a rectangle and a parallelogram, to this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).|
|warp(dest_points, src_rect, matrix, warp_mode)|Applies a warp transform, defined by a rectangle and a parallelogram, to this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).|
|warp(dest_points, src_rect, matrix, warp_mode, flatness)|Applies a warp transform, defined by a rectangle and a parallelogram, to this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).|
|add_path(adding_path)|Appends the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to this path.|
|add_path(adding_path, connect)|Appends the specified [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to this path.|
|transform(transform)|Applies the specified transformation to the shape.|
|reset()|Empties the graphics path and sets the [FillMode](/imaging/python-net/aspose.imaging/fillmode/) to [ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).|
|reverse()|Reverses the order of figures, shapes, and points in each shape of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).|
|is_visible_xyf(x, y)|Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).|
|is_visible_point_f(point)|Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).|
|is_visible_xy(x, y)|Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).|
|is_visible_point(point)|Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).|
|is_visible_xyf_graphics(x, y, graphics)|Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) in the visible clip region of the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).|
|is_visible_point_f_graphics(pt, graphics)|Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).|
|is_visible_xy_graphics(x, y, graphics)|Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).|
|is_visible_point_graphics(pt, graphics)|Indicates whether the specified point is contained within this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).|
|is_outline_visible_xyf(x, y, pen)|Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/).|
|is_outline_visible_point_f(point, pen)|Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/).|
|is_outline_visible_xyf_graphics(x, y, pen, graphics)|Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/) and using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).|
|is_outline_visible_point_f_graphics(pt, pen, graphics)|Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/) and using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).|
|is_outline_visible_xy(x, y, pen)|Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/).|
|is_outline_visible_point(point, pen)|Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/).|
|is_outline_visible_xy_graphics(x, y, pen, graphics)|Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/) and using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).|
|is_outline_visible_point_graphics(pt, pen, graphics)|Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) when drawn with the specified [Pen](/imaging/python-net/aspose.imaging/pen/) and using the specified [Graphics](/imaging/python-net/aspose.imaging/graphics/).|
|add_figure(figure)|Adds a new figure.|
|add_figures(figures)|Adds new figures.|
|remove_figure(figure)|Removes a figure.|
|remove_figures(figures)|Removes figures.|
|deep_clone()|Performs a deep clone of this graphics path.|
