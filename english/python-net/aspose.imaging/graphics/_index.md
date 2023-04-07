---
title: Graphics Class
type: docs
weight: 220
url: /python-net/api-reference/aspose.imaging/graphics/
---

Represents the graphics according to the graphics engine used in the current assembly.

**Namespace:** [aspose.imaging](/imaging/python-net/api-reference/aspose.imaging/)

**Full Class Name:** aspose.imaging.Graphics

**Assembly:**  Aspose.Imaging Version: 23.3.0

The Graphics type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|Graphics(source_image)|Initializes a new instance of the Graphics class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|dpi_x|Gets the horizontal resolution of this Aspose.Imaging.Graphics.|
|dpi_y|Gets the vertical resolution of this Aspose.Imaging.Graphics.|
|page_unit|Gets or sets the unit of measure used for page coordinates in this Aspose.Imaging.Graphics.|
|page_scale|Gets or sets the scaling between world units and page units for this Aspose.Imaging.Graphics.|
|clip|Gets or sets the clip region.|
|transform|Gets or sets a copy of the geometric world transformation for this [Graphics](/imaging/python-net/api-reference/aspose.imaging/graphics/).|
|is_in_begin_update_call|Gets a value indicating whether graphics is in BeginUpdate call state.|
|image|Gets the image.|
|compositing_quality|Gets or sets the compositing quality.|
|interpolation_mode|Gets or sets the interpolation mode.|
|smoothing_mode|Gets or sets the smoothing mode.|
|text_rendering_hint|Gets or sets the text rendering hint.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|multiply_transform(matrix)|Multiplies the [Matrix](/imaging/python-net/api-reference/aspose.imaging/matrix/) that represents the local geometric transform of this [Graphics](/imaging/python-net/api-reference/aspose.imaging/graphics/) by the specified [Matrix](/imaging/python-net/api-reference/aspose.imaging/matrix/) by prepending the specified [Matrix](/imaging/python-net/api-reference/aspose.imaging/matrix/).|
|multiply_transform(matrix, order)|Multiplies the [Matrix](/imaging/python-net/api-reference/aspose.imaging/matrix/) that represents the local geometric transform of this [Graphics](/imaging/python-net/api-reference/aspose.imaging/graphics/) by the specified [Matrix](/imaging/python-net/api-reference/aspose.imaging/matrix/) in the specified order.|
|translate_transform(dx, dy)|Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform.|
|translate_transform(dx, dy, order)|Translates the local geometric transform by the specified dimensions in the specified order.|
|scale_transform(sx, sy)|Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform.|
|scale_transform(sx, sy, order)|Scales the local geometric transform by the specified amounts in the specified order.|
|rotate_transform(angle)|Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform.|
|rotate_transform(angle, order)|Rotates the local geometric transform by the specified amount in the specified order.|
|draw_line(pen, point1, point2)|Draws a line connecting two [Point](/imaging/python-net/api-reference/aspose.imaging/point/) structures.|
|draw_line(pen, point1, point2)|Draws a line connecting two [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures.|
|draw_line(pen, x1, y1, x2, y2)|Draws a line connecting two [Point](/imaging/python-net/api-reference/aspose.imaging/point/) structures.|
|draw_line(pen, x1, y1, x2, y2)|Draws a line connecting the two points specified by the coordinate pairs.|
|draw_lines(pen, points)|Draws a series of line segments that connect an array of [Point](/imaging/python-net/api-reference/aspose.imaging/point/) structures.|
|draw_lines(pen, points)|Draws a series of line segments that connect an array of [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures.|
|fill_rectangle(brush, rect)|Fills the interior of a rectangle specified by a [Rectangle](/imaging/python-net/api-reference/aspose.imaging/rectangle/) structure.|
|fill_rectangle(brush, rect)|Fills the interior of a rectangle specified by a [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|fill_rectangle(brush, x, y, width, height)|Fills the interior of a rectangle specified by a pair of coordinates, a width and a height.|
|fill_rectangle(brush, x, y, width, height)|Fills the interior of a rectangle specified by a pair of coordinates, a width and a height.|
|fill_rectangles(brush, rects)|Fills the interiors of a series of rectangles specified by [Rectangle](/imaging/python-net/api-reference/aspose.imaging/rectangle/) structures.|
|fill_rectangles(brush, rects)|Fills the interiors of a series of rectangles specified by [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structures.|
|draw_rectangle(pen, rect)|Draws a rectangle specified by a [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|draw_rectangle(pen, rect)|Draws a rectangle specified by a [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|draw_rectangle(pen, x, y, width, height)|  |
|draw_rectangle(pen, x, y, width, height)|  |
|draw_rectangles(pen, rects)|Draws a series of rectangles specified by [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structures.|
|draw_rectangles(pen, rects)|Draws a series of rectangles specified by [Rectangle](/imaging/python-net/api-reference/aspose.imaging/rectangle/) structures.|
|draw_ellipse(pen, rect)|Draws an ellipse defined by a bounding [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/).|
|draw_ellipse(pen, x, y, width, height)|Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width.|
|draw_ellipse(pen, rect)|Draws an ellipse defined by a bounding [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/).|
|draw_ellipse(pen, x, y, width, height)|Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width.|
|draw_polygon(pen, points)|Draws a polygon defined by an array of [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures.|
|draw_polygon(pen, points)|Draws a polygon defined by an array of [Point](/imaging/python-net/api-reference/aspose.imaging/point/) structures.|
|draw_image(source_image, point)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/), using its original physical size, at the specified location.|
|draw_image(source_image, x, y)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/), using its original physical size, at the specified location.|
|draw_image(source_image, rect)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/) at the specified location and with the specified size.|
|draw_image(source_image, rect_destination, graphics_unit)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/) at the specified location and with the specified size.|
|draw_image(source_image, rect_destination, graphics_unit)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/) at the specified location and with the specified size.|
|draw_image(source_image, rect_destination, graphics_unit, image_attributes)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/) at the specified location and with the specified size.|
|draw_image(source_image, rect_destination, graphics_unit, image_attributes)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/) at the specified location and with the specified size.|
|draw_image(source_image, rect_source, rect_destination, graphics_unit)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/) at the specified location and with the specified size.|
|draw_image(source_image, rect_source, rect_destination, graphics_unit)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/) at the specified location and with the specified size.|
|draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/) at the specified location and with the specified size.|
|draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/) at the specified location and with the specified size.|
|draw_image(image, dest_points)|Draws the specified portion of the specified|
|draw_image(image, dest_points, src_rect)|Draws the specified portion of the specified|
|draw_image(image, dest_points, src_rect, src_unit)|Draws the specified portion of the specified|
|draw_image(image, dest_points, src_rect, src_unit, image_attributes)|Draws the specified portion of the specified|
|draw_image(image, dest_points)|Draws the specified portion of the specified|
|draw_image(image, dest_points, src_rect)|Draws the specified portion of the specified|
|draw_image(image, dest_points, src_rect, src_unit)|Draws the specified portion of the specified|
|draw_image(image, dest_points, src_rect, src_unit, image_attributes)|Draws the specified portion of the specified|
|draw_image(source_image, x, y, width, height)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/), using its original physical size, at the specified location.|
|draw_image(source_image, point)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/), using its original physical size, at the specified location.|
|draw_image(source_image, x, y)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/), using its original physical size, at the specified location.|
|draw_image(source_image, rect)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/) at the specified location and with the specified size.|
|draw_image(source_image, x, y, width, height)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/), using its original physical size, at the specified location.|
|draw_image_unscaled(source_image, point)|Draws a specified image using its original physical size at a specified location.|
|draw_image_unscaled(source_image, x, y)|Draws a specified image using its original physical size at a specified location.|
|draw_image_unscaled(source_image, rect)|Draws a specified image using its original physical size at a specified location.|
|draw_image_unscaled(source_image, x, y, width, height)|Draws a specified image using its original physical size at a specified location.|
|draw_arc(pen, x, y, width, height, start_angle, sweep_angle)|Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height.|
|draw_arc(pen, rect, start_angle, sweep_angle)|Draws an arc representing a portion of an ellipse specified by a [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|draw_arc(pen, x, y, width, height, start_angle, sweep_angle)|Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height.|
|draw_arc(pen, rect, start_angle, sweep_angle)|Draws an arc representing a portion of an ellipse specified by a [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|draw_pie(pen, rect, start_angle, sweep_angle)|Draws a pie shape defined by an ellipse specified by a [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure and two radial lines.|
|draw_pie(pen, x, y, width, height, start_angle, sweep_angle)|Draws a pie shape defined by an ellipse specified by a [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure and two radial lines.|
|draw_pie(pen, rect, start_angle, sweep_angle)|Draws a pie shape defined by an ellipse specified by a [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure and two radial lines.|
|draw_pie(pen, x, y, width, height, start_angle, sweep_angle)|Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines.|
|draw_curve(pen, points)|Draws a cardinal spline through a specified array of [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5.|
|draw_curve(pen, points, tension)|Draws a cardinal spline through a specified array of [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures using a specified tension.|
|draw_curve(pen, points, offset, number_of_segments)|Draws a cardinal spline through a specified array of [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5.|
|draw_curve(pen, points, offset, number_of_segments, tension)|Draws a cardinal spline through a specified array of [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures using a specified tension.|
|draw_curve(pen, points)|Draws a cardinal spline through a specified array of [Point](/imaging/python-net/api-reference/aspose.imaging/point/) structures.|
|draw_curve(pen, points, tension)|Draws a cardinal spline through a specified array of [Point](/imaging/python-net/api-reference/aspose.imaging/point/) structures using a specified tension.|
|draw_curve(pen, points, offset, number_of_segments, tension)|Draws a cardinal spline through a specified array of [Point](/imaging/python-net/api-reference/aspose.imaging/point/) structures using a specified tension.|
|draw_closed_curve(pen, points)|Draws a closed cardinal spline defined by an array of [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5 and [ALTERNATE](/imaging/python-net/api-reference/aspose.imaging/fillmode/) fill mode.|
|draw_closed_curve(pen, points, tension)|Draws a closed cardinal spline defined by an array of [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures using a specified tension. This method uses a default [ALTERNATE](/imaging/python-net/api-reference/aspose.imaging/fillmode/) fill mode.|
|draw_closed_curve(pen, points)|Draws a closed cardinal spline defined by an array of [Point](/imaging/python-net/api-reference/aspose.imaging/point/) structures. This method uses a default tension of 0.5 and [ALTERNATE](/imaging/python-net/api-reference/aspose.imaging/fillmode/) fill mode.|
|draw_closed_curve(pen, points, tension)|Draws a closed cardinal spline defined by an array of [Point](/imaging/python-net/api-reference/aspose.imaging/point/) structures using a specified tension. This method uses a default [ALTERNATE](/imaging/python-net/api-reference/aspose.imaging/fillmode/) fill mode.|
|draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4)|Draws a Bézier spline defined by four ordered pairs of coordinates that represent points.|
|draw_bezier(pen, pt1, pt2, pt3, pt4)|Draws a Bézier spline defined by four [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures.|
|draw_bezier(pen, pt1, pt2, pt3, pt4)|Draws a Bézier spline defined by four [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures.|
|draw_beziers(pen, points)|Draws a series of Bézier splines from an array of [Point](/imaging/python-net/api-reference/aspose.imaging/point/) structures.|
|draw_beziers(pen, points)|Draws a series of Bézier splines from an array of [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures.|
|draw_string(s, font, brush, x, y)|Draws the specified text string at the specified location with the specified [Brush](/imaging/python-net/api-reference/aspose.imaging/brush/) and [Font](/imaging/python-net/api-reference/aspose.imaging/font/) objects.|
|draw_string(s, font, brush, point)|Draws the specified text string at the specified location with the specified [Brush](/imaging/python-net/api-reference/aspose.imaging/brush/) and [Font](/imaging/python-net/api-reference/aspose.imaging/font/) objects.|
|draw_string(s, font, brush, x, y, format)|Draws the specified text string at the specified location with the specified [Brush](/imaging/python-net/api-reference/aspose.imaging/brush/) and [Font](/imaging/python-net/api-reference/aspose.imaging/font/) objects using the formatting attributes of the specified [StringFormat](/imaging/python-net/api-reference/aspose.imaging/stringformat/).|
|draw_string(s, font, brush, point, format)|Draws the specified text string at the specified location with the specified [Brush](/imaging/python-net/api-reference/aspose.imaging/brush/) and [Font](/imaging/python-net/api-reference/aspose.imaging/font/) objects using the formatting attributes of the specified [StringFormat](/imaging/python-net/api-reference/aspose.imaging/stringformat/).|
|draw_string(s, font, brush, layout_rectangle)|Draws the specified text string in the specified rectangle with the specified [Brush](/imaging/python-net/api-reference/aspose.imaging/brush/) and [Font](/imaging/python-net/api-reference/aspose.imaging/font/) objects.|
|draw_string(s, font, brush, layout_rectangle, format)|Draws the specified text string in the specified rectangle with the specified [Brush](/imaging/python-net/api-reference/aspose.imaging/brush/) and [Font](/imaging/python-net/api-reference/aspose.imaging/font/) objects using the formatting attributes of the specified [StringFormat](/imaging/python-net/api-reference/aspose.imaging/stringformat/).|
|fill_ellipse(brush, rect)|Fills the interior of an ellipse defined by a bounding rectangle specified by a [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|fill_ellipse(brush, x, y, width, height)|Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height.|
|fill_ellipse(brush, rect)|Fills the interior of an ellipse defined by a bounding rectangle specified by a [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|fill_ellipse(brush, x, y, width, height)|Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height.|
|fill_pie(brush, rect, start_angle, sweep_angle)|Fills the interior of a pie section defined by an ellipse specified by a [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure and two radial lines.|
|fill_pie(brush, rect, start_angle, sweep_angle)|Fills the interior of a pie section defined by an ellipse specified by a [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure and two radial lines.|
|fill_pie(brush, x, y, width, height, start_angle, sweep_angle)|Fills the interior of a pie section defined by an ellipse specified by a [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure and two radial lines.|
|fill_pie(brush, x, y, width, height, start_angle, sweep_angle)|Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines.|
|fill_polygon(brush, points)|Fills the interior of a polygon defined by an array of points specified by [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures and [ALTERNATE](/imaging/python-net/api-reference/aspose.imaging/fillmode/).|
|fill_polygon(brush, points, fill_mode)|Fills the interior of a polygon defined by an array of points specified by [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures using the specified fill mode.|
|fill_polygon(brush, points)|Fills the interior of a polygon defined by an array of points specified by [Point](/imaging/python-net/api-reference/aspose.imaging/point/) structures and [ALTERNATE](/imaging/python-net/api-reference/aspose.imaging/fillmode/).|
|fill_polygon(brush, points, fill_mode)|Fills the interior of a polygon defined by an array of points specified by [Point](/imaging/python-net/api-reference/aspose.imaging/point/) structures using the specified fill mode.|
|fill_closed_curve(brush, points)|Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5 and [ALTERNATE](/imaging/python-net/api-reference/aspose.imaging/fillmode/) fill mode.|
|fill_closed_curve(brush, points, fillmode)|Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures using the specified fill mode. This method uses a default tension of 0.5.|
|fill_closed_curve(brush, points, fillmode, tension)|Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures using the specified fill mode and tension.|
|fill_closed_curve(brush, points)|Fills the interior of a closed cardinal spline curve defined by an array of [Point](/imaging/python-net/api-reference/aspose.imaging/point/) structures. This method uses a default tension of 0.5 and [ALTERNATE](/imaging/python-net/api-reference/aspose.imaging/fillmode/) fill mode.|
|fill_closed_curve(brush, points, fillmode)|Fills the interior of a closed cardinal spline curve defined by an array of [Point](/imaging/python-net/api-reference/aspose.imaging/point/) structures using the specified fill mode. This method uses a default tension of 0.5.|
|fill_closed_curve(brush, points, fillmode, tension)|Fills the interior of a closed cardinal spline curve defined by an array of [Point](/imaging/python-net/api-reference/aspose.imaging/point/) structures using the specified fill mode and tension.|
|reset_transform()|Resets the [transform](/imaging/python-net/api-reference/aspose.imaging/graphics/) property to identity.|
|begin_update()|Starts caching of the following graphics operations. The graphics effects applied afterwards will not be applied immediately instead the EndUpdate will cause applying all the effects at once.|
|end_update()|Finishes caching of the graphics operations started after BeginUpdate was called. The preceding graphics operations will be applied at once when calling this method.|
|clear(color)|Clears the graphics surface using the specified color.|
|draw_line_point_f(pen, point1, point2)|Draws a line connecting two [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures.|
|draw_line_by_xy(pen, x1, y1, x2, y2)|Draws a line connecting the two points specified by the coordinate pairs.|
|draw_line_f_by_xy(pen, x1, y1, x2, y2)|Draws a line connecting the two points specified by the coordinate pairs.|
|draw_lines_f(pen, points)|Draws a series of line segments that connect an array of [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures.|
|fill_rectangle_f(brush, rect)|Fills the interior of a rectangle specified by a [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|fill_rectangle_f_with_brush(brush, x, y, width, height)|Fills the interior of a rectangle specified by a pair of coordinates, a width and a height.|
|fill_rectangle_with_brush(brush, x, y, width, height)|Fills the interior of a rectangle specified by a pair of coordinates, a width and a height.|
|fill_rectangles_f(brush, rects)|Fills the interiors of a series of rectangles specified by [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structures.|
|draw_rectangle_f(pen, rect)|Draws a rectangle specified by a [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|draw_rect_f(pen, x, y, width, height)|Draws a rectangle specified by a coordinate pair, a width, and a height.|
|draw_rect(pen, x, y, width, height)|Draws a rectangle specified by a coordinate pair, a width, and a height.|
|draw_rectangles_f(pen, rects)|Draws a series of rectangles specified by [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structures.|
|draw_ellipse_f(pen, rect)|Draws an ellipse defined by a bounding [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/).|
|draw_ellipse_by_xyf(pen, x, y, width, height)|Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width.|
|draw_ellipse_by_xy(pen, x, y, width, height)|Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width.|
|draw_polygon_f(pen, points)|Draws a polygon defined by an array of [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures.|
|draw_image_at_point_f(source_image, point)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/), using its original physical size, at the specified location.|
|draw_image_at_xyf(source_image, x, y)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/), using its original physical size, at the specified location.|
|draw_image_rectangle_f(source_image, rect)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/) at the specified location and with the specified size.|
|draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/) at the specified location and with the specified size.|
|draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/) at the specified location and with the specified size.|
|draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/) at the specified location and with the specified size.|
|draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/) at the specified location and with the specified size.|
|draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/) at the specified location and with the specified size.|
|draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/) at the specified location and with the specified size.|
|draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/) at the specified location and with the specified size.|
|draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/) at the specified location and with the specified size.|
|draw_image_points(image, dest_points)|Draws the specified portion of the specified|
|draw_image_dest_points_src_rect(image, dest_points, src_rect)|Draws the specified portion of the specified|
|draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit)|Draws the specified portion of the specified|
|draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes)|Draws the specified portion of the specified|
|draw_image_points_f(image, dest_points)|Draws the specified portion of the specified|
|draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect)|Draws the specified portion of the specified|
|draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit)|Draws the specified portion of the specified|
|draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes)|Draws the specified portion of the specified|
|draw_image_in_rect_f(source_image, x, y, width, height)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/) at the specified location and with the specified size.|
|draw_image_at_point(source_image, point)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/), using its original physical size, at the specified location.|
|draw_image_at_xy(source_image, x, y)|Draws the specified image, using its original physical size, at the location specified by a coordinate pair.|
|draw_image_in_rectangle(source_image, rect)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/) at the specified location and with the specified size.|
|draw_image_in_rect(source_image, x, y, width, height)|Draws the specified [image](/imaging/python-net/api-reference/aspose.imaging/graphics/) at the specified location and with the specified size.|
|draw_image_unscaled_to_point(source_image, point)|Draws a specified image using its original physical size at a specified location.|
|draw_image_unscaled_in_rectangle(source_image, rect)|Draws a specified image using its original physical size at a specified location.|
|draw_image_unscaled_and_clipped(source_image, rect)|Draws the specified image without scaling and clips it, if necessary, to fit in the specified rectangle.|
|draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle)|Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height.|
|draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle)|Draws an arc representing a portion of an ellipse specified by a [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle)|Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height.|
|draw_arc_in_rect(pen, rect, start_angle, sweep_angle)|Draws an arc representing a portion of an ellipse specified by a [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle)|Draws a pie shape defined by an ellipse specified by a [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure and two radial lines.|
|draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle)|Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines.|
|draw_pie_in_rect(pen, rect, start_angle, sweep_angle)|Draws a pie shape defined by an ellipse specified by a [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure and two radial lines.|
|draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle)|Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines.|
|draw_curve_by_points(pen, points)|Draws a cardinal spline through a specified array of [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5.|
|draw_curve_by_point_fs_tension(pen, points, tension)|Draws a cardinal spline through a specified array of [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures using a specified tension.|
|draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension)|Draws a cardinal spline through a specified array of [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures using a specified tension. The drawing begins offset from the beginning of the array.|
|draw_curve_by_point_fs(pen, points)|Draws a cardinal spline through a specified array of [Point](/imaging/python-net/api-reference/aspose.imaging/point/) structures.|
|draw_curve_by_points_tension(pen, points, tension)|Draws a cardinal spline through a specified array of [Point](/imaging/python-net/api-reference/aspose.imaging/point/) structures using a specified tension.|
|draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension)|Draws a cardinal spline through a specified array of [Point](/imaging/python-net/api-reference/aspose.imaging/point/) structures using a specified tension.|
|draw_closed_curve_by_points_f(pen, points)|Draws a closed cardinal spline defined by an array of [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5 and [ALTERNATE](/imaging/python-net/api-reference/aspose.imaging/fillmode/) fill mode.|
|draw_closed_curve_by_points_f_tension(pen, points, tension)|Draws a closed cardinal spline defined by an array of [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures using a specified tension. This method uses a default [ALTERNATE](/imaging/python-net/api-reference/aspose.imaging/fillmode/) fill mode.|
|draw_closed_curve_by_points(pen, points)|Draws a closed cardinal spline defined by an array of [Point](/imaging/python-net/api-reference/aspose.imaging/point/) structures. This method uses a default tension of 0.5 and [ALTERNATE](/imaging/python-net/api-reference/aspose.imaging/fillmode/) fill mode.|
|draw_closed_curve_by_points_tension(pen, points, tension)|Draws a closed cardinal spline defined by an array of [Point](/imaging/python-net/api-reference/aspose.imaging/point/) structures using a specified tension. This method uses a default [ALTERNATE](/imaging/python-net/api-reference/aspose.imaging/fillmode/) fill mode.|
|draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4)|Draws a Bézier spline defined by four [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures.|
|draw_bezier_by_points(pen, pt1, pt2, pt3, pt4)|Draws a Bézier spline defined by four [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures.|
|draw_beziers_by_pt_array(pen, points)|Draws a series of Bézier splines from an array of [Point](/imaging/python-net/api-reference/aspose.imaging/point/) structures.|
|draw_beziers_by_pt_array_f(pen, points)|Draws a series of Bézier splines from an array of [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures.|
|draw_string_at_xy(s, font, brush, x, y)|Draws the specified text string at the specified location with the specified [Brush](/imaging/python-net/api-reference/aspose.imaging/brush/) and [Font](/imaging/python-net/api-reference/aspose.imaging/font/) objects.|
|draw_string_at_point_f(s, font, brush, point)|Draws the specified text string at the specified location with the specified [Brush](/imaging/python-net/api-reference/aspose.imaging/brush/) and [Font](/imaging/python-net/api-reference/aspose.imaging/font/) objects.|
|draw_string_at_point_f_format(s, font, brush, point, format)|Draws the specified text string at the specified location with the specified [Brush](/imaging/python-net/api-reference/aspose.imaging/brush/) and [Font](/imaging/python-net/api-reference/aspose.imaging/font/) objects using the formatting attributes of the specified [StringFormat](/imaging/python-net/api-reference/aspose.imaging/stringformat/).|
|draw_string_in_rect(s, font, brush, layout_rectangle)|Draws the specified text string in the specified rectangle with the specified [Brush](/imaging/python-net/api-reference/aspose.imaging/brush/) and [Font](/imaging/python-net/api-reference/aspose.imaging/font/) objects.|
|draw_string_in_rect_f(s, font, brush, layout_rectangle, format)|Draws the specified text string in the specified rectangle with the specified [Brush](/imaging/python-net/api-reference/aspose.imaging/brush/) and [Font](/imaging/python-net/api-reference/aspose.imaging/font/) objects using the formatting attributes of the specified [StringFormat](/imaging/python-net/api-reference/aspose.imaging/stringformat/).|
|fill_ellipse_in_rect_f(brush, rect)|Fills the interior of an ellipse defined by a bounding rectangle specified by a [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|fill_ellipse_at_xywhf(brush, x, y, width, height)|Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height.|
|fill_ellipse_in_rect(brush, rect)|Fills the interior of an ellipse defined by a bounding rectangle specified by a [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|fill_ellipse_at_xywh(brush, x, y, width, height)|Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height.|
|fill_pie_in_rect(brush, rect, start_angle, sweep_angle)|Fills the interior of a pie section defined by an ellipse specified by a [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure and two radial lines.|
|fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle)|Fills the interior of a pie section defined by an ellipse specified by a [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure and two radial lines.|
|fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle)|Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines.|
|fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle)|Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines.|
|fill_polygon_by_point_f(brush, points)|Fills the interior of a polygon defined by an array of points specified by [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures and [ALTERNATE](/imaging/python-net/api-reference/aspose.imaging/fillmode/).|
|fill_polygon_by_point_f_fill_mode(brush, points, fill_mode)|Fills the interior of a polygon defined by an array of points specified by [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures using the specified fill mode.|
|fill_polygon_by_point(brush, points)|Fills the interior of a polygon defined by an array of points specified by [Point](/imaging/python-net/api-reference/aspose.imaging/point/) structures and [ALTERNATE](/imaging/python-net/api-reference/aspose.imaging/fillmode/).|
|fill_polygon_by_point_fill_mode(brush, points, fill_mode)|Fills the interior of a polygon defined by an array of points specified by [Point](/imaging/python-net/api-reference/aspose.imaging/point/) structures using the specified fill mode.|
|fill_closed_curve_by_point_f(brush, points)|Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5 and [ALTERNATE](/imaging/python-net/api-reference/aspose.imaging/fillmode/) fill mode.|
|fill_closed_curve_by_point_f_fill_mode(brush, points, fillmode)|Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures using the specified fill mode. This method uses a default tension of 0.5.|
|fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension)|Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structures using the specified fill mode and tension.|
|fill_closed_curve_by_point(brush, points)|Fills the interior of a closed cardinal spline curve defined by an array of [Point](/imaging/python-net/api-reference/aspose.imaging/point/) structures. This method uses a default tension of 0.5 and [ALTERNATE](/imaging/python-net/api-reference/aspose.imaging/fillmode/) fill mode.|
|fill_closed_curve_by_point_fill_mode(brush, points, fillmode)|Fills the interior of a closed cardinal spline curve defined by an array of [Point](/imaging/python-net/api-reference/aspose.imaging/point/) structures using the specified fill mode. This method uses a default tension of 0.5.|
|fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension)|Fills the interior of a closed cardinal spline curve defined by an array of [Point](/imaging/python-net/api-reference/aspose.imaging/point/) structures using the specified fill mode and tension.|
|draw_path(pen, path)|Draws a [GraphicsPath](/imaging/python-net/api-reference/aspose.imaging/graphicspath/).|
|fill_path(brush, path)|Fills the interior of a [GraphicsPath](/imaging/python-net/api-reference/aspose.imaging/graphicspath/).|
|fill_region(brush, region)|Fills the interior of a [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|measure_string(text, font, layout_area, string_format)|Measures the specified text string with specified parameters|
