---
title: "SvgGraphics2D-klass"
type: docs
weight: 10
url: /sv/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/
---

**Summary:** Provides drawing commmands to compose an Svg image.

**Module:** [aspose.imaging.fileformats.svg.graphics](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/)

**Full Name:** aspose.imaging.fileformats.svg.graphics.SvgGraphics2D

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SvgGraphics2D(image)](#SvgGraphics2D_image_1) | Initierar en ny instans av klassen [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/). |
| [SvgGraphics2D(width, height, dpi)](#SvgGraphics2D_width_height_dpi_2) | Initierar en ny instans av klassen [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [draw_arc(pen, rect, start_angle, arc_angle)](#draw_arc_pen_rect_start_angle_arc_angle_1) | Ritar en båge som representerar en del av en ellips specificerad av en rektangelstruktur. |
| [draw_cubic_bezier(pen, pt1, pt2, pt3, pt4)](#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2) | Ritar den kubiska Bézier-kurvan. |
| [draw_image(image, origin)](#draw_image_image_origin_3) | Ritar den angivna bilden på den angivna platsen. |
| [draw_image(image, origin, size)](#draw_image_image_origin_size_4) | Ritar den angivna bilden i den angivna storleken på den angivna platsen. |
| [draw_image(src_rect, dest_rect, image)](#draw_image_src_rect_dest_rect_image_5) | Ritar den angivna delen av den angivna bilden på den angivna platsen och med den angivna storleken. |
| [draw_image_point_size(image, origin, size)](#draw_image_point_size_image_origin_size_6) | Ritar den angivna bilden i den angivna storleken på den angivna platsen. |
| [draw_image_src_dst_rects(src_rect, dest_rect, image)](#draw_image_src_dst_rects_src_rect_dest_rect_image_7) | Ritar den angivna delen av den angivna bilden på den angivna platsen och med den angivna storleken. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_8) | Ritar linjen. |
| [draw_path(pen, path)](#draw_path_pen_path_9) | Ritar sökvägen. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_10) | Ritar rektangeln. |
| [draw_string(font, text, origin, text_color)](#draw_string_font_text_origin_text_color_11) | Ritar textsträngen. |
| [end_recording()](#end_recording__12) | Hämtar den slutliga Svg-bilden som inkluderar alla ritkommandon som utförts via objektet [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/). |
| [fill_arc(pen, brush, rect, start_angle, arc_angle)](#fill_arc_pen_brush_rect_start_angle_arc_angle_13) | Fyller en båge som representerar en del av en ellips specificerad av en rektangelstruktur. |
| [fill_path(pen, brush, path)](#fill_path_pen_brush_path_14) | Fyller sökvägen. |
| [fill_rectangle(pen, brush, x, y, width, height)](#fill_rectangle_pen_brush_x_y_width_height_15) | Fyller rektangeln. |


### Constructor: SvgGraphics2D(image) {#SvgGraphics2D_image_1}


```
 SvgGraphics2D(image) 
```

Initierar en ny instans av klassen [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) | Bilden som ritoperationer ska utföras på. |

### Constructor: SvgGraphics2D(width, height, dpi) {#SvgGraphics2D_width_height_dpi_2}


```
 SvgGraphics2D(width, height, dpi) 
```

Initierar en ny instans av klassen [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | int | Bredden på den utgående Svg-bilden. |
| height | int | Bredden på den utgående Svg-bilden. |
| dpi | int | Enhetens upplösning, t.ex. 96 punkter per tum. |


**See also:**

**[Example # 1](#example_171)**: This example shows how to create an SVG image of the specified size and raste...


### Method: draw_arc(pen, rect, start_angle, arc_angle) {#draw_arc_pen_rect_start_angle_arc_angle_1}


```
 draw_arc(pen, rect, start_angle, arc_angle) 
```

Ritar en båge som representerar en del av en ellips specificerad av en rektangelstruktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pennan för att rita figurens kontur. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Ellipsens gränser. |
| start_angle | float | Vinkeln i grader, mätt medurs från x-axeln till bågens startpunkt. |
| arc_angle | float | Vinkeln i grader, mätt medurs från startAngle-parametern till bågens slutpunkt. |

### Method: draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) {#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2}


```
 draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) 
```

Ritar den kubiska Bézier-kurvan.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pennan som bestämmer figurens färg, bredd och stil. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Kurvans startpunkt. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Kurvans första kontrollpunkt. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Kurvans andra kontrollpunkt. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Kurvans slutpunkt. |

### Method: draw_image(image, origin) {#draw_image_image_origin_3}


```
 draw_image(image, origin) 
```

Ritar den angivna bilden på den angivna platsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Den ritade bilden. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | Platsen för den ritade bilden. |

### Method: draw_image(image, origin, size) {#draw_image_image_origin_size_4}


```
 draw_image(image, origin, size) 
```

Ritar den angivna bilden i den angivna storleken på den angivna platsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Den ritade bilden. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | Platsen för den ritade bilden. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Den önskade storleken på den ritade bilden. |

### Method: draw_image(src_rect, dest_rect, image) {#draw_image_src_rect_dest_rect_image_5}


```
 draw_image(src_rect, dest_rect, image) 
```

Ritar den angivna delen av den angivna bilden på den angivna platsen och med den angivna storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den del av bildobjektet som ska ritas. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Platsen och storleken för den ritade bilden. Bilden skalas för att passa rektangeln. |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Bilden som ska ritas. |

### Method: draw_image_point_size(image, origin, size) {#draw_image_point_size_image_origin_size_6}


```
 draw_image_point_size(image, origin, size) 
```

Ritar den angivna bilden i den angivna storleken på den angivna platsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Den ritade bilden. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | Platsen för den ritade bilden. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Den önskade storleken på den ritade bilden. |

### Method: draw_image_src_dst_rects(src_rect, dest_rect, image) {#draw_image_src_dst_rects_src_rect_dest_rect_image_7}


```
 draw_image_src_dst_rects(src_rect, dest_rect, image) 
```

Ritar den angivna delen av den angivna bilden på den angivna platsen och med den angivna storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den del av bildobjektet som ska ritas. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Platsen och storleken för den ritade bilden. Bilden skalas för att passa rektangeln. |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Bilden som ska ritas. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_8}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Ritar linjen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pennan som bestämmer figurens färg, bredd och stil. |
| x1 | int | X-koordinaten för den första punkten. |
| y1 | int | Y-koordinaten för den första punkten. |
| x2 | int | X-koordinaten för den andra punkten. |
| y2 | int | Y-koordinaten för den andra punkten. |

### Method: draw_path(pen, path) {#draw_path_pen_path_9}


```
 draw_path(pen, path) 
```

Ritar sökvägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pennan för att rita figurens kontur. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Sökvägen att rita. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_10}


```
 draw_rectangle(pen, x, y, width, height) 
```

Ritar rektangeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pennan för att rita figurens kontur. |
| x | int | X-koordinaten för det övre vänstra hörnet av rektangeln som ska ritas. |
| y | int | Y-koordinaten för det övre vänstra hörnet av rektangeln som ska ritas. |
| width | int | Bredden på rektangeln som ska ritas. |
| height | int | Höjden på rektangeln som ska ritas. |

### Method: draw_string(font, text, origin, text_color) {#draw_string_font_text_origin_text_color_11}


```
 draw_string(font, text, origin, text_color) 
```

Ritar textsträngen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Typsnittet som används för att rendera text. |
| text | string | Unicode-textsträngen. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | Det övre vänstra hörnet av textsekvensen. |
| text_color | [Color](/imaging/python-net/aspose.imaging/color/) | Textfärgen. |

### Method: end_recording() {#end_recording__12}


```
 end_recording() 
```

Hämtar den slutliga Svg-bilden som inkluderar alla ritkommandon som utförts via objektet [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/).

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) | Den slutgiltiga Svg-bilden. |


### Method: fill_arc(pen, brush, rect, start_angle, arc_angle) {#fill_arc_pen_brush_rect_start_angle_arc_angle_13}


```
 fill_arc(pen, brush, rect, start_angle, arc_angle) 
```

Fyller en båge som representerar en del av en ellips specificerad av en rektangelstruktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pennan för att rita figurens kontur. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Penseln för att fylla figurens inre. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Ellipsens gränser. |
| start_angle | float | Vinkeln i grader, mätt medurs från x-axeln till bågens startpunkt. |
| arc_angle | float | Vinkeln i grader, mätt medurs från startAngle-parametern till bågens slutpunkt. |

### Method: fill_path(pen, brush, path) {#fill_path_pen_brush_path_14}


```
 fill_path(pen, brush, path) 
```

Fyller sökvägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pennan för att rita figurens kontur. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Penseln för att fylla figurens inre. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Sökvägen att rita. |

### Method: fill_rectangle(pen, brush, x, y, width, height) {#fill_rectangle_pen_brush_x_y_width_height_15}


```
 fill_rectangle(pen, brush, x, y, width, height) 
```

Fyller rektangeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pennan för att rita figurens kontur. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Penseln för att fylla figurens inre. |
| x | int | X-koordinaten för det övre vänstra hörnet av rektangeln som ska ritas. |
| y | int | Y-koordinaten för det övre vänstra hörnet av rektangeln som ska ritas. |
| width | int | Bredden på rektangeln som ska ritas. |
| height | int | Höjden på rektangeln som ska ritas. |

## **Examples**
### This example shows how to create an SVG image of the specified size and rasterize it to PNG. {#example_171}
``` python
from aspose.imaging.fileformats.svg.graphics import SvgGraphics2D
from aspose.imaging import Graphics, Color, Pen
from aspose.imaging.brushes import SolidBrush
from os.path import join

dir_: str = "c:\\temp"
image_width: int = 100
image_height: int = 100
dpi: int = 96
# Skapa en SVG-bild på 100x100 px.
graphics = SvgGraphics2D(image_width, image_height, dpi)
pen = Pen(Color.yellow, 10)
brush = SolidBrush(Color.red)
# Fyll hela bilden med rött.
# Rita en gul rektangel på 10px bredd längs bildens kanter.
graphics.fill_rectangle(pen, brush, 0, 0, image_width, image_height)
# Hämta den slutgiltiga Svg-bilden som inkluderar alla ritkommandon
with graphics.end_recording() as svg_image:
	svg_image.save(join(dir_, "test.output.svg"))


```

