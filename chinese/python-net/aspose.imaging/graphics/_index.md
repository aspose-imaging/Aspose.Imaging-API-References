---
title: "Graphics 类"
type: docs
weight: 5030
url: /zh/python-net/aspose.imaging/graphics/
---

**Summary:** Represents the graphics according to the graphics engine used in the current assembly.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Graphics

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [Graphics(source_image)](#Graphics_source_image_1) | 初始化 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| clip | [Region](/imaging/python-net/aspose.imaging/region/) | r/w | 获取或设置剪辑区域。 |
| compositing_quality | [CompositingQuality](/imaging/python-net/aspose.imaging/compositingquality/) | r/w | 获取或设置合成质量。 |
| dpi_x | float | r | 获取此 `aspose.imaging.Graphics` 的水平分辨率。 |
| dpi_y | float | r | 获取此 `aspose.imaging.Graphics` 的垂直分辨率。 |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | r | 获取图像。 |
| interpolation_mode | [InterpolationMode](/imaging/python-net/aspose.imaging/interpolationmode/) | r/w | 获取或设置插值模式。 |
| is_in_begin_update_call | bool | r | 获取一个值，指示图形是否处于 BeginUpdate 调用状态。 |
| page_scale | float | r/w | 获取或设置此 `aspose.imaging.Graphics` 的世界单位与页面单位之间的缩放比例。 |
| page_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | r/w | 获取或设置此 `aspose.imaging.Graphics` 中页面坐标使用的计量单位。 |
| paintable_image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | r/w | 获取或设置图像选项，用于创建可绘制的矢量图像。 |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | 获取或设置平滑模式。 |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | 获取或设置文本呈现提示。 |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | 获取或设置此 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 的几何世界变换的副本。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| begin_update() | 开始缓存以下图形操作。随后应用的图形效果不会立即生效，而是等到 EndUpdate 时一次性应用所有效果。 |
| [clear(color)](#clear_color_1) | 使用指定的颜色清除图形表面。 |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_2) | 绘制一个弧线，表示由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的椭圆的一部分。 |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_3) | 绘制一个弧线，表示由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的椭圆的一部分。 |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4) | 绘制一个弧线，表示由一对坐标、宽度和高度指定的椭圆的一部分。 |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5) | 绘制一个弧线，表示由一对坐标、宽度和高度指定的椭圆的一部分。 |
| [draw_arc_in_rect(pen, rect, start_angle, sweep_angle)](#draw_arc_in_rect_pen_rect_start_angle_sweep_angle_6) | 绘制一个弧线，表示由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的椭圆的一部分。 |
| [draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle)](#draw_arc_in_rect_f_pen_rect_start_angle_sweep_angle_7) | 绘制一个弧线，表示由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的椭圆的一部分。 |
| [draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_xy_pen_x_y_width_height_start_angle_sweep_angle_8) | 绘制一个弧线，表示由一对坐标、宽度和高度指定的椭圆的一部分。 |
| [draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_xyf_pen_x_y_width_height_start_angle_sweep_angle_9) | 绘制一个弧线，表示由一对坐标、宽度和高度指定的椭圆的一部分。 |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_10) | 绘制由四个 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构定义的贝塞尔样条。 |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_11) | 绘制由四个 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构定义的贝塞尔样条。 |
| [draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4)](#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_12) | 绘制由四个有序坐标对（表示点）定义的贝塞尔样条。 |
| [draw_bezier_by_points(pen, pt1, pt2, pt3, pt4)](#draw_bezier_by_points_pen_pt1_pt2_pt3_pt4_13) | 绘制由四个 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构定义的贝塞尔样条。 |
| [draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4)](#draw_bezier_by_points_f_pen_pt1_pt2_pt3_pt4_14) | 绘制由四个 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构定义的贝塞尔样条。 |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_15) | 从一个 [Point](/imaging/python-net/aspose.imaging/point/) 结构数组绘制一系列贝塞尔样条。 |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_16) | 从一个 [Point](/imaging/python-net/aspose.imaging/point/) 结构数组绘制一系列贝塞尔样条。 |
| [draw_beziers_by_pt_array(pen, points)](#draw_beziers_by_pt_array_pen_points_17) | 从一个 [Point](/imaging/python-net/aspose.imaging/point/) 结构数组绘制一系列贝塞尔样条。 |
| [draw_beziers_by_pt_array_f(pen, points)](#draw_beziers_by_pt_array_f_pen_points_18) | 从一个 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组绘制一系列贝塞尔样条。 |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_19) | 绘制由一组 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构定义的闭合基数样条。此方法使用默认张力 0.5 和 [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式。 |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_20) | 绘制由一组 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构定义的闭合基数样条。此方法使用默认张力 0.5 和 [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式。 |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_21) | 绘制由一组 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构定义的闭合基数样条，使用指定的张力。此方法使用默认的 [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式。 |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_22) | 绘制由一组 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构定义的闭合基数样条，使用指定的张力。此方法使用默认的 [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式。 |
| [draw_closed_curve_by_points(pen, points)](#draw_closed_curve_by_points_pen_points_23) | 绘制由一组 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构定义的闭合基数样条。此方法使用默认张力 0.5 和 [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式。 |
| [draw_closed_curve_by_points_f(pen, points)](#draw_closed_curve_by_points_f_pen_points_24) | 绘制由一组 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构定义的闭合基数样条。此方法使用默认张力 0.5 和 [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式。 |
| [draw_closed_curve_by_points_f_tension(pen, points, tension)](#draw_closed_curve_by_points_f_tension_pen_points_tension_25) | 绘制由一组 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构定义的闭合基数样条，使用指定的张力。此方法使用默认的 [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式。 |
| [draw_closed_curve_by_points_tension(pen, points, tension)](#draw_closed_curve_by_points_tension_pen_points_tension_26) | 绘制由一组 [Point](/imaging/python-net/aspose.imaging/point/) 结构定义的闭合基数样条，使用指定的张力。此方法使用默认的 [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式。 |
| [draw_curve(pen, points)](#draw_curve_pen_points_27) | 绘制通过指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组的基数样条。此方法使用默认张力 0.5。 |
| [draw_curve(pen, points)](#draw_curve_pen_points_28) | 绘制通过指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组的基数样条。此方法使用默认张力 0.5。 |
| [draw_curve(pen, points, offset, number_of_segments)](#draw_curve_pen_points_offset_number_of_segments_29) | 在指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组上绘制基数样条曲线。绘制从数组的起始位置偏移开始。<br/>            此方法使用默认张力 0.5。 |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_30) | 使用指定的张力，在指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组上绘制基数样条曲线。绘制从数组的起始位置偏移开始。 |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_31) | 使用指定的张力，在指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组上绘制基数样条曲线。绘制从数组的起始位置偏移开始。 |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_32) | 使用指定的张力，在指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组上绘制基数样条曲线。 |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_33) | 使用指定的张力，在指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组上绘制基数样条曲线。 |
| [draw_curve_by_point_fs(pen, points)](#draw_curve_by_point_fs_pen_points_34) | 在指定的 [Point](/imaging/python-net/aspose.imaging/point/) 结构数组上绘制基数样条曲线。 |
| [draw_curve_by_point_fs_tension(pen, points, tension)](#draw_curve_by_point_fs_tension_pen_points_tension_35) | 使用指定的张力，在指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组上绘制基数样条曲线。 |
| [draw_curve_by_points(pen, points)](#draw_curve_by_points_pen_points_36) | 绘制通过指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组的基数样条。此方法使用默认张力 0.5。 |
| [draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension)](#draw_curve_by_points_f_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_37) | 使用指定的张力，在指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组上绘制基数样条曲线。绘制从数组的起始位置偏移开始。 |
| [draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension)](#draw_curve_by_points_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_38) | 使用指定的张力，在指定的 [Point](/imaging/python-net/aspose.imaging/point/) 结构数组上绘制基数样条曲线。 |
| [draw_curve_by_points_tension(pen, points, tension)](#draw_curve_by_points_tension_pen_points_tension_39) | 使用指定的张力，在指定的 [Point](/imaging/python-net/aspose.imaging/point/) 结构数组上绘制基数样条曲线。 |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_40) | 绘制由边界 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 定义的椭圆。 |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_41) | 绘制由边界 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 定义的椭圆。 |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_42) | 绘制由一对坐标、一个高度和一个宽度指定的边界矩形定义的椭圆。 |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_43) | 绘制由一对坐标、一个高度和一个宽度指定的边界矩形定义的椭圆。 |
| [draw_ellipse_by_xy(pen, x, y, width, height)](#draw_ellipse_by_xy_pen_x_y_width_height_44) | 绘制由一对坐标、一个高度和一个宽度指定的边界矩形定义的椭圆。 |
| [draw_ellipse_by_xyf(pen, x, y, width, height)](#draw_ellipse_by_xyf_pen_x_y_width_height_45) | 绘制由一对坐标、一个高度和一个宽度指定的边界矩形定义的椭圆。 |
| [draw_ellipse_f(pen, rect)](#draw_ellipse_f_pen_rect_46) | 绘制由边界 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 定义的椭圆。 |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_47) | 在指定位置以指定尺寸绘制指定 _image_ 的指定部分。 |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_48) | 在指定位置以指定尺寸绘制指定 _image_ 的指定部分。 |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_49) | 在指定位置以指定尺寸绘制指定 _image_ 的指定部分。 |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_50) | 在指定位置以指定尺寸绘制指定 _image_ 的指定部分。 |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_51) | 在指定位置以指定尺寸绘制指定 _image_ 的指定部分。 |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_52) | 在指定位置以指定尺寸绘制指定 _image_ 的指定部分。 |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_53) | 在指定位置以指定尺寸绘制指定 _image_ 的指定部分。 |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_54) | 在指定位置以指定尺寸绘制指定 _image_ 的指定部分。 |
| [draw_image(source_image, point)](#draw_image_source_image_point_55) | 在指定位置绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)，使用其原始物理尺寸。 |
| [draw_image(source_image, point)](#draw_image_source_image_point_56) | 在指定位置绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)，使用其原始物理尺寸。 |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_57) | 在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。 |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_58) | 在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。 |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_59) | 在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。 |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_60) | 在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。 |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_61) | 在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。 |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_62) | 在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。 |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_63) | 在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。 |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_64) | 在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。 |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_65) | 在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。 |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_66) | 在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。 |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_67) | 在指定位置绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)，使用其原始物理尺寸。 |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_68) | 在指定位置绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)，使用其原始物理尺寸。 |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_69) | 在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。 |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_70) | 在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。 |
| [draw_image_at_point(source_image, point)](#draw_image_at_point_source_image_point_71) | 在指定位置绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)，使用其原始物理尺寸。 |
| [draw_image_at_point_f(source_image, point)](#draw_image_at_point_f_source_image_point_72) | 在指定位置绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)，使用其原始物理尺寸。 |
| [draw_image_at_xy(source_image, x, y)](#draw_image_at_xy_source_image_x_y_73) | 在指定位置绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)，使用其原始物理尺寸。 |
| [draw_image_at_xyf(source_image, x, y)](#draw_image_at_xyf_source_image_x_y_74) | 在指定位置绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)，使用其原始物理尺寸。 |
| [draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit)](#draw_image_dest_point_f_src_rect_f_with_unit_image_dest_points_src_rect_src_unit_75) | 在指定位置以指定尺寸绘制指定 _image_ 的指定部分。 |
| [draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_dest_point_f_src_rect_f_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_76) | 在指定位置以指定尺寸绘制指定 _image_ 的指定部分。 |
| [draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect)](#draw_image_dest_points_f_src_rect_f_image_dest_points_src_rect_77) | 在指定位置以指定尺寸绘制指定 _image_ 的指定部分。 |
| [draw_image_dest_points_src_rect(image, dest_points, src_rect)](#draw_image_dest_points_src_rect_image_dest_points_src_rect_78) | 在指定位置以指定尺寸绘制指定 _image_ 的指定部分。 |
| [draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit)](#draw_image_dest_points_src_rect_with_unit_image_dest_points_src_rect_src_unit_79) | 在指定位置以指定尺寸绘制指定 _image_ 的指定部分。 |
| [draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_dest_points_src_rect_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_80) | 在指定位置以指定尺寸绘制指定 _image_ 的指定部分。 |
| [draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_dest_rect_f_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_81) | 在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。 |
| [draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_dest_rect_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_82) | 在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。 |
| [draw_image_in_rect(source_image, x, y, width, height)](#draw_image_in_rect_source_image_x_y_width_height_83) | 在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。 |
| [draw_image_in_rect_f(source_image, x, y, width, height)](#draw_image_in_rect_f_source_image_x_y_width_height_84) | 在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。 |
| [draw_image_in_rectangle(source_image, rect)](#draw_image_in_rectangle_source_image_rect_85) | 在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。 |
| [draw_image_points(image, dest_points)](#draw_image_points_image_dest_points_86) | 在指定位置以指定尺寸绘制指定 _image_ 的指定部分。 |
| [draw_image_points_f(image, dest_points)](#draw_image_points_f_image_dest_points_87) | 在指定位置以指定尺寸绘制指定 _image_ 的指定部分。 |
| [draw_image_rectangle_f(source_image, rect)](#draw_image_rectangle_f_source_image_rect_88) | 在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。 |
| [draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_src_dest_rects_f_with_unit_source_image_rect_source_rect_destination_graphics_unit_89) | 在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。 |
| [draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_src_dest_rects_with_unit_source_image_rect_source_rect_destination_graphics_unit_90) | 在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。 |
| [draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_src_dst_rect_f_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_91) | 在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。 |
| [draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_src_dst_rects_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_92) | 在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。 |
| [draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit)](#draw_image_to_rect_f_with_unit_source_image_rect_destination_graphics_unit_93) | 在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。 |
| [draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit)](#draw_image_to_rect_with_unit_source_image_rect_destination_graphics_unit_94) | 在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。 |
| [draw_image_unscaled(source_image, point)](#draw_image_unscaled_source_image_point_95) | 在指定位置使用其原始物理尺寸绘制指定的图像。 |
| [draw_image_unscaled(source_image, rect)](#draw_image_unscaled_source_image_rect_96) | 在指定位置使用其原始物理尺寸绘制指定的图像。 |
| [draw_image_unscaled(source_image, x, y)](#draw_image_unscaled_source_image_x_y_97) | 在由坐标对指定的位置使用其原始物理尺寸绘制指定的图像。 |
| [draw_image_unscaled(source_image, x, y, width, height)](#draw_image_unscaled_source_image_x_y_width_height_98) | 在指定位置使用其原始物理尺寸绘制指定的图像。 |
| [draw_image_unscaled_and_clipped(source_image, rect)](#draw_image_unscaled_and_clipped_source_image_rect_99) | 在不缩放的情况下绘制指定的图像，并在必要时裁剪以适应指定的矩形。 |
| [draw_image_unscaled_in_rectangle(source_image, rect)](#draw_image_unscaled_in_rectangle_source_image_rect_100) | 在指定位置使用其原始物理尺寸绘制指定的图像。 |
| [draw_image_unscaled_to_point(source_image, point)](#draw_image_unscaled_to_point_source_image_point_101) | 在指定位置使用其原始物理尺寸绘制指定的图像。 |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_102) | 绘制连接两个 [Point](/imaging/python-net/aspose.imaging/point/) 结构的直线。 |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_103) | 绘制连接两个 [Point](/imaging/python-net/aspose.imaging/point/) 结构的直线。 |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_104) | 绘制连接由坐标对指定的两点的直线。 |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_105) | 绘制连接由坐标对指定的两点的直线。 |
| [draw_line_by_xy(pen, x1, y1, x2, y2)](#draw_line_by_xy_pen_x1_y1_x2_y2_106) | 绘制连接由坐标对指定的两点的直线。 |
| [draw_line_f_by_xy(pen, x1, y1, x2, y2)](#draw_line_f_by_xy_pen_x1_y1_x2_y2_107) | 绘制连接由坐标对指定的两点的直线。 |
| [draw_line_point_f(pen, point1, point2)](#draw_line_point_f_pen_point1_point2_108) | 绘制连接两个 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构的直线。 |
| [draw_lines(pen, points)](#draw_lines_pen_points_109) | 绘制一系列连接 [Point](/imaging/python-net/aspose.imaging/point/) 结构数组的线段。 |
| [draw_lines(pen, points)](#draw_lines_pen_points_110) | 绘制一系列连接 [Point](/imaging/python-net/aspose.imaging/point/) 结构数组的线段。 |
| [draw_lines_f(pen, points)](#draw_lines_f_pen_points_111) | 绘制一系列连接 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组的线段。 |
| [draw_path(pen, path)](#draw_path_pen_path_112) | 绘制一个 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)。 |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_113) | 绘制由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的椭圆和两条径向线定义的饼形。 |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_114) | 绘制由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的椭圆和两条径向线定义的饼形。 |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_115) | 绘制由坐标对、宽度、高度以及两条径向线指定的椭圆定义的饼形。 |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_116) | 绘制由坐标对、宽度、高度以及两条径向线指定的椭圆定义的饼形。 |
| [draw_pie_in_rect(pen, rect, start_angle, sweep_angle)](#draw_pie_in_rect_pen_rect_start_angle_sweep_angle_117) | 绘制由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的椭圆和两条径向线定义的饼形。 |
| [draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle)](#draw_pie_in_rect_f_pen_rect_start_angle_sweep_angle_118) | 绘制由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的椭圆和两条径向线定义的饼形。 |
| [draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_xy_pen_x_y_width_height_start_angle_sweep_angle_119) | 绘制由坐标对、宽度、高度以及两条径向线指定的椭圆定义的饼形。 |
| [draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_xyf_pen_x_y_width_height_start_angle_sweep_angle_120) | 绘制由坐标对、宽度、高度以及两条径向线指定的椭圆定义的饼形。 |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_121) | 绘制由 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组定义的多边形。 |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_122) | 绘制由 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组定义的多边形。 |
| [draw_polygon_f(pen, points)](#draw_polygon_f_pen_points_123) | 绘制由 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组定义的多边形。 |
| [draw_rect(pen, x, y, width, height)](#draw_rect_pen_x_y_width_height_124) | 绘制由坐标对、宽度和高度指定的矩形。 |
| [draw_rect_f(pen, x, y, width, height)](#draw_rect_f_pen_x_y_width_height_125) | 绘制由坐标对、宽度和高度指定的矩形。 |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_126) | 绘制由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的矩形。 |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_127) | 绘制由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的矩形。 |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_128) | 绘制由坐标对、宽度和高度指定的矩形。 |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_129) | 绘制由坐标对、宽度和高度指定的矩形。 |
| [draw_rectangle_f(pen, rect)](#draw_rectangle_f_pen_rect_130) | 绘制由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的矩形。 |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_131) | 绘制由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的一系列矩形。 |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_132) | 绘制由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的一系列矩形。 |
| [draw_rectangles_f(pen, rects)](#draw_rectangles_f_pen_rects_133) | 绘制由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的一系列矩形。 |
| [draw_string(s, font, brush, layout_rectangle)](#draw_string_s_font_brush_layout_rectangle_134) | 在指定的矩形中使用指定的[Brush](/imaging/python-net/aspose.imaging/brush/)和[Font](/imaging/python-net/aspose.imaging/font/)对象绘制指定的文本字符串。 |
| [draw_string(s, font, brush, layout_rectangle, format)](#draw_string_s_font_brush_layout_rectangle_format_135) | 在指定的矩形中使用指定的[Brush](/imaging/python-net/aspose.imaging/brush/)和[Font](/imaging/python-net/aspose.imaging/font/)对象绘制指定的文本字符串，并使用指定的[StringFormat](/imaging/python-net/aspose.imaging/stringformat/)的格式属性。 |
| [draw_string(s, font, brush, point)](#draw_string_s_font_brush_point_136) | 在指定位置使用指定的[Brush](/imaging/python-net/aspose.imaging/brush/)和[Font](/imaging/python-net/aspose.imaging/font/)对象绘制指定的文本字符串。 |
| [draw_string(s, font, brush, point, format)](#draw_string_s_font_brush_point_format_137) | 在指定位置使用指定的[Brush](/imaging/python-net/aspose.imaging/brush/)和[Font](/imaging/python-net/aspose.imaging/font/)对象绘制指定的文本字符串，并使用指定的[StringFormat](/imaging/python-net/aspose.imaging/stringformat/)的格式属性。 |
| [draw_string(s, font, brush, x, y)](#draw_string_s_font_brush_x_y_138) | 在指定位置使用指定的[Brush](/imaging/python-net/aspose.imaging/brush/)和[Font](/imaging/python-net/aspose.imaging/font/)对象绘制指定的文本字符串。 |
| [draw_string(s, font, brush, x, y, format)](#draw_string_s_font_brush_x_y_format_139) | 在指定位置使用指定的[Brush](/imaging/python-net/aspose.imaging/brush/)和[Font](/imaging/python-net/aspose.imaging/font/)对象绘制指定的文本字符串，并使用指定的[StringFormat](/imaging/python-net/aspose.imaging/stringformat/)的格式属性。 |
| [draw_string_at_point_f(s, font, brush, point)](#draw_string_at_point_f_s_font_brush_point_140) | 在指定位置使用指定的[Brush](/imaging/python-net/aspose.imaging/brush/)和[Font](/imaging/python-net/aspose.imaging/font/)对象绘制指定的文本字符串。 |
| [draw_string_at_point_f_format(s, font, brush, point, format)](#draw_string_at_point_f_format_s_font_brush_point_format_141) | 在指定位置使用指定的[Brush](/imaging/python-net/aspose.imaging/brush/)和[Font](/imaging/python-net/aspose.imaging/font/)对象绘制指定的文本字符串，并使用指定的[StringFormat](/imaging/python-net/aspose.imaging/stringformat/)的格式属性。 |
| [draw_string_at_xy(s, font, brush, x, y)](#draw_string_at_xy_s_font_brush_x_y_142) | 在指定位置使用指定的[Brush](/imaging/python-net/aspose.imaging/brush/)和[Font](/imaging/python-net/aspose.imaging/font/)对象绘制指定的文本字符串。 |
| [draw_string_in_rect(s, font, brush, layout_rectangle)](#draw_string_in_rect_s_font_brush_layout_rectangle_143) | 在指定的矩形中使用指定的[Brush](/imaging/python-net/aspose.imaging/brush/)和[Font](/imaging/python-net/aspose.imaging/font/)对象绘制指定的文本字符串。 |
| [draw_string_in_rect_f(s, font, brush, layout_rectangle, format)](#draw_string_in_rect_f_s_font_brush_layout_rectangle_format_144) | 在指定的矩形中使用指定的[Brush](/imaging/python-net/aspose.imaging/brush/)和[Font](/imaging/python-net/aspose.imaging/font/)对象绘制指定的文本字符串，并使用指定的[StringFormat](/imaging/python-net/aspose.imaging/stringformat/)的格式属性。 |
| end_update() | 完成在调用 BeginUpdate 后开始的图形操作的缓存。调用此方法时，之前的图形操作将一次性应用。 |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_145) | 填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5 和 [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式。 |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_146) | 填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5 和 [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式。 |
| [fill_closed_curve(brush, points, fill_mode)](#fill_closed_curve_brush_points_fill_mode_147) | 填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构定义的闭合基数样条曲线的内部，使用指定的填充模式。此方法使用默认张力 0.5。 |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_148) | 填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构定义的闭合基数样条曲线的内部，使用指定的填充模式。此方法使用默认张力 0.5。 |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_149) | 填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构定义的闭合基数样条曲线的内部，使用指定的填充模式和张力。 |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_150) | 填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构定义的闭合基数样条曲线的内部，使用指定的填充模式和张力。 |
| [fill_closed_curve_by_point(brush, points)](#fill_closed_curve_by_point_brush_points_151) | 填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5 和 [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式。 |
| [fill_closed_curve_by_point_f(brush, points)](#fill_closed_curve_by_point_f_brush_points_152) | 填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5 和 [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式。 |
| fill_closed_curve_by_point_f_fill_mode(brush, points, fillmode) |  |
| [fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension)](#fill_closed_curve_by_point_f_fill_mode_tension_brush_points_fillmode_tension_153) | 填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构定义的闭合基数样条曲线的内部，使用指定的填充模式和张力。 |
| [fill_closed_curve_by_point_fill_mode(brush, points, fillmode)](#fill_closed_curve_by_point_fill_mode_brush_points_fillmode_154) | 填充由一组[Point](/imaging/python-net/aspose.imaging/point/)结构定义的闭合基数样条曲线的内部，使用指定的填充模式。此方法使用默认张力 0.5。 |
| [fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension)](#fill_closed_curve_by_point_fill_mode_tension_brush_points_fillmode_tension_155) | 填充由一组[Point](/imaging/python-net/aspose.imaging/point/)结构定义的闭合基数样条曲线的内部，使用指定的填充模式和张力。 |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_156) | 填充由[RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)结构指定的边界矩形所定义的椭圆的内部。 |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_157) | 填充由[RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)结构指定的边界矩形所定义的椭圆的内部。 |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_158) | 填充由一对坐标、宽度和高度指定的边界矩形所定义的椭圆的内部。 |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_159) | 填充由一对坐标、宽度和高度指定的边界矩形所定义的椭圆的内部。 |
| [fill_ellipse_at_xywh(brush, x, y, width, height)](#fill_ellipse_at_xywh_brush_x_y_width_height_160) | 填充由一对坐标、宽度和高度指定的边界矩形所定义的椭圆的内部。 |
| [fill_ellipse_at_xywhf(brush, x, y, width, height)](#fill_ellipse_at_xywhf_brush_x_y_width_height_161) | 填充由一对坐标、宽度和高度指定的边界矩形所定义的椭圆的内部。 |
| [fill_ellipse_in_rect(brush, rect)](#fill_ellipse_in_rect_brush_rect_162) | 填充由[RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)结构指定的边界矩形所定义的椭圆的内部。 |
| [fill_ellipse_in_rect_f(brush, rect)](#fill_ellipse_in_rect_f_brush_rect_163) | 填充由[RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)结构指定的边界矩形所定义的椭圆的内部。 |
| [fill_path(brush, path)](#fill_path_brush_path_164) | 填充[GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)的内部。 |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_165) | 填充由[RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)结构指定的椭圆和两条径向线所定义的饼形区域的内部。 |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_166) | 填充由[RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)结构指定的椭圆和两条径向线所定义的饼形区域的内部。 |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_167) | 填充由一对坐标、宽度和高度指定的椭圆和两条径向线所定义的饼形区域的内部。 |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_168) | 填充由一对坐标、宽度和高度指定的椭圆和两条径向线所定义的饼形区域的内部。 |
| [fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_at_xy_brush_x_y_width_height_start_angle_sweep_angle_169) | 填充由一对坐标、宽度和高度指定的椭圆和两条径向线所定义的饼形区域的内部。 |
| [fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_at_xyf_brush_x_y_width_height_start_angle_sweep_angle_170) | 填充由一对坐标、宽度和高度指定的椭圆和两条径向线所定义的饼形区域的内部。 |
| [fill_pie_in_rect(brush, rect, start_angle, sweep_angle)](#fill_pie_in_rect_brush_rect_start_angle_sweep_angle_171) | 填充由[RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)结构指定的椭圆和两条径向线所定义的饼形区域的内部。 |
| [fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle)](#fill_pie_in_rect_f_brush_rect_start_angle_sweep_angle_172) | 填充由[RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)结构指定的椭圆和两条径向线所定义的饼形区域的内部。 |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_173) | 填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构指定的点并使用[FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式定义的多边形的内部。 |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_174) | 填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构指定的点并使用[FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式定义的多边形的内部。 |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_175) | 填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构指定的点并使用指定的填充模式定义的多边形的内部。 |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_176) | 填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构指定的点并使用指定的填充模式定义的多边形的内部。 |
| [fill_polygon_by_point(brush, points)](#fill_polygon_by_point_brush_points_177) | 填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构指定的点并使用[FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式定义的多边形的内部。 |
| [fill_polygon_by_point_f(brush, points)](#fill_polygon_by_point_f_brush_points_178) | 填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构指定的点并使用[FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式定义的多边形的内部。 |
| [fill_polygon_by_point_f_fill_mode(brush, points, fill_mode)](#fill_polygon_by_point_f_fill_mode_brush_points_fill_mode_179) | 填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构指定的点并使用指定的填充模式定义的多边形的内部。 |
| [fill_polygon_by_point_fill_mode(brush, points, fill_mode)](#fill_polygon_by_point_fill_mode_brush_points_fill_mode_180) | 填充由一组[Point](/imaging/python-net/aspose.imaging/point/)结构指定的点并使用指定的填充模式定义的多边形的内部。 |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_181) | 填充由[Rectangle](/imaging/python-net/aspose.imaging/rectangle/)结构指定的矩形的内部。 |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_182) | 填充由[Rectangle](/imaging/python-net/aspose.imaging/rectangle/)结构指定的矩形的内部。 |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_183) | 填充由一对坐标、宽度和高度指定的矩形的内部。 |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_184) | 填充由一对坐标、宽度和高度指定的矩形的内部。 |
| [fill_rectangle_f(brush, rect)](#fill_rectangle_f_brush_rect_185) | 填充由[RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)结构指定的矩形的内部。 |
| [fill_rectangle_f_with_brush(brush, x, y, width, height)](#fill_rectangle_f_with_brush_brush_x_y_width_height_186) | 填充由一对坐标、宽度和高度指定的矩形的内部。 |
| [fill_rectangle_with_brush(brush, x, y, width, height)](#fill_rectangle_with_brush_brush_x_y_width_height_187) | 填充由一对坐标、宽度和高度指定的矩形的内部。 |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_188) | 填充由一系列[Rectangle](/imaging/python-net/aspose.imaging/rectangle/)结构指定的矩形的内部。 |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_189) | 填充由一系列[Rectangle](/imaging/python-net/aspose.imaging/rectangle/)结构指定的矩形的内部。 |
| [fill_rectangles_f(brush, rects)](#fill_rectangles_f_brush_rects_190) | 填充由一系列[RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)结构指定的矩形的内部。 |
| [fill_region(brush, region)](#fill_region_brush_region_191) | 填充 [Region](/imaging/python-net/aspose.imaging/region/) 的内部。 |
| [measure_string(text, font, layout_area, string_format)](#measure_string_text_font_layout_area_string_format_192) | 使用指定的参数测量指定的文本字符串 |
| [multiply_transform(matrix)](#multiply_transform_matrix_193) | 将表示此 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 的局部几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 与指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 相乘，并通过在前面添加指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 来实现。 |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_194) | 将表示此 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 的局部几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 与指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 按指定顺序相乘。 |
| reset_transform() | 将 [Graphics.transform](/imaging/python-net/aspose.imaging/graphics/) 属性重置为单位矩阵。 |
| [rotate_transform(angle)](#rotate_transform_angle_195) | 按指定量旋转本地几何变换。此方法将在变换前预置旋转。 |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_196) | 按指定量并按指定顺序旋转本地几何变换。 |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_197) | 按指定的比例缩放本地几何变换。此方法将在变换前预置缩放矩阵。 |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_198) | 按指定的比例并按指定顺序缩放本地几何变换。 |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_199) | 按指定的尺寸平移本地几何变换。此方法将在变换前预置平移。 |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_200) | 按指定的尺寸并按指定顺序平移本地几何变换。 |


### Constructor: Graphics(source_image) {#Graphics_source_image_1}


```
 Graphics(source_image) 
```

初始化 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 源图像。 |

### Method: clear(color) {#clear_color_1}


```
 clear(color) 
```

使用指定的颜色清除图形表面。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | 用于清除图形表面的颜色。 |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...

**[Example # 2](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_2}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

绘制一个弧线，表示由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的椭圆的一部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定弧线的颜色、宽度和样式。 |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构，定义椭圆的边界。 |
| start_angle | float | 角度（度），从 x 轴顺时针测量到弧线起始点。 |
| sweep_angle | float | 角度（度），从 _startAngle_ 参数顺时针测量到弧线结束点。 |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_3}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

绘制一个弧线，表示由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的椭圆的一部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定弧线的颜色、宽度和样式。 |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构，定义椭圆的边界。 |
| start_angle | float | 角度（度），从 x 轴顺时针测量到弧线起始点。 |
| sweep_angle | float | 角度（度），从 _startAngle_ 参数顺时针测量到弧线结束点。 |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

绘制一个弧线，表示由一对坐标、宽度和高度指定的椭圆的一部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定弧线的颜色、宽度和样式。 |
| x | float | 定义椭圆的矩形左上角的 x 坐标。 |
| y | float | 定义椭圆的矩形左上角的 y 坐标。 |
| width | float | 定义椭圆的矩形的宽度。 |
| height | float | 定义椭圆的矩形的高度。 |
| start_angle | float | 角度（度），从 x 轴顺时针测量到弧线起始点。 |
| sweep_angle | float | 角度（度），从 _startAngle_ 参数顺时针测量到弧线结束点。 |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

绘制一个弧线，表示由一对坐标、宽度和高度指定的椭圆的一部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定弧线的颜色、宽度和样式。 |
| x | int | 定义椭圆的矩形左上角的 x 坐标。 |
| y | int | 定义椭圆的矩形左上角的 y 坐标。 |
| width | int | 定义椭圆的矩形的宽度。 |
| height | int | 定义椭圆的矩形的高度。 |
| start_angle | int | 角度（度），从 x 轴顺时针测量到弧线起始点。 |
| sweep_angle | int | 角度（度），从 _startAngle_ 参数顺时针测量到弧线结束点。 |

### Method: draw_arc_in_rect(pen, rect, start_angle, sweep_angle) {#draw_arc_in_rect_pen_rect_start_angle_sweep_angle_6}


```
 draw_arc_in_rect(pen, rect, start_angle, sweep_angle) 
```

绘制一个弧线，表示由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的椭圆的一部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定弧线的颜色、宽度和样式。 |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构，定义椭圆的边界。 |
| start_angle | float | 角度（度），从 x 轴顺时针测量到弧线起始点。 |
| sweep_angle | float | 角度（度），从 _startAngle_ 参数顺时针测量到弧线结束点。 |

### Method: draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle) {#draw_arc_in_rect_f_pen_rect_start_angle_sweep_angle_7}


```
 draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle) 
```

绘制一个弧线，表示由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的椭圆的一部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定弧线的颜色、宽度和样式。 |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构，定义椭圆的边界。 |
| start_angle | float | 角度（度），从 x 轴顺时针测量到弧线起始点。 |
| sweep_angle | float | 角度（度），从 _startAngle_ 参数顺时针测量到弧线结束点。 |

### Method: draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_xy_pen_x_y_width_height_start_angle_sweep_angle_8}


```
 draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle) 
```

绘制一个弧线，表示由一对坐标、宽度和高度指定的椭圆的一部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定弧线的颜色、宽度和样式。 |
| x | int | 定义椭圆的矩形左上角的 x 坐标。 |
| y | int | 定义椭圆的矩形左上角的 y 坐标。 |
| width | int | 定义椭圆的矩形的宽度。 |
| height | int | 定义椭圆的矩形的高度。 |
| start_angle | int | 角度（度），从 x 轴顺时针测量到弧线起始点。 |
| sweep_angle | int | 角度（度），从 _startAngle_ 参数顺时针测量到弧线结束点。 |

### Method: draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_xyf_pen_x_y_width_height_start_angle_sweep_angle_9}


```
 draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle) 
```

绘制一个弧线，表示由一对坐标、宽度和高度指定的椭圆的一部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定弧线的颜色、宽度和样式。 |
| x | float | 定义椭圆的矩形左上角的 x 坐标。 |
| y | float | 定义椭圆的矩形左上角的 y 坐标。 |
| width | float | 定义椭圆的矩形的宽度。 |
| height | float | 定义椭圆的矩形的高度。 |
| start_angle | float | 角度（度），从 x 轴顺时针测量到弧线起始点。 |
| sweep_angle | float | 角度（度），从 _startAngle_ 参数顺时针测量到弧线结束点。 |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_10}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

绘制由四个 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构定义的贝塞尔样条。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定曲线的颜色、宽度和样式。 |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构，表示曲线的起始点。 |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构，表示曲线的第一个控制点。 |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构，表示曲线的第二个控制点。 |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构，表示曲线的结束点。 |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_11}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

绘制由四个 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构定义的贝塞尔样条。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定曲线的颜色、宽度和样式。 |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构，表示曲线的起始点。 |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构，表示曲线的第一个控制点。 |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构，表示曲线的第二个控制点。 |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构，表示曲线的结束点。 |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) {#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_12}


```
 draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) 
```

绘制由四个有序坐标对（表示点）定义的贝塞尔样条。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定曲线的颜色、宽度和样式。 |
| x1 | float | 曲线起始点的 x 坐标。 |
| y1 | float | 曲线起始点的 y 坐标。 |
| x2 | float | 曲线第一个控制点的 x 坐标。 |
| y2 | float | 曲线第一个控制点的 y 坐标。 |
| x3 | float | 曲线第二个控制点的 x 坐标。 |
| y3 | float | 曲线第二个控制点的 y 坐标。 |
| x4 | float | 曲线结束点的 x 坐标。 |
| y4 | float | 曲线结束点的 y 坐标。 |

### Method: draw_bezier_by_points(pen, pt1, pt2, pt3, pt4) {#draw_bezier_by_points_pen_pt1_pt2_pt3_pt4_13}


```
 draw_bezier_by_points(pen, pt1, pt2, pt3, pt4) 
```

绘制由四个 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构定义的贝塞尔样条。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定曲线的颜色、宽度和样式。 |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构，表示曲线的起始点。 |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构，表示曲线的第一个控制点。 |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构，表示曲线的第二个控制点。 |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构，表示曲线的结束点。 |

### Method: draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4) {#draw_bezier_by_points_f_pen_pt1_pt2_pt3_pt4_14}


```
 draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4) 
```

绘制由四个 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构定义的贝塞尔样条。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定曲线的颜色、宽度和样式。 |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构，表示曲线的起始点。 |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构，表示曲线的第一个控制点。 |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构，表示曲线的第二个控制点。 |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构，表示曲线的结束点。 |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_15}


```
 draw_beziers(pen, points) 
```

从一个 [Point](/imaging/python-net/aspose.imaging/point/) 结构数组绘制一系列贝塞尔样条。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定曲线的颜色、宽度和样式。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 表示决定曲线的点的 [Point](/imaging/python-net/aspose.imaging/point/) 结构数组。 |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_16}


```
 draw_beziers(pen, points) 
```

从一个 [Point](/imaging/python-net/aspose.imaging/point/) 结构数组绘制一系列贝塞尔样条。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定曲线的颜色、宽度和样式。 |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 表示决定曲线的点的 [Point](/imaging/python-net/aspose.imaging/point/) 结构数组。 |

### Method: draw_beziers_by_pt_array(pen, points) {#draw_beziers_by_pt_array_pen_points_17}


```
 draw_beziers_by_pt_array(pen, points) 
```

从一个 [Point](/imaging/python-net/aspose.imaging/point/) 结构数组绘制一系列贝塞尔样条。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定曲线的颜色、宽度和样式。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 表示决定曲线的点的 [Point](/imaging/python-net/aspose.imaging/point/) 结构数组。 |

### Method: draw_beziers_by_pt_array_f(pen, points) {#draw_beziers_by_pt_array_f_pen_points_18}


```
 draw_beziers_by_pt_array_f(pen, points) 
```

从一个 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组绘制一系列贝塞尔样条。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定曲线的颜色、宽度和样式。 |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 表示决定曲线的点的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_19}


```
 draw_closed_curve(pen, points) 
```

绘制由一组 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构定义的闭合基数样条。此方法使用默认张力 0.5 和 [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定曲线颜色、宽度和高度的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 定义样条的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_20}


```
 draw_closed_curve(pen, points) 
```

绘制由一组 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构定义的闭合基数样条。此方法使用默认张力 0.5 和 [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定曲线颜色、宽度和高度的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 定义样条的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_21}


```
 draw_closed_curve(pen, points, tension) 
```

绘制由一组 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构定义的闭合基数样条，使用指定的张力。此方法使用默认的 [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定曲线颜色、宽度和高度的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 定义样条的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |
| 张力 | float | 指定曲线张力的值，必须大于或等于 0.0F。 |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_22}


```
 draw_closed_curve(pen, points, tension) 
```

绘制由一组 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构定义的闭合基数样条，使用指定的张力。此方法使用默认的 [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定曲线颜色、宽度和高度的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 定义样条的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |
| 张力 | float | 指定曲线张力的值，必须大于或等于 0.0F。 |

### Method: draw_closed_curve_by_points(pen, points) {#draw_closed_curve_by_points_pen_points_23}


```
 draw_closed_curve_by_points(pen, points) 
```

绘制由一组 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构定义的闭合基数样条。此方法使用默认张力 0.5 和 [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定曲线颜色、宽度和高度的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 定义样条的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |

### Method: draw_closed_curve_by_points_f(pen, points) {#draw_closed_curve_by_points_f_pen_points_24}


```
 draw_closed_curve_by_points_f(pen, points) 
```

绘制由一组 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构定义的闭合基数样条。此方法使用默认张力 0.5 和 [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定曲线颜色、宽度和高度的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 定义样条的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |

### Method: draw_closed_curve_by_points_f_tension(pen, points, tension) {#draw_closed_curve_by_points_f_tension_pen_points_tension_25}


```
 draw_closed_curve_by_points_f_tension(pen, points, tension) 
```

绘制由一组 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构定义的闭合基数样条，使用指定的张力。此方法使用默认的 [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定曲线颜色、宽度和高度的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 定义样条的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |
| 张力 | float | 指定曲线张力的值，必须大于或等于 0.0F。 |

### Method: draw_closed_curve_by_points_tension(pen, points, tension) {#draw_closed_curve_by_points_tension_pen_points_tension_26}


```
 draw_closed_curve_by_points_tension(pen, points, tension) 
```

绘制由一组 [Point](/imaging/python-net/aspose.imaging/point/) 结构定义的闭合基数样条，使用指定的张力。此方法使用默认的 [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定曲线颜色、宽度和高度的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 定义样条的 [Point](/imaging/python-net/aspose.imaging/point/) 结构数组。 |
| 张力 | float | 指定曲线张力的值，必须大于或等于 0.0F。 |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_27}


```
 draw_curve(pen, points) 
```

绘制通过指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组的基数样条。此方法使用默认张力 0.5。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定曲线颜色、宽度和高度的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 定义样条的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_curve(pen, points) {#draw_curve_pen_points_28}


```
 draw_curve(pen, points) 
```

绘制通过指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组的基数样条。此方法使用默认张力 0.5。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定曲线颜色、宽度和高度的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 定义样条的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_curve(pen, points, offset, number_of_segments) {#draw_curve_pen_points_offset_number_of_segments_29}


```
 draw_curve(pen, points, offset, number_of_segments) 
```

在指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组上绘制基数样条曲线。绘制从数组的起始位置偏移开始。<br/>            此方法使用默认张力 0.5。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定曲线颜色、宽度和高度的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 定义样条的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |
| offset | int | 从 _points_ 参数数组的第一个元素到曲线起始点的偏移量。 |
| number_of_segments | int | 起始点之后要包含在曲线中的段数。 |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_30}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

使用指定的张力，在指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组上绘制基数样条曲线。绘制从数组的起始位置偏移开始。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定曲线颜色、宽度和高度的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 定义样条的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |
| offset | int | 从 _points_ 参数数组的第一个元素到曲线起始点的偏移量。 |
| number_of_segments | int | 起始点之后要包含在曲线中的段数。 |
| 张力 | float | 指定曲线张力的值，必须大于或等于 0.0F。 |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_31}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

使用指定的张力，在指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组上绘制基数样条曲线。绘制从数组的起始位置偏移开始。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定曲线颜色、宽度和高度的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 定义样条的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |
| offset | int | 从 _points_ 参数数组的第一个元素到曲线起始点的偏移量。 |
| number_of_segments | int | 起始点之后要包含在曲线中的段数。 |
| 张力 | float | 指定曲线张力的值，必须大于或等于 0.0F。 |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_32}


```
 draw_curve(pen, points, tension) 
```

使用指定的张力，在指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组上绘制基数样条曲线。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定曲线颜色、宽度和高度的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 表示定义曲线的点的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |
| 张力 | float | 指定曲线张力的值，必须大于或等于 0.0F。 |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_33}


```
 draw_curve(pen, points, tension) 
```

使用指定的张力，在指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组上绘制基数样条曲线。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定曲线颜色、宽度和高度的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 表示定义曲线的点的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |
| 张力 | float | 指定曲线张力的值，必须大于或等于 0.0F。 |

### Method: draw_curve_by_point_fs(pen, points) {#draw_curve_by_point_fs_pen_points_34}


```
 draw_curve_by_point_fs(pen, points) 
```

在指定的 [Point](/imaging/python-net/aspose.imaging/point/) 结构数组上绘制基数样条曲线。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定曲线颜色、宽度和高度的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 定义样条的 [Point](/imaging/python-net/aspose.imaging/point/) 结构数组。 |

### Method: draw_curve_by_point_fs_tension(pen, points, tension) {#draw_curve_by_point_fs_tension_pen_points_tension_35}


```
 draw_curve_by_point_fs_tension(pen, points, tension) 
```

使用指定的张力，在指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组上绘制基数样条曲线。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定曲线颜色、宽度和高度的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 表示定义曲线的点的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |
| 张力 | float | 指定曲线张力的值，必须大于或等于 0.0F。 |

### Method: draw_curve_by_points(pen, points) {#draw_curve_by_points_pen_points_36}


```
 draw_curve_by_points(pen, points) 
```

绘制通过指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组的基数样条。此方法使用默认张力 0.5。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定曲线颜色、宽度和高度的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 定义样条的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |

### Method: draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) {#draw_curve_by_points_f_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_37}


```
 draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) 
```

使用指定的张力，在指定的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组上绘制基数样条曲线。绘制从数组的起始位置偏移开始。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定曲线颜色、宽度和高度的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 定义样条的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |
| offset | int | 从 _points_ 参数数组的第一个元素到曲线起始点的偏移量。 |
| number_of_segments | int | 起始点之后要包含在曲线中的段数。 |
| 张力 | float | 指定曲线张力的值，必须大于或等于 0.0F。 |

### Method: draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) {#draw_curve_by_points_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_38}


```
 draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) 
```

使用指定的张力，在指定的 [Point](/imaging/python-net/aspose.imaging/point/) 结构数组上绘制基数样条曲线。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定曲线颜色、宽度和高度的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 定义样条的 [Point](/imaging/python-net/aspose.imaging/point/) 结构数组。 |
| offset | int | 从 _points_ 参数数组的第一个元素到曲线起始点的偏移量。 |
| number_of_segments | int | 起始点之后要包含在曲线中的段数。 |
| 张力 | float | 指定曲线张力的值，必须大于或等于 0.0F。 |

### Method: draw_curve_by_points_tension(pen, points, tension) {#draw_curve_by_points_tension_pen_points_tension_39}


```
 draw_curve_by_points_tension(pen, points, tension) 
```

使用指定的张力，在指定的 [Point](/imaging/python-net/aspose.imaging/point/) 结构数组上绘制基数样条曲线。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定曲线颜色、宽度和高度的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 定义样条的 [Point](/imaging/python-net/aspose.imaging/point/) 结构数组。 |
| 张力 | float | 指定曲线张力的值，必须大于或等于 0.0F。 |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_40}


```
 draw_ellipse(pen, rect) 
```

绘制由边界 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 定义的椭圆。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定椭圆颜色、宽度和样式的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构，定义椭圆的边界。 |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_41}


```
 draw_ellipse(pen, rect) 
```

绘制由边界 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 定义的椭圆。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定椭圆颜色、宽度和样式的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构，定义椭圆的边界。 |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_42}


```
 draw_ellipse(pen, x, y, width, height) 
```

绘制由一对坐标、一个高度和一个宽度指定的边界矩形定义的椭圆。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定椭圆颜色、宽度和样式的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| x | float | 定义椭圆的边界矩形左上角的 x 坐标。 |
| y | float | 定义椭圆的边界矩形左上角的 y 坐标。 |
| width | float | 定义椭圆的边界矩形的宽度。 |
| height | float | 定义椭圆的边界矩形的高度。 |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_43}


```
 draw_ellipse(pen, x, y, width, height) 
```

绘制由一对坐标、一个高度和一个宽度指定的边界矩形定义的椭圆。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定椭圆颜色、宽度和样式的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| x | int | 定义椭圆的边界矩形左上角的 x 坐标。 |
| y | int | 定义椭圆的边界矩形左上角的 y 坐标。 |
| width | int | 定义椭圆的边界矩形的宽度。 |
| height | int | 定义椭圆的边界矩形的高度。 |

### Method: draw_ellipse_by_xy(pen, x, y, width, height) {#draw_ellipse_by_xy_pen_x_y_width_height_44}


```
 draw_ellipse_by_xy(pen, x, y, width, height) 
```

绘制由一对坐标、一个高度和一个宽度指定的边界矩形定义的椭圆。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定椭圆颜色、宽度和样式的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| x | int | 定义椭圆的边界矩形左上角的 x 坐标。 |
| y | int | 定义椭圆的边界矩形左上角的 y 坐标。 |
| width | int | 定义椭圆的边界矩形的宽度。 |
| height | int | 定义椭圆的边界矩形的高度。 |

### Method: draw_ellipse_by_xyf(pen, x, y, width, height) {#draw_ellipse_by_xyf_pen_x_y_width_height_45}


```
 draw_ellipse_by_xyf(pen, x, y, width, height) 
```

绘制由一对坐标、一个高度和一个宽度指定的边界矩形定义的椭圆。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定椭圆颜色、宽度和样式的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| x | float | 定义椭圆的边界矩形左上角的 x 坐标。 |
| y | float | 定义椭圆的边界矩形左上角的 y 坐标。 |
| width | float | 定义椭圆的边界矩形的宽度。 |
| height | float | 定义椭圆的边界矩形的高度。 |

### Method: draw_ellipse_f(pen, rect) {#draw_ellipse_f_pen_rect_46}


```
 draw_ellipse_f(pen, rect) 
```

绘制由边界 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 定义的椭圆。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定椭圆颜色、宽度和样式的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构，定义椭圆的边界。 |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_47}


```
 draw_image(image, dest_points) 
```

在指定位置以指定尺寸绘制指定 _image_ 的指定部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 要绘制的图像。 |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 由三个 PointF 结构组成的数组，用于定义平行四边形。 |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_48}


```
 draw_image(image, dest_points) 
```

在指定位置以指定尺寸绘制指定 _image_ 的指定部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 要绘制的图像。 |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 由三个 PointF 结构组成的数组，用于定义平行四边形。 |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_49}


```
 draw_image(image, dest_points, src_rect) 
```

在指定位置以指定尺寸绘制指定 _image_ 的指定部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 要绘制的图像。 |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 由三个 PointF 结构组成的数组，用于定义平行四边形。 |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 源矩形。 |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_50}


```
 draw_image(image, dest_points, src_rect) 
```

在指定位置以指定尺寸绘制指定 _image_ 的指定部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 要绘制的图像。 |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 由三个 PointF 结构组成的数组，用于定义平行四边形。 |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 源矩形。 |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_51}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

在指定位置以指定尺寸绘制指定 _image_ 的指定部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 要绘制的图像。 |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 由三个 PointF 结构组成的数组，用于定义平行四边形。 |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 源矩形。 |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 度量单位。 |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_52}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

在指定位置以指定尺寸绘制指定 _image_ 的指定部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 要绘制的图像。 |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 由三个 PointF 结构组成的数组，用于定义平行四边形。 |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 源矩形。 |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 度量单位。 |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_53}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

在指定位置以指定尺寸绘制指定 _image_ 的指定部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 要绘制的图像。 |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 由三个 PointF 结构组成的数组，用于定义平行四边形。 |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 源矩形。 |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 度量单位。 |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | 图像属性。 |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_54}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

在指定位置以指定尺寸绘制指定 _image_ 的指定部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 要绘制的图像。 |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 由三个 PointF 结构组成的数组，用于定义平行四边形。 |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 源矩形。 |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 度量单位。 |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | 图像属性。 |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_55}


```
 draw_image(source_image, point) 
```

在指定位置绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)，使用其原始物理尺寸。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构，表示绘制图像的左上角。 |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_56}


```
 draw_image(source_image, point) 
```

在指定位置绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)，使用其原始物理尺寸。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构，表示绘制图像的左上角。 |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_57}


```
 draw_image(source_image, rect) 
```

在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构，指定绘制图像的位置和大小。 |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_58}


```
 draw_image(source_image, rect) 
```

在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构，指定绘制图像的位置和大小。 |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_59}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 目标矩形。 |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 图形单位。 |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_60}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 目标矩形。 |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 图形单位。 |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_61}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 目标矩形。 |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 图形单位。 |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | 图像属性。 |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_62}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 目标矩形。 |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 图形单位。 |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | 图像属性。 |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_63}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 源矩形。 |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 目标矩形。 |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 图形单位。 |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_64}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 源矩形。 |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 目标矩形。 |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 图形单位。 |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_65}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 源矩形。 |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 目标矩形。 |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 图形单位。 |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | 图像属性。 |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_66}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 源矩形。 |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 目标矩形。 |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 图形单位。 |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | 图像属性。 |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_67}


```
 draw_image(source_image, x, y) 
```

在指定位置绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)，使用其原始物理尺寸。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| x | float | 绘制图像左上角的 x 坐标。 |
| y | float | 绘制图像左上角的 y 坐标。 |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_68}


```
 draw_image(source_image, x, y) 
```

在指定位置绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)，使用其原始物理尺寸。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| x | int | 绘制图像左上角的 x 坐标。 |
| y | int | 绘制图像左上角的 y 坐标。 |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_69}


```
 draw_image(source_image, x, y, width, height) 
```

在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| x | float | 绘制图像左上角的 x 坐标。 |
| y | float | 绘制图像左上角的 y 坐标。 |
| width | float | 绘制图像的宽度。 |
| height | float | 绘制图像的高度。 |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_70}


```
 draw_image(source_image, x, y, width, height) 
```

在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| x | int | 绘制图像左上角的 x 坐标。 |
| y | int | 绘制图像左上角的 y 坐标。 |
| width | int | 绘制图像的宽度。 |
| height | int | 绘制图像的高度。 |

### Method: draw_image_at_point(source_image, point) {#draw_image_at_point_source_image_point_71}


```
 draw_image_at_point(source_image, point) 
```

在指定位置绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)，使用其原始物理尺寸。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构，表示绘制图像的左上角。 |

### Method: draw_image_at_point_f(source_image, point) {#draw_image_at_point_f_source_image_point_72}


```
 draw_image_at_point_f(source_image, point) 
```

在指定位置绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)，使用其原始物理尺寸。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构，表示绘制图像的左上角。 |

### Method: draw_image_at_xy(source_image, x, y) {#draw_image_at_xy_source_image_x_y_73}


```
 draw_image_at_xy(source_image, x, y) 
```

在指定位置绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)，使用其原始物理尺寸。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| x | int | 绘制图像左上角的 x 坐标。 |
| y | int | 绘制图像左上角的 y 坐标。 |

### Method: draw_image_at_xyf(source_image, x, y) {#draw_image_at_xyf_source_image_x_y_74}


```
 draw_image_at_xyf(source_image, x, y) 
```

在指定位置绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)，使用其原始物理尺寸。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| x | float | 绘制图像左上角的 x 坐标。 |
| y | float | 绘制图像左上角的 y 坐标。 |

### Method: draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit) {#draw_image_dest_point_f_src_rect_f_with_unit_image_dest_points_src_rect_src_unit_75}


```
 draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit) 
```

在指定位置以指定尺寸绘制指定 _image_ 的指定部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 要绘制的图像。 |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 由三个 PointF 结构组成的数组，用于定义平行四边形。 |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 源矩形。 |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 度量单位。 |

### Method: draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_dest_point_f_src_rect_f_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_76}


```
 draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) 
```

在指定位置以指定尺寸绘制指定 _image_ 的指定部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 要绘制的图像。 |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 由三个 PointF 结构组成的数组，用于定义平行四边形。 |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 源矩形。 |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 度量单位。 |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | 图像属性。 |

### Method: draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect) {#draw_image_dest_points_f_src_rect_f_image_dest_points_src_rect_77}


```
 draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect) 
```

在指定位置以指定尺寸绘制指定 _image_ 的指定部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 要绘制的图像。 |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 由三个 PointF 结构组成的数组，用于定义平行四边形。 |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 源矩形。 |

### Method: draw_image_dest_points_src_rect(image, dest_points, src_rect) {#draw_image_dest_points_src_rect_image_dest_points_src_rect_78}


```
 draw_image_dest_points_src_rect(image, dest_points, src_rect) 
```

在指定位置以指定尺寸绘制指定 _image_ 的指定部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 要绘制的图像。 |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 由三个 PointF 结构组成的数组，用于定义平行四边形。 |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 源矩形。 |

### Method: draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit) {#draw_image_dest_points_src_rect_with_unit_image_dest_points_src_rect_src_unit_79}


```
 draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit) 
```

在指定位置以指定尺寸绘制指定 _image_ 的指定部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 要绘制的图像。 |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 由三个 PointF 结构组成的数组，用于定义平行四边形。 |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 源矩形。 |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 度量单位。 |

### Method: draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_dest_points_src_rect_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_80}


```
 draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) 
```

在指定位置以指定尺寸绘制指定 _image_ 的指定部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 要绘制的图像。 |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 由三个 PointF 结构组成的数组，用于定义平行四边形。 |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 源矩形。 |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 度量单位。 |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | 图像属性。 |

### Method: draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_dest_rect_f_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_81}


```
 draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) 
```

在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 用于绘制的目标矩形。 |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 图形单位。 |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | 图像属性。 |

### Method: draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_dest_rect_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_82}


```
 draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) 
```

在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 目标矩形。 |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 图形单位。 |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | 图像属性。 |

### Method: draw_image_in_rect(source_image, x, y, width, height) {#draw_image_in_rect_source_image_x_y_width_height_83}


```
 draw_image_in_rect(source_image, x, y, width, height) 
```

在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| x | int | 绘制图像左上角的 x 坐标。 |
| y | int | 绘制图像左上角的 y 坐标。 |
| width | int | 绘制图像的宽度。 |
| height | int | 绘制图像的高度。 |

### Method: draw_image_in_rect_f(source_image, x, y, width, height) {#draw_image_in_rect_f_source_image_x_y_width_height_84}


```
 draw_image_in_rect_f(source_image, x, y, width, height) 
```

在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| x | float | 绘制图像左上角的 x 坐标。 |
| y | float | 绘制图像左上角的 y 坐标。 |
| width | float | 绘制图像的宽度。 |
| height | float | 绘制图像的高度。 |

### Method: draw_image_in_rectangle(source_image, rect) {#draw_image_in_rectangle_source_image_rect_85}


```
 draw_image_in_rectangle(source_image, rect) 
```

在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构，指定绘制图像的位置和大小。 |

### Method: draw_image_points(image, dest_points) {#draw_image_points_image_dest_points_86}


```
 draw_image_points(image, dest_points) 
```

在指定位置以指定尺寸绘制指定 _image_ 的指定部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 要绘制的图像。 |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 由三个 PointF 结构组成的数组，用于定义平行四边形。 |

### Method: draw_image_points_f(image, dest_points) {#draw_image_points_f_image_dest_points_87}


```
 draw_image_points_f(image, dest_points) 
```

在指定位置以指定尺寸绘制指定 _image_ 的指定部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 要绘制的图像。 |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 由三个 PointF 结构组成的数组，用于定义平行四边形。 |

### Method: draw_image_rectangle_f(source_image, rect) {#draw_image_rectangle_f_source_image_rect_88}


```
 draw_image_rectangle_f(source_image, rect) 
```

在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构，指定绘制图像的位置和大小。 |

### Method: draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_src_dest_rects_f_with_unit_source_image_rect_source_rect_destination_graphics_unit_89}


```
 draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit) 
```

在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 源矩形。 |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 目标矩形。 |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 图形单位。 |

### Method: draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_src_dest_rects_with_unit_source_image_rect_source_rect_destination_graphics_unit_90}


```
 draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit) 
```

在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 源矩形。 |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 目标矩形。 |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 图形单位。 |

### Method: draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_src_dst_rect_f_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_91}


```
 draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 源矩形。 |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 目标矩形。 |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 要使用的图形单位。 |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | 要使用的图像属性。 |

### Method: draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_src_dst_rects_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_92}


```
 draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 源矩形。 |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 目标矩形。 |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 图形单位。 |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | 图像属性。 |

### Method: draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit) {#draw_image_to_rect_f_with_unit_source_image_rect_destination_graphics_unit_93}


```
 draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit) 
```

在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 目标矩形。 |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 图形单位。 |

### Method: draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit) {#draw_image_to_rect_with_unit_source_image_rect_destination_graphics_unit_94}


```
 draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit) 
```

在指定位置以指定尺寸绘制指定的 [Graphics.image](/imaging/python-net/aspose.imaging/graphics/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 目标矩形。 |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 图形单位。 |

### Method: draw_image_unscaled(source_image, point) {#draw_image_unscaled_source_image_point_95}


```
 draw_image_unscaled(source_image, point) 
```

在指定位置使用其原始物理尺寸绘制指定的图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) 结构，指定绘制图像的左上角。 |

### Method: draw_image_unscaled(source_image, rect) {#draw_image_unscaled_source_image_rect_96}


```
 draw_image_unscaled(source_image, rect) 
```

在指定位置使用其原始物理尺寸绘制指定的图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)，指定绘制图像的左上角。矩形的 X 和 Y 属性指定左上角。Width 和 Height 属性将被忽略。 |

### Method: draw_image_unscaled(source_image, x, y) {#draw_image_unscaled_source_image_x_y_97}


```
 draw_image_unscaled(source_image, x, y) 
```

在由坐标对指定的位置使用其原始物理尺寸绘制指定的图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| x | int | 绘制图像左上角的 x 坐标。 |
| y | int | 绘制图像左上角的 y 坐标。 |

### Method: draw_image_unscaled(source_image, x, y, width, height) {#draw_image_unscaled_source_image_x_y_width_height_98}


```
 draw_image_unscaled(source_image, x, y, width, height) 
```

在指定位置使用其原始物理尺寸绘制指定的图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| x | int | 绘制图像左上角的 x 坐标。 |
| y | int | 绘制图像左上角的 y 坐标。 |
| width | int | 此参数未使用。 |
| height | int | 此参数未使用。 |

### Method: draw_image_unscaled_and_clipped(source_image, rect) {#draw_image_unscaled_and_clipped_source_image_rect_99}


```
 draw_image_unscaled_and_clipped(source_image, rect) 
```

在不缩放的情况下绘制指定的图像，并在必要时裁剪以适应指定的矩形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 在其中绘制图像的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。 |

### Method: draw_image_unscaled_in_rectangle(source_image, rect) {#draw_image_unscaled_in_rectangle_source_image_rect_100}


```
 draw_image_unscaled_in_rectangle(source_image, rect) 
```

在指定位置使用其原始物理尺寸绘制指定的图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)，指定绘制图像的左上角。矩形的 X 和 Y 属性指定左上角。Width 和 Height 属性将被忽略。 |

### Method: draw_image_unscaled_to_point(source_image, point) {#draw_image_unscaled_to_point_source_image_point_101}


```
 draw_image_unscaled_to_point(source_image, point) 
```

在指定位置使用其原始物理尺寸绘制指定的图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | 用于绘制的图像。 |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) 结构，指定绘制图像的左上角。 |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_102}


```
 draw_line(pen, point1, point2) 
```

绘制连接两个 [Point](/imaging/python-net/aspose.imaging/point/) 结构的直线。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定线条的颜色、宽度和样式。 |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) 结构，表示要连接的第一个点。 |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) 结构，表示要连接的第二个点。 |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_103}


```
 draw_line(pen, point1, point2) 
```

绘制连接两个 [Point](/imaging/python-net/aspose.imaging/point/) 结构的直线。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定线条的颜色、宽度和样式。 |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [Point](/imaging/python-net/aspose.imaging/point/) 结构，表示要连接的第一个点。 |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [Point](/imaging/python-net/aspose.imaging/point/) 结构，表示要连接的第二个点。 |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_104}


```
 draw_line(pen, x1, y1, x2, y2) 
```

绘制连接由坐标对指定的两点的直线。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定线条的颜色、宽度和样式。 |
| x1 | int | 第一个点的 x 坐标。 |
| y1 | int | 第一个点的 y 坐标。 |
| x2 | int | 第二个点的 x 坐标。 |
| y2 | int | 第二个点的 y 坐标。 |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_105}


```
 draw_line(pen, x1, y1, x2, y2) 
```

绘制连接由坐标对指定的两点的直线。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定线条的颜色、宽度和样式。 |
| x1 | float | 第一个点的 x 坐标。 |
| y1 | float | 第一个点的 y 坐标。 |
| x2 | float | 第二个点的 x 坐标。 |
| y2 | float | 第二个点的 y 坐标。 |

### Method: draw_line_by_xy(pen, x1, y1, x2, y2) {#draw_line_by_xy_pen_x1_y1_x2_y2_106}


```
 draw_line_by_xy(pen, x1, y1, x2, y2) 
```

绘制连接由坐标对指定的两点的直线。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定线条的颜色、宽度和样式。 |
| x1 | int | 第一个点的 x 坐标。 |
| y1 | int | 第一个点的 y 坐标。 |
| x2 | int | 第二个点的 x 坐标。 |
| y2 | int | 第二个点的 y 坐标。 |

### Method: draw_line_f_by_xy(pen, x1, y1, x2, y2) {#draw_line_f_by_xy_pen_x1_y1_x2_y2_107}


```
 draw_line_f_by_xy(pen, x1, y1, x2, y2) 
```

绘制连接由坐标对指定的两点的直线。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定线条的颜色、宽度和样式。 |
| x1 | float | 第一个点的 x 坐标。 |
| y1 | float | 第一个点的 y 坐标。 |
| x2 | float | 第二个点的 x 坐标。 |
| y2 | float | 第二个点的 y 坐标。 |

### Method: draw_line_point_f(pen, point1, point2) {#draw_line_point_f_pen_point1_point2_108}


```
 draw_line_point_f(pen, point1, point2) 
```

绘制连接两个 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构的直线。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定线条的颜色、宽度和样式。 |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构，表示要连接的第一个点。 |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构，表示要连接的第二个点。 |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_109}


```
 draw_lines(pen, points) 
```

绘制一系列连接 [Point](/imaging/python-net/aspose.imaging/point/) 结构数组的线段。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定线段的颜色、宽度和样式。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 表示要连接的点的 [Point](/imaging/python-net/aspose.imaging/point/) 结构数组。 |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_110}


```
 draw_lines(pen, points) 
```

绘制一系列连接 [Point](/imaging/python-net/aspose.imaging/point/) 结构数组的线段。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定线段的颜色、宽度和样式。 |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 表示要连接的点的 [Point](/imaging/python-net/aspose.imaging/point/) 结构数组。 |

### Method: draw_lines_f(pen, points) {#draw_lines_f_pen_points_111}


```
 draw_lines_f(pen, points) 
```

绘制一系列连接 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组的线段。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定线段的颜色、宽度和样式。 |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 表示要连接的点的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |

### Method: draw_path(pen, path) {#draw_path_pen_path_112}


```
 draw_path(pen, path) 
```

绘制一个 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定路径的颜色、宽度和样式。 |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 用于绘制的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)。 |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_113}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

绘制由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的椭圆和两条径向线定义的饼形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定饼形的颜色、宽度和样式。 |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构，表示定义饼形所在椭圆的外接矩形。 |
| start_angle | float | 从 x 轴顺时针测量到饼形第一边的角度（以度为单位）。 |
| sweep_angle | float | 从 _startAngle_ 参数顺时针测量到饼形第二边的角度（以度为单位）。 |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_114}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

绘制由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的椭圆和两条径向线定义的饼形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定饼形的颜色、宽度和样式。 |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构，表示定义饼形所在椭圆的外接矩形。 |
| start_angle | float | 从 x 轴顺时针测量到饼形第一边的角度（以度为单位）。 |
| sweep_angle | float | 从 _startAngle_ 参数顺时针测量到饼形第二边的角度（以度为单位）。 |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_115}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

绘制由坐标对、宽度、高度以及两条径向线指定的椭圆定义的饼形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定饼形的颜色、宽度和样式。 |
| x | float | 定义饼形所在椭圆的外接矩形左上角的 x 坐标。 |
| y | float | 定义饼形所在椭圆的外接矩形左上角的 y 坐标。 |
| width | float | 定义饼形所在椭圆的外接矩形的宽度。 |
| height | float | 定义饼形所在椭圆的外接矩形的高度。 |
| start_angle | float | 从 x 轴顺时针测量到饼形第一边的角度（以度为单位）。 |
| sweep_angle | float | 从 _startAngle_ 参数顺时针测量到饼形第二边的角度（以度为单位）。 |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_116}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

绘制由坐标对、宽度、高度以及两条径向线指定的椭圆定义的饼形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定饼形的颜色、宽度和样式。 |
| x | int | 定义饼形所在椭圆的外接矩形左上角的 x 坐标。 |
| y | int | 定义饼形所在椭圆的外接矩形左上角的 y 坐标。 |
| width | int | 定义饼形所在椭圆的外接矩形的宽度。 |
| height | int | 定义饼形所在椭圆的外接矩形的高度。 |
| start_angle | int | 从 x 轴顺时针测量到饼形第一边的角度（以度为单位）。 |
| sweep_angle | int | 从 _startAngle_ 参数顺时针测量到饼形第二边的角度（以度为单位）。 |

### Method: draw_pie_in_rect(pen, rect, start_angle, sweep_angle) {#draw_pie_in_rect_pen_rect_start_angle_sweep_angle_117}


```
 draw_pie_in_rect(pen, rect, start_angle, sweep_angle) 
```

绘制由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的椭圆和两条径向线定义的饼形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定饼形的颜色、宽度和样式。 |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构，表示定义饼形所在椭圆的外接矩形。 |
| start_angle | float | 从 x 轴顺时针测量到饼形第一边的角度（以度为单位）。 |
| sweep_angle | float | 从 _startAngle_ 参数顺时针测量到饼形第二边的角度（以度为单位）。 |

### Method: draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle) {#draw_pie_in_rect_f_pen_rect_start_angle_sweep_angle_118}


```
 draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle) 
```

绘制由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的椭圆和两条径向线定义的饼形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定饼形的颜色、宽度和样式。 |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构，表示定义饼形所在椭圆的外接矩形。 |
| start_angle | float | 从 x 轴顺时针测量到饼形第一边的角度（以度为单位）。 |
| sweep_angle | float | 从 _startAngle_ 参数顺时针测量到饼形第二边的角度（以度为单位）。 |

### Method: draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_xy_pen_x_y_width_height_start_angle_sweep_angle_119}


```
 draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle) 
```

绘制由坐标对、宽度、高度以及两条径向线指定的椭圆定义的饼形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定饼形的颜色、宽度和样式。 |
| x | int | 定义饼形所在椭圆的外接矩形左上角的 x 坐标。 |
| y | int | 定义饼形所在椭圆的外接矩形左上角的 y 坐标。 |
| width | int | 定义饼形所在椭圆的外接矩形的宽度。 |
| height | int | 定义饼形所在椭圆的外接矩形的高度。 |
| start_angle | int | 从 x 轴顺时针测量到饼形第一边的角度（以度为单位）。 |
| sweep_angle | int | 从 _startAngle_ 参数顺时针测量到饼形第二边的角度（以度为单位）。 |

### Method: draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_xyf_pen_x_y_width_height_start_angle_sweep_angle_120}


```
 draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle) 
```

绘制由坐标对、宽度、高度以及两条径向线指定的椭圆定义的饼形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定饼形的颜色、宽度和样式。 |
| x | float | 定义饼形所在椭圆的外接矩形左上角的 x 坐标。 |
| y | float | 定义饼形所在椭圆的外接矩形左上角的 y 坐标。 |
| width | float | 定义饼形所在椭圆的外接矩形的宽度。 |
| height | float | 定义饼形所在椭圆的外接矩形的高度。 |
| start_angle | float | 从 x 轴顺时针测量到饼形第一边的角度（以度为单位）。 |
| sweep_angle | float | 从 _startAngle_ 参数顺时针测量到饼形第二边的角度（以度为单位）。 |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_121}


```
 draw_polygon(pen, points) 
```

绘制由 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组定义的多边形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定多边形的颜色、宽度和样式。 |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 表示多边形顶点的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_122}


```
 draw_polygon(pen, points) 
```

绘制由 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组定义的多边形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定多边形的颜色、宽度和样式。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 表示多边形顶点的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_polygon_f(pen, points) {#draw_polygon_f_pen_points_123}


```
 draw_polygon_f(pen, points) 
```

绘制由 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组定义的多边形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) 用于确定多边形的颜色、宽度和样式。 |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 表示多边形顶点的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |

### Method: draw_rect(pen, x, y, width, height) {#draw_rect_pen_x_y_width_height_124}


```
 draw_rect(pen, x, y, width, height) 
```

绘制由坐标对、宽度和高度指定的矩形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于确定矩形的颜色、宽度和样式的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| x | int | 要绘制的矩形左上角的 x 坐标。 |
| y | int | 要绘制的矩形左上角的 y 坐标。 |
| width | int | 要绘制的矩形的宽度。 |
| height | int | 要绘制的矩形的高度。 |

### Method: draw_rect_f(pen, x, y, width, height) {#draw_rect_f_pen_x_y_width_height_125}


```
 draw_rect_f(pen, x, y, width, height) 
```

绘制由坐标对、宽度和高度指定的矩形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于确定矩形的颜色、宽度和样式的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| x | float | 要绘制的矩形左上角的 x 坐标。 |
| y | float | 要绘制的矩形左上角的 y 坐标。 |
| width | float | 要绘制的矩形的宽度。 |
| height | float | 要绘制的矩形的高度。 |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_126}


```
 draw_rectangle(pen, rect) 
```

绘制由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的矩形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于确定矩形的颜色、宽度和样式的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 表示要绘制的矩形的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_127}


```
 draw_rectangle(pen, rect) 
```

绘制由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的矩形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于确定矩形的颜色、宽度和样式的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 表示要绘制的矩形的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_128}


```
 draw_rectangle(pen, x, y, width, height) 
```

绘制由坐标对、宽度和高度指定的矩形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于确定矩形的颜色、宽度和样式的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| x | float | 要绘制的矩形左上角的 x 坐标。 |
| y | float | 要绘制的矩形左上角的 y 坐标。 |
| width | float | 要绘制的矩形的宽度。 |
| height | float | 要绘制的矩形的高度。 |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_129}


```
 draw_rectangle(pen, x, y, width, height) 
```

绘制由坐标对、宽度和高度指定的矩形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于确定矩形的颜色、宽度和样式的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| x | int | 要绘制的矩形左上角的 x 坐标。 |
| y | int | 要绘制的矩形左上角的 y 坐标。 |
| width | int | 要绘制的矩形的宽度。 |
| height | int | 要绘制的矩形的高度。 |

### Method: draw_rectangle_f(pen, rect) {#draw_rectangle_f_pen_rect_130}


```
 draw_rectangle_f(pen, rect) 
```

绘制由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的矩形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于确定矩形的颜色、宽度和样式的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 表示要绘制的矩形的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_131}


```
 draw_rectangles(pen, rects) 
```

绘制由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的一系列矩形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 确定矩形轮廓的颜色、宽度和样式的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | 表示要绘制的矩形的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构数组。 |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_132}


```
 draw_rectangles(pen, rects) 
```

绘制由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的一系列矩形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 确定矩形轮廓的颜色、宽度和样式的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| rects | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | 表示要绘制的矩形的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构数组。 |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: draw_rectangles_f(pen, rects) {#draw_rectangles_f_pen_rects_133}


```
 draw_rectangles_f(pen, rects) 
```

绘制由 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构指定的一系列矩形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 确定矩形轮廓的颜色、宽度和样式的 [Pen](/imaging/python-net/aspose.imaging/pen/)。 |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | 表示要绘制的矩形的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构数组。 |

### Method: draw_string(s, font, brush, layout_rectangle) {#draw_string_s_font_brush_layout_rectangle_134}


```
 draw_string(s, font, brush, layout_rectangle) 
```

在指定的矩形中使用指定的[Brush](/imaging/python-net/aspose.imaging/brush/)和[Font](/imaging/python-net/aspose.imaging/font/)对象绘制指定的文本字符串。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| s | string | 要绘制的字符串。 |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | 定义字符串文本格式的 [Font](/imaging/python-net/aspose.imaging/font/)。 |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定绘制文本的颜色和纹理的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 指定绘制文本位置的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: draw_string(s, font, brush, layout_rectangle, format) {#draw_string_s_font_brush_layout_rectangle_format_135}


```
 draw_string(s, font, brush, layout_rectangle, format) 
```

在指定的矩形中使用指定的[Brush](/imaging/python-net/aspose.imaging/brush/)和[Font](/imaging/python-net/aspose.imaging/font/)对象绘制指定的文本字符串，并使用指定的[StringFormat](/imaging/python-net/aspose.imaging/stringformat/)的格式属性。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| s | string | 要绘制的字符串。 |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | 定义字符串文本格式的 [Font](/imaging/python-net/aspose.imaging/font/)。 |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定绘制文本的颜色和纹理的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 指定绘制文本位置的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | 指定应用于绘制文本的格式属性（如行间距和对齐方式）的 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/)。 |

### Method: draw_string(s, font, brush, point) {#draw_string_s_font_brush_point_136}


```
 draw_string(s, font, brush, point) 
```

在指定位置使用指定的[Brush](/imaging/python-net/aspose.imaging/brush/)和[Font](/imaging/python-net/aspose.imaging/font/)对象绘制指定的文本字符串。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| s | string | 要绘制的字符串。 |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | 定义字符串文本格式的 [Font](/imaging/python-net/aspose.imaging/font/)。 |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定绘制文本的颜色和纹理的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 指定绘制文本左上角的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构。 |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_string(s, font, brush, point, format) {#draw_string_s_font_brush_point_format_137}


```
 draw_string(s, font, brush, point, format) 
```

在指定位置使用指定的[Brush](/imaging/python-net/aspose.imaging/brush/)和[Font](/imaging/python-net/aspose.imaging/font/)对象绘制指定的文本字符串，并使用指定的[StringFormat](/imaging/python-net/aspose.imaging/stringformat/)的格式属性。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| s | string | 要绘制的字符串。 |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | 定义字符串文本格式的 [Font](/imaging/python-net/aspose.imaging/font/)。 |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定绘制文本的颜色和纹理的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 指定绘制文本左上角的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构。 |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | 指定应用于绘制文本的格式属性（如行间距和对齐方式）的 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/)。 |

### Method: draw_string(s, font, brush, x, y) {#draw_string_s_font_brush_x_y_138}


```
 draw_string(s, font, brush, x, y) 
```

在指定位置使用指定的[Brush](/imaging/python-net/aspose.imaging/brush/)和[Font](/imaging/python-net/aspose.imaging/font/)对象绘制指定的文本字符串。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| s | string | 要绘制的字符串。 |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | 定义字符串文本格式的 [Font](/imaging/python-net/aspose.imaging/font/)。 |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定绘制文本的颜色和纹理的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| x | float | 绘制文本左上角的 x 坐标。 |
| y | float | 绘制文本左上角的 y 坐标。 |

### Method: draw_string(s, font, brush, x, y, format) {#draw_string_s_font_brush_x_y_format_139}


```
 draw_string(s, font, brush, x, y, format) 
```

在指定位置使用指定的[Brush](/imaging/python-net/aspose.imaging/brush/)和[Font](/imaging/python-net/aspose.imaging/font/)对象绘制指定的文本字符串，并使用指定的[StringFormat](/imaging/python-net/aspose.imaging/stringformat/)的格式属性。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| s | string | 要绘制的字符串。 |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | 定义字符串文本格式的 [Font](/imaging/python-net/aspose.imaging/font/)。 |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定绘制文本的颜色和纹理的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| x | float | 绘制文本左上角的 x 坐标。 |
| y | float | 绘制文本左上角的 y 坐标。 |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | 指定应用于绘制文本的格式属性（如行间距和对齐方式）的 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/)。 |

### Method: draw_string_at_point_f(s, font, brush, point) {#draw_string_at_point_f_s_font_brush_point_140}


```
 draw_string_at_point_f(s, font, brush, point) 
```

在指定位置使用指定的[Brush](/imaging/python-net/aspose.imaging/brush/)和[Font](/imaging/python-net/aspose.imaging/font/)对象绘制指定的文本字符串。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| s | string | 要绘制的字符串。 |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | 定义字符串文本格式的 [Font](/imaging/python-net/aspose.imaging/font/)。 |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定绘制文本的颜色和纹理的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 指定绘制文本左上角的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构。 |

### Method: draw_string_at_point_f_format(s, font, brush, point, format) {#draw_string_at_point_f_format_s_font_brush_point_format_141}


```
 draw_string_at_point_f_format(s, font, brush, point, format) 
```

在指定位置使用指定的[Brush](/imaging/python-net/aspose.imaging/brush/)和[Font](/imaging/python-net/aspose.imaging/font/)对象绘制指定的文本字符串，并使用指定的[StringFormat](/imaging/python-net/aspose.imaging/stringformat/)的格式属性。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| s | string | 要绘制的字符串。 |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | 定义字符串文本格式的 [Font](/imaging/python-net/aspose.imaging/font/)。 |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定绘制文本的颜色和纹理的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 指定绘制文本左上角的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构。 |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | 指定应用于绘制文本的格式属性（如行间距和对齐方式）的 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/)。 |

### Method: draw_string_at_xy(s, font, brush, x, y) {#draw_string_at_xy_s_font_brush_x_y_142}


```
 draw_string_at_xy(s, font, brush, x, y) 
```

在指定位置使用指定的[Brush](/imaging/python-net/aspose.imaging/brush/)和[Font](/imaging/python-net/aspose.imaging/font/)对象绘制指定的文本字符串。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| s | string | 要绘制的字符串。 |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | 定义字符串文本格式的 [Font](/imaging/python-net/aspose.imaging/font/)。 |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定绘制文本的颜色和纹理的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| x | float | 绘制文本左上角的 x 坐标。 |
| y | float | 绘制文本左上角的 y 坐标。 |

### Method: draw_string_in_rect(s, font, brush, layout_rectangle) {#draw_string_in_rect_s_font_brush_layout_rectangle_143}


```
 draw_string_in_rect(s, font, brush, layout_rectangle) 
```

在指定的矩形中使用指定的[Brush](/imaging/python-net/aspose.imaging/brush/)和[Font](/imaging/python-net/aspose.imaging/font/)对象绘制指定的文本字符串。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| s | string | 要绘制的字符串。 |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | 定义字符串文本格式的 [Font](/imaging/python-net/aspose.imaging/font/)。 |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定绘制文本的颜色和纹理的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 指定绘制文本位置的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: draw_string_in_rect_f(s, font, brush, layout_rectangle, format) {#draw_string_in_rect_f_s_font_brush_layout_rectangle_format_144}


```
 draw_string_in_rect_f(s, font, brush, layout_rectangle, format) 
```

在指定的矩形中使用指定的[Brush](/imaging/python-net/aspose.imaging/brush/)和[Font](/imaging/python-net/aspose.imaging/font/)对象绘制指定的文本字符串，并使用指定的[StringFormat](/imaging/python-net/aspose.imaging/stringformat/)的格式属性。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| s | string | 要绘制的字符串。 |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | 定义字符串文本格式的 [Font](/imaging/python-net/aspose.imaging/font/)。 |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定绘制文本的颜色和纹理的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 指定绘制文本位置的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | 指定应用于绘制文本的格式属性（如行间距和对齐方式）的 [StringFormat](/imaging/python-net/aspose.imaging/stringformat/)。 |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_145}


```
 fill_closed_curve(brush, points) 
```

填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5 和 [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 定义样条的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_146}


```
 fill_closed_curve(brush, points) 
```

填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5 和 [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 定义样条的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |

### Method: fill_closed_curve(brush, points, fill_mode) {#fill_closed_curve_brush_points_fill_mode_147}


```
 fill_closed_curve(brush, points, fill_mode) 
```

填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构定义的闭合基数样条曲线的内部，使用指定的填充模式。此方法使用默认张力 0.5。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 定义样条的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | 确定曲线填充方式的 [FillMode](/imaging/python-net/aspose.imaging/fillmode/) 枚举成员。 |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_148}


```
 fill_closed_curve(brush, points, fillmode) 
```

填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构定义的闭合基数样条曲线的内部，使用指定的填充模式。此方法使用默认张力 0.5。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 定义样条的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) |  |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_149}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构定义的闭合基数样条曲线的内部，使用指定的填充模式和张力。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 定义样条的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | 确定曲线填充方式的 [FillMode](/imaging/python-net/aspose.imaging/fillmode/) 枚举成员。 |
| 张力 | float | 指定曲线张力的值，必须大于或等于 0.0F。 |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_150}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构定义的闭合基数样条曲线的内部，使用指定的填充模式和张力。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 定义样条的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | 确定曲线填充方式的 [FillMode](/imaging/python-net/aspose.imaging/fillmode/) 枚举成员。 |
| 张力 | float | 指定曲线张力的值，必须大于或等于 0.0F。 |

### Method: fill_closed_curve_by_point(brush, points) {#fill_closed_curve_by_point_brush_points_151}


```
 fill_closed_curve_by_point(brush, points) 
```

填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5 和 [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 定义样条的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |

### Method: fill_closed_curve_by_point_f(brush, points) {#fill_closed_curve_by_point_f_brush_points_152}


```
 fill_closed_curve_by_point_f(brush, points) 
```

填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5 和 [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 定义样条的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |

### Method: fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension) {#fill_closed_curve_by_point_f_fill_mode_tension_brush_points_fillmode_tension_153}


```
 fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension) 
```

填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构定义的闭合基数样条曲线的内部，使用指定的填充模式和张力。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | 定义样条的 [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组。 |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | 确定曲线填充方式的 [FillMode](/imaging/python-net/aspose.imaging/fillmode/) 枚举成员。 |
| 张力 | float | 指定曲线张力的值，必须大于或等于 0.0F。 |

### Method: fill_closed_curve_by_point_fill_mode(brush, points, fillmode) {#fill_closed_curve_by_point_fill_mode_brush_points_fillmode_154}


```
 fill_closed_curve_by_point_fill_mode(brush, points, fillmode) 
```

填充由一组[Point](/imaging/python-net/aspose.imaging/point/)结构定义的闭合基数样条曲线的内部，使用指定的填充模式。此方法使用默认张力 0.5。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 定义样条的 [Point](/imaging/python-net/aspose.imaging/point/) 结构数组。 |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | 确定曲线填充方式的 [FillMode](/imaging/python-net/aspose.imaging/fillmode/) 枚举成员。 |

### Method: fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension) {#fill_closed_curve_by_point_fill_mode_tension_brush_points_fillmode_tension_155}


```
 fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension) 
```

填充由一组[Point](/imaging/python-net/aspose.imaging/point/)结构定义的闭合基数样条曲线的内部，使用指定的填充模式和张力。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 定义样条的 [Point](/imaging/python-net/aspose.imaging/point/) 结构数组。 |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | 确定曲线填充方式的 [FillMode](/imaging/python-net/aspose.imaging/fillmode/) 枚举成员。 |
| 张力 | float | 指定曲线张力的值，必须大于或等于 0.0F。 |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_156}


```
 fill_ellipse(brush, rect) 
```

填充由[RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)结构指定的边界矩形所定义的椭圆的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 表示定义椭圆的边界矩形的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_157}


```
 fill_ellipse(brush, rect) 
```

填充由[RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)结构指定的边界矩形所定义的椭圆的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 表示定义椭圆的边界矩形的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_158}


```
 fill_ellipse(brush, x, y, width, height) 
```

填充由一对坐标、宽度和高度指定的边界矩形所定义的椭圆的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| x | float | 定义椭圆的边界矩形左上角的 x 坐标。 |
| y | float | 定义椭圆的边界矩形左上角的 y 坐标。 |
| width | float | 定义椭圆的边界矩形的宽度。 |
| height | float | 定义椭圆的边界矩形的高度。 |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_159}


```
 fill_ellipse(brush, x, y, width, height) 
```

填充由一对坐标、宽度和高度指定的边界矩形所定义的椭圆的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| x | int | 定义椭圆的边界矩形左上角的 x 坐标。 |
| y | int | 定义椭圆的边界矩形左上角的 y 坐标。 |
| width | int | 定义椭圆的边界矩形的宽度。 |
| height | int | 定义椭圆的边界矩形的高度。 |

### Method: fill_ellipse_at_xywh(brush, x, y, width, height) {#fill_ellipse_at_xywh_brush_x_y_width_height_160}


```
 fill_ellipse_at_xywh(brush, x, y, width, height) 
```

填充由一对坐标、宽度和高度指定的边界矩形所定义的椭圆的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| x | int | 定义椭圆的边界矩形左上角的 x 坐标。 |
| y | int | 定义椭圆的边界矩形左上角的 y 坐标。 |
| width | int | 定义椭圆的边界矩形的宽度。 |
| height | int | 定义椭圆的边界矩形的高度。 |

### Method: fill_ellipse_at_xywhf(brush, x, y, width, height) {#fill_ellipse_at_xywhf_brush_x_y_width_height_161}


```
 fill_ellipse_at_xywhf(brush, x, y, width, height) 
```

填充由一对坐标、宽度和高度指定的边界矩形所定义的椭圆的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| x | float | 定义椭圆的边界矩形左上角的 x 坐标。 |
| y | float | 定义椭圆的边界矩形左上角的 y 坐标。 |
| width | float | 定义椭圆的边界矩形的宽度。 |
| height | float | 定义椭圆的边界矩形的高度。 |

### Method: fill_ellipse_in_rect(brush, rect) {#fill_ellipse_in_rect_brush_rect_162}


```
 fill_ellipse_in_rect(brush, rect) 
```

填充由[RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)结构指定的边界矩形所定义的椭圆的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 表示定义椭圆的边界矩形的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: fill_ellipse_in_rect_f(brush, rect) {#fill_ellipse_in_rect_f_brush_rect_163}


```
 fill_ellipse_in_rect_f(brush, rect) 
```

填充由[RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)结构指定的边界矩形所定义的椭圆的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 表示定义椭圆的边界矩形的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

### Method: fill_path(brush, path) {#fill_path_brush_path_164}


```
 fill_path(brush, path) 
```

填充[GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 表示要填充的路径的 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/)。 |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_165}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

填充由[RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)结构指定的椭圆和两条径向线所定义的饼形区域的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 表示定义椭圆（饼块来源）的边界矩形的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构。 |
| start_angle | float | 以度为单位、顺时针从 x 轴测量到饼块第一边的角度。 |
| sweep_angle | float | 以度为单位、顺时针从 _startAngle_ 参数测量到饼块第二边的角度。 |


**See also:**

**[Example # 1](#example_95)**: The following example shows how to compose an animated GIF image from individ...


### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_166}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

填充由[RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)结构指定的椭圆和两条径向线所定义的饼形区域的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 表示定义椭圆（饼块来源）的边界矩形的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构。 |
| start_angle | float | 以度为单位、顺时针从 x 轴测量到饼块第一边的角度。 |
| sweep_angle | float | 以度为单位、顺时针从 _startAngle_ 参数测量到饼块第二边的角度。 |


**See also:**

**[Example # 1](#example_95)**: The following example shows how to compose an animated GIF image from individ...


### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_167}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

填充由一对坐标、宽度和高度指定的椭圆和两条径向线所定义的饼形区域的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| x | float | 定义饼块来源椭圆的边界矩形左上角的 x 坐标。 |
| y | float | 定义饼块来源椭圆的边界矩形左上角的 y 坐标。 |
| width | float | 定义饼块来源椭圆的边界矩形的宽度。 |
| height | float | 定义饼块来源椭圆的边界矩形的高度。 |
| start_angle | float | 以度为单位、顺时针从 x 轴测量到饼块第一边的角度。 |
| sweep_angle | float | 以度为单位、顺时针从 _startAngle_ 参数测量到饼块第二边的角度。 |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_168}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

填充由一对坐标、宽度和高度指定的椭圆和两条径向线所定义的饼形区域的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| x | int | 定义饼块来源椭圆的边界矩形左上角的 x 坐标。 |
| y | int | 定义饼块来源椭圆的边界矩形左上角的 y 坐标。 |
| width | int | 定义饼块来源椭圆的边界矩形的宽度。 |
| height | int | 定义饼块来源椭圆的边界矩形的高度。 |
| start_angle | int | 以度为单位、顺时针从 x 轴测量到饼块第一边的角度。 |
| sweep_angle | int | 以度为单位、顺时针从 _startAngle_ 参数测量到饼块第二边的角度。 |

### Method: fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_at_xy_brush_x_y_width_height_start_angle_sweep_angle_169}


```
 fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle) 
```

填充由一对坐标、宽度和高度指定的椭圆和两条径向线所定义的饼形区域的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| x | int | 定义饼块来源椭圆的边界矩形左上角的 x 坐标。 |
| y | int | 定义饼块来源椭圆的边界矩形左上角的 y 坐标。 |
| width | int | 定义饼块来源椭圆的边界矩形的宽度。 |
| height | int | 定义饼块来源椭圆的边界矩形的高度。 |
| start_angle | int | 以度为单位、顺时针从 x 轴测量到饼块第一边的角度。 |
| sweep_angle | int | 以度为单位、顺时针从 _startAngle_ 参数测量到饼块第二边的角度。 |

### Method: fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_at_xyf_brush_x_y_width_height_start_angle_sweep_angle_170}


```
 fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle) 
```

填充由一对坐标、宽度和高度指定的椭圆和两条径向线所定义的饼形区域的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| x | float | 定义饼块来源椭圆的边界矩形左上角的 x 坐标。 |
| y | float | 定义饼块来源椭圆的边界矩形左上角的 y 坐标。 |
| width | float | 定义饼块来源椭圆的边界矩形的宽度。 |
| height | float | 定义饼块来源椭圆的边界矩形的高度。 |
| start_angle | float | 以度为单位、顺时针从 x 轴测量到饼块第一边的角度。 |
| sweep_angle | float | 以度为单位、顺时针从 _startAngle_ 参数测量到饼块第二边的角度。 |

### Method: fill_pie_in_rect(brush, rect, start_angle, sweep_angle) {#fill_pie_in_rect_brush_rect_start_angle_sweep_angle_171}


```
 fill_pie_in_rect(brush, rect, start_angle, sweep_angle) 
```

填充由[RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)结构指定的椭圆和两条径向线所定义的饼形区域的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 表示定义椭圆（饼块来源）的边界矩形的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构。 |
| start_angle | float | 以度为单位、顺时针从 x 轴测量到饼块第一边的角度。 |
| sweep_angle | float | 以度为单位、顺时针从 _startAngle_ 参数测量到饼块第二边的角度。 |

### Method: fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle) {#fill_pie_in_rect_f_brush_rect_start_angle_sweep_angle_172}


```
 fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle) 
```

填充由[RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)结构指定的椭圆和两条径向线所定义的饼形区域的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构，表示定义饼块来源椭圆的边界矩形。 |
| start_angle | float | 以度为单位、顺时针从 x 轴测量到饼块第一边的角度。 |
| sweep_angle | float | 以度为单位、顺时针从 _startAngle_ 参数测量到饼块第二边的角度。 |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_173}


```
 fill_polygon(brush, points) 
```

填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构指定的点并使用[FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式定义的多边形的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组，表示要填充的多边形的顶点。 |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_174}


```
 fill_polygon(brush, points) 
```

填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构指定的点并使用[FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式定义的多边形的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组，表示要填充的多边形的顶点。 |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_175}


```
 fill_polygon(brush, points, fill_mode) 
```

填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构指定的点并使用指定的填充模式定义的多边形的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组，表示要填充的多边形的顶点。 |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) 枚举的成员，决定填充的样式。 |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_176}


```
 fill_polygon(brush, points, fill_mode) 
```

填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构指定的点并使用指定的填充模式定义的多边形的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组，表示要填充的多边形的顶点。 |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) 枚举的成员，决定填充的样式。 |

### Method: fill_polygon_by_point(brush, points) {#fill_polygon_by_point_brush_points_177}


```
 fill_polygon_by_point(brush, points) 
```

填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构指定的点并使用[FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式定义的多边形的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组，表示要填充的多边形的顶点。 |

### Method: fill_polygon_by_point_f(brush, points) {#fill_polygon_by_point_f_brush_points_178}


```
 fill_polygon_by_point_f(brush, points) 
```

填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构指定的点并使用[FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) 填充模式定义的多边形的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组，表示要填充的多边形的顶点。 |

### Method: fill_polygon_by_point_f_fill_mode(brush, points, fill_mode) {#fill_polygon_by_point_f_fill_mode_brush_points_fill_mode_179}


```
 fill_polygon_by_point_f_fill_mode(brush, points, fill_mode) 
```

填充由一组[PointF](/imaging/python-net/aspose.imaging/pointf/)结构指定的点并使用指定的填充模式定义的多边形的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) 结构数组，表示要填充的多边形的顶点。 |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) 枚举的成员，决定填充的样式。 |

### Method: fill_polygon_by_point_fill_mode(brush, points, fill_mode) {#fill_polygon_by_point_fill_mode_brush_points_fill_mode_180}


```
 fill_polygon_by_point_fill_mode(brush, points, fill_mode) 
```

填充由一组[Point](/imaging/python-net/aspose.imaging/point/)结构指定的点并使用指定的填充模式定义的多边形的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) 结构数组，表示要填充的多边形的顶点。 |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) 枚举的成员，决定填充的样式。 |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_181}


```
 fill_rectangle(brush, rect) 
```

填充由[Rectangle](/imaging/python-net/aspose.imaging/rectangle/)结构指定的矩形的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构，表示要填充的矩形。 |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_182}


```
 fill_rectangle(brush, rect) 
```

填充由[Rectangle](/imaging/python-net/aspose.imaging/rectangle/)结构指定的矩形的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构，表示要填充的矩形。 |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_183}


```
 fill_rectangle(brush, x, y, width, height) 
```

填充由一对坐标、宽度和高度指定的矩形的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| x | float | 要填充矩形左上角的 x 坐标。 |
| y | float | 要填充矩形左上角的 y 坐标。 |
| width | float | 要填充矩形的宽度。 |
| height | float | 要填充矩形的高度。 |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_184}


```
 fill_rectangle(brush, x, y, width, height) 
```

填充由一对坐标、宽度和高度指定的矩形的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| x | int | 要填充矩形左上角的 x 坐标。 |
| y | int | 要填充矩形左上角的 y 坐标。 |
| width | int | 要填充矩形的宽度。 |
| height | int | 要填充矩形的高度。 |

### Method: fill_rectangle_f(brush, rect) {#fill_rectangle_f_brush_rect_185}


```
 fill_rectangle_f(brush, rect) 
```

填充由[RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)结构指定的矩形的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构，表示要填充的矩形。 |

### Method: fill_rectangle_f_with_brush(brush, x, y, width, height) {#fill_rectangle_f_with_brush_brush_x_y_width_height_186}


```
 fill_rectangle_f_with_brush(brush, x, y, width, height) 
```

填充由一对坐标、宽度和高度指定的矩形的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| x | float | 要填充矩形左上角的 x 坐标。 |
| y | float | 要填充矩形左上角的 y 坐标。 |
| width | float | 要填充矩形的宽度。 |
| height | float | 要填充矩形的高度。 |

### Method: fill_rectangle_with_brush(brush, x, y, width, height) {#fill_rectangle_with_brush_brush_x_y_width_height_187}


```
 fill_rectangle_with_brush(brush, x, y, width, height) 
```

填充由一对坐标、宽度和高度指定的矩形的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| x | int | 要填充矩形左上角的 x 坐标。 |
| y | int | 要填充矩形左上角的 y 坐标。 |
| width | int | 要填充矩形的宽度。 |
| height | int | 要填充矩形的高度。 |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_188}


```
 fill_rectangles(brush, rects) 
```

填充由一系列[Rectangle](/imaging/python-net/aspose.imaging/rectangle/)结构指定的矩形的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| rects | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构数组，表示要填充的矩形。 |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_189}


```
 fill_rectangles(brush, rects) 
```

填充由一系列[Rectangle](/imaging/python-net/aspose.imaging/rectangle/)结构指定的矩形的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构数组，表示要填充的矩形。 |

### Method: fill_rectangles_f(brush, rects) {#fill_rectangles_f_brush_rects_190}


```
 fill_rectangles_f(brush, rects) 
```

填充由一系列[RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)结构指定的矩形的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构数组，表示要填充的矩形。 |

### Method: fill_region(brush, region) {#fill_region_brush_region_191}


```
 fill_region(brush, region) 
```

填充 [Region](/imaging/python-net/aspose.imaging/region/) 的内部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的 [Brush](/imaging/python-net/aspose.imaging/brush/)。 |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | [Region](/imaging/python-net/aspose.imaging/region/)，表示要填充的区域。 |

### Method: measure_string(text, font, layout_area, string_format) {#measure_string_text_font_layout_area_string_format_192}


```
 measure_string(text, font, layout_area, string_format) 
```

使用指定的参数测量指定的文本字符串

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| text | string | 要测量的文本。 |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | 要测量的字体。 |
| layout_area | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | 布局区域。 |
| string_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | 字符串格式。 |

**Returns**

| Type | Description |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | 测量文本字符串的像素大小。 |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_193}


```
 multiply_transform(matrix) 
```

将表示此 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 的局部几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 与指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 相乘，并通过在前面添加指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 来实现。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 用于乘以几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_194}


```
 multiply_transform(matrix, order) 
```

将表示此 [Graphics](/imaging/python-net/aspose.imaging/graphics/) 的局部几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 与指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 按指定顺序相乘。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 用于乘以几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 指定两个矩阵相乘顺序的 [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/)。 |

### Method: rotate_transform(angle) {#rotate_transform_angle_195}


```
 rotate_transform(angle) 
```

按指定量旋转本地几何变换。此方法将在变换前预置旋转。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 角度 | float | 旋转角度。 |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_196}


```
 rotate_transform(angle, order) 
```

按指定量并按指定顺序旋转本地几何变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 角度 | float | 旋转角度。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 指定是追加还是预置旋转矩阵的 [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/)。 |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_197}


```
 scale_transform(sx, sy) 
```

按指定的比例缩放本地几何变换。此方法将在变换前预置缩放矩阵。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| sx | float | 在 x 轴方向上缩放变换的量。 |
| sy | float | 在 y 轴方向上缩放变换的量。 |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_198}


```
 scale_transform(sx, sy, order) 
```

按指定的比例并按指定顺序缩放本地几何变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| sx | float | 在 x 轴方向上缩放变换的量。 |
| sy | float | 在 y 轴方向上缩放变换的量。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 一个 [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) 用于指定是追加还是预先追加缩放矩阵。 |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_199}


```
 translate_transform(dx, dy) 
```

按指定的尺寸平移本地几何变换。此方法将在变换前预置平移。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dx | float | x 方向的平移值。 |
| dy | float | y 方向的平移值。 |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_200}


```
 translate_transform(dx, dy, order) 
```

按指定的尺寸并按指定顺序平移本地几何变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dx | float | x 方向的平移值。 |
| dy | float | y 方向的平移值。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 应用平移的顺序（预先追加或追加）。 |

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

#创建文件流的实例
with open(r"C:\temp\output.png", "w+b") as stream:
	#创建 PngOptions 实例并设置其各种属性
	pngOptions = PngOptions()
	#设置 PngOptions 的 Source
	pngOptions.source = StreamSource(stream)
	#创建 Image 实例
	with Image.create(pngOptions, 500, 500) as image:
		#创建并初始化 Graphics 类的实例
		graphics = Graphics(image)
		#清除 Graphics 表面
		graphics.clear(Color.wheat);
		#通过指定具有黑色的 Pen 对象来绘制弧线，
		#一个围绕弧线的矩形、起始角度和扫掠角度
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#通过指定具有蓝色的 Pen 对象和坐标点来绘制贝塞尔曲线。
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#通过指定具有绿色颜色的 Pen 对象和一个点数组来绘制曲线
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#使用 Pen 对象和一个包围的矩形绘制椭圆
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#绘制直线
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#绘制饼图扇形
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#通过指定具有红色颜色的 Pen 对象和一个点数组来绘制多边形
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#绘制矩形
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#创建 SolidBrush 对象并设置其各种属性
		brush = SolidBrush()
		brush.color = Color.purple
		#使用 SolidBrush 对象和 Font 在特定点绘制字符串
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# 保存所有更改。
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


# 创建文件流的实例
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# 创建 TiffOptions 的实例并设置其各种属性
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# 为 ImageOptions 实例设置源
	tiffOptions.source = StreamSource(stream)
	# 创建 Image 的实例
	with Image.create(tiffOptions, 500, 500) as image:
		# 创建并初始化 Graphics 类的实例
		graphics = Graphics(image)
		# 清除 Graphics 表面
		graphics.clear(Color.wheat);
		# 创建 GraphicsPath 类的实例
		graphics_path = GraphicsPath()
		# 创建 Figure 类的实例
		figure = Figure()
		# 向 Figure 对象添加形状
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# 将 Figure 对象添加到 GraphicsPath
		graphics_path.add_figure(figure)
		# 使用颜色为 Black 的 Pen 对象绘制路径
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# 保存所有更改。
		image.save()


```

### This example shows the creation and usage Pen objects. The example creates a new Image and draw rectangles on the Image surface. {#example_14}
``` python

from aspose.imaging import Image, Graphics, Color, Pen, Rectangle, Point, Size
from aspose.imaging.brushes import HatchBrush
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

# 创建 BmpOptions 实例并设置其各种属性。
bmpOptions = BmpOptions()
bmpOptions.bits_per_pixel = 24
# 创建 FileCreateSource 的实例并将其分配为 BmpOptions 实例的 Source
# 第二个布尔参数决定要创建的文件是否为临时文件
bmpOptions.source = FileCreateSource(r"C:\temp\sample.bmp", False)
# 在指定路径创建 Image 实例。
with Image.create(bmpOptions, 500, 500) as image:
	# 创建 Graphics 实例并使用 Image 对象进行初始化。
	graphics = Graphics(image)
	# 使用白色清除 Graphics 表面。
	graphics.clear(Color.white)
	#创建颜色为红色、宽度为 5 的 Pen 实例。
	pen = Pen(Color.red, 5.0);
	# 创建 HatchBrush 实例并设置其属性。
	brush = HatchBrush()
	brush.background_color = Color.wheat;
	brush.foreground_color = Color.red;
	# 创建 Pen 实例。
	# 使用 HatchBrush 对象和宽度进行初始化
	brusedpen = Pen(brush, 5.0)
	# 通过指定 Pen 对象绘制矩形
	graphics.draw_rectangles(pen, [
		Rectangle(Point(210, 210), Size(100, 100)),
		Rectangle(Point(110, 110), Size(100, 100)),
		Rectangle(Point(310, 310), Size(100, 100)) ])

	# 通过指定 Pen 对象绘制矩形
	graphics.draw_rectangles(brusedpen, [
		Rectangle(Point(310, 110), Size(100, 100)),
		Rectangle(Point(110, 310), Size(100, 100)) ])

	# 保存所有更改。
	image.save()


```

### The following example shows how to compose an animated GIF image from individual GIF blocks. {#example_95}
``` python
from aspose.imaging.fileformats.gif.blocks import GifFrameBlock
from aspose.imaging.fileformats.gif import GifImage 
from aspose.imaging.brushes import SolidBrush
from aspose.imaging import Graphics, Color

# 创建一个 100 x 100 像素的 GIF 图像。
# 默认情况下，第一个块是全黑的。
with GifFrameBlock(100, 100) as firstBlock:
	with GifImage(firstBlock) as gifImage:
		# 第一个圆是红色的
		brush1 = SolidBrush(Color.red)

		# 第二个圆是黑色的
		brush2 = SolidBrush(Color.black)

		# 逐渐增加红色弧形的角度。
		for angle in range(10, 361, 10):
			block = GifFrameBlock(100, 100)
			gr = Graphics(block)
			gr.fill_pie(brush1, block.bounds, 0, angle)
			gifImage.add_block(block)
		
		# 逐渐增加黑色弧形的角度并抹去红色弧形。
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
# 创建一个 100x100 像素的 PNG 图像。
with PngImage(100, 100) as png_image:
	# 进行一些图像处理，例如将整个图像填充为红色。
	graphics = Graphics(png_image)
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, png_image.bounds)
	# 保存到文件。
	png_image.save(join(dir_, "output.png"))


```

