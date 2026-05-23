---
title: "EmfRecorderGraphics2D Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/
---

**Summary:** The Emf recorder graphics

**Module:** [aspose.imaging.fileformats.emf.graphics](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/)

**Full Name:** aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D

**Inheritance:** MetafileRecorderGraphics2D

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfRecorderGraphics2D(frame, device_size, device_size_mm)](#EmfRecorderGraphics2D_frame_device_size_device_size_mm_1) | Initialisiert eine neue Instanz der [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Liest oder legt die Hintergrundfarbe fest. |
| background_mode | [EmfBackgroundMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfbackgroundmode/) | r/w | Liest oder legt den Hintergrundmodus fest. |
| clip | [Region](/imaging/python-net/aspose.imaging/region/) | r/w | Liest oder legt eine Region fest, die den Zeichenbereich dieses Graphics einschränkt |
| clip_bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Liest die Clip-Grenzen. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| clear() | Löscht den Zustand des Grafikobjekts |
| [draw_arc(pen, rect, start_angle, arc_angle)](#draw_arc_pen_rect_start_angle_arc_angle_1) | Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch eine Rechteckstruktur angegeben ist. |
| [draw_cubic_bezier(pen, pt1, pt2, pt3, pt4)](#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2) | Zeichnet die kubische Bézierkurve. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_3) | Zeichnet die Ellipse. |
| [draw_image(image, dest_rect, src_rect, src_unit)](#draw_image_image_dest_rect_src_rect_src_unit_4) | Zeichnet den angegebenen Teil des angegebenen Bildes an der angegebenen Position und mit der angegebenen Größe. |
| [draw_image(image, location)](#draw_image_image_location_5) | Zeichnet das angegebene Image, unter Verwendung seiner ursprünglichen physischen Größe, am angegebenen Ort. |
| [draw_image(image_bytes, dest_rect, src_unit)](#draw_image_image_bytes_dest_rect_src_unit_6) | Zeichnet das Image. |
| [draw_image(stream, dest_rect, src_unit)](#draw_image_stream_dest_rect_src_unit_7) | Zeichnet das Image. |
| [draw_image_from_bytes(image_bytes, dest_rect, src_unit)](#draw_image_from_bytes_image_bytes_dest_rect_src_unit_8) | Zeichnet das Image. |
| [draw_image_from_stream(stream, dest_rect, src_unit)](#draw_image_from_stream_stream_dest_rect_src_unit_9) | Zeichnet das Image. |
| [draw_line(pen, pt1, pt2)](#draw_line_pen_pt1_pt2_10) | Zeichnet die Linie. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_11) | Zeichnet die Linie. |
| [draw_path(pen, path)](#draw_path_pen_path_12) | Zeichnet den Pfad. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_13) | Zeichnet das Kuchenstück. |
| [draw_poly_cubic_bezier(pen, points)](#draw_poly_cubic_bezier_pen_points_14) | Zeichnet die polykubische Bezierkurve. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_15) | Zeichnet das Polygon. |
| [draw_polyline(pen, points)](#draw_polyline_pen_points_16) | Zeichnet die Polylinie. |
| [draw_rectangle(pen, rectangle)](#draw_rectangle_pen_rectangle_17) | Zeichnet das Rechteck. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_18) | Zeichnet das Rechteck. |
| [draw_string(string, font, color, x, y)](#draw_string_string_font_color_x_y_19) | Zeichnet die Zeichenkette. |
| [draw_string(string, font, color, x, y, angle)](#draw_string_string_font_color_x_y_angle_20) | Zeichnet die Zeichenkette. |
| [end_recording()](#end_recording__21) | Beendet die Aufnahme. |
| [exclude_clip(rect)](#exclude_clip_rect_22) | Aktualisiert den Clip-Bereich dieses Graphics, um den durch eine Rectangle-Struktur angegebenen Bereich auszuschließen. |
| [exclude_clip(region)](#exclude_clip_region_23) | Aktualisiert den Clip-Bereich dieses Graphics, um den durch eine Region angegebenen Bereich auszuschließen. |
| [exclude_clip_rect(rect)](#exclude_clip_rect_rect_24) | Aktualisiert den Clip-Bereich dieses Graphics, um den durch eine Rectangle-Struktur angegebenen Bereich auszuschließen. |
| [exclude_clip_rgn(region)](#exclude_clip_rgn_region_25) | Aktualisiert den Clip-Bereich dieses Graphics, um den durch eine Region angegebenen Bereich auszuschließen. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_26) | Füllt die Ellipse. |
| [fill_path(pen, brush, path)](#fill_path_pen_brush_path_27) | Füllt den Pfad. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_28) | Füllt das Kuchenstück. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_29) | Füllt das Polygon. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_30) | Füllt das Polygon. |
| [fill_rectangle(brush, rectangle)](#fill_rectangle_brush_rectangle_31) | Füllt das Rechteck. |
| [from_emf_image(emf_image)](#from_emf_image_emf_image_32) | Gibt eine Instanz der [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) zurück, die alle Datensätze aus dem Emf-Bild enthält. |
| [get_transform()](#get_transform__33) | Erhält die Welt-Transformation. |
| [intersect_clip(rect)](#intersect_clip_rect_34) | Aktualisiert den Clip-Bereich dieses Graphics zur Schnittmenge des aktuellen Clip-Bereichs und der angegebenen Rectangle-Struktur. |
| [intersect_clip(region)](#intersect_clip_region_35) | Aktualisiert den Clip-Bereich dieses Graphics zur Schnittmenge des aktuellen Clip-Bereichs und der angegebenen Region. |
| [intersect_clip_rect_f(rect)](#intersect_clip_rect_f_rect_36) | Aktualisiert den Clip-Bereich dieses Graphics zur Schnittmenge des aktuellen Clip-Bereichs und der angegebenen Rectangle-Struktur. |
| [intersect_clip_rgn(region)](#intersect_clip_rgn_region_37) | Aktualisiert den Clip-Bereich dieses Graphics zur Schnittmenge des aktuellen Clip-Bereichs und der angegebenen Region. |
| [multiply_transform(matrix)](#multiply_transform_matrix_38) | Multipliziert die Welt-Transformation dieses Graphics mit der angegebenen Matrix. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_39) | Multipliziert die Welt-Transformation dieses Graphics mit der angegebenen Matrix in der angegebenen Reihenfolge. |
| reset_clip() | Setzt den Clip zurück. |
| [rotate_transform(angle)](#rotate_transform_angle_40) | Wendet die angegebene Drehung auf die Transformationsmatrix dieses Graphics an. |
| [rotate_transform(angle, center, order)](#rotate_transform_angle_center_order_41) | Wendet die angegebene Drehung in der angegebenen Reihenfolge auf die Transformationsmatrix dieses Graphics an. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_42) | Wendet die angegebene Skalierungsoperation auf die Transformationsmatrix dieses Graphics an, indem sie dieser Transformationsmatrix vorangestellt wird. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_43) | Wendet die angegebene Skalierungsoperation in der angegebenen Reihenfolge auf die Transformationsmatrix dieses Graphics an. |
| [set_transform(transform)](#set_transform_transform_44) | Setzt die Transformation. |
| [translate_transform(x, y)](#translate_transform_x_y_45) | Ändert den Ursprung des Koordinatensystems, indem die angegebene Verschiebung der Transformationsmatrix dieses Graphics vorangestellt wird. |
| [translate_transform(x, y, order)](#translate_transform_x_y_order_46) | Ändert den Ursprung des Koordinatensystems, indem die angegebene Verschiebung in der angegebenen Reihenfolge auf die Transformationsmatrix dieses Graphics angewendet wird. |


### Constructor: EmfRecorderGraphics2D(frame, device_size, device_size_mm) {#EmfRecorderGraphics2D_frame_device_size_device_size_mm_1}


```
 EmfRecorderGraphics2D(frame, device_size, device_size_mm) 
```

Initialisiert eine neue Instanz der [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| frame | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Rahmen. |
| device_size | [Size](/imaging/python-net/aspose.imaging/size/) | Größe des Geräts. |
| device_size_mm | [Size](/imaging/python-net/aspose.imaging/size/) | Die Gerätgröße in mm. |


**See also:**

**[Example # 1](#example_174)**: This example shows how to create a EMF image and draw some geometric shapes o...


### Method: draw_arc(pen, rect, start_angle, arc_angle) {#draw_arc_pen_rect_start_angle_arc_angle_1}


```
 draw_arc(pen, rect, start_angle, arc_angle) 
```

Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch eine Rechteckstruktur angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Die Grenzen der Ellipse. |
| start_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| arc_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom Parameter startAngle bis zum Endpunkt des Bogens. |

### Method: draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) {#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2}


```
 draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) 
```

Zeichnet die kubische Bézierkurve.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | Der Startpunkt der Kurve. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | Der erste Kontrollpunkt der Kurve. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | Der zweite Kontrollpunkt der Kurve. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | Der Endpunkt der Kurve. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_3}


```
 draw_ellipse(pen, rect) 
```

Zeichnet die Ellipse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Die Grenzen der Ellipse. |

### Method: draw_image(image, dest_rect, src_rect, src_unit) {#draw_image_image_dest_rect_src_rect_src_unit_4}


```
 draw_image(image, dest_rect, src_rect, src_unit) 
```

Zeichnet den angegebenen Teil des angegebenen Bildes an der angegebenen Position und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das Bild zum Zeichnen. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rechteckstruktur, die den Ort und die Größe des gezeichneten Bildes angibt. Das Bild wird skaliert, um in das Rechteck zu passen. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rechteckstruktur, die den Teil des Bildobjekts angibt, der gezeichnet werden soll. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Maßeinheiten, die vom Parameter srcRect verwendet werden. |

### Method: draw_image(image, location) {#draw_image_image_location_5}


```
 draw_image(image, location) 
```

Zeichnet das angegebene Image, unter Verwendung seiner ursprünglichen physischen Größe, am angegebenen Ort.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das Bild zum Zeichnen. |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | Der Ort der oberen linken Ecke des gezeichneten Bildes. |

### Method: draw_image(image_bytes, dest_rect, src_unit) {#draw_image_image_bytes_dest_rect_src_unit_6}


```
 draw_image(image_bytes, dest_rect, src_unit) 
```

Zeichnet das Image.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_bytes | System.Byte | Die Bildbytes. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Zielrechteck. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Quelleneinheit. |

### Method: draw_image(stream, dest_rect, src_unit) {#draw_image_stream_dest_rect_src_unit_7}


```
 draw_image(stream, dest_rect, src_unit) 
```

Zeichnet das Image.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Zielrechteck. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Quelleneinheit. |

### Method: draw_image_from_bytes(image_bytes, dest_rect, src_unit) {#draw_image_from_bytes_image_bytes_dest_rect_src_unit_8}


```
 draw_image_from_bytes(image_bytes, dest_rect, src_unit) 
```

Zeichnet das Image.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_bytes | System.Byte | Die Bildbytes. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Zielrechteck. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Quelleneinheit. |

### Method: draw_image_from_stream(stream, dest_rect, src_unit) {#draw_image_from_stream_stream_dest_rect_src_unit_9}


```
 draw_image_from_stream(stream, dest_rect, src_unit) 
```

Zeichnet das Image.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Zielrechteck. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Quelleneinheit. |

### Method: draw_line(pen, pt1, pt2) {#draw_line_pen_pt1_pt2_10}


```
 draw_line(pen, pt1, pt2) 
```

Zeichnet die Linie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | Der erste Punkt. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | Der zweite Punkt. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_11}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Zeichnet die Linie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| x1 | int | Die x-Koordinate des ersten Punktes. |
| y1 | int | Die y-Koordinate des ersten Punktes. |
| x2 | int | Die x-Koordinate des zweiten Punktes. |
| y2 | int | Die y-Koordinate des zweiten Punktes. |

### Method: draw_path(pen, path) {#draw_path_pen_path_12}


```
 draw_path(pen, path) 
```

Zeichnet den Pfad.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Der Pfad zum Zeichnen. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_13}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Zeichnet das Kuchenstück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Die Grenzen der Ellipse. |
| start_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| sweep_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom Parameter startAngle bis zum Endpunkt des Bogens. |

### Method: draw_poly_cubic_bezier(pen, points) {#draw_poly_cubic_bezier_pen_points_14}


```
 draw_poly_cubic_bezier(pen, points) 
```

Zeichnet die polykubische Bezierkurve.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Die Punkte. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_15}


```
 draw_polygon(pen, points) 
```

Zeichnet das Polygon.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Die Punkte. |

### Method: draw_polyline(pen, points) {#draw_polyline_pen_points_16}


```
 draw_polyline(pen, points) 
```

Zeichnet die Polylinie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Die Punkte. |

### Method: draw_rectangle(pen, rectangle) {#draw_rectangle_pen_rectangle_17}


```
 draw_rectangle(pen, rectangle) 
```

Zeichnet das Rechteck.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck zum Zeichnen. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_18}


```
 draw_rectangle(pen, x, y, width, height) 
```

Zeichnet das Rechteck.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| x | int | Die x-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| y | int | Die y-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| width | int | Die Breite des zu zeichnenden Rechtecks. |
| height | int | Die Höhe des zu zeichnenden Rechtecks. |

### Method: draw_string(string, font, color, x, y) {#draw_string_string_font_color_x_y_19}


```
 draw_string(string, font, color, x, y) 
```

Zeichnet die Zeichenkette.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| string | string | Die Zeichenkette. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Schriftart, die das Textformat der Zeichenkette definiert. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Die Textfarbe. |
| x | int | Die x-Koordinate der oberen linken Ecke des gezeichneten Textes. |
| y | int | Die y-Koordinate der oberen linken Ecke des gezeichneten Textes. |

### Method: draw_string(string, font, color, x, y, angle) {#draw_string_string_font_color_x_y_angle_20}


```
 draw_string(string, font, color, x, y, angle) 
```

Zeichnet die Zeichenkette.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| string | string | Die Zeichenkette. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Schriftart, die das Textformat der Zeichenkette definiert. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Die Textfarbe. |
| x | int | Die x-Koordinate der oberen linken Ecke des gezeichneten Textes. |
| y | int | Die y-Koordinate der oberen linken Ecke des gezeichneten Textes. |
| angle | float | Der Winkel in Grad, zwischen dem Escapement-Vektor und der x-Achse des Geräts. <br/>            Der Escapement-Vektor ist parallel zur Grundlinie einer Textzeile. |

### Method: end_recording() {#end_recording__21}


```
 end_recording() 
```

Beendet die Aufnahme.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [EmfImage](/imaging/python-net/aspose.imaging.fileformats.emf/emfimage/) | Das Ergebnisbild. |


### Method: exclude_clip(rect) {#exclude_clip_rect_22}


```
 exclude_clip(rect) 
```

Aktualisiert den Clip-Bereich dieses Graphics, um den durch eine Rectangle-Struktur angegebenen Bereich auszuschließen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rechteckstruktur, die das Rechteck angibt, das vom Clip-Bereich ausgeschlossen werden soll. |

### Method: exclude_clip(region) {#exclude_clip_region_23}


```
 exclude_clip(region) 
```

Aktualisiert den Clip-Bereich dieses Graphics, um den durch eine Region angegebenen Bereich auszuschließen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Region, die den Bereich angibt, der vom Clip-Bereich ausgeschlossen werden soll. |

### Method: exclude_clip_rect(rect) {#exclude_clip_rect_rect_24}


```
 exclude_clip_rect(rect) 
```

Aktualisiert den Clip-Bereich dieses Graphics, um den durch eine Rectangle-Struktur angegebenen Bereich auszuschließen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rechteckstruktur, die das Rechteck angibt, das vom Clip-Bereich ausgeschlossen werden soll. |

### Method: exclude_clip_rgn(region) {#exclude_clip_rgn_region_25}


```
 exclude_clip_rgn(region) 
```

Aktualisiert den Clip-Bereich dieses Graphics, um den durch eine Region angegebenen Bereich auszuschließen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Region, die den Bereich angibt, der vom Clip-Bereich ausgeschlossen werden soll. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_26}


```
 fill_ellipse(brush, rect) 
```

Füllt die Ellipse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pinsel, der die Eigenschaften der Füllung bestimmt. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Die Grenzen der Ellipse. |

### Method: fill_path(pen, brush, path) {#fill_path_pen_brush_path_27}


```
 fill_path(pen, brush, path) 
```

Füllt den Pfad.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pinsel, der die Eigenschaften der Füllung bestimmt. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Der Pfad zum Füllen. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_28}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Füllt das Kuchenstück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pinsel, der die Eigenschaften der Füllung bestimmt. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Die Grenzen der Ellipse. |
| start_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| sweep_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom Parameter startAngle bis zum Endpunkt des Bogens. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_29}


```
 fill_polygon(brush, points) 
```

Füllt das Polygon.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pinsel, der die Eigenschaften der Füllung bestimmt. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Die Punkte. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_30}


```
 fill_polygon(brush, points, fill_mode) 
```

Füllt das Polygon.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pinsel, der die Eigenschaften der Füllung bestimmt. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Die Punkte. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Der Füllmodus. |

### Method: fill_rectangle(brush, rectangle) {#fill_rectangle_brush_rectangle_31}


```
 fill_rectangle(brush, rectangle) 
```

Füllt das Rechteck.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pinsel, der die Eigenschaften der Füllung bestimmt. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Rechteck zum Füllen. |

### Method: from_emf_image(emf_image)  [static] {#from_emf_image_emf_image_32}


```
 from_emf_image(emf_image) 
```

Gibt eine Instanz der [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) zurück, die alle Datensätze aus dem Emf-Bild enthält.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| emf_image | [EmfImage](/imaging/python-net/aspose.imaging.fileformats.emf/emfimage/) | Das Emf-Bild, aus dem Datensätze gelesen werden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) | Eine Instanz der [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) |


### Method: get_transform() {#get_transform__33}


```
 get_transform() 
```

Erhält die Welt-Transformation.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Die Transformationsmatrix. |


### Method: intersect_clip(rect) {#intersect_clip_rect_34}


```
 intersect_clip(rect) 
```

Aktualisiert den Clip-Bereich dieses Graphics zur Schnittmenge des aktuellen Clip-Bereichs und der angegebenen Rectangle-Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Rechteckstruktur, die mit dem aktuellen Clip-Bereich geschnitten wird. |

### Method: intersect_clip(region) {#intersect_clip_region_35}


```
 intersect_clip(region) 
```

Aktualisiert den Clip-Bereich dieses Graphics zur Schnittmenge des aktuellen Clip-Bereichs und der angegebenen Region.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Region, die mit dem aktuellen Bereich geschnitten wird. |

### Method: intersect_clip_rect_f(rect) {#intersect_clip_rect_f_rect_36}


```
 intersect_clip_rect_f(rect) 
```

Aktualisiert den Clip-Bereich dieses Graphics zur Schnittmenge des aktuellen Clip-Bereichs und der angegebenen Rectangle-Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Rechteckstruktur, die mit dem aktuellen Clip-Bereich geschnitten wird. |

### Method: intersect_clip_rgn(region) {#intersect_clip_rgn_region_37}


```
 intersect_clip_rgn(region) 
```

Aktualisiert den Clip-Bereich dieses Graphics zur Schnittmenge des aktuellen Clip-Bereichs und der angegebenen Region.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Region, die mit dem aktuellen Bereich geschnitten wird. |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_38}


```
 multiply_transform(matrix) 
```

Multipliziert die Welt-Transformation dieses Graphics mit der angegebenen Matrix.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Die Matrix, die die Welttransformation multipliziert. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_39}


```
 multiply_transform(matrix, order) 
```

Multipliziert die Welt-Transformation dieses Graphics mit der angegebenen Matrix in der angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Die Matrix, die die Welttransformation multipliziert. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Die Reihenfolge der Multiplikation. |

### Method: rotate_transform(angle) {#rotate_transform_angle_40}


```
 rotate_transform(angle) 
```

Wendet die angegebene Drehung auf die Transformationsmatrix dieses Graphics an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Winkel der Drehung in Grad. |

### Method: rotate_transform(angle, center, order) {#rotate_transform_angle_center_order_41}


```
 rotate_transform(angle, center, order) 
```

Wendet die angegebene Drehung in der angegebenen Reihenfolge auf die Transformationsmatrix dieses Graphics an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Winkel der Drehung in Grad. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Das Rotationszentrum. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Gibt an, ob die Drehung an die Matrixtransformation angehängt oder vorangestellt wird.. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_42}


```
 scale_transform(sx, sy) 
```

Wendet die angegebene Skalierungsoperation auf die Transformationsmatrix dieses Graphics an, indem sie dieser Transformationsmatrix vorangestellt wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| sx | float | Skalierungsfaktor in x-Richtung. |
| sy | float | Skalierungsfaktor in y-Richtung. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_43}


```
 scale_transform(sx, sy, order) 
```

Wendet die angegebene Skalierungsoperation in der angegebenen Reihenfolge auf die Transformationsmatrix dieses Graphics an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| sx | float | Skalierungsfaktor in x-Richtung. |
| sy | float | Skalierungsfaktor in y-Richtung. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Gibt an, ob die Skalierungsoperation an die Transformationsmatrix vorangestellt oder angehängt wird. |

### Method: set_transform(transform) {#set_transform_transform_44}


```
 set_transform(transform) 
```

Setzt die Transformation.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Die neue Transformationsmatrix. |

### Method: translate_transform(x, y) {#translate_transform_x_y_45}


```
 translate_transform(x, y) 
```

Ändert den Ursprung des Koordinatensystems, indem die angegebene Verschiebung der Transformationsmatrix dieses Graphics vorangestellt wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | float | Die x-Koordinate der Translation. |
| y | float | Die y-Koordinate der Translation. |

### Method: translate_transform(x, y, order) {#translate_transform_x_y_order_46}


```
 translate_transform(x, y, order) 
```

Ändert den Ursprung des Koordinatensystems, indem die angegebene Verschiebung in der angegebenen Reihenfolge auf die Transformationsmatrix dieses Graphics angewendet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | float | Die x-Koordinate der Translation. |
| y | float | Die y-Koordinate der Translation. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Gibt an, ob die Translation an die Transformationsmatrix vorangestellt oder angehängt wird. |

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
# Die Bildgröße in Pixeln
device_width: int = 600
device_height: int = 400
# Die Bildgröße in Millimetern
device_width_mm = device_width // 100
device_height_mm = device_height // 100
frame = Rectangle(0, 0, device_width, device_height)
# Erstelle ein EMF-Bild.
graphics = EmfRecorderGraphics2D(frame, Size(device_width, device_height), Size(device_width_mm, device_height_mm))
# Zeichne ein schwarzes Rechteck entlang der Bildränder mit einem 1-pixel-wide schwarzen Stift.
graphics.draw_rectangle(Pen(Color.black, 1), 0, 0, device_width, device_height)
# Fülle ein Rechteck mit der Farbe white-smoke.
graphics.fill_rectangle(SolidBrush(Color.white_smoke), Rectangle(10, 10, 580, 380))
# Zeichne zwei diagonale Linien mit einem 1-pixel-wide darkgreen Stift.
graphics.draw_line(Pen(Color.dark_green, 1), 0, 0, device_width, device_height)
graphics.draw_line(Pen(Color.dark_green, 1), 0, device_height, device_width, 0)
# Zeichne einen Bogen innerhalb des Rechtecks {0, 0, 200, 200} mit einem 2-pixel-wide blauen Stift.
graphics.draw_arc(Pen(Color.blue, 2), Rectangle(0, 0, 200, 200), 90, 270)
# Fülle einen Bogen
graphics.fill_pie(SolidBrush(Color.light_sky_blue), Rectangle(0, 0, 150, 150), 90, 270)
# Zeichne ein kubisches Bézier mit einem 2-pixel-wide roten Stift.
graphics.draw_cubic_bezier(Pen(Color.red, 2), Point(0, 0), Point(200, 133), Point(400, 166), Point(600, 400))

# Zeichne ein Rasterbild der angegebenen Größe am angegebenen Ort.
# Das Bild wird skaliert, um das gewünschte Rechteck zu füllen.
with aspycore.as_of(Image.load(join(dir_, "sample.bmp")), RasterImage) as image_to_draw:
	graphics.draw_image(image_to_draw, Rectangle(400, 200, 100, 50), Rectangle(0, 0, device_width, device_height), GraphicsUnit.PIXEL)

# Zeichne eine Textzeichenkette
graphics.draw_string("Hello World!", Font("Arial", 48, FontStyle.REGULAR), Color.dark_red, 200, 300)

# Erstelle einen Pfad zum Füllen
figure_to_fill = Figure()
figure_to_fill.is_closed = True
path_to_fill = GraphicsPath()
path_to_fill.add_figure(figure_to_fill)
figure_to_fill.add_shapes([ArcShape(Rectangle(400, 0, 200, 100), 45, 300), BezierShape([PointF(300, 200), PointF(400, 200), PointF(500, 100), PointF(600, 200)]), PolygonShape([PointF(300, 100)]), RectangleShape(RectangleF(0, 100, 200, 200))])

# Fülle den Pfad mit einem gelben Pinsel und einem grünen Stift, um die Kontur zu zeichnen
graphics.fill_path(Pen(Color.green, 2), SolidBrushColor.yellow), path_to_fill)

# Erstelle einen Pfad zum Zeichnen
path_to_draw = GraphicsPath()
figure_to_draw = Figure()
path_to_draw.add_figure(figure_to_draw)
figure_to_draw.add_shapes([ArcShape(RectangleF(200, 200, 200, 200), 0, 360)])

# Zeichne den Pfad mit einem 5-pixel-wide orangefarbenen Stift.
graphics.draw_path(Pen(Color.orange, 5), path_to_draw)

# Erhalte das endgültige WMF-Bild, das alle Zeichenbefehle enthält
with graphics.end_recording() as emf_image:
	emf_image.save(join(dir_, "test.output.emf"))


```

