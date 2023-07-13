---
title: SvgGraphics2D Class
type: docs
weight: 10
url: /python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/
---

Provides drawing commmands to compose an Svg image.

**Module:** [aspose.imaging.fileformats.svg.graphics](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/)

**Full Name:** aspose.imaging.fileformats.svg.graphics.SvgGraphics2D

**Aspose.Imaging Version:** 23.6

The SvgGraphics2D type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [SvgGraphics2D(width, height, dpi)](#SvgGraphics2D_width_height_dpi_0) | Initializes a new instance of the [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) class. |
| [SvgGraphics2D(image)](#SvgGraphics2D_image_1) | Initializes a new instance of the [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) class. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [draw_image(image, origin)](#draw_image_image_origin_2) | Draws the specified image at the specified location. |
| [draw_image(image, origin, size)](#draw_image_image_origin_size_3) | Draws the specified image of the specified size at the specified location. |
| [draw_image(src_rect, dest_rect, image)](#draw_image_src_rect_dest_rect_image_4) | Draws the specified portion of the specified image at the specified location and with the specified size. |
| [draw_image_point_size(image, origin, size)](#draw_image_point_size_image_origin_size_5) | Draws the specified image of the specified size at the specified location. |
| [draw_image_src_dst_rects(src_rect, dest_rect, image)](#draw_image_src_dst_rects_src_rect_dest_rect_image_6) | Draws the specified portion of the specified image at the specified location and with the specified size. |
| [draw_arc(pen, rect, start_angle, arc_angle)](#draw_arc_pen_rect_start_angle_arc_angle_7) | Draws an arc representing a portion of an ellipse specified by a Rectangle structure. |
| [fill_arc(pen, brush, rect, start_angle, arc_angle)](#fill_arc_pen_brush_rect_start_angle_arc_angle_8) | Fills an arc representing a portion of an ellipse specified by a Rectangle structure. |
| [draw_cubic_bezier(pen, pt1, pt2, pt3, pt4)](#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_9) | Draws the cubic bezier. |
| [draw_string(font, text, origin, text_color)](#draw_string_font_text_origin_text_color_10) | Draws the text string. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_11) | Draws the line. |
| [draw_path(pen, path)](#draw_path_pen_path_12) | Draws the path. |
| [fill_path(pen, brush, path)](#fill_path_pen_brush_path_13) | Fills the path. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_14) | Draws the rectangle. |
| [fill_rectangle(pen, brush, x, y, width, height)](#fill_rectangle_pen_brush_x_y_width_height_15) | Fills the rectangle. |
| [end_recording()](#end_recording__16) | Gets the final Svg image which includes all drawing commands performed via [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) object. |

### SvgGraphics2D(width, height, dpi) {#SvgGraphics2D_width_height_dpi_0}


```
 SvgGraphics2D(width, height, dpi) 
```

Initializes a new instance of the [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| width | int | The width of the output Svg image. |
| height | int | The width of the output Svg image. |
| dpi | int | The device resolution, e.g. 96 dots per inch. |

### SvgGraphics2D(image) {#SvgGraphics2D_image_1}


```
 SvgGraphics2D(image) 
```

Initializes a new instance of the [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage) | The image to perform drawing operations on. |

### draw_image(image, origin) {#draw_image_image_origin_2}


```
 draw_image(image, origin) 
```

Draws the specified image at the specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The drawn image. |
| origin | [Point](/imaging/python-net/aspose.imaging/point) | The location of the drawn image. |

### draw_image(image, origin, size) {#draw_image_image_origin_size_3}


```
 draw_image(image, origin, size) 
```

Draws the specified image of the specified size at the specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The drawn image. |
| origin | [Point](/imaging/python-net/aspose.imaging/point) | The location of the drawn image. |
| size | [Size](/imaging/python-net/aspose.imaging/size) | The desired size of the drawn image. |

### draw_image(src_rect, dest_rect, image) {#draw_image_src_rect_dest_rect_image_4}


```
 draw_image(src_rect, dest_rect, image) 
```

Draws the specified portion of the specified image at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The portion of the image object to draw. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The location and size of the drawn image. The image is scaled to fit the rectangle. |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The image to draw. |

### draw_image_point_size(image, origin, size) {#draw_image_point_size_image_origin_size_5}


```
 draw_image_point_size(image, origin, size) 
```

Draws the specified image of the specified size at the specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The drawn image. |
| origin | [Point](/imaging/python-net/aspose.imaging/point) | The location of the drawn image. |
| size | [Size](/imaging/python-net/aspose.imaging/size) | The desired size of the drawn image. |

### draw_image_src_dst_rects(src_rect, dest_rect, image) {#draw_image_src_dst_rects_src_rect_dest_rect_image_6}


```
 draw_image_src_dst_rects(src_rect, dest_rect, image) 
```

Draws the specified portion of the specified image at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The portion of the image object to draw. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The location and size of the drawn image. The image is scaled to fit the rectangle. |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The image to draw. |

### draw_arc(pen, rect, start_angle, arc_angle) {#draw_arc_pen_rect_start_angle_arc_angle_7}


```
 draw_arc(pen, rect, start_angle, arc_angle) 
```

Draws an arc representing a portion of an ellipse specified by a Rectangle structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | The pen to draw the outline of the figure. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The boundaries of the ellipse. |
| start_angle | float | The angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| arc_angle | float | The angle in degrees measured clockwise from the startAngle parameter to ending point of the arc. |

### fill_arc(pen, brush, rect, start_angle, arc_angle) {#fill_arc_pen_brush_rect_start_angle_arc_angle_8}


```
 fill_arc(pen, brush, rect, start_angle, arc_angle) 
```

Fills an arc representing a portion of an ellipse specified by a Rectangle structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | The pen to draw the outline of the figure. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush) | The brush to fill the interior of the figure. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The boundaries of the ellipse. |
| start_angle | float | The angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| arc_angle | float | The angle in degrees measured clockwise from the startAngle parameter to ending point of the arc. |

### draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) {#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_9}


```
 draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) 
```

Draws the cubic bezier.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | The pen that determines the color, width, and style of the figure. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf) | The starting point of the curve. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf) | The first control point for the curve. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf) | The second control point for the curve. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf) | The ending point of the curve. |

### draw_string(font, text, origin, text_color) {#draw_string_font_text_origin_text_color_10}


```
 draw_string(font, text, origin, text_color) 
```

Draws the text string.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| font | [Font](/imaging/python-net/aspose.imaging.xmp.types.complex.font/font) | The font used to render text. |
| text | string | The unicode text string. |
| origin | [Point](/imaging/python-net/aspose.imaging/point) | The top-left corner of the text run. |
| text_color | [Color](/imaging/python-net/aspose.imaging/color) | The text color. |

### draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_11}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Draws the line.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | The pen that determines the color, width, and style of the figure. |
| x1 | int | The x-coordinate of the first point. |
| y1 | int | The y-coordinate of the first point. |
| x2 | int | The x-coordinate of the second point. |
| y2 | int | The y-coordinate of the second point. |

### draw_path(pen, path) {#draw_path_pen_path_12}


```
 draw_path(pen, path) 
```

Draws the path.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | The pen to draw the outline of the figure. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath) | The path to draw. |

### fill_path(pen, brush, path) {#fill_path_pen_brush_path_13}


```
 fill_path(pen, brush, path) 
```

Fills the path.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | The pen to draw the outline of the figure. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush) | The brush to fill the interior of the figure. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath) | The path to draw. |

### draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_14}


```
 draw_rectangle(pen, x, y, width, height) 
```

Draws the rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | The pen to draw the outline of the figure. |
| x | int | The x-coordinate of the upper-left corner of the rectangle to draw. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to draw. |
| width | int | The width of the rectangle to draw. |
| height | int | The height of the rectangle to draw. |

### fill_rectangle(pen, brush, x, y, width, height) {#fill_rectangle_pen_brush_x_y_width_height_15}


```
 fill_rectangle(pen, brush, x, y, width, height) 
```

Fills the rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | The pen to draw the outline of the figure. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush) | The brush to fill the interior of the figure. |
| x | int | The x-coordinate of the upper-left corner of the rectangle to draw. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to draw. |
| width | int | The width of the rectangle to draw. |
| height | int | The height of the rectangle to draw. |

### end_recording() {#end_recording__16}


```
 end_recording() 
```

Gets the final Svg image which includes all drawing commands performed via [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) object.

**Returns**

| Type | Description |
| :- | :- |
| [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage) | The final Svg image. |


