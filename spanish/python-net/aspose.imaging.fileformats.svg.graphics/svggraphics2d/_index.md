---
title: "Clase SvgGraphics2D"
type: docs
weight: 10
url: /es/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/
---

**Summary:** Provides drawing commmands to compose an Svg image.

**Module:** [aspose.imaging.fileformats.svg.graphics](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/)

**Full Name:** aspose.imaging.fileformats.svg.graphics.SvgGraphics2D

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [SvgGraphics2D(image)](#SvgGraphics2D_image_1) | Inicializa una nueva instancia de la clase [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/). |
| [SvgGraphics2D(width, height, dpi)](#SvgGraphics2D_width_height_dpi_2) | Inicializa una nueva instancia de la clase [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [draw_arc(pen, rect, start_angle, arc_angle)](#draw_arc_pen_rect_start_angle_arc_angle_1) | Dibuja un arco que representa una porción de una elipse especificada por una estructura Rectangle. |
| [draw_cubic_bezier(pen, pt1, pt2, pt3, pt4)](#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2) | Dibuja el Bézier cúbico. |
| [draw_image(image, origin)](#draw_image_image_origin_3) | Dibuja la imagen especificada en la ubicación especificada. |
| [draw_image(image, origin, size)](#draw_image_image_origin_size_4) | Dibuja la imagen especificada del tamaño especificado en la ubicación especificada. |
| [draw_image(src_rect, dest_rect, image)](#draw_image_src_rect_dest_rect_image_5) | Dibuja la porción especificada de la imagen especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image_point_size(image, origin, size)](#draw_image_point_size_image_origin_size_6) | Dibuja la imagen especificada del tamaño especificado en la ubicación especificada. |
| [draw_image_src_dst_rects(src_rect, dest_rect, image)](#draw_image_src_dst_rects_src_rect_dest_rect_image_7) | Dibuja la porción especificada de la imagen especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_8) | Dibuja la línea. |
| [draw_path(pen, path)](#draw_path_pen_path_9) | Dibuja la ruta. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_10) | Dibuja el rectángulo. |
| [draw_string(font, text, origin, text_color)](#draw_string_font_text_origin_text_color_11) | Dibuja la cadena de texto. |
| [end_recording()](#end_recording__12) | Obtiene la imagen Svg final que incluye todos los comandos de dibujo realizados a través del objeto [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/). |
| [fill_arc(pen, brush, rect, start_angle, arc_angle)](#fill_arc_pen_brush_rect_start_angle_arc_angle_13) | Rellena un arco que representa una porción de una elipse especificada por una estructura Rectangle. |
| [fill_path(pen, brush, path)](#fill_path_pen_brush_path_14) | Rellena la ruta. |
| [fill_rectangle(pen, brush, x, y, width, height)](#fill_rectangle_pen_brush_x_y_width_height_15) | Rellena el rectángulo. |


### Constructor: SvgGraphics2D(image) {#SvgGraphics2D_image_1}


```
 SvgGraphics2D(image) 
```

Inicializa una nueva instancia de la clase [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) | La imagen sobre la que se realizan operaciones de dibujo. |

### Constructor: SvgGraphics2D(width, height, dpi) {#SvgGraphics2D_width_height_dpi_2}


```
 SvgGraphics2D(width, height, dpi) 
```

Inicializa una nueva instancia de la clase [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | int | El ancho de la imagen Svg de salida. |
| height | int | El ancho de la imagen Svg de salida. |
| dpi | int | La resolución del dispositivo, p. ej. 96 puntos por pulgada. |


**See also:**

**[Example # 1](#example_171)**: This example shows how to create an SVG image of the specified size and raste...


### Method: draw_arc(pen, rect, start_angle, arc_angle) {#draw_arc_pen_rect_start_angle_arc_angle_1}


```
 draw_arc(pen, rect, start_angle, arc_angle) 
```

Dibuja un arco que representa una porción de una elipse especificada por una estructura Rectangle.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | El lápiz para dibujar el contorno de la figura. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Los límites de la elipse. |
| start_angle | float | El ángulo en grados medido en sentido horario desde el eje x hasta el punto de inicio del arco. |
| arc_angle | float | El ángulo en grados medido en sentido horario desde el parámetro startAngle hasta el punto final del arco. |

### Method: draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) {#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2}


```
 draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) 
```

Dibuja el Bézier cúbico.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | El lápiz que determina el color, el ancho y el estilo de la figura. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | El punto de inicio de la curva. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | El primer punto de control de la curva. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | El segundo punto de control de la curva. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | El punto final de la curva. |

### Method: draw_image(image, origin) {#draw_image_image_origin_3}


```
 draw_image(image, origin) 
```

Dibuja la imagen especificada en la ubicación especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen dibujada. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | La ubicación de la imagen dibujada. |

### Method: draw_image(image, origin, size) {#draw_image_image_origin_size_4}


```
 draw_image(image, origin, size) 
```

Dibuja la imagen especificada del tamaño especificado en la ubicación especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen dibujada. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | La ubicación de la imagen dibujada. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | El tamaño deseado de la imagen dibujada. |

### Method: draw_image(src_rect, dest_rect, image) {#draw_image_src_rect_dest_rect_image_5}


```
 draw_image(src_rect, dest_rect, image) 
```

Dibuja la porción especificada de la imagen especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La porción del objeto imagen a dibujar. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La ubicación y el tamaño de la imagen dibujada. La imagen se escala para ajustarse al rectángulo. |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen a dibujar. |

### Method: draw_image_point_size(image, origin, size) {#draw_image_point_size_image_origin_size_6}


```
 draw_image_point_size(image, origin, size) 
```

Dibuja la imagen especificada del tamaño especificado en la ubicación especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen dibujada. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | La ubicación de la imagen dibujada. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | El tamaño deseado de la imagen dibujada. |

### Method: draw_image_src_dst_rects(src_rect, dest_rect, image) {#draw_image_src_dst_rects_src_rect_dest_rect_image_7}


```
 draw_image_src_dst_rects(src_rect, dest_rect, image) 
```

Dibuja la porción especificada de la imagen especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La porción del objeto imagen a dibujar. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La ubicación y el tamaño de la imagen dibujada. La imagen se escala para ajustarse al rectángulo. |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen a dibujar. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_8}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Dibuja la línea.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | El lápiz que determina el color, el ancho y el estilo de la figura. |
| x1 | int | La coordenada x del primer punto. |
| y1 | int | La coordenada y del primer punto. |
| x2 | int | La coordenada x del segundo punto. |
| y2 | int | La coordenada y del segundo punto. |

### Method: draw_path(pen, path) {#draw_path_pen_path_9}


```
 draw_path(pen, path) 
```

Dibuja la ruta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | El lápiz para dibujar el contorno de la figura. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | La ruta a dibujar. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_10}


```
 draw_rectangle(pen, x, y, width, height) 
```

Dibuja el rectángulo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | El lápiz para dibujar el contorno de la figura. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo a dibujar. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo a dibujar. |
| width | int | El ancho del rectángulo a dibujar. |
| height | int | La altura del rectángulo a dibujar. |

### Method: draw_string(font, text, origin, text_color) {#draw_string_font_text_origin_text_color_11}


```
 draw_string(font, text, origin, text_color) 
```

Dibuja la cadena de texto.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | La fuente utilizada para renderizar texto. |
| text | string | La cadena de texto Unicode. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | La esquina superior izquierda del fragmento de texto. |
| text_color | [Color](/imaging/python-net/aspose.imaging/color/) | El color del texto. |

### Method: end_recording() {#end_recording__12}


```
 end_recording() 
```

Obtiene la imagen Svg final que incluye todos los comandos de dibujo realizados a través del objeto [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/).

**Returns**

| Tipo | Descripción |
| :- | :- |
| [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) | La imagen Svg final. |


### Method: fill_arc(pen, brush, rect, start_angle, arc_angle) {#fill_arc_pen_brush_rect_start_angle_arc_angle_13}


```
 fill_arc(pen, brush, rect, start_angle, arc_angle) 
```

Rellena un arco que representa una porción de una elipse especificada por una estructura Rectangle.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | El lápiz para dibujar el contorno de la figura. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | El pincel para rellenar el interior de la figura. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Los límites de la elipse. |
| start_angle | float | El ángulo en grados medido en sentido horario desde el eje x hasta el punto de inicio del arco. |
| arc_angle | float | El ángulo en grados medido en sentido horario desde el parámetro startAngle hasta el punto final del arco. |

### Method: fill_path(pen, brush, path) {#fill_path_pen_brush_path_14}


```
 fill_path(pen, brush, path) 
```

Rellena la ruta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | El lápiz para dibujar el contorno de la figura. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | El pincel para rellenar el interior de la figura. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | La ruta a dibujar. |

### Method: fill_rectangle(pen, brush, x, y, width, height) {#fill_rectangle_pen_brush_x_y_width_height_15}


```
 fill_rectangle(pen, brush, x, y, width, height) 
```

Rellena el rectángulo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | El lápiz para dibujar el contorno de la figura. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | El pincel para rellenar el interior de la figura. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo a dibujar. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo a dibujar. |
| width | int | El ancho del rectángulo a dibujar. |
| height | int | La altura del rectángulo a dibujar. |

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
# Crea una imagen SVG de 100x100 px.
graphics = SvgGraphics2D(image_width, image_height, dpi)
pen = Pen(Color.yellow, 10)
brush = SolidBrush(Color.red)
# Rellene toda la imagen de rojo.
# Dibuja un rectángulo amarillo de 10px de ancho a lo largo de los bordes de la imagen.
graphics.fill_rectangle(pen, brush, 0, 0, image_width, image_height)
# Obtén la imagen Svg final que incluye todos los comandos de dibujo
with graphics.end_recording() as svg_image:
	svg_image.save(join(dir_, "test.output.svg"))


```

