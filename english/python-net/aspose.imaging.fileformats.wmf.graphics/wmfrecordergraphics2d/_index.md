---
title: WmfRecorderGraphics2D Class
type: docs
weight: 10
url: /python-net/aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d/
---

**Summary:** The Wmf recorder.

**Module:** [aspose.imaging.fileformats.wmf.graphics](/imaging/python-net/aspose.imaging.fileformats.wmf.graphics/)

**Full Name:** aspose.imaging.fileformats.wmf.graphics.WmfRecorderGraphics2D

**Inheritance:** MetafileRecorderGraphics2D

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WmfRecorderGraphics2D(frame, inch)](#WmfRecorderGraphics2D_frame_inch_1) | Initializes a new instance of the [WmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Gets or sets the color of the background. |
| background_mode | [WmfMixMode](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfmixmode/) | r/w | Gets or sets the background mode. |
| clip | [Region](/imaging/python-net/aspose.imaging/region/) | r/w | Gets or sets a Region that limits the drawing region of this Graphics |
| clip_bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Gets the clip bounds. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| clear() | Clears the state of the graphics object |
| [draw_arc(pen, rect, start_angle, arc_angle)](#draw_arc_pen_rect_start_angle_arc_angle_1) | Draws an arc representing a portion of an ellipse specified by a Rectangle structure. |
| [draw_cubic_bezier(pen, pt1, pt2, pt3, pt4)](#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2) | Draws the cubic bezier. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_3) | Draws the ellipse. |
| [draw_image(image, dest_rect, src_rect, src_unit)](#draw_image_image_dest_rect_src_rect_src_unit_4) | Draws the specified portion of the specified Image at the specified location and with the specified size. |
| [draw_image(image, location)](#draw_image_image_location_5) | Draws the specified Image, using its original physical size, at the specified location. |
| [draw_image(image_bytes, dest_rect, src_unit)](#draw_image_image_bytes_dest_rect_src_unit_6) | Draws the image. |
| [draw_image(stream, dest_rect, src_unit)](#draw_image_stream_dest_rect_src_unit_7) | Draws the image. |
| [draw_image_from_bytes(image_bytes, dest_rect, src_unit)](#draw_image_from_bytes_image_bytes_dest_rect_src_unit_8) | Draws the image. |
| [draw_image_from_stream(stream, dest_rect, src_unit)](#draw_image_from_stream_stream_dest_rect_src_unit_9) | Draws the image. |
| [draw_line(pen, pt1, pt2)](#draw_line_pen_pt1_pt2_10) | Draws the line. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_11) | Draws the line. |
| [draw_path(pen, path)](#draw_path_pen_path_12) | Draws the path. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_13) | Draws the pie. |
| [draw_poly_cubic_bezier(pen, points)](#draw_poly_cubic_bezier_pen_points_14) | Draws the poly cubic bezier. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_15) | Draws the polygon. |
| [draw_polyline(pen, points)](#draw_polyline_pen_points_16) | Draws the polyline. |
| [draw_rectangle(pen, rectangle)](#draw_rectangle_pen_rectangle_17) | Draws the rectangle. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_18) | Draws the rectangle. |
| [draw_string(string, font, color, x, y)](#draw_string_string_font_color_x_y_19) | Draws the string. |
| [draw_string(string, font, color, x, y, angle)](#draw_string_string_font_color_x_y_angle_20) | Draws the string. |
| [end_recording()](#end_recording__21) | Ends the recording. |
| [exclude_clip(rect)](#exclude_clip_rect_22) | Updates the clip region of this Graphics to exclude the area specified by a Rectangle structure. |
| [exclude_clip(region)](#exclude_clip_region_23) | Updates the clip region of this Graphics to exclude the area specified by a Region. |
| [exclude_clip_rect(rect)](#exclude_clip_rect_rect_24) | Updates the clip region of this Graphics to exclude the area specified by a Rectangle structure. |
| [exclude_clip_rgn(region)](#exclude_clip_rgn_region_25) | Updates the clip region of this Graphics to exclude the area specified by a Region. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_26) | Fills the ellipse. |
| [fill_path(pen, brush, path)](#fill_path_pen_brush_path_27) | Fills the path. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_28) | Fills the pie. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_29) | Fills the polygon. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_30) | Fills the polygon. |
| [fill_rectangle(brush, rectangle)](#fill_rectangle_brush_rectangle_31) | Fills the rectangle. |
| [from_wmf_image(wmf_image)](#from_wmf_image_wmf_image_32) | Gets an instance of the Wmf recorder for the existing Wmf image. |
| [get_transform()](#get_transform__33) | Gets the world transform. |
| [intersect_clip(rect)](#intersect_clip_rect_34) | Updates the clip region of this Graphics to the intersection of the current clip region and the specified Rectangle structure. |
| [intersect_clip(region)](#intersect_clip_region_35) | Updates the clip region of this Graphics to the intersection of the current clip region and the specified Region. |
| [intersect_clip_rect_f(rect)](#intersect_clip_rect_f_rect_36) | Updates the clip region of this Graphics to the intersection of the current clip region and the specified Rectangle structure. |
| [intersect_clip_rgn(region)](#intersect_clip_rgn_region_37) | Updates the clip region of this Graphics to the intersection of the current clip region and the specified Region. |
| [multiply_transform(matrix)](#multiply_transform_matrix_38) | Multiplies the world transformation of this Graphics and specified the Matrix. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_39) | Multiplies the world transformation of this Graphics and specified the Matrix in the specified order. |
| reset_clip() | Resets the clip. |
| [rotate_transform(angle)](#rotate_transform_angle_40) | Applies the specified rotation to the transformation matrix of this Graphics. |
| [rotate_transform(angle, center, order)](#rotate_transform_angle_center_order_41) | Applies the specified rotation to the transformation matrix of this Graphics in the specified order. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_42) | Applies the specified scaling operation to the transformation matrix of this Graphics by prepending it to the object's transformation matrix. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_43) | Applies the specified scaling operation to the transformation matrix of this Graphics in the specified order. |
| [set_transform(transform)](#set_transform_transform_44) | Sets the transform. |
| [translate_transform(x, y)](#translate_transform_x_y_45) | Changes the origin of the coordinate system by prepending the specified translation to the transformation matrix of this Graphics. |
| [translate_transform(x, y, order)](#translate_transform_x_y_order_46) | Changes the origin of the coordinate system by applying the specified translation to the transformation matrix of this Graphics in the specified order. |


### Constructor: WmfRecorderGraphics2D(frame, inch) {#WmfRecorderGraphics2D_frame_inch_1}


```
 WmfRecorderGraphics2D(frame, inch) 
```

Initializes a new instance of the [WmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| frame | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Destination rectangle, measured in twips, for displaying the metafile. |
| inch | int | The number of pixel per inch. |

### Method: draw_arc(pen, rect, start_angle, arc_angle) {#draw_arc_pen_rect_start_angle_arc_angle_1}


```
 draw_arc(pen, rect, start_angle, arc_angle) 
```

Draws an arc representing a portion of an ellipse specified by a Rectangle structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pen that determines the color, width, and style of the figure. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The boundaries of the ellipse. |
| start_angle | float | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| arc_angle | float | Angle in degrees measured clockwise from the startAngle parameter to ending point of the arc. |

### Method: draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) {#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2}


```
 draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) 
```

Draws the cubic bezier.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pen that determines the color, width, and style of the figure. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | The starting point of the curve. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | The first control point for the curve. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | The second control point for the curve. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | The ending point of the curve. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_3}


```
 draw_ellipse(pen, rect) 
```

Draws the ellipse.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pen that determines the color, width, and style of the figure. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The boundaries of the ellipse. |

### Method: draw_image(image, dest_rect, src_rect, src_unit) {#draw_image_image_dest_rect_src_rect_src_unit_4}


```
 draw_image(image, dest_rect, src_rect, src_unit) 
```

Draws the specified portion of the specified Image at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | The image to draw. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rectangle structure that specifies the location and size of the drawn image. The image is scaled to fit the rectangle. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rectangle structure that specifies the portion of the image object to draw. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The units of measure used by the srcRect parameter. |

### Method: draw_image(image, location) {#draw_image_image_location_5}


```
 draw_image(image, location) 
```

Draws the specified Image, using its original physical size, at the specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | The image to draw. |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | The location of the upper-left corner of the drawn image. |

### Method: draw_image(image_bytes, dest_rect, src_unit) {#draw_image_image_bytes_dest_rect_src_unit_6}


```
 draw_image(image_bytes, dest_rect, src_unit) 
```

Draws the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image_bytes | System.Byte | The image bytes. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The dest rect. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The source unit. |

### Method: draw_image(stream, dest_rect, src_unit) {#draw_image_stream_dest_rect_src_unit_7}


```
 draw_image(stream, dest_rect, src_unit) 
```

Draws the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The dest rect. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The source unit. |

### Method: draw_image_from_bytes(image_bytes, dest_rect, src_unit) {#draw_image_from_bytes_image_bytes_dest_rect_src_unit_8}


```
 draw_image_from_bytes(image_bytes, dest_rect, src_unit) 
```

Draws the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image_bytes | System.Byte | The image bytes. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The dest rect. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The source unit. |

### Method: draw_image_from_stream(stream, dest_rect, src_unit) {#draw_image_from_stream_stream_dest_rect_src_unit_9}


```
 draw_image_from_stream(stream, dest_rect, src_unit) 
```

Draws the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The dest rect. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The source unit. |

### Method: draw_line(pen, pt1, pt2) {#draw_line_pen_pt1_pt2_10}


```
 draw_line(pen, pt1, pt2) 
```

Draws the line.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pen that determines the color, width, and style of the figure. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | The first point. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | The second point. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_11}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Draws the line.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pen that determines the color, width, and style of the figure. |
| x1 | int | The x-coordinate of the first point. |
| y1 | int | The y-coordinate of the first point. |
| x2 | int | The x-coordinate of the second point. |
| y2 | int | The y-coordinate of the second point. |

### Method: draw_path(pen, path) {#draw_path_pen_path_12}


```
 draw_path(pen, path) 
```

Draws the path.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pen that determines the color, width, and style of the figure. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | The path to draw. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_13}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Draws the pie.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pen that determines the color, width, and style of the figure. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The boundaries of the ellipse. |
| start_angle | float | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweep_angle | float | Angle in degrees measured clockwise from the startAngle parameter to ending point of the arc. |

### Method: draw_poly_cubic_bezier(pen, points) {#draw_poly_cubic_bezier_pen_points_14}


```
 draw_poly_cubic_bezier(pen, points) 
```

Draws the poly cubic bezier.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pen that determines the color, width, and style of the figure. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | The points. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_15}


```
 draw_polygon(pen, points) 
```

Draws the polygon.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pen that determines the color, width, and style of the figure. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | The points. |

### Method: draw_polyline(pen, points) {#draw_polyline_pen_points_16}


```
 draw_polyline(pen, points) 
```

Draws the polyline.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pen that determines the color, width, and style of the figure. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | The points. |

### Method: draw_rectangle(pen, rectangle) {#draw_rectangle_pen_rectangle_17}


```
 draw_rectangle(pen, rectangle) 
```

Draws the rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pen that determines the color, width, and style of the figure. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to draw. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_18}


```
 draw_rectangle(pen, x, y, width, height) 
```

Draws the rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pen that determines the color, width, and style of the figure. |
| x | int | The x-coordinate of the upper-left corner of the rectangle to draw. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to draw. |
| width | int | The width of the rectangle to draw. |
| height | int | The height of the rectangle to draw. |

### Method: draw_string(string, font, color, x, y) {#draw_string_string_font_color_x_y_19}


```
 draw_string(string, font, color, x, y) 
```

Draws the string.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| string | string | The string. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Font that defines the text format of the string. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | The text color. |
| x | int | The x-coordinate of the upper-left corner of the drawn text. |
| y | int | The y-coordinate of the upper-left corner of the drawn text. |

### Method: draw_string(string, font, color, x, y, angle) {#draw_string_string_font_color_x_y_angle_20}


```
 draw_string(string, font, color, x, y, angle) 
```

Draws the string.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| string | string | The string. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Font that defines the text format of the string. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | The text color. |
| x | int | The x-coordinate of the upper-left corner of the drawn text. |
| y | int | The y-coordinate of the upper-left corner of the drawn text. |
| angle | float | The angle in degrees, between the escapement vector and the x-axis of the device. <br/>            The escapement vector is parallel to the base line of a row of text. |

### Method: end_recording() {#end_recording__21}


```
 end_recording() 
```

Ends the recording.

**Returns**

| Type | Description |
| :- | :- |
| [WmfImage](/imaging/python-net/aspose.imaging.fileformats.wmf/wmfimage/) | The result image. |


### Method: exclude_clip(rect) {#exclude_clip_rect_22}


```
 exclude_clip(rect) 
```

Updates the clip region of this Graphics to exclude the area specified by a Rectangle structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rectangle structure that specifies the rectangle to exclude from the clip region. |

### Method: exclude_clip(region) {#exclude_clip_region_23}


```
 exclude_clip(region) 
```

Updates the clip region of this Graphics to exclude the area specified by a Region.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Region that specifies the region to exclude from the clip region. |

### Method: exclude_clip_rect(rect) {#exclude_clip_rect_rect_24}


```
 exclude_clip_rect(rect) 
```

Updates the clip region of this Graphics to exclude the area specified by a Rectangle structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rectangle structure that specifies the rectangle to exclude from the clip region. |

### Method: exclude_clip_rgn(region) {#exclude_clip_rgn_region_25}


```
 exclude_clip_rgn(region) 
```

Updates the clip region of this Graphics to exclude the area specified by a Region.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Region that specifies the region to exclude from the clip region. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_26}


```
 fill_ellipse(brush, rect) 
```

Fills the ellipse.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Brush that determines the characteristics of the fill. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The boundaries of the ellipse. |

### Method: fill_path(pen, brush, path) {#fill_path_pen_brush_path_27}


```
 fill_path(pen, brush, path) 
```

Fills the path.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pen that determines the color, width, and style of the figure. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Brush that determines the characteristics of the fill. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | The path to fill. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_28}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Fills the pie.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Brush that determines the characteristics of the fill. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The boundaries of the ellipse. |
| start_angle | float | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweep_angle | float | Angle in degrees measured clockwise from the startAngle parameter to ending point of the arc. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_29}


```
 fill_polygon(brush, points) 
```

Fills the polygon.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Brush that determines the characteristics of the fill. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | The points. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_30}


```
 fill_polygon(brush, points, fill_mode) 
```

Fills the polygon.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Brush that determines the characteristics of the fill. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | The points. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | The fill mode. |

### Method: fill_rectangle(brush, rectangle) {#fill_rectangle_brush_rectangle_31}


```
 fill_rectangle(brush, rectangle) 
```

Fills the rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Brush that determines the characteristics of the fill. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to fill. |

### Method: from_wmf_image(wmf_image)  [static] {#from_wmf_image_wmf_image_32}


```
 from_wmf_image(wmf_image) 
```

Gets an instance of the Wmf recorder for the existing Wmf image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| wmf_image | [WmfImage](/imaging/python-net/aspose.imaging.fileformats.wmf/wmfimage/) | The Wmf image to get a recoreder for. |

**Returns**

| Type | Description |
| :- | :- |
| [WmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d/) | An instance of the [WmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d/) class. |


### Method: get_transform() {#get_transform__33}


```
 get_transform() 
```

Gets the world transform.

**Returns**

| Type | Description |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) | The transform matrix. |


### Method: intersect_clip(rect) {#intersect_clip_rect_34}


```
 intersect_clip(rect) 
```

Updates the clip region of this Graphics to the intersection of the current clip region and the specified Rectangle structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Rectangle structure to intersect with the current clip region. |

### Method: intersect_clip(region) {#intersect_clip_region_35}


```
 intersect_clip(region) 
```

Updates the clip region of this Graphics to the intersection of the current clip region and the specified Region.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Region to intersect with the current region. |

### Method: intersect_clip_rect_f(rect) {#intersect_clip_rect_f_rect_36}


```
 intersect_clip_rect_f(rect) 
```

Updates the clip region of this Graphics to the intersection of the current clip region and the specified Rectangle structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Rectangle structure to intersect with the current clip region. |

### Method: intersect_clip_rgn(region) {#intersect_clip_rgn_region_37}


```
 intersect_clip_rgn(region) 
```

Updates the clip region of this Graphics to the intersection of the current clip region and the specified Region.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Region to intersect with the current region. |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_38}


```
 multiply_transform(matrix) 
```

Multiplies the world transformation of this Graphics and specified the Matrix.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | The matrix that multiplies the world transformation. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_39}


```
 multiply_transform(matrix, order) 
```

Multiplies the world transformation of this Graphics and specified the Matrix in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | The matrix that multiplies the world transformation. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | The order of the multiplication. |

### Method: rotate_transform(angle) {#rotate_transform_angle_40}


```
 rotate_transform(angle) 
```

Applies the specified rotation to the transformation matrix of this Graphics.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | Angle of rotation in degrees. |

### Method: rotate_transform(angle, center, order) {#rotate_transform_angle_center_order_41}


```
 rotate_transform(angle, center, order) 
```

Applies the specified rotation to the transformation matrix of this Graphics in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | Angle of rotation in degrees. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The rotating center. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Specifies whether the rotation is appended or prepended to the matrix transformation.. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_42}


```
 scale_transform(sx, sy) 
```

Applies the specified scaling operation to the transformation matrix of this Graphics by prepending it to the object's transformation matrix.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| sx | float | Scale factor in the x direction. |
| sy | float | Scale factor in the y direction. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_43}


```
 scale_transform(sx, sy, order) 
```

Applies the specified scaling operation to the transformation matrix of this Graphics in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| sx | float | Scale factor in the x direction. |
| sy | float | Scale factor in the y direction. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Specifies whether the scaling operation is prepended or appended to the transformation matrix. |

### Method: set_transform(transform) {#set_transform_transform_44}


```
 set_transform(transform) 
```

Sets the transform.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | The new transform matrix. |

### Method: translate_transform(x, y) {#translate_transform_x_y_45}


```
 translate_transform(x, y) 
```

Changes the origin of the coordinate system by prepending the specified translation to the transformation matrix of this Graphics.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the translation. |
| y | float | The y-coordinate of the translation. |

### Method: translate_transform(x, y, order) {#translate_transform_x_y_order_46}


```
 translate_transform(x, y, order) 
```

Changes the origin of the coordinate system by applying the specified translation to the transformation matrix of this Graphics in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the translation. |
| y | float | The y-coordinate of the translation. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Specifies whether the translation is prepended or appended to the transformation matrix. |

