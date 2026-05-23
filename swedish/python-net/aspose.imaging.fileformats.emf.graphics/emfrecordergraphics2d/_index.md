---
title: "EmfRecorderGraphics2D-klass"
type: docs
weight: 10
url: /sv/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/
---

**Summary:** The Emf recorder graphics

**Module:** [aspose.imaging.fileformats.emf.graphics](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/)

**Full Name:** aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D

**Inheritance:** MetafileRecorderGraphics2D

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfRecorderGraphics2D(frame, device_size, device_size_mm)](#EmfRecorderGraphics2D_frame_device_size_device_size_mm_1) | Initierar en ny instans av [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) klassen. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Hämtar eller anger bakgrundens färg. |
| background_mode | [EmfBackgroundMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfbackgroundmode/) | r/w | Hämtar eller anger bakgrundsläget. |
| clip | [Region](/imaging/python-net/aspose.imaging/region/) | r/w | Hämtar eller anger en Region som begränsar ritningsområdet för denna Graphics. |
| clip_bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Hämtar klippningsgränserna. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| clear() | Rensar tillståndet för grafikobjektet. |
| [draw_arc(pen, rect, start_angle, arc_angle)](#draw_arc_pen_rect_start_angle_arc_angle_1) | Ritar en båge som representerar en del av en ellips specificerad av en rektangelstruktur. |
| [draw_cubic_bezier(pen, pt1, pt2, pt3, pt4)](#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2) | Ritar den kubiska Bézier-kurvan. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_3) | Ritar ellipsen. |
| [draw_image(image, dest_rect, src_rect, src_unit)](#draw_image_image_dest_rect_src_rect_src_unit_4) | Ritar den angivna delen av den specificerade bilden på den angivna platsen och med den angivna storleken. |
| [draw_image(image, location)](#draw_image_image_location_5) | Ritar den angivna bilden, med dess ursprungliga fysiska storlek, på den angivna platsen. |
| [draw_image(image_bytes, dest_rect, src_unit)](#draw_image_image_bytes_dest_rect_src_unit_6) | Ritar bilden. |
| [draw_image(stream, dest_rect, src_unit)](#draw_image_stream_dest_rect_src_unit_7) | Ritar bilden. |
| [draw_image_from_bytes(image_bytes, dest_rect, src_unit)](#draw_image_from_bytes_image_bytes_dest_rect_src_unit_8) | Ritar bilden. |
| [draw_image_from_stream(stream, dest_rect, src_unit)](#draw_image_from_stream_stream_dest_rect_src_unit_9) | Ritar bilden. |
| [draw_line(pen, pt1, pt2)](#draw_line_pen_pt1_pt2_10) | Ritar linjen. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_11) | Ritar linjen. |
| [draw_path(pen, path)](#draw_path_pen_path_12) | Ritar sökvägen. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_13) | Ritar pajen. |
| [draw_poly_cubic_bezier(pen, points)](#draw_poly_cubic_bezier_pen_points_14) | Ritar den polykubiska Bézier-kurvan. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_15) | Ritar polygonen. |
| [draw_polyline(pen, points)](#draw_polyline_pen_points_16) | Ritar polylinjen. |
| [draw_rectangle(pen, rectangle)](#draw_rectangle_pen_rectangle_17) | Ritar rektangeln. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_18) | Ritar rektangeln. |
| [draw_string(string, font, color, x, y)](#draw_string_string_font_color_x_y_19) | Ritar strängen. |
| [draw_string(string, font, color, x, y, angle)](#draw_string_string_font_color_x_y_angle_20) | Ritar strängen. |
| [end_recording()](#end_recording__21) | Avslutar inspelningen. |
| [exclude_clip(rect)](#exclude_clip_rect_22) | Uppdaterar klippområdet för denna Graphics för att utesluta området som anges av en rektangelstruktur. |
| [exclude_clip(region)](#exclude_clip_region_23) | Uppdaterar klippområdet för denna Graphics för att utesluta området som anges av en region. |
| [exclude_clip_rect(rect)](#exclude_clip_rect_rect_24) | Uppdaterar klippområdet för denna Graphics för att utesluta området som anges av en rektangelstruktur. |
| [exclude_clip_rgn(region)](#exclude_clip_rgn_region_25) | Uppdaterar klippområdet för denna Graphics för att utesluta området som anges av en region. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_26) | Fyller ellipsen. |
| [fill_path(pen, brush, path)](#fill_path_pen_brush_path_27) | Fyller sökvägen. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_28) | Fyller pajen. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_29) | Fyller polygonen. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_30) | Fyller polygonen. |
| [fill_rectangle(brush, rectangle)](#fill_rectangle_brush_rectangle_31) | Fyller rektangeln. |
| [from_emf_image(emf_image)](#from_emf_image_emf_image_32) | Hämtar en instans av [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) som innehåller alla poster från Emf-bilden. |
| [get_transform()](#get_transform__33) | Hämtar världstransformationen. |
| [intersect_clip(rect)](#intersect_clip_rect_34) | Uppdaterar klippområdet för denna Graphics till skärningspunkten mellan det aktuella klippområdet och den angivna rektangelstrukturen. |
| [intersect_clip(region)](#intersect_clip_region_35) | Uppdaterar klippområdet för denna Graphics till skärningspunkten mellan det aktuella klippområdet och den angivna regionen. |
| [intersect_clip_rect_f(rect)](#intersect_clip_rect_f_rect_36) | Uppdaterar klippområdet för denna Graphics till skärningspunkten mellan det aktuella klippområdet och den angivna rektangelstrukturen. |
| [intersect_clip_rgn(region)](#intersect_clip_rgn_region_37) | Uppdaterar klippområdet för denna Graphics till skärningspunkten mellan det aktuella klippområdet och den angivna regionen. |
| [multiply_transform(matrix)](#multiply_transform_matrix_38) | Multiplicerar världstransformationen för denna Graphics med den angivna matrisen. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_39) | Multiplicerar världstransformationen för denna Graphics med den angivna matrisen i angiven ordning. |
| reset_clip() | Återställer klippet. |
| [rotate_transform(angle)](#rotate_transform_angle_40) | Tillämpar den angivna rotationen på transformationsmatrisen för denna Graphics. |
| [rotate_transform(angle, center, order)](#rotate_transform_angle_center_order_41) | Tillämpar den angivna rotationen på transformationsmatrisen för denna Graphics i den angivna ordningen. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_42) | Tillämpar den angivna skalningsoperationen på transformationsmatrisen för denna Graphics genom att föra in den i början av objektets transformationsmatris. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_43) | Tillämpar den angivna skalningsoperationen på transformationsmatrisen för denna Graphics i den angivna ordningen. |
| [set_transform(transform)](#set_transform_transform_44) | Ställer in transformen. |
| [translate_transform(x, y)](#translate_transform_x_y_45) | Ändrar ursprunget för koordinatsystemet genom att föra in den angivna translationen i början av transformationsmatrisen för denna Graphics. |
| [translate_transform(x, y, order)](#translate_transform_x_y_order_46) | Ändrar ursprunget för koordinatsystemet genom att tillämpa den angivna translationen på transformationsmatrisen för denna Graphics i den angivna ordningen. |


### Constructor: EmfRecorderGraphics2D(frame, device_size, device_size_mm) {#EmfRecorderGraphics2D_frame_device_size_device_size_mm_1}


```
 EmfRecorderGraphics2D(frame, device_size, device_size_mm) 
```

Initierar en ny instans av [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) klassen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| frame | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Ramen. |
| device_size | [Size](/imaging/python-net/aspose.imaging/size/) | Storlek på enheten. |
| device_size_mm | [Size](/imaging/python-net/aspose.imaging/size/) | Enhetens storlek mm. |


**See also:**

**[Example # 1](#example_174)**: This example shows how to create a EMF image and draw some geometric shapes o...


### Method: draw_arc(pen, rect, start_angle, arc_angle) {#draw_arc_pen_rect_start_angle_arc_angle_1}


```
 draw_arc(pen, rect, start_angle, arc_angle) 
```

Ritar en båge som representerar en del av en ellips specificerad av en rektangelstruktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Penna som bestämmer figurens färg, bredd och stil. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Ellipsens gränser. |
| start_angle | float | Vinkel i grader, mätt medurs från x-axeln till bågens startpunkt. |
| arc_angle | float | Vinkel i grader mätt medurs från startAngle‑parametern till arcens slutpunkt. |

### Method: draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) {#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2}


```
 draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) 
```

Ritar den kubiska Bézier-kurvan.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Penna som bestämmer figurens färg, bredd och stil. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | Kurvans startpunkt. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | Kurvans första kontrollpunkt. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | Kurvans andra kontrollpunkt. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | Kurvans slutpunkt. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_3}


```
 draw_ellipse(pen, rect) 
```

Ritar ellipsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Penna som bestämmer figurens färg, bredd och stil. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Ellipsens gränser. |

### Method: draw_image(image, dest_rect, src_rect, src_unit) {#draw_image_image_dest_rect_src_rect_src_unit_4}


```
 draw_image(image, dest_rect, src_rect, src_unit) 
```

Ritar den angivna delen av den specificerade bilden på den angivna platsen och med den angivna storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Bilden som ska ritas. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangelstruktur som specificerar platsen och storleken på den ritade bilden. Bilden skalas för att passa rektangeln. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangelstruktur som specificerar den del av bildobjektet som ska ritas. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Måttenheterna som används av srcRect‑parametern. |

### Method: draw_image(image, location) {#draw_image_image_location_5}


```
 draw_image(image, location) 
```

Ritar den angivna bilden, med dess ursprungliga fysiska storlek, på den angivna platsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Bilden som ska ritas. |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | Platsen för den ritade bildens övre vänstra hörn. |

### Method: draw_image(image_bytes, dest_rect, src_unit) {#draw_image_image_bytes_dest_rect_src_unit_6}


```
 draw_image(image_bytes, dest_rect, src_unit) 
```

Ritar bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_bytes | System.Byte | Bildens byte. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den destrektangeln. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Den källenheten. |

### Method: draw_image(stream, dest_rect, src_unit) {#draw_image_stream_dest_rect_src_unit_7}


```
 draw_image(stream, dest_rect, src_unit) 
```

Ritar bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den destrektangeln. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Den källenheten. |

### Method: draw_image_from_bytes(image_bytes, dest_rect, src_unit) {#draw_image_from_bytes_image_bytes_dest_rect_src_unit_8}


```
 draw_image_from_bytes(image_bytes, dest_rect, src_unit) 
```

Ritar bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_bytes | System.Byte | Bildens byte. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den destrektangeln. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Den källenheten. |

### Method: draw_image_from_stream(stream, dest_rect, src_unit) {#draw_image_from_stream_stream_dest_rect_src_unit_9}


```
 draw_image_from_stream(stream, dest_rect, src_unit) 
```

Ritar bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den destrektangeln. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Den källenheten. |

### Method: draw_line(pen, pt1, pt2) {#draw_line_pen_pt1_pt2_10}


```
 draw_line(pen, pt1, pt2) 
```

Ritar linjen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Penna som bestämmer figurens färg, bredd och stil. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | Den första punkten. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | Den andra punkten. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_11}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Ritar linjen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Penna som bestämmer figurens färg, bredd och stil. |
| x1 | int | X-koordinaten för den första punkten. |
| y1 | int | Y-koordinaten för den första punkten. |
| x2 | int | X-koordinaten för den andra punkten. |
| y2 | int | Y-koordinaten för den andra punkten. |

### Method: draw_path(pen, path) {#draw_path_pen_path_12}


```
 draw_path(pen, path) 
```

Ritar sökvägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Penna som bestämmer figurens färg, bredd och stil. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Sökvägen att rita. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_13}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Ritar pajen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Penna som bestämmer figurens färg, bredd och stil. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Ellipsens gränser. |
| start_angle | float | Vinkel i grader, mätt medurs från x-axeln till bågens startpunkt. |
| sweep_angle | float | Vinkel i grader mätt medurs från startAngle‑parametern till arcens slutpunkt. |

### Method: draw_poly_cubic_bezier(pen, points) {#draw_poly_cubic_bezier_pen_points_14}


```
 draw_poly_cubic_bezier(pen, points) 
```

Ritar den polykubiska Bézier-kurvan.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Penna som bestämmer figurens färg, bredd och stil. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Punkterna. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_15}


```
 draw_polygon(pen, points) 
```

Ritar polygonen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Penna som bestämmer figurens färg, bredd och stil. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Punkterna. |

### Method: draw_polyline(pen, points) {#draw_polyline_pen_points_16}


```
 draw_polyline(pen, points) 
```

Ritar polylinjen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Penna som bestämmer figurens färg, bredd och stil. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Punkterna. |

### Method: draw_rectangle(pen, rectangle) {#draw_rectangle_pen_rectangle_17}


```
 draw_rectangle(pen, rectangle) 
```

Ritar rektangeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Penna som bestämmer figurens färg, bredd och stil. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att rita. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_18}


```
 draw_rectangle(pen, x, y, width, height) 
```

Ritar rektangeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Penna som bestämmer figurens färg, bredd och stil. |
| x | int | X-koordinaten för det övre vänstra hörnet av rektangeln som ska ritas. |
| y | int | Y-koordinaten för det övre vänstra hörnet av rektangeln som ska ritas. |
| width | int | Bredden på rektangeln som ska ritas. |
| height | int | Höjden på rektangeln som ska ritas. |

### Method: draw_string(string, font, color, x, y) {#draw_string_string_font_color_x_y_19}


```
 draw_string(string, font, color, x, y) 
```

Ritar strängen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| string | string | Strängen. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Typsnitt som definierar textformatet för strängen. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Textfärgen. |
| x | int | X-koordinaten för det övre vänstra hörnet på den ritade texten. |
| y | int | Y-koordinaten för det övre vänstra hörnet på den ritade texten. |

### Method: draw_string(string, font, color, x, y, angle) {#draw_string_string_font_color_x_y_angle_20}


```
 draw_string(string, font, color, x, y, angle) 
```

Ritar strängen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| string | string | Strängen. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Typsnitt som definierar textformatet för strängen. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Textfärgen. |
| x | int | X-koordinaten för det övre vänstra hörnet på den ritade texten. |
| y | int | Y-koordinaten för det övre vänstra hörnet på den ritade texten. |
| vinkel | float | Vinkeln i grader, mellan escapementvektorn och enhetens x-axel. <br/>            Escapementvektorn är parallell med baslinjen för en textrad. |

### Method: end_recording() {#end_recording__21}


```
 end_recording() 
```

Avslutar inspelningen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [EmfImage](/imaging/python-net/aspose.imaging.fileformats.emf/emfimage/) | Resultatbilden. |


### Method: exclude_clip(rect) {#exclude_clip_rect_22}


```
 exclude_clip(rect) 
```

Uppdaterar klippområdet för denna Graphics för att utesluta området som anges av en rektangelstruktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangelstruktur som specificerar rektangeln att utesluta från klippområdet. |

### Method: exclude_clip(region) {#exclude_clip_region_23}


```
 exclude_clip(region) 
```

Uppdaterar klippområdet för denna Graphics för att utesluta området som anges av en region.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Region som specificerar regionen att utesluta från klippområdet. |

### Method: exclude_clip_rect(rect) {#exclude_clip_rect_rect_24}


```
 exclude_clip_rect(rect) 
```

Uppdaterar klippområdet för denna Graphics för att utesluta området som anges av en rektangelstruktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangelstruktur som specificerar rektangeln att utesluta från klippområdet. |

### Method: exclude_clip_rgn(region) {#exclude_clip_rgn_region_25}


```
 exclude_clip_rgn(region) 
```

Uppdaterar klippområdet för denna Graphics för att utesluta området som anges av en region.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Region som specificerar regionen att utesluta från klippområdet. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_26}


```
 fill_ellipse(brush, rect) 
```

Fyller ellipsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pensel som bestämmer fyllningens egenskaper. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Ellipsens gränser. |

### Method: fill_path(pen, brush, path) {#fill_path_pen_brush_path_27}


```
 fill_path(pen, brush, path) 
```

Fyller sökvägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Penna som bestämmer figurens färg, bredd och stil. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pensel som bestämmer fyllningens egenskaper. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Sökvägen att fylla. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_28}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Fyller pajen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pensel som bestämmer fyllningens egenskaper. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Ellipsens gränser. |
| start_angle | float | Vinkel i grader, mätt medurs från x-axeln till bågens startpunkt. |
| sweep_angle | float | Vinkel i grader mätt medurs från startAngle‑parametern till arcens slutpunkt. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_29}


```
 fill_polygon(brush, points) 
```

Fyller polygonen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pensel som bestämmer fyllningens egenskaper. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Punkterna. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_30}


```
 fill_polygon(brush, points, fill_mode) 
```

Fyller polygonen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pensel som bestämmer fyllningens egenskaper. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Punkterna. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Fyllningsläget. |

### Method: fill_rectangle(brush, rectangle) {#fill_rectangle_brush_rectangle_31}


```
 fill_rectangle(brush, rectangle) 
```

Fyller rektangeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Pensel som bestämmer fyllningens egenskaper. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att fylla. |

### Method: from_emf_image(emf_image)  [static] {#from_emf_image_emf_image_32}


```
 from_emf_image(emf_image) 
```

Hämtar en instans av [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) som innehåller alla poster från Emf-bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| emf_image | [EmfImage](/imaging/python-net/aspose.imaging.fileformats.emf/emfimage/) | Emf-bilden att läsa poster från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) | En instans av [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) |


### Method: get_transform() {#get_transform__33}


```
 get_transform() 
```

Hämtar världstransformationen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Transformationsmatrisen. |


### Method: intersect_clip(rect) {#intersect_clip_rect_34}


```
 intersect_clip(rect) 
```

Uppdaterar klippområdet för denna Graphics till skärningspunkten mellan det aktuella klippområdet och den angivna rektangelstrukturen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Rektangelstruktur för att skära med det aktuella klippområdet. |

### Method: intersect_clip(region) {#intersect_clip_region_35}


```
 intersect_clip(region) 
```

Uppdaterar klippområdet för denna Graphics till skärningspunkten mellan det aktuella klippområdet och den angivna regionen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Region för att skära med den aktuella regionen. |

### Method: intersect_clip_rect_f(rect) {#intersect_clip_rect_f_rect_36}


```
 intersect_clip_rect_f(rect) 
```

Uppdaterar klippområdet för denna Graphics till skärningspunkten mellan det aktuella klippområdet och den angivna rektangelstrukturen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Rektangelstruktur för att skära med det aktuella klippområdet. |

### Method: intersect_clip_rgn(region) {#intersect_clip_rgn_region_37}


```
 intersect_clip_rgn(region) 
```

Uppdaterar klippområdet för denna Graphics till skärningspunkten mellan det aktuella klippområdet och den angivna regionen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Region för att skära med den aktuella regionen. |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_38}


```
 multiply_transform(matrix) 
```

Multiplicerar världstransformationen för denna Graphics med den angivna matrisen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Matrisen som multiplicerar världstransformationen. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_39}


```
 multiply_transform(matrix, order) 
```

Multiplicerar världstransformationen för denna Graphics med den angivna matrisen i angiven ordning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Matrisen som multiplicerar världstransformationen. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Multiplikationsordningen. |

### Method: rotate_transform(angle) {#rotate_transform_angle_40}


```
 rotate_transform(angle) 
```

Tillämpar den angivna rotationen på transformationsmatrisen för denna Graphics.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln i grader. |

### Method: rotate_transform(angle, center, order) {#rotate_transform_angle_center_order_41}


```
 rotate_transform(angle, center, order) 
```

Tillämpar den angivna rotationen på transformationsmatrisen för denna Graphics i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln i grader. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Rotationscentrum. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Anger om rotationen läggs till eller infogas före i matrisomvandlingen.. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_42}


```
 scale_transform(sx, sy) 
```

Tillämpar den angivna skalningsoperationen på transformationsmatrisen för denna Graphics genom att föra in den i början av objektets transformationsmatris.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sx | float | Skalfaktor i x-riktning. |
| sy | float | Skalfaktor i y-riktning. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_43}


```
 scale_transform(sx, sy, order) 
```

Tillämpar den angivna skalningsoperationen på transformationsmatrisen för denna Graphics i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sx | float | Skalfaktor i x-riktning. |
| sy | float | Skalfaktor i y-riktning. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Anger om skalningsoperationen infogas före eller läggs till i transformationsmatrisen. |

### Method: set_transform(transform) {#set_transform_transform_44}


```
 set_transform(transform) 
```

Ställer in transformen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Den nya transformationsmatrisen. |

### Method: translate_transform(x, y) {#translate_transform_x_y_45}


```
 translate_transform(x, y) 
```

Ändrar ursprunget för koordinatsystemet genom att föra in den angivna translationen i början av transformationsmatrisen för denna Graphics.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | float | X-koordinaten för förflyttningen. |
| y | float | Y-koordinaten för förflyttningen. |

### Method: translate_transform(x, y, order) {#translate_transform_x_y_order_46}


```
 translate_transform(x, y, order) 
```

Ändrar ursprunget för koordinatsystemet genom att tillämpa den angivna translationen på transformationsmatrisen för denna Graphics i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | float | X-koordinaten för förflyttningen. |
| y | float | Y-koordinaten för förflyttningen. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Anger om förflyttningen infogas före eller läggs till i transformationsmatrisen. |

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
# Bildens storlek i pixlar
device_width: int = 600
device_height: int = 400
# Bildens storlek i millimeter
device_width_mm = device_width // 100
device_height_mm = device_height // 100
frame = Rectangle(0, 0, device_width, device_height)
# Skapa en EMF-bild.
graphics = EmfRecorderGraphics2D(frame, Size(device_width, device_height), Size(device_width_mm, device_height_mm))
# Rita en svart rektangel längs bildens kanter med en 1‑pixel bred svart penna.
graphics.draw_rectangle(Pen(Color.black, 1), 0, 0, device_width, device_height)
# Fyll en rektangel med färgen vit rök.
graphics.fill_rectangle(SolidBrush(Color.white_smoke), Rectangle(10, 10, 580, 380))
# Rita två diagonala linjer med en 1‑pixel bred mörkgrön penna.
graphics.draw_line(Pen(Color.dark_green, 1), 0, 0, device_width, device_height)
graphics.draw_line(Pen(Color.dark_green, 1), 0, device_height, device_width, 0)
# Rita en båge inom rektangeln {0, 0, 200, 200} med en 2‑pixel bred blå penna.
graphics.draw_arc(Pen(Color.blue, 2), Rectangle(0, 0, 200, 200), 90, 270)
# Fyll en båge
graphics.fill_pie(SolidBrush(Color.light_sky_blue), Rectangle(0, 0, 150, 150), 90, 270)
# Rita en kubisk Bézier med en 2‑pixel bred röd penna.
graphics.draw_cubic_bezier(Pen(Color.red, 2), Point(0, 0), Point(200, 133), Point(400, 166), Point(600, 400))

# Rita en rasterbild av angiven storlek på den angivna platsen.
# Bilden skalas för att passa den önskade rektangeln.
with aspycore.as_of(Image.load(join(dir_, "sample.bmp")), RasterImage) as image_to_draw:
	graphics.draw_image(image_to_draw, Rectangle(400, 200, 100, 50), Rectangle(0, 0, device_width, device_height), GraphicsUnit.PIXEL)

# Rita en textsträng
graphics.draw_string("Hello World!", Font("Arial", 48, FontStyle.REGULAR), Color.dark_red, 200, 300)

# Skapa en bana för fyllning
figure_to_fill = Figure()
figure_to_fill.is_closed = True
path_to_fill = GraphicsPath()
path_to_fill.add_figure(figure_to_fill)
figure_to_fill.add_shapes([ArcShape(Rectangle(400, 0, 200, 100), 45, 300), BezierShape([PointF(300, 200), PointF(400, 200), PointF(500, 100), PointF(600, 200)]), PolygonShape([PointF(300, 100)]), RectangleShape(RectangleF(0, 100, 200, 200))])

# Fyll banan med en gul pensel och en grön penna för att rita kontur
graphics.fill_path(Pen(Color.green, 2), SolidBrushColor.yellow), path_to_fill)

# Skapa en bana för ritning
path_to_draw = GraphicsPath()
figure_to_draw = Figure()
path_to_draw.add_figure(figure_to_draw)
figure_to_draw.add_shapes([ArcShape(RectangleF(200, 200, 200, 200), 0, 360)])

# Rita banan med en 5‑pixel bred orange penna.
graphics.draw_path(Pen(Color.orange, 5), path_to_draw)

# Hämta den slutgiltiga WMF-bilden som innehåller alla ritkommandon
with graphics.end_recording() as emf_image:
	emf_image.save(join(dir_, "test.output.emf"))


```

