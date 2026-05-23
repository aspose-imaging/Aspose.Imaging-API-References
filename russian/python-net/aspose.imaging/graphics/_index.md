---
title: "Класс Graphics"
type: docs
weight: 5030
url: /ru/python-net/aspose.imaging/graphics/
---

**Summary:** Represents the graphics according to the graphics engine used in the current assembly.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Graphics

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Graphics(source_image)](#Graphics_source_image_1) | Инициализирует новый экземпляр класса [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| clip | [Region](/imaging/python-net/aspose.imaging/region/) | r/w | Получает или задает область обрезки. |
| compositing_quality | [CompositingQuality](/imaging/python-net/aspose.imaging/compositingquality/) | r/w | Получает или задает качество композиции. |
| dpi_x | float | r | Получает горизонтальное разрешение этого `aspose.imaging.Graphics`. |
| dpi_y | float | r | Получает вертикальное разрешение этого `aspose.imaging.Graphics`. |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | r | Получает изображение. |
| interpolation_mode | [InterpolationMode](/imaging/python-net/aspose.imaging/interpolationmode/) | r/w | Получает или задает режим интерполяции. |
| is_in_begin_update_call | bool | r | Возвращает значение, указывающее, находится ли графика в состоянии вызова BeginUpdate. |
| page_scale | float | r/w | Получает или задает масштабирование между мировыми единицами и единицами страницы для этого `aspose.imaging.Graphics`. |
| page_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | r/w | Получает или задает единицу измерения, используемую для координат страницы в этом `aspose.imaging.Graphics`. |
| paintable_image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | r/w | Получает или задает параметры изображения, используемые для создания рисуемых векторных изображений. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Получает или задает режим сглаживания. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Получает или задает подсказку рендеринга текста. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Получает или задает копию геометрического преобразования мира для этого [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| begin_update() | Начинает кэширование последующих графических операций. Графические эффекты, применяемые позже, не будут применяться сразу; вместо этого EndUpdate применит все эффекты одновременно. |
| [clear(color)](#clear_color_1) | Очищает графическую поверхность, используя указанный цвет. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_2) | Рисует дугу, представляющую часть эллипса, заданную структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_3) | Рисует дугу, представляющую часть эллипса, заданную структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4) | Рисует дугу, представляющую часть эллипса, заданную парой координат, шириной и высотой. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5) | Рисует дугу, представляющую часть эллипса, заданную парой координат, шириной и высотой. |
| [draw_arc_in_rect(pen, rect, start_angle, sweep_angle)](#draw_arc_in_rect_pen_rect_start_angle_sweep_angle_6) | Рисует дугу, представляющую часть эллипса, заданную структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle)](#draw_arc_in_rect_f_pen_rect_start_angle_sweep_angle_7) | Рисует дугу, представляющую часть эллипса, заданную структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_xy_pen_x_y_width_height_start_angle_sweep_angle_8) | Рисует дугу, представляющую часть эллипса, заданную парой координат, шириной и высотой. |
| [draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_xyf_pen_x_y_width_height_start_angle_sweep_angle_9) | Рисует дугу, представляющую часть эллипса, заданную парой координат, шириной и высотой. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_10) | Рисует сплайн Безье, определённый четырьмя структурами [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_11) | Рисует сплайн Безье, определённый четырьмя структурами [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4)](#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_12) | Рисует сплайн Безье, определённый четырьмя упорядоченными парами координат, представляющими точки. |
| [draw_bezier_by_points(pen, pt1, pt2, pt3, pt4)](#draw_bezier_by_points_pen_pt1_pt2_pt3_pt4_13) | Рисует сплайн Безье, определённый четырьмя структурами [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4)](#draw_bezier_by_points_f_pen_pt1_pt2_pt3_pt4_14) | Рисует сплайн Безье, определённый четырьмя структурами [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_15) | Рисует серию сплайнов Безье из массива структур [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_16) | Рисует серию сплайнов Безье из массива структур [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_beziers_by_pt_array(pen, points)](#draw_beziers_by_pt_array_pen_points_17) | Рисует серию сплайнов Безье из массива структур [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_beziers_by_pt_array_f(pen, points)](#draw_beziers_by_pt_array_f_pen_points_18) | Рисует серию сплайнов Безье из массива структур [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_19) | Рисует замкнутый кардинальный сплайн, определённый массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/). Этот метод использует напряжение по умолчанию 0.5 и режим заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_20) | Рисует замкнутый кардинальный сплайн, определённый массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/). Этот метод использует напряжение по умолчанию 0.5 и режим заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_21) | Рисует замкнутый кардинальный сплайн, определённый массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/), используя указанное напряжение. Этот метод использует режим заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) по умолчанию. |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_22) | Рисует замкнутый кардинальный сплайн, определённый массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/), используя указанное напряжение. Этот метод использует режим заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) по умолчанию. |
| [draw_closed_curve_by_points(pen, points)](#draw_closed_curve_by_points_pen_points_23) | Рисует замкнутый кардинальный сплайн, определённый массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/). Этот метод использует напряжение по умолчанию 0.5 и режим заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve_by_points_f(pen, points)](#draw_closed_curve_by_points_f_pen_points_24) | Рисует замкнутый кардинальный сплайн, определённый массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/). Этот метод использует напряжение по умолчанию 0.5 и режим заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve_by_points_f_tension(pen, points, tension)](#draw_closed_curve_by_points_f_tension_pen_points_tension_25) | Рисует замкнутый кардинальный сплайн, определённый массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/), используя указанное напряжение. Этот метод использует режим заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) по умолчанию. |
| [draw_closed_curve_by_points_tension(pen, points, tension)](#draw_closed_curve_by_points_tension_pen_points_tension_26) | Рисует замкнутый кардинальный сплайн, определённый массивом структур [Point](/imaging/python-net/aspose.imaging/point/), используя указанное напряжение. Этот метод использует режим заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) по умолчанию. |
| [draw_curve(pen, points)](#draw_curve_pen_points_27) | Рисует кардинальный сплайн через указанный массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/). Этот метод использует напряжение по умолчанию 0.5. |
| [draw_curve(pen, points)](#draw_curve_pen_points_28) | Рисует кардинальный сплайн через указанный массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/). Этот метод использует напряжение по умолчанию 0.5. |
| [draw_curve(pen, points, offset, number_of_segments)](#draw_curve_pen_points_offset_number_of_segments_29) | Рисует кардинальный сплайн через указанный массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/). Рисование начинается со смещения от начала массива.<br/>            Этот метод использует напряжение по умолчанию 0.5. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_30) | Рисует кардинальный сплайн через указанный массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/) с заданным напряжением. Рисование начинается со смещения от начала массива. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_31) | Рисует кардинальный сплайн через указанный массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/) с заданным напряжением. Рисование начинается со смещения от начала массива. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_32) | Рисует кардинальный сплайн через указанный массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/) с заданным напряжением. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_33) | Рисует кардинальный сплайн через указанный массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/) с заданным напряжением. |
| [draw_curve_by_point_fs(pen, points)](#draw_curve_by_point_fs_pen_points_34) | Рисует кардинальный сплайн через указанный массив структур [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_curve_by_point_fs_tension(pen, points, tension)](#draw_curve_by_point_fs_tension_pen_points_tension_35) | Рисует кардинальный сплайн через указанный массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/) с заданным напряжением. |
| [draw_curve_by_points(pen, points)](#draw_curve_by_points_pen_points_36) | Рисует кардинальный сплайн через указанный массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/). Этот метод использует напряжение по умолчанию 0.5. |
| [draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension)](#draw_curve_by_points_f_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_37) | Рисует кардинальный сплайн через указанный массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/) с заданным напряжением. Рисование начинается со смещения от начала массива. |
| [draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension)](#draw_curve_by_points_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_38) | Рисует кардинальный сплайн через указанный массив структур [Point](/imaging/python-net/aspose.imaging/point/) с заданным напряжением. |
| [draw_curve_by_points_tension(pen, points, tension)](#draw_curve_by_points_tension_pen_points_tension_39) | Рисует кардинальный сплайн через указанный массив структур [Point](/imaging/python-net/aspose.imaging/point/) с заданным напряжением. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_40) | Рисует эллипс, определяемый ограничивающим [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_41) | Рисует эллипс, определяемый ограничивающим [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_42) | Рисует эллипс, определяемый ограничивающим прямоугольником, заданным парой координат, высотой и шириной. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_43) | Рисует эллипс, определяемый ограничивающим прямоугольником, заданным парой координат, высотой и шириной. |
| [draw_ellipse_by_xy(pen, x, y, width, height)](#draw_ellipse_by_xy_pen_x_y_width_height_44) | Рисует эллипс, определяемый ограничивающим прямоугольником, заданным парой координат, высотой и шириной. |
| [draw_ellipse_by_xyf(pen, x, y, width, height)](#draw_ellipse_by_xyf_pen_x_y_width_height_45) | Рисует эллипс, определяемый ограничивающим прямоугольником, заданным парой координат, высотой и шириной. |
| [draw_ellipse_f(pen, rect)](#draw_ellipse_f_pen_rect_46) | Рисует эллипс, определяемый ограничивающим [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_47) | Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_48) | Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_49) | Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_50) | Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_51) | Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_52) | Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_53) | Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_54) | Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером. |
| [draw_image(source_image, point)](#draw_image_source_image_point_55) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), используя его оригинальный физический размер, в указанном месте. |
| [draw_image(source_image, point)](#draw_image_source_image_point_56) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), используя его оригинальный физический размер, в указанном месте. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_57) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_58) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_59) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_60) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_61) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_62) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_63) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_64) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_65) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_66) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_67) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), используя его оригинальный физический размер, в указанном месте. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_68) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), используя его оригинальный физический размер, в указанном месте. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_69) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_70) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером. |
| [draw_image_at_point(source_image, point)](#draw_image_at_point_source_image_point_71) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), используя его оригинальный физический размер, в указанном месте. |
| [draw_image_at_point_f(source_image, point)](#draw_image_at_point_f_source_image_point_72) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), используя его оригинальный физический размер, в указанном месте. |
| [draw_image_at_xy(source_image, x, y)](#draw_image_at_xy_source_image_x_y_73) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), используя его оригинальный физический размер, в указанном месте. |
| [draw_image_at_xyf(source_image, x, y)](#draw_image_at_xyf_source_image_x_y_74) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), используя его оригинальный физический размер, в указанном месте. |
| [draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit)](#draw_image_dest_point_f_src_rect_f_with_unit_image_dest_points_src_rect_src_unit_75) | Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером. |
| [draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_dest_point_f_src_rect_f_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_76) | Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером. |
| [draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect)](#draw_image_dest_points_f_src_rect_f_image_dest_points_src_rect_77) | Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером. |
| [draw_image_dest_points_src_rect(image, dest_points, src_rect)](#draw_image_dest_points_src_rect_image_dest_points_src_rect_78) | Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером. |
| [draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit)](#draw_image_dest_points_src_rect_with_unit_image_dest_points_src_rect_src_unit_79) | Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером. |
| [draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_dest_points_src_rect_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_80) | Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером. |
| [draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_dest_rect_f_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_81) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером. |
| [draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_dest_rect_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_82) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером. |
| [draw_image_in_rect(source_image, x, y, width, height)](#draw_image_in_rect_source_image_x_y_width_height_83) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером. |
| [draw_image_in_rect_f(source_image, x, y, width, height)](#draw_image_in_rect_f_source_image_x_y_width_height_84) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером. |
| [draw_image_in_rectangle(source_image, rect)](#draw_image_in_rectangle_source_image_rect_85) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером. |
| [draw_image_points(image, dest_points)](#draw_image_points_image_dest_points_86) | Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером. |
| [draw_image_points_f(image, dest_points)](#draw_image_points_f_image_dest_points_87) | Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером. |
| [draw_image_rectangle_f(source_image, rect)](#draw_image_rectangle_f_source_image_rect_88) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером. |
| [draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_src_dest_rects_f_with_unit_source_image_rect_source_rect_destination_graphics_unit_89) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером. |
| [draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_src_dest_rects_with_unit_source_image_rect_source_rect_destination_graphics_unit_90) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером. |
| [draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_src_dst_rect_f_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_91) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером. |
| [draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_src_dst_rects_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_92) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером. |
| [draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit)](#draw_image_to_rect_f_with_unit_source_image_rect_destination_graphics_unit_93) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером. |
| [draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit)](#draw_image_to_rect_with_unit_source_image_rect_destination_graphics_unit_94) | Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером. |
| [draw_image_unscaled(source_image, point)](#draw_image_unscaled_source_image_point_95) | Рисует указанное изображение, используя его оригинальный физический размер, в указанном месте. |
| [draw_image_unscaled(source_image, rect)](#draw_image_unscaled_source_image_rect_96) | Рисует указанное изображение, используя его оригинальный физический размер, в указанном месте. |
| [draw_image_unscaled(source_image, x, y)](#draw_image_unscaled_source_image_x_y_97) | Рисует указанное изображение, используя его оригинальный физический размер, в месте, указанном парой координат. |
| [draw_image_unscaled(source_image, x, y, width, height)](#draw_image_unscaled_source_image_x_y_width_height_98) | Рисует указанное изображение, используя его оригинальный физический размер, в указанном месте. |
| [draw_image_unscaled_and_clipped(source_image, rect)](#draw_image_unscaled_and_clipped_source_image_rect_99) | Рисует указанное изображение без масштабирования и обрезает его при необходимости, чтобы вписать в указанный прямоугольник. |
| [draw_image_unscaled_in_rectangle(source_image, rect)](#draw_image_unscaled_in_rectangle_source_image_rect_100) | Рисует указанное изображение, используя его оригинальный физический размер, в указанном месте. |
| [draw_image_unscaled_to_point(source_image, point)](#draw_image_unscaled_to_point_source_image_point_101) | Рисует указанное изображение, используя его оригинальный физический размер, в указанном месте. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_102) | Рисует линию, соединяющую две структуры [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_103) | Рисует линию, соединяющую две структуры [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_104) | Рисует линию, соединяющую две точки, указанные парами координат. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_105) | Рисует линию, соединяющую две точки, указанные парами координат. |
| [draw_line_by_xy(pen, x1, y1, x2, y2)](#draw_line_by_xy_pen_x1_y1_x2_y2_106) | Рисует линию, соединяющую две точки, указанные парами координат. |
| [draw_line_f_by_xy(pen, x1, y1, x2, y2)](#draw_line_f_by_xy_pen_x1_y1_x2_y2_107) | Рисует линию, соединяющую две точки, указанные парами координат. |
| [draw_line_point_f(pen, point1, point2)](#draw_line_point_f_pen_point1_point2_108) | Рисует линию, соединяющую две структуры [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_lines(pen, points)](#draw_lines_pen_points_109) | Рисует серию отрезков, соединяющих массив структур [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_lines(pen, points)](#draw_lines_pen_points_110) | Рисует серию отрезков, соединяющих массив структур [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_lines_f(pen, points)](#draw_lines_f_pen_points_111) | Рисует серию отрезков, соединяющих массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_path(pen, path)](#draw_path_pen_path_112) | Рисует [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_113) | Рисует форму сектора, определяемую эллипсом, заданным структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) и двумя радиальными линиями. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_114) | Рисует форму сектора, определяемую эллипсом, заданным структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) и двумя радиальными линиями. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_115) | Рисует форму сектора, определяемую эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_116) | Рисует форму сектора, определяемую эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [draw_pie_in_rect(pen, rect, start_angle, sweep_angle)](#draw_pie_in_rect_pen_rect_start_angle_sweep_angle_117) | Рисует форму сектора, определяемую эллипсом, заданным структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) и двумя радиальными линиями. |
| [draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle)](#draw_pie_in_rect_f_pen_rect_start_angle_sweep_angle_118) | Рисует форму сектора, определяемую эллипсом, заданным структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) и двумя радиальными линиями. |
| [draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_xy_pen_x_y_width_height_start_angle_sweep_angle_119) | Рисует форму сектора, определяемую эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_xyf_pen_x_y_width_height_start_angle_sweep_angle_120) | Рисует форму сектора, определяемую эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_121) | Рисует многоугольник, определяемый массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_122) | Рисует многоугольник, определяемый массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_polygon_f(pen, points)](#draw_polygon_f_pen_points_123) | Рисует многоугольник, определяемый массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_rect(pen, x, y, width, height)](#draw_rect_pen_x_y_width_height_124) | Рисует прямоугольник, заданный парой координат, шириной и высотой. |
| [draw_rect_f(pen, x, y, width, height)](#draw_rect_f_pen_x_y_width_height_125) | Рисует прямоугольник, заданный парой координат, шириной и высотой. |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_126) | Рисует прямоугольник, заданный структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_127) | Рисует прямоугольник, заданный структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_128) | Рисует прямоугольник, заданный парой координат, шириной и высотой. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_129) | Рисует прямоугольник, заданный парой координат, шириной и высотой. |
| [draw_rectangle_f(pen, rect)](#draw_rectangle_f_pen_rect_130) | Рисует прямоугольник, заданный структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_131) | Рисует серию прямоугольников, заданных структурами [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_132) | Рисует серию прямоугольников, заданных структурами [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_rectangles_f(pen, rects)](#draw_rectangles_f_pen_rects_133) | Рисует серию прямоугольников, заданных структурами [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_string(s, font, brush, layout_rectangle)](#draw_string_s_font_brush_layout_rectangle_134) | Отрисовывает указанный текст в указанном прямоугольнике с указанным [Brush](/imaging/python-net/aspose.imaging/brush/) и [Font](/imaging/python-net/aspose.imaging/font/) объектами. |
| [draw_string(s, font, brush, layout_rectangle, format)](#draw_string_s_font_brush_layout_rectangle_format_135) | Отрисовывает указанный текст в указанном прямоугольнике с указанным [Brush](/imaging/python-net/aspose.imaging/brush/) и [Font](/imaging/python-net/aspose.imaging/font/) объектами, используя атрибуты форматирования указанного [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [draw_string(s, font, brush, point)](#draw_string_s_font_brush_point_136) | Отрисовывает указанный текст в указанном месте с указанным [Brush](/imaging/python-net/aspose.imaging/brush/) и [Font](/imaging/python-net/aspose.imaging/font/) объектами. |
| [draw_string(s, font, brush, point, format)](#draw_string_s_font_brush_point_format_137) | Отрисовывает указанный текст в указанном месте с указанным [Brush](/imaging/python-net/aspose.imaging/brush/) и [Font](/imaging/python-net/aspose.imaging/font/) объектами, используя атрибуты форматирования указанного [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [draw_string(s, font, brush, x, y)](#draw_string_s_font_brush_x_y_138) | Отрисовывает указанный текст в указанном месте с указанным [Brush](/imaging/python-net/aspose.imaging/brush/) и [Font](/imaging/python-net/aspose.imaging/font/) объектами. |
| [draw_string(s, font, brush, x, y, format)](#draw_string_s_font_brush_x_y_format_139) | Отрисовывает указанный текст в указанном месте с указанным [Brush](/imaging/python-net/aspose.imaging/brush/) и [Font](/imaging/python-net/aspose.imaging/font/) объектами, используя атрибуты форматирования указанного [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [draw_string_at_point_f(s, font, brush, point)](#draw_string_at_point_f_s_font_brush_point_140) | Отрисовывает указанный текст в указанном месте с указанным [Brush](/imaging/python-net/aspose.imaging/brush/) и [Font](/imaging/python-net/aspose.imaging/font/) объектами. |
| [draw_string_at_point_f_format(s, font, brush, point, format)](#draw_string_at_point_f_format_s_font_brush_point_format_141) | Отрисовывает указанный текст в указанном месте с указанным [Brush](/imaging/python-net/aspose.imaging/brush/) и [Font](/imaging/python-net/aspose.imaging/font/) объектами, используя атрибуты форматирования указанного [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [draw_string_at_xy(s, font, brush, x, y)](#draw_string_at_xy_s_font_brush_x_y_142) | Отрисовывает указанный текст в указанном месте с указанным [Brush](/imaging/python-net/aspose.imaging/brush/) и [Font](/imaging/python-net/aspose.imaging/font/) объектами. |
| [draw_string_in_rect(s, font, brush, layout_rectangle)](#draw_string_in_rect_s_font_brush_layout_rectangle_143) | Отрисовывает указанный текст в указанном прямоугольнике с указанным [Brush](/imaging/python-net/aspose.imaging/brush/) и [Font](/imaging/python-net/aspose.imaging/font/) объектами. |
| [draw_string_in_rect_f(s, font, brush, layout_rectangle, format)](#draw_string_in_rect_f_s_font_brush_layout_rectangle_format_144) | Отрисовывает указанный текст в указанном прямоугольнике с указанным [Brush](/imaging/python-net/aspose.imaging/brush/) и [Font](/imaging/python-net/aspose.imaging/font/) объектами, используя атрибуты форматирования указанного [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| end_update() | Завершает кэширование графических операций, начатых после вызова BeginUpdate. Предыдущие графические операции будут применены сразу при вызове этого метода. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_145) | Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/). Этот метод использует напряжение по умолчанию 0.5 и режим заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_146) | Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/). Этот метод использует напряжение по умолчанию 0.5 и режим заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [fill_closed_curve(brush, points, fill_mode)](#fill_closed_curve_brush_points_fill_mode_147) | Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/), используя указанный режим заполнения. Этот метод использует напряжение по умолчанию 0.5. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_148) | Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/), используя указанный режим заполнения. Этот метод использует напряжение по умолчанию 0.5. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_149) | Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/), используя указанный режим заполнения и напряжение. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_150) | Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/), используя указанный режим заполнения и напряжение. |
| [fill_closed_curve_by_point(brush, points)](#fill_closed_curve_by_point_brush_points_151) | Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/). Этот метод использует напряжение по умолчанию 0.5 и режим заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [fill_closed_curve_by_point_f(brush, points)](#fill_closed_curve_by_point_f_brush_points_152) | Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/). Этот метод использует напряжение по умолчанию 0.5 и режим заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| fill_closed_curve_by_point_f_fill_mode(brush, points, fillmode) |  |
| [fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension)](#fill_closed_curve_by_point_f_fill_mode_tension_brush_points_fillmode_tension_153) | Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/), используя указанный режим заполнения и напряжение. |
| [fill_closed_curve_by_point_fill_mode(brush, points, fillmode)](#fill_closed_curve_by_point_fill_mode_brush_points_fillmode_154) | Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [Point](/imaging/python-net/aspose.imaging/point/), используя указанный режим заполнения. Этот метод использует напряжение по умолчанию 0.5. |
| [fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension)](#fill_closed_curve_by_point_fill_mode_tension_brush_points_fillmode_tension_155) | Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [Point](/imaging/python-net/aspose.imaging/point/), используя указанный режим заполнения и напряжение. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_156) | Заполняет внутреннюю часть эллипса, определенного ограничивающим прямоугольником, указанным структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_157) | Заполняет внутреннюю часть эллипса, определенного ограничивающим прямоугольником, указанным структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_158) | Заполняет внутреннюю часть эллипса, определенного ограничивающим прямоугольником, заданным парой координат, шириной и высотой. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_159) | Заполняет внутреннюю часть эллипса, определенного ограничивающим прямоугольником, заданным парой координат, шириной и высотой. |
| [fill_ellipse_at_xywh(brush, x, y, width, height)](#fill_ellipse_at_xywh_brush_x_y_width_height_160) | Заполняет внутреннюю часть эллипса, определенного ограничивающим прямоугольником, заданным парой координат, шириной и высотой. |
| [fill_ellipse_at_xywhf(brush, x, y, width, height)](#fill_ellipse_at_xywhf_brush_x_y_width_height_161) | Заполняет внутреннюю часть эллипса, определенного ограничивающим прямоугольником, заданным парой координат, шириной и высотой. |
| [fill_ellipse_in_rect(brush, rect)](#fill_ellipse_in_rect_brush_rect_162) | Заполняет внутреннюю часть эллипса, определенного ограничивающим прямоугольником, указанным структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [fill_ellipse_in_rect_f(brush, rect)](#fill_ellipse_in_rect_f_brush_rect_163) | Заполняет внутреннюю часть эллипса, определенного ограничивающим прямоугольником, указанным структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [fill_path(brush, path)](#fill_path_brush_path_164) | Заполняет внутреннюю часть [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_165) | Заполняет внутреннюю часть сектора пирога, определенного эллипсом, указанным структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) и двумя радиальными линиями. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_166) | Заполняет внутреннюю часть сектора пирога, определенного эллипсом, указанным структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) и двумя радиальными линиями. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_167) | Заполняет внутреннюю часть сектора пирога, определенного эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_168) | Заполняет внутреннюю часть сектора пирога, определенного эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_at_xy_brush_x_y_width_height_start_angle_sweep_angle_169) | Заполняет внутреннюю часть сектора пирога, определенного эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_at_xyf_brush_x_y_width_height_start_angle_sweep_angle_170) | Заполняет внутреннюю часть сектора пирога, определенного эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [fill_pie_in_rect(brush, rect, start_angle, sweep_angle)](#fill_pie_in_rect_brush_rect_start_angle_sweep_angle_171) | Заполняет внутреннюю часть сектора пирога, определенного эллипсом, указанным структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) и двумя радиальными линиями. |
| [fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle)](#fill_pie_in_rect_f_brush_rect_start_angle_sweep_angle_172) | Заполняет внутреннюю часть сектора пирога, определенного эллипсом, указанным структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) и двумя радиальными линиями. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_173) | Заполняет внутреннюю часть многоугольника, определенного массивом точек, указанных структурами [PointF](/imaging/python-net/aspose.imaging/pointf/) и режимом заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_174) | Заполняет внутреннюю часть многоугольника, определенного массивом точек, указанных структурами [PointF](/imaging/python-net/aspose.imaging/pointf/) и режимом заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_175) | Заполняет внутреннюю часть многоугольника, определенного массивом точек, указанных структурами [PointF](/imaging/python-net/aspose.imaging/pointf/), используя указанный режим заполнения. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_176) | Заполняет внутреннюю часть многоугольника, определенного массивом точек, указанных структурами [PointF](/imaging/python-net/aspose.imaging/pointf/), используя указанный режим заполнения. |
| [fill_polygon_by_point(brush, points)](#fill_polygon_by_point_brush_points_177) | Заполняет внутреннюю часть многоугольника, определенного массивом точек, указанных структурами [PointF](/imaging/python-net/aspose.imaging/pointf/) и режимом заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [fill_polygon_by_point_f(brush, points)](#fill_polygon_by_point_f_brush_points_178) | Заполняет внутреннюю часть многоугольника, определенного массивом точек, указанных структурами [PointF](/imaging/python-net/aspose.imaging/pointf/) и режимом заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [fill_polygon_by_point_f_fill_mode(brush, points, fill_mode)](#fill_polygon_by_point_f_fill_mode_brush_points_fill_mode_179) | Заполняет внутреннюю часть многоугольника, определенного массивом точек, указанных структурами [PointF](/imaging/python-net/aspose.imaging/pointf/), используя указанный режим заполнения. |
| [fill_polygon_by_point_fill_mode(brush, points, fill_mode)](#fill_polygon_by_point_fill_mode_brush_points_fill_mode_180) | Заполняет внутреннюю часть многоугольника, определенного массивом точек, указанных структурами [Point](/imaging/python-net/aspose.imaging/point/), используя указанный режим заполнения. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_181) | Заполняет внутреннюю часть прямоугольника, указанного структурой [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_182) | Заполняет внутреннюю часть прямоугольника, указанного структурой [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_183) | Заполняет внутреннюю часть прямоугольника, заданного парой координат, шириной и высотой. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_184) | Заполняет внутреннюю часть прямоугольника, заданного парой координат, шириной и высотой. |
| [fill_rectangle_f(brush, rect)](#fill_rectangle_f_brush_rect_185) | Заполняет внутреннюю часть прямоугольника, указанного структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [fill_rectangle_f_with_brush(brush, x, y, width, height)](#fill_rectangle_f_with_brush_brush_x_y_width_height_186) | Заполняет внутреннюю часть прямоугольника, заданного парой координат, шириной и высотой. |
| [fill_rectangle_with_brush(brush, x, y, width, height)](#fill_rectangle_with_brush_brush_x_y_width_height_187) | Заполняет внутреннюю часть прямоугольника, заданного парой координат, шириной и высотой. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_188) | Заполняет внутренние части серии прямоугольников, указанных структурами [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_189) | Заполняет внутренние части серии прямоугольников, указанных структурами [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [fill_rectangles_f(brush, rects)](#fill_rectangles_f_brush_rects_190) | Заполняет внутренние части серии прямоугольников, указанных структурами [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [fill_region(brush, region)](#fill_region_brush_region_191) | Заполняет внутреннюю часть [Region](/imaging/python-net/aspose.imaging/region/). |
| [measure_string(text, font, layout_area, string_format)](#measure_string_text_font_layout_area_string_format_192) | Измеряет указанную строку текста с заданными параметрами |
| [multiply_transform(matrix)](#multiply_transform_matrix_193) | Умножает [Matrix](/imaging/python-net/aspose.imaging/matrix/), представляющий локальное геометрическое преобразование этого [Graphics](/imaging/python-net/aspose.imaging/graphics/), на указанный [Matrix](/imaging/python-net/aspose.imaging/matrix/) путем предварительного добавления указанного [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_194) | Умножает [Matrix](/imaging/python-net/aspose.imaging/matrix/), представляющий локальное геометрическое преобразование этого [Graphics](/imaging/python-net/aspose.imaging/graphics/), на указанный [Matrix](/imaging/python-net/aspose.imaging/matrix/) в указанном порядке. |
| reset_transform() | Сбрасывает свойство [Graphics.transform](/imaging/python-net/aspose.imaging/graphics/) к единичному. |
| [rotate_transform(angle)](#rotate_transform_angle_195) | Вращает локальное геометрическое преобразование на указанную величину. Этот метод предварительно добавляет вращение к преобразованию. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_196) | Вращает локальное геометрическое преобразование на указанную величину в указанном порядке. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_197) | Масштабирует локальное геометрическое преобразование на указанные величины. Этот метод предварительно добавляет матрицу масштабирования к преобразованию. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_198) | Масштабирует локальное геометрическое преобразование на указанные величины в указанном порядке. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_199) | Смещает локальное геометрическое преобразование на указанные размеры. Этот метод предварительно добавляет трансляцию к преобразованию. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_200) | Смещает локальное геометрическое преобразование на указанные размеры в указанном порядке. |


### Constructor: Graphics(source_image) {#Graphics_source_image_1}


```
 Graphics(source_image) 
```

Инициализирует новый экземпляр класса [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Исходное изображение. |

### Method: clear(color) {#clear_color_1}


```
 clear(color) 
```

Очищает графическую поверхность, используя указанный цвет.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Цвет, которым очищается поверхность графики. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...

**[Example # 2](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_2}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Рисует дугу, представляющую часть эллипса, заданную структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/), определяющий цвет, ширину и стиль дуги. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), определяющая границы эллипса. |
| start_angle | float | Угол в градусах, измеренный по часовой стрелке от оси x до начальной точки дуги. |
| sweep_angle | float | Угол в градусах, измеренный по часовой стрелке от параметра _startAngle_ до конечной точки дуги. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_3}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Рисует дугу, представляющую часть эллипса, заданную структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/), определяющий цвет, ширину и стиль дуги. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), определяющая границы эллипса. |
| start_angle | float | Угол в градусах, измеренный по часовой стрелке от оси x до начальной точки дуги. |
| sweep_angle | float | Угол в градусах, измеренный по часовой стрелке от параметра _startAngle_ до конечной точки дуги. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Рисует дугу, представляющую часть эллипса, заданную парой координат, шириной и высотой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/), определяющий цвет, ширину и стиль дуги. |
| x | float | Координата x верхнего левого угла прямоугольника, определяющего эллипс. |
| y | float | Координата y верхнего левого угла прямоугольника, определяющего эллипс. |
| width | float | Ширина прямоугольника, определяющего эллипс. |
| height | float | Высота прямоугольника, определяющего эллипс. |
| start_angle | float | Угол в градусах, измеренный по часовой стрелке от оси x до начальной точки дуги. |
| sweep_angle | float | Угол в градусах, измеренный по часовой стрелке от параметра _startAngle_ до конечной точки дуги. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Рисует дугу, представляющую часть эллипса, заданную парой координат, шириной и высотой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/), определяющий цвет, ширину и стиль дуги. |
| x | int | Координата x верхнего левого угла прямоугольника, определяющего эллипс. |
| y | int | Координата y верхнего левого угла прямоугольника, определяющего эллипс. |
| width | int | Ширина прямоугольника, определяющего эллипс. |
| height | int | Высота прямоугольника, определяющего эллипс. |
| start_angle | int | Угол в градусах, измеренный по часовой стрелке от оси x до начальной точки дуги. |
| sweep_angle | int | Угол в градусах, измеренный по часовой стрелке от параметра _startAngle_ до конечной точки дуги. |

### Method: draw_arc_in_rect(pen, rect, start_angle, sweep_angle) {#draw_arc_in_rect_pen_rect_start_angle_sweep_angle_6}


```
 draw_arc_in_rect(pen, rect, start_angle, sweep_angle) 
```

Рисует дугу, представляющую часть эллипса, заданную структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/), определяющий цвет, ширину и стиль дуги. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), определяющая границы эллипса. |
| start_angle | float | Угол в градусах, измеренный по часовой стрелке от оси x до начальной точки дуги. |
| sweep_angle | float | Угол в градусах, измеренный по часовой стрелке от параметра _startAngle_ до конечной точки дуги. |

### Method: draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle) {#draw_arc_in_rect_f_pen_rect_start_angle_sweep_angle_7}


```
 draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle) 
```

Рисует дугу, представляющую часть эллипса, заданную структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/), определяющий цвет, ширину и стиль дуги. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), определяющая границы эллипса. |
| start_angle | float | Угол в градусах, измеренный по часовой стрелке от оси x до начальной точки дуги. |
| sweep_angle | float | Угол в градусах, измеренный по часовой стрелке от параметра _startAngle_ до конечной точки дуги. |

### Method: draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_xy_pen_x_y_width_height_start_angle_sweep_angle_8}


```
 draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle) 
```

Рисует дугу, представляющую часть эллипса, заданную парой координат, шириной и высотой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/), определяющий цвет, ширину и стиль дуги. |
| x | int | Координата x верхнего левого угла прямоугольника, определяющего эллипс. |
| y | int | Координата y верхнего левого угла прямоугольника, определяющего эллипс. |
| width | int | Ширина прямоугольника, определяющего эллипс. |
| height | int | Высота прямоугольника, определяющего эллипс. |
| start_angle | int | Угол в градусах, измеренный по часовой стрелке от оси x до начальной точки дуги. |
| sweep_angle | int | Угол в градусах, измеренный по часовой стрелке от параметра _startAngle_ до конечной точки дуги. |

### Method: draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_xyf_pen_x_y_width_height_start_angle_sweep_angle_9}


```
 draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle) 
```

Рисует дугу, представляющую часть эллипса, заданную парой координат, шириной и высотой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/), определяющий цвет, ширину и стиль дуги. |
| x | float | Координата x верхнего левого угла прямоугольника, определяющего эллипс. |
| y | float | Координата y верхнего левого угла прямоугольника, определяющего эллипс. |
| width | float | Ширина прямоугольника, определяющего эллипс. |
| height | float | Высота прямоугольника, определяющего эллипс. |
| start_angle | float | Угол в градусах, измеренный по часовой стрелке от оси x до начальной точки дуги. |
| sweep_angle | float | Угол в градусах, измеренный по часовой стрелке от параметра _startAngle_ до конечной точки дуги. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_10}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Рисует сплайн Безье, определённый четырьмя структурами [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/), определяющий цвет, ширину и стиль кривой. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющая начальную точку кривой. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющая первую управляющую точку кривой. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющая вторую управляющую точку кривой. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющая конечную точку кривой. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_11}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Рисует сплайн Безье, определённый четырьмя структурами [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/), определяющий цвет, ширину и стиль кривой. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющая начальную точку кривой. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющая первую управляющую точку кривой. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющая вторую управляющую точку кривой. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющая конечную точку кривой. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) {#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_12}


```
 draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) 
```

Рисует сплайн Безье, определённый четырьмя упорядоченными парами координат, представляющими точки.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/), определяющий цвет, ширину и стиль кривой. |
| x1 | float | Координата x начальной точки кривой. |
| y1 | float | Координата y начальной точки кривой. |
| x2 | float | Координата x первой управляющей точки кривой. |
| y2 | float | Y‑координата первой контрольной точки кривой. |
| x3 | float | X‑координата второй контрольной точки кривой. |
| y3 | float | Y‑координата второй контрольной точки кривой. |
| x4 | float | X‑координата конечной точки кривой. |
| y4 | float | Y‑координата конечной точки кривой. |

### Method: draw_bezier_by_points(pen, pt1, pt2, pt3, pt4) {#draw_bezier_by_points_pen_pt1_pt2_pt3_pt4_13}


```
 draw_bezier_by_points(pen, pt1, pt2, pt3, pt4) 
```

Рисует сплайн Безье, определённый четырьмя структурами [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/), определяющий цвет, ширину и стиль кривой. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющая начальную точку кривой. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющая первую управляющую точку кривой. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющая вторую управляющую точку кривой. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющая конечную точку кривой. |

### Method: draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4) {#draw_bezier_by_points_f_pen_pt1_pt2_pt3_pt4_14}


```
 draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4) 
```

Рисует сплайн Безье, определённый четырьмя структурами [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/), определяющий цвет, ширину и стиль кривой. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющая начальную точку кривой. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющая первую управляющую точку кривой. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющая вторую управляющую точку кривой. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющая конечную точку кривой. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_15}


```
 draw_beziers(pen, points) 
```

Рисует серию сплайнов Безье из массива структур [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/), определяющий цвет, ширину и стиль кривой. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [Point](/imaging/python-net/aspose.imaging/point/), представляющих точки, определяющие кривую. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_16}


```
 draw_beziers(pen, points) 
```

Рисует серию сплайнов Безье из массива структур [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/), определяющий цвет, ширину и стиль кривой. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [Point](/imaging/python-net/aspose.imaging/point/), представляющих точки, определяющие кривую. |

### Method: draw_beziers_by_pt_array(pen, points) {#draw_beziers_by_pt_array_pen_points_17}


```
 draw_beziers_by_pt_array(pen, points) 
```

Рисует серию сплайнов Безье из массива структур [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/), определяющий цвет, ширину и стиль кривой. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [Point](/imaging/python-net/aspose.imaging/point/), представляющих точки, определяющие кривую. |

### Method: draw_beziers_by_pt_array_f(pen, points) {#draw_beziers_by_pt_array_f_pen_points_18}


```
 draw_beziers_by_pt_array_f(pen, points) 
```

Рисует серию сплайнов Безье из массива структур [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/), определяющий цвет, ширину и стиль кривой. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих точки, определяющие кривую. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_19}


```
 draw_closed_curve(pen, points) 
```

Рисует замкнутый кардинальный сплайн, определённый массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/). Этот метод использует напряжение по умолчанию 0.5 и режим заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и высоту кривой. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), определяющих сплайн. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_20}


```
 draw_closed_curve(pen, points) 
```

Рисует замкнутый кардинальный сплайн, определённый массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/). Этот метод использует напряжение по умолчанию 0.5 и режим заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и высоту кривой. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), определяющих сплайн. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_21}


```
 draw_closed_curve(pen, points, tension) 
```

Рисует замкнутый кардинальный сплайн, определённый массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/), используя указанное напряжение. Этот метод использует режим заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и высоту кривой. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), определяющих сплайн. |
| натяжение | float | Значение, большее или равное 0.0F, которое задаёт натяжение кривой. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_22}


```
 draw_closed_curve(pen, points, tension) 
```

Рисует замкнутый кардинальный сплайн, определённый массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/), используя указанное напряжение. Этот метод использует режим заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и высоту кривой. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), определяющих сплайн. |
| натяжение | float | Значение, большее или равное 0.0F, которое задаёт натяжение кривой. |

### Method: draw_closed_curve_by_points(pen, points) {#draw_closed_curve_by_points_pen_points_23}


```
 draw_closed_curve_by_points(pen, points) 
```

Рисует замкнутый кардинальный сплайн, определённый массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/). Этот метод использует напряжение по умолчанию 0.5 и режим заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и высоту кривой. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), определяющих сплайн. |

### Method: draw_closed_curve_by_points_f(pen, points) {#draw_closed_curve_by_points_f_pen_points_24}


```
 draw_closed_curve_by_points_f(pen, points) 
```

Рисует замкнутый кардинальный сплайн, определённый массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/). Этот метод использует напряжение по умолчанию 0.5 и режим заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и высоту кривой. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), определяющих сплайн. |

### Method: draw_closed_curve_by_points_f_tension(pen, points, tension) {#draw_closed_curve_by_points_f_tension_pen_points_tension_25}


```
 draw_closed_curve_by_points_f_tension(pen, points, tension) 
```

Рисует замкнутый кардинальный сплайн, определённый массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/), используя указанное напряжение. Этот метод использует режим заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и высоту кривой. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), определяющих сплайн. |
| натяжение | float | Значение, большее или равное 0.0F, которое задаёт натяжение кривой. |

### Method: draw_closed_curve_by_points_tension(pen, points, tension) {#draw_closed_curve_by_points_tension_pen_points_tension_26}


```
 draw_closed_curve_by_points_tension(pen, points, tension) 
```

Рисует замкнутый кардинальный сплайн, определённый массивом структур [Point](/imaging/python-net/aspose.imaging/point/), используя указанное напряжение. Этот метод использует режим заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и высоту кривой. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [Point](/imaging/python-net/aspose.imaging/point/), определяющих сплайн. |
| натяжение | float | Значение, большее или равное 0.0F, которое задаёт натяжение кривой. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_27}


```
 draw_curve(pen, points) 
```

Рисует кардинальный сплайн через указанный массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/). Этот метод использует напряжение по умолчанию 0.5.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и высоту кривой. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), определяющих сплайн. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_curve(pen, points) {#draw_curve_pen_points_28}


```
 draw_curve(pen, points) 
```

Рисует кардинальный сплайн через указанный массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/). Этот метод использует напряжение по умолчанию 0.5.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и высоту кривой. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), определяющих сплайн. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_curve(pen, points, offset, number_of_segments) {#draw_curve_pen_points_offset_number_of_segments_29}


```
 draw_curve(pen, points, offset, number_of_segments) 
```

Рисует кардинальный сплайн через указанный массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/). Рисование начинается со смещения от начала массива.<br/>            Этот метод использует напряжение по умолчанию 0.5.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и высоту кривой. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), определяющих сплайн. |
| offset | int | Смещение от первого элемента массива параметра _points_ до начальной точки кривой. |
| number_of_segments | int | Количество сегментов после начальной точки, включаемых в кривую. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_30}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Рисует кардинальный сплайн через указанный массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/) с заданным напряжением. Рисование начинается со смещения от начала массива.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и высоту кривой. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), определяющих сплайн. |
| offset | int | Смещение от первого элемента массива параметра _points_ до начальной точки кривой. |
| number_of_segments | int | Количество сегментов после начальной точки, включаемых в кривую. |
| натяжение | float | Значение, большее или равное 0.0F, которое задаёт натяжение кривой. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_31}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Рисует кардинальный сплайн через указанный массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/) с заданным напряжением. Рисование начинается со смещения от начала массива.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и высоту кривой. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), определяющих сплайн. |
| offset | int | Смещение от первого элемента массива параметра _points_ до начальной точки кривой. |
| number_of_segments | int | Количество сегментов после начальной точки, включаемых в кривую. |
| натяжение | float | Значение, большее или равное 0.0F, которое задаёт натяжение кривой. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_32}


```
 draw_curve(pen, points, tension) 
```

Рисует кардинальный сплайн через указанный массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/) с заданным напряжением.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и высоту кривой. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих точки, определяющие кривую. |
| натяжение | float | Значение, большее или равное 0.0F, которое задаёт натяжение кривой. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_33}


```
 draw_curve(pen, points, tension) 
```

Рисует кардинальный сплайн через указанный массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/) с заданным напряжением.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и высоту кривой. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих точки, определяющие кривую. |
| натяжение | float | Значение, большее или равное 0.0F, которое задаёт натяжение кривой. |

### Method: draw_curve_by_point_fs(pen, points) {#draw_curve_by_point_fs_pen_points_34}


```
 draw_curve_by_point_fs(pen, points) 
```

Рисует кардинальный сплайн через указанный массив структур [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и высоту кривой. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [Point](/imaging/python-net/aspose.imaging/point/), определяющих сплайн. |

### Method: draw_curve_by_point_fs_tension(pen, points, tension) {#draw_curve_by_point_fs_tension_pen_points_tension_35}


```
 draw_curve_by_point_fs_tension(pen, points, tension) 
```

Рисует кардинальный сплайн через указанный массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/) с заданным напряжением.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и высоту кривой. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих точки, определяющие кривую. |
| натяжение | float | Значение, большее или равное 0.0F, которое задаёт натяжение кривой. |

### Method: draw_curve_by_points(pen, points) {#draw_curve_by_points_pen_points_36}


```
 draw_curve_by_points(pen, points) 
```

Рисует кардинальный сплайн через указанный массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/). Этот метод использует напряжение по умолчанию 0.5.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и высоту кривой. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), определяющих сплайн. |

### Method: draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) {#draw_curve_by_points_f_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_37}


```
 draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) 
```

Рисует кардинальный сплайн через указанный массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/) с заданным напряжением. Рисование начинается со смещения от начала массива.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и высоту кривой. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), определяющих сплайн. |
| offset | int | Смещение от первого элемента массива параметра _points_ до начальной точки кривой. |
| number_of_segments | int | Количество сегментов после начальной точки, включаемых в кривую. |
| натяжение | float | Значение, большее или равное 0.0F, которое задаёт натяжение кривой. |

### Method: draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) {#draw_curve_by_points_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_38}


```
 draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) 
```

Рисует кардинальный сплайн через указанный массив структур [Point](/imaging/python-net/aspose.imaging/point/) с заданным напряжением.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и высоту кривой. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [Point](/imaging/python-net/aspose.imaging/point/), определяющих сплайн. |
| offset | int | Смещение от первого элемента массива параметра _points_ до начальной точки кривой. |
| number_of_segments | int | Количество сегментов после начальной точки, включаемых в кривую. |
| натяжение | float | Значение, большее или равное 0.0F, которое задаёт натяжение кривой. |

### Method: draw_curve_by_points_tension(pen, points, tension) {#draw_curve_by_points_tension_pen_points_tension_39}


```
 draw_curve_by_points_tension(pen, points, tension) 
```

Рисует кардинальный сплайн через указанный массив структур [Point](/imaging/python-net/aspose.imaging/point/) с заданным напряжением.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и высоту кривой. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [Point](/imaging/python-net/aspose.imaging/point/), определяющих сплайн. |
| натяжение | float | Значение, большее или равное 0.0F, которое задаёт натяжение кривой. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_40}


```
 draw_ellipse(pen, rect) 
```

Рисует эллипс, определяемый ограничивающим [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и стиль эллипса. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), определяющая границы эллипса. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_41}


```
 draw_ellipse(pen, rect) 
```

Рисует эллипс, определяемый ограничивающим [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и стиль эллипса. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), определяющая границы эллипса. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_42}


```
 draw_ellipse(pen, x, y, width, height) 
```

Рисует эллипс, определяемый ограничивающим прямоугольником, заданным парой координат, высотой и шириной.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и стиль эллипса. |
| x | float | X‑координата левого верхнего угла ограничивающего прямоугольника, определяющего эллипс. |
| y | float | Y‑координата левого верхнего угла ограничивающего прямоугольника, определяющего эллипс. |
| width | float | Ширина ограничивающего прямоугольника, определяющего эллипс. |
| height | float | Высота ограничивающего прямоугольника, определяющего эллипс. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_43}


```
 draw_ellipse(pen, x, y, width, height) 
```

Рисует эллипс, определяемый ограничивающим прямоугольником, заданным парой координат, высотой и шириной.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и стиль эллипса. |
| x | int | X‑координата левого верхнего угла ограничивающего прямоугольника, определяющего эллипс. |
| y | int | Y‑координата левого верхнего угла ограничивающего прямоугольника, определяющего эллипс. |
| width | int | Ширина ограничивающего прямоугольника, определяющего эллипс. |
| height | int | Высота ограничивающего прямоугольника, определяющего эллипс. |

### Method: draw_ellipse_by_xy(pen, x, y, width, height) {#draw_ellipse_by_xy_pen_x_y_width_height_44}


```
 draw_ellipse_by_xy(pen, x, y, width, height) 
```

Рисует эллипс, определяемый ограничивающим прямоугольником, заданным парой координат, высотой и шириной.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и стиль эллипса. |
| x | int | X‑координата левого верхнего угла ограничивающего прямоугольника, определяющего эллипс. |
| y | int | Y‑координата левого верхнего угла ограничивающего прямоугольника, определяющего эллипс. |
| width | int | Ширина ограничивающего прямоугольника, определяющего эллипс. |
| height | int | Высота ограничивающего прямоугольника, определяющего эллипс. |

### Method: draw_ellipse_by_xyf(pen, x, y, width, height) {#draw_ellipse_by_xyf_pen_x_y_width_height_45}


```
 draw_ellipse_by_xyf(pen, x, y, width, height) 
```

Рисует эллипс, определяемый ограничивающим прямоугольником, заданным парой координат, высотой и шириной.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и стиль эллипса. |
| x | float | X‑координата левого верхнего угла ограничивающего прямоугольника, определяющего эллипс. |
| y | float | Y‑координата левого верхнего угла ограничивающего прямоугольника, определяющего эллипс. |
| width | float | Ширина ограничивающего прямоугольника, определяющего эллипс. |
| height | float | Высота ограничивающего прямоугольника, определяющего эллипс. |

### Method: draw_ellipse_f(pen, rect) {#draw_ellipse_f_pen_rect_46}


```
 draw_ellipse_f(pen, rect) 
```

Рисует эллипс, определяемый ограничивающим [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) который определяет цвет, ширину и стиль эллипса. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), определяющая границы эллипса. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_47}


```
 draw_image(image, dest_points) 
```

Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение для отрисовки. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив из трёх структур PointF, определяющих параллелограмм. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_48}


```
 draw_image(image, dest_points) 
```

Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение для отрисовки. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив из трёх структур PointF, определяющих параллелограмм. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_49}


```
 draw_image(image, dest_points, src_rect) 
```

Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение для отрисовки. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив из трёх структур PointF, определяющих параллелограмм. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Исходный прямоугольник. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_50}


```
 draw_image(image, dest_points, src_rect) 
```

Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение для отрисовки. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив из трёх структур PointF, определяющих параллелограмм. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Исходный прямоугольник. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_51}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение для отрисовки. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив из трёх структур PointF, определяющих параллелограмм. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Исходный прямоугольник. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Единицы измерения. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_52}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение для отрисовки. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив из трёх структур PointF, определяющих параллелограмм. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Исходный прямоугольник. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Единицы измерения. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_53}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение для отрисовки. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив из трёх структур PointF, определяющих параллелограмм. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Исходный прямоугольник. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Единицы измерения. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Атрибуты изображения. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_54}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение для отрисовки. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив из трёх структур PointF, определяющих параллелограмм. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Исходный прямоугольник. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Единицы измерения. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Атрибуты изображения. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_55}


```
 draw_image(source_image, point) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), используя его оригинальный физический размер, в указанном месте.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) структура, представляющая верхний левый угол нарисованного изображения. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_56}


```
 draw_image(source_image, point) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), используя его оригинальный физический размер, в указанном месте.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) структура, представляющая верхний левый угол нарисованного изображения. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_57}


```
 draw_image(source_image, rect) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) структура, указывающая расположение и размер нарисованного изображения. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_58}


```
 draw_image(source_image, rect) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) структура, указывающая расположение и размер нарисованного изображения. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_59}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник назначения. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Графическая единица. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_60}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Прямоугольник назначения. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Графическая единица. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_61}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник назначения. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Графическая единица. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Атрибуты изображения. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_62}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Прямоугольник назначения. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Графическая единица. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Атрибуты изображения. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_63}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Исходный rect. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rect назначения. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Графическая единица. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_64}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Исходный rect. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Rect назначения. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Графическая единица. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_65}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Исходный rect. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rect назначения. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Графическая единица. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Атрибуты изображения. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_66}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Исходный rect. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Rect назначения. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Графическая единица. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Атрибуты изображения. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_67}


```
 draw_image(source_image, x, y) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), используя его оригинальный физический размер, в указанном месте.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| x | float | Координата x верхнего левого угла нарисованного изображения. |
| y | float | Координата y верхнего левого угла нарисованного изображения. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_68}


```
 draw_image(source_image, x, y) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), используя его оригинальный физический размер, в указанном месте.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| x | int | Координата x верхнего левого угла нарисованного изображения. |
| y | int | Координата y верхнего левого угла нарисованного изображения. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_69}


```
 draw_image(source_image, x, y, width, height) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| x | float | Координата x верхнего левого угла нарисованного изображения. |
| y | float | Координата y верхнего левого угла нарисованного изображения. |
| width | float | Ширина нарисованного изображения. |
| height | float | Высота нарисованного изображения. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_70}


```
 draw_image(source_image, x, y, width, height) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| x | int | Координата x верхнего левого угла нарисованного изображения. |
| y | int | Координата y верхнего левого угла нарисованного изображения. |
| width | int | Ширина нарисованного изображения. |
| height | int | Высота нарисованного изображения. |

### Method: draw_image_at_point(source_image, point) {#draw_image_at_point_source_image_point_71}


```
 draw_image_at_point(source_image, point) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), используя его оригинальный физический размер, в указанном месте.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) структура, представляющая верхний левый угол нарисованного изображения. |

### Method: draw_image_at_point_f(source_image, point) {#draw_image_at_point_f_source_image_point_72}


```
 draw_image_at_point_f(source_image, point) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), используя его оригинальный физический размер, в указанном месте.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) структура, представляющая верхний левый угол нарисованного изображения. |

### Method: draw_image_at_xy(source_image, x, y) {#draw_image_at_xy_source_image_x_y_73}


```
 draw_image_at_xy(source_image, x, y) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), используя его оригинальный физический размер, в указанном месте.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| x | int | Координата x верхнего левого угла нарисованного изображения. |
| y | int | Координата y верхнего левого угла нарисованного изображения. |

### Method: draw_image_at_xyf(source_image, x, y) {#draw_image_at_xyf_source_image_x_y_74}


```
 draw_image_at_xyf(source_image, x, y) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), используя его оригинальный физический размер, в указанном месте.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| x | float | Координата x верхнего левого угла нарисованного изображения. |
| y | float | Координата y верхнего левого угла нарисованного изображения. |

### Method: draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit) {#draw_image_dest_point_f_src_rect_f_with_unit_image_dest_points_src_rect_src_unit_75}


```
 draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit) 
```

Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение для отрисовки. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив из трёх структур PointF, определяющих параллелограмм. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Исходный прямоугольник. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Единицы измерения. |

### Method: draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_dest_point_f_src_rect_f_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_76}


```
 draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) 
```

Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение для отрисовки. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив из трёх структур PointF, определяющих параллелограмм. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Исходный прямоугольник. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Единицы измерения. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Атрибуты изображения. |

### Method: draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect) {#draw_image_dest_points_f_src_rect_f_image_dest_points_src_rect_77}


```
 draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect) 
```

Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение для отрисовки. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив из трёх структур PointF, определяющих параллелограмм. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Исходный прямоугольник. |

### Method: draw_image_dest_points_src_rect(image, dest_points, src_rect) {#draw_image_dest_points_src_rect_image_dest_points_src_rect_78}


```
 draw_image_dest_points_src_rect(image, dest_points, src_rect) 
```

Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение для отрисовки. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив из трёх структур PointF, определяющих параллелограмм. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Исходный прямоугольник. |

### Method: draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit) {#draw_image_dest_points_src_rect_with_unit_image_dest_points_src_rect_src_unit_79}


```
 draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit) 
```

Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение для отрисовки. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив из трёх структур PointF, определяющих параллелограмм. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Исходный прямоугольник. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Единицы измерения. |

### Method: draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_dest_points_src_rect_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_80}


```
 draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) 
```

Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение для отрисовки. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив из трёх структур PointF, определяющих параллелограмм. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Исходный прямоугольник. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Единицы измерения. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Атрибуты изображения. |

### Method: draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_dest_rect_f_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_81}


```
 draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Прямоугольник назначения, в котором выполнять отрисовку. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Графическая единица. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Атрибуты изображения. |

### Method: draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_dest_rect_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_82}


```
 draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник назначения. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Графическая единица. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Атрибуты изображения. |

### Method: draw_image_in_rect(source_image, x, y, width, height) {#draw_image_in_rect_source_image_x_y_width_height_83}


```
 draw_image_in_rect(source_image, x, y, width, height) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| x | int | Координата x верхнего левого угла нарисованного изображения. |
| y | int | Координата y верхнего левого угла нарисованного изображения. |
| width | int | Ширина нарисованного изображения. |
| height | int | Высота нарисованного изображения. |

### Method: draw_image_in_rect_f(source_image, x, y, width, height) {#draw_image_in_rect_f_source_image_x_y_width_height_84}


```
 draw_image_in_rect_f(source_image, x, y, width, height) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| x | float | Координата x верхнего левого угла нарисованного изображения. |
| y | float | Координата y верхнего левого угла нарисованного изображения. |
| width | float | Ширина нарисованного изображения. |
| height | float | Высота нарисованного изображения. |

### Method: draw_image_in_rectangle(source_image, rect) {#draw_image_in_rectangle_source_image_rect_85}


```
 draw_image_in_rectangle(source_image, rect) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) структура, указывающая расположение и размер нарисованного изображения. |

### Method: draw_image_points(image, dest_points) {#draw_image_points_image_dest_points_86}


```
 draw_image_points(image, dest_points) 
```

Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение для отрисовки. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив из трёх структур PointF, определяющих параллелограмм. |

### Method: draw_image_points_f(image, dest_points) {#draw_image_points_f_image_dest_points_87}


```
 draw_image_points_f(image, dest_points) 
```

Рисует указанную часть указанного _изображения_ в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение для отрисовки. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив из трёх структур PointF, определяющих параллелограмм. |

### Method: draw_image_rectangle_f(source_image, rect) {#draw_image_rectangle_f_source_image_rect_88}


```
 draw_image_rectangle_f(source_image, rect) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) структура, указывающая расположение и размер нарисованного изображения. |

### Method: draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_src_dest_rects_f_with_unit_source_image_rect_source_rect_destination_graphics_unit_89}


```
 draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Исходный rect. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Rect назначения. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Графическая единица. |

### Method: draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_src_dest_rects_with_unit_source_image_rect_source_rect_destination_graphics_unit_90}


```
 draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Исходный rect. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rect назначения. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Графическая единица. |

### Method: draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_src_dst_rect_f_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_91}


```
 draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Исходный прямоугольник. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Прямоугольник назначения. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Графическая единица для использования. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Атрибуты изображения для использования. |

### Method: draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_src_dst_rects_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_92}


```
 draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Исходный rect. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rect назначения. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Графическая единица. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Атрибуты изображения. |

### Method: draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit) {#draw_image_to_rect_f_with_unit_source_image_rect_destination_graphics_unit_93}


```
 draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Прямоугольник назначения. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Графическая единица. |

### Method: draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit) {#draw_image_to_rect_with_unit_source_image_rect_destination_graphics_unit_94}


```
 draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit) 
```

Рисует указанное [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник назначения. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Графическая единица. |

### Method: draw_image_unscaled(source_image, point) {#draw_image_unscaled_source_image_point_95}


```
 draw_image_unscaled(source_image, point) 
```

Рисует указанное изображение, используя его оригинальный физический размер, в указанном месте.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) структура, указывающая верхний левый угол нарисованного изображения. |

### Method: draw_image_unscaled(source_image, rect) {#draw_image_unscaled_source_image_rect_96}


```
 draw_image_unscaled(source_image, rect) 
```

Рисует указанное изображение, используя его оригинальный физический размер, в указанном месте.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) указывает верхний левый угол нарисованного изображения. Свойства X и Y прямоугольника указывают верхний левый угол. Свойства Width и Height игнорируются. |

### Method: draw_image_unscaled(source_image, x, y) {#draw_image_unscaled_source_image_x_y_97}


```
 draw_image_unscaled(source_image, x, y) 
```

Рисует указанное изображение, используя его оригинальный физический размер, в месте, указанном парой координат.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| x | int | Координата x верхнего левого угла нарисованного изображения. |
| y | int | Координата y верхнего левого угла нарисованного изображения. |

### Method: draw_image_unscaled(source_image, x, y, width, height) {#draw_image_unscaled_source_image_x_y_width_height_98}


```
 draw_image_unscaled(source_image, x, y, width, height) 
```

Рисует указанное изображение, используя его оригинальный физический размер, в указанном месте.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| x | int | Координата x верхнего левого угла нарисованного изображения. |
| y | int | Координата y верхнего левого угла нарисованного изображения. |
| width | int | Параметр не используется. |
| height | int | Параметр не используется. |

### Method: draw_image_unscaled_and_clipped(source_image, rect) {#draw_image_unscaled_and_clipped_source_image_rect_99}


```
 draw_image_unscaled_and_clipped(source_image, rect) 
```

Рисует указанное изображение без масштабирования и обрезает его при необходимости, чтобы вписать в указанный прямоугольник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник [Rectangle](/imaging/python-net/aspose.imaging/rectangle/), в котором отрисовывать изображение. |

### Method: draw_image_unscaled_in_rectangle(source_image, rect) {#draw_image_unscaled_in_rectangle_source_image_rect_100}


```
 draw_image_unscaled_in_rectangle(source_image, rect) 
```

Рисует указанное изображение, используя его оригинальный физический размер, в указанном месте.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) указывает верхний левый угол нарисованного изображения. Свойства X и Y прямоугольника указывают верхний левый угол. Свойства Width и Height игнорируются. |

### Method: draw_image_unscaled_to_point(source_image, point) {#draw_image_unscaled_to_point_source_image_point_101}


```
 draw_image_unscaled_to_point(source_image, point) 
```

Рисует указанное изображение, используя его оригинальный физический размер, в указанном месте.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Изображение, с которым выполнять отрисовку. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) структура, указывающая верхний левый угол нарисованного изображения. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_102}


```
 draw_line(pen, point1, point2) 
```

Рисует линию, соединяющую две структуры [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль линии. |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) структура, представляющая первую точку для соединения. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) структура, представляющая вторую точку для соединения. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_103}


```
 draw_line(pen, point1, point2) 
```

Рисует линию, соединяющую две структуры [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль линии. |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [Point](/imaging/python-net/aspose.imaging/point/) структура, представляющая первую точку для соединения. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [Point](/imaging/python-net/aspose.imaging/point/) структура, представляющая вторую точку для соединения. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_104}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Рисует линию, соединяющую две точки, указанные парами координат.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль линии. |
| x1 | int | Координата x первой точки. |
| y1 | int | Координата y первой точки. |
| x2 | int | Координата x второй точки. |
| y2 | int | Координата y второй точки. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_105}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Рисует линию, соединяющую две точки, указанные парами координат.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль линии. |
| x1 | float | Координата x первой точки. |
| y1 | float | Координата y первой точки. |
| x2 | float | Координата x второй точки. |
| y2 | float | Координата y второй точки. |

### Method: draw_line_by_xy(pen, x1, y1, x2, y2) {#draw_line_by_xy_pen_x1_y1_x2_y2_106}


```
 draw_line_by_xy(pen, x1, y1, x2, y2) 
```

Рисует линию, соединяющую две точки, указанные парами координат.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль линии. |
| x1 | int | Координата x первой точки. |
| y1 | int | Координата y первой точки. |
| x2 | int | Координата x второй точки. |
| y2 | int | Координата y второй точки. |

### Method: draw_line_f_by_xy(pen, x1, y1, x2, y2) {#draw_line_f_by_xy_pen_x1_y1_x2_y2_107}


```
 draw_line_f_by_xy(pen, x1, y1, x2, y2) 
```

Рисует линию, соединяющую две точки, указанные парами координат.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль линии. |
| x1 | float | Координата x первой точки. |
| y1 | float | Координата y первой точки. |
| x2 | float | Координата x второй точки. |
| y2 | float | Координата y второй точки. |

### Method: draw_line_point_f(pen, point1, point2) {#draw_line_point_f_pen_point1_point2_108}


```
 draw_line_point_f(pen, point1, point2) 
```

Рисует линию, соединяющую две структуры [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль линии. |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) структура, представляющая первую точку для соединения. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) структура, представляющая вторую точку для соединения. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_109}


```
 draw_lines(pen, points) 
```

Рисует серию отрезков, соединяющих массив структур [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль отрезков линии. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [Point](/imaging/python-net/aspose.imaging/point/), представляющих точки для соединения. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_110}


```
 draw_lines(pen, points) 
```

Рисует серию отрезков, соединяющих массив структур [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль отрезков линии. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [Point](/imaging/python-net/aspose.imaging/point/), представляющих точки для соединения. |

### Method: draw_lines_f(pen, points) {#draw_lines_f_pen_points_111}


```
 draw_lines_f(pen, points) 
```

Рисует серию отрезков, соединяющих массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль отрезков линии. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих точки для соединения. |

### Method: draw_path(pen, path) {#draw_path_pen_path_112}


```
 draw_path(pen, path) 
```

Рисует [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль пути. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) для рисования. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_113}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Рисует форму сектора, определяемую эллипсом, заданным структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) и двумя радиальными линиями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль формы сектора. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) структура, представляющая ограничивающий прямоугольник, определяющий эллипс, из которого формируется сектор. |
| start_angle | float | Угол, измеряемый в градусах по часовой стрелке от оси x до первой стороны сектора. |
| sweep_angle | float | Угол, измеряемый в градусах по часовой стрелке от параметра _startAngle_ до второй стороны сектора. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_114}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Рисует форму сектора, определяемую эллипсом, заданным структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) и двумя радиальными линиями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль формы сектора. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) структура, представляющая ограничивающий прямоугольник, определяющий эллипс, из которого формируется сектор. |
| start_angle | float | Угол, измеряемый в градусах по часовой стрелке от оси x до первой стороны сектора. |
| sweep_angle | float | Угол, измеряемый в градусах по часовой стрелке от параметра _startAngle_ до второй стороны сектора. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_115}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Рисует форму сектора, определяемую эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль формы сектора. |
| x | float | Координата x левого верхнего угла ограничивающего прямоугольника, определяющего эллипс, из которого формируется сектор. |
| y | float | Координата y левого верхнего угла ограничивающего прямоугольника, определяющего эллипс, из которого формируется сектор. |
| width | float | Ширина ограничивающего прямоугольника, определяющего эллипс, из которого формируется сектор. |
| height | float | Высота ограничивающего прямоугольника, определяющего эллипс, из которого формируется сектор. |
| start_angle | float | Угол, измеряемый в градусах по часовой стрелке от оси x до первой стороны сектора. |
| sweep_angle | float | Угол, измеряемый в градусах по часовой стрелке от параметра _startAngle_ до второй стороны сектора. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_116}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Рисует форму сектора, определяемую эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль формы сектора. |
| x | int | Координата x левого верхнего угла ограничивающего прямоугольника, определяющего эллипс, из которого формируется сектор. |
| y | int | Координата y левого верхнего угла ограничивающего прямоугольника, определяющего эллипс, из которого формируется сектор. |
| width | int | Ширина ограничивающего прямоугольника, определяющего эллипс, из которого формируется сектор. |
| height | int | Высота ограничивающего прямоугольника, определяющего эллипс, из которого формируется сектор. |
| start_angle | int | Угол, измеряемый в градусах по часовой стрелке от оси x до первой стороны сектора. |
| sweep_angle | int | Угол, измеряемый в градусах по часовой стрелке от параметра _startAngle_ до второй стороны сектора. |

### Method: draw_pie_in_rect(pen, rect, start_angle, sweep_angle) {#draw_pie_in_rect_pen_rect_start_angle_sweep_angle_117}


```
 draw_pie_in_rect(pen, rect, start_angle, sweep_angle) 
```

Рисует форму сектора, определяемую эллипсом, заданным структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) и двумя радиальными линиями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль формы сектора. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) структура, представляющая ограничивающий прямоугольник, определяющий эллипс, из которого формируется сектор. |
| start_angle | float | Угол, измеряемый в градусах по часовой стрелке от оси x до первой стороны сектора. |
| sweep_angle | float | Угол, измеряемый в градусах по часовой стрелке от параметра _startAngle_ до второй стороны сектора. |

### Method: draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle) {#draw_pie_in_rect_f_pen_rect_start_angle_sweep_angle_118}


```
 draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle) 
```

Рисует форму сектора, определяемую эллипсом, заданным структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) и двумя радиальными линиями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль формы сектора. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) структура, представляющая ограничивающий прямоугольник, определяющий эллипс, из которого формируется сектор. |
| start_angle | float | Угол, измеряемый в градусах по часовой стрелке от оси x до первой стороны сектора. |
| sweep_angle | float | Угол, измеряемый в градусах по часовой стрелке от параметра _startAngle_ до второй стороны сектора. |

### Method: draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_xy_pen_x_y_width_height_start_angle_sweep_angle_119}


```
 draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle) 
```

Рисует форму сектора, определяемую эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль формы сектора. |
| x | int | Координата x левого верхнего угла ограничивающего прямоугольника, определяющего эллипс, из которого формируется сектор. |
| y | int | Координата y левого верхнего угла ограничивающего прямоугольника, определяющего эллипс, из которого формируется сектор. |
| width | int | Ширина ограничивающего прямоугольника, определяющего эллипс, из которого формируется сектор. |
| height | int | Высота ограничивающего прямоугольника, определяющего эллипс, из которого формируется сектор. |
| start_angle | int | Угол, измеряемый в градусах по часовой стрелке от оси x до первой стороны сектора. |
| sweep_angle | int | Угол, измеряемый в градусах по часовой стрелке от параметра _startAngle_ до второй стороны сектора. |

### Method: draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_xyf_pen_x_y_width_height_start_angle_sweep_angle_120}


```
 draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle) 
```

Рисует форму сектора, определяемую эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль формы сектора. |
| x | float | Координата x левого верхнего угла ограничивающего прямоугольника, определяющего эллипс, из которого формируется сектор. |
| y | float | Координата y левого верхнего угла ограничивающего прямоугольника, определяющего эллипс, из которого формируется сектор. |
| width | float | Ширина ограничивающего прямоугольника, определяющего эллипс, из которого формируется сектор. |
| height | float | Высота ограничивающего прямоугольника, определяющего эллипс, из которого формируется сектор. |
| start_angle | float | Угол, измеряемый в градусах по часовой стрелке от оси x до первой стороны сектора. |
| sweep_angle | float | Угол, измеряемый в градусах по часовой стрелке от параметра _startAngle_ до второй стороны сектора. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_121}


```
 draw_polygon(pen, points) 
```

Рисует многоугольник, определяемый массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль многоугольника. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих вершины многоугольника. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_122}


```
 draw_polygon(pen, points) 
```

Рисует многоугольник, определяемый массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль многоугольника. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих вершины многоугольника. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_polygon_f(pen, points) {#draw_polygon_f_pen_points_123}


```
 draw_polygon_f(pen, points) 
```

Рисует многоугольник, определяемый массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль многоугольника. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих вершины многоугольника. |

### Method: draw_rect(pen, x, y, width, height) {#draw_rect_pen_x_y_width_height_124}


```
 draw_rect(pen, x, y, width, height) 
```

Рисует прямоугольник, заданный парой координат, шириной и высотой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Объект [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль прямоугольника. |
| x | int | Координата x левого верхнего угла прямоугольника для рисования. |
| y | int | Координата y левого верхнего угла прямоугольника для рисования. |
| width | int | Ширина прямоугольника для рисования. |
| height | int | Высота прямоугольника для рисования. |

### Method: draw_rect_f(pen, x, y, width, height) {#draw_rect_f_pen_x_y_width_height_125}


```
 draw_rect_f(pen, x, y, width, height) 
```

Рисует прямоугольник, заданный парой координат, шириной и высотой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Объект [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль прямоугольника. |
| x | float | Координата x левого верхнего угла прямоугольника для рисования. |
| y | float | Координата y левого верхнего угла прямоугольника для рисования. |
| width | float | Ширина прямоугольника для рисования. |
| height | float | Высота прямоугольника для рисования. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_126}


```
 draw_rectangle(pen, rect) 
```

Рисует прямоугольник, заданный структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Объект [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль прямоугольника. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) представляет прямоугольник для рисования. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_127}


```
 draw_rectangle(pen, rect) 
```

Рисует прямоугольник, заданный структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Объект [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль прямоугольника. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) представляет прямоугольник для рисования. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_128}


```
 draw_rectangle(pen, x, y, width, height) 
```

Рисует прямоугольник, заданный парой координат, шириной и высотой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Объект [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль прямоугольника. |
| x | float | Координата x левого верхнего угла прямоугольника для рисования. |
| y | float | Координата y левого верхнего угла прямоугольника для рисования. |
| width | float | Ширина прямоугольника для рисования. |
| height | float | Высота прямоугольника для рисования. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_129}


```
 draw_rectangle(pen, x, y, width, height) 
```

Рисует прямоугольник, заданный парой координат, шириной и высотой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Объект [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль прямоугольника. |
| x | int | Координата x левого верхнего угла прямоугольника для рисования. |
| y | int | Координата y левого верхнего угла прямоугольника для рисования. |
| width | int | Ширина прямоугольника для рисования. |
| height | int | Высота прямоугольника для рисования. |

### Method: draw_rectangle_f(pen, rect) {#draw_rectangle_f_pen_rect_130}


```
 draw_rectangle_f(pen, rect) 
```

Рисует прямоугольник, заданный структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Объект [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль прямоугольника. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) представляет прямоугольник для рисования. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_131}


```
 draw_rectangles(pen, rects) 
```

Рисует серию прямоугольников, заданных структурами [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль контуров прямоугольников. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Массив структур [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), представляющих прямоугольники для рисования. |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_132}


```
 draw_rectangles(pen, rects) 
```

Рисует серию прямоугольников, заданных структурами [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль контуров прямоугольников. |
| rects | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | Массив структур [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), представляющих прямоугольники для рисования. |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: draw_rectangles_f(pen, rects) {#draw_rectangles_f_pen_rects_133}


```
 draw_rectangles_f(pen, rects) 
```

Рисует серию прямоугольников, заданных структурами [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) определяет цвет, ширину и стиль контуров прямоугольников. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Массив структур [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), представляющих прямоугольники для рисования. |

### Method: draw_string(s, font, brush, layout_rectangle) {#draw_string_s_font_brush_layout_rectangle_134}


```
 draw_string(s, font, brush, layout_rectangle) 
```

Отрисовывает указанный текст в указанном прямоугольнике с указанным [Brush](/imaging/python-net/aspose.imaging/brush/) и [Font](/imaging/python-net/aspose.imaging/font/) объектами.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| s | string | Строка для рисования. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) определяет формат текста строки. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет цвет и текстуру нарисованного текста. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) указывает расположение нарисованного текста. |

### Method: draw_string(s, font, brush, layout_rectangle, format) {#draw_string_s_font_brush_layout_rectangle_format_135}


```
 draw_string(s, font, brush, layout_rectangle, format) 
```

Отрисовывает указанный текст в указанном прямоугольнике с указанным [Brush](/imaging/python-net/aspose.imaging/brush/) и [Font](/imaging/python-net/aspose.imaging/font/) объектами, используя атрибуты форматирования указанного [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| s | string | Строка для рисования. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) определяет формат текста строки. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет цвет и текстуру нарисованного текста. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) указывает расположение нарисованного текста. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) определяет атрибуты форматирования, такие как межстрочный интервал и выравнивание, применяемые к нарисованному тексту. |

### Method: draw_string(s, font, brush, point) {#draw_string_s_font_brush_point_136}


```
 draw_string(s, font, brush, point) 
```

Отрисовывает указанный текст в указанном месте с указанным [Brush](/imaging/python-net/aspose.imaging/brush/) и [Font](/imaging/python-net/aspose.imaging/font/) объектами.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| s | string | Строка для рисования. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) определяет формат текста строки. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет цвет и текстуру нарисованного текста. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/) указывает верхний левый угол нарисованного текста. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_string(s, font, brush, point, format) {#draw_string_s_font_brush_point_format_137}


```
 draw_string(s, font, brush, point, format) 
```

Отрисовывает указанный текст в указанном месте с указанным [Brush](/imaging/python-net/aspose.imaging/brush/) и [Font](/imaging/python-net/aspose.imaging/font/) объектами, используя атрибуты форматирования указанного [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| s | string | Строка для рисования. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) определяет формат текста строки. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет цвет и текстуру нарисованного текста. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/) указывает верхний левый угол нарисованного текста. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) определяет атрибуты форматирования, такие как межстрочный интервал и выравнивание, применяемые к нарисованному тексту. |

### Method: draw_string(s, font, brush, x, y) {#draw_string_s_font_brush_x_y_138}


```
 draw_string(s, font, brush, x, y) 
```

Отрисовывает указанный текст в указанном месте с указанным [Brush](/imaging/python-net/aspose.imaging/brush/) и [Font](/imaging/python-net/aspose.imaging/font/) объектами.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| s | string | Строка для рисования. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) определяет формат текста строки. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет цвет и текстуру нарисованного текста. |
| x | float | Координата x верхнего левого угла нарисованного текста. |
| y | float | Координата y верхнего левого угла нарисованного текста. |

### Method: draw_string(s, font, brush, x, y, format) {#draw_string_s_font_brush_x_y_format_139}


```
 draw_string(s, font, brush, x, y, format) 
```

Отрисовывает указанный текст в указанном месте с указанным [Brush](/imaging/python-net/aspose.imaging/brush/) и [Font](/imaging/python-net/aspose.imaging/font/) объектами, используя атрибуты форматирования указанного [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| s | string | Строка для рисования. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) определяет формат текста строки. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет цвет и текстуру нарисованного текста. |
| x | float | Координата x верхнего левого угла нарисованного текста. |
| y | float | Координата y верхнего левого угла нарисованного текста. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) определяет атрибуты форматирования, такие как межстрочный интервал и выравнивание, применяемые к нарисованному тексту. |

### Method: draw_string_at_point_f(s, font, brush, point) {#draw_string_at_point_f_s_font_brush_point_140}


```
 draw_string_at_point_f(s, font, brush, point) 
```

Отрисовывает указанный текст в указанном месте с указанным [Brush](/imaging/python-net/aspose.imaging/brush/) и [Font](/imaging/python-net/aspose.imaging/font/) объектами.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| s | string | Строка для рисования. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) определяет формат текста строки. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет цвет и текстуру нарисованного текста. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/) указывает верхний левый угол нарисованного текста. |

### Method: draw_string_at_point_f_format(s, font, brush, point, format) {#draw_string_at_point_f_format_s_font_brush_point_format_141}


```
 draw_string_at_point_f_format(s, font, brush, point, format) 
```

Отрисовывает указанный текст в указанном месте с указанным [Brush](/imaging/python-net/aspose.imaging/brush/) и [Font](/imaging/python-net/aspose.imaging/font/) объектами, используя атрибуты форматирования указанного [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| s | string | Строка для рисования. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) определяет формат текста строки. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет цвет и текстуру нарисованного текста. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/) указывает верхний левый угол нарисованного текста. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) определяет атрибуты форматирования, такие как межстрочный интервал и выравнивание, применяемые к нарисованному тексту. |

### Method: draw_string_at_xy(s, font, brush, x, y) {#draw_string_at_xy_s_font_brush_x_y_142}


```
 draw_string_at_xy(s, font, brush, x, y) 
```

Отрисовывает указанный текст в указанном месте с указанным [Brush](/imaging/python-net/aspose.imaging/brush/) и [Font](/imaging/python-net/aspose.imaging/font/) объектами.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| s | string | Строка для рисования. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) определяет формат текста строки. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет цвет и текстуру нарисованного текста. |
| x | float | Координата x верхнего левого угла нарисованного текста. |
| y | float | Координата y верхнего левого угла нарисованного текста. |

### Method: draw_string_in_rect(s, font, brush, layout_rectangle) {#draw_string_in_rect_s_font_brush_layout_rectangle_143}


```
 draw_string_in_rect(s, font, brush, layout_rectangle) 
```

Отрисовывает указанный текст в указанном прямоугольнике с указанным [Brush](/imaging/python-net/aspose.imaging/brush/) и [Font](/imaging/python-net/aspose.imaging/font/) объектами.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| s | string | Строка для рисования. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) определяет формат текста строки. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет цвет и текстуру нарисованного текста. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) указывает расположение нарисованного текста. |

### Method: draw_string_in_rect_f(s, font, brush, layout_rectangle, format) {#draw_string_in_rect_f_s_font_brush_layout_rectangle_format_144}


```
 draw_string_in_rect_f(s, font, brush, layout_rectangle, format) 
```

Отрисовывает указанный текст в указанном прямоугольнике с указанным [Brush](/imaging/python-net/aspose.imaging/brush/) и [Font](/imaging/python-net/aspose.imaging/font/) объектами, используя атрибуты форматирования указанного [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| s | string | Строка для рисования. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) определяет формат текста строки. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет цвет и текстуру нарисованного текста. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) указывает расположение нарисованного текста. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) определяет атрибуты форматирования, такие как межстрочный интервал и выравнивание, применяемые к нарисованному тексту. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_145}


```
 fill_closed_curve(brush, points) 
```

Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/). Этот метод использует напряжение по умолчанию 0.5 и режим заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), определяющих сплайн. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_146}


```
 fill_closed_curve(brush, points) 
```

Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/). Этот метод использует напряжение по умолчанию 0.5 и режим заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), определяющих сплайн. |

### Method: fill_closed_curve(brush, points, fill_mode) {#fill_closed_curve_brush_points_fill_mode_147}


```
 fill_closed_curve(brush, points, fill_mode) 
```

Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/), используя указанный режим заполнения. Этот метод использует напряжение по умолчанию 0.5.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), определяющих сплайн. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Элемент перечисления [FillMode](/imaging/python-net/aspose.imaging/fillmode/), определяющий способ заливки кривой. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_148}


```
 fill_closed_curve(brush, points, fillmode) 
```

Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/), используя указанный режим заполнения. Этот метод использует напряжение по умолчанию 0.5.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), определяющих сплайн. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) |  |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_149}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/), используя указанный режим заполнения и напряжение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Объект [Brush](/imaging/python-net/aspose.imaging/brush/), определяющий характеристики заливки. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), определяющих сплайн. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Элемент перечисления [FillMode](/imaging/python-net/aspose.imaging/fillmode/), определяющий способ заливки кривой. |
| натяжение | float | Значение, большее или равное 0.0F, которое задаёт натяжение кривой. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_150}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/), используя указанный режим заполнения и напряжение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Объект [Brush](/imaging/python-net/aspose.imaging/brush/), определяющий характеристики заливки. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), определяющих сплайн. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Элемент перечисления [FillMode](/imaging/python-net/aspose.imaging/fillmode/), определяющий способ заливки кривой. |
| натяжение | float | Значение, большее или равное 0.0F, которое задаёт натяжение кривой. |

### Method: fill_closed_curve_by_point(brush, points) {#fill_closed_curve_by_point_brush_points_151}


```
 fill_closed_curve_by_point(brush, points) 
```

Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/). Этот метод использует напряжение по умолчанию 0.5 и режим заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), определяющих сплайн. |

### Method: fill_closed_curve_by_point_f(brush, points) {#fill_closed_curve_by_point_f_brush_points_152}


```
 fill_closed_curve_by_point_f(brush, points) 
```

Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/). Этот метод использует напряжение по умолчанию 0.5 и режим заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), определяющих сплайн. |

### Method: fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension) {#fill_closed_curve_by_point_f_fill_mode_tension_brush_points_fillmode_tension_153}


```
 fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension) 
```

Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/imaging/python-net/aspose.imaging/pointf/), используя указанный режим заполнения и напряжение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Объект [Brush](/imaging/python-net/aspose.imaging/brush/), определяющий характеристики заливки. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), определяющих сплайн. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Элемент перечисления [FillMode](/imaging/python-net/aspose.imaging/fillmode/), определяющий способ заливки кривой. |
| натяжение | float | Значение, большее или равное 0.0F, которое задаёт натяжение кривой. |

### Method: fill_closed_curve_by_point_fill_mode(brush, points, fillmode) {#fill_closed_curve_by_point_fill_mode_brush_points_fillmode_154}


```
 fill_closed_curve_by_point_fill_mode(brush, points, fillmode) 
```

Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [Point](/imaging/python-net/aspose.imaging/point/), используя указанный режим заполнения. Этот метод использует напряжение по умолчанию 0.5.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [Point](/imaging/python-net/aspose.imaging/point/), определяющих сплайн. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Элемент перечисления [FillMode](/imaging/python-net/aspose.imaging/fillmode/), определяющий способ заливки кривой. |

### Method: fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension) {#fill_closed_curve_by_point_fill_mode_tension_brush_points_fillmode_tension_155}


```
 fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension) 
```

Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [Point](/imaging/python-net/aspose.imaging/point/), используя указанный режим заполнения и напряжение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [Point](/imaging/python-net/aspose.imaging/point/), определяющих сплайн. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Элемент перечисления [FillMode](/imaging/python-net/aspose.imaging/fillmode/), определяющий способ заливки кривой. |
| натяжение | float | Значение, большее или равное 0.0F, которое задаёт натяжение кривой. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_156}


```
 fill_ellipse(brush, rect) 
```

Заполняет внутреннюю часть эллипса, определенного ограничивающим прямоугольником, указанным структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) представляет ограничивающий прямоугольник, определяющий эллипс. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_157}


```
 fill_ellipse(brush, rect) 
```

Заполняет внутреннюю часть эллипса, определенного ограничивающим прямоугольником, указанным структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) представляет ограничивающий прямоугольник, определяющий эллипс. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_158}


```
 fill_ellipse(brush, x, y, width, height) 
```

Заполняет внутреннюю часть эллипса, определенного ограничивающим прямоугольником, заданным парой координат, шириной и высотой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| x | float | X‑координата левого верхнего угла ограничивающего прямоугольника, определяющего эллипс. |
| y | float | Y‑координата левого верхнего угла ограничивающего прямоугольника, определяющего эллипс. |
| width | float | Ширина ограничивающего прямоугольника, определяющего эллипс. |
| height | float | Высота ограничивающего прямоугольника, определяющего эллипс. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_159}


```
 fill_ellipse(brush, x, y, width, height) 
```

Заполняет внутреннюю часть эллипса, определенного ограничивающим прямоугольником, заданным парой координат, шириной и высотой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| x | int | X‑координата левого верхнего угла ограничивающего прямоугольника, определяющего эллипс. |
| y | int | Y‑координата левого верхнего угла ограничивающего прямоугольника, определяющего эллипс. |
| width | int | Ширина ограничивающего прямоугольника, определяющего эллипс. |
| height | int | Высота ограничивающего прямоугольника, определяющего эллипс. |

### Method: fill_ellipse_at_xywh(brush, x, y, width, height) {#fill_ellipse_at_xywh_brush_x_y_width_height_160}


```
 fill_ellipse_at_xywh(brush, x, y, width, height) 
```

Заполняет внутреннюю часть эллипса, определенного ограничивающим прямоугольником, заданным парой координат, шириной и высотой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| x | int | X‑координата левого верхнего угла ограничивающего прямоугольника, определяющего эллипс. |
| y | int | Y‑координата левого верхнего угла ограничивающего прямоугольника, определяющего эллипс. |
| width | int | Ширина ограничивающего прямоугольника, определяющего эллипс. |
| height | int | Высота ограничивающего прямоугольника, определяющего эллипс. |

### Method: fill_ellipse_at_xywhf(brush, x, y, width, height) {#fill_ellipse_at_xywhf_brush_x_y_width_height_161}


```
 fill_ellipse_at_xywhf(brush, x, y, width, height) 
```

Заполняет внутреннюю часть эллипса, определенного ограничивающим прямоугольником, заданным парой координат, шириной и высотой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| x | float | X‑координата левого верхнего угла ограничивающего прямоугольника, определяющего эллипс. |
| y | float | Y‑координата левого верхнего угла ограничивающего прямоугольника, определяющего эллипс. |
| width | float | Ширина ограничивающего прямоугольника, определяющего эллипс. |
| height | float | Высота ограничивающего прямоугольника, определяющего эллипс. |

### Method: fill_ellipse_in_rect(brush, rect) {#fill_ellipse_in_rect_brush_rect_162}


```
 fill_ellipse_in_rect(brush, rect) 
```

Заполняет внутреннюю часть эллипса, определенного ограничивающим прямоугольником, указанным структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) представляет ограничивающий прямоугольник, определяющий эллипс. |

### Method: fill_ellipse_in_rect_f(brush, rect) {#fill_ellipse_in_rect_f_brush_rect_163}


```
 fill_ellipse_in_rect_f(brush, rect) 
```

Заполняет внутреннюю часть эллипса, определенного ограничивающим прямоугольником, указанным структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) представляет ограничивающий прямоугольник, определяющий эллипс. |

### Method: fill_path(brush, path) {#fill_path_brush_path_164}


```
 fill_path(brush, path) 
```

Заполняет внутреннюю часть [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) представляет путь для заливки. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_165}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Заполняет внутреннюю часть сектора пирога, определенного эллипсом, указанным структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) и двумя радиальными линиями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) представляет ограничивающий прямоугольник, определяющий эллипс, из которого берётся сектор пирога. |
| start_angle | float | Угол в градусах, измеренный по часовой стрелке от оси x до первой стороны сектора пирога. |
| sweep_angle | float | Угол в градусах, измеренный по часовой стрелке от параметра _startAngle_ до второй стороны сектора пирога. |


**See also:**

**[Example # 1](#example_95)**: The following example shows how to compose an animated GIF image from individ...


### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_166}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Заполняет внутреннюю часть сектора пирога, определенного эллипсом, указанным структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) и двумя радиальными линиями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) представляет ограничивающий прямоугольник, определяющий эллипс, из которого берётся сектор пирога. |
| start_angle | float | Угол в градусах, измеренный по часовой стрелке от оси x до первой стороны сектора пирога. |
| sweep_angle | float | Угол в градусах, измеренный по часовой стрелке от параметра _startAngle_ до второй стороны сектора пирога. |


**See also:**

**[Example # 1](#example_95)**: The following example shows how to compose an animated GIF image from individ...


### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_167}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Заполняет внутреннюю часть сектора пирога, определенного эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| x | float | Координата x верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор пирога. |
| y | float | Координата y верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор пирога. |
| width | float | Ширина ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор пирога. |
| height | float | Высота ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор пирога. |
| start_angle | float | Угол в градусах, измеренный по часовой стрелке от оси x до первой стороны сектора пирога. |
| sweep_angle | float | Угол в градусах, измеренный по часовой стрелке от параметра _startAngle_ до второй стороны сектора пирога. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_168}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Заполняет внутреннюю часть сектора пирога, определенного эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| x | int | Координата x верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор пирога. |
| y | int | Координата y верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор пирога. |
| width | int | Ширина ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор пирога. |
| height | int | Высота ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор пирога. |
| start_angle | int | Угол в градусах, измеренный по часовой стрелке от оси x до первой стороны сектора пирога. |
| sweep_angle | int | Угол в градусах, измеренный по часовой стрелке от параметра _startAngle_ до второй стороны сектора пирога. |

### Method: fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_at_xy_brush_x_y_width_height_start_angle_sweep_angle_169}


```
 fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle) 
```

Заполняет внутреннюю часть сектора пирога, определенного эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| x | int | Координата x верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор пирога. |
| y | int | Координата y верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор пирога. |
| width | int | Ширина ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор пирога. |
| height | int | Высота ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор пирога. |
| start_angle | int | Угол в градусах, измеренный по часовой стрелке от оси x до первой стороны сектора пирога. |
| sweep_angle | int | Угол в градусах, измеренный по часовой стрелке от параметра _startAngle_ до второй стороны сектора пирога. |

### Method: fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_at_xyf_brush_x_y_width_height_start_angle_sweep_angle_170}


```
 fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle) 
```

Заполняет внутреннюю часть сектора пирога, определенного эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| x | float | Координата x верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор пирога. |
| y | float | Координата y верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор пирога. |
| width | float | Ширина ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор пирога. |
| height | float | Высота ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор пирога. |
| start_angle | float | Угол в градусах, измеренный по часовой стрелке от оси x до первой стороны сектора пирога. |
| sweep_angle | float | Угол в градусах, измеренный по часовой стрелке от параметра _startAngle_ до второй стороны сектора пирога. |

### Method: fill_pie_in_rect(brush, rect, start_angle, sweep_angle) {#fill_pie_in_rect_brush_rect_start_angle_sweep_angle_171}


```
 fill_pie_in_rect(brush, rect, start_angle, sweep_angle) 
```

Заполняет внутреннюю часть сектора пирога, определенного эллипсом, указанным структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) и двумя радиальными линиями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) представляет ограничивающий прямоугольник, определяющий эллипс, из которого берётся сектор пирога. |
| start_angle | float | Угол в градусах, измеренный по часовой стрелке от оси x до первой стороны сектора пирога. |
| sweep_angle | float | Угол в градусах, измеренный по часовой стрелке от параметра _startAngle_ до второй стороны сектора пирога. |

### Method: fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle) {#fill_pie_in_rect_f_brush_rect_start_angle_sweep_angle_172}


```
 fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle) 
```

Заполняет внутреннюю часть сектора пирога, определенного эллипсом, указанным структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) и двумя радиальными линиями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) структура, представляющая ограничивающий прямоугольник, определяющий эллипс, из которого берётся сектор пирога. |
| start_angle | float | Угол в градусах, измеренный по часовой стрелке от оси x до первой стороны сектора пирога. |
| sweep_angle | float | Угол в градусах, измеренный по часовой стрелке от параметра _startAngle_ до второй стороны сектора пирога. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_173}


```
 fill_polygon(brush, points) 
```

Заполняет внутреннюю часть многоугольника, определенного массивом точек, указанных структурами [PointF](/imaging/python-net/aspose.imaging/pointf/) и режимом заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих вершины полигона для заполнения. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_174}


```
 fill_polygon(brush, points) 
```

Заполняет внутреннюю часть многоугольника, определенного массивом точек, указанных структурами [PointF](/imaging/python-net/aspose.imaging/pointf/) и режимом заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих вершины полигона для заполнения. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_175}


```
 fill_polygon(brush, points, fill_mode) 
```

Заполняет внутреннюю часть многоугольника, определенного массивом точек, указанных структурами [PointF](/imaging/python-net/aspose.imaging/pointf/), используя указанный режим заполнения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих вершины полигона для заполнения. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Элемент перечисления [FillMode](/imaging/python-net/aspose.imaging/fillmode/), определяющий стиль заливки. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_176}


```
 fill_polygon(brush, points, fill_mode) 
```

Заполняет внутреннюю часть многоугольника, определенного массивом точек, указанных структурами [PointF](/imaging/python-net/aspose.imaging/pointf/), используя указанный режим заполнения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих вершины полигона для заполнения. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Элемент перечисления [FillMode](/imaging/python-net/aspose.imaging/fillmode/), определяющий стиль заливки. |

### Method: fill_polygon_by_point(brush, points) {#fill_polygon_by_point_brush_points_177}


```
 fill_polygon_by_point(brush, points) 
```

Заполняет внутреннюю часть многоугольника, определенного массивом точек, указанных структурами [PointF](/imaging/python-net/aspose.imaging/pointf/) и режимом заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих вершины полигона для заполнения. |

### Method: fill_polygon_by_point_f(brush, points) {#fill_polygon_by_point_f_brush_points_178}


```
 fill_polygon_by_point_f(brush, points) 
```

Заполняет внутреннюю часть многоугольника, определенного массивом точек, указанных структурами [PointF](/imaging/python-net/aspose.imaging/pointf/) и режимом заполнения [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих вершины полигона для заполнения. |

### Method: fill_polygon_by_point_f_fill_mode(brush, points, fill_mode) {#fill_polygon_by_point_f_fill_mode_brush_points_fill_mode_179}


```
 fill_polygon_by_point_f_fill_mode(brush, points, fill_mode) 
```

Заполняет внутреннюю часть многоугольника, определенного массивом точек, указанных структурами [PointF](/imaging/python-net/aspose.imaging/pointf/), используя указанный режим заполнения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих вершины полигона для заполнения. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Элемент перечисления [FillMode](/imaging/python-net/aspose.imaging/fillmode/), определяющий стиль заливки. |

### Method: fill_polygon_by_point_fill_mode(brush, points, fill_mode) {#fill_polygon_by_point_fill_mode_brush_points_fill_mode_180}


```
 fill_polygon_by_point_fill_mode(brush, points, fill_mode) 
```

Заполняет внутреннюю часть многоугольника, определенного массивом точек, указанных структурами [Point](/imaging/python-net/aspose.imaging/point/), используя указанный режим заполнения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [Point](/imaging/python-net/aspose.imaging/point/), представляющих вершины полигона для заполнения. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Элемент перечисления [FillMode](/imaging/python-net/aspose.imaging/fillmode/), определяющий стиль заливки. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_181}


```
 fill_rectangle(brush, rect) 
```

Заполняет внутреннюю часть прямоугольника, указанного структурой [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) структура, представляющая прямоугольник для заполнения. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_182}


```
 fill_rectangle(brush, rect) 
```

Заполняет внутреннюю часть прямоугольника, указанного структурой [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) структура, представляющая прямоугольник для заполнения. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_183}


```
 fill_rectangle(brush, x, y, width, height) 
```

Заполняет внутреннюю часть прямоугольника, заданного парой координат, шириной и высотой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| x | float | Координата x верхнего левого угла прямоугольника для заполнения. |
| y | float | Координата y верхнего левого угла прямоугольника для заполнения. |
| width | float | Ширина прямоугольника для заполнения. |
| height | float | Высота прямоугольника для заполнения. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_184}


```
 fill_rectangle(brush, x, y, width, height) 
```

Заполняет внутреннюю часть прямоугольника, заданного парой координат, шириной и высотой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| x | int | Координата x верхнего левого угла прямоугольника для заполнения. |
| y | int | Координата y верхнего левого угла прямоугольника для заполнения. |
| width | int | Ширина прямоугольника для заполнения. |
| height | int | Высота прямоугольника для заполнения. |

### Method: fill_rectangle_f(brush, rect) {#fill_rectangle_f_brush_rect_185}


```
 fill_rectangle_f(brush, rect) 
```

Заполняет внутреннюю часть прямоугольника, указанного структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) структура, представляющая прямоугольник для заполнения. |

### Method: fill_rectangle_f_with_brush(brush, x, y, width, height) {#fill_rectangle_f_with_brush_brush_x_y_width_height_186}


```
 fill_rectangle_f_with_brush(brush, x, y, width, height) 
```

Заполняет внутреннюю часть прямоугольника, заданного парой координат, шириной и высотой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| x | float | Координата x верхнего левого угла прямоугольника для заполнения. |
| y | float | Координата y верхнего левого угла прямоугольника для заполнения. |
| width | float | Ширина прямоугольника для заполнения. |
| height | float | Высота прямоугольника для заполнения. |

### Method: fill_rectangle_with_brush(brush, x, y, width, height) {#fill_rectangle_with_brush_brush_x_y_width_height_187}


```
 fill_rectangle_with_brush(brush, x, y, width, height) 
```

Заполняет внутреннюю часть прямоугольника, заданного парой координат, шириной и высотой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| x | int | Координата x верхнего левого угла прямоугольника для заполнения. |
| y | int | Координата y верхнего левого угла прямоугольника для заполнения. |
| width | int | Ширина прямоугольника для заполнения. |
| height | int | Высота прямоугольника для заполнения. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_188}


```
 fill_rectangles(brush, rects) 
```

Заполняет внутренние части серии прямоугольников, указанных структурами [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| rects | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | Массив структур [Rectangle](/imaging/python-net/aspose.imaging/rectangle/), представляющих прямоугольники для заполнения. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_189}


```
 fill_rectangles(brush, rects) 
```

Заполняет внутренние части серии прямоугольников, указанных структурами [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Массив структур [Rectangle](/imaging/python-net/aspose.imaging/rectangle/), представляющих прямоугольники для заполнения. |

### Method: fill_rectangles_f(brush, rects) {#fill_rectangles_f_brush_rects_190}


```
 fill_rectangles_f(brush, rects) 
```

Заполняет внутренние части серии прямоугольников, указанных структурами [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Массив структур [Rectangle](/imaging/python-net/aspose.imaging/rectangle/), представляющих прямоугольники для заполнения. |

### Method: fill_region(brush, region) {#fill_region_brush_region_191}


```
 fill_region(brush, region) 
```

Заполняет внутреннюю часть [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) определяет характеристики заливки. |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | [Region](/imaging/python-net/aspose.imaging/region/) представляет область для заполнения. |

### Method: measure_string(text, font, layout_area, string_format) {#measure_string_text_font_layout_area_string_format_192}


```
 measure_string(text, font, layout_area, string_format) 
```

Измеряет указанную строку текста с заданными параметрами

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | string | Текст для измерения. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Шрифт для измерения. |
| layout_area | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Область размещения. |
| string_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Формат строки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Размер в пикселях измеренной текстовой строки |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_193}


```
 multiply_transform(matrix) 
```

Умножает [Matrix](/imaging/python-net/aspose.imaging/matrix/), представляющий локальное геометрическое преобразование этого [Graphics](/imaging/python-net/aspose.imaging/graphics/), на указанный [Matrix](/imaging/python-net/aspose.imaging/matrix/) путем предварительного добавления указанного [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Матрица [Matrix](/imaging/python-net/aspose.imaging/matrix/), на которую следует умножить геометрическое преобразование. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_194}


```
 multiply_transform(matrix, order) 
```

Умножает [Matrix](/imaging/python-net/aspose.imaging/matrix/), представляющий локальное геометрическое преобразование этого [Graphics](/imaging/python-net/aspose.imaging/graphics/), на указанный [Matrix](/imaging/python-net/aspose.imaging/matrix/) в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Матрица [Matrix](/imaging/python-net/aspose.imaging/matrix/), на которую следует умножить геометрическое преобразование. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Структура [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/), указывающая порядок умножения двух матриц. |

### Method: rotate_transform(angle) {#rotate_transform_angle_195}


```
 rotate_transform(angle) 
```

Вращает локальное геометрическое преобразование на указанную величину. Этот метод предварительно добавляет вращение к преобразованию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол вращения. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_196}


```
 rotate_transform(angle, order) 
```

Вращает локальное геометрическое преобразование на указанную величину в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол вращения. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Структура [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/), указывающая, следует ли добавить в конец или в начало матрицу вращения. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_197}


```
 scale_transform(sx, sy) 
```

Масштабирует локальное геометрическое преобразование на указанные величины. Этот метод предварительно добавляет матрицу масштабирования к преобразованию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| sx | float | Величина масштабирования преобразования по оси x. |
| sy | float | Величина масштабирования преобразования по оси y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_198}


```
 scale_transform(sx, sy, order) 
```

Масштабирует локальное геометрическое преобразование на указанные величины в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| sx | float | Величина масштабирования преобразования по оси x. |
| sy | float | Величина масштабирования преобразования по оси y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Тип [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) который указывает, добавлять или предварять матрицу масштабирования. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_199}


```
 translate_transform(dx, dy) 
```

Смещает локальное геометрическое преобразование на указанные размеры. Этот метод предварительно добавляет трансляцию к преобразованию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_200}


```
 translate_transform(dx, dy, order) 
```

Смещает локальное геометрическое преобразование на указанные размеры в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Порядок (предварительно или последовательно), в котором применяется трансляция. |

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

#Создает экземпляр файлового потока.
with open(r"C:\temp\output.png", "w+b") as stream:
	#Создайте экземпляр PngOptions и задайте его различные свойства.
	pngOptions = PngOptions()
	#Установите источник для PngOptions.
	pngOptions.source = StreamSource(stream)
	#Создайте экземпляр Image
	with Image.create(pngOptions, 500, 500) as image:
		#Создайте и инициализируйте экземпляр класса Graphics.
		graphics = Graphics(image)
		#Очистить поверхность Graphics.
		graphics.clear(Color.wheat);
		#Нарисуйте дугу, указав объект Pen с черным цветом, 
		#прямоугольник, окружающий дугу, начальный угол и угол разворота
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#Нарисуйте кривую Безье, указав объект Pen с синим цветом и координатные точки.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#Нарисуйте кривую, указав объект Pen, имеющий зелёный цвет, и массив точек
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#Нарисуйте эллипс, используя объект Pen и окружающий прямоугольник
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#Нарисуйте линию 
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#Нарисуйте сегмент пирога
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#Нарисуйте многоугольник, указав объект Pen, имеющий красный цвет, и массив точек
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#Нарисуйте прямоугольник
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#Создайте объект SolidBrush и задайте его различные свойства
		brush = SolidBrush()
		brush.color = Color.purple
		#Нарисуйте строку, используя объект SolidBrush и Font, в конкретной точке
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# Сохраните все изменения.
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


# Создайте экземпляр файлового потока
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# Создайте экземпляр TiffOptions и установите его различные свойства
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Установите источник для экземпляра ImageOptions
	tiffOptions.source = StreamSource(stream)
	# Создайте экземпляр Image
	with Image.create(tiffOptions, 500, 500) as image:
		# Создайте и инициализируйте экземпляр класса Graphics.
		graphics = Graphics(image)
		# Очистить поверхность Graphics.
		graphics.clear(Color.wheat);
		# Создайте экземпляр класса GraphicsPath
		graphics_path = GraphicsPath()
		# Создайте экземпляр класса Figure
		figure = Figure()
		# Добавьте формы в объект Figure
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# Добавьте объект Figure в GraphicsPath
		graphics_path.add_figure(figure)
		# Нарисуйте путь с объектом Pen цвета Black
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# Сохраните все изменения.
		image.save()


```

### This example shows the creation and usage Pen objects. The example creates a new Image and draw rectangles on the Image surface. {#example_14}
``` python

from aspose.imaging import Image, Graphics, Color, Pen, Rectangle, Point, Size
from aspose.imaging.brushes import HatchBrush
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

# Создайте экземпляр BmpOptions и задайте его различные свойства
bmpOptions = BmpOptions()
bmpOptions.bits_per_pixel = 24
# Создайте экземпляр FileCreateSource и назначьте его в качестве Source для экземпляра BmpOptions
# Второй параметр типа Boolean определяет, будет ли создаваемый файл IsTemporal или нет
bmpOptions.source = FileCreateSource(r"C:\temp\sample.bmp", False)
# Создайте экземпляр Image по указанному пути
with Image.create(bmpOptions, 500, 500) as image:
	# Создайте экземпляр Graphics и инициализируйте его объектом Image
	graphics = Graphics(image)
	# Очистите поверхность Graphics белым цветом
	graphics.clear(Color.white)
	#Создайте экземпляр Pen с красным цветом и шириной 5
	pen = Pen(Color.red, 5.0);
	# Создайте экземпляр HatchBrush и задайте его свойства
	brush = HatchBrush()
	brush.background_color = Color.wheat;
	brush.foreground_color = Color.red;
	# Создайте экземпляр Pen
	# инициализировать его объектом HatchBrush и шириной
	brusedpen = Pen(brush, 5.0)
	# Рисовать прямоугольники, указывая объект Pen
	graphics.draw_rectangles(pen, [
		Rectangle(Point(210, 210), Size(100, 100)),
		Rectangle(Point(110, 110), Size(100, 100)),
		Rectangle(Point(310, 310), Size(100, 100)) ])

	# Рисовать прямоугольники, указывая объект Pen
	graphics.draw_rectangles(brusedpen, [
		Rectangle(Point(310, 110), Size(100, 100)),
		Rectangle(Point(110, 310), Size(100, 100)) ])

	# Сохраните все изменения.
	image.save()


```

### The following example shows how to compose an animated GIF image from individual GIF blocks. {#example_95}
``` python
from aspose.imaging.fileformats.gif.blocks import GifFrameBlock
from aspose.imaging.fileformats.gif import GifImage 
from aspose.imaging.brushes import SolidBrush
from aspose.imaging import Graphics, Color

# Создать GIF‑изображение 100 × 100 px.
# Первый блок по умолчанию полностью чёрный.
with GifFrameBlock(100, 100) as firstBlock:
	with GifImage(firstBlock) as gifImage:
		# Первый круг красный
		brush1 = SolidBrush(Color.red)

		# Второй круг чёрный
		brush2 = SolidBrush(Color.black)

		# Постепенно увеличивать угол красной дуги.
		for angle in range(10, 361, 10):
			block = GifFrameBlock(100, 100)
			gr = Graphics(block)
			gr.fill_pie(brush1, block.bounds, 0, angle)
			gifImage.add_block(block)
		
		# Постепенно увеличивать угол чёрной дуги и стирать красную дугу.
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
# Создать PNG‑изображение размером 100 × 100 px.
with PngImage(100, 100) as png_image:
	# Выполнить обработку изображения, например, заполнить всё изображение красным.
	graphics = Graphics(png_image)
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, png_image.bounds)
	# Сохранить в файл.
	png_image.save(join(dir_, "output.png"))


```

