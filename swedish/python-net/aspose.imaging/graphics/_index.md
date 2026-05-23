---
title: "Graphics-klass"
type: docs
weight: 5030
url: /sv/python-net/aspose.imaging/graphics/
---

**Summary:** Represents the graphics according to the graphics engine used in the current assembly.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Graphics

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Graphics(source_image)](#Graphics_source_image_1) | Initierar en ny instans av klassen [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| clip | [Region](/imaging/python-net/aspose.imaging/region/) | r/w | Hämtar eller anger klippområdet. |
| compositing_quality | [CompositingQuality](/imaging/python-net/aspose.imaging/compositingquality/) | r/w | Hämtar eller anger sammansättningskvaliteten. |
| dpi_x | float | r | Hämtar den horisontella upplösningen för detta `aspose.imaging.Graphics`. |
| dpi_y | float | r | Hämtar den vertikala upplösningen för detta `aspose.imaging.Graphics`. |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | r | Hämtar bilden. |
| interpolation_mode | [InterpolationMode](/imaging/python-net/aspose.imaging/interpolationmode/) | r/w | Hämtar eller anger interpolationsläget. |
| is_in_begin_update_call | bool | r | Hämtar ett värde som indikerar om grafik är i BeginUpdate-anropstillstånd. |
| page_scale | float | r/w | Hämtar eller anger skalningen mellan världsenheter och sidoyenheter för detta `aspose.imaging.Graphics`. |
| page_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | r/w | Hämtar eller anger måttenheten som används för sidkoordinater i detta `aspose.imaging.Graphics`. |
| paintable_image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | r/w | Hämtar eller anger bildalternativ som används för att skapa målbara vektor‑bilder att rita. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Hämtar eller anger utjämningsläget. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Hämtar eller anger tips för textrendering. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Hämtar eller anger en kopia av den geometriska världstransformationen för detta [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| begin_update() | Startar cachning av följande grafikoperationer. Grafik‑effekterna som tillämpas därefter kommer inte att appliceras omedelbart; istället kommer EndUpdate att orsaka att alla effekter tillämpas på en gång. |
| [clear(color)](#clear_color_1) | Rensar grafikytan med den angivna färgen. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_2) | Ritar en båge som representerar en del av en ellips specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_3) | Ritar en båge som representerar en del av en ellips specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4) | Ritar en båge som representerar en del av en ellips specificerad av ett koordinatpar, en bredd och en höjd. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5) | Ritar en båge som representerar en del av en ellips specificerad av ett koordinatpar, en bredd och en höjd. |
| [draw_arc_in_rect(pen, rect, start_angle, sweep_angle)](#draw_arc_in_rect_pen_rect_start_angle_sweep_angle_6) | Ritar en båge som representerar en del av en ellips specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur. |
| [draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle)](#draw_arc_in_rect_f_pen_rect_start_angle_sweep_angle_7) | Ritar en båge som representerar en del av en ellips specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur. |
| [draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_xy_pen_x_y_width_height_start_angle_sweep_angle_8) | Ritar en båge som representerar en del av en ellips specificerad av ett koordinatpar, en bredd och en höjd. |
| [draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_xyf_pen_x_y_width_height_start_angle_sweep_angle_9) | Ritar en båge som representerar en del av en ellips specificerad av ett koordinatpar, en bredd och en höjd. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_10) | Ritar en Bézier‑spline definierad av fyra [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_11) | Ritar en Bézier‑spline definierad av fyra [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. |
| [draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4)](#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_12) | Ritar en Bézier‑spline definierad av fyra ordnade koordinatpar som representerar punkter. |
| [draw_bezier_by_points(pen, pt1, pt2, pt3, pt4)](#draw_bezier_by_points_pen_pt1_pt2_pt3_pt4_13) | Ritar en Bézier‑spline definierad av fyra [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. |
| [draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4)](#draw_bezier_by_points_f_pen_pt1_pt2_pt3_pt4_14) | Ritar en Bézier‑spline definierad av fyra [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_15) | Ritar en serie av Bézier‑splines från en matris av [Point](/imaging/python-net/aspose.imaging/point/) strukturer. |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_16) | Ritar en serie av Bézier‑splines från en matris av [Point](/imaging/python-net/aspose.imaging/point/) strukturer. |
| [draw_beziers_by_pt_array(pen, points)](#draw_beziers_by_pt_array_pen_points_17) | Ritar en serie av Bézier‑splines från en matris av [Point](/imaging/python-net/aspose.imaging/point/) strukturer. |
| [draw_beziers_by_pt_array_f(pen, points)](#draw_beziers_by_pt_array_f_pen_points_18) | Ritar en serie av Bézier‑splines från en matris av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_19) | Ritar en sluten cardinal‑spline definierad av en matris av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. Denna metod använder en standardspänning på 0.5 och [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fyllningsläge. |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_20) | Ritar en sluten cardinal‑spline definierad av en matris av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. Denna metod använder en standardspänning på 0.5 och [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fyllningsläge. |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_21) | Ritar en sluten cardinal‑spline definierad av en matris av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med en specificerad spänning. Denna metod använder ett standard [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fyllningsläge. |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_22) | Ritar en sluten cardinal‑spline definierad av en matris av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med en specificerad spänning. Denna metod använder ett standard [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fyllningsläge. |
| [draw_closed_curve_by_points(pen, points)](#draw_closed_curve_by_points_pen_points_23) | Ritar en sluten cardinal‑spline definierad av en matris av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. Denna metod använder en standardspänning på 0.5 och [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fyllningsläge. |
| [draw_closed_curve_by_points_f(pen, points)](#draw_closed_curve_by_points_f_pen_points_24) | Ritar en sluten cardinal‑spline definierad av en matris av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. Denna metod använder en standardspänning på 0.5 och [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fyllningsläge. |
| [draw_closed_curve_by_points_f_tension(pen, points, tension)](#draw_closed_curve_by_points_f_tension_pen_points_tension_25) | Ritar en sluten cardinal‑spline definierad av en matris av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med en specificerad spänning. Denna metod använder ett standard [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fyllningsläge. |
| [draw_closed_curve_by_points_tension(pen, points, tension)](#draw_closed_curve_by_points_tension_pen_points_tension_26) | Ritar en sluten cardinal‑spline definierad av en matris av [Point](/imaging/python-net/aspose.imaging/point/) strukturer med en specificerad spänning. Denna metod använder ett standard [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fyllningsläge. |
| [draw_curve(pen, points)](#draw_curve_pen_points_27) | Ritar en cardinal‑spline genom en specificerad matris av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. Denna metod använder en standardspänning på 0.5. |
| [draw_curve(pen, points)](#draw_curve_pen_points_28) | Ritar en cardinal‑spline genom en specificerad matris av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. Denna metod använder en standardspänning på 0.5. |
| [draw_curve(pen, points, offset, number_of_segments)](#draw_curve_pen_points_offset_number_of_segments_29) | Ritar en kardinal spline genom en specificerad array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. Ritningen börjar förskjuten från början av arrayen.<br/>            Denna metod använder en standardspänning på 0,5. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_30) | Ritar en kardinal spline genom en specificerad array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med en specificerad spänning. Ritningen börjar förskjuten från början av arrayen. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_31) | Ritar en kardinal spline genom en specificerad array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med en specificerad spänning. Ritningen börjar förskjuten från början av arrayen. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_32) | Ritar en kardinal spline genom en specificerad array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med en specificerad spänning. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_33) | Ritar en kardinal spline genom en specificerad array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med en specificerad spänning. |
| [draw_curve_by_point_fs(pen, points)](#draw_curve_by_point_fs_pen_points_34) | Ritar en kardinal spline genom en specificerad array av [Point](/imaging/python-net/aspose.imaging/point/) strukturer. |
| [draw_curve_by_point_fs_tension(pen, points, tension)](#draw_curve_by_point_fs_tension_pen_points_tension_35) | Ritar en kardinal spline genom en specificerad array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med en specificerad spänning. |
| [draw_curve_by_points(pen, points)](#draw_curve_by_points_pen_points_36) | Ritar en cardinal‑spline genom en specificerad matris av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. Denna metod använder en standardspänning på 0.5. |
| [draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension)](#draw_curve_by_points_f_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_37) | Ritar en kardinal spline genom en specificerad array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med en specificerad spänning. Ritningen börjar förskjuten från början av arrayen. |
| [draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension)](#draw_curve_by_points_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_38) | Ritar en kardinal spline genom en specificerad array av [Point](/imaging/python-net/aspose.imaging/point/) strukturer med en specificerad spänning. |
| [draw_curve_by_points_tension(pen, points, tension)](#draw_curve_by_points_tension_pen_points_tension_39) | Ritar en kardinal spline genom en specificerad array av [Point](/imaging/python-net/aspose.imaging/point/) strukturer med en specificerad spänning. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_40) | Ritar en ellips definierad av en avgränsande [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_41) | Ritar en ellips definierad av en avgränsande [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_42) | Ritar en ellips definierad av en avgränsande rektangel som anges av ett koordinatpar, en höjd och en bredd. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_43) | Ritar en ellips definierad av en avgränsande rektangel som anges av ett koordinatpar, en höjd och en bredd. |
| [draw_ellipse_by_xy(pen, x, y, width, height)](#draw_ellipse_by_xy_pen_x_y_width_height_44) | Ritar en ellips definierad av en avgränsande rektangel som anges av ett koordinatpar, en höjd och en bredd. |
| [draw_ellipse_by_xyf(pen, x, y, width, height)](#draw_ellipse_by_xyf_pen_x_y_width_height_45) | Ritar en ellips definierad av en avgränsande rektangel som anges av ett koordinatpar, en höjd och en bredd. |
| [draw_ellipse_f(pen, rect)](#draw_ellipse_f_pen_rect_46) | Ritar en ellips definierad av en avgränsande [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_47) | Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_48) | Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_49) | Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_50) | Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_51) | Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_52) | Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_53) | Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_54) | Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken. |
| [draw_image(source_image, point)](#draw_image_source_image_point_55) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), med dess ursprungliga fysiska storlek, på den specificerade platsen. |
| [draw_image(source_image, point)](#draw_image_source_image_point_56) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), med dess ursprungliga fysiska storlek, på den specificerade platsen. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_57) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_58) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_59) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_60) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_61) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_62) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_63) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_64) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_65) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_66) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_67) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), med dess ursprungliga fysiska storlek, på den specificerade platsen. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_68) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), med dess ursprungliga fysiska storlek, på den specificerade platsen. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_69) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_70) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken. |
| [draw_image_at_point(source_image, point)](#draw_image_at_point_source_image_point_71) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), med dess ursprungliga fysiska storlek, på den specificerade platsen. |
| [draw_image_at_point_f(source_image, point)](#draw_image_at_point_f_source_image_point_72) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), med dess ursprungliga fysiska storlek, på den specificerade platsen. |
| [draw_image_at_xy(source_image, x, y)](#draw_image_at_xy_source_image_x_y_73) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), med dess ursprungliga fysiska storlek, på den specificerade platsen. |
| [draw_image_at_xyf(source_image, x, y)](#draw_image_at_xyf_source_image_x_y_74) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), med dess ursprungliga fysiska storlek, på den specificerade platsen. |
| [draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit)](#draw_image_dest_point_f_src_rect_f_with_unit_image_dest_points_src_rect_src_unit_75) | Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken. |
| [draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_dest_point_f_src_rect_f_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_76) | Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken. |
| [draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect)](#draw_image_dest_points_f_src_rect_f_image_dest_points_src_rect_77) | Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken. |
| [draw_image_dest_points_src_rect(image, dest_points, src_rect)](#draw_image_dest_points_src_rect_image_dest_points_src_rect_78) | Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken. |
| [draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit)](#draw_image_dest_points_src_rect_with_unit_image_dest_points_src_rect_src_unit_79) | Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken. |
| [draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_dest_points_src_rect_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_80) | Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken. |
| [draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_dest_rect_f_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_81) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken. |
| [draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_dest_rect_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_82) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken. |
| [draw_image_in_rect(source_image, x, y, width, height)](#draw_image_in_rect_source_image_x_y_width_height_83) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken. |
| [draw_image_in_rect_f(source_image, x, y, width, height)](#draw_image_in_rect_f_source_image_x_y_width_height_84) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken. |
| [draw_image_in_rectangle(source_image, rect)](#draw_image_in_rectangle_source_image_rect_85) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken. |
| [draw_image_points(image, dest_points)](#draw_image_points_image_dest_points_86) | Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken. |
| [draw_image_points_f(image, dest_points)](#draw_image_points_f_image_dest_points_87) | Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken. |
| [draw_image_rectangle_f(source_image, rect)](#draw_image_rectangle_f_source_image_rect_88) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken. |
| [draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_src_dest_rects_f_with_unit_source_image_rect_source_rect_destination_graphics_unit_89) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken. |
| [draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_src_dest_rects_with_unit_source_image_rect_source_rect_destination_graphics_unit_90) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken. |
| [draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_src_dst_rect_f_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_91) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken. |
| [draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_src_dst_rects_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_92) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken. |
| [draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit)](#draw_image_to_rect_f_with_unit_source_image_rect_destination_graphics_unit_93) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken. |
| [draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit)](#draw_image_to_rect_with_unit_source_image_rect_destination_graphics_unit_94) | Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken. |
| [draw_image_unscaled(source_image, point)](#draw_image_unscaled_source_image_point_95) | Ritar en specificerad bild med dess ursprungliga fysiska storlek på en specificerad plats. |
| [draw_image_unscaled(source_image, rect)](#draw_image_unscaled_source_image_rect_96) | Ritar en specificerad bild med dess ursprungliga fysiska storlek på en specificerad plats. |
| [draw_image_unscaled(source_image, x, y)](#draw_image_unscaled_source_image_x_y_97) | Ritar den specificerade bilden med dess ursprungliga fysiska storlek på den plats som anges av ett koordinatpar. |
| [draw_image_unscaled(source_image, x, y, width, height)](#draw_image_unscaled_source_image_x_y_width_height_98) | Ritar en specificerad bild med dess ursprungliga fysiska storlek på en specificerad plats. |
| [draw_image_unscaled_and_clipped(source_image, rect)](#draw_image_unscaled_and_clipped_source_image_rect_99) | Ritar den specificerade bilden utan skalning och beskär den, om nödvändigt, för att passa i den specificerade rektangeln. |
| [draw_image_unscaled_in_rectangle(source_image, rect)](#draw_image_unscaled_in_rectangle_source_image_rect_100) | Ritar en specificerad bild med dess ursprungliga fysiska storlek på en specificerad plats. |
| [draw_image_unscaled_to_point(source_image, point)](#draw_image_unscaled_to_point_source_image_point_101) | Ritar en specificerad bild med dess ursprungliga fysiska storlek på en specificerad plats. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_102) | Ritar en linje som förbinder två [Point](/imaging/python-net/aspose.imaging/point/) strukturer. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_103) | Ritar en linje som förbinder två [Point](/imaging/python-net/aspose.imaging/point/) strukturer. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_104) | Ritar en linje som förbinder de två punkterna som specificeras av koordinatparen. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_105) | Ritar en linje som förbinder de två punkterna som specificeras av koordinatparen. |
| [draw_line_by_xy(pen, x1, y1, x2, y2)](#draw_line_by_xy_pen_x1_y1_x2_y2_106) | Ritar en linje som förbinder de två punkterna som specificeras av koordinatparen. |
| [draw_line_f_by_xy(pen, x1, y1, x2, y2)](#draw_line_f_by_xy_pen_x1_y1_x2_y2_107) | Ritar en linje som förbinder de två punkterna som specificeras av koordinatparen. |
| [draw_line_point_f(pen, point1, point2)](#draw_line_point_f_pen_point1_point2_108) | Ritar en linje som förbinder två [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. |
| [draw_lines(pen, points)](#draw_lines_pen_points_109) | Ritar en serie linjesegment som förbinder en array av [Point](/imaging/python-net/aspose.imaging/point/) strukturer. |
| [draw_lines(pen, points)](#draw_lines_pen_points_110) | Ritar en serie linjesegment som förbinder en array av [Point](/imaging/python-net/aspose.imaging/point/) strukturer. |
| [draw_lines_f(pen, points)](#draw_lines_f_pen_points_111) | Ritar en serie linjesegment som förbinder en array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. |
| [draw_path(pen, path)](#draw_path_pen_path_112) | Ritar en [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_113) | Ritar en pajform definierad av en ellips specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur och två radiala linjer. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_114) | Ritar en pajform definierad av en ellips specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur och två radiala linjer. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_115) | Ritar en pajform definierad av en ellips specificerad av ett koordinatpar, en bredd, en höjd och två radiala linjer. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_116) | Ritar en pajform definierad av en ellips specificerad av ett koordinatpar, en bredd, en höjd och två radiala linjer. |
| [draw_pie_in_rect(pen, rect, start_angle, sweep_angle)](#draw_pie_in_rect_pen_rect_start_angle_sweep_angle_117) | Ritar en pajform definierad av en ellips specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur och två radiala linjer. |
| [draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle)](#draw_pie_in_rect_f_pen_rect_start_angle_sweep_angle_118) | Ritar en pajform definierad av en ellips specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur och två radiala linjer. |
| [draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_xy_pen_x_y_width_height_start_angle_sweep_angle_119) | Ritar en pajform definierad av en ellips specificerad av ett koordinatpar, en bredd, en höjd och två radiala linjer. |
| [draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_xyf_pen_x_y_width_height_start_angle_sweep_angle_120) | Ritar en pajform definierad av en ellips specificerad av ett koordinatpar, en bredd, en höjd och två radiala linjer. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_121) | Ritar en polygon definierad av en array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_122) | Ritar en polygon definierad av en array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. |
| [draw_polygon_f(pen, points)](#draw_polygon_f_pen_points_123) | Ritar en polygon definierad av en array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. |
| [draw_rect(pen, x, y, width, height)](#draw_rect_pen_x_y_width_height_124) | Ritar en rektangel specificerad av ett koordinatpar, en bredd och en höjd. |
| [draw_rect_f(pen, x, y, width, height)](#draw_rect_f_pen_x_y_width_height_125) | Ritar en rektangel specificerad av ett koordinatpar, en bredd och en höjd. |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_126) | Ritar en rektangel specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur. |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_127) | Ritar en rektangel specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_128) | Ritar en rektangel specificerad av ett koordinatpar, en bredd och en höjd. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_129) | Ritar en rektangel specificerad av ett koordinatpar, en bredd och en höjd. |
| [draw_rectangle_f(pen, rect)](#draw_rectangle_f_pen_rect_130) | Ritar en rektangel specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur. |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_131) | Ritar en serie rektanglar specificerade av [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) strukturer. |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_132) | Ritar en serie rektanglar specificerade av [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) strukturer. |
| [draw_rectangles_f(pen, rects)](#draw_rectangles_f_pen_rects_133) | Ritar en serie rektanglar specificerade av [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) strukturer. |
| [draw_string(s, font, brush, layout_rectangle)](#draw_string_s_font_brush_layout_rectangle_134) | Ritar den angivna textsträngen i den angivna rektangeln med de angivna [Brush](/imaging/python-net/aspose.imaging/brush/) och [Font](/imaging/python-net/aspose.imaging/font/) objekten. |
| [draw_string(s, font, brush, layout_rectangle, format)](#draw_string_s_font_brush_layout_rectangle_format_135) | Ritar den angivna textsträngen i den angivna rektangeln med de angivna [Brush](/imaging/python-net/aspose.imaging/brush/) och [Font](/imaging/python-net/aspose.imaging/font/) objekten med formateringsattributen från den angivna [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [draw_string(s, font, brush, point)](#draw_string_s_font_brush_point_136) | Ritar den angivna textsträngen på den angivna platsen med de angivna [Brush](/imaging/python-net/aspose.imaging/brush/) och [Font](/imaging/python-net/aspose.imaging/font/) objekten. |
| [draw_string(s, font, brush, point, format)](#draw_string_s_font_brush_point_format_137) | Ritar den angivna textsträngen på den angivna platsen med de angivna [Brush](/imaging/python-net/aspose.imaging/brush/) och [Font](/imaging/python-net/aspose.imaging/font/) objekten med formateringsattributen från den angivna [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [draw_string(s, font, brush, x, y)](#draw_string_s_font_brush_x_y_138) | Ritar den angivna textsträngen på den angivna platsen med de angivna [Brush](/imaging/python-net/aspose.imaging/brush/) och [Font](/imaging/python-net/aspose.imaging/font/) objekten. |
| [draw_string(s, font, brush, x, y, format)](#draw_string_s_font_brush_x_y_format_139) | Ritar den angivna textsträngen på den angivna platsen med de angivna [Brush](/imaging/python-net/aspose.imaging/brush/) och [Font](/imaging/python-net/aspose.imaging/font/) objekten med formateringsattributen från den angivna [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [draw_string_at_point_f(s, font, brush, point)](#draw_string_at_point_f_s_font_brush_point_140) | Ritar den angivna textsträngen på den angivna platsen med de angivna [Brush](/imaging/python-net/aspose.imaging/brush/) och [Font](/imaging/python-net/aspose.imaging/font/) objekten. |
| [draw_string_at_point_f_format(s, font, brush, point, format)](#draw_string_at_point_f_format_s_font_brush_point_format_141) | Ritar den angivna textsträngen på den angivna platsen med de angivna [Brush](/imaging/python-net/aspose.imaging/brush/) och [Font](/imaging/python-net/aspose.imaging/font/) objekten med formateringsattributen från den angivna [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [draw_string_at_xy(s, font, brush, x, y)](#draw_string_at_xy_s_font_brush_x_y_142) | Ritar den angivna textsträngen på den angivna platsen med de angivna [Brush](/imaging/python-net/aspose.imaging/brush/) och [Font](/imaging/python-net/aspose.imaging/font/) objekten. |
| [draw_string_in_rect(s, font, brush, layout_rectangle)](#draw_string_in_rect_s_font_brush_layout_rectangle_143) | Ritar den angivna textsträngen i den angivna rektangeln med de angivna [Brush](/imaging/python-net/aspose.imaging/brush/) och [Font](/imaging/python-net/aspose.imaging/font/) objekten. |
| [draw_string_in_rect_f(s, font, brush, layout_rectangle, format)](#draw_string_in_rect_f_s_font_brush_layout_rectangle_format_144) | Ritar den angivna textsträngen i den angivna rektangeln med de angivna [Brush](/imaging/python-net/aspose.imaging/brush/) och [Font](/imaging/python-net/aspose.imaging/font/) objekten med formateringsattributen från den angivna [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| end_update() | Avslutar cachning av grafikoperationerna som startades efter att BeginUpdate anropades. De föregående grafikoperationerna kommer att tillämpas på en gång när denna metod anropas. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_145) | Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. Denna metod använder en standardspänning på 0,5 och [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fyllningsläge. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_146) | Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. Denna metod använder en standardspänning på 0,5 och [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fyllningsläge. |
| [fill_closed_curve(brush, points, fill_mode)](#fill_closed_curve_brush_points_fill_mode_147) | Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med det angivna fyllningsläget. Denna metod använder en standardspänning på 0,5. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_148) | Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med det angivna fyllningsläget. Denna metod använder en standardspänning på 0,5. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_149) | Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med det angivna fyllningsläget och spänning. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_150) | Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med det angivna fyllningsläget och spänning. |
| [fill_closed_curve_by_point(brush, points)](#fill_closed_curve_by_point_brush_points_151) | Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. Denna metod använder en standardspänning på 0,5 och [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fyllningsläge. |
| [fill_closed_curve_by_point_f(brush, points)](#fill_closed_curve_by_point_f_brush_points_152) | Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. Denna metod använder en standardspänning på 0,5 och [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fyllningsläge. |
| fill_closed_curve_by_point_f_fill_mode(brush, points, fillmode) |  |
| [fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension)](#fill_closed_curve_by_point_f_fill_mode_tension_brush_points_fillmode_tension_153) | Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med det angivna fyllningsläget och spänning. |
| [fill_closed_curve_by_point_fill_mode(brush, points, fillmode)](#fill_closed_curve_by_point_fill_mode_brush_points_fillmode_154) | Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [Point](/imaging/python-net/aspose.imaging/point/) strukturer med det angivna fyllningsläget. Denna metod använder en standardspänning på 0,5. |
| [fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension)](#fill_closed_curve_by_point_fill_mode_tension_brush_points_fillmode_tension_155) | Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [Point](/imaging/python-net/aspose.imaging/point/) strukturer med det angivna fyllningsläget och spänning. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_156) | Fyller insidan av en ellips definierad av en omslutande rektangel specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_157) | Fyller insidan av en ellips definierad av en omslutande rektangel specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_158) | Fyller insidan av en ellips definierad av en omslutande rektangel specificerad av ett par koordinater, en bredd och en höjd. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_159) | Fyller insidan av en ellips definierad av en omslutande rektangel specificerad av ett par koordinater, en bredd och en höjd. |
| [fill_ellipse_at_xywh(brush, x, y, width, height)](#fill_ellipse_at_xywh_brush_x_y_width_height_160) | Fyller insidan av en ellips definierad av en omslutande rektangel specificerad av ett par koordinater, en bredd och en höjd. |
| [fill_ellipse_at_xywhf(brush, x, y, width, height)](#fill_ellipse_at_xywhf_brush_x_y_width_height_161) | Fyller insidan av en ellips definierad av en omslutande rektangel specificerad av ett par koordinater, en bredd och en höjd. |
| [fill_ellipse_in_rect(brush, rect)](#fill_ellipse_in_rect_brush_rect_162) | Fyller insidan av en ellips definierad av en omslutande rektangel specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur. |
| [fill_ellipse_in_rect_f(brush, rect)](#fill_ellipse_in_rect_f_brush_rect_163) | Fyller insidan av en ellips definierad av en omslutande rektangel specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur. |
| [fill_path(brush, path)](#fill_path_brush_path_164) | Fyller insidan av en [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_165) | Fyller insidan av ett pajsegment definierat av en ellips specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur och två radiala linjer. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_166) | Fyller insidan av ett pajsegment definierat av en ellips specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur och två radiala linjer. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_167) | Fyller insidan av ett pajsegment definierat av en ellips specificerad av ett par koordinater, en bredd, en höjd och två radiala linjer. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_168) | Fyller insidan av ett pajsegment definierat av en ellips specificerad av ett par koordinater, en bredd, en höjd och två radiala linjer. |
| [fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_at_xy_brush_x_y_width_height_start_angle_sweep_angle_169) | Fyller insidan av ett pajsegment definierat av en ellips specificerad av ett par koordinater, en bredd, en höjd och två radiala linjer. |
| [fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_at_xyf_brush_x_y_width_height_start_angle_sweep_angle_170) | Fyller insidan av ett pajsegment definierat av en ellips specificerad av ett par koordinater, en bredd, en höjd och två radiala linjer. |
| [fill_pie_in_rect(brush, rect, start_angle, sweep_angle)](#fill_pie_in_rect_brush_rect_start_angle_sweep_angle_171) | Fyller insidan av ett pajsegment definierat av en ellips specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur och två radiala linjer. |
| [fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle)](#fill_pie_in_rect_f_brush_rect_start_angle_sweep_angle_172) | Fyller insidan av ett pajsegment definierat av en ellips specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur och två radiala linjer. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_173) | Fyller insidan av en polygon definierad av en array av punkter specificerade av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer och [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_174) | Fyller insidan av en polygon definierad av en array av punkter specificerade av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer och [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_175) | Fyller insidan av en polygon definierad av en array av punkter specificerade av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med det angivna fyllningsläget. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_176) | Fyller insidan av en polygon definierad av en array av punkter specificerade av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med det angivna fyllningsläget. |
| [fill_polygon_by_point(brush, points)](#fill_polygon_by_point_brush_points_177) | Fyller insidan av en polygon definierad av en array av punkter specificerade av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer och [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [fill_polygon_by_point_f(brush, points)](#fill_polygon_by_point_f_brush_points_178) | Fyller insidan av en polygon definierad av en array av punkter specificerade av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer och [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [fill_polygon_by_point_f_fill_mode(brush, points, fill_mode)](#fill_polygon_by_point_f_fill_mode_brush_points_fill_mode_179) | Fyller insidan av en polygon definierad av en array av punkter specificerade av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med det angivna fyllningsläget. |
| [fill_polygon_by_point_fill_mode(brush, points, fill_mode)](#fill_polygon_by_point_fill_mode_brush_points_fill_mode_180) | Fyller insidan av en polygon definierad av en array av punkter specificerade av [Point](/imaging/python-net/aspose.imaging/point/) strukturer med det angivna fyllningsläget. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_181) | Fyller insidan av en rektangel specificerad av en [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_182) | Fyller insidan av en rektangel specificerad av en [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_183) | Fyller insidan av en rektangel specificerad av ett par koordinater, en bredd och en höjd. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_184) | Fyller insidan av en rektangel specificerad av ett par koordinater, en bredd och en höjd. |
| [fill_rectangle_f(brush, rect)](#fill_rectangle_f_brush_rect_185) | Fyller insidan av en rektangel specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur. |
| [fill_rectangle_f_with_brush(brush, x, y, width, height)](#fill_rectangle_f_with_brush_brush_x_y_width_height_186) | Fyller insidan av en rektangel specificerad av ett par koordinater, en bredd och en höjd. |
| [fill_rectangle_with_brush(brush, x, y, width, height)](#fill_rectangle_with_brush_brush_x_y_width_height_187) | Fyller insidan av en rektangel specificerad av ett par koordinater, en bredd och en höjd. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_188) | Fyller insidan av en serie rektanglar specificerade av [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) strukturer. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_189) | Fyller insidan av en serie rektanglar specificerade av [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) strukturer. |
| [fill_rectangles_f(brush, rects)](#fill_rectangles_f_brush_rects_190) | Fyller insidan av en serie rektanglar specificerade av [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) strukturer. |
| [fill_region(brush, region)](#fill_region_brush_region_191) | Fyller i insidan av en [Region](/imaging/python-net/aspose.imaging/region/). |
| [measure_string(text, font, layout_area, string_format)](#measure_string_text_font_layout_area_string_format_192) | Mäter den angivna textsträngen med angivna parametrar |
| [multiply_transform(matrix)](#multiply_transform_matrix_193) | Multiplicerar [Matrix](/imaging/python-net/aspose.imaging/matrix/) som representerar den lokala geometriska transformen för denna [Graphics](/imaging/python-net/aspose.imaging/graphics/) med den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/) genom att föregå den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_194) | Multiplicerar [Matrix](/imaging/python-net/aspose.imaging/matrix/) som representerar den lokala geometriska transformen för denna [Graphics](/imaging/python-net/aspose.imaging/graphics/) med den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/) i den angivna ordningen. |
| reset_transform() | Återställer egenskapen [Graphics.transform](/imaging/python-net/aspose.imaging/graphics/) till identitet. |
| [rotate_transform(angle)](#rotate_transform_angle_195) | Rotera den lokala geometriska transformen med den angivna mängden. Denna metod lägger till rotationen i början av transformen. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_196) | Rotera den lokala geometriska transformen med den angivna mängden i den angivna ordningen. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_197) | Skalar den lokala geometriska transformen med de angivna värdena. Denna metod lägger till skalningsmatrisen i början av transformen. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_198) | Skalar den lokala geometriska transformen med de angivna värdena i den angivna ordningen. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_199) | Översätter den lokala geometriska transformen med de angivna dimensionerna. Denna metod lägger till översättningen i början av transformen. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_200) | Översätter den lokala geometriska transformen med de angivna dimensionerna i den angivna ordningen. |


### Constructor: Graphics(source_image) {#Graphics_source_image_1}


```
 Graphics(source_image) 
```

Initierar en ny instans av klassen [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Källbilden. |

### Method: clear(color) {#clear_color_1}


```
 clear(color) 
```

Rensar grafikytan med den angivna färgen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Färgen som används för att rensa grafikytan. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...

**[Example # 2](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_2}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Ritar en båge som representerar en del av en ellips specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för bågen. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som definierar ellipsens gränser. |
| start_angle | float | Vinkel i grader, mätt medurs från x-axeln till bågens startpunkt. |
| sweep_angle | float | Vinkel i grader, mätt medurs från parametern _startAngle_ till bågens slutpunkt. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_3}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Ritar en båge som representerar en del av en ellips specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för bågen. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som definierar ellipsens gränser. |
| start_angle | float | Vinkel i grader, mätt medurs från x-axeln till bågens startpunkt. |
| sweep_angle | float | Vinkel i grader, mätt medurs från parametern _startAngle_ till bågens slutpunkt. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Ritar en båge som representerar en del av en ellips specificerad av ett koordinatpar, en bredd och en höjd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för bågen. |
| x | float | X-koordinaten för rektangelns övre vänstra hörn som definierar ellipsen. |
| y | float | Y-koordinaten för rektangelns övre vänstra hörn som definierar ellipsen. |
| width | float | Bredden på rektangeln som definierar ellipsen. |
| height | float | Höjden på rektangeln som definierar ellipsen. |
| start_angle | float | Vinkel i grader, mätt medurs från x-axeln till bågens startpunkt. |
| sweep_angle | float | Vinkel i grader, mätt medurs från parametern _startAngle_ till bågens slutpunkt. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Ritar en båge som representerar en del av en ellips specificerad av ett koordinatpar, en bredd och en höjd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för bågen. |
| x | int | X-koordinaten för rektangelns övre vänstra hörn som definierar ellipsen. |
| y | int | Y-koordinaten för rektangelns övre vänstra hörn som definierar ellipsen. |
| width | int | Bredden på rektangeln som definierar ellipsen. |
| height | int | Höjden på rektangeln som definierar ellipsen. |
| start_angle | int | Vinkel i grader, mätt medurs från x-axeln till bågens startpunkt. |
| sweep_angle | int | Vinkel i grader, mätt medurs från parametern _startAngle_ till bågens slutpunkt. |

### Method: draw_arc_in_rect(pen, rect, start_angle, sweep_angle) {#draw_arc_in_rect_pen_rect_start_angle_sweep_angle_6}


```
 draw_arc_in_rect(pen, rect, start_angle, sweep_angle) 
```

Ritar en båge som representerar en del av en ellips specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för bågen. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som definierar ellipsens gränser. |
| start_angle | float | Vinkel i grader, mätt medurs från x-axeln till bågens startpunkt. |
| sweep_angle | float | Vinkel i grader, mätt medurs från parametern _startAngle_ till bågens slutpunkt. |

### Method: draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle) {#draw_arc_in_rect_f_pen_rect_start_angle_sweep_angle_7}


```
 draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle) 
```

Ritar en båge som representerar en del av en ellips specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för bågen. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som definierar ellipsens gränser. |
| start_angle | float | Vinkel i grader, mätt medurs från x-axeln till bågens startpunkt. |
| sweep_angle | float | Vinkel i grader, mätt medurs från parametern _startAngle_ till bågens slutpunkt. |

### Method: draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_xy_pen_x_y_width_height_start_angle_sweep_angle_8}


```
 draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle) 
```

Ritar en båge som representerar en del av en ellips specificerad av ett koordinatpar, en bredd och en höjd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för bågen. |
| x | int | X-koordinaten för rektangelns övre vänstra hörn som definierar ellipsen. |
| y | int | Y-koordinaten för rektangelns övre vänstra hörn som definierar ellipsen. |
| width | int | Bredden på rektangeln som definierar ellipsen. |
| height | int | Höjden på rektangeln som definierar ellipsen. |
| start_angle | int | Vinkel i grader, mätt medurs från x-axeln till bågens startpunkt. |
| sweep_angle | int | Vinkel i grader, mätt medurs från parametern _startAngle_ till bågens slutpunkt. |

### Method: draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_xyf_pen_x_y_width_height_start_angle_sweep_angle_9}


```
 draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle) 
```

Ritar en båge som representerar en del av en ellips specificerad av ett koordinatpar, en bredd och en höjd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för bågen. |
| x | float | X-koordinaten för rektangelns övre vänstra hörn som definierar ellipsen. |
| y | float | Y-koordinaten för rektangelns övre vänstra hörn som definierar ellipsen. |
| width | float | Bredden på rektangeln som definierar ellipsen. |
| height | float | Höjden på rektangeln som definierar ellipsen. |
| start_angle | float | Vinkel i grader, mätt medurs från x-axeln till bågens startpunkt. |
| sweep_angle | float | Vinkel i grader, mätt medurs från parametern _startAngle_ till bågens slutpunkt. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_10}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Ritar en Bézier‑spline definierad av fyra [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för kurvan. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som representerar kurvans startpunkt. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som representerar kurvans första kontrollpunkt. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som representerar kurvans andra kontrollpunkt. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som representerar kurvans slutpunkt. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_11}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Ritar en Bézier‑spline definierad av fyra [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för kurvan. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som representerar kurvans startpunkt. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som representerar kurvans första kontrollpunkt. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som representerar kurvans andra kontrollpunkt. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som representerar kurvans slutpunkt. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) {#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_12}


```
 draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) 
```

Ritar en Bézier‑spline definierad av fyra ordnade koordinatpar som representerar punkter.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för kurvan. |
| x1 | float | X-koordinaten för kurvans startpunkt. |
| y1 | float | Y-koordinaten för kurvans startpunkt. |
| x2 | float | X-koordinaten för kurvans första kontrollpunkt. |
| y2 | float | Y-koordinaten för den första kontrollpunkten på kurvan. |
| x3 | float | X-koordinaten för den andra kontrollpunkten på kurvan. |
| y3 | float | Y-koordinaten för den andra kontrollpunkten på kurvan. |
| x4 | float | X-koordinaten för slutpunkten på kurvan. |
| y4 | float | Y-koordinaten för slutpunkten på kurvan. |

### Method: draw_bezier_by_points(pen, pt1, pt2, pt3, pt4) {#draw_bezier_by_points_pen_pt1_pt2_pt3_pt4_13}


```
 draw_bezier_by_points(pen, pt1, pt2, pt3, pt4) 
```

Ritar en Bézier‑spline definierad av fyra [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för kurvan. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som representerar kurvans startpunkt. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som representerar kurvans första kontrollpunkt. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som representerar kurvans andra kontrollpunkt. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som representerar kurvans slutpunkt. |

### Method: draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4) {#draw_bezier_by_points_f_pen_pt1_pt2_pt3_pt4_14}


```
 draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4) 
```

Ritar en Bézier‑spline definierad av fyra [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för kurvan. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som representerar kurvans startpunkt. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som representerar kurvans första kontrollpunkt. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som representerar kurvans andra kontrollpunkt. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som representerar kurvans slutpunkt. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_15}


```
 draw_beziers(pen, points) 
```

Ritar en serie av Bézier‑splines från en matris av [Point](/imaging/python-net/aspose.imaging/point/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för kurvan. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av [Point](/imaging/python-net/aspose.imaging/point/) strukturer som representerar de punkter som bestämmer kurvan. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_16}


```
 draw_beziers(pen, points) 
```

Ritar en serie av Bézier‑splines från en matris av [Point](/imaging/python-net/aspose.imaging/point/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för kurvan. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av [Point](/imaging/python-net/aspose.imaging/point/) strukturer som representerar de punkter som bestämmer kurvan. |

### Method: draw_beziers_by_pt_array(pen, points) {#draw_beziers_by_pt_array_pen_points_17}


```
 draw_beziers_by_pt_array(pen, points) 
```

Ritar en serie av Bézier‑splines från en matris av [Point](/imaging/python-net/aspose.imaging/point/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för kurvan. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av [Point](/imaging/python-net/aspose.imaging/point/) strukturer som representerar de punkter som bestämmer kurvan. |

### Method: draw_beziers_by_pt_array_f(pen, points) {#draw_beziers_by_pt_array_f_pen_points_18}


```
 draw_beziers_by_pt_array_f(pen, points) 
```

Ritar en serie av Bézier‑splines från en matris av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för kurvan. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som representerar de punkter som bestämmer kurvan. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_19}


```
 draw_closed_curve(pen, points) 
```

Ritar en sluten cardinal‑spline definierad av en matris av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. Denna metod använder en standardspänning på 0.5 och [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fyllningsläge.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och höjden på kurvan. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som definierar splinen. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_20}


```
 draw_closed_curve(pen, points) 
```

Ritar en sluten cardinal‑spline definierad av en matris av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. Denna metod använder en standardspänning på 0.5 och [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fyllningsläge.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och höjden på kurvan. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som definierar splinen. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_21}


```
 draw_closed_curve(pen, points, tension) 
```

Ritar en sluten cardinal‑spline definierad av en matris av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med en specificerad spänning. Denna metod använder ett standard [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fyllningsläge.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och höjden på kurvan. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som definierar splinen. |
| spänning | float | Värde större än eller lika med 0.0F som specificerar spänningen i kurvan. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_22}


```
 draw_closed_curve(pen, points, tension) 
```

Ritar en sluten cardinal‑spline definierad av en matris av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med en specificerad spänning. Denna metod använder ett standard [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fyllningsläge.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och höjden på kurvan. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som definierar splinen. |
| spänning | float | Värde större än eller lika med 0.0F som specificerar spänningen i kurvan. |

### Method: draw_closed_curve_by_points(pen, points) {#draw_closed_curve_by_points_pen_points_23}


```
 draw_closed_curve_by_points(pen, points) 
```

Ritar en sluten cardinal‑spline definierad av en matris av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. Denna metod använder en standardspänning på 0.5 och [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fyllningsläge.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och höjden på kurvan. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som definierar splinen. |

### Method: draw_closed_curve_by_points_f(pen, points) {#draw_closed_curve_by_points_f_pen_points_24}


```
 draw_closed_curve_by_points_f(pen, points) 
```

Ritar en sluten cardinal‑spline definierad av en matris av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. Denna metod använder en standardspänning på 0.5 och [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fyllningsläge.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och höjden på kurvan. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som definierar splinen. |

### Method: draw_closed_curve_by_points_f_tension(pen, points, tension) {#draw_closed_curve_by_points_f_tension_pen_points_tension_25}


```
 draw_closed_curve_by_points_f_tension(pen, points, tension) 
```

Ritar en sluten cardinal‑spline definierad av en matris av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med en specificerad spänning. Denna metod använder ett standard [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fyllningsläge.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och höjden på kurvan. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som definierar splinen. |
| spänning | float | Värde större än eller lika med 0.0F som specificerar spänningen i kurvan. |

### Method: draw_closed_curve_by_points_tension(pen, points, tension) {#draw_closed_curve_by_points_tension_pen_points_tension_26}


```
 draw_closed_curve_by_points_tension(pen, points, tension) 
```

Ritar en sluten cardinal‑spline definierad av en matris av [Point](/imaging/python-net/aspose.imaging/point/) strukturer med en specificerad spänning. Denna metod använder ett standard [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fyllningsläge.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och höjden på kurvan. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av [Point](/imaging/python-net/aspose.imaging/point/) strukturer som definierar splinen. |
| spänning | float | Värde större än eller lika med 0.0F som specificerar spänningen i kurvan. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_27}


```
 draw_curve(pen, points) 
```

Ritar en cardinal‑spline genom en specificerad matris av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. Denna metod använder en standardspänning på 0.5.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och höjden på kurvan. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som definierar splinen. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_curve(pen, points) {#draw_curve_pen_points_28}


```
 draw_curve(pen, points) 
```

Ritar en cardinal‑spline genom en specificerad matris av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. Denna metod använder en standardspänning på 0.5.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och höjden på kurvan. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som definierar splinen. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_curve(pen, points, offset, number_of_segments) {#draw_curve_pen_points_offset_number_of_segments_29}


```
 draw_curve(pen, points, offset, number_of_segments) 
```

Ritar en kardinal spline genom en specificerad array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. Ritningen börjar förskjuten från början av arrayen.<br/>            Denna metod använder en standardspänning på 0,5.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och höjden på kurvan. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som definierar splinen. |
| offset | int | Offset från det första elementet i arrayen av parametern _points_ till startpunkten i kurvan. |
| number_of_segments | int | Antal segment efter startpunkten som ska inkluderas i kurvan. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_30}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Ritar en kardinal spline genom en specificerad array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med en specificerad spänning. Ritningen börjar förskjuten från början av arrayen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och höjden på kurvan. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som definierar splinen. |
| offset | int | Offset från det första elementet i arrayen av parametern _points_ till startpunkten i kurvan. |
| number_of_segments | int | Antal segment efter startpunkten som ska inkluderas i kurvan. |
| spänning | float | Värde större än eller lika med 0.0F som specificerar spänningen i kurvan. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_31}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Ritar en kardinal spline genom en specificerad array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med en specificerad spänning. Ritningen börjar förskjuten från början av arrayen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och höjden på kurvan. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som definierar splinen. |
| offset | int | Offset från det första elementet i arrayen av parametern _points_ till startpunkten i kurvan. |
| number_of_segments | int | Antal segment efter startpunkten som ska inkluderas i kurvan. |
| spänning | float | Värde större än eller lika med 0.0F som specificerar spänningen i kurvan. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_32}


```
 draw_curve(pen, points, tension) 
```

Ritar en kardinal spline genom en specificerad array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med en specificerad spänning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och höjden på kurvan. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som representerar de punkter som definierar kurvan. |
| spänning | float | Värde större än eller lika med 0.0F som specificerar spänningen i kurvan. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_33}


```
 draw_curve(pen, points, tension) 
```

Ritar en kardinal spline genom en specificerad array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med en specificerad spänning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och höjden på kurvan. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som representerar de punkter som definierar kurvan. |
| spänning | float | Värde större än eller lika med 0.0F som specificerar spänningen i kurvan. |

### Method: draw_curve_by_point_fs(pen, points) {#draw_curve_by_point_fs_pen_points_34}


```
 draw_curve_by_point_fs(pen, points) 
```

Ritar en kardinal spline genom en specificerad array av [Point](/imaging/python-net/aspose.imaging/point/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och höjden på kurvan. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av [Point](/imaging/python-net/aspose.imaging/point/) strukturer som definierar splinen. |

### Method: draw_curve_by_point_fs_tension(pen, points, tension) {#draw_curve_by_point_fs_tension_pen_points_tension_35}


```
 draw_curve_by_point_fs_tension(pen, points, tension) 
```

Ritar en kardinal spline genom en specificerad array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med en specificerad spänning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och höjden på kurvan. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som representerar de punkter som definierar kurvan. |
| spänning | float | Värde större än eller lika med 0.0F som specificerar spänningen i kurvan. |

### Method: draw_curve_by_points(pen, points) {#draw_curve_by_points_pen_points_36}


```
 draw_curve_by_points(pen, points) 
```

Ritar en cardinal‑spline genom en specificerad matris av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. Denna metod använder en standardspänning på 0.5.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och höjden på kurvan. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som definierar splinen. |

### Method: draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) {#draw_curve_by_points_f_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_37}


```
 draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) 
```

Ritar en kardinal spline genom en specificerad array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med en specificerad spänning. Ritningen börjar förskjuten från början av arrayen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och höjden på kurvan. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som definierar splinen. |
| offset | int | Offset från det första elementet i arrayen av parametern _points_ till startpunkten i kurvan. |
| number_of_segments | int | Antal segment efter startpunkten som ska inkluderas i kurvan. |
| spänning | float | Värde större än eller lika med 0.0F som specificerar spänningen i kurvan. |

### Method: draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) {#draw_curve_by_points_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_38}


```
 draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) 
```

Ritar en kardinal spline genom en specificerad array av [Point](/imaging/python-net/aspose.imaging/point/) strukturer med en specificerad spänning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och höjden på kurvan. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av [Point](/imaging/python-net/aspose.imaging/point/) strukturer som definierar splinen. |
| offset | int | Offset från det första elementet i arrayen av parametern _points_ till startpunkten i kurvan. |
| number_of_segments | int | Antal segment efter startpunkten som ska inkluderas i kurvan. |
| spänning | float | Värde större än eller lika med 0.0F som specificerar spänningen i kurvan. |

### Method: draw_curve_by_points_tension(pen, points, tension) {#draw_curve_by_points_tension_pen_points_tension_39}


```
 draw_curve_by_points_tension(pen, points, tension) 
```

Ritar en kardinal spline genom en specificerad array av [Point](/imaging/python-net/aspose.imaging/point/) strukturer med en specificerad spänning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och höjden på kurvan. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av [Point](/imaging/python-net/aspose.imaging/point/) strukturer som definierar splinen. |
| spänning | float | Värde större än eller lika med 0.0F som specificerar spänningen i kurvan. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_40}


```
 draw_ellipse(pen, rect) 
```

Ritar en ellips definierad av en avgränsande [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och stilen på ellipsen. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som definierar ellipsens gränser. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_41}


```
 draw_ellipse(pen, rect) 
```

Ritar en ellips definierad av en avgränsande [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och stilen på ellipsen. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som definierar ellipsens gränser. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_42}


```
 draw_ellipse(pen, x, y, width, height) 
```

Ritar en ellips definierad av en avgränsande rektangel som anges av ett koordinatpar, en höjd och en bredd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och stilen på ellipsen. |
| x | float | X-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen. |
| y | float | Y-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen. |
| width | float | Bredden på den omgivande rektangeln som definierar ellipsen. |
| height | float | Höjden på den omgivande rektangeln som definierar ellipsen. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_43}


```
 draw_ellipse(pen, x, y, width, height) 
```

Ritar en ellips definierad av en avgränsande rektangel som anges av ett koordinatpar, en höjd och en bredd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och stilen på ellipsen. |
| x | int | X-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen. |
| y | int | Y-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen. |
| width | int | Bredden på den omgivande rektangeln som definierar ellipsen. |
| height | int | Höjden på den omgivande rektangeln som definierar ellipsen. |

### Method: draw_ellipse_by_xy(pen, x, y, width, height) {#draw_ellipse_by_xy_pen_x_y_width_height_44}


```
 draw_ellipse_by_xy(pen, x, y, width, height) 
```

Ritar en ellips definierad av en avgränsande rektangel som anges av ett koordinatpar, en höjd och en bredd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och stilen på ellipsen. |
| x | int | X-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen. |
| y | int | Y-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen. |
| width | int | Bredden på den omgivande rektangeln som definierar ellipsen. |
| height | int | Höjden på den omgivande rektangeln som definierar ellipsen. |

### Method: draw_ellipse_by_xyf(pen, x, y, width, height) {#draw_ellipse_by_xyf_pen_x_y_width_height_45}


```
 draw_ellipse_by_xyf(pen, x, y, width, height) 
```

Ritar en ellips definierad av en avgränsande rektangel som anges av ett koordinatpar, en höjd och en bredd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och stilen på ellipsen. |
| x | float | X-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen. |
| y | float | Y-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen. |
| width | float | Bredden på den omgivande rektangeln som definierar ellipsen. |
| height | float | Höjden på den omgivande rektangeln som definierar ellipsen. |

### Method: draw_ellipse_f(pen, rect) {#draw_ellipse_f_pen_rect_46}


```
 draw_ellipse_f(pen, rect) 
```

Ritar en ellips definierad av en avgränsande [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och stilen på ellipsen. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som definierar ellipsens gränser. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_47}


```
 draw_image(image, dest_points) 
```

Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden som ska ritas. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av tre PointF-strukturer som definierar ett parallellogram. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_48}


```
 draw_image(image, dest_points) 
```

Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden som ska ritas. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av tre PointF-strukturer som definierar ett parallellogram. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_49}


```
 draw_image(image, dest_points, src_rect) 
```

Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden som ska ritas. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av tre PointF-strukturer som definierar ett parallellogram. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Källrektangeln. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_50}


```
 draw_image(image, dest_points, src_rect) 
```

Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden som ska ritas. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av tre PointF-strukturer som definierar ett parallellogram. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Källrektangeln. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_51}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden som ska ritas. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av tre PointF-strukturer som definierar ett parallellogram. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Källrektangeln. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Måttenheterna. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_52}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden som ska ritas. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av tre PointF-strukturer som definierar ett parallellogram. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Källrektangeln. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Måttenheterna. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_53}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden som ska ritas. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av tre PointF-strukturer som definierar ett parallellogram. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Källrektangeln. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Måttenheterna. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Bildattributen. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_54}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden som ska ritas. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av tre PointF-strukturer som definierar ett parallellogram. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Källrektangeln. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Måttenheterna. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Bildattributen. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_55}


```
 draw_image(source_image, point) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), med dess ursprungliga fysiska storlek, på den specificerade platsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som representerar den övre vänstra hörnet av den ritade bilden. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_56}


```
 draw_image(source_image, point) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), med dess ursprungliga fysiska storlek, på den specificerade platsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som representerar den övre vänstra hörnet av den ritade bilden. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_57}


```
 draw_image(source_image, rect) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som specificerar platsen och storleken på den ritade bilden. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_58}


```
 draw_image(source_image, rect) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som specificerar platsen och storleken på den ritade bilden. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_59}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Destinationsrektangeln. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafikenheten. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_60}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Destinationsrektangeln. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafikenheten. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_61}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Destinationsrektangeln. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafikenheten. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Bildattributen. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_62}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Destinationsrektangeln. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafikenheten. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Bildattributen. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_63}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rect-källan. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rect-destinationen. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafikenheten. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_64}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Rect-källan. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Rect-destinationen. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafikenheten. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_65}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rect-källan. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rect-destinationen. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafikenheten. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Bildattributen. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_66}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Rect-källan. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Rect-destinationen. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafikenheten. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Bildattributen. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_67}


```
 draw_image(source_image, x, y) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), med dess ursprungliga fysiska storlek, på den specificerade platsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| x | float | X-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| y | float | Y-koordinaten för det övre vänstra hörnet av den ritade bilden. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_68}


```
 draw_image(source_image, x, y) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), med dess ursprungliga fysiska storlek, på den specificerade platsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| x | int | X-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| y | int | Y-koordinaten för det övre vänstra hörnet av den ritade bilden. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_69}


```
 draw_image(source_image, x, y, width, height) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| x | float | X-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| y | float | Y-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| width | float | Bredden på den ritade bilden. |
| height | float | Höjden på den ritade bilden. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_70}


```
 draw_image(source_image, x, y, width, height) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| x | int | X-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| y | int | Y-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| width | int | Bredden på den ritade bilden. |
| height | int | Höjden på den ritade bilden. |

### Method: draw_image_at_point(source_image, point) {#draw_image_at_point_source_image_point_71}


```
 draw_image_at_point(source_image, point) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), med dess ursprungliga fysiska storlek, på den specificerade platsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som representerar den övre vänstra hörnet av den ritade bilden. |

### Method: draw_image_at_point_f(source_image, point) {#draw_image_at_point_f_source_image_point_72}


```
 draw_image_at_point_f(source_image, point) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), med dess ursprungliga fysiska storlek, på den specificerade platsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som representerar den övre vänstra hörnet av den ritade bilden. |

### Method: draw_image_at_xy(source_image, x, y) {#draw_image_at_xy_source_image_x_y_73}


```
 draw_image_at_xy(source_image, x, y) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), med dess ursprungliga fysiska storlek, på den specificerade platsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| x | int | X-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| y | int | Y-koordinaten för det övre vänstra hörnet av den ritade bilden. |

### Method: draw_image_at_xyf(source_image, x, y) {#draw_image_at_xyf_source_image_x_y_74}


```
 draw_image_at_xyf(source_image, x, y) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), med dess ursprungliga fysiska storlek, på den specificerade platsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| x | float | X-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| y | float | Y-koordinaten för det övre vänstra hörnet av den ritade bilden. |

### Method: draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit) {#draw_image_dest_point_f_src_rect_f_with_unit_image_dest_points_src_rect_src_unit_75}


```
 draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit) 
```

Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden som ska ritas. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av tre PointF-strukturer som definierar ett parallellogram. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Källrektangeln. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Måttenheterna. |

### Method: draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_dest_point_f_src_rect_f_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_76}


```
 draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) 
```

Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden som ska ritas. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av tre PointF-strukturer som definierar ett parallellogram. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Källrektangeln. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Måttenheterna. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Bildattributen. |

### Method: draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect) {#draw_image_dest_points_f_src_rect_f_image_dest_points_src_rect_77}


```
 draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect) 
```

Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden som ska ritas. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av tre PointF-strukturer som definierar ett parallellogram. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Källrektangeln. |

### Method: draw_image_dest_points_src_rect(image, dest_points, src_rect) {#draw_image_dest_points_src_rect_image_dest_points_src_rect_78}


```
 draw_image_dest_points_src_rect(image, dest_points, src_rect) 
```

Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden som ska ritas. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av tre PointF-strukturer som definierar ett parallellogram. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Källrektangeln. |

### Method: draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit) {#draw_image_dest_points_src_rect_with_unit_image_dest_points_src_rect_src_unit_79}


```
 draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit) 
```

Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden som ska ritas. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av tre PointF-strukturer som definierar ett parallellogram. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Källrektangeln. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Måttenheterna. |

### Method: draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_dest_points_src_rect_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_80}


```
 draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) 
```

Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden som ska ritas. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av tre PointF-strukturer som definierar ett parallellogram. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Källrektangeln. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Måttenheterna. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Bildattributen. |

### Method: draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_dest_rect_f_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_81}


```
 draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Destinationsrektangeln att rita i. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafikenheten. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Bildattributen. |

### Method: draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_dest_rect_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_82}


```
 draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Destinationsrektangeln. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafikenheten. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Bildattributen. |

### Method: draw_image_in_rect(source_image, x, y, width, height) {#draw_image_in_rect_source_image_x_y_width_height_83}


```
 draw_image_in_rect(source_image, x, y, width, height) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| x | int | X-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| y | int | Y-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| width | int | Bredden på den ritade bilden. |
| height | int | Höjden på den ritade bilden. |

### Method: draw_image_in_rect_f(source_image, x, y, width, height) {#draw_image_in_rect_f_source_image_x_y_width_height_84}


```
 draw_image_in_rect_f(source_image, x, y, width, height) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| x | float | X-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| y | float | Y-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| width | float | Bredden på den ritade bilden. |
| height | float | Höjden på den ritade bilden. |

### Method: draw_image_in_rectangle(source_image, rect) {#draw_image_in_rectangle_source_image_rect_85}


```
 draw_image_in_rectangle(source_image, rect) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur som specificerar platsen och storleken på den ritade bilden. |

### Method: draw_image_points(image, dest_points) {#draw_image_points_image_dest_points_86}


```
 draw_image_points(image, dest_points) 
```

Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden som ska ritas. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av tre PointF-strukturer som definierar ett parallellogram. |

### Method: draw_image_points_f(image, dest_points) {#draw_image_points_f_image_dest_points_87}


```
 draw_image_points_f(image, dest_points) 
```

Ritar den specificerade delen av den specificerade _bilden_ på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden som ska ritas. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av tre PointF-strukturer som definierar ett parallellogram. |

### Method: draw_image_rectangle_f(source_image, rect) {#draw_image_rectangle_f_source_image_rect_88}


```
 draw_image_rectangle_f(source_image, rect) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som specificerar platsen och storleken på den ritade bilden. |

### Method: draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_src_dest_rects_f_with_unit_source_image_rect_source_rect_destination_graphics_unit_89}


```
 draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Rect-källan. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Rect-destinationen. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafikenheten. |

### Method: draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_src_dest_rects_with_unit_source_image_rect_source_rect_destination_graphics_unit_90}


```
 draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rect-källan. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rect-destinationen. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafikenheten. |

### Method: draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_src_dst_rect_f_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_91}


```
 draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Källrektangeln. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Destinationsrektangeln. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafikenheten att använda. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Bildattributen att använda. |

### Method: draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_src_dst_rects_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_92}


```
 draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rect-källan. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rect-destinationen. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafikenheten. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Bildattributen. |

### Method: draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit) {#draw_image_to_rect_f_with_unit_source_image_rect_destination_graphics_unit_93}


```
 draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Destinationsrektangeln. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafikenheten. |

### Method: draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit) {#draw_image_to_rect_with_unit_source_image_rect_destination_graphics_unit_94}


```
 draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit) 
```

Ritar den specificerade [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) på den specificerade platsen och med den specificerade storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Destinationsrektangeln. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Grafikenheten. |

### Method: draw_image_unscaled(source_image, point) {#draw_image_unscaled_source_image_point_95}


```
 draw_image_unscaled(source_image, point) 
```

Ritar en specificerad bild med dess ursprungliga fysiska storlek på en specificerad plats.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) struktur som specificerar det övre vänstra hörnet av den ritade bilden. |

### Method: draw_image_unscaled(source_image, rect) {#draw_image_unscaled_source_image_rect_96}


```
 draw_image_unscaled(source_image, rect) 
```

Ritar en specificerad bild med dess ursprungliga fysiska storlek på en specificerad plats.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) som specificerar det övre vänstra hörnet av den ritade bilden. X- och Y-egenskaperna för rektangeln specificerar det övre vänstra hörnet. Bredd- och höjd-egenskaperna ignoreras. |

### Method: draw_image_unscaled(source_image, x, y) {#draw_image_unscaled_source_image_x_y_97}


```
 draw_image_unscaled(source_image, x, y) 
```

Ritar den specificerade bilden med dess ursprungliga fysiska storlek på den plats som anges av ett koordinatpar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| x | int | X-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| y | int | Y-koordinaten för det övre vänstra hörnet av den ritade bilden. |

### Method: draw_image_unscaled(source_image, x, y, width, height) {#draw_image_unscaled_source_image_x_y_width_height_98}


```
 draw_image_unscaled(source_image, x, y, width, height) 
```

Ritar en specificerad bild med dess ursprungliga fysiska storlek på en specificerad plats.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| x | int | X-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| y | int | Y-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| width | int | Parametern används inte. |
| height | int | Parametern används inte. |

### Method: draw_image_unscaled_and_clipped(source_image, rect) {#draw_image_unscaled_and_clipped_source_image_rect_99}


```
 draw_image_unscaled_and_clipped(source_image, rect) 
```

Ritar den specificerade bilden utan skalning och beskär den, om nödvändigt, för att passa i den specificerade rektangeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) i vilken bilden ska ritas. |

### Method: draw_image_unscaled_in_rectangle(source_image, rect) {#draw_image_unscaled_in_rectangle_source_image_rect_100}


```
 draw_image_unscaled_in_rectangle(source_image, rect) 
```

Ritar en specificerad bild med dess ursprungliga fysiska storlek på en specificerad plats.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) som specificerar det övre vänstra hörnet av den ritade bilden. X- och Y-egenskaperna för rektangeln specificerar det övre vänstra hörnet. Bredd- och höjd-egenskaperna ignoreras. |

### Method: draw_image_unscaled_to_point(source_image, point) {#draw_image_unscaled_to_point_source_image_point_101}


```
 draw_image_unscaled_to_point(source_image, point) 
```

Ritar en specificerad bild med dess ursprungliga fysiska storlek på en specificerad plats.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Bilden att rita med. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) struktur som specificerar det övre vänstra hörnet av den ritade bilden. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_102}


```
 draw_line(pen, point1, point2) 
```

Ritar en linje som förbinder två [Point](/imaging/python-net/aspose.imaging/point/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och stilen på linjen. |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) struktur som representerar den första punkten att ansluta. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) struktur som representerar den andra punkten att ansluta. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_103}


```
 draw_line(pen, point1, point2) 
```

Ritar en linje som förbinder två [Point](/imaging/python-net/aspose.imaging/point/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och stilen på linjen. |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [Point](/imaging/python-net/aspose.imaging/point/) struktur som representerar den första punkten att ansluta. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [Point](/imaging/python-net/aspose.imaging/point/) struktur som representerar den andra punkten att ansluta. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_104}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Ritar en linje som förbinder de två punkterna som specificeras av koordinatparen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och stilen på linjen. |
| x1 | int | X-koordinaten för den första punkten. |
| y1 | int | Y-koordinaten för den första punkten. |
| x2 | int | X-koordinaten för den andra punkten. |
| y2 | int | Y-koordinaten för den andra punkten. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_105}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Ritar en linje som förbinder de två punkterna som specificeras av koordinatparen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och stilen på linjen. |
| x1 | float | X-koordinaten för den första punkten. |
| y1 | float | Y-koordinaten för den första punkten. |
| x2 | float | X-koordinaten för den andra punkten. |
| y2 | float | Y-koordinaten för den andra punkten. |

### Method: draw_line_by_xy(pen, x1, y1, x2, y2) {#draw_line_by_xy_pen_x1_y1_x2_y2_106}


```
 draw_line_by_xy(pen, x1, y1, x2, y2) 
```

Ritar en linje som förbinder de två punkterna som specificeras av koordinatparen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och stilen på linjen. |
| x1 | int | X-koordinaten för den första punkten. |
| y1 | int | Y-koordinaten för den första punkten. |
| x2 | int | X-koordinaten för den andra punkten. |
| y2 | int | Y-koordinaten för den andra punkten. |

### Method: draw_line_f_by_xy(pen, x1, y1, x2, y2) {#draw_line_f_by_xy_pen_x1_y1_x2_y2_107}


```
 draw_line_f_by_xy(pen, x1, y1, x2, y2) 
```

Ritar en linje som förbinder de två punkterna som specificeras av koordinatparen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och stilen på linjen. |
| x1 | float | X-koordinaten för den första punkten. |
| y1 | float | Y-koordinaten för den första punkten. |
| x2 | float | X-koordinaten för den andra punkten. |
| y2 | float | Y-koordinaten för den andra punkten. |

### Method: draw_line_point_f(pen, point1, point2) {#draw_line_point_f_pen_point1_point2_108}


```
 draw_line_point_f(pen, point1, point2) 
```

Ritar en linje som förbinder två [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och stilen på linjen. |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som representerar den första punkten att ansluta. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som representerar den andra punkten att ansluta. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_109}


```
 draw_lines(pen, points) 
```

Ritar en serie linjesegment som förbinder en array av [Point](/imaging/python-net/aspose.imaging/point/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för linjesegmenten. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av [Point](/imaging/python-net/aspose.imaging/point/) strukturer som representerar punkterna att ansluta. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_110}


```
 draw_lines(pen, points) 
```

Ritar en serie linjesegment som förbinder en array av [Point](/imaging/python-net/aspose.imaging/point/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för linjesegmenten. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av [Point](/imaging/python-net/aspose.imaging/point/) strukturer som representerar punkterna att ansluta. |

### Method: draw_lines_f(pen, points) {#draw_lines_f_pen_points_111}


```
 draw_lines_f(pen, points) 
```

Ritar en serie linjesegment som förbinder en array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för linjesegmenten. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som representerar punkterna att ansluta. |

### Method: draw_path(pen, path) {#draw_path_pen_path_112}


```
 draw_path(pen, path) 
```

Ritar en [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för sökvägen. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) att rita. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_113}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Ritar en pajform definierad av en ellips specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur och två radiala linjer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för pajformen. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som representerar den omgivande rektangeln som definierar ellipsen som pajformen kommer från. |
| start_angle | float | Vinkel mätt i grader medurs från x-axeln till den första sidan av pajformen. |
| sweep_angle | float | Vinkel mätt i grader medurs från parametern _startAngle_ till den andra sidan av pajformen. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_114}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Ritar en pajform definierad av en ellips specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur och två radiala linjer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för pajformen. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som representerar den omgivande rektangeln som definierar ellipsen som pajformen kommer från. |
| start_angle | float | Vinkel mätt i grader medurs från x-axeln till den första sidan av pajformen. |
| sweep_angle | float | Vinkel mätt i grader medurs från parametern _startAngle_ till den andra sidan av pajformen. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_115}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Ritar en pajform definierad av en ellips specificerad av ett koordinatpar, en bredd, en höjd och två radiala linjer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för pajformen. |
| x | float | X-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen som pajformen kommer från. |
| y | float | Y-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen som pajformen kommer från. |
| width | float | Bredden på den omgivande rektangeln som definierar ellipsen som pajformen kommer från. |
| height | float | Höjden på den omgivande rektangeln som definierar ellipsen som pajformen kommer från. |
| start_angle | float | Vinkel mätt i grader medurs från x-axeln till den första sidan av pajformen. |
| sweep_angle | float | Vinkel mätt i grader medurs från parametern _startAngle_ till den andra sidan av pajformen. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_116}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Ritar en pajform definierad av en ellips specificerad av ett koordinatpar, en bredd, en höjd och två radiala linjer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för pajformen. |
| x | int | X-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen som pajformen kommer från. |
| y | int | Y-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen som pajformen kommer från. |
| width | int | Bredden på den omgivande rektangeln som definierar ellipsen som pajformen kommer från. |
| height | int | Höjden på den omgivande rektangeln som definierar ellipsen som pajformen kommer från. |
| start_angle | int | Vinkel mätt i grader medurs från x-axeln till den första sidan av pajformen. |
| sweep_angle | int | Vinkel mätt i grader medurs från parametern _startAngle_ till den andra sidan av pajformen. |

### Method: draw_pie_in_rect(pen, rect, start_angle, sweep_angle) {#draw_pie_in_rect_pen_rect_start_angle_sweep_angle_117}


```
 draw_pie_in_rect(pen, rect, start_angle, sweep_angle) 
```

Ritar en pajform definierad av en ellips specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur och två radiala linjer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för pajformen. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som representerar den omgivande rektangeln som definierar ellipsen som pajformen kommer från. |
| start_angle | float | Vinkel mätt i grader medurs från x-axeln till den första sidan av pajformen. |
| sweep_angle | float | Vinkel mätt i grader medurs från parametern _startAngle_ till den andra sidan av pajformen. |

### Method: draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle) {#draw_pie_in_rect_f_pen_rect_start_angle_sweep_angle_118}


```
 draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle) 
```

Ritar en pajform definierad av en ellips specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur och två radiala linjer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för pajformen. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som representerar den omgivande rektangeln som definierar ellipsen som pajformen kommer från. |
| start_angle | float | Vinkel mätt i grader medurs från x-axeln till den första sidan av pajformen. |
| sweep_angle | float | Vinkel mätt i grader medurs från parametern _startAngle_ till den andra sidan av pajformen. |

### Method: draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_xy_pen_x_y_width_height_start_angle_sweep_angle_119}


```
 draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle) 
```

Ritar en pajform definierad av en ellips specificerad av ett koordinatpar, en bredd, en höjd och två radiala linjer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för pajformen. |
| x | int | X-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen som pajformen kommer från. |
| y | int | Y-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen som pajformen kommer från. |
| width | int | Bredden på den omgivande rektangeln som definierar ellipsen som pajformen kommer från. |
| height | int | Höjden på den omgivande rektangeln som definierar ellipsen som pajformen kommer från. |
| start_angle | int | Vinkel mätt i grader medurs från x-axeln till den första sidan av pajformen. |
| sweep_angle | int | Vinkel mätt i grader medurs från parametern _startAngle_ till den andra sidan av pajformen. |

### Method: draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_xyf_pen_x_y_width_height_start_angle_sweep_angle_120}


```
 draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle) 
```

Ritar en pajform definierad av en ellips specificerad av ett koordinatpar, en bredd, en höjd och två radiala linjer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för pajformen. |
| x | float | X-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen som pajformen kommer från. |
| y | float | Y-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen som pajformen kommer från. |
| width | float | Bredden på den omgivande rektangeln som definierar ellipsen som pajformen kommer från. |
| height | float | Höjden på den omgivande rektangeln som definierar ellipsen som pajformen kommer från. |
| start_angle | float | Vinkel mätt i grader medurs från x-axeln till den första sidan av pajformen. |
| sweep_angle | float | Vinkel mätt i grader medurs från parametern _startAngle_ till den andra sidan av pajformen. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_121}


```
 draw_polygon(pen, points) 
```

Ritar en polygon definierad av en array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för polygonen. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som representerar polygonens hörn. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_122}


```
 draw_polygon(pen, points) 
```

Ritar en polygon definierad av en array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för polygonen. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som representerar polygonens hörn. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_polygon_f(pen, points) {#draw_polygon_f_pen_points_123}


```
 draw_polygon_f(pen, points) 
```

Ritar en polygon definierad av en array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för polygonen. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som representerar polygonens hörn. |

### Method: draw_rect(pen, x, y, width, height) {#draw_rect_pen_x_y_width_height_124}


```
 draw_rect(pen, x, y, width, height) 
```

Ritar en rektangel specificerad av ett koordinatpar, en bredd och en höjd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | En [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för rektangeln. |
| x | int | X-koordinaten för det övre vänstra hörnet av rektangeln som ska ritas. |
| y | int | Y-koordinaten för det övre vänstra hörnet av rektangeln som ska ritas. |
| width | int | Bredden på rektangeln som ska ritas. |
| height | int | Höjden på rektangeln som ska ritas. |

### Method: draw_rect_f(pen, x, y, width, height) {#draw_rect_f_pen_x_y_width_height_125}


```
 draw_rect_f(pen, x, y, width, height) 
```

Ritar en rektangel specificerad av ett koordinatpar, en bredd och en höjd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | En [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för rektangeln. |
| x | float | X-koordinaten för det övre vänstra hörnet av rektangeln som ska ritas. |
| y | float | Y-koordinaten för det övre vänstra hörnet av rektangeln som ska ritas. |
| width | float | Bredden på rektangeln som ska ritas. |
| height | float | Höjden på rektangeln som ska ritas. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_126}


```
 draw_rectangle(pen, rect) 
```

Ritar en rektangel specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | En [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för rektangeln. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | En [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som representerar rektangeln som ska ritas. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_127}


```
 draw_rectangle(pen, rect) 
```

Ritar en rektangel specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | En [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för rektangeln. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | En [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som representerar rektangeln som ska ritas. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_128}


```
 draw_rectangle(pen, x, y, width, height) 
```

Ritar en rektangel specificerad av ett koordinatpar, en bredd och en höjd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | En [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för rektangeln. |
| x | float | X-koordinaten för det övre vänstra hörnet av rektangeln som ska ritas. |
| y | float | Y-koordinaten för det övre vänstra hörnet av rektangeln som ska ritas. |
| width | float | Bredden på rektangeln som ska ritas. |
| height | float | Höjden på rektangeln som ska ritas. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_129}


```
 draw_rectangle(pen, x, y, width, height) 
```

Ritar en rektangel specificerad av ett koordinatpar, en bredd och en höjd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | En [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för rektangeln. |
| x | int | X-koordinaten för det övre vänstra hörnet av rektangeln som ska ritas. |
| y | int | Y-koordinaten för det övre vänstra hörnet av rektangeln som ska ritas. |
| width | int | Bredden på rektangeln som ska ritas. |
| height | int | Höjden på rektangeln som ska ritas. |

### Method: draw_rectangle_f(pen, rect) {#draw_rectangle_f_pen_rect_130}


```
 draw_rectangle_f(pen, rect) 
```

Ritar en rektangel specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | En [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färg, bredd och stil för rektangeln. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | En [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som representerar rektangeln som ska ritas. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_131}


```
 draw_rectangles(pen, rects) 
```

Ritar en serie rektanglar specificerade av [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och stilen på rektanglarnas konturer. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Array av [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) strukturer som representerar rektanglarna som ska ritas. |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_132}


```
 draw_rectangles(pen, rects) 
```

Ritar en serie rektanglar specificerade av [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och stilen på rektanglarnas konturer. |
| rects | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | Array av [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) strukturer som representerar rektanglarna som ska ritas. |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: draw_rectangles_f(pen, rects) {#draw_rectangles_f_pen_rects_133}


```
 draw_rectangles_f(pen, rects) 
```

Ritar en serie rektanglar specificerade av [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) som bestämmer färgen, bredden och stilen på rektanglarnas konturer. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Array av [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) strukturer som representerar rektanglarna som ska ritas. |

### Method: draw_string(s, font, brush, layout_rectangle) {#draw_string_s_font_brush_layout_rectangle_134}


```
 draw_string(s, font, brush, layout_rectangle) 
```

Ritar den angivna textsträngen i den angivna rektangeln med de angivna [Brush](/imaging/python-net/aspose.imaging/brush/) och [Font](/imaging/python-net/aspose.imaging/font/) objekten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| s | string | Sträng att rita. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) som definierar textformatet för strängen. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer färgen och texturen på den ritade texten. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som specificerar platsen för den ritade texten. |

### Method: draw_string(s, font, brush, layout_rectangle, format) {#draw_string_s_font_brush_layout_rectangle_format_135}


```
 draw_string(s, font, brush, layout_rectangle, format) 
```

Ritar den angivna textsträngen i den angivna rektangeln med de angivna [Brush](/imaging/python-net/aspose.imaging/brush/) och [Font](/imaging/python-net/aspose.imaging/font/) objekten med formateringsattributen från den angivna [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| s | string | Sträng att rita. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) som definierar textformatet för strängen. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer färgen och texturen på den ritade texten. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som specificerar platsen för den ritade texten. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) som specificerar formateringsattribut, såsom radavstånd och justering, som tillämpas på den ritade texten. |

### Method: draw_string(s, font, brush, point) {#draw_string_s_font_brush_point_136}


```
 draw_string(s, font, brush, point) 
```

Ritar den angivna textsträngen på den angivna platsen med de angivna [Brush](/imaging/python-net/aspose.imaging/brush/) och [Font](/imaging/python-net/aspose.imaging/font/) objekten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| s | string | Sträng att rita. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) som definierar textformatet för strängen. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer färgen och texturen på den ritade texten. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som specificerar det övre vänstra hörnet på den ritade texten. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_string(s, font, brush, point, format) {#draw_string_s_font_brush_point_format_137}


```
 draw_string(s, font, brush, point, format) 
```

Ritar den angivna textsträngen på den angivna platsen med de angivna [Brush](/imaging/python-net/aspose.imaging/brush/) och [Font](/imaging/python-net/aspose.imaging/font/) objekten med formateringsattributen från den angivna [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| s | string | Sträng att rita. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) som definierar textformatet för strängen. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer färgen och texturen på den ritade texten. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som specificerar det övre vänstra hörnet på den ritade texten. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) som specificerar formateringsattribut, såsom radavstånd och justering, som tillämpas på den ritade texten. |

### Method: draw_string(s, font, brush, x, y) {#draw_string_s_font_brush_x_y_138}


```
 draw_string(s, font, brush, x, y) 
```

Ritar den angivna textsträngen på den angivna platsen med de angivna [Brush](/imaging/python-net/aspose.imaging/brush/) och [Font](/imaging/python-net/aspose.imaging/font/) objekten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| s | string | Sträng att rita. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) som definierar textformatet för strängen. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer färgen och texturen på den ritade texten. |
| x | float | X-koordinaten för det övre vänstra hörnet på den ritade texten. |
| y | float | Y-koordinaten för det övre vänstra hörnet på den ritade texten. |

### Method: draw_string(s, font, brush, x, y, format) {#draw_string_s_font_brush_x_y_format_139}


```
 draw_string(s, font, brush, x, y, format) 
```

Ritar den angivna textsträngen på den angivna platsen med de angivna [Brush](/imaging/python-net/aspose.imaging/brush/) och [Font](/imaging/python-net/aspose.imaging/font/) objekten med formateringsattributen från den angivna [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| s | string | Sträng att rita. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) som definierar textformatet för strängen. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer färgen och texturen på den ritade texten. |
| x | float | X-koordinaten för det övre vänstra hörnet på den ritade texten. |
| y | float | Y-koordinaten för det övre vänstra hörnet på den ritade texten. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) som specificerar formateringsattribut, såsom radavstånd och justering, som tillämpas på den ritade texten. |

### Method: draw_string_at_point_f(s, font, brush, point) {#draw_string_at_point_f_s_font_brush_point_140}


```
 draw_string_at_point_f(s, font, brush, point) 
```

Ritar den angivna textsträngen på den angivna platsen med de angivna [Brush](/imaging/python-net/aspose.imaging/brush/) och [Font](/imaging/python-net/aspose.imaging/font/) objekten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| s | string | Sträng att rita. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) som definierar textformatet för strängen. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer färgen och texturen på den ritade texten. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som specificerar det övre vänstra hörnet på den ritade texten. |

### Method: draw_string_at_point_f_format(s, font, brush, point, format) {#draw_string_at_point_f_format_s_font_brush_point_format_141}


```
 draw_string_at_point_f_format(s, font, brush, point, format) 
```

Ritar den angivna textsträngen på den angivna platsen med de angivna [Brush](/imaging/python-net/aspose.imaging/brush/) och [Font](/imaging/python-net/aspose.imaging/font/) objekten med formateringsattributen från den angivna [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| s | string | Sträng att rita. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) som definierar textformatet för strängen. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer färgen och texturen på den ritade texten. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struktur som specificerar det övre vänstra hörnet på den ritade texten. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) som specificerar formateringsattribut, såsom radavstånd och justering, som tillämpas på den ritade texten. |

### Method: draw_string_at_xy(s, font, brush, x, y) {#draw_string_at_xy_s_font_brush_x_y_142}


```
 draw_string_at_xy(s, font, brush, x, y) 
```

Ritar den angivna textsträngen på den angivna platsen med de angivna [Brush](/imaging/python-net/aspose.imaging/brush/) och [Font](/imaging/python-net/aspose.imaging/font/) objekten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| s | string | Sträng att rita. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) som definierar textformatet för strängen. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer färgen och texturen på den ritade texten. |
| x | float | X-koordinaten för det övre vänstra hörnet på den ritade texten. |
| y | float | Y-koordinaten för det övre vänstra hörnet på den ritade texten. |

### Method: draw_string_in_rect(s, font, brush, layout_rectangle) {#draw_string_in_rect_s_font_brush_layout_rectangle_143}


```
 draw_string_in_rect(s, font, brush, layout_rectangle) 
```

Ritar den angivna textsträngen i den angivna rektangeln med de angivna [Brush](/imaging/python-net/aspose.imaging/brush/) och [Font](/imaging/python-net/aspose.imaging/font/) objekten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| s | string | Sträng att rita. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) som definierar textformatet för strängen. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer färgen och texturen på den ritade texten. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som specificerar platsen för den ritade texten. |

### Method: draw_string_in_rect_f(s, font, brush, layout_rectangle, format) {#draw_string_in_rect_f_s_font_brush_layout_rectangle_format_144}


```
 draw_string_in_rect_f(s, font, brush, layout_rectangle, format) 
```

Ritar den angivna textsträngen i den angivna rektangeln med de angivna [Brush](/imaging/python-net/aspose.imaging/brush/) och [Font](/imaging/python-net/aspose.imaging/font/) objekten med formateringsattributen från den angivna [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| s | string | Sträng att rita. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) som definierar textformatet för strängen. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer färgen och texturen på den ritade texten. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som specificerar platsen för den ritade texten. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) som specificerar formateringsattribut, såsom radavstånd och justering, som tillämpas på den ritade texten. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_145}


```
 fill_closed_curve(brush, points) 
```

Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. Denna metod använder en standardspänning på 0,5 och [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fyllningsläge.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som definierar splinen. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_146}


```
 fill_closed_curve(brush, points) 
```

Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. Denna metod använder en standardspänning på 0,5 och [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fyllningsläge.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som definierar splinen. |

### Method: fill_closed_curve(brush, points, fill_mode) {#fill_closed_curve_brush_points_fill_mode_147}


```
 fill_closed_curve(brush, points, fill_mode) 
```

Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med det angivna fyllningsläget. Denna metod använder en standardspänning på 0,5.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som definierar splinen. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Medlem av [FillMode](/imaging/python-net/aspose.imaging/fillmode/)‑enumerationen som bestämmer hur kurvan fylls. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_148}


```
 fill_closed_curve(brush, points, fillmode) 
```

Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med det angivna fyllningsläget. Denna metod använder en standardspänning på 0,5.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som definierar splinen. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) |  |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_149}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med det angivna fyllningsläget och spänning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | En [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som definierar splinen. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Medlem av [FillMode](/imaging/python-net/aspose.imaging/fillmode/)‑enumerationen som bestämmer hur kurvan fylls. |
| spänning | float | Värde större än eller lika med 0.0F som specificerar spänningen i kurvan. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_150}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med det angivna fyllningsläget och spänning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | En [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som definierar splinen. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Medlem av [FillMode](/imaging/python-net/aspose.imaging/fillmode/)‑enumerationen som bestämmer hur kurvan fylls. |
| spänning | float | Värde större än eller lika med 0.0F som specificerar spänningen i kurvan. |

### Method: fill_closed_curve_by_point(brush, points) {#fill_closed_curve_by_point_brush_points_151}


```
 fill_closed_curve_by_point(brush, points) 
```

Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. Denna metod använder en standardspänning på 0,5 och [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fyllningsläge.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som definierar splinen. |

### Method: fill_closed_curve_by_point_f(brush, points) {#fill_closed_curve_by_point_f_brush_points_152}


```
 fill_closed_curve_by_point_f(brush, points) 
```

Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer. Denna metod använder en standardspänning på 0,5 och [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) fyllningsläge.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som definierar splinen. |

### Method: fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension) {#fill_closed_curve_by_point_f_fill_mode_tension_brush_points_fillmode_tension_153}


```
 fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension) 
```

Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med det angivna fyllningsläget och spänning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | En [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som definierar splinen. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Medlem av [FillMode](/imaging/python-net/aspose.imaging/fillmode/)‑enumerationen som bestämmer hur kurvan fylls. |
| spänning | float | Värde större än eller lika med 0.0F som specificerar spänningen i kurvan. |

### Method: fill_closed_curve_by_point_fill_mode(brush, points, fillmode) {#fill_closed_curve_by_point_fill_mode_brush_points_fillmode_154}


```
 fill_closed_curve_by_point_fill_mode(brush, points, fillmode) 
```

Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [Point](/imaging/python-net/aspose.imaging/point/) strukturer med det angivna fyllningsläget. Denna metod använder en standardspänning på 0,5.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av [Point](/imaging/python-net/aspose.imaging/point/) strukturer som definierar splinen. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Medlem av [FillMode](/imaging/python-net/aspose.imaging/fillmode/)‑enumerationen som bestämmer hur kurvan fylls. |

### Method: fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension) {#fill_closed_curve_by_point_fill_mode_tension_brush_points_fillmode_tension_155}


```
 fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension) 
```

Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [Point](/imaging/python-net/aspose.imaging/point/) strukturer med det angivna fyllningsläget och spänning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av [Point](/imaging/python-net/aspose.imaging/point/) strukturer som definierar splinen. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Medlem av [FillMode](/imaging/python-net/aspose.imaging/fillmode/)‑enumerationen som bestämmer hur kurvan fylls. |
| spänning | float | Värde större än eller lika med 0.0F som specificerar spänningen i kurvan. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_156}


```
 fill_ellipse(brush, rect) 
```

Fyller insidan av en ellips definierad av en omslutande rektangel specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som representerar den omgivande rektangeln som definierar ellipsen. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_157}


```
 fill_ellipse(brush, rect) 
```

Fyller insidan av en ellips definierad av en omslutande rektangel specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som representerar den omgivande rektangeln som definierar ellipsen. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_158}


```
 fill_ellipse(brush, x, y, width, height) 
```

Fyller insidan av en ellips definierad av en omslutande rektangel specificerad av ett par koordinater, en bredd och en höjd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| x | float | X-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen. |
| y | float | Y-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen. |
| width | float | Bredden på den omgivande rektangeln som definierar ellipsen. |
| height | float | Höjden på den omgivande rektangeln som definierar ellipsen. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_159}


```
 fill_ellipse(brush, x, y, width, height) 
```

Fyller insidan av en ellips definierad av en omslutande rektangel specificerad av ett par koordinater, en bredd och en höjd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| x | int | X-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen. |
| y | int | Y-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen. |
| width | int | Bredden på den omgivande rektangeln som definierar ellipsen. |
| height | int | Höjden på den omgivande rektangeln som definierar ellipsen. |

### Method: fill_ellipse_at_xywh(brush, x, y, width, height) {#fill_ellipse_at_xywh_brush_x_y_width_height_160}


```
 fill_ellipse_at_xywh(brush, x, y, width, height) 
```

Fyller insidan av en ellips definierad av en omslutande rektangel specificerad av ett par koordinater, en bredd och en höjd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| x | int | X-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen. |
| y | int | Y-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen. |
| width | int | Bredden på den omgivande rektangeln som definierar ellipsen. |
| height | int | Höjden på den omgivande rektangeln som definierar ellipsen. |

### Method: fill_ellipse_at_xywhf(brush, x, y, width, height) {#fill_ellipse_at_xywhf_brush_x_y_width_height_161}


```
 fill_ellipse_at_xywhf(brush, x, y, width, height) 
```

Fyller insidan av en ellips definierad av en omslutande rektangel specificerad av ett par koordinater, en bredd och en höjd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| x | float | X-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen. |
| y | float | Y-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen. |
| width | float | Bredden på den omgivande rektangeln som definierar ellipsen. |
| height | float | Höjden på den omgivande rektangeln som definierar ellipsen. |

### Method: fill_ellipse_in_rect(brush, rect) {#fill_ellipse_in_rect_brush_rect_162}


```
 fill_ellipse_in_rect(brush, rect) 
```

Fyller insidan av en ellips definierad av en omslutande rektangel specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som representerar den omgivande rektangeln som definierar ellipsen. |

### Method: fill_ellipse_in_rect_f(brush, rect) {#fill_ellipse_in_rect_f_brush_rect_163}


```
 fill_ellipse_in_rect_f(brush, rect) 
```

Fyller insidan av en ellips definierad av en omslutande rektangel specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som representerar den omgivande rektangeln som definierar ellipsen. |

### Method: fill_path(brush, path) {#fill_path_brush_path_164}


```
 fill_path(brush, path) 
```

Fyller insidan av en [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) som representerar sökvägen att fylla. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_165}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Fyller insidan av ett pajsegment definierat av en ellips specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur och två radiala linjer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur som representerar den omgivande rektangeln som definierar ellipsen varifrån pajsektionen kommer. |
| start_angle | float | Vinkel i grader mätt medurs från x-axeln till den första sidan av pajsektionen. |
| sweep_angle | float | Vinkel i grader mätt medurs från parametern _startAngle_ till den andra sidan av pajsektionen. |


**See also:**

**[Example # 1](#example_95)**: The following example shows how to compose an animated GIF image from individ...


### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_166}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Fyller insidan av ett pajsegment definierat av en ellips specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur och två radiala linjer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur som representerar den omgivande rektangeln som definierar ellipsen varifrån pajsektionen kommer. |
| start_angle | float | Vinkel i grader mätt medurs från x-axeln till den första sidan av pajsektionen. |
| sweep_angle | float | Vinkel i grader mätt medurs från parametern _startAngle_ till den andra sidan av pajsektionen. |


**See also:**

**[Example # 1](#example_95)**: The following example shows how to compose an animated GIF image from individ...


### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_167}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Fyller insidan av ett pajsegment definierat av en ellips specificerad av ett par koordinater, en bredd, en höjd och två radiala linjer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| x | float | X-koordinaten för det övre vänstra hörnet på den omgivande rektangeln som definierar ellipsen varifrån pajsektionen kommer. |
| y | float | Y-koordinaten för det övre vänstra hörnet på den omgivande rektangeln som definierar ellipsen varifrån pajsektionen kommer. |
| width | float | Bredden på den omgivande rektangeln som definierar ellipsen varifrån pajsektionen kommer. |
| height | float | Höjden på den avgränsande rektangeln som definierar ellipsen varifrån pajsektionen kommer. |
| start_angle | float | Vinkel i grader mätt medurs från x-axeln till den första sidan av pajsektionen. |
| sweep_angle | float | Vinkel i grader mätt medurs från parametern _startAngle_ till den andra sidan av pajsektionen. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_168}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Fyller insidan av ett pajsegment definierat av en ellips specificerad av ett par koordinater, en bredd, en höjd och två radiala linjer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| x | int | X-koordinaten för det övre vänstra hörnet på den omgivande rektangeln som definierar ellipsen varifrån pajsektionen kommer. |
| y | int | Y-koordinaten för det övre vänstra hörnet på den omgivande rektangeln som definierar ellipsen varifrån pajsektionen kommer. |
| width | int | Bredden på den omgivande rektangeln som definierar ellipsen varifrån pajsektionen kommer. |
| height | int | Höjden på den avgränsande rektangeln som definierar ellipsen varifrån pajsektionen kommer. |
| start_angle | int | Vinkel i grader mätt medurs från x-axeln till den första sidan av pajsektionen. |
| sweep_angle | int | Vinkel i grader mätt medurs från parametern _startAngle_ till den andra sidan av pajsektionen. |

### Method: fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_at_xy_brush_x_y_width_height_start_angle_sweep_angle_169}


```
 fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle) 
```

Fyller insidan av ett pajsegment definierat av en ellips specificerad av ett par koordinater, en bredd, en höjd och två radiala linjer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| x | int | X-koordinaten för det övre vänstra hörnet på den omgivande rektangeln som definierar ellipsen varifrån pajsektionen kommer. |
| y | int | Y-koordinaten för det övre vänstra hörnet på den omgivande rektangeln som definierar ellipsen varifrån pajsektionen kommer. |
| width | int | Bredden på den omgivande rektangeln som definierar ellipsen varifrån pajsektionen kommer. |
| height | int | Höjden på den avgränsande rektangeln som definierar ellipsen varifrån pajsektionen kommer. |
| start_angle | int | Vinkel i grader mätt medurs från x-axeln till den första sidan av pajsektionen. |
| sweep_angle | int | Vinkel i grader mätt medurs från parametern _startAngle_ till den andra sidan av pajsektionen. |

### Method: fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_at_xyf_brush_x_y_width_height_start_angle_sweep_angle_170}


```
 fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle) 
```

Fyller insidan av ett pajsegment definierat av en ellips specificerad av ett par koordinater, en bredd, en höjd och två radiala linjer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| x | float | X-koordinaten för det övre vänstra hörnet på den omgivande rektangeln som definierar ellipsen varifrån pajsektionen kommer. |
| y | float | Y-koordinaten för det övre vänstra hörnet på den omgivande rektangeln som definierar ellipsen varifrån pajsektionen kommer. |
| width | float | Bredden på den omgivande rektangeln som definierar ellipsen varifrån pajsektionen kommer. |
| height | float | Höjden på den avgränsande rektangeln som definierar ellipsen varifrån pajsektionen kommer. |
| start_angle | float | Vinkel i grader mätt medurs från x-axeln till den första sidan av pajsektionen. |
| sweep_angle | float | Vinkel i grader mätt medurs från parametern _startAngle_ till den andra sidan av pajsektionen. |

### Method: fill_pie_in_rect(brush, rect, start_angle, sweep_angle) {#fill_pie_in_rect_brush_rect_start_angle_sweep_angle_171}


```
 fill_pie_in_rect(brush, rect, start_angle, sweep_angle) 
```

Fyller insidan av ett pajsegment definierat av en ellips specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur och två radiala linjer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur som representerar den omgivande rektangeln som definierar ellipsen varifrån pajsektionen kommer. |
| start_angle | float | Vinkel i grader mätt medurs från x-axeln till den första sidan av pajsektionen. |
| sweep_angle | float | Vinkel i grader mätt medurs från parametern _startAngle_ till den andra sidan av pajsektionen. |

### Method: fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle) {#fill_pie_in_rect_f_brush_rect_start_angle_sweep_angle_172}


```
 fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle) 
```

Fyller insidan av ett pajsegment definierat av en ellips specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur och två radiala linjer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som representerar den avgränsande rektangeln som definierar ellipsen varifrån pajsektionen kommer. |
| start_angle | float | Vinkel i grader mätt medurs från x-axeln till den första sidan av pajsektionen. |
| sweep_angle | float | Vinkel i grader mätt medurs från parametern _startAngle_ till den andra sidan av pajsektionen. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_173}


```
 fill_polygon(brush, points) 
```

Fyller insidan av en polygon definierad av en array av punkter specificerade av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer och [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som representerar polygonens hörn som ska fyllas. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_174}


```
 fill_polygon(brush, points) 
```

Fyller insidan av en polygon definierad av en array av punkter specificerade av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer och [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som representerar polygonens hörn som ska fyllas. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_175}


```
 fill_polygon(brush, points, fill_mode) 
```

Fyller insidan av en polygon definierad av en array av punkter specificerade av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med det angivna fyllningsläget.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som representerar polygonens hörn som ska fyllas. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Medlem av [FillMode](/imaging/python-net/aspose.imaging/fillmode/)‑enumerationen som bestämmer fyllningsstilen. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_176}


```
 fill_polygon(brush, points, fill_mode) 
```

Fyller insidan av en polygon definierad av en array av punkter specificerade av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med det angivna fyllningsläget.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som representerar polygonens hörn som ska fyllas. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Medlem av [FillMode](/imaging/python-net/aspose.imaging/fillmode/)‑enumerationen som bestämmer fyllningsstilen. |

### Method: fill_polygon_by_point(brush, points) {#fill_polygon_by_point_brush_points_177}


```
 fill_polygon_by_point(brush, points) 
```

Fyller insidan av en polygon definierad av en array av punkter specificerade av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer och [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som representerar polygonens hörn som ska fyllas. |

### Method: fill_polygon_by_point_f(brush, points) {#fill_polygon_by_point_f_brush_points_178}


```
 fill_polygon_by_point_f(brush, points) 
```

Fyller insidan av en polygon definierad av en array av punkter specificerade av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer och [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som representerar polygonens hörn som ska fyllas. |

### Method: fill_polygon_by_point_f_fill_mode(brush, points, fill_mode) {#fill_polygon_by_point_f_fill_mode_brush_points_fill_mode_179}


```
 fill_polygon_by_point_f_fill_mode(brush, points, fill_mode) 
```

Fyller insidan av en polygon definierad av en array av punkter specificerade av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer med det angivna fyllningsläget.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array av [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som representerar polygonens hörn som ska fyllas. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Medlem av [FillMode](/imaging/python-net/aspose.imaging/fillmode/)‑enumerationen som bestämmer fyllningsstilen. |

### Method: fill_polygon_by_point_fill_mode(brush, points, fill_mode) {#fill_polygon_by_point_fill_mode_brush_points_fill_mode_180}


```
 fill_polygon_by_point_fill_mode(brush, points, fill_mode) 
```

Fyller insidan av en polygon definierad av en array av punkter specificerade av [Point](/imaging/python-net/aspose.imaging/point/) strukturer med det angivna fyllningsläget.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array av [Point](/imaging/python-net/aspose.imaging/point/) strukturer som representerar polygonens hörn som ska fyllas. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Medlem av [FillMode](/imaging/python-net/aspose.imaging/fillmode/)‑enumerationen som bestämmer fyllningsstilen. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_181}


```
 fill_rectangle(brush, rect) 
```

Fyller insidan av en rektangel specificerad av en [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur som representerar rektangeln som ska fyllas. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_182}


```
 fill_rectangle(brush, rect) 
```

Fyller insidan av en rektangel specificerad av en [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struktur som representerar rektangeln som ska fyllas. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_183}


```
 fill_rectangle(brush, x, y, width, height) 
```

Fyller insidan av en rektangel specificerad av ett par koordinater, en bredd och en höjd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| x | float | X‑koordinaten för det övre vänstra hörnet av rektangeln som ska fyllas. |
| y | float | Y‑koordinaten för det övre vänstra hörnet av rektangeln som ska fyllas. |
| width | float | Bredden på rektangeln som ska fyllas. |
| height | float | Höjden på rektangeln som ska fyllas. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_184}


```
 fill_rectangle(brush, x, y, width, height) 
```

Fyller insidan av en rektangel specificerad av ett par koordinater, en bredd och en höjd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| x | int | X‑koordinaten för det övre vänstra hörnet av rektangeln som ska fyllas. |
| y | int | Y‑koordinaten för det övre vänstra hörnet av rektangeln som ska fyllas. |
| width | int | Bredden på rektangeln som ska fyllas. |
| height | int | Höjden på rektangeln som ska fyllas. |

### Method: fill_rectangle_f(brush, rect) {#fill_rectangle_f_brush_rect_185}


```
 fill_rectangle_f(brush, rect) 
```

Fyller insidan av en rektangel specificerad av en [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som representerar rektangeln som ska fyllas. |

### Method: fill_rectangle_f_with_brush(brush, x, y, width, height) {#fill_rectangle_f_with_brush_brush_x_y_width_height_186}


```
 fill_rectangle_f_with_brush(brush, x, y, width, height) 
```

Fyller insidan av en rektangel specificerad av ett par koordinater, en bredd och en höjd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| x | float | X‑koordinaten för det övre vänstra hörnet av rektangeln som ska fyllas. |
| y | float | Y‑koordinaten för det övre vänstra hörnet av rektangeln som ska fyllas. |
| width | float | Bredden på rektangeln som ska fyllas. |
| height | float | Höjden på rektangeln som ska fyllas. |

### Method: fill_rectangle_with_brush(brush, x, y, width, height) {#fill_rectangle_with_brush_brush_x_y_width_height_187}


```
 fill_rectangle_with_brush(brush, x, y, width, height) 
```

Fyller insidan av en rektangel specificerad av ett par koordinater, en bredd och en höjd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| x | int | X‑koordinaten för det övre vänstra hörnet av rektangeln som ska fyllas. |
| y | int | Y‑koordinaten för det övre vänstra hörnet av rektangeln som ska fyllas. |
| width | int | Bredden på rektangeln som ska fyllas. |
| height | int | Höjden på rektangeln som ska fyllas. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_188}


```
 fill_rectangles(brush, rects) 
```

Fyller insidan av en serie rektanglar specificerade av [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| rects | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | Array av [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) strukturer som representerar rektanglarna som ska fyllas. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_189}


```
 fill_rectangles(brush, rects) 
```

Fyller insidan av en serie rektanglar specificerade av [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Array av [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) strukturer som representerar rektanglarna som ska fyllas. |

### Method: fill_rectangles_f(brush, rects) {#fill_rectangles_f_brush_rects_190}


```
 fill_rectangles_f(brush, rects) 
```

Fyller insidan av en serie rektanglar specificerade av [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Array av [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) strukturer som representerar rektanglarna som ska fyllas. |

### Method: fill_region(brush, region) {#fill_region_brush_region_191}


```
 fill_region(brush, region) 
```

Fyller i insidan av en [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) som bestämmer fyllningens egenskaper. |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | [Region](/imaging/python-net/aspose.imaging/region/) som representerar området som ska fyllas. |

### Method: measure_string(text, font, layout_area, string_format) {#measure_string_text_font_layout_area_string_format_192}


```
 measure_string(text, font, layout_area, string_format) 
```

Mäter den angivna textsträngen med angivna parametrar

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| text | string | Texten att mäta. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Typsnittet att mäta. |
| layout_area | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Layoutområdet. |
| string_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Strängformatet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Storlek i pixlar för den uppmätta textsträngen |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_193}


```
 multiply_transform(matrix) 
```

Multiplicerar [Matrix](/imaging/python-net/aspose.imaging/matrix/) som representerar den lokala geometriska transformen för denna [Graphics](/imaging/python-net/aspose.imaging/graphics/) med den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/) genom att föregå den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Den [Matrix](/imaging/python-net/aspose.imaging/matrix/) som ska multipliceras med den geometriska transformen. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_194}


```
 multiply_transform(matrix, order) 
```

Multiplicerar [Matrix](/imaging/python-net/aspose.imaging/matrix/) som representerar den lokala geometriska transformen för denna [Graphics](/imaging/python-net/aspose.imaging/graphics/) med den angivna [Matrix](/imaging/python-net/aspose.imaging/matrix/) i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Den [Matrix](/imaging/python-net/aspose.imaging/matrix/) som ska multipliceras med den geometriska transformen. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | En [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) som specificerar i vilken ordning de två matriserna ska multipliceras. |

### Method: rotate_transform(angle) {#rotate_transform_angle_195}


```
 rotate_transform(angle) 
```

Rotera den lokala geometriska transformen med den angivna mängden. Denna metod lägger till rotationen i början av transformen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_196}


```
 rotate_transform(angle, order) 
```

Rotera den lokala geometriska transformen med den angivna mängden i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | En [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) som specificerar om rotationsmatrisen ska läggas till i slutet eller i början. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_197}


```
 scale_transform(sx, sy) 
```

Skalar den lokala geometriska transformen med de angivna värdena. Denna metod lägger till skalningsmatrisen i början av transformen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sx | float | Mängden att skala transformen i x‑axelns riktning. |
| sy | float | Mängden att skala transformen i y‑axelns riktning. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_198}


```
 scale_transform(sx, sy, order) 
```

Skalar den lokala geometriska transformen med de angivna värdena i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sx | float | Mängden att skala transformen i x‑axelns riktning. |
| sy | float | Mängden att skala transformen i y‑axelns riktning. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | En [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) som anger om skalningsmatrisen ska läggas till eller föregås. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_199}


```
 translate_transform(dx, dy) 
```

Översätter den lokala geometriska transformen med de angivna dimensionerna. Denna metod lägger till översättningen i början av transformen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dx | float | Värdet för translationen i x. |
| dy | float | Värdet för translationen i y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_200}


```
 translate_transform(dx, dy, order) 
```

Översätter den lokala geometriska transformen med de angivna dimensionerna i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dx | float | Värdet för translationen i x. |
| dy | float | Värdet för translationen i y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Ordningen (före eller efter) i vilken translationen ska tillämpas. |

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

#Skapar en instans av filström
with open(r"C:\temp\output.png", "w+b") as stream:
	#Skapa en instans av PngOptions och ange dess olika egenskaper
	pngOptions = PngOptions()
	#Ange källan för PngOptions
	pngOptions.source = StreamSource(stream)
	#Skapa en instans av Image
	with Image.create(pngOptions, 500, 500) as image:
		#Skapa och initiera en instans av Graphics-klassen
		graphics = Graphics(image)
		#Rensa Graphics-ytan
		graphics.clear(Color.wheat);
		#Rita en båge genom att ange Pen-objektet med svart färg, 
		#en rektangel som omger bågen, startvinkel och svepvinkel
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#Rita en Bezier genom att ange Pen-objektet med blå färg och koordinatpunkter.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#Rita en kurva genom att specificera Pen-objektet med grön färg och en array av punkter
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#Rita en ellips med Pen-objektet och en omgivande Rectangle
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#Rita en linje
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#Rita ett pajsegment
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#Rita en polygon genom att specificera Pen-objektet med röd färg och en array av punkter
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#Rita en Rectangle
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#Skapa ett SolidBrush-objekt och sätt dess olika egenskaper
		brush = SolidBrush()
		brush.color = Color.purple
		#Rita en String med SolidBrush-objektet och Font, vid en specifik Point
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# spara alla ändringar.
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


# Skapa en instans av en filström
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# Skapa en instans av TiffOptions och ställ in dess olika egenskaper
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Ange källan för instansen av ImageOptions
	tiffOptions.source = StreamSource(stream)
	# Skapa en instans av Image
	with Image.create(tiffOptions, 500, 500) as image:
		# Skapa och initiera en instans av Graphics-klassen
		graphics = Graphics(image)
		# Rensa Graphics-ytan
		graphics.clear(Color.wheat);
		# Skapa en instans av klassen GraphicsPath
		graphics_path = GraphicsPath()
		# Skapa en instans av klassen Figure
		figure = Figure()
		# Lägg till former till Figure-objektet
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# Lägg till Figure-objektet till GraphicsPath
		graphics_path.add_figure(figure)
		# Rita bana med Pen-objektet i färgen svart
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# spara alla ändringar.
		image.save()


```

### This example shows the creation and usage Pen objects. The example creates a new Image and draw rectangles on the Image surface. {#example_14}
``` python

from aspose.imaging import Image, Graphics, Color, Pen, Rectangle, Point, Size
from aspose.imaging.brushes import HatchBrush
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

# Skapa en instans av BmpOptions och sätt dess olika egenskaper
bmpOptions = BmpOptions()
bmpOptions.bits_per_pixel = 24
# Skapa en instans av FileCreateSource och tilldela den som källa för instansen av BmpOptions
# Den andra booleska parametern bestämmer om filen som ska skapas är temporär eller inte
bmpOptions.source = FileCreateSource(r"C:\temp\sample.bmp", False)
# Skapa en instans av Image på angiven sökväg
with Image.create(bmpOptions, 500, 500) as image:
	# Skapa en instans av Graphics och initiera den med Image‑objektet
	graphics = Graphics(image)
	# Rensa Graphics‑ytan med vit färg
	graphics.clear(Color.white)
	#Skapa en instans av Pen med färgen röd och bredd 5
	pen = Pen(Color.red, 5.0);
	# Skapa en instans av HatchBrush och sätt dess egenskaper
	brush = HatchBrush()
	brush.background_color = Color.wheat;
	brush.foreground_color = Color.red;
	# Skapa en instans av Pen
	# initiera den med HatchBrush-objekt och bredd
	brusedpen = Pen(brush, 5.0)
	# Rita rektanglar genom att ange Pen-objekt
	graphics.draw_rectangles(pen, [
		Rectangle(Point(210, 210), Size(100, 100)),
		Rectangle(Point(110, 110), Size(100, 100)),
		Rectangle(Point(310, 310), Size(100, 100)) ])

	# Rita rektanglar genom att ange Pen-objekt
	graphics.draw_rectangles(brusedpen, [
		Rectangle(Point(310, 110), Size(100, 100)),
		Rectangle(Point(110, 310), Size(100, 100)) ])

	# spara alla ändringar.
	image.save()


```

### The following example shows how to compose an animated GIF image from individual GIF blocks. {#example_95}
``` python
from aspose.imaging.fileformats.gif.blocks import GifFrameBlock
from aspose.imaging.fileformats.gif import GifImage 
from aspose.imaging.brushes import SolidBrush
from aspose.imaging import Graphics, Color

# Skapa en GIF-bild 100 x 100 px.
# Det första blocket är helt svart som standard.
with GifFrameBlock(100, 100) as firstBlock:
	with GifImage(firstBlock) as gifImage:
		# Den första cirkeln är röd
		brush1 = SolidBrush(Color.red)

		# Den andra cirkeln är svart
		brush2 = SolidBrush(Color.black)

		# Öka gradvis vinkeln på den röda bågformen.
		for angle in range(10, 361, 10):
			block = GifFrameBlock(100, 100)
			gr = Graphics(block)
			gr.fill_pie(brush1, block.bounds, 0, angle)
			gifImage.add_block(block)
		
		# Öka gradvis vinkeln på den svarta bågen och radera den röda bågen.
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
# Skapa en PNG-bild på 100x100 px.
with PngImage(100, 100) as png_image:
	# Utför någon bildbehandling, t.ex. fyll hela bilden med rött.
	graphics = Graphics(png_image)
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, png_image.bounds)
	# Spara till en fil.
	png_image.save(join(dir_, "output.png"))


```

