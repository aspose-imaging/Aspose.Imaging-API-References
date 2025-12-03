---
title: Graphics Class
type: docs
weight: 5010
url: /python-net/aspose.imaging/graphics/
---

**Summary:** Represents the graphics according to the graphics engine used in the current assembly.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Graphics

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Graphics(source_image)](#Graphics_source_image_1) | Initializes a new instance of the [Graphics](/imaging/python-net/aspose.imaging/graphics/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| clip | [Region](/imaging/python-net/aspose.imaging/region/) | r/w | Gets or sets the clip region. |
| compositing_quality | [CompositingQuality](/imaging/python-net/aspose.imaging/compositingquality/) | r/w | Gets or sets the compositing quality. |
| dpi_x | float | r | Gets the horizontal resolution of this `aspose.imaging.Graphics`. |
| dpi_y | float | r | Gets the vertical resolution of this `aspose.imaging.Graphics`. |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | r | Gets the image. |
| interpolation_mode | [InterpolationMode](/imaging/python-net/aspose.imaging/interpolationmode/) | r/w | Gets or sets the interpolation mode. |
| is_in_begin_update_call | bool | r | Gets a value indicating whether graphics is in BeginUpdate call state. |
| page_scale | float | r/w | Gets or sets the scaling between world units and page units for this `aspose.imaging.Graphics`. |
| page_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | r/w | Gets or sets the unit of measure used for page coordinates in this `aspose.imaging.Graphics`. |
| paintable_image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | r/w | Gets or sets image options, used to create paintable vactor images to draw. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Gets or sets the smoothing mode. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Gets or sets the text rendering hint. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Gets or sets a copy of the geometric world transformation for this [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| begin_update() | Starts caching of the following graphics operations. The graphics effects applied afterwards will not be applied immediately instead the EndUpdate will cause applying all the effects at once. |
| [clear(color)](#clear_color_1) | Clears the graphics surface using the specified color. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_2) | Draws an arc representing a portion of an ellipse specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_3) | Draws an arc representing a portion of an ellipse specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4) | Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5) | Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height. |
| [draw_arc_in_rect(pen, rect, start_angle, sweep_angle)](#draw_arc_in_rect_pen_rect_start_angle_sweep_angle_6) | Draws an arc representing a portion of an ellipse specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle)](#draw_arc_in_rect_f_pen_rect_start_angle_sweep_angle_7) | Draws an arc representing a portion of an ellipse specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_xy_pen_x_y_width_height_start_angle_sweep_angle_8) | Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height. |
| [draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_xyf_pen_x_y_width_height_start_angle_sweep_angle_9) | Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_10) | Draws a Bézier spline defined by four [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_11) | Draws a Bézier spline defined by four [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. |
| [draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4)](#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_12) | Draws a Bézier spline defined by four ordered pairs of coordinates that represent points. |
| [draw_bezier_by_points(pen, pt1, pt2, pt3, pt4)](#draw_bezier_by_points_pen_pt1_pt2_pt3_pt4_13) | Draws a Bézier spline defined by four [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. |
| [draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4)](#draw_bezier_by_points_f_pen_pt1_pt2_pt3_pt4_14) | Draws a Bézier spline defined by four [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_15) | Draws a series of Bézier splines from an array of [Point](/imaging/python-net/aspose.imaging/point/) structures. |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_16) | Draws a series of Bézier splines from an array of [Point](/imaging/python-net/aspose.imaging/point/) structures. |
| [draw_beziers_by_pt_array(pen, points)](#draw_beziers_by_pt_array_pen_points_17) | Draws a series of Bézier splines from an array of [Point](/imaging/python-net/aspose.imaging/point/) structures. |
| [draw_beziers_by_pt_array_f(pen, points)](#draw_beziers_by_pt_array_f_pen_points_18) | Draws a series of Bézier splines from an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_19) | Draws a closed cardinal spline defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5 and [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fill mode. |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_20) | Draws a closed cardinal spline defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5 and [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fill mode. |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_21) | Draws a closed cardinal spline defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using a specified tension. This method uses a default [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fill mode. |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_22) | Draws a closed cardinal spline defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using a specified tension. This method uses a default [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fill mode. |
| [draw_closed_curve_by_points(pen, points)](#draw_closed_curve_by_points_pen_points_23) | Draws a closed cardinal spline defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5 and [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fill mode. |
| [draw_closed_curve_by_points_f(pen, points)](#draw_closed_curve_by_points_f_pen_points_24) | Draws a closed cardinal spline defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5 and [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fill mode. |
| [draw_closed_curve_by_points_f_tension(pen, points, tension)](#draw_closed_curve_by_points_f_tension_pen_points_tension_25) | Draws a closed cardinal spline defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using a specified tension. This method uses a default [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fill mode. |
| [draw_closed_curve_by_points_tension(pen, points, tension)](#draw_closed_curve_by_points_tension_pen_points_tension_26) | Draws a closed cardinal spline defined by an array of [Point](/imaging/python-net/aspose.imaging/point/) structures using a specified tension. This method uses a default [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fill mode. |
| [draw_curve(pen, points)](#draw_curve_pen_points_27) | Draws a cardinal spline through a specified array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5. |
| [draw_curve(pen, points)](#draw_curve_pen_points_28) | Draws a cardinal spline through a specified array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5. |
| [draw_curve(pen, points, offset, number_of_segments)](#draw_curve_pen_points_offset_number_of_segments_29) | Draws a cardinal spline through a specified array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. The drawing begins offset from the beginning of the array.<br/>            This method uses a default tension of 0.5. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_30) | Draws a cardinal spline through a specified array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using a specified tension. The drawing begins offset from the beginning of the array. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_31) | Draws a cardinal spline through a specified array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using a specified tension. The drawing begins offset from the beginning of the array. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_32) | Draws a cardinal spline through a specified array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using a specified tension. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_33) | Draws a cardinal spline through a specified array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using a specified tension. |
| [draw_curve_by_point_fs(pen, points)](#draw_curve_by_point_fs_pen_points_34) | Draws a cardinal spline through a specified array of [Point](/imaging/python-net/aspose.imaging/point/) structures. |
| [draw_curve_by_point_fs_tension(pen, points, tension)](#draw_curve_by_point_fs_tension_pen_points_tension_35) | Draws a cardinal spline through a specified array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using a specified tension. |
| [draw_curve_by_points(pen, points)](#draw_curve_by_points_pen_points_36) | Draws a cardinal spline through a specified array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5. |
| [draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension)](#draw_curve_by_points_f_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_37) | Draws a cardinal spline through a specified array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using a specified tension. The drawing begins offset from the beginning of the array. |
| [draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension)](#draw_curve_by_points_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_38) | Draws a cardinal spline through a specified array of [Point](/imaging/python-net/aspose.imaging/point/) structures using a specified tension. |
| [draw_curve_by_points_tension(pen, points, tension)](#draw_curve_by_points_tension_pen_points_tension_39) | Draws a cardinal spline through a specified array of [Point](/imaging/python-net/aspose.imaging/point/) structures using a specified tension. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_40) | Draws an ellipse defined by a bounding [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_41) | Draws an ellipse defined by a bounding [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_42) | Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_43) | Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width. |
| [draw_ellipse_by_xy(pen, x, y, width, height)](#draw_ellipse_by_xy_pen_x_y_width_height_44) | Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width. |
| [draw_ellipse_by_xyf(pen, x, y, width, height)](#draw_ellipse_by_xyf_pen_x_y_width_height_45) | Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width. |
| [draw_ellipse_f(pen, rect)](#draw_ellipse_f_pen_rect_46) | Draws an ellipse defined by a bounding [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_47) | Draws the specified portion of the specified _image_ at the specified location and with the specified size. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_48) | Draws the specified portion of the specified _image_ at the specified location and with the specified size. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_49) | Draws the specified portion of the specified _image_ at the specified location and with the specified size. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_50) | Draws the specified portion of the specified _image_ at the specified location and with the specified size. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_51) | Draws the specified portion of the specified _image_ at the specified location and with the specified size. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_52) | Draws the specified portion of the specified _image_ at the specified location and with the specified size. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_53) | Draws the specified portion of the specified _image_ at the specified location and with the specified size. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_54) | Draws the specified portion of the specified _image_ at the specified location and with the specified size. |
| [draw_image(source_image, point)](#draw_image_source_image_point_55) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), using its original physical size, at the specified location. |
| [draw_image(source_image, point)](#draw_image_source_image_point_56) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), using its original physical size, at the specified location. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_57) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_58) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_59) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_60) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_61) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_62) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_63) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_64) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_65) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_66) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_67) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), using its original physical size, at the specified location. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_68) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), using its original physical size, at the specified location. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_69) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_70) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size. |
| [draw_image_at_point(source_image, point)](#draw_image_at_point_source_image_point_71) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), using its original physical size, at the specified location. |
| [draw_image_at_point_f(source_image, point)](#draw_image_at_point_f_source_image_point_72) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), using its original physical size, at the specified location. |
| [draw_image_at_xy(source_image, x, y)](#draw_image_at_xy_source_image_x_y_73) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), using its original physical size, at the specified location. |
| [draw_image_at_xyf(source_image, x, y)](#draw_image_at_xyf_source_image_x_y_74) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), using its original physical size, at the specified location. |
| [draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit)](#draw_image_dest_point_f_src_rect_f_with_unit_image_dest_points_src_rect_src_unit_75) | Draws the specified portion of the specified _image_ at the specified location and with the specified size. |
| [draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_dest_point_f_src_rect_f_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_76) | Draws the specified portion of the specified _image_ at the specified location and with the specified size. |
| [draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect)](#draw_image_dest_points_f_src_rect_f_image_dest_points_src_rect_77) | Draws the specified portion of the specified _image_ at the specified location and with the specified size. |
| [draw_image_dest_points_src_rect(image, dest_points, src_rect)](#draw_image_dest_points_src_rect_image_dest_points_src_rect_78) | Draws the specified portion of the specified _image_ at the specified location and with the specified size. |
| [draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit)](#draw_image_dest_points_src_rect_with_unit_image_dest_points_src_rect_src_unit_79) | Draws the specified portion of the specified _image_ at the specified location and with the specified size. |
| [draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_dest_points_src_rect_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_80) | Draws the specified portion of the specified _image_ at the specified location and with the specified size. |
| [draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_dest_rect_f_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_81) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size. |
| [draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_dest_rect_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_82) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size. |
| [draw_image_in_rect(source_image, x, y, width, height)](#draw_image_in_rect_source_image_x_y_width_height_83) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size. |
| [draw_image_in_rect_f(source_image, x, y, width, height)](#draw_image_in_rect_f_source_image_x_y_width_height_84) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size. |
| [draw_image_in_rectangle(source_image, rect)](#draw_image_in_rectangle_source_image_rect_85) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size. |
| [draw_image_points(image, dest_points)](#draw_image_points_image_dest_points_86) | Draws the specified portion of the specified _image_ at the specified location and with the specified size. |
| [draw_image_points_f(image, dest_points)](#draw_image_points_f_image_dest_points_87) | Draws the specified portion of the specified _image_ at the specified location and with the specified size. |
| [draw_image_rectangle_f(source_image, rect)](#draw_image_rectangle_f_source_image_rect_88) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size. |
| [draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_src_dest_rects_f_with_unit_source_image_rect_source_rect_destination_graphics_unit_89) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size. |
| [draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_src_dest_rects_with_unit_source_image_rect_source_rect_destination_graphics_unit_90) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size. |
| [draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_src_dst_rect_f_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_91) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size. |
| [draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_src_dst_rects_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_92) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size. |
| [draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit)](#draw_image_to_rect_f_with_unit_source_image_rect_destination_graphics_unit_93) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size. |
| [draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit)](#draw_image_to_rect_with_unit_source_image_rect_destination_graphics_unit_94) | Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size. |
| [draw_image_unscaled(source_image, point)](#draw_image_unscaled_source_image_point_95) | Draws a specified image using its original physical size at a specified location. |
| [draw_image_unscaled(source_image, rect)](#draw_image_unscaled_source_image_rect_96) | Draws a specified image using its original physical size at a specified location. |
| [draw_image_unscaled(source_image, x, y)](#draw_image_unscaled_source_image_x_y_97) | Draws the specified image using its original physical size at the location specified by a coordinate pair. |
| [draw_image_unscaled(source_image, x, y, width, height)](#draw_image_unscaled_source_image_x_y_width_height_98) | Draws a specified image using its original physical size at a specified location. |
| [draw_image_unscaled_and_clipped(source_image, rect)](#draw_image_unscaled_and_clipped_source_image_rect_99) | Draws the specified image without scaling and clips it, if necessary, to fit in the specified rectangle. |
| [draw_image_unscaled_in_rectangle(source_image, rect)](#draw_image_unscaled_in_rectangle_source_image_rect_100) | Draws a specified image using its original physical size at a specified location. |
| [draw_image_unscaled_to_point(source_image, point)](#draw_image_unscaled_to_point_source_image_point_101) | Draws a specified image using its original physical size at a specified location. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_102) | Draws a line connecting two [Point](/imaging/python-net/aspose.imaging/point/) structures. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_103) | Draws a line connecting two [Point](/imaging/python-net/aspose.imaging/point/) structures. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_104) | Draws a line connecting the two points specified by the coordinate pairs. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_105) | Draws a line connecting the two points specified by the coordinate pairs. |
| [draw_line_by_xy(pen, x1, y1, x2, y2)](#draw_line_by_xy_pen_x1_y1_x2_y2_106) | Draws a line connecting the two points specified by the coordinate pairs. |
| [draw_line_f_by_xy(pen, x1, y1, x2, y2)](#draw_line_f_by_xy_pen_x1_y1_x2_y2_107) | Draws a line connecting the two points specified by the coordinate pairs. |
| [draw_line_point_f(pen, point1, point2)](#draw_line_point_f_pen_point1_point2_108) | Draws a line connecting two [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. |
| [draw_lines(pen, points)](#draw_lines_pen_points_109) | Draws a series of line segments that connect an array of [Point](/imaging/python-net/aspose.imaging/point/) structures. |
| [draw_lines(pen, points)](#draw_lines_pen_points_110) | Draws a series of line segments that connect an array of [Point](/imaging/python-net/aspose.imaging/point/) structures. |
| [draw_lines_f(pen, points)](#draw_lines_f_pen_points_111) | Draws a series of line segments that connect an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. |
| [draw_path(pen, path)](#draw_path_pen_path_112) | Draws a [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_113) | Draws a pie shape defined by an ellipse specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure and two radial lines. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_114) | Draws a pie shape defined by an ellipse specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure and two radial lines. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_115) | Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_116) | Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines. |
| [draw_pie_in_rect(pen, rect, start_angle, sweep_angle)](#draw_pie_in_rect_pen_rect_start_angle_sweep_angle_117) | Draws a pie shape defined by an ellipse specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure and two radial lines. |
| [draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle)](#draw_pie_in_rect_f_pen_rect_start_angle_sweep_angle_118) | Draws a pie shape defined by an ellipse specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure and two radial lines. |
| [draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_xy_pen_x_y_width_height_start_angle_sweep_angle_119) | Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines. |
| [draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_xyf_pen_x_y_width_height_start_angle_sweep_angle_120) | Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_121) | Draws a polygon defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_122) | Draws a polygon defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. |
| [draw_polygon_f(pen, points)](#draw_polygon_f_pen_points_123) | Draws a polygon defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. |
| [draw_rect(pen, x, y, width, height)](#draw_rect_pen_x_y_width_height_124) | Draws a rectangle specified by a coordinate pair, a width, and a height. |
| [draw_rect_f(pen, x, y, width, height)](#draw_rect_f_pen_x_y_width_height_125) | Draws a rectangle specified by a coordinate pair, a width, and a height. |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_126) | Draws a rectangle specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_127) | Draws a rectangle specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_128) | Draws a rectangle specified by a coordinate pair, a width, and a height. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_129) | Draws a rectangle specified by a coordinate pair, a width, and a height. |
| [draw_rectangle_f(pen, rect)](#draw_rectangle_f_pen_rect_130) | Draws a rectangle specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_131) | Draws a series of rectangles specified by [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structures. |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_132) | Draws a series of rectangles specified by [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structures. |
| [draw_rectangles_f(pen, rects)](#draw_rectangles_f_pen_rects_133) | Draws a series of rectangles specified by [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structures. |
| [draw_string(s, font, brush, layout_rectangle)](#draw_string_s_font_brush_layout_rectangle_134) | Draws the specified text string in the specified rectangle with the specified [Brush](/imaging/python-net/aspose.imaging/brush/) and [Font](/imaging/python-net/aspose.imaging/font/) objects. |
| [draw_string(s, font, brush, layout_rectangle, format)](#draw_string_s_font_brush_layout_rectangle_format_135) | Draws the specified text string in the specified rectangle with the specified [Brush](/imaging/python-net/aspose.imaging/brush/) and [Font](/imaging/python-net/aspose.imaging/font/) objects using the formatting attributes of the specified [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [draw_string(s, font, brush, point)](#draw_string_s_font_brush_point_136) | Draws the specified text string at the specified location with the specified [Brush](/imaging/python-net/aspose.imaging/brush/) and [Font](/imaging/python-net/aspose.imaging/font/) objects. |
| [draw_string(s, font, brush, point, format)](#draw_string_s_font_brush_point_format_137) | Draws the specified text string at the specified location with the specified [Brush](/imaging/python-net/aspose.imaging/brush/) and [Font](/imaging/python-net/aspose.imaging/font/) objects using the formatting attributes of the specified [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [draw_string(s, font, brush, x, y)](#draw_string_s_font_brush_x_y_138) | Draws the specified text string at the specified location with the specified [Brush](/imaging/python-net/aspose.imaging/brush/) and [Font](/imaging/python-net/aspose.imaging/font/) objects. |
| [draw_string(s, font, brush, x, y, format)](#draw_string_s_font_brush_x_y_format_139) | Draws the specified text string at the specified location with the specified [Brush](/imaging/python-net/aspose.imaging/brush/) and [Font](/imaging/python-net/aspose.imaging/font/) objects using the formatting attributes of the specified [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [draw_string_at_point_f(s, font, brush, point)](#draw_string_at_point_f_s_font_brush_point_140) | Draws the specified text string at the specified location with the specified [Brush](/imaging/python-net/aspose.imaging/brush/) and [Font](/imaging/python-net/aspose.imaging/font/) objects. |
| [draw_string_at_point_f_format(s, font, brush, point, format)](#draw_string_at_point_f_format_s_font_brush_point_format_141) | Draws the specified text string at the specified location with the specified [Brush](/imaging/python-net/aspose.imaging/brush/) and [Font](/imaging/python-net/aspose.imaging/font/) objects using the formatting attributes of the specified [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [draw_string_at_xy(s, font, brush, x, y)](#draw_string_at_xy_s_font_brush_x_y_142) | Draws the specified text string at the specified location with the specified [Brush](/imaging/python-net/aspose.imaging/brush/) and [Font](/imaging/python-net/aspose.imaging/font/) objects. |
| [draw_string_in_rect(s, font, brush, layout_rectangle)](#draw_string_in_rect_s_font_brush_layout_rectangle_143) | Draws the specified text string in the specified rectangle with the specified [Brush](/imaging/python-net/aspose.imaging/brush/) and [Font](/imaging/python-net/aspose.imaging/font/) objects. |
| [draw_string_in_rect_f(s, font, brush, layout_rectangle, format)](#draw_string_in_rect_f_s_font_brush_layout_rectangle_format_144) | Draws the specified text string in the specified rectangle with the specified [Brush](/imaging/python-net/aspose.imaging/brush/) and [Font](/imaging/python-net/aspose.imaging/font/) objects using the formatting attributes of the specified [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| end_update() | Finishes caching of the graphics operations started after BeginUpdate was called. The preceding graphics operations will be applied at once when calling this method. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_145) | Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5 and [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fill mode. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_146) | Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5 and [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fill mode. |
| [fill_closed_curve(brush, points, fill_mode)](#fill_closed_curve_brush_points_fill_mode_147) | Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using the specified fill mode. This method uses a default tension of 0.5. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_148) | Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using the specified fill mode. This method uses a default tension of 0.5. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_149) | Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using the specified fill mode and tension. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_150) | Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using the specified fill mode and tension. |
| [fill_closed_curve_by_point(brush, points)](#fill_closed_curve_by_point_brush_points_151) | Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5 and [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fill mode. |
| [fill_closed_curve_by_point_f(brush, points)](#fill_closed_curve_by_point_f_brush_points_152) | Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5 and [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fill mode. |
| fill_closed_curve_by_point_f_fill_mode(brush, points, fillmode) |    |
| [fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension)](#fill_closed_curve_by_point_f_fill_mode_tension_brush_points_fillmode_tension_153) | Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using the specified fill mode and tension. |
| [fill_closed_curve_by_point_fill_mode(brush, points, fillmode)](#fill_closed_curve_by_point_fill_mode_brush_points_fillmode_154) | Fills the interior of a closed cardinal spline curve defined by an array of [Point](/imaging/python-net/aspose.imaging/point/) structures using the specified fill mode. This method uses a default tension of 0.5. |
| [fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension)](#fill_closed_curve_by_point_fill_mode_tension_brush_points_fillmode_tension_155) | Fills the interior of a closed cardinal spline curve defined by an array of [Point](/imaging/python-net/aspose.imaging/point/) structures using the specified fill mode and tension. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_156) | Fills the interior of an ellipse defined by a bounding rectangle specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_157) | Fills the interior of an ellipse defined by a bounding rectangle specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_158) | Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_159) | Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height. |
| [fill_ellipse_at_xywh(brush, x, y, width, height)](#fill_ellipse_at_xywh_brush_x_y_width_height_160) | Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height. |
| [fill_ellipse_at_xywhf(brush, x, y, width, height)](#fill_ellipse_at_xywhf_brush_x_y_width_height_161) | Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height. |
| [fill_ellipse_in_rect(brush, rect)](#fill_ellipse_in_rect_brush_rect_162) | Fills the interior of an ellipse defined by a bounding rectangle specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [fill_ellipse_in_rect_f(brush, rect)](#fill_ellipse_in_rect_f_brush_rect_163) | Fills the interior of an ellipse defined by a bounding rectangle specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [fill_path(brush, path)](#fill_path_brush_path_164) | Fills the interior of a [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_165) | Fills the interior of a pie section defined by an ellipse specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure and two radial lines. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_166) | Fills the interior of a pie section defined by an ellipse specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure and two radial lines. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_167) | Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_168) | Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines. |
| [fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_at_xy_brush_x_y_width_height_start_angle_sweep_angle_169) | Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines. |
| [fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_at_xyf_brush_x_y_width_height_start_angle_sweep_angle_170) | Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines. |
| [fill_pie_in_rect(brush, rect, start_angle, sweep_angle)](#fill_pie_in_rect_brush_rect_start_angle_sweep_angle_171) | Fills the interior of a pie section defined by an ellipse specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure and two radial lines. |
| [fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle)](#fill_pie_in_rect_f_brush_rect_start_angle_sweep_angle_172) | Fills the interior of a pie section defined by an ellipse specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure and two radial lines. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_173) | Fills the interior of a polygon defined by an array of points specified by [PointF](/imaging/python-net/aspose.imaging/pointf/) structures and [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_174) | Fills the interior of a polygon defined by an array of points specified by [PointF](/imaging/python-net/aspose.imaging/pointf/) structures and [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_175) | Fills the interior of a polygon defined by an array of points specified by [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using the specified fill mode. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_176) | Fills the interior of a polygon defined by an array of points specified by [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using the specified fill mode. |
| [fill_polygon_by_point(brush, points)](#fill_polygon_by_point_brush_points_177) | Fills the interior of a polygon defined by an array of points specified by [PointF](/imaging/python-net/aspose.imaging/pointf/) structures and [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [fill_polygon_by_point_f(brush, points)](#fill_polygon_by_point_f_brush_points_178) | Fills the interior of a polygon defined by an array of points specified by [PointF](/imaging/python-net/aspose.imaging/pointf/) structures and [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [fill_polygon_by_point_f_fill_mode(brush, points, fill_mode)](#fill_polygon_by_point_f_fill_mode_brush_points_fill_mode_179) | Fills the interior of a polygon defined by an array of points specified by [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using the specified fill mode. |
| [fill_polygon_by_point_fill_mode(brush, points, fill_mode)](#fill_polygon_by_point_fill_mode_brush_points_fill_mode_180) | Fills the interior of a polygon defined by an array of points specified by [Point](/imaging/python-net/aspose.imaging/point/) structures using the specified fill mode. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_181) | Fills the interior of a rectangle specified by a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_182) | Fills the interior of a rectangle specified by a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_183) | Fills the interior of a rectangle specified by a pair of coordinates, a width and a height. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_184) | Fills the interior of a rectangle specified by a pair of coordinates, a width and a height. |
| [fill_rectangle_f(brush, rect)](#fill_rectangle_f_brush_rect_185) | Fills the interior of a rectangle specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure. |
| [fill_rectangle_f_with_brush(brush, x, y, width, height)](#fill_rectangle_f_with_brush_brush_x_y_width_height_186) | Fills the interior of a rectangle specified by a pair of coordinates, a width and a height. |
| [fill_rectangle_with_brush(brush, x, y, width, height)](#fill_rectangle_with_brush_brush_x_y_width_height_187) | Fills the interior of a rectangle specified by a pair of coordinates, a width and a height. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_188) | Fills the interiors of a series of rectangles specified by [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structures. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_189) | Fills the interiors of a series of rectangles specified by [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structures. |
| [fill_rectangles_f(brush, rects)](#fill_rectangles_f_brush_rects_190) | Fills the interiors of a series of rectangles specified by [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structures. |
| [fill_region(brush, region)](#fill_region_brush_region_191) | Fills the interior of a [Region](/imaging/python-net/aspose.imaging/region/). |
| [measure_string(text, font, layout_area, string_format)](#measure_string_text_font_layout_area_string_format_192) | Measures the specified text string with specified parameters |
| [multiply_transform(matrix)](#multiply_transform_matrix_193) | Multiplies the [Matrix](/imaging/python-net/aspose.imaging/matrix/) that represents the local geometric transform of this [Graphics](/imaging/python-net/aspose.imaging/graphics/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/) by prepending the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_194) | Multiplies the [Matrix](/imaging/python-net/aspose.imaging/matrix/) that represents the local geometric transform of this [Graphics](/imaging/python-net/aspose.imaging/graphics/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/) in the specified order. |
| reset_transform() | Resets the [Graphics.transform](/imaging/python-net/aspose.imaging/graphics/) property to identity. |
| [rotate_transform(angle)](#rotate_transform_angle_195) | Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_196) | Rotates the local geometric transform by the specified amount in the specified order. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_197) | Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_198) | Scales the local geometric transform by the specified amounts in the specified order. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_199) | Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_200) | Translates the local geometric transform by the specified dimensions in the specified order. |


### Constructor: Graphics(source_image) {#Graphics_source_image_1}


```
 Graphics(source_image) 
```

Initializes a new instance of the [Graphics](/imaging/python-net/aspose.imaging/graphics/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The source image. |

### Method: clear(color) {#clear_color_1}


```
 clear(color) 
```

Clears the graphics surface using the specified color.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | The color to clear the graphics surface by. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...

**[Example # 2](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_2}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Draws an arc representing a portion of an ellipse specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the arc. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that defines the boundaries of the ellipse. |
| start_angle | float | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweep_angle | float | Angle in degrees measured clockwise from the _startAngle_ parameter to ending point of the arc. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_3}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Draws an arc representing a portion of an ellipse specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the arc. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that defines the boundaries of the ellipse. |
| start_angle | float | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweep_angle | float | Angle in degrees measured clockwise from the _startAngle_ parameter to ending point of the arc. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the arc. |
| x | float | The x-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| y | float | The y-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| width | float | Width of the rectangle that defines the ellipse. |
| height | float | Height of the rectangle that defines the ellipse. |
| start_angle | float | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweep_angle | float | Angle in degrees measured clockwise from the _startAngle_ parameter to ending point of the arc. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the arc. |
| x | int | The x-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| y | int | The y-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| width | int | Width of the rectangle that defines the ellipse. |
| height | int | Height of the rectangle that defines the ellipse. |
| start_angle | int | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweep_angle | int | Angle in degrees measured clockwise from the _startAngle_ parameter to ending point of the arc. |

### Method: draw_arc_in_rect(pen, rect, start_angle, sweep_angle) {#draw_arc_in_rect_pen_rect_start_angle_sweep_angle_6}


```
 draw_arc_in_rect(pen, rect, start_angle, sweep_angle) 
```

Draws an arc representing a portion of an ellipse specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the arc. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that defines the boundaries of the ellipse. |
| start_angle | float | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweep_angle | float | Angle in degrees measured clockwise from the _startAngle_ parameter to ending point of the arc. |

### Method: draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle) {#draw_arc_in_rect_f_pen_rect_start_angle_sweep_angle_7}


```
 draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle) 
```

Draws an arc representing a portion of an ellipse specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the arc. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that defines the boundaries of the ellipse. |
| start_angle | float | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweep_angle | float | Angle in degrees measured clockwise from the _startAngle_ parameter to ending point of the arc. |

### Method: draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_xy_pen_x_y_width_height_start_angle_sweep_angle_8}


```
 draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle) 
```

Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the arc. |
| x | int | The x-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| y | int | The y-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| width | int | Width of the rectangle that defines the ellipse. |
| height | int | Height of the rectangle that defines the ellipse. |
| start_angle | int | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweep_angle | int | Angle in degrees measured clockwise from the _startAngle_ parameter to ending point of the arc. |

### Method: draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_xyf_pen_x_y_width_height_start_angle_sweep_angle_9}


```
 draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle) 
```

Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the arc. |
| x | float | The x-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| y | float | The y-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| width | float | Width of the rectangle that defines the ellipse. |
| height | float | Height of the rectangle that defines the ellipse. |
| start_angle | float | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweep_angle | float | Angle in degrees measured clockwise from the _startAngle_ parameter to ending point of the arc. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_10}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Draws a Bézier spline defined by four [PointF](/imaging/python-net/aspose.imaging/pointf/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the curve. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that represents the starting point of the curve. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that represents the first control point for the curve. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that represents the second control point for the curve. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that represents the ending point of the curve. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_11}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Draws a Bézier spline defined by four [PointF](/imaging/python-net/aspose.imaging/pointf/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the curve. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that represents the starting point of the curve. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that represents the first control point for the curve. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that represents the second control point for the curve. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that represents the ending point of the curve. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) {#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_12}


```
 draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) 
```

Draws a Bézier spline defined by four ordered pairs of coordinates that represent points.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the curve. |
| x1 | float | The x-coordinate of the starting point of the curve. |
| y1 | float | The y-coordinate of the starting point of the curve. |
| x2 | float | The x-coordinate of the first control point of the curve. |
| y2 | float | The y-coordinate of the first control point of the curve. |
| x3 | float | The x-coordinate of the second control point of the curve. |
| y3 | float | The y-coordinate of the second control point of the curve. |
| x4 | float | The x-coordinate of the ending point of the curve. |
| y4 | float | The y-coordinate of the ending point of the curve. |

### Method: draw_bezier_by_points(pen, pt1, pt2, pt3, pt4) {#draw_bezier_by_points_pen_pt1_pt2_pt3_pt4_13}


```
 draw_bezier_by_points(pen, pt1, pt2, pt3, pt4) 
```

Draws a Bézier spline defined by four [PointF](/imaging/python-net/aspose.imaging/pointf/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the curve. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that represents the starting point of the curve. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that represents the first control point for the curve. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that represents the second control point for the curve. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that represents the ending point of the curve. |

### Method: draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4) {#draw_bezier_by_points_f_pen_pt1_pt2_pt3_pt4_14}


```
 draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4) 
```

Draws a Bézier spline defined by four [PointF](/imaging/python-net/aspose.imaging/pointf/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the curve. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that represents the starting point of the curve. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that represents the first control point for the curve. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that represents the second control point for the curve. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that represents the ending point of the curve. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_15}


```
 draw_beziers(pen, points) 
```

Draws a series of Bézier splines from an array of [Point](/imaging/python-net/aspose.imaging/point/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the curve. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of [Point](/imaging/python-net/aspose.imaging/point/) structures that represent the points that determine the curve. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_16}


```
 draw_beziers(pen, points) 
```

Draws a series of Bézier splines from an array of [Point](/imaging/python-net/aspose.imaging/point/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the curve. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of [Point](/imaging/python-net/aspose.imaging/point/) structures that represent the points that determine the curve. |

### Method: draw_beziers_by_pt_array(pen, points) {#draw_beziers_by_pt_array_pen_points_17}


```
 draw_beziers_by_pt_array(pen, points) 
```

Draws a series of Bézier splines from an array of [Point](/imaging/python-net/aspose.imaging/point/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the curve. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of [Point](/imaging/python-net/aspose.imaging/point/) structures that represent the points that determine the curve. |

### Method: draw_beziers_by_pt_array_f(pen, points) {#draw_beziers_by_pt_array_f_pen_points_18}


```
 draw_beziers_by_pt_array_f(pen, points) 
```

Draws a series of Bézier splines from an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the curve. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that represent the points that determine the curve. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_19}


```
 draw_closed_curve(pen, points) 
```

Draws a closed cardinal spline defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5 and [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fill mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and height of the curve. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that define the spline. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_20}


```
 draw_closed_curve(pen, points) 
```

Draws a closed cardinal spline defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5 and [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fill mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and height of the curve. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that define the spline. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_21}


```
 draw_closed_curve(pen, points, tension) 
```

Draws a closed cardinal spline defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using a specified tension. This method uses a default [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fill mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and height of the curve. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that define the spline. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_22}


```
 draw_closed_curve(pen, points, tension) 
```

Draws a closed cardinal spline defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using a specified tension. This method uses a default [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fill mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and height of the curve. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that define the spline. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### Method: draw_closed_curve_by_points(pen, points) {#draw_closed_curve_by_points_pen_points_23}


```
 draw_closed_curve_by_points(pen, points) 
```

Draws a closed cardinal spline defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5 and [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fill mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and height of the curve. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that define the spline. |

### Method: draw_closed_curve_by_points_f(pen, points) {#draw_closed_curve_by_points_f_pen_points_24}


```
 draw_closed_curve_by_points_f(pen, points) 
```

Draws a closed cardinal spline defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5 and [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fill mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and height of the curve. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that define the spline. |

### Method: draw_closed_curve_by_points_f_tension(pen, points, tension) {#draw_closed_curve_by_points_f_tension_pen_points_tension_25}


```
 draw_closed_curve_by_points_f_tension(pen, points, tension) 
```

Draws a closed cardinal spline defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using a specified tension. This method uses a default [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fill mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and height of the curve. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that define the spline. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### Method: draw_closed_curve_by_points_tension(pen, points, tension) {#draw_closed_curve_by_points_tension_pen_points_tension_26}


```
 draw_closed_curve_by_points_tension(pen, points, tension) 
```

Draws a closed cardinal spline defined by an array of [Point](/imaging/python-net/aspose.imaging/point/) structures using a specified tension. This method uses a default [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fill mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and height of the curve. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of [Point](/imaging/python-net/aspose.imaging/point/) structures that define the spline. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_27}


```
 draw_curve(pen, points) 
```

Draws a cardinal spline through a specified array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and height of the curve. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that define the spline. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_curve(pen, points) {#draw_curve_pen_points_28}


```
 draw_curve(pen, points) 
```

Draws a cardinal spline through a specified array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and height of the curve. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that define the spline. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_curve(pen, points, offset, number_of_segments) {#draw_curve_pen_points_offset_number_of_segments_29}


```
 draw_curve(pen, points, offset, number_of_segments) 
```

Draws a cardinal spline through a specified array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. The drawing begins offset from the beginning of the array.<br/>            This method uses a default tension of 0.5.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and height of the curve. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that define the spline. |
| offset | int | Offset from the first element in the array of the _points_ parameter to the starting point in the curve. |
| number_of_segments | int | Number of segments after the starting point to include in the curve. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_30}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Draws a cardinal spline through a specified array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using a specified tension. The drawing begins offset from the beginning of the array.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and height of the curve. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that define the spline. |
| offset | int | Offset from the first element in the array of the _points_ parameter to the starting point in the curve. |
| number_of_segments | int | Number of segments after the starting point to include in the curve. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_31}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Draws a cardinal spline through a specified array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using a specified tension. The drawing begins offset from the beginning of the array.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and height of the curve. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that define the spline. |
| offset | int | Offset from the first element in the array of the _points_ parameter to the starting point in the curve. |
| number_of_segments | int | Number of segments after the starting point to include in the curve. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_32}


```
 draw_curve(pen, points, tension) 
```

Draws a cardinal spline through a specified array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using a specified tension.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and height of the curve. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that represent the points that define the curve. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_33}


```
 draw_curve(pen, points, tension) 
```

Draws a cardinal spline through a specified array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using a specified tension.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and height of the curve. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that represent the points that define the curve. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### Method: draw_curve_by_point_fs(pen, points) {#draw_curve_by_point_fs_pen_points_34}


```
 draw_curve_by_point_fs(pen, points) 
```

Draws a cardinal spline through a specified array of [Point](/imaging/python-net/aspose.imaging/point/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and height of the curve. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of [Point](/imaging/python-net/aspose.imaging/point/) structures that define the spline. |

### Method: draw_curve_by_point_fs_tension(pen, points, tension) {#draw_curve_by_point_fs_tension_pen_points_tension_35}


```
 draw_curve_by_point_fs_tension(pen, points, tension) 
```

Draws a cardinal spline through a specified array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using a specified tension.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and height of the curve. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that represent the points that define the curve. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### Method: draw_curve_by_points(pen, points) {#draw_curve_by_points_pen_points_36}


```
 draw_curve_by_points(pen, points) 
```

Draws a cardinal spline through a specified array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and height of the curve. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that define the spline. |

### Method: draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) {#draw_curve_by_points_f_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_37}


```
 draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) 
```

Draws a cardinal spline through a specified array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using a specified tension. The drawing begins offset from the beginning of the array.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and height of the curve. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that define the spline. |
| offset | int | Offset from the first element in the array of the _points_ parameter to the starting point in the curve. |
| number_of_segments | int | Number of segments after the starting point to include in the curve. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### Method: draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) {#draw_curve_by_points_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_38}


```
 draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) 
```

Draws a cardinal spline through a specified array of [Point](/imaging/python-net/aspose.imaging/point/) structures using a specified tension.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and height of the curve. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of [Point](/imaging/python-net/aspose.imaging/point/) structures that define the spline. |
| offset | int | Offset from the first element in the array of the _points_ parameter to the starting point in the curve. |
| number_of_segments | int | Number of segments after the starting point to include in the curve. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### Method: draw_curve_by_points_tension(pen, points, tension) {#draw_curve_by_points_tension_pen_points_tension_39}


```
 draw_curve_by_points_tension(pen, points, tension) 
```

Draws a cardinal spline through a specified array of [Point](/imaging/python-net/aspose.imaging/point/) structures using a specified tension.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and height of the curve. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of [Point](/imaging/python-net/aspose.imaging/point/) structures that define the spline. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_40}


```
 draw_ellipse(pen, rect) 
```

Draws an ellipse defined by a bounding [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the ellipse. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that defines the boundaries of the ellipse. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_41}


```
 draw_ellipse(pen, rect) 
```

Draws an ellipse defined by a bounding [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the ellipse. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that defines the boundaries of the ellipse. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_42}


```
 draw_ellipse(pen, x, y, width, height) 
```

Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the ellipse. |
| x | float | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| y | float | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| width | float | Width of the bounding rectangle that defines the ellipse. |
| height | float | Height of the bounding rectangle that defines the ellipse. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_43}


```
 draw_ellipse(pen, x, y, width, height) 
```

Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the ellipse. |
| x | int | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| y | int | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| width | int | Width of the bounding rectangle that defines the ellipse. |
| height | int | Height of the bounding rectangle that defines the ellipse. |

### Method: draw_ellipse_by_xy(pen, x, y, width, height) {#draw_ellipse_by_xy_pen_x_y_width_height_44}


```
 draw_ellipse_by_xy(pen, x, y, width, height) 
```

Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the ellipse. |
| x | int | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| y | int | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| width | int | Width of the bounding rectangle that defines the ellipse. |
| height | int | Height of the bounding rectangle that defines the ellipse. |

### Method: draw_ellipse_by_xyf(pen, x, y, width, height) {#draw_ellipse_by_xyf_pen_x_y_width_height_45}


```
 draw_ellipse_by_xyf(pen, x, y, width, height) 
```

Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the ellipse. |
| x | float | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| y | float | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| width | float | Width of the bounding rectangle that defines the ellipse. |
| height | float | Height of the bounding rectangle that defines the ellipse. |

### Method: draw_ellipse_f(pen, rect) {#draw_ellipse_f_pen_rect_46}


```
 draw_ellipse_f(pen, rect) 
```

Draws an ellipse defined by a bounding [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the ellipse. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that defines the boundaries of the ellipse. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_47}


```
 draw_image(image, dest_points) 
```

Draws the specified portion of the specified _image_ at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of three PointF structures that define a parallelogram. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_48}


```
 draw_image(image, dest_points) 
```

Draws the specified portion of the specified _image_ at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of three PointF structures that define a parallelogram. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_49}


```
 draw_image(image, dest_points, src_rect) 
```

Draws the specified portion of the specified _image_ at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of three PointF structures that define a parallelogram. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The source rectangle. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_50}


```
 draw_image(image, dest_points, src_rect) 
```

Draws the specified portion of the specified _image_ at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of three PointF structures that define a parallelogram. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The source rectangle. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_51}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Draws the specified portion of the specified _image_ at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of three PointF structures that define a parallelogram. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The source rectangle. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The units of measure. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_52}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Draws the specified portion of the specified _image_ at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of three PointF structures that define a parallelogram. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The source rectangle. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The units of measure. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_53}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Draws the specified portion of the specified _image_ at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of three PointF structures that define a parallelogram. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The source rectangle. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The units of measure. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | The image attributes. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_54}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Draws the specified portion of the specified _image_ at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of three PointF structures that define a parallelogram. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The source rectangle. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The units of measure. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | The image attributes. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_55}


```
 draw_image(source_image, point) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), using its original physical size, at the specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that represents the upper-left corner of the drawn image. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_56}


```
 draw_image(source_image, point) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), using its original physical size, at the specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that represents the upper-left corner of the drawn image. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_57}


```
 draw_image(source_image, rect) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that specifies the location and size of the drawn image. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_58}


```
 draw_image(source_image, rect) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that specifies the location and size of the drawn image. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_59}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The destination rectangle. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The graphics unit. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_60}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The destination rectangle. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The graphics unit. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_61}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The destination rectangle. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The graphics unit. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | The image attributes. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_62}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The destination rectangle. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The graphics unit. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | The image attributes. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_63}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rect source. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rect destination. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The graphics unit. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_64}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The rect source. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The rect destination. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The graphics unit. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_65}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rect source. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rect destination. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The graphics unit. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | The image attributes. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_66}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The rect source. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The rect destination. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The graphics unit. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | The image attributes. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_67}


```
 draw_image(source_image, x, y) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), using its original physical size, at the specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| x | float | The x-coordinate of the upper-left corner of the drawn image. |
| y | float | The y-coordinate of the upper-left corner of the drawn image. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_68}


```
 draw_image(source_image, x, y) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), using its original physical size, at the specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| x | int | The x-coordinate of the upper-left corner of the drawn image. |
| y | int | The y-coordinate of the upper-left corner of the drawn image. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_69}


```
 draw_image(source_image, x, y, width, height) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| x | float | The x-coordinate of the upper-left corner of the drawn image. |
| y | float | The y-coordinate of the upper-left corner of the drawn image. |
| width | float | Width of the drawn image. |
| height | float | Height of the drawn image. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_70}


```
 draw_image(source_image, x, y, width, height) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| x | int | The x-coordinate of the upper-left corner of the drawn image. |
| y | int | The y-coordinate of the upper-left corner of the drawn image. |
| width | int | Width of the drawn image. |
| height | int | Height of the drawn image. |

### Method: draw_image_at_point(source_image, point) {#draw_image_at_point_source_image_point_71}


```
 draw_image_at_point(source_image, point) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), using its original physical size, at the specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that represents the upper-left corner of the drawn image. |

### Method: draw_image_at_point_f(source_image, point) {#draw_image_at_point_f_source_image_point_72}


```
 draw_image_at_point_f(source_image, point) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), using its original physical size, at the specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that represents the upper-left corner of the drawn image. |

### Method: draw_image_at_xy(source_image, x, y) {#draw_image_at_xy_source_image_x_y_73}


```
 draw_image_at_xy(source_image, x, y) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), using its original physical size, at the specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| x | int | The x-coordinate of the upper-left corner of the drawn image. |
| y | int | The y-coordinate of the upper-left corner of the drawn image. |

### Method: draw_image_at_xyf(source_image, x, y) {#draw_image_at_xyf_source_image_x_y_74}


```
 draw_image_at_xyf(source_image, x, y) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), using its original physical size, at the specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| x | float | The x-coordinate of the upper-left corner of the drawn image. |
| y | float | The y-coordinate of the upper-left corner of the drawn image. |

### Method: draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit) {#draw_image_dest_point_f_src_rect_f_with_unit_image_dest_points_src_rect_src_unit_75}


```
 draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit) 
```

Draws the specified portion of the specified _image_ at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of three PointF structures that define a parallelogram. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The source rectangle. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The units of measure. |

### Method: draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_dest_point_f_src_rect_f_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_76}


```
 draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) 
```

Draws the specified portion of the specified _image_ at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of three PointF structures that define a parallelogram. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The source rectangle. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The units of measure. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | The image attributes. |

### Method: draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect) {#draw_image_dest_points_f_src_rect_f_image_dest_points_src_rect_77}


```
 draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect) 
```

Draws the specified portion of the specified _image_ at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of three PointF structures that define a parallelogram. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The source rectangle. |

### Method: draw_image_dest_points_src_rect(image, dest_points, src_rect) {#draw_image_dest_points_src_rect_image_dest_points_src_rect_78}


```
 draw_image_dest_points_src_rect(image, dest_points, src_rect) 
```

Draws the specified portion of the specified _image_ at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of three PointF structures that define a parallelogram. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The source rectangle. |

### Method: draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit) {#draw_image_dest_points_src_rect_with_unit_image_dest_points_src_rect_src_unit_79}


```
 draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit) 
```

Draws the specified portion of the specified _image_ at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of three PointF structures that define a parallelogram. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The source rectangle. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The units of measure. |

### Method: draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_dest_points_src_rect_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_80}


```
 draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) 
```

Draws the specified portion of the specified _image_ at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of three PointF structures that define a parallelogram. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The source rectangle. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The units of measure. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | The image attributes. |

### Method: draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_dest_rect_f_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_81}


```
 draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The destination rectangle to draw in. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The graphics unit. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | The image attributes. |

### Method: draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_dest_rect_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_82}


```
 draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The destination rectangle. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The graphics unit. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | The image attributes. |

### Method: draw_image_in_rect(source_image, x, y, width, height) {#draw_image_in_rect_source_image_x_y_width_height_83}


```
 draw_image_in_rect(source_image, x, y, width, height) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| x | int | The x-coordinate of the upper-left corner of the drawn image. |
| y | int | The y-coordinate of the upper-left corner of the drawn image. |
| width | int | Width of the drawn image. |
| height | int | Height of the drawn image. |

### Method: draw_image_in_rect_f(source_image, x, y, width, height) {#draw_image_in_rect_f_source_image_x_y_width_height_84}


```
 draw_image_in_rect_f(source_image, x, y, width, height) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| x | float | The x-coordinate of the upper-left corner of the drawn image. |
| y | float | The y-coordinate of the upper-left corner of the drawn image. |
| width | float | Width of the drawn image. |
| height | float | Height of the drawn image. |

### Method: draw_image_in_rectangle(source_image, rect) {#draw_image_in_rectangle_source_image_rect_85}


```
 draw_image_in_rectangle(source_image, rect) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that specifies the location and size of the drawn image. |

### Method: draw_image_points(image, dest_points) {#draw_image_points_image_dest_points_86}


```
 draw_image_points(image, dest_points) 
```

Draws the specified portion of the specified _image_ at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of three PointF structures that define a parallelogram. |

### Method: draw_image_points_f(image, dest_points) {#draw_image_points_f_image_dest_points_87}


```
 draw_image_points_f(image, dest_points) 
```

Draws the specified portion of the specified _image_ at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of three PointF structures that define a parallelogram. |

### Method: draw_image_rectangle_f(source_image, rect) {#draw_image_rectangle_f_source_image_rect_88}


```
 draw_image_rectangle_f(source_image, rect) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that specifies the location and size of the drawn image. |

### Method: draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_src_dest_rects_f_with_unit_source_image_rect_source_rect_destination_graphics_unit_89}


```
 draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The rect source. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The rect destination. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The graphics unit. |

### Method: draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_src_dest_rects_with_unit_source_image_rect_source_rect_destination_graphics_unit_90}


```
 draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rect source. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rect destination. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The graphics unit. |

### Method: draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_src_dst_rect_f_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_91}


```
 draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The source rectangle. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The destination rectangle. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The graphics unit to use. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | The image attributes to use. |

### Method: draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_src_dst_rects_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_92}


```
 draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rect source. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rect destination. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The graphics unit. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | The image attributes. |

### Method: draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit) {#draw_image_to_rect_f_with_unit_source_image_rect_destination_graphics_unit_93}


```
 draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The destination rectangle. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The graphics unit. |

### Method: draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit) {#draw_image_to_rect_with_unit_source_image_rect_destination_graphics_unit_94}


```
 draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit) 
```

Draws the specified [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The destination rectangle. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | The graphics unit. |

### Method: draw_image_unscaled(source_image, point) {#draw_image_unscaled_source_image_point_95}


```
 draw_image_unscaled(source_image, point) 
```

Draws a specified image using its original physical size at a specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) structure that specifies the upper-left corner of the drawn image. |

### Method: draw_image_unscaled(source_image, rect) {#draw_image_unscaled_source_image_rect_96}


```
 draw_image_unscaled(source_image, rect) 
```

Draws a specified image using its original physical size at a specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) that specifies the upper-left corner of the drawn image. The X and Y properties of the rectangle specify the upper-left corner. The Width and Height properties are ignored. |

### Method: draw_image_unscaled(source_image, x, y) {#draw_image_unscaled_source_image_x_y_97}


```
 draw_image_unscaled(source_image, x, y) 
```

Draws the specified image using its original physical size at the location specified by a coordinate pair.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| x | int | The x-coordinate of the upper-left corner of the drawn image. |
| y | int | The y-coordinate of the upper-left corner of the drawn image. |

### Method: draw_image_unscaled(source_image, x, y, width, height) {#draw_image_unscaled_source_image_x_y_width_height_98}


```
 draw_image_unscaled(source_image, x, y, width, height) 
```

Draws a specified image using its original physical size at a specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| x | int | The x-coordinate of the upper-left corner of the drawn image. |
| y | int | The y-coordinate of the upper-left corner of the drawn image. |
| width | int | The parameter is not used. |
| height | int | The parameter is not used. |

### Method: draw_image_unscaled_and_clipped(source_image, rect) {#draw_image_unscaled_and_clipped_source_image_rect_99}


```
 draw_image_unscaled_and_clipped(source_image, rect) 
```

Draws the specified image without scaling and clips it, if necessary, to fit in the specified rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) in which to draw the image. |

### Method: draw_image_unscaled_in_rectangle(source_image, rect) {#draw_image_unscaled_in_rectangle_source_image_rect_100}


```
 draw_image_unscaled_in_rectangle(source_image, rect) 
```

Draws a specified image using its original physical size at a specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) that specifies the upper-left corner of the drawn image. The X and Y properties of the rectangle specify the upper-left corner. The Width and Height properties are ignored. |

### Method: draw_image_unscaled_to_point(source_image, point) {#draw_image_unscaled_to_point_source_image_point_101}


```
 draw_image_unscaled_to_point(source_image, point) 
```

Draws a specified image using its original physical size at a specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | The image to draw with. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) structure that specifies the upper-left corner of the drawn image. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_102}


```
 draw_line(pen, point1, point2) 
```

Draws a line connecting two [Point](/imaging/python-net/aspose.imaging/point/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the line. |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) structure that represents the first point to connect. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) structure that represents the second point to connect. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_103}


```
 draw_line(pen, point1, point2) 
```

Draws a line connecting two [Point](/imaging/python-net/aspose.imaging/point/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the line. |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [Point](/imaging/python-net/aspose.imaging/point/) structure that represents the first point to connect. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [Point](/imaging/python-net/aspose.imaging/point/) structure that represents the second point to connect. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_104}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Draws a line connecting the two points specified by the coordinate pairs.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the line. |
| x1 | int | The x-coordinate of the first point. |
| y1 | int | The y-coordinate of the first point. |
| x2 | int | The x-coordinate of the second point. |
| y2 | int | The y-coordinate of the second point. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_105}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Draws a line connecting the two points specified by the coordinate pairs.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the line. |
| x1 | float | The x-coordinate of the first point. |
| y1 | float | The y-coordinate of the first point. |
| x2 | float | The x-coordinate of the second point. |
| y2 | float | The y-coordinate of the second point. |

### Method: draw_line_by_xy(pen, x1, y1, x2, y2) {#draw_line_by_xy_pen_x1_y1_x2_y2_106}


```
 draw_line_by_xy(pen, x1, y1, x2, y2) 
```

Draws a line connecting the two points specified by the coordinate pairs.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the line. |
| x1 | int | The x-coordinate of the first point. |
| y1 | int | The y-coordinate of the first point. |
| x2 | int | The x-coordinate of the second point. |
| y2 | int | The y-coordinate of the second point. |

### Method: draw_line_f_by_xy(pen, x1, y1, x2, y2) {#draw_line_f_by_xy_pen_x1_y1_x2_y2_107}


```
 draw_line_f_by_xy(pen, x1, y1, x2, y2) 
```

Draws a line connecting the two points specified by the coordinate pairs.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the line. |
| x1 | float | The x-coordinate of the first point. |
| y1 | float | The y-coordinate of the first point. |
| x2 | float | The x-coordinate of the second point. |
| y2 | float | The y-coordinate of the second point. |

### Method: draw_line_point_f(pen, point1, point2) {#draw_line_point_f_pen_point1_point2_108}


```
 draw_line_point_f(pen, point1, point2) 
```

Draws a line connecting two [PointF](/imaging/python-net/aspose.imaging/pointf/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the line. |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that represents the first point to connect. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that represents the second point to connect. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_109}


```
 draw_lines(pen, points) 
```

Draws a series of line segments that connect an array of [Point](/imaging/python-net/aspose.imaging/point/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the line segments. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of [Point](/imaging/python-net/aspose.imaging/point/) structures that represent the points to connect. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_110}


```
 draw_lines(pen, points) 
```

Draws a series of line segments that connect an array of [Point](/imaging/python-net/aspose.imaging/point/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the line segments. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of [Point](/imaging/python-net/aspose.imaging/point/) structures that represent the points to connect. |

### Method: draw_lines_f(pen, points) {#draw_lines_f_pen_points_111}


```
 draw_lines_f(pen, points) 
```

Draws a series of line segments that connect an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the line segments. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that represent the points to connect. |

### Method: draw_path(pen, path) {#draw_path_pen_path_112}


```
 draw_path(pen, path) 
```

Draws a [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the path. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) to draw. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_113}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Draws a pie shape defined by an ellipse specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure and two radial lines.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the pie shape. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that represents the bounding rectangle that defines the ellipse from which the pie shape comes. |
| start_angle | float | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweep_angle | float | Angle measured in degrees clockwise from the _startAngle_ parameter to the second side of the pie shape. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_114}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Draws a pie shape defined by an ellipse specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure and two radial lines.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the pie shape. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that represents the bounding rectangle that defines the ellipse from which the pie shape comes. |
| start_angle | float | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweep_angle | float | Angle measured in degrees clockwise from the _startAngle_ parameter to the second side of the pie shape. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_115}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the pie shape. |
| x | float | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| y | float | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| width | float | Width of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| height | float | Height of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| start_angle | float | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweep_angle | float | Angle measured in degrees clockwise from the _startAngle_ parameter to the second side of the pie shape. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_116}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the pie shape. |
| x | int | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| y | int | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| width | int | Width of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| height | int | Height of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| start_angle | int | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweep_angle | int | Angle measured in degrees clockwise from the _startAngle_ parameter to the second side of the pie shape. |

### Method: draw_pie_in_rect(pen, rect, start_angle, sweep_angle) {#draw_pie_in_rect_pen_rect_start_angle_sweep_angle_117}


```
 draw_pie_in_rect(pen, rect, start_angle, sweep_angle) 
```

Draws a pie shape defined by an ellipse specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure and two radial lines.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the pie shape. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that represents the bounding rectangle that defines the ellipse from which the pie shape comes. |
| start_angle | float | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweep_angle | float | Angle measured in degrees clockwise from the _startAngle_ parameter to the second side of the pie shape. |

### Method: draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle) {#draw_pie_in_rect_f_pen_rect_start_angle_sweep_angle_118}


```
 draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle) 
```

Draws a pie shape defined by an ellipse specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure and two radial lines.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the pie shape. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that represents the bounding rectangle that defines the ellipse from which the pie shape comes. |
| start_angle | float | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweep_angle | float | Angle measured in degrees clockwise from the _startAngle_ parameter to the second side of the pie shape. |

### Method: draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_xy_pen_x_y_width_height_start_angle_sweep_angle_119}


```
 draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle) 
```

Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the pie shape. |
| x | int | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| y | int | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| width | int | Width of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| height | int | Height of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| start_angle | int | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweep_angle | int | Angle measured in degrees clockwise from the _startAngle_ parameter to the second side of the pie shape. |

### Method: draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_xyf_pen_x_y_width_height_start_angle_sweep_angle_120}


```
 draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle) 
```

Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the pie shape. |
| x | float | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| y | float | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| width | float | Width of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| height | float | Height of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| start_angle | float | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweep_angle | float | Angle measured in degrees clockwise from the _startAngle_ parameter to the second side of the pie shape. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_121}


```
 draw_polygon(pen, points) 
```

Draws a polygon defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the polygon. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that represent the vertices of the polygon. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_122}


```
 draw_polygon(pen, points) 
```

Draws a polygon defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the polygon. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that represent the vertices of the polygon. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_polygon_f(pen, points) {#draw_polygon_f_pen_points_123}


```
 draw_polygon_f(pen, points) 
```

Draws a polygon defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the polygon. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that represent the vertices of the polygon. |

### Method: draw_rect(pen, x, y, width, height) {#draw_rect_pen_x_y_width_height_124}


```
 draw_rect(pen, x, y, width, height) 
```

Draws a rectangle specified by a coordinate pair, a width, and a height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | A [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the rectangle. |
| x | int | The x-coordinate of the upper-left corner of the rectangle to draw. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to draw. |
| width | int | The width of the rectangle to draw. |
| height | int | The height of the rectangle to draw. |

### Method: draw_rect_f(pen, x, y, width, height) {#draw_rect_f_pen_x_y_width_height_125}


```
 draw_rect_f(pen, x, y, width, height) 
```

Draws a rectangle specified by a coordinate pair, a width, and a height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | A [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the rectangle. |
| x | float | The x-coordinate of the upper-left corner of the rectangle to draw. |
| y | float | The y-coordinate of the upper-left corner of the rectangle to draw. |
| width | float | The width of the rectangle to draw. |
| height | float | The height of the rectangle to draw. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_126}


```
 draw_rectangle(pen, rect) 
```

Draws a rectangle specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | A [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the rectangle. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | A [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that represents the rectangle to draw. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_127}


```
 draw_rectangle(pen, rect) 
```

Draws a rectangle specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | A [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the rectangle. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | A [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that represents the rectangle to draw. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_128}


```
 draw_rectangle(pen, x, y, width, height) 
```

Draws a rectangle specified by a coordinate pair, a width, and a height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | A [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the rectangle. |
| x | float | The x-coordinate of the upper-left corner of the rectangle to draw. |
| y | float | The y-coordinate of the upper-left corner of the rectangle to draw. |
| width | float | The width of the rectangle to draw. |
| height | float | The height of the rectangle to draw. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_129}


```
 draw_rectangle(pen, x, y, width, height) 
```

Draws a rectangle specified by a coordinate pair, a width, and a height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | A [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the rectangle. |
| x | int | The x-coordinate of the upper-left corner of the rectangle to draw. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to draw. |
| width | int | The width of the rectangle to draw. |
| height | int | The height of the rectangle to draw. |

### Method: draw_rectangle_f(pen, rect) {#draw_rectangle_f_pen_rect_130}


```
 draw_rectangle_f(pen, rect) 
```

Draws a rectangle specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | A [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the rectangle. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | A [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that represents the rectangle to draw. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_131}


```
 draw_rectangles(pen, rects) 
```

Draws a series of rectangles specified by [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the outlines of the rectangles. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Array of [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structures that represent the rectangles to draw. |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_132}


```
 draw_rectangles(pen, rects) 
```

Draws a series of rectangles specified by [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the outlines of the rectangles. |
| rects | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | Array of [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structures that represent the rectangles to draw. |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: draw_rectangles_f(pen, rects) {#draw_rectangles_f_pen_rects_133}


```
 draw_rectangles_f(pen, rects) 
```

Draws a series of rectangles specified by [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) that determines the color, width, and style of the outlines of the rectangles. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Array of [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structures that represent the rectangles to draw. |

### Method: draw_string(s, font, brush, layout_rectangle) {#draw_string_s_font_brush_layout_rectangle_134}


```
 draw_string(s, font, brush, layout_rectangle) 
```

Draws the specified text string in the specified rectangle with the specified [Brush](/imaging/python-net/aspose.imaging/brush/) and [Font](/imaging/python-net/aspose.imaging/font/) objects.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| s | string | String to draw. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) that defines the text format of the string. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the color and texture of the drawn text. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that specifies the location of the drawn text. |

### Method: draw_string(s, font, brush, layout_rectangle, format) {#draw_string_s_font_brush_layout_rectangle_format_135}


```
 draw_string(s, font, brush, layout_rectangle, format) 
```

Draws the specified text string in the specified rectangle with the specified [Brush](/imaging/python-net/aspose.imaging/brush/) and [Font](/imaging/python-net/aspose.imaging/font/) objects using the formatting attributes of the specified [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| s | string | String to draw. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) that defines the text format of the string. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the color and texture of the drawn text. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that specifies the location of the drawn text. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) that specifies formatting attributes, such as line spacing and alignment, that are applied to the drawn text. |

### Method: draw_string(s, font, brush, point) {#draw_string_s_font_brush_point_136}


```
 draw_string(s, font, brush, point) 
```

Draws the specified text string at the specified location with the specified [Brush](/imaging/python-net/aspose.imaging/brush/) and [Font](/imaging/python-net/aspose.imaging/font/) objects.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| s | string | String to draw. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) that defines the text format of the string. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the color and texture of the drawn text. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that specifies the upper-left corner of the drawn text. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_string(s, font, brush, point, format) {#draw_string_s_font_brush_point_format_137}


```
 draw_string(s, font, brush, point, format) 
```

Draws the specified text string at the specified location with the specified [Brush](/imaging/python-net/aspose.imaging/brush/) and [Font](/imaging/python-net/aspose.imaging/font/) objects using the formatting attributes of the specified [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| s | string | String to draw. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) that defines the text format of the string. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the color and texture of the drawn text. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that specifies the upper-left corner of the drawn text. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) that specifies formatting attributes, such as line spacing and alignment, that are applied to the drawn text. |

### Method: draw_string(s, font, brush, x, y) {#draw_string_s_font_brush_x_y_138}


```
 draw_string(s, font, brush, x, y) 
```

Draws the specified text string at the specified location with the specified [Brush](/imaging/python-net/aspose.imaging/brush/) and [Font](/imaging/python-net/aspose.imaging/font/) objects.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| s | string | String to draw. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) that defines the text format of the string. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the color and texture of the drawn text. |
| x | float | The x-coordinate of the upper-left corner of the drawn text. |
| y | float | The y-coordinate of the upper-left corner of the drawn text. |

### Method: draw_string(s, font, brush, x, y, format) {#draw_string_s_font_brush_x_y_format_139}


```
 draw_string(s, font, brush, x, y, format) 
```

Draws the specified text string at the specified location with the specified [Brush](/imaging/python-net/aspose.imaging/brush/) and [Font](/imaging/python-net/aspose.imaging/font/) objects using the formatting attributes of the specified [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| s | string | String to draw. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) that defines the text format of the string. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the color and texture of the drawn text. |
| x | float | The x-coordinate of the upper-left corner of the drawn text. |
| y | float | The y-coordinate of the upper-left corner of the drawn text. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) that specifies formatting attributes, such as line spacing and alignment, that are applied to the drawn text. |

### Method: draw_string_at_point_f(s, font, brush, point) {#draw_string_at_point_f_s_font_brush_point_140}


```
 draw_string_at_point_f(s, font, brush, point) 
```

Draws the specified text string at the specified location with the specified [Brush](/imaging/python-net/aspose.imaging/brush/) and [Font](/imaging/python-net/aspose.imaging/font/) objects.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| s | string | String to draw. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) that defines the text format of the string. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the color and texture of the drawn text. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that specifies the upper-left corner of the drawn text. |

### Method: draw_string_at_point_f_format(s, font, brush, point, format) {#draw_string_at_point_f_format_s_font_brush_point_format_141}


```
 draw_string_at_point_f_format(s, font, brush, point, format) 
```

Draws the specified text string at the specified location with the specified [Brush](/imaging/python-net/aspose.imaging/brush/) and [Font](/imaging/python-net/aspose.imaging/font/) objects using the formatting attributes of the specified [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| s | string | String to draw. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) that defines the text format of the string. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the color and texture of the drawn text. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure that specifies the upper-left corner of the drawn text. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) that specifies formatting attributes, such as line spacing and alignment, that are applied to the drawn text. |

### Method: draw_string_at_xy(s, font, brush, x, y) {#draw_string_at_xy_s_font_brush_x_y_142}


```
 draw_string_at_xy(s, font, brush, x, y) 
```

Draws the specified text string at the specified location with the specified [Brush](/imaging/python-net/aspose.imaging/brush/) and [Font](/imaging/python-net/aspose.imaging/font/) objects.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| s | string | String to draw. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) that defines the text format of the string. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the color and texture of the drawn text. |
| x | float | The x-coordinate of the upper-left corner of the drawn text. |
| y | float | The y-coordinate of the upper-left corner of the drawn text. |

### Method: draw_string_in_rect(s, font, brush, layout_rectangle) {#draw_string_in_rect_s_font_brush_layout_rectangle_143}


```
 draw_string_in_rect(s, font, brush, layout_rectangle) 
```

Draws the specified text string in the specified rectangle with the specified [Brush](/imaging/python-net/aspose.imaging/brush/) and [Font](/imaging/python-net/aspose.imaging/font/) objects.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| s | string | String to draw. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) that defines the text format of the string. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the color and texture of the drawn text. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that specifies the location of the drawn text. |

### Method: draw_string_in_rect_f(s, font, brush, layout_rectangle, format) {#draw_string_in_rect_f_s_font_brush_layout_rectangle_format_144}


```
 draw_string_in_rect_f(s, font, brush, layout_rectangle, format) 
```

Draws the specified text string in the specified rectangle with the specified [Brush](/imaging/python-net/aspose.imaging/brush/) and [Font](/imaging/python-net/aspose.imaging/font/) objects using the formatting attributes of the specified [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| s | string | String to draw. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) that defines the text format of the string. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the color and texture of the drawn text. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that specifies the location of the drawn text. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) that specifies formatting attributes, such as line spacing and alignment, that are applied to the drawn text. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_145}


```
 fill_closed_curve(brush, points) 
```

Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5 and [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fill mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that define the spline. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_146}


```
 fill_closed_curve(brush, points) 
```

Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5 and [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fill mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that define the spline. |

### Method: fill_closed_curve(brush, points, fill_mode) {#fill_closed_curve_brush_points_fill_mode_147}


```
 fill_closed_curve(brush, points, fill_mode) 
```

Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using the specified fill mode. This method uses a default tension of 0.5.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that define the spline. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Member of the [FillMode](/imaging/python-net/aspose.imaging/fillmode/) enumeration that determines how the curve is filled. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_148}


```
 fill_closed_curve(brush, points, fillmode) 
```

Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using the specified fill mode. This method uses a default tension of 0.5.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that define the spline. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) |  |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_149}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using the specified fill mode and tension.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | A [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that define the spline. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Member of the [FillMode](/imaging/python-net/aspose.imaging/fillmode/) enumeration that determines how the curve is filled. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_150}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using the specified fill mode and tension.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | A [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that define the spline. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Member of the [FillMode](/imaging/python-net/aspose.imaging/fillmode/) enumeration that determines how the curve is filled. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### Method: fill_closed_curve_by_point(brush, points) {#fill_closed_curve_by_point_brush_points_151}


```
 fill_closed_curve_by_point(brush, points) 
```

Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5 and [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fill mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that define the spline. |

### Method: fill_closed_curve_by_point_f(brush, points) {#fill_closed_curve_by_point_f_brush_points_152}


```
 fill_closed_curve_by_point_f(brush, points) 
```

Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures. This method uses a default tension of 0.5 and [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fill mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that define the spline. |

### Method: fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension) {#fill_closed_curve_by_point_f_fill_mode_tension_brush_points_fillmode_tension_153}


```
 fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension) 
```

Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using the specified fill mode and tension.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | A [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that define the spline. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Member of the [FillMode](/imaging/python-net/aspose.imaging/fillmode/) enumeration that determines how the curve is filled. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### Method: fill_closed_curve_by_point_fill_mode(brush, points, fillmode) {#fill_closed_curve_by_point_fill_mode_brush_points_fillmode_154}


```
 fill_closed_curve_by_point_fill_mode(brush, points, fillmode) 
```

Fills the interior of a closed cardinal spline curve defined by an array of [Point](/imaging/python-net/aspose.imaging/point/) structures using the specified fill mode. This method uses a default tension of 0.5.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of [Point](/imaging/python-net/aspose.imaging/point/) structures that define the spline. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Member of the [FillMode](/imaging/python-net/aspose.imaging/fillmode/) enumeration that determines how the curve is filled. |

### Method: fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension) {#fill_closed_curve_by_point_fill_mode_tension_brush_points_fillmode_tension_155}


```
 fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension) 
```

Fills the interior of a closed cardinal spline curve defined by an array of [Point](/imaging/python-net/aspose.imaging/point/) structures using the specified fill mode and tension.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of [Point](/imaging/python-net/aspose.imaging/point/) structures that define the spline. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Member of the [FillMode](/imaging/python-net/aspose.imaging/fillmode/) enumeration that determines how the curve is filled. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_156}


```
 fill_ellipse(brush, rect) 
```

Fills the interior of an ellipse defined by a bounding rectangle specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that represents the bounding rectangle that defines the ellipse. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_157}


```
 fill_ellipse(brush, rect) 
```

Fills the interior of an ellipse defined by a bounding rectangle specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that represents the bounding rectangle that defines the ellipse. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_158}


```
 fill_ellipse(brush, x, y, width, height) 
```

Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| x | float | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| y | float | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| width | float | Width of the bounding rectangle that defines the ellipse. |
| height | float | Height of the bounding rectangle that defines the ellipse. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_159}


```
 fill_ellipse(brush, x, y, width, height) 
```

Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| x | int | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| y | int | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| width | int | Width of the bounding rectangle that defines the ellipse. |
| height | int | Height of the bounding rectangle that defines the ellipse. |

### Method: fill_ellipse_at_xywh(brush, x, y, width, height) {#fill_ellipse_at_xywh_brush_x_y_width_height_160}


```
 fill_ellipse_at_xywh(brush, x, y, width, height) 
```

Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| x | int | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| y | int | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| width | int | Width of the bounding rectangle that defines the ellipse. |
| height | int | Height of the bounding rectangle that defines the ellipse. |

### Method: fill_ellipse_at_xywhf(brush, x, y, width, height) {#fill_ellipse_at_xywhf_brush_x_y_width_height_161}


```
 fill_ellipse_at_xywhf(brush, x, y, width, height) 
```

Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| x | float | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| y | float | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| width | float | Width of the bounding rectangle that defines the ellipse. |
| height | float | Height of the bounding rectangle that defines the ellipse. |

### Method: fill_ellipse_in_rect(brush, rect) {#fill_ellipse_in_rect_brush_rect_162}


```
 fill_ellipse_in_rect(brush, rect) 
```

Fills the interior of an ellipse defined by a bounding rectangle specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that represents the bounding rectangle that defines the ellipse. |

### Method: fill_ellipse_in_rect_f(brush, rect) {#fill_ellipse_in_rect_f_brush_rect_163}


```
 fill_ellipse_in_rect_f(brush, rect) 
```

Fills the interior of an ellipse defined by a bounding rectangle specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that represents the bounding rectangle that defines the ellipse. |

### Method: fill_path(brush, path) {#fill_path_brush_path_164}


```
 fill_path(brush, path) 
```

Fills the interior of a [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) that represents the path to fill. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_165}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Fills the interior of a pie section defined by an ellipse specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure and two radial lines.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that represents the bounding rectangle that defines the ellipse from which the pie section comes. |
| start_angle | float | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweep_angle | float | Angle in degrees measured clockwise from the _startAngle_ parameter to the second side of the pie section. |


**See also:**

**[Example # 1](#example_95)**: The following example shows how to compose an animated GIF image from individ...


### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_166}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Fills the interior of a pie section defined by an ellipse specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure and two radial lines.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that represents the bounding rectangle that defines the ellipse from which the pie section comes. |
| start_angle | float | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweep_angle | float | Angle in degrees measured clockwise from the _startAngle_ parameter to the second side of the pie section. |


**See also:**

**[Example # 1](#example_95)**: The following example shows how to compose an animated GIF image from individ...


### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_167}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| x | float | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| y | float | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| width | float | Width of the bounding rectangle that defines the ellipse from which the pie section comes. |
| height | float | Height of the bounding rectangle that defines the ellipse from which the pie section comes. |
| start_angle | float | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweep_angle | float | Angle in degrees measured clockwise from the _startAngle_ parameter to the second side of the pie section. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_168}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| x | int | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| y | int | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| width | int | Width of the bounding rectangle that defines the ellipse from which the pie section comes. |
| height | int | Height of the bounding rectangle that defines the ellipse from which the pie section comes. |
| start_angle | int | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweep_angle | int | Angle in degrees measured clockwise from the _startAngle_ parameter to the second side of the pie section. |

### Method: fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_at_xy_brush_x_y_width_height_start_angle_sweep_angle_169}


```
 fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle) 
```

Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| x | int | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| y | int | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| width | int | Width of the bounding rectangle that defines the ellipse from which the pie section comes. |
| height | int | Height of the bounding rectangle that defines the ellipse from which the pie section comes. |
| start_angle | int | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweep_angle | int | Angle in degrees measured clockwise from the _startAngle_ parameter to the second side of the pie section. |

### Method: fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_at_xyf_brush_x_y_width_height_start_angle_sweep_angle_170}


```
 fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle) 
```

Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| x | float | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| y | float | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| width | float | Width of the bounding rectangle that defines the ellipse from which the pie section comes. |
| height | float | Height of the bounding rectangle that defines the ellipse from which the pie section comes. |
| start_angle | float | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweep_angle | float | Angle in degrees measured clockwise from the _startAngle_ parameter to the second side of the pie section. |

### Method: fill_pie_in_rect(brush, rect, start_angle, sweep_angle) {#fill_pie_in_rect_brush_rect_start_angle_sweep_angle_171}


```
 fill_pie_in_rect(brush, rect, start_angle, sweep_angle) 
```

Fills the interior of a pie section defined by an ellipse specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure and two radial lines.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that represents the bounding rectangle that defines the ellipse from which the pie section comes. |
| start_angle | float | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweep_angle | float | Angle in degrees measured clockwise from the _startAngle_ parameter to the second side of the pie section. |

### Method: fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle) {#fill_pie_in_rect_f_brush_rect_start_angle_sweep_angle_172}


```
 fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle) 
```

Fills the interior of a pie section defined by an ellipse specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure and two radial lines.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that represents the bounding rectangle that defines the ellipse from which the pie section comes. |
| start_angle | float | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweep_angle | float | Angle in degrees measured clockwise from the _startAngle_ parameter to the second side of the pie section. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_173}


```
 fill_polygon(brush, points) 
```

Fills the interior of a polygon defined by an array of points specified by [PointF](/imaging/python-net/aspose.imaging/pointf/) structures and [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that represent the vertices of the polygon to fill. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_174}


```
 fill_polygon(brush, points) 
```

Fills the interior of a polygon defined by an array of points specified by [PointF](/imaging/python-net/aspose.imaging/pointf/) structures and [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that represent the vertices of the polygon to fill. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_175}


```
 fill_polygon(brush, points, fill_mode) 
```

Fills the interior of a polygon defined by an array of points specified by [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using the specified fill mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that represent the vertices of the polygon to fill. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Member of the [FillMode](/imaging/python-net/aspose.imaging/fillmode/) enumeration that determines the style of the fill. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_176}


```
 fill_polygon(brush, points, fill_mode) 
```

Fills the interior of a polygon defined by an array of points specified by [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using the specified fill mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that represent the vertices of the polygon to fill. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Member of the [FillMode](/imaging/python-net/aspose.imaging/fillmode/) enumeration that determines the style of the fill. |

### Method: fill_polygon_by_point(brush, points) {#fill_polygon_by_point_brush_points_177}


```
 fill_polygon_by_point(brush, points) 
```

Fills the interior of a polygon defined by an array of points specified by [PointF](/imaging/python-net/aspose.imaging/pointf/) structures and [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that represent the vertices of the polygon to fill. |

### Method: fill_polygon_by_point_f(brush, points) {#fill_polygon_by_point_f_brush_points_178}


```
 fill_polygon_by_point_f(brush, points) 
```

Fills the interior of a polygon defined by an array of points specified by [PointF](/imaging/python-net/aspose.imaging/pointf/) structures and [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that represent the vertices of the polygon to fill. |

### Method: fill_polygon_by_point_f_fill_mode(brush, points, fill_mode) {#fill_polygon_by_point_f_fill_mode_brush_points_fill_mode_179}


```
 fill_polygon_by_point_f_fill_mode(brush, points, fill_mode) 
```

Fills the interior of a polygon defined by an array of points specified by [PointF](/imaging/python-net/aspose.imaging/pointf/) structures using the specified fill mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array of [PointF](/imaging/python-net/aspose.imaging/pointf/) structures that represent the vertices of the polygon to fill. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Member of the [FillMode](/imaging/python-net/aspose.imaging/fillmode/) enumeration that determines the style of the fill. |

### Method: fill_polygon_by_point_fill_mode(brush, points, fill_mode) {#fill_polygon_by_point_fill_mode_brush_points_fill_mode_180}


```
 fill_polygon_by_point_fill_mode(brush, points, fill_mode) 
```

Fills the interior of a polygon defined by an array of points specified by [Point](/imaging/python-net/aspose.imaging/point/) structures using the specified fill mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array of [Point](/imaging/python-net/aspose.imaging/point/) structures that represent the vertices of the polygon to fill. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Member of the [FillMode](/imaging/python-net/aspose.imaging/fillmode/) enumeration that determines the style of the fill. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_181}


```
 fill_rectangle(brush, rect) 
```

Fills the interior of a rectangle specified by a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that represents the rectangle to fill. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_182}


```
 fill_rectangle(brush, rect) 
```

Fills the interior of a rectangle specified by a [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that represents the rectangle to fill. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_183}


```
 fill_rectangle(brush, x, y, width, height) 
```

Fills the interior of a rectangle specified by a pair of coordinates, a width and a height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| x | float | The x-coordinate of the upper-left corner of the rectangle to fill. |
| y | float | The y-coordinate of the upper-left corner of the rectangle to fill. |
| width | float | Width of the rectangle to fill. |
| height | float | Height of the rectangle to fill. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_184}


```
 fill_rectangle(brush, x, y, width, height) 
```

Fills the interior of a rectangle specified by a pair of coordinates, a width and a height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| x | int | The x-coordinate of the upper-left corner of the rectangle to fill. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to fill. |
| width | int | Width of the rectangle to fill. |
| height | int | Height of the rectangle to fill. |

### Method: fill_rectangle_f(brush, rect) {#fill_rectangle_f_brush_rect_185}


```
 fill_rectangle_f(brush, rect) 
```

Fills the interior of a rectangle specified by a [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that represents the rectangle to fill. |

### Method: fill_rectangle_f_with_brush(brush, x, y, width, height) {#fill_rectangle_f_with_brush_brush_x_y_width_height_186}


```
 fill_rectangle_f_with_brush(brush, x, y, width, height) 
```

Fills the interior of a rectangle specified by a pair of coordinates, a width and a height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| x | float | The x-coordinate of the upper-left corner of the rectangle to fill. |
| y | float | The y-coordinate of the upper-left corner of the rectangle to fill. |
| width | float | Width of the rectangle to fill. |
| height | float | Height of the rectangle to fill. |

### Method: fill_rectangle_with_brush(brush, x, y, width, height) {#fill_rectangle_with_brush_brush_x_y_width_height_187}


```
 fill_rectangle_with_brush(brush, x, y, width, height) 
```

Fills the interior of a rectangle specified by a pair of coordinates, a width and a height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| x | int | The x-coordinate of the upper-left corner of the rectangle to fill. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to fill. |
| width | int | Width of the rectangle to fill. |
| height | int | Height of the rectangle to fill. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_188}


```
 fill_rectangles(brush, rects) 
```

Fills the interiors of a series of rectangles specified by [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| rects | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | Array of [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structures that represent the rectangles to fill. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_189}


```
 fill_rectangles(brush, rects) 
```

Fills the interiors of a series of rectangles specified by [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Array of [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structures that represent the rectangles to fill. |

### Method: fill_rectangles_f(brush, rects) {#fill_rectangles_f_brush_rects_190}


```
 fill_rectangles_f(brush, rects) 
```

Fills the interiors of a series of rectangles specified by [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Array of [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structures that represent the rectangles to fill. |

### Method: fill_region(brush, region) {#fill_region_brush_region_191}


```
 fill_region(brush, region) 
```

Fills the interior of a [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) that determines the characteristics of the fill. |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | [Region](/imaging/python-net/aspose.imaging/region/) that represents the area to fill. |

### Method: measure_string(text, font, layout_area, string_format) {#measure_string_text_font_layout_area_string_format_192}


```
 measure_string(text, font, layout_area, string_format) 
```

Measures the specified text string with specified parameters

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| text | string | The text to measure. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | The font to measure. |
| layout_area | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | The layout area. |
| string_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | The string format. |

**Returns**

| Type | Description |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Size in pixels of measured text string |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_193}


```
 multiply_transform(matrix) 
```

Multiplies the [Matrix](/imaging/python-net/aspose.imaging/matrix/) that represents the local geometric transform of this [Graphics](/imaging/python-net/aspose.imaging/graphics/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/) by prepending the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | The [Matrix](/imaging/python-net/aspose.imaging/matrix/) by which to multiply the geometric transform. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_194}


```
 multiply_transform(matrix, order) 
```

Multiplies the [Matrix](/imaging/python-net/aspose.imaging/matrix/) that represents the local geometric transform of this [Graphics](/imaging/python-net/aspose.imaging/graphics/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/) in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | The [Matrix](/imaging/python-net/aspose.imaging/matrix/) by which to multiply the geometric transform. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | A [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) that specifies in which order to multiply the two matrices. |

### Method: rotate_transform(angle) {#rotate_transform_angle_195}


```
 rotate_transform(angle) 
```

Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The angle of rotation. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_196}


```
 rotate_transform(angle, order) 
```

Rotates the local geometric transform by the specified amount in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The angle of rotation. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | A [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) that specifies whether to append or prepend the rotation matrix. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_197}


```
 scale_transform(sx, sy) 
```

Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| sx | float | The amount by which to scale the transform in the x-axis direction. |
| sy | float | The amount by which to scale the transform in the y-axis direction. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_198}


```
 scale_transform(sx, sy, order) 
```

Scales the local geometric transform by the specified amounts in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| sx | float | The amount by which to scale the transform in the x-axis direction. |
| sy | float | The amount by which to scale the transform in the y-axis direction. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | A [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) that specifies whether to append or prepend the scaling matrix. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_199}


```
 translate_transform(dx, dy) 
```

Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_200}


```
 translate_transform(dx, dy, order) 
```

Translates the local geometric transform by the specified dimensions in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | The order (prepend or append) in which to apply the translation. |

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

#Creates an instance of file stream
with open(r"C:\temp\output.png", "w+b") as stream:
	#Create an instance of PngOptions and set its various properties
	pngOptions = PngOptions()
	#Set the Source for PngOptions
	pngOptions.source = StreamSource(stream)
	#Create an instance of Image 
	with Image.create(pngOptions, 500, 500) as image:
		#Create and initialize an instance of Graphics class
		graphics = Graphics(image)
		#Clear Graphics surface
		graphics.clear(Color.wheat);
		#Draw an Arc by specifying the Pen object having Black color, 
		#a Rectangle surrounding the Arc, Start Angle and Sweep Angle
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#Draw a Bezier by specifying the Pen object having Blue color and co-ordinate Points.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#Draw a Curve by specifying the Pen object having Green color and an array of Points
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#Draw an Ellipse using the Pen object and a surrounding Rectangle
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#Draw a Line 
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#Draw a Pie segment
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#Draw a Polygon by specifying the Pen object having Red color and an array of Points
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#Draw a Rectangle
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#Create a SolidBrush object and set its various properties
		brush = SolidBrush()
		brush.color = Color.purple
		#Draw a String using the SolidBrush object and Font, at specific Point
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# save all changes.
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


# Create an instance of a file stream
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# Create an instance of TiffOptions and set its various properties
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Set the source for the instance of ImageOptions
	tiffOptions.source = StreamSource(stream)
	# Create an instance of Image
	with Image.create(tiffOptions, 500, 500) as image:
		# Create and initialize an instance of Graphics class
		graphics = Graphics(image)
		# Clear Graphics surface
		graphics.clear(Color.wheat);
		# Create an instance of GraphicsPath class
		graphics_path = GraphicsPath()
		# Create an instance of Figure class
		figure = Figure()
		# Add Shapes to Figure object
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# Add Figure object to GraphicsPath
		graphics_path.add_figure(figure)
		# Draw path with Pen object of color Black
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# save all changes.
		image.save()


```

### This example shows the creation and usage Pen objects. The example creates a new Image and draw rectangles on the Image surface. {#example_14}
``` python

from aspose.imaging import Image, Graphics, Color, Pen, Rectangle, Point, Size
from aspose.imaging.brushes import HatchBrush
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

# Create an instance of BmpOptions and set its various properties
bmpOptions = BmpOptions()
bmpOptions.bits_per_pixel = 24
# Create an instance of FileCreateSource and assign it as Source for the instance of BmpOptions
# Second Boolean parameter determines if the file to be created IsTemporal or not
bmpOptions.source = FileCreateSource(r"C:\temp\sample.bmp", False)
# Create an instance of Image at specified Path
with Image.create(bmpOptions, 500, 500) as image:
	# Create an instance of Graphics and initialize it with Image object
	graphics = Graphics(image)
	# Clear the Graphics surface with White Color
	graphics.clear(Color.white)
	#Create an instance of Pen with color Red and width 5
	pen = Pen(Color.red, 5.0);
	# Create an instance of HatchBrush and set its properties
	brush = HatchBrush()
	brush.background_color = Color.wheat;
	brush.foreground_color = Color.red;
	# Create an instance of Pen
	# initialize it with HatchBrush object and width
	brusedpen = Pen(brush, 5.0)
	# Draw Rectangles by specifying Pen object
	graphics.draw_rectangles(pen, [
		Rectangle(Point(210, 210), Size(100, 100)),
		Rectangle(Point(110, 110), Size(100, 100)),
		Rectangle(Point(310, 310), Size(100, 100)) ])

	# Draw Rectangles by specifying Pen object
	graphics.draw_rectangles(brusedpen, [
		Rectangle(Point(310, 110), Size(100, 100)),
		Rectangle(Point(110, 310), Size(100, 100)) ])

	# save all changes.
	image.save()


```

### The following example shows how to compose an animated GIF image from individual GIF blocks. {#example_95}
``` python
from aspose.imaging.fileformats.gif.blocks import GifFrameBlock
from aspose.imaging.fileformats.gif import GifImage 
from aspose.imaging.brushes import SolidBrush
from aspose.imaging import Graphics, Color

# Create a GIF image 100 x 100 px.
# The first block is fully black by default.
with GifFrameBlock(100, 100) as firstBlock:
	with GifImage(firstBlock) as gifImage:
		# The first circle is red
		brush1 = SolidBrush(Color.red)

		# The second circle is black
		brush2 = SolidBrush(Color.black)

		# Gradually increase the angle of the red arc shape.
		for angle in range(10, 361, 10):
			block = GifFrameBlock(100, 100)
			gr = Graphics(block)
			gr.fill_pie(brush1, block.bounds, 0, angle)
			gifImage.add_block(block)
		
		# Gradually increase the angle of the black arc and wipe out the red arc.
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
# Create a PNG image of 100x100 px.
with PngImage(100, 100) as png_image:
	# Do some image processing, e.g. fill the entire image in red.
	graphics = Graphics(png_image)
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, png_image.bounds)
	# Save to a file.
	png_image.save(join(dir_, "output.png"))


```

