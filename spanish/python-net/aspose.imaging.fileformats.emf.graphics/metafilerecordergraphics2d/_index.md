---
title: "Clase MetafileRecorderGraphics2D"
type: docs
weight: 20
url: /es/python-net/aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/
---

**Summary:** The metafiles recorder graphics

**Module:** [aspose.imaging.fileformats.emf.graphics](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/)

**Full Name:** aspose.imaging.fileformats.emf.graphics.MetafileRecorderGraphics2D

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtiene o establece el color del fondo. |
| clip | [Region](/imaging/python-net/aspose.imaging/region/) | r/w | Obtiene o establece una Región que limita la zona de dibujo de este Graphics |
| clip_bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Obtiene los límites del recorte. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| clear() | Limpia el estado del objeto Graphics |
| [draw_arc(pen, rect, start_angle, arc_angle)](#draw_arc_pen_rect_start_angle_arc_angle_1) | Dibuja un arco que representa una porción de una elipse especificada por una estructura Rectangle. |
| [draw_cubic_bezier(pen, pt1, pt2, pt3, pt4)](#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2) | Dibuja el Bézier cúbico. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_3) | Dibuja la elipse. |
| [draw_image(image, dest_rect, src_rect, src_unit)](#draw_image_image_dest_rect_src_rect_src_unit_4) | Dibuja la porción especificada de la Imagen especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(image, location)](#draw_image_image_location_5) | Dibuja la Imagen especificada, usando su tamaño físico original, en la ubicación especificada. |
| [draw_image(image_bytes, dest_rect, src_unit)](#draw_image_image_bytes_dest_rect_src_unit_6) | Dibuja la imagen. |
| [draw_image(stream, dest_rect, src_unit)](#draw_image_stream_dest_rect_src_unit_7) | Dibuja la imagen. |
| [draw_image_from_bytes(image_bytes, dest_rect, src_unit)](#draw_image_from_bytes_image_bytes_dest_rect_src_unit_8) | Dibuja la imagen. |
| [draw_image_from_stream(stream, dest_rect, src_unit)](#draw_image_from_stream_stream_dest_rect_src_unit_9) | Dibuja la imagen. |
| [draw_line(pen, pt1, pt2)](#draw_line_pen_pt1_pt2_10) | Dibuja la línea. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_11) | Dibuja la línea. |
| [draw_path(pen, path)](#draw_path_pen_path_12) | Dibuja la ruta. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_13) | Dibuja el sector. |
| [draw_poly_cubic_bezier(pen, points)](#draw_poly_cubic_bezier_pen_points_14) | Dibuja el Bezier cúbico poligonal. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_15) | Dibuja el polígono. |
| [draw_polyline(pen, points)](#draw_polyline_pen_points_16) | Dibuja la polilínea. |
| [draw_rectangle(pen, rectangle)](#draw_rectangle_pen_rectangle_17) | Dibuja el rectángulo. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_18) | Dibuja el rectángulo. |
| [draw_string(string, font, color, x, y)](#draw_string_string_font_color_x_y_19) | Dibuja la cadena. |
| [draw_string(string, font, color, x, y, angle)](#draw_string_string_font_color_x_y_angle_20) | Dibuja la cadena. |
| [exclude_clip(rect)](#exclude_clip_rect_21) | Actualiza la región de recorte de este Graphics para excluir el área especificada por una estructura Rectangle. |
| [exclude_clip(region)](#exclude_clip_region_22) | Actualiza la región de recorte de este Graphics para excluir el área especificada por una Región. |
| [exclude_clip_rect(rect)](#exclude_clip_rect_rect_23) | Actualiza la región de recorte de este Graphics para excluir el área especificada por una estructura Rectangle. |
| [exclude_clip_rgn(region)](#exclude_clip_rgn_region_24) | Actualiza la región de recorte de este Graphics para excluir el área especificada por una Región. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_25) | Rellena la elipse. |
| [fill_path(pen, brush, path)](#fill_path_pen_brush_path_26) | Rellena la ruta. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_27) | Rellena el sector. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_28) | Rellena el polígono. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_29) | Rellena el polígono. |
| [fill_rectangle(brush, rectangle)](#fill_rectangle_brush_rectangle_30) | Rellena el rectángulo. |
| [get_transform()](#get_transform__31) | Obtiene la transformación mundial. |
| [intersect_clip(rect)](#intersect_clip_rect_32) | Actualiza la región de recorte de este Graphics a la intersección de la región de recorte actual y la estructura Rectangle especificada. |
| [intersect_clip(region)](#intersect_clip_region_33) | Actualiza la región de recorte de este Graphics a la intersección de la región de recorte actual y la Región especificada. |
| [intersect_clip_rect_f(rect)](#intersect_clip_rect_f_rect_34) | Actualiza la región de recorte de este Graphics a la intersección de la región de recorte actual y la estructura Rectangle especificada. |
| [intersect_clip_rgn(region)](#intersect_clip_rgn_region_35) | Actualiza la región de recorte de este Graphics a la intersección de la región de recorte actual y la Región especificada. |
| [multiply_transform(matrix)](#multiply_transform_matrix_36) | Multiplica la transformación mundial de este Graphics por la Matriz especificada. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_37) | Multiplica la transformación mundial de este Graphics por la Matriz especificada en el orden especificado. |
| reset_clip() | Restablece el recorte. |
| [rotate_transform(angle)](#rotate_transform_angle_38) | Aplica la rotación especificada a la matriz de transformación de este Graphics. |
| [rotate_transform(angle, center, order)](#rotate_transform_angle_center_order_39) | Aplica la rotación especificada a la matriz de transformación de este Graphics en el orden especificado. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_40) | Aplica la operación de escalado especificada a la matriz de transformación de este Graphics anteponiéndola a la matriz de transformación del objeto. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_41) | Aplica la operación de escalado especificada a la matriz de transformación de este Graphics en el orden especificado. |
| [set_transform(transform)](#set_transform_transform_42) | Establece la transformación. |
| [translate_transform(x, y)](#translate_transform_x_y_43) | Cambia el origen del sistema de coordenadas anteponiendo la traslación especificada a la matriz de transformación de este Graphics. |
| [translate_transform(x, y, order)](#translate_transform_x_y_order_44) | Cambia el origen del sistema de coordenadas aplicando la traslación especificada a la matriz de transformación de este Graphics en el orden especificado. |


### Method: draw_arc(pen, rect, start_angle, arc_angle) {#draw_arc_pen_rect_start_angle_arc_angle_1}


```
 draw_arc(pen, rect, start_angle, arc_angle) 
```

Dibuja un arco que representa una porción de una elipse especificada por una estructura Rectangle.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pluma que determina el color, el ancho y el estilo de la figura. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Los límites de la elipse. |
| start_angle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el punto de inicio del arco. |
| arc_angle | float | Ángulo en grados medido en sentido horario desde el parámetro startAngle hasta el punto final del arco. |


**See also:**

**[Example # 1](#example_172)**: This example shows how to create a WMF image and draw some geometric shapes u...

**[Example # 2](#example_174)**: This example shows how to create a EMF image and draw some geometric shapes o...


### Method: draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) {#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2}


```
 draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) 
```

Dibuja el Bézier cúbico.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pluma que determina el color, el ancho y el estilo de la figura. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | El punto de inicio de la curva. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | El primer punto de control de la curva. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | El segundo punto de control de la curva. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | El punto final de la curva. |


**See also:**

**[Example # 1](#example_172)**: This example shows how to create a WMF image and draw some geometric shapes u...

**[Example # 2](#example_174)**: This example shows how to create a EMF image and draw some geometric shapes o...


### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_3}


```
 draw_ellipse(pen, rect) 
```

Dibuja la elipse.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pluma que determina el color, el ancho y el estilo de la figura. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Los límites de la elipse. |

### Method: draw_image(image, dest_rect, src_rect, src_unit) {#draw_image_image_dest_rect_src_rect_src_unit_4}


```
 draw_image(image, dest_rect, src_rect, src_unit) 
```

Dibuja la porción especificada de la Imagen especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen a dibujar. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Estructura de rectángulo que especifica la ubicación y el tamaño de la imagen dibujada. La imagen se escala para ajustarse al rectángulo. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Estructura de rectángulo que especifica la porción del objeto imagen a dibujar. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Las unidades de medida utilizadas por el parámetro srcRect. |


**See also:**

**[Example # 1](#example_172)**: This example shows how to create a WMF image and draw some geometric shapes u...

**[Example # 2](#example_174)**: This example shows how to create a EMF image and draw some geometric shapes o...


### Method: draw_image(image, location) {#draw_image_image_location_5}


```
 draw_image(image, location) 
```

Dibuja la Imagen especificada, usando su tamaño físico original, en la ubicación especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen a dibujar. |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | La ubicación de la esquina superior izquierda de la imagen dibujada. |

### Method: draw_image(image_bytes, dest_rect, src_unit) {#draw_image_image_bytes_dest_rect_src_unit_6}


```
 draw_image(image_bytes, dest_rect, src_unit) 
```

Dibuja la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_bytes | System.Byte | Los bytes de la imagen. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de destino. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | La unidad de origen. |

### Method: draw_image(stream, dest_rect, src_unit) {#draw_image_stream_dest_rect_src_unit_7}


```
 draw_image(stream, dest_rect, src_unit) 
```

Dibuja la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de destino. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | La unidad de origen. |

### Method: draw_image_from_bytes(image_bytes, dest_rect, src_unit) {#draw_image_from_bytes_image_bytes_dest_rect_src_unit_8}


```
 draw_image_from_bytes(image_bytes, dest_rect, src_unit) 
```

Dibuja la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_bytes | System.Byte | Los bytes de la imagen. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de destino. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | La unidad de origen. |

### Method: draw_image_from_stream(stream, dest_rect, src_unit) {#draw_image_from_stream_stream_dest_rect_src_unit_9}


```
 draw_image_from_stream(stream, dest_rect, src_unit) 
```

Dibuja la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de destino. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | La unidad de origen. |

### Method: draw_line(pen, pt1, pt2) {#draw_line_pen_pt1_pt2_10}


```
 draw_line(pen, pt1, pt2) 
```

Dibuja la línea.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pluma que determina el color, el ancho y el estilo de la figura. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | El primer punto. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | El segundo punto. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_11}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Dibuja la línea.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pluma que determina el color, el ancho y el estilo de la figura. |
| x1 | int | La coordenada x del primer punto. |
| y1 | int | La coordenada y del primer punto. |
| x2 | int | La coordenada x del segundo punto. |
| y2 | int | La coordenada y del segundo punto. |


**See also:**

**[Example # 1](#example_172)**: This example shows how to create a WMF image and draw some geometric shapes u...

**[Example # 2](#example_174)**: This example shows how to create a EMF image and draw some geometric shapes o...


### Method: draw_path(pen, path) {#draw_path_pen_path_12}


```
 draw_path(pen, path) 
```

Dibuja la ruta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pluma que determina el color, el ancho y el estilo de la figura. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | La ruta a dibujar. |


**See also:**

**[Example # 1](#example_172)**: This example shows how to create a WMF image and draw some geometric shapes u...

**[Example # 2](#example_174)**: This example shows how to create a EMF image and draw some geometric shapes o...


### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_13}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Dibuja el sector.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pluma que determina el color, el ancho y el estilo de la figura. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Los límites de la elipse. |
| start_angle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el punto de inicio del arco. |
| sweep_angle | float | Ángulo en grados medido en sentido horario desde el parámetro startAngle hasta el punto final del arco. |

### Method: draw_poly_cubic_bezier(pen, points) {#draw_poly_cubic_bezier_pen_points_14}


```
 draw_poly_cubic_bezier(pen, points) 
```

Dibuja el Bezier cúbico poligonal.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pluma que determina el color, el ancho y el estilo de la figura. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Los puntos. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_15}


```
 draw_polygon(pen, points) 
```

Dibuja el polígono.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pluma que determina el color, el ancho y el estilo de la figura. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Los puntos. |

### Method: draw_polyline(pen, points) {#draw_polyline_pen_points_16}


```
 draw_polyline(pen, points) 
```

Dibuja la polilínea.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pluma que determina el color, el ancho y el estilo de la figura. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Los puntos. |

### Method: draw_rectangle(pen, rectangle) {#draw_rectangle_pen_rectangle_17}


```
 draw_rectangle(pen, rectangle) 
```

Dibuja el rectángulo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pluma que determina el color, el ancho y el estilo de la figura. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo a dibujar. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_18}


```
 draw_rectangle(pen, x, y, width, height) 
```

Dibuja el rectángulo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pluma que determina el color, el ancho y el estilo de la figura. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo a dibujar. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo a dibujar. |
| width | int | El ancho del rectángulo a dibujar. |
| height | int | La altura del rectángulo a dibujar. |


**See also:**

**[Example # 1](#example_172)**: This example shows how to create a WMF image and draw some geometric shapes u...

**[Example # 2](#example_174)**: This example shows how to create a EMF image and draw some geometric shapes o...


### Method: draw_string(string, font, color, x, y) {#draw_string_string_font_color_x_y_19}


```
 draw_string(string, font, color, x, y) 
```

Dibuja la cadena.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| string | string | La cadena. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Fuente que define el formato de texto de la cadena. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | El color del texto. |
| x | int | La coordenada x de la esquina superior izquierda del texto dibujado. |
| y | int | La coordenada y de la esquina superior izquierda del texto dibujado. |


**See also:**

**[Example # 1](#example_172)**: This example shows how to create a WMF image and draw some geometric shapes u...

**[Example # 2](#example_174)**: This example shows how to create a EMF image and draw some geometric shapes o...


### Method: draw_string(string, font, color, x, y, angle) {#draw_string_string_font_color_x_y_angle_20}


```
 draw_string(string, font, color, x, y, angle) 
```

Dibuja la cadena.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| string | string | La cadena. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Fuente que define el formato de texto de la cadena. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | El color del texto. |
| x | int | La coordenada x de la esquina superior izquierda del texto dibujado. |
| y | int | La coordenada y de la esquina superior izquierda del texto dibujado. |
| angle | float | El ángulo en grados, entre el vector de escapamiento y el eje x del dispositivo. <br/> El vector de escapamiento es paralelo a la línea base de una fila de texto. |

### Method: exclude_clip(rect) {#exclude_clip_rect_21}


```
 exclude_clip(rect) 
```

Actualiza la región de recorte de este Graphics para excluir el área especificada por una estructura Rectangle.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Estructura de rectángulo que especifica el rectángulo a excluir de la región de recorte. |

### Method: exclude_clip(region) {#exclude_clip_region_22}


```
 exclude_clip(region) 
```

Actualiza la región de recorte de este Graphics para excluir el área especificada por una Región.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Región que especifica la zona a excluir de la región de recorte. |

### Method: exclude_clip_rect(rect) {#exclude_clip_rect_rect_23}


```
 exclude_clip_rect(rect) 
```

Actualiza la región de recorte de este Graphics para excluir el área especificada por una estructura Rectangle.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Estructura de rectángulo que especifica el rectángulo a excluir de la región de recorte. |

### Method: exclude_clip_rgn(region) {#exclude_clip_rgn_region_24}


```
 exclude_clip_rgn(region) 
```

Actualiza la región de recorte de este Graphics para excluir el área especificada por una Región.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Región que especifica la zona a excluir de la región de recorte. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_25}


```
 fill_ellipse(brush, rect) 
```

Rellena la elipse.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pincel que determina las características del relleno. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Los límites de la elipse. |

### Method: fill_path(pen, brush, path) {#fill_path_pen_brush_path_26}


```
 fill_path(pen, brush, path) 
```

Rellena la ruta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pluma que determina el color, el ancho y el estilo de la figura. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pincel que determina las características del relleno. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | La ruta a rellenar. |


**See also:**

**[Example # 1](#example_172)**: This example shows how to create a WMF image and draw some geometric shapes u...

**[Example # 2](#example_174)**: This example shows how to create a EMF image and draw some geometric shapes o...


### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_27}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Rellena el sector.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pincel que determina las características del relleno. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Los límites de la elipse. |
| start_angle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el punto de inicio del arco. |
| sweep_angle | float | Ángulo en grados medido en sentido horario desde el parámetro startAngle hasta el punto final del arco. |


**See also:**

**[Example # 1](#example_172)**: This example shows how to create a WMF image and draw some geometric shapes u...

**[Example # 2](#example_174)**: This example shows how to create a EMF image and draw some geometric shapes o...


### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_28}


```
 fill_polygon(brush, points) 
```

Rellena el polígono.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pincel que determina las características del relleno. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Los puntos. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_29}


```
 fill_polygon(brush, points, fill_mode) 
```

Rellena el polígono.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pincel que determina las características del relleno. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Los puntos. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | El modo de relleno. |

### Method: fill_rectangle(brush, rectangle) {#fill_rectangle_brush_rectangle_30}


```
 fill_rectangle(brush, rectangle) 
```

Rellena el rectángulo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pincel que determina las características del relleno. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo a rellenar. |


**See also:**

**[Example # 1](#example_172)**: This example shows how to create a WMF image and draw some geometric shapes u...

**[Example # 2](#example_174)**: This example shows how to create a EMF image and draw some geometric shapes o...


### Method: get_transform() {#get_transform__31}


```
 get_transform() 
```

Obtiene la transformación mundial.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La matriz de transformación. |


### Method: intersect_clip(rect) {#intersect_clip_rect_32}


```
 intersect_clip(rect) 
```

Actualiza la región de recorte de este Graphics a la intersección de la región de recorte actual y la estructura Rectangle especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Estructura de rectángulo para intersectar con la región de recorte actual. |

### Method: intersect_clip(region) {#intersect_clip_region_33}


```
 intersect_clip(region) 
```

Actualiza la región de recorte de este Graphics a la intersección de la región de recorte actual y la Región especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Región para intersectar con la región actual. |

### Method: intersect_clip_rect_f(rect) {#intersect_clip_rect_f_rect_34}


```
 intersect_clip_rect_f(rect) 
```

Actualiza la región de recorte de este Graphics a la intersección de la región de recorte actual y la estructura Rectangle especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Estructura de rectángulo para intersectar con la región de recorte actual. |

### Method: intersect_clip_rgn(region) {#intersect_clip_rgn_region_35}


```
 intersect_clip_rgn(region) 
```

Actualiza la región de recorte de este Graphics a la intersección de la región de recorte actual y la Región especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Región para intersectar con la región actual. |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_36}


```
 multiply_transform(matrix) 
```

Multiplica la transformación mundial de este Graphics por la Matriz especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La matriz que multiplica la transformación mundial. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_37}


```
 multiply_transform(matrix, order) 
```

Multiplica la transformación mundial de este Graphics por la Matriz especificada en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La matriz que multiplica la transformación mundial. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | El orden de la multiplicación. |

### Method: rotate_transform(angle) {#rotate_transform_angle_38}


```
 rotate_transform(angle) 
```

Aplica la rotación especificada a la matriz de transformación de este Graphics.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| angle | float | Ángulo de rotación en grados. |

### Method: rotate_transform(angle, center, order) {#rotate_transform_angle_center_order_39}


```
 rotate_transform(angle, center, order) 
```

Aplica la rotación especificada a la matriz de transformación de este Graphics en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| angle | float | Ángulo de rotación en grados. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | El centro de rotación. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Especifica si la rotación se agrega o se antepone a la transformación de la matriz.. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_40}


```
 scale_transform(sx, sy) 
```

Aplica la operación de escalado especificada a la matriz de transformación de este Graphics anteponiéndola a la matriz de transformación del objeto.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| sx | float | Factor de escala en la dirección x. |
| sy | float | Factor de escala en la dirección y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_41}


```
 scale_transform(sx, sy, order) 
```

Aplica la operación de escalado especificada a la matriz de transformación de este Graphics en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| sx | float | Factor de escala en la dirección x. |
| sy | float | Factor de escala en la dirección y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Especifica si la operación de escalado se antepone o se agrega a la matriz de transformación. |

### Method: set_transform(transform) {#set_transform_transform_42}


```
 set_transform(transform) 
```

Establece la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La nueva matriz de transformación. |

### Method: translate_transform(x, y) {#translate_transform_x_y_43}


```
 translate_transform(x, y) 
```

Cambia el origen del sistema de coordenadas anteponiendo la traslación especificada a la matriz de transformación de este Graphics.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x de la traslación. |
| y | float | La coordenada y de la traslación. |

### Method: translate_transform(x, y, order) {#translate_transform_x_y_order_44}


```
 translate_transform(x, y, order) 
```

Cambia el origen del sistema de coordenadas aplicando la traslación especificada a la matriz de transformación de este Graphics en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x de la traslación. |
| y | float | La coordenada y de la traslación. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Especifica si la traslación se antepone o se agrega a la matriz de transformación. |

## **Examples**
### This example shows how to create a WMF image and draw some geometric shapes using WmfRecorderGraphics2D. {#example_172}
``` python

from os.path import join as path_join
import aspose.pycore as aspycore
from aspose.imaging import Rectangle, Pen, Color, Point, Image, RasterImage, GraphicsUnit, Font, FontStyle, Figure,\
   GraphicsPath, RectangleF, PointF
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.shapes import ArcShape, BezierShape, PolygonShape, RectangleShape
from aspose.imaging.fileformats.wmf.graphics import WmfRecorderGraphics2D
from aspose.imaging.imageoptions import SvgRasterizationOptions, PngOptions

dir_ = "c:\\temp"
image_width = 600
image_height = 400
# Esta es la resolución de pantalla predeterminada.
dpi = 96
frame = Rectangle(0, 0, image_width, image_height)
# Crear una imagen WMF.
graphics = WmfRecorderGraphics2D(frame, dpi)
# Dibujar un rectángulo negro a lo largo de los bordes de la imagen usando un lápiz negro de 1 píxel de ancho.
graphics.draw_rectangle(Pen(Color.black, 1), 0, 0, image_width, image_height)
# Rellenar un rectángulo con el color de humo blanco.
graphics.fill_rectangle(SolidBrush(Color.white_smoke), Rectangle(10, 10, 580, 380))
# Dibujar dos líneas diagonales usando un lápiz verde oscuro de 1 píxel de ancho.
graphics.draw_line(Pen(Color.dark_green, 1), 0, 0, image_width, image_height)
graphics.draw_line(Pen(Color.dark_green, 1), 0, image_height, image_width, 0)
# Dibujar un arco dentro del rectángulo {0, 0, 200, 200} usando un lápiz azul de 2 píxeles de ancho.
graphics.draw_arc(Pen(Color.blue, 2), Rectangle(0, 0, 200, 200), 90, 270)
# Rellenar un arco
graphics.fill_pie(SolidBrush(Color.light_sky_blue), Rectangle(0, 0, 150, 150), 90, 270)
# Dibujar un Bézier cúbico usando un lápiz rojo de 2 píxeles de ancho.
graphics.draw_cubic_bezier(Pen(Color.red, 2), Point(0, 0), Point(200, 133), Point(400, 166), Point(600, 400))
# Dibujar una imagen raster de tamaño especificado en la ubicación especificada.
# La imagen se escala para ajustarse al rectángulo deseado.
with aspycore.as_of(Image.load(path_join(dir_, "sample.bmp")), RasterImage) as image_to_draw:
	graphics.draw_image(image_to_draw, Rectangle(400, 200, 100, 50), Rectangle(0, 0, image_width, image_height), GraphicsUnit.PIXEL)

# Dibujar una cadena de texto
graphics.draw_string("Hello World!", Font("Arial", 48, FontStyle.REGULAR), Color.dark_red, 200, 300)
# Crear una ruta para rellenar
figure_to_fill = Figure()
figure_to_fill.is_closed = True
path_to_fill = GraphicsPath()
path_to_fill.add_figure(figure_to_fill)
figure_to_fill.add_shapes([ArcShape(Rectangle(400, 0, 200, 100), 45, 300),
	BezierShape([PointF(300, 200), PointF(400, 200), PointF(500, 100), Aspose.Imaging.PointF(600, 200)]), 
	PolygonShape([PointF(300, 100)]), RectangleShape(RectangleF(0, 100, 200, 200))])
# Rellenar la ruta usando un pincel amarillo y un lápiz verde para dibujar el contorno
graphics.fill_path(Pen(Color.green, 2), SolidBrush(Color.yellow), path_to_fill)
# Crear una ruta para dibujar
path_to_draw = GraphicsPath()
figure_to_draw = Figure()
path_to_draw.add_figure(figure_to_draw)
figure_to_draw.add_shapes([ArcShape(RectangleF(200, 200, 200, 200), 0, 360)])
# Dibujar la ruta usando un lápiz naranja de 5 píxeles de ancho.
graphics.draw_path(Pen(Color.orange, 5), path_to_draw)
# Para rasterizar SVG necesitamos especificar opciones de rasterización.
rasterization_options = SvgRasterizationOptions()
save_options = PngOptions()
save_options.vector_rasterization_options = rasterization_options
# Obtener la imagen WMF final que incluye todos los comandos de dibujo
with graphics.end_recording() as wmf_image:
	wmf_image.save(path_join(dir_, "test.output.wmf"))


```

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
# El tamaño de la imagen en píxeles
device_width: int = 600
device_height: int = 400
# El tamaño de la imagen en milímetros
device_width_mm = device_width // 100
device_height_mm = device_height // 100
frame = Rectangle(0, 0, device_width, device_height)
# Crea una imagen EMF.
graphics = EmfRecorderGraphics2D(frame, Size(device_width, device_height), Size(device_width_mm, device_height_mm))
# Dibujar un rectángulo negro a lo largo de los bordes de la imagen usando un lápiz negro de 1 píxel de ancho.
graphics.draw_rectangle(Pen(Color.black, 1), 0, 0, device_width, device_height)
# Rellenar un rectángulo con el color de humo blanco.
graphics.fill_rectangle(SolidBrush(Color.white_smoke), Rectangle(10, 10, 580, 380))
# Dibujar dos líneas diagonales usando un lápiz verde oscuro de 1 píxel de ancho.
graphics.draw_line(Pen(Color.dark_green, 1), 0, 0, device_width, device_height)
graphics.draw_line(Pen(Color.dark_green, 1), 0, device_height, device_width, 0)
# Dibujar un arco dentro del rectángulo {0, 0, 200, 200} usando un lápiz azul de 2 píxeles de ancho.
graphics.draw_arc(Pen(Color.blue, 2), Rectangle(0, 0, 200, 200), 90, 270)
# Rellenar un arco
graphics.fill_pie(SolidBrush(Color.light_sky_blue), Rectangle(0, 0, 150, 150), 90, 270)
# Dibujar un Bézier cúbico usando un lápiz rojo de 2 píxeles de ancho.
graphics.draw_cubic_bezier(Pen(Color.red, 2), Point(0, 0), Point(200, 133), Point(400, 166), Point(600, 400))

# Dibujar una imagen raster de tamaño especificado en la ubicación especificada.
# La imagen se escala para ajustarse al rectángulo deseado.
with aspycore.as_of(Image.load(join(dir_, "sample.bmp")), RasterImage) as image_to_draw:
	graphics.draw_image(image_to_draw, Rectangle(400, 200, 100, 50), Rectangle(0, 0, device_width, device_height), GraphicsUnit.PIXEL)

# Dibujar una cadena de texto
graphics.draw_string("Hello World!", Font("Arial", 48, FontStyle.REGULAR), Color.dark_red, 200, 300)

# Crear una ruta para rellenar
figure_to_fill = Figure()
figure_to_fill.is_closed = True
path_to_fill = GraphicsPath()
path_to_fill.add_figure(figure_to_fill)
figure_to_fill.add_shapes([ArcShape(Rectangle(400, 0, 200, 100), 45, 300), BezierShape([PointF(300, 200), PointF(400, 200), PointF(500, 100), PointF(600, 200)]), PolygonShape([PointF(300, 100)]), RectangleShape(RectangleF(0, 100, 200, 200))])

# Rellenar la ruta usando un pincel amarillo y un lápiz verde para dibujar el contorno
graphics.fill_path(Pen(Color.green, 2), SolidBrushColor.yellow), path_to_fill)

# Crear una ruta para dibujar
path_to_draw = GraphicsPath()
figure_to_draw = Figure()
path_to_draw.add_figure(figure_to_draw)
figure_to_draw.add_shapes([ArcShape(RectangleF(200, 200, 200, 200), 0, 360)])

# Dibujar la ruta usando un lápiz naranja de 5 píxeles de ancho.
graphics.draw_path(Pen(Color.orange, 5), path_to_draw)

# Obtener la imagen WMF final que incluye todos los comandos de dibujo
with graphics.end_recording() as emf_image:
	emf_image.save(join(dir_, "test.output.emf"))


```

