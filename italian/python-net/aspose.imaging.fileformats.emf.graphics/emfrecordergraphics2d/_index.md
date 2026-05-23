---
title: "Classe EmfRecorderGraphics2D"
type: docs
weight: 10
url: /it/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/
---

**Summary:** The Emf recorder graphics

**Module:** [aspose.imaging.fileformats.emf.graphics](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/)

**Full Name:** aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D

**Inheritance:** MetafileRecorderGraphics2D

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfRecorderGraphics2D(frame, device_size, device_size_mm)](#EmfRecorderGraphics2D_frame_device_size_device_size_mm_1) | Inizializza una nuova istanza della classe [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Ottiene o imposta il colore dello sfondo. |
| background_mode | [EmfBackgroundMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfbackgroundmode/) | r/w | Ottiene o imposta la modalità di sfondo. |
| clip | [Region](/imaging/python-net/aspose.imaging/region/) | r/w | Ottiene o imposta una Regione che limita l'area di disegno di questo Graphics |
| clip_bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Ottiene i limiti di ritaglio. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| clear() | Cancella lo stato dell'oggetto graphics |
| [draw_arc(pen, rect, start_angle, arc_angle)](#draw_arc_pen_rect_start_angle_arc_angle_1) | Disegna un arco che rappresenta una porzione di un'ellisse specificata da una struttura Rectangle. |
| [draw_cubic_bezier(pen, pt1, pt2, pt3, pt4)](#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2) | Disegna la curva Bézier cubica. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_3) | Disegna l'ellisse. |
| [draw_image(image, dest_rect, src_rect, src_unit)](#draw_image_image_dest_rect_src_rect_src_unit_4) | Disegna la porzione specificata dell'Image specificata nella posizione specificata e con le dimensioni specificate. |
| [draw_image(image, location)](#draw_image_image_location_5) | Disegna l'Image specificata, usando la sua dimensione fisica originale, nella posizione specificata. |
| [draw_image(image_bytes, dest_rect, src_unit)](#draw_image_image_bytes_dest_rect_src_unit_6) | Disegna l'immagine. |
| [draw_image(stream, dest_rect, src_unit)](#draw_image_stream_dest_rect_src_unit_7) | Disegna l'immagine. |
| [draw_image_from_bytes(image_bytes, dest_rect, src_unit)](#draw_image_from_bytes_image_bytes_dest_rect_src_unit_8) | Disegna l'immagine. |
| [draw_image_from_stream(stream, dest_rect, src_unit)](#draw_image_from_stream_stream_dest_rect_src_unit_9) | Disegna l'immagine. |
| [draw_line(pen, pt1, pt2)](#draw_line_pen_pt1_pt2_10) | Disegna la linea. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_11) | Disegna la linea. |
| [draw_path(pen, path)](#draw_path_pen_path_12) | Disegna il percorso. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_13) | Disegna la torta. |
| [draw_poly_cubic_bezier(pen, points)](#draw_poly_cubic_bezier_pen_points_14) | Disegna il bezier cubico poligonale. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_15) | Disegna il poligono. |
| [draw_polyline(pen, points)](#draw_polyline_pen_points_16) | Disegna la polilinea. |
| [draw_rectangle(pen, rectangle)](#draw_rectangle_pen_rectangle_17) | Disegna il rettangolo. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_18) | Disegna il rettangolo. |
| [draw_string(string, font, color, x, y)](#draw_string_string_font_color_x_y_19) | Disegna la stringa. |
| [draw_string(string, font, color, x, y, angle)](#draw_string_string_font_color_x_y_angle_20) | Disegna la stringa. |
| [end_recording()](#end_recording__21) | Termina la registrazione. |
| [exclude_clip(rect)](#exclude_clip_rect_22) | Aggiorna la regione di ritaglio di questo Graphics per escludere l'area specificata da una struttura Rectangle. |
| [exclude_clip(region)](#exclude_clip_region_23) | Aggiorna la regione di ritaglio di questo Graphics per escludere l'area specificata da una Region. |
| [exclude_clip_rect(rect)](#exclude_clip_rect_rect_24) | Aggiorna la regione di ritaglio di questo Graphics per escludere l'area specificata da una struttura Rectangle. |
| [exclude_clip_rgn(region)](#exclude_clip_rgn_region_25) | Aggiorna la regione di ritaglio di questo Graphics per escludere l'area specificata da una Region. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_26) | Riempie l'ellisse. |
| [fill_path(pen, brush, path)](#fill_path_pen_brush_path_27) | Riempie il percorso. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_28) | Riempie la torta. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_29) | Riempie il poligono. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_30) | Riempie il poligono. |
| [fill_rectangle(brush, rectangle)](#fill_rectangle_brush_rectangle_31) | Riempie il rettangolo. |
| [from_emf_image(emf_image)](#from_emf_image_emf_image_32) | Ottiene un'istanza di [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) contenente tutti i record dell'immagine Emf. |
| [get_transform()](#get_transform__33) | Ottiene la trasformazione del mondo. |
| [intersect_clip(rect)](#intersect_clip_rect_34) | Aggiorna la regione di ritaglio di questo Graphics all'intersezione della regione di ritaglio corrente e della struttura Rectangle specificata. |
| [intersect_clip(region)](#intersect_clip_region_35) | Aggiorna la regione di ritaglio di questo Graphics all'intersezione della regione di ritaglio corrente e della Region specificata. |
| [intersect_clip_rect_f(rect)](#intersect_clip_rect_f_rect_36) | Aggiorna la regione di ritaglio di questo Graphics all'intersezione della regione di ritaglio corrente e della struttura Rectangle specificata. |
| [intersect_clip_rgn(region)](#intersect_clip_rgn_region_37) | Aggiorna la regione di ritaglio di questo Graphics all'intersezione della regione di ritaglio corrente e della Region specificata. |
| [multiply_transform(matrix)](#multiply_transform_matrix_38) | Moltiplica la trasformazione del mondo di questo Graphics per la Matrix specificata. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_39) | Moltiplica la trasformazione del mondo di questo Graphics per la Matrix specificata nell'ordine specificato. |
| reset_clip() | Ripristina il ritaglio. |
| [rotate_transform(angle)](#rotate_transform_angle_40) | Applica la rotazione specificata alla matrice di trasformazione di questo Graphics. |
| [rotate_transform(angle, center, order)](#rotate_transform_angle_center_order_41) | Applica la rotazione specificata alla matrice di trasformazione di questo Graphics nell'ordine specificato. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_42) | Applica l'operazione di scaling specificata alla matrice di trasformazione di questo Graphics anteponendola alla matrice di trasformazione dell'oggetto. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_43) | Applica l'operazione di scaling specificata alla matrice di trasformazione di questo Graphics nell'ordine specificato. |
| [set_transform(transform)](#set_transform_transform_44) | Imposta la trasformazione. |
| [translate_transform(x, y)](#translate_transform_x_y_45) | Modifica l'origine del sistema di coordinate anteponendo la traslazione specificata alla matrice di trasformazione di questo Graphics. |
| [translate_transform(x, y, order)](#translate_transform_x_y_order_46) | Modifica l'origine del sistema di coordinate applicando la traslazione specificata alla matrice di trasformazione di questo Graphics nell'ordine specificato. |


### Constructor: EmfRecorderGraphics2D(frame, device_size, device_size_mm) {#EmfRecorderGraphics2D_frame_device_size_device_size_mm_1}


```
 EmfRecorderGraphics2D(frame, device_size, device_size_mm) 
```

Inizializza una nuova istanza della classe [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| frame | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il fotogramma. |
| device_size | [Size](/imaging/python-net/aspose.imaging/size/) | Dimensione del dispositivo. |
| device_size_mm | [Size](/imaging/python-net/aspose.imaging/size/) | La dimensione del dispositivo in mm. |


**See also:**

**[Example # 1](#example_174)**: This example shows how to create a EMF image and draw some geometric shapes o...


### Method: draw_arc(pen, rect, start_angle, arc_angle) {#draw_arc_pen_rect_start_angle_arc_angle_1}


```
 draw_arc(pen, rect, start_angle, arc_angle) 
```

Disegna un arco che rappresenta una porzione di un'ellisse specificata da una struttura Rectangle.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Penna che determina il colore, la larghezza e lo stile della figura. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | I confini dell'ellisse. |
| start_angle | float | Angolo in gradi misurato in senso orario dall'asse x al punto di partenza dell'arco. |
| arc_angle | float | Angolo in gradi misurato in senso orario dal parametro startAngle al punto finale dell'arco. |

### Method: draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) {#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2}


```
 draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) 
```

Disegna la curva Bézier cubica.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Penna che determina il colore, la larghezza e lo stile della figura. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | Il punto di partenza della curva. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | Il primo punto di controllo per la curva. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | Il secondo punto di controllo per la curva. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | Il punto finale della curva. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_3}


```
 draw_ellipse(pen, rect) 
```

Disegna l'ellisse.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Penna che determina il colore, la larghezza e lo stile della figura. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | I confini dell'ellisse. |

### Method: draw_image(image, dest_rect, src_rect, src_unit) {#draw_image_image_dest_rect_src_rect_src_unit_4}


```
 draw_image(image, dest_rect, src_rect, src_unit) 
```

Disegna la porzione specificata dell'Image specificata nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine da disegnare. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Struttura Rectangle che specifica la posizione e le dimensioni dell'immagine disegnata. L'immagine è scalata per adattarsi al rettangolo. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Struttura Rectangle che specifica la porzione dell'oggetto immagine da disegnare. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Le unità di misura utilizzate dal parametro srcRect. |

### Method: draw_image(image, location) {#draw_image_image_location_5}


```
 draw_image(image, location) 
```

Disegna l'Image specificata, usando la sua dimensione fisica originale, nella posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine da disegnare. |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | La posizione dell'angolo superiore sinistro dell'immagine disegnata. |

### Method: draw_image(image_bytes, dest_rect, src_unit) {#draw_image_image_bytes_dest_rect_src_unit_6}


```
 draw_image(image_bytes, dest_rect, src_unit) 
```

Disegna l'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image_bytes | System.Byte | I byte dell'immagine. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo di destinazione. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unità di origine. |

### Method: draw_image(stream, dest_rect, src_unit) {#draw_image_stream_dest_rect_src_unit_7}


```
 draw_image(stream, dest_rect, src_unit) 
```

Disegna l'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Lo stream. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo di destinazione. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unità di origine. |

### Method: draw_image_from_bytes(image_bytes, dest_rect, src_unit) {#draw_image_from_bytes_image_bytes_dest_rect_src_unit_8}


```
 draw_image_from_bytes(image_bytes, dest_rect, src_unit) 
```

Disegna l'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image_bytes | System.Byte | I byte dell'immagine. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo di destinazione. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unità di origine. |

### Method: draw_image_from_stream(stream, dest_rect, src_unit) {#draw_image_from_stream_stream_dest_rect_src_unit_9}


```
 draw_image_from_stream(stream, dest_rect, src_unit) 
```

Disegna l'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Lo stream. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo di destinazione. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unità di origine. |

### Method: draw_line(pen, pt1, pt2) {#draw_line_pen_pt1_pt2_10}


```
 draw_line(pen, pt1, pt2) 
```

Disegna la linea.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Penna che determina il colore, la larghezza e lo stile della figura. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | Il primo punto. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | Il secondo punto. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_11}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Disegna la linea.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Penna che determina il colore, la larghezza e lo stile della figura. |
| x1 | int | La coordinata x del primo punto. |
| y1 | int | La coordinata y del primo punto. |
| x2 | int | La coordinata x del secondo punto. |
| y2 | int | La coordinata y del secondo punto. |

### Method: draw_path(pen, path) {#draw_path_pen_path_12}


```
 draw_path(pen, path) 
```

Disegna il percorso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Penna che determina il colore, la larghezza e lo stile della figura. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Il percorso da disegnare. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_13}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Disegna la torta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Penna che determina il colore, la larghezza e lo stile della figura. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | I confini dell'ellisse. |
| start_angle | float | Angolo in gradi misurato in senso orario dall'asse x al punto di partenza dell'arco. |
| sweep_angle | float | Angolo in gradi misurato in senso orario dal parametro startAngle al punto finale dell'arco. |

### Method: draw_poly_cubic_bezier(pen, points) {#draw_poly_cubic_bezier_pen_points_14}


```
 draw_poly_cubic_bezier(pen, points) 
```

Disegna il bezier cubico poligonale.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Penna che determina il colore, la larghezza e lo stile della figura. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | I punti. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_15}


```
 draw_polygon(pen, points) 
```

Disegna il poligono.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Penna che determina il colore, la larghezza e lo stile della figura. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | I punti. |

### Method: draw_polyline(pen, points) {#draw_polyline_pen_points_16}


```
 draw_polyline(pen, points) 
```

Disegna la polilinea.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Penna che determina il colore, la larghezza e lo stile della figura. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | I punti. |

### Method: draw_rectangle(pen, rectangle) {#draw_rectangle_pen_rectangle_17}


```
 draw_rectangle(pen, rectangle) 
```

Disegna il rettangolo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Penna che determina il colore, la larghezza e lo stile della figura. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo da disegnare. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_18}


```
 draw_rectangle(pen, x, y, width, height) 
```

Disegna il rettangolo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Penna che determina il colore, la larghezza e lo stile della figura. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo da disegnare. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo da disegnare. |
| width | int | La larghezza del rettangolo da disegnare. |
| height | int | L'altezza del rettangolo da disegnare. |

### Method: draw_string(string, font, color, x, y) {#draw_string_string_font_color_x_y_19}


```
 draw_string(string, font, color, x, y) 
```

Disegna la stringa.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| string | string | La stringa. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Carattere che definisce il formato del testo della stringa. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Il colore del testo. |
| x | int | La coordinata x dell'angolo in alto a sinistra del testo disegnato. |
| y | int | La coordinata y dell'angolo in alto a sinistra del testo disegnato. |

### Method: draw_string(string, font, color, x, y, angle) {#draw_string_string_font_color_x_y_angle_20}


```
 draw_string(string, font, color, x, y, angle) 
```

Disegna la stringa.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| string | string | La stringa. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Carattere che definisce il formato del testo della stringa. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Il colore del testo. |
| x | int | La coordinata x dell'angolo in alto a sinistra del testo disegnato. |
| y | int | La coordinata y dell'angolo in alto a sinistra del testo disegnato. |
| angle | float | L'angolo in gradi, tra il vettore di escapement e l'asse x del dispositivo. <br/>            Il vettore di escapement è parallelo alla linea di base di una riga di testo. |

### Method: end_recording() {#end_recording__21}


```
 end_recording() 
```

Termina la registrazione.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [EmfImage](/imaging/python-net/aspose.imaging.fileformats.emf/emfimage/) | L'immagine risultante. |


### Method: exclude_clip(rect) {#exclude_clip_rect_22}


```
 exclude_clip(rect) 
```

Aggiorna la regione di ritaglio di questo Graphics per escludere l'area specificata da una struttura Rectangle.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Struttura rettangolo che specifica il rettangolo da escludere dalla regione di clip. |

### Method: exclude_clip(region) {#exclude_clip_region_23}


```
 exclude_clip(region) 
```

Aggiorna la regione di ritaglio di questo Graphics per escludere l'area specificata da una Region.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Regione che specifica la regione da escludere dalla regione di clip. |

### Method: exclude_clip_rect(rect) {#exclude_clip_rect_rect_24}


```
 exclude_clip_rect(rect) 
```

Aggiorna la regione di ritaglio di questo Graphics per escludere l'area specificata da una struttura Rectangle.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Struttura rettangolo che specifica il rettangolo da escludere dalla regione di clip. |

### Method: exclude_clip_rgn(region) {#exclude_clip_rgn_region_25}


```
 exclude_clip_rgn(region) 
```

Aggiorna la regione di ritaglio di questo Graphics per escludere l'area specificata da una Region.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Regione che specifica la regione da escludere dalla regione di clip. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_26}


```
 fill_ellipse(brush, rect) 
```

Riempie l'ellisse.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pennello che determina le caratteristiche del riempimento. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | I confini dell'ellisse. |

### Method: fill_path(pen, brush, path) {#fill_path_pen_brush_path_27}


```
 fill_path(pen, brush, path) 
```

Riempie il percorso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Penna che determina il colore, la larghezza e lo stile della figura. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pennello che determina le caratteristiche del riempimento. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Il percorso da riempire. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_28}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Riempie la torta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pennello che determina le caratteristiche del riempimento. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | I confini dell'ellisse. |
| start_angle | float | Angolo in gradi misurato in senso orario dall'asse x al punto di partenza dell'arco. |
| sweep_angle | float | Angolo in gradi misurato in senso orario dal parametro startAngle al punto finale dell'arco. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_29}


```
 fill_polygon(brush, points) 
```

Riempie il poligono.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pennello che determina le caratteristiche del riempimento. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | I punti. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_30}


```
 fill_polygon(brush, points, fill_mode) 
```

Riempie il poligono.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pennello che determina le caratteristiche del riempimento. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | I punti. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | La modalità di riempimento. |

### Method: fill_rectangle(brush, rectangle) {#fill_rectangle_brush_rectangle_31}


```
 fill_rectangle(brush, rectangle) 
```

Riempie il rettangolo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pennello che determina le caratteristiche del riempimento. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo da riempire. |

### Method: from_emf_image(emf_image)  [static] {#from_emf_image_emf_image_32}


```
 from_emf_image(emf_image) 
```

Ottiene un'istanza di [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) contenente tutti i record dell'immagine Emf.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| emf_image | [EmfImage](/imaging/python-net/aspose.imaging.fileformats.emf/emfimage/) | L'immagine Emf da cui leggere i record. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) | Un'istanza di [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) |


### Method: get_transform() {#get_transform__33}


```
 get_transform() 
```

Ottiene la trasformazione del mondo.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La matrice di trasformazione. |


### Method: intersect_clip(rect) {#intersect_clip_rect_34}


```
 intersect_clip(rect) 
```

Aggiorna la regione di ritaglio di questo Graphics all'intersezione della regione di ritaglio corrente e della struttura Rectangle specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Struttura rettangolo da intersecare con la regione di clip corrente. |

### Method: intersect_clip(region) {#intersect_clip_region_35}


```
 intersect_clip(region) 
```

Aggiorna la regione di ritaglio di questo Graphics all'intersezione della regione di ritaglio corrente e della Region specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Regione da intersecare con la regione corrente. |

### Method: intersect_clip_rect_f(rect) {#intersect_clip_rect_f_rect_36}


```
 intersect_clip_rect_f(rect) 
```

Aggiorna la regione di ritaglio di questo Graphics all'intersezione della regione di ritaglio corrente e della struttura Rectangle specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Struttura rettangolo da intersecare con la regione di clip corrente. |

### Method: intersect_clip_rgn(region) {#intersect_clip_rgn_region_37}


```
 intersect_clip_rgn(region) 
```

Aggiorna la regione di ritaglio di questo Graphics all'intersezione della regione di ritaglio corrente e della Region specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Regione da intersecare con la regione corrente. |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_38}


```
 multiply_transform(matrix) 
```

Moltiplica la trasformazione del mondo di questo Graphics per la Matrix specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La matrice che moltiplica la trasformazione globale. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_39}


```
 multiply_transform(matrix, order) 
```

Moltiplica la trasformazione del mondo di questo Graphics per la Matrix specificata nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La matrice che moltiplica la trasformazione globale. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | L'ordine della moltiplicazione. |

### Method: rotate_transform(angle) {#rotate_transform_angle_40}


```
 rotate_transform(angle) 
```

Applica la rotazione specificata alla matrice di trasformazione di questo Graphics.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angle | float | Angolo di rotazione in gradi. |

### Method: rotate_transform(angle, center, order) {#rotate_transform_angle_center_order_41}


```
 rotate_transform(angle, center, order) 
```

Applica la rotazione specificata alla matrice di trasformazione di questo Graphics nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angle | float | Angolo di rotazione in gradi. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Il centro di rotazione. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Specifica se la rotazione è aggiunta o anteposta alla trasformazione della matrice.. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_42}


```
 scale_transform(sx, sy) 
```

Applica l'operazione di scaling specificata alla matrice di trasformazione di questo Graphics anteponendola alla matrice di trasformazione dell'oggetto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| sx | float | Fattore di scala nella direzione x. |
| sy | float | Fattore di scala nella direzione y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_43}


```
 scale_transform(sx, sy, order) 
```

Applica l'operazione di scaling specificata alla matrice di trasformazione di questo Graphics nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| sx | float | Fattore di scala nella direzione x. |
| sy | float | Fattore di scala nella direzione y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Specifica se l'operazione di scala è anteposta o aggiunta alla matrice di trasformazione. |

### Method: set_transform(transform) {#set_transform_transform_44}


```
 set_transform(transform) 
```

Imposta la trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La nuova matrice di trasformazione. |

### Method: translate_transform(x, y) {#translate_transform_x_y_45}


```
 translate_transform(x, y) 
```

Modifica l'origine del sistema di coordinate anteponendo la traslazione specificata alla matrice di trasformazione di questo Graphics.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x della traslazione. |
| y | float | La coordinata y della traslazione. |

### Method: translate_transform(x, y, order) {#translate_transform_x_y_order_46}


```
 translate_transform(x, y, order) 
```

Modifica l'origine del sistema di coordinate applicando la traslazione specificata alla matrice di trasformazione di questo Graphics nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x della traslazione. |
| y | float | La coordinata y della traslazione. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Specifica se la traslazione è anteposta o aggiunta alla matrice di trasformazione. |

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
# La dimensione dell'immagine in pixel
device_width: int = 600
device_height: int = 400
# La dimensione dell'immagine in millimetri
device_width_mm = device_width // 100
device_height_mm = device_height // 100
frame = Rectangle(0, 0, device_width, device_height)
# Crea un'immagine EMF.
graphics = EmfRecorderGraphics2D(frame, Size(device_width, device_height), Size(device_width_mm, device_height_mm))
# Disegna un rettangolo nero lungo i bordi dell'immagine usando una penna nera larga 1 pixel.
graphics.draw_rectangle(Pen(Color.black, 1), 0, 0, device_width, device_height)
# Riempi un rettangolo con il colore white-smoke.
graphics.fill_rectangle(SolidBrush(Color.white_smoke), Rectangle(10, 10, 580, 380))
# Disegna due linee diagonali usando una penna darkgreen larga 1 pixel.
graphics.draw_line(Pen(Color.dark_green, 1), 0, 0, device_width, device_height)
graphics.draw_line(Pen(Color.dark_green, 1), 0, device_height, device_width, 0)
# Disegna un arco all'interno del rettangolo {0, 0, 200, 200} usando una penna blu larga 2 pixel.
graphics.draw_arc(Pen(Color.blue, 2), Rectangle(0, 0, 200, 200), 90, 270)
# Riempi un arco
graphics.fill_pie(SolidBrush(Color.light_sky_blue), Rectangle(0, 0, 150, 150), 90, 270)
# Disegna un bezier cubico usando una penna rossa larga 2 pixel.
graphics.draw_cubic_bezier(Pen(Color.red, 2), Point(0, 0), Point(200, 133), Point(400, 166), Point(600, 400))

# Disegna un'immagine raster delle dimensioni specificate nella posizione specificata.
# L'immagine è scalata per adattarsi al rettangolo desiderato.
with aspycore.as_of(Image.load(join(dir_, "sample.bmp")), RasterImage) as image_to_draw:
	graphics.draw_image(image_to_draw, Rectangle(400, 200, 100, 50), Rectangle(0, 0, device_width, device_height), GraphicsUnit.PIXEL)

# Disegna una stringa di testo
graphics.draw_string("Hello World!", Font("Arial", 48, FontStyle.REGULAR), Color.dark_red, 200, 300)

# Crea un percorso da riempire
figure_to_fill = Figure()
figure_to_fill.is_closed = True
path_to_fill = GraphicsPath()
path_to_fill.add_figure(figure_to_fill)
figure_to_fill.add_shapes([ArcShape(Rectangle(400, 0, 200, 100), 45, 300), BezierShape([PointF(300, 200), PointF(400, 200), PointF(500, 100), PointF(600, 200)]), PolygonShape([PointF(300, 100)]), RectangleShape(RectangleF(0, 100, 200, 200))])

# Riempi il percorso usando un pennello giallo e una penna verde per disegnare il contorno
graphics.fill_path(Pen(Color.green, 2), SolidBrushColor.yellow), path_to_fill)

# Crea un percorso da disegnare
path_to_draw = GraphicsPath()
figure_to_draw = Figure()
path_to_draw.add_figure(figure_to_draw)
figure_to_draw.add_shapes([ArcShape(RectangleF(200, 200, 200, 200), 0, 360)])

# Disegna il percorso usando una penna arancione larga 5 pixel.
graphics.draw_path(Pen(Color.orange, 5), path_to_draw)

# Ottieni l'immagine WMF finale che include tutti i comandi di disegno
with graphics.end_recording() as emf_image:
	emf_image.save(join(dir_, "test.output.emf"))


```

