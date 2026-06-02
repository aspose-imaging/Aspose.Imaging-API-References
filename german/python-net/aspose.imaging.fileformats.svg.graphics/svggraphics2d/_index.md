---
title: "SvgGraphics2D Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/
---

**Summary:** Provides drawing commmands to compose an Svg image.

**Module:** [aspose.imaging.fileformats.svg.graphics](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/)

**Full Name:** aspose.imaging.fileformats.svg.graphics.SvgGraphics2D

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [SvgGraphics2D(image)](#SvgGraphics2D_image_1) | Initialisiert eine neue Instanz der [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) Klasse. |
| [SvgGraphics2D(width, height, dpi)](#SvgGraphics2D_width_height_dpi_2) | Initialisiert eine neue Instanz der [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) Klasse. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [draw_arc(pen, rect, start_angle, arc_angle)](#draw_arc_pen_rect_start_angle_arc_angle_1) | Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch eine Rechteckstruktur angegeben ist. |
| [draw_cubic_bezier(pen, pt1, pt2, pt3, pt4)](#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2) | Zeichnet die kubische Bézierkurve. |
| [draw_image(image, origin)](#draw_image_image_origin_3) | Zeichnet das angegebene Bild am angegebenen Ort. |
| [draw_image(image, origin, size)](#draw_image_image_origin_size_4) | Zeichnet das angegebene Bild in der angegebenen Größe am angegebenen Ort. |
| [draw_image(src_rect, dest_rect, image)](#draw_image_src_rect_dest_rect_image_5) | Zeichnet den angegebenen Ausschnitt des angegebenen Bildes am angegebenen Ort und in der angegebenen Größe. |
| [draw_image_point_size(image, origin, size)](#draw_image_point_size_image_origin_size_6) | Zeichnet das angegebene Bild in der angegebenen Größe am angegebenen Ort. |
| [draw_image_src_dst_rects(src_rect, dest_rect, image)](#draw_image_src_dst_rects_src_rect_dest_rect_image_7) | Zeichnet den angegebenen Ausschnitt des angegebenen Bildes am angegebenen Ort und in der angegebenen Größe. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_8) | Zeichnet die Linie. |
| [draw_path(pen, path)](#draw_path_pen_path_9) | Zeichnet den Pfad. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_10) | Zeichnet das Rechteck. |
| [draw_string(font, text, origin, text_color)](#draw_string_font_text_origin_text_color_11) | Zeichnet die Textzeichenfolge. |
| [end_recording()](#end_recording__12) | Liest das endgültige Svg-Bild, das alle Zeichenbefehle enthält, die über das [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) Objekt ausgeführt wurden. |
| [fill_arc(pen, brush, rect, start_angle, arc_angle)](#fill_arc_pen_brush_rect_start_angle_arc_angle_13) | Füllt einen Bogen, der einen Teil einer Ellipse darstellt, angegeben durch eine Rechteckstruktur. |
| [fill_path(pen, brush, path)](#fill_path_pen_brush_path_14) | Füllt den Pfad. |
| [fill_rectangle(pen, brush, x, y, width, height)](#fill_rectangle_pen_brush_x_y_width_height_15) | Füllt das Rechteck. |


### Constructor: SvgGraphics2D(image) {#SvgGraphics2D_image_1}


```
 SvgGraphics2D(image) 
```

Initialisiert eine neue Instanz der [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) | Das Bild, auf dem Zeichenoperationen ausgeführt werden. |

### Constructor: SvgGraphics2D(width, height, dpi) {#SvgGraphics2D_width_height_dpi_2}


```
 SvgGraphics2D(width, height, dpi) 
```

Initialisiert eine neue Instanz der [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | int | Die Breite des ausgegebenen Svg-Bildes. |
| height | int | Die Breite des ausgegebenen Svg-Bildes. |
| dpi | int | Die Geräteauflösung, z. B. 96 Punkte pro Zoll. |


**See also:**

**[Example # 1](#example_171)**: This example shows how to create an SVG image of the specified size and raste...


### Method: draw_arc(pen, rect, start_angle, arc_angle) {#draw_arc_pen_rect_start_angle_arc_angle_1}


```
 draw_arc(pen, rect, start_angle, arc_angle) 
```

Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch eine Rechteckstruktur angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der Stift zum Zeichnen der Kontur der Figur. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Die Grenzen der Ellipse. |
| start_angle | float | Der Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| arc_angle | float | Der Winkel in Grad, gemessen im Uhrzeigersinn vom Parameter startAngle zum Endpunkt des Bogens. |

### Method: draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) {#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2}


```
 draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) 
```

Zeichnet die kubische Bézierkurve.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Der Startpunkt der Kurve. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Der erste Kontrollpunkt der Kurve. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Der zweite Kontrollpunkt der Kurve. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Der Endpunkt der Kurve. |

### Method: draw_image(image, origin) {#draw_image_image_origin_3}


```
 draw_image(image, origin) 
```

Zeichnet das angegebene Bild am angegebenen Ort.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das gezeichnete Bild. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | Der Ort des gezeichneten Bildes. |

### Method: draw_image(image, origin, size) {#draw_image_image_origin_size_4}


```
 draw_image(image, origin, size) 
```

Zeichnet das angegebene Bild in der angegebenen Größe am angegebenen Ort.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das gezeichnete Bild. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | Der Ort des gezeichneten Bildes. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Die gewünschte Größe des gezeichneten Bildes. |

### Method: draw_image(src_rect, dest_rect, image) {#draw_image_src_rect_dest_rect_image_5}


```
 draw_image(src_rect, dest_rect, image) 
```

Zeichnet den angegebenen Ausschnitt des angegebenen Bildes am angegebenen Ort und in der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der zu zeichnende Ausschnitt des Bildobjekts. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Ort und die Größe des gezeichneten Bildes. Das Bild wird skaliert, um in das Rechteck zu passen. |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das Bild zum Zeichnen. |

### Method: draw_image_point_size(image, origin, size) {#draw_image_point_size_image_origin_size_6}


```
 draw_image_point_size(image, origin, size) 
```

Zeichnet das angegebene Bild in der angegebenen Größe am angegebenen Ort.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das gezeichnete Bild. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | Der Ort des gezeichneten Bildes. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Die gewünschte Größe des gezeichneten Bildes. |

### Method: draw_image_src_dst_rects(src_rect, dest_rect, image) {#draw_image_src_dst_rects_src_rect_dest_rect_image_7}


```
 draw_image_src_dst_rects(src_rect, dest_rect, image) 
```

Zeichnet den angegebenen Ausschnitt des angegebenen Bildes am angegebenen Ort und in der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der zu zeichnende Ausschnitt des Bildobjekts. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Ort und die Größe des gezeichneten Bildes. Das Bild wird skaliert, um in das Rechteck zu passen. |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das Bild zum Zeichnen. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_8}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Zeichnet die Linie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| x1 | int | Die x-Koordinate des ersten Punktes. |
| y1 | int | Die y-Koordinate des ersten Punktes. |
| x2 | int | Die x-Koordinate des zweiten Punktes. |
| y2 | int | Die y-Koordinate des zweiten Punktes. |

### Method: draw_path(pen, path) {#draw_path_pen_path_9}


```
 draw_path(pen, path) 
```

Zeichnet den Pfad.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der Stift zum Zeichnen der Kontur der Figur. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Der Pfad zum Zeichnen. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_10}


```
 draw_rectangle(pen, x, y, width, height) 
```

Zeichnet das Rechteck.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der Stift zum Zeichnen der Kontur der Figur. |
| x | int | Die x-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| y | int | Die y-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| width | int | Die Breite des zu zeichnenden Rechtecks. |
| height | int | Die Höhe des zu zeichnenden Rechtecks. |

### Method: draw_string(font, text, origin, text_color) {#draw_string_font_text_origin_text_color_11}


```
 draw_string(font, text, origin, text_color) 
```

Zeichnet die Textzeichenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Die zum Rendern von Text verwendete Schriftart. |
| text | string | Die Unicode-Textzeichenfolge. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | Die obere linke Ecke des Textlaufs. |
| text_color | [Color](/imaging/python-net/aspose.imaging/color/) | Die Textfarbe. |

### Method: end_recording() {#end_recording__12}


```
 end_recording() 
```

Liest das endgültige Svg-Bild, das alle Zeichenbefehle enthält, die über das [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) Objekt ausgeführt wurden.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) | Das endgültige Svg-Bild. |


### Method: fill_arc(pen, brush, rect, start_angle, arc_angle) {#fill_arc_pen_brush_rect_start_angle_arc_angle_13}


```
 fill_arc(pen, brush, rect, start_angle, arc_angle) 
```

Füllt einen Bogen, der einen Teil einer Ellipse darstellt, angegeben durch eine Rechteckstruktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der Stift zum Zeichnen der Kontur der Figur. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Der Pinsel zum Füllen des Inneren der Figur. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Die Grenzen der Ellipse. |
| start_angle | float | Der Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| arc_angle | float | Der Winkel in Grad, gemessen im Uhrzeigersinn vom Parameter startAngle zum Endpunkt des Bogens. |

### Method: fill_path(pen, brush, path) {#fill_path_pen_brush_path_14}


```
 fill_path(pen, brush, path) 
```

Füllt den Pfad.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der Stift zum Zeichnen der Kontur der Figur. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Der Pinsel zum Füllen des Inneren der Figur. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Der Pfad zum Zeichnen. |

### Method: fill_rectangle(pen, brush, x, y, width, height) {#fill_rectangle_pen_brush_x_y_width_height_15}


```
 fill_rectangle(pen, brush, x, y, width, height) 
```

Füllt das Rechteck.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der Stift zum Zeichnen der Kontur der Figur. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Der Pinsel zum Füllen des Inneren der Figur. |
| x | int | Die x-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| y | int | Die y-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| width | int | Die Breite des zu zeichnenden Rechtecks. |
| height | int | Die Höhe des zu zeichnenden Rechtecks. |

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
# Erstelle ein SVG-Bild von 100x100 px.
graphics = SvgGraphics2D(image_width, image_height, dpi)
pen = Pen(Color.yellow, 10)
brush = SolidBrush(Color.red)
# Füllen Sie das gesamte Bild mit Rot.
# Zeichne ein gelbes Rechteck mit einer Breite von 10px entlang der Bildränder.
graphics.fill_rectangle(pen, brush, 0, 0, image_width, image_height)
# Hole das endgültige Svg-Bild, das alle Zeichenbefehle enthält
with graphics.end_recording() as svg_image:
	svg_image.save(join(dir_, "test.output.svg"))


```

