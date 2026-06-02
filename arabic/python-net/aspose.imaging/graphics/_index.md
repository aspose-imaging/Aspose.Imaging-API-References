---
title: "الفئة Graphics"
type: docs
weight: 5030
url: /ar/python-net/aspose.imaging/graphics/
---

**Summary:** Represents the graphics according to the graphics engine used in the current assembly.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Graphics

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Graphics(source_image)](#Graphics_source_image_1) | يُنشئ مثلاً جديدًا من الفئة [Graphics](/imaging/python-net/aspose.imaging/graphics/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| clip | [Region](/imaging/python-net/aspose.imaging/region/) | r/w | يحصل أو يعيّن منطقة القص. |
| compositing_quality | [CompositingQuality](/imaging/python-net/aspose.imaging/compositingquality/) | r/w | يحصل أو يضبط جودة التركيب. |
| dpi_x | float | r | يحصل على الدقة الأفقية لهذا `aspose.imaging.Graphics`. |
| dpi_y | float | r | يحصل على الدقة العمودية لهذا `aspose.imaging.Graphics`. |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | r | يحصل على الصورة. |
| interpolation_mode | [InterpolationMode](/imaging/python-net/aspose.imaging/interpolationmode/) | r/w | يحصل أو يضبط وضع الاستيفاء. |
| is_in_begin_update_call | bool | r | يحصل على قيمة تشير إلى ما إذا كانت الرسومات في حالة استدعاء BeginUpdate. |
| page_scale | float | r/w | يحصل أو يضبط المقياس بين وحدات العالم ووحدات الصفحة لهذا `aspose.imaging.Graphics`. |
| page_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | r/w | يحصل أو يضبط وحدة القياس المستخدمة لإحداثيات الصفحة في هذا `aspose.imaging.Graphics`. |
| paintable_image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | r/w | يحصل أو يضبط خيارات الصورة، المستخدمة لإنشاء صور متجهية قابلة للطلاء للرسم. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | يحصل أو يضبط وضع التنعيم. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | يحصل أو يضبط تلميح عرض النص. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | يحصل أو يضبط نسخة من التحويل الهندسي العالمي لهذا [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| begin_update() | يبدأ تخزين عمليات الرسومات التالية في الذاكرة المؤقتة. لن يتم تطبيق تأثيرات الرسومات التي تُطبق بعد ذلك فورًا، بل سيؤدي EndUpdate إلى تطبيق جميع التأثيرات مرة واحدة. |
| [clear(color)](#clear_color_1) | يمسح سطح الرسومات باستخدام اللون المحدد. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_2) | يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة بنية [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_3) | يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة بنية [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4) | يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5) | يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع. |
| [draw_arc_in_rect(pen, rect, start_angle, sweep_angle)](#draw_arc_in_rect_pen_rect_start_angle_sweep_angle_6) | يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة بنية [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle)](#draw_arc_in_rect_f_pen_rect_start_angle_sweep_angle_7) | يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة بنية [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_xy_pen_x_y_width_height_start_angle_sweep_angle_8) | يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع. |
| [draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_xyf_pen_x_y_width_height_start_angle_sweep_angle_9) | يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_10) | يرسم منحنى بيزيير محدد بأربع بنى [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_11) | يرسم منحنى بيزيير محدد بأربع بنى [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4)](#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_12) | يرسم منحنى بيزيير محدد بأربع أزواج مرتبة من الإحداثيات تمثل نقاطًا. |
| [draw_bezier_by_points(pen, pt1, pt2, pt3, pt4)](#draw_bezier_by_points_pen_pt1_pt2_pt3_pt4_13) | يرسم منحنى بيزيير محدد بأربع بنى [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4)](#draw_bezier_by_points_f_pen_pt1_pt2_pt3_pt4_14) | يرسم منحنى بيزيير محدد بأربع بنى [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_15) | يرسم سلسلة من منحنيات بيزيير من مصفوفة من بنى [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_16) | يرسم سلسلة من منحنيات بيزيير من مصفوفة من بنى [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_beziers_by_pt_array(pen, points)](#draw_beziers_by_pt_array_pen_points_17) | يرسم سلسلة من منحنيات بيزيير من مصفوفة من بنى [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_beziers_by_pt_array_f(pen, points)](#draw_beziers_by_pt_array_f_pen_points_18) | يرسم سلسلة من منحنيات بيزيير من مصفوفة من بنى [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_19) | يرسم منحنى كاردينال مغلق محدد بمصفوفة من بنى [PointF](/imaging/python-net/aspose.imaging/pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 ووضع تعبئة [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_20) | يرسم منحنى كاردينال مغلق محدد بمصفوفة من بنى [PointF](/imaging/python-net/aspose.imaging/pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 ووضع تعبئة [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_21) | يرسم منحنى كاردينال مغلق محدد بمصفوفة من بنى [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام توتر محدد. تستخدم هذه الطريقة وضع تعبئة افتراضي [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_22) | يرسم منحنى كاردينال مغلق محدد بمصفوفة من بنى [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام توتر محدد. تستخدم هذه الطريقة وضع تعبئة افتراضي [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve_by_points(pen, points)](#draw_closed_curve_by_points_pen_points_23) | يرسم منحنى كاردينال مغلق محدد بمصفوفة من بنى [PointF](/imaging/python-net/aspose.imaging/pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 ووضع تعبئة [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve_by_points_f(pen, points)](#draw_closed_curve_by_points_f_pen_points_24) | يرسم منحنى كاردينال مغلق محدد بمصفوفة من بنى [PointF](/imaging/python-net/aspose.imaging/pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 ووضع تعبئة [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve_by_points_f_tension(pen, points, tension)](#draw_closed_curve_by_points_f_tension_pen_points_tension_25) | يرسم منحنى كاردينال مغلق محدد بمصفوفة من بنى [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام توتر محدد. تستخدم هذه الطريقة وضع تعبئة افتراضي [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve_by_points_tension(pen, points, tension)](#draw_closed_curve_by_points_tension_pen_points_tension_26) | يرسم منحنى كاردينال مغلق محدد بمصفوفة من بنى [Point](/imaging/python-net/aspose.imaging/point/) باستخدام توتر محدد. تستخدم هذه الطريقة وضع تعبئة افتراضي [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_curve(pen, points)](#draw_curve_pen_points_27) | يرسم منحنى كاردينال عبر مصفوفة محددة من بنى [PointF](/imaging/python-net/aspose.imaging/pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5. |
| [draw_curve(pen, points)](#draw_curve_pen_points_28) | يرسم منحنى كاردينال عبر مصفوفة محددة من بنى [PointF](/imaging/python-net/aspose.imaging/pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5. |
| [draw_curve(pen, points, offset, number_of_segments)](#draw_curve_pen_points_offset_number_of_segments_29) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/). يبدأ الرسم متأخراً عن بداية المصفوفة.<br/>            تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_30) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام توتر محدد. يبدأ الرسم متأخراً عن بداية المصفوفة. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_31) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام توتر محدد. يبدأ الرسم متأخراً عن بداية المصفوفة. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_32) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام توتر محدد. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_33) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام توتر محدد. |
| [draw_curve_by_point_fs(pen, points)](#draw_curve_by_point_fs_pen_points_34) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_curve_by_point_fs_tension(pen, points, tension)](#draw_curve_by_point_fs_tension_pen_points_tension_35) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام توتر محدد. |
| [draw_curve_by_points(pen, points)](#draw_curve_by_points_pen_points_36) | يرسم منحنى كاردينال عبر مصفوفة محددة من بنى [PointF](/imaging/python-net/aspose.imaging/pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5. |
| [draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension)](#draw_curve_by_points_f_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_37) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام توتر محدد. يبدأ الرسم متأخراً عن بداية المصفوفة. |
| [draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension)](#draw_curve_by_points_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_38) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [Point](/imaging/python-net/aspose.imaging/point/) باستخدام توتر محدد. |
| [draw_curve_by_points_tension(pen, points, tension)](#draw_curve_by_points_tension_pen_points_tension_39) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [Point](/imaging/python-net/aspose.imaging/point/) باستخدام توتر محدد. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_40) | يرسم قطعًا ناقصًا يُحدَّد بواسطة [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) محيط. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_41) | يرسم قطعًا ناقصًا يُحدَّد بواسطة [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) محيط. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_42) | يرسم قطعًا ناقصًا يُحدَّد بواسطة مستطيل محيط يُحدد بواسطة زوج من الإحداثيات، ارتفاع، وعرض. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_43) | يرسم قطعًا ناقصًا يُحدَّد بواسطة مستطيل محيط يُحدد بواسطة زوج من الإحداثيات، ارتفاع، وعرض. |
| [draw_ellipse_by_xy(pen, x, y, width, height)](#draw_ellipse_by_xy_pen_x_y_width_height_44) | يرسم قطعًا ناقصًا يُحدَّد بواسطة مستطيل محيط يُحدد بواسطة زوج من الإحداثيات، ارتفاع، وعرض. |
| [draw_ellipse_by_xyf(pen, x, y, width, height)](#draw_ellipse_by_xyf_pen_x_y_width_height_45) | يرسم قطعًا ناقصًا يُحدَّد بواسطة مستطيل محيط يُحدد بواسطة زوج من الإحداثيات، ارتفاع، وعرض. |
| [draw_ellipse_f(pen, rect)](#draw_ellipse_f_pen_rect_46) | يرسم قطعًا ناقصًا يُحدَّد بواسطة [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) محيط. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_47) | يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_48) | يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_49) | يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_50) | يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_51) | يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_52) | يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_53) | يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_54) | يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(source_image, point)](#draw_image_source_image_point_55) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد. |
| [draw_image(source_image, point)](#draw_image_source_image_point_56) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_57) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_58) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_59) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_60) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_61) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_62) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_63) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_64) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_65) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_66) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_67) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_68) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_69) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_70) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image_at_point(source_image, point)](#draw_image_at_point_source_image_point_71) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد. |
| [draw_image_at_point_f(source_image, point)](#draw_image_at_point_f_source_image_point_72) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد. |
| [draw_image_at_xy(source_image, x, y)](#draw_image_at_xy_source_image_x_y_73) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد. |
| [draw_image_at_xyf(source_image, x, y)](#draw_image_at_xyf_source_image_x_y_74) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد. |
| [draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit)](#draw_image_dest_point_f_src_rect_f_with_unit_image_dest_points_src_rect_src_unit_75) | يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_dest_point_f_src_rect_f_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_76) | يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect)](#draw_image_dest_points_f_src_rect_f_image_dest_points_src_rect_77) | يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image_dest_points_src_rect(image, dest_points, src_rect)](#draw_image_dest_points_src_rect_image_dest_points_src_rect_78) | يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit)](#draw_image_dest_points_src_rect_with_unit_image_dest_points_src_rect_src_unit_79) | يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_dest_points_src_rect_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_80) | يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_dest_rect_f_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_81) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_dest_rect_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_82) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image_in_rect(source_image, x, y, width, height)](#draw_image_in_rect_source_image_x_y_width_height_83) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image_in_rect_f(source_image, x, y, width, height)](#draw_image_in_rect_f_source_image_x_y_width_height_84) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image_in_rectangle(source_image, rect)](#draw_image_in_rectangle_source_image_rect_85) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image_points(image, dest_points)](#draw_image_points_image_dest_points_86) | يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image_points_f(image, dest_points)](#draw_image_points_f_image_dest_points_87) | يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image_rectangle_f(source_image, rect)](#draw_image_rectangle_f_source_image_rect_88) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_src_dest_rects_f_with_unit_source_image_rect_source_rect_destination_graphics_unit_89) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_src_dest_rects_with_unit_source_image_rect_source_rect_destination_graphics_unit_90) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_src_dst_rect_f_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_91) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_src_dst_rects_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_92) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit)](#draw_image_to_rect_f_with_unit_source_image_rect_destination_graphics_unit_93) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit)](#draw_image_to_rect_with_unit_source_image_rect_destination_graphics_unit_94) | يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image_unscaled(source_image, point)](#draw_image_unscaled_source_image_point_95) | يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد. |
| [draw_image_unscaled(source_image, rect)](#draw_image_unscaled_source_image_rect_96) | يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد. |
| [draw_image_unscaled(source_image, x, y)](#draw_image_unscaled_source_image_x_y_97) | يرسم الصورة المحددة باستخدام حجمها الفيزيائي الأصلي في الموقع المحدد بواسطة زوج من الإحداثيات. |
| [draw_image_unscaled(source_image, x, y, width, height)](#draw_image_unscaled_source_image_x_y_width_height_98) | يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد. |
| [draw_image_unscaled_and_clipped(source_image, rect)](#draw_image_unscaled_and_clipped_source_image_rect_99) | يرسم الصورة المحددة دون تغيير الحجم ويقصها، إذا لزم الأمر، لتتناسب مع المستطيل المحدد. |
| [draw_image_unscaled_in_rectangle(source_image, rect)](#draw_image_unscaled_in_rectangle_source_image_rect_100) | يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد. |
| [draw_image_unscaled_to_point(source_image, point)](#draw_image_unscaled_to_point_source_image_point_101) | يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_102) | يرسم خطًا يربط بين هيكلين [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_103) | يرسم خطًا يربط بين هيكلين [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_104) | يرسم خطًا يربط النقطتين المحددتين بواسطة أزواج الإحداثيات. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_105) | يرسم خطًا يربط النقطتين المحددتين بواسطة أزواج الإحداثيات. |
| [draw_line_by_xy(pen, x1, y1, x2, y2)](#draw_line_by_xy_pen_x1_y1_x2_y2_106) | يرسم خطًا يربط النقطتين المحددتين بواسطة أزواج الإحداثيات. |
| [draw_line_f_by_xy(pen, x1, y1, x2, y2)](#draw_line_f_by_xy_pen_x1_y1_x2_y2_107) | يرسم خطًا يربط النقطتين المحددتين بواسطة أزواج الإحداثيات. |
| [draw_line_point_f(pen, point1, point2)](#draw_line_point_f_pen_point1_point2_108) | يرسم خطًا يربط بين هيكلين [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_lines(pen, points)](#draw_lines_pen_points_109) | يرسم سلسلة من مقاطع الخط التي تربط مصفوفة من هياكل [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_lines(pen, points)](#draw_lines_pen_points_110) | يرسم سلسلة من مقاطع الخط التي تربط مصفوفة من هياكل [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_lines_f(pen, points)](#draw_lines_f_pen_points_111) | يرسم سلسلة من مقاطع الخط التي تربط مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_path(pen, path)](#draw_path_pen_path_112) | يرسم [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_113) | يرسم شكل فطيرة يُحدَّد بواسطة قطع ناقص محدد بواسطة هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) وخطين شعاعيين. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_114) | يرسم شكل فطيرة يُحدَّد بواسطة قطع ناقص محدد بواسطة هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) وخطين شعاعيين. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_115) | يرسم شكل فطيرة يُحدَّد بواسطة قطع ناقص محدد بواسطة زوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_116) | يرسم شكل فطيرة يُحدَّد بواسطة قطع ناقص محدد بواسطة زوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين. |
| [draw_pie_in_rect(pen, rect, start_angle, sweep_angle)](#draw_pie_in_rect_pen_rect_start_angle_sweep_angle_117) | يرسم شكل فطيرة يُحدَّد بواسطة قطع ناقص محدد بواسطة هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) وخطين شعاعيين. |
| [draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle)](#draw_pie_in_rect_f_pen_rect_start_angle_sweep_angle_118) | يرسم شكل فطيرة يُحدَّد بواسطة قطع ناقص محدد بواسطة هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) وخطين شعاعيين. |
| [draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_xy_pen_x_y_width_height_start_angle_sweep_angle_119) | يرسم شكل فطيرة يُحدَّد بواسطة قطع ناقص محدد بواسطة زوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين. |
| [draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_xyf_pen_x_y_width_height_start_angle_sweep_angle_120) | يرسم شكل فطيرة يُحدَّد بواسطة قطع ناقص محدد بواسطة زوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_121) | يرسم مضلعًا يُحدَّد بواسطة مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_122) | يرسم مضلعًا يُحدَّد بواسطة مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_polygon_f(pen, points)](#draw_polygon_f_pen_points_123) | يرسم مضلعًا يُحدَّد بواسطة مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_rect(pen, x, y, width, height)](#draw_rect_pen_x_y_width_height_124) | يرسم مستطيلًا يُحدَّد بواسطة زوج من الإحداثيات، عرض، وارتفاع. |
| [draw_rect_f(pen, x, y, width, height)](#draw_rect_f_pen_x_y_width_height_125) | يرسم مستطيلًا يُحدَّد بواسطة زوج من الإحداثيات، عرض، وارتفاع. |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_126) | يرسم مستطيلًا يُحدَّد بواسطة هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_127) | يرسم مستطيلًا يُحدَّد بواسطة هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_128) | يرسم مستطيلًا يُحدَّد بواسطة زوج من الإحداثيات، عرض، وارتفاع. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_129) | يرسم مستطيلًا يُحدَّد بواسطة زوج من الإحداثيات، عرض، وارتفاع. |
| [draw_rectangle_f(pen, rect)](#draw_rectangle_f_pen_rect_130) | يرسم مستطيلًا يُحدَّد بواسطة هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_131) | يرسم سلسلة من المستطيلات التي تُحدَّد بواسطة هياكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_132) | يرسم سلسلة من المستطيلات التي تُحدَّد بواسطة هياكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_rectangles_f(pen, rects)](#draw_rectangles_f_pen_rects_133) | يرسم سلسلة من المستطيلات التي تُحدَّد بواسطة هياكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_string(s, font, brush, layout_rectangle)](#draw_string_s_font_brush_layout_rectangle_134) | يرسم سلسلة النص المحددة في المستطيل المحدد باستخدام [Brush](/imaging/python-net/aspose.imaging/brush/) و[Font](/imaging/python-net/aspose.imaging/font/) المحددين. |
| [draw_string(s, font, brush, layout_rectangle, format)](#draw_string_s_font_brush_layout_rectangle_format_135) | يرسم سلسلة النص المحددة في المستطيل المحدد باستخدام [Brush](/imaging/python-net/aspose.imaging/brush/) و[Font](/imaging/python-net/aspose.imaging/font/) المحددين مع خصائص التنسيق الخاصة بـ [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) المحدد. |
| [draw_string(s, font, brush, point)](#draw_string_s_font_brush_point_136) | يرسم سلسلة النص المحددة في الموقع المحدد باستخدام [Brush](/imaging/python-net/aspose.imaging/brush/) و[Font](/imaging/python-net/aspose.imaging/font/) المحددين. |
| [draw_string(s, font, brush, point, format)](#draw_string_s_font_brush_point_format_137) | يرسم سلسلة النص المحددة في الموقع المحدد باستخدام [Brush](/imaging/python-net/aspose.imaging/brush/) و[Font](/imaging/python-net/aspose.imaging/font/) المحددين مع خصائص التنسيق الخاصة بـ [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) المحدد. |
| [draw_string(s, font, brush, x, y)](#draw_string_s_font_brush_x_y_138) | يرسم سلسلة النص المحددة في الموقع المحدد باستخدام [Brush](/imaging/python-net/aspose.imaging/brush/) و[Font](/imaging/python-net/aspose.imaging/font/) المحددين. |
| [draw_string(s, font, brush, x, y, format)](#draw_string_s_font_brush_x_y_format_139) | يرسم سلسلة النص المحددة في الموقع المحدد باستخدام [Brush](/imaging/python-net/aspose.imaging/brush/) و[Font](/imaging/python-net/aspose.imaging/font/) المحددين مع خصائص التنسيق الخاصة بـ [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) المحدد. |
| [draw_string_at_point_f(s, font, brush, point)](#draw_string_at_point_f_s_font_brush_point_140) | يرسم سلسلة النص المحددة في الموقع المحدد باستخدام [Brush](/imaging/python-net/aspose.imaging/brush/) و[Font](/imaging/python-net/aspose.imaging/font/) المحددين. |
| [draw_string_at_point_f_format(s, font, brush, point, format)](#draw_string_at_point_f_format_s_font_brush_point_format_141) | يرسم سلسلة النص المحددة في الموقع المحدد باستخدام [Brush](/imaging/python-net/aspose.imaging/brush/) و[Font](/imaging/python-net/aspose.imaging/font/) المحددين مع خصائص التنسيق الخاصة بـ [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) المحدد. |
| [draw_string_at_xy(s, font, brush, x, y)](#draw_string_at_xy_s_font_brush_x_y_142) | يرسم سلسلة النص المحددة في الموقع المحدد باستخدام [Brush](/imaging/python-net/aspose.imaging/brush/) و[Font](/imaging/python-net/aspose.imaging/font/) المحددين. |
| [draw_string_in_rect(s, font, brush, layout_rectangle)](#draw_string_in_rect_s_font_brush_layout_rectangle_143) | يرسم سلسلة النص المحددة في المستطيل المحدد باستخدام [Brush](/imaging/python-net/aspose.imaging/brush/) و[Font](/imaging/python-net/aspose.imaging/font/) المحددين. |
| [draw_string_in_rect_f(s, font, brush, layout_rectangle, format)](#draw_string_in_rect_f_s_font_brush_layout_rectangle_format_144) | يرسم سلسلة النص المحددة في المستطيل المحدد باستخدام [Brush](/imaging/python-net/aspose.imaging/brush/) و[Font](/imaging/python-net/aspose.imaging/font/) المحددين مع خصائص التنسيق الخاصة بـ [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) المحدد. |
| end_update() | ينهي تخزين عمليات الرسوميات في الذاكرة التي بدأت بعد استدعاء BeginUpdate. سيتم تطبيق عمليات الرسوميات السابقة دفعة واحدة عند استدعاء هذه الطريقة. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_145) | يملأ داخل منحنى السبلين المغلق المحدد بواسطة مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) . يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5 ووضع تعبئة [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) . |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_146) | يملأ داخل منحنى السبلين المغلق المحدد بواسطة مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) . يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5 ووضع تعبئة [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) . |
| [fill_closed_curve(brush, points, fill_mode)](#fill_closed_curve_brush_points_fill_mode_147) | يملأ داخل منحنى السبلين المغلق المحدد بواسطة مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام وضع التعبئة المحدد. يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_148) | يملأ داخل منحنى السبلين المغلق المحدد بواسطة مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام وضع التعبئة المحدد. يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_149) | يملأ داخل منحنى السبلين المغلق المحدد بواسطة مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام وضع التعبئة والتوتر المحددين. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_150) | يملأ داخل منحنى السبلين المغلق المحدد بواسطة مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام وضع التعبئة والتوتر المحددين. |
| [fill_closed_curve_by_point(brush, points)](#fill_closed_curve_by_point_brush_points_151) | يملأ داخل منحنى السبلين المغلق المحدد بواسطة مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) . يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5 ووضع تعبئة [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) . |
| [fill_closed_curve_by_point_f(brush, points)](#fill_closed_curve_by_point_f_brush_points_152) | يملأ داخل منحنى السبلين المغلق المحدد بواسطة مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) . يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5 ووضع تعبئة [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) . |
| fill_closed_curve_by_point_f_fill_mode(brush, points, fillmode) |  |
| [fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension)](#fill_closed_curve_by_point_f_fill_mode_tension_brush_points_fillmode_tension_153) | يملأ داخل منحنى السبلين المغلق المحدد بواسطة مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام وضع التعبئة والتوتر المحددين. |
| [fill_closed_curve_by_point_fill_mode(brush, points, fillmode)](#fill_closed_curve_by_point_fill_mode_brush_points_fillmode_154) | يملأ داخل منحنى السبلين المغلق المحدد بواسطة مصفوفة من هياكل [Point](/imaging/python-net/aspose.imaging/point/) باستخدام وضع التعبئة المحدد. يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5. |
| [fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension)](#fill_closed_curve_by_point_fill_mode_tension_brush_points_fillmode_tension_155) | يملأ داخل منحنى السبلين المغلق المحدد بواسطة مصفوفة من هياكل [Point](/imaging/python-net/aspose.imaging/point/) باستخدام وضع التعبئة والتوتر المحددين. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_156) | يملأ داخل إهليلج محدد بواسطة مستطيل حد يحدده هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) . |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_157) | يملأ داخل إهليلج محدد بواسطة مستطيل حد يحدده هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) . |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_158) | يملأ داخل إهليلج محدد بواسطة مستطيل حد يحدده زوج من الإحداثيات، عرض، وارتفاع. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_159) | يملأ داخل إهليلج محدد بواسطة مستطيل حد يحدده زوج من الإحداثيات، عرض، وارتفاع. |
| [fill_ellipse_at_xywh(brush, x, y, width, height)](#fill_ellipse_at_xywh_brush_x_y_width_height_160) | يملأ داخل إهليلج محدد بواسطة مستطيل حد يحدده زوج من الإحداثيات، عرض، وارتفاع. |
| [fill_ellipse_at_xywhf(brush, x, y, width, height)](#fill_ellipse_at_xywhf_brush_x_y_width_height_161) | يملأ داخل إهليلج محدد بواسطة مستطيل حد يحدده زوج من الإحداثيات، عرض، وارتفاع. |
| [fill_ellipse_in_rect(brush, rect)](#fill_ellipse_in_rect_brush_rect_162) | يملأ داخل إهليلج محدد بواسطة مستطيل حد يحدده هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) . |
| [fill_ellipse_in_rect_f(brush, rect)](#fill_ellipse_in_rect_f_brush_rect_163) | يملأ داخل إهليلج محدد بواسطة مستطيل حد يحدده هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) . |
| [fill_path(brush, path)](#fill_path_brush_path_164) | يملأ داخل [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_165) | يملأ داخل قطاع فطيرة محدد بواسطة إهليلج يحدده هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) وخطين شعاعيين. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_166) | يملأ داخل قطاع فطيرة محدد بواسطة إهليلج يحدده هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) وخطين شعاعيين. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_167) | يملأ داخل قطاع فطيرة محدد بواسطة إهليلج يحدده زوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_168) | يملأ داخل قطاع فطيرة محدد بواسطة إهليلج يحدده زوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين. |
| [fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_at_xy_brush_x_y_width_height_start_angle_sweep_angle_169) | يملأ داخل قطاع فطيرة محدد بواسطة إهليلج يحدده زوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين. |
| [fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_at_xyf_brush_x_y_width_height_start_angle_sweep_angle_170) | يملأ داخل قطاع فطيرة محدد بواسطة إهليلج يحدده زوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين. |
| [fill_pie_in_rect(brush, rect, start_angle, sweep_angle)](#fill_pie_in_rect_brush_rect_start_angle_sweep_angle_171) | يملأ داخل قطاع فطيرة محدد بواسطة إهليلج يحدده هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) وخطين شعاعيين. |
| [fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle)](#fill_pie_in_rect_f_brush_rect_start_angle_sweep_angle_172) | يملأ داخل قطاع فطيرة محدد بواسطة إهليلج يحدده هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) وخطين شعاعيين. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_173) | يملأ داخل مضلع محدد بواسطة مصفوفة من النقاط المحددة بهياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) و[FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) . |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_174) | يملأ داخل مضلع محدد بواسطة مصفوفة من النقاط المحددة بهياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) و[FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) . |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_175) | يملأ داخل مضلع محدد بواسطة مصفوفة من النقاط المحددة بهياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام وضع التعبئة المحدد. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_176) | يملأ داخل مضلع محدد بواسطة مصفوفة من النقاط المحددة بهياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام وضع التعبئة المحدد. |
| [fill_polygon_by_point(brush, points)](#fill_polygon_by_point_brush_points_177) | يملأ داخل مضلع محدد بواسطة مصفوفة من النقاط المحددة بهياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) و[FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) . |
| [fill_polygon_by_point_f(brush, points)](#fill_polygon_by_point_f_brush_points_178) | يملأ داخل مضلع محدد بواسطة مصفوفة من النقاط المحددة بهياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) و[FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) . |
| [fill_polygon_by_point_f_fill_mode(brush, points, fill_mode)](#fill_polygon_by_point_f_fill_mode_brush_points_fill_mode_179) | يملأ داخل مضلع محدد بواسطة مصفوفة من النقاط المحددة بهياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام وضع التعبئة المحدد. |
| [fill_polygon_by_point_fill_mode(brush, points, fill_mode)](#fill_polygon_by_point_fill_mode_brush_points_fill_mode_180) | يملأ داخل مضلع محدد بواسطة مصفوفة من النقاط المحددة بهياكل [Point](/imaging/python-net/aspose.imaging/point/) باستخدام وضع التعبئة المحدد. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_181) | يملأ داخل مستطيل محدد بواسطة هيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) . |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_182) | يملأ داخل مستطيل محدد بواسطة هيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) . |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_183) | يملأ داخل مستطيل محدد بواسطة زوج من الإحداثيات، عرض وارتفاع. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_184) | يملأ داخل مستطيل محدد بواسطة زوج من الإحداثيات، عرض وارتفاع. |
| [fill_rectangle_f(brush, rect)](#fill_rectangle_f_brush_rect_185) | يملأ داخل مستطيل محدد بواسطة هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) . |
| [fill_rectangle_f_with_brush(brush, x, y, width, height)](#fill_rectangle_f_with_brush_brush_x_y_width_height_186) | يملأ داخل مستطيل محدد بواسطة زوج من الإحداثيات، عرض وارتفاع. |
| [fill_rectangle_with_brush(brush, x, y, width, height)](#fill_rectangle_with_brush_brush_x_y_width_height_187) | يملأ داخل مستطيل محدد بواسطة زوج من الإحداثيات، عرض وارتفاع. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_188) | يملأ داخل مجموعة من المستطيلات المحددة بهياكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) . |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_189) | يملأ داخل مجموعة من المستطيلات المحددة بهياكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) . |
| [fill_rectangles_f(brush, rects)](#fill_rectangles_f_brush_rects_190) | يملأ داخل مجموعة من المستطيلات المحددة بهياكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) . |
| [fill_region(brush, region)](#fill_region_brush_region_191) | يملأ داخل [Region](/imaging/python-net/aspose.imaging/region/). |
| [measure_string(text, font, layout_area, string_format)](#measure_string_text_font_layout_area_string_format_192) | يقيس سلسلة النص المحددة باستخدام المعلمات المحددة |
| [multiply_transform(matrix)](#multiply_transform_matrix_193) | يضرب [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [Graphics](/imaging/python-net/aspose.imaging/graphics/) بالمصفوفة [Matrix](/imaging/python-net/aspose.imaging/matrix/) المحددة عن طريق إلحاق المصفوفة [Matrix](/imaging/python-net/aspose.imaging/matrix/) المحددة في البداية. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_194) | يضرب [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [Graphics](/imaging/python-net/aspose.imaging/graphics/) بالمصفوفة [Matrix](/imaging/python-net/aspose.imaging/matrix/) المحددة بالترتيب المحدد. |
| reset_transform() | يعيد تعيين خاصية [Graphics.transform](/imaging/python-net/aspose.imaging/graphics/) إلى الهوية. |
| [rotate_transform(angle)](#rotate_transform_angle_195) | يدور التحويل الهندسي المحلي بالمقدار المحدد. هذه الطريقة تسبق الدوران إلى التحويل. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_196) | يدور التحويل الهندسي المحلي بالمقدار المحدد وفقًا للترتيب المحدد. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_197) | يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة. هذه الطريقة تسبق مصفوفة التكبير إلى التحويل. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_198) | يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة وفقًا للترتيب المحدد. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_199) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة. هذه الطريقة تسبق الترجمة إلى التحويل. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_200) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة وفقًا للترتيب المحدد. |


### Constructor: Graphics(source_image) {#Graphics_source_image_1}


```
 Graphics(source_image) 
```

يُنشئ مثلاً جديدًا من الفئة [Graphics](/imaging/python-net/aspose.imaging/graphics/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | صورة المصدر. |

### Method: clear(color) {#clear_color_1}


```
 clear(color) 
```

يمسح سطح الرسومات باستخدام اللون المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | اللون المستخدم لمسح سطح الرسومات. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...

**[Example # 2](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_2}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة بنية [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للقوس. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الذي يحدد حدود القطع الناقص. |
| start_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى نقطة بدء القوس. |
| sweep_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل _startAngle_ إلى نقطة نهاية القوس. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_3}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة بنية [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للقوس. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الذي يحدد حدود القطع الناقص. |
| start_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى نقطة بدء القوس. |
| sweep_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل _startAngle_ إلى نقطة نهاية القوس. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للقوس. |
| x | float | الإحداثي x للزاوية العلوية اليسرى للمستطيل الذي يحدد القطع الناقص. |
| y | float | الإحداثي y للزاوية العلوية اليسرى للمستطيل الذي يحدد القطع الناقص. |
| width | float | عرض المستطيل الذي يحدد القطع الناقص. |
| height | float | ارتفاع المستطيل الذي يحدد القطع الناقص. |
| start_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى نقطة بدء القوس. |
| sweep_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل _startAngle_ إلى نقطة نهاية القوس. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للقوس. |
| x | int | الإحداثي x للزاوية العلوية اليسرى للمستطيل الذي يحدد القطع الناقص. |
| y | int | الإحداثي y للزاوية العلوية اليسرى للمستطيل الذي يحدد القطع الناقص. |
| width | int | عرض المستطيل الذي يحدد القطع الناقص. |
| height | int | ارتفاع المستطيل الذي يحدد القطع الناقص. |
| start_angle | int | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى نقطة بدء القوس. |
| sweep_angle | int | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل _startAngle_ إلى نقطة نهاية القوس. |

### Method: draw_arc_in_rect(pen, rect, start_angle, sweep_angle) {#draw_arc_in_rect_pen_rect_start_angle_sweep_angle_6}


```
 draw_arc_in_rect(pen, rect, start_angle, sweep_angle) 
```

يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة بنية [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للقوس. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الذي يحدد حدود القطع الناقص. |
| start_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى نقطة بدء القوس. |
| sweep_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل _startAngle_ إلى نقطة نهاية القوس. |

### Method: draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle) {#draw_arc_in_rect_f_pen_rect_start_angle_sweep_angle_7}


```
 draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle) 
```

يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة بنية [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للقوس. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الذي يحدد حدود القطع الناقص. |
| start_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى نقطة بدء القوس. |
| sweep_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل _startAngle_ إلى نقطة نهاية القوس. |

### Method: draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_xy_pen_x_y_width_height_start_angle_sweep_angle_8}


```
 draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle) 
```

يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للقوس. |
| x | int | الإحداثي x للزاوية العلوية اليسرى للمستطيل الذي يحدد القطع الناقص. |
| y | int | الإحداثي y للزاوية العلوية اليسرى للمستطيل الذي يحدد القطع الناقص. |
| width | int | عرض المستطيل الذي يحدد القطع الناقص. |
| height | int | ارتفاع المستطيل الذي يحدد القطع الناقص. |
| start_angle | int | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى نقطة بدء القوس. |
| sweep_angle | int | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل _startAngle_ إلى نقطة نهاية القوس. |

### Method: draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_xyf_pen_x_y_width_height_start_angle_sweep_angle_9}


```
 draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle) 
```

يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للقوس. |
| x | float | الإحداثي x للزاوية العلوية اليسرى للمستطيل الذي يحدد القطع الناقص. |
| y | float | الإحداثي y للزاوية العلوية اليسرى للمستطيل الذي يحدد القطع الناقص. |
| width | float | عرض المستطيل الذي يحدد القطع الناقص. |
| height | float | ارتفاع المستطيل الذي يحدد القطع الناقص. |
| start_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى نقطة بدء القوس. |
| sweep_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل _startAngle_ إلى نقطة نهاية القوس. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_10}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

يرسم منحنى بيزيير محدد بأربع بنى [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للمنحنى. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) الذي يمثل نقطة بدء المنحنى. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) الذي يمثل نقطة التحكم الأولى للمنحنى. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) الذي يمثل نقطة التحكم الثانية للمنحنى. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) الذي يمثل نقطة النهاية للمنحنى. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_11}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

يرسم منحنى بيزيير محدد بأربع بنى [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للمنحنى. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) الذي يمثل نقطة بدء المنحنى. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) الذي يمثل نقطة التحكم الأولى للمنحنى. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) الذي يمثل نقطة التحكم الثانية للمنحنى. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) الذي يمثل نقطة النهاية للمنحنى. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) {#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_12}


```
 draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) 
```

يرسم منحنى بيزيير محدد بأربع أزواج مرتبة من الإحداثيات تمثل نقاطًا.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للمنحنى. |
| x1 | float | الإحداثي x لنقطة بدء المنحنى. |
| y1 | float | الإحداثي y لنقطة بدء المنحنى. |
| x2 | float | الإحداثي x لنقطة التحكم الأولى للمنحنى. |
| y2 | float | الإحداثي ص لنقطة التحكم الأولى للمنحنى. |
| x3 | float | الإحداثي س لنقطة التحكم الثانية للمنحنى. |
| y3 | float | الإحداثي ص لنقطة التحكم الثانية للمنحنى. |
| x4 | float | الإحداثي س لنقطة النهاية للمنحنى. |
| y4 | float | الإحداثي ص لنقطة النهاية للمنحنى. |

### Method: draw_bezier_by_points(pen, pt1, pt2, pt3, pt4) {#draw_bezier_by_points_pen_pt1_pt2_pt3_pt4_13}


```
 draw_bezier_by_points(pen, pt1, pt2, pt3, pt4) 
```

يرسم منحنى بيزيير محدد بأربع بنى [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للمنحنى. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) الذي يمثل نقطة بدء المنحنى. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) الذي يمثل نقطة التحكم الأولى للمنحنى. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) الذي يمثل نقطة التحكم الثانية للمنحنى. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) الذي يمثل نقطة النهاية للمنحنى. |

### Method: draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4) {#draw_bezier_by_points_f_pen_pt1_pt2_pt3_pt4_14}


```
 draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4) 
```

يرسم منحنى بيزيير محدد بأربع بنى [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للمنحنى. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) الذي يمثل نقطة بدء المنحنى. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) الذي يمثل نقطة التحكم الأولى للمنحنى. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) الذي يمثل نقطة التحكم الثانية للمنحنى. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) الذي يمثل نقطة النهاية للمنحنى. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_15}


```
 draw_beziers(pen, points) 
```

يرسم سلسلة من منحنيات بيزيير من مصفوفة من بنى [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للمنحنى. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [Point](/imaging/python-net/aspose.imaging/point/) التي تمثل النقاط التي تحدد المنحنى. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_16}


```
 draw_beziers(pen, points) 
```

يرسم سلسلة من منحنيات بيزيير من مصفوفة من بنى [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للمنحنى. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [Point](/imaging/python-net/aspose.imaging/point/) التي تمثل النقاط التي تحدد المنحنى. |

### Method: draw_beziers_by_pt_array(pen, points) {#draw_beziers_by_pt_array_pen_points_17}


```
 draw_beziers_by_pt_array(pen, points) 
```

يرسم سلسلة من منحنيات بيزيير من مصفوفة من بنى [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للمنحنى. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [Point](/imaging/python-net/aspose.imaging/point/) التي تمثل النقاط التي تحدد المنحنى. |

### Method: draw_beziers_by_pt_array_f(pen, points) {#draw_beziers_by_pt_array_f_pen_points_18}


```
 draw_beziers_by_pt_array_f(pen, points) 
```

يرسم سلسلة من منحنيات بيزيير من مصفوفة من بنى [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للمنحنى. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تمثل النقاط التي تحدد المنحنى. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_19}


```
 draw_closed_curve(pen, points) 
```

يرسم منحنى كاردينال مغلق محدد بمصفوفة من بنى [PointF](/imaging/python-net/aspose.imaging/pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 ووضع تعبئة [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تعرف المنحنى المتعدد القطع. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_20}


```
 draw_closed_curve(pen, points) 
```

يرسم منحنى كاردينال مغلق محدد بمصفوفة من بنى [PointF](/imaging/python-net/aspose.imaging/pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 ووضع تعبئة [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تعرف المنحنى المتعدد القطع. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_21}


```
 draw_closed_curve(pen, points, tension) 
```

يرسم منحنى كاردينال مغلق محدد بمصفوفة من بنى [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام توتر محدد. تستخدم هذه الطريقة وضع تعبئة افتراضي [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تعرف المنحنى المتعدد القطع. |
| التوتر | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_22}


```
 draw_closed_curve(pen, points, tension) 
```

يرسم منحنى كاردينال مغلق محدد بمصفوفة من بنى [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام توتر محدد. تستخدم هذه الطريقة وضع تعبئة افتراضي [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تعرف المنحنى المتعدد القطع. |
| التوتر | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### Method: draw_closed_curve_by_points(pen, points) {#draw_closed_curve_by_points_pen_points_23}


```
 draw_closed_curve_by_points(pen, points) 
```

يرسم منحنى كاردينال مغلق محدد بمصفوفة من بنى [PointF](/imaging/python-net/aspose.imaging/pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 ووضع تعبئة [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تعرف المنحنى المتعدد القطع. |

### Method: draw_closed_curve_by_points_f(pen, points) {#draw_closed_curve_by_points_f_pen_points_24}


```
 draw_closed_curve_by_points_f(pen, points) 
```

يرسم منحنى كاردينال مغلق محدد بمصفوفة من بنى [PointF](/imaging/python-net/aspose.imaging/pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 ووضع تعبئة [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تعرف المنحنى المتعدد القطع. |

### Method: draw_closed_curve_by_points_f_tension(pen, points, tension) {#draw_closed_curve_by_points_f_tension_pen_points_tension_25}


```
 draw_closed_curve_by_points_f_tension(pen, points, tension) 
```

يرسم منحنى كاردينال مغلق محدد بمصفوفة من بنى [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام توتر محدد. تستخدم هذه الطريقة وضع تعبئة افتراضي [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تعرف المنحنى المتعدد القطع. |
| التوتر | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### Method: draw_closed_curve_by_points_tension(pen, points, tension) {#draw_closed_curve_by_points_tension_pen_points_tension_26}


```
 draw_closed_curve_by_points_tension(pen, points, tension) 
```

يرسم منحنى كاردينال مغلق محدد بمصفوفة من بنى [Point](/imaging/python-net/aspose.imaging/point/) باستخدام توتر محدد. تستخدم هذه الطريقة وضع تعبئة افتراضي [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [Point](/imaging/python-net/aspose.imaging/point/) التي تعرف المنحنى المتعدد القطع. |
| التوتر | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_27}


```
 draw_curve(pen, points) 
```

يرسم منحنى كاردينال عبر مصفوفة محددة من بنى [PointF](/imaging/python-net/aspose.imaging/pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تعرف المنحنى المتعدد القطع. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_curve(pen, points) {#draw_curve_pen_points_28}


```
 draw_curve(pen, points) 
```

يرسم منحنى كاردينال عبر مصفوفة محددة من بنى [PointF](/imaging/python-net/aspose.imaging/pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تعرف المنحنى المتعدد القطع. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_curve(pen, points, offset, number_of_segments) {#draw_curve_pen_points_offset_number_of_segments_29}


```
 draw_curve(pen, points, offset, number_of_segments) 
```

يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/). يبدأ الرسم متأخراً عن بداية المصفوفة.<br/>            تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تعرف المنحنى المتعدد القطع. |
| offset | int | الإزاحة من العنصر الأول في مصفوفة معلمة _points_ إلى نقطة البدء في المنحنى. |
| number_of_segments | int | عدد القطاعات بعد نقطة البدء لتضمينها في المنحنى. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_30}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام توتر محدد. يبدأ الرسم متأخراً عن بداية المصفوفة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تعرف المنحنى المتعدد القطع. |
| offset | int | الإزاحة من العنصر الأول في مصفوفة معلمة _points_ إلى نقطة البدء في المنحنى. |
| number_of_segments | int | عدد القطاعات بعد نقطة البدء لتضمينها في المنحنى. |
| التوتر | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_31}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام توتر محدد. يبدأ الرسم متأخراً عن بداية المصفوفة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تعرف المنحنى المتعدد القطع. |
| offset | int | الإزاحة من العنصر الأول في مصفوفة معلمة _points_ إلى نقطة البدء في المنحنى. |
| number_of_segments | int | عدد القطاعات بعد نقطة البدء لتضمينها في المنحنى. |
| التوتر | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_32}


```
 draw_curve(pen, points, tension) 
```

يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام توتر محدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تمثل النقاط التي تعرف المنحنى. |
| التوتر | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_33}


```
 draw_curve(pen, points, tension) 
```

يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام توتر محدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تمثل النقاط التي تعرف المنحنى. |
| التوتر | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### Method: draw_curve_by_point_fs(pen, points) {#draw_curve_by_point_fs_pen_points_34}


```
 draw_curve_by_point_fs(pen, points) 
```

يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [Point](/imaging/python-net/aspose.imaging/point/) التي تعرف المنحنى المتعدد القطع. |

### Method: draw_curve_by_point_fs_tension(pen, points, tension) {#draw_curve_by_point_fs_tension_pen_points_tension_35}


```
 draw_curve_by_point_fs_tension(pen, points, tension) 
```

يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام توتر محدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تمثل النقاط التي تعرف المنحنى. |
| التوتر | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### Method: draw_curve_by_points(pen, points) {#draw_curve_by_points_pen_points_36}


```
 draw_curve_by_points(pen, points) 
```

يرسم منحنى كاردينال عبر مصفوفة محددة من بنى [PointF](/imaging/python-net/aspose.imaging/pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تعرف المنحنى المتعدد القطع. |

### Method: draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) {#draw_curve_by_points_f_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_37}


```
 draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) 
```

يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام توتر محدد. يبدأ الرسم متأخراً عن بداية المصفوفة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تعرف المنحنى المتعدد القطع. |
| offset | int | الإزاحة من العنصر الأول في مصفوفة معلمة _points_ إلى نقطة البدء في المنحنى. |
| number_of_segments | int | عدد القطاعات بعد نقطة البدء لتضمينها في المنحنى. |
| التوتر | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### Method: draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) {#draw_curve_by_points_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_38}


```
 draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) 
```

يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [Point](/imaging/python-net/aspose.imaging/point/) باستخدام توتر محدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [Point](/imaging/python-net/aspose.imaging/point/) التي تعرف المنحنى المتعدد القطع. |
| offset | int | الإزاحة من العنصر الأول في مصفوفة معلمة _points_ إلى نقطة البدء في المنحنى. |
| number_of_segments | int | عدد القطاعات بعد نقطة البدء لتضمينها في المنحنى. |
| التوتر | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### Method: draw_curve_by_points_tension(pen, points, tension) {#draw_curve_by_points_tension_pen_points_tension_39}


```
 draw_curve_by_points_tension(pen, points, tension) 
```

يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [Point](/imaging/python-net/aspose.imaging/point/) باستخدام توتر محدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [Point](/imaging/python-net/aspose.imaging/point/) التي تعرف المنحنى المتعدد القطع. |
| التوتر | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_40}


```
 draw_ellipse(pen, rect) 
```

يرسم قطعًا ناقصًا يُحدَّد بواسطة [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) محيط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والنمط للقطع الناقص. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الذي يحدد حدود القطع الناقص. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_41}


```
 draw_ellipse(pen, rect) 
```

يرسم قطعًا ناقصًا يُحدَّد بواسطة [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) محيط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والنمط للقطع الناقص. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الذي يحدد حدود القطع الناقص. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_42}


```
 draw_ellipse(pen, x, y, width, height) 
```

يرسم قطعًا ناقصًا يُحدَّد بواسطة مستطيل محيط يُحدد بواسطة زوج من الإحداثيات، ارتفاع، وعرض.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والنمط للقطع الناقص. |
| x | float | الإحداثي س للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص. |
| y | float | الإحداثي ص للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص. |
| width | float | عرض المستطيل المحيط الذي يحدد القطع الناقص. |
| height | float | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_43}


```
 draw_ellipse(pen, x, y, width, height) 
```

يرسم قطعًا ناقصًا يُحدَّد بواسطة مستطيل محيط يُحدد بواسطة زوج من الإحداثيات، ارتفاع، وعرض.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والنمط للقطع الناقص. |
| x | int | الإحداثي س للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص. |
| y | int | الإحداثي ص للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص. |
| width | int | عرض المستطيل المحيط الذي يحدد القطع الناقص. |
| height | int | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص. |

### Method: draw_ellipse_by_xy(pen, x, y, width, height) {#draw_ellipse_by_xy_pen_x_y_width_height_44}


```
 draw_ellipse_by_xy(pen, x, y, width, height) 
```

يرسم قطعًا ناقصًا يُحدَّد بواسطة مستطيل محيط يُحدد بواسطة زوج من الإحداثيات، ارتفاع، وعرض.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والنمط للقطع الناقص. |
| x | int | الإحداثي س للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص. |
| y | int | الإحداثي ص للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص. |
| width | int | عرض المستطيل المحيط الذي يحدد القطع الناقص. |
| height | int | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص. |

### Method: draw_ellipse_by_xyf(pen, x, y, width, height) {#draw_ellipse_by_xyf_pen_x_y_width_height_45}


```
 draw_ellipse_by_xyf(pen, x, y, width, height) 
```

يرسم قطعًا ناقصًا يُحدَّد بواسطة مستطيل محيط يُحدد بواسطة زوج من الإحداثيات، ارتفاع، وعرض.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والنمط للقطع الناقص. |
| x | float | الإحداثي س للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص. |
| y | float | الإحداثي ص للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص. |
| width | float | عرض المستطيل المحيط الذي يحدد القطع الناقص. |
| height | float | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص. |

### Method: draw_ellipse_f(pen, rect) {#draw_ellipse_f_pen_rect_46}


```
 draw_ellipse_f(pen, rect) 
```

يرسم قطعًا ناقصًا يُحدَّد بواسطة [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) محيط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) التي تحدد اللون والعرض والنمط للقطع الناقص. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الذي يحدد حدود القطع الناقص. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_47}


```
 draw_image(image, dest_points) 
```

يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة المراد رسمها. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من ثلاث هياكل PointF تُعرّف متوازي أضلاع. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_48}


```
 draw_image(image, dest_points) 
```

يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة المراد رسمها. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من ثلاث هياكل PointF تُعرّف متوازي أضلاع. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_49}


```
 draw_image(image, dest_points, src_rect) 
```

يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة المراد رسمها. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من ثلاث هياكل PointF تُعرّف متوازي أضلاع. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل المصدر. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_50}


```
 draw_image(image, dest_points, src_rect) 
```

يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة المراد رسمها. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من ثلاث هياكل PointF تُعرّف متوازي أضلاع. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | المستطيل المصدر. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_51}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة المراد رسمها. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من ثلاث هياكل PointF تُعرّف متوازي أضلاع. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل المصدر. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدات القياس. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_52}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة المراد رسمها. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من ثلاث هياكل PointF تُعرّف متوازي أضلاع. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | المستطيل المصدر. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدات القياس. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_53}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة المراد رسمها. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من ثلاث هياكل PointF تُعرّف متوازي أضلاع. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل المصدر. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدات القياس. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | خصائص الصورة. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_54}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة المراد رسمها. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من ثلاث هياكل PointF تُعرّف متوازي أضلاع. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | المستطيل المصدر. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدات القياس. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | خصائص الصورة. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_55}


```
 draw_image(source_image, point) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) الذي يمثل الزاوية العلوية اليسرى للصورة المرسومة. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_56}


```
 draw_image(source_image, point) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) الذي يمثل الزاوية العلوية اليسرى للصورة المرسومة. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_57}


```
 draw_image(source_image, rect) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الذي يحدد موقع وحجم الصورة المرسومة. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_58}


```
 draw_image(source_image, rect) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الذي يحدد موقع وحجم الصورة المرسومة. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_59}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل الوجهة. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدة الرسومات. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_60}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | المستطيل الوجهة. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدة الرسومات. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_61}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل الوجهة. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدة الرسومات. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | خصائص الصورة. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_62}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | المستطيل الوجهة. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدة الرسومات. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | خصائص الصورة. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_63}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | مصدر المستطيل. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | وجهة المستطيل. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدة الرسومات. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_64}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | مصدر المستطيل. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | وجهة المستطيل. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدة الرسومات. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_65}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | مصدر المستطيل. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | وجهة المستطيل. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدة الرسومات. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | خصائص الصورة. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_66}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | مصدر المستطيل. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | وجهة المستطيل. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدة الرسومات. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | خصائص الصورة. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_67}


```
 draw_image(source_image, x, y) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| x | float | الإحداثي X للزاوية العلوية اليسرى للصورة المرسومة. |
| y | float | الإحداثي Y للزاوية العلوية اليسرى للصورة المرسومة. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_68}


```
 draw_image(source_image, x, y) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| x | int | الإحداثي X للزاوية العلوية اليسرى للصورة المرسومة. |
| y | int | الإحداثي Y للزاوية العلوية اليسرى للصورة المرسومة. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_69}


```
 draw_image(source_image, x, y, width, height) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| x | float | الإحداثي X للزاوية العلوية اليسرى للصورة المرسومة. |
| y | float | الإحداثي Y للزاوية العلوية اليسرى للصورة المرسومة. |
| width | float | عرض الصورة المرسومة. |
| height | float | ارتفاع الصورة المرسومة. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_70}


```
 draw_image(source_image, x, y, width, height) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| x | int | الإحداثي X للزاوية العلوية اليسرى للصورة المرسومة. |
| y | int | الإحداثي Y للزاوية العلوية اليسرى للصورة المرسومة. |
| width | int | عرض الصورة المرسومة. |
| height | int | ارتفاع الصورة المرسومة. |

### Method: draw_image_at_point(source_image, point) {#draw_image_at_point_source_image_point_71}


```
 draw_image_at_point(source_image, point) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) الذي يمثل الزاوية العلوية اليسرى للصورة المرسومة. |

### Method: draw_image_at_point_f(source_image, point) {#draw_image_at_point_f_source_image_point_72}


```
 draw_image_at_point_f(source_image, point) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) الذي يمثل الزاوية العلوية اليسرى للصورة المرسومة. |

### Method: draw_image_at_xy(source_image, x, y) {#draw_image_at_xy_source_image_x_y_73}


```
 draw_image_at_xy(source_image, x, y) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| x | int | الإحداثي X للزاوية العلوية اليسرى للصورة المرسومة. |
| y | int | الإحداثي Y للزاوية العلوية اليسرى للصورة المرسومة. |

### Method: draw_image_at_xyf(source_image, x, y) {#draw_image_at_xyf_source_image_x_y_74}


```
 draw_image_at_xyf(source_image, x, y) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| x | float | الإحداثي X للزاوية العلوية اليسرى للصورة المرسومة. |
| y | float | الإحداثي Y للزاوية العلوية اليسرى للصورة المرسومة. |

### Method: draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit) {#draw_image_dest_point_f_src_rect_f_with_unit_image_dest_points_src_rect_src_unit_75}


```
 draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit) 
```

يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة المراد رسمها. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من ثلاث هياكل PointF تُعرّف متوازي أضلاع. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | المستطيل المصدر. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدات القياس. |

### Method: draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_dest_point_f_src_rect_f_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_76}


```
 draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) 
```

يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة المراد رسمها. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من ثلاث هياكل PointF تُعرّف متوازي أضلاع. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | المستطيل المصدر. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدات القياس. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | خصائص الصورة. |

### Method: draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect) {#draw_image_dest_points_f_src_rect_f_image_dest_points_src_rect_77}


```
 draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect) 
```

يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة المراد رسمها. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من ثلاث هياكل PointF تُعرّف متوازي أضلاع. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | المستطيل المصدر. |

### Method: draw_image_dest_points_src_rect(image, dest_points, src_rect) {#draw_image_dest_points_src_rect_image_dest_points_src_rect_78}


```
 draw_image_dest_points_src_rect(image, dest_points, src_rect) 
```

يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة المراد رسمها. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من ثلاث هياكل PointF تُعرّف متوازي أضلاع. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل المصدر. |

### Method: draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit) {#draw_image_dest_points_src_rect_with_unit_image_dest_points_src_rect_src_unit_79}


```
 draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit) 
```

يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة المراد رسمها. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من ثلاث هياكل PointF تُعرّف متوازي أضلاع. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل المصدر. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدات القياس. |

### Method: draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_dest_points_src_rect_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_80}


```
 draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) 
```

يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة المراد رسمها. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من ثلاث هياكل PointF تُعرّف متوازي أضلاع. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل المصدر. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدات القياس. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | خصائص الصورة. |

### Method: draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_dest_rect_f_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_81}


```
 draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | المستطيل الوجهة للرسم فيه. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدة الرسومات. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | خصائص الصورة. |

### Method: draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_dest_rect_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_82}


```
 draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل الوجهة. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدة الرسومات. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | خصائص الصورة. |

### Method: draw_image_in_rect(source_image, x, y, width, height) {#draw_image_in_rect_source_image_x_y_width_height_83}


```
 draw_image_in_rect(source_image, x, y, width, height) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| x | int | الإحداثي X للزاوية العلوية اليسرى للصورة المرسومة. |
| y | int | الإحداثي Y للزاوية العلوية اليسرى للصورة المرسومة. |
| width | int | عرض الصورة المرسومة. |
| height | int | ارتفاع الصورة المرسومة. |

### Method: draw_image_in_rect_f(source_image, x, y, width, height) {#draw_image_in_rect_f_source_image_x_y_width_height_84}


```
 draw_image_in_rect_f(source_image, x, y, width, height) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| x | float | الإحداثي X للزاوية العلوية اليسرى للصورة المرسومة. |
| y | float | الإحداثي Y للزاوية العلوية اليسرى للصورة المرسومة. |
| width | float | عرض الصورة المرسومة. |
| height | float | ارتفاع الصورة المرسومة. |

### Method: draw_image_in_rectangle(source_image, rect) {#draw_image_in_rectangle_source_image_rect_85}


```
 draw_image_in_rectangle(source_image, rect) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) الذي يحدد موقع وحجم الصورة المرسومة. |

### Method: draw_image_points(image, dest_points) {#draw_image_points_image_dest_points_86}


```
 draw_image_points(image, dest_points) 
```

يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة المراد رسمها. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من ثلاث هياكل PointF تُعرّف متوازي أضلاع. |

### Method: draw_image_points_f(image, dest_points) {#draw_image_points_f_image_dest_points_87}


```
 draw_image_points_f(image, dest_points) 
```

يرسم الجزء المحدد من _image_ المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة المراد رسمها. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من ثلاث هياكل PointF تُعرّف متوازي أضلاع. |

### Method: draw_image_rectangle_f(source_image, rect) {#draw_image_rectangle_f_source_image_rect_88}


```
 draw_image_rectangle_f(source_image, rect) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الذي يحدد موقع وحجم الصورة المرسومة. |

### Method: draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_src_dest_rects_f_with_unit_source_image_rect_source_rect_destination_graphics_unit_89}


```
 draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | مصدر المستطيل. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | وجهة المستطيل. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدة الرسومات. |

### Method: draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_src_dest_rects_with_unit_source_image_rect_source_rect_destination_graphics_unit_90}


```
 draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | مصدر المستطيل. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | وجهة المستطيل. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدة الرسومات. |

### Method: draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_src_dst_rect_f_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_91}


```
 draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | المستطيل المصدر. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | المستطيل الوجهة. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدة الرسومات المستخدمة. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | خصائص الصورة المستخدمة. |

### Method: draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_src_dst_rects_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_92}


```
 draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | مصدر المستطيل. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | وجهة المستطيل. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدة الرسومات. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | خصائص الصورة. |

### Method: draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit) {#draw_image_to_rect_f_with_unit_source_image_rect_destination_graphics_unit_93}


```
 draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | المستطيل الوجهة. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدة الرسومات. |

### Method: draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit) {#draw_image_to_rect_with_unit_source_image_rect_destination_graphics_unit_94}


```
 draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit) 
```

يرسم [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل الوجهة. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | وحدة الرسومات. |

### Method: draw_image_unscaled(source_image, point) {#draw_image_unscaled_source_image_point_95}


```
 draw_image_unscaled(source_image, point) 
```

يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | هيكل [Point](/imaging/python-net/aspose.imaging/point/) الذي يحدد الزاوية العلوية اليسرى للصورة المرسومة. |

### Method: draw_image_unscaled(source_image, rect) {#draw_image_unscaled_source_image_rect_96}


```
 draw_image_unscaled(source_image, rect) 
```

يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) الذي يحدد الزاوية العلوية اليسرى للصورة المرسومة. خصائص X و Y للمستطيل تحدد الزاوية العلوية اليسرى. خصائص العرض والارتفاع يتم تجاهلها. |

### Method: draw_image_unscaled(source_image, x, y) {#draw_image_unscaled_source_image_x_y_97}


```
 draw_image_unscaled(source_image, x, y) 
```

يرسم الصورة المحددة باستخدام حجمها الفيزيائي الأصلي في الموقع المحدد بواسطة زوج من الإحداثيات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| x | int | الإحداثي X للزاوية العلوية اليسرى للصورة المرسومة. |
| y | int | الإحداثي Y للزاوية العلوية اليسرى للصورة المرسومة. |

### Method: draw_image_unscaled(source_image, x, y, width, height) {#draw_image_unscaled_source_image_x_y_width_height_98}


```
 draw_image_unscaled(source_image, x, y, width, height) 
```

يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| x | int | الإحداثي X للزاوية العلوية اليسرى للصورة المرسومة. |
| y | int | الإحداثي Y للزاوية العلوية اليسرى للصورة المرسومة. |
| width | int | المعامل غير مستخدم. |
| height | int | المعامل غير مستخدم. |

### Method: draw_image_unscaled_and_clipped(source_image, rect) {#draw_image_unscaled_and_clipped_source_image_rect_99}


```
 draw_image_unscaled_and_clipped(source_image, rect) 
```

يرسم الصورة المحددة دون تغيير الحجم ويقصها، إذا لزم الأمر، لتتناسب مع المستطيل المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | الـ[Rectangle](/imaging/python-net/aspose.imaging/rectangle/) الذي يُرسم فيه الصورة. |

### Method: draw_image_unscaled_in_rectangle(source_image, rect) {#draw_image_unscaled_in_rectangle_source_image_rect_100}


```
 draw_image_unscaled_in_rectangle(source_image, rect) 
```

يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) الذي يحدد الزاوية العلوية اليسرى للصورة المرسومة. خصائص X و Y للمستطيل تحدد الزاوية العلوية اليسرى. خصائص العرض والارتفاع يتم تجاهلها. |

### Method: draw_image_unscaled_to_point(source_image, point) {#draw_image_unscaled_to_point_source_image_point_101}


```
 draw_image_unscaled_to_point(source_image, point) 
```

يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | الصورة التي سيتم الرسم بها. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | هيكل [Point](/imaging/python-net/aspose.imaging/point/) الذي يحدد الزاوية العلوية اليسرى للصورة المرسومة. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_102}


```
 draw_line(pen, point1, point2) 
```

يرسم خطًا يربط بين هيكلين [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض ونمط الخط. |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | هيكل [Point](/imaging/python-net/aspose.imaging/point/) الذي يمثل النقطة الأولى للاتصال. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) الهيكل الذي يمثل النقطة الثانية للاتصال. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_103}


```
 draw_line(pen, point1, point2) 
```

يرسم خطًا يربط بين هيكلين [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض ونمط الخط. |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | هيكل [Point](/imaging/python-net/aspose.imaging/point/) الذي يمثل النقطة الأولى للاتصال. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [Point](/imaging/python-net/aspose.imaging/point/) الهيكل الذي يمثل النقطة الثانية للاتصال. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_104}


```
 draw_line(pen, x1, y1, x2, y2) 
```

يرسم خطًا يربط النقطتين المحددتين بواسطة أزواج الإحداثيات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض ونمط الخط. |
| x1 | int | الإحداثي السيني للنقطة الأولى. |
| y1 | int | الإحداثي الصادي للنقطة الأولى. |
| x2 | int | الإحداثي السيني للنقطة الثانية. |
| y2 | int | الإحداثي الصادي للنقطة الثانية. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_105}


```
 draw_line(pen, x1, y1, x2, y2) 
```

يرسم خطًا يربط النقطتين المحددتين بواسطة أزواج الإحداثيات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض ونمط الخط. |
| x1 | float | الإحداثي السيني للنقطة الأولى. |
| y1 | float | الإحداثي الصادي للنقطة الأولى. |
| x2 | float | الإحداثي السيني للنقطة الثانية. |
| y2 | float | الإحداثي الصادي للنقطة الثانية. |

### Method: draw_line_by_xy(pen, x1, y1, x2, y2) {#draw_line_by_xy_pen_x1_y1_x2_y2_106}


```
 draw_line_by_xy(pen, x1, y1, x2, y2) 
```

يرسم خطًا يربط النقطتين المحددتين بواسطة أزواج الإحداثيات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض ونمط الخط. |
| x1 | int | الإحداثي السيني للنقطة الأولى. |
| y1 | int | الإحداثي الصادي للنقطة الأولى. |
| x2 | int | الإحداثي السيني للنقطة الثانية. |
| y2 | int | الإحداثي الصادي للنقطة الثانية. |

### Method: draw_line_f_by_xy(pen, x1, y1, x2, y2) {#draw_line_f_by_xy_pen_x1_y1_x2_y2_107}


```
 draw_line_f_by_xy(pen, x1, y1, x2, y2) 
```

يرسم خطًا يربط النقطتين المحددتين بواسطة أزواج الإحداثيات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض ونمط الخط. |
| x1 | float | الإحداثي السيني للنقطة الأولى. |
| y1 | float | الإحداثي الصادي للنقطة الأولى. |
| x2 | float | الإحداثي السيني للنقطة الثانية. |
| y2 | float | الإحداثي الصادي للنقطة الثانية. |

### Method: draw_line_point_f(pen, point1, point2) {#draw_line_point_f_pen_point1_point2_108}


```
 draw_line_point_f(pen, point1, point2) 
```

يرسم خطًا يربط بين هيكلين [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض ونمط الخط. |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) الهيكل الذي يمثل النقطة الأولى للاتصال. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) الهيكل الذي يمثل النقطة الثانية للاتصال. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_109}


```
 draw_lines(pen, points) 
```

يرسم سلسلة من مقاطع الخط التي تربط مصفوفة من هياكل [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط لقطاعات الخط. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [Point](/imaging/python-net/aspose.imaging/point/) التي تمثل النقاط للاتصال. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_110}


```
 draw_lines(pen, points) 
```

يرسم سلسلة من مقاطع الخط التي تربط مصفوفة من هياكل [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط لقطاعات الخط. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [Point](/imaging/python-net/aspose.imaging/point/) التي تمثل النقاط للاتصال. |

### Method: draw_lines_f(pen, points) {#draw_lines_f_pen_points_111}


```
 draw_lines_f(pen, points) 
```

يرسم سلسلة من مقاطع الخط التي تربط مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط لقطاعات الخط. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تمثل النقاط للاتصال. |

### Method: draw_path(pen, path) {#draw_path_pen_path_112}


```
 draw_path(pen, path) 
```

يرسم [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للمسار. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) للرسم. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_113}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

يرسم شكل فطيرة يُحدَّد بواسطة قطع ناقص محدد بواسطة هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) وخطين شعاعيين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط لشكل الفطيرة. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الهيكل الذي يمثل المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| start_angle | float | الزاوية مقاسة بالدرجات في اتجاه عقارب الساعة من محور x إلى الجانب الأول من شكل الفطيرة. |
| sweep_angle | float | الزاوية مقاسة بالدرجات في اتجاه عقارب الساعة من المعامل _startAngle_ إلى الجانب الثاني من شكل الفطيرة. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_114}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

يرسم شكل فطيرة يُحدَّد بواسطة قطع ناقص محدد بواسطة هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) وخطين شعاعيين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط لشكل الفطيرة. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الهيكل الذي يمثل المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| start_angle | float | الزاوية مقاسة بالدرجات في اتجاه عقارب الساعة من محور x إلى الجانب الأول من شكل الفطيرة. |
| sweep_angle | float | الزاوية مقاسة بالدرجات في اتجاه عقارب الساعة من المعامل _startAngle_ إلى الجانب الثاني من شكل الفطيرة. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_115}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

يرسم شكل فطيرة يُحدَّد بواسطة قطع ناقص محدد بواسطة زوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط لشكل الفطيرة. |
| x | float | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| y | float | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| width | float | عرض المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| height | float | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| start_angle | float | الزاوية مقاسة بالدرجات في اتجاه عقارب الساعة من محور x إلى الجانب الأول من شكل الفطيرة. |
| sweep_angle | float | الزاوية مقاسة بالدرجات في اتجاه عقارب الساعة من المعامل _startAngle_ إلى الجانب الثاني من شكل الفطيرة. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_116}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

يرسم شكل فطيرة يُحدَّد بواسطة قطع ناقص محدد بواسطة زوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط لشكل الفطيرة. |
| x | int | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| y | int | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| width | int | عرض المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| height | int | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| start_angle | int | الزاوية مقاسة بالدرجات في اتجاه عقارب الساعة من محور x إلى الجانب الأول من شكل الفطيرة. |
| sweep_angle | int | الزاوية مقاسة بالدرجات في اتجاه عقارب الساعة من المعامل _startAngle_ إلى الجانب الثاني من شكل الفطيرة. |

### Method: draw_pie_in_rect(pen, rect, start_angle, sweep_angle) {#draw_pie_in_rect_pen_rect_start_angle_sweep_angle_117}


```
 draw_pie_in_rect(pen, rect, start_angle, sweep_angle) 
```

يرسم شكل فطيرة يُحدَّد بواسطة قطع ناقص محدد بواسطة هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) وخطين شعاعيين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط لشكل الفطيرة. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الهيكل الذي يمثل المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| start_angle | float | الزاوية مقاسة بالدرجات في اتجاه عقارب الساعة من محور x إلى الجانب الأول من شكل الفطيرة. |
| sweep_angle | float | الزاوية مقاسة بالدرجات في اتجاه عقارب الساعة من المعامل _startAngle_ إلى الجانب الثاني من شكل الفطيرة. |

### Method: draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle) {#draw_pie_in_rect_f_pen_rect_start_angle_sweep_angle_118}


```
 draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle) 
```

يرسم شكل فطيرة يُحدَّد بواسطة قطع ناقص محدد بواسطة هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) وخطين شعاعيين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط لشكل الفطيرة. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الهيكل الذي يمثل المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| start_angle | float | الزاوية مقاسة بالدرجات في اتجاه عقارب الساعة من محور x إلى الجانب الأول من شكل الفطيرة. |
| sweep_angle | float | الزاوية مقاسة بالدرجات في اتجاه عقارب الساعة من المعامل _startAngle_ إلى الجانب الثاني من شكل الفطيرة. |

### Method: draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_xy_pen_x_y_width_height_start_angle_sweep_angle_119}


```
 draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle) 
```

يرسم شكل فطيرة يُحدَّد بواسطة قطع ناقص محدد بواسطة زوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط لشكل الفطيرة. |
| x | int | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| y | int | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| width | int | عرض المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| height | int | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| start_angle | int | الزاوية مقاسة بالدرجات في اتجاه عقارب الساعة من محور x إلى الجانب الأول من شكل الفطيرة. |
| sweep_angle | int | الزاوية مقاسة بالدرجات في اتجاه عقارب الساعة من المعامل _startAngle_ إلى الجانب الثاني من شكل الفطيرة. |

### Method: draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_xyf_pen_x_y_width_height_start_angle_sweep_angle_120}


```
 draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle) 
```

يرسم شكل فطيرة يُحدَّد بواسطة قطع ناقص محدد بواسطة زوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط لشكل الفطيرة. |
| x | float | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| y | float | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| width | float | عرض المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| height | float | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| start_angle | float | الزاوية مقاسة بالدرجات في اتجاه عقارب الساعة من محور x إلى الجانب الأول من شكل الفطيرة. |
| sweep_angle | float | الزاوية مقاسة بالدرجات في اتجاه عقارب الساعة من المعامل _startAngle_ إلى الجانب الثاني من شكل الفطيرة. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_121}


```
 draw_polygon(pen, points) 
```

يرسم مضلعًا يُحدَّد بواسطة مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للمضلع. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تمثل رؤوس المضلع. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_122}


```
 draw_polygon(pen, points) 
```

يرسم مضلعًا يُحدَّد بواسطة مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للمضلع. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تمثل رؤوس المضلع. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_polygon_f(pen, points) {#draw_polygon_f_pen_points_123}


```
 draw_polygon_f(pen, points) 
```

يرسم مضلعًا يُحدَّد بواسطة مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للمضلع. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تمثل رؤوس المضلع. |

### Method: draw_rect(pen, x, y, width, height) {#draw_rect_pen_x_y_width_height_124}


```
 draw_rect(pen, x, y, width, height) 
```

يرسم مستطيلًا يُحدَّد بواسطة زوج من الإحداثيات، عرض، وارتفاع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للمستطيل. |
| x | int | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل المراد رسمه. |
| y | int | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل المراد رسمه. |
| width | int | عرض المستطيل المراد رسمه. |
| height | int | ارتفاع المستطيل المراد رسمه. |

### Method: draw_rect_f(pen, x, y, width, height) {#draw_rect_f_pen_x_y_width_height_125}


```
 draw_rect_f(pen, x, y, width, height) 
```

يرسم مستطيلًا يُحدَّد بواسطة زوج من الإحداثيات، عرض، وارتفاع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للمستطيل. |
| x | float | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل المراد رسمه. |
| y | float | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل المراد رسمه. |
| width | float | عرض المستطيل المراد رسمه. |
| height | float | ارتفاع المستطيل المراد رسمه. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_126}


```
 draw_rectangle(pen, rect) 
```

يرسم مستطيلًا يُحدَّد بواسطة هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للمستطيل. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يمثل المستطيل المراد رسمه. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_127}


```
 draw_rectangle(pen, rect) 
```

يرسم مستطيلًا يُحدَّد بواسطة هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للمستطيل. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يمثل المستطيل المراد رسمه. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_128}


```
 draw_rectangle(pen, x, y, width, height) 
```

يرسم مستطيلًا يُحدَّد بواسطة زوج من الإحداثيات، عرض، وارتفاع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للمستطيل. |
| x | float | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل المراد رسمه. |
| y | float | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل المراد رسمه. |
| width | float | عرض المستطيل المراد رسمه. |
| height | float | ارتفاع المستطيل المراد رسمه. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_129}


```
 draw_rectangle(pen, x, y, width, height) 
```

يرسم مستطيلًا يُحدَّد بواسطة زوج من الإحداثيات، عرض، وارتفاع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للمستطيل. |
| x | int | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل المراد رسمه. |
| y | int | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل المراد رسمه. |
| width | int | عرض المستطيل المراد رسمه. |
| height | int | ارتفاع المستطيل المراد رسمه. |

### Method: draw_rectangle_f(pen, rect) {#draw_rectangle_f_pen_rect_130}


```
 draw_rectangle_f(pen, rect) 
```

يرسم مستطيلًا يُحدَّد بواسطة هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط للمستطيل. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يمثل المستطيل المراد رسمه. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_131}


```
 draw_rectangles(pen, rects) 
```

يرسم سلسلة من المستطيلات التي تُحدَّد بواسطة هياكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط لحدود المستطيلات. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | مصفوفة من هياكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) التي تمثل المستطيلات المراد رسمها. |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_132}


```
 draw_rectangles(pen, rects) 
```

يرسم سلسلة من المستطيلات التي تُحدَّد بواسطة هياكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط لحدود المستطيلات. |
| rects | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | مصفوفة من هياكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) التي تمثل المستطيلات المراد رسمها. |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: draw_rectangles_f(pen, rects) {#draw_rectangles_f_pen_rects_133}


```
 draw_rectangles_f(pen, rects) 
```

يرسم سلسلة من المستطيلات التي تُحدَّد بواسطة هياكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) الذي يحدد اللون والعرض والنمط لحدود المستطيلات. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | مصفوفة من هياكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) التي تمثل المستطيلات المراد رسمها. |

### Method: draw_string(s, font, brush, layout_rectangle) {#draw_string_s_font_brush_layout_rectangle_134}


```
 draw_string(s, font, brush, layout_rectangle) 
```

يرسم سلسلة النص المحددة في المستطيل المحدد باستخدام [Brush](/imaging/python-net/aspose.imaging/brush/) و[Font](/imaging/python-net/aspose.imaging/font/) المحددين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| s | string | النص المراد رسمه. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) الذي يحدد تنسيق النص. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد اللون والملمس للنص المرسوم. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الذي يحدد موقع النص المرسوم. |

### Method: draw_string(s, font, brush, layout_rectangle, format) {#draw_string_s_font_brush_layout_rectangle_format_135}


```
 draw_string(s, font, brush, layout_rectangle, format) 
```

يرسم سلسلة النص المحددة في المستطيل المحدد باستخدام [Brush](/imaging/python-net/aspose.imaging/brush/) و[Font](/imaging/python-net/aspose.imaging/font/) المحددين مع خصائص التنسيق الخاصة بـ [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| s | string | النص المراد رسمه. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) الذي يحدد تنسيق النص. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد اللون والملمس للنص المرسوم. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الذي يحدد موقع النص المرسوم. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) الذي يحدد سمات التنسيق، مثل تباعد الأسطر والمحاذاة، التي تُطبق على النص المرسوم. |

### Method: draw_string(s, font, brush, point) {#draw_string_s_font_brush_point_136}


```
 draw_string(s, font, brush, point) 
```

يرسم سلسلة النص المحددة في الموقع المحدد باستخدام [Brush](/imaging/python-net/aspose.imaging/brush/) و[Font](/imaging/python-net/aspose.imaging/font/) المحددين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| s | string | النص المراد رسمه. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) الذي يحدد تنسيق النص. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد اللون والملمس للنص المرسوم. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) الذي يحدد الزاوية العليا اليسرى للنص المرسوم. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_string(s, font, brush, point, format) {#draw_string_s_font_brush_point_format_137}


```
 draw_string(s, font, brush, point, format) 
```

يرسم سلسلة النص المحددة في الموقع المحدد باستخدام [Brush](/imaging/python-net/aspose.imaging/brush/) و[Font](/imaging/python-net/aspose.imaging/font/) المحددين مع خصائص التنسيق الخاصة بـ [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| s | string | النص المراد رسمه. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) الذي يحدد تنسيق النص. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد اللون والملمس للنص المرسوم. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) الذي يحدد الزاوية العليا اليسرى للنص المرسوم. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) الذي يحدد سمات التنسيق، مثل تباعد الأسطر والمحاذاة، التي تُطبق على النص المرسوم. |

### Method: draw_string(s, font, brush, x, y) {#draw_string_s_font_brush_x_y_138}


```
 draw_string(s, font, brush, x, y) 
```

يرسم سلسلة النص المحددة في الموقع المحدد باستخدام [Brush](/imaging/python-net/aspose.imaging/brush/) و[Font](/imaging/python-net/aspose.imaging/font/) المحددين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| s | string | النص المراد رسمه. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) الذي يحدد تنسيق النص. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد اللون والملمس للنص المرسوم. |
| x | float | الإحداثي السيني للزاوية العليا اليسرى للنص المرسوم. |
| y | float | الإحداثي الصادي للزاوية العليا اليسرى للنص المرسوم. |

### Method: draw_string(s, font, brush, x, y, format) {#draw_string_s_font_brush_x_y_format_139}


```
 draw_string(s, font, brush, x, y, format) 
```

يرسم سلسلة النص المحددة في الموقع المحدد باستخدام [Brush](/imaging/python-net/aspose.imaging/brush/) و[Font](/imaging/python-net/aspose.imaging/font/) المحددين مع خصائص التنسيق الخاصة بـ [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| s | string | النص المراد رسمه. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) الذي يحدد تنسيق النص. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد اللون والملمس للنص المرسوم. |
| x | float | الإحداثي السيني للزاوية العليا اليسرى للنص المرسوم. |
| y | float | الإحداثي الصادي للزاوية العليا اليسرى للنص المرسوم. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) الذي يحدد سمات التنسيق، مثل تباعد الأسطر والمحاذاة، التي تُطبق على النص المرسوم. |

### Method: draw_string_at_point_f(s, font, brush, point) {#draw_string_at_point_f_s_font_brush_point_140}


```
 draw_string_at_point_f(s, font, brush, point) 
```

يرسم سلسلة النص المحددة في الموقع المحدد باستخدام [Brush](/imaging/python-net/aspose.imaging/brush/) و[Font](/imaging/python-net/aspose.imaging/font/) المحددين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| s | string | النص المراد رسمه. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) الذي يحدد تنسيق النص. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد اللون والملمس للنص المرسوم. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) الذي يحدد الزاوية العليا اليسرى للنص المرسوم. |

### Method: draw_string_at_point_f_format(s, font, brush, point, format) {#draw_string_at_point_f_format_s_font_brush_point_format_141}


```
 draw_string_at_point_f_format(s, font, brush, point, format) 
```

يرسم سلسلة النص المحددة في الموقع المحدد باستخدام [Brush](/imaging/python-net/aspose.imaging/brush/) و[Font](/imaging/python-net/aspose.imaging/font/) المحددين مع خصائص التنسيق الخاصة بـ [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| s | string | النص المراد رسمه. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) الذي يحدد تنسيق النص. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد اللون والملمس للنص المرسوم. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | هيكل [PointF](/imaging/python-net/aspose.imaging/pointf/) الذي يحدد الزاوية العليا اليسرى للنص المرسوم. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) الذي يحدد سمات التنسيق، مثل تباعد الأسطر والمحاذاة، التي تُطبق على النص المرسوم. |

### Method: draw_string_at_xy(s, font, brush, x, y) {#draw_string_at_xy_s_font_brush_x_y_142}


```
 draw_string_at_xy(s, font, brush, x, y) 
```

يرسم سلسلة النص المحددة في الموقع المحدد باستخدام [Brush](/imaging/python-net/aspose.imaging/brush/) و[Font](/imaging/python-net/aspose.imaging/font/) المحددين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| s | string | النص المراد رسمه. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) الذي يحدد تنسيق النص. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد اللون والملمس للنص المرسوم. |
| x | float | الإحداثي السيني للزاوية العليا اليسرى للنص المرسوم. |
| y | float | الإحداثي الصادي للزاوية العليا اليسرى للنص المرسوم. |

### Method: draw_string_in_rect(s, font, brush, layout_rectangle) {#draw_string_in_rect_s_font_brush_layout_rectangle_143}


```
 draw_string_in_rect(s, font, brush, layout_rectangle) 
```

يرسم سلسلة النص المحددة في المستطيل المحدد باستخدام [Brush](/imaging/python-net/aspose.imaging/brush/) و[Font](/imaging/python-net/aspose.imaging/font/) المحددين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| s | string | النص المراد رسمه. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) الذي يحدد تنسيق النص. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد اللون والملمس للنص المرسوم. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الذي يحدد موقع النص المرسوم. |

### Method: draw_string_in_rect_f(s, font, brush, layout_rectangle, format) {#draw_string_in_rect_f_s_font_brush_layout_rectangle_format_144}


```
 draw_string_in_rect_f(s, font, brush, layout_rectangle, format) 
```

يرسم سلسلة النص المحددة في المستطيل المحدد باستخدام [Brush](/imaging/python-net/aspose.imaging/brush/) و[Font](/imaging/python-net/aspose.imaging/font/) المحددين مع خصائص التنسيق الخاصة بـ [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| s | string | النص المراد رسمه. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) الذي يحدد تنسيق النص. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد اللون والملمس للنص المرسوم. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) الذي يحدد موقع النص المرسوم. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) الذي يحدد سمات التنسيق، مثل تباعد الأسطر والمحاذاة، التي تُطبق على النص المرسوم. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_145}


```
 fill_closed_curve(brush, points) 
```

يملأ داخل منحنى السبلين المغلق المحدد بواسطة مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) . يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5 ووضع تعبئة [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تعرف المنحنى المتعدد القطع. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_146}


```
 fill_closed_curve(brush, points) 
```

يملأ داخل منحنى السبلين المغلق المحدد بواسطة مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) . يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5 ووضع تعبئة [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تعرف المنحنى المتعدد القطع. |

### Method: fill_closed_curve(brush, points, fill_mode) {#fill_closed_curve_brush_points_fill_mode_147}


```
 fill_closed_curve(brush, points, fill_mode) 
```

يملأ داخل منحنى السبلين المغلق المحدد بواسطة مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام وضع التعبئة المحدد. يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تعرف المنحنى المتعدد القطع. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | عضو في تعداد [FillMode](/imaging/python-net/aspose.imaging/fillmode/) الذي يحدد كيفية تعبئة المنحنى. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_148}


```
 fill_closed_curve(brush, points, fillmode) 
```

يملأ داخل منحنى السبلين المغلق المحدد بواسطة مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام وضع التعبئة المحدد. يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تعرف المنحنى المتعدد القطع. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) |  |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_149}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

يملأ داخل منحنى السبلين المغلق المحدد بواسطة مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام وضع التعبئة والتوتر المحددين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | فرشاة [Brush](/imaging/python-net/aspose.imaging/brush/) التي تحدد خصائص التعبئة. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تعرف المنحنى المتعدد القطع. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | عضو في تعداد [FillMode](/imaging/python-net/aspose.imaging/fillmode/) الذي يحدد كيفية تعبئة المنحنى. |
| التوتر | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_150}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

يملأ داخل منحنى السبلين المغلق المحدد بواسطة مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام وضع التعبئة والتوتر المحددين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | فرشاة [Brush](/imaging/python-net/aspose.imaging/brush/) التي تحدد خصائص التعبئة. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تعرف المنحنى المتعدد القطع. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | عضو في تعداد [FillMode](/imaging/python-net/aspose.imaging/fillmode/) الذي يحدد كيفية تعبئة المنحنى. |
| التوتر | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### Method: fill_closed_curve_by_point(brush, points) {#fill_closed_curve_by_point_brush_points_151}


```
 fill_closed_curve_by_point(brush, points) 
```

يملأ داخل منحنى السبلين المغلق المحدد بواسطة مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) . يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5 ووضع تعبئة [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تعرف المنحنى المتعدد القطع. |

### Method: fill_closed_curve_by_point_f(brush, points) {#fill_closed_curve_by_point_f_brush_points_152}


```
 fill_closed_curve_by_point_f(brush, points) 
```

يملأ داخل منحنى السبلين المغلق المحدد بواسطة مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) . يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5 ووضع تعبئة [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تعرف المنحنى المتعدد القطع. |

### Method: fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension) {#fill_closed_curve_by_point_f_fill_mode_tension_brush_points_fillmode_tension_153}


```
 fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension) 
```

يملأ داخل منحنى السبلين المغلق المحدد بواسطة مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام وضع التعبئة والتوتر المحددين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | فرشاة [Brush](/imaging/python-net/aspose.imaging/brush/) التي تحدد خصائص التعبئة. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تعرف المنحنى المتعدد القطع. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | عضو في تعداد [FillMode](/imaging/python-net/aspose.imaging/fillmode/) الذي يحدد كيفية تعبئة المنحنى. |
| التوتر | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### Method: fill_closed_curve_by_point_fill_mode(brush, points, fillmode) {#fill_closed_curve_by_point_fill_mode_brush_points_fillmode_154}


```
 fill_closed_curve_by_point_fill_mode(brush, points, fillmode) 
```

يملأ داخل منحنى السبلين المغلق المحدد بواسطة مصفوفة من هياكل [Point](/imaging/python-net/aspose.imaging/point/) باستخدام وضع التعبئة المحدد. يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [Point](/imaging/python-net/aspose.imaging/point/) التي تعرف المنحنى المتعدد القطع. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | عضو في تعداد [FillMode](/imaging/python-net/aspose.imaging/fillmode/) الذي يحدد كيفية تعبئة المنحنى. |

### Method: fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension) {#fill_closed_curve_by_point_fill_mode_tension_brush_points_fillmode_tension_155}


```
 fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension) 
```

يملأ داخل منحنى السبلين المغلق المحدد بواسطة مصفوفة من هياكل [Point](/imaging/python-net/aspose.imaging/point/) باستخدام وضع التعبئة والتوتر المحددين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [Point](/imaging/python-net/aspose.imaging/point/) التي تعرف المنحنى المتعدد القطع. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | عضو في تعداد [FillMode](/imaging/python-net/aspose.imaging/fillmode/) الذي يحدد كيفية تعبئة المنحنى. |
| التوتر | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_156}


```
 fill_ellipse(brush, rect) 
```

يملأ داخل إهليلج محدد بواسطة مستطيل حد يحدده هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يمثل المستطيل المحيط الذي يحدد القطع الناقص. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_157}


```
 fill_ellipse(brush, rect) 
```

يملأ داخل إهليلج محدد بواسطة مستطيل حد يحدده هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يمثل المستطيل المحيط الذي يحدد القطع الناقص. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_158}


```
 fill_ellipse(brush, x, y, width, height) 
```

يملأ داخل إهليلج محدد بواسطة مستطيل حد يحدده زوج من الإحداثيات، عرض، وارتفاع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| x | float | الإحداثي س للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص. |
| y | float | الإحداثي ص للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص. |
| width | float | عرض المستطيل المحيط الذي يحدد القطع الناقص. |
| height | float | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_159}


```
 fill_ellipse(brush, x, y, width, height) 
```

يملأ داخل إهليلج محدد بواسطة مستطيل حد يحدده زوج من الإحداثيات، عرض، وارتفاع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| x | int | الإحداثي س للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص. |
| y | int | الإحداثي ص للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص. |
| width | int | عرض المستطيل المحيط الذي يحدد القطع الناقص. |
| height | int | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص. |

### Method: fill_ellipse_at_xywh(brush, x, y, width, height) {#fill_ellipse_at_xywh_brush_x_y_width_height_160}


```
 fill_ellipse_at_xywh(brush, x, y, width, height) 
```

يملأ داخل إهليلج محدد بواسطة مستطيل حد يحدده زوج من الإحداثيات، عرض، وارتفاع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| x | int | الإحداثي س للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص. |
| y | int | الإحداثي ص للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص. |
| width | int | عرض المستطيل المحيط الذي يحدد القطع الناقص. |
| height | int | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص. |

### Method: fill_ellipse_at_xywhf(brush, x, y, width, height) {#fill_ellipse_at_xywhf_brush_x_y_width_height_161}


```
 fill_ellipse_at_xywhf(brush, x, y, width, height) 
```

يملأ داخل إهليلج محدد بواسطة مستطيل حد يحدده زوج من الإحداثيات، عرض، وارتفاع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| x | float | الإحداثي س للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص. |
| y | float | الإحداثي ص للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص. |
| width | float | عرض المستطيل المحيط الذي يحدد القطع الناقص. |
| height | float | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص. |

### Method: fill_ellipse_in_rect(brush, rect) {#fill_ellipse_in_rect_brush_rect_162}


```
 fill_ellipse_in_rect(brush, rect) 
```

يملأ داخل إهليلج محدد بواسطة مستطيل حد يحدده هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يمثل المستطيل المحيط الذي يحدد القطع الناقص. |

### Method: fill_ellipse_in_rect_f(brush, rect) {#fill_ellipse_in_rect_f_brush_rect_163}


```
 fill_ellipse_in_rect_f(brush, rect) 
```

يملأ داخل إهليلج محدد بواسطة مستطيل حد يحدده هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) يمثل المستطيل المحيط الذي يحدد القطع الناقص. |

### Method: fill_path(brush, path) {#fill_path_brush_path_164}


```
 fill_path(brush, path) 
```

يملأ داخل [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) الذي يمثل المسار للتعبئة. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_165}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

يملأ داخل قطاع فطيرة محدد بواسطة إهليلج يحدده هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) وخطين شعاعيين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) يمثل المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| start_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى الجانب الأول لقطاع الفطيرة. |
| sweep_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل _startAngle_ إلى الجانب الثاني لقطاع الفطيرة. |


**See also:**

**[Example # 1](#example_95)**: The following example shows how to compose an animated GIF image from individ...


### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_166}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

يملأ داخل قطاع فطيرة محدد بواسطة إهليلج يحدده هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) وخطين شعاعيين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | هيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) يمثل المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| start_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى الجانب الأول لقطاع الفطيرة. |
| sweep_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل _startAngle_ إلى الجانب الثاني لقطاع الفطيرة. |


**See also:**

**[Example # 1](#example_95)**: The following example shows how to compose an animated GIF image from individ...


### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_167}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

يملأ داخل قطاع فطيرة محدد بواسطة إهليلج يحدده زوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| x | float | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| y | float | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| width | float | عرض المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| height | float | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قسم الفطيرة. |
| start_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى الجانب الأول لقطاع الفطيرة. |
| sweep_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل _startAngle_ إلى الجانب الثاني لقطاع الفطيرة. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_168}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

يملأ داخل قطاع فطيرة محدد بواسطة إهليلج يحدده زوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| x | int | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| y | int | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| width | int | عرض المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| height | int | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قسم الفطيرة. |
| start_angle | int | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى الجانب الأول لقطاع الفطيرة. |
| sweep_angle | int | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل _startAngle_ إلى الجانب الثاني لقطاع الفطيرة. |

### Method: fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_at_xy_brush_x_y_width_height_start_angle_sweep_angle_169}


```
 fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle) 
```

يملأ داخل قطاع فطيرة محدد بواسطة إهليلج يحدده زوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| x | int | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| y | int | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| width | int | عرض المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| height | int | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قسم الفطيرة. |
| start_angle | int | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى الجانب الأول لقطاع الفطيرة. |
| sweep_angle | int | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل _startAngle_ إلى الجانب الثاني لقطاع الفطيرة. |

### Method: fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_at_xyf_brush_x_y_width_height_start_angle_sweep_angle_170}


```
 fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle) 
```

يملأ داخل قطاع فطيرة محدد بواسطة إهليلج يحدده زوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| x | float | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| y | float | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| width | float | عرض المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| height | float | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قسم الفطيرة. |
| start_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى الجانب الأول لقطاع الفطيرة. |
| sweep_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل _startAngle_ إلى الجانب الثاني لقطاع الفطيرة. |

### Method: fill_pie_in_rect(brush, rect, start_angle, sweep_angle) {#fill_pie_in_rect_brush_rect_start_angle_sweep_angle_171}


```
 fill_pie_in_rect(brush, rect, start_angle, sweep_angle) 
```

يملأ داخل قطاع فطيرة محدد بواسطة إهليلج يحدده هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) وخطين شعاعيين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | هيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) يمثل المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| start_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى الجانب الأول لقطاع الفطيرة. |
| sweep_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل _startAngle_ إلى الجانب الثاني لقطاع الفطيرة. |

### Method: fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle) {#fill_pie_in_rect_f_brush_rect_start_angle_sweep_angle_172}


```
 fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle) 
```

يملأ داخل قطاع فطيرة محدد بواسطة إهليلج يحدده هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) وخطين شعاعيين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) بنية تمثل المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قسم الفطيرة. |
| start_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى الجانب الأول لقطاع الفطيرة. |
| sweep_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل _startAngle_ إلى الجانب الثاني لقطاع الفطيرة. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_173}


```
 fill_polygon(brush, points) 
```

يملأ داخل مضلع محدد بواسطة مصفوفة من النقاط المحددة بهياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) و[FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تمثل رؤوس المضلع المراد تعبئته. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_174}


```
 fill_polygon(brush, points) 
```

يملأ داخل مضلع محدد بواسطة مصفوفة من النقاط المحددة بهياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) و[FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تمثل رؤوس المضلع المراد تعبئته. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_175}


```
 fill_polygon(brush, points, fill_mode) 
```

يملأ داخل مضلع محدد بواسطة مصفوفة من النقاط المحددة بهياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام وضع التعبئة المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تمثل رؤوس المضلع المراد تعبئته. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | عضو في تعداد [FillMode](/imaging/python-net/aspose.imaging/fillmode/) الذي يحدد نمط التعبئة. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_176}


```
 fill_polygon(brush, points, fill_mode) 
```

يملأ داخل مضلع محدد بواسطة مصفوفة من النقاط المحددة بهياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام وضع التعبئة المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تمثل رؤوس المضلع المراد تعبئته. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | عضو في تعداد [FillMode](/imaging/python-net/aspose.imaging/fillmode/) الذي يحدد نمط التعبئة. |

### Method: fill_polygon_by_point(brush, points) {#fill_polygon_by_point_brush_points_177}


```
 fill_polygon_by_point(brush, points) 
```

يملأ داخل مضلع محدد بواسطة مصفوفة من النقاط المحددة بهياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) و[FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تمثل رؤوس المضلع المراد تعبئته. |

### Method: fill_polygon_by_point_f(brush, points) {#fill_polygon_by_point_f_brush_points_178}


```
 fill_polygon_by_point_f(brush, points) 
```

يملأ داخل مضلع محدد بواسطة مصفوفة من النقاط المحددة بهياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) و[FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تمثل رؤوس المضلع المراد تعبئته. |

### Method: fill_polygon_by_point_f_fill_mode(brush, points, fill_mode) {#fill_polygon_by_point_f_fill_mode_brush_points_fill_mode_179}


```
 fill_polygon_by_point_f_fill_mode(brush, points, fill_mode) 
```

يملأ داخل مضلع محدد بواسطة مصفوفة من النقاط المحددة بهياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) باستخدام وضع التعبئة المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة من هياكل [PointF](/imaging/python-net/aspose.imaging/pointf/) التي تمثل رؤوس المضلع المراد تعبئته. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | عضو في تعداد [FillMode](/imaging/python-net/aspose.imaging/fillmode/) الذي يحدد نمط التعبئة. |

### Method: fill_polygon_by_point_fill_mode(brush, points, fill_mode) {#fill_polygon_by_point_fill_mode_brush_points_fill_mode_180}


```
 fill_polygon_by_point_fill_mode(brush, points, fill_mode) 
```

يملأ داخل مضلع محدد بواسطة مصفوفة من النقاط المحددة بهياكل [Point](/imaging/python-net/aspose.imaging/point/) باستخدام وضع التعبئة المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | مصفوفة من هياكل [Point](/imaging/python-net/aspose.imaging/point/) التي تمثل رؤوس المضلع المراد تعبئته. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | عضو في تعداد [FillMode](/imaging/python-net/aspose.imaging/fillmode/) الذي يحدد نمط التعبئة. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_181}


```
 fill_rectangle(brush, rect) 
```

يملأ داخل مستطيل محدد بواسطة هيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | بنية [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) التي تمثل المستطيل المراد تعبئته. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_182}


```
 fill_rectangle(brush, rect) 
```

يملأ داخل مستطيل محدد بواسطة هيكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | بنية [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) التي تمثل المستطيل المراد تعبئته. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_183}


```
 fill_rectangle(brush, x, y, width, height) 
```

يملأ داخل مستطيل محدد بواسطة زوج من الإحداثيات، عرض وارتفاع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| x | float | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل المراد تعبئته. |
| y | float | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل المراد تعبئته. |
| width | float | عرض المستطيل المراد تعبئته. |
| height | float | ارتفاع المستطيل المراد تعبئته. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_184}


```
 fill_rectangle(brush, x, y, width, height) 
```

يملأ داخل مستطيل محدد بواسطة زوج من الإحداثيات، عرض وارتفاع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| x | int | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل المراد تعبئته. |
| y | int | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل المراد تعبئته. |
| width | int | عرض المستطيل المراد تعبئته. |
| height | int | ارتفاع المستطيل المراد تعبئته. |

### Method: fill_rectangle_f(brush, rect) {#fill_rectangle_f_brush_rect_185}


```
 fill_rectangle_f(brush, rect) 
```

يملأ داخل مستطيل محدد بواسطة هيكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | بنية [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) التي تمثل المستطيل المراد تعبئته. |

### Method: fill_rectangle_f_with_brush(brush, x, y, width, height) {#fill_rectangle_f_with_brush_brush_x_y_width_height_186}


```
 fill_rectangle_f_with_brush(brush, x, y, width, height) 
```

يملأ داخل مستطيل محدد بواسطة زوج من الإحداثيات، عرض وارتفاع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| x | float | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل المراد تعبئته. |
| y | float | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل المراد تعبئته. |
| width | float | عرض المستطيل المراد تعبئته. |
| height | float | ارتفاع المستطيل المراد تعبئته. |

### Method: fill_rectangle_with_brush(brush, x, y, width, height) {#fill_rectangle_with_brush_brush_x_y_width_height_187}


```
 fill_rectangle_with_brush(brush, x, y, width, height) 
```

يملأ داخل مستطيل محدد بواسطة زوج من الإحداثيات، عرض وارتفاع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| x | int | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل المراد تعبئته. |
| y | int | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل المراد تعبئته. |
| width | int | عرض المستطيل المراد تعبئته. |
| height | int | ارتفاع المستطيل المراد تعبئته. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_188}


```
 fill_rectangles(brush, rects) 
```

يملأ داخل مجموعة من المستطيلات المحددة بهياكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| rects | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | مصفوفة من هياكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) التي تمثل المستطيلات المراد تعبئتها. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_189}


```
 fill_rectangles(brush, rects) 
```

يملأ داخل مجموعة من المستطيلات المحددة بهياكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | مصفوفة من هياكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) التي تمثل المستطيلات المراد تعبئتها. |

### Method: fill_rectangles_f(brush, rects) {#fill_rectangles_f_brush_rects_190}


```
 fill_rectangles_f(brush, rects) 
```

يملأ داخل مجموعة من المستطيلات المحددة بهياكل [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | مصفوفة من هياكل [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) التي تمثل المستطيلات المراد تعبئتها. |

### Method: fill_region(brush, region) {#fill_region_brush_region_191}


```
 fill_region(brush, region) 
```

يملأ داخل [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) الذي يحدد خصائص التعبئة. |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | [Region](/imaging/python-net/aspose.imaging/region/) التي تمثل المنطقة المراد تعبئتها. |

### Method: measure_string(text, font, layout_area, string_format) {#measure_string_text_font_layout_area_string_format_192}


```
 measure_string(text, font, layout_area, string_format) 
```

يقيس سلسلة النص المحددة باستخدام المعلمات المحددة

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| text | string | النص المراد قياسه. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | الخط المراد قياسه. |
| layout_area | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | منطقة التخطيط. |
| string_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | تنسيق السلسلة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | الحجم بالبكسل لسلسلة النص المقاسة |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_193}


```
 multiply_transform(matrix) 
```

يضرب [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [Graphics](/imaging/python-net/aspose.imaging/graphics/) بالمصفوفة [Matrix](/imaging/python-net/aspose.imaging/matrix/) المحددة عن طريق إلحاق المصفوفة [Matrix](/imaging/python-net/aspose.imaging/matrix/) المحددة في البداية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | الـ [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يُضرب به التحويل الهندسي. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_194}


```
 multiply_transform(matrix, order) 
```

يضرب [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [Graphics](/imaging/python-net/aspose.imaging/graphics/) بالمصفوفة [Matrix](/imaging/python-net/aspose.imaging/matrix/) المحددة بالترتيب المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | الـ [Matrix](/imaging/python-net/aspose.imaging/matrix/) الذي يُضرب به التحويل الهندسي. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) يحدد الترتيب الذي يُضرب فيه المصفوفتان. |

### Method: rotate_transform(angle) {#rotate_transform_angle_195}


```
 rotate_transform(angle) 
```

يدور التحويل الهندسي المحلي بالمقدار المحدد. هذه الطريقة تسبق الدوران إلى التحويل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| angle | float | زاوية الدوران. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_196}


```
 rotate_transform(angle, order) 
```

يدور التحويل الهندسي المحلي بالمقدار المحدد وفقًا للترتيب المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| angle | float | زاوية الدوران. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) يحدد ما إذا كان يجب إضافة أو إلحاق مسبق لمصفوفة الدوران. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_197}


```
 scale_transform(sx, sy) 
```

يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة. هذه الطريقة تسبق مصفوفة التكبير إلى التحويل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| sx | float | المقدار الذي يُكَبَّر به التحويل في اتجاه المحور x. |
| sy | float | المقدار الذي يُكَبَّر به التحويل في اتجاه المحور y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_198}


```
 scale_transform(sx, sy, order) 
```

يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة وفقًا للترتيب المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| sx | float | المقدار الذي يُكَبَّر به التحويل في اتجاه المحور x. |
| sy | float | المقدار الذي يُكَبَّر به التحويل في اتجاه المحور y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | قائمة [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) التي تحدد ما إذا كان سيتم إلحاق أو إلحاق مسبق لمصفوفة التحجيم. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_199}


```
 translate_transform(dx, dy) 
```

ينقل التحويل الهندسي المحلي بالأبعاد المحددة. هذه الطريقة تسبق الترجمة إلى التحويل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dx | float | قيمة الإزاحة في المحور x. |
| dy | float | قيمة الإزاحة في المحور y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_200}


```
 translate_transform(dx, dy, order) 
```

ينقل التحويل الهندسي المحلي بالأبعاد المحددة وفقًا للترتيب المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| dx | float | قيمة الإزاحة في المحور x. |
| dy | float | قيمة الإزاحة في المحور y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | الترتيب (إلحاق مسبق أو إلحاق) الذي يتم تطبيق الإزاحة به. |

## **Examples**
### This example uses Graphics class to create primitive shapes on the Image surface. To demonstrate the operation, the example creates a new Image in PNG format and draw primitive shapes on Image surface using Draw methods exposed by Graphics class {#example_12}
``` python

from aspose.imaging import Image, RotateFlipType, Graphics, Color, Pen, Rectangle, Point, Size,\
	Font, PointF
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.psd import CompressionMethod, ColorModes
from aspose.imaging.sources import StreamSource

from os.path import join as path_join

#ينشئ مثيلاً من تدفق الملف.
with open(r"C:\temp\output.png", "w+b") as stream:
	#إنشاء مثيل من PngOptions وتعيين خصائصه المتنوعة.
	pngOptions = PngOptions()
	#تعيين المصدر لـ PngOptions.
	pngOptions.source = StreamSource(stream)
	#إنشاء مثيل من Image.
	with Image.create(pngOptions, 500, 500) as image:
		#إنشاء وتهيئة مثيل من فئة Graphics.
		graphics = Graphics(image)
		#مسح سطح Graphics.
		graphics.clear(Color.wheat);
		#ارسم قوسًا بتحديد كائن Pen الذي لديه لون أسود،
		#مستطيل يحيط بالقوس، زاوية البداية وزاوية المسح
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#ارسم منحنى Bezier بتحديد كائن Pen الذي لديه لون أزرق ونقاط الإحداثيات.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#ارسم منحنى عن طريق تحديد كائن Pen ذو اللون الأخضر ومصفوفة من Points
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#ارسم إهليلجًا باستخدام كائن Pen ومستطيل محيط
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#ارسم خطًا
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#ارسم قطعة فطيرة
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#ارسم مضلعًا بتحديد كائن Pen ذو اللون الأحمر ومصفوفة من Points
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#ارسم مستطيلًا
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#أنشئ كائن SolidBrush واضبط خصائصه المتنوعة
		brush = SolidBrush()
		brush.color = Color.purple
		#ارسم نصًا باستخدام كائن SolidBrush و Font، عند نقطة محددة
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# احفظ جميع التغييرات.
		image.save();

```

### This examples make use of GraphicsPath and Graphics classes to create and manipulate figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end `draw_path` method exposed by Graphics class is called to render the paths on surface. {#example_13}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, PointF, SizeF
from aspose.imaging import Pen
from aspose.imaging.sources import StreamSource
from aspose.imaging.imageoptions import TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from aspose.imaging.shapes import RectangleShape, EllipseShape, PieShape


# إنشاء كائن من تدفق ملف
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# إنشاء نسخة من TiffOptions وتعيين خصائصه المتنوعة
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# تعيين المصدر للنسخة من ImageOptions
	tiffOptions.source = StreamSource(stream)
	# إنشاء نسخة من Image
	with Image.create(tiffOptions, 500, 500) as image:
		# إنشاء وتهيئة مثيل من فئة Graphics.
		graphics = Graphics(image)
		# مسح سطح Graphics.
		graphics.clear(Color.wheat);
		# إنشاء نسخة من الفئة GraphicsPath
		graphics_path = GraphicsPath()
		# إنشاء نسخة من الفئة Figure
		figure = Figure()
		# إضافة أشكال إلى كائن Figure
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# إضافة كائن Figure إلى GraphicsPath
		graphics_path.add_figure(figure)
		# رسم المسار باستخدام كائن Pen باللون الأسود
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# احفظ جميع التغييرات.
		image.save()


```

### This example shows the creation and usage Pen objects. The example creates a new Image and draw rectangles on the Image surface. {#example_14}
``` python

from aspose.imaging import Image, Graphics, Color, Pen, Rectangle, Point, Size
from aspose.imaging.brushes import HatchBrush
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

# إنشاء نسخة من BmpOptions وتعيين خصائصه المتنوعة
bmpOptions = BmpOptions()
bmpOptions.bits_per_pixel = 24
# إنشاء نسخة من FileCreateSource وتعيينها كمصدر للنسخة من BmpOptions
# المعامل البولياني الثاني يحدد ما إذا كان الملف الذي سيتم إنشاؤه IsTemporal أم لا
bmpOptions.source = FileCreateSource(r"C:\temp\sample.bmp", False)
# إنشاء نسخة من Image في المسار المحدد
with Image.create(bmpOptions, 500, 500) as image:
	# إنشاء نسخة من Graphics وتهيئتها باستخدام كائن Image
	graphics = Graphics(image)
	# مسح سطح Graphics بلون أبيض
	graphics.clear(Color.white)
	#إنشاء نسخة من Pen باللون الأحمر وعرض 5
	pen = Pen(Color.red, 5.0);
	# إنشاء نسخة من HatchBrush وتعيين خصائصه
	brush = HatchBrush()
	brush.background_color = Color.wheat;
	brush.foreground_color = Color.red;
	# إنشاء نسخة من Pen
	# قم بتهيئتها باستخدام كائن HatchBrush والعرض
	brusedpen = Pen(brush, 5.0)
	# ارسم مستطيلات عن طريق تحديد كائن Pen
	graphics.draw_rectangles(pen, [
		Rectangle(Point(210, 210), Size(100, 100)),
		Rectangle(Point(110, 110), Size(100, 100)),
		Rectangle(Point(310, 310), Size(100, 100)) ])

	# ارسم مستطيلات عن طريق تحديد كائن Pen
	graphics.draw_rectangles(brusedpen, [
		Rectangle(Point(310, 110), Size(100, 100)),
		Rectangle(Point(110, 310), Size(100, 100)) ])

	# احفظ جميع التغييرات.
	image.save()


```

### The following example shows how to compose an animated GIF image from individual GIF blocks. {#example_95}
``` python
from aspose.imaging.fileformats.gif.blocks import GifFrameBlock
from aspose.imaging.fileformats.gif import GifImage 
from aspose.imaging.brushes import SolidBrush
from aspose.imaging import Graphics, Color

# أنشئ صورة GIF بحجم 100 × 100 بكسل.
# الكتلة الأولى سوداء بالكامل بشكل افتراضي.
with GifFrameBlock(100, 100) as firstBlock:
	with GifImage(firstBlock) as gifImage:
		# الدائرة الأولى حمراء
		brush1 = SolidBrush(Color.red)

		# الدائرة الثانية سوداء
		brush2 = SolidBrush(Color.black)

		# زد زاوية الشكل القوسي الأحمر تدريجيًا.
		for angle in range(10, 361, 10):
			block = GifFrameBlock(100, 100)
			gr = Graphics(block)
			gr.fill_pie(brush1, block.bounds, 0, angle)
			gifImage.add_block(block)
		
		# زد زاوية القوس الأسود تدريجيًا وامسح القوس الأحمر.
		for angle in range(10, 361, 10):
			block = GifFrameBlock(100, 100)
			gr = Graphics(block)
			gr.fill_pie(brush2, block.bounds, 0, angle)
			gr.fill_pie(brush1, block.bounds, angle, 360 - angle)
			gifImage.add_block(block)

		gifImage.save("animated_radar.gif")


```

### This example shows how to create a PNG image of the specified size, fill it with a solid color and save it to a file. {#example_114}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.fileformats.png import PngImage
from os.path import join


dir_ = "c:\\temp"
# أنشئ صورة PNG بحجم 100 × 100 بكسل.
with PngImage(100, 100) as png_image:
	# قم ببعض معالجة الصور، مثل ملء الصورة بالكامل باللون الأحمر.
	graphics = Graphics(png_image)
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, png_image.bounds)
	# احفظ إلى ملف.
	png_image.save(join(dir_, "output.png"))


```

