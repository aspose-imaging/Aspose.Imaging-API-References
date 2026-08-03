---
title: SvgGraphics2D Class
type: docs
weight: 10
url: /python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/
---

**Summary:** Provides drawing commmands to compose an Svg image.

**Module:** [aspose.imaging.fileformats.svg.graphics](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/)

**Full Name:** aspose.imaging.fileformats.svg.graphics.SvgGraphics2D

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SvgGraphics2D(image)](#SvgGraphics2D_image_1) | Initializes a new instance of the [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) class. |
| [SvgGraphics2D(width, height, dpi)](#SvgGraphics2D_width_height_dpi_2) | Initializes a new instance of the [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) class. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [draw_arc(pen, rect, start_angle, arc_angle)](#draw_arc_pen_rect_start_angle_arc_angle_1) | Draws an arc representing a portion of an ellipse specified by a Rectangle structure. |
| [draw_cubic_bezier(pen, pt1, pt2, pt3, pt4)](#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2) | Draws the cubic bezier. |
| [draw_image(image, origin)](#draw_image_image_origin_3) | Draws the specified image at the specified location. |
| [draw_image(image, origin, size)](#draw_image_image_origin_size_4) | Draws the specified image of the specified size at the specified location. |
| [draw_image(src_rect, dest_rect, image)](#draw_image_src_rect_dest_rect_image_5) | Draws the specified portion of the specified image at the specified location and with the specified size. |
| [draw_image_point_size(image, origin, size)](#draw_image_point_size_image_origin_size_6) | Draws the specified image of the specified size at the specified location. |
| [draw_image_src_dst_rects(src_rect, dest_rect, image)](#draw_image_src_dst_rects_src_rect_dest_rect_image_7) | Draws the specified portion of the specified image at the specified location and with the specified size. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_8) | Draws the line. |
| [draw_path(pen, path)](#draw_path_pen_path_9) | Draws the path. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_10) | Draws the rectangle. |
| [draw_string(font, text, origin, text_color)](#draw_string_font_text_origin_text_color_11) | Draws the text string. |
| [end_recording()](#end_recording__12) | Gets the final Svg image which includes all drawing commands performed via [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) object. |
| [fill_arc(pen, brush, rect, start_angle, arc_angle)](#fill_arc_pen_brush_rect_start_angle_arc_angle_13) | Fills an arc representing a portion of an ellipse specified by a Rectangle structure. |
| [fill_path(pen, brush, path)](#fill_path_pen_brush_path_14) | Fills the path. |
| [fill_rectangle(pen, brush, x, y, width, height)](#fill_rectangle_pen_brush_x_y_width_height_15) | Fills the rectangle. |


### Constructor: SvgGraphics2D(image) {#SvgGraphics2D_image_1}


```
 SvgGraphics2D(image) 
```

Initializes a new instance of the [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) | The image to perform drawing operations on. |

### Constructor: SvgGraphics2D(width, height, dpi) {#SvgGraphics2D_width_height_dpi_2}


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


**See also:**

**[Example # 1](#example_180)**: This example shows how to create an SVG image of the specified size and raste...

**[Example # 2](#example_181)**: This example shows how to create an SVG image of the specified size and draw ...


### Method: draw_arc(pen, rect, start_angle, arc_angle) {#draw_arc_pen_rect_start_angle_arc_angle_1}


```
 draw_arc(pen, rect, start_angle, arc_angle) 
```

Draws an arc representing a portion of an ellipse specified by a Rectangle structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | The pen to draw the outline of the figure. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The boundaries of the ellipse. |
| start_angle | float | The angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| arc_angle | float | The angle in degrees measured clockwise from the startAngle parameter to ending point of the arc. |


**See also:**

**[Example # 1](#example_181)**: This example shows how to create an SVG image of the specified size and draw ...


### Method: draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) {#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2}


```
 draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) 
```

Draws the cubic bezier.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | The pen that determines the color, width, and style of the figure. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The starting point of the curve. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The first control point for the curve. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The second control point for the curve. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | The ending point of the curve. |


**See also:**

**[Example # 1](#example_181)**: This example shows how to create an SVG image of the specified size and draw ...


### Method: draw_image(image, origin) {#draw_image_image_origin_3}


```
 draw_image(image, origin) 
```

Draws the specified image at the specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | The drawn image. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | The location of the drawn image. |

### Method: draw_image(image, origin, size) {#draw_image_image_origin_size_4}


```
 draw_image(image, origin, size) 
```

Draws the specified image of the specified size at the specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | The drawn image. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | The location of the drawn image. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | The desired size of the drawn image. |


**See also:**

**[Example # 1](#example_181)**: This example shows how to create an SVG image of the specified size and draw ...


### Method: draw_image(src_rect, dest_rect, image) {#draw_image_src_rect_dest_rect_image_5}


```
 draw_image(src_rect, dest_rect, image) 
```

Draws the specified portion of the specified image at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The portion of the image object to draw. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The location and size of the drawn image. The image is scaled to fit the rectangle. |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | The image to draw. |

### Method: draw_image_point_size(image, origin, size) {#draw_image_point_size_image_origin_size_6}


```
 draw_image_point_size(image, origin, size) 
```

Draws the specified image of the specified size at the specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | The drawn image. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | The location of the drawn image. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | The desired size of the drawn image. |

### Method: draw_image_src_dst_rects(src_rect, dest_rect, image) {#draw_image_src_dst_rects_src_rect_dest_rect_image_7}


```
 draw_image_src_dst_rects(src_rect, dest_rect, image) 
```

Draws the specified portion of the specified image at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The portion of the image object to draw. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The location and size of the drawn image. The image is scaled to fit the rectangle. |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | The image to draw. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_8}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Draws the line.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | The pen that determines the color, width, and style of the figure. |
| x1 | int | The x-coordinate of the first point. |
| y1 | int | The y-coordinate of the first point. |
| x2 | int | The x-coordinate of the second point. |
| y2 | int | The y-coordinate of the second point. |


**See also:**

**[Example # 1](#example_181)**: This example shows how to create an SVG image of the specified size and draw ...


### Method: draw_path(pen, path) {#draw_path_pen_path_9}


```
 draw_path(pen, path) 
```

Draws the path.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | The pen to draw the outline of the figure. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | The path to draw. |


**See also:**

**[Example # 1](#example_181)**: This example shows how to create an SVG image of the specified size and draw ...


### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_10}


```
 draw_rectangle(pen, x, y, width, height) 
```

Draws the rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | The pen to draw the outline of the figure. |
| x | int | The x-coordinate of the upper-left corner of the rectangle to draw. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to draw. |
| width | int | The width of the rectangle to draw. |
| height | int | The height of the rectangle to draw. |


**See also:**

**[Example # 1](#example_181)**: This example shows how to create an SVG image of the specified size and draw ...


### Method: draw_string(font, text, origin, text_color) {#draw_string_font_text_origin_text_color_11}


```
 draw_string(font, text, origin, text_color) 
```

Draws the text string.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | The font used to render text. |
| text | string | The unicode text string. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | The top-left corner of the text run. |
| text_color | [Color](/imaging/python-net/aspose.imaging/color/) | The text color. |


**See also:**

**[Example # 1](#example_181)**: This example shows how to create an SVG image of the specified size and draw ...


### Method: end_recording() {#end_recording__12}


```
 end_recording() 
```

Gets the final Svg image which includes all drawing commands performed via [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) object.

**Returns**

| Type | Description |
| :- | :- |
| [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) | The final Svg image. |



**See also:**

**[Example # 1](#example_181)**: This example shows how to create an SVG image of the specified size and draw ...


### Method: fill_arc(pen, brush, rect, start_angle, arc_angle) {#fill_arc_pen_brush_rect_start_angle_arc_angle_13}


```
 fill_arc(pen, brush, rect, start_angle, arc_angle) 
```

Fills an arc representing a portion of an ellipse specified by a Rectangle structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | The pen to draw the outline of the figure. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | The brush to fill the interior of the figure. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The boundaries of the ellipse. |
| start_angle | float | The angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| arc_angle | float | The angle in degrees measured clockwise from the startAngle parameter to ending point of the arc. |


**See also:**

**[Example # 1](#example_181)**: This example shows how to create an SVG image of the specified size and draw ...


### Method: fill_path(pen, brush, path) {#fill_path_pen_brush_path_14}


```
 fill_path(pen, brush, path) 
```

Fills the path.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | The pen to draw the outline of the figure. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | The brush to fill the interior of the figure. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | The path to draw. |


**See also:**

**[Example # 1](#example_181)**: This example shows how to create an SVG image of the specified size and draw ...


### Method: fill_rectangle(pen, brush, x, y, width, height) {#fill_rectangle_pen_brush_x_y_width_height_15}


```
 fill_rectangle(pen, brush, x, y, width, height) 
```

Fills the rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | The pen to draw the outline of the figure. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | The brush to fill the interior of the figure. |
| x | int | The x-coordinate of the upper-left corner of the rectangle to draw. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to draw. |
| width | int | The width of the rectangle to draw. |
| height | int | The height of the rectangle to draw. |


**See also:**

**[Example # 1](#example_181)**: This example shows how to create an SVG image of the specified size and draw ...


## **Examples**
### This example shows how to create an SVG image of the specified size and rasterize it to PNG. {#example_180}
``` python
from aspose.imaging.fileformats.svg.graphics import SvgGraphics2D
from aspose.imaging import Graphics, Color, Pen
from aspose.imaging.brushes import SolidBrush
from os.path import join

dir_: str = "c:\\temp"
image_width: int = 100
image_height: int = 100
dpi: int = 96
# Create an SVG image of 100x100 px.
graphics = SvgGraphics2D(image_width, image_height, dpi)
pen = Pen(Color.yellow, 10)
brush = SolidBrush(Color.red)
# Fill the entire image in red.
# Draw a yellow rectangle of 10px wide along the image boundaries.
graphics.fill_rectangle(pen, brush, 0, 0, image_width, image_height)
# Get the final Svg image which includes all drawing commands
with graphics.end_recording() as svg_image:
	svg_image.save(join(dir_, "test.output.svg"))


```

### This example shows how to create an SVG image of the specified size and draw different shapes on it using SvgGraphics2D. {#example_181}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Pen, Color, Rectangle, PointF, Image, RasterImage, Size, Font, FontStyle, Figure,\
	GraphicsPath, RectangleF, SizeF, Point
from aspose.imaging.shapes import ArcShape, BezierShape, PolygonShape, RectangleShape
from aspose.imaging.fileformats.svg.graphics import SvgGraphics2D
from aspose.imaging.brushes import SolidBrush
from os.path import join as path_join


dir_: str = r"C:\Dev\Aspose\Aspose.Imaging\Aspose.Imaging.Python\doc-examples-26.4"
image_width: int = 600
image_height: int = 400
dpi: int = 96
graphics = SvgGraphics2D(image_width, image_height, dpi)
# Draw a black rectangle along the image borders using a 1-pixel-wide black pen.
graphics.draw_rectangle(Pen(Color.black, 1), 0, 0, image_width, image_height)
# Fill a rectangle with the color of white-smoke.
graphics.fill_rectangle(Pen(Color.white_smoke, 1), SolidBrush(Color.white_smoke), 10, 10, 580, 380)
# Draw two diagonal lines using a 1-pixel-wide dark-green pen.
graphics.draw_line(Pen(Color.dark_green, 1), 0, 0, image_width, image_height)
graphics.draw_line(Pen(Color.dark_green, 1), 0, image_height, image_width, 0)
# Draw an arc within the rectangle {0, 0, 200, 200} using a 2-pixel-wide blue pen.
graphics.draw_arc(Pen(Color.blue, 2), Rectangle(0, 0, 200, 200), 90, 270)
# Fill an arc
graphics.fill_arc(Pen(Color.light_coral, 10), SolidBrush(Color.light_sky_blue), Rectangle(0, 0, 150, 150), 90, 270)
# Draw a cubic bezier using a 2-pixel-wide red pen.
graphics.draw_cubic_bezier(Pen(Color.red, 2), PointF(0, 0), PointF(200, 133), PointF(400, 166), PointF(600, 400))
# Draw a raster image of the specified size at the specified location.
# The image is scaled to fit the desired rectangle.
with aspycore.as_of(Image.load(path_join(dir_, "sample.bmp")), RasterImage) as image_to_draw:
	graphics.draw_image(image_to_draw, Point(400, 200), Size(100, 50))

# Draw a text string
graphics.draw_string(Font("Arial", 48, FontStyle.REGULAR), "Hello World!", Point(200, 300), Color.dark_red)
# Create a path to fill
figure_to_fill = Figure()
figure_to_fill.is_closed = True
path_to_fill = GraphicsPath()
path_to_fill.add_figure(figure_to_fill)
figure_to_fill.add_shapes([ArcShape(RectangleF(400, 0, 200, 100), 45, 300), 
							BezierShape([PointF(300, 200), 
										PointF(400, 200), 
										PointF(500, 100), 
										PointF(600, 200)]), 
							PolygonShape([PointF(300, 100)]), 
							RectangleShape(RectangleF(0, 100, 200, 200))])
# Fill the path using a yellow brush and a green pen to draw outline
graphics.fill_path(Pen(Color.green, 2), SolidBrush(Color.yellow), path_to_fill)
# Create a path to draw
path_to_draw = GraphicsPath()
figure_to_draw = Figure()
path_to_draw.add_figure(figure_to_draw)
figure_to_draw.add_shapes([ArcShape(RectangleF(200, 200, 200, 200), 0, 360)])
# Draw the path using a 5-pixel-wide orange pen.
graphics.draw_path(Pen(Color.orange, 5), path_to_draw)
# Get the final SVG image which includes all drawing commands
with graphics.end_recording() as svg_image:
	svg_image.save(path_join(dir_, "test.output.svg"))


```

