---
title: "SvgGraphics2D Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/
---

**Summary:** Provides drawing commmands to compose an Svg image.

**Module:** [aspose.imaging.fileformats.svg.graphics](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/)

**Full Name:** aspose.imaging.fileformats.svg.graphics.SvgGraphics2D

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [SvgGraphics2D(image)](#SvgGraphics2D_image_1) | Yeni bir [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) sınıfı örneği başlatır. |
| [SvgGraphics2D(width, height, dpi)](#SvgGraphics2D_width_height_dpi_2) | Yeni bir [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) sınıfı örneği başlatır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [draw_arc(pen, rect, start_angle, arc_angle)](#draw_arc_pen_rect_start_angle_arc_angle_1) | Bir Dikdörtgen yapısı tarafından belirtilen elipsin bir bölümünü temsil eden bir yay çizer. |
| [draw_cubic_bezier(pen, pt1, pt2, pt3, pt4)](#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2) | Kübik bezier çizer. |
| [draw_image(image, origin)](#draw_image_image_origin_3) | Belirtilen resmi belirtilen konuma çizer. |
| [draw_image(image, origin, size)](#draw_image_image_origin_size_4) | Belirtilen boyuttaki belirtilen resmi belirtilen konuma çizer. |
| [draw_image(src_rect, dest_rect, image)](#draw_image_src_rect_dest_rect_image_5) | Belirtilen resmin belirtilen bölümünü belirtilen konuma ve belirtilen boyutta çizer. |
| [draw_image_point_size(image, origin, size)](#draw_image_point_size_image_origin_size_6) | Belirtilen boyuttaki belirtilen resmi belirtilen konuma çizer. |
| [draw_image_src_dst_rects(src_rect, dest_rect, image)](#draw_image_src_dst_rects_src_rect_dest_rect_image_7) | Belirtilen resmin belirtilen bölümünü belirtilen konuma ve belirtilen boyutta çizer. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_8) | Çizgiyi çizer. |
| [draw_path(pen, path)](#draw_path_pen_path_9) | Yolu çizer. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_10) | Dikdörtgeni çizer. |
| [draw_string(font, text, origin, text_color)](#draw_string_font_text_origin_text_color_11) | Metin dizesini çizer. |
| [end_recording()](#end_recording__12) | Tüm çizim komutlarının [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) nesnesi aracılığıyla gerçekleştirildiği son Svg görüntüsünü alır. |
| [fill_arc(pen, brush, rect, start_angle, arc_angle)](#fill_arc_pen_brush_rect_start_angle_arc_angle_13) | Bir Dikdörtgen yapısı tarafından belirtilen bir elipsin bir bölümünü temsil eden bir yay doldurur. |
| [fill_path(pen, brush, path)](#fill_path_pen_brush_path_14) | Yolu doldurur. |
| [fill_rectangle(pen, brush, x, y, width, height)](#fill_rectangle_pen_brush_x_y_width_height_15) | Dikdörtgeni doldurur. |


### Constructor: SvgGraphics2D(image) {#SvgGraphics2D_image_1}


```
 SvgGraphics2D(image) 
```

Yeni bir [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) | Çizim işlemlerinin yapılacağı resim. |

### Constructor: SvgGraphics2D(width, height, dpi) {#SvgGraphics2D_width_height_dpi_2}


```
 SvgGraphics2D(width, height, dpi) 
```

Yeni bir [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| width | int | Çıktı Svg görüntüsünün genişliği. |
| height | int | Çıktı Svg görüntüsünün genişliği. |
| dpi | int | Cihaz çözünürlüğü, ör. inç başına 96 nokta. |


**See also:**

**[Example # 1](#example_171)**: This example shows how to create an SVG image of the specified size and raste...


### Method: draw_arc(pen, rect, start_angle, arc_angle) {#draw_arc_pen_rect_start_angle_arc_angle_1}


```
 draw_arc(pen, rect, start_angle, arc_angle) 
```

Bir Dikdörtgen yapısı tarafından belirtilen elipsin bir bölümünü temsil eden bir yay çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Şeklin ana hatlarını çizmeye yarayan kalem. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Elipsin sınırları. |
| start_angle | float | X ekseninden yay başlangıç noktasına doğru saat yönünde ölçülen açı (derece). |
| arc_angle | float | startAngle parametresinden yay son noktasına doğru saat yönünde ölçülen açı (derece). |

### Method: draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) {#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2}


```
 draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) 
```

Kübik bezier çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Şeklin renk, genişlik ve stilini belirleyen kalem. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Eğrinin başlangıç noktası. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Eğri için ilk kontrol noktası. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Eğri için ikinci kontrol noktası. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Eğrinin bitiş noktası. |

### Method: draw_image(image, origin) {#draw_image_image_origin_3}


```
 draw_image(image, origin) 
```

Belirtilen resmi belirtilen konuma çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Çizilen resim. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | Çizilen resmin konumu. |

### Method: draw_image(image, origin, size) {#draw_image_image_origin_size_4}


```
 draw_image(image, origin, size) 
```

Belirtilen boyuttaki belirtilen resmi belirtilen konuma çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Çizilen resim. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | Çizilen resmin konumu. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Çizilen resmin istenen boyutu. |

### Method: draw_image(src_rect, dest_rect, image) {#draw_image_src_rect_dest_rect_image_5}


```
 draw_image(src_rect, dest_rect, image) 
```

Belirtilen resmin belirtilen bölümünü belirtilen konuma ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Çizilecek resim nesnesinin bölümü. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Çizilen resmin konumu ve boyutu. Resim, dikdörtgene sığacak şekilde ölçeklendirilir. |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Çizilecek görüntü. |

### Method: draw_image_point_size(image, origin, size) {#draw_image_point_size_image_origin_size_6}


```
 draw_image_point_size(image, origin, size) 
```

Belirtilen boyuttaki belirtilen resmi belirtilen konuma çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Çizilen resim. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | Çizilen resmin konumu. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Çizilen resmin istenen boyutu. |

### Method: draw_image_src_dst_rects(src_rect, dest_rect, image) {#draw_image_src_dst_rects_src_rect_dest_rect_image_7}


```
 draw_image_src_dst_rects(src_rect, dest_rect, image) 
```

Belirtilen resmin belirtilen bölümünü belirtilen konuma ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Çizilecek resim nesnesinin bölümü. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Çizilen resmin konumu ve boyutu. Resim, dikdörtgene sığacak şekilde ölçeklendirilir. |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Çizilecek görüntü. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_8}


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

### Method: draw_path(pen, path) {#draw_path_pen_path_9}


```
 draw_path(pen, path) 
```

Yolu çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Şeklin ana hatlarını çizmeye yarayan kalem. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Çizilecek yol. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_10}


```
 draw_rectangle(pen, x, y, width, height) 
```

Dikdörtgeni çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Şeklin ana hatlarını çizmeye yarayan kalem. |
| x | int | Çizilecek dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Çizilecek dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Çizilecek dikdörtgenin genişliği. |
| height | int | Çizilecek dikdörtgenin yüksekliği. |

### Method: draw_string(font, text, origin, text_color) {#draw_string_font_text_origin_text_color_11}


```
 draw_string(font, text, origin, text_color) 
```

Metin dizesini çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Metni işlemek için kullanılan yazı tipi. |
| text | string | Unicode metin dizesi. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | Metin akışının sol üst köşesi. |
| text_color | [Color](/imaging/python-net/aspose.imaging/color/) | Metin rengi. |

### Method: end_recording() {#end_recording__12}


```
 end_recording() 
```

Tüm çizim komutlarının [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) nesnesi aracılığıyla gerçekleştirildiği son Svg görüntüsünü alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) | Son Svg görüntüsü. |


### Method: fill_arc(pen, brush, rect, start_angle, arc_angle) {#fill_arc_pen_brush_rect_start_angle_arc_angle_13}


```
 fill_arc(pen, brush, rect, start_angle, arc_angle) 
```

Bir Dikdörtgen yapısı tarafından belirtilen bir elipsin bir bölümünü temsil eden bir yay doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Şeklin ana hatlarını çizmeye yarayan kalem. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Şeklin iç kısmını doldurmak için fırça. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Elipsin sınırları. |
| start_angle | float | X ekseninden yay başlangıç noktasına doğru saat yönünde ölçülen açı (derece). |
| arc_angle | float | startAngle parametresinden yay son noktasına doğru saat yönünde ölçülen açı (derece). |

### Method: fill_path(pen, brush, path) {#fill_path_pen_brush_path_14}


```
 fill_path(pen, brush, path) 
```

Yolu doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Şeklin ana hatlarını çizmeye yarayan kalem. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Şeklin iç kısmını doldurmak için fırça. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Çizilecek yol. |

### Method: fill_rectangle(pen, brush, x, y, width, height) {#fill_rectangle_pen_brush_x_y_width_height_15}


```
 fill_rectangle(pen, brush, x, y, width, height) 
```

Dikdörtgeni doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Şeklin ana hatlarını çizmeye yarayan kalem. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Şeklin iç kısmını doldurmak için fırça. |
| x | int | Çizilecek dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Çizilecek dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Çizilecek dikdörtgenin genişliği. |
| height | int | Çizilecek dikdörtgenin yüksekliği. |

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
# 100x100 px boyutunda bir SVG görüntüsü oluşturun.
graphics = SvgGraphics2D(image_width, image_height, dpi)
pen = Pen(Color.yellow, 10)
brush = SolidBrush(Color.red)
# Tüm görüntüyü kırmızıyla doldur.
# Görüntü sınırları boyunca 10px genişliğinde sarı bir dikdörtgen çizin.
graphics.fill_rectangle(pen, brush, 0, 0, image_width, image_height)
# Tüm çizim komutlarını içeren son Svg görüntüsünü alın
with graphics.end_recording() as svg_image:
	svg_image.save(join(dir_, "test.output.svg"))


```

