---
title: EmfRecorderGraphics2D Class
type: docs
weight: 10
url: /python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/
---

The Emf recorder graphics

**Namespace:** [aspose.imaging.fileformats.emf.graphics](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/)

**Full Class Name:** aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D

**Assembly:**  Aspose.Imaging Version: 23.5.6

The EmfRecorderGraphics2D type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfRecorderGraphics2D(frame, device_size, device_size_mm)|Initializes a new instance of the EmfRecorderGraphics2D class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|clip|Gets or sets a Region that limits the drawing region of this Graphics|
|clip_bounds|Gets the clip bounds.|
|background_color|Gets or sets the color of the background.|
|background_mode|Gets or sets the background mode.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|draw_image(image, location)|Draws the specified Image, using its original physical size, at the specified location.|
|draw_image(image, dest_rect, src_rect, src_unit)|Draws the specified portion of the specified Image at the specified location and with the specified size.|
|draw_image(image_bytes, dest_rect, src_unit)|Draws the image.|
|draw_image(stream, dest_rect, src_unit)|Draws the image.|
|draw_line(pen, x1, y1, x2, y2)|Draws the line.|
|draw_line(pen, pt1, pt2)|Draws the line.|
|fill_polygon(brush, points)|Fills the polygon.|
|fill_polygon(brush, points, fill_mode)|Fills the polygon.|
|draw_rectangle(pen, x, y, width, height)|Draws the rectangle.|
|draw_rectangle(pen, rectangle)|Draws the rectangle.|
|draw_string(string, font, color, x, y)|Draws the string.|
|draw_string(string, font, color, x, y, angle)|Draws the string.|
|exclude_clip(rect)|Updates the clip region of this Graphics to exclude the area specified by a Rectangle structure.|
|exclude_clip(region)|Updates the clip region of this Graphics to exclude the area specified by a Region.|
|intersect_clip(rect)|Updates the clip region of this Graphics to the intersection of the current clip region and the specified Rectangle structure.|
|intersect_clip(region)|Updates the clip region of this Graphics to the intersection of the current clip region and the specified Region.|
|multiply_transform(matrix)|Multiplies the world transformation of this Graphics and specified the Matrix.|
|multiply_transform(matrix, order)|Multiplies the world transformation of this Graphics and specified the Matrix in the specified order.|
|translate_transform(x, y)|Changes the origin of the coordinate system by prepending the specified translation to the transformation matrix of this Graphics.|
|translate_transform(x, y, order)|Changes the origin of the coordinate system by applying the specified translation to the transformation matrix of this Graphics in the specified order.|
|rotate_transform(angle)|Applies the specified rotation to the transformation matrix of this Graphics.|
|rotate_transform(angle, center, order)|Applies the specified rotation to the transformation matrix of this Graphics in the specified order.|
|scale_transform(sx, sy)|Applies the specified scaling operation to the transformation matrix of this Graphics by prepending it to the object's transformation matrix.|
|scale_transform(sx, sy, order)|Applies the specified scaling operation to the transformation matrix of this Graphics in the specified order.|
|clear()|Clears the state of the graphics object|
|draw_arc(pen, rect, start_angle, arc_angle)|Draws an arc representing a portion of an ellipse specified by a Rectangle structure.|
|draw_cubic_bezier(pen, pt1, pt2, pt3, pt4)|Draws the cubic bezier.|
|draw_poly_cubic_bezier(pen, points)|Draws the poly cubic bezier.|
|draw_ellipse(pen, rect)|Draws the ellipse.|
|fill_ellipse(brush, rect)|Fills the ellipse.|
|draw_image_from_bytes(image_bytes, dest_rect, src_unit)|Draws the image.|
|draw_image_from_stream(stream, dest_rect, src_unit)|Draws the image.|
|draw_polyline(pen, points)|Draws the polyline.|
|draw_path(pen, path)|Draws the path.|
|fill_path(pen, brush, path)|Fills the path.|
|draw_pie(pen, rect, start_angle, sweep_angle)|Draws the pie.|
|fill_pie(brush, rect, start_angle, sweep_angle)|Fills the pie.|
|draw_polygon(pen, points)|Draws the polygon.|
|fill_rectangle(brush, rectangle)|Fills the rectangle.|
|exclude_clip_rect(rect)|Updates the clip region of this Graphics to exclude the area specified by a Rectangle structure.|
|exclude_clip_rgn(region)|Updates the clip region of this Graphics to exclude the area specified by a Region.|
|intersect_clip_rect_f(rect)|Updates the clip region of this Graphics to the intersection of the current clip region and the specified Rectangle structure.|
|intersect_clip_rgn(region)|Updates the clip region of this Graphics to the intersection of the current clip region and the specified Region.|
|reset_clip()|Resets the clip.|
|get_transform()|Gets the world transform.|
|set_transform(transform)|Sets the transform.|
|end_recording()|Ends the recording.|
|from_emf_image(emf_image)|Gets an instance of the [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) containing all records from the Emf image.|
