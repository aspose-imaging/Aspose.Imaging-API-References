---
title: "Graphics Classe"
type: docs
weight: 5030
url: /fr/python-net/aspose.imaging/graphics/
---

**Summary:** Represents the graphics according to the graphics engine used in the current assembly.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Graphics

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Graphics(source_image)](#Graphics_source_image_1) | Initialise une nouvelle instance de la [Graphics](/imaging/python-net/aspose.imaging/graphics/) classe. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| clip | [Region](/imaging/python-net/aspose.imaging/region/) | r/w | Obtient ou définit la région de découpage. |
| compositing_quality | [CompositingQuality](/imaging/python-net/aspose.imaging/compositingquality/) | r/w | Obtient ou définit la qualité de composition. |
| dpi_x | float | r | Obtient la résolution horizontale de ce `aspose.imaging.Graphics`. |
| dpi_y | float | r | Obtient la résolution verticale de ce `aspose.imaging.Graphics`. |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | r | Obtient l'image. |
| interpolation_mode | [InterpolationMode](/imaging/python-net/aspose.imaging/interpolationmode/) | r/w | Obtient ou définit le mode d'interpolation. |
| is_in_begin_update_call | bool | r | Obtient une valeur indiquant si le graphique est dans l'état d'appel BeginUpdate. |
| page_scale | float | r/w | Obtient ou définit l'échelle entre les unités du monde et les unités de page pour ce `aspose.imaging.Graphics`. |
| page_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | r/w | Obtient ou définit l'unité de mesure utilisée pour les coordonnées de page dans ce `aspose.imaging.Graphics`. |
| paintable_image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | r/w | Obtient ou définit les options d'image, utilisées pour créer des images vactor peintables à dessiner. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Obtient ou définit le mode d'anticrénelage. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Obtient ou définit l'indice de rendu du texte. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtient ou définit une copie de la transformation géométrique du monde pour ce [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| begin_update() | Démarre la mise en cache des opérations graphiques suivantes. Les effets graphiques appliqués par la suite ne seront pas appliqués immédiatement ; à la place, EndUpdate provoquera l'application de tous les effets en une fois. |
| [clear(color)](#clear_color_1) | Efface la surface graphique en utilisant la couleur spécifiée. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_2) | Dessine un arc représentant une partie d'une ellipse spécifiée par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_3) | Dessine un arc représentant une partie d'une ellipse spécifiée par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4) | Dessine un arc représentant une partie d'une ellipse spécifiée par une paire de coordonnées, une largeur et une hauteur. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5) | Dessine un arc représentant une partie d'une ellipse spécifiée par une paire de coordonnées, une largeur et une hauteur. |
| [draw_arc_in_rect(pen, rect, start_angle, sweep_angle)](#draw_arc_in_rect_pen_rect_start_angle_sweep_angle_6) | Dessine un arc représentant une partie d'une ellipse spécifiée par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle)](#draw_arc_in_rect_f_pen_rect_start_angle_sweep_angle_7) | Dessine un arc représentant une partie d'une ellipse spécifiée par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_xy_pen_x_y_width_height_start_angle_sweep_angle_8) | Dessine un arc représentant une partie d'une ellipse spécifiée par une paire de coordonnées, une largeur et une hauteur. |
| [draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_xyf_pen_x_y_width_height_start_angle_sweep_angle_9) | Dessine un arc représentant une partie d'une ellipse spécifiée par une paire de coordonnées, une largeur et une hauteur. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_10) | Dessine une spline de Bézier définie par quatre structures [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_11) | Dessine une spline de Bézier définie par quatre structures [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4)](#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_12) | Dessine une spline de Bézier définie par quatre paires ordonnées de coordonnées représentant des points. |
| [draw_bezier_by_points(pen, pt1, pt2, pt3, pt4)](#draw_bezier_by_points_pen_pt1_pt2_pt3_pt4_13) | Dessine une spline de Bézier définie par quatre structures [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4)](#draw_bezier_by_points_f_pen_pt1_pt2_pt3_pt4_14) | Dessine une spline de Bézier définie par quatre structures [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_15) | Dessine une série de splines de Bézier à partir d'un tableau de structures [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_16) | Dessine une série de splines de Bézier à partir d'un tableau de structures [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_beziers_by_pt_array(pen, points)](#draw_beziers_by_pt_array_pen_points_17) | Dessine une série de splines de Bézier à partir d'un tableau de structures [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_beziers_by_pt_array_f(pen, points)](#draw_beziers_by_pt_array_f_pen_points_18) | Dessine une série de splines de Bézier à partir d'un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_19) | Dessine une spline cardinal fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). Cette méthode utilise une tension par défaut de 0,5 et le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_20) | Dessine une spline cardinal fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). Cette méthode utilise une tension par défaut de 0,5 et le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_21) | Dessine une spline cardinal fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant une tension spécifiée. Cette méthode utilise le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) par défaut. |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_22) | Dessine une spline cardinal fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant une tension spécifiée. Cette méthode utilise le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) par défaut. |
| [draw_closed_curve_by_points(pen, points)](#draw_closed_curve_by_points_pen_points_23) | Dessine une spline cardinal fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). Cette méthode utilise une tension par défaut de 0,5 et le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve_by_points_f(pen, points)](#draw_closed_curve_by_points_f_pen_points_24) | Dessine une spline cardinal fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). Cette méthode utilise une tension par défaut de 0,5 et le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve_by_points_f_tension(pen, points, tension)](#draw_closed_curve_by_points_f_tension_pen_points_tension_25) | Dessine une spline cardinal fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant une tension spécifiée. Cette méthode utilise le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) par défaut. |
| [draw_closed_curve_by_points_tension(pen, points, tension)](#draw_closed_curve_by_points_tension_pen_points_tension_26) | Dessine une spline cardinal fermée définie par un tableau de structures [Point](/imaging/python-net/aspose.imaging/point/) en utilisant une tension spécifiée. Cette méthode utilise le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) par défaut. |
| [draw_curve(pen, points)](#draw_curve_pen_points_27) | Dessine une spline cardinal à travers un tableau spécifié de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). Cette méthode utilise une tension par défaut de 0,5. |
| [draw_curve(pen, points)](#draw_curve_pen_points_28) | Dessine une spline cardinal à travers un tableau spécifié de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). Cette méthode utilise une tension par défaut de 0,5. |
| [draw_curve(pen, points, offset, number_of_segments)](#draw_curve_pen_points_offset_number_of_segments_29) | Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). Le dessin commence décalé depuis le début du tableau.<br/>            Cette méthode utilise une tension par défaut de 0,5. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_30) | Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant une tension spécifiée. Le dessin commence décalé depuis le début du tableau. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_31) | Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant une tension spécifiée. Le dessin commence décalé depuis le début du tableau. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_32) | Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant une tension spécifiée. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_33) | Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant une tension spécifiée. |
| [draw_curve_by_point_fs(pen, points)](#draw_curve_by_point_fs_pen_points_34) | Dessine une spline cardinale à travers un tableau spécifié de structures [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_curve_by_point_fs_tension(pen, points, tension)](#draw_curve_by_point_fs_tension_pen_points_tension_35) | Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant une tension spécifiée. |
| [draw_curve_by_points(pen, points)](#draw_curve_by_points_pen_points_36) | Dessine une spline cardinal à travers un tableau spécifié de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). Cette méthode utilise une tension par défaut de 0,5. |
| [draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension)](#draw_curve_by_points_f_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_37) | Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant une tension spécifiée. Le dessin commence décalé depuis le début du tableau. |
| [draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension)](#draw_curve_by_points_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_38) | Dessine une spline cardinale à travers un tableau spécifié de structures [Point](/imaging/python-net/aspose.imaging/point/) en utilisant une tension spécifiée. |
| [draw_curve_by_points_tension(pen, points, tension)](#draw_curve_by_points_tension_pen_points_tension_39) | Dessine une spline cardinale à travers un tableau spécifié de structures [Point](/imaging/python-net/aspose.imaging/point/) en utilisant une tension spécifiée. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_40) | Dessine une ellipse définie par un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) englobant. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_41) | Dessine une ellipse définie par un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) englobant. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_42) | Dessine une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une hauteur et une largeur. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_43) | Dessine une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une hauteur et une largeur. |
| [draw_ellipse_by_xy(pen, x, y, width, height)](#draw_ellipse_by_xy_pen_x_y_width_height_44) | Dessine une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une hauteur et une largeur. |
| [draw_ellipse_by_xyf(pen, x, y, width, height)](#draw_ellipse_by_xyf_pen_x_y_width_height_45) | Dessine une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une hauteur et une largeur. |
| [draw_ellipse_f(pen, rect)](#draw_ellipse_f_pen_rect_46) | Dessine une ellipse définie par un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) englobant. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_47) | Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_48) | Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_49) | Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_50) | Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_51) | Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_52) | Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_53) | Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_54) | Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image(source_image, point)](#draw_image_source_image_point_55) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié, en utilisant sa taille physique originale, à l'emplacement spécifié. |
| [draw_image(source_image, point)](#draw_image_source_image_point_56) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié, en utilisant sa taille physique originale, à l'emplacement spécifié. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_57) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_58) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_59) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_60) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_61) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_62) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_63) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_64) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_65) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_66) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_67) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié, en utilisant sa taille physique originale, à l'emplacement spécifié. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_68) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié, en utilisant sa taille physique originale, à l'emplacement spécifié. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_69) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_70) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image_at_point(source_image, point)](#draw_image_at_point_source_image_point_71) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié, en utilisant sa taille physique originale, à l'emplacement spécifié. |
| [draw_image_at_point_f(source_image, point)](#draw_image_at_point_f_source_image_point_72) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié, en utilisant sa taille physique originale, à l'emplacement spécifié. |
| [draw_image_at_xy(source_image, x, y)](#draw_image_at_xy_source_image_x_y_73) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié, en utilisant sa taille physique originale, à l'emplacement spécifié. |
| [draw_image_at_xyf(source_image, x, y)](#draw_image_at_xyf_source_image_x_y_74) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié, en utilisant sa taille physique originale, à l'emplacement spécifié. |
| [draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit)](#draw_image_dest_point_f_src_rect_f_with_unit_image_dest_points_src_rect_src_unit_75) | Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_dest_point_f_src_rect_f_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_76) | Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect)](#draw_image_dest_points_f_src_rect_f_image_dest_points_src_rect_77) | Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image_dest_points_src_rect(image, dest_points, src_rect)](#draw_image_dest_points_src_rect_image_dest_points_src_rect_78) | Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit)](#draw_image_dest_points_src_rect_with_unit_image_dest_points_src_rect_src_unit_79) | Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_dest_points_src_rect_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_80) | Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_dest_rect_f_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_81) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_dest_rect_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_82) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image_in_rect(source_image, x, y, width, height)](#draw_image_in_rect_source_image_x_y_width_height_83) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image_in_rect_f(source_image, x, y, width, height)](#draw_image_in_rect_f_source_image_x_y_width_height_84) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image_in_rectangle(source_image, rect)](#draw_image_in_rectangle_source_image_rect_85) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image_points(image, dest_points)](#draw_image_points_image_dest_points_86) | Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image_points_f(image, dest_points)](#draw_image_points_f_image_dest_points_87) | Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image_rectangle_f(source_image, rect)](#draw_image_rectangle_f_source_image_rect_88) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_src_dest_rects_f_with_unit_source_image_rect_source_rect_destination_graphics_unit_89) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_src_dest_rects_with_unit_source_image_rect_source_rect_destination_graphics_unit_90) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_src_dst_rect_f_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_91) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_src_dst_rects_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_92) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit)](#draw_image_to_rect_f_with_unit_source_image_rect_destination_graphics_unit_93) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit)](#draw_image_to_rect_with_unit_source_image_rect_destination_graphics_unit_94) | Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée. |
| [draw_image_unscaled(source_image, point)](#draw_image_unscaled_source_image_point_95) | Dessine une image spécifiée en utilisant sa taille physique originale à un emplacement spécifié. |
| [draw_image_unscaled(source_image, rect)](#draw_image_unscaled_source_image_rect_96) | Dessine une image spécifiée en utilisant sa taille physique originale à un emplacement spécifié. |
| [draw_image_unscaled(source_image, x, y)](#draw_image_unscaled_source_image_x_y_97) | Dessine l'image spécifiée en utilisant sa taille physique originale à l'emplacement spécifié par une paire de coordonnées. |
| [draw_image_unscaled(source_image, x, y, width, height)](#draw_image_unscaled_source_image_x_y_width_height_98) | Dessine une image spécifiée en utilisant sa taille physique originale à un emplacement spécifié. |
| [draw_image_unscaled_and_clipped(source_image, rect)](#draw_image_unscaled_and_clipped_source_image_rect_99) | Dessine l'image spécifiée sans mise à l'échelle et la découpe, si nécessaire, pour l'adapter au rectangle spécifié. |
| [draw_image_unscaled_in_rectangle(source_image, rect)](#draw_image_unscaled_in_rectangle_source_image_rect_100) | Dessine une image spécifiée en utilisant sa taille physique originale à un emplacement spécifié. |
| [draw_image_unscaled_to_point(source_image, point)](#draw_image_unscaled_to_point_source_image_point_101) | Dessine une image spécifiée en utilisant sa taille physique originale à un emplacement spécifié. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_102) | Dessine une ligne reliant deux structures [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_103) | Dessine une ligne reliant deux structures [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_104) | Dessine une ligne reliant les deux points spécifiés par les paires de coordonnées. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_105) | Dessine une ligne reliant les deux points spécifiés par les paires de coordonnées. |
| [draw_line_by_xy(pen, x1, y1, x2, y2)](#draw_line_by_xy_pen_x1_y1_x2_y2_106) | Dessine une ligne reliant les deux points spécifiés par les paires de coordonnées. |
| [draw_line_f_by_xy(pen, x1, y1, x2, y2)](#draw_line_f_by_xy_pen_x1_y1_x2_y2_107) | Dessine une ligne reliant les deux points spécifiés par les paires de coordonnées. |
| [draw_line_point_f(pen, point1, point2)](#draw_line_point_f_pen_point1_point2_108) | Dessine une ligne reliant deux structures [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_lines(pen, points)](#draw_lines_pen_points_109) | Dessine une série de segments de ligne qui relient un tableau de structures [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_lines(pen, points)](#draw_lines_pen_points_110) | Dessine une série de segments de ligne qui relient un tableau de structures [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_lines_f(pen, points)](#draw_lines_f_pen_points_111) | Dessine une série de segments de ligne qui relient un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_path(pen, path)](#draw_path_pen_path_112) | Dessine un [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_113) | Dessine une forme de secteur définie par une ellipse spécifiée par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) et deux lignes radiales. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_114) | Dessine une forme de secteur définie par une ellipse spécifiée par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) et deux lignes radiales. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_115) | Dessine une forme de secteur définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_116) | Dessine une forme de secteur définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales. |
| [draw_pie_in_rect(pen, rect, start_angle, sweep_angle)](#draw_pie_in_rect_pen_rect_start_angle_sweep_angle_117) | Dessine une forme de secteur définie par une ellipse spécifiée par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) et deux lignes radiales. |
| [draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle)](#draw_pie_in_rect_f_pen_rect_start_angle_sweep_angle_118) | Dessine une forme de secteur définie par une ellipse spécifiée par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) et deux lignes radiales. |
| [draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_xy_pen_x_y_width_height_start_angle_sweep_angle_119) | Dessine une forme de secteur définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales. |
| [draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_xyf_pen_x_y_width_height_start_angle_sweep_angle_120) | Dessine une forme de secteur définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_121) | Dessine un polygone défini par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_122) | Dessine un polygone défini par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_polygon_f(pen, points)](#draw_polygon_f_pen_points_123) | Dessine un polygone défini par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_rect(pen, x, y, width, height)](#draw_rect_pen_x_y_width_height_124) | Dessine un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [draw_rect_f(pen, x, y, width, height)](#draw_rect_f_pen_x_y_width_height_125) | Dessine un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_126) | Dessine un rectangle spécifié par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_127) | Dessine un rectangle spécifié par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_128) | Dessine un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_129) | Dessine un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [draw_rectangle_f(pen, rect)](#draw_rectangle_f_pen_rect_130) | Dessine un rectangle spécifié par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_131) | Dessine une série de rectangles spécifiés par des structures [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_132) | Dessine une série de rectangles spécifiés par des structures [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_rectangles_f(pen, rects)](#draw_rectangles_f_pen_rects_133) | Dessine une série de rectangles spécifiés par des structures [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_string(s, font, brush, layout_rectangle)](#draw_string_s_font_brush_layout_rectangle_134) | Dessine la chaîne de texte spécifiée dans le rectangle spécifié avec le [Brush](/imaging/python-net/aspose.imaging/brush/) et le [Font](/imaging/python-net/aspose.imaging/font/) spécifiés. |
| [draw_string(s, font, brush, layout_rectangle, format)](#draw_string_s_font_brush_layout_rectangle_format_135) | Dessine la chaîne de texte spécifiée dans le rectangle spécifié avec le [Brush](/imaging/python-net/aspose.imaging/brush/) et le [Font](/imaging/python-net/aspose.imaging/font/) spécifiés en utilisant les attributs de formatage du [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) spécifié. |
| [draw_string(s, font, brush, point)](#draw_string_s_font_brush_point_136) | Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec le [Brush](/imaging/python-net/aspose.imaging/brush/) et le [Font](/imaging/python-net/aspose.imaging/font/) spécifiés. |
| [draw_string(s, font, brush, point, format)](#draw_string_s_font_brush_point_format_137) | Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec le [Brush](/imaging/python-net/aspose.imaging/brush/) et le [Font](/imaging/python-net/aspose.imaging/font/) spécifiés en utilisant les attributs de formatage du [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) spécifié. |
| [draw_string(s, font, brush, x, y)](#draw_string_s_font_brush_x_y_138) | Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec le [Brush](/imaging/python-net/aspose.imaging/brush/) et le [Font](/imaging/python-net/aspose.imaging/font/) spécifiés. |
| [draw_string(s, font, brush, x, y, format)](#draw_string_s_font_brush_x_y_format_139) | Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec le [Brush](/imaging/python-net/aspose.imaging/brush/) et le [Font](/imaging/python-net/aspose.imaging/font/) spécifiés en utilisant les attributs de formatage du [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) spécifié. |
| [draw_string_at_point_f(s, font, brush, point)](#draw_string_at_point_f_s_font_brush_point_140) | Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec le [Brush](/imaging/python-net/aspose.imaging/brush/) et le [Font](/imaging/python-net/aspose.imaging/font/) spécifiés. |
| [draw_string_at_point_f_format(s, font, brush, point, format)](#draw_string_at_point_f_format_s_font_brush_point_format_141) | Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec le [Brush](/imaging/python-net/aspose.imaging/brush/) et le [Font](/imaging/python-net/aspose.imaging/font/) spécifiés en utilisant les attributs de formatage du [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) spécifié. |
| [draw_string_at_xy(s, font, brush, x, y)](#draw_string_at_xy_s_font_brush_x_y_142) | Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec le [Brush](/imaging/python-net/aspose.imaging/brush/) et le [Font](/imaging/python-net/aspose.imaging/font/) spécifiés. |
| [draw_string_in_rect(s, font, brush, layout_rectangle)](#draw_string_in_rect_s_font_brush_layout_rectangle_143) | Dessine la chaîne de texte spécifiée dans le rectangle spécifié avec le [Brush](/imaging/python-net/aspose.imaging/brush/) et le [Font](/imaging/python-net/aspose.imaging/font/) spécifiés. |
| [draw_string_in_rect_f(s, font, brush, layout_rectangle, format)](#draw_string_in_rect_f_s_font_brush_layout_rectangle_format_144) | Dessine la chaîne de texte spécifiée dans le rectangle spécifié avec le [Brush](/imaging/python-net/aspose.imaging/brush/) et le [Font](/imaging/python-net/aspose.imaging/font/) spécifiés en utilisant les attributs de formatage du [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) spécifié. |
| end_update() | Termine la mise en cache des opérations graphiques démarrées après l'appel de BeginUpdate. Les opérations graphiques précédentes seront appliquées d'un coup lors de l'appel de cette méthode. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_145) | Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). Cette méthode utilise une tension par défaut de 0,5 et le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_146) | Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). Cette méthode utilise une tension par défaut de 0,5 et le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [fill_closed_curve(brush, points, fill_mode)](#fill_closed_curve_brush_points_fill_mode_147) | Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant le mode de remplissage spécifié. Cette méthode utilise une tension par défaut de 0,5. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_148) | Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant le mode de remplissage spécifié. Cette méthode utilise une tension par défaut de 0,5. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_149) | Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant le mode de remplissage et la tension spécifiés. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_150) | Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant le mode de remplissage et la tension spécifiés. |
| [fill_closed_curve_by_point(brush, points)](#fill_closed_curve_by_point_brush_points_151) | Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). Cette méthode utilise une tension par défaut de 0,5 et le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [fill_closed_curve_by_point_f(brush, points)](#fill_closed_curve_by_point_f_brush_points_152) | Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). Cette méthode utilise une tension par défaut de 0,5 et le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| fill_closed_curve_by_point_f_fill_mode(brush, points, fillmode) |  |
| [fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension)](#fill_closed_curve_by_point_f_fill_mode_tension_brush_points_fillmode_tension_153) | Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant le mode de remplissage et la tension spécifiés. |
| [fill_closed_curve_by_point_fill_mode(brush, points, fillmode)](#fill_closed_curve_by_point_fill_mode_brush_points_fillmode_154) | Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures [Point](/imaging/python-net/aspose.imaging/point/) en utilisant le mode de remplissage spécifié. Cette méthode utilise une tension par défaut de 0,5. |
| [fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension)](#fill_closed_curve_by_point_fill_mode_tension_brush_points_fillmode_tension_155) | Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures [Point](/imaging/python-net/aspose.imaging/point/) en utilisant le mode de remplissage et la tension spécifiés. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_156) | Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_157) | Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_158) | Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_159) | Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [fill_ellipse_at_xywh(brush, x, y, width, height)](#fill_ellipse_at_xywh_brush_x_y_width_height_160) | Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [fill_ellipse_at_xywhf(brush, x, y, width, height)](#fill_ellipse_at_xywhf_brush_x_y_width_height_161) | Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [fill_ellipse_in_rect(brush, rect)](#fill_ellipse_in_rect_brush_rect_162) | Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [fill_ellipse_in_rect_f(brush, rect)](#fill_ellipse_in_rect_f_brush_rect_163) | Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [fill_path(brush, path)](#fill_path_brush_path_164) | Remplit l'intérieur d'un [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_165) | Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) et deux lignes radiales. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_166) | Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) et deux lignes radiales. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_167) | Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_168) | Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales. |
| [fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_at_xy_brush_x_y_width_height_start_angle_sweep_angle_169) | Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales. |
| [fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_at_xyf_brush_x_y_width_height_start_angle_sweep_angle_170) | Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales. |
| [fill_pie_in_rect(brush, rect, start_angle, sweep_angle)](#fill_pie_in_rect_brush_rect_start_angle_sweep_angle_171) | Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) et deux lignes radiales. |
| [fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle)](#fill_pie_in_rect_f_brush_rect_start_angle_sweep_angle_172) | Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) et deux lignes radiales. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_173) | Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [PointF](/imaging/python-net/aspose.imaging/pointf/) et le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_174) | Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [PointF](/imaging/python-net/aspose.imaging/pointf/) et le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_175) | Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant le mode de remplissage spécifié. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_176) | Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant le mode de remplissage spécifié. |
| [fill_polygon_by_point(brush, points)](#fill_polygon_by_point_brush_points_177) | Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [PointF](/imaging/python-net/aspose.imaging/pointf/) et le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [fill_polygon_by_point_f(brush, points)](#fill_polygon_by_point_f_brush_points_178) | Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [PointF](/imaging/python-net/aspose.imaging/pointf/) et le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [fill_polygon_by_point_f_fill_mode(brush, points, fill_mode)](#fill_polygon_by_point_f_fill_mode_brush_points_fill_mode_179) | Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant le mode de remplissage spécifié. |
| [fill_polygon_by_point_fill_mode(brush, points, fill_mode)](#fill_polygon_by_point_fill_mode_brush_points_fill_mode_180) | Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [Point](/imaging/python-net/aspose.imaging/point/) en utilisant le mode de remplissage spécifié. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_181) | Remplit l'intérieur d'un rectangle spécifié par une structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_182) | Remplit l'intérieur d'un rectangle spécifié par une structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_183) | Remplit l'intérieur d'un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_184) | Remplit l'intérieur d'un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [fill_rectangle_f(brush, rect)](#fill_rectangle_f_brush_rect_185) | Remplit l'intérieur d'un rectangle spécifié par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [fill_rectangle_f_with_brush(brush, x, y, width, height)](#fill_rectangle_f_with_brush_brush_x_y_width_height_186) | Remplit l'intérieur d'un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [fill_rectangle_with_brush(brush, x, y, width, height)](#fill_rectangle_with_brush_brush_x_y_width_height_187) | Remplit l'intérieur d'un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_188) | Remplit l'intérieur d'une série de rectangles spécifiés par des structures [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_189) | Remplit l'intérieur d'une série de rectangles spécifiés par des structures [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [fill_rectangles_f(brush, rects)](#fill_rectangles_f_brush_rects_190) | Remplit l'intérieur d'une série de rectangles spécifiés par des structures [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [fill_region(brush, region)](#fill_region_brush_region_191) | Remplit l'intérieur d'une [Region](/imaging/python-net/aspose.imaging/region/). |
| [measure_string(text, font, layout_area, string_format)](#measure_string_text_font_layout_area_string_format_192) | Mesure la chaîne de texte spécifiée avec les paramètres spécifiés |
| [multiply_transform(matrix)](#multiply_transform_matrix_193) | Multiplie la [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui représente la transformation géométrique locale de ce [Graphics](/imaging/python-net/aspose.imaging/graphics/) par la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée en préfixant la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_194) | Multiplie la [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui représente la transformation géométrique locale de ce [Graphics](/imaging/python-net/aspose.imaging/graphics/) par la [Matrix](/imaging/python-net/aspose.imaging/matrix/) dans l'ordre spécifié. |
| reset_transform() | Réinitialise la propriété [Graphics.transform](/imaging/python-net/aspose.imaging/graphics/) à l'identité. |
| [rotate_transform(angle)](#rotate_transform_angle_195) | Fait pivoter la transformation géométrique locale de la valeur spécifiée. Cette méthode préfixe la rotation à la transformation. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_196) | Fait pivoter la transformation géométrique locale de la valeur spécifiée dans l'ordre indiqué. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_197) | Redimensionne la transformation géométrique locale par les valeurs spécifiées. Cette méthode préfixe la matrice d'échelle à la transformation. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_198) | Redimensionne la transformation géométrique locale par les valeurs spécifiées dans l'ordre indiqué. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_199) | Transalte la transformation géométrique locale des dimensions spécifiées. Cette méthode préfixe la translation à la transformation. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_200) | Transalte la transformation géométrique locale des dimensions spécifiées dans l'ordre indiqué. |


### Constructor: Graphics(source_image) {#Graphics_source_image_1}


```
 Graphics(source_image) 
```

Initialise une nouvelle instance de la [Graphics](/imaging/python-net/aspose.imaging/graphics/) classe.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image source. |

### Method: clear(color) {#clear_color_1}


```
 clear(color) 
```

Efface la surface graphique en utilisant la couleur spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | La couleur utilisée pour effacer la surface graphique. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...

**[Example # 2](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_2}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Dessine un arc représentant une partie d'une ellipse spécifiée par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de l'arc. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure qui définit les limites de l'ellipse. |
| start_angle | float | Angle en degrés mesuré dans le sens horaire depuis l'axe x jusqu'au point de départ de l'arc. |
| sweep_angle | float | Angle en degrés mesuré dans le sens horaire depuis le paramètre _startAngle_ jusqu'au point final de l'arc. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_3}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Dessine un arc représentant une partie d'une ellipse spécifiée par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de l'arc. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure qui définit les limites de l'ellipse. |
| start_angle | float | Angle en degrés mesuré dans le sens horaire depuis l'axe x jusqu'au point de départ de l'arc. |
| sweep_angle | float | Angle en degrés mesuré dans le sens horaire depuis le paramètre _startAngle_ jusqu'au point final de l'arc. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Dessine un arc représentant une partie d'une ellipse spécifiée par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de l'arc. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle qui définit l'ellipse. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle qui définit l'ellipse. |
| width | float | Largeur du rectangle qui définit l'ellipse. |
| height | float | Hauteur du rectangle qui définit l'ellipse. |
| start_angle | float | Angle en degrés mesuré dans le sens horaire depuis l'axe x jusqu'au point de départ de l'arc. |
| sweep_angle | float | Angle en degrés mesuré dans le sens horaire depuis le paramètre _startAngle_ jusqu'au point final de l'arc. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Dessine un arc représentant une partie d'une ellipse spécifiée par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de l'arc. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle qui définit l'ellipse. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle qui définit l'ellipse. |
| width | int | Largeur du rectangle qui définit l'ellipse. |
| height | int | Hauteur du rectangle qui définit l'ellipse. |
| start_angle | int | Angle en degrés mesuré dans le sens horaire depuis l'axe x jusqu'au point de départ de l'arc. |
| sweep_angle | int | Angle en degrés mesuré dans le sens horaire depuis le paramètre _startAngle_ jusqu'au point final de l'arc. |

### Method: draw_arc_in_rect(pen, rect, start_angle, sweep_angle) {#draw_arc_in_rect_pen_rect_start_angle_sweep_angle_6}


```
 draw_arc_in_rect(pen, rect, start_angle, sweep_angle) 
```

Dessine un arc représentant une partie d'une ellipse spécifiée par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de l'arc. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure qui définit les limites de l'ellipse. |
| start_angle | float | Angle en degrés mesuré dans le sens horaire depuis l'axe x jusqu'au point de départ de l'arc. |
| sweep_angle | float | Angle en degrés mesuré dans le sens horaire depuis le paramètre _startAngle_ jusqu'au point final de l'arc. |

### Method: draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle) {#draw_arc_in_rect_f_pen_rect_start_angle_sweep_angle_7}


```
 draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle) 
```

Dessine un arc représentant une partie d'une ellipse spécifiée par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de l'arc. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure qui définit les limites de l'ellipse. |
| start_angle | float | Angle en degrés mesuré dans le sens horaire depuis l'axe x jusqu'au point de départ de l'arc. |
| sweep_angle | float | Angle en degrés mesuré dans le sens horaire depuis le paramètre _startAngle_ jusqu'au point final de l'arc. |

### Method: draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_xy_pen_x_y_width_height_start_angle_sweep_angle_8}


```
 draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle) 
```

Dessine un arc représentant une partie d'une ellipse spécifiée par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de l'arc. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle qui définit l'ellipse. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle qui définit l'ellipse. |
| width | int | Largeur du rectangle qui définit l'ellipse. |
| height | int | Hauteur du rectangle qui définit l'ellipse. |
| start_angle | int | Angle en degrés mesuré dans le sens horaire depuis l'axe x jusqu'au point de départ de l'arc. |
| sweep_angle | int | Angle en degrés mesuré dans le sens horaire depuis le paramètre _startAngle_ jusqu'au point final de l'arc. |

### Method: draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_xyf_pen_x_y_width_height_start_angle_sweep_angle_9}


```
 draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle) 
```

Dessine un arc représentant une partie d'une ellipse spécifiée par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de l'arc. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle qui définit l'ellipse. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle qui définit l'ellipse. |
| width | float | Largeur du rectangle qui définit l'ellipse. |
| height | float | Hauteur du rectangle qui définit l'ellipse. |
| start_angle | float | Angle en degrés mesuré dans le sens horaire depuis l'axe x jusqu'au point de départ de l'arc. |
| sweep_angle | float | Angle en degrés mesuré dans le sens horaire depuis le paramètre _startAngle_ jusqu'au point final de l'arc. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_10}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Dessine une spline de Bézier définie par quatre structures [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de la courbe. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure qui représente le point de départ de la courbe. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure qui représente le premier point de contrôle de la courbe. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure qui représente le deuxième point de contrôle de la courbe. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure qui représente le point final de la courbe. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_11}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Dessine une spline de Bézier définie par quatre structures [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de la courbe. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure qui représente le point de départ de la courbe. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure qui représente le premier point de contrôle de la courbe. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure qui représente le deuxième point de contrôle de la courbe. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure qui représente le point final de la courbe. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) {#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_12}


```
 draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) 
```

Dessine une spline de Bézier définie par quatre paires ordonnées de coordonnées représentant des points.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de la courbe. |
| x1 | float | La coordonnée x du point de départ de la courbe. |
| y1 | float | La coordonnée y du point de départ de la courbe. |
| x2 | float | La coordonnée x du premier point de contrôle de la courbe. |
| y2 | float | La coordonnée y du premier point de contrôle de la courbe. |
| x3 | float | La coordonnée x du deuxième point de contrôle de la courbe. |
| y3 | float | La coordonnée y du deuxième point de contrôle de la courbe. |
| x4 | float | La coordonnée x du point final de la courbe. |
| y4 | float | La coordonnée y du point final de la courbe. |

### Method: draw_bezier_by_points(pen, pt1, pt2, pt3, pt4) {#draw_bezier_by_points_pen_pt1_pt2_pt3_pt4_13}


```
 draw_bezier_by_points(pen, pt1, pt2, pt3, pt4) 
```

Dessine une spline de Bézier définie par quatre structures [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de la courbe. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure qui représente le point de départ de la courbe. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure qui représente le premier point de contrôle de la courbe. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure qui représente le deuxième point de contrôle de la courbe. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure qui représente le point final de la courbe. |

### Method: draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4) {#draw_bezier_by_points_f_pen_pt1_pt2_pt3_pt4_14}


```
 draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4) 
```

Dessine une spline de Bézier définie par quatre structures [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de la courbe. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure qui représente le point de départ de la courbe. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure qui représente le premier point de contrôle de la courbe. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure qui représente le deuxième point de contrôle de la courbe. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure qui représente le point final de la courbe. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_15}


```
 draw_beziers(pen, points) 
```

Dessine une série de splines de Bézier à partir d'un tableau de structures [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de la courbe. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de structures [Point](/imaging/python-net/aspose.imaging/point/) qui représentent les points qui déterminent la courbe. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_16}


```
 draw_beziers(pen, points) 
```

Dessine une série de splines de Bézier à partir d'un tableau de structures [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de la courbe. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de structures [Point](/imaging/python-net/aspose.imaging/point/) qui représentent les points qui déterminent la courbe. |

### Method: draw_beziers_by_pt_array(pen, points) {#draw_beziers_by_pt_array_pen_points_17}


```
 draw_beziers_by_pt_array(pen, points) 
```

Dessine une série de splines de Bézier à partir d'un tableau de structures [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de la courbe. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de structures [Point](/imaging/python-net/aspose.imaging/point/) qui représentent les points qui déterminent la courbe. |

### Method: draw_beziers_by_pt_array_f(pen, points) {#draw_beziers_by_pt_array_f_pen_points_18}


```
 draw_beziers_by_pt_array_f(pen, points) 
```

Dessine une série de splines de Bézier à partir d'un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de la courbe. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représentent les points qui déterminent la courbe. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_19}


```
 draw_closed_curve(pen, points) 
```

Dessine une spline cardinal fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). Cette méthode utilise une tension par défaut de 0,5 et le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui définissent la spline. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_20}


```
 draw_closed_curve(pen, points) 
```

Dessine une spline cardinal fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). Cette méthode utilise une tension par défaut de 0,5 et le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui définissent la spline. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_21}


```
 draw_closed_curve(pen, points, tension) 
```

Dessine une spline cardinal fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant une tension spécifiée. Cette méthode utilise le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui définissent la spline. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_22}


```
 draw_closed_curve(pen, points, tension) 
```

Dessine une spline cardinal fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant une tension spécifiée. Cette méthode utilise le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui définissent la spline. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Method: draw_closed_curve_by_points(pen, points) {#draw_closed_curve_by_points_pen_points_23}


```
 draw_closed_curve_by_points(pen, points) 
```

Dessine une spline cardinal fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). Cette méthode utilise une tension par défaut de 0,5 et le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui définissent la spline. |

### Method: draw_closed_curve_by_points_f(pen, points) {#draw_closed_curve_by_points_f_pen_points_24}


```
 draw_closed_curve_by_points_f(pen, points) 
```

Dessine une spline cardinal fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). Cette méthode utilise une tension par défaut de 0,5 et le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui définissent la spline. |

### Method: draw_closed_curve_by_points_f_tension(pen, points, tension) {#draw_closed_curve_by_points_f_tension_pen_points_tension_25}


```
 draw_closed_curve_by_points_f_tension(pen, points, tension) 
```

Dessine une spline cardinal fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant une tension spécifiée. Cette méthode utilise le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui définissent la spline. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Method: draw_closed_curve_by_points_tension(pen, points, tension) {#draw_closed_curve_by_points_tension_pen_points_tension_26}


```
 draw_closed_curve_by_points_tension(pen, points, tension) 
```

Dessine une spline cardinal fermée définie par un tableau de structures [Point](/imaging/python-net/aspose.imaging/point/) en utilisant une tension spécifiée. Cette méthode utilise le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de structures [Point](/imaging/python-net/aspose.imaging/point/) qui définissent la spline. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_27}


```
 draw_curve(pen, points) 
```

Dessine une spline cardinal à travers un tableau spécifié de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). Cette méthode utilise une tension par défaut de 0,5.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui définissent la spline. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_curve(pen, points) {#draw_curve_pen_points_28}


```
 draw_curve(pen, points) 
```

Dessine une spline cardinal à travers un tableau spécifié de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). Cette méthode utilise une tension par défaut de 0,5.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui définissent la spline. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_curve(pen, points, offset, number_of_segments) {#draw_curve_pen_points_offset_number_of_segments_29}


```
 draw_curve(pen, points, offset, number_of_segments) 
```

Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). Le dessin commence décalé depuis le début du tableau.<br/>            Cette méthode utilise une tension par défaut de 0,5.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui définissent la spline. |
| offset | int | Décalage du premier élément du tableau du paramètre _points_ au point de départ de la courbe. |
| number_of_segments | int | Nombre de segments après le point de départ à inclure dans la courbe. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_30}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant une tension spécifiée. Le dessin commence décalé depuis le début du tableau.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui définissent la spline. |
| offset | int | Décalage du premier élément du tableau du paramètre _points_ au point de départ de la courbe. |
| number_of_segments | int | Nombre de segments après le point de départ à inclure dans la courbe. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_31}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant une tension spécifiée. Le dessin commence décalé depuis le début du tableau.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui définissent la spline. |
| offset | int | Décalage du premier élément du tableau du paramètre _points_ au point de départ de la courbe. |
| number_of_segments | int | Nombre de segments après le point de départ à inclure dans la courbe. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_32}


```
 draw_curve(pen, points, tension) 
```

Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant une tension spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représentent les points qui définissent la courbe. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_33}


```
 draw_curve(pen, points, tension) 
```

Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant une tension spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représentent les points qui définissent la courbe. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Method: draw_curve_by_point_fs(pen, points) {#draw_curve_by_point_fs_pen_points_34}


```
 draw_curve_by_point_fs(pen, points) 
```

Dessine une spline cardinale à travers un tableau spécifié de structures [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de structures [Point](/imaging/python-net/aspose.imaging/point/) qui définissent la spline. |

### Method: draw_curve_by_point_fs_tension(pen, points, tension) {#draw_curve_by_point_fs_tension_pen_points_tension_35}


```
 draw_curve_by_point_fs_tension(pen, points, tension) 
```

Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant une tension spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représentent les points qui définissent la courbe. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Method: draw_curve_by_points(pen, points) {#draw_curve_by_points_pen_points_36}


```
 draw_curve_by_points(pen, points) 
```

Dessine une spline cardinal à travers un tableau spécifié de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). Cette méthode utilise une tension par défaut de 0,5.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui définissent la spline. |

### Method: draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) {#draw_curve_by_points_f_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_37}


```
 draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) 
```

Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant une tension spécifiée. Le dessin commence décalé depuis le début du tableau.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui définissent la spline. |
| offset | int | Décalage du premier élément du tableau du paramètre _points_ au point de départ de la courbe. |
| number_of_segments | int | Nombre de segments après le point de départ à inclure dans la courbe. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Method: draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) {#draw_curve_by_points_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_38}


```
 draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) 
```

Dessine une spline cardinale à travers un tableau spécifié de structures [Point](/imaging/python-net/aspose.imaging/point/) en utilisant une tension spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de structures [Point](/imaging/python-net/aspose.imaging/point/) qui définissent la spline. |
| offset | int | Décalage du premier élément du tableau du paramètre _points_ au point de départ de la courbe. |
| number_of_segments | int | Nombre de segments après le point de départ à inclure dans la courbe. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Method: draw_curve_by_points_tension(pen, points, tension) {#draw_curve_by_points_tension_pen_points_tension_39}


```
 draw_curve_by_points_tension(pen, points, tension) 
```

Dessine une spline cardinale à travers un tableau spécifié de structures [Point](/imaging/python-net/aspose.imaging/point/) en utilisant une tension spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de structures [Point](/imaging/python-net/aspose.imaging/point/) qui définissent la spline. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_40}


```
 draw_ellipse(pen, rect) 
```

Dessine une ellipse définie par un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) englobant.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de l'ellipse. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure qui définit les limites de l'ellipse. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_41}


```
 draw_ellipse(pen, rect) 
```

Dessine une ellipse définie par un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) englobant.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de l'ellipse. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure qui définit les limites de l'ellipse. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_42}


```
 draw_ellipse(pen, x, y, width, height) 
```

Dessine une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une hauteur et une largeur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de l'ellipse. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| width | float | Largeur du rectangle englobant qui définit l'ellipse. |
| height | float | Hauteur du rectangle englobant qui définit l'ellipse. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_43}


```
 draw_ellipse(pen, x, y, width, height) 
```

Dessine une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une hauteur et une largeur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de l'ellipse. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| width | int | Largeur du rectangle englobant qui définit l'ellipse. |
| height | int | Hauteur du rectangle englobant qui définit l'ellipse. |

### Method: draw_ellipse_by_xy(pen, x, y, width, height) {#draw_ellipse_by_xy_pen_x_y_width_height_44}


```
 draw_ellipse_by_xy(pen, x, y, width, height) 
```

Dessine une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une hauteur et une largeur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de l'ellipse. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| width | int | Largeur du rectangle englobant qui définit l'ellipse. |
| height | int | Hauteur du rectangle englobant qui définit l'ellipse. |

### Method: draw_ellipse_by_xyf(pen, x, y, width, height) {#draw_ellipse_by_xyf_pen_x_y_width_height_45}


```
 draw_ellipse_by_xyf(pen, x, y, width, height) 
```

Dessine une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une hauteur et une largeur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de l'ellipse. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| width | float | Largeur du rectangle englobant qui définit l'ellipse. |
| height | float | Hauteur du rectangle englobant qui définit l'ellipse. |

### Method: draw_ellipse_f(pen, rect) {#draw_ellipse_f_pen_rect_46}


```
 draw_ellipse_f(pen, rect) 
```

Dessine une ellipse définie par un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) englobant.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de l'ellipse. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure qui définit les limites de l'ellipse. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_47}


```
 draw_image(image, dest_points) 
```

Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image à dessiner. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de trois structures PointF qui définissent un parallélogramme. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_48}


```
 draw_image(image, dest_points) 
```

Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image à dessiner. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de trois structures PointF qui définissent un parallélogramme. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_49}


```
 draw_image(image, dest_points, src_rect) 
```

Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image à dessiner. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de trois structures PointF qui définissent un parallélogramme. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle source. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_50}


```
 draw_image(image, dest_points, src_rect) 
```

Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image à dessiner. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de trois structures PointF qui définissent un parallélogramme. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le rectangle source. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_51}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image à dessiner. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de trois structures PointF qui définissent un parallélogramme. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle source. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Les unités de mesure. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_52}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image à dessiner. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de trois structures PointF qui définissent un parallélogramme. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le rectangle source. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Les unités de mesure. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_53}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image à dessiner. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de trois structures PointF qui définissent un parallélogramme. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle source. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Les unités de mesure. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Les attributs de l'image. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_54}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image à dessiner. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de trois structures PointF qui définissent un parallélogramme. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le rectangle source. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Les unités de mesure. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Les attributs de l'image. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_55}


```
 draw_image(source_image, point) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié, en utilisant sa taille physique originale, à l'emplacement spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure qui représente le coin supérieur gauche de l'image dessinée. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_56}


```
 draw_image(source_image, point) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié, en utilisant sa taille physique originale, à l'emplacement spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure qui représente le coin supérieur gauche de l'image dessinée. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_57}


```
 draw_image(source_image, rect) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure qui spécifie l'emplacement et la taille de l'image dessinée. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_58}


```
 draw_image(source_image, rect) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure qui spécifie l'emplacement et la taille de l'image dessinée. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_59}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle de destination. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unité graphique. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_60}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le rectangle de destination. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unité graphique. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_61}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle de destination. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unité graphique. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Les attributs de l'image. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_62}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le rectangle de destination. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unité graphique. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Les attributs de l'image. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_63}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rect source. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rect destination. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unité graphique. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_64}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le rect source. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le rect destination. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unité graphique. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_65}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rect source. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rect destination. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unité graphique. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Les attributs de l'image. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_66}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le rect source. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le rect destination. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unité graphique. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Les attributs de l'image. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_67}


```
 draw_image(source_image, x, y) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié, en utilisant sa taille physique originale, à l'emplacement spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| x | float | La coordonnée x du coin supérieur gauche de l'image dessinée. |
| y | float | La coordonnée y du coin supérieur gauche de l'image dessinée. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_68}


```
 draw_image(source_image, x, y) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié, en utilisant sa taille physique originale, à l'emplacement spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| x | int | La coordonnée x du coin supérieur gauche de l'image dessinée. |
| y | int | La coordonnée y du coin supérieur gauche de l'image dessinée. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_69}


```
 draw_image(source_image, x, y, width, height) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| x | float | La coordonnée x du coin supérieur gauche de l'image dessinée. |
| y | float | La coordonnée y du coin supérieur gauche de l'image dessinée. |
| width | float | Largeur de l'image dessinée. |
| height | float | Hauteur de l'image dessinée. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_70}


```
 draw_image(source_image, x, y, width, height) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| x | int | La coordonnée x du coin supérieur gauche de l'image dessinée. |
| y | int | La coordonnée y du coin supérieur gauche de l'image dessinée. |
| width | int | Largeur de l'image dessinée. |
| height | int | Hauteur de l'image dessinée. |

### Method: draw_image_at_point(source_image, point) {#draw_image_at_point_source_image_point_71}


```
 draw_image_at_point(source_image, point) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié, en utilisant sa taille physique originale, à l'emplacement spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure qui représente le coin supérieur gauche de l'image dessinée. |

### Method: draw_image_at_point_f(source_image, point) {#draw_image_at_point_f_source_image_point_72}


```
 draw_image_at_point_f(source_image, point) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié, en utilisant sa taille physique originale, à l'emplacement spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure qui représente le coin supérieur gauche de l'image dessinée. |

### Method: draw_image_at_xy(source_image, x, y) {#draw_image_at_xy_source_image_x_y_73}


```
 draw_image_at_xy(source_image, x, y) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié, en utilisant sa taille physique originale, à l'emplacement spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| x | int | La coordonnée x du coin supérieur gauche de l'image dessinée. |
| y | int | La coordonnée y du coin supérieur gauche de l'image dessinée. |

### Method: draw_image_at_xyf(source_image, x, y) {#draw_image_at_xyf_source_image_x_y_74}


```
 draw_image_at_xyf(source_image, x, y) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié, en utilisant sa taille physique originale, à l'emplacement spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| x | float | La coordonnée x du coin supérieur gauche de l'image dessinée. |
| y | float | La coordonnée y du coin supérieur gauche de l'image dessinée. |

### Method: draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit) {#draw_image_dest_point_f_src_rect_f_with_unit_image_dest_points_src_rect_src_unit_75}


```
 draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit) 
```

Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image à dessiner. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de trois structures PointF qui définissent un parallélogramme. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le rectangle source. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Les unités de mesure. |

### Method: draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_dest_point_f_src_rect_f_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_76}


```
 draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) 
```

Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image à dessiner. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de trois structures PointF qui définissent un parallélogramme. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le rectangle source. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Les unités de mesure. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Les attributs de l'image. |

### Method: draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect) {#draw_image_dest_points_f_src_rect_f_image_dest_points_src_rect_77}


```
 draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect) 
```

Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image à dessiner. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de trois structures PointF qui définissent un parallélogramme. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le rectangle source. |

### Method: draw_image_dest_points_src_rect(image, dest_points, src_rect) {#draw_image_dest_points_src_rect_image_dest_points_src_rect_78}


```
 draw_image_dest_points_src_rect(image, dest_points, src_rect) 
```

Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image à dessiner. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de trois structures PointF qui définissent un parallélogramme. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle source. |

### Method: draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit) {#draw_image_dest_points_src_rect_with_unit_image_dest_points_src_rect_src_unit_79}


```
 draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit) 
```

Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image à dessiner. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de trois structures PointF qui définissent un parallélogramme. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle source. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Les unités de mesure. |

### Method: draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_dest_points_src_rect_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_80}


```
 draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) 
```

Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image à dessiner. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de trois structures PointF qui définissent un parallélogramme. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle source. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Les unités de mesure. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Les attributs de l'image. |

### Method: draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_dest_rect_f_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_81}


```
 draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le rectangle de destination dans lequel dessiner. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unité graphique. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Les attributs de l'image. |

### Method: draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_dest_rect_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_82}


```
 draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle de destination. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unité graphique. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Les attributs de l'image. |

### Method: draw_image_in_rect(source_image, x, y, width, height) {#draw_image_in_rect_source_image_x_y_width_height_83}


```
 draw_image_in_rect(source_image, x, y, width, height) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| x | int | La coordonnée x du coin supérieur gauche de l'image dessinée. |
| y | int | La coordonnée y du coin supérieur gauche de l'image dessinée. |
| width | int | Largeur de l'image dessinée. |
| height | int | Hauteur de l'image dessinée. |

### Method: draw_image_in_rect_f(source_image, x, y, width, height) {#draw_image_in_rect_f_source_image_x_y_width_height_84}


```
 draw_image_in_rect_f(source_image, x, y, width, height) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| x | float | La coordonnée x du coin supérieur gauche de l'image dessinée. |
| y | float | La coordonnée y du coin supérieur gauche de l'image dessinée. |
| width | float | Largeur de l'image dessinée. |
| height | float | Hauteur de l'image dessinée. |

### Method: draw_image_in_rectangle(source_image, rect) {#draw_image_in_rectangle_source_image_rect_85}


```
 draw_image_in_rectangle(source_image, rect) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure qui spécifie l'emplacement et la taille de l'image dessinée. |

### Method: draw_image_points(image, dest_points) {#draw_image_points_image_dest_points_86}


```
 draw_image_points(image, dest_points) 
```

Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image à dessiner. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de trois structures PointF qui définissent un parallélogramme. |

### Method: draw_image_points_f(image, dest_points) {#draw_image_points_f_image_dest_points_87}


```
 draw_image_points_f(image, dest_points) 
```

Dessine la portion spécifiée de l'_image_ spécifiée à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image à dessiner. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de trois structures PointF qui définissent un parallélogramme. |

### Method: draw_image_rectangle_f(source_image, rect) {#draw_image_rectangle_f_source_image_rect_88}


```
 draw_image_rectangle_f(source_image, rect) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure qui spécifie l'emplacement et la taille de l'image dessinée. |

### Method: draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_src_dest_rects_f_with_unit_source_image_rect_source_rect_destination_graphics_unit_89}


```
 draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le rect source. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le rect destination. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unité graphique. |

### Method: draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_src_dest_rects_with_unit_source_image_rect_source_rect_destination_graphics_unit_90}


```
 draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rect source. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rect destination. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unité graphique. |

### Method: draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_src_dst_rect_f_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_91}


```
 draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le rectangle source. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le rectangle de destination. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unité graphique à utiliser. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Les attributs de l'image à utiliser. |

### Method: draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_src_dst_rects_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_92}


```
 draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rect source. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rect destination. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unité graphique. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Les attributs de l'image. |

### Method: draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit) {#draw_image_to_rect_f_with_unit_source_image_rect_destination_graphics_unit_93}


```
 draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Le rectangle de destination. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unité graphique. |

### Method: draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit) {#draw_image_to_rect_with_unit_source_image_rect_destination_graphics_unit_94}


```
 draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit) 
```

Dessine le [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) spécifié à l'emplacement spécifié et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle de destination. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unité graphique. |

### Method: draw_image_unscaled(source_image, point) {#draw_image_unscaled_source_image_point_95}


```
 draw_image_unscaled(source_image, point) 
```

Dessine une image spécifiée en utilisant sa taille physique originale à un emplacement spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) structure qui spécifie le coin supérieur gauche de l'image dessinée. |

### Method: draw_image_unscaled(source_image, rect) {#draw_image_unscaled_source_image_rect_96}


```
 draw_image_unscaled(source_image, rect) 
```

Dessine une image spécifiée en utilisant sa taille physique originale à un emplacement spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) qui spécifie le coin supérieur gauche de l'image dessinée. Les propriétés X et Y du rectangle spécifient le coin supérieur gauche. Les propriétés Width et Height sont ignorées. |

### Method: draw_image_unscaled(source_image, x, y) {#draw_image_unscaled_source_image_x_y_97}


```
 draw_image_unscaled(source_image, x, y) 
```

Dessine l'image spécifiée en utilisant sa taille physique originale à l'emplacement spécifié par une paire de coordonnées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| x | int | La coordonnée x du coin supérieur gauche de l'image dessinée. |
| y | int | La coordonnée y du coin supérieur gauche de l'image dessinée. |

### Method: draw_image_unscaled(source_image, x, y, width, height) {#draw_image_unscaled_source_image_x_y_width_height_98}


```
 draw_image_unscaled(source_image, x, y, width, height) 
```

Dessine une image spécifiée en utilisant sa taille physique originale à un emplacement spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| x | int | La coordonnée x du coin supérieur gauche de l'image dessinée. |
| y | int | La coordonnée y du coin supérieur gauche de l'image dessinée. |
| width | int | Le paramètre n'est pas utilisé. |
| height | int | Le paramètre n'est pas utilisé. |

### Method: draw_image_unscaled_and_clipped(source_image, rect) {#draw_image_unscaled_and_clipped_source_image_rect_99}


```
 draw_image_unscaled_and_clipped(source_image, rect) 
```

Dessine l'image spécifiée sans mise à l'échelle et la découpe, si nécessaire, pour l'adapter au rectangle spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) dans lequel dessiner l'image. |

### Method: draw_image_unscaled_in_rectangle(source_image, rect) {#draw_image_unscaled_in_rectangle_source_image_rect_100}


```
 draw_image_unscaled_in_rectangle(source_image, rect) 
```

Dessine une image spécifiée en utilisant sa taille physique originale à un emplacement spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) qui spécifie le coin supérieur gauche de l'image dessinée. Les propriétés X et Y du rectangle spécifient le coin supérieur gauche. Les propriétés Width et Height sont ignorées. |

### Method: draw_image_unscaled_to_point(source_image, point) {#draw_image_unscaled_to_point_source_image_point_101}


```
 draw_image_unscaled_to_point(source_image, point) 
```

Dessine une image spécifiée en utilisant sa taille physique originale à un emplacement spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'image avec laquelle dessiner. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) structure qui spécifie le coin supérieur gauche de l'image dessinée. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_102}


```
 draw_line(pen, point1, point2) 
```

Dessine une ligne reliant deux structures [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de la ligne. |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) structure qui représente le premier point à connecter. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) structure qui représente le deuxième point à connecter. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_103}


```
 draw_line(pen, point1, point2) 
```

Dessine une ligne reliant deux structures [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de la ligne. |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [Point](/imaging/python-net/aspose.imaging/point/) structure qui représente le premier point à connecter. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [Point](/imaging/python-net/aspose.imaging/point/) structure qui représente le deuxième point à connecter. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_104}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Dessine une ligne reliant les deux points spécifiés par les paires de coordonnées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de la ligne. |
| x1 | int | La coordonnée x du premier point. |
| y1 | int | La coordonnée y du premier point. |
| x2 | int | La coordonnée x du deuxième point. |
| y2 | int | La coordonnée y du deuxième point. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_105}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Dessine une ligne reliant les deux points spécifiés par les paires de coordonnées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de la ligne. |
| x1 | float | La coordonnée x du premier point. |
| y1 | float | La coordonnée y du premier point. |
| x2 | float | La coordonnée x du deuxième point. |
| y2 | float | La coordonnée y du deuxième point. |

### Method: draw_line_by_xy(pen, x1, y1, x2, y2) {#draw_line_by_xy_pen_x1_y1_x2_y2_106}


```
 draw_line_by_xy(pen, x1, y1, x2, y2) 
```

Dessine une ligne reliant les deux points spécifiés par les paires de coordonnées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de la ligne. |
| x1 | int | La coordonnée x du premier point. |
| y1 | int | La coordonnée y du premier point. |
| x2 | int | La coordonnée x du deuxième point. |
| y2 | int | La coordonnée y du deuxième point. |

### Method: draw_line_f_by_xy(pen, x1, y1, x2, y2) {#draw_line_f_by_xy_pen_x1_y1_x2_y2_107}


```
 draw_line_f_by_xy(pen, x1, y1, x2, y2) 
```

Dessine une ligne reliant les deux points spécifiés par les paires de coordonnées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de la ligne. |
| x1 | float | La coordonnée x du premier point. |
| y1 | float | La coordonnée y du premier point. |
| x2 | float | La coordonnée x du deuxième point. |
| y2 | float | La coordonnée y du deuxième point. |

### Method: draw_line_point_f(pen, point1, point2) {#draw_line_point_f_pen_point1_point2_108}


```
 draw_line_point_f(pen, point1, point2) 
```

Dessine une ligne reliant deux structures [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de la ligne. |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure qui représente le premier point à connecter. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) structure qui représente le deuxième point à connecter. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_109}


```
 draw_lines(pen, points) 
```

Dessine une série de segments de ligne qui relient un tableau de structures [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style des segments de ligne. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de structures [Point](/imaging/python-net/aspose.imaging/point/) qui représentent les points à connecter. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_110}


```
 draw_lines(pen, points) 
```

Dessine une série de segments de ligne qui relient un tableau de structures [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style des segments de ligne. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de structures [Point](/imaging/python-net/aspose.imaging/point/) qui représentent les points à connecter. |

### Method: draw_lines_f(pen, points) {#draw_lines_f_pen_points_111}


```
 draw_lines_f(pen, points) 
```

Dessine une série de segments de ligne qui relient un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style des segments de ligne. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représentent les points à connecter. |

### Method: draw_path(pen, path) {#draw_path_pen_path_112}


```
 draw_path(pen, path) 
```

Dessine un [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style du tracé. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) à dessiner. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_113}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Dessine une forme de secteur définie par une ellipse spécifiée par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) et deux lignes radiales.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de la forme de secteur. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure qui représente le rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| start_angle | float | Angle mesuré en degrés dans le sens horaire à partir de l'axe x jusqu'au premier côté de la forme de secteur. |
| sweep_angle | float | Angle mesuré en degrés dans le sens horaire à partir du paramètre _startAngle_ jusqu'au deuxième côté de la forme de secteur. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_114}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Dessine une forme de secteur définie par une ellipse spécifiée par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) et deux lignes radiales.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de la forme de secteur. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure qui représente le rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| start_angle | float | Angle mesuré en degrés dans le sens horaire à partir de l'axe x jusqu'au premier côté de la forme de secteur. |
| sweep_angle | float | Angle mesuré en degrés dans le sens horaire à partir du paramètre _startAngle_ jusqu'au deuxième côté de la forme de secteur. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_115}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Dessine une forme de secteur définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de la forme de secteur. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| width | float | Largeur du rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| height | float | Hauteur du rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| start_angle | float | Angle mesuré en degrés dans le sens horaire à partir de l'axe x jusqu'au premier côté de la forme de secteur. |
| sweep_angle | float | Angle mesuré en degrés dans le sens horaire à partir du paramètre _startAngle_ jusqu'au deuxième côté de la forme de secteur. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_116}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Dessine une forme de secteur définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de la forme de secteur. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| width | int | Largeur du rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| height | int | Hauteur du rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| start_angle | int | Angle mesuré en degrés dans le sens horaire à partir de l'axe x jusqu'au premier côté de la forme de secteur. |
| sweep_angle | int | Angle mesuré en degrés dans le sens horaire à partir du paramètre _startAngle_ jusqu'au deuxième côté de la forme de secteur. |

### Method: draw_pie_in_rect(pen, rect, start_angle, sweep_angle) {#draw_pie_in_rect_pen_rect_start_angle_sweep_angle_117}


```
 draw_pie_in_rect(pen, rect, start_angle, sweep_angle) 
```

Dessine une forme de secteur définie par une ellipse spécifiée par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) et deux lignes radiales.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de la forme de secteur. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure qui représente le rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| start_angle | float | Angle mesuré en degrés dans le sens horaire à partir de l'axe x jusqu'au premier côté de la forme de secteur. |
| sweep_angle | float | Angle mesuré en degrés dans le sens horaire à partir du paramètre _startAngle_ jusqu'au deuxième côté de la forme de secteur. |

### Method: draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle) {#draw_pie_in_rect_f_pen_rect_start_angle_sweep_angle_118}


```
 draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle) 
```

Dessine une forme de secteur définie par une ellipse spécifiée par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) et deux lignes radiales.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de la forme de secteur. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure qui représente le rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| start_angle | float | Angle mesuré en degrés dans le sens horaire à partir de l'axe x jusqu'au premier côté de la forme de secteur. |
| sweep_angle | float | Angle mesuré en degrés dans le sens horaire à partir du paramètre _startAngle_ jusqu'au deuxième côté de la forme de secteur. |

### Method: draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_xy_pen_x_y_width_height_start_angle_sweep_angle_119}


```
 draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle) 
```

Dessine une forme de secteur définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de la forme de secteur. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| width | int | Largeur du rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| height | int | Hauteur du rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| start_angle | int | Angle mesuré en degrés dans le sens horaire à partir de l'axe x jusqu'au premier côté de la forme de secteur. |
| sweep_angle | int | Angle mesuré en degrés dans le sens horaire à partir du paramètre _startAngle_ jusqu'au deuxième côté de la forme de secteur. |

### Method: draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_xyf_pen_x_y_width_height_start_angle_sweep_angle_120}


```
 draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle) 
```

Dessine une forme de secteur définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style de la forme de secteur. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| width | float | Largeur du rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| height | float | Hauteur du rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| start_angle | float | Angle mesuré en degrés dans le sens horaire à partir de l'axe x jusqu'au premier côté de la forme de secteur. |
| sweep_angle | float | Angle mesuré en degrés dans le sens horaire à partir du paramètre _startAngle_ jusqu'au deuxième côté de la forme de secteur. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_121}


```
 draw_polygon(pen, points) 
```

Dessine un polygone défini par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style du polygone. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représentent les sommets du polygone. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_122}


```
 draw_polygon(pen, points) 
```

Dessine un polygone défini par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style du polygone. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représentent les sommets du polygone. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_polygon_f(pen, points) {#draw_polygon_f_pen_points_123}


```
 draw_polygon_f(pen, points) 
```

Dessine un polygone défini par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style du polygone. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représentent les sommets du polygone. |

### Method: draw_rect(pen, x, y, width, height) {#draw_rect_pen_x_y_width_height_124}


```
 draw_rect(pen, x, y, width, height) 
```

Dessine un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Un [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style du rectangle. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle à dessiner. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle à dessiner. |
| width | int | La largeur du rectangle à dessiner. |
| height | int | La hauteur du rectangle à dessiner. |

### Method: draw_rect_f(pen, x, y, width, height) {#draw_rect_f_pen_x_y_width_height_125}


```
 draw_rect_f(pen, x, y, width, height) 
```

Dessine un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Un [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style du rectangle. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle à dessiner. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle à dessiner. |
| width | float | La largeur du rectangle à dessiner. |
| height | float | La hauteur du rectangle à dessiner. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_126}


```
 draw_rectangle(pen, rect) 
```

Dessine un rectangle spécifié par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Un [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style du rectangle. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représente le rectangle à dessiner. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_127}


```
 draw_rectangle(pen, rect) 
```

Dessine un rectangle spécifié par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Un [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style du rectangle. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représente le rectangle à dessiner. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_128}


```
 draw_rectangle(pen, x, y, width, height) 
```

Dessine un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Un [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style du rectangle. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle à dessiner. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle à dessiner. |
| width | float | La largeur du rectangle à dessiner. |
| height | float | La hauteur du rectangle à dessiner. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_129}


```
 draw_rectangle(pen, x, y, width, height) 
```

Dessine un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Un [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style du rectangle. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle à dessiner. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle à dessiner. |
| width | int | La largeur du rectangle à dessiner. |
| height | int | La hauteur du rectangle à dessiner. |

### Method: draw_rectangle_f(pen, rect) {#draw_rectangle_f_pen_rect_130}


```
 draw_rectangle_f(pen, rect) 
```

Dessine un rectangle spécifié par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Un [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style du rectangle. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représente le rectangle à dessiner. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_131}


```
 draw_rectangles(pen, rects) 
```

Dessine une série de rectangles spécifiés par des structures [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style des contours des rectangles. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Tableau de structures [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représentent les rectangles à dessiner. |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_132}


```
 draw_rectangles(pen, rects) 
```

Dessine une série de rectangles spécifiés par des structures [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style des contours des rectangles. |
| rects | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | Tableau de structures [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représentent les rectangles à dessiner. |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: draw_rectangles_f(pen, rects) {#draw_rectangles_f_pen_rects_133}


```
 draw_rectangles_f(pen, rects) 
```

Dessine une série de rectangles spécifiés par des structures [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) qui détermine la couleur, la largeur et le style des contours des rectangles. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Tableau de structures [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représentent les rectangles à dessiner. |

### Method: draw_string(s, font, brush, layout_rectangle) {#draw_string_s_font_brush_layout_rectangle_134}


```
 draw_string(s, font, brush, layout_rectangle) 
```

Dessine la chaîne de texte spécifiée dans le rectangle spécifié avec le [Brush](/imaging/python-net/aspose.imaging/brush/) et le [Font](/imaging/python-net/aspose.imaging/font/) spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| s | string | Chaîne à dessiner. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) qui définit le format du texte de la chaîne. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine la couleur et la texture du texte dessiné. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui spécifie l'emplacement du texte dessiné. |

### Method: draw_string(s, font, brush, layout_rectangle, format) {#draw_string_s_font_brush_layout_rectangle_format_135}


```
 draw_string(s, font, brush, layout_rectangle, format) 
```

Dessine la chaîne de texte spécifiée dans le rectangle spécifié avec le [Brush](/imaging/python-net/aspose.imaging/brush/) et le [Font](/imaging/python-net/aspose.imaging/font/) spécifiés en utilisant les attributs de formatage du [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| s | string | Chaîne à dessiner. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) qui définit le format du texte de la chaîne. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine la couleur et la texture du texte dessiné. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui spécifie l'emplacement du texte dessiné. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) qui spécifie les attributs de mise en forme, tels que l'espacement des lignes et l'alignement, qui sont appliqués au texte dessiné. |

### Method: draw_string(s, font, brush, point) {#draw_string_s_font_brush_point_136}


```
 draw_string(s, font, brush, point) 
```

Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec le [Brush](/imaging/python-net/aspose.imaging/brush/) et le [Font](/imaging/python-net/aspose.imaging/font/) spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| s | string | Chaîne à dessiner. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) qui définit le format du texte de la chaîne. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine la couleur et la texture du texte dessiné. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Structure [PointF](/imaging/python-net/aspose.imaging/pointf/) qui spécifie le coin supérieur gauche du texte dessiné. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_string(s, font, brush, point, format) {#draw_string_s_font_brush_point_format_137}


```
 draw_string(s, font, brush, point, format) 
```

Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec le [Brush](/imaging/python-net/aspose.imaging/brush/) et le [Font](/imaging/python-net/aspose.imaging/font/) spécifiés en utilisant les attributs de formatage du [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| s | string | Chaîne à dessiner. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) qui définit le format du texte de la chaîne. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine la couleur et la texture du texte dessiné. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Structure [PointF](/imaging/python-net/aspose.imaging/pointf/) qui spécifie le coin supérieur gauche du texte dessiné. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) qui spécifie les attributs de mise en forme, tels que l'espacement des lignes et l'alignement, qui sont appliqués au texte dessiné. |

### Method: draw_string(s, font, brush, x, y) {#draw_string_s_font_brush_x_y_138}


```
 draw_string(s, font, brush, x, y) 
```

Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec le [Brush](/imaging/python-net/aspose.imaging/brush/) et le [Font](/imaging/python-net/aspose.imaging/font/) spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| s | string | Chaîne à dessiner. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) qui définit le format du texte de la chaîne. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine la couleur et la texture du texte dessiné. |
| x | float | La coordonnée x du coin supérieur gauche du texte dessiné. |
| y | float | La coordonnée y du coin supérieur gauche du texte dessiné. |

### Method: draw_string(s, font, brush, x, y, format) {#draw_string_s_font_brush_x_y_format_139}


```
 draw_string(s, font, brush, x, y, format) 
```

Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec le [Brush](/imaging/python-net/aspose.imaging/brush/) et le [Font](/imaging/python-net/aspose.imaging/font/) spécifiés en utilisant les attributs de formatage du [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| s | string | Chaîne à dessiner. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) qui définit le format du texte de la chaîne. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine la couleur et la texture du texte dessiné. |
| x | float | La coordonnée x du coin supérieur gauche du texte dessiné. |
| y | float | La coordonnée y du coin supérieur gauche du texte dessiné. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) qui spécifie les attributs de mise en forme, tels que l'espacement des lignes et l'alignement, qui sont appliqués au texte dessiné. |

### Method: draw_string_at_point_f(s, font, brush, point) {#draw_string_at_point_f_s_font_brush_point_140}


```
 draw_string_at_point_f(s, font, brush, point) 
```

Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec le [Brush](/imaging/python-net/aspose.imaging/brush/) et le [Font](/imaging/python-net/aspose.imaging/font/) spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| s | string | Chaîne à dessiner. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) qui définit le format du texte de la chaîne. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine la couleur et la texture du texte dessiné. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Structure [PointF](/imaging/python-net/aspose.imaging/pointf/) qui spécifie le coin supérieur gauche du texte dessiné. |

### Method: draw_string_at_point_f_format(s, font, brush, point, format) {#draw_string_at_point_f_format_s_font_brush_point_format_141}


```
 draw_string_at_point_f_format(s, font, brush, point, format) 
```

Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec le [Brush](/imaging/python-net/aspose.imaging/brush/) et le [Font](/imaging/python-net/aspose.imaging/font/) spécifiés en utilisant les attributs de formatage du [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| s | string | Chaîne à dessiner. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) qui définit le format du texte de la chaîne. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine la couleur et la texture du texte dessiné. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Structure [PointF](/imaging/python-net/aspose.imaging/pointf/) qui spécifie le coin supérieur gauche du texte dessiné. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) qui spécifie les attributs de mise en forme, tels que l'espacement des lignes et l'alignement, qui sont appliqués au texte dessiné. |

### Method: draw_string_at_xy(s, font, brush, x, y) {#draw_string_at_xy_s_font_brush_x_y_142}


```
 draw_string_at_xy(s, font, brush, x, y) 
```

Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec le [Brush](/imaging/python-net/aspose.imaging/brush/) et le [Font](/imaging/python-net/aspose.imaging/font/) spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| s | string | Chaîne à dessiner. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) qui définit le format du texte de la chaîne. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine la couleur et la texture du texte dessiné. |
| x | float | La coordonnée x du coin supérieur gauche du texte dessiné. |
| y | float | La coordonnée y du coin supérieur gauche du texte dessiné. |

### Method: draw_string_in_rect(s, font, brush, layout_rectangle) {#draw_string_in_rect_s_font_brush_layout_rectangle_143}


```
 draw_string_in_rect(s, font, brush, layout_rectangle) 
```

Dessine la chaîne de texte spécifiée dans le rectangle spécifié avec le [Brush](/imaging/python-net/aspose.imaging/brush/) et le [Font](/imaging/python-net/aspose.imaging/font/) spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| s | string | Chaîne à dessiner. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) qui définit le format du texte de la chaîne. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine la couleur et la texture du texte dessiné. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui spécifie l'emplacement du texte dessiné. |

### Method: draw_string_in_rect_f(s, font, brush, layout_rectangle, format) {#draw_string_in_rect_f_s_font_brush_layout_rectangle_format_144}


```
 draw_string_in_rect_f(s, font, brush, layout_rectangle, format) 
```

Dessine la chaîne de texte spécifiée dans le rectangle spécifié avec le [Brush](/imaging/python-net/aspose.imaging/brush/) et le [Font](/imaging/python-net/aspose.imaging/font/) spécifiés en utilisant les attributs de formatage du [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| s | string | Chaîne à dessiner. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) qui définit le format du texte de la chaîne. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine la couleur et la texture du texte dessiné. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui spécifie l'emplacement du texte dessiné. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) qui spécifie les attributs de mise en forme, tels que l'espacement des lignes et l'alignement, qui sont appliqués au texte dessiné. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_145}


```
 fill_closed_curve(brush, points) 
```

Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). Cette méthode utilise une tension par défaut de 0,5 et le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui définissent la spline. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_146}


```
 fill_closed_curve(brush, points) 
```

Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). Cette méthode utilise une tension par défaut de 0,5 et le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui définissent la spline. |

### Method: fill_closed_curve(brush, points, fill_mode) {#fill_closed_curve_brush_points_fill_mode_147}


```
 fill_closed_curve(brush, points, fill_mode) 
```

Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant le mode de remplissage spécifié. Cette méthode utilise une tension par défaut de 0,5.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui définissent la spline. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Membre de l'énumération [FillMode](/imaging/python-net/aspose.imaging/fillmode/) qui détermine comment la courbe est remplie. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_148}


```
 fill_closed_curve(brush, points, fillmode) 
```

Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant le mode de remplissage spécifié. Cette méthode utilise une tension par défaut de 0,5.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui définissent la spline. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) |  |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_149}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant le mode de remplissage et la tension spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Un [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui définissent la spline. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Membre de l'énumération [FillMode](/imaging/python-net/aspose.imaging/fillmode/) qui détermine comment la courbe est remplie. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_150}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant le mode de remplissage et la tension spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Un [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui définissent la spline. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Membre de l'énumération [FillMode](/imaging/python-net/aspose.imaging/fillmode/) qui détermine comment la courbe est remplie. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Method: fill_closed_curve_by_point(brush, points) {#fill_closed_curve_by_point_brush_points_151}


```
 fill_closed_curve_by_point(brush, points) 
```

Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). Cette méthode utilise une tension par défaut de 0,5 et le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui définissent la spline. |

### Method: fill_closed_curve_by_point_f(brush, points) {#fill_closed_curve_by_point_f_brush_points_152}


```
 fill_closed_curve_by_point_f(brush, points) 
```

Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/). Cette méthode utilise une tension par défaut de 0,5 et le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui définissent la spline. |

### Method: fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension) {#fill_closed_curve_by_point_f_fill_mode_tension_brush_points_fillmode_tension_153}


```
 fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension) 
```

Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant le mode de remplissage et la tension spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Un [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui définissent la spline. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Membre de l'énumération [FillMode](/imaging/python-net/aspose.imaging/fillmode/) qui détermine comment la courbe est remplie. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Method: fill_closed_curve_by_point_fill_mode(brush, points, fillmode) {#fill_closed_curve_by_point_fill_mode_brush_points_fillmode_154}


```
 fill_closed_curve_by_point_fill_mode(brush, points, fillmode) 
```

Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures [Point](/imaging/python-net/aspose.imaging/point/) en utilisant le mode de remplissage spécifié. Cette méthode utilise une tension par défaut de 0,5.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de structures [Point](/imaging/python-net/aspose.imaging/point/) qui définissent la spline. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Membre de l'énumération [FillMode](/imaging/python-net/aspose.imaging/fillmode/) qui détermine comment la courbe est remplie. |

### Method: fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension) {#fill_closed_curve_by_point_fill_mode_tension_brush_points_fillmode_tension_155}


```
 fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension) 
```

Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de structures [Point](/imaging/python-net/aspose.imaging/point/) en utilisant le mode de remplissage et la tension spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de structures [Point](/imaging/python-net/aspose.imaging/point/) qui définissent la spline. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Membre de l'énumération [FillMode](/imaging/python-net/aspose.imaging/fillmode/) qui détermine comment la courbe est remplie. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_156}


```
 fill_ellipse(brush, rect) 
```

Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représente le rectangle englobant qui définit l'ellipse. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_157}


```
 fill_ellipse(brush, rect) 
```

Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représente le rectangle englobant qui définit l'ellipse. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_158}


```
 fill_ellipse(brush, x, y, width, height) 
```

Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| width | float | Largeur du rectangle englobant qui définit l'ellipse. |
| height | float | Hauteur du rectangle englobant qui définit l'ellipse. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_159}


```
 fill_ellipse(brush, x, y, width, height) 
```

Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| width | int | Largeur du rectangle englobant qui définit l'ellipse. |
| height | int | Hauteur du rectangle englobant qui définit l'ellipse. |

### Method: fill_ellipse_at_xywh(brush, x, y, width, height) {#fill_ellipse_at_xywh_brush_x_y_width_height_160}


```
 fill_ellipse_at_xywh(brush, x, y, width, height) 
```

Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| width | int | Largeur du rectangle englobant qui définit l'ellipse. |
| height | int | Hauteur du rectangle englobant qui définit l'ellipse. |

### Method: fill_ellipse_at_xywhf(brush, x, y, width, height) {#fill_ellipse_at_xywhf_brush_x_y_width_height_161}


```
 fill_ellipse_at_xywhf(brush, x, y, width, height) 
```

Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| width | float | Largeur du rectangle englobant qui définit l'ellipse. |
| height | float | Hauteur du rectangle englobant qui définit l'ellipse. |

### Method: fill_ellipse_in_rect(brush, rect) {#fill_ellipse_in_rect_brush_rect_162}


```
 fill_ellipse_in_rect(brush, rect) 
```

Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représente le rectangle englobant qui définit l'ellipse. |

### Method: fill_ellipse_in_rect_f(brush, rect) {#fill_ellipse_in_rect_f_brush_rect_163}


```
 fill_ellipse_in_rect_f(brush, rect) 
```

Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représente le rectangle englobant qui définit l'ellipse. |

### Method: fill_path(brush, path) {#fill_path_brush_path_164}


```
 fill_path(brush, path) 
```

Remplit l'intérieur d'un [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) qui représente le chemin à remplir. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_165}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) et deux lignes radiales.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) qui représente le rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| start_angle | float | Angle en degrés mesuré dans le sens horaire à partir de l'axe x jusqu'au premier côté de la section de tarte. |
| sweep_angle | float | Angle en degrés mesuré dans le sens horaire à partir du paramètre _startAngle_ jusqu'au deuxième côté de la section de tarte. |


**See also:**

**[Example # 1](#example_95)**: The following example shows how to compose an animated GIF image from individ...


### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_166}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) et deux lignes radiales.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) qui représente le rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| start_angle | float | Angle en degrés mesuré dans le sens horaire à partir de l'axe x jusqu'au premier côté de la section de tarte. |
| sweep_angle | float | Angle en degrés mesuré dans le sens horaire à partir du paramètre _startAngle_ jusqu'au deuxième côté de la section de tarte. |


**See also:**

**[Example # 1](#example_95)**: The following example shows how to compose an animated GIF image from individ...


### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_167}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| width | float | Largeur du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| height | float | Hauteur du rectangle englobant qui définit l'ellipse à partir de laquelle provient la section de tarte. |
| start_angle | float | Angle en degrés mesuré dans le sens horaire à partir de l'axe x jusqu'au premier côté de la section de tarte. |
| sweep_angle | float | Angle en degrés mesuré dans le sens horaire à partir du paramètre _startAngle_ jusqu'au deuxième côté de la section de tarte. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_168}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| width | int | Largeur du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| height | int | Hauteur du rectangle englobant qui définit l'ellipse à partir de laquelle provient la section de tarte. |
| start_angle | int | Angle en degrés mesuré dans le sens horaire à partir de l'axe x jusqu'au premier côté de la section de tarte. |
| sweep_angle | int | Angle en degrés mesuré dans le sens horaire à partir du paramètre _startAngle_ jusqu'au deuxième côté de la section de tarte. |

### Method: fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_at_xy_brush_x_y_width_height_start_angle_sweep_angle_169}


```
 fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle) 
```

Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| width | int | Largeur du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| height | int | Hauteur du rectangle englobant qui définit l'ellipse à partir de laquelle provient la section de tarte. |
| start_angle | int | Angle en degrés mesuré dans le sens horaire à partir de l'axe x jusqu'au premier côté de la section de tarte. |
| sweep_angle | int | Angle en degrés mesuré dans le sens horaire à partir du paramètre _startAngle_ jusqu'au deuxième côté de la section de tarte. |

### Method: fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_at_xyf_brush_x_y_width_height_start_angle_sweep_angle_170}


```
 fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle) 
```

Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| width | float | Largeur du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| height | float | Hauteur du rectangle englobant qui définit l'ellipse à partir de laquelle provient la section de tarte. |
| start_angle | float | Angle en degrés mesuré dans le sens horaire à partir de l'axe x jusqu'au premier côté de la section de tarte. |
| sweep_angle | float | Angle en degrés mesuré dans le sens horaire à partir du paramètre _startAngle_ jusqu'au deuxième côté de la section de tarte. |

### Method: fill_pie_in_rect(brush, rect, start_angle, sweep_angle) {#fill_pie_in_rect_brush_rect_start_angle_sweep_angle_171}


```
 fill_pie_in_rect(brush, rect, start_angle, sweep_angle) 
```

Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) et deux lignes radiales.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) qui représente le rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| start_angle | float | Angle en degrés mesuré dans le sens horaire à partir de l'axe x jusqu'au premier côté de la section de tarte. |
| sweep_angle | float | Angle en degrés mesuré dans le sens horaire à partir du paramètre _startAngle_ jusqu'au deuxième côté de la section de tarte. |

### Method: fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle) {#fill_pie_in_rect_f_brush_rect_start_angle_sweep_angle_172}


```
 fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle) 
```

Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) et deux lignes radiales.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure qui représente le rectangle englobant qui définit l'ellipse à partir de laquelle provient la section de tarte. |
| start_angle | float | Angle en degrés mesuré dans le sens horaire à partir de l'axe x jusqu'au premier côté de la section de tarte. |
| sweep_angle | float | Angle en degrés mesuré dans le sens horaire à partir du paramètre _startAngle_ jusqu'au deuxième côté de la section de tarte. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_173}


```
 fill_polygon(brush, points) 
```

Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [PointF](/imaging/python-net/aspose.imaging/pointf/) et le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représentent les sommets du polygone à remplir. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_174}


```
 fill_polygon(brush, points) 
```

Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [PointF](/imaging/python-net/aspose.imaging/pointf/) et le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représentent les sommets du polygone à remplir. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_175}


```
 fill_polygon(brush, points, fill_mode) 
```

Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant le mode de remplissage spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représentent les sommets du polygone à remplir. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Membre de l'énumération [FillMode](/imaging/python-net/aspose.imaging/fillmode/) qui détermine le style du remplissage. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_176}


```
 fill_polygon(brush, points, fill_mode) 
```

Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant le mode de remplissage spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représentent les sommets du polygone à remplir. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Membre de l'énumération [FillMode](/imaging/python-net/aspose.imaging/fillmode/) qui détermine le style du remplissage. |

### Method: fill_polygon_by_point(brush, points) {#fill_polygon_by_point_brush_points_177}


```
 fill_polygon_by_point(brush, points) 
```

Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [PointF](/imaging/python-net/aspose.imaging/pointf/) et le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représentent les sommets du polygone à remplir. |

### Method: fill_polygon_by_point_f(brush, points) {#fill_polygon_by_point_f_brush_points_178}


```
 fill_polygon_by_point_f(brush, points) 
```

Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [PointF](/imaging/python-net/aspose.imaging/pointf/) et le mode de remplissage [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représentent les sommets du polygone à remplir. |

### Method: fill_polygon_by_point_f_fill_mode(brush, points, fill_mode) {#fill_polygon_by_point_f_fill_mode_brush_points_fill_mode_179}


```
 fill_polygon_by_point_f_fill_mode(brush, points, fill_mode) 
```

Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [PointF](/imaging/python-net/aspose.imaging/pointf/) en utilisant le mode de remplissage spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représentent les sommets du polygone à remplir. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Membre de l'énumération [FillMode](/imaging/python-net/aspose.imaging/fillmode/) qui détermine le style du remplissage. |

### Method: fill_polygon_by_point_fill_mode(brush, points, fill_mode) {#fill_polygon_by_point_fill_mode_brush_points_fill_mode_180}


```
 fill_polygon_by_point_fill_mode(brush, points, fill_mode) 
```

Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [Point](/imaging/python-net/aspose.imaging/point/) en utilisant le mode de remplissage spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Tableau de structures [Point](/imaging/python-net/aspose.imaging/point/) qui représentent les sommets du polygone à remplir. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Membre de l'énumération [FillMode](/imaging/python-net/aspose.imaging/fillmode/) qui détermine le style du remplissage. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_181}


```
 fill_rectangle(brush, rect) 
```

Remplit l'intérieur d'un rectangle spécifié par une structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) qui représente le rectangle à remplir. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_182}


```
 fill_rectangle(brush, rect) 
```

Remplit l'intérieur d'un rectangle spécifié par une structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) qui représente le rectangle à remplir. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_183}


```
 fill_rectangle(brush, x, y, width, height) 
```

Remplit l'intérieur d'un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle à remplir. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle à remplir. |
| width | float | Largeur du rectangle à remplir. |
| height | float | Hauteur du rectangle à remplir. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_184}


```
 fill_rectangle(brush, x, y, width, height) 
```

Remplit l'intérieur d'un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle à remplir. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle à remplir. |
| width | int | Largeur du rectangle à remplir. |
| height | int | Hauteur du rectangle à remplir. |

### Method: fill_rectangle_f(brush, rect) {#fill_rectangle_f_brush_rect_185}


```
 fill_rectangle_f(brush, rect) 
```

Remplit l'intérieur d'un rectangle spécifié par une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représente le rectangle à remplir. |

### Method: fill_rectangle_f_with_brush(brush, x, y, width, height) {#fill_rectangle_f_with_brush_brush_x_y_width_height_186}


```
 fill_rectangle_f_with_brush(brush, x, y, width, height) 
```

Remplit l'intérieur d'un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle à remplir. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle à remplir. |
| width | float | Largeur du rectangle à remplir. |
| height | float | Hauteur du rectangle à remplir. |

### Method: fill_rectangle_with_brush(brush, x, y, width, height) {#fill_rectangle_with_brush_brush_x_y_width_height_187}


```
 fill_rectangle_with_brush(brush, x, y, width, height) 
```

Remplit l'intérieur d'un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle à remplir. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle à remplir. |
| width | int | Largeur du rectangle à remplir. |
| height | int | Hauteur du rectangle à remplir. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_188}


```
 fill_rectangles(brush, rects) 
```

Remplit l'intérieur d'une série de rectangles spécifiés par des structures [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| rects | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | Tableau de structures [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) qui représentent les rectangles à remplir. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_189}


```
 fill_rectangles(brush, rects) 
```

Remplit l'intérieur d'une série de rectangles spécifiés par des structures [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Tableau de structures [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) qui représentent les rectangles à remplir. |

### Method: fill_rectangles_f(brush, rects) {#fill_rectangles_f_brush_rects_190}


```
 fill_rectangles_f(brush, rects) 
```

Remplit l'intérieur d'une série de rectangles spécifiés par des structures [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Tableau de structures [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) qui représentent les rectangles à remplir. |

### Method: fill_region(brush, region) {#fill_region_brush_region_191}


```
 fill_region(brush, region) 
```

Remplit l'intérieur d'une [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) qui détermine les caractéristiques du remplissage. |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | [Region](/imaging/python-net/aspose.imaging/region/) qui représente la zone à remplir. |

### Method: measure_string(text, font, layout_area, string_format) {#measure_string_text_font_layout_area_string_format_192}


```
 measure_string(text, font, layout_area, string_format) 
```

Mesure la chaîne de texte spécifiée avec les paramètres spécifiés

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| text | string | Le texte à mesurer. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | La police à mesurer. |
| layout_area | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | La zone de mise en page. |
| string_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Le format de chaîne. |

**Returns**

| Type | Description |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Taille en pixels de la chaîne de texte mesurée |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_193}


```
 multiply_transform(matrix) 
```

Multiplie la [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui représente la transformation géométrique locale de ce [Graphics](/imaging/python-net/aspose.imaging/graphics/) par la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée en préfixant la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) par laquelle multiplier la transformation géométrique. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_194}


```
 multiply_transform(matrix, order) 
```

Multiplie la [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui représente la transformation géométrique locale de ce [Graphics](/imaging/python-net/aspose.imaging/graphics/) par la [Matrix](/imaging/python-net/aspose.imaging/matrix/) dans l'ordre spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) par laquelle multiplier la transformation géométrique. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) qui spécifie dans quel ordre multiplier les deux matrices. |

### Method: rotate_transform(angle) {#rotate_transform_angle_195}


```
 rotate_transform(angle) 
```

Fait pivoter la transformation géométrique locale de la valeur spécifiée. Cette méthode préfixe la rotation à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_196}


```
 rotate_transform(angle, order) 
```

Fait pivoter la transformation géométrique locale de la valeur spécifiée dans l'ordre indiqué.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) qui spécifie s'il faut ajouter ou préfixer la matrice de rotation. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_197}


```
 scale_transform(sx, sy) 
```

Redimensionne la transformation géométrique locale par les valeurs spécifiées. Cette méthode préfixe la matrice d'échelle à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| sx | float | La valeur par laquelle redimensionner la transformation selon l'axe x. |
| sy | float | La valeur par laquelle redimensionner la transformation selon l'axe y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_198}


```
 scale_transform(sx, sy, order) 
```

Redimensionne la transformation géométrique locale par les valeurs spécifiées dans l'ordre indiqué.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| sx | float | La valeur par laquelle redimensionner la transformation selon l'axe x. |
| sy | float | La valeur par laquelle redimensionner la transformation selon l'axe y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) qui spécifie s'il faut ajouter ou préfixer la matrice d'échelle. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_199}


```
 translate_transform(dx, dy) 
```

Transalte la transformation géométrique locale des dimensions spécifiées. Cette méthode préfixe la translation à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la translation en y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_200}


```
 translate_transform(dx, dy, order) 
```

Transalte la transformation géométrique locale des dimensions spécifiées dans l'ordre indiqué.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la translation en y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | L'ordre (préfixer ou ajouter) dans lequel appliquer la translation. |

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

#Crée une instance de flux de fichier
with open(r"C:\temp\output.png", "w+b") as stream:
	#Créez une instance de PngOptions et définissez ses différentes propriétés
	pngOptions = PngOptions()
	#Définissez la source pour PngOptions
	pngOptions.source = StreamSource(stream)
	#Créez une instance de Image
	with Image.create(pngOptions, 500, 500) as image:
		#Créez et initialisez une instance de la classe Graphics
		graphics = Graphics(image)
		#Efface la surface Graphics
		graphics.clear(Color.wheat);
		#Dessinez un arc en spécifiant l'objet Pen de couleur noire, 
		#un Rectangle entourant l'arc, l'angle de départ et l'angle de balayage
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#Dessinez un Bézier en spécifiant l'objet Pen de couleur bleue et les points de coordonnées.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#Dessinez une courbe en spécifiant l'objet Pen ayant la couleur Verte et un tableau de Points
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#Dessinez une ellipse en utilisant l'objet Pen et un rectangle environnant
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#Dessinez une ligne
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#Dessinez un segment de tarte
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#Dessinez un polygone en spécifiant l'objet Pen ayant la couleur Rouge et un tableau de Points
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#Dessinez un rectangle
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#Créez un objet SolidBrush et définissez ses différentes propriétés
		brush = SolidBrush()
		brush.color = Color.purple
		#Dessinez un String en utilisant l'objet SolidBrush et Font, à un Point spécifique
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# enregistrez toutes les modifications.
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


# Créez une instance d'un flux de fichier
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# Créez une instance de TiffOptions et définissez ses différentes propriétés
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Définissez la source pour l'instance de ImageOptions
	tiffOptions.source = StreamSource(stream)
	# Créez une instance de Image
	with Image.create(tiffOptions, 500, 500) as image:
		# Créez et initialisez une instance de la classe Graphics
		graphics = Graphics(image)
		# Efface la surface Graphics
		graphics.clear(Color.wheat);
		# Créez une instance de la classe GraphicsPath
		graphics_path = GraphicsPath()
		# Créez une instance de la classe Figure
		figure = Figure()
		# Ajoutez des formes à l'objet Figure
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# Ajoutez l'objet Figure à GraphicsPath
		graphics_path.add_figure(figure)
		# Dessinez le chemin avec l'objet Pen de couleur Noir
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# enregistrez toutes les modifications.
		image.save()


```

### This example shows the creation and usage Pen objects. The example creates a new Image and draw rectangles on the Image surface. {#example_14}
``` python

from aspose.imaging import Image, Graphics, Color, Pen, Rectangle, Point, Size
from aspose.imaging.brushes import HatchBrush
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

# Créez une instance de BmpOptions et définissez ses différentes propriétés
bmpOptions = BmpOptions()
bmpOptions.bits_per_pixel = 24
# Créez une instance de FileCreateSource et assignez‑la comme Source pour l'instance de BmpOptions
# Le deuxième paramètre booléen détermine si le fichier à créer est temporaire ou non
bmpOptions.source = FileCreateSource(r"C:\temp\sample.bmp", False)
# Créez une instance d'Image au chemin spécifié
with Image.create(bmpOptions, 500, 500) as image:
	# Créez une instance de Graphics et initialisez‑la avec l'objet Image
	graphics = Graphics(image)
	# Effacez la surface Graphics avec la couleur blanche
	graphics.clear(Color.white)
	#Créez une instance de Pen avec la couleur Rouge et une largeur de 5
	pen = Pen(Color.red, 5.0);
	# Créez une instance de HatchBrush et définissez ses propriétés
	brush = HatchBrush()
	brush.background_color = Color.wheat;
	brush.foreground_color = Color.red;
	# Créez une instance de Pen
	# initialisez-le avec l'objet HatchBrush et la largeur
	brusedpen = Pen(brush, 5.0)
	# Dessinez des rectangles en spécifiant l'objet Pen
	graphics.draw_rectangles(pen, [
		Rectangle(Point(210, 210), Size(100, 100)),
		Rectangle(Point(110, 110), Size(100, 100)),
		Rectangle(Point(310, 310), Size(100, 100)) ])

	# Dessinez des rectangles en spécifiant l'objet Pen
	graphics.draw_rectangles(brusedpen, [
		Rectangle(Point(310, 110), Size(100, 100)),
		Rectangle(Point(110, 310), Size(100, 100)) ])

	# enregistrez toutes les modifications.
	image.save()


```

### The following example shows how to compose an animated GIF image from individual GIF blocks. {#example_95}
``` python
from aspose.imaging.fileformats.gif.blocks import GifFrameBlock
from aspose.imaging.fileformats.gif import GifImage 
from aspose.imaging.brushes import SolidBrush
from aspose.imaging import Graphics, Color

# Créez une image GIF de 100 x 100 px.
# Le premier bloc est entièrement noir par défaut.
with GifFrameBlock(100, 100) as firstBlock:
	with GifImage(firstBlock) as gifImage:
		# Le premier cercle est rouge
		brush1 = SolidBrush(Color.red)

		# Le deuxième cercle est noir
		brush2 = SolidBrush(Color.black)

		# Augmentez progressivement l'angle de la forme d'arc rouge.
		for angle in range(10, 361, 10):
			block = GifFrameBlock(100, 100)
			gr = Graphics(block)
			gr.fill_pie(brush1, block.bounds, 0, angle)
			gifImage.add_block(block)
		
		# Augmentez progressivement l'angle de l'arc noir et effacez l'arc rouge.
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
# Créez une image PNG de 100x100 px.
with PngImage(100, 100) as png_image:
	# Effectuez un traitement d'image, par ex. remplissez toute l'image en rouge.
	graphics = Graphics(png_image)
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, png_image.bounds)
	# Enregistrez dans un fichier.
	png_image.save(join(dir_, "output.png"))


```

