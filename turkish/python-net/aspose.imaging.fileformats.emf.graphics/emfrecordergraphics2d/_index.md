---
title: "EmfRecorderGraphics2D Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/
---

**Summary:** The Emf recorder graphics

**Module:** [aspose.imaging.fileformats.emf.graphics](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/)

**Full Name:** aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D

**Inheritance:** MetafileRecorderGraphics2D

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfRecorderGraphics2D(frame, device_size, device_size_mm)](#EmfRecorderGraphics2D_frame_device_size_device_size_mm_1) | Yeni bir [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Arka plan rengini alır veya ayarlar. |
| background_mode | [EmfBackgroundMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfbackgroundmode/) | r/w | Arka plan modunu alır veya ayarlar. |
| clip | [Region](/imaging/python-net/aspose.imaging/region/) | r/w | Bu Graphics nesnesinin çizim bölgesini sınırlayan bir Region'ı alır veya ayarlar. |
| clip_bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Kırpma sınırlarını alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| clear() | Grafik nesnesinin durumunu temizler. |
| [draw_arc(pen, rect, start_angle, arc_angle)](#draw_arc_pen_rect_start_angle_arc_angle_1) | Bir Dikdörtgen yapısı tarafından belirtilen elipsin bir bölümünü temsil eden bir yay çizer. |
| [draw_cubic_bezier(pen, pt1, pt2, pt3, pt4)](#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2) | Kübik bezier çizer. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_3) | Elipsi çizer. |
| [draw_image(image, dest_rect, src_rect, src_unit)](#draw_image_image_dest_rect_src_rect_src_unit_4) | Belirtilen görüntünün belirtilen konumda ve belirtilen boyutta belirtilen bölümünü çizer. |
| [draw_image(image, location)](#draw_image_image_location_5) | Belirtilen Görüntüyü, orijinal fiziksel boyutunu kullanarak, belirtilen konumda çizer. |
| [draw_image(image_bytes, dest_rect, src_unit)](#draw_image_image_bytes_dest_rect_src_unit_6) | Resmi çizer. |
| [draw_image(stream, dest_rect, src_unit)](#draw_image_stream_dest_rect_src_unit_7) | Resmi çizer. |
| [draw_image_from_bytes(image_bytes, dest_rect, src_unit)](#draw_image_from_bytes_image_bytes_dest_rect_src_unit_8) | Resmi çizer. |
| [draw_image_from_stream(stream, dest_rect, src_unit)](#draw_image_from_stream_stream_dest_rect_src_unit_9) | Resmi çizer. |
| [draw_line(pen, pt1, pt2)](#draw_line_pen_pt1_pt2_10) | Çizgiyi çizer. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_11) | Çizgiyi çizer. |
| [draw_path(pen, path)](#draw_path_pen_path_12) | Yolu çizer. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_13) | Pasta dilimini çizer. |
| [draw_poly_cubic_bezier(pen, points)](#draw_poly_cubic_bezier_pen_points_14) | Poli kübik bezier çizer. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_15) | Poligonu çizer. |
| [draw_polyline(pen, points)](#draw_polyline_pen_points_16) | Polilini çizer. |
| [draw_rectangle(pen, rectangle)](#draw_rectangle_pen_rectangle_17) | Dikdörtgeni çizer. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_18) | Dikdörtgeni çizer. |
| [draw_string(string, font, color, x, y)](#draw_string_string_font_color_x_y_19) | Metni çizer. |
| [draw_string(string, font, color, x, y, angle)](#draw_string_string_font_color_x_y_angle_20) | Metni çizer. |
| [end_recording()](#end_recording__21) | Kayıt işlemini sonlandırır. |
| [exclude_clip(rect)](#exclude_clip_rect_22) | Bu Graphics nesnesinin kırpma bölgesini, bir Rectangle yapısı tarafından belirtilen alanı hariç tutacak şekilde günceller. |
| [exclude_clip(region)](#exclude_clip_region_23) | Bu Graphics nesnesinin kırpma bölgesini, bir Region tarafından belirtilen alanı hariç tutacak şekilde günceller. |
| [exclude_clip_rect(rect)](#exclude_clip_rect_rect_24) | Bu Graphics nesnesinin kırpma bölgesini, bir Rectangle yapısı tarafından belirtilen alanı hariç tutacak şekilde günceller. |
| [exclude_clip_rgn(region)](#exclude_clip_rgn_region_25) | Bu Graphics nesnesinin kırpma bölgesini, bir Region tarafından belirtilen alanı hariç tutacak şekilde günceller. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_26) | Elipsi doldurur. |
| [fill_path(pen, brush, path)](#fill_path_pen_brush_path_27) | Yolu doldurur. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_28) | Pasta dilimini doldurur. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_29) | Poligonu doldurur. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_30) | Poligonu doldurur. |
| [fill_rectangle(brush, rectangle)](#fill_rectangle_brush_rectangle_31) | Dikdörtgeni doldurur. |
| [from_emf_image(emf_image)](#from_emf_image_emf_image_32) | Emf görüntüsünden tüm kayıtları içeren [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) örneğini alır. |
| [get_transform()](#get_transform__33) | Dünya dönüşümünü alır. |
| [intersect_clip(rect)](#intersect_clip_rect_34) | Bu Graphics nesnesinin kırpma bölgesini, mevcut kırpma bölgesi ile belirtilen Rectangle yapısının kesişimi olarak günceller. |
| [intersect_clip(region)](#intersect_clip_region_35) | Bu Graphics nesnesinin kırpma bölgesini, mevcut kırpma bölgesi ile belirtilen Region'un kesişimi olarak günceller. |
| [intersect_clip_rect_f(rect)](#intersect_clip_rect_f_rect_36) | Bu Graphics nesnesinin kırpma bölgesini, mevcut kırpma bölgesi ile belirtilen Rectangle yapısının kesişimi olarak günceller. |
| [intersect_clip_rgn(region)](#intersect_clip_rgn_region_37) | Bu Graphics nesnesinin kırpma bölgesini, mevcut kırpma bölgesi ile belirtilen Region'un kesişimi olarak günceller. |
| [multiply_transform(matrix)](#multiply_transform_matrix_38) | Bu Graphics nesnesinin dünya dönüşümünü belirtilen Matris ile çarpar. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_39) | Bu Graphics nesnesinin dünya dönüşümünü belirtilen Matris ile belirtilen sırada çarpar. |
| reset_clip() | Klip'i sıfırlar. |
| [rotate_transform(angle)](#rotate_transform_angle_40) | Bu Graphics nesnesinin dönüşüm matrisine belirtilen dönüşü uygular. |
| [rotate_transform(angle, center, order)](#rotate_transform_angle_center_order_41) | Bu Graphics nesnesinin dönüşüm matrisine belirtilen dönüşü belirtilen sırada uygular. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_42) | Bu Graphics nesnesinin dönüşüm matrisine belirtilen ölçekleme işlemini nesnenin dönüşüm matrisine ön ekleyerek uygular. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_43) | Bu Graphics nesnesinin dönüşüm matrisine belirtilen ölçekleme işlemini belirtilen sırada uygular. |
| [set_transform(transform)](#set_transform_transform_44) | Dönüşümü ayarlar. |
| [translate_transform(x, y)](#translate_transform_x_y_45) | Bu Graphics nesnesinin dönüşüm matrisine belirtilen çeviriyi ön ekleyerek koordinat sisteminin orijini değiştirir. |
| [translate_transform(x, y, order)](#translate_transform_x_y_order_46) | Bu Graphics nesnesinin dönüşüm matrisine belirtilen çeviriyi belirtilen sırada uygulayarak koordinat sisteminin orijini değiştirir. |


### Constructor: EmfRecorderGraphics2D(frame, device_size, device_size_mm) {#EmfRecorderGraphics2D_frame_device_size_device_size_mm_1}


```
 EmfRecorderGraphics2D(frame, device_size, device_size_mm) 
```

Yeni bir [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| frame | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Çerçeve. |
| device_size | [Size](/imaging/python-net/aspose.imaging/size/) | Cihazın boyutu. |
| device_size_mm | [Size](/imaging/python-net/aspose.imaging/size/) | Cihazın boyutu mm. |


**See also:**

**[Example # 1](#example_174)**: This example shows how to create a EMF image and draw some geometric shapes o...


### Method: draw_arc(pen, rect, start_angle, arc_angle) {#draw_arc_pen_rect_start_angle_arc_angle_1}


```
 draw_arc(pen, rect, start_angle, arc_angle) 
```

Bir Dikdörtgen yapısı tarafından belirtilen elipsin bir bölümünü temsil eden bir yay çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Şeklin renk, genişlik ve stilini belirleyen kalem. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Elipsin sınırları. |
| start_angle | float | x ekseninden yay başlangıç noktasına doğru saat yönünde ölçülen açı (derece). |
| arc_angle | float | startAngle parametresinden yay son noktasına doğru saat yönünde ölçülen derece cinsinden açı. |

### Method: draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) {#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2}


```
 draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) 
```

Kübik bezier çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Şeklin renk, genişlik ve stilini belirleyen kalem. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | Eğrinin başlangıç noktası. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | Eğri için ilk kontrol noktası. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | Eğri için ikinci kontrol noktası. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | Eğrinin bitiş noktası. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_3}


```
 draw_ellipse(pen, rect) 
```

Elipsi çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Şeklin renk, genişlik ve stilini belirleyen kalem. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Elipsin sınırları. |

### Method: draw_image(image, dest_rect, src_rect, src_unit) {#draw_image_image_dest_rect_src_rect_src_unit_4}


```
 draw_image(image, dest_rect, src_rect, src_unit) 
```

Belirtilen görüntünün belirtilen konumda ve belirtilen boyutta belirtilen bölümünü çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Çizilecek görüntü. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Çizilen görüntünün konumunu ve boyutunu belirten dikdörtgen yapısı. Görüntü dikdörtgene sığacak şekilde ölçeklendirilir. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Çizilecek görüntü nesnesinin bölümünü belirten dikdörtgen yapısı. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | srcRect parametresi tarafından kullanılan ölçü birimleri. |

### Method: draw_image(image, location) {#draw_image_image_location_5}


```
 draw_image(image, location) 
```

Belirtilen Görüntüyü, orijinal fiziksel boyutunu kullanarak, belirtilen konumda çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Çizilecek görüntü. |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | Çizilen görüntünün sol üst köşesinin konumu. |

### Method: draw_image(image_bytes, dest_rect, src_unit) {#draw_image_image_bytes_dest_rect_src_unit_6}


```
 draw_image(image_bytes, dest_rect, src_unit) 
```

Resmi çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image_bytes | System.Byte | Görüntü baytları. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Hedef dikdörtgen. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Kaynak birim. |

### Method: draw_image(stream, dest_rect, src_unit) {#draw_image_stream_dest_rect_src_unit_7}


```
 draw_image(stream, dest_rect, src_unit) 
```

Resmi çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Akış. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Hedef dikdörtgen. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Kaynak birim. |

### Method: draw_image_from_bytes(image_bytes, dest_rect, src_unit) {#draw_image_from_bytes_image_bytes_dest_rect_src_unit_8}


```
 draw_image_from_bytes(image_bytes, dest_rect, src_unit) 
```

Resmi çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image_bytes | System.Byte | Görüntü baytları. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Hedef dikdörtgen. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Kaynak birim. |

### Method: draw_image_from_stream(stream, dest_rect, src_unit) {#draw_image_from_stream_stream_dest_rect_src_unit_9}


```
 draw_image_from_stream(stream, dest_rect, src_unit) 
```

Resmi çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Akış. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Hedef dikdörtgen. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Kaynak birim. |

### Method: draw_line(pen, pt1, pt2) {#draw_line_pen_pt1_pt2_10}


```
 draw_line(pen, pt1, pt2) 
```

Çizgiyi çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Şeklin renk, genişlik ve stilini belirleyen kalem. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | İlk nokta. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | İkinci nokta. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_11}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Çizgiyi çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Şeklin renk, genişlik ve stilini belirleyen kalem. |
| x1 | int | İlk noktanın x koordinatı. |
| y1 | int | İlk noktanın y koordinatı. |
| x2 | int | İkinci noktanın x koordinatı. |
| y2 | int | İkinci noktanın y koordinatı. |

### Method: draw_path(pen, path) {#draw_path_pen_path_12}


```
 draw_path(pen, path) 
```

Yolu çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Şeklin renk, genişlik ve stilini belirleyen kalem. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Çizilecek yol. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_13}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Pasta dilimini çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Şeklin renk, genişlik ve stilini belirleyen kalem. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Elipsin sınırları. |
| start_angle | float | x ekseninden yay başlangıç noktasına doğru saat yönünde ölçülen açı (derece). |
| sweep_angle | float | startAngle parametresinden yay son noktasına doğru saat yönünde ölçülen derece cinsinden açı. |

### Method: draw_poly_cubic_bezier(pen, points) {#draw_poly_cubic_bezier_pen_points_14}


```
 draw_poly_cubic_bezier(pen, points) 
```

Poli kübik bezier çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Şeklin renk, genişlik ve stilini belirleyen kalem. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Noktalar. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_15}


```
 draw_polygon(pen, points) 
```

Poligonu çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Şeklin renk, genişlik ve stilini belirleyen kalem. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Noktalar. |

### Method: draw_polyline(pen, points) {#draw_polyline_pen_points_16}


```
 draw_polyline(pen, points) 
```

Polilini çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Şeklin renk, genişlik ve stilini belirleyen kalem. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Noktalar. |

### Method: draw_rectangle(pen, rectangle) {#draw_rectangle_pen_rectangle_17}


```
 draw_rectangle(pen, rectangle) 
```

Dikdörtgeni çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Şeklin renk, genişlik ve stilini belirleyen kalem. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Çizilecek dikdörtgen. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_18}


```
 draw_rectangle(pen, x, y, width, height) 
```

Dikdörtgeni çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Şeklin renk, genişlik ve stilini belirleyen kalem. |
| x | int | Çizilecek dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Çizilecek dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Çizilecek dikdörtgenin genişliği. |
| height | int | Çizilecek dikdörtgenin yüksekliği. |

### Method: draw_string(string, font, color, x, y) {#draw_string_string_font_color_x_y_19}


```
 draw_string(string, font, color, x, y) 
```

Metni çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| string | string | Dize. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Dizenin metin biçimini tanımlayan yazı tipi. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Metin rengi. |
| x | int | Çizilen metnin sol üst köşesinin x koordinatı. |
| y | int | Çizilen metnin sol üst köşesinin y koordinatı. |

### Method: draw_string(string, font, color, x, y, angle) {#draw_string_string_font_color_x_y_angle_20}


```
 draw_string(string, font, color, x, y, angle) 
```

Metni çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| string | string | Dize. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Dizenin metin biçimini tanımlayan yazı tipi. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Metin rengi. |
| x | int | Çizilen metnin sol üst köşesinin x koordinatı. |
| y | int | Çizilen metnin sol üst köşesinin y koordinatı. |
| angle | float | Cihazın x ekseni ile kaçış vektörü arasındaki açı (derece cinsinden). <br/>            Kaçış vektörü, bir metin satırının temel çizgisine paraleldir. |

### Method: end_recording() {#end_recording__21}


```
 end_recording() 
```

Kayıt işlemini sonlandırır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [EmfImage](/imaging/python-net/aspose.imaging.fileformats.emf/emfimage/) | Sonuç görüntüsü. |


### Method: exclude_clip(rect) {#exclude_clip_rect_22}


```
 exclude_clip(rect) 
```

Bu Graphics nesnesinin kırpma bölgesini, bir Rectangle yapısı tarafından belirtilen alanı hariç tutacak şekilde günceller.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Klip bölgesinden hariç tutulacak dikdörtgeni belirten dikdörtgen yapısı. |

### Method: exclude_clip(region) {#exclude_clip_region_23}


```
 exclude_clip(region) 
```

Bu Graphics nesnesinin kırpma bölgesini, bir Region tarafından belirtilen alanı hariç tutacak şekilde günceller.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Klip bölgesinden hariç tutulacak bölgeyi belirten bölge. |

### Method: exclude_clip_rect(rect) {#exclude_clip_rect_rect_24}


```
 exclude_clip_rect(rect) 
```

Bu Graphics nesnesinin kırpma bölgesini, bir Rectangle yapısı tarafından belirtilen alanı hariç tutacak şekilde günceller.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Klip bölgesinden hariç tutulacak dikdörtgeni belirten dikdörtgen yapısı. |

### Method: exclude_clip_rgn(region) {#exclude_clip_rgn_region_25}


```
 exclude_clip_rgn(region) 
```

Bu Graphics nesnesinin kırpma bölgesini, bir Region tarafından belirtilen alanı hariç tutacak şekilde günceller.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Klip bölgesinden hariç tutulacak bölgeyi belirten bölge. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_26}


```
 fill_ellipse(brush, rect) 
```

Elipsi doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Dolgunun özelliklerini belirleyen fırça. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Elipsin sınırları. |

### Method: fill_path(pen, brush, path) {#fill_path_pen_brush_path_27}


```
 fill_path(pen, brush, path) 
```

Yolu doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Şeklin renk, genişlik ve stilini belirleyen kalem. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Dolgunun özelliklerini belirleyen fırça. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Doldurulacak yol. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_28}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Pasta dilimini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Dolgunun özelliklerini belirleyen fırça. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Elipsin sınırları. |
| start_angle | float | x ekseninden yay başlangıç noktasına doğru saat yönünde ölçülen açı (derece). |
| sweep_angle | float | startAngle parametresinden yay son noktasına doğru saat yönünde ölçülen derece cinsinden açı. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_29}


```
 fill_polygon(brush, points) 
```

Poligonu doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Dolgunun özelliklerini belirleyen fırça. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Noktalar. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_30}


```
 fill_polygon(brush, points, fill_mode) 
```

Poligonu doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Dolgunun özelliklerini belirleyen fırça. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Noktalar. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Dolgu modu. |

### Method: fill_rectangle(brush, rectangle) {#fill_rectangle_brush_rectangle_31}


```
 fill_rectangle(brush, rectangle) 
```

Dikdörtgeni doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Dolgunun özelliklerini belirleyen fırça. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Doldurulacak dikdörtgen. |

### Method: from_emf_image(emf_image)  [static] {#from_emf_image_emf_image_32}


```
 from_emf_image(emf_image) 
```

Emf görüntüsünden tüm kayıtları içeren [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) örneğini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| emf_image | [EmfImage](/imaging/python-net/aspose.imaging.fileformats.emf/emfimage/) | Kayıtların okunacağı Emf görüntüsü. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) | Bir [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) örneği |


### Method: get_transform() {#get_transform__33}


```
 get_transform() 
```

Dünya dönüşümünü alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Dönüşüm matrisi. |


### Method: intersect_clip(rect) {#intersect_clip_rect_34}


```
 intersect_clip(rect) 
```

Bu Graphics nesnesinin kırpma bölgesini, mevcut kırpma bölgesi ile belirtilen Rectangle yapısının kesişimi olarak günceller.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Mevcut klip bölgesiyle kesişecek dikdörtgen yapısı. |

### Method: intersect_clip(region) {#intersect_clip_region_35}


```
 intersect_clip(region) 
```

Bu Graphics nesnesinin kırpma bölgesini, mevcut kırpma bölgesi ile belirtilen Region'un kesişimi olarak günceller.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Mevcut bölgeyle kesişecek bölge. |

### Method: intersect_clip_rect_f(rect) {#intersect_clip_rect_f_rect_36}


```
 intersect_clip_rect_f(rect) 
```

Bu Graphics nesnesinin kırpma bölgesini, mevcut kırpma bölgesi ile belirtilen Rectangle yapısının kesişimi olarak günceller.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Mevcut klip bölgesiyle kesişecek dikdörtgen yapısı. |

### Method: intersect_clip_rgn(region) {#intersect_clip_rgn_region_37}


```
 intersect_clip_rgn(region) 
```

Bu Graphics nesnesinin kırpma bölgesini, mevcut kırpma bölgesi ile belirtilen Region'un kesişimi olarak günceller.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Mevcut bölgeyle kesişecek bölge. |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_38}


```
 multiply_transform(matrix) 
```

Bu Graphics nesnesinin dünya dönüşümünü belirtilen Matris ile çarpar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Dünya dönüşümünü çarpan matris. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_39}


```
 multiply_transform(matrix, order) 
```

Bu Graphics nesnesinin dünya dönüşümünü belirtilen Matris ile belirtilen sırada çarpar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Dünya dönüşümünü çarpan matris. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Çarpmanın sırası. |

### Method: rotate_transform(angle) {#rotate_transform_angle_40}


```
 rotate_transform(angle) 
```

Bu Graphics nesnesinin dönüşüm matrisine belirtilen dönüşü uygular.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| angle | float | Dönüş açısı (derece cinsinden). |

### Method: rotate_transform(angle, center, order) {#rotate_transform_angle_center_order_41}


```
 rotate_transform(angle, center, order) 
```

Bu Graphics nesnesinin dönüşüm matrisine belirtilen dönüşü belirtilen sırada uygular.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| angle | float | Dönüş açısı (derece cinsinden). |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Dönme merkezi. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Dönmenin matris dönüşümüne eklenip eklenmeyeceğini ya da önüne eklenip eklenmeyeceğini belirtir.. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_42}


```
 scale_transform(sx, sy) 
```

Bu Graphics nesnesinin dönüşüm matrisine belirtilen ölçekleme işlemini nesnenin dönüşüm matrisine ön ekleyerek uygular.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| sx | float | X yönündeki ölçek faktörü. |
| sy | float | Y yönündeki ölçek faktörü. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_43}


```
 scale_transform(sx, sy, order) 
```

Bu Graphics nesnesinin dönüşüm matrisine belirtilen ölçekleme işlemini belirtilen sırada uygular.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| sx | float | X yönündeki ölçek faktörü. |
| sy | float | Y yönündeki ölçek faktörü. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Ölçekleme işleminin dönüşüm matrisine önceden eklenip eklenmeyeceğini ya da sonradan eklenip eklenmeyeceğini belirtir. |

### Method: set_transform(transform) {#set_transform_transform_44}


```
 set_transform(transform) 
```

Dönüşümü ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Yeni dönüşüm matrisi. |

### Method: translate_transform(x, y) {#translate_transform_x_y_45}


```
 translate_transform(x, y) 
```

Bu Graphics nesnesinin dönüşüm matrisine belirtilen çeviriyi ön ekleyerek koordinat sisteminin orijini değiştirir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | float | Çevirme işleminin x koordinatı. |
| y | float | Çevirme işleminin y koordinatı. |

### Method: translate_transform(x, y, order) {#translate_transform_x_y_order_46}


```
 translate_transform(x, y, order) 
```

Bu Graphics nesnesinin dönüşüm matrisine belirtilen çeviriyi belirtilen sırada uygulayarak koordinat sisteminin orijini değiştirir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | float | Çevirme işleminin x koordinatı. |
| y | float | Çevirme işleminin y koordinatı. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Çevirmenin dönüşüm matrisine önceden eklenip eklenmeyeceğini ya da sonradan eklenip eklenmeyeceğini belirtir. |

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
# Görüntünün piksel cinsinden boyutu
device_width: int = 600
device_height: int = 400
# Görüntünün milimetre cinsinden boyutu
device_width_mm = device_width // 100
device_height_mm = device_height // 100
frame = Rectangle(0, 0, device_width, device_height)
# Bir EMF görüntüsü oluştur.
graphics = EmfRecorderGraphics2D(frame, Size(device_width, device_height), Size(device_width_mm, device_height_mm))
# 1 piksel genişliğinde siyah bir kalem kullanarak görüntü kenarları boyunca siyah bir dikdörtgen çizin.
graphics.draw_rectangle(Pen(Color.black, 1), 0, 0, device_width, device_height)
# Bir dikdörtgeni beyaz duman rengiyle doldurun.
graphics.fill_rectangle(SolidBrush(Color.white_smoke), Rectangle(10, 10, 580, 380))
# 1 piksel genişliğinde koyu yeşil bir kalem kullanarak iki çapraz çizgi çizin.
graphics.draw_line(Pen(Color.dark_green, 1), 0, 0, device_width, device_height)
graphics.draw_line(Pen(Color.dark_green, 1), 0, device_height, device_width, 0)
# 2 piksel genişliğinde mavi bir kalem kullanarak {0, 0, 200, 200} dikdörtgeni içinde bir yay çizin.
graphics.draw_arc(Pen(Color.blue, 2), Rectangle(0, 0, 200, 200), 90, 270)
# Bir yay doldurun
graphics.fill_pie(SolidBrush(Color.light_sky_blue), Rectangle(0, 0, 150, 150), 90, 270)
# 2 piksel genişliğinde kırmızı bir kalem kullanarak kübik bir bezier çizin.
graphics.draw_cubic_bezier(Pen(Color.red, 2), Point(0, 0), Point(200, 133), Point(400, 166), Point(600, 400))

# Belirtilen konumda belirtilen boyutta bir raster görüntüsü çizin.
# Görüntü, istenen dikdörtgene sığacak şekilde ölçeklendirilir.
with aspycore.as_of(Image.load(join(dir_, "sample.bmp")), RasterImage) as image_to_draw:
	graphics.draw_image(image_to_draw, Rectangle(400, 200, 100, 50), Rectangle(0, 0, device_width, device_height), GraphicsUnit.PIXEL)

# Bir metin dizesi çizin
graphics.draw_string("Hello World!", Font("Arial", 48, FontStyle.REGULAR), Color.dark_red, 200, 300)

# Doldurmak için bir yol oluştur
figure_to_fill = Figure()
figure_to_fill.is_closed = True
path_to_fill = GraphicsPath()
path_to_fill.add_figure(figure_to_fill)
figure_to_fill.add_shapes([ArcShape(Rectangle(400, 0, 200, 100), 45, 300), BezierShape([PointF(300, 200), PointF(400, 200), PointF(500, 100), PointF(600, 200)]), PolygonShape([PointF(300, 100)]), RectangleShape(RectangleF(0, 100, 200, 200))])

# Yolun dış çizgisini çizmek için sarı bir fırça ve yeşil bir kalem kullanarak yolu doldurun
graphics.fill_path(Pen(Color.green, 2), SolidBrushColor.yellow), path_to_fill)

# Çizmek için bir yol oluştur
path_to_draw = GraphicsPath()
figure_to_draw = Figure()
path_to_draw.add_figure(figure_to_draw)
figure_to_draw.add_shapes([ArcShape(RectangleF(200, 200, 200, 200), 0, 360)])

# 5 piksel genişliğinde turuncu bir kalem kullanarak yolu çizin.
graphics.draw_path(Pen(Color.orange, 5), path_to_draw)

# Tüm çizim komutlarını içeren son WMF görüntüsünü alın
with graphics.end_recording() as emf_image:
	emf_image.save(join(dir_, "test.output.emf"))


```

