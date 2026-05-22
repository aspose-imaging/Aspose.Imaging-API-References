---
title: "فئة SvgGraphics2D"
type: docs
weight: 10
url: /ar/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/
---

**Summary:** Provides drawing commmands to compose an Svg image.

**Module:** [aspose.imaging.fileformats.svg.graphics](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/)

**Full Name:** aspose.imaging.fileformats.svg.graphics.SvgGraphics2D

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [SvgGraphics2D(image)](#SvgGraphics2D_image_1) | ينشئ مثيلاً جديدًا من الفئة [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/). |
| [SvgGraphics2D(width, height, dpi)](#SvgGraphics2D_width_height_dpi_2) | ينشئ مثيلاً جديدًا من الفئة [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [draw_arc(pen, rect, start_angle, arc_angle)](#draw_arc_pen_rect_start_angle_arc_angle_1) | يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة هيكل مستطيل. |
| [draw_cubic_bezier(pen, pt1, pt2, pt3, pt4)](#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2) | يرسم بيزيه مكعب. |
| [draw_image(image, origin)](#draw_image_image_origin_3) | يرسم الصورة المحددة في الموقع المحدد. |
| [draw_image(image, origin, size)](#draw_image_image_origin_size_4) | يرسم الصورة المحددة بالحجم المحدد في الموقع المحدد. |
| [draw_image(src_rect, dest_rect, image)](#draw_image_src_rect_dest_rect_image_5) | يرسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد. |
| [draw_image_point_size(image, origin, size)](#draw_image_point_size_image_origin_size_6) | يرسم الصورة المحددة بالحجم المحدد في الموقع المحدد. |
| [draw_image_src_dst_rects(src_rect, dest_rect, image)](#draw_image_src_dst_rects_src_rect_dest_rect_image_7) | يرسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_8) | يرسم الخط. |
| [draw_path(pen, path)](#draw_path_pen_path_9) | يرسم المسار. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_10) | يرسم المستطيل. |
| [draw_string(font, text, origin, text_color)](#draw_string_font_text_origin_text_color_11) | يرسم سلسلة النص. |
| [end_recording()](#end_recording__12) | يحصل على صورة Svg النهائية التي تشمل جميع أوامر الرسم التي تم تنفيذها عبر كائن [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/). |
| [fill_arc(pen, brush, rect, start_angle, arc_angle)](#fill_arc_pen_brush_rect_start_angle_arc_angle_13) | يملأ قوسًا يمثل جزءًا من إهليلج محدد بواسطة بنية Rectangle. |
| [fill_path(pen, brush, path)](#fill_path_pen_brush_path_14) | يملأ المسار. |
| [fill_rectangle(pen, brush, x, y, width, height)](#fill_rectangle_pen_brush_x_y_width_height_15) | يملأ المستطيل. |


### Constructor: SvgGraphics2D(image) {#SvgGraphics2D_image_1}


```
 SvgGraphics2D(image) 
```

ينشئ مثيلاً جديدًا من الفئة [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) | الصورة التي تُجرى عليها عمليات الرسم. |

### Constructor: SvgGraphics2D(width, height, dpi) {#SvgGraphics2D_width_height_dpi_2}


```
 SvgGraphics2D(width, height, dpi) 
```

ينشئ مثيلاً جديدًا من الفئة [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| width | int | عرض صورة Svg الناتجة. |
| height | int | عرض صورة Svg الناتجة. |
| dpi | int | دقة الجهاز، مثال: 96 نقطة لكل بوصة. |


**See also:**

**[Example # 1](#example_171)**: This example shows how to create an SVG image of the specified size and raste...


### Method: draw_arc(pen, rect, start_angle, arc_angle) {#draw_arc_pen_rect_start_angle_arc_angle_1}


```
 draw_arc(pen, rect, start_angle, arc_angle) 
```

يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة هيكل مستطيل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | القلم لرسم حدود الشكل. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | حدود القطع الناقص. |
| start_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى نقطة بدء القوس. |
| arc_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من معلمة startAngle إلى نقطة انتهاء القوس. |

### Method: draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) {#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2}


```
 draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) 
```

يرسم بيزيه مكعب.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | القلم الذي يحدد اللون والعرض والنمط للشكل. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | نقطة البداية للمنحنى. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | نقطة التحكم الأولى للمنحنى. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | نقطة التحكم الثانية للمنحنى. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | نقطة النهاية للمنحنى. |

### Method: draw_image(image, origin) {#draw_image_image_origin_3}


```
 draw_image(image, origin) 
```

يرسم الصورة المحددة في الموقع المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة المرسومة. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | موقع الصورة المرسومة. |

### Method: draw_image(image, origin, size) {#draw_image_image_origin_size_4}


```
 draw_image(image, origin, size) 
```

يرسم الصورة المحددة بالحجم المحدد في الموقع المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة المرسومة. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | موقع الصورة المرسومة. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | الحجم المطلوب للصورة المرسومة. |

### Method: draw_image(src_rect, dest_rect, image) {#draw_image_src_rect_dest_rect_image_5}


```
 draw_image(src_rect, dest_rect, image) 
```

يرسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | الجزء من كائن الصورة الذي سيتم رسمه. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | موقع وحجم الصورة المرسومة. يتم تحجيم الصورة لتناسب المستطيل. |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة المراد رسمها. |

### Method: draw_image_point_size(image, origin, size) {#draw_image_point_size_image_origin_size_6}


```
 draw_image_point_size(image, origin, size) 
```

يرسم الصورة المحددة بالحجم المحدد في الموقع المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة المرسومة. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | موقع الصورة المرسومة. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | الحجم المطلوب للصورة المرسومة. |

### Method: draw_image_src_dst_rects(src_rect, dest_rect, image) {#draw_image_src_dst_rects_src_rect_dest_rect_image_7}


```
 draw_image_src_dst_rects(src_rect, dest_rect, image) 
```

يرسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | الجزء من كائن الصورة الذي سيتم رسمه. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | موقع وحجم الصورة المرسومة. يتم تحجيم الصورة لتناسب المستطيل. |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة المراد رسمها. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_8}


```
 draw_line(pen, x1, y1, x2, y2) 
```

يرسم الخط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | القلم الذي يحدد اللون والعرض والنمط للشكل. |
| x1 | int | الإحداثي السيني للنقطة الأولى. |
| y1 | int | الإحداثي الصادي للنقطة الأولى. |
| x2 | int | الإحداثي السيني للنقطة الثانية. |
| y2 | int | الإحداثي الصادي للنقطة الثانية. |

### Method: draw_path(pen, path) {#draw_path_pen_path_9}


```
 draw_path(pen, path) 
```

يرسم المسار.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | القلم لرسم حدود الشكل. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | المسار للرسم. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_10}


```
 draw_rectangle(pen, x, y, width, height) 
```

يرسم المستطيل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | القلم لرسم حدود الشكل. |
| x | int | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل المراد رسمه. |
| y | int | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل المراد رسمه. |
| width | int | عرض المستطيل المراد رسمه. |
| height | int | ارتفاع المستطيل المراد رسمه. |

### Method: draw_string(font, text, origin, text_color) {#draw_string_font_text_origin_text_color_11}


```
 draw_string(font, text, origin, text_color) 
```

يرسم سلسلة النص.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | الخط المستخدم لعرض النص. |
| text | string | سلسلة النص Unicode. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | الزاوية العلوية اليسرى لمجموعة النص. |
| text_color | [Color](/imaging/python-net/aspose.imaging/color/) | لون النص. |

### Method: end_recording() {#end_recording__12}


```
 end_recording() 
```

يحصل على صورة Svg النهائية التي تشمل جميع أوامر الرسم التي تم تنفيذها عبر كائن [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/).

**Returns**

| نوع | الوصف |
| :- | :- |
| [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) | الصورة النهائية Svg. |


### Method: fill_arc(pen, brush, rect, start_angle, arc_angle) {#fill_arc_pen_brush_rect_start_angle_arc_angle_13}


```
 fill_arc(pen, brush, rect, start_angle, arc_angle) 
```

يملأ قوسًا يمثل جزءًا من إهليلج محدد بواسطة بنية Rectangle.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | القلم لرسم حدود الشكل. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | الفرشاة لملء داخل الشكل. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | حدود القطع الناقص. |
| start_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى نقطة بدء القوس. |
| arc_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من معلمة startAngle إلى نقطة انتهاء القوس. |

### Method: fill_path(pen, brush, path) {#fill_path_pen_brush_path_14}


```
 fill_path(pen, brush, path) 
```

يملأ المسار.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | القلم لرسم حدود الشكل. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | الفرشاة لملء داخل الشكل. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | المسار للرسم. |

### Method: fill_rectangle(pen, brush, x, y, width, height) {#fill_rectangle_pen_brush_x_y_width_height_15}


```
 fill_rectangle(pen, brush, x, y, width, height) 
```

يملأ المستطيل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | القلم لرسم حدود الشكل. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | الفرشاة لملء داخل الشكل. |
| x | int | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل المراد رسمه. |
| y | int | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل المراد رسمه. |
| width | int | عرض المستطيل المراد رسمه. |
| height | int | ارتفاع المستطيل المراد رسمه. |

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
# إنشاء صورة SVG بحجم 100×100 بكسل.
graphics = SvgGraphics2D(image_width, image_height, dpi)
pen = Pen(Color.yellow, 10)
brush = SolidBrush(Color.red)
# ملء الصورة بالكامل باللون الأحمر.
# ارسم مستطيلًا أصفر بعرض 10 بكسل على حدود الصورة.
graphics.fill_rectangle(pen, brush, 0, 0, image_width, image_height)
# احصل على الصورة النهائية Svg التي تشمل جميع أوامر الرسم
with graphics.end_recording() as svg_image:
	svg_image.save(join(dir_, "test.output.svg"))


```

