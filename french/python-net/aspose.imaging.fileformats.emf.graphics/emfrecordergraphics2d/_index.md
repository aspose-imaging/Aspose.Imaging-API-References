---
title: "Classe EmfRecorderGraphics2D"
type: docs
weight: 10
url: /fr/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/
---

**Summary:** The Emf recorder graphics

**Module:** [aspose.imaging.fileformats.emf.graphics](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/)

**Full Name:** aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D

**Inheritance:** MetafileRecorderGraphics2D

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfRecorderGraphics2D(frame, device_size, device_size_mm)](#EmfRecorderGraphics2D_frame_device_size_device_size_mm_1) | Initialise une nouvelle instance de la classe [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtient ou définit la couleur de l'arrière-plan. |
| background_mode | [EmfBackgroundMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfbackgroundmode/) | r/w | Obtient ou définit le mode d'arrière-plan. |
| clip | [Region](/imaging/python-net/aspose.imaging/region/) | r/w | Obtient ou définit une région qui limite la zone de dessin de ce Graphics |
| clip_bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Obtient les limites du clip. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| clear() | Efface l'état de l'objet graphique |
| [draw_arc(pen, rect, start_angle, arc_angle)](#draw_arc_pen_rect_start_angle_arc_angle_1) | Dessine un arc représentant une partie d'une ellipse spécifiée par une structure Rectangle. |
| [draw_cubic_bezier(pen, pt1, pt2, pt3, pt4)](#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2) | Dessine le bézier cubique. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_3) | Dessine l'ellipse. |
| [draw_image(image, dest_rect, src_rect, src_unit)](#draw_image_image_dest_rect_src_rect_src_unit_4) | Dessine la partie spécifiée de l'image spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image(image, location)](#draw_image_image_location_5) | Dessine l'Image spécifiée, en utilisant sa taille physique d'origine, à l'emplacement spécifié. |
| [draw_image(image_bytes, dest_rect, src_unit)](#draw_image_image_bytes_dest_rect_src_unit_6) | Dessine l'image. |
| [draw_image(stream, dest_rect, src_unit)](#draw_image_stream_dest_rect_src_unit_7) | Dessine l'image. |
| [draw_image_from_bytes(image_bytes, dest_rect, src_unit)](#draw_image_from_bytes_image_bytes_dest_rect_src_unit_8) | Dessine l'image. |
| [draw_image_from_stream(stream, dest_rect, src_unit)](#draw_image_from_stream_stream_dest_rect_src_unit_9) | Dessine l'image. |
| [draw_line(pen, pt1, pt2)](#draw_line_pen_pt1_pt2_10) | Dessine la ligne. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_11) | Dessine la ligne. |
| [draw_path(pen, path)](#draw_path_pen_path_12) | Dessine le chemin. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_13) | Dessine le secteur. |
| [draw_poly_cubic_bezier(pen, points)](#draw_poly_cubic_bezier_pen_points_14) | Dessine le bézier poly cubique. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_15) | Dessine le polygone. |
| [draw_polyline(pen, points)](#draw_polyline_pen_points_16) | Dessine la polyligne. |
| [draw_rectangle(pen, rectangle)](#draw_rectangle_pen_rectangle_17) | Dessine le rectangle. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_18) | Dessine le rectangle. |
| [draw_string(string, font, color, x, y)](#draw_string_string_font_color_x_y_19) | Dessine la chaîne. |
| [draw_string(string, font, color, x, y, angle)](#draw_string_string_font_color_x_y_angle_20) | Dessine la chaîne. |
| [end_recording()](#end_recording__21) | Met fin à l'enregistrement. |
| [exclude_clip(rect)](#exclude_clip_rect_22) | Met à jour la région de découpage de ce Graphics pour exclure la zone spécifiée par une structure Rectangle. |
| [exclude_clip(region)](#exclude_clip_region_23) | Met à jour la région de découpage de ce Graphics pour exclure la zone spécifiée par une Region. |
| [exclude_clip_rect(rect)](#exclude_clip_rect_rect_24) | Met à jour la région de découpage de ce Graphics pour exclure la zone spécifiée par une structure Rectangle. |
| [exclude_clip_rgn(region)](#exclude_clip_rgn_region_25) | Met à jour la région de découpage de ce Graphics pour exclure la zone spécifiée par une Region. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_26) | Remplit l'ellipse. |
| [fill_path(pen, brush, path)](#fill_path_pen_brush_path_27) | Remplit le chemin. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_28) | Remplit le secteur. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_29) | Remplit le polygone. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_30) | Remplit le polygone. |
| [fill_rectangle(brush, rectangle)](#fill_rectangle_brush_rectangle_31) | Remplit le rectangle. |
| [from_emf_image(emf_image)](#from_emf_image_emf_image_32) | Obtient une instance de [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) contenant tous les enregistrements de l'image Emf. |
| [get_transform()](#get_transform__33) | Obtient la transformation du monde. |
| [intersect_clip(rect)](#intersect_clip_rect_34) | Met à jour la région de découpage de ce Graphics pour l'intersection de la région de découpage actuelle et de la structure Rectangle spécifiée. |
| [intersect_clip(region)](#intersect_clip_region_35) | Met à jour la région de découpage de ce Graphics pour l'intersection de la région de découpage actuelle et de la Region spécifiée. |
| [intersect_clip_rect_f(rect)](#intersect_clip_rect_f_rect_36) | Met à jour la région de découpage de ce Graphics pour l'intersection de la région de découpage actuelle et de la structure Rectangle spécifiée. |
| [intersect_clip_rgn(region)](#intersect_clip_rgn_region_37) | Met à jour la région de découpage de ce Graphics pour l'intersection de la région de découpage actuelle et de la Region spécifiée. |
| [multiply_transform(matrix)](#multiply_transform_matrix_38) | Multiplie la transformation du monde de ce Graphics et spécifie la Matrix. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_39) | Multiplie la transformation du monde de ce Graphics et spécifie la Matrix dans l'ordre spécifié. |
| reset_clip() | Réinitialise le clip. |
| [rotate_transform(angle)](#rotate_transform_angle_40) | Applique la rotation spécifiée à la matrice de transformation de cet objet Graphics. |
| [rotate_transform(angle, center, order)](#rotate_transform_angle_center_order_41) | Applique la rotation spécifiée à la matrice de transformation de cet objet Graphics dans l'ordre spécifié. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_42) | Applique l'opération de mise à l'échelle spécifiée à la matrice de transformation de cet objet Graphics en la préfixant à la matrice de transformation de l'objet. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_43) | Applique l'opération de mise à l'échelle spécifiée à la matrice de transformation de cet objet Graphics dans l'ordre spécifié. |
| [set_transform(transform)](#set_transform_transform_44) | Définit la transformation. |
| [translate_transform(x, y)](#translate_transform_x_y_45) | Modifie l'origine du système de coordonnées en préfixant la translation spécifiée à la matrice de transformation de cet objet Graphics. |
| [translate_transform(x, y, order)](#translate_transform_x_y_order_46) | Modifie l'origine du système de coordonnées en appliquant la translation spécifiée à la matrice de transformation de cet objet Graphics dans l'ordre spécifié. |


### Constructor: EmfRecorderGraphics2D(frame, device_size, device_size_mm) {#EmfRecorderGraphics2D_frame_device_size_device_size_mm_1}


```
 EmfRecorderGraphics2D(frame, device_size, device_size_mm) 
```

Initialise une nouvelle instance de la classe [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| frame | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le cadre. |
| device_size | [Size](/imaging/python-net/aspose.imaging/size/) | Taille de l'appareil. |
| device_size_mm | [Size](/imaging/python-net/aspose.imaging/size/) | La taille de l'appareil en mm. |


**See also:**

**[Example # 1](#example_174)**: This example shows how to create a EMF image and draw some geometric shapes o...


### Method: draw_arc(pen, rect, start_angle, arc_angle) {#draw_arc_pen_rect_start_angle_arc_angle_1}


```
 draw_arc(pen, rect, start_angle, arc_angle) 
```

Dessine un arc représentant une partie d'une ellipse spécifiée par une structure Rectangle.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Stylo qui détermine la couleur, la largeur et le style de la figure. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Les limites de l'ellipse. |
| start_angle | float | Angle en degrés mesuré dans le sens horaire depuis l'axe x jusqu'au point de départ de l'arc. |
| arc_angle | float | Angle en degrés mesuré dans le sens horaire depuis le paramètre startAngle jusqu'au point final de l'arc. |

### Method: draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) {#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2}


```
 draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) 
```

Dessine le bézier cubique.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Stylo qui détermine la couleur, la largeur et le style de la figure. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | Le point de départ de la courbe. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | Le premier point de contrôle de la courbe. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | Le deuxième point de contrôle de la courbe. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | Le point final de la courbe. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_3}


```
 draw_ellipse(pen, rect) 
```

Dessine l'ellipse.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Stylo qui détermine la couleur, la largeur et le style de la figure. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Les limites de l'ellipse. |

### Method: draw_image(image, dest_rect, src_rect, src_unit) {#draw_image_image_dest_rect_src_rect_src_unit_4}


```
 draw_image(image, dest_rect, src_rect, src_unit) 
```

Dessine la partie spécifiée de l'image spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image à dessiner. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Structure de rectangle qui spécifie l'emplacement et la taille de l'image dessinée. L'image est mise à l'échelle pour s'adapter au rectangle. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Structure de rectangle qui spécifie la partie de l'objet image à dessiner. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Les unités de mesure utilisées par le paramètre srcRect. |

### Method: draw_image(image, location) {#draw_image_image_location_5}


```
 draw_image(image, location) 
```

Dessine l'Image spécifiée, en utilisant sa taille physique d'origine, à l'emplacement spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image à dessiner. |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | L'emplacement du coin supérieur gauche de l'image dessinée. |

### Method: draw_image(image_bytes, dest_rect, src_unit) {#draw_image_image_bytes_dest_rect_src_unit_6}


```
 draw_image(image_bytes, dest_rect, src_unit) 
```

Dessine l'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image_bytes | System.Byte | Les octets de l'image. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le dest rect. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unité source. |

### Method: draw_image(stream, dest_rect, src_unit) {#draw_image_stream_dest_rect_src_unit_7}


```
 draw_image(stream, dest_rect, src_unit) 
```

Dessine l'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le dest rect. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unité source. |

### Method: draw_image_from_bytes(image_bytes, dest_rect, src_unit) {#draw_image_from_bytes_image_bytes_dest_rect_src_unit_8}


```
 draw_image_from_bytes(image_bytes, dest_rect, src_unit) 
```

Dessine l'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image_bytes | System.Byte | Les octets de l'image. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le dest rect. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unité source. |

### Method: draw_image_from_stream(stream, dest_rect, src_unit) {#draw_image_from_stream_stream_dest_rect_src_unit_9}


```
 draw_image_from_stream(stream, dest_rect, src_unit) 
```

Dessine l'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le dest rect. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unité source. |

### Method: draw_line(pen, pt1, pt2) {#draw_line_pen_pt1_pt2_10}


```
 draw_line(pen, pt1, pt2) 
```

Dessine la ligne.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Stylo qui détermine la couleur, la largeur et le style de la figure. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | Le premier point. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | Le deuxième point. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_11}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Dessine la ligne.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Stylo qui détermine la couleur, la largeur et le style de la figure. |
| x1 | int | La coordonnée x du premier point. |
| y1 | int | La coordonnée y du premier point. |
| x2 | int | La coordonnée x du deuxième point. |
| y2 | int | La coordonnée y du deuxième point. |

### Method: draw_path(pen, path) {#draw_path_pen_path_12}


```
 draw_path(pen, path) 
```

Dessine le chemin.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Stylo qui détermine la couleur, la largeur et le style de la figure. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Le chemin à dessiner. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_13}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Dessine le secteur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Stylo qui détermine la couleur, la largeur et le style de la figure. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Les limites de l'ellipse. |
| start_angle | float | Angle en degrés mesuré dans le sens horaire depuis l'axe x jusqu'au point de départ de l'arc. |
| sweep_angle | float | Angle en degrés mesuré dans le sens horaire depuis le paramètre startAngle jusqu'au point final de l'arc. |

### Method: draw_poly_cubic_bezier(pen, points) {#draw_poly_cubic_bezier_pen_points_14}


```
 draw_poly_cubic_bezier(pen, points) 
```

Dessine le bézier poly cubique.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Stylo qui détermine la couleur, la largeur et le style de la figure. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Les points. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_15}


```
 draw_polygon(pen, points) 
```

Dessine le polygone.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Stylo qui détermine la couleur, la largeur et le style de la figure. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Les points. |

### Method: draw_polyline(pen, points) {#draw_polyline_pen_points_16}


```
 draw_polyline(pen, points) 
```

Dessine la polyligne.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Stylo qui détermine la couleur, la largeur et le style de la figure. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Les points. |

### Method: draw_rectangle(pen, rectangle) {#draw_rectangle_pen_rectangle_17}


```
 draw_rectangle(pen, rectangle) 
```

Dessine le rectangle.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Stylo qui détermine la couleur, la largeur et le style de la figure. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle à dessiner. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_18}


```
 draw_rectangle(pen, x, y, width, height) 
```

Dessine le rectangle.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Stylo qui détermine la couleur, la largeur et le style de la figure. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle à dessiner. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle à dessiner. |
| width | int | La largeur du rectangle à dessiner. |
| height | int | La hauteur du rectangle à dessiner. |

### Method: draw_string(string, font, color, x, y) {#draw_string_string_font_color_x_y_19}


```
 draw_string(string, font, color, x, y) 
```

Dessine la chaîne.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| string | string | La chaîne. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Police qui définit le format texte de la chaîne. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | La couleur du texte. |
| x | int | La coordonnée x du coin supérieur gauche du texte dessiné. |
| y | int | La coordonnée y du coin supérieur gauche du texte dessiné. |

### Method: draw_string(string, font, color, x, y, angle) {#draw_string_string_font_color_x_y_angle_20}


```
 draw_string(string, font, color, x, y, angle) 
```

Dessine la chaîne.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| string | string | La chaîne. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Police qui définit le format texte de la chaîne. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | La couleur du texte. |
| x | int | La coordonnée x du coin supérieur gauche du texte dessiné. |
| y | int | La coordonnée y du coin supérieur gauche du texte dessiné. |
| angle | float | L'angle en degrés, entre le vecteur d'échappement et l'axe x de l'appareil.<br/>            Le vecteur d'échappement est parallèle à la ligne de base d'une rangée de texte. |

### Method: end_recording() {#end_recording__21}


```
 end_recording() 
```

Met fin à l'enregistrement.

**Returns**

| Type | Description |
| :- | :- |
| [EmfImage](/imaging/python-net/aspose.imaging.fileformats.emf/emfimage/) | L'image résultante. |


### Method: exclude_clip(rect) {#exclude_clip_rect_22}


```
 exclude_clip(rect) 
```

Met à jour la région de découpage de ce Graphics pour exclure la zone spécifiée par une structure Rectangle.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Structure de rectangle qui spécifie le rectangle à exclure de la région de découpage. |

### Method: exclude_clip(region) {#exclude_clip_region_23}


```
 exclude_clip(region) 
```

Met à jour la région de découpage de ce Graphics pour exclure la zone spécifiée par une Region.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Région qui spécifie la région à exclure de la région de découpage. |

### Method: exclude_clip_rect(rect) {#exclude_clip_rect_rect_24}


```
 exclude_clip_rect(rect) 
```

Met à jour la région de découpage de ce Graphics pour exclure la zone spécifiée par une structure Rectangle.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Structure de rectangle qui spécifie le rectangle à exclure de la région de découpage. |

### Method: exclude_clip_rgn(region) {#exclude_clip_rgn_region_25}


```
 exclude_clip_rgn(region) 
```

Met à jour la région de découpage de ce Graphics pour exclure la zone spécifiée par une Region.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Région qui spécifie la région à exclure de la région de découpage. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_26}


```
 fill_ellipse(brush, rect) 
```

Remplit l'ellipse.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pinceau qui détermine les caractéristiques du remplissage. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Les limites de l'ellipse. |

### Method: fill_path(pen, brush, path) {#fill_path_pen_brush_path_27}


```
 fill_path(pen, brush, path) 
```

Remplit le chemin.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Stylo qui détermine la couleur, la largeur et le style de la figure. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pinceau qui détermine les caractéristiques du remplissage. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Le chemin à remplir. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_28}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Remplit le secteur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pinceau qui détermine les caractéristiques du remplissage. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Les limites de l'ellipse. |
| start_angle | float | Angle en degrés mesuré dans le sens horaire depuis l'axe x jusqu'au point de départ de l'arc. |
| sweep_angle | float | Angle en degrés mesuré dans le sens horaire depuis le paramètre startAngle jusqu'au point final de l'arc. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_29}


```
 fill_polygon(brush, points) 
```

Remplit le polygone.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pinceau qui détermine les caractéristiques du remplissage. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Les points. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_30}


```
 fill_polygon(brush, points, fill_mode) 
```

Remplit le polygone.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pinceau qui détermine les caractéristiques du remplissage. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Les points. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Le mode de remplissage. |

### Method: fill_rectangle(brush, rectangle) {#fill_rectangle_brush_rectangle_31}


```
 fill_rectangle(brush, rectangle) 
```

Remplit le rectangle.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pinceau qui détermine les caractéristiques du remplissage. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle à remplir. |

### Method: from_emf_image(emf_image)  [static] {#from_emf_image_emf_image_32}


```
 from_emf_image(emf_image) 
```

Obtient une instance de [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) contenant tous les enregistrements de l'image Emf.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| emf_image | [EmfImage](/imaging/python-net/aspose.imaging.fileformats.emf/emfimage/) | L'image Emf dont il faut lire les enregistrements. |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) | Une instance de [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) |


### Method: get_transform() {#get_transform__33}


```
 get_transform() 
```

Obtient la transformation du monde.

**Returns**

| Type | Description |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La matrice de transformation. |


### Method: intersect_clip(rect) {#intersect_clip_rect_34}


```
 intersect_clip(rect) 
```

Met à jour la région de découpage de ce Graphics pour l'intersection de la région de découpage actuelle et de la structure Rectangle spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Structure de rectangle à intersecter avec la région de découpage actuelle. |

### Method: intersect_clip(region) {#intersect_clip_region_35}


```
 intersect_clip(region) 
```

Met à jour la région de découpage de ce Graphics pour l'intersection de la région de découpage actuelle et de la Region spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Région à intersecter avec la région actuelle. |

### Method: intersect_clip_rect_f(rect) {#intersect_clip_rect_f_rect_36}


```
 intersect_clip_rect_f(rect) 
```

Met à jour la région de découpage de ce Graphics pour l'intersection de la région de découpage actuelle et de la structure Rectangle spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Structure de rectangle à intersecter avec la région de découpage actuelle. |

### Method: intersect_clip_rgn(region) {#intersect_clip_rgn_region_37}


```
 intersect_clip_rgn(region) 
```

Met à jour la région de découpage de ce Graphics pour l'intersection de la région de découpage actuelle et de la Region spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Région à intersecter avec la région actuelle. |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_38}


```
 multiply_transform(matrix) 
```

Multiplie la transformation du monde de ce Graphics et spécifie la Matrix.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La matrice qui multiplie la transformation du monde. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_39}


```
 multiply_transform(matrix, order) 
```

Multiplie la transformation du monde de ce Graphics et spécifie la Matrix dans l'ordre spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La matrice qui multiplie la transformation du monde. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | L'ordre de la multiplication. |

### Method: rotate_transform(angle) {#rotate_transform_angle_40}


```
 rotate_transform(angle) 
```

Applique la rotation spécifiée à la matrice de transformation de cet objet Graphics.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | Angle de rotation en degrés. |

### Method: rotate_transform(angle, center, order) {#rotate_transform_angle_center_order_41}


```
 rotate_transform(angle, center, order) 
```

Applique la rotation spécifiée à la matrice de transformation de cet objet Graphics dans l'ordre spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | Angle de rotation en degrés. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Le centre de rotation. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Spécifie si la rotation est ajoutée ou préfixée à la transformation matricielle.. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_42}


```
 scale_transform(sx, sy) 
```

Applique l'opération de mise à l'échelle spécifiée à la matrice de transformation de cet objet Graphics en la préfixant à la matrice de transformation de l'objet.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| sx | float | Facteur d'échelle dans la direction x. |
| sy | float | Facteur d'échelle dans la direction y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_43}


```
 scale_transform(sx, sy, order) 
```

Applique l'opération de mise à l'échelle spécifiée à la matrice de transformation de cet objet Graphics dans l'ordre spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| sx | float | Facteur d'échelle dans la direction x. |
| sy | float | Facteur d'échelle dans la direction y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Spécifie si l'opération de mise à l'échelle est préfixée ou ajoutée à la matrice de transformation. |

### Method: set_transform(transform) {#set_transform_transform_44}


```
 set_transform(transform) 
```

Définit la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La nouvelle matrice de transformation. |

### Method: translate_transform(x, y) {#translate_transform_x_y_45}


```
 translate_transform(x, y) 
```

Modifie l'origine du système de coordonnées en préfixant la translation spécifiée à la matrice de transformation de cet objet Graphics.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x de la translation. |
| y | float | La coordonnée y de la translation. |

### Method: translate_transform(x, y, order) {#translate_transform_x_y_order_46}


```
 translate_transform(x, y, order) 
```

Modifie l'origine du système de coordonnées en appliquant la translation spécifiée à la matrice de transformation de cet objet Graphics dans l'ordre spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x de la translation. |
| y | float | La coordonnée y de la translation. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Spécifie si la translation est préfixée ou ajoutée à la matrice de transformation. |

## **Examples**
### This example shows how to create a EMF image and draw some geometric shapes on it using EmfRecorderGraphics2D. {#example_174}
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
# La taille de l'image en pixels
device_width: int = 600
device_height: int = 400
# La taille de l'image en millimètres
device_width_mm = device_width // 100
device_height_mm = device_height // 100
frame = Rectangle(0, 0, device_width, device_height)
# Créer une image EMF.
graphics = EmfRecorderGraphics2D(frame, Size(device_width, device_height), Size(device_width_mm, device_height_mm))
# Dessiner un rectangle noir le long des bordures de l'image en utilisant un stylo noir de 1 pixel de largeur.
graphics.draw_rectangle(Pen(Color.black, 1), 0, 0, device_width, device_height)
# Remplir un rectangle avec la couleur blanc fumé.
graphics.fill_rectangle(SolidBrush(Color.white_smoke), Rectangle(10, 10, 580, 380))
# Dessiner deux lignes diagonales en utilisant un stylo vert foncé de 1 pixel de largeur.
graphics.draw_line(Pen(Color.dark_green, 1), 0, 0, device_width, device_height)
graphics.draw_line(Pen(Color.dark_green, 1), 0, device_height, device_width, 0)
# Dessiner un arc à l'intérieur du rectangle {0, 0, 200, 200} en utilisant un stylo bleu de 2 pixels de largeur.
graphics.draw_arc(Pen(Color.blue, 2), Rectangle(0, 0, 200, 200), 90, 270)
# Remplir un arc
graphics.fill_pie(SolidBrush(Color.light_sky_blue), Rectangle(0, 0, 150, 150), 90, 270)
# Dessiner un Bézier cubique en utilisant un stylo rouge de 2 pixels de largeur.
graphics.draw_cubic_bezier(Pen(Color.red, 2), Point(0, 0), Point(200, 133), Point(400, 166), Point(600, 400))

# Dessiner une image raster de la taille spécifiée à l'emplacement spécifié.
# L'image est mise à l'échelle pour s'adapter au rectangle souhaité.
with aspycore.as_of(Image.load(join(dir_, "sample.bmp")), RasterImage) as image_to_draw:
	graphics.draw_image(image_to_draw, Rectangle(400, 200, 100, 50), Rectangle(0, 0, device_width, device_height), GraphicsUnit.PIXEL)

# Dessiner une chaîne de texte
graphics.draw_string("Hello World!", Font("Arial", 48, FontStyle.REGULAR), Color.dark_red, 200, 300)

# Créer un chemin à remplir
figure_to_fill = Figure()
figure_to_fill.is_closed = True
path_to_fill = GraphicsPath()
path_to_fill.add_figure(figure_to_fill)
figure_to_fill.add_shapes([ArcShape(Rectangle(400, 0, 200, 100), 45, 300), BezierShape([PointF(300, 200), PointF(400, 200), PointF(500, 100), PointF(600, 200)]), PolygonShape([PointF(300, 100)]), RectangleShape(RectangleF(0, 100, 200, 200))])

# Remplir le chemin en utilisant un pinceau jaune et un stylo vert pour dessiner le contour
graphics.fill_path(Pen(Color.green, 2), SolidBrushColor.yellow), path_to_fill)

# Créer un chemin à dessiner
path_to_draw = GraphicsPath()
figure_to_draw = Figure()
path_to_draw.add_figure(figure_to_draw)
figure_to_draw.add_shapes([ArcShape(RectangleF(200, 200, 200, 200), 0, 360)])

# Dessiner le chemin en utilisant un stylo orange de 5 pixels de largeur.
graphics.draw_path(Pen(Color.orange, 5), path_to_draw)

# Obtenir l'image WMF finale qui inclut toutes les commandes de dessin
with graphics.end_recording() as emf_image:
	emf_image.save(join(dir_, "test.output.emf"))


```

