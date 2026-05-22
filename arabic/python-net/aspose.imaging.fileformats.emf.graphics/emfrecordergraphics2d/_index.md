---
title: "EmfRecorderGraphics2D فئة"
type: docs
weight: 10
url: /ar/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/
---

**Summary:** The Emf recorder graphics

**Module:** [aspose.imaging.fileformats.emf.graphics](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/)

**Full Name:** aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D

**Inheritance:** MetafileRecorderGraphics2D

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfRecorderGraphics2D(frame, device_size, device_size_mm)](#EmfRecorderGraphics2D_frame_device_size_device_size_mm_1) | ينشئ مثلاً جديداً من الفئة [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | يحصل أو يعيّن لون الخلفية. |
| background_mode | [EmfBackgroundMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfbackgroundmode/) | r/w | يحصل أو يعيّن وضع الخلفية. |
| clip | [Region](/imaging/python-net/aspose.imaging/region/) | r/w | يحصل أو يعيّن منطقة تحدد منطقة الرسم لهذا Graphics |
| clip_bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | يحصل على حدود القص. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| clear() | يمسح حالة كائن الرسومات |
| [draw_arc(pen, rect, start_angle, arc_angle)](#draw_arc_pen_rect_start_angle_arc_angle_1) | يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة هيكل مستطيل. |
| [draw_cubic_bezier(pen, pt1, pt2, pt3, pt4)](#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2) | يرسم بيزيه مكعب. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_3) | يرسم الإهليلج. |
| [draw_image(image, dest_rect, src_rect, src_unit)](#draw_image_image_dest_rect_src_rect_src_unit_4) | يرسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد. |
| [draw_image(image, location)](#draw_image_image_location_5) | يرسم الصورة المحددة، باستخدام حجمها الفيزيائي الأصلي، في الموقع المحدد. |
| [draw_image(image_bytes, dest_rect, src_unit)](#draw_image_image_bytes_dest_rect_src_unit_6) | يرسم الصورة. |
| [draw_image(stream, dest_rect, src_unit)](#draw_image_stream_dest_rect_src_unit_7) | يرسم الصورة. |
| [draw_image_from_bytes(image_bytes, dest_rect, src_unit)](#draw_image_from_bytes_image_bytes_dest_rect_src_unit_8) | يرسم الصورة. |
| [draw_image_from_stream(stream, dest_rect, src_unit)](#draw_image_from_stream_stream_dest_rect_src_unit_9) | يرسم الصورة. |
| [draw_line(pen, pt1, pt2)](#draw_line_pen_pt1_pt2_10) | يرسم الخط. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_11) | يرسم الخط. |
| [draw_path(pen, path)](#draw_path_pen_path_12) | يرسم المسار. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_13) | يرسم الفطيرة. |
| [draw_poly_cubic_bezier(pen, points)](#draw_poly_cubic_bezier_pen_points_14) | يرسم منحنى بيزيه متعدد المكعبات. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_15) | يرسم المضلع. |
| [draw_polyline(pen, points)](#draw_polyline_pen_points_16) | يرسم الخط المتعدد. |
| [draw_rectangle(pen, rectangle)](#draw_rectangle_pen_rectangle_17) | يرسم المستطيل. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_18) | يرسم المستطيل. |
| [draw_string(string, font, color, x, y)](#draw_string_string_font_color_x_y_19) | يرسم النص. |
| [draw_string(string, font, color, x, y, angle)](#draw_string_string_font_color_x_y_angle_20) | يرسم النص. |
| [end_recording()](#end_recording__21) | ينهي التسجيل. |
| [exclude_clip(rect)](#exclude_clip_rect_22) | يقوم بتحديث منطقة القص لهذه الرسومات لاستبعاد المنطقة المحددة بواسطة بنية المستطيل. |
| [exclude_clip(region)](#exclude_clip_region_23) | يقوم بتحديث منطقة القص لهذه الرسومات لاستبعاد المنطقة المحددة بواسطة المنطقة. |
| [exclude_clip_rect(rect)](#exclude_clip_rect_rect_24) | يقوم بتحديث منطقة القص لهذه الرسومات لاستبعاد المنطقة المحددة بواسطة بنية المستطيل. |
| [exclude_clip_rgn(region)](#exclude_clip_rgn_region_25) | يقوم بتحديث منطقة القص لهذه الرسومات لاستبعاد المنطقة المحددة بواسطة المنطقة. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_26) | يملأ القطع الناقص. |
| [fill_path(pen, brush, path)](#fill_path_pen_brush_path_27) | يملأ المسار. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_28) | يملأ الفطيرة. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_29) | يملأ المضلع. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_30) | يملأ المضلع. |
| [fill_rectangle(brush, rectangle)](#fill_rectangle_brush_rectangle_31) | يملأ المستطيل. |
| [from_emf_image(emf_image)](#from_emf_image_emf_image_32) | يحصل على مثيل من الفئة [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) يحتوي على جميع السجلات من صورة Emf. |
| [get_transform()](#get_transform__33) | يحصل على تحويل العالم. |
| [intersect_clip(rect)](#intersect_clip_rect_34) | يقوم بتحديث منطقة القص لهذه الرسومات إلى تقاطع منطقة القص الحالية والبنية المحددة للمستطيل. |
| [intersect_clip(region)](#intersect_clip_region_35) | يقوم بتحديث منطقة القص لهذه الرسومات إلى تقاطع منطقة القص الحالية والمنطقة المحددة. |
| [intersect_clip_rect_f(rect)](#intersect_clip_rect_f_rect_36) | يقوم بتحديث منطقة القص لهذه الرسومات إلى تقاطع منطقة القص الحالية والبنية المحددة للمستطيل. |
| [intersect_clip_rgn(region)](#intersect_clip_rgn_region_37) | يقوم بتحديث منطقة القص لهذه الرسومات إلى تقاطع منطقة القص الحالية والمنطقة المحددة. |
| [multiply_transform(matrix)](#multiply_transform_matrix_38) | يضرب تحويل العالم لهذه الرسومات بالمصفوفة المحددة. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_39) | يضرب تحويل العالم لهذه الرسومات بالمصفوفة المحددة بالترتيب المحدد. |
| reset_clip() | يعيد ضبط القص. |
| [rotate_transform(angle)](#rotate_transform_angle_40) | يطبق الدوران المحدد على مصفوفة التحويل لهذا Graphics. |
| [rotate_transform(angle, center, order)](#rotate_transform_angle_center_order_41) | يطبق الدوران المحدد على مصفوفة التحويل لهذا Graphics بالترتيب المحدد. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_42) | يطبق عملية التحجيم المحددة على مصفوفة التحويل لهذا Graphics عن طريق إلحاقها في مقدمة مصفوفة التحويل الخاصة بالكائن. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_43) | يطبق عملية التحجيم المحددة على مصفوفة التحويل لهذا Graphics بالترتيب المحدد. |
| [set_transform(transform)](#set_transform_transform_44) | يضبط التحويل. |
| [translate_transform(x, y)](#translate_transform_x_y_45) | يغيّر أصل نظام الإحداثيات عن طريق إلحاق الترجمة المحددة في مقدمة مصفوفة التحويل لهذا Graphics. |
| [translate_transform(x, y, order)](#translate_transform_x_y_order_46) | يغيّر أصل نظام الإحداثيات عن طريق تطبيق الترجمة المحددة على مصفوفة التحويل لهذا Graphics بالترتيب المحدد. |


### Constructor: EmfRecorderGraphics2D(frame, device_size, device_size_mm) {#EmfRecorderGraphics2D_frame_device_size_device_size_mm_1}


```
 EmfRecorderGraphics2D(frame, device_size, device_size_mm) 
```

ينشئ مثلاً جديداً من الفئة [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| frame | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | الإطار. |
| device_size | [Size](/imaging/python-net/aspose.imaging/size/) | حجم الجهاز. |
| device_size_mm | [Size](/imaging/python-net/aspose.imaging/size/) | حجم الجهاز بالمليمتر. |


**See also:**

**[Example # 1](#example_174)**: This example shows how to create a EMF image and draw some geometric shapes o...


### Method: draw_arc(pen, rect, start_angle, arc_angle) {#draw_arc_pen_rect_start_angle_arc_angle_1}


```
 draw_arc(pen, rect, start_angle, arc_angle) 
```

يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة هيكل مستطيل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | قلم يحدد اللون والعرض والنمط للشكل. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | حدود القطع الناقص. |
| start_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى نقطة بدء القوس. |
| arc_angle | float | الزاوية بالدرجات مقاسة باتجاه عقارب الساعة من معامل startAngle إلى نقطة النهاية للقوس. |

### Method: draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) {#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2}


```
 draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) 
```

يرسم بيزيه مكعب.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | قلم يحدد اللون والعرض والنمط للشكل. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | نقطة البداية للمنحنى. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | نقطة التحكم الأولى للمنحنى. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | نقطة التحكم الثانية للمنحنى. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | نقطة النهاية للمنحنى. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_3}


```
 draw_ellipse(pen, rect) 
```

يرسم الإهليلج.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | قلم يحدد اللون والعرض والنمط للشكل. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | حدود القطع الناقص. |

### Method: draw_image(image, dest_rect, src_rect, src_unit) {#draw_image_image_dest_rect_src_rect_src_unit_4}


```
 draw_image(image, dest_rect, src_rect, src_unit) 
```

يرسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة المراد رسمها. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل المستطيل الذي يحدد موقع وحجم الصورة المرسومة. يتم تحجيم الصورة لتناسب المستطيل. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل المستطيل الذي يحدد الجزء من كائن الصورة الذي سيتم رسمه. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدات القياس المستخدمة بواسطة معامل srcRect. |

### Method: draw_image(image, location) {#draw_image_image_location_5}


```
 draw_image(image, location) 
```

يرسم الصورة المحددة، باستخدام حجمها الفيزيائي الأصلي، في الموقع المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة المراد رسمها. |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | موقع الزاوية العلوية اليسرى للصورة المرسومة. |

### Method: draw_image(image_bytes, dest_rect, src_unit) {#draw_image_image_bytes_dest_rect_src_unit_6}


```
 draw_image(image_bytes, dest_rect, src_unit) 
```

يرسم الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image_bytes | System.Byte | بايتات الصورة. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل الوجهة. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدة المصدر. |

### Method: draw_image(stream, dest_rect, src_unit) {#draw_image_stream_dest_rect_src_unit_7}


```
 draw_image(stream, dest_rect, src_unit) 
```

يرسم الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل الوجهة. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدة المصدر. |

### Method: draw_image_from_bytes(image_bytes, dest_rect, src_unit) {#draw_image_from_bytes_image_bytes_dest_rect_src_unit_8}


```
 draw_image_from_bytes(image_bytes, dest_rect, src_unit) 
```

يرسم الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image_bytes | System.Byte | بايتات الصورة. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل الوجهة. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدة المصدر. |

### Method: draw_image_from_stream(stream, dest_rect, src_unit) {#draw_image_from_stream_stream_dest_rect_src_unit_9}


```
 draw_image_from_stream(stream, dest_rect, src_unit) 
```

يرسم الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل الوجهة. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدة المصدر. |

### Method: draw_line(pen, pt1, pt2) {#draw_line_pen_pt1_pt2_10}


```
 draw_line(pen, pt1, pt2) 
```

يرسم الخط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | قلم يحدد اللون والعرض والنمط للشكل. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | النقطة الأولى. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | النقطة الثانية. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_11}


```
 draw_line(pen, x1, y1, x2, y2) 
```

يرسم الخط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | قلم يحدد اللون والعرض والنمط للشكل. |
| x1 | int | الإحداثي السيني للنقطة الأولى. |
| y1 | int | الإحداثي الصادي للنقطة الأولى. |
| x2 | int | الإحداثي السيني للنقطة الثانية. |
| y2 | int | الإحداثي الصادي للنقطة الثانية. |

### Method: draw_path(pen, path) {#draw_path_pen_path_12}


```
 draw_path(pen, path) 
```

يرسم المسار.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | قلم يحدد اللون والعرض والنمط للشكل. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | المسار للرسم. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_13}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

يرسم الفطيرة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | قلم يحدد اللون والعرض والنمط للشكل. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | حدود القطع الناقص. |
| start_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى نقطة بدء القوس. |
| sweep_angle | float | الزاوية بالدرجات مقاسة باتجاه عقارب الساعة من معامل startAngle إلى نقطة النهاية للقوس. |

### Method: draw_poly_cubic_bezier(pen, points) {#draw_poly_cubic_bezier_pen_points_14}


```
 draw_poly_cubic_bezier(pen, points) 
```

يرسم منحنى بيزيه متعدد المكعبات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | قلم يحدد اللون والعرض والنمط للشكل. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | النقاط. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_15}


```
 draw_polygon(pen, points) 
```

يرسم المضلع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | قلم يحدد اللون والعرض والنمط للشكل. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | النقاط. |

### Method: draw_polyline(pen, points) {#draw_polyline_pen_points_16}


```
 draw_polyline(pen, points) 
```

يرسم الخط المتعدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | قلم يحدد اللون والعرض والنمط للشكل. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | النقاط. |

### Method: draw_rectangle(pen, rectangle) {#draw_rectangle_pen_rectangle_17}


```
 draw_rectangle(pen, rectangle) 
```

يرسم المستطيل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | قلم يحدد اللون والعرض والنمط للشكل. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل للرسم. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_18}


```
 draw_rectangle(pen, x, y, width, height) 
```

يرسم المستطيل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | قلم يحدد اللون والعرض والنمط للشكل. |
| x | int | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل المراد رسمه. |
| y | int | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل المراد رسمه. |
| width | int | عرض المستطيل المراد رسمه. |
| height | int | ارتفاع المستطيل المراد رسمه. |

### Method: draw_string(string, font, color, x, y) {#draw_string_string_font_color_x_y_19}


```
 draw_string(string, font, color, x, y) 
```

يرسم النص.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| string | string | السلسلة. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | الخط الذي يحدد تنسيق النص للسلسلة. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | لون النص. |
| x | int | الإحداثي السيني للزاوية العليا اليسرى للنص المرسوم. |
| y | int | الإحداثي الصادي للزاوية العليا اليسرى للنص المرسوم. |

### Method: draw_string(string, font, color, x, y, angle) {#draw_string_string_font_color_x_y_angle_20}


```
 draw_string(string, font, color, x, y, angle) 
```

يرسم النص.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| string | string | السلسلة. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | الخط الذي يحدد تنسيق النص للسلسلة. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | لون النص. |
| x | int | الإحداثي السيني للزاوية العليا اليسرى للنص المرسوم. |
| y | int | الإحداثي الصادي للزاوية العليا اليسرى للنص المرسوم. |
| angle | float | الزاوية بالدرجات، بين متجه الإزاحة ومحور x للجهاز.<br/>            متجه الإزاحة موازٍ للخط الأساسي لسطر من النص. |

### Method: end_recording() {#end_recording__21}


```
 end_recording() 
```

ينهي التسجيل.

**Returns**

| نوع | الوصف |
| :- | :- |
| [EmfImage](/imaging/python-net/aspose.imaging.fileformats.emf/emfimage/) | صورة النتيجة. |


### Method: exclude_clip(rect) {#exclude_clip_rect_22}


```
 exclude_clip(rect) 
```

يقوم بتحديث منطقة القص لهذه الرسومات لاستبعاد المنطقة المحددة بواسطة بنية المستطيل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل المستطيل الذي يحدد المستطيل المستبعد من منطقة القص. |

### Method: exclude_clip(region) {#exclude_clip_region_23}


```
 exclude_clip(region) 
```

يقوم بتحديث منطقة القص لهذه الرسومات لاستبعاد المنطقة المحددة بواسطة المنطقة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | المنطقة التي تحدد المنطقة المستبعدة من منطقة القص. |

### Method: exclude_clip_rect(rect) {#exclude_clip_rect_rect_24}


```
 exclude_clip_rect(rect) 
```

يقوم بتحديث منطقة القص لهذه الرسومات لاستبعاد المنطقة المحددة بواسطة بنية المستطيل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل المستطيل الذي يحدد المستطيل المستبعد من منطقة القص. |

### Method: exclude_clip_rgn(region) {#exclude_clip_rgn_region_25}


```
 exclude_clip_rgn(region) 
```

يقوم بتحديث منطقة القص لهذه الرسومات لاستبعاد المنطقة المحددة بواسطة المنطقة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | المنطقة التي تحدد المنطقة المستبعدة من منطقة القص. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_26}


```
 fill_ellipse(brush, rect) 
```

يملأ القطع الناقص.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | الفرشاة التي تحدد خصائص التعبئة. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | حدود القطع الناقص. |

### Method: fill_path(pen, brush, path) {#fill_path_pen_brush_path_27}


```
 fill_path(pen, brush, path) 
```

يملأ المسار.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | قلم يحدد اللون والعرض والنمط للشكل. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | الفرشاة التي تحدد خصائص التعبئة. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | المسار للتعبئة. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_28}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

يملأ الفطيرة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | الفرشاة التي تحدد خصائص التعبئة. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | حدود القطع الناقص. |
| start_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى نقطة بدء القوس. |
| sweep_angle | float | الزاوية بالدرجات مقاسة باتجاه عقارب الساعة من معامل startAngle إلى نقطة النهاية للقوس. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_29}


```
 fill_polygon(brush, points) 
```

يملأ المضلع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | الفرشاة التي تحدد خصائص التعبئة. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | النقاط. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_30}


```
 fill_polygon(brush, points, fill_mode) 
```

يملأ المضلع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | الفرشاة التي تحدد خصائص التعبئة. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | النقاط. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | وضع التعبئة. |

### Method: fill_rectangle(brush, rectangle) {#fill_rectangle_brush_rectangle_31}


```
 fill_rectangle(brush, rectangle) 
```

يملأ المستطيل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | الفرشاة التي تحدد خصائص التعبئة. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل للتعبئة. |

### Method: from_emf_image(emf_image)  [static] {#from_emf_image_emf_image_32}


```
 from_emf_image(emf_image) 
```

يحصل على مثيل من الفئة [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) يحتوي على جميع السجلات من صورة Emf.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| emf_image | [EmfImage](/imaging/python-net/aspose.imaging.fileformats.emf/emfimage/) | صورة Emf لقراءة السجلات منها. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) | مثيل من الفئة [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) |


### Method: get_transform() {#get_transform__33}


```
 get_transform() 
```

يحصل على تحويل العالم.

**Returns**

| نوع | الوصف |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) | مصفوفة التحويل. |


### Method: intersect_clip(rect) {#intersect_clip_rect_34}


```
 intersect_clip(rect) 
```

يقوم بتحديث منطقة القص لهذه الرسومات إلى تقاطع منطقة القص الحالية والبنية المحددة للمستطيل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل المستطيل لتقاطع مع منطقة القص الحالية. |

### Method: intersect_clip(region) {#intersect_clip_region_35}


```
 intersect_clip(region) 
```

يقوم بتحديث منطقة القص لهذه الرسومات إلى تقاطع منطقة القص الحالية والمنطقة المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | المنطقة لتقاطع مع المنطقة الحالية. |

### Method: intersect_clip_rect_f(rect) {#intersect_clip_rect_f_rect_36}


```
 intersect_clip_rect_f(rect) 
```

يقوم بتحديث منطقة القص لهذه الرسومات إلى تقاطع منطقة القص الحالية والبنية المحددة للمستطيل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل المستطيل لتقاطع مع منطقة القص الحالية. |

### Method: intersect_clip_rgn(region) {#intersect_clip_rgn_region_37}


```
 intersect_clip_rgn(region) 
```

يقوم بتحديث منطقة القص لهذه الرسومات إلى تقاطع منطقة القص الحالية والمنطقة المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | المنطقة لتقاطع مع المنطقة الحالية. |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_38}


```
 multiply_transform(matrix) 
```

يضرب تحويل العالم لهذه الرسومات بالمصفوفة المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | المصفوفة التي تضرب التحويل العالمي. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_39}


```
 multiply_transform(matrix, order) 
```

يضرب تحويل العالم لهذه الرسومات بالمصفوفة المحددة بالترتيب المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | المصفوفة التي تضرب التحويل العالمي. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | ترتيب الضرب. |

### Method: rotate_transform(angle) {#rotate_transform_angle_40}


```
 rotate_transform(angle) 
```

يطبق الدوران المحدد على مصفوفة التحويل لهذا Graphics.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| angle | float | زاوية الدوران بالدرجات. |

### Method: rotate_transform(angle, center, order) {#rotate_transform_angle_center_order_41}


```
 rotate_transform(angle, center, order) 
```

يطبق الدوران المحدد على مصفوفة التحويل لهذا Graphics بالترتيب المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| angle | float | زاوية الدوران بالدرجات. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | مركز الدوران. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | يحدد ما إذا كان يتم إلحاق الدوران أو إضافته إلى تحويل المصفوفة.. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_42}


```
 scale_transform(sx, sy) 
```

يطبق عملية التحجيم المحددة على مصفوفة التحويل لهذا Graphics عن طريق إلحاقها في مقدمة مصفوفة التحويل الخاصة بالكائن.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| sx | float | عامل المقياس في الاتجاه السيني. |
| sy | float | عامل المقياس في الاتجاه الصادي. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_43}


```
 scale_transform(sx, sy, order) 
```

يطبق عملية التحجيم المحددة على مصفوفة التحويل لهذا Graphics بالترتيب المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| sx | float | عامل المقياس في الاتجاه السيني. |
| sy | float | عامل المقياس في الاتجاه الصادي. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | يحدد ما إذا كانت عملية التحجيم تُضاف مسبقًا أو تُلحق بمصفوفة التحويل. |

### Method: set_transform(transform) {#set_transform_transform_44}


```
 set_transform(transform) 
```

يضبط التحويل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | مصفوفة التحويل الجديدة. |

### Method: translate_transform(x, y) {#translate_transform_x_y_45}


```
 translate_transform(x, y) 
```

يغيّر أصل نظام الإحداثيات عن طريق إلحاق الترجمة المحددة في مقدمة مصفوفة التحويل لهذا Graphics.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | float | الإحداثي السيني للترجمة. |
| y | float | الإحداثي الصادي للترجمة. |

### Method: translate_transform(x, y, order) {#translate_transform_x_y_order_46}


```
 translate_transform(x, y, order) 
```

يغيّر أصل نظام الإحداثيات عن طريق تطبيق الترجمة المحددة على مصفوفة التحويل لهذا Graphics بالترتيب المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | float | الإحداثي السيني للترجمة. |
| y | float | الإحداثي الصادي للترجمة. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | يحدد ما إذا كانت الترجمة تُضاف مسبقًا أو تُلحق بمصفوفة التحويل. |

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
# حجم الصورة بالبكسل
device_width: int = 600
device_height: int = 400
# حجم الصورة بالمليمترات
device_width_mm = device_width // 100
device_height_mm = device_height // 100
frame = Rectangle(0, 0, device_width, device_height)
# إنشاء صورة EMF.
graphics = EmfRecorderGraphics2D(frame, Size(device_width, device_height), Size(device_width_mm, device_height_mm))
# ارسم مستطيلًا أسود على حدود الصورة باستخدام قلم أسود بعرض بكسل واحد.
graphics.draw_rectangle(Pen(Color.black, 1), 0, 0, device_width, device_height)
# املأ مستطيلًا بلون الدخان الأبيض.
graphics.fill_rectangle(SolidBrush(Color.white_smoke), Rectangle(10, 10, 580, 380))
# ارسم خطين قطريين باستخدام قلم أخضر داكن بعرض بكسل واحد.
graphics.draw_line(Pen(Color.dark_green, 1), 0, 0, device_width, device_height)
graphics.draw_line(Pen(Color.dark_green, 1), 0, device_height, device_width, 0)
# ارسم قوسًا داخل المستطيل {0, 0, 200, 200} باستخدام قلم أزرق بعرض بكسلين.
graphics.draw_arc(Pen(Color.blue, 2), Rectangle(0, 0, 200, 200), 90, 270)
# املأ قوسًا
graphics.fill_pie(SolidBrush(Color.light_sky_blue), Rectangle(0, 0, 150, 150), 90, 270)
# ارسم منحنى بيزيه مكعب باستخدام قلم أحمر بعرض بكسلين.
graphics.draw_cubic_bezier(Pen(Color.red, 2), Point(0, 0), Point(200, 133), Point(400, 166), Point(600, 400))

# ارسم صورة نقطية بالحجم المحدد في الموقع المحدد.
# يتم تحجيم الصورة لتناسب المستطيل المطلوب.
with aspycore.as_of(Image.load(join(dir_, "sample.bmp")), RasterImage) as image_to_draw:
	graphics.draw_image(image_to_draw, Rectangle(400, 200, 100, 50), Rectangle(0, 0, device_width, device_height), GraphicsUnit.PIXEL)

# ارسم سلسلة نصية
graphics.draw_string("Hello World!", Font("Arial", 48, FontStyle.REGULAR), Color.dark_red, 200, 300)

# إنشاء مسار للتعبئة
figure_to_fill = Figure()
figure_to_fill.is_closed = True
path_to_fill = GraphicsPath()
path_to_fill.add_figure(figure_to_fill)
figure_to_fill.add_shapes([ArcShape(Rectangle(400, 0, 200, 100), 45, 300), BezierShape([PointF(300, 200), PointF(400, 200), PointF(500, 100), PointF(600, 200)]), PolygonShape([PointF(300, 100)]), RectangleShape(RectangleF(0, 100, 200, 200))])

# املأ المسار باستخدام فرشاة صفراء وقلم أخضر لرسم الحدود
graphics.fill_path(Pen(Color.green, 2), SolidBrushColor.yellow), path_to_fill)

# إنشاء مسار للرسم
path_to_draw = GraphicsPath()
figure_to_draw = Figure()
path_to_draw.add_figure(figure_to_draw)
figure_to_draw.add_shapes([ArcShape(RectangleF(200, 200, 200, 200), 0, 360)])

# ارسم المسار باستخدام قلم برتقالي بعرض 5 بكسلات.
graphics.draw_path(Pen(Color.orange, 5), path_to_draw)

# احصل على صورة WMF النهائية التي تشمل جميع أوامر الرسم
with graphics.end_recording() as emf_image:
	emf_image.save(join(dir_, "test.output.emf"))


```

