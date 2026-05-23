---
title: "Graphics Sınıfı"
type: docs
weight: 5030
url: /tr/python-net/aspose.imaging/graphics/
---

**Summary:** Represents the graphics according to the graphics engine used in the current assembly.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Graphics

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [Graphics(source_image)](#Graphics_source_image_1) | Yeni bir [Graphics](/imaging/python-net/aspose.imaging/graphics/) sınıfı başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| clip | [Region](/imaging/python-net/aspose.imaging/region/) | r/w | Kırpma bölgesini alır veya ayarlar. |
| compositing_quality | [CompositingQuality](/imaging/python-net/aspose.imaging/compositingquality/) | r/w | Bileşim kalitesini alır veya ayarlar. |
| dpi_x | float | r | Bu `aspose.imaging.Graphics` nesnesinin yatay çözünürlüğünü alır. |
| dpi_y | float | r | Bu `aspose.imaging.Graphics` nesnesinin dikey çözünürlüğünü alır. |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | r | Görüntüyü alır. |
| interpolation_mode | [InterpolationMode](/imaging/python-net/aspose.imaging/interpolationmode/) | r/w | Enterpolasyon modunu alır veya ayarlar. |
| is_in_begin_update_call | bool | r | Grafiğin BeginUpdate çağrı durumunda olup olmadığını gösteren bir değeri alır. |
| page_scale | float | r/w | Bu `aspose.imaging.Graphics` için dünya birimleri ile sayfa birimleri arasındaki ölçeklemeyi alır veya ayarlar. |
| page_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | r/w | Bu `aspose.imaging.Graphics` içindeki sayfa koordinatları için kullanılan ölçü birimini alır veya ayarlar. |
| paintable_image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | r/w | Görsel seçeneklerini alır veya ayarlar; bu seçenekler, çizim için boyanabilir vektör görüntüleri oluşturmakta kullanılır. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Yumuşatma modunu alır veya ayarlar. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Metin renderleme ipucunu alır veya ayarlar. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Bu [Graphics](/imaging/python-net/aspose.imaging/graphics/) için geometrik dünya dönüşümünün bir kopyasını alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| begin_update() | Aşağıdaki grafik işlemlerinin önbelleğe alınmasını başlatır. Sonradan uygulanan grafik efektleri hemen uygulanmaz, bunun yerine EndUpdate tüm efektlerin bir kerede uygulanmasını sağlar. |
| [clear(color)](#clear_color_1) | Belirtilen rengi kullanarak grafik yüzeyini temizler. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_2) | Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ile belirtilen elipsin bir kısmını temsil eden bir yay çizer. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_3) | Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ile belirtilen elipsin bir kısmını temsil eden bir yay çizer. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4) | Koordinat çifti, genişlik ve yükseklik ile belirtilen elipsin bir kısmını temsil eden bir yay çizer. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5) | Koordinat çifti, genişlik ve yükseklik ile belirtilen elipsin bir kısmını temsil eden bir yay çizer. |
| [draw_arc_in_rect(pen, rect, start_angle, sweep_angle)](#draw_arc_in_rect_pen_rect_start_angle_sweep_angle_6) | Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ile belirtilen elipsin bir kısmını temsil eden bir yay çizer. |
| [draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle)](#draw_arc_in_rect_f_pen_rect_start_angle_sweep_angle_7) | Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ile belirtilen elipsin bir kısmını temsil eden bir yay çizer. |
| [draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_xy_pen_x_y_width_height_start_angle_sweep_angle_8) | Koordinat çifti, genişlik ve yükseklik ile belirtilen elipsin bir kısmını temsil eden bir yay çizer. |
| [draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_xyf_pen_x_y_width_height_start_angle_sweep_angle_9) | Koordinat çifti, genişlik ve yükseklik ile belirtilen elipsin bir kısmını temsil eden bir yay çizer. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_10) | Dört [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ile tanımlanan bir Bézier spline çizer. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_11) | Dört [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ile tanımlanan bir Bézier spline çizer. |
| [draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4)](#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_12) | Noktaları temsil eden dört sıralı koordinat çifti ile tanımlanan bir Bézier spline çizer. |
| [draw_bezier_by_points(pen, pt1, pt2, pt3, pt4)](#draw_bezier_by_points_pen_pt1_pt2_pt3_pt4_13) | Dört [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ile tanımlanan bir Bézier spline çizer. |
| [draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4)](#draw_bezier_by_points_f_pen_pt1_pt2_pt3_pt4_14) | Dört [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ile tanımlanan bir Bézier spline çizer. |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_15) | Bir dizi [Point](/imaging/python-net/aspose.imaging/point/) yapısından bir dizi Bézier spline çizer. |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_16) | Bir dizi [Point](/imaging/python-net/aspose.imaging/point/) yapısından bir dizi Bézier spline çizer. |
| [draw_beziers_by_pt_array(pen, points)](#draw_beziers_by_pt_array_pen_points_17) | Bir dizi [Point](/imaging/python-net/aspose.imaging/point/) yapısından bir dizi Bézier spline çizer. |
| [draw_beziers_by_pt_array_f(pen, points)](#draw_beziers_by_pt_array_f_pen_points_18) | Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısından bir dizi Bézier spline çizer. |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_19) | Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ile tanımlanan kapalı bir kardinal spline çizer. Bu yöntem varsayılan 0.5 gerilim ve [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) doldurma modunu kullanır. |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_20) | Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ile tanımlanan kapalı bir kardinal spline çizer. Bu yöntem varsayılan 0.5 gerilim ve [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) doldurma modunu kullanır. |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_21) | Belirtilen bir gerilim kullanarak bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ile tanımlanan kapalı bir kardinal spline çizer. Bu yöntem varsayılan [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) doldurma modunu kullanır. |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_22) | Belirtilen bir gerilim kullanarak bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ile tanımlanan kapalı bir kardinal spline çizer. Bu yöntem varsayılan [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) doldurma modunu kullanır. |
| [draw_closed_curve_by_points(pen, points)](#draw_closed_curve_by_points_pen_points_23) | Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ile tanımlanan kapalı bir kardinal spline çizer. Bu yöntem varsayılan 0.5 gerilim ve [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) doldurma modunu kullanır. |
| [draw_closed_curve_by_points_f(pen, points)](#draw_closed_curve_by_points_f_pen_points_24) | Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ile tanımlanan kapalı bir kardinal spline çizer. Bu yöntem varsayılan 0.5 gerilim ve [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) doldurma modunu kullanır. |
| [draw_closed_curve_by_points_f_tension(pen, points, tension)](#draw_closed_curve_by_points_f_tension_pen_points_tension_25) | Belirtilen bir gerilim kullanarak bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ile tanımlanan kapalı bir kardinal spline çizer. Bu yöntem varsayılan [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) doldurma modunu kullanır. |
| [draw_closed_curve_by_points_tension(pen, points, tension)](#draw_closed_curve_by_points_tension_pen_points_tension_26) | Belirtilen bir gerilim kullanarak bir dizi [Point](/imaging/python-net/aspose.imaging/point/) yapısı ile tanımlanan kapalı bir kardinal spline çizer. Bu yöntem varsayılan [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) doldurma modunu kullanır. |
| [draw_curve(pen, points)](#draw_curve_pen_points_27) | Belirtilen bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı üzerinden bir kardinal spline çizer. Bu yöntem varsayılan 0.5 gerilimi kullanır. |
| [draw_curve(pen, points)](#draw_curve_pen_points_28) | Belirtilen bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı üzerinden bir kardinal spline çizer. Bu yöntem varsayılan 0.5 gerilimi kullanır. |
| [draw_curve(pen, points, offset, number_of_segments)](#draw_curve_pen_points_offset_number_of_segments_29) | Belirtilen bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı üzerinden bir kardinal spline çizer. Çizim, dizinin başından bir offset ile başlar.<br/>            Bu yöntem varsayılan 0.5 gerilim kullanır. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_30) | Belirtilen bir gerilim kullanarak, belirtilen bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı üzerinden bir kardinal spline çizer. Çizim, dizinin başından bir offset ile başlar. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_31) | Belirtilen bir gerilim kullanarak, belirtilen bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı üzerinden bir kardinal spline çizer. Çizim, dizinin başından bir offset ile başlar. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_32) | Belirtilen bir gerilim kullanarak, belirtilen bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı üzerinden bir kardinal spline çizer. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_33) | Belirtilen bir gerilim kullanarak, belirtilen bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı üzerinden bir kardinal spline çizer. |
| [draw_curve_by_point_fs(pen, points)](#draw_curve_by_point_fs_pen_points_34) | Belirtilen bir dizi [Point](/imaging/python-net/aspose.imaging/point/) yapısı üzerinden bir kardinal spline çizer. |
| [draw_curve_by_point_fs_tension(pen, points, tension)](#draw_curve_by_point_fs_tension_pen_points_tension_35) | Belirtilen bir gerilim kullanarak, belirtilen bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı üzerinden bir kardinal spline çizer. |
| [draw_curve_by_points(pen, points)](#draw_curve_by_points_pen_points_36) | Belirtilen bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı üzerinden bir kardinal spline çizer. Bu yöntem varsayılan 0.5 gerilimi kullanır. |
| [draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension)](#draw_curve_by_points_f_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_37) | Belirtilen bir gerilim kullanarak, belirtilen bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı üzerinden bir kardinal spline çizer. Çizim, dizinin başından bir offset ile başlar. |
| [draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension)](#draw_curve_by_points_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_38) | Belirtilen bir gerilim kullanarak, belirtilen bir dizi [Point](/imaging/python-net/aspose.imaging/point/) yapısı üzerinden bir kardinal spline çizer. |
| [draw_curve_by_points_tension(pen, points, tension)](#draw_curve_by_points_tension_pen_points_tension_39) | Belirtilen bir gerilim kullanarak, belirtilen bir dizi [Point](/imaging/python-net/aspose.imaging/point/) yapısı üzerinden bir kardinal spline çizer. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_40) | Sınırlayıcı bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) tarafından tanımlanan bir elips çizer. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_41) | Sınırlayıcı bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) tarafından tanımlanan bir elips çizer. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_42) | Koordinat çifti, yükseklik ve genişlik ile belirtilen sınırlayıcı bir dikdörtgen tarafından tanımlanan bir elips çizer. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_43) | Koordinat çifti, yükseklik ve genişlik ile belirtilen sınırlayıcı bir dikdörtgen tarafından tanımlanan bir elips çizer. |
| [draw_ellipse_by_xy(pen, x, y, width, height)](#draw_ellipse_by_xy_pen_x_y_width_height_44) | Koordinat çifti, yükseklik ve genişlik ile belirtilen sınırlayıcı bir dikdörtgen tarafından tanımlanan bir elips çizer. |
| [draw_ellipse_by_xyf(pen, x, y, width, height)](#draw_ellipse_by_xyf_pen_x_y_width_height_45) | Koordinat çifti, yükseklik ve genişlik ile belirtilen sınırlayıcı bir dikdörtgen tarafından tanımlanan bir elips çizer. |
| [draw_ellipse_f(pen, rect)](#draw_ellipse_f_pen_rect_46) | Sınırlayıcı bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) tarafından tanımlanan bir elips çizer. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_47) | Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_48) | Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_49) | Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_50) | Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_51) | Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_52) | Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_53) | Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_54) | Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(source_image, point)](#draw_image_source_image_point_55) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer. |
| [draw_image(source_image, point)](#draw_image_source_image_point_56) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_57) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_58) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_59) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_60) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_61) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_62) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_63) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_64) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_65) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_66) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_67) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_68) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_69) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_70) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image_at_point(source_image, point)](#draw_image_at_point_source_image_point_71) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer. |
| [draw_image_at_point_f(source_image, point)](#draw_image_at_point_f_source_image_point_72) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer. |
| [draw_image_at_xy(source_image, x, y)](#draw_image_at_xy_source_image_x_y_73) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer. |
| [draw_image_at_xyf(source_image, x, y)](#draw_image_at_xyf_source_image_x_y_74) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer. |
| [draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit)](#draw_image_dest_point_f_src_rect_f_with_unit_image_dest_points_src_rect_src_unit_75) | Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_dest_point_f_src_rect_f_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_76) | Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect)](#draw_image_dest_points_f_src_rect_f_image_dest_points_src_rect_77) | Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image_dest_points_src_rect(image, dest_points, src_rect)](#draw_image_dest_points_src_rect_image_dest_points_src_rect_78) | Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit)](#draw_image_dest_points_src_rect_with_unit_image_dest_points_src_rect_src_unit_79) | Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_dest_points_src_rect_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_80) | Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_dest_rect_f_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_81) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_dest_rect_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_82) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image_in_rect(source_image, x, y, width, height)](#draw_image_in_rect_source_image_x_y_width_height_83) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image_in_rect_f(source_image, x, y, width, height)](#draw_image_in_rect_f_source_image_x_y_width_height_84) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image_in_rectangle(source_image, rect)](#draw_image_in_rectangle_source_image_rect_85) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image_points(image, dest_points)](#draw_image_points_image_dest_points_86) | Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image_points_f(image, dest_points)](#draw_image_points_f_image_dest_points_87) | Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image_rectangle_f(source_image, rect)](#draw_image_rectangle_f_source_image_rect_88) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_src_dest_rects_f_with_unit_source_image_rect_source_rect_destination_graphics_unit_89) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_src_dest_rects_with_unit_source_image_rect_source_rect_destination_graphics_unit_90) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_src_dst_rect_f_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_91) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_src_dst_rects_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_92) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit)](#draw_image_to_rect_f_with_unit_source_image_rect_destination_graphics_unit_93) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit)](#draw_image_to_rect_with_unit_source_image_rect_destination_graphics_unit_94) | Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image_unscaled(source_image, point)](#draw_image_unscaled_source_image_point_95) | Belirtilen bir resmi, özgün fiziksel boyutunu kullanarak, belirtilen bir konumda çizer. |
| [draw_image_unscaled(source_image, rect)](#draw_image_unscaled_source_image_rect_96) | Belirtilen bir resmi, özgün fiziksel boyutunu kullanarak, belirtilen bir konumda çizer. |
| [draw_image_unscaled(source_image, x, y)](#draw_image_unscaled_source_image_x_y_97) | Belirtilen resmi, özgün fiziksel boyutunu kullanarak, bir koordinat çiftiyle belirtilen konumda çizer. |
| [draw_image_unscaled(source_image, x, y, width, height)](#draw_image_unscaled_source_image_x_y_width_height_98) | Belirtilen bir resmi, özgün fiziksel boyutunu kullanarak, belirtilen bir konumda çizer. |
| [draw_image_unscaled_and_clipped(source_image, rect)](#draw_image_unscaled_and_clipped_source_image_rect_99) | Belirtilen resmi ölçeklendirmeden çizer ve gerekirse, belirtilen dikdörtgene sığması için kırpar. |
| [draw_image_unscaled_in_rectangle(source_image, rect)](#draw_image_unscaled_in_rectangle_source_image_rect_100) | Belirtilen bir resmi, özgün fiziksel boyutunu kullanarak, belirtilen bir konumda çizer. |
| [draw_image_unscaled_to_point(source_image, point)](#draw_image_unscaled_to_point_source_image_point_101) | Belirtilen bir resmi, özgün fiziksel boyutunu kullanarak, belirtilen bir konumda çizer. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_102) | İki [Point](/imaging/python-net/aspose.imaging/point/) yapısını birleştiren bir çizgi çizer. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_103) | İki [Point](/imaging/python-net/aspose.imaging/point/) yapısını birleştiren bir çizgi çizer. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_104) | Koordinat çiftleriyle belirtilen iki noktayı birleştiren bir çizgi çizer. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_105) | Koordinat çiftleriyle belirtilen iki noktayı birleştiren bir çizgi çizer. |
| [draw_line_by_xy(pen, x1, y1, x2, y2)](#draw_line_by_xy_pen_x1_y1_x2_y2_106) | Koordinat çiftleriyle belirtilen iki noktayı birleştiren bir çizgi çizer. |
| [draw_line_f_by_xy(pen, x1, y1, x2, y2)](#draw_line_f_by_xy_pen_x1_y1_x2_y2_107) | Koordinat çiftleriyle belirtilen iki noktayı birleştiren bir çizgi çizer. |
| [draw_line_point_f(pen, point1, point2)](#draw_line_point_f_pen_point1_point2_108) | İki [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısını birleştiren bir çizgi çizer. |
| [draw_lines(pen, points)](#draw_lines_pen_points_109) | Bir dizi [Point](/imaging/python-net/aspose.imaging/point/) yapısını birleştiren bir dizi çizgi parçası çizer. |
| [draw_lines(pen, points)](#draw_lines_pen_points_110) | Bir dizi [Point](/imaging/python-net/aspose.imaging/point/) yapısını birleştiren bir dizi çizgi parçası çizer. |
| [draw_lines_f(pen, points)](#draw_lines_f_pen_points_111) | Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısını birleştiren bir dizi çizgi parçası çizer. |
| [draw_path(pen, path)](#draw_path_pen_path_112) | Bir [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) çizer. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_113) | Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_114) | Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_115) | Koordinat çifti, genişlik, yükseklik ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_116) | Koordinat çifti, genişlik, yükseklik ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer. |
| [draw_pie_in_rect(pen, rect, start_angle, sweep_angle)](#draw_pie_in_rect_pen_rect_start_angle_sweep_angle_117) | Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer. |
| [draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle)](#draw_pie_in_rect_f_pen_rect_start_angle_sweep_angle_118) | Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer. |
| [draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_xy_pen_x_y_width_height_start_angle_sweep_angle_119) | Koordinat çifti, genişlik, yükseklik ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer. |
| [draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_xyf_pen_x_y_width_height_start_angle_sweep_angle_120) | Koordinat çifti, genişlik, yükseklik ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_121) | Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından tanımlanan bir çokgen çizer. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_122) | Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından tanımlanan bir çokgen çizer. |
| [draw_polygon_f(pen, points)](#draw_polygon_f_pen_points_123) | Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından tanımlanan bir çokgen çizer. |
| [draw_rect(pen, x, y, width, height)](#draw_rect_pen_x_y_width_height_124) | Koordinat çifti, genişlik ve yükseklik ile belirtilen bir dikdörtgen çizer. |
| [draw_rect_f(pen, x, y, width, height)](#draw_rect_f_pen_x_y_width_height_125) | Koordinat çifti, genişlik ve yükseklik ile belirtilen bir dikdörtgen çizer. |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_126) | Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ile belirtilen bir dikdörtgen çizer. |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_127) | Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ile belirtilen bir dikdörtgen çizer. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_128) | Koordinat çifti, genişlik ve yükseklik ile belirtilen bir dikdörtgen çizer. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_129) | Koordinat çifti, genişlik ve yükseklik ile belirtilen bir dikdörtgen çizer. |
| [draw_rectangle_f(pen, rect)](#draw_rectangle_f_pen_rect_130) | Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ile belirtilen bir dikdörtgen çizer. |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_131) | Bir dizi [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ile belirtilen dikdörtgenler çizer. |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_132) | Bir dizi [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ile belirtilen dikdörtgenler çizer. |
| [draw_rectangles_f(pen, rects)](#draw_rectangles_f_pen_rects_133) | Bir dizi [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ile belirtilen dikdörtgenler çizer. |
| [draw_string(s, font, brush, layout_rectangle)](#draw_string_s_font_brush_layout_rectangle_134) | Belirtilen metin dizesini belirtilen dikdörtgende belirtilen [Brush](/imaging/python-net/aspose.imaging/brush/) ve [Font](/imaging/python-net/aspose.imaging/font/) nesneleriyle çizer. |
| [draw_string(s, font, brush, layout_rectangle, format)](#draw_string_s_font_brush_layout_rectangle_format_135) | Belirtilen metin dizesini belirtilen dikdörtgende belirtilen [Brush](/imaging/python-net/aspose.imaging/brush/) ve [Font](/imaging/python-net/aspose.imaging/font/) nesneleriyle, belirtilen [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) biçimlendirme özniteliklerini kullanarak çizer. |
| [draw_string(s, font, brush, point)](#draw_string_s_font_brush_point_136) | Belirtilen metin dizesini belirtilen konumda belirtilen [Brush](/imaging/python-net/aspose.imaging/brush/) ve [Font](/imaging/python-net/aspose.imaging/font/) nesneleriyle çizer. |
| [draw_string(s, font, brush, point, format)](#draw_string_s_font_brush_point_format_137) | Belirtilen metin dizesini belirtilen konumda belirtilen [Brush](/imaging/python-net/aspose.imaging/brush/) ve [Font](/imaging/python-net/aspose.imaging/font/) nesneleriyle, belirtilen [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) biçimlendirme özniteliklerini kullanarak çizer. |
| [draw_string(s, font, brush, x, y)](#draw_string_s_font_brush_x_y_138) | Belirtilen metin dizesini belirtilen konumda belirtilen [Brush](/imaging/python-net/aspose.imaging/brush/) ve [Font](/imaging/python-net/aspose.imaging/font/) nesneleriyle çizer. |
| [draw_string(s, font, brush, x, y, format)](#draw_string_s_font_brush_x_y_format_139) | Belirtilen metin dizesini belirtilen konumda belirtilen [Brush](/imaging/python-net/aspose.imaging/brush/) ve [Font](/imaging/python-net/aspose.imaging/font/) nesneleriyle, belirtilen [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) biçimlendirme özniteliklerini kullanarak çizer. |
| [draw_string_at_point_f(s, font, brush, point)](#draw_string_at_point_f_s_font_brush_point_140) | Belirtilen metin dizesini belirtilen konumda belirtilen [Brush](/imaging/python-net/aspose.imaging/brush/) ve [Font](/imaging/python-net/aspose.imaging/font/) nesneleriyle çizer. |
| [draw_string_at_point_f_format(s, font, brush, point, format)](#draw_string_at_point_f_format_s_font_brush_point_format_141) | Belirtilen metin dizesini belirtilen konumda belirtilen [Brush](/imaging/python-net/aspose.imaging/brush/) ve [Font](/imaging/python-net/aspose.imaging/font/) nesneleriyle, belirtilen [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) biçimlendirme özniteliklerini kullanarak çizer. |
| [draw_string_at_xy(s, font, brush, x, y)](#draw_string_at_xy_s_font_brush_x_y_142) | Belirtilen metin dizesini belirtilen konumda belirtilen [Brush](/imaging/python-net/aspose.imaging/brush/) ve [Font](/imaging/python-net/aspose.imaging/font/) nesneleriyle çizer. |
| [draw_string_in_rect(s, font, brush, layout_rectangle)](#draw_string_in_rect_s_font_brush_layout_rectangle_143) | Belirtilen metin dizesini belirtilen dikdörtgende belirtilen [Brush](/imaging/python-net/aspose.imaging/brush/) ve [Font](/imaging/python-net/aspose.imaging/font/) nesneleriyle çizer. |
| [draw_string_in_rect_f(s, font, brush, layout_rectangle, format)](#draw_string_in_rect_f_s_font_brush_layout_rectangle_format_144) | Belirtilen metin dizesini belirtilen dikdörtgende belirtilen [Brush](/imaging/python-net/aspose.imaging/brush/) ve [Font](/imaging/python-net/aspose.imaging/font/) nesneleriyle, belirtilen [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) biçimlendirme özniteliklerini kullanarak çizer. |
| end_update() | BeginUpdate çağrıldıktan sonra başlatılan grafik işlemlerinin önbelleğe alınmasını tamamlar. Önceki grafik işlemleri bu yöntem çağrıldığında bir kerede uygulanacaktır. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_145) | Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini doldurur. Bu yöntem varsayılan 0,5 gerilim ve [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) doldurma kipini kullanır. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_146) | Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini doldurur. Bu yöntem varsayılan 0,5 gerilim ve [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) doldurma kipini kullanır. |
| [fill_closed_curve(brush, points, fill_mode)](#fill_closed_curve_brush_points_fill_mode_147) | Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini belirtilen doldurma kipini kullanarak doldurur. Bu yöntem varsayılan 0,5 gerilim kullanır. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_148) | Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini belirtilen doldurma kipini kullanarak doldurur. Bu yöntem varsayılan 0,5 gerilim kullanır. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_149) | Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini belirtilen doldurma kipi ve gerilimi kullanarak doldurur. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_150) | Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini belirtilen doldurma kipi ve gerilimi kullanarak doldurur. |
| [fill_closed_curve_by_point(brush, points)](#fill_closed_curve_by_point_brush_points_151) | Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini doldurur. Bu yöntem varsayılan 0,5 gerilim ve [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) doldurma kipini kullanır. |
| [fill_closed_curve_by_point_f(brush, points)](#fill_closed_curve_by_point_f_brush_points_152) | Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini doldurur. Bu yöntem varsayılan 0,5 gerilim ve [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) doldurma kipini kullanır. |
| fill_closed_curve_by_point_f_fill_mode(brush, points, fillmode) |  |
| [fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension)](#fill_closed_curve_by_point_f_fill_mode_tension_brush_points_fillmode_tension_153) | Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini belirtilen doldurma kipi ve gerilimi kullanarak doldurur. |
| [fill_closed_curve_by_point_fill_mode(brush, points, fillmode)](#fill_closed_curve_by_point_fill_mode_brush_points_fillmode_154) | Bir dizi [Point](/imaging/python-net/aspose.imaging/point/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini belirtilen doldurma kipini kullanarak doldurur. Bu yöntem varsayılan 0,5 gerilim kullanır. |
| [fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension)](#fill_closed_curve_by_point_fill_mode_tension_brush_points_fillmode_tension_155) | Bir dizi [Point](/imaging/python-net/aspose.imaging/point/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini belirtilen doldurma kipi ve gerilimi kullanarak doldurur. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_156) | Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı tarafından belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_157) | Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı tarafından belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_158) | Koordinat çifti, genişlik ve yükseklik ile belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_159) | Koordinat çifti, genişlik ve yükseklik ile belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur. |
| [fill_ellipse_at_xywh(brush, x, y, width, height)](#fill_ellipse_at_xywh_brush_x_y_width_height_160) | Koordinat çifti, genişlik ve yükseklik ile belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur. |
| [fill_ellipse_at_xywhf(brush, x, y, width, height)](#fill_ellipse_at_xywhf_brush_x_y_width_height_161) | Koordinat çifti, genişlik ve yükseklik ile belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur. |
| [fill_ellipse_in_rect(brush, rect)](#fill_ellipse_in_rect_brush_rect_162) | Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı tarafından belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur. |
| [fill_ellipse_in_rect_f(brush, rect)](#fill_ellipse_in_rect_f_brush_rect_163) | Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı tarafından belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur. |
| [fill_path(brush, path)](#fill_path_brush_path_164) | Bir [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) nesnesinin içini doldurur. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_165) | Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ve iki radyal çizgiyle belirtilen elips tarafından tanımlanan bir dilim bölümünün içini doldurur. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_166) | Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ve iki radyal çizgiyle belirtilen elips tarafından tanımlanan bir dilim bölümünün içini doldurur. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_167) | Koordinat çifti, genişlik, yükseklik ve iki radyal çizgiyle belirtilen elips tarafından tanımlanan bir dilim bölümünün içini doldurur. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_168) | Koordinat çifti, genişlik, yükseklik ve iki radyal çizgiyle belirtilen elips tarafından tanımlanan bir dilim bölümünün içini doldurur. |
| [fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_at_xy_brush_x_y_width_height_start_angle_sweep_angle_169) | Koordinat çifti, genişlik, yükseklik ve iki radyal çizgiyle belirtilen elips tarafından tanımlanan bir dilim bölümünün içini doldurur. |
| [fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_at_xyf_brush_x_y_width_height_start_angle_sweep_angle_170) | Koordinat çifti, genişlik, yükseklik ve iki radyal çizgiyle belirtilen elips tarafından tanımlanan bir dilim bölümünün içini doldurur. |
| [fill_pie_in_rect(brush, rect, start_angle, sweep_angle)](#fill_pie_in_rect_brush_rect_start_angle_sweep_angle_171) | Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ve iki radyal çizgiyle belirtilen elips tarafından tanımlanan bir dilim bölümünün içini doldurur. |
| [fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle)](#fill_pie_in_rect_f_brush_rect_start_angle_sweep_angle_172) | Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ve iki radyal çizgiyle belirtilen elips tarafından tanımlanan bir dilim bölümünün içini doldurur. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_173) | Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ve [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) ile belirtilen noktalarla tanımlanan bir çokgenin içini doldurur. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_174) | Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ve [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) ile belirtilen noktalarla tanımlanan bir çokgenin içini doldurur. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_175) | Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından belirtilen noktalarla tanımlanan bir çokgenin içini belirtilen doldurma kipini kullanarak doldurur. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_176) | Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından belirtilen noktalarla tanımlanan bir çokgenin içini belirtilen doldurma kipini kullanarak doldurur. |
| [fill_polygon_by_point(brush, points)](#fill_polygon_by_point_brush_points_177) | Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ve [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) ile belirtilen noktalarla tanımlanan bir çokgenin içini doldurur. |
| [fill_polygon_by_point_f(brush, points)](#fill_polygon_by_point_f_brush_points_178) | Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ve [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) ile belirtilen noktalarla tanımlanan bir çokgenin içini doldurur. |
| [fill_polygon_by_point_f_fill_mode(brush, points, fill_mode)](#fill_polygon_by_point_f_fill_mode_brush_points_fill_mode_179) | Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından belirtilen noktalarla tanımlanan bir çokgenin içini belirtilen doldurma kipini kullanarak doldurur. |
| [fill_polygon_by_point_fill_mode(brush, points, fill_mode)](#fill_polygon_by_point_fill_mode_brush_points_fill_mode_180) | Bir dizi [Point](/imaging/python-net/aspose.imaging/point/) yapısı tarafından belirtilen noktalarla tanımlanan bir çokgenin içini belirtilen doldurma kipini kullanarak doldurur. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_181) | Bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısı tarafından belirtilen bir dikdörtgenin içini doldurur. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_182) | Bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısı tarafından belirtilen bir dikdörtgenin içini doldurur. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_183) | Koordinat çifti, genişlik ve yükseklik ile belirtilen bir dikdörtgenin içini doldurur. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_184) | Koordinat çifti, genişlik ve yükseklik ile belirtilen bir dikdörtgenin içini doldurur. |
| [fill_rectangle_f(brush, rect)](#fill_rectangle_f_brush_rect_185) | Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı tarafından belirtilen bir dikdörtgenin içini doldurur. |
| [fill_rectangle_f_with_brush(brush, x, y, width, height)](#fill_rectangle_f_with_brush_brush_x_y_width_height_186) | Koordinat çifti, genişlik ve yükseklik ile belirtilen bir dikdörtgenin içini doldurur. |
| [fill_rectangle_with_brush(brush, x, y, width, height)](#fill_rectangle_with_brush_brush_x_y_width_height_187) | Koordinat çifti, genişlik ve yükseklik ile belirtilen bir dikdörtgenin içini doldurur. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_188) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapılarıyla belirtilen bir dizi dikdörtgenin içlerini doldurur. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_189) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapılarıyla belirtilen bir dizi dikdörtgenin içlerini doldurur. |
| [fill_rectangles_f(brush, rects)](#fill_rectangles_f_brush_rects_190) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapılarıyla belirtilen bir dizi dikdörtgenin içlerini doldurur. |
| [fill_region(brush, region)](#fill_region_brush_region_191) | Bir [Region](/imaging/python-net/aspose.imaging/region/) içini doldurur. |
| [measure_string(text, font, layout_area, string_format)](#measure_string_text_font_layout_area_string_format_192) | Belirtilen metin dizesini belirtilen parametrelerle ölçer |
| [multiply_transform(matrix)](#multiply_transform_matrix_193) | Bu [Graphics](/imaging/python-net/aspose.imaging/graphics/) öğesinin yerel geometrik dönüşümünü temsil eden [Matrix](/imaging/python-net/aspose.imaging/matrix/) öğesini, belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) öğesiyle çarpar ve belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) öğesini ön ekleyerek çarpar. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_194) | Bu [Graphics](/imaging/python-net/aspose.imaging/graphics/) öğesinin yerel geometrik dönüşümünü temsil eden [Matrix](/imaging/python-net/aspose.imaging/matrix/) öğesini, belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) öğesiyle belirtilen sırada çarpar. |
| reset_transform() | [Graphics.transform](/imaging/python-net/aspose.imaging/graphics/) özelliğini birim matrisine sıfırlar. |
| [rotate_transform(angle)](#rotate_transform_angle_195) | Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem döndürmeyi dönüşüme ön ekler. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_196) | Yerel geometrik dönüşümü belirtilen miktarda, belirtilen sırada döndürür. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_197) | Yerel geometrik dönüşümü belirtilen değerlerle ölçeklendirir. Bu yöntem ölçekleme matrisini dönüşüme ön ekler. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_198) | Yerel geometrik dönüşümü belirtilen değerlerle, belirtilen sırada ölçeklendirir. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_199) | Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. Bu yöntem çeviriyi dönüşüme ön ekler. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_200) | Yerel geometrik dönüşümü belirtilen boyutlarla, belirtilen sırada çevirir. |


### Constructor: Graphics(source_image) {#Graphics_source_image_1}


```
 Graphics(source_image) 
```

Yeni bir [Graphics](/imaging/python-net/aspose.imaging/graphics/) sınıfı başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Kaynak görüntü. |

### Method: clear(color) {#clear_color_1}


```
 clear(color) 
```

Belirtilen rengi kullanarak grafik yüzeyini temizler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Grafik yüzeyini temizlemek için kullanılan renk. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...

**[Example # 2](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_2}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ile belirtilen elipsin bir kısmını temsil eden bir yay çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) yayının renk, genişlik ve stilini belirler. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) elipsin sınırlarını tanımlayan yapı. |
| start_angle | float | x ekseninden yay başlangıç noktasına doğru saat yönünde ölçülen açı (derece). |
| sweep_angle | float | _startAngle_ parametresinden yay son noktasına doğru saat yönünde ölçülen açı (derece). |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_3}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ile belirtilen elipsin bir kısmını temsil eden bir yay çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) yayının renk, genişlik ve stilini belirler. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) elipsin sınırlarını tanımlayan yapı. |
| start_angle | float | x ekseninden yay başlangıç noktasına doğru saat yönünde ölçülen açı (derece). |
| sweep_angle | float | _startAngle_ parametresinden yay son noktasına doğru saat yönünde ölçülen açı (derece). |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Koordinat çifti, genişlik ve yükseklik ile belirtilen elipsin bir kısmını temsil eden bir yay çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) yayının renk, genişlik ve stilini belirler. |
| x | float | Elipsi tanımlayan dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Elipsi tanımlayan dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Elipsi tanımlayan dikdörtgenin genişliği. |
| height | float | Elipsi tanımlayan dikdörtgenin yüksekliği. |
| start_angle | float | x ekseninden yay başlangıç noktasına doğru saat yönünde ölçülen açı (derece). |
| sweep_angle | float | _startAngle_ parametresinden yay son noktasına doğru saat yönünde ölçülen açı (derece). |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Koordinat çifti, genişlik ve yükseklik ile belirtilen elipsin bir kısmını temsil eden bir yay çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) yayının renk, genişlik ve stilini belirler. |
| x | int | Elipsi tanımlayan dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Elipsi tanımlayan dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Elipsi tanımlayan dikdörtgenin genişliği. |
| height | int | Elipsi tanımlayan dikdörtgenin yüksekliği. |
| start_angle | int | x ekseninden yay başlangıç noktasına doğru saat yönünde ölçülen açı (derece). |
| sweep_angle | int | _startAngle_ parametresinden yay son noktasına doğru saat yönünde ölçülen açı (derece). |

### Method: draw_arc_in_rect(pen, rect, start_angle, sweep_angle) {#draw_arc_in_rect_pen_rect_start_angle_sweep_angle_6}


```
 draw_arc_in_rect(pen, rect, start_angle, sweep_angle) 
```

Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ile belirtilen elipsin bir kısmını temsil eden bir yay çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) yayının renk, genişlik ve stilini belirler. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) elipsin sınırlarını tanımlayan yapı. |
| start_angle | float | x ekseninden yay başlangıç noktasına doğru saat yönünde ölçülen açı (derece). |
| sweep_angle | float | _startAngle_ parametresinden yay son noktasına doğru saat yönünde ölçülen açı (derece). |

### Method: draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle) {#draw_arc_in_rect_f_pen_rect_start_angle_sweep_angle_7}


```
 draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle) 
```

Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ile belirtilen elipsin bir kısmını temsil eden bir yay çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) yayının renk, genişlik ve stilini belirler. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) elipsin sınırlarını tanımlayan yapı. |
| start_angle | float | x ekseninden yay başlangıç noktasına doğru saat yönünde ölçülen açı (derece). |
| sweep_angle | float | _startAngle_ parametresinden yay son noktasına doğru saat yönünde ölçülen açı (derece). |

### Method: draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_xy_pen_x_y_width_height_start_angle_sweep_angle_8}


```
 draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle) 
```

Koordinat çifti, genişlik ve yükseklik ile belirtilen elipsin bir kısmını temsil eden bir yay çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) yayının renk, genişlik ve stilini belirler. |
| x | int | Elipsi tanımlayan dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Elipsi tanımlayan dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Elipsi tanımlayan dikdörtgenin genişliği. |
| height | int | Elipsi tanımlayan dikdörtgenin yüksekliği. |
| start_angle | int | x ekseninden yay başlangıç noktasına doğru saat yönünde ölçülen açı (derece). |
| sweep_angle | int | _startAngle_ parametresinden yay son noktasına doğru saat yönünde ölçülen açı (derece). |

### Method: draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_xyf_pen_x_y_width_height_start_angle_sweep_angle_9}


```
 draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle) 
```

Koordinat çifti, genişlik ve yükseklik ile belirtilen elipsin bir kısmını temsil eden bir yay çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) yayının renk, genişlik ve stilini belirler. |
| x | float | Elipsi tanımlayan dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Elipsi tanımlayan dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Elipsi tanımlayan dikdörtgenin genişliği. |
| height | float | Elipsi tanımlayan dikdörtgenin yüksekliği. |
| start_angle | float | x ekseninden yay başlangıç noktasına doğru saat yönünde ölçülen açı (derece). |
| sweep_angle | float | _startAngle_ parametresinden yay son noktasına doğru saat yönünde ölçülen açı (derece). |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_10}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Dört [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ile tanımlanan bir Bézier spline çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) eğrinin renk, genişlik ve stilini belirler. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) eğrinin başlangıç noktasını temsil eden yapı. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) eğri için birinci kontrol noktasını temsil eden yapı. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) eğri için ikinci kontrol noktasını temsil eden yapı. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) eğrinin bitiş noktasını temsil eden yapı. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_11}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Dört [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ile tanımlanan bir Bézier spline çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) eğrinin renk, genişlik ve stilini belirler. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) eğrinin başlangıç noktasını temsil eden yapı. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) eğri için birinci kontrol noktasını temsil eden yapı. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) eğri için ikinci kontrol noktasını temsil eden yapı. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) eğrinin bitiş noktasını temsil eden yapı. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) {#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_12}


```
 draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) 
```

Noktaları temsil eden dört sıralı koordinat çifti ile tanımlanan bir Bézier spline çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) eğrinin renk, genişlik ve stilini belirler. |
| x1 | float | Eğri başlangıç noktasının x koordinatı. |
| y1 | float | Eğri başlangıç noktasının y koordinatı. |
| x2 | float | Eğri birinci kontrol noktasının x koordinatı. |
| y2 | float | Eğrinin ilk kontrol noktasının y koordinatı. |
| x3 | float | Eğrinin ikinci kontrol noktasının x koordinatı. |
| y3 | float | Eğrinin ikinci kontrol noktasının y koordinatı. |
| x4 | float | Eğrinin bitiş noktasının x koordinatı. |
| y4 | float | Eğrinin bitiş noktasının y koordinatı. |

### Method: draw_bezier_by_points(pen, pt1, pt2, pt3, pt4) {#draw_bezier_by_points_pen_pt1_pt2_pt3_pt4_13}


```
 draw_bezier_by_points(pen, pt1, pt2, pt3, pt4) 
```

Dört [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ile tanımlanan bir Bézier spline çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) eğrinin renk, genişlik ve stilini belirler. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) eğrinin başlangıç noktasını temsil eden yapı. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) eğri için birinci kontrol noktasını temsil eden yapı. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) eğri için ikinci kontrol noktasını temsil eden yapı. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) eğrinin bitiş noktasını temsil eden yapı. |

### Method: draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4) {#draw_bezier_by_points_f_pen_pt1_pt2_pt3_pt4_14}


```
 draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4) 
```

Dört [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ile tanımlanan bir Bézier spline çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) eğrinin renk, genişlik ve stilini belirler. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) eğrinin başlangıç noktasını temsil eden yapı. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) eğri için birinci kontrol noktasını temsil eden yapı. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) eğri için ikinci kontrol noktasını temsil eden yapı. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) eğrinin bitiş noktasını temsil eden yapı. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_15}


```
 draw_beziers(pen, points) 
```

Bir dizi [Point](/imaging/python-net/aspose.imaging/point/) yapısından bir dizi Bézier spline çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) eğrinin renk, genişlik ve stilini belirler. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Eğriyi belirleyen noktaları temsil eden [Point](/imaging/python-net/aspose.imaging/point/) yapıların dizisi. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_16}


```
 draw_beziers(pen, points) 
```

Bir dizi [Point](/imaging/python-net/aspose.imaging/point/) yapısından bir dizi Bézier spline çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) eğrinin renk, genişlik ve stilini belirler. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Eğriyi belirleyen noktaları temsil eden [Point](/imaging/python-net/aspose.imaging/point/) yapıların dizisi. |

### Method: draw_beziers_by_pt_array(pen, points) {#draw_beziers_by_pt_array_pen_points_17}


```
 draw_beziers_by_pt_array(pen, points) 
```

Bir dizi [Point](/imaging/python-net/aspose.imaging/point/) yapısından bir dizi Bézier spline çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) eğrinin renk, genişlik ve stilini belirler. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Eğriyi belirleyen noktaları temsil eden [Point](/imaging/python-net/aspose.imaging/point/) yapıların dizisi. |

### Method: draw_beziers_by_pt_array_f(pen, points) {#draw_beziers_by_pt_array_f_pen_points_18}


```
 draw_beziers_by_pt_array_f(pen, points) 
```

Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısından bir dizi Bézier spline çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) eğrinin renk, genişlik ve stilini belirler. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Eğriyi belirleyen noktaları temsil eden [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıların dizisi. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_19}


```
 draw_closed_curve(pen, points) 
```

Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ile tanımlanan kapalı bir kardinal spline çizer. Bu yöntem varsayılan 0.5 gerilim ve [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) doldurma modunu kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Spline'ı tanımlayan [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıların dizisi. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_20}


```
 draw_closed_curve(pen, points) 
```

Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ile tanımlanan kapalı bir kardinal spline çizer. Bu yöntem varsayılan 0.5 gerilim ve [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) doldurma modunu kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Spline'ı tanımlayan [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıların dizisi. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_21}


```
 draw_closed_curve(pen, points, tension) 
```

Belirtilen bir gerilim kullanarak bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ile tanımlanan kapalı bir kardinal spline çizer. Bu yöntem varsayılan [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) doldurma modunu kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Spline'ı tanımlayan [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıların dizisi. |
| gerilim | float | Eğrinin gerilimini belirten 0.0F veya daha büyük bir değer. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_22}


```
 draw_closed_curve(pen, points, tension) 
```

Belirtilen bir gerilim kullanarak bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ile tanımlanan kapalı bir kardinal spline çizer. Bu yöntem varsayılan [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) doldurma modunu kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Spline'ı tanımlayan [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıların dizisi. |
| gerilim | float | Eğrinin gerilimini belirten 0.0F veya daha büyük bir değer. |

### Method: draw_closed_curve_by_points(pen, points) {#draw_closed_curve_by_points_pen_points_23}


```
 draw_closed_curve_by_points(pen, points) 
```

Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ile tanımlanan kapalı bir kardinal spline çizer. Bu yöntem varsayılan 0.5 gerilim ve [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) doldurma modunu kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Spline'ı tanımlayan [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıların dizisi. |

### Method: draw_closed_curve_by_points_f(pen, points) {#draw_closed_curve_by_points_f_pen_points_24}


```
 draw_closed_curve_by_points_f(pen, points) 
```

Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ile tanımlanan kapalı bir kardinal spline çizer. Bu yöntem varsayılan 0.5 gerilim ve [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) doldurma modunu kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Spline'ı tanımlayan [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıların dizisi. |

### Method: draw_closed_curve_by_points_f_tension(pen, points, tension) {#draw_closed_curve_by_points_f_tension_pen_points_tension_25}


```
 draw_closed_curve_by_points_f_tension(pen, points, tension) 
```

Belirtilen bir gerilim kullanarak bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ile tanımlanan kapalı bir kardinal spline çizer. Bu yöntem varsayılan [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) doldurma modunu kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Spline'ı tanımlayan [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıların dizisi. |
| gerilim | float | Eğrinin gerilimini belirten 0.0F veya daha büyük bir değer. |

### Method: draw_closed_curve_by_points_tension(pen, points, tension) {#draw_closed_curve_by_points_tension_pen_points_tension_26}


```
 draw_closed_curve_by_points_tension(pen, points, tension) 
```

Belirtilen bir gerilim kullanarak bir dizi [Point](/imaging/python-net/aspose.imaging/point/) yapısı ile tanımlanan kapalı bir kardinal spline çizer. Bu yöntem varsayılan [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) doldurma modunu kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Spline'ı tanımlayan [Point](/imaging/python-net/aspose.imaging/point/) yapıların dizisi. |
| gerilim | float | Eğrinin gerilimini belirten 0.0F veya daha büyük bir değer. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_27}


```
 draw_curve(pen, points) 
```

Belirtilen bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı üzerinden bir kardinal spline çizer. Bu yöntem varsayılan 0.5 gerilimi kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Spline'ı tanımlayan [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıların dizisi. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_curve(pen, points) {#draw_curve_pen_points_28}


```
 draw_curve(pen, points) 
```

Belirtilen bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı üzerinden bir kardinal spline çizer. Bu yöntem varsayılan 0.5 gerilimi kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Spline'ı tanımlayan [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıların dizisi. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_curve(pen, points, offset, number_of_segments) {#draw_curve_pen_points_offset_number_of_segments_29}


```
 draw_curve(pen, points, offset, number_of_segments) 
```

Belirtilen bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı üzerinden bir kardinal spline çizer. Çizim, dizinin başından bir offset ile başlar.<br/>            Bu yöntem varsayılan 0.5 gerilim kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Spline'ı tanımlayan [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıların dizisi. |
| offset | int | _points_ parametresinin dizi içindeki ilk elemanından eğrinin başlangıç noktasına olan offset. |
| number_of_segments | int | Eğriye dahil edilecek, başlangıç noktasından sonraki segment sayısı. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_30}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Belirtilen bir gerilim kullanarak, belirtilen bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı üzerinden bir kardinal spline çizer. Çizim, dizinin başından bir offset ile başlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Spline'ı tanımlayan [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıların dizisi. |
| offset | int | _points_ parametresinin dizi içindeki ilk elemanından eğrinin başlangıç noktasına olan offset. |
| number_of_segments | int | Eğriye dahil edilecek, başlangıç noktasından sonraki segment sayısı. |
| gerilim | float | Eğrinin gerilimini belirten 0.0F veya daha büyük bir değer. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_31}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Belirtilen bir gerilim kullanarak, belirtilen bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı üzerinden bir kardinal spline çizer. Çizim, dizinin başından bir offset ile başlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Spline'ı tanımlayan [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıların dizisi. |
| offset | int | _points_ parametresinin dizi içindeki ilk elemanından eğrinin başlangıç noktasına olan offset. |
| number_of_segments | int | Eğriye dahil edilecek, başlangıç noktasından sonraki segment sayısı. |
| gerilim | float | Eğrinin gerilimini belirten 0.0F veya daha büyük bir değer. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_32}


```
 draw_curve(pen, points, tension) 
```

Belirtilen bir gerilim kullanarak, belirtilen bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı üzerinden bir kardinal spline çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Eğriyi tanımlayan noktaları temsil eden [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıların dizisi. |
| gerilim | float | Eğrinin gerilimini belirten 0.0F veya daha büyük bir değer. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_33}


```
 draw_curve(pen, points, tension) 
```

Belirtilen bir gerilim kullanarak, belirtilen bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı üzerinden bir kardinal spline çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Eğriyi tanımlayan noktaları temsil eden [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıların dizisi. |
| gerilim | float | Eğrinin gerilimini belirten 0.0F veya daha büyük bir değer. |

### Method: draw_curve_by_point_fs(pen, points) {#draw_curve_by_point_fs_pen_points_34}


```
 draw_curve_by_point_fs(pen, points) 
```

Belirtilen bir dizi [Point](/imaging/python-net/aspose.imaging/point/) yapısı üzerinden bir kardinal spline çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Spline'ı tanımlayan [Point](/imaging/python-net/aspose.imaging/point/) yapıların dizisi. |

### Method: draw_curve_by_point_fs_tension(pen, points, tension) {#draw_curve_by_point_fs_tension_pen_points_tension_35}


```
 draw_curve_by_point_fs_tension(pen, points, tension) 
```

Belirtilen bir gerilim kullanarak, belirtilen bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı üzerinden bir kardinal spline çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Eğriyi tanımlayan noktaları temsil eden [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıların dizisi. |
| gerilim | float | Eğrinin gerilimini belirten 0.0F veya daha büyük bir değer. |

### Method: draw_curve_by_points(pen, points) {#draw_curve_by_points_pen_points_36}


```
 draw_curve_by_points(pen, points) 
```

Belirtilen bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı üzerinden bir kardinal spline çizer. Bu yöntem varsayılan 0.5 gerilimi kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Spline'ı tanımlayan [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıların dizisi. |

### Method: draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) {#draw_curve_by_points_f_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_37}


```
 draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) 
```

Belirtilen bir gerilim kullanarak, belirtilen bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı üzerinden bir kardinal spline çizer. Çizim, dizinin başından bir offset ile başlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Spline'ı tanımlayan [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıların dizisi. |
| offset | int | _points_ parametresinin dizi içindeki ilk elemanından eğrinin başlangıç noktasına olan offset. |
| number_of_segments | int | Eğriye dahil edilecek, başlangıç noktasından sonraki segment sayısı. |
| gerilim | float | Eğrinin gerilimini belirten 0.0F veya daha büyük bir değer. |

### Method: draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) {#draw_curve_by_points_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_38}


```
 draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) 
```

Belirtilen bir gerilim kullanarak, belirtilen bir dizi [Point](/imaging/python-net/aspose.imaging/point/) yapısı üzerinden bir kardinal spline çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Spline'ı tanımlayan [Point](/imaging/python-net/aspose.imaging/point/) yapıların dizisi. |
| offset | int | _points_ parametresinin dizi içindeki ilk elemanından eğrinin başlangıç noktasına olan offset. |
| number_of_segments | int | Eğriye dahil edilecek, başlangıç noktasından sonraki segment sayısı. |
| gerilim | float | Eğrinin gerilimini belirten 0.0F veya daha büyük bir değer. |

### Method: draw_curve_by_points_tension(pen, points, tension) {#draw_curve_by_points_tension_pen_points_tension_39}


```
 draw_curve_by_points_tension(pen, points, tension) 
```

Belirtilen bir gerilim kullanarak, belirtilen bir dizi [Point](/imaging/python-net/aspose.imaging/point/) yapısı üzerinden bir kardinal spline çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Spline'ı tanımlayan [Point](/imaging/python-net/aspose.imaging/point/) yapıların dizisi. |
| gerilim | float | Eğrinin gerilimini belirten 0.0F veya daha büyük bir değer. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_40}


```
 draw_ellipse(pen, rect) 
```

Sınırlayıcı bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) tarafından tanımlanan bir elips çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Elipsin renk, genişlik ve stilini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) elipsin sınırlarını tanımlayan yapı. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_41}


```
 draw_ellipse(pen, rect) 
```

Sınırlayıcı bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) tarafından tanımlanan bir elips çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Elipsin renk, genişlik ve stilini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) elipsin sınırlarını tanımlayan yapı. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_42}


```
 draw_ellipse(pen, x, y, width, height) 
```

Koordinat çifti, yükseklik ve genişlik ile belirtilen sınırlayıcı bir dikdörtgen tarafından tanımlanan bir elips çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Elipsin renk, genişlik ve stilini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| x | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_43}


```
 draw_ellipse(pen, x, y, width, height) 
```

Koordinat çifti, yükseklik ve genişlik ile belirtilen sınırlayıcı bir dikdörtgen tarafından tanımlanan bir elips çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Elipsin renk, genişlik ve stilini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| x | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |

### Method: draw_ellipse_by_xy(pen, x, y, width, height) {#draw_ellipse_by_xy_pen_x_y_width_height_44}


```
 draw_ellipse_by_xy(pen, x, y, width, height) 
```

Koordinat çifti, yükseklik ve genişlik ile belirtilen sınırlayıcı bir dikdörtgen tarafından tanımlanan bir elips çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Elipsin renk, genişlik ve stilini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| x | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |

### Method: draw_ellipse_by_xyf(pen, x, y, width, height) {#draw_ellipse_by_xyf_pen_x_y_width_height_45}


```
 draw_ellipse_by_xyf(pen, x, y, width, height) 
```

Koordinat çifti, yükseklik ve genişlik ile belirtilen sınırlayıcı bir dikdörtgen tarafından tanımlanan bir elips çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Elipsin renk, genişlik ve stilini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| x | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |

### Method: draw_ellipse_f(pen, rect) {#draw_ellipse_f_pen_rect_46}


```
 draw_ellipse_f(pen, rect) 
```

Sınırlayıcı bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) tarafından tanımlanan bir elips çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Elipsin renk, genişlik ve stilini belirleyen [Pen](/imaging/python-net/aspose.imaging/pen/). |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) elipsin sınırlarını tanımlayan yapı. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_47}


```
 draw_image(image, dest_points) 
```

Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizilecek görüntü. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Paralelkenarı tanımlayan üç PointF yapısından oluşan dizi. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_48}


```
 draw_image(image, dest_points) 
```

Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizilecek görüntü. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Paralelkenarı tanımlayan üç PointF yapısından oluşan dizi. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_49}


```
 draw_image(image, dest_points, src_rect) 
```

Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizilecek görüntü. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Paralelkenarı tanımlayan üç PointF yapısından oluşan dizi. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Kaynak dikdörtgen. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_50}


```
 draw_image(image, dest_points, src_rect) 
```

Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizilecek görüntü. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Paralelkenarı tanımlayan üç PointF yapısından oluşan dizi. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Kaynak dikdörtgen. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_51}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizilecek görüntü. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Paralelkenarı tanımlayan üç PointF yapısından oluşan dizi. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Kaynak dikdörtgen. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Ölçü birimleri. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_52}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizilecek görüntü. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Paralelkenarı tanımlayan üç PointF yapısından oluşan dizi. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Kaynak dikdörtgen. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Ölçü birimleri. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_53}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizilecek görüntü. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Paralelkenarı tanımlayan üç PointF yapısından oluşan dizi. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Kaynak dikdörtgen. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Ölçü birimleri. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Görüntü öznitelikleri. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_54}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizilecek görüntü. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Paralelkenarı tanımlayan üç PointF yapısından oluşan dizi. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Kaynak dikdörtgen. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Ölçü birimleri. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Görüntü öznitelikleri. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_55}


```
 draw_image(source_image, point) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı, çizilen görüntünün sol üst köşesini temsil eder. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_56}


```
 draw_image(source_image, point) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı, çizilen görüntünün sol üst köşesini temsil eder. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_57}


```
 draw_image(source_image, rect) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı, çizilen görüntünün konumunu ve boyutunu belirler. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_58}


```
 draw_image(source_image, rect) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı, çizilen görüntünün konumunu ve boyutunu belirler. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_59}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Hedef dikdörtgen. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafik birimi. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_60}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Hedef dikdörtgen. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafik birimi. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_61}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Hedef dikdörtgen. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafik birimi. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Görüntü öznitelikleri. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_62}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Hedef dikdörtgen. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafik birimi. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Görüntü öznitelikleri. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_63}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Kaynak dikdörtgen. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Hedef dikdörtgen. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafik birimi. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_64}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Kaynak dikdörtgen. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Hedef dikdörtgen. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafik birimi. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_65}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Kaynak dikdörtgen. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Hedef dikdörtgen. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafik birimi. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Görüntü öznitelikleri. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_66}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Kaynak dikdörtgen. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Hedef dikdörtgen. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafik birimi. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Görüntü öznitelikleri. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_67}


```
 draw_image(source_image, x, y) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| x | float | Çizilen görüntünün sol üst köşesinin x koordinatı. |
| y | float | Çizilen görüntünün sol üst köşesinin y koordinatı. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_68}


```
 draw_image(source_image, x, y) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| x | int | Çizilen görüntünün sol üst köşesinin x koordinatı. |
| y | int | Çizilen görüntünün sol üst köşesinin y koordinatı. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_69}


```
 draw_image(source_image, x, y, width, height) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| x | float | Çizilen görüntünün sol üst köşesinin x koordinatı. |
| y | float | Çizilen görüntünün sol üst köşesinin y koordinatı. |
| width | float | Çizilen görüntünün genişliği. |
| height | float | Çizilen görüntünün yüksekliği. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_70}


```
 draw_image(source_image, x, y, width, height) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| x | int | Çizilen görüntünün sol üst köşesinin x koordinatı. |
| y | int | Çizilen görüntünün sol üst köşesinin y koordinatı. |
| width | int | Çizilen görüntünün genişliği. |
| height | int | Çizilen görüntünün yüksekliği. |

### Method: draw_image_at_point(source_image, point) {#draw_image_at_point_source_image_point_71}


```
 draw_image_at_point(source_image, point) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı, çizilen görüntünün sol üst köşesini temsil eder. |

### Method: draw_image_at_point_f(source_image, point) {#draw_image_at_point_f_source_image_point_72}


```
 draw_image_at_point_f(source_image, point) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı, çizilen görüntünün sol üst köşesini temsil eder. |

### Method: draw_image_at_xy(source_image, x, y) {#draw_image_at_xy_source_image_x_y_73}


```
 draw_image_at_xy(source_image, x, y) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| x | int | Çizilen görüntünün sol üst köşesinin x koordinatı. |
| y | int | Çizilen görüntünün sol üst köşesinin y koordinatı. |

### Method: draw_image_at_xyf(source_image, x, y) {#draw_image_at_xyf_source_image_x_y_74}


```
 draw_image_at_xyf(source_image, x, y) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| x | float | Çizilen görüntünün sol üst köşesinin x koordinatı. |
| y | float | Çizilen görüntünün sol üst köşesinin y koordinatı. |

### Method: draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit) {#draw_image_dest_point_f_src_rect_f_with_unit_image_dest_points_src_rect_src_unit_75}


```
 draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit) 
```

Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizilecek görüntü. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Paralelkenarı tanımlayan üç PointF yapısından oluşan dizi. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Kaynak dikdörtgen. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Ölçü birimleri. |

### Method: draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_dest_point_f_src_rect_f_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_76}


```
 draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) 
```

Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizilecek görüntü. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Paralelkenarı tanımlayan üç PointF yapısından oluşan dizi. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Kaynak dikdörtgen. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Ölçü birimleri. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Görüntü öznitelikleri. |

### Method: draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect) {#draw_image_dest_points_f_src_rect_f_image_dest_points_src_rect_77}


```
 draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect) 
```

Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizilecek görüntü. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Paralelkenarı tanımlayan üç PointF yapısından oluşan dizi. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Kaynak dikdörtgen. |

### Method: draw_image_dest_points_src_rect(image, dest_points, src_rect) {#draw_image_dest_points_src_rect_image_dest_points_src_rect_78}


```
 draw_image_dest_points_src_rect(image, dest_points, src_rect) 
```

Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizilecek görüntü. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Paralelkenarı tanımlayan üç PointF yapısından oluşan dizi. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Kaynak dikdörtgen. |

### Method: draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit) {#draw_image_dest_points_src_rect_with_unit_image_dest_points_src_rect_src_unit_79}


```
 draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit) 
```

Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizilecek görüntü. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Paralelkenarı tanımlayan üç PointF yapısından oluşan dizi. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Kaynak dikdörtgen. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Ölçü birimleri. |

### Method: draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_dest_points_src_rect_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_80}


```
 draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) 
```

Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizilecek görüntü. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Paralelkenarı tanımlayan üç PointF yapısından oluşan dizi. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Kaynak dikdörtgen. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Ölçü birimleri. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Görüntü öznitelikleri. |

### Method: draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_dest_rect_f_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_81}


```
 draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Çizim yapılacak hedef dikdörtgen. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafik birimi. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Görüntü öznitelikleri. |

### Method: draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_dest_rect_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_82}


```
 draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Hedef dikdörtgen. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafik birimi. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Görüntü öznitelikleri. |

### Method: draw_image_in_rect(source_image, x, y, width, height) {#draw_image_in_rect_source_image_x_y_width_height_83}


```
 draw_image_in_rect(source_image, x, y, width, height) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| x | int | Çizilen görüntünün sol üst köşesinin x koordinatı. |
| y | int | Çizilen görüntünün sol üst köşesinin y koordinatı. |
| width | int | Çizilen görüntünün genişliği. |
| height | int | Çizilen görüntünün yüksekliği. |

### Method: draw_image_in_rect_f(source_image, x, y, width, height) {#draw_image_in_rect_f_source_image_x_y_width_height_84}


```
 draw_image_in_rect_f(source_image, x, y, width, height) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| x | float | Çizilen görüntünün sol üst köşesinin x koordinatı. |
| y | float | Çizilen görüntünün sol üst köşesinin y koordinatı. |
| width | float | Çizilen görüntünün genişliği. |
| height | float | Çizilen görüntünün yüksekliği. |

### Method: draw_image_in_rectangle(source_image, rect) {#draw_image_in_rectangle_source_image_rect_85}


```
 draw_image_in_rectangle(source_image, rect) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısı, çizilen görüntünün konumunu ve boyutunu belirler. |

### Method: draw_image_points(image, dest_points) {#draw_image_points_image_dest_points_86}


```
 draw_image_points(image, dest_points) 
```

Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizilecek görüntü. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Paralelkenarı tanımlayan üç PointF yapısından oluşan dizi. |

### Method: draw_image_points_f(image, dest_points) {#draw_image_points_f_image_dest_points_87}


```
 draw_image_points_f(image, dest_points) 
```

Belirtilen _image_'in belirtilen bölümünü belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizilecek görüntü. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Paralelkenarı tanımlayan üç PointF yapısından oluşan dizi. |

### Method: draw_image_rectangle_f(source_image, rect) {#draw_image_rectangle_f_source_image_rect_88}


```
 draw_image_rectangle_f(source_image, rect) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı, çizilen görüntünün konumunu ve boyutunu belirler. |

### Method: draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_src_dest_rects_f_with_unit_source_image_rect_source_rect_destination_graphics_unit_89}


```
 draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Kaynak dikdörtgen. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Hedef dikdörtgen. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafik birimi. |

### Method: draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_src_dest_rects_with_unit_source_image_rect_source_rect_destination_graphics_unit_90}


```
 draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Kaynak dikdörtgen. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Hedef dikdörtgen. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafik birimi. |

### Method: draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_src_dst_rect_f_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_91}


```
 draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Kaynak dikdörtgen. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Hedef dikdörtgen. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Kullanılacak grafik birimi. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Kullanılacak görüntü öznitelikleri. |

### Method: draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_src_dst_rects_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_92}


```
 draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Kaynak dikdörtgen. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Hedef dikdörtgen. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafik birimi. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Görüntü öznitelikleri. |

### Method: draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit) {#draw_image_to_rect_f_with_unit_source_image_rect_destination_graphics_unit_93}


```
 draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Hedef dikdörtgen. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafik birimi. |

### Method: draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit) {#draw_image_to_rect_with_unit_source_image_rect_destination_graphics_unit_94}


```
 draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit) 
```

Belirtilen [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)'i belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Hedef dikdörtgen. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafik birimi. |

### Method: draw_image_unscaled(source_image, point) {#draw_image_unscaled_source_image_point_95}


```
 draw_image_unscaled(source_image, point) 
```

Belirtilen bir resmi, özgün fiziksel boyutunu kullanarak, belirtilen bir konumda çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) yapısı, çizilen görüntünün sol üst köşesini belirler. |

### Method: draw_image_unscaled(source_image, rect) {#draw_image_unscaled_source_image_rect_96}


```
 draw_image_unscaled(source_image, rect) 
```

Belirtilen bir resmi, özgün fiziksel boyutunu kullanarak, belirtilen bir konumda çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) çizilen görüntünün sol üst köşesini belirler. Dikdörtgenin X ve Y özellikleri sol üst köşeyi tanımlar. Genişlik ve Yükseklik özellikleri göz ardı edilir. |

### Method: draw_image_unscaled(source_image, x, y) {#draw_image_unscaled_source_image_x_y_97}


```
 draw_image_unscaled(source_image, x, y) 
```

Belirtilen resmi, özgün fiziksel boyutunu kullanarak, bir koordinat çiftiyle belirtilen konumda çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| x | int | Çizilen görüntünün sol üst köşesinin x koordinatı. |
| y | int | Çizilen görüntünün sol üst köşesinin y koordinatı. |

### Method: draw_image_unscaled(source_image, x, y, width, height) {#draw_image_unscaled_source_image_x_y_width_height_98}


```
 draw_image_unscaled(source_image, x, y, width, height) 
```

Belirtilen bir resmi, özgün fiziksel boyutunu kullanarak, belirtilen bir konumda çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| x | int | Çizilen görüntünün sol üst köşesinin x koordinatı. |
| y | int | Çizilen görüntünün sol üst köşesinin y koordinatı. |
| width | int | Parametre kullanılmaz. |
| height | int | Parametre kullanılmaz. |

### Method: draw_image_unscaled_and_clipped(source_image, rect) {#draw_image_unscaled_and_clipped_source_image_rect_99}


```
 draw_image_unscaled_and_clipped(source_image, rect) 
```

Belirtilen resmi ölçeklendirmeden çizer ve gerekirse, belirtilen dikdörtgene sığması için kırpar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Görüntünün çizileceği [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |

### Method: draw_image_unscaled_in_rectangle(source_image, rect) {#draw_image_unscaled_in_rectangle_source_image_rect_100}


```
 draw_image_unscaled_in_rectangle(source_image, rect) 
```

Belirtilen bir resmi, özgün fiziksel boyutunu kullanarak, belirtilen bir konumda çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) çizilen görüntünün sol üst köşesini belirler. Dikdörtgenin X ve Y özellikleri sol üst köşeyi tanımlar. Genişlik ve Yükseklik özellikleri göz ardı edilir. |

### Method: draw_image_unscaled_to_point(source_image, point) {#draw_image_unscaled_to_point_source_image_point_101}


```
 draw_image_unscaled_to_point(source_image, point) 
```

Belirtilen bir resmi, özgün fiziksel boyutunu kullanarak, belirtilen bir konumda çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Çizim için kullanılacak görüntü. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) yapısı, çizilen görüntünün sol üst köşesini belirler. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_102}


```
 draw_line(pen, point1, point2) 
```

İki [Point](/imaging/python-net/aspose.imaging/point/) yapısını birleştiren bir çizgi çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) çizginin rengini, genişliğini ve stilini belirler. |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) yapısı, bağlanacak ilk noktayı temsil eder. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) bağlanacak ikinci noktayı temsil eden yapı. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_103}


```
 draw_line(pen, point1, point2) 
```

İki [Point](/imaging/python-net/aspose.imaging/point/) yapısını birleştiren bir çizgi çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) çizginin rengini, genişliğini ve stilini belirler. |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [Point](/imaging/python-net/aspose.imaging/point/) yapısı, bağlanacak ilk noktayı temsil eder. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [Point](/imaging/python-net/aspose.imaging/point/) bağlanacak ikinci noktayı temsil eden yapı. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_104}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Koordinat çiftleriyle belirtilen iki noktayı birleştiren bir çizgi çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) çizginin rengini, genişliğini ve stilini belirler. |
| x1 | int | İlk noktanın x koordinatı. |
| y1 | int | İlk noktanın y koordinatı. |
| x2 | int | İkinci noktanın x koordinatı. |
| y2 | int | İkinci noktanın y koordinatı. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_105}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Koordinat çiftleriyle belirtilen iki noktayı birleştiren bir çizgi çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) çizginin rengini, genişliğini ve stilini belirler. |
| x1 | float | İlk noktanın x koordinatı. |
| y1 | float | İlk noktanın y koordinatı. |
| x2 | float | İkinci noktanın x koordinatı. |
| y2 | float | İkinci noktanın y koordinatı. |

### Method: draw_line_by_xy(pen, x1, y1, x2, y2) {#draw_line_by_xy_pen_x1_y1_x2_y2_106}


```
 draw_line_by_xy(pen, x1, y1, x2, y2) 
```

Koordinat çiftleriyle belirtilen iki noktayı birleştiren bir çizgi çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) çizginin rengini, genişliğini ve stilini belirler. |
| x1 | int | İlk noktanın x koordinatı. |
| y1 | int | İlk noktanın y koordinatı. |
| x2 | int | İkinci noktanın x koordinatı. |
| y2 | int | İkinci noktanın y koordinatı. |

### Method: draw_line_f_by_xy(pen, x1, y1, x2, y2) {#draw_line_f_by_xy_pen_x1_y1_x2_y2_107}


```
 draw_line_f_by_xy(pen, x1, y1, x2, y2) 
```

Koordinat çiftleriyle belirtilen iki noktayı birleştiren bir çizgi çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) çizginin rengini, genişliğini ve stilini belirler. |
| x1 | float | İlk noktanın x koordinatı. |
| y1 | float | İlk noktanın y koordinatı. |
| x2 | float | İkinci noktanın x koordinatı. |
| y2 | float | İkinci noktanın y koordinatı. |

### Method: draw_line_point_f(pen, point1, point2) {#draw_line_point_f_pen_point1_point2_108}


```
 draw_line_point_f(pen, point1, point2) 
```

İki [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısını birleştiren bir çizgi çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) çizginin rengini, genişliğini ve stilini belirler. |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) bağlanacak ilk noktayı temsil eden yapı. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) bağlanacak ikinci noktayı temsil eden yapı. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_109}


```
 draw_lines(pen, points) 
```

Bir dizi [Point](/imaging/python-net/aspose.imaging/point/) yapısını birleştiren bir dizi çizgi parçası çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) çizgi segmentlerinin renk, genişlik ve stilini belirler. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Bağlanacak noktaları temsil eden [Point](/imaging/python-net/aspose.imaging/point/) yapılarını içeren dizi. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_110}


```
 draw_lines(pen, points) 
```

Bir dizi [Point](/imaging/python-net/aspose.imaging/point/) yapısını birleştiren bir dizi çizgi parçası çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) çizgi segmentlerinin renk, genişlik ve stilini belirler. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Bağlanacak noktaları temsil eden [Point](/imaging/python-net/aspose.imaging/point/) yapılarını içeren dizi. |

### Method: draw_lines_f(pen, points) {#draw_lines_f_pen_points_111}


```
 draw_lines_f(pen, points) 
```

Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısını birleştiren bir dizi çizgi parçası çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) çizgi segmentlerinin renk, genişlik ve stilini belirler. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Bağlanacak noktaları temsil eden [PointF](/imaging/python-net/aspose.imaging/pointf/) yapılarını içeren dizi. |

### Method: draw_path(pen, path) {#draw_path_pen_path_112}


```
 draw_path(pen, path) 
```

Bir [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) yolun renk, genişlik ve stilini belirler. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) çizmek için. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_113}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) pasta şeklinin renk, genişlik ve stilini belirler. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eden yapı. |
| start_angle | float | Pasta şeklinin ilk kenarına x ekseninden saat yönünde derece cinsinden ölçülen açı. |
| sweep_angle | float | _startAngle_ parametresinden pasta şeklinin ikinci kenarına saat yönünde derece cinsinden ölçülen açı. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_114}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) pasta şeklinin renk, genişlik ve stilini belirler. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eden yapı. |
| start_angle | float | Pasta şeklinin ilk kenarına x ekseninden saat yönünde derece cinsinden ölçülen açı. |
| sweep_angle | float | _startAngle_ parametresinden pasta şeklinin ikinci kenarına saat yönünde derece cinsinden ölçülen açı. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_115}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Koordinat çifti, genişlik, yükseklik ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) pasta şeklinin renk, genişlik ve stilini belirler. |
| x | float | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | float | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |
| start_angle | float | Pasta şeklinin ilk kenarına x ekseninden saat yönünde derece cinsinden ölçülen açı. |
| sweep_angle | float | _startAngle_ parametresinden pasta şeklinin ikinci kenarına saat yönünde derece cinsinden ölçülen açı. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_116}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Koordinat çifti, genişlik, yükseklik ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) pasta şeklinin renk, genişlik ve stilini belirler. |
| x | int | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | int | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |
| start_angle | int | Pasta şeklinin ilk kenarına x ekseninden saat yönünde derece cinsinden ölçülen açı. |
| sweep_angle | int | _startAngle_ parametresinden pasta şeklinin ikinci kenarına saat yönünde derece cinsinden ölçülen açı. |

### Method: draw_pie_in_rect(pen, rect, start_angle, sweep_angle) {#draw_pie_in_rect_pen_rect_start_angle_sweep_angle_117}


```
 draw_pie_in_rect(pen, rect, start_angle, sweep_angle) 
```

Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) pasta şeklinin renk, genişlik ve stilini belirler. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eden yapı. |
| start_angle | float | Pasta şeklinin ilk kenarına x ekseninden saat yönünde derece cinsinden ölçülen açı. |
| sweep_angle | float | _startAngle_ parametresinden pasta şeklinin ikinci kenarına saat yönünde derece cinsinden ölçülen açı. |

### Method: draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle) {#draw_pie_in_rect_f_pen_rect_start_angle_sweep_angle_118}


```
 draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle) 
```

Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) pasta şeklinin renk, genişlik ve stilini belirler. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eden yapı. |
| start_angle | float | Pasta şeklinin ilk kenarına x ekseninden saat yönünde derece cinsinden ölçülen açı. |
| sweep_angle | float | _startAngle_ parametresinden pasta şeklinin ikinci kenarına saat yönünde derece cinsinden ölçülen açı. |

### Method: draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_xy_pen_x_y_width_height_start_angle_sweep_angle_119}


```
 draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle) 
```

Koordinat çifti, genişlik, yükseklik ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) pasta şeklinin renk, genişlik ve stilini belirler. |
| x | int | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | int | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |
| start_angle | int | Pasta şeklinin ilk kenarına x ekseninden saat yönünde derece cinsinden ölçülen açı. |
| sweep_angle | int | _startAngle_ parametresinden pasta şeklinin ikinci kenarına saat yönünde derece cinsinden ölçülen açı. |

### Method: draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_xyf_pen_x_y_width_height_start_angle_sweep_angle_120}


```
 draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle) 
```

Koordinat çifti, genişlik, yükseklik ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) pasta şeklinin renk, genişlik ve stilini belirler. |
| x | float | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | float | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |
| start_angle | float | Pasta şeklinin ilk kenarına x ekseninden saat yönünde derece cinsinden ölçülen açı. |
| sweep_angle | float | _startAngle_ parametresinden pasta şeklinin ikinci kenarına saat yönünde derece cinsinden ölçülen açı. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_121}


```
 draw_polygon(pen, points) 
```

Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından tanımlanan bir çokgen çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) çokgenin renk, genişlik ve stilini belirler. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Çokgenin köşe noktalarını temsil eden [PointF](/imaging/python-net/aspose.imaging/pointf/) yapılarını içeren dizi. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_122}


```
 draw_polygon(pen, points) 
```

Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından tanımlanan bir çokgen çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) çokgenin renk, genişlik ve stilini belirler. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Çokgenin köşe noktalarını temsil eden [PointF](/imaging/python-net/aspose.imaging/pointf/) yapılarını içeren dizi. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_polygon_f(pen, points) {#draw_polygon_f_pen_points_123}


```
 draw_polygon_f(pen, points) 
```

Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından tanımlanan bir çokgen çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) çokgenin renk, genişlik ve stilini belirler. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Çokgenin köşe noktalarını temsil eden [PointF](/imaging/python-net/aspose.imaging/pointf/) yapılarını içeren dizi. |

### Method: draw_rect(pen, x, y, width, height) {#draw_rect_pen_x_y_width_height_124}


```
 draw_rect(pen, x, y, width, height) 
```

Koordinat çifti, genişlik ve yükseklik ile belirtilen bir dikdörtgen çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Bir [Pen](/imaging/python-net/aspose.imaging/pen/) dikdörtgenin renk, genişlik ve stilini belirler. |
| x | int | Çizilecek dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Çizilecek dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Çizilecek dikdörtgenin genişliği. |
| height | int | Çizilecek dikdörtgenin yüksekliği. |

### Method: draw_rect_f(pen, x, y, width, height) {#draw_rect_f_pen_x_y_width_height_125}


```
 draw_rect_f(pen, x, y, width, height) 
```

Koordinat çifti, genişlik ve yükseklik ile belirtilen bir dikdörtgen çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Bir [Pen](/imaging/python-net/aspose.imaging/pen/) dikdörtgenin renk, genişlik ve stilini belirler. |
| x | float | Çizilecek dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Çizilecek dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Çizilecek dikdörtgenin genişliği. |
| height | float | Çizilecek dikdörtgenin yüksekliği. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_126}


```
 draw_rectangle(pen, rect) 
```

Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ile belirtilen bir dikdörtgen çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Bir [Pen](/imaging/python-net/aspose.imaging/pen/) dikdörtgenin renk, genişlik ve stilini belirler. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Çizilecek dikdörtgeni temsil eden bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_127}


```
 draw_rectangle(pen, rect) 
```

Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ile belirtilen bir dikdörtgen çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Bir [Pen](/imaging/python-net/aspose.imaging/pen/) dikdörtgenin renk, genişlik ve stilini belirler. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Çizilecek dikdörtgeni temsil eden bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_128}


```
 draw_rectangle(pen, x, y, width, height) 
```

Koordinat çifti, genişlik ve yükseklik ile belirtilen bir dikdörtgen çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Bir [Pen](/imaging/python-net/aspose.imaging/pen/) dikdörtgenin renk, genişlik ve stilini belirler. |
| x | float | Çizilecek dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Çizilecek dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Çizilecek dikdörtgenin genişliği. |
| height | float | Çizilecek dikdörtgenin yüksekliği. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_129}


```
 draw_rectangle(pen, x, y, width, height) 
```

Koordinat çifti, genişlik ve yükseklik ile belirtilen bir dikdörtgen çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Bir [Pen](/imaging/python-net/aspose.imaging/pen/) dikdörtgenin renk, genişlik ve stilini belirler. |
| x | int | Çizilecek dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Çizilecek dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Çizilecek dikdörtgenin genişliği. |
| height | int | Çizilecek dikdörtgenin yüksekliği. |

### Method: draw_rectangle_f(pen, rect) {#draw_rectangle_f_pen_rect_130}


```
 draw_rectangle_f(pen, rect) 
```

Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ile belirtilen bir dikdörtgen çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Bir [Pen](/imaging/python-net/aspose.imaging/pen/) dikdörtgenin renk, genişlik ve stilini belirler. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Çizilecek dikdörtgeni temsil eden bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_131}


```
 draw_rectangles(pen, rects) 
```

Bir dizi [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ile belirtilen dikdörtgenler çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) dikdörtgenlerin kenar çizgilerinin renk, genişlik ve stilini belirler. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Çizilecek dikdörtgenleri temsil eden [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapıların dizisi. |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_132}


```
 draw_rectangles(pen, rects) 
```

Bir dizi [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ile belirtilen dikdörtgenler çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) dikdörtgenlerin kenar çizgilerinin renk, genişlik ve stilini belirler. |
| rects | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | Çizilecek dikdörtgenleri temsil eden [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapıların dizisi. |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: draw_rectangles_f(pen, rects) {#draw_rectangles_f_pen_rects_133}


```
 draw_rectangles_f(pen, rects) 
```

Bir dizi [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ile belirtilen dikdörtgenler çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) dikdörtgenlerin kenar çizgilerinin renk, genişlik ve stilini belirler. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Çizilecek dikdörtgenleri temsil eden [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapıların dizisi. |

### Method: draw_string(s, font, brush, layout_rectangle) {#draw_string_s_font_brush_layout_rectangle_134}


```
 draw_string(s, font, brush, layout_rectangle) 
```

Belirtilen metin dizesini belirtilen dikdörtgende belirtilen [Brush](/imaging/python-net/aspose.imaging/brush/) ve [Font](/imaging/python-net/aspose.imaging/font/) nesneleriyle çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| s | string | Çizilecek dize. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) dizenin metin biçimini tanımlar. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) çizilen metnin renk ve dokusunu belirler. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) çizilen metnin konumunu belirten yapı. |

### Method: draw_string(s, font, brush, layout_rectangle, format) {#draw_string_s_font_brush_layout_rectangle_format_135}


```
 draw_string(s, font, brush, layout_rectangle, format) 
```

Belirtilen metin dizesini belirtilen dikdörtgende belirtilen [Brush](/imaging/python-net/aspose.imaging/brush/) ve [Font](/imaging/python-net/aspose.imaging/font/) nesneleriyle, belirtilen [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) biçimlendirme özniteliklerini kullanarak çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| s | string | Çizilecek dize. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) dizenin metin biçimini tanımlar. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) çizilen metnin renk ve dokusunu belirler. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) çizilen metnin konumunu belirten yapı. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) çizilen metne uygulanan satır aralığı ve hizalama gibi biçimlendirme özelliklerini belirten. |

### Method: draw_string(s, font, brush, point) {#draw_string_s_font_brush_point_136}


```
 draw_string(s, font, brush, point) 
```

Belirtilen metin dizesini belirtilen konumda belirtilen [Brush](/imaging/python-net/aspose.imaging/brush/) ve [Font](/imaging/python-net/aspose.imaging/font/) nesneleriyle çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| s | string | Çizilecek dize. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) dizenin metin biçimini tanımlar. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) çizilen metnin renk ve dokusunu belirler. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) çizilen metnin sol üst köşesini belirten yapı. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_string(s, font, brush, point, format) {#draw_string_s_font_brush_point_format_137}


```
 draw_string(s, font, brush, point, format) 
```

Belirtilen metin dizesini belirtilen konumda belirtilen [Brush](/imaging/python-net/aspose.imaging/brush/) ve [Font](/imaging/python-net/aspose.imaging/font/) nesneleriyle, belirtilen [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) biçimlendirme özniteliklerini kullanarak çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| s | string | Çizilecek dize. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) dizenin metin biçimini tanımlar. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) çizilen metnin renk ve dokusunu belirler. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) çizilen metnin sol üst köşesini belirten yapı. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) çizilen metne uygulanan satır aralığı ve hizalama gibi biçimlendirme özelliklerini belirten. |

### Method: draw_string(s, font, brush, x, y) {#draw_string_s_font_brush_x_y_138}


```
 draw_string(s, font, brush, x, y) 
```

Belirtilen metin dizesini belirtilen konumda belirtilen [Brush](/imaging/python-net/aspose.imaging/brush/) ve [Font](/imaging/python-net/aspose.imaging/font/) nesneleriyle çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| s | string | Çizilecek dize. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) dizenin metin biçimini tanımlar. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) çizilen metnin renk ve dokusunu belirler. |
| x | float | Çizilen metnin sol üst köşesinin x koordinatı. |
| y | float | Çizilen metnin sol üst köşesinin y koordinatı. |

### Method: draw_string(s, font, brush, x, y, format) {#draw_string_s_font_brush_x_y_format_139}


```
 draw_string(s, font, brush, x, y, format) 
```

Belirtilen metin dizesini belirtilen konumda belirtilen [Brush](/imaging/python-net/aspose.imaging/brush/) ve [Font](/imaging/python-net/aspose.imaging/font/) nesneleriyle, belirtilen [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) biçimlendirme özniteliklerini kullanarak çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| s | string | Çizilecek dize. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) dizenin metin biçimini tanımlar. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) çizilen metnin renk ve dokusunu belirler. |
| x | float | Çizilen metnin sol üst köşesinin x koordinatı. |
| y | float | Çizilen metnin sol üst köşesinin y koordinatı. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) çizilen metne uygulanan satır aralığı ve hizalama gibi biçimlendirme özelliklerini belirten. |

### Method: draw_string_at_point_f(s, font, brush, point) {#draw_string_at_point_f_s_font_brush_point_140}


```
 draw_string_at_point_f(s, font, brush, point) 
```

Belirtilen metin dizesini belirtilen konumda belirtilen [Brush](/imaging/python-net/aspose.imaging/brush/) ve [Font](/imaging/python-net/aspose.imaging/font/) nesneleriyle çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| s | string | Çizilecek dize. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) dizenin metin biçimini tanımlar. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) çizilen metnin renk ve dokusunu belirler. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) çizilen metnin sol üst köşesini belirten yapı. |

### Method: draw_string_at_point_f_format(s, font, brush, point, format) {#draw_string_at_point_f_format_s_font_brush_point_format_141}


```
 draw_string_at_point_f_format(s, font, brush, point, format) 
```

Belirtilen metin dizesini belirtilen konumda belirtilen [Brush](/imaging/python-net/aspose.imaging/brush/) ve [Font](/imaging/python-net/aspose.imaging/font/) nesneleriyle, belirtilen [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) biçimlendirme özniteliklerini kullanarak çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| s | string | Çizilecek dize. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) dizenin metin biçimini tanımlar. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) çizilen metnin renk ve dokusunu belirler. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) çizilen metnin sol üst köşesini belirten yapı. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) çizilen metne uygulanan satır aralığı ve hizalama gibi biçimlendirme özelliklerini belirten. |

### Method: draw_string_at_xy(s, font, brush, x, y) {#draw_string_at_xy_s_font_brush_x_y_142}


```
 draw_string_at_xy(s, font, brush, x, y) 
```

Belirtilen metin dizesini belirtilen konumda belirtilen [Brush](/imaging/python-net/aspose.imaging/brush/) ve [Font](/imaging/python-net/aspose.imaging/font/) nesneleriyle çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| s | string | Çizilecek dize. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) dizenin metin biçimini tanımlar. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) çizilen metnin renk ve dokusunu belirler. |
| x | float | Çizilen metnin sol üst köşesinin x koordinatı. |
| y | float | Çizilen metnin sol üst köşesinin y koordinatı. |

### Method: draw_string_in_rect(s, font, brush, layout_rectangle) {#draw_string_in_rect_s_font_brush_layout_rectangle_143}


```
 draw_string_in_rect(s, font, brush, layout_rectangle) 
```

Belirtilen metin dizesini belirtilen dikdörtgende belirtilen [Brush](/imaging/python-net/aspose.imaging/brush/) ve [Font](/imaging/python-net/aspose.imaging/font/) nesneleriyle çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| s | string | Çizilecek dize. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) dizenin metin biçimini tanımlar. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) çizilen metnin renk ve dokusunu belirler. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) çizilen metnin konumunu belirten yapı. |

### Method: draw_string_in_rect_f(s, font, brush, layout_rectangle, format) {#draw_string_in_rect_f_s_font_brush_layout_rectangle_format_144}


```
 draw_string_in_rect_f(s, font, brush, layout_rectangle, format) 
```

Belirtilen metin dizesini belirtilen dikdörtgende belirtilen [Brush](/imaging/python-net/aspose.imaging/brush/) ve [Font](/imaging/python-net/aspose.imaging/font/) nesneleriyle, belirtilen [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) biçimlendirme özniteliklerini kullanarak çizer.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| s | string | Çizilecek dize. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) dizenin metin biçimini tanımlar. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) çizilen metnin renk ve dokusunu belirler. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) çizilen metnin konumunu belirten yapı. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) çizilen metne uygulanan satır aralığı ve hizalama gibi biçimlendirme özelliklerini belirten. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_145}


```
 fill_closed_curve(brush, points) 
```

Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini doldurur. Bu yöntem varsayılan 0,5 gerilim ve [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) doldurma kipini kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Spline'ı tanımlayan [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıların dizisi. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_146}


```
 fill_closed_curve(brush, points) 
```

Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini doldurur. Bu yöntem varsayılan 0,5 gerilim ve [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) doldurma kipini kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Spline'ı tanımlayan [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıların dizisi. |

### Method: fill_closed_curve(brush, points, fill_mode) {#fill_closed_curve_brush_points_fill_mode_147}


```
 fill_closed_curve(brush, points, fill_mode) 
```

Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini belirtilen doldurma kipini kullanarak doldurur. Bu yöntem varsayılan 0,5 gerilim kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Spline'ı tanımlayan [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıların dizisi. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Eğrinin nasıl doldurulacağını belirleyen [FillMode](/imaging/python-net/aspose.imaging/fillmode/) sayımının üyesi. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_148}


```
 fill_closed_curve(brush, points, fillmode) 
```

Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini belirtilen doldurma kipini kullanarak doldurur. Bu yöntem varsayılan 0,5 gerilim kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Spline'ı tanımlayan [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıların dizisi. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) |  |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_149}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini belirtilen doldurma kipi ve gerilimi kullanarak doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Doldurmanın özelliklerini belirleyen bir [Brush](/imaging/python-net/aspose.imaging/brush/). |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Spline'ı tanımlayan [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıların dizisi. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Eğrinin nasıl doldurulacağını belirleyen [FillMode](/imaging/python-net/aspose.imaging/fillmode/) sayımının üyesi. |
| gerilim | float | Eğrinin gerilimini belirten 0.0F veya daha büyük bir değer. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_150}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini belirtilen doldurma kipi ve gerilimi kullanarak doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Doldurmanın özelliklerini belirleyen bir [Brush](/imaging/python-net/aspose.imaging/brush/). |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Spline'ı tanımlayan [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıların dizisi. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Eğrinin nasıl doldurulacağını belirleyen [FillMode](/imaging/python-net/aspose.imaging/fillmode/) sayımının üyesi. |
| gerilim | float | Eğrinin gerilimini belirten 0.0F veya daha büyük bir değer. |

### Method: fill_closed_curve_by_point(brush, points) {#fill_closed_curve_by_point_brush_points_151}


```
 fill_closed_curve_by_point(brush, points) 
```

Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini doldurur. Bu yöntem varsayılan 0,5 gerilim ve [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) doldurma kipini kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Spline'ı tanımlayan [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıların dizisi. |

### Method: fill_closed_curve_by_point_f(brush, points) {#fill_closed_curve_by_point_f_brush_points_152}


```
 fill_closed_curve_by_point_f(brush, points) 
```

Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini doldurur. Bu yöntem varsayılan 0,5 gerilim ve [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) doldurma kipini kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Spline'ı tanımlayan [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıların dizisi. |

### Method: fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension) {#fill_closed_curve_by_point_f_fill_mode_tension_brush_points_fillmode_tension_153}


```
 fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension) 
```

Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini belirtilen doldurma kipi ve gerilimi kullanarak doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Doldurmanın özelliklerini belirleyen bir [Brush](/imaging/python-net/aspose.imaging/brush/). |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Spline'ı tanımlayan [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıların dizisi. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Eğrinin nasıl doldurulacağını belirleyen [FillMode](/imaging/python-net/aspose.imaging/fillmode/) sayımının üyesi. |
| gerilim | float | Eğrinin gerilimini belirten 0.0F veya daha büyük bir değer. |

### Method: fill_closed_curve_by_point_fill_mode(brush, points, fillmode) {#fill_closed_curve_by_point_fill_mode_brush_points_fillmode_154}


```
 fill_closed_curve_by_point_fill_mode(brush, points, fillmode) 
```

Bir dizi [Point](/imaging/python-net/aspose.imaging/point/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini belirtilen doldurma kipini kullanarak doldurur. Bu yöntem varsayılan 0,5 gerilim kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Spline'ı tanımlayan [Point](/imaging/python-net/aspose.imaging/point/) yapıların dizisi. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Eğrinin nasıl doldurulacağını belirleyen [FillMode](/imaging/python-net/aspose.imaging/fillmode/) sayımının üyesi. |

### Method: fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension) {#fill_closed_curve_by_point_fill_mode_tension_brush_points_fillmode_tension_155}


```
 fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension) 
```

Bir dizi [Point](/imaging/python-net/aspose.imaging/point/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini belirtilen doldurma kipi ve gerilimi kullanarak doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Spline'ı tanımlayan [Point](/imaging/python-net/aspose.imaging/point/) yapıların dizisi. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Eğrinin nasıl doldurulacağını belirleyen [FillMode](/imaging/python-net/aspose.imaging/fillmode/) sayımının üyesi. |
| gerilim | float | Eğrinin gerilimini belirten 0.0F veya daha büyük bir değer. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_156}


```
 fill_ellipse(brush, rect) 
```

Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı tarafından belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eden yapı. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_157}


```
 fill_ellipse(brush, rect) 
```

Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı tarafından belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eden yapı. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_158}


```
 fill_ellipse(brush, x, y, width, height) 
```

Koordinat çifti, genişlik ve yükseklik ile belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| x | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_159}


```
 fill_ellipse(brush, x, y, width, height) 
```

Koordinat çifti, genişlik ve yükseklik ile belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| x | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |

### Method: fill_ellipse_at_xywh(brush, x, y, width, height) {#fill_ellipse_at_xywh_brush_x_y_width_height_160}


```
 fill_ellipse_at_xywh(brush, x, y, width, height) 
```

Koordinat çifti, genişlik ve yükseklik ile belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| x | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |

### Method: fill_ellipse_at_xywhf(brush, x, y, width, height) {#fill_ellipse_at_xywhf_brush_x_y_width_height_161}


```
 fill_ellipse_at_xywhf(brush, x, y, width, height) 
```

Koordinat çifti, genişlik ve yükseklik ile belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| x | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |

### Method: fill_ellipse_in_rect(brush, rect) {#fill_ellipse_in_rect_brush_rect_162}


```
 fill_ellipse_in_rect(brush, rect) 
```

Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı tarafından belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eden yapı. |

### Method: fill_ellipse_in_rect_f(brush, rect) {#fill_ellipse_in_rect_f_brush_rect_163}


```
 fill_ellipse_in_rect_f(brush, rect) 
```

Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı tarafından belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eden yapı. |

### Method: fill_path(brush, path) {#fill_path_brush_path_164}


```
 fill_path(brush, path) 
```

Bir [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) nesnesinin içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) doldurulacak yolu temsil eder. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_165}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ve iki radyal çizgiyle belirtilen elips tarafından tanımlanan bir dilim bölümünün içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) dilim bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eden yapı. |
| start_angle | float | X ekseninden dilim bölümünün ilk kenarına doğru saat yönünde ölçülen açı (derece). |
| sweep_angle | float | _startAngle_ parametresinden dilim bölümünün ikinci kenarına doğru saat yönünde ölçülen açı (derece). |


**See also:**

**[Example # 1](#example_95)**: The following example shows how to compose an animated GIF image from individ...


### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_166}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ve iki radyal çizgiyle belirtilen elips tarafından tanımlanan bir dilim bölümünün içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) dilim bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eden yapı. |
| start_angle | float | X ekseninden dilim bölümünün ilk kenarına doğru saat yönünde ölçülen açı (derece). |
| sweep_angle | float | _startAngle_ parametresinden dilim bölümünün ikinci kenarına doğru saat yönünde ölçülen açı (derece). |


**See also:**

**[Example # 1](#example_95)**: The following example shows how to compose an animated GIF image from individ...


### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_167}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Koordinat çifti, genişlik, yükseklik ve iki radyal çizgiyle belirtilen elips tarafından tanımlanan bir dilim bölümünün içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| x | float | Dilim bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Dilim bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Dilim bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | float | Pasta diliminin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |
| start_angle | float | X ekseninden dilim bölümünün ilk kenarına doğru saat yönünde ölçülen açı (derece). |
| sweep_angle | float | _startAngle_ parametresinden dilim bölümünün ikinci kenarına doğru saat yönünde ölçülen açı (derece). |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_168}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Koordinat çifti, genişlik, yükseklik ve iki radyal çizgiyle belirtilen elips tarafından tanımlanan bir dilim bölümünün içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| x | int | Dilim bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Dilim bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Dilim bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | int | Pasta diliminin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |
| start_angle | int | X ekseninden dilim bölümünün ilk kenarına doğru saat yönünde ölçülen açı (derece). |
| sweep_angle | int | _startAngle_ parametresinden dilim bölümünün ikinci kenarına doğru saat yönünde ölçülen açı (derece). |

### Method: fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_at_xy_brush_x_y_width_height_start_angle_sweep_angle_169}


```
 fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle) 
```

Koordinat çifti, genişlik, yükseklik ve iki radyal çizgiyle belirtilen elips tarafından tanımlanan bir dilim bölümünün içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| x | int | Dilim bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Dilim bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Dilim bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | int | Pasta diliminin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |
| start_angle | int | X ekseninden dilim bölümünün ilk kenarına doğru saat yönünde ölçülen açı (derece). |
| sweep_angle | int | _startAngle_ parametresinden dilim bölümünün ikinci kenarına doğru saat yönünde ölçülen açı (derece). |

### Method: fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_at_xyf_brush_x_y_width_height_start_angle_sweep_angle_170}


```
 fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle) 
```

Koordinat çifti, genişlik, yükseklik ve iki radyal çizgiyle belirtilen elips tarafından tanımlanan bir dilim bölümünün içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| x | float | Dilim bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Dilim bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Dilim bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | float | Pasta diliminin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |
| start_angle | float | X ekseninden dilim bölümünün ilk kenarına doğru saat yönünde ölçülen açı (derece). |
| sweep_angle | float | _startAngle_ parametresinden dilim bölümünün ikinci kenarına doğru saat yönünde ölçülen açı (derece). |

### Method: fill_pie_in_rect(brush, rect, start_angle, sweep_angle) {#fill_pie_in_rect_brush_rect_start_angle_sweep_angle_171}


```
 fill_pie_in_rect(brush, rect, start_angle, sweep_angle) 
```

Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ve iki radyal çizgiyle belirtilen elips tarafından tanımlanan bir dilim bölümünün içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) dilim bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eden yapı. |
| start_angle | float | X ekseninden dilim bölümünün ilk kenarına doğru saat yönünde ölçülen açı (derece). |
| sweep_angle | float | _startAngle_ parametresinden dilim bölümünün ikinci kenarına doğru saat yönünde ölçülen açı (derece). |

### Method: fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle) {#fill_pie_in_rect_f_brush_rect_start_angle_sweep_angle_172}


```
 fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle) 
```

Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı ve iki radyal çizgiyle belirtilen elips tarafından tanımlanan bir dilim bölümünün içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı, pasta diliminin geldiği elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eder. |
| start_angle | float | X ekseninden dilim bölümünün ilk kenarına doğru saat yönünde ölçülen açı (derece). |
| sweep_angle | float | _startAngle_ parametresinden dilim bölümünün ikinci kenarına doğru saat yönünde ölçülen açı (derece). |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_173}


```
 fill_polygon(brush, points) 
```

Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ve [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) ile belirtilen noktalarla tanımlanan bir çokgenin içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) yapılarını içeren dizi, doldurulacak çokgenin köşelerini temsil eder. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_174}


```
 fill_polygon(brush, points) 
```

Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ve [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) ile belirtilen noktalarla tanımlanan bir çokgenin içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) yapılarını içeren dizi, doldurulacak çokgenin köşelerini temsil eder. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_175}


```
 fill_polygon(brush, points, fill_mode) 
```

Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından belirtilen noktalarla tanımlanan bir çokgenin içini belirtilen doldurma kipini kullanarak doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) yapılarını içeren dizi, doldurulacak çokgenin köşelerini temsil eder. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) enum'ının doldurma stilini belirleyen üyesi. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_176}


```
 fill_polygon(brush, points, fill_mode) 
```

Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından belirtilen noktalarla tanımlanan bir çokgenin içini belirtilen doldurma kipini kullanarak doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) yapılarını içeren dizi, doldurulacak çokgenin köşelerini temsil eder. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) enum'ının doldurma stilini belirleyen üyesi. |

### Method: fill_polygon_by_point(brush, points) {#fill_polygon_by_point_brush_points_177}


```
 fill_polygon_by_point(brush, points) 
```

Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ve [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) ile belirtilen noktalarla tanımlanan bir çokgenin içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) yapılarını içeren dizi, doldurulacak çokgenin köşelerini temsil eder. |

### Method: fill_polygon_by_point_f(brush, points) {#fill_polygon_by_point_f_brush_points_178}


```
 fill_polygon_by_point_f(brush, points) 
```

Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı ve [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) ile belirtilen noktalarla tanımlanan bir çokgenin içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) yapılarını içeren dizi, doldurulacak çokgenin köşelerini temsil eder. |

### Method: fill_polygon_by_point_f_fill_mode(brush, points, fill_mode) {#fill_polygon_by_point_f_fill_mode_brush_points_fill_mode_179}


```
 fill_polygon_by_point_f_fill_mode(brush, points, fill_mode) 
```

Bir dizi [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı tarafından belirtilen noktalarla tanımlanan bir çokgenin içini belirtilen doldurma kipini kullanarak doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) yapılarını içeren dizi, doldurulacak çokgenin köşelerini temsil eder. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) enum'ının doldurma stilini belirleyen üyesi. |

### Method: fill_polygon_by_point_fill_mode(brush, points, fill_mode) {#fill_polygon_by_point_fill_mode_brush_points_fill_mode_180}


```
 fill_polygon_by_point_fill_mode(brush, points, fill_mode) 
```

Bir dizi [Point](/imaging/python-net/aspose.imaging/point/) yapısı tarafından belirtilen noktalarla tanımlanan bir çokgenin içini belirtilen doldurma kipini kullanarak doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) yapılarını içeren dizi, doldurulacak çokgenin köşelerini temsil eder. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) enum'ının doldurma stilini belirleyen üyesi. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_181}


```
 fill_rectangle(brush, rect) 
```

Bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısı tarafından belirtilen bir dikdörtgenin içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısı, doldurulacak dikdörtgeni temsil eder. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_182}


```
 fill_rectangle(brush, rect) 
```

Bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısı tarafından belirtilen bir dikdörtgenin içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısı, doldurulacak dikdörtgeni temsil eder. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_183}


```
 fill_rectangle(brush, x, y, width, height) 
```

Koordinat çifti, genişlik ve yükseklik ile belirtilen bir dikdörtgenin içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| x | float | Doldurulacak dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Doldurulacak dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Doldurulacak dikdörtgenin genişliği. |
| height | float | Doldurulacak dikdörtgenin yüksekliği. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_184}


```
 fill_rectangle(brush, x, y, width, height) 
```

Koordinat çifti, genişlik ve yükseklik ile belirtilen bir dikdörtgenin içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| x | int | Doldurulacak dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Doldurulacak dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Doldurulacak dikdörtgenin genişliği. |
| height | int | Doldurulacak dikdörtgenin yüksekliği. |

### Method: fill_rectangle_f(brush, rect) {#fill_rectangle_f_brush_rect_185}


```
 fill_rectangle_f(brush, rect) 
```

Bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı tarafından belirtilen bir dikdörtgenin içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı, doldurulacak dikdörtgeni temsil eder. |

### Method: fill_rectangle_f_with_brush(brush, x, y, width, height) {#fill_rectangle_f_with_brush_brush_x_y_width_height_186}


```
 fill_rectangle_f_with_brush(brush, x, y, width, height) 
```

Koordinat çifti, genişlik ve yükseklik ile belirtilen bir dikdörtgenin içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| x | float | Doldurulacak dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Doldurulacak dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Doldurulacak dikdörtgenin genişliği. |
| height | float | Doldurulacak dikdörtgenin yüksekliği. |

### Method: fill_rectangle_with_brush(brush, x, y, width, height) {#fill_rectangle_with_brush_brush_x_y_width_height_187}


```
 fill_rectangle_with_brush(brush, x, y, width, height) 
```

Koordinat çifti, genişlik ve yükseklik ile belirtilen bir dikdörtgenin içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| x | int | Doldurulacak dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Doldurulacak dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Doldurulacak dikdörtgenin genişliği. |
| height | int | Doldurulacak dikdörtgenin yüksekliği. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_188}


```
 fill_rectangles(brush, rects) 
```

[Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapılarıyla belirtilen bir dizi dikdörtgenin içlerini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| rects | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapılarını içeren dizi, doldurulacak dikdörtgenleri temsil eder. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_189}


```
 fill_rectangles(brush, rects) 
```

[Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapılarıyla belirtilen bir dizi dikdörtgenin içlerini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapılarını içeren dizi, doldurulacak dikdörtgenleri temsil eder. |

### Method: fill_rectangles_f(brush, rects) {#fill_rectangles_f_brush_rects_190}


```
 fill_rectangles_f(brush, rects) 
```

[RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapılarıyla belirtilen bir dizi dikdörtgenin içlerini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapılarını içeren dizi, doldurulacak dikdörtgenleri temsil eder. |

### Method: fill_region(brush, region) {#fill_region_brush_region_191}


```
 fill_region(brush, region) 
```

Bir [Region](/imaging/python-net/aspose.imaging/region/) içini doldurur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) doldurmanın özelliklerini belirler. |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | [Region](/imaging/python-net/aspose.imaging/region/) doldurulacak alanı temsil eder. |

### Method: measure_string(text, font, layout_area, string_format) {#measure_string_text_font_layout_area_string_format_192}


```
 measure_string(text, font, layout_area, string_format) 
```

Belirtilen metin dizesini belirtilen parametrelerle ölçer

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| text | string | Ölçülecek metin. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Ölçülecek yazı tipi. |
| layout_area | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Düzen alanı. |
| string_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Dize biçimi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Ölçülen metin dizesinin piksel cinsinden boyutu |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_193}


```
 multiply_transform(matrix) 
```

Bu [Graphics](/imaging/python-net/aspose.imaging/graphics/) öğesinin yerel geometrik dönüşümünü temsil eden [Matrix](/imaging/python-net/aspose.imaging/matrix/) öğesini, belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) öğesiyle çarpar ve belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) öğesini ön ekleyerek çarpar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Geometrik dönüşümü çarpmak için kullanılacak [Matrix](/imaging/python-net/aspose.imaging/matrix/). |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_194}


```
 multiply_transform(matrix, order) 
```

Bu [Graphics](/imaging/python-net/aspose.imaging/graphics/) öğesinin yerel geometrik dönüşümünü temsil eden [Matrix](/imaging/python-net/aspose.imaging/matrix/) öğesini, belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) öğesiyle belirtilen sırada çarpar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Geometrik dönüşümü çarpmak için kullanılacak [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | İki matrisi hangi sırada çarpacağını belirten bir [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/). |

### Method: rotate_transform(angle) {#rotate_transform_angle_195}


```
 rotate_transform(angle) 
```

Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem döndürmeyi dönüşüme ön ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| angle | float | Dönüş açısı. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_196}


```
 rotate_transform(angle, order) 
```

Yerel geometrik dönüşümü belirtilen miktarda, belirtilen sırada döndürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| angle | float | Dönüş açısı. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Dönüşüm matrisini ekleyecek mi yoksa ön ekleyecek mi olduğunu belirten bir [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/). |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_197}


```
 scale_transform(sx, sy) 
```

Yerel geometrik dönüşümü belirtilen değerlerle ölçeklendirir. Bu yöntem ölçekleme matrisini dönüşüme ön ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| sx | float | Dönüşümün x ekseni yönündeki ölçekleme miktarı. |
| sy | float | Dönüşümün y ekseni yönündeki ölçekleme miktarı. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_198}


```
 scale_transform(sx, sy, order) 
```

Yerel geometrik dönüşümü belirtilen değerlerle, belirtilen sırada ölçeklendirir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| sx | float | Dönüşümün x ekseni yönündeki ölçekleme miktarı. |
| sy | float | Dönüşümün y ekseni yönündeki ölçekleme miktarı. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Ölçekleme matrisini ekleme ya da başına ekleme belirten bir [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/). |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_199}


```
 translate_transform(dx, dy) 
```

Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. Bu yöntem çeviriyi dönüşüme ön ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dx | float | x eksenindeki çevirmenin değeri. |
| dy | float | y eksenindeki çevirmenin değeri. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_200}


```
 translate_transform(dx, dy, order) 
```

Yerel geometrik dönüşümü belirtilen boyutlarla, belirtilen sırada çevirir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dx | float | x eksenindeki çevirmenin değeri. |
| dy | float | y eksenindeki çevirmenin değeri. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Çevirmenin uygulanacağı sıra (başına ekleme ya da ekleme). |

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

#Bir dosya akışı örneği oluşturur.
with open(r"C:\temp\output.png", "w+b") as stream:
	#PngOptions bir örnek oluştur ve çeşitli özelliklerini ayarla.
	pngOptions = PngOptions()
	#PngOptions için Kaynak ayarla.
	pngOptions.source = StreamSource(stream)
	#Image bir örnek oluştur.
	with Image.create(pngOptions, 500, 500) as image:
		#Graphics sınıfının bir örneğini oluştur ve başlat.
		graphics = Graphics(image)
		#Graphics yüzeyini temizle.
		graphics.clear(Color.wheat);
		#Siyah renkli Pen nesnesini belirterek bir Yay çizin, 
		#Yayı çevreleyen bir Rectangle, Başlangıç Açısı ve Tarama Açısı
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#Mavi renkli Pen nesnesini ve koordinat noktalarını belirterek bir Bezier çizin.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#Pen nesnesini Yeşil renkli olarak belirterek ve bir dizi Nokta ile bir Eğri çizin
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#Pen nesnesini ve çevresindeki Rectangle kullanarak bir Elips çizin
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#Bir Çizgi çizin
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#Bir Pasta dilimi çizin
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#Pen nesnesini Kırmızı renkli olarak belirterek ve bir dizi Nokta ile bir Çokgen çizin
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#Bir Dikdörtgen çizin
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#SolidBrush nesnesi oluşturun ve çeşitli özelliklerini ayarlayın
		brush = SolidBrush()
		brush.color = Color.purple
		#SolidBrush nesnesi ve Font kullanarak, belirli bir Point'ta bir Dize çizin
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# Tüm değişiklikleri kaydedin.
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


# Bir dosya akışı örneği oluştur
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# TiffOptions sınıfının bir örneğini oluşturun ve çeşitli özelliklerini ayarlayın
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# ImageOptions örneği için kaynağı ayarlayın
	tiffOptions.source = StreamSource(stream)
	# Image sınıfının bir örneğini oluşturun
	with Image.create(tiffOptions, 500, 500) as image:
		# Graphics sınıfının bir örneğini oluştur ve başlat.
		graphics = Graphics(image)
		# Graphics yüzeyini temizle.
		graphics.clear(Color.wheat);
		# GraphicsPath sınıfının bir örneğini oluşturun
		graphics_path = GraphicsPath()
		# Figure sınıfının bir örneğini oluşturun
		figure = Figure()
		# Figure nesnesine Şekiller ekleyin
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# Figure nesnesini GraphicsPath'e ekleyin
		graphics_path.add_figure(figure)
		# Siyah renkli Pen nesnesiyle yolu çizin
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# Tüm değişiklikleri kaydedin.
		image.save()


```

### This example shows the creation and usage Pen objects. The example creates a new Image and draw rectangles on the Image surface. {#example_14}
``` python

from aspose.imaging import Image, Graphics, Color, Pen, Rectangle, Point, Size
from aspose.imaging.brushes import HatchBrush
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

# BmpOptions bir örneği oluşturun ve çeşitli özelliklerini ayarlayın
bmpOptions = BmpOptions()
bmpOptions.bits_per_pixel = 24
# FileCreateSource sınıfının bir örneğini oluşturun ve BmpOptions örneği için Kaynak olarak atayın
# İkinci Boolean parametresi, oluşturulacak dosyanın Geçici olup olmadığını belirler
bmpOptions.source = FileCreateSource(r"C:\temp\sample.bmp", False)
# Belirtilen Yolda bir Image örneği oluşturun
with Image.create(bmpOptions, 500, 500) as image:
	# Graphics bir örneği oluşturun ve Image nesnesiyle başlatın
	graphics = Graphics(image)
	# Graphics yüzeyini Beyaz Renk ile temizleyin
	graphics.clear(Color.white)
	#Renk Kırmızı ve genişlik 5 olan bir Pen örneği oluşturun
	pen = Pen(Color.red, 5.0);
	# HatchBrush bir örneği oluşturun ve özelliklerini ayarlayın
	brush = HatchBrush()
	brush.background_color = Color.wheat;
	brush.foreground_color = Color.red;
	# Pen bir örneği oluşturun
	# HatchBrush nesnesi ve genişlikle başlatın
	brusedpen = Pen(brush, 5.0)
	# Pen nesnesini belirterek Dikdörtgenler çizin
	graphics.draw_rectangles(pen, [
		Rectangle(Point(210, 210), Size(100, 100)),
		Rectangle(Point(110, 110), Size(100, 100)),
		Rectangle(Point(310, 310), Size(100, 100)) ])

	# Pen nesnesini belirterek Dikdörtgenler çizin
	graphics.draw_rectangles(brusedpen, [
		Rectangle(Point(310, 110), Size(100, 100)),
		Rectangle(Point(110, 310), Size(100, 100)) ])

	# Tüm değişiklikleri kaydedin.
	image.save()


```

### The following example shows how to compose an animated GIF image from individual GIF blocks. {#example_95}
``` python
from aspose.imaging.fileformats.gif.blocks import GifFrameBlock
from aspose.imaging.fileformats.gif import GifImage 
from aspose.imaging.brushes import SolidBrush
from aspose.imaging import Graphics, Color

# 100 x 100 piksel boyutunda bir GIF resmi oluşturun.
# İlk blok varsayılan olarak tamamen siyahtır.
with GifFrameBlock(100, 100) as firstBlock:
	with GifImage(firstBlock) as gifImage:
		# İlk daire kırmızıdır.
		brush1 = SolidBrush(Color.red)

		# İkinci daire siyahtır.
		brush2 = SolidBrush(Color.black)

		# Kırmızı yay şeklinin açısını yavaş yavaş artırın.
		for angle in range(10, 361, 10):
			block = GifFrameBlock(100, 100)
			gr = Graphics(block)
			gr.fill_pie(brush1, block.bounds, 0, angle)
			gifImage.add_block(block)
		
		# Siyah yay açısını yavaş yavaş artırın ve kırmızı yayı silin.
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
# 100x100 piksel boyutunda bir PNG resmi oluşturun.
with PngImage(100, 100) as png_image:
	# Bazı görüntü işleme yapın, ör. tüm resmi kırmızıyla doldurun.
	graphics = Graphics(png_image)
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, png_image.bounds)
	# Bir dosyaya kaydedin.
	png_image.save(join(dir_, "output.png"))


```

