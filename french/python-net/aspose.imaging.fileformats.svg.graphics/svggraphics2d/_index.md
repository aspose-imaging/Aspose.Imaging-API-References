---
title: "Classe SvgGraphics2D"
type: docs
weight: 10
url: /fr/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/
---

**Summary:** Provides drawing commmands to compose an Svg image.

**Module:** [aspose.imaging.fileformats.svg.graphics](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/)

**Full Name:** aspose.imaging.fileformats.svg.graphics.SvgGraphics2D

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SvgGraphics2D(image)](#SvgGraphics2D_image_1) | Initialise une nouvelle instance de la classe [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/). |
| [SvgGraphics2D(width, height, dpi)](#SvgGraphics2D_width_height_dpi_2) | Initialise une nouvelle instance de la classe [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [draw_arc(pen, rect, start_angle, arc_angle)](#draw_arc_pen_rect_start_angle_arc_angle_1) | Dessine un arc représentant une partie d'une ellipse spécifiée par une structure Rectangle. |
| [draw_cubic_bezier(pen, pt1, pt2, pt3, pt4)](#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2) | Dessine le bézier cubique. |
| [draw_image(image, origin)](#draw_image_image_origin_3) | Dessine l'image spécifiée à l'emplacement spécifié. |
| [draw_image(image, origin, size)](#draw_image_image_origin_size_4) | Dessine l'image spécifiée de la taille spécifiée à l'emplacement spécifié. |
| [draw_image(src_rect, dest_rect, image)](#draw_image_src_rect_dest_rect_image_5) | Dessine la portion spécifiée de l'image spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image_point_size(image, origin, size)](#draw_image_point_size_image_origin_size_6) | Dessine l'image spécifiée de la taille spécifiée à l'emplacement spécifié. |
| [draw_image_src_dst_rects(src_rect, dest_rect, image)](#draw_image_src_dst_rects_src_rect_dest_rect_image_7) | Dessine la portion spécifiée de l'image spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_8) | Dessine la ligne. |
| [draw_path(pen, path)](#draw_path_pen_path_9) | Dessine le chemin. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_10) | Dessine le rectangle. |
| [draw_string(font, text, origin, text_color)](#draw_string_font_text_origin_text_color_11) | Dessine la chaîne de texte. |
| [end_recording()](#end_recording__12) | Obtient l'image Svg finale qui inclut toutes les commandes de dessin effectuées via l'objet [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/). |
| [fill_arc(pen, brush, rect, start_angle, arc_angle)](#fill_arc_pen_brush_rect_start_angle_arc_angle_13) | Remplit un arc représentant une portion d'une ellipse spécifiée par une structure Rectangle. |
| [fill_path(pen, brush, path)](#fill_path_pen_brush_path_14) | Remplit le chemin. |
| [fill_rectangle(pen, brush, x, y, width, height)](#fill_rectangle_pen_brush_x_y_width_height_15) | Remplit le rectangle. |


### Constructor: SvgGraphics2D(image) {#SvgGraphics2D_image_1}


```
 SvgGraphics2D(image) 
```

Initialise une nouvelle instance de la classe [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) | L'image sur laquelle effectuer les opérations de dessin. |

### Constructor: SvgGraphics2D(width, height, dpi) {#SvgGraphics2D_width_height_dpi_2}


```
 SvgGraphics2D(width, height, dpi) 
```

Initialise une nouvelle instance de la classe [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| width | int | La largeur de l'image Svg de sortie. |
| height | int | La largeur de l'image Svg de sortie. |
| dpi | int | La résolution de l'appareil, par ex. 96 points par pouce. |


**See also:**

**[Example # 1](#example_171)**: This example shows how to create an SVG image of the specified size and raste...


### Method: draw_arc(pen, rect, start_angle, arc_angle) {#draw_arc_pen_rect_start_angle_arc_angle_1}


```
 draw_arc(pen, rect, start_angle, arc_angle) 
```

Dessine un arc représentant une partie d'une ellipse spécifiée par une structure Rectangle.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Le stylo pour dessiner le contour de la figure. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Les limites de l'ellipse. |
| start_angle | float | L'angle en degrés mesuré dans le sens horaire depuis l'axe x jusqu'au point de départ de l'arc. |
| arc_angle | float | L'angle en degrés mesuré dans le sens horaire depuis le paramètre startAngle jusqu'au point final de l'arc. |

### Method: draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) {#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2}


```
 draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) 
```

Dessine le bézier cubique.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Le stylo qui détermine la couleur, la largeur et le style de la figure. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Le point de départ de la courbe. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Le premier point de contrôle de la courbe. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Le deuxième point de contrôle de la courbe. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Le point final de la courbe. |

### Method: draw_image(image, origin) {#draw_image_image_origin_3}


```
 draw_image(image, origin) 
```

Dessine l'image spécifiée à l'emplacement spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image dessinée. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | L'emplacement de l'image dessinée. |

### Method: draw_image(image, origin, size) {#draw_image_image_origin_size_4}


```
 draw_image(image, origin, size) 
```

Dessine l'image spécifiée de la taille spécifiée à l'emplacement spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image dessinée. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | L'emplacement de l'image dessinée. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | La taille souhaitée de l'image dessinée. |

### Method: draw_image(src_rect, dest_rect, image) {#draw_image_src_rect_dest_rect_image_5}


```
 draw_image(src_rect, dest_rect, image) 
```

Dessine la portion spécifiée de l'image spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La portion de l'objet image à dessiner. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | L'emplacement et la taille de l'image dessinée. L'image est redimensionnée pour s'adapter au rectangle. |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image à dessiner. |

### Method: draw_image_point_size(image, origin, size) {#draw_image_point_size_image_origin_size_6}


```
 draw_image_point_size(image, origin, size) 
```

Dessine l'image spécifiée de la taille spécifiée à l'emplacement spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image dessinée. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | L'emplacement de l'image dessinée. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | La taille souhaitée de l'image dessinée. |

### Method: draw_image_src_dst_rects(src_rect, dest_rect, image) {#draw_image_src_dst_rects_src_rect_dest_rect_image_7}


```
 draw_image_src_dst_rects(src_rect, dest_rect, image) 
```

Dessine la portion spécifiée de l'image spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La portion de l'objet image à dessiner. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | L'emplacement et la taille de l'image dessinée. L'image est redimensionnée pour s'adapter au rectangle. |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image à dessiner. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_8}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Dessine la ligne.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Le stylo qui détermine la couleur, la largeur et le style de la figure. |
| x1 | int | La coordonnée x du premier point. |
| y1 | int | La coordonnée y du premier point. |
| x2 | int | La coordonnée x du deuxième point. |
| y2 | int | La coordonnée y du deuxième point. |

### Method: draw_path(pen, path) {#draw_path_pen_path_9}


```
 draw_path(pen, path) 
```

Dessine le chemin.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Le stylo pour dessiner le contour de la figure. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Le chemin à dessiner. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_10}


```
 draw_rectangle(pen, x, y, width, height) 
```

Dessine le rectangle.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Le stylo pour dessiner le contour de la figure. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle à dessiner. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle à dessiner. |
| width | int | La largeur du rectangle à dessiner. |
| height | int | La hauteur du rectangle à dessiner. |

### Method: draw_string(font, text, origin, text_color) {#draw_string_font_text_origin_text_color_11}


```
 draw_string(font, text, origin, text_color) 
```

Dessine la chaîne de texte.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | La police utilisée pour rendre le texte. |
| text | string | La chaîne de texte Unicode. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | Le coin supérieur gauche du texte. |
| text_color | [Color](/imaging/python-net/aspose.imaging/color/) | La couleur du texte. |

### Method: end_recording() {#end_recording__12}


```
 end_recording() 
```

Obtient l'image Svg finale qui inclut toutes les commandes de dessin effectuées via l'objet [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/).

**Returns**

| Type | Description |
| :- | :- |
| [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) | L'image Svg finale. |


### Method: fill_arc(pen, brush, rect, start_angle, arc_angle) {#fill_arc_pen_brush_rect_start_angle_arc_angle_13}


```
 fill_arc(pen, brush, rect, start_angle, arc_angle) 
```

Remplit un arc représentant une portion d'une ellipse spécifiée par une structure Rectangle.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Le stylo pour dessiner le contour de la figure. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Le pinceau pour remplir l'intérieur de la figure. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Les limites de l'ellipse. |
| start_angle | float | L'angle en degrés mesuré dans le sens horaire depuis l'axe x jusqu'au point de départ de l'arc. |
| arc_angle | float | L'angle en degrés mesuré dans le sens horaire depuis le paramètre startAngle jusqu'au point final de l'arc. |

### Method: fill_path(pen, brush, path) {#fill_path_pen_brush_path_14}


```
 fill_path(pen, brush, path) 
```

Remplit le chemin.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Le stylo pour dessiner le contour de la figure. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Le pinceau pour remplir l'intérieur de la figure. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Le chemin à dessiner. |

### Method: fill_rectangle(pen, brush, x, y, width, height) {#fill_rectangle_pen_brush_x_y_width_height_15}


```
 fill_rectangle(pen, brush, x, y, width, height) 
```

Remplit le rectangle.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Le stylo pour dessiner le contour de la figure. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Le pinceau pour remplir l'intérieur de la figure. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle à dessiner. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle à dessiner. |
| width | int | La largeur du rectangle à dessiner. |
| height | int | La hauteur du rectangle à dessiner. |

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
# Créez une image SVG de 100x100 px.
graphics = SvgGraphics2D(image_width, image_height, dpi)
pen = Pen(Color.yellow, 10)
brush = SolidBrush(Color.red)
# Remplissez toute l'image en rouge.
# Dessinez un rectangle jaune de 10 px de large le long des bordures de l'image.
graphics.fill_rectangle(pen, brush, 0, 0, image_width, image_height)
# Obtenez l'image Svg finale qui inclut toutes les commandes de dessin.
with graphics.end_recording() as svg_image:
	svg_image.save(join(dir_, "test.output.svg"))


```

