---
title: "Graphics Klasse"
type: docs
weight: 5030
url: /de/python-net/aspose.imaging/graphics/
---

**Summary:** Represents the graphics according to the graphics engine used in the current assembly.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Graphics

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Graphics(source_image)](#Graphics_source_image_1) | Initialisiert eine neue Instanz der [Graphics](/imaging/python-net/aspose.imaging/graphics/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| clip | [Region](/imaging/python-net/aspose.imaging/region/) | r/w | Liest oder setzt den Clip-Bereich. |
| compositing_quality | [CompositingQuality](/imaging/python-net/aspose.imaging/compositingquality/) | r/w | Liest oder setzt die Kompositierungsqualität. |
| dpi_x | float | r | Gibt die horizontale Auflösung dieses `aspose.imaging.Graphics` zurück. |
| dpi_y | float | r | Gibt die vertikale Auflösung dieses `aspose.imaging.Graphics` zurück. |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | r | Liest das Bild. |
| interpolation_mode | [InterpolationMode](/imaging/python-net/aspose.imaging/interpolationmode/) | r/w | Liest oder setzt den Interpolationsmodus. |
| is_in_begin_update_call | bool | r | Gibt einen Wert zurück, der angibt, ob die Grafik sich im BeginUpdate‑Aufrufzustand befindet. |
| page_scale | float | r/w | Liest oder setzt die Skalierung zwischen Welteinheiten und Seiteneinheiten für dieses `aspose.imaging.Graphics`. |
| page_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | r/w | Liest oder setzt die Maßeinheit, die für Seitenkoordinaten in diesem `aspose.imaging.Graphics` verwendet wird. |
| paintable_image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | r/w | Liest oder setzt Bildoptionen, die zum Erstellen von malbaren Vektor‑Bildern zum Zeichnen verwendet werden. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Liest oder setzt den Glättungsmodus. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Liest oder setzt den Hinweis zur Textdarstellung. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Liest oder setzt eine Kopie der geometrischen Welttransformation für dieses [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| begin_update() | Startet das Zwischenspeichern der folgenden Grafikoperationen. Die danach angewendeten Grafikeffekte werden nicht sofort angewendet, stattdessen sorgt EndUpdate dafür, dass alle Effekte auf einmal angewendet werden. |
| [clear(color)](#clear_color_1) | Löscht die Grafikfläche mit der angegebenen Farbe. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_2) | Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)‑Struktur angegeben ist. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_3) | Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)‑Struktur angegeben ist. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4) | Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5) | Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist. |
| [draw_arc_in_rect(pen, rect, start_angle, sweep_angle)](#draw_arc_in_rect_pen_rect_start_angle_sweep_angle_6) | Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)‑Struktur angegeben ist. |
| [draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle)](#draw_arc_in_rect_f_pen_rect_start_angle_sweep_angle_7) | Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)‑Struktur angegeben ist. |
| [draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_xy_pen_x_y_width_height_start_angle_sweep_angle_8) | Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist. |
| [draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_xyf_pen_x_y_width_height_start_angle_sweep_angle_9) | Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_10) | Zeichnet eine Bézier‑Kurve, definiert durch vier [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_11) | Zeichnet eine Bézier‑Kurve, definiert durch vier [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen. |
| [draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4)](#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_12) | Zeichnet eine Bézier‑Kurve, definiert durch vier geordnete Koordinatenpaare, die Punkte darstellen. |
| [draw_bezier_by_points(pen, pt1, pt2, pt3, pt4)](#draw_bezier_by_points_pen_pt1_pt2_pt3_pt4_13) | Zeichnet eine Bézier‑Kurve, definiert durch vier [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen. |
| [draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4)](#draw_bezier_by_points_f_pen_pt1_pt2_pt3_pt4_14) | Zeichnet eine Bézier‑Kurve, definiert durch vier [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen. |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_15) | Zeichnet eine Reihe von Bézier‑Kurven aus einem Array von [Point](/imaging/python-net/aspose.imaging/point/)‑Strukturen. |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_16) | Zeichnet eine Reihe von Bézier‑Kurven aus einem Array von [Point](/imaging/python-net/aspose.imaging/point/)‑Strukturen. |
| [draw_beziers_by_pt_array(pen, points)](#draw_beziers_by_pt_array_pen_points_17) | Zeichnet eine Reihe von Bézier‑Kurven aus einem Array von [Point](/imaging/python-net/aspose.imaging/point/)‑Strukturen. |
| [draw_beziers_by_pt_array_f(pen, points)](#draw_beziers_by_pt_array_f_pen_points_18) | Zeichnet eine Reihe von Bézier‑Kurven aus einem Array von [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen. |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_19) | Zeichnet eine geschlossene Kardinal‑Spline, definiert durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen. Diese Methode verwendet eine Standardspannung von 0,5 und den Füllmodus [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_20) | Zeichnet eine geschlossene Kardinal‑Spline, definiert durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen. Diese Methode verwendet eine Standardspannung von 0,5 und den Füllmodus [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_21) | Zeichnet eine geschlossene Kardinal‑Spline, definiert durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen unter Verwendung einer angegebenen Spannung. Diese Methode verwendet den Standard‑Füllmodus [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_22) | Zeichnet eine geschlossene Kardinal‑Spline, definiert durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen unter Verwendung einer angegebenen Spannung. Diese Methode verwendet den Standard‑Füllmodus [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve_by_points(pen, points)](#draw_closed_curve_by_points_pen_points_23) | Zeichnet eine geschlossene Kardinal‑Spline, definiert durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen. Diese Methode verwendet eine Standardspannung von 0,5 und den Füllmodus [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve_by_points_f(pen, points)](#draw_closed_curve_by_points_f_pen_points_24) | Zeichnet eine geschlossene Kardinal‑Spline, definiert durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen. Diese Methode verwendet eine Standardspannung von 0,5 und den Füllmodus [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve_by_points_f_tension(pen, points, tension)](#draw_closed_curve_by_points_f_tension_pen_points_tension_25) | Zeichnet eine geschlossene Kardinal‑Spline, definiert durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen unter Verwendung einer angegebenen Spannung. Diese Methode verwendet den Standard‑Füllmodus [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve_by_points_tension(pen, points, tension)](#draw_closed_curve_by_points_tension_pen_points_tension_26) | Zeichnet eine geschlossene Kardinal‑Spline, definiert durch ein Array von [Point](/imaging/python-net/aspose.imaging/point/)‑Strukturen unter Verwendung einer angegebenen Spannung. Diese Methode verwendet den Standard‑Füllmodus [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_curve(pen, points)](#draw_curve_pen_points_27) | Zeichnet eine Kardinal‑Spline durch ein angegebenes Array von [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen. Diese Methode verwendet eine Standardspannung von 0,5. |
| [draw_curve(pen, points)](#draw_curve_pen_points_28) | Zeichnet eine Kardinal‑Spline durch ein angegebenes Array von [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen. Diese Methode verwendet eine Standardspannung von 0,5. |
| [draw_curve(pen, points, offset, number_of_segments)](#draw_curve_pen_points_offset_number_of_segments_29) | Zeichnet eine kardinale Spline durch ein angegebenes Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen. Die Zeichnung beginnt versetzt vom Anfang des Arrays.<br/>            Diese Methode verwendet eine Standardspannung von 0,5. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_30) | Zeichnet eine kardinale Spline durch ein angegebenes Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen unter Verwendung einer angegebenen Spannung. Die Zeichnung beginnt versetzt vom Anfang des Arrays. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_31) | Zeichnet eine kardinale Spline durch ein angegebenes Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen unter Verwendung einer angegebenen Spannung. Die Zeichnung beginnt versetzt vom Anfang des Arrays. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_32) | Zeichnet eine kardinale Spline durch ein angegebenes Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen unter Verwendung einer angegebenen Spannung. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_33) | Zeichnet eine kardinale Spline durch ein angegebenes Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen unter Verwendung einer angegebenen Spannung. |
| [draw_curve_by_point_fs(pen, points)](#draw_curve_by_point_fs_pen_points_34) | Zeichnet eine kardinale Spline durch ein angegebenes Array von [Point](/imaging/python-net/aspose.imaging/point/) Strukturen. |
| [draw_curve_by_point_fs_tension(pen, points, tension)](#draw_curve_by_point_fs_tension_pen_points_tension_35) | Zeichnet eine kardinale Spline durch ein angegebenes Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen unter Verwendung einer angegebenen Spannung. |
| [draw_curve_by_points(pen, points)](#draw_curve_by_points_pen_points_36) | Zeichnet eine Kardinal‑Spline durch ein angegebenes Array von [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen. Diese Methode verwendet eine Standardspannung von 0,5. |
| [draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension)](#draw_curve_by_points_f_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_37) | Zeichnet eine kardinale Spline durch ein angegebenes Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen unter Verwendung einer angegebenen Spannung. Die Zeichnung beginnt versetzt vom Anfang des Arrays. |
| [draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension)](#draw_curve_by_points_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_38) | Zeichnet eine kardinale Spline durch ein angegebenes Array von [Point](/imaging/python-net/aspose.imaging/point/) Strukturen unter Verwendung einer angegebenen Spannung. |
| [draw_curve_by_points_tension(pen, points, tension)](#draw_curve_by_points_tension_pen_points_tension_39) | Zeichnet eine kardinale Spline durch ein angegebenes Array von [Point](/imaging/python-net/aspose.imaging/point/) Strukturen unter Verwendung einer angegebenen Spannung. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_40) | Zeichnet eine Ellipse, definiert durch ein begrenzendes [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_41) | Zeichnet eine Ellipse, definiert durch ein begrenzendes [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_42) | Zeichnet eine Ellipse, definiert durch ein begrenzendes Rechteck, das durch ein Koordinatenpaar, eine Höhe und eine Breite angegeben ist. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_43) | Zeichnet eine Ellipse, definiert durch ein begrenzendes Rechteck, das durch ein Koordinatenpaar, eine Höhe und eine Breite angegeben ist. |
| [draw_ellipse_by_xy(pen, x, y, width, height)](#draw_ellipse_by_xy_pen_x_y_width_height_44) | Zeichnet eine Ellipse, definiert durch ein begrenzendes Rechteck, das durch ein Koordinatenpaar, eine Höhe und eine Breite angegeben ist. |
| [draw_ellipse_by_xyf(pen, x, y, width, height)](#draw_ellipse_by_xyf_pen_x_y_width_height_45) | Zeichnet eine Ellipse, definiert durch ein begrenzendes Rechteck, das durch ein Koordinatenpaar, eine Höhe und eine Breite angegeben ist. |
| [draw_ellipse_f(pen, rect)](#draw_ellipse_f_pen_rect_46) | Zeichnet eine Ellipse, definiert durch ein begrenzendes [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_47) | Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_48) | Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_49) | Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_50) | Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_51) | Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_52) | Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_53) | Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_54) | Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image(source_image, point)](#draw_image_source_image_point_55) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), unter Verwendung seiner ursprünglichen physischen Größe, am angegebenen Ort. |
| [draw_image(source_image, point)](#draw_image_source_image_point_56) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), unter Verwendung seiner ursprünglichen physischen Größe, am angegebenen Ort. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_57) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_58) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_59) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_60) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_61) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_62) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_63) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_64) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_65) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_66) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_67) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), unter Verwendung seiner ursprünglichen physischen Größe, am angegebenen Ort. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_68) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), unter Verwendung seiner ursprünglichen physischen Größe, am angegebenen Ort. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_69) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_70) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image_at_point(source_image, point)](#draw_image_at_point_source_image_point_71) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), unter Verwendung seiner ursprünglichen physischen Größe, am angegebenen Ort. |
| [draw_image_at_point_f(source_image, point)](#draw_image_at_point_f_source_image_point_72) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), unter Verwendung seiner ursprünglichen physischen Größe, am angegebenen Ort. |
| [draw_image_at_xy(source_image, x, y)](#draw_image_at_xy_source_image_x_y_73) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), unter Verwendung seiner ursprünglichen physischen Größe, am angegebenen Ort. |
| [draw_image_at_xyf(source_image, x, y)](#draw_image_at_xyf_source_image_x_y_74) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), unter Verwendung seiner ursprünglichen physischen Größe, am angegebenen Ort. |
| [draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit)](#draw_image_dest_point_f_src_rect_f_with_unit_image_dest_points_src_rect_src_unit_75) | Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_dest_point_f_src_rect_f_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_76) | Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect)](#draw_image_dest_points_f_src_rect_f_image_dest_points_src_rect_77) | Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image_dest_points_src_rect(image, dest_points, src_rect)](#draw_image_dest_points_src_rect_image_dest_points_src_rect_78) | Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit)](#draw_image_dest_points_src_rect_with_unit_image_dest_points_src_rect_src_unit_79) | Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_dest_points_src_rect_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_80) | Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_dest_rect_f_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_81) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_dest_rect_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_82) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image_in_rect(source_image, x, y, width, height)](#draw_image_in_rect_source_image_x_y_width_height_83) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image_in_rect_f(source_image, x, y, width, height)](#draw_image_in_rect_f_source_image_x_y_width_height_84) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image_in_rectangle(source_image, rect)](#draw_image_in_rectangle_source_image_rect_85) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image_points(image, dest_points)](#draw_image_points_image_dest_points_86) | Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image_points_f(image, dest_points)](#draw_image_points_f_image_dest_points_87) | Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image_rectangle_f(source_image, rect)](#draw_image_rectangle_f_source_image_rect_88) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_src_dest_rects_f_with_unit_source_image_rect_source_rect_destination_graphics_unit_89) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_src_dest_rects_with_unit_source_image_rect_source_rect_destination_graphics_unit_90) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_src_dst_rect_f_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_91) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_src_dst_rects_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_92) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit)](#draw_image_to_rect_f_with_unit_source_image_rect_destination_graphics_unit_93) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit)](#draw_image_to_rect_with_unit_source_image_rect_destination_graphics_unit_94) | Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe. |
| [draw_image_unscaled(source_image, point)](#draw_image_unscaled_source_image_point_95) | Zeichnet ein angegebenes Bild unter Verwendung seiner ursprünglichen physischen Größe an einem angegebenen Ort. |
| [draw_image_unscaled(source_image, rect)](#draw_image_unscaled_source_image_rect_96) | Zeichnet ein angegebenes Bild unter Verwendung seiner ursprünglichen physischen Größe an einem angegebenen Ort. |
| [draw_image_unscaled(source_image, x, y)](#draw_image_unscaled_source_image_x_y_97) | Zeichnet das angegebene Bild unter Verwendung seiner ursprünglichen physischen Größe an dem Ort, der durch ein Koordinatenpaar angegeben ist. |
| [draw_image_unscaled(source_image, x, y, width, height)](#draw_image_unscaled_source_image_x_y_width_height_98) | Zeichnet ein angegebenes Bild unter Verwendung seiner ursprünglichen physischen Größe an einem angegebenen Ort. |
| [draw_image_unscaled_and_clipped(source_image, rect)](#draw_image_unscaled_and_clipped_source_image_rect_99) | Zeichnet das angegebene Bild ohne Skalierung und schneidet es, falls nötig, zu, um in das angegebene Rechteck zu passen. |
| [draw_image_unscaled_in_rectangle(source_image, rect)](#draw_image_unscaled_in_rectangle_source_image_rect_100) | Zeichnet ein angegebenes Bild unter Verwendung seiner ursprünglichen physischen Größe an einem angegebenen Ort. |
| [draw_image_unscaled_to_point(source_image, point)](#draw_image_unscaled_to_point_source_image_point_101) | Zeichnet ein angegebenes Bild unter Verwendung seiner ursprünglichen physischen Größe an einem angegebenen Ort. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_102) | Zeichnet eine Linie, die zwei [Point](/imaging/python-net/aspose.imaging/point/) Strukturen verbindet. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_103) | Zeichnet eine Linie, die zwei [Point](/imaging/python-net/aspose.imaging/point/) Strukturen verbindet. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_104) | Zeichnet eine Linie, die die beiden durch Koordinatenpaare angegebenen Punkte verbindet. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_105) | Zeichnet eine Linie, die die beiden durch Koordinatenpaare angegebenen Punkte verbindet. |
| [draw_line_by_xy(pen, x1, y1, x2, y2)](#draw_line_by_xy_pen_x1_y1_x2_y2_106) | Zeichnet eine Linie, die die beiden durch Koordinatenpaare angegebenen Punkte verbindet. |
| [draw_line_f_by_xy(pen, x1, y1, x2, y2)](#draw_line_f_by_xy_pen_x1_y1_x2_y2_107) | Zeichnet eine Linie, die die beiden durch Koordinatenpaare angegebenen Punkte verbindet. |
| [draw_line_point_f(pen, point1, point2)](#draw_line_point_f_pen_point1_point2_108) | Zeichnet eine Linie, die zwei [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen verbindet. |
| [draw_lines(pen, points)](#draw_lines_pen_points_109) | Zeichnet eine Reihe von Liniensegmenten, die ein Array von [Point](/imaging/python-net/aspose.imaging/point/) Strukturen verbinden. |
| [draw_lines(pen, points)](#draw_lines_pen_points_110) | Zeichnet eine Reihe von Liniensegmenten, die ein Array von [Point](/imaging/python-net/aspose.imaging/point/) Strukturen verbinden. |
| [draw_lines_f(pen, points)](#draw_lines_f_pen_points_111) | Zeichnet eine Reihe von Liniensegmenten, die ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen verbinden. |
| [draw_path(pen, path)](#draw_path_pen_path_112) | Zeichnet einen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_113) | Zeichnet eine Tortenform, definiert durch eine Ellipse, die durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur und zwei Radiallinien angegeben ist. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_114) | Zeichnet eine Tortenform, definiert durch eine Ellipse, die durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur und zwei Radiallinien angegeben ist. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_115) | Zeichnet eine Tortenform, definiert durch eine Ellipse, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien angegeben ist. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_116) | Zeichnet eine Tortenform, definiert durch eine Ellipse, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien angegeben ist. |
| [draw_pie_in_rect(pen, rect, start_angle, sweep_angle)](#draw_pie_in_rect_pen_rect_start_angle_sweep_angle_117) | Zeichnet eine Tortenform, definiert durch eine Ellipse, die durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur und zwei Radiallinien angegeben ist. |
| [draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle)](#draw_pie_in_rect_f_pen_rect_start_angle_sweep_angle_118) | Zeichnet eine Tortenform, definiert durch eine Ellipse, die durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur und zwei Radiallinien angegeben ist. |
| [draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_xy_pen_x_y_width_height_start_angle_sweep_angle_119) | Zeichnet eine Tortenform, definiert durch eine Ellipse, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien angegeben ist. |
| [draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_xyf_pen_x_y_width_height_start_angle_sweep_angle_120) | Zeichnet eine Tortenform, definiert durch eine Ellipse, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien angegeben ist. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_121) | Zeichnet ein Polygon, definiert durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_122) | Zeichnet ein Polygon, definiert durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen. |
| [draw_polygon_f(pen, points)](#draw_polygon_f_pen_points_123) | Zeichnet ein Polygon, definiert durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen. |
| [draw_rect(pen, x, y, width, height)](#draw_rect_pen_x_y_width_height_124) | Zeichnet ein Rechteck, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist. |
| [draw_rect_f(pen, x, y, width, height)](#draw_rect_f_pen_x_y_width_height_125) | Zeichnet ein Rechteck, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist. |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_126) | Zeichnet ein Rechteck, das durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur angegeben ist. |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_127) | Zeichnet ein Rechteck, das durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur angegeben ist. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_128) | Zeichnet ein Rechteck, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_129) | Zeichnet ein Rechteck, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist. |
| [draw_rectangle_f(pen, rect)](#draw_rectangle_f_pen_rect_130) | Zeichnet ein Rechteck, das durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur angegeben ist. |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_131) | Zeichnet eine Reihe von Rechtecken, die durch [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Strukturen angegeben sind. |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_132) | Zeichnet eine Reihe von Rechtecken, die durch [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Strukturen angegeben sind. |
| [draw_rectangles_f(pen, rects)](#draw_rectangles_f_pen_rects_133) | Zeichnet eine Reihe von Rechtecken, die durch [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Strukturen angegeben sind. |
| [draw_string(s, font, brush, layout_rectangle)](#draw_string_s_font_brush_layout_rectangle_134) | Zeichnet die angegebene Textzeichenfolge im angegebenen Rechteck mit den angegebenen [Brush](/imaging/python-net/aspose.imaging/brush/) und [Font](/imaging/python-net/aspose.imaging/font/) Objekten. |
| [draw_string(s, font, brush, layout_rectangle, format)](#draw_string_s_font_brush_layout_rectangle_format_135) | Zeichnet die angegebene Textzeichenfolge im angegebenen Rechteck mit den angegebenen [Brush](/imaging/python-net/aspose.imaging/brush/) und [Font](/imaging/python-net/aspose.imaging/font/) Objekten unter Verwendung der Formatattribute des angegebenen [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [draw_string(s, font, brush, point)](#draw_string_s_font_brush_point_136) | Zeichnet die angegebene Textzeichenfolge an der angegebenen Position mit den angegebenen [Brush](/imaging/python-net/aspose.imaging/brush/) und [Font](/imaging/python-net/aspose.imaging/font/) Objekten. |
| [draw_string(s, font, brush, point, format)](#draw_string_s_font_brush_point_format_137) | Zeichnet die angegebene Textzeichenfolge an der angegebenen Position mit den angegebenen [Brush](/imaging/python-net/aspose.imaging/brush/) und [Font](/imaging/python-net/aspose.imaging/font/) Objekten unter Verwendung der Formatattribute des angegebenen [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [draw_string(s, font, brush, x, y)](#draw_string_s_font_brush_x_y_138) | Zeichnet die angegebene Textzeichenfolge an der angegebenen Position mit den angegebenen [Brush](/imaging/python-net/aspose.imaging/brush/) und [Font](/imaging/python-net/aspose.imaging/font/) Objekten. |
| [draw_string(s, font, brush, x, y, format)](#draw_string_s_font_brush_x_y_format_139) | Zeichnet die angegebene Textzeichenfolge an der angegebenen Position mit den angegebenen [Brush](/imaging/python-net/aspose.imaging/brush/) und [Font](/imaging/python-net/aspose.imaging/font/) Objekten unter Verwendung der Formatattribute des angegebenen [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [draw_string_at_point_f(s, font, brush, point)](#draw_string_at_point_f_s_font_brush_point_140) | Zeichnet die angegebene Textzeichenfolge an der angegebenen Position mit den angegebenen [Brush](/imaging/python-net/aspose.imaging/brush/) und [Font](/imaging/python-net/aspose.imaging/font/) Objekten. |
| [draw_string_at_point_f_format(s, font, brush, point, format)](#draw_string_at_point_f_format_s_font_brush_point_format_141) | Zeichnet die angegebene Textzeichenfolge an der angegebenen Position mit den angegebenen [Brush](/imaging/python-net/aspose.imaging/brush/) und [Font](/imaging/python-net/aspose.imaging/font/) Objekten unter Verwendung der Formatattribute des angegebenen [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| [draw_string_at_xy(s, font, brush, x, y)](#draw_string_at_xy_s_font_brush_x_y_142) | Zeichnet die angegebene Textzeichenfolge an der angegebenen Position mit den angegebenen [Brush](/imaging/python-net/aspose.imaging/brush/) und [Font](/imaging/python-net/aspose.imaging/font/) Objekten. |
| [draw_string_in_rect(s, font, brush, layout_rectangle)](#draw_string_in_rect_s_font_brush_layout_rectangle_143) | Zeichnet die angegebene Textzeichenfolge im angegebenen Rechteck mit den angegebenen [Brush](/imaging/python-net/aspose.imaging/brush/) und [Font](/imaging/python-net/aspose.imaging/font/) Objekten. |
| [draw_string_in_rect_f(s, font, brush, layout_rectangle, format)](#draw_string_in_rect_f_s_font_brush_layout_rectangle_format_144) | Zeichnet die angegebene Textzeichenfolge im angegebenen Rechteck mit den angegebenen [Brush](/imaging/python-net/aspose.imaging/brush/) und [Font](/imaging/python-net/aspose.imaging/font/) Objekten unter Verwendung der Formatattribute des angegebenen [StringFormat](/imaging/python-net/aspose.imaging/stringformat/). |
| end_update() | Beendet das Zwischenspeichern der Grafikoperationen, die nach dem Aufruf von BeginUpdate gestartet wurden. Die vorherigen Grafikoperationen werden sofort angewendet, wenn diese Methode aufgerufen wird. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_145) | Füllt das Innere einer geschlossenen Kardinal‑Spline‑Kurve, die durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen definiert ist. Diese Methode verwendet eine Standardspannung von 0.5 und den [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) Füllmodus. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_146) | Füllt das Innere einer geschlossenen Kardinal‑Spline‑Kurve, die durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen definiert ist. Diese Methode verwendet eine Standardspannung von 0.5 und den [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) Füllmodus. |
| [fill_closed_curve(brush, points, fill_mode)](#fill_closed_curve_brush_points_fill_mode_147) | Füllt das Innere einer geschlossenen Kardinal‑Spline‑Kurve, die durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus. Diese Methode verwendet eine Standardspannung von 0.5. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_148) | Füllt das Innere einer geschlossenen Kardinal‑Spline‑Kurve, die durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus. Diese Methode verwendet eine Standardspannung von 0.5. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_149) | Füllt das Innere einer geschlossenen Kardinal‑Spline‑Kurve, die durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus und der Spannung. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_150) | Füllt das Innere einer geschlossenen Kardinal‑Spline‑Kurve, die durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus und der Spannung. |
| [fill_closed_curve_by_point(brush, points)](#fill_closed_curve_by_point_brush_points_151) | Füllt das Innere einer geschlossenen Kardinal‑Spline‑Kurve, die durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen definiert ist. Diese Methode verwendet eine Standardspannung von 0.5 und den [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) Füllmodus. |
| [fill_closed_curve_by_point_f(brush, points)](#fill_closed_curve_by_point_f_brush_points_152) | Füllt das Innere einer geschlossenen Kardinal‑Spline‑Kurve, die durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen definiert ist. Diese Methode verwendet eine Standardspannung von 0.5 und den [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) Füllmodus. |
| fill_closed_curve_by_point_f_fill_mode(brush, points, fillmode) |  |
| [fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension)](#fill_closed_curve_by_point_f_fill_mode_tension_brush_points_fillmode_tension_153) | Füllt das Innere einer geschlossenen Kardinal‑Spline‑Kurve, die durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus und der Spannung. |
| [fill_closed_curve_by_point_fill_mode(brush, points, fillmode)](#fill_closed_curve_by_point_fill_mode_brush_points_fillmode_154) | Füllt das Innere einer geschlossenen Kardinal‑Spline‑Kurve, die durch ein Array von [Point](/imaging/python-net/aspose.imaging/point/) Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus. Diese Methode verwendet eine Standardspannung von 0.5. |
| [fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension)](#fill_closed_curve_by_point_fill_mode_tension_brush_points_fillmode_tension_155) | Füllt das Innere einer geschlossenen Kardinal‑Spline‑Kurve, die durch ein Array von [Point](/imaging/python-net/aspose.imaging/point/) Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus und der Spannung. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_156) | Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, angegeben durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_157) | Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, angegeben durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_158) | Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_159) | Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe. |
| [fill_ellipse_at_xywh(brush, x, y, width, height)](#fill_ellipse_at_xywh_brush_x_y_width_height_160) | Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe. |
| [fill_ellipse_at_xywhf(brush, x, y, width, height)](#fill_ellipse_at_xywhf_brush_x_y_width_height_161) | Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe. |
| [fill_ellipse_in_rect(brush, rect)](#fill_ellipse_in_rect_brush_rect_162) | Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, angegeben durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur. |
| [fill_ellipse_in_rect_f(brush, rect)](#fill_ellipse_in_rect_f_brush_rect_163) | Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, angegeben durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur. |
| [fill_path(brush, path)](#fill_path_brush_path_164) | Füllt das Innere eines [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_165) | Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, angegeben durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur und zwei Radiallinien. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_166) | Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, angegeben durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur und zwei Radiallinien. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_167) | Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, angegeben durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_168) | Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, angegeben durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien. |
| [fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_at_xy_brush_x_y_width_height_start_angle_sweep_angle_169) | Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, angegeben durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien. |
| [fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_at_xyf_brush_x_y_width_height_start_angle_sweep_angle_170) | Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, angegeben durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien. |
| [fill_pie_in_rect(brush, rect, start_angle, sweep_angle)](#fill_pie_in_rect_brush_rect_start_angle_sweep_angle_171) | Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, angegeben durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur und zwei Radiallinien. |
| [fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle)](#fill_pie_in_rect_f_brush_rect_start_angle_sweep_angle_172) | Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, angegeben durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur und zwei Radiallinien. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_173) | Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen und den [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) Füllmodus. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_174) | Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen und den [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) Füllmodus. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_175) | Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, unter Verwendung des angegebenen Füllmodus. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_176) | Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, unter Verwendung des angegebenen Füllmodus. |
| [fill_polygon_by_point(brush, points)](#fill_polygon_by_point_brush_points_177) | Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen und den [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) Füllmodus. |
| [fill_polygon_by_point_f(brush, points)](#fill_polygon_by_point_f_brush_points_178) | Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen und den [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) Füllmodus. |
| [fill_polygon_by_point_f_fill_mode(brush, points, fill_mode)](#fill_polygon_by_point_f_fill_mode_brush_points_fill_mode_179) | Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, unter Verwendung des angegebenen Füllmodus. |
| [fill_polygon_by_point_fill_mode(brush, points, fill_mode)](#fill_polygon_by_point_fill_mode_brush_points_fill_mode_180) | Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch [Point](/imaging/python-net/aspose.imaging/point/) Strukturen, unter Verwendung des angegebenen Füllmodus. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_181) | Füllt das Innere eines Rechtecks, angegeben durch eine [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_182) | Füllt das Innere eines Rechtecks, angegeben durch eine [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_183) | Füllt das Innere eines Rechtecks, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_184) | Füllt das Innere eines Rechtecks, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe. |
| [fill_rectangle_f(brush, rect)](#fill_rectangle_f_brush_rect_185) | Füllt das Innere eines Rechtecks, angegeben durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur. |
| [fill_rectangle_f_with_brush(brush, x, y, width, height)](#fill_rectangle_f_with_brush_brush_x_y_width_height_186) | Füllt das Innere eines Rechtecks, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe. |
| [fill_rectangle_with_brush(brush, x, y, width, height)](#fill_rectangle_with_brush_brush_x_y_width_height_187) | Füllt das Innere eines Rechtecks, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_188) | Füllt die Innenbereiche einer Reihe von Rechtecken, angegeben durch [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Strukturen. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_189) | Füllt die Innenbereiche einer Reihe von Rechtecken, angegeben durch [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Strukturen. |
| [fill_rectangles_f(brush, rects)](#fill_rectangles_f_brush_rects_190) | Füllt die Innenbereiche einer Reihe von Rechtecken, angegeben durch [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Strukturen. |
| [fill_region(brush, region)](#fill_region_brush_region_191) | Füllt das Innere einer [Region](/imaging/python-net/aspose.imaging/region/). |
| [measure_string(text, font, layout_area, string_format)](#measure_string_text_font_layout_area_string_format_192) | Misst die angegebene Textzeichenfolge mit den angegebenen Parametern |
| [multiply_transform(matrix)](#multiply_transform_matrix_193) | Multipliziert die [Matrix](/imaging/python-net/aspose.imaging/matrix/), die die lokale geometrische Transformation dieses [Graphics](/imaging/python-net/aspose.imaging/graphics/) darstellt, mit der angegebenen [Matrix](/imaging/python-net/aspose.imaging/matrix/) durch Voranstellen der angegebenen [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_194) | Multipliziert die [Matrix](/imaging/python-net/aspose.imaging/matrix/), die die lokale geometrische Transformation dieses [Graphics](/imaging/python-net/aspose.imaging/graphics/) darstellt, mit der angegebenen [Matrix](/imaging/python-net/aspose.imaging/matrix/) in der angegebenen Reihenfolge. |
| reset_transform() | Setzt die Eigenschaft [Graphics.transform](/imaging/python-net/aspose.imaging/graphics/) auf die Identität zurück. |
| [rotate_transform(angle)](#rotate_transform_angle_195) | Dreht die lokale geometrische Transformation um den angegebenen Betrag. Diese Methode fügt die Rotation der Transformation voran. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_196) | Dreht die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_197) | Skaliert die lokale geometrische Transformation um die angegebenen Werte. Diese Methode fügt die Skalierungs-Matrix der Transformation voran. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_198) | Skaliert die lokale geometrische Transformation um die angegebenen Werte in der angegebenen Reihenfolge. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_199) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. Diese Methode fügt die Translation der Transformation voran. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_200) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |


### Constructor: Graphics(source_image) {#Graphics_source_image_1}


```
 Graphics(source_image) 
```

Initialisiert eine neue Instanz der [Graphics](/imaging/python-net/aspose.imaging/graphics/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Quellbild. |

### Method: clear(color) {#clear_color_1}


```
 clear(color) 
```

Löscht die Grafikfläche mit der angegebenen Farbe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Die Farbe, mit der die Grafikfläche gelöscht wird. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...

**[Example # 2](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_2}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)‑Struktur angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil des Bogens. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die die Grenzen der Ellipse definiert. |
| start_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| sweep_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom _startAngle_-Parameter zum Endpunkt des Bogens. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_3}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)‑Struktur angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil des Bogens. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die die Grenzen der Ellipse definiert. |
| start_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| sweep_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom _startAngle_-Parameter zum Endpunkt des Bogens. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil des Bogens. |
| x | float | Die x-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert. |
| y | float | Die y-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert. |
| width | float | Breite des Rechtecks, das die Ellipse definiert. |
| height | float | Höhe des Rechtecks, das die Ellipse definiert. |
| start_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| sweep_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom _startAngle_-Parameter zum Endpunkt des Bogens. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil des Bogens. |
| x | int | Die x-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert. |
| y | int | Die y-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert. |
| width | int | Breite des Rechtecks, das die Ellipse definiert. |
| height | int | Höhe des Rechtecks, das die Ellipse definiert. |
| start_angle | int | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| sweep_angle | int | Winkel in Grad, gemessen im Uhrzeigersinn vom _startAngle_-Parameter zum Endpunkt des Bogens. |

### Method: draw_arc_in_rect(pen, rect, start_angle, sweep_angle) {#draw_arc_in_rect_pen_rect_start_angle_sweep_angle_6}


```
 draw_arc_in_rect(pen, rect, start_angle, sweep_angle) 
```

Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)‑Struktur angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil des Bogens. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die die Grenzen der Ellipse definiert. |
| start_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| sweep_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom _startAngle_-Parameter zum Endpunkt des Bogens. |

### Method: draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle) {#draw_arc_in_rect_f_pen_rect_start_angle_sweep_angle_7}


```
 draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle) 
```

Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/)‑Struktur angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil des Bogens. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die die Grenzen der Ellipse definiert. |
| start_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| sweep_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom _startAngle_-Parameter zum Endpunkt des Bogens. |

### Method: draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_xy_pen_x_y_width_height_start_angle_sweep_angle_8}


```
 draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle) 
```

Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil des Bogens. |
| x | int | Die x-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert. |
| y | int | Die y-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert. |
| width | int | Breite des Rechtecks, das die Ellipse definiert. |
| height | int | Höhe des Rechtecks, das die Ellipse definiert. |
| start_angle | int | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| sweep_angle | int | Winkel in Grad, gemessen im Uhrzeigersinn vom _startAngle_-Parameter zum Endpunkt des Bogens. |

### Method: draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_xyf_pen_x_y_width_height_start_angle_sweep_angle_9}


```
 draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle) 
```

Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil des Bogens. |
| x | float | Die x-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert. |
| y | float | Die y-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert. |
| width | float | Breite des Rechtecks, das die Ellipse definiert. |
| height | float | Höhe des Rechtecks, das die Ellipse definiert. |
| start_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| sweep_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom _startAngle_-Parameter zum Endpunkt des Bogens. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_10}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Zeichnet eine Bézier‑Kurve, definiert durch vier [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Kurve. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die den Startpunkt der Kurve darstellt. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die den ersten Kontrollpunkt für die Kurve darstellt. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die den zweiten Kontrollpunkt für die Kurve darstellt. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die den Endpunkt der Kurve darstellt. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_11}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Zeichnet eine Bézier‑Kurve, definiert durch vier [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Kurve. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die den Startpunkt der Kurve darstellt. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die den ersten Kontrollpunkt für die Kurve darstellt. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die den zweiten Kontrollpunkt für die Kurve darstellt. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die den Endpunkt der Kurve darstellt. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) {#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_12}


```
 draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) 
```

Zeichnet eine Bézier‑Kurve, definiert durch vier geordnete Koordinatenpaare, die Punkte darstellen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Kurve. |
| x1 | float | Die x-Koordinate des Startpunkts der Kurve. |
| y1 | float | Die y-Koordinate des Startpunkts der Kurve. |
| x2 | float | Die x-Koordinate des ersten Kontrollpunkts der Kurve. |
| y2 | float | Die y-Koordinate des ersten Kontrollpunkts der Kurve. |
| x3 | float | Die x-Koordinate des zweiten Kontrollpunkts der Kurve. |
| y3 | float | Die y-Koordinate des zweiten Kontrollpunkts der Kurve. |
| x4 | float | Die x-Koordinate des Endpunkts der Kurve. |
| y4 | float | Die y-Koordinate des Endpunkts der Kurve. |

### Method: draw_bezier_by_points(pen, pt1, pt2, pt3, pt4) {#draw_bezier_by_points_pen_pt1_pt2_pt3_pt4_13}


```
 draw_bezier_by_points(pen, pt1, pt2, pt3, pt4) 
```

Zeichnet eine Bézier‑Kurve, definiert durch vier [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Kurve. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die den Startpunkt der Kurve darstellt. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die den ersten Kontrollpunkt für die Kurve darstellt. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die den zweiten Kontrollpunkt für die Kurve darstellt. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die den Endpunkt der Kurve darstellt. |

### Method: draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4) {#draw_bezier_by_points_f_pen_pt1_pt2_pt3_pt4_14}


```
 draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4) 
```

Zeichnet eine Bézier‑Kurve, definiert durch vier [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Kurve. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die den Startpunkt der Kurve darstellt. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die den ersten Kontrollpunkt für die Kurve darstellt. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die den zweiten Kontrollpunkt für die Kurve darstellt. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die den Endpunkt der Kurve darstellt. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_15}


```
 draw_beziers(pen, points) 
```

Zeichnet eine Reihe von Bézier‑Kurven aus einem Array von [Point](/imaging/python-net/aspose.imaging/point/)‑Strukturen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Kurve. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von [Point](/imaging/python-net/aspose.imaging/point/) Strukturen, die die Punkte darstellen, die die Kurve bestimmen. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_16}


```
 draw_beziers(pen, points) 
```

Zeichnet eine Reihe von Bézier‑Kurven aus einem Array von [Point](/imaging/python-net/aspose.imaging/point/)‑Strukturen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Kurve. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von [Point](/imaging/python-net/aspose.imaging/point/) Strukturen, die die Punkte darstellen, die die Kurve bestimmen. |

### Method: draw_beziers_by_pt_array(pen, points) {#draw_beziers_by_pt_array_pen_points_17}


```
 draw_beziers_by_pt_array(pen, points) 
```

Zeichnet eine Reihe von Bézier‑Kurven aus einem Array von [Point](/imaging/python-net/aspose.imaging/point/)‑Strukturen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Kurve. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von [Point](/imaging/python-net/aspose.imaging/point/) Strukturen, die die Punkte darstellen, die die Kurve bestimmen. |

### Method: draw_beziers_by_pt_array_f(pen, points) {#draw_beziers_by_pt_array_f_pen_points_18}


```
 draw_beziers_by_pt_array_f(pen, points) 
```

Zeichnet eine Reihe von Bézier‑Kurven aus einem Array von [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Kurve. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Punkte darstellen, die die Kurve bestimmen. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_19}


```
 draw_closed_curve(pen, points) 
```

Zeichnet eine geschlossene Kardinal‑Spline, definiert durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen. Diese Methode verwendet eine Standardspannung von 0,5 und den Füllmodus [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Spline definieren. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_20}


```
 draw_closed_curve(pen, points) 
```

Zeichnet eine geschlossene Kardinal‑Spline, definiert durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen. Diese Methode verwendet eine Standardspannung von 0,5 und den Füllmodus [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Spline definieren. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_21}


```
 draw_closed_curve(pen, points, tension) 
```

Zeichnet eine geschlossene Kardinal‑Spline, definiert durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen unter Verwendung einer angegebenen Spannung. Diese Methode verwendet den Standard‑Füllmodus [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Spline definieren. |
| Spannung | float | Wert größer oder gleich 0.0F, der die Spannung der Kurve angibt. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_22}


```
 draw_closed_curve(pen, points, tension) 
```

Zeichnet eine geschlossene Kardinal‑Spline, definiert durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen unter Verwendung einer angegebenen Spannung. Diese Methode verwendet den Standard‑Füllmodus [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Spline definieren. |
| Spannung | float | Wert größer oder gleich 0.0F, der die Spannung der Kurve angibt. |

### Method: draw_closed_curve_by_points(pen, points) {#draw_closed_curve_by_points_pen_points_23}


```
 draw_closed_curve_by_points(pen, points) 
```

Zeichnet eine geschlossene Kardinal‑Spline, definiert durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen. Diese Methode verwendet eine Standardspannung von 0,5 und den Füllmodus [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Spline definieren. |

### Method: draw_closed_curve_by_points_f(pen, points) {#draw_closed_curve_by_points_f_pen_points_24}


```
 draw_closed_curve_by_points_f(pen, points) 
```

Zeichnet eine geschlossene Kardinal‑Spline, definiert durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen. Diese Methode verwendet eine Standardspannung von 0,5 und den Füllmodus [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Spline definieren. |

### Method: draw_closed_curve_by_points_f_tension(pen, points, tension) {#draw_closed_curve_by_points_f_tension_pen_points_tension_25}


```
 draw_closed_curve_by_points_f_tension(pen, points, tension) 
```

Zeichnet eine geschlossene Kardinal‑Spline, definiert durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen unter Verwendung einer angegebenen Spannung. Diese Methode verwendet den Standard‑Füllmodus [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Spline definieren. |
| Spannung | float | Wert größer oder gleich 0.0F, der die Spannung der Kurve angibt. |

### Method: draw_closed_curve_by_points_tension(pen, points, tension) {#draw_closed_curve_by_points_tension_pen_points_tension_26}


```
 draw_closed_curve_by_points_tension(pen, points, tension) 
```

Zeichnet eine geschlossene Kardinal‑Spline, definiert durch ein Array von [Point](/imaging/python-net/aspose.imaging/point/)‑Strukturen unter Verwendung einer angegebenen Spannung. Diese Methode verwendet den Standard‑Füllmodus [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von [Point](/imaging/python-net/aspose.imaging/point/) Strukturen, die die Spline definieren. |
| Spannung | float | Wert größer oder gleich 0.0F, der die Spannung der Kurve angibt. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_27}


```
 draw_curve(pen, points) 
```

Zeichnet eine Kardinal‑Spline durch ein angegebenes Array von [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen. Diese Methode verwendet eine Standardspannung von 0,5.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Spline definieren. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_curve(pen, points) {#draw_curve_pen_points_28}


```
 draw_curve(pen, points) 
```

Zeichnet eine Kardinal‑Spline durch ein angegebenes Array von [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen. Diese Methode verwendet eine Standardspannung von 0,5.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Spline definieren. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_curve(pen, points, offset, number_of_segments) {#draw_curve_pen_points_offset_number_of_segments_29}


```
 draw_curve(pen, points, offset, number_of_segments) 
```

Zeichnet eine kardinale Spline durch ein angegebenes Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen. Die Zeichnung beginnt versetzt vom Anfang des Arrays.<br/>            Diese Methode verwendet eine Standardspannung von 0,5.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Spline definieren. |
| offset | int | Versatz vom ersten Element im Array des _points_-Parameters zum Startpunkt der Kurve. |
| number_of_segments | int | Anzahl der Segmente nach dem Startpunkt, die in die Kurve einbezogen werden. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_30}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Zeichnet eine kardinale Spline durch ein angegebenes Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen unter Verwendung einer angegebenen Spannung. Die Zeichnung beginnt versetzt vom Anfang des Arrays.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Spline definieren. |
| offset | int | Versatz vom ersten Element im Array des _points_-Parameters zum Startpunkt der Kurve. |
| number_of_segments | int | Anzahl der Segmente nach dem Startpunkt, die in die Kurve einbezogen werden. |
| Spannung | float | Wert größer oder gleich 0.0F, der die Spannung der Kurve angibt. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_31}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Zeichnet eine kardinale Spline durch ein angegebenes Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen unter Verwendung einer angegebenen Spannung. Die Zeichnung beginnt versetzt vom Anfang des Arrays.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Spline definieren. |
| offset | int | Versatz vom ersten Element im Array des _points_-Parameters zum Startpunkt der Kurve. |
| number_of_segments | int | Anzahl der Segmente nach dem Startpunkt, die in die Kurve einbezogen werden. |
| Spannung | float | Wert größer oder gleich 0.0F, der die Spannung der Kurve angibt. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_32}


```
 draw_curve(pen, points, tension) 
```

Zeichnet eine kardinale Spline durch ein angegebenes Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen unter Verwendung einer angegebenen Spannung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Punkte darstellen, die die Kurve definieren. |
| Spannung | float | Wert größer oder gleich 0.0F, der die Spannung der Kurve angibt. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_33}


```
 draw_curve(pen, points, tension) 
```

Zeichnet eine kardinale Spline durch ein angegebenes Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen unter Verwendung einer angegebenen Spannung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Punkte darstellen, die die Kurve definieren. |
| Spannung | float | Wert größer oder gleich 0.0F, der die Spannung der Kurve angibt. |

### Method: draw_curve_by_point_fs(pen, points) {#draw_curve_by_point_fs_pen_points_34}


```
 draw_curve_by_point_fs(pen, points) 
```

Zeichnet eine kardinale Spline durch ein angegebenes Array von [Point](/imaging/python-net/aspose.imaging/point/) Strukturen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von [Point](/imaging/python-net/aspose.imaging/point/) Strukturen, die die Spline definieren. |

### Method: draw_curve_by_point_fs_tension(pen, points, tension) {#draw_curve_by_point_fs_tension_pen_points_tension_35}


```
 draw_curve_by_point_fs_tension(pen, points, tension) 
```

Zeichnet eine kardinale Spline durch ein angegebenes Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen unter Verwendung einer angegebenen Spannung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Punkte darstellen, die die Kurve definieren. |
| Spannung | float | Wert größer oder gleich 0.0F, der die Spannung der Kurve angibt. |

### Method: draw_curve_by_points(pen, points) {#draw_curve_by_points_pen_points_36}


```
 draw_curve_by_points(pen, points) 
```

Zeichnet eine Kardinal‑Spline durch ein angegebenes Array von [PointF](/imaging/python-net/aspose.imaging/pointf/)‑Strukturen. Diese Methode verwendet eine Standardspannung von 0,5.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Spline definieren. |

### Method: draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) {#draw_curve_by_points_f_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_37}


```
 draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) 
```

Zeichnet eine kardinale Spline durch ein angegebenes Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen unter Verwendung einer angegebenen Spannung. Die Zeichnung beginnt versetzt vom Anfang des Arrays.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Spline definieren. |
| offset | int | Versatz vom ersten Element im Array des _points_-Parameters zum Startpunkt der Kurve. |
| number_of_segments | int | Anzahl der Segmente nach dem Startpunkt, die in die Kurve einbezogen werden. |
| Spannung | float | Wert größer oder gleich 0.0F, der die Spannung der Kurve angibt. |

### Method: draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) {#draw_curve_by_points_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_38}


```
 draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) 
```

Zeichnet eine kardinale Spline durch ein angegebenes Array von [Point](/imaging/python-net/aspose.imaging/point/) Strukturen unter Verwendung einer angegebenen Spannung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von [Point](/imaging/python-net/aspose.imaging/point/) Strukturen, die die Spline definieren. |
| offset | int | Versatz vom ersten Element im Array des _points_-Parameters zum Startpunkt der Kurve. |
| number_of_segments | int | Anzahl der Segmente nach dem Startpunkt, die in die Kurve einbezogen werden. |
| Spannung | float | Wert größer oder gleich 0.0F, der die Spannung der Kurve angibt. |

### Method: draw_curve_by_points_tension(pen, points, tension) {#draw_curve_by_points_tension_pen_points_tension_39}


```
 draw_curve_by_points_tension(pen, points, tension) 
```

Zeichnet eine kardinale Spline durch ein angegebenes Array von [Point](/imaging/python-net/aspose.imaging/point/) Strukturen unter Verwendung einer angegebenen Spannung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von [Point](/imaging/python-net/aspose.imaging/point/) Strukturen, die die Spline definieren. |
| Spannung | float | Wert größer oder gleich 0.0F, der die Spannung der Kurve angibt. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_40}


```
 draw_ellipse(pen, rect) 
```

Zeichnet eine Ellipse, definiert durch ein begrenzendes [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Ellipse. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die die Grenzen der Ellipse definiert. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_41}


```
 draw_ellipse(pen, rect) 
```

Zeichnet eine Ellipse, definiert durch ein begrenzendes [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Ellipse. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die die Grenzen der Ellipse definiert. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_42}


```
 draw_ellipse(pen, x, y, width, height) 
```

Zeichnet eine Ellipse, definiert durch ein begrenzendes Rechteck, das durch ein Koordinatenpaar, eine Höhe und eine Breite angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Ellipse. |
| x | float | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| y | float | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| width | float | Breite des Begrenzungsrechtecks, das die Ellipse definiert. |
| height | float | Höhe des Begrenzungsrechtecks, das die Ellipse definiert. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_43}


```
 draw_ellipse(pen, x, y, width, height) 
```

Zeichnet eine Ellipse, definiert durch ein begrenzendes Rechteck, das durch ein Koordinatenpaar, eine Höhe und eine Breite angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Ellipse. |
| x | int | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| y | int | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| width | int | Breite des Begrenzungsrechtecks, das die Ellipse definiert. |
| height | int | Höhe des Begrenzungsrechtecks, das die Ellipse definiert. |

### Method: draw_ellipse_by_xy(pen, x, y, width, height) {#draw_ellipse_by_xy_pen_x_y_width_height_44}


```
 draw_ellipse_by_xy(pen, x, y, width, height) 
```

Zeichnet eine Ellipse, definiert durch ein begrenzendes Rechteck, das durch ein Koordinatenpaar, eine Höhe und eine Breite angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Ellipse. |
| x | int | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| y | int | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| width | int | Breite des Begrenzungsrechtecks, das die Ellipse definiert. |
| height | int | Höhe des Begrenzungsrechtecks, das die Ellipse definiert. |

### Method: draw_ellipse_by_xyf(pen, x, y, width, height) {#draw_ellipse_by_xyf_pen_x_y_width_height_45}


```
 draw_ellipse_by_xyf(pen, x, y, width, height) 
```

Zeichnet eine Ellipse, definiert durch ein begrenzendes Rechteck, das durch ein Koordinatenpaar, eine Höhe und eine Breite angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Ellipse. |
| x | float | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| y | float | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| width | float | Breite des Begrenzungsrechtecks, das die Ellipse definiert. |
| height | float | Höhe des Begrenzungsrechtecks, das die Ellipse definiert. |

### Method: draw_ellipse_f(pen, rect) {#draw_ellipse_f_pen_rect_46}


```
 draw_ellipse_f(pen, rect) 
```

Zeichnet eine Ellipse, definiert durch ein begrenzendes [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Ellipse. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die die Grenzen der Ellipse definiert. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_47}


```
 draw_image(image, dest_points) 
```

Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild zum Zeichnen. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von drei PointF-Strukturen, die ein Parallelogramm definieren. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_48}


```
 draw_image(image, dest_points) 
```

Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild zum Zeichnen. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von drei PointF-Strukturen, die ein Parallelogramm definieren. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_49}


```
 draw_image(image, dest_points, src_rect) 
```

Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild zum Zeichnen. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von drei PointF-Strukturen, die ein Parallelogramm definieren. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Quellrechteck. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_50}


```
 draw_image(image, dest_points, src_rect) 
```

Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild zum Zeichnen. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von drei PointF-Strukturen, die ein Parallelogramm definieren. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das Quellrechteck. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_51}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild zum Zeichnen. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von drei PointF-Strukturen, die ein Parallelogramm definieren. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Quellrechteck. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Maßeinheiten. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_52}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild zum Zeichnen. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von drei PointF-Strukturen, die ein Parallelogramm definieren. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das Quellrechteck. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Maßeinheiten. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_53}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild zum Zeichnen. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von drei PointF-Strukturen, die ein Parallelogramm definieren. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Quellrechteck. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Maßeinheiten. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Die Bildeigenschaften. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_54}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild zum Zeichnen. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von drei PointF-Strukturen, die ein Parallelogramm definieren. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das Quellrechteck. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Maßeinheiten. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Die Bildeigenschaften. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_55}


```
 draw_image(source_image, point) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), unter Verwendung seiner ursprünglichen physischen Größe, am angegebenen Ort.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die die obere linke Ecke des gezeichneten Bildes darstellt. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_56}


```
 draw_image(source_image, point) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), unter Verwendung seiner ursprünglichen physischen Größe, am angegebenen Ort.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die die obere linke Ecke des gezeichneten Bildes darstellt. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_57}


```
 draw_image(source_image, rect) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die den Ort und die Größe des gezeichneten Bildes angibt. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_58}


```
 draw_image(source_image, rect) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die den Ort und die Größe des gezeichneten Bildes angibt. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_59}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Zielrechteck. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Grafikeinheit. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_60}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das Zielrechteck. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Grafikeinheit. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_61}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Zielrechteck. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Grafikeinheit. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Die Bildeigenschaften. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_62}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das Zielrechteck. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Grafikeinheit. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Die Bildeigenschaften. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_63}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Quell-Rect. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Ziel-Rect. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Grafikeinheit. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_64}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Der Quell-Rect. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Der Ziel-Rect. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Grafikeinheit. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_65}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Quell-Rect. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Ziel-Rect. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Grafikeinheit. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Die Bildeigenschaften. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_66}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Der Quell-Rect. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Der Ziel-Rect. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Grafikeinheit. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Die Bildeigenschaften. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_67}


```
 draw_image(source_image, x, y) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), unter Verwendung seiner ursprünglichen physischen Größe, am angegebenen Ort.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| x | float | Die x-Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| y | float | Die y-Koordinate der oberen linken Ecke des gezeichneten Bildes. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_68}


```
 draw_image(source_image, x, y) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), unter Verwendung seiner ursprünglichen physischen Größe, am angegebenen Ort.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| x | int | Die x-Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| y | int | Die y-Koordinate der oberen linken Ecke des gezeichneten Bildes. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_69}


```
 draw_image(source_image, x, y, width, height) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| x | float | Die x-Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| y | float | Die y-Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| width | float | Breite des gezeichneten Bildes. |
| height | float | Höhe des gezeichneten Bildes. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_70}


```
 draw_image(source_image, x, y, width, height) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| x | int | Die x-Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| y | int | Die y-Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| width | int | Breite des gezeichneten Bildes. |
| height | int | Höhe des gezeichneten Bildes. |

### Method: draw_image_at_point(source_image, point) {#draw_image_at_point_source_image_point_71}


```
 draw_image_at_point(source_image, point) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), unter Verwendung seiner ursprünglichen physischen Größe, am angegebenen Ort.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die die obere linke Ecke des gezeichneten Bildes darstellt. |

### Method: draw_image_at_point_f(source_image, point) {#draw_image_at_point_f_source_image_point_72}


```
 draw_image_at_point_f(source_image, point) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), unter Verwendung seiner ursprünglichen physischen Größe, am angegebenen Ort.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die die obere linke Ecke des gezeichneten Bildes darstellt. |

### Method: draw_image_at_xy(source_image, x, y) {#draw_image_at_xy_source_image_x_y_73}


```
 draw_image_at_xy(source_image, x, y) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), unter Verwendung seiner ursprünglichen physischen Größe, am angegebenen Ort.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| x | int | Die x-Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| y | int | Die y-Koordinate der oberen linken Ecke des gezeichneten Bildes. |

### Method: draw_image_at_xyf(source_image, x, y) {#draw_image_at_xyf_source_image_x_y_74}


```
 draw_image_at_xyf(source_image, x, y) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/), unter Verwendung seiner ursprünglichen physischen Größe, am angegebenen Ort.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| x | float | Die x-Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| y | float | Die y-Koordinate der oberen linken Ecke des gezeichneten Bildes. |

### Method: draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit) {#draw_image_dest_point_f_src_rect_f_with_unit_image_dest_points_src_rect_src_unit_75}


```
 draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit) 
```

Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild zum Zeichnen. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von drei PointF-Strukturen, die ein Parallelogramm definieren. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das Quellrechteck. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Maßeinheiten. |

### Method: draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_dest_point_f_src_rect_f_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_76}


```
 draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) 
```

Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild zum Zeichnen. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von drei PointF-Strukturen, die ein Parallelogramm definieren. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das Quellrechteck. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Maßeinheiten. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Die Bildeigenschaften. |

### Method: draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect) {#draw_image_dest_points_f_src_rect_f_image_dest_points_src_rect_77}


```
 draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect) 
```

Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild zum Zeichnen. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von drei PointF-Strukturen, die ein Parallelogramm definieren. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das Quellrechteck. |

### Method: draw_image_dest_points_src_rect(image, dest_points, src_rect) {#draw_image_dest_points_src_rect_image_dest_points_src_rect_78}


```
 draw_image_dest_points_src_rect(image, dest_points, src_rect) 
```

Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild zum Zeichnen. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von drei PointF-Strukturen, die ein Parallelogramm definieren. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Quellrechteck. |

### Method: draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit) {#draw_image_dest_points_src_rect_with_unit_image_dest_points_src_rect_src_unit_79}


```
 draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit) 
```

Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild zum Zeichnen. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von drei PointF-Strukturen, die ein Parallelogramm definieren. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Quellrechteck. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Maßeinheiten. |

### Method: draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_dest_points_src_rect_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_80}


```
 draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) 
```

Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild zum Zeichnen. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von drei PointF-Strukturen, die ein Parallelogramm definieren. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Quellrechteck. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Maßeinheiten. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Die Bildeigenschaften. |

### Method: draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_dest_rect_f_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_81}


```
 draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das Zielrechteck, in dem gezeichnet wird. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Grafikeinheit. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Die Bildeigenschaften. |

### Method: draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_dest_rect_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_82}


```
 draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Zielrechteck. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Grafikeinheit. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Die Bildeigenschaften. |

### Method: draw_image_in_rect(source_image, x, y, width, height) {#draw_image_in_rect_source_image_x_y_width_height_83}


```
 draw_image_in_rect(source_image, x, y, width, height) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| x | int | Die x-Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| y | int | Die y-Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| width | int | Breite des gezeichneten Bildes. |
| height | int | Höhe des gezeichneten Bildes. |

### Method: draw_image_in_rect_f(source_image, x, y, width, height) {#draw_image_in_rect_f_source_image_x_y_width_height_84}


```
 draw_image_in_rect_f(source_image, x, y, width, height) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| x | float | Die x-Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| y | float | Die y-Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| width | float | Breite des gezeichneten Bildes. |
| height | float | Höhe des gezeichneten Bildes. |

### Method: draw_image_in_rectangle(source_image, rect) {#draw_image_in_rectangle_source_image_rect_85}


```
 draw_image_in_rectangle(source_image, rect) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur, die den Ort und die Größe des gezeichneten Bildes angibt. |

### Method: draw_image_points(image, dest_points) {#draw_image_points_image_dest_points_86}


```
 draw_image_points(image, dest_points) 
```

Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild zum Zeichnen. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von drei PointF-Strukturen, die ein Parallelogramm definieren. |

### Method: draw_image_points_f(image, dest_points) {#draw_image_points_f_image_dest_points_87}


```
 draw_image_points_f(image, dest_points) 
```

Zeichnet den angegebenen Teil des angegebenen _image_ am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild zum Zeichnen. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von drei PointF-Strukturen, die ein Parallelogramm definieren. |

### Method: draw_image_rectangle_f(source_image, rect) {#draw_image_rectangle_f_source_image_rect_88}


```
 draw_image_rectangle_f(source_image, rect) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die den Ort und die Größe des gezeichneten Bildes angibt. |

### Method: draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_src_dest_rects_f_with_unit_source_image_rect_source_rect_destination_graphics_unit_89}


```
 draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Der Quell-Rect. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Der Ziel-Rect. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Grafikeinheit. |

### Method: draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_src_dest_rects_with_unit_source_image_rect_source_rect_destination_graphics_unit_90}


```
 draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Quell-Rect. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Ziel-Rect. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Grafikeinheit. |

### Method: draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_src_dst_rect_f_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_91}


```
 draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das Quellrechteck. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das Zielrechteck. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die zu verwendende Grafikeinheit. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Die zu verwendenden Bildeigenschaften. |

### Method: draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_src_dst_rects_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_92}


```
 draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Quell-Rect. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Der Ziel-Rect. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Grafikeinheit. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Die Bildeigenschaften. |

### Method: draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit) {#draw_image_to_rect_f_with_unit_source_image_rect_destination_graphics_unit_93}


```
 draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das Zielrechteck. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Grafikeinheit. |

### Method: draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit) {#draw_image_to_rect_with_unit_source_image_rect_destination_graphics_unit_94}


```
 draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit) 
```

Zeichnet das angegebene [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Zielrechteck. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Die Grafikeinheit. |

### Method: draw_image_unscaled(source_image, point) {#draw_image_unscaled_source_image_point_95}


```
 draw_image_unscaled(source_image, point) 
```

Zeichnet ein angegebenes Bild unter Verwendung seiner ursprünglichen physischen Größe an einem angegebenen Ort.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) Struktur, die die obere linke Ecke des gezeichneten Bildes angibt. |

### Method: draw_image_unscaled(source_image, rect) {#draw_image_unscaled_source_image_rect_96}


```
 draw_image_unscaled(source_image, rect) 
```

Zeichnet ein angegebenes Bild unter Verwendung seiner ursprünglichen physischen Größe an einem angegebenen Ort.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) das die obere linke Ecke des gezeichneten Bildes angibt. Die X- und Y-Eigenschaften des Rechtecks geben die obere linke Ecke an. Die Breite- und Höhe-Eigenschaften werden ignoriert. |

### Method: draw_image_unscaled(source_image, x, y) {#draw_image_unscaled_source_image_x_y_97}


```
 draw_image_unscaled(source_image, x, y) 
```

Zeichnet das angegebene Bild unter Verwendung seiner ursprünglichen physischen Größe an dem Ort, der durch ein Koordinatenpaar angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| x | int | Die x-Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| y | int | Die y-Koordinate der oberen linken Ecke des gezeichneten Bildes. |

### Method: draw_image_unscaled(source_image, x, y, width, height) {#draw_image_unscaled_source_image_x_y_width_height_98}


```
 draw_image_unscaled(source_image, x, y, width, height) 
```

Zeichnet ein angegebenes Bild unter Verwendung seiner ursprünglichen physischen Größe an einem angegebenen Ort.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| x | int | Die x-Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| y | int | Die y-Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| width | int | Der Parameter wird nicht verwendet. |
| height | int | Der Parameter wird nicht verwendet. |

### Method: draw_image_unscaled_and_clipped(source_image, rect) {#draw_image_unscaled_and_clipped_source_image_rect_99}


```
 draw_image_unscaled_and_clipped(source_image, rect) 
```

Zeichnet das angegebene Bild ohne Skalierung und schneidet es, falls nötig, zu, um in das angegebene Rechteck zu passen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) in dem das Bild gezeichnet wird. |

### Method: draw_image_unscaled_in_rectangle(source_image, rect) {#draw_image_unscaled_in_rectangle_source_image_rect_100}


```
 draw_image_unscaled_in_rectangle(source_image, rect) 
```

Zeichnet ein angegebenes Bild unter Verwendung seiner ursprünglichen physischen Größe an einem angegebenen Ort.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) das die obere linke Ecke des gezeichneten Bildes angibt. Die X- und Y-Eigenschaften des Rechtecks geben die obere linke Ecke an. Die Breite- und Höhe-Eigenschaften werden ignoriert. |

### Method: draw_image_unscaled_to_point(source_image, point) {#draw_image_unscaled_to_point_source_image_point_101}


```
 draw_image_unscaled_to_point(source_image, point) 
```

Zeichnet ein angegebenes Bild unter Verwendung seiner ursprünglichen physischen Größe an einem angegebenen Ort.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | Das Bild, mit dem gezeichnet wird. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) Struktur, die die obere linke Ecke des gezeichneten Bildes angibt. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_102}


```
 draw_line(pen, point1, point2) 
```

Zeichnet eine Linie, die zwei [Point](/imaging/python-net/aspose.imaging/point/) Strukturen verbindet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) der die Farbe, Breite und den Stil der Linie bestimmt. |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) Struktur, die den ersten zu verbindenden Punkt darstellt. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) Struktur, die den zweiten Punkt zum Verbinden darstellt. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_103}


```
 draw_line(pen, point1, point2) 
```

Zeichnet eine Linie, die zwei [Point](/imaging/python-net/aspose.imaging/point/) Strukturen verbindet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) der die Farbe, Breite und den Stil der Linie bestimmt. |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [Point](/imaging/python-net/aspose.imaging/point/) Struktur, die den ersten zu verbindenden Punkt darstellt. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [Point](/imaging/python-net/aspose.imaging/point/) Struktur, die den zweiten Punkt zum Verbinden darstellt. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_104}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Zeichnet eine Linie, die die beiden durch Koordinatenpaare angegebenen Punkte verbindet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) der die Farbe, Breite und den Stil der Linie bestimmt. |
| x1 | int | Die x-Koordinate des ersten Punktes. |
| y1 | int | Die y-Koordinate des ersten Punktes. |
| x2 | int | Die x-Koordinate des zweiten Punktes. |
| y2 | int | Die y-Koordinate des zweiten Punktes. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_105}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Zeichnet eine Linie, die die beiden durch Koordinatenpaare angegebenen Punkte verbindet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) der die Farbe, Breite und den Stil der Linie bestimmt. |
| x1 | float | Die x-Koordinate des ersten Punktes. |
| y1 | float | Die y-Koordinate des ersten Punktes. |
| x2 | float | Die x-Koordinate des zweiten Punktes. |
| y2 | float | Die y-Koordinate des zweiten Punktes. |

### Method: draw_line_by_xy(pen, x1, y1, x2, y2) {#draw_line_by_xy_pen_x1_y1_x2_y2_106}


```
 draw_line_by_xy(pen, x1, y1, x2, y2) 
```

Zeichnet eine Linie, die die beiden durch Koordinatenpaare angegebenen Punkte verbindet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) der die Farbe, Breite und den Stil der Linie bestimmt. |
| x1 | int | Die x-Koordinate des ersten Punktes. |
| y1 | int | Die y-Koordinate des ersten Punktes. |
| x2 | int | Die x-Koordinate des zweiten Punktes. |
| y2 | int | Die y-Koordinate des zweiten Punktes. |

### Method: draw_line_f_by_xy(pen, x1, y1, x2, y2) {#draw_line_f_by_xy_pen_x1_y1_x2_y2_107}


```
 draw_line_f_by_xy(pen, x1, y1, x2, y2) 
```

Zeichnet eine Linie, die die beiden durch Koordinatenpaare angegebenen Punkte verbindet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) der die Farbe, Breite und den Stil der Linie bestimmt. |
| x1 | float | Die x-Koordinate des ersten Punktes. |
| y1 | float | Die y-Koordinate des ersten Punktes. |
| x2 | float | Die x-Koordinate des zweiten Punktes. |
| y2 | float | Die y-Koordinate des zweiten Punktes. |

### Method: draw_line_point_f(pen, point1, point2) {#draw_line_point_f_pen_point1_point2_108}


```
 draw_line_point_f(pen, point1, point2) 
```

Zeichnet eine Linie, die zwei [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen verbindet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) der die Farbe, Breite und den Stil der Linie bestimmt. |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die den ersten Punkt zum Verbinden darstellt. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die den zweiten Punkt zum Verbinden darstellt. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_109}


```
 draw_lines(pen, points) 
```

Zeichnet eine Reihe von Liniensegmenten, die ein Array von [Point](/imaging/python-net/aspose.imaging/point/) Strukturen verbinden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Liniensegmente. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von [Point](/imaging/python-net/aspose.imaging/point/) Strukturen, die die zu verbindenden Punkte darstellen. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_110}


```
 draw_lines(pen, points) 
```

Zeichnet eine Reihe von Liniensegmenten, die ein Array von [Point](/imaging/python-net/aspose.imaging/point/) Strukturen verbinden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Liniensegmente. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von [Point](/imaging/python-net/aspose.imaging/point/) Strukturen, die die zu verbindenden Punkte darstellen. |

### Method: draw_lines_f(pen, points) {#draw_lines_f_pen_points_111}


```
 draw_lines_f(pen, points) 
```

Zeichnet eine Reihe von Liniensegmenten, die ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen verbinden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Liniensegmente. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die zu verbindenden Punkte darstellen. |

### Method: draw_path(pen, path) {#draw_path_pen_path_112}


```
 draw_path(pen, path) 
```

Zeichnet einen [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil des Pfads. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) zum Zeichnen. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_113}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Zeichnet eine Tortenform, definiert durch eine Ellipse, die durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur und zwei Radiallinien angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Kuchenform. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die das Begrenzungsrechteck darstellt, das die Ellipse definiert, aus der die Kuchenform stammt. |
| start_angle | float | Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse zur ersten Seite der Kuchenform. |
| sweep_angle | float | Winkel, gemessen in Grad im Uhrzeigersinn vom Parameter _startAngle_ zur zweiten Seite der Kuchenform. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_114}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Zeichnet eine Tortenform, definiert durch eine Ellipse, die durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur und zwei Radiallinien angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Kuchenform. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die das Begrenzungsrechteck darstellt, das die Ellipse definiert, aus der die Kuchenform stammt. |
| start_angle | float | Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse zur ersten Seite der Kuchenform. |
| sweep_angle | float | Winkel, gemessen in Grad im Uhrzeigersinn vom Parameter _startAngle_ zur zweiten Seite der Kuchenform. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_115}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Zeichnet eine Tortenform, definiert durch eine Ellipse, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Kuchenform. |
| x | float | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| y | float | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| width | float | Breite des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| height | float | Höhe des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| start_angle | float | Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse zur ersten Seite der Kuchenform. |
| sweep_angle | float | Winkel, gemessen in Grad im Uhrzeigersinn vom Parameter _startAngle_ zur zweiten Seite der Kuchenform. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_116}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Zeichnet eine Tortenform, definiert durch eine Ellipse, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Kuchenform. |
| x | int | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| y | int | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| width | int | Breite des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| height | int | Höhe des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| start_angle | int | Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse zur ersten Seite der Kuchenform. |
| sweep_angle | int | Winkel, gemessen in Grad im Uhrzeigersinn vom Parameter _startAngle_ zur zweiten Seite der Kuchenform. |

### Method: draw_pie_in_rect(pen, rect, start_angle, sweep_angle) {#draw_pie_in_rect_pen_rect_start_angle_sweep_angle_117}


```
 draw_pie_in_rect(pen, rect, start_angle, sweep_angle) 
```

Zeichnet eine Tortenform, definiert durch eine Ellipse, die durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur und zwei Radiallinien angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Kuchenform. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die das Begrenzungsrechteck darstellt, das die Ellipse definiert, aus der die Kuchenform stammt. |
| start_angle | float | Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse zur ersten Seite der Kuchenform. |
| sweep_angle | float | Winkel, gemessen in Grad im Uhrzeigersinn vom Parameter _startAngle_ zur zweiten Seite der Kuchenform. |

### Method: draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle) {#draw_pie_in_rect_f_pen_rect_start_angle_sweep_angle_118}


```
 draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle) 
```

Zeichnet eine Tortenform, definiert durch eine Ellipse, die durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur und zwei Radiallinien angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Kuchenform. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die das Begrenzungsrechteck darstellt, das die Ellipse definiert, aus der die Kuchenform stammt. |
| start_angle | float | Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse zur ersten Seite der Kuchenform. |
| sweep_angle | float | Winkel, gemessen in Grad im Uhrzeigersinn vom Parameter _startAngle_ zur zweiten Seite der Kuchenform. |

### Method: draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_xy_pen_x_y_width_height_start_angle_sweep_angle_119}


```
 draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle) 
```

Zeichnet eine Tortenform, definiert durch eine Ellipse, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Kuchenform. |
| x | int | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| y | int | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| width | int | Breite des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| height | int | Höhe des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| start_angle | int | Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse zur ersten Seite der Kuchenform. |
| sweep_angle | int | Winkel, gemessen in Grad im Uhrzeigersinn vom Parameter _startAngle_ zur zweiten Seite der Kuchenform. |

### Method: draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_xyf_pen_x_y_width_height_start_angle_sweep_angle_120}


```
 draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle) 
```

Zeichnet eine Tortenform, definiert durch eine Ellipse, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Kuchenform. |
| x | float | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| y | float | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| width | float | Breite des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| height | float | Höhe des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| start_angle | float | Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse zur ersten Seite der Kuchenform. |
| sweep_angle | float | Winkel, gemessen in Grad im Uhrzeigersinn vom Parameter _startAngle_ zur zweiten Seite der Kuchenform. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_121}


```
 draw_polygon(pen, points) 
```

Zeichnet ein Polygon, definiert durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil des Polygons. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Scheitelpunkte des Polygons darstellen. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_122}


```
 draw_polygon(pen, points) 
```

Zeichnet ein Polygon, definiert durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil des Polygons. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Scheitelpunkte des Polygons darstellen. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_polygon_f(pen, points) {#draw_polygon_f_pen_points_123}


```
 draw_polygon_f(pen, points) 
```

Zeichnet ein Polygon, definiert durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil des Polygons. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Scheitelpunkte des Polygons darstellen. |

### Method: draw_rect(pen, x, y, width, height) {#draw_rect_pen_x_y_width_height_124}


```
 draw_rect(pen, x, y, width, height) 
```

Zeichnet ein Rechteck, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ein [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil des Rechtecks. |
| x | int | Die x-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| y | int | Die y-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| width | int | Die Breite des zu zeichnenden Rechtecks. |
| height | int | Die Höhe des zu zeichnenden Rechtecks. |

### Method: draw_rect_f(pen, x, y, width, height) {#draw_rect_f_pen_x_y_width_height_125}


```
 draw_rect_f(pen, x, y, width, height) 
```

Zeichnet ein Rechteck, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ein [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil des Rechtecks. |
| x | float | Die x-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| y | float | Die y-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| width | float | Die Breite des zu zeichnenden Rechtecks. |
| height | float | Die Höhe des zu zeichnenden Rechtecks. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_126}


```
 draw_rectangle(pen, rect) 
```

Zeichnet ein Rechteck, das durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ein [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil des Rechtecks. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die das zu zeichnende Rechteck darstellt. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_127}


```
 draw_rectangle(pen, rect) 
```

Zeichnet ein Rechteck, das durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ein [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil des Rechtecks. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die das zu zeichnende Rechteck darstellt. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_128}


```
 draw_rectangle(pen, x, y, width, height) 
```

Zeichnet ein Rechteck, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ein [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil des Rechtecks. |
| x | float | Die x-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| y | float | Die y-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| width | float | Die Breite des zu zeichnenden Rechtecks. |
| height | float | Die Höhe des zu zeichnenden Rechtecks. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_129}


```
 draw_rectangle(pen, x, y, width, height) 
```

Zeichnet ein Rechteck, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ein [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil des Rechtecks. |
| x | int | Die x-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| y | int | Die y-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| width | int | Die Breite des zu zeichnenden Rechtecks. |
| height | int | Die Höhe des zu zeichnenden Rechtecks. |

### Method: draw_rectangle_f(pen, rect) {#draw_rectangle_f_pen_rect_130}


```
 draw_rectangle_f(pen, rect) 
```

Zeichnet ein Rechteck, das durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ein [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil des Rechtecks. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die das zu zeichnende Rechteck darstellt. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_131}


```
 draw_rectangles(pen, rects) 
```

Zeichnet eine Reihe von Rechtecken, die durch [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Strukturen angegeben sind.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Umrisse der Rechtecke. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Array von [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Strukturen, die die zu zeichnenden Rechtecke darstellen. |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_132}


```
 draw_rectangles(pen, rects) 
```

Zeichnet eine Reihe von Rechtecken, die durch [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Strukturen angegeben sind.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Umrisse der Rechtecke. |
| rects | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | Array von [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Strukturen, die die zu zeichnenden Rechtecke darstellen. |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: draw_rectangles_f(pen, rects) {#draw_rectangles_f_pen_rects_133}


```
 draw_rectangles_f(pen, rects) 
```

Zeichnet eine Reihe von Rechtecken, die durch [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Strukturen angegeben sind.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) bestimmt die Farbe, Breite und den Stil der Umrisse der Rechtecke. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Array von [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Strukturen, die die zu zeichnenden Rechtecke darstellen. |

### Method: draw_string(s, font, brush, layout_rectangle) {#draw_string_s_font_brush_layout_rectangle_134}


```
 draw_string(s, font, brush, layout_rectangle) 
```

Zeichnet die angegebene Textzeichenfolge im angegebenen Rechteck mit den angegebenen [Brush](/imaging/python-net/aspose.imaging/brush/) und [Font](/imaging/python-net/aspose.imaging/font/) Objekten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| s | string | Zeichenkette zum Zeichnen. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) definiert das Textformat der Zeichenkette. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Farbe und Textur des gezeichneten Textes. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die den Ort des gezeichneten Textes angibt. |

### Method: draw_string(s, font, brush, layout_rectangle, format) {#draw_string_s_font_brush_layout_rectangle_format_135}


```
 draw_string(s, font, brush, layout_rectangle, format) 
```

Zeichnet die angegebene Textzeichenfolge im angegebenen Rechteck mit den angegebenen [Brush](/imaging/python-net/aspose.imaging/brush/) und [Font](/imaging/python-net/aspose.imaging/font/) Objekten unter Verwendung der Formatattribute des angegebenen [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| s | string | Zeichenkette zum Zeichnen. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) definiert das Textformat der Zeichenkette. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Farbe und Textur des gezeichneten Textes. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die den Ort des gezeichneten Textes angibt. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) gibt Formatierungsattribute an, wie Zeilenabstand und Ausrichtung, die auf den gezeichneten Text angewendet werden. |

### Method: draw_string(s, font, brush, point) {#draw_string_s_font_brush_point_136}


```
 draw_string(s, font, brush, point) 
```

Zeichnet die angegebene Textzeichenfolge an der angegebenen Position mit den angegebenen [Brush](/imaging/python-net/aspose.imaging/brush/) und [Font](/imaging/python-net/aspose.imaging/font/) Objekten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| s | string | Zeichenkette zum Zeichnen. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) definiert das Textformat der Zeichenkette. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Farbe und Textur des gezeichneten Textes. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die die obere linke Ecke des gezeichneten Textes angibt. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_string(s, font, brush, point, format) {#draw_string_s_font_brush_point_format_137}


```
 draw_string(s, font, brush, point, format) 
```

Zeichnet die angegebene Textzeichenfolge an der angegebenen Position mit den angegebenen [Brush](/imaging/python-net/aspose.imaging/brush/) und [Font](/imaging/python-net/aspose.imaging/font/) Objekten unter Verwendung der Formatattribute des angegebenen [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| s | string | Zeichenkette zum Zeichnen. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) definiert das Textformat der Zeichenkette. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Farbe und Textur des gezeichneten Textes. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die die obere linke Ecke des gezeichneten Textes angibt. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) gibt Formatierungsattribute an, wie Zeilenabstand und Ausrichtung, die auf den gezeichneten Text angewendet werden. |

### Method: draw_string(s, font, brush, x, y) {#draw_string_s_font_brush_x_y_138}


```
 draw_string(s, font, brush, x, y) 
```

Zeichnet die angegebene Textzeichenfolge an der angegebenen Position mit den angegebenen [Brush](/imaging/python-net/aspose.imaging/brush/) und [Font](/imaging/python-net/aspose.imaging/font/) Objekten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| s | string | Zeichenkette zum Zeichnen. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) definiert das Textformat der Zeichenkette. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Farbe und Textur des gezeichneten Textes. |
| x | float | Die x-Koordinate der oberen linken Ecke des gezeichneten Textes. |
| y | float | Die y-Koordinate der oberen linken Ecke des gezeichneten Textes. |

### Method: draw_string(s, font, brush, x, y, format) {#draw_string_s_font_brush_x_y_format_139}


```
 draw_string(s, font, brush, x, y, format) 
```

Zeichnet die angegebene Textzeichenfolge an der angegebenen Position mit den angegebenen [Brush](/imaging/python-net/aspose.imaging/brush/) und [Font](/imaging/python-net/aspose.imaging/font/) Objekten unter Verwendung der Formatattribute des angegebenen [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| s | string | Zeichenkette zum Zeichnen. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) definiert das Textformat der Zeichenkette. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Farbe und Textur des gezeichneten Textes. |
| x | float | Die x-Koordinate der oberen linken Ecke des gezeichneten Textes. |
| y | float | Die y-Koordinate der oberen linken Ecke des gezeichneten Textes. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) gibt Formatierungsattribute an, wie Zeilenabstand und Ausrichtung, die auf den gezeichneten Text angewendet werden. |

### Method: draw_string_at_point_f(s, font, brush, point) {#draw_string_at_point_f_s_font_brush_point_140}


```
 draw_string_at_point_f(s, font, brush, point) 
```

Zeichnet die angegebene Textzeichenfolge an der angegebenen Position mit den angegebenen [Brush](/imaging/python-net/aspose.imaging/brush/) und [Font](/imaging/python-net/aspose.imaging/font/) Objekten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| s | string | Zeichenkette zum Zeichnen. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) definiert das Textformat der Zeichenkette. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Farbe und Textur des gezeichneten Textes. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die die obere linke Ecke des gezeichneten Textes angibt. |

### Method: draw_string_at_point_f_format(s, font, brush, point, format) {#draw_string_at_point_f_format_s_font_brush_point_format_141}


```
 draw_string_at_point_f_format(s, font, brush, point, format) 
```

Zeichnet die angegebene Textzeichenfolge an der angegebenen Position mit den angegebenen [Brush](/imaging/python-net/aspose.imaging/brush/) und [Font](/imaging/python-net/aspose.imaging/font/) Objekten unter Verwendung der Formatattribute des angegebenen [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| s | string | Zeichenkette zum Zeichnen. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) definiert das Textformat der Zeichenkette. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Farbe und Textur des gezeichneten Textes. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) Struktur, die die obere linke Ecke des gezeichneten Textes angibt. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) gibt Formatierungsattribute an, wie Zeilenabstand und Ausrichtung, die auf den gezeichneten Text angewendet werden. |

### Method: draw_string_at_xy(s, font, brush, x, y) {#draw_string_at_xy_s_font_brush_x_y_142}


```
 draw_string_at_xy(s, font, brush, x, y) 
```

Zeichnet die angegebene Textzeichenfolge an der angegebenen Position mit den angegebenen [Brush](/imaging/python-net/aspose.imaging/brush/) und [Font](/imaging/python-net/aspose.imaging/font/) Objekten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| s | string | Zeichenkette zum Zeichnen. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) definiert das Textformat der Zeichenkette. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Farbe und Textur des gezeichneten Textes. |
| x | float | Die x-Koordinate der oberen linken Ecke des gezeichneten Textes. |
| y | float | Die y-Koordinate der oberen linken Ecke des gezeichneten Textes. |

### Method: draw_string_in_rect(s, font, brush, layout_rectangle) {#draw_string_in_rect_s_font_brush_layout_rectangle_143}


```
 draw_string_in_rect(s, font, brush, layout_rectangle) 
```

Zeichnet die angegebene Textzeichenfolge im angegebenen Rechteck mit den angegebenen [Brush](/imaging/python-net/aspose.imaging/brush/) und [Font](/imaging/python-net/aspose.imaging/font/) Objekten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| s | string | Zeichenkette zum Zeichnen. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) definiert das Textformat der Zeichenkette. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Farbe und Textur des gezeichneten Textes. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die den Ort des gezeichneten Textes angibt. |

### Method: draw_string_in_rect_f(s, font, brush, layout_rectangle, format) {#draw_string_in_rect_f_s_font_brush_layout_rectangle_format_144}


```
 draw_string_in_rect_f(s, font, brush, layout_rectangle, format) 
```

Zeichnet die angegebene Textzeichenfolge im angegebenen Rechteck mit den angegebenen [Brush](/imaging/python-net/aspose.imaging/brush/) und [Font](/imaging/python-net/aspose.imaging/font/) Objekten unter Verwendung der Formatattribute des angegebenen [StringFormat](/imaging/python-net/aspose.imaging/stringformat/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| s | string | Zeichenkette zum Zeichnen. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) definiert das Textformat der Zeichenkette. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Farbe und Textur des gezeichneten Textes. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die den Ort des gezeichneten Textes angibt. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) gibt Formatierungsattribute an, wie Zeilenabstand und Ausrichtung, die auf den gezeichneten Text angewendet werden. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_145}


```
 fill_closed_curve(brush, points) 
```

Füllt das Innere einer geschlossenen Kardinal‑Spline‑Kurve, die durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen definiert ist. Diese Methode verwendet eine Standardspannung von 0.5 und den [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) Füllmodus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Spline definieren. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_146}


```
 fill_closed_curve(brush, points) 
```

Füllt das Innere einer geschlossenen Kardinal‑Spline‑Kurve, die durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen definiert ist. Diese Methode verwendet eine Standardspannung von 0.5 und den [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) Füllmodus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Spline definieren. |

### Method: fill_closed_curve(brush, points, fill_mode) {#fill_closed_curve_brush_points_fill_mode_147}


```
 fill_closed_curve(brush, points, fill_mode) 
```

Füllt das Innere einer geschlossenen Kardinal‑Spline‑Kurve, die durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus. Diese Methode verwendet eine Standardspannung von 0.5.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Spline definieren. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Mitglied der [FillMode](/imaging/python-net/aspose.imaging/fillmode/) Aufzählung, die bestimmt, wie die Kurve gefüllt wird. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_148}


```
 fill_closed_curve(brush, points, fillmode) 
```

Füllt das Innere einer geschlossenen Kardinal‑Spline‑Kurve, die durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus. Diese Methode verwendet eine Standardspannung von 0.5.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Spline definieren. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) |  |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_149}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Füllt das Innere einer geschlossenen Kardinal‑Spline‑Kurve, die durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus und der Spannung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Ein [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Spline definieren. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Mitglied der [FillMode](/imaging/python-net/aspose.imaging/fillmode/) Aufzählung, die bestimmt, wie die Kurve gefüllt wird. |
| Spannung | float | Wert größer oder gleich 0.0F, der die Spannung der Kurve angibt. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_150}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Füllt das Innere einer geschlossenen Kardinal‑Spline‑Kurve, die durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus und der Spannung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Ein [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Spline definieren. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Mitglied der [FillMode](/imaging/python-net/aspose.imaging/fillmode/) Aufzählung, die bestimmt, wie die Kurve gefüllt wird. |
| Spannung | float | Wert größer oder gleich 0.0F, der die Spannung der Kurve angibt. |

### Method: fill_closed_curve_by_point(brush, points) {#fill_closed_curve_by_point_brush_points_151}


```
 fill_closed_curve_by_point(brush, points) 
```

Füllt das Innere einer geschlossenen Kardinal‑Spline‑Kurve, die durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen definiert ist. Diese Methode verwendet eine Standardspannung von 0.5 und den [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) Füllmodus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Spline definieren. |

### Method: fill_closed_curve_by_point_f(brush, points) {#fill_closed_curve_by_point_f_brush_points_152}


```
 fill_closed_curve_by_point_f(brush, points) 
```

Füllt das Innere einer geschlossenen Kardinal‑Spline‑Kurve, die durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen definiert ist. Diese Methode verwendet eine Standardspannung von 0.5 und den [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) Füllmodus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Spline definieren. |

### Method: fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension) {#fill_closed_curve_by_point_f_fill_mode_tension_brush_points_fillmode_tension_153}


```
 fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension) 
```

Füllt das Innere einer geschlossenen Kardinal‑Spline‑Kurve, die durch ein Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus und der Spannung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Ein [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Spline definieren. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Mitglied der [FillMode](/imaging/python-net/aspose.imaging/fillmode/) Aufzählung, die bestimmt, wie die Kurve gefüllt wird. |
| Spannung | float | Wert größer oder gleich 0.0F, der die Spannung der Kurve angibt. |

### Method: fill_closed_curve_by_point_fill_mode(brush, points, fillmode) {#fill_closed_curve_by_point_fill_mode_brush_points_fillmode_154}


```
 fill_closed_curve_by_point_fill_mode(brush, points, fillmode) 
```

Füllt das Innere einer geschlossenen Kardinal‑Spline‑Kurve, die durch ein Array von [Point](/imaging/python-net/aspose.imaging/point/) Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus. Diese Methode verwendet eine Standardspannung von 0.5.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von [Point](/imaging/python-net/aspose.imaging/point/) Strukturen, die die Spline definieren. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Mitglied der [FillMode](/imaging/python-net/aspose.imaging/fillmode/) Aufzählung, die bestimmt, wie die Kurve gefüllt wird. |

### Method: fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension) {#fill_closed_curve_by_point_fill_mode_tension_brush_points_fillmode_tension_155}


```
 fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension) 
```

Füllt das Innere einer geschlossenen Kardinal‑Spline‑Kurve, die durch ein Array von [Point](/imaging/python-net/aspose.imaging/point/) Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus und der Spannung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von [Point](/imaging/python-net/aspose.imaging/point/) Strukturen, die die Spline definieren. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Mitglied der [FillMode](/imaging/python-net/aspose.imaging/fillmode/) Aufzählung, die bestimmt, wie die Kurve gefüllt wird. |
| Spannung | float | Wert größer oder gleich 0.0F, der die Spannung der Kurve angibt. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_156}


```
 fill_ellipse(brush, rect) 
```

Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, angegeben durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die das Begrenzungsrechteck darstellt, das die Ellipse definiert. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_157}


```
 fill_ellipse(brush, rect) 
```

Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, angegeben durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die das Begrenzungsrechteck darstellt, das die Ellipse definiert. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_158}


```
 fill_ellipse(brush, x, y, width, height) 
```

Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| x | float | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| y | float | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| width | float | Breite des Begrenzungsrechtecks, das die Ellipse definiert. |
| height | float | Höhe des Begrenzungsrechtecks, das die Ellipse definiert. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_159}


```
 fill_ellipse(brush, x, y, width, height) 
```

Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| x | int | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| y | int | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| width | int | Breite des Begrenzungsrechtecks, das die Ellipse definiert. |
| height | int | Höhe des Begrenzungsrechtecks, das die Ellipse definiert. |

### Method: fill_ellipse_at_xywh(brush, x, y, width, height) {#fill_ellipse_at_xywh_brush_x_y_width_height_160}


```
 fill_ellipse_at_xywh(brush, x, y, width, height) 
```

Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| x | int | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| y | int | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| width | int | Breite des Begrenzungsrechtecks, das die Ellipse definiert. |
| height | int | Höhe des Begrenzungsrechtecks, das die Ellipse definiert. |

### Method: fill_ellipse_at_xywhf(brush, x, y, width, height) {#fill_ellipse_at_xywhf_brush_x_y_width_height_161}


```
 fill_ellipse_at_xywhf(brush, x, y, width, height) 
```

Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| x | float | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| y | float | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| width | float | Breite des Begrenzungsrechtecks, das die Ellipse definiert. |
| height | float | Höhe des Begrenzungsrechtecks, das die Ellipse definiert. |

### Method: fill_ellipse_in_rect(brush, rect) {#fill_ellipse_in_rect_brush_rect_162}


```
 fill_ellipse_in_rect(brush, rect) 
```

Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, angegeben durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die das Begrenzungsrechteck darstellt, das die Ellipse definiert. |

### Method: fill_ellipse_in_rect_f(brush, rect) {#fill_ellipse_in_rect_f_brush_rect_163}


```
 fill_ellipse_in_rect_f(brush, rect) 
```

Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, angegeben durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die das Begrenzungsrechteck darstellt, das die Ellipse definiert. |

### Method: fill_path(brush, path) {#fill_path_brush_path_164}


```
 fill_path(brush, path) 
```

Füllt das Innere eines [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) stellt den Pfad zum Füllen dar. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_165}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, angegeben durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur und zwei Radiallinien.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur, die das Begrenzungsrechteck darstellt, das die Ellipse definiert, aus der das Kuchenstück stammt. |
| start_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zur ersten Seite des Kuchenstücks. |
| sweep_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom Parameter _startAngle_ zur zweiten Seite des Kuchenstücks. |


**See also:**

**[Example # 1](#example_95)**: The following example shows how to compose an animated GIF image from individ...


### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_166}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, angegeben durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur und zwei Radiallinien.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur, die das Begrenzungsrechteck darstellt, das die Ellipse definiert, aus der das Kuchenstück stammt. |
| start_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zur ersten Seite des Kuchenstücks. |
| sweep_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom Parameter _startAngle_ zur zweiten Seite des Kuchenstücks. |


**See also:**

**[Example # 1](#example_95)**: The following example shows how to compose an animated GIF image from individ...


### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_167}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, angegeben durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| x | float | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der das Kuchenstück stammt. |
| y | float | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der das Kuchenstück stammt. |
| width | float | Breite des Begrenzungsrechtecks, das die Ellipse definiert, aus der das Kuchenstück stammt. |
| height | float | Höhe des Begrenzungsrechtecks, das die Ellipse definiert, aus der der Kuchenabschnitt stammt. |
| start_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zur ersten Seite des Kuchenstücks. |
| sweep_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom Parameter _startAngle_ zur zweiten Seite des Kuchenstücks. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_168}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, angegeben durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| x | int | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der das Kuchenstück stammt. |
| y | int | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der das Kuchenstück stammt. |
| width | int | Breite des Begrenzungsrechtecks, das die Ellipse definiert, aus der das Kuchenstück stammt. |
| height | int | Höhe des Begrenzungsrechtecks, das die Ellipse definiert, aus der der Kuchenabschnitt stammt. |
| start_angle | int | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zur ersten Seite des Kuchenstücks. |
| sweep_angle | int | Winkel in Grad, gemessen im Uhrzeigersinn vom Parameter _startAngle_ zur zweiten Seite des Kuchenstücks. |

### Method: fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_at_xy_brush_x_y_width_height_start_angle_sweep_angle_169}


```
 fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle) 
```

Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, angegeben durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| x | int | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der das Kuchenstück stammt. |
| y | int | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der das Kuchenstück stammt. |
| width | int | Breite des Begrenzungsrechtecks, das die Ellipse definiert, aus der das Kuchenstück stammt. |
| height | int | Höhe des Begrenzungsrechtecks, das die Ellipse definiert, aus der der Kuchenabschnitt stammt. |
| start_angle | int | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zur ersten Seite des Kuchenstücks. |
| sweep_angle | int | Winkel in Grad, gemessen im Uhrzeigersinn vom Parameter _startAngle_ zur zweiten Seite des Kuchenstücks. |

### Method: fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_at_xyf_brush_x_y_width_height_start_angle_sweep_angle_170}


```
 fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle) 
```

Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, angegeben durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| x | float | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der das Kuchenstück stammt. |
| y | float | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der das Kuchenstück stammt. |
| width | float | Breite des Begrenzungsrechtecks, das die Ellipse definiert, aus der das Kuchenstück stammt. |
| height | float | Höhe des Begrenzungsrechtecks, das die Ellipse definiert, aus der der Kuchenabschnitt stammt. |
| start_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zur ersten Seite des Kuchenstücks. |
| sweep_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom Parameter _startAngle_ zur zweiten Seite des Kuchenstücks. |

### Method: fill_pie_in_rect(brush, rect, start_angle, sweep_angle) {#fill_pie_in_rect_brush_rect_start_angle_sweep_angle_171}


```
 fill_pie_in_rect(brush, rect, start_angle, sweep_angle) 
```

Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, angegeben durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur und zwei Radiallinien.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur, die das Begrenzungsrechteck darstellt, das die Ellipse definiert, aus der das Kuchenstück stammt. |
| start_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zur ersten Seite des Kuchenstücks. |
| sweep_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom Parameter _startAngle_ zur zweiten Seite des Kuchenstücks. |

### Method: fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle) {#fill_pie_in_rect_f_brush_rect_start_angle_sweep_angle_172}


```
 fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle) 
```

Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, angegeben durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur und zwei Radiallinien.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die das Begrenzungsrechteck darstellt, das die Ellipse definiert, aus der der Kuchenabschnitt stammt. |
| start_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zur ersten Seite des Kuchenstücks. |
| sweep_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom Parameter _startAngle_ zur zweiten Seite des Kuchenstücks. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_173}


```
 fill_polygon(brush, points) 
```

Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen und den [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) Füllmodus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Eckpunkte des auszufüllenden Polygons darstellen. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_174}


```
 fill_polygon(brush, points) 
```

Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen und den [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) Füllmodus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Eckpunkte des auszufüllenden Polygons darstellen. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_175}


```
 fill_polygon(brush, points, fill_mode) 
```

Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, unter Verwendung des angegebenen Füllmodus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Eckpunkte des auszufüllenden Polygons darstellen. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Mitglied der [FillMode](/imaging/python-net/aspose.imaging/fillmode/) Aufzählung, die den Füllstil bestimmt. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_176}


```
 fill_polygon(brush, points, fill_mode) 
```

Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, unter Verwendung des angegebenen Füllmodus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Eckpunkte des auszufüllenden Polygons darstellen. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Mitglied der [FillMode](/imaging/python-net/aspose.imaging/fillmode/) Aufzählung, die den Füllstil bestimmt. |

### Method: fill_polygon_by_point(brush, points) {#fill_polygon_by_point_brush_points_177}


```
 fill_polygon_by_point(brush, points) 
```

Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen und den [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) Füllmodus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Eckpunkte des auszufüllenden Polygons darstellen. |

### Method: fill_polygon_by_point_f(brush, points) {#fill_polygon_by_point_f_brush_points_178}


```
 fill_polygon_by_point_f(brush, points) 
```

Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen und den [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) Füllmodus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Eckpunkte des auszufüllenden Polygons darstellen. |

### Method: fill_polygon_by_point_f_fill_mode(brush, points, fill_mode) {#fill_polygon_by_point_f_fill_mode_brush_points_fill_mode_179}


```
 fill_polygon_by_point_f_fill_mode(brush, points, fill_mode) 
```

Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, unter Verwendung des angegebenen Füllmodus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array von [PointF](/imaging/python-net/aspose.imaging/pointf/) Strukturen, die die Eckpunkte des auszufüllenden Polygons darstellen. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Mitglied der [FillMode](/imaging/python-net/aspose.imaging/fillmode/) Aufzählung, die den Füllstil bestimmt. |

### Method: fill_polygon_by_point_fill_mode(brush, points, fill_mode) {#fill_polygon_by_point_fill_mode_brush_points_fill_mode_180}


```
 fill_polygon_by_point_fill_mode(brush, points, fill_mode) 
```

Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch [Point](/imaging/python-net/aspose.imaging/point/) Strukturen, unter Verwendung des angegebenen Füllmodus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array von [Point](/imaging/python-net/aspose.imaging/point/) Strukturen, die die Eckpunkte des auszufüllenden Polygons darstellen. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Mitglied der [FillMode](/imaging/python-net/aspose.imaging/fillmode/) Aufzählung, die den Füllstil bestimmt. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_181}


```
 fill_rectangle(brush, rect) 
```

Füllt das Innere eines Rechtecks, angegeben durch eine [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur, die das auszufüllende Rechteck darstellt. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_182}


```
 fill_rectangle(brush, rect) 
```

Füllt das Innere eines Rechtecks, angegeben durch eine [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Struktur, die das auszufüllende Rechteck darstellt. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_183}


```
 fill_rectangle(brush, x, y, width, height) 
```

Füllt das Innere eines Rechtecks, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| x | float | Die x‑Koordinate der oberen linken Ecke des auszufüllenden Rechtecks. |
| y | float | Die y‑Koordinate der oberen linken Ecke des auszufüllenden Rechtecks. |
| width | float | Breite des auszufüllenden Rechtecks. |
| height | float | Höhe des auszufüllenden Rechtecks. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_184}


```
 fill_rectangle(brush, x, y, width, height) 
```

Füllt das Innere eines Rechtecks, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| x | int | Die x‑Koordinate der oberen linken Ecke des auszufüllenden Rechtecks. |
| y | int | Die y‑Koordinate der oberen linken Ecke des auszufüllenden Rechtecks. |
| width | int | Breite des auszufüllenden Rechtecks. |
| height | int | Höhe des auszufüllenden Rechtecks. |

### Method: fill_rectangle_f(brush, rect) {#fill_rectangle_f_brush_rect_185}


```
 fill_rectangle_f(brush, rect) 
```

Füllt das Innere eines Rechtecks, angegeben durch eine [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Struktur, die das auszufüllende Rechteck darstellt. |

### Method: fill_rectangle_f_with_brush(brush, x, y, width, height) {#fill_rectangle_f_with_brush_brush_x_y_width_height_186}


```
 fill_rectangle_f_with_brush(brush, x, y, width, height) 
```

Füllt das Innere eines Rechtecks, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| x | float | Die x‑Koordinate der oberen linken Ecke des auszufüllenden Rechtecks. |
| y | float | Die y‑Koordinate der oberen linken Ecke des auszufüllenden Rechtecks. |
| width | float | Breite des auszufüllenden Rechtecks. |
| height | float | Höhe des auszufüllenden Rechtecks. |

### Method: fill_rectangle_with_brush(brush, x, y, width, height) {#fill_rectangle_with_brush_brush_x_y_width_height_187}


```
 fill_rectangle_with_brush(brush, x, y, width, height) 
```

Füllt das Innere eines Rechtecks, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| x | int | Die x‑Koordinate der oberen linken Ecke des auszufüllenden Rechtecks. |
| y | int | Die y‑Koordinate der oberen linken Ecke des auszufüllenden Rechtecks. |
| width | int | Breite des auszufüllenden Rechtecks. |
| height | int | Höhe des auszufüllenden Rechtecks. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_188}


```
 fill_rectangles(brush, rects) 
```

Füllt die Innenbereiche einer Reihe von Rechtecken, angegeben durch [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Strukturen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| rects | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | Array von [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Strukturen, die die auszufüllenden Rechtecke darstellen. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_189}


```
 fill_rectangles(brush, rects) 
```

Füllt die Innenbereiche einer Reihe von Rechtecken, angegeben durch [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Strukturen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Array von [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Strukturen, die die auszufüllenden Rechtecke darstellen. |

### Method: fill_rectangles_f(brush, rects) {#fill_rectangles_f_brush_rects_190}


```
 fill_rectangles_f(brush, rects) 
```

Füllt die Innenbereiche einer Reihe von Rechtecken, angegeben durch [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) Strukturen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Array von [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) Strukturen, die die auszufüllenden Rechtecke darstellen. |

### Method: fill_region(brush, region) {#fill_region_brush_region_191}


```
 fill_region(brush, region) 
```

Füllt das Innere einer [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) bestimmt die Eigenschaften der Füllung. |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | [Region](/imaging/python-net/aspose.imaging/region/) das den auszufüllenden Bereich darstellt. |

### Method: measure_string(text, font, layout_area, string_format) {#measure_string_text_font_layout_area_string_format_192}


```
 measure_string(text, font, layout_area, string_format) 
```

Misst die angegebene Textzeichenfolge mit den angegebenen Parametern

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| text | string | Der zu messende Text. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Die zu messende Schriftart. |
| layout_area | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Der Layout‑Bereich. |
| string_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Das Zeichenkettenformat. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Größe in Pixeln der gemessenen Textzeichenkette |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_193}


```
 multiply_transform(matrix) 
```

Multipliziert die [Matrix](/imaging/python-net/aspose.imaging/matrix/), die die lokale geometrische Transformation dieses [Graphics](/imaging/python-net/aspose.imaging/graphics/) darstellt, mit der angegebenen [Matrix](/imaging/python-net/aspose.imaging/matrix/) durch Voranstellen der angegebenen [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Die [Matrix](/imaging/python-net/aspose.imaging/matrix/), mit der die geometrische Transformation multipliziert wird. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_194}


```
 multiply_transform(matrix, order) 
```

Multipliziert die [Matrix](/imaging/python-net/aspose.imaging/matrix/), die die lokale geometrische Transformation dieses [Graphics](/imaging/python-net/aspose.imaging/graphics/) darstellt, mit der angegebenen [Matrix](/imaging/python-net/aspose.imaging/matrix/) in der angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Die [Matrix](/imaging/python-net/aspose.imaging/matrix/), mit der die geometrische Transformation multipliziert wird. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Ein [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/), der angibt, in welcher Reihenfolge die beiden Matrizen zu multiplizieren sind. |

### Method: rotate_transform(angle) {#rotate_transform_angle_195}


```
 rotate_transform(angle) 
```

Dreht die lokale geometrische Transformation um den angegebenen Betrag. Diese Methode fügt die Rotation der Transformation voran.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_196}


```
 rotate_transform(angle, order) 
```

Dreht die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Ein [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/), der angibt, ob die Rotationsmatrix angehängt oder vorangestellt wird. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_197}


```
 scale_transform(sx, sy) 
```

Skaliert die lokale geometrische Transformation um die angegebenen Werte. Diese Methode fügt die Skalierungs-Matrix der Transformation voran.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| sx | float | Der Betrag, um den die Transformation in x-Richtung skaliert wird. |
| sy | float | Der Betrag, um den die Transformation in y-Richtung skaliert wird. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_198}


```
 scale_transform(sx, sy, order) 
```

Skaliert die lokale geometrische Transformation um die angegebenen Werte in der angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| sx | float | Der Betrag, um den die Transformation in x-Richtung skaliert wird. |
| sy | float | Der Betrag, um den die Transformation in y-Richtung skaliert wird. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Ein [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) der angibt, ob die Skalierungsmatrix angehängt oder vorangestellt werden soll. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_199}


```
 translate_transform(dx, dy) 
```

Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. Diese Methode fügt die Translation der Transformation voran.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dx | float | Der Wert der Verschiebung in x. |
| dy | float | Der Wert der Verschiebung in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_200}


```
 translate_transform(dx, dy, order) 
```

Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dx | float | Der Wert der Verschiebung in x. |
| dy | float | Der Wert der Verschiebung in y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Die Reihenfolge (voranstellen oder anhängen), in der die Verschiebung angewendet wird. |

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

#Erstellt eine Instanz eines Dateistreams.
with open(r"C:\temp\output.png", "w+b") as stream:
	#Erstelle eine Instanz von PngOptions und setze deren verschiedene Eigenschaften.
	pngOptions = PngOptions()
	#Setze die Quelle für PngOptions.
	pngOptions.source = StreamSource(stream)
	#Erstelle eine Instanz von Image.
	with Image.create(pngOptions, 500, 500) as image:
		#Erstelle und initialisiere eine Instanz der Graphics Klasse.
		graphics = Graphics(image)
		#Lösche die Graphics-Oberfläche.
		graphics.clear(Color.wheat);
		#Zeichne einen Bogen, indem du das Pen-Objekt mit schwarzer Farbe angibst, 
		#ein Rechteck, das den Bogen umgibt, Startwinkel und Sweep-Winkel.
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#Zeichne eine Bézierkurve, indem du das Pen-Objekt mit blauer Farbe und Koordinatenpunkten angibst.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#Zeichnen Sie eine Kurve, indem Sie das Pen-Objekt mit grüner Farbe und einem Array von Punkten angeben.
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#Zeichnen Sie eine Ellipse mit dem Pen-Objekt und einem umgebenden Rechteck.
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#Zeichnen Sie eine Linie
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#Zeichnen Sie ein Kuchenstück.
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#Zeichnen Sie ein Polygon, indem Sie das Pen-Objekt mit roter Farbe und einem Array von Punkten angeben.
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#Zeichnen Sie ein Rechteck.
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#Erstellen Sie ein SolidBrush-Objekt und setzen Sie dessen verschiedene Eigenschaften.
		brush = SolidBrush()
		brush.color = Color.purple
		#Zeichnen Sie einen String mit dem SolidBrush-Objekt und Font an einem bestimmten Punkt.
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# Alle Änderungen speichern.
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


# Erstelle eine Instanz eines Dateistreams
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# Erstellen Sie eine Instanz von TiffOptions und setzen Sie deren verschiedene Eigenschaften
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Legen Sie die Quelle für die Instanz von ImageOptions fest
	tiffOptions.source = StreamSource(stream)
	# Erstellen Sie eine Instanz von Image
	with Image.create(tiffOptions, 500, 500) as image:
		# Erstelle und initialisiere eine Instanz der Graphics Klasse.
		graphics = Graphics(image)
		# Lösche die Graphics-Oberfläche.
		graphics.clear(Color.wheat);
		# Erstellen Sie eine Instanz der Klasse GraphicsPath
		graphics_path = GraphicsPath()
		# Erstellen Sie eine Instanz der Klasse Figure
		figure = Figure()
		# Fügen Sie dem Figure-Objekt Formen hinzu
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# Fügen Sie das Figure-Objekt zu GraphicsPath hinzu
		graphics_path.add_figure(figure)
		# Zeichnen Sie den Pfad mit dem Pen-Objekt in der Farbe Schwarz
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# Alle Änderungen speichern.
		image.save()


```

### This example shows the creation and usage Pen objects. The example creates a new Image and draw rectangles on the Image surface. {#example_14}
``` python

from aspose.imaging import Image, Graphics, Color, Pen, Rectangle, Point, Size
from aspose.imaging.brushes import HatchBrush
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

# Erstellen Sie eine Instanz von BmpOptions und setzen Sie deren verschiedenen Eigenschaften
bmpOptions = BmpOptions()
bmpOptions.bits_per_pixel = 24
# Erstellen Sie eine Instanz von FileCreateSource und weisen Sie sie als Quelle für die Instanz von BmpOptions zu
# Der zweite boolesche Parameter bestimmt, ob die zu erstellende Datei temporär ist oder nicht
bmpOptions.source = FileCreateSource(r"C:\temp\sample.bmp", False)
# Erstellen Sie eine Instanz von Image am angegebenen Pfad
with Image.create(bmpOptions, 500, 500) as image:
	# Erstellen Sie eine Instanz von Graphics und initialisieren Sie sie mit einem Image‑Objekt
	graphics = Graphics(image)
	# Löschen Sie die Graphics‑Oberfläche mit weißer Farbe
	graphics.clear(Color.white)
	#Erstellen Sie eine Instanz von Pen mit der Farbe Rot und einer Breite von 5
	pen = Pen(Color.red, 5.0);
	# Erstellen Sie eine Instanz von HatchBrush und setzen Sie deren Eigenschaften
	brush = HatchBrush()
	brush.background_color = Color.wheat;
	brush.foreground_color = Color.red;
	# Erstellen Sie eine Instanz von Pen
	# Initialisieren Sie es mit einem HatchBrush-Objekt und einer Breite
	brusedpen = Pen(brush, 5.0)
	# Zeichnen Sie Rechtecke, indem Sie ein Pen-Objekt angeben
	graphics.draw_rectangles(pen, [
		Rectangle(Point(210, 210), Size(100, 100)),
		Rectangle(Point(110, 110), Size(100, 100)),
		Rectangle(Point(310, 310), Size(100, 100)) ])

	# Zeichnen Sie Rechtecke, indem Sie ein Pen-Objekt angeben
	graphics.draw_rectangles(brusedpen, [
		Rectangle(Point(310, 110), Size(100, 100)),
		Rectangle(Point(110, 310), Size(100, 100)) ])

	# Alle Änderungen speichern.
	image.save()


```

### The following example shows how to compose an animated GIF image from individual GIF blocks. {#example_95}
``` python
from aspose.imaging.fileformats.gif.blocks import GifFrameBlock
from aspose.imaging.fileformats.gif import GifImage 
from aspose.imaging.brushes import SolidBrush
from aspose.imaging import Graphics, Color

# Erstellen Sie ein GIF-Bild mit 100 × 100 px.
# Der erste Block ist standardmäßig vollständig schwarz.
with GifFrameBlock(100, 100) as firstBlock:
	with GifImage(firstBlock) as gifImage:
		# Der erste Kreis ist rot
		brush1 = SolidBrush(Color.red)

		# Der zweite Kreis ist schwarz
		brush2 = SolidBrush(Color.black)

		# Erhöhen Sie schrittweise den Winkel der roten Bogenform.
		for angle in range(10, 361, 10):
			block = GifFrameBlock(100, 100)
			gr = Graphics(block)
			gr.fill_pie(brush1, block.bounds, 0, angle)
			gifImage.add_block(block)
		
		# Erhöhen Sie schrittweise den Winkel des schwarzen Bogens und entfernen Sie den roten Bogen.
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
# Erstellen Sie ein PNG-Bild mit 100 × 100 px.
with PngImage(100, 100) as png_image:
	# Führen Sie einige Bildverarbeitungen durch, z. B. das gesamte Bild rot füllen.
	graphics = Graphics(png_image)
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, png_image.bounds)
	# In einer Datei speichern.
	png_image.save(join(dir_, "output.png"))


```

