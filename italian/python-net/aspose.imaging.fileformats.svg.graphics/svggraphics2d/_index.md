---
title: "Classe SvgGraphics2D"
type: docs
weight: 10
url: /it/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/
---

**Summary:** Provides drawing commmands to compose an Svg image.

**Module:** [aspose.imaging.fileformats.svg.graphics](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/)

**Full Name:** aspose.imaging.fileformats.svg.graphics.SvgGraphics2D

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [SvgGraphics2D(image)](#SvgGraphics2D_image_1) | Inizializza una nuova istanza della classe [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/). |
| [SvgGraphics2D(width, height, dpi)](#SvgGraphics2D_width_height_dpi_2) | Inizializza una nuova istanza della classe [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/). |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [draw_arc(pen, rect, start_angle, arc_angle)](#draw_arc_pen_rect_start_angle_arc_angle_1) | Disegna un arco che rappresenta una porzione di un'ellisse specificata da una struttura Rectangle. |
| [draw_cubic_bezier(pen, pt1, pt2, pt3, pt4)](#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2) | Disegna la curva Bézier cubica. |
| [draw_image(image, origin)](#draw_image_image_origin_3) | Disegna l'immagine specificata nella posizione specificata. |
| [draw_image(image, origin, size)](#draw_image_image_origin_size_4) | Disegna l'immagine specificata della dimensione specificata nella posizione specificata. |
| [draw_image(src_rect, dest_rect, image)](#draw_image_src_rect_dest_rect_image_5) | Disegna la porzione specificata dell'immagine specificata nella posizione specificata e con la dimensione specificata. |
| [draw_image_point_size(image, origin, size)](#draw_image_point_size_image_origin_size_6) | Disegna l'immagine specificata della dimensione specificata nella posizione specificata. |
| [draw_image_src_dst_rects(src_rect, dest_rect, image)](#draw_image_src_dst_rects_src_rect_dest_rect_image_7) | Disegna la porzione specificata dell'immagine specificata nella posizione specificata e con la dimensione specificata. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_8) | Disegna la linea. |
| [draw_path(pen, path)](#draw_path_pen_path_9) | Disegna il percorso. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_10) | Disegna il rettangolo. |
| [draw_string(font, text, origin, text_color)](#draw_string_font_text_origin_text_color_11) | Disegna la stringa di testo. |
| [end_recording()](#end_recording__12) | Ottiene l'immagine Svg finale che include tutti i comandi di disegno eseguiti tramite l'oggetto [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/). |
| [fill_arc(pen, brush, rect, start_angle, arc_angle)](#fill_arc_pen_brush_rect_start_angle_arc_angle_13) | Riempie un arco che rappresenta una porzione di un'ellisse specificata da una struttura Rectangle. |
| [fill_path(pen, brush, path)](#fill_path_pen_brush_path_14) | Riempie il percorso. |
| [fill_rectangle(pen, brush, x, y, width, height)](#fill_rectangle_pen_brush_x_y_width_height_15) | Riempie il rettangolo. |


### Constructor: SvgGraphics2D(image) {#SvgGraphics2D_image_1}


```
 SvgGraphics2D(image) 
```

Inizializza una nuova istanza della classe [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) | L'immagine su cui eseguire le operazioni di disegno. |

### Constructor: SvgGraphics2D(width, height, dpi) {#SvgGraphics2D_width_height_dpi_2}


```
 SvgGraphics2D(width, height, dpi) 
```

Inizializza una nuova istanza della classe [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| width | int | La larghezza dell'immagine Svg di output. |
| height | int | La larghezza dell'immagine Svg di output. |
| dpi | int | La risoluzione del dispositivo, ad es. 96 punti per pollice. |


**See also:**

**[Example # 1](#example_171)**: This example shows how to create an SVG image of the specified size and raste...


### Method: draw_arc(pen, rect, start_angle, arc_angle) {#draw_arc_pen_rect_start_angle_arc_angle_1}


```
 draw_arc(pen, rect, start_angle, arc_angle) 
```

Disegna un arco che rappresenta una porzione di un'ellisse specificata da una struttura Rectangle.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La penna per disegnare il contorno della figura. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | I confini dell'ellisse. |
| start_angle | float | L'angolo in gradi misurato in senso orario dall'asse x al punto di partenza dell'arco. |
| arc_angle | float | L'angolo in gradi misurato in senso orario dal parametro startAngle al punto finale dell'arco. |

### Method: draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) {#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2}


```
 draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) 
```

Disegna la curva Bézier cubica.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La penna che determina il colore, la larghezza e lo stile della figura. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Il punto di partenza della curva. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Il primo punto di controllo per la curva. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Il secondo punto di controllo per la curva. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Il punto finale della curva. |

### Method: draw_image(image, origin) {#draw_image_image_origin_3}


```
 draw_image(image, origin) 
```

Disegna l'immagine specificata nella posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine disegnata. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | La posizione dell'immagine disegnata. |

### Method: draw_image(image, origin, size) {#draw_image_image_origin_size_4}


```
 draw_image(image, origin, size) 
```

Disegna l'immagine specificata della dimensione specificata nella posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine disegnata. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | La posizione dell'immagine disegnata. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | La dimensione desiderata dell'immagine disegnata. |

### Method: draw_image(src_rect, dest_rect, image) {#draw_image_src_rect_dest_rect_image_5}


```
 draw_image(src_rect, dest_rect, image) 
```

Disegna la porzione specificata dell'immagine specificata nella posizione specificata e con la dimensione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La porzione dell'oggetto immagine da disegnare. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La posizione e la dimensione dell'immagine disegnata. L'immagine è scalata per adattarsi al rettangolo. |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine da disegnare. |

### Method: draw_image_point_size(image, origin, size) {#draw_image_point_size_image_origin_size_6}


```
 draw_image_point_size(image, origin, size) 
```

Disegna l'immagine specificata della dimensione specificata nella posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine disegnata. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | La posizione dell'immagine disegnata. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | La dimensione desiderata dell'immagine disegnata. |

### Method: draw_image_src_dst_rects(src_rect, dest_rect, image) {#draw_image_src_dst_rects_src_rect_dest_rect_image_7}


```
 draw_image_src_dst_rects(src_rect, dest_rect, image) 
```

Disegna la porzione specificata dell'immagine specificata nella posizione specificata e con la dimensione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La porzione dell'oggetto immagine da disegnare. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La posizione e la dimensione dell'immagine disegnata. L'immagine è scalata per adattarsi al rettangolo. |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine da disegnare. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_8}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Disegna la linea.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La penna che determina il colore, la larghezza e lo stile della figura. |
| x1 | int | La coordinata x del primo punto. |
| y1 | int | La coordinata y del primo punto. |
| x2 | int | La coordinata x del secondo punto. |
| y2 | int | La coordinata y del secondo punto. |

### Method: draw_path(pen, path) {#draw_path_pen_path_9}


```
 draw_path(pen, path) 
```

Disegna il percorso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La penna per disegnare il contorno della figura. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Il percorso da disegnare. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_10}


```
 draw_rectangle(pen, x, y, width, height) 
```

Disegna il rettangolo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La penna per disegnare il contorno della figura. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo da disegnare. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo da disegnare. |
| width | int | La larghezza del rettangolo da disegnare. |
| height | int | L'altezza del rettangolo da disegnare. |

### Method: draw_string(font, text, origin, text_color) {#draw_string_font_text_origin_text_color_11}


```
 draw_string(font, text, origin, text_color) 
```

Disegna la stringa di testo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Il carattere usato per renderizzare il testo. |
| text | string | La stringa di testo Unicode. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | L'angolo in alto a sinistra della sequenza di testo. |
| text_color | [Color](/imaging/python-net/aspose.imaging/color/) | Il colore del testo. |

### Method: end_recording() {#end_recording__12}


```
 end_recording() 
```

Ottiene l'immagine Svg finale che include tutti i comandi di disegno eseguiti tramite l'oggetto [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/).

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) | L'immagine Svg finale. |


### Method: fill_arc(pen, brush, rect, start_angle, arc_angle) {#fill_arc_pen_brush_rect_start_angle_arc_angle_13}


```
 fill_arc(pen, brush, rect, start_angle, arc_angle) 
```

Riempie un arco che rappresenta una porzione di un'ellisse specificata da una struttura Rectangle.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La penna per disegnare il contorno della figura. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Il pennello per riempire l'interno della figura. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | I confini dell'ellisse. |
| start_angle | float | L'angolo in gradi misurato in senso orario dall'asse x al punto di partenza dell'arco. |
| arc_angle | float | L'angolo in gradi misurato in senso orario dal parametro startAngle al punto finale dell'arco. |

### Method: fill_path(pen, brush, path) {#fill_path_pen_brush_path_14}


```
 fill_path(pen, brush, path) 
```

Riempie il percorso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La penna per disegnare il contorno della figura. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Il pennello per riempire l'interno della figura. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Il percorso da disegnare. |

### Method: fill_rectangle(pen, brush, x, y, width, height) {#fill_rectangle_pen_brush_x_y_width_height_15}


```
 fill_rectangle(pen, brush, x, y, width, height) 
```

Riempie il rettangolo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La penna per disegnare il contorno della figura. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Il pennello per riempire l'interno della figura. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo da disegnare. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo da disegnare. |
| width | int | La larghezza del rettangolo da disegnare. |
| height | int | L'altezza del rettangolo da disegnare. |

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
# Crea un'immagine SVG di 100x100 px.
graphics = SvgGraphics2D(image_width, image_height, dpi)
pen = Pen(Color.yellow, 10)
brush = SolidBrush(Color.red)
# Riempire l'intera immagine di rosso.
# Disegna un rettangolo giallo largo 10px lungo i bordi dell'immagine.
graphics.fill_rectangle(pen, brush, 0, 0, image_width, image_height)
# Ottieni l'immagine Svg finale che include tutti i comandi di disegno
with graphics.end_recording() as svg_image:
	svg_image.save(join(dir_, "test.output.svg"))


```

