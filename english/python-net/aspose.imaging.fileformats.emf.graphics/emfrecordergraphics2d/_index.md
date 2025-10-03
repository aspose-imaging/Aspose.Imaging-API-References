---
title: EmfRecorderGraphics2D Class
type: docs
weight: 10
url: /python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/
---

**Summary:** The Emf recorder graphics

**Module:** [aspose.imaging.fileformats.emf.graphics](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/)

**Full Name:** aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D

**Inheritance:** MetafileRecorderGraphics2D

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfRecorderGraphics2D(frame, device_size, device_size_mm)](#EmfRecorderGraphics2D_frame_device_size_device_size_mm_1) | Initializes a new instance of the [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Gets or sets the color of the background. |
| background_mode | [EmfBackgroundMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfbackgroundmode/) | r/w | Gets or sets the background mode. |
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
| [from_emf_image(emf_image)](#from_emf_image_emf_image_32) | Gets an instance of the [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) containing all records from the Emf image. |
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


### Constructor: EmfRecorderGraphics2D(frame, device_size, device_size_mm) {#EmfRecorderGraphics2D_frame_device_size_device_size_mm_1}


```
 EmfRecorderGraphics2D(frame, device_size, device_size_mm) 
```

Initializes a new instance of the [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| frame | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The frame. |
| device_size | [Size](/imaging/python-net/aspose.imaging/size/) | Size of the device. |
| device_size_mm | [Size](/imaging/python-net/aspose.imaging/size/) | The device size mm. |


**See also:**

**[Example # 1](#example_159)**: This example shows how to create a EMF image and draw some geometric shapes o...


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
| [EmfImage](/imaging/python-net/aspose.imaging.fileformats.emf/emfimage/) | The result image. |


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

### Method: from_emf_image(emf_image)  [static] {#from_emf_image_emf_image_32}


```
 from_emf_image(emf_image) 
```

Gets an instance of the [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) containing all records from the Emf image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| emf_image | [EmfImage](/imaging/python-net/aspose.imaging.fileformats.emf/emfimage/) | The Emf image to read records from. |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) | An instance of the [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) |


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

## **Examples**
### This example shows how to create a EMF image and draw some geometric shapes on it using EmfRecorderGraphics2D. {#example_159}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Rectangle, Pen, Color, Point, Image, RasterImage, GraphicsUnit, Font, FontStyle, Figure, GraphicsPath,\
	PointF, RectangleF, Size
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.shapes import ArcShape, BezierShape, PolygonShape, RectangleShape
from aspose.imaging.imageoptions import SvgRasterizationOptions, PngOptions
from aspose.imaging.fileformats.emf.graphics import EmfRecorderGraphics2D
from os.path import join

dir_: str = "c:\\temp"
# The image size in pixels
device_width: int = 600
device_height: int = 400
# The image size in millimeters
device_width_mm = device_width // 100
device_height_mm = device_height // 100
frame = Rectangle(0, 0, device_width, device_height)
# Create a EMF image.
graphics = EmfRecorderGraphics2D(frame, Size(device_width, device_height), Size(device_width_mm, device_height_mm))
# Draw a black rectangle along the image borders using a 1-pixel-wide black pen.
graphics.draw_rectangle(Pen(Color.black, 1), 0, 0, device_width, device_height)
# Fill a rectangle with the color of white-smoke.
graphics.fill_rectangle(SolidBrush(Color.white_smoke), Rectangle(10, 10, 580, 380))
# Draw two diagonal lines using a 1-pixel-wide darkgreen pen.
graphics.draw_line(Pen(Color.dark_green, 1), 0, 0, device_width, device_height)
graphics.draw_line(Pen(Color.dark_green, 1), 0, device_height, device_width, 0)
# Draw an arc within the rectangle {0, 0, 200, 200} using a 2-pixel-wide blue pen.
graphics.draw_arc(Pen(Color.blue, 2), Rectangle(0, 0, 200, 200), 90, 270)
# Fill an arc
graphics.fill_pie(SolidBrush(Color.light_sky_blue), Rectangle(0, 0, 150, 150), 90, 270)
# Draw a cubic bezier using a 2-pixel-wide red pen.
graphics.draw_cubic_bezier(Pen(Color.red, 2), Point(0, 0), Point(200, 133), Point(400, 166), Point(600, 400))

# Draw a raster image of the specified size at the specified location.
# The image is scaled to fit the desired rectangle.
with aspycore.as_of(Image.load(join(dir_, "sample.bmp")), RasterImage) as image_to_draw:
	graphics.draw_image(image_to_draw, Rectangle(400, 200, 100, 50), Rectangle(0, 0, device_width, device_height), GraphicsUnit.PIXEL)

# Draw a text string
graphics.draw_string("Hello World!", Font("Arial", 48, FontStyle.REGULAR), Color.dark_red, 200, 300)

# Create a path to fill
figure_to_fill = Figure()
figure_to_fill.is_closed = True
path_to_fill = GraphicsPath()
path_to_fill.add_figure(figure_to_fill)
figure_to_fill.add_shapes([ArcShape(Rectangle(400, 0, 200, 100), 45, 300), BezierShape([PointF(300, 200), PointF(400, 200), PointF(500, 100), PointF(600, 200)]), PolygonShape([PointF(300, 100)]), RectangleShape(RectangleF(0, 100, 200, 200))])

# Fill the path using a yellow brush and a green pen to draw outline
graphics.fill_path(Pen(Color.green, 2), SolidBrushColor.yellow), path_to_fill)

# Create a path to draw
path_to_draw = GraphicsPath()
figure_to_draw = Figure()
path_to_draw.add_figure(figure_to_draw)
figure_to_draw.add_shapes([ArcShape(RectangleF(200, 200, 200, 200), 0, 360)])

# Draw the path using a 5-pixel-wide orange pen.
graphics.draw_path(Pen(Color.orange, 5), path_to_draw)

# Get the final WMF image which includes all drawing commands
with graphics.end_recording() as emf_image:
	emf_image.save(join(dir_, "test.output.emf"))


```

