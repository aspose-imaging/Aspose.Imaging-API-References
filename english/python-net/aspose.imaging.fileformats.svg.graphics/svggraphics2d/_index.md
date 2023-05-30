---
title: SvgGraphics2D Class
type: docs
weight: 10
url: /python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/
---

Provides drawing commmands to compose an Svg image.

**Namespace:** [aspose.imaging.fileformats.svg.graphics](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/)

**Full Class Name:** aspose.imaging.fileformats.svg.graphics.SvgGraphics2D

**Assembly:**  Aspose.Imaging Version: 23.5.6

The SvgGraphics2D type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|SvgGraphics2D(width, height, dpi)|Initializes a new instance of the SvgGraphics2D class|
|SvgGraphics2D(image)|Initializes a new instance of the SvgGraphics2D class|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|draw_image(image, origin)|Draws the specified image at the specified location.|
|draw_image(image, origin, size)|Draws the specified image of the specified size at the specified location.|
|draw_image(src_rect, dest_rect, image)|Draws the specified portion of the specified image at the specified location and with the specified size.|
|draw_image_point_size(image, origin, size)|Draws the specified image of the specified size at the specified location.|
|draw_image_src_dst_rects(src_rect, dest_rect, image)|Draws the specified portion of the specified image at the specified location and with the specified size.|
|draw_arc(pen, rect, start_angle, arc_angle)|Draws an arc representing a portion of an ellipse specified by a Rectangle structure.|
|fill_arc(pen, brush, rect, start_angle, arc_angle)|Fills an arc representing a portion of an ellipse specified by a Rectangle structure.|
|draw_cubic_bezier(pen, pt1, pt2, pt3, pt4)|Draws the cubic bezier.|
|draw_string(font, text, origin, text_color)|Draws the text string.|
|draw_line(pen, x1, y1, x2, y2)|Draws the line.|
|draw_path(pen, path)|Draws the path.|
|fill_path(pen, brush, path)|Fills the path.|
|draw_rectangle(pen, x, y, width, height)|Draws the rectangle.|
|fill_rectangle(pen, brush, x, y, width, height)|Fills the rectangle.|
|end_recording()|Gets the final Svg image which includes all drawing commands performed via [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) object.|
