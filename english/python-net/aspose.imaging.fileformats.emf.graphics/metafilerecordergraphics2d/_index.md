---
title: MetafileRecorderGraphics2D Class
type: docs
weight: 20
url: /python-net/aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/
---

The metafiles recorder graphics

**Module:** [aspose.imaging.fileformats.emf.graphics](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/)

**Full Name:** aspose.imaging.fileformats.emf.graphics.MetafileRecorderGraphics2D

**Aspose.Imaging Version:** 23.6

The MetafileRecorderGraphics2D type exposes the following members:
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| clip | [Region](/imaging/python-net/aspose.imaging/region) | r/w | Gets or sets a Region that limits the drawing region of this Graphics |
| clip_bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | r | Gets the clip bounds. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color) | r/w | Gets or sets the color of the background. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [draw_image(image, location)](#draw_image_image_location_0) | Draws the specified Image, using its original physical size, at the specified location. |
| [draw_image(image, dest_rect, src_rect, src_unit)](#draw_image_image_dest_rect_src_rect_src_unit_1) | Draws the specified portion of the specified Image at the specified location and with the specified size. |
| [draw_image(image_bytes, dest_rect, src_unit)](#draw_image_image_bytes_dest_rect_src_unit_2) | Draws the image. |
| [draw_image(stream, dest_rect, src_unit)](#draw_image_stream_dest_rect_src_unit_3) | Draws the image. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_4) | Draws the line. |
| [draw_line(pen, pt1, pt2)](#draw_line_pen_pt1_pt2_5) | Draws the line. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_6) | Fills the polygon. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_7) | Fills the polygon. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_8) | Draws the rectangle. |
| [draw_rectangle(pen, rectangle)](#draw_rectangle_pen_rectangle_9) | Draws the rectangle. |
| [draw_string(string, font, color, x, y)](#draw_string_string_font_color_x_y_10) | Draws the string. |
| [draw_string(string, font, color, x, y, angle)](#draw_string_string_font_color_x_y_angle_11) | Draws the string. |
| [exclude_clip(rect)](#exclude_clip_rect_12) | Updates the clip region of this Graphics to exclude the area specified by a Rectangle structure. |
| [exclude_clip(region)](#exclude_clip_region_13) | Updates the clip region of this Graphics to exclude the area specified by a Region. |
| [intersect_clip(rect)](#intersect_clip_rect_14) | Updates the clip region of this Graphics to the intersection of the current clip region and the specified Rectangle structure. |
| [intersect_clip(region)](#intersect_clip_region_15) | Updates the clip region of this Graphics to the intersection of the current clip region and the specified Region. |
| [multiply_transform(matrix)](#multiply_transform_matrix_16) | Multiplies the world transformation of this Graphics and specified the Matrix. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_17) | Multiplies the world transformation of this Graphics and specified the Matrix in the specified order. |
| [translate_transform(x, y)](#translate_transform_x_y_18) | Changes the origin of the coordinate system by prepending the specified translation to the transformation matrix of this Graphics. |
| [translate_transform(x, y, order)](#translate_transform_x_y_order_19) | Changes the origin of the coordinate system by applying the specified translation to the transformation matrix of this Graphics in the specified order. |
| [rotate_transform(angle)](#rotate_transform_angle_20) | Applies the specified rotation to the transformation matrix of this Graphics. |
| [rotate_transform(angle, center, order)](#rotate_transform_angle_center_order_21) | Applies the specified rotation to the transformation matrix of this Graphics in the specified order. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_22) | Applies the specified scaling operation to the transformation matrix of this Graphics by prepending it to the object's transformation matrix. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_23) | Applies the specified scaling operation to the transformation matrix of this Graphics in the specified order. |
| clear() | Clears the state of the graphics object |
| [draw_arc(pen, rect, start_angle, arc_angle)](#draw_arc_pen_rect_start_angle_arc_angle_24) | Draws an arc representing a portion of an ellipse specified by a Rectangle structure. |
| [draw_cubic_bezier(pen, pt1, pt2, pt3, pt4)](#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_25) | Draws the cubic bezier. |
| [draw_poly_cubic_bezier(pen, points)](#draw_poly_cubic_bezier_pen_points_26) | Draws the poly cubic bezier. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_27) | Draws the ellipse. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_28) | Fills the ellipse. |
| [draw_image_from_bytes(image_bytes, dest_rect, src_unit)](#draw_image_from_bytes_image_bytes_dest_rect_src_unit_29) | Draws the image. |
| [draw_image_from_stream(stream, dest_rect, src_unit)](#draw_image_from_stream_stream_dest_rect_src_unit_30) | Draws the image. |
| [draw_polyline(pen, points)](#draw_polyline_pen_points_31) | Draws the polyline. |
| [draw_path(pen, path)](#draw_path_pen_path_32) | Draws the path. |
| [fill_path(pen, brush, path)](#fill_path_pen_brush_path_33) | Fills the path. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_34) | Draws the pie. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_35) | Fills the pie. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_36) | Draws the polygon. |
| [fill_rectangle(brush, rectangle)](#fill_rectangle_brush_rectangle_37) | Fills the rectangle. |
| [exclude_clip_rect(rect)](#exclude_clip_rect_rect_38) | Updates the clip region of this Graphics to exclude the area specified by a Rectangle structure. |
| [exclude_clip_rgn(region)](#exclude_clip_rgn_region_39) | Updates the clip region of this Graphics to exclude the area specified by a Region. |
| [intersect_clip_rect_f(rect)](#intersect_clip_rect_f_rect_40) | Updates the clip region of this Graphics to the intersection of the current clip region and the specified Rectangle structure. |
| [intersect_clip_rgn(region)](#intersect_clip_rgn_region_41) | Updates the clip region of this Graphics to the intersection of the current clip region and the specified Region. |
| reset_clip() | Resets the clip. |
| [get_transform()](#get_transform__42) | Gets the world transform. |
| [set_transform(transform)](#set_transform_transform_43) | Sets the transform. |

### draw_image(image, location) {#draw_image_image_location_0}


```
 draw_image(image, location) 
```

Draws the specified Image, using its original physical size, at the specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The image to draw. |
| location | [Point](/imaging/python-net/aspose.imaging/point) | The location of the upper-left corner of the drawn image. |

### draw_image(image, dest_rect, src_rect, src_unit) {#draw_image_image_dest_rect_src_rect_src_unit_1}


```
 draw_image(image, dest_rect, src_rect, src_unit) 
```

Draws the specified portion of the specified Image at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The image to draw. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | Rectangle structure that specifies the location and size of the drawn image. The image is scaled to fit the rectangle. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | Rectangle structure that specifies the portion of the image object to draw. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit) | The units of measure used by the srcRect parameter. |

### draw_image(image_bytes, dest_rect, src_unit) {#draw_image_image_bytes_dest_rect_src_unit_2}


```
 draw_image(image_bytes, dest_rect, src_unit) 
```

Draws the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image_bytes | byte | The image bytes. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The dest rect. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit) | The source unit. |

### draw_image(stream, dest_rect, src_unit) {#draw_image_stream_dest_rect_src_unit_3}


```
 draw_image(stream, dest_rect, src_unit) 
```

Draws the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The dest rect. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit) | The source unit. |

### draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_4}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Draws the line.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | Pen that determines the color, width, and style of the figure. |
| x1 | int | The x-coordinate of the first point. |
| y1 | int | The y-coordinate of the first point. |
| x2 | int | The x-coordinate of the second point. |
| y2 | int | The y-coordinate of the second point. |

### draw_line(pen, pt1, pt2) {#draw_line_pen_pt1_pt2_5}


```
 draw_line(pen, pt1, pt2) 
```

Draws the line.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | Pen that determines the color, width, and style of the figure. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point) | The first point. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point) | The second point. |

### fill_polygon(brush, points) {#fill_polygon_brush_points_6}


```
 fill_polygon(brush, points) 
```

Fills the polygon.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush) | Brush that determines the characteristics of the fill. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point) | The points. |

### fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_7}


```
 fill_polygon(brush, points, fill_mode) 
```

Fills the polygon.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush) | Brush that determines the characteristics of the fill. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point) | The points. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode) | The fill mode. |

### draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_8}


```
 draw_rectangle(pen, x, y, width, height) 
```

Draws the rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | Pen that determines the color, width, and style of the figure. |
| x | int | The x-coordinate of the upper-left corner of the rectangle to draw. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to draw. |
| width | int | The width of the rectangle to draw. |
| height | int | The height of the rectangle to draw. |

### draw_rectangle(pen, rectangle) {#draw_rectangle_pen_rectangle_9}


```
 draw_rectangle(pen, rectangle) 
```

Draws the rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | Pen that determines the color, width, and style of the figure. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to draw. |

### draw_string(string, font, color, x, y) {#draw_string_string_font_color_x_y_10}


```
 draw_string(string, font, color, x, y) 
```

Draws the string.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| string | string | The string. |
| font | [Font](/imaging/python-net/aspose.imaging.xmp.types.complex.font/font) | Font that defines the text format of the string. |
| color | [Color](/imaging/python-net/aspose.imaging/color) | The text color. |
| x | int | The x-coordinate of the upper-left corner of the drawn text. |
| y | int | The y-coordinate of the upper-left corner of the drawn text. |

### draw_string(string, font, color, x, y, angle) {#draw_string_string_font_color_x_y_angle_11}


```
 draw_string(string, font, color, x, y, angle) 
```

Draws the string.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| string | string | The string. |
| font | [Font](/imaging/python-net/aspose.imaging.xmp.types.complex.font/font) | Font that defines the text format of the string. |
| color | [Color](/imaging/python-net/aspose.imaging/color) | The text color. |
| x | int | The x-coordinate of the upper-left corner of the drawn text. |
| y | int | The y-coordinate of the upper-left corner of the drawn text. |
| angle | float | The angle in degrees, between the escapement vector and the x-axis of the device. <br/>            The escapement vector is parallel to the base line of a row of text. |

### exclude_clip(rect) {#exclude_clip_rect_12}


```
 exclude_clip(rect) 
```

Updates the clip region of this Graphics to exclude the area specified by a Rectangle structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | Rectangle structure that specifies the rectangle to exclude from the clip region. |

### exclude_clip(region) {#exclude_clip_region_13}


```
 exclude_clip(region) 
```

Updates the clip region of this Graphics to exclude the area specified by a Region.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region) | Region that specifies the region to exclude from the clip region. |

### intersect_clip(rect) {#intersect_clip_rect_14}


```
 intersect_clip(rect) 
```

Updates the clip region of this Graphics to the intersection of the current clip region and the specified Rectangle structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | Rectangle structure to intersect with the current clip region. |

### intersect_clip(region) {#intersect_clip_region_15}


```
 intersect_clip(region) 
```

Updates the clip region of this Graphics to the intersection of the current clip region and the specified Region.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region) | Region to intersect with the current region. |

### multiply_transform(matrix) {#multiply_transform_matrix_16}


```
 multiply_transform(matrix) 
```

Multiplies the world transformation of this Graphics and specified the Matrix.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix) | The matrix that multiplies the world transformation. |

### multiply_transform(matrix, order) {#multiply_transform_matrix_order_17}


```
 multiply_transform(matrix, order) 
```

Multiplies the world transformation of this Graphics and specified the Matrix in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix) | The matrix that multiplies the world transformation. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder) | The order of the multiplication. |

### translate_transform(x, y) {#translate_transform_x_y_18}


```
 translate_transform(x, y) 
```

Changes the origin of the coordinate system by prepending the specified translation to the transformation matrix of this Graphics.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the translation. |
| y | float | The y-coordinate of the translation. |

### translate_transform(x, y, order) {#translate_transform_x_y_order_19}


```
 translate_transform(x, y, order) 
```

Changes the origin of the coordinate system by applying the specified translation to the transformation matrix of this Graphics in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the translation. |
| y | float | The y-coordinate of the translation. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder) | Specifies whether the translation is prepended or appended to the transformation matrix. |

### rotate_transform(angle) {#rotate_transform_angle_20}


```
 rotate_transform(angle) 
```

Applies the specified rotation to the transformation matrix of this Graphics.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | Angle of rotation in degrees. |

### rotate_transform(angle, center, order) {#rotate_transform_angle_center_order_21}


```
 rotate_transform(angle, center, order) 
```

Applies the specified rotation to the transformation matrix of this Graphics in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | Angle of rotation in degrees. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf) | The rotating center. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder) | Specifies whether the rotation is appended or prepended to the matrix transformation.. |

### scale_transform(sx, sy) {#scale_transform_sx_sy_22}


```
 scale_transform(sx, sy) 
```

Applies the specified scaling operation to the transformation matrix of this Graphics by prepending it to the object's transformation matrix.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| sx | float | Scale factor in the x direction. |
| sy | float | Scale factor in the y direction. |

### scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_23}


```
 scale_transform(sx, sy, order) 
```

Applies the specified scaling operation to the transformation matrix of this Graphics in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| sx | float | Scale factor in the x direction. |
| sy | float | Scale factor in the y direction. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder) | Specifies whether the scaling operation is prepended or appended to the transformation matrix. |

### draw_arc(pen, rect, start_angle, arc_angle) {#draw_arc_pen_rect_start_angle_arc_angle_24}


```
 draw_arc(pen, rect, start_angle, arc_angle) 
```

Draws an arc representing a portion of an ellipse specified by a Rectangle structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | Pen that determines the color, width, and style of the figure. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The boundaries of the ellipse. |
| start_angle | float | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| arc_angle | float | Angle in degrees measured clockwise from the startAngle parameter to ending point of the arc. |

### draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) {#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_25}


```
 draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) 
```

Draws the cubic bezier.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | Pen that determines the color, width, and style of the figure. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point) | The starting point of the curve. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point) | The first control point for the curve. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point) | The second control point for the curve. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point) | The ending point of the curve. |

### draw_poly_cubic_bezier(pen, points) {#draw_poly_cubic_bezier_pen_points_26}


```
 draw_poly_cubic_bezier(pen, points) 
```

Draws the poly cubic bezier.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | Pen that determines the color, width, and style of the figure. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point) | The points. |

### draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_27}


```
 draw_ellipse(pen, rect) 
```

Draws the ellipse.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | Pen that determines the color, width, and style of the figure. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The boundaries of the ellipse. |

### fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_28}


```
 fill_ellipse(brush, rect) 
```

Fills the ellipse.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush) | Brush that determines the characteristics of the fill. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The boundaries of the ellipse. |

### draw_image_from_bytes(image_bytes, dest_rect, src_unit) {#draw_image_from_bytes_image_bytes_dest_rect_src_unit_29}


```
 draw_image_from_bytes(image_bytes, dest_rect, src_unit) 
```

Draws the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image_bytes | byte | The image bytes. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The dest rect. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit) | The source unit. |

### draw_image_from_stream(stream, dest_rect, src_unit) {#draw_image_from_stream_stream_dest_rect_src_unit_30}


```
 draw_image_from_stream(stream, dest_rect, src_unit) 
```

Draws the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The dest rect. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit) | The source unit. |

### draw_polyline(pen, points) {#draw_polyline_pen_points_31}


```
 draw_polyline(pen, points) 
```

Draws the polyline.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | Pen that determines the color, width, and style of the figure. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point) | The points. |

### draw_path(pen, path) {#draw_path_pen_path_32}


```
 draw_path(pen, path) 
```

Draws the path.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | Pen that determines the color, width, and style of the figure. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath) | The path to draw. |

### fill_path(pen, brush, path) {#fill_path_pen_brush_path_33}


```
 fill_path(pen, brush, path) 
```

Fills the path.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | Pen that determines the color, width, and style of the figure. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush) | Brush that determines the characteristics of the fill. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath) | The path to fill. |

### draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_34}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Draws the pie.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | Pen that determines the color, width, and style of the figure. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The boundaries of the ellipse. |
| start_angle | float | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweep_angle | float | Angle in degrees measured clockwise from the startAngle parameter to ending point of the arc. |

### fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_35}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Fills the pie.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush) | Brush that determines the characteristics of the fill. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The boundaries of the ellipse. |
| start_angle | float | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweep_angle | float | Angle in degrees measured clockwise from the startAngle parameter to ending point of the arc. |

### draw_polygon(pen, points) {#draw_polygon_pen_points_36}


```
 draw_polygon(pen, points) 
```

Draws the polygon.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | Pen that determines the color, width, and style of the figure. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point) | The points. |

### fill_rectangle(brush, rectangle) {#fill_rectangle_brush_rectangle_37}


```
 fill_rectangle(brush, rectangle) 
```

Fills the rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush) | Brush that determines the characteristics of the fill. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to fill. |

### exclude_clip_rect(rect) {#exclude_clip_rect_rect_38}


```
 exclude_clip_rect(rect) 
```

Updates the clip region of this Graphics to exclude the area specified by a Rectangle structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | Rectangle structure that specifies the rectangle to exclude from the clip region. |

### exclude_clip_rgn(region) {#exclude_clip_rgn_region_39}


```
 exclude_clip_rgn(region) 
```

Updates the clip region of this Graphics to exclude the area specified by a Region.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region) | Region that specifies the region to exclude from the clip region. |

### intersect_clip_rect_f(rect) {#intersect_clip_rect_f_rect_40}


```
 intersect_clip_rect_f(rect) 
```

Updates the clip region of this Graphics to the intersection of the current clip region and the specified Rectangle structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | Rectangle structure to intersect with the current clip region. |

### intersect_clip_rgn(region) {#intersect_clip_rgn_region_41}


```
 intersect_clip_rgn(region) 
```

Updates the clip region of this Graphics to the intersection of the current clip region and the specified Region.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region) | Region to intersect with the current region. |

### get_transform() {#get_transform__42}


```
 get_transform() 
```

Gets the world transform.

**Returns**

| Type | Description |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix) | The transform matrix. |


### set_transform(transform) {#set_transform_transform_43}


```
 set_transform(transform) 
```

Sets the transform.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix) | The new transform matrix. |

