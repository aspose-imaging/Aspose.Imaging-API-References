---
title: "Clase Graphics"
type: docs
weight: 5030
url: /es/python-net/aspose.imaging/graphics/
---

**Summary:** Represents the graphics according to the graphics engine used in the current assembly.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Graphics

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Graphics(source_image)](#Graphics_source_image_1) | Inicializa una nueva instancia de la clase [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| clip | [Region](/imaging/python-net/aspose.imaging/region/) | r/w | Obtiene o establece la región de recorte. |
| compositing_quality | [CompositingQuality](/imaging/python-net/aspose.imaging/compositingquality/) | r/w | Obtiene o establece la calidad de composición. |
| dpi_x | float | r | Obtiene la resolución horizontal de este `aspose.imaging.Graphics`. |
| dpi_y | float | r | Obtiene la resolución vertical de este `aspose.imaging.Graphics`. |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | r | Obtiene la imagen. |
| interpolation_mode | [InterpolationMode](/imaging/python-net/aspose.imaging/interpolationmode/) | r/w | Obtiene o establece el modo de interpolación. |
| is_in_begin_update_call | bool | r | Obtiene un valor que indica si los gráficos están en estado de llamada BeginUpdate. |
| page_scale | float | r/w | Obtiene o establece la escala entre unidades del mundo y unidades de página para este `aspose.imaging.Graphics`. |
| page_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | r/w | Obtiene o establece la unidad de medida utilizada para las coordenadas de página en este `aspose.imaging.Graphics`. |
| paintable_image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | r/w | Obtiene o establece las opciones de imagen, utilizadas para crear imágenes vectoriales pintables para dibujar. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Obtiene o establece el modo de suavizado. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Obtiene o establece la sugerencia de renderizado de texto. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtiene o establece una copia de la transformación geométrica del mundo para este [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| begin_update() | Inicia el almacenamiento en caché de las siguientes operaciones gráficas. Los efectos gráficos aplicados posteriormente no se aplicarán de inmediato; en su lugar, EndUpdate provocará la aplicación de todos los efectos a la vez. |
| [clear(color)](#clear_color_1) | Borra la superficie gráfica usando el color especificado. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_2) | Dibuja un arco que representa una porción de una elipse especificada por una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_3) | Dibuja un arco que representa una porción de una elipse especificada por una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4) | Dibuja un arco que representa una porción de una elipse especificada por un par de coordenadas, un ancho y una altura. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5) | Dibuja un arco que representa una porción de una elipse especificada por un par de coordenadas, un ancho y una altura. |
| [draw_arc_in_rect(pen, rect, start_angle, sweep_angle)](#draw_arc_in_rect_pen_rect_start_angle_sweep_angle_6) | Dibuja un arco que representa una porción de una elipse especificada por una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle)](#draw_arc_in_rect_f_pen_rect_start_angle_sweep_angle_7) | Dibuja un arco que representa una porción de una elipse especificada por una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_xy_pen_x_y_width_height_start_angle_sweep_angle_8) | Dibuja un arco que representa una porción de una elipse especificada por un par de coordenadas, un ancho y una altura. |
| [draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_xyf_pen_x_y_width_height_start_angle_sweep_angle_9) | Dibuja un arco que representa una porción de una elipse especificada por un par de coordenadas, un ancho y una altura. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_10) | Dibuja una spline Bézier definida por cuatro estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_11) | Dibuja una spline Bézier definida por cuatro estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4)](#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_12) | Dibuja una spline Bézier definida por cuatro pares ordenados de coordenadas que representan puntos. |
| [draw_bezier_by_points(pen, pt1, pt2, pt3, pt4)](#draw_bezier_by_points_pen_pt1_pt2_pt3_pt4_13) | Dibuja una spline Bézier definida por cuatro estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4)](#draw_bezier_by_points_f_pen_pt1_pt2_pt3_pt4_14) | Dibuja una spline Bézier definida por cuatro estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_15) | Dibuja una serie de splines Bézier a partir de una matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_16) | Dibuja una serie de splines Bézier a partir de una matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_beziers_by_pt_array(pen, points)](#draw_beziers_by_pt_array_pen_points_17) | Dibuja una serie de splines Bézier a partir de una matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_beziers_by_pt_array_f(pen, points)](#draw_beziers_by_pt_array_f_pen_points_18) | Dibuja una serie de splines Bézier a partir de una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_19) | Dibuja una spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/). Este método utiliza una tensión predeterminada de 0.5 y el modo de relleno [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_20) | Dibuja una spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/). Este método utiliza una tensión predeterminada de 0.5 y el modo de relleno [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_21) | Dibuja una spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizando una tensión especificada. Este método utiliza el modo de relleno predeterminado [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_22) | Dibuja una spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizando una tensión especificada. Este método utiliza el modo de relleno predeterminado [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve_by_points(pen, points)](#draw_closed_curve_by_points_pen_points_23) | Dibuja una spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/). Este método utiliza una tensión predeterminada de 0.5 y el modo de relleno [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve_by_points_f(pen, points)](#draw_closed_curve_by_points_f_pen_points_24) | Dibuja una spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/). Este método utiliza una tensión predeterminada de 0.5 y el modo de relleno [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve_by_points_f_tension(pen, points, tension)](#draw_closed_curve_by_points_f_tension_pen_points_tension_25) | Dibuja una spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizando una tensión especificada. Este método utiliza el modo de relleno predeterminado [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve_by_points_tension(pen, points, tension)](#draw_closed_curve_by_points_tension_pen_points_tension_26) | Dibuja una spline cardinal cerrada definida por una matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/) utilizando una tensión especificada. Este método utiliza el modo de relleno predeterminado [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_curve(pen, points)](#draw_curve_pen_points_27) | Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/). Este método utiliza una tensión predeterminada de 0.5. |
| [draw_curve(pen, points)](#draw_curve_pen_points_28) | Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/). Este método utiliza una tensión predeterminada de 0.5. |
| [draw_curve(pen, points, offset, number_of_segments)](#draw_curve_pen_points_offset_number_of_segments_29) | Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/). El dibujo comienza desplazado desde el inicio de la matriz.<br/>            Este método usa una tensión predeterminada de 0.5. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_30) | Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) usando una tensión especificada. El dibujo comienza desplazado desde el inicio de la matriz. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_31) | Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) usando una tensión especificada. El dibujo comienza desplazado desde el inicio de la matriz. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_32) | Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) usando una tensión especificada. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_33) | Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) usando una tensión especificada. |
| [draw_curve_by_point_fs(pen, points)](#draw_curve_by_point_fs_pen_points_34) | Dibuja una spline cardinal a través de una matriz especificada de estructuras [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_curve_by_point_fs_tension(pen, points, tension)](#draw_curve_by_point_fs_tension_pen_points_tension_35) | Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) usando una tensión especificada. |
| [draw_curve_by_points(pen, points)](#draw_curve_by_points_pen_points_36) | Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/). Este método utiliza una tensión predeterminada de 0.5. |
| [draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension)](#draw_curve_by_points_f_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_37) | Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) usando una tensión especificada. El dibujo comienza desplazado desde el inicio de la matriz. |
| [draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension)](#draw_curve_by_points_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_38) | Dibuja una spline cardinal a través de una matriz especificada de estructuras [Point](/imaging/python-net/aspose.imaging/point/) usando una tensión especificada. |
| [draw_curve_by_points_tension(pen, points, tension)](#draw_curve_by_points_tension_pen_points_tension_39) | Dibuja una spline cardinal a través de una matriz especificada de estructuras [Point](/imaging/python-net/aspose.imaging/point/) usando una tensión especificada. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_40) | Dibuja una elipse definida por un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) delimitador. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_41) | Dibuja una elipse definida por un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) delimitador. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_42) | Dibuja una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, una altura y un ancho. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_43) | Dibuja una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, una altura y un ancho. |
| [draw_ellipse_by_xy(pen, x, y, width, height)](#draw_ellipse_by_xy_pen_x_y_width_height_44) | Dibuja una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, una altura y un ancho. |
| [draw_ellipse_by_xyf(pen, x, y, width, height)](#draw_ellipse_by_xyf_pen_x_y_width_height_45) | Dibuja una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, una altura y un ancho. |
| [draw_ellipse_f(pen, rect)](#draw_ellipse_f_pen_rect_46) | Dibuja una elipse definida por un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) delimitador. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_47) | Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_48) | Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_49) | Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_50) | Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_51) | Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_52) | Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_53) | Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_54) | Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(source_image, point)](#draw_image_source_image_point_55) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada, usando su tamaño físico original, en la ubicación especificada. |
| [draw_image(source_image, point)](#draw_image_source_image_point_56) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada, usando su tamaño físico original, en la ubicación especificada. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_57) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_58) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_59) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_60) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_61) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_62) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_63) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_64) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_65) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_66) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_67) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada, usando su tamaño físico original, en la ubicación especificada. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_68) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada, usando su tamaño físico original, en la ubicación especificada. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_69) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_70) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image_at_point(source_image, point)](#draw_image_at_point_source_image_point_71) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada, usando su tamaño físico original, en la ubicación especificada. |
| [draw_image_at_point_f(source_image, point)](#draw_image_at_point_f_source_image_point_72) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada, usando su tamaño físico original, en la ubicación especificada. |
| [draw_image_at_xy(source_image, x, y)](#draw_image_at_xy_source_image_x_y_73) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada, usando su tamaño físico original, en la ubicación especificada. |
| [draw_image_at_xyf(source_image, x, y)](#draw_image_at_xyf_source_image_x_y_74) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada, usando su tamaño físico original, en la ubicación especificada. |
| [draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit)](#draw_image_dest_point_f_src_rect_f_with_unit_image_dest_points_src_rect_src_unit_75) | Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_dest_point_f_src_rect_f_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_76) | Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect)](#draw_image_dest_points_f_src_rect_f_image_dest_points_src_rect_77) | Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image_dest_points_src_rect(image, dest_points, src_rect)](#draw_image_dest_points_src_rect_image_dest_points_src_rect_78) | Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit)](#draw_image_dest_points_src_rect_with_unit_image_dest_points_src_rect_src_unit_79) | Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_dest_points_src_rect_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_80) | Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_dest_rect_f_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_81) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_dest_rect_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_82) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image_in_rect(source_image, x, y, width, height)](#draw_image_in_rect_source_image_x_y_width_height_83) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image_in_rect_f(source_image, x, y, width, height)](#draw_image_in_rect_f_source_image_x_y_width_height_84) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image_in_rectangle(source_image, rect)](#draw_image_in_rectangle_source_image_rect_85) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image_points(image, dest_points)](#draw_image_points_image_dest_points_86) | Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image_points_f(image, dest_points)](#draw_image_points_f_image_dest_points_87) | Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image_rectangle_f(source_image, rect)](#draw_image_rectangle_f_source_image_rect_88) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_src_dest_rects_f_with_unit_source_image_rect_source_rect_destination_graphics_unit_89) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_src_dest_rects_with_unit_source_image_rect_source_rect_destination_graphics_unit_90) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_src_dst_rect_f_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_91) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_src_dst_rects_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_92) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit)](#draw_image_to_rect_f_with_unit_source_image_rect_destination_graphics_unit_93) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit)](#draw_image_to_rect_with_unit_source_image_rect_destination_graphics_unit_94) | Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image_unscaled(source_image, point)](#draw_image_unscaled_source_image_point_95) | Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada. |
| [draw_image_unscaled(source_image, rect)](#draw_image_unscaled_source_image_rect_96) | Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada. |
| [draw_image_unscaled(source_image, x, y)](#draw_image_unscaled_source_image_x_y_97) | Dibuja la imagen especificada usando su tamaño físico original en la ubicación especificada por un par de coordenadas. |
| [draw_image_unscaled(source_image, x, y, width, height)](#draw_image_unscaled_source_image_x_y_width_height_98) | Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada. |
| [draw_image_unscaled_and_clipped(source_image, rect)](#draw_image_unscaled_and_clipped_source_image_rect_99) | Dibuja la imagen especificada sin escalar y la recorta, si es necesario, para que quepa en el rectángulo especificado. |
| [draw_image_unscaled_in_rectangle(source_image, rect)](#draw_image_unscaled_in_rectangle_source_image_rect_100) | Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada. |
| [draw_image_unscaled_to_point(source_image, point)](#draw_image_unscaled_to_point_source_image_point_101) | Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_102) | Dibuja una línea que conecta dos estructuras [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_103) | Dibuja una línea que conecta dos estructuras [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_104) | Dibuja una línea que conecta los dos puntos especificados por los pares de coordenadas. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_105) | Dibuja una línea que conecta los dos puntos especificados por los pares de coordenadas. |
| [draw_line_by_xy(pen, x1, y1, x2, y2)](#draw_line_by_xy_pen_x1_y1_x2_y2_106) | Dibuja una línea que conecta los dos puntos especificados por los pares de coordenadas. |
| [draw_line_f_by_xy(pen, x1, y1, x2, y2)](#draw_line_f_by_xy_pen_x1_y1_x2_y2_107) | Dibuja una línea que conecta los dos puntos especificados por los pares de coordenadas. |
| [draw_line_point_f(pen, point1, point2)](#draw_line_point_f_pen_point1_point2_108) | Dibuja una línea que conecta dos estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_lines(pen, points)](#draw_lines_pen_points_109) | Dibuja una serie de segmentos de línea que conectan una matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_lines(pen, points)](#draw_lines_pen_points_110) | Dibuja una serie de segmentos de línea que conectan una matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_lines_f(pen, points)](#draw_lines_f_pen_points_111) | Dibuja una serie de segmentos de línea que conectan una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_path(pen, path)](#draw_path_pen_path_112) | Dibuja un [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_113) | Dibuja una forma de pastel definida por una elipse especificada por una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) y dos líneas radiales. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_114) | Dibuja una forma de pastel definida por una elipse especificada por una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) y dos líneas radiales. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_115) | Dibuja una forma de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_116) | Dibuja una forma de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales. |
| [draw_pie_in_rect(pen, rect, start_angle, sweep_angle)](#draw_pie_in_rect_pen_rect_start_angle_sweep_angle_117) | Dibuja una forma de pastel definida por una elipse especificada por una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) y dos líneas radiales. |
| [draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle)](#draw_pie_in_rect_f_pen_rect_start_angle_sweep_angle_118) | Dibuja una forma de pastel definida por una elipse especificada por una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) y dos líneas radiales. |
| [draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_xy_pen_x_y_width_height_start_angle_sweep_angle_119) | Dibuja una forma de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales. |
| [draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_xyf_pen_x_y_width_height_start_angle_sweep_angle_120) | Dibuja una forma de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_121) | Dibuja un polígono definido por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_122) | Dibuja un polígono definido por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_polygon_f(pen, points)](#draw_polygon_f_pen_points_123) | Dibuja un polígono definido por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_rect(pen, x, y, width, height)](#draw_rect_pen_x_y_width_height_124) | Dibuja un rectángulo especificado por un par de coordenadas, un ancho y una altura. |
| [draw_rect_f(pen, x, y, width, height)](#draw_rect_f_pen_x_y_width_height_125) | Dibuja un rectángulo especificado por un par de coordenadas, un ancho y una altura. |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_126) | Dibuja un rectángulo especificado por una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_127) | Dibuja un rectángulo especificado por una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_128) | Dibuja un rectángulo especificado por un par de coordenadas, un ancho y una altura. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_129) | Dibuja un rectángulo especificado por un par de coordenadas, un ancho y una altura. |
| [draw_rectangle_f(pen, rect)](#draw_rectangle_f_pen_rect_130) | Dibuja un rectángulo especificado por una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_131) | Dibuja una serie de rectángulos especificados por estructuras [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_132) | Dibuja una serie de rectángulos especificados por estructuras [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_rectangles_f(pen, rects)](#draw_rectangles_f_pen_rects_133) | Dibuja una serie de rectángulos especificados por estructuras [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_string(s, font, brush, layout_rectangle)](#draw_string_s_font_brush_layout_rectangle_134) | Dibuja la cadena de texto especificada en el rectángulo especificado con los objetos [Brush](/imaging/python-net/aspose.imaging/brush/) y [Font](/imaging/python-net/aspose.imaging/font/) especificados. |
| [draw_string(s, font, brush, layout_rectangle, format)](#draw_string_s_font_brush_layout_rectangle_format_135) | Dibuja la cadena de texto especificada en el rectángulo especificado con los objetos [Brush](/imaging/python-net/aspose.imaging/brush/) y [Font](/imaging/python-net/aspose.imaging/font/) especificados, utilizando los atributos de formato del [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) especificado. |
| [draw_string(s, font, brush, point)](#draw_string_s_font_brush_point_136) | Dibuja la cadena de texto especificada en la ubicación especificada con los objetos [Brush](/imaging/python-net/aspose.imaging/brush/) y [Font](/imaging/python-net/aspose.imaging/font/) especificados. |
| [draw_string(s, font, brush, point, format)](#draw_string_s_font_brush_point_format_137) | Dibuja la cadena de texto especificada en la ubicación especificada con los objetos [Brush](/imaging/python-net/aspose.imaging/brush/) y [Font](/imaging/python-net/aspose.imaging/font/) especificados, utilizando los atributos de formato del [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) especificado. |
| [draw_string(s, font, brush, x, y)](#draw_string_s_font_brush_x_y_138) | Dibuja la cadena de texto especificada en la ubicación especificada con los objetos [Brush](/imaging/python-net/aspose.imaging/brush/) y [Font](/imaging/python-net/aspose.imaging/font/) especificados. |
| [draw_string(s, font, brush, x, y, format)](#draw_string_s_font_brush_x_y_format_139) | Dibuja la cadena de texto especificada en la ubicación especificada con los objetos [Brush](/imaging/python-net/aspose.imaging/brush/) y [Font](/imaging/python-net/aspose.imaging/font/) especificados, utilizando los atributos de formato del [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) especificado. |
| [draw_string_at_point_f(s, font, brush, point)](#draw_string_at_point_f_s_font_brush_point_140) | Dibuja la cadena de texto especificada en la ubicación especificada con los objetos [Brush](/imaging/python-net/aspose.imaging/brush/) y [Font](/imaging/python-net/aspose.imaging/font/) especificados. |
| [draw_string_at_point_f_format(s, font, brush, point, format)](#draw_string_at_point_f_format_s_font_brush_point_format_141) | Dibuja la cadena de texto especificada en la ubicación especificada con los objetos [Brush](/imaging/python-net/aspose.imaging/brush/) y [Font](/imaging/python-net/aspose.imaging/font/) especificados, utilizando los atributos de formato del [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) especificado. |
| [draw_string_at_xy(s, font, brush, x, y)](#draw_string_at_xy_s_font_brush_x_y_142) | Dibuja la cadena de texto especificada en la ubicación especificada con los objetos [Brush](/imaging/python-net/aspose.imaging/brush/) y [Font](/imaging/python-net/aspose.imaging/font/) especificados. |
| [draw_string_in_rect(s, font, brush, layout_rectangle)](#draw_string_in_rect_s_font_brush_layout_rectangle_143) | Dibuja la cadena de texto especificada en el rectángulo especificado con los objetos [Brush](/imaging/python-net/aspose.imaging/brush/) y [Font](/imaging/python-net/aspose.imaging/font/) especificados. |
| [draw_string_in_rect_f(s, font, brush, layout_rectangle, format)](#draw_string_in_rect_f_s_font_brush_layout_rectangle_format_144) | Dibuja la cadena de texto especificada en el rectángulo especificado con los objetos [Brush](/imaging/python-net/aspose.imaging/brush/) y [Font](/imaging/python-net/aspose.imaging/font/) especificados, utilizando los atributos de formato del [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) especificado. |
| end_update() | Finaliza el almacenamiento en caché de las operaciones gráficas iniciadas después de que se llamó a BeginUpdate. Las operaciones gráficas precedentes se aplicarán de inmediato al invocar este método. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_145) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) . Este método utiliza una tensión predeterminada de 0.5 y el modo de relleno [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) . |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_146) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) . Este método utiliza una tensión predeterminada de 0.5 y el modo de relleno [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) . |
| [fill_closed_curve(brush, points, fill_mode)](#fill_closed_curve_brush_points_fill_mode_147) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizando el modo de relleno especificado. Este método utiliza una tensión predeterminada de 0.5. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_148) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizando el modo de relleno especificado. Este método utiliza una tensión predeterminada de 0.5. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_149) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizando el modo de relleno y la tensión especificados. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_150) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizando el modo de relleno y la tensión especificados. |
| [fill_closed_curve_by_point(brush, points)](#fill_closed_curve_by_point_brush_points_151) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) . Este método utiliza una tensión predeterminada de 0.5 y el modo de relleno [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) . |
| [fill_closed_curve_by_point_f(brush, points)](#fill_closed_curve_by_point_f_brush_points_152) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) . Este método utiliza una tensión predeterminada de 0.5 y el modo de relleno [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) . |
| fill_closed_curve_by_point_f_fill_mode(brush, points, fillmode) |  |
| [fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension)](#fill_closed_curve_by_point_f_fill_mode_tension_brush_points_fillmode_tension_153) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizando el modo de relleno y la tensión especificados. |
| [fill_closed_curve_by_point_fill_mode(brush, points, fillmode)](#fill_closed_curve_by_point_fill_mode_brush_points_fillmode_154) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/) utilizando el modo de relleno especificado. Este método utiliza una tensión predeterminada de 0.5. |
| [fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension)](#fill_closed_curve_by_point_fill_mode_tension_brush_points_fillmode_tension_155) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/) utilizando el modo de relleno y la tensión especificados. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_156) | Rellena el interior de una elipse definida por un rectángulo delimitador especificado mediante una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) . |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_157) | Rellena el interior de una elipse definida por un rectángulo delimitador especificado mediante una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) . |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_158) | Rellena el interior de una elipse definida por un rectángulo delimitador especificado mediante un par de coordenadas, un ancho y una altura. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_159) | Rellena el interior de una elipse definida por un rectángulo delimitador especificado mediante un par de coordenadas, un ancho y una altura. |
| [fill_ellipse_at_xywh(brush, x, y, width, height)](#fill_ellipse_at_xywh_brush_x_y_width_height_160) | Rellena el interior de una elipse definida por un rectángulo delimitador especificado mediante un par de coordenadas, un ancho y una altura. |
| [fill_ellipse_at_xywhf(brush, x, y, width, height)](#fill_ellipse_at_xywhf_brush_x_y_width_height_161) | Rellena el interior de una elipse definida por un rectángulo delimitador especificado mediante un par de coordenadas, un ancho y una altura. |
| [fill_ellipse_in_rect(brush, rect)](#fill_ellipse_in_rect_brush_rect_162) | Rellena el interior de una elipse definida por un rectángulo delimitador especificado mediante una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) . |
| [fill_ellipse_in_rect_f(brush, rect)](#fill_ellipse_in_rect_f_brush_rect_163) | Rellena el interior de una elipse definida por un rectángulo delimitador especificado mediante una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) . |
| [fill_path(brush, path)](#fill_path_brush_path_164) | Rellena el interior de un [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_165) | Rellena el interior de una porción de pastel definida por una elipse especificada mediante una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) y dos líneas radiales. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_166) | Rellena el interior de una porción de pastel definida por una elipse especificada mediante una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) y dos líneas radiales. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_167) | Rellena el interior de una porción de pastel definida por una elipse especificada mediante un par de coordenadas, un ancho, una altura y dos líneas radiales. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_168) | Rellena el interior de una porción de pastel definida por una elipse especificada mediante un par de coordenadas, un ancho, una altura y dos líneas radiales. |
| [fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_at_xy_brush_x_y_width_height_start_angle_sweep_angle_169) | Rellena el interior de una porción de pastel definida por una elipse especificada mediante un par de coordenadas, un ancho, una altura y dos líneas radiales. |
| [fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_at_xyf_brush_x_y_width_height_start_angle_sweep_angle_170) | Rellena el interior de una porción de pastel definida por una elipse especificada mediante un par de coordenadas, un ancho, una altura y dos líneas radiales. |
| [fill_pie_in_rect(brush, rect, start_angle, sweep_angle)](#fill_pie_in_rect_brush_rect_start_angle_sweep_angle_171) | Rellena el interior de una porción de pastel definida por una elipse especificada mediante una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) y dos líneas radiales. |
| [fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle)](#fill_pie_in_rect_f_brush_rect_start_angle_sweep_angle_172) | Rellena el interior de una porción de pastel definida por una elipse especificada mediante una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) y dos líneas radiales. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_173) | Rellena el interior de un polígono definido por una matriz de puntos especificados mediante estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) y el modo de relleno [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) . |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_174) | Rellena el interior de un polígono definido por una matriz de puntos especificados mediante estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) y el modo de relleno [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) . |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_175) | Rellena el interior de un polígono definido por una matriz de puntos especificados mediante estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizando el modo de relleno especificado. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_176) | Rellena el interior de un polígono definido por una matriz de puntos especificados mediante estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizando el modo de relleno especificado. |
| [fill_polygon_by_point(brush, points)](#fill_polygon_by_point_brush_points_177) | Rellena el interior de un polígono definido por una matriz de puntos especificados mediante estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) y el modo de relleno [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) . |
| [fill_polygon_by_point_f(brush, points)](#fill_polygon_by_point_f_brush_points_178) | Rellena el interior de un polígono definido por una matriz de puntos especificados mediante estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) y el modo de relleno [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) . |
| [fill_polygon_by_point_f_fill_mode(brush, points, fill_mode)](#fill_polygon_by_point_f_fill_mode_brush_points_fill_mode_179) | Rellena el interior de un polígono definido por una matriz de puntos especificados mediante estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizando el modo de relleno especificado. |
| [fill_polygon_by_point_fill_mode(brush, points, fill_mode)](#fill_polygon_by_point_fill_mode_brush_points_fill_mode_180) | Rellena el interior de un polígono definido por una matriz de puntos especificados mediante estructuras [Point](/imaging/python-net/aspose.imaging/point/) utilizando el modo de relleno especificado. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_181) | Rellena el interior de un rectángulo especificado mediante una estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) . |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_182) | Rellena el interior de un rectángulo especificado mediante una estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) . |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_183) | Rellena el interior de un rectángulo especificado mediante un par de coordenadas, un ancho y una altura. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_184) | Rellena el interior de un rectángulo especificado mediante un par de coordenadas, un ancho y una altura. |
| [fill_rectangle_f(brush, rect)](#fill_rectangle_f_brush_rect_185) | Rellena el interior de un rectángulo especificado mediante una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) . |
| [fill_rectangle_f_with_brush(brush, x, y, width, height)](#fill_rectangle_f_with_brush_brush_x_y_width_height_186) | Rellena el interior de un rectángulo especificado mediante un par de coordenadas, un ancho y una altura. |
| [fill_rectangle_with_brush(brush, x, y, width, height)](#fill_rectangle_with_brush_brush_x_y_width_height_187) | Rellena el interior de un rectángulo especificado mediante un par de coordenadas, un ancho y una altura. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_188) | Rellena los interiores de una serie de rectángulos especificados mediante estructuras [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) . |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_189) | Rellena los interiores de una serie de rectángulos especificados mediante estructuras [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) . |
| [fill_rectangles_f(brush, rects)](#fill_rectangles_f_brush_rects_190) | Rellena los interiores de una serie de rectángulos especificados mediante estructuras [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) . |
| [fill_region(brush, region)](#fill_region_brush_region_191) | Rellena el interior de una [Region](/imaging/python-net/aspose.imaging/region/). |
| [measure_string(text, font, layout_area, string_format)](#measure_string_text_font_layout_area_string_format_192) | Mide la cadena de texto especificada con los parámetros especificados |
| [multiply_transform(matrix)](#multiply_transform_matrix_193) | Multiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) que representa la transformación geométrica local de este [Graphics](/imaging/python-net/aspose.imaging/graphics/) por la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada, anteponiendo la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_194) | Multiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) que representa la transformación geométrica local de este [Graphics](/imaging/python-net/aspose.imaging/graphics/) por la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada en el orden especificado. |
| reset_transform() | Restablece la propiedad [Graphics.transform](/imaging/python-net/aspose.imaging/graphics/) a la identidad. |
| [rotate_transform(angle)](#rotate_transform_angle_195) | Rota la transformación geométrica local en la cantidad especificada. Este método antepone la rotación a la transformación. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_196) | Rota la transformación geométrica local en la cantidad especificada en el orden especificado. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_197) | Escala la transformación geométrica local por las cantidades especificadas. Este método antepone la matriz de escala a la transformación. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_198) | Escala la transformación geométrica local por las cantidades especificadas en el orden especificado. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_199) | Traslada la transformación geométrica local por las dimensiones especificadas. Este método antepone la traslación a la transformación. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_200) | Traslada la transformación geométrica local por las dimensiones especificadas en el orden especificado. |


### Constructor: Graphics(source_image) {#Graphics_source_image_1}


```
 Graphics(source_image) 
```

Inicializa una nueva instancia de la clase [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen de origen. |

### Method: clear(color) {#clear_color_1}


```
 clear(color) 
```

Borra la superficie gráfica usando el color especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | El color con el que se limpia la superficie gráfica. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...

**[Example # 2](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_2}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Dibuja un arco que representa una porción de una elipse especificada por una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo del arco. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) estructura que define los límites de la elipse. |
| start_angle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el punto de inicio del arco. |
| sweep_angle | float | Ángulo en grados medido en sentido horario desde el parámetro _startAngle_ hasta el punto final del arco. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_3}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Dibuja un arco que representa una porción de una elipse especificada por una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo del arco. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) estructura que define los límites de la elipse. |
| start_angle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el punto de inicio del arco. |
| sweep_angle | float | Ángulo en grados medido en sentido horario desde el parámetro _startAngle_ hasta el punto final del arco. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Dibuja un arco que representa una porción de una elipse especificada por un par de coordenadas, un ancho y una altura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo del arco. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo que define la elipse. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo que define la elipse. |
| width | float | Ancho del rectángulo que define la elipse. |
| height | float | Altura del rectángulo que define la elipse. |
| start_angle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el punto de inicio del arco. |
| sweep_angle | float | Ángulo en grados medido en sentido horario desde el parámetro _startAngle_ hasta el punto final del arco. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Dibuja un arco que representa una porción de una elipse especificada por un par de coordenadas, un ancho y una altura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo del arco. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo que define la elipse. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo que define la elipse. |
| width | int | Ancho del rectángulo que define la elipse. |
| height | int | Altura del rectángulo que define la elipse. |
| start_angle | int | Ángulo en grados medido en sentido horario desde el eje x hasta el punto de inicio del arco. |
| sweep_angle | int | Ángulo en grados medido en sentido horario desde el parámetro _startAngle_ hasta el punto final del arco. |

### Method: draw_arc_in_rect(pen, rect, start_angle, sweep_angle) {#draw_arc_in_rect_pen_rect_start_angle_sweep_angle_6}


```
 draw_arc_in_rect(pen, rect, start_angle, sweep_angle) 
```

Dibuja un arco que representa una porción de una elipse especificada por una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo del arco. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) estructura que define los límites de la elipse. |
| start_angle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el punto de inicio del arco. |
| sweep_angle | float | Ángulo en grados medido en sentido horario desde el parámetro _startAngle_ hasta el punto final del arco. |

### Method: draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle) {#draw_arc_in_rect_f_pen_rect_start_angle_sweep_angle_7}


```
 draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle) 
```

Dibuja un arco que representa una porción de una elipse especificada por una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo del arco. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) estructura que define los límites de la elipse. |
| start_angle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el punto de inicio del arco. |
| sweep_angle | float | Ángulo en grados medido en sentido horario desde el parámetro _startAngle_ hasta el punto final del arco. |

### Method: draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_xy_pen_x_y_width_height_start_angle_sweep_angle_8}


```
 draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle) 
```

Dibuja un arco que representa una porción de una elipse especificada por un par de coordenadas, un ancho y una altura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo del arco. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo que define la elipse. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo que define la elipse. |
| width | int | Ancho del rectángulo que define la elipse. |
| height | int | Altura del rectángulo que define la elipse. |
| start_angle | int | Ángulo en grados medido en sentido horario desde el eje x hasta el punto de inicio del arco. |
| sweep_angle | int | Ángulo en grados medido en sentido horario desde el parámetro _startAngle_ hasta el punto final del arco. |

### Method: draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_xyf_pen_x_y_width_height_start_angle_sweep_angle_9}


```
 draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle) 
```

Dibuja un arco que representa una porción de una elipse especificada por un par de coordenadas, un ancho y una altura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo del arco. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo que define la elipse. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo que define la elipse. |
| width | float | Ancho del rectángulo que define la elipse. |
| height | float | Altura del rectángulo que define la elipse. |
| start_angle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el punto de inicio del arco. |
| sweep_angle | float | Ángulo en grados medido en sentido horario desde el parámetro _startAngle_ hasta el punto final del arco. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_10}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Dibuja una spline Bézier definida por cuatro estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la curva. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) estructura que representa el punto de inicio de la curva. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) estructura que representa el primer punto de control de la curva. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) estructura que representa el segundo punto de control de la curva. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) estructura que representa el punto final de la curva. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_11}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Dibuja una spline Bézier definida por cuatro estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la curva. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) estructura que representa el punto de inicio de la curva. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) estructura que representa el primer punto de control de la curva. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) estructura que representa el segundo punto de control de la curva. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) estructura que representa el punto final de la curva. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) {#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_12}


```
 draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) 
```

Dibuja una spline Bézier definida por cuatro pares ordenados de coordenadas que representan puntos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la curva. |
| x1 | float | La coordenada x del punto de inicio de la curva. |
| y1 | float | La coordenada y del punto de inicio de la curva. |
| x2 | float | La coordenada x del primer punto de control de la curva. |
| y2 | float | La coordenada y del primer punto de control de la curva. |
| x3 | float | La coordenada x del segundo punto de control de la curva. |
| y3 | float | La coordenada y del segundo punto de control de la curva. |
| x4 | float | La coordenada x del punto final de la curva. |
| y4 | float | La coordenada y del punto final de la curva. |

### Method: draw_bezier_by_points(pen, pt1, pt2, pt3, pt4) {#draw_bezier_by_points_pen_pt1_pt2_pt3_pt4_13}


```
 draw_bezier_by_points(pen, pt1, pt2, pt3, pt4) 
```

Dibuja una spline Bézier definida por cuatro estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la curva. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) estructura que representa el punto de inicio de la curva. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) estructura que representa el primer punto de control de la curva. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) estructura que representa el segundo punto de control de la curva. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) estructura que representa el punto final de la curva. |

### Method: draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4) {#draw_bezier_by_points_f_pen_pt1_pt2_pt3_pt4_14}


```
 draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4) 
```

Dibuja una spline Bézier definida por cuatro estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la curva. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) estructura que representa el punto de inicio de la curva. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) estructura que representa el primer punto de control de la curva. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) estructura que representa el segundo punto de control de la curva. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) estructura que representa el punto final de la curva. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_15}


```
 draw_beziers(pen, points) 
```

Dibuja una serie de splines Bézier a partir de una matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la curva. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/) que representan los puntos que determinan la curva. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_16}


```
 draw_beziers(pen, points) 
```

Dibuja una serie de splines Bézier a partir de una matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la curva. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/) que representan los puntos que determinan la curva. |

### Method: draw_beziers_by_pt_array(pen, points) {#draw_beziers_by_pt_array_pen_points_17}


```
 draw_beziers_by_pt_array(pen, points) 
```

Dibuja una serie de splines Bézier a partir de una matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la curva. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/) que representan los puntos que determinan la curva. |

### Method: draw_beziers_by_pt_array_f(pen, points) {#draw_beziers_by_pt_array_f_pen_points_18}


```
 draw_beziers_by_pt_array_f(pen, points) 
```

Dibuja una serie de splines Bézier a partir de una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la curva. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que representan los puntos que determinan la curva. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_19}


```
 draw_closed_curve(pen, points) 
```

Dibuja una spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/). Este método utiliza una tensión predeterminada de 0.5 y el modo de relleno [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que definen la spline. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_20}


```
 draw_closed_curve(pen, points) 
```

Dibuja una spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/). Este método utiliza una tensión predeterminada de 0.5 y el modo de relleno [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que definen la spline. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_21}


```
 draw_closed_curve(pen, points, tension) 
```

Dibuja una spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizando una tensión especificada. Este método utiliza el modo de relleno predeterminado [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que definen la spline. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_22}


```
 draw_closed_curve(pen, points, tension) 
```

Dibuja una spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizando una tensión especificada. Este método utiliza el modo de relleno predeterminado [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que definen la spline. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Method: draw_closed_curve_by_points(pen, points) {#draw_closed_curve_by_points_pen_points_23}


```
 draw_closed_curve_by_points(pen, points) 
```

Dibuja una spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/). Este método utiliza una tensión predeterminada de 0.5 y el modo de relleno [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que definen la spline. |

### Method: draw_closed_curve_by_points_f(pen, points) {#draw_closed_curve_by_points_f_pen_points_24}


```
 draw_closed_curve_by_points_f(pen, points) 
```

Dibuja una spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/). Este método utiliza una tensión predeterminada de 0.5 y el modo de relleno [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que definen la spline. |

### Method: draw_closed_curve_by_points_f_tension(pen, points, tension) {#draw_closed_curve_by_points_f_tension_pen_points_tension_25}


```
 draw_closed_curve_by_points_f_tension(pen, points, tension) 
```

Dibuja una spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizando una tensión especificada. Este método utiliza el modo de relleno predeterminado [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que definen la spline. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Method: draw_closed_curve_by_points_tension(pen, points, tension) {#draw_closed_curve_by_points_tension_pen_points_tension_26}


```
 draw_closed_curve_by_points_tension(pen, points, tension) 
```

Dibuja una spline cardinal cerrada definida por una matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/) utilizando una tensión especificada. Este método utiliza el modo de relleno predeterminado [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/) que definen la spline. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_27}


```
 draw_curve(pen, points) 
```

Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/). Este método utiliza una tensión predeterminada de 0.5.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que definen la spline. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_curve(pen, points) {#draw_curve_pen_points_28}


```
 draw_curve(pen, points) 
```

Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/). Este método utiliza una tensión predeterminada de 0.5.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que definen la spline. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_curve(pen, points, offset, number_of_segments) {#draw_curve_pen_points_offset_number_of_segments_29}


```
 draw_curve(pen, points, offset, number_of_segments) 
```

Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/). El dibujo comienza desplazado desde el inicio de la matriz.<br/>            Este método usa una tensión predeterminada de 0.5.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que definen la spline. |
| offset | int | Desplazamiento desde el primer elemento en la matriz del parámetro _points_ hasta el punto de inicio en la curva. |
| number_of_segments | int | Número de segmentos después del punto de inicio que se incluyen en la curva. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_30}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) usando una tensión especificada. El dibujo comienza desplazado desde el inicio de la matriz.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que definen la spline. |
| offset | int | Desplazamiento desde el primer elemento en la matriz del parámetro _points_ hasta el punto de inicio en la curva. |
| number_of_segments | int | Número de segmentos después del punto de inicio que se incluyen en la curva. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_31}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) usando una tensión especificada. El dibujo comienza desplazado desde el inicio de la matriz.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que definen la spline. |
| offset | int | Desplazamiento desde el primer elemento en la matriz del parámetro _points_ hasta el punto de inicio en la curva. |
| number_of_segments | int | Número de segmentos después del punto de inicio que se incluyen en la curva. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_32}


```
 draw_curve(pen, points, tension) 
```

Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) usando una tensión especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que representan los puntos que definen la curva. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_33}


```
 draw_curve(pen, points, tension) 
```

Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) usando una tensión especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que representan los puntos que definen la curva. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Method: draw_curve_by_point_fs(pen, points) {#draw_curve_by_point_fs_pen_points_34}


```
 draw_curve_by_point_fs(pen, points) 
```

Dibuja una spline cardinal a través de una matriz especificada de estructuras [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/) que definen la spline. |

### Method: draw_curve_by_point_fs_tension(pen, points, tension) {#draw_curve_by_point_fs_tension_pen_points_tension_35}


```
 draw_curve_by_point_fs_tension(pen, points, tension) 
```

Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) usando una tensión especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que representan los puntos que definen la curva. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Method: draw_curve_by_points(pen, points) {#draw_curve_by_points_pen_points_36}


```
 draw_curve_by_points(pen, points) 
```

Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/). Este método utiliza una tensión predeterminada de 0.5.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que definen la spline. |

### Method: draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) {#draw_curve_by_points_f_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_37}


```
 draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) 
```

Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) usando una tensión especificada. El dibujo comienza desplazado desde el inicio de la matriz.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que definen la spline. |
| offset | int | Desplazamiento desde el primer elemento en la matriz del parámetro _points_ hasta el punto de inicio en la curva. |
| number_of_segments | int | Número de segmentos después del punto de inicio que se incluyen en la curva. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Method: draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) {#draw_curve_by_points_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_38}


```
 draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) 
```

Dibuja una spline cardinal a través de una matriz especificada de estructuras [Point](/imaging/python-net/aspose.imaging/point/) usando una tensión especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/) que definen la spline. |
| offset | int | Desplazamiento desde el primer elemento en la matriz del parámetro _points_ hasta el punto de inicio en la curva. |
| number_of_segments | int | Número de segmentos después del punto de inicio que se incluyen en la curva. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Method: draw_curve_by_points_tension(pen, points, tension) {#draw_curve_by_points_tension_pen_points_tension_39}


```
 draw_curve_by_points_tension(pen, points, tension) 
```

Dibuja una spline cardinal a través de una matriz especificada de estructuras [Point](/imaging/python-net/aspose.imaging/point/) usando una tensión especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/) que definen la spline. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_40}


```
 draw_ellipse(pen, rect) 
```

Dibuja una elipse definida por un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) delimitador.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la elipse. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) estructura que define los límites de la elipse. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_41}


```
 draw_ellipse(pen, rect) 
```

Dibuja una elipse definida por un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) delimitador.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la elipse. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) estructura que define los límites de la elipse. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_42}


```
 draw_ellipse(pen, x, y, width, height) 
```

Dibuja una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, una altura y un ancho.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la elipse. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| width | float | Ancho del rectángulo delimitador que define la elipse. |
| height | float | Altura del rectángulo delimitador que define la elipse. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_43}


```
 draw_ellipse(pen, x, y, width, height) 
```

Dibuja una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, una altura y un ancho.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la elipse. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| width | int | Ancho del rectángulo delimitador que define la elipse. |
| height | int | Altura del rectángulo delimitador que define la elipse. |

### Method: draw_ellipse_by_xy(pen, x, y, width, height) {#draw_ellipse_by_xy_pen_x_y_width_height_44}


```
 draw_ellipse_by_xy(pen, x, y, width, height) 
```

Dibuja una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, una altura y un ancho.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la elipse. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| width | int | Ancho del rectángulo delimitador que define la elipse. |
| height | int | Altura del rectángulo delimitador que define la elipse. |

### Method: draw_ellipse_by_xyf(pen, x, y, width, height) {#draw_ellipse_by_xyf_pen_x_y_width_height_45}


```
 draw_ellipse_by_xyf(pen, x, y, width, height) 
```

Dibuja una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, una altura y un ancho.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la elipse. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| width | float | Ancho del rectángulo delimitador que define la elipse. |
| height | float | Altura del rectángulo delimitador que define la elipse. |

### Method: draw_ellipse_f(pen, rect) {#draw_ellipse_f_pen_rect_46}


```
 draw_ellipse_f(pen, rect) 
```

Dibuja una elipse definida por un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) delimitador.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la elipse. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) estructura que define los límites de la elipse. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_47}


```
 draw_image(image, dest_points) 
```

Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen a dibujar. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de tres estructuras PointF que definen un paralelogramo. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_48}


```
 draw_image(image, dest_points) 
```

Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen a dibujar. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de tres estructuras PointF que definen un paralelogramo. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_49}


```
 draw_image(image, dest_points, src_rect) 
```

Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen a dibujar. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de tres estructuras PointF que definen un paralelogramo. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de origen. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_50}


```
 draw_image(image, dest_points, src_rect) 
```

Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen a dibujar. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de tres estructuras PointF que definen un paralelogramo. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El rectángulo de origen. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_51}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen a dibujar. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de tres estructuras PointF que definen un paralelogramo. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de origen. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Las unidades de medida. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_52}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen a dibujar. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de tres estructuras PointF que definen un paralelogramo. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El rectángulo de origen. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Las unidades de medida. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_53}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen a dibujar. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de tres estructuras PointF que definen un paralelogramo. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de origen. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Las unidades de medida. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Los atributos de la imagen. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_54}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen a dibujar. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de tres estructuras PointF que definen un paralelogramo. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El rectángulo de origen. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Las unidades de medida. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Los atributos de la imagen. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_55}


```
 draw_image(source_image, point) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada, usando su tamaño físico original, en la ubicación especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) estructura que representa la esquina superior izquierda de la imagen dibujada. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_56}


```
 draw_image(source_image, point) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada, usando su tamaño físico original, en la ubicación especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) estructura que representa la esquina superior izquierda de la imagen dibujada. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_57}


```
 draw_image(source_image, rect) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) estructura que especifica la ubicación y el tamaño de la imagen dibujada. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_58}


```
 draw_image(source_image, rect) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) estructura que especifica la ubicación y el tamaño de la imagen dibujada. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_59}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de destino. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | La unidad gráfica. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_60}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El rectángulo de destino. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | La unidad gráfica. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_61}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de destino. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | La unidad gráfica. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Los atributos de la imagen. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_62}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El rectángulo de destino. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | La unidad gráfica. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Los atributos de la imagen. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_63}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de origen. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de destino. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | La unidad gráfica. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_64}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El rectángulo de origen. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El rectángulo de destino. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | La unidad gráfica. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_65}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de origen. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de destino. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | La unidad gráfica. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Los atributos de la imagen. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_66}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El rectángulo de origen. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El rectángulo de destino. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | La unidad gráfica. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Los atributos de la imagen. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_67}


```
 draw_image(source_image, x, y) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada, usando su tamaño físico original, en la ubicación especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| x | float | La coordenada x de la esquina superior izquierda de la imagen dibujada. |
| y | float | La coordenada y de la esquina superior izquierda de la imagen dibujada. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_68}


```
 draw_image(source_image, x, y) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada, usando su tamaño físico original, en la ubicación especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| x | int | La coordenada x de la esquina superior izquierda de la imagen dibujada. |
| y | int | La coordenada y de la esquina superior izquierda de la imagen dibujada. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_69}


```
 draw_image(source_image, x, y, width, height) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| x | float | La coordenada x de la esquina superior izquierda de la imagen dibujada. |
| y | float | La coordenada y de la esquina superior izquierda de la imagen dibujada. |
| width | float | Ancho de la imagen dibujada. |
| height | float | Altura de la imagen dibujada. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_70}


```
 draw_image(source_image, x, y, width, height) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| x | int | La coordenada x de la esquina superior izquierda de la imagen dibujada. |
| y | int | La coordenada y de la esquina superior izquierda de la imagen dibujada. |
| width | int | Ancho de la imagen dibujada. |
| height | int | Altura de la imagen dibujada. |

### Method: draw_image_at_point(source_image, point) {#draw_image_at_point_source_image_point_71}


```
 draw_image_at_point(source_image, point) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada, usando su tamaño físico original, en la ubicación especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) estructura que representa la esquina superior izquierda de la imagen dibujada. |

### Method: draw_image_at_point_f(source_image, point) {#draw_image_at_point_f_source_image_point_72}


```
 draw_image_at_point_f(source_image, point) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada, usando su tamaño físico original, en la ubicación especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) estructura que representa la esquina superior izquierda de la imagen dibujada. |

### Method: draw_image_at_xy(source_image, x, y) {#draw_image_at_xy_source_image_x_y_73}


```
 draw_image_at_xy(source_image, x, y) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada, usando su tamaño físico original, en la ubicación especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| x | int | La coordenada x de la esquina superior izquierda de la imagen dibujada. |
| y | int | La coordenada y de la esquina superior izquierda de la imagen dibujada. |

### Method: draw_image_at_xyf(source_image, x, y) {#draw_image_at_xyf_source_image_x_y_74}


```
 draw_image_at_xyf(source_image, x, y) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada, usando su tamaño físico original, en la ubicación especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| x | float | La coordenada x de la esquina superior izquierda de la imagen dibujada. |
| y | float | La coordenada y de la esquina superior izquierda de la imagen dibujada. |

### Method: draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit) {#draw_image_dest_point_f_src_rect_f_with_unit_image_dest_points_src_rect_src_unit_75}


```
 draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit) 
```

Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen a dibujar. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de tres estructuras PointF que definen un paralelogramo. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El rectángulo de origen. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Las unidades de medida. |

### Method: draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_dest_point_f_src_rect_f_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_76}


```
 draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) 
```

Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen a dibujar. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de tres estructuras PointF que definen un paralelogramo. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El rectángulo de origen. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Las unidades de medida. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Los atributos de la imagen. |

### Method: draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect) {#draw_image_dest_points_f_src_rect_f_image_dest_points_src_rect_77}


```
 draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect) 
```

Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen a dibujar. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de tres estructuras PointF que definen un paralelogramo. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El rectángulo de origen. |

### Method: draw_image_dest_points_src_rect(image, dest_points, src_rect) {#draw_image_dest_points_src_rect_image_dest_points_src_rect_78}


```
 draw_image_dest_points_src_rect(image, dest_points, src_rect) 
```

Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen a dibujar. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de tres estructuras PointF que definen un paralelogramo. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de origen. |

### Method: draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit) {#draw_image_dest_points_src_rect_with_unit_image_dest_points_src_rect_src_unit_79}


```
 draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit) 
```

Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen a dibujar. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de tres estructuras PointF que definen un paralelogramo. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de origen. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Las unidades de medida. |

### Method: draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_dest_points_src_rect_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_80}


```
 draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) 
```

Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen a dibujar. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de tres estructuras PointF que definen un paralelogramo. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de origen. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Las unidades de medida. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Los atributos de la imagen. |

### Method: draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_dest_rect_f_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_81}


```
 draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El rectángulo de destino en el que dibujar. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | La unidad gráfica. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Los atributos de la imagen. |

### Method: draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_dest_rect_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_82}


```
 draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de destino. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | La unidad gráfica. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Los atributos de la imagen. |

### Method: draw_image_in_rect(source_image, x, y, width, height) {#draw_image_in_rect_source_image_x_y_width_height_83}


```
 draw_image_in_rect(source_image, x, y, width, height) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| x | int | La coordenada x de la esquina superior izquierda de la imagen dibujada. |
| y | int | La coordenada y de la esquina superior izquierda de la imagen dibujada. |
| width | int | Ancho de la imagen dibujada. |
| height | int | Altura de la imagen dibujada. |

### Method: draw_image_in_rect_f(source_image, x, y, width, height) {#draw_image_in_rect_f_source_image_x_y_width_height_84}


```
 draw_image_in_rect_f(source_image, x, y, width, height) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| x | float | La coordenada x de la esquina superior izquierda de la imagen dibujada. |
| y | float | La coordenada y de la esquina superior izquierda de la imagen dibujada. |
| width | float | Ancho de la imagen dibujada. |
| height | float | Altura de la imagen dibujada. |

### Method: draw_image_in_rectangle(source_image, rect) {#draw_image_in_rectangle_source_image_rect_85}


```
 draw_image_in_rectangle(source_image, rect) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) estructura que especifica la ubicación y el tamaño de la imagen dibujada. |

### Method: draw_image_points(image, dest_points) {#draw_image_points_image_dest_points_86}


```
 draw_image_points(image, dest_points) 
```

Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen a dibujar. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de tres estructuras PointF que definen un paralelogramo. |

### Method: draw_image_points_f(image, dest_points) {#draw_image_points_f_image_dest_points_87}


```
 draw_image_points_f(image, dest_points) 
```

Dibuja la porción especificada de la _imagen_ especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen a dibujar. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de tres estructuras PointF que definen un paralelogramo. |

### Method: draw_image_rectangle_f(source_image, rect) {#draw_image_rectangle_f_source_image_rect_88}


```
 draw_image_rectangle_f(source_image, rect) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) estructura que especifica la ubicación y el tamaño de la imagen dibujada. |

### Method: draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_src_dest_rects_f_with_unit_source_image_rect_source_rect_destination_graphics_unit_89}


```
 draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El rectángulo de origen. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El rectángulo de destino. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | La unidad gráfica. |

### Method: draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_src_dest_rects_with_unit_source_image_rect_source_rect_destination_graphics_unit_90}


```
 draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de origen. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de destino. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | La unidad gráfica. |

### Method: draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_src_dst_rect_f_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_91}


```
 draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El rectángulo de origen. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El rectángulo de destino. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | La unidad gráfica a usar. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Los atributos de la imagen a usar. |

### Method: draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_src_dst_rects_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_92}


```
 draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de origen. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de destino. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | La unidad gráfica. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Los atributos de la imagen. |

### Method: draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit) {#draw_image_to_rect_f_with_unit_source_image_rect_destination_graphics_unit_93}


```
 draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El rectángulo de destino. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | La unidad gráfica. |

### Method: draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit) {#draw_image_to_rect_with_unit_source_image_rect_destination_graphics_unit_94}


```
 draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit) 
```

Dibuja la [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de destino. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | La unidad gráfica. |

### Method: draw_image_unscaled(source_image, point) {#draw_image_unscaled_source_image_point_95}


```
 draw_image_unscaled(source_image, point) 
```

Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) estructura que especifica la esquina superior izquierda de la imagen dibujada. |

### Method: draw_image_unscaled(source_image, rect) {#draw_image_unscaled_source_image_rect_96}


```
 draw_image_unscaled(source_image, rect) 
```

Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) que especifica la esquina superior izquierda de la imagen dibujada. Las propiedades X e Y del rectángulo especifican la esquina superior izquierda. Las propiedades Width y Height se ignoran. |

### Method: draw_image_unscaled(source_image, x, y) {#draw_image_unscaled_source_image_x_y_97}


```
 draw_image_unscaled(source_image, x, y) 
```

Dibuja la imagen especificada usando su tamaño físico original en la ubicación especificada por un par de coordenadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| x | int | La coordenada x de la esquina superior izquierda de la imagen dibujada. |
| y | int | La coordenada y de la esquina superior izquierda de la imagen dibujada. |

### Method: draw_image_unscaled(source_image, x, y, width, height) {#draw_image_unscaled_source_image_x_y_width_height_98}


```
 draw_image_unscaled(source_image, x, y, width, height) 
```

Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| x | int | La coordenada x de la esquina superior izquierda de la imagen dibujada. |
| y | int | La coordenada y de la esquina superior izquierda de la imagen dibujada. |
| width | int | El parámetro no se utiliza. |
| height | int | El parámetro no se utiliza. |

### Method: draw_image_unscaled_and_clipped(source_image, rect) {#draw_image_unscaled_and_clipped_source_image_rect_99}


```
 draw_image_unscaled_and_clipped(source_image, rect) 
```

Dibuja la imagen especificada sin escalar y la recorta, si es necesario, para que quepa en el rectángulo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) en el que dibujar la imagen. |

### Method: draw_image_unscaled_in_rectangle(source_image, rect) {#draw_image_unscaled_in_rectangle_source_image_rect_100}


```
 draw_image_unscaled_in_rectangle(source_image, rect) 
```

Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) que especifica la esquina superior izquierda de la imagen dibujada. Las propiedades X e Y del rectángulo especifican la esquina superior izquierda. Las propiedades Width y Height se ignoran. |

### Method: draw_image_unscaled_to_point(source_image, point) {#draw_image_unscaled_to_point_source_image_point_101}


```
 draw_image_unscaled_to_point(source_image, point) 
```

Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | La imagen con la que dibujar. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) estructura que especifica la esquina superior izquierda de la imagen dibujada. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_102}


```
 draw_line(pen, point1, point2) 
```

Dibuja una línea que conecta dos estructuras [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la línea. |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) estructura que representa el primer punto a conectar. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) estructura que representa el segundo punto a conectar. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_103}


```
 draw_line(pen, point1, point2) 
```

Dibuja una línea que conecta dos estructuras [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la línea. |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [Point](/imaging/python-net/aspose.imaging/point/) estructura que representa el primer punto a conectar. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [Point](/imaging/python-net/aspose.imaging/point/) estructura que representa el segundo punto a conectar. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_104}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Dibuja una línea que conecta los dos puntos especificados por los pares de coordenadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la línea. |
| x1 | int | La coordenada x del primer punto. |
| y1 | int | La coordenada y del primer punto. |
| x2 | int | La coordenada x del segundo punto. |
| y2 | int | La coordenada y del segundo punto. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_105}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Dibuja una línea que conecta los dos puntos especificados por los pares de coordenadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la línea. |
| x1 | float | La coordenada x del primer punto. |
| y1 | float | La coordenada y del primer punto. |
| x2 | float | La coordenada x del segundo punto. |
| y2 | float | La coordenada y del segundo punto. |

### Method: draw_line_by_xy(pen, x1, y1, x2, y2) {#draw_line_by_xy_pen_x1_y1_x2_y2_106}


```
 draw_line_by_xy(pen, x1, y1, x2, y2) 
```

Dibuja una línea que conecta los dos puntos especificados por los pares de coordenadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la línea. |
| x1 | int | La coordenada x del primer punto. |
| y1 | int | La coordenada y del primer punto. |
| x2 | int | La coordenada x del segundo punto. |
| y2 | int | La coordenada y del segundo punto. |

### Method: draw_line_f_by_xy(pen, x1, y1, x2, y2) {#draw_line_f_by_xy_pen_x1_y1_x2_y2_107}


```
 draw_line_f_by_xy(pen, x1, y1, x2, y2) 
```

Dibuja una línea que conecta los dos puntos especificados por los pares de coordenadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la línea. |
| x1 | float | La coordenada x del primer punto. |
| y1 | float | La coordenada y del primer punto. |
| x2 | float | La coordenada x del segundo punto. |
| y2 | float | La coordenada y del segundo punto. |

### Method: draw_line_point_f(pen, point1, point2) {#draw_line_point_f_pen_point1_point2_108}


```
 draw_line_point_f(pen, point1, point2) 
```

Dibuja una línea que conecta dos estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la línea. |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) estructura que representa el primer punto a conectar. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) estructura que representa el segundo punto a conectar. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_109}


```
 draw_lines(pen, points) 
```

Dibuja una serie de segmentos de línea que conectan una matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de los segmentos de línea. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/) que representan los puntos a conectar. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_110}


```
 draw_lines(pen, points) 
```

Dibuja una serie de segmentos de línea que conectan una matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de los segmentos de línea. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/) que representan los puntos a conectar. |

### Method: draw_lines_f(pen, points) {#draw_lines_f_pen_points_111}


```
 draw_lines_f(pen, points) 
```

Dibuja una serie de segmentos de línea que conectan una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de los segmentos de línea. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que representan los puntos a conectar. |

### Method: draw_path(pen, path) {#draw_path_pen_path_112}


```
 draw_path(pen, path) 
```

Dibuja un [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la ruta. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) para dibujar. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_113}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Dibuja una forma de pastel definida por una elipse especificada por una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) y dos líneas radiales.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la forma de pastel. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) estructura que representa el rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| start_angle | float | Ángulo medido en grados en sentido horario desde el eje x hasta el primer lado de la forma de pastel. |
| sweep_angle | float | Ángulo medido en grados en sentido horario desde el parámetro _startAngle_ hasta el segundo lado de la forma de pastel. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_114}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Dibuja una forma de pastel definida por una elipse especificada por una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) y dos líneas radiales.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la forma de pastel. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) estructura que representa el rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| start_angle | float | Ángulo medido en grados en sentido horario desde el eje x hasta el primer lado de la forma de pastel. |
| sweep_angle | float | Ángulo medido en grados en sentido horario desde el parámetro _startAngle_ hasta el segundo lado de la forma de pastel. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_115}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Dibuja una forma de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la forma de pastel. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| width | float | Ancho del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| height | float | Altura del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| start_angle | float | Ángulo medido en grados en sentido horario desde el eje x hasta el primer lado de la forma de pastel. |
| sweep_angle | float | Ángulo medido en grados en sentido horario desde el parámetro _startAngle_ hasta el segundo lado de la forma de pastel. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_116}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Dibuja una forma de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la forma de pastel. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| width | int | Ancho del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| height | int | Altura del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| start_angle | int | Ángulo medido en grados en sentido horario desde el eje x hasta el primer lado de la forma de pastel. |
| sweep_angle | int | Ángulo medido en grados en sentido horario desde el parámetro _startAngle_ hasta el segundo lado de la forma de pastel. |

### Method: draw_pie_in_rect(pen, rect, start_angle, sweep_angle) {#draw_pie_in_rect_pen_rect_start_angle_sweep_angle_117}


```
 draw_pie_in_rect(pen, rect, start_angle, sweep_angle) 
```

Dibuja una forma de pastel definida por una elipse especificada por una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) y dos líneas radiales.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la forma de pastel. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) estructura que representa el rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| start_angle | float | Ángulo medido en grados en sentido horario desde el eje x hasta el primer lado de la forma de pastel. |
| sweep_angle | float | Ángulo medido en grados en sentido horario desde el parámetro _startAngle_ hasta el segundo lado de la forma de pastel. |

### Method: draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle) {#draw_pie_in_rect_f_pen_rect_start_angle_sweep_angle_118}


```
 draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle) 
```

Dibuja una forma de pastel definida por una elipse especificada por una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) y dos líneas radiales.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la forma de pastel. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) estructura que representa el rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| start_angle | float | Ángulo medido en grados en sentido horario desde el eje x hasta el primer lado de la forma de pastel. |
| sweep_angle | float | Ángulo medido en grados en sentido horario desde el parámetro _startAngle_ hasta el segundo lado de la forma de pastel. |

### Method: draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_xy_pen_x_y_width_height_start_angle_sweep_angle_119}


```
 draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle) 
```

Dibuja una forma de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la forma de pastel. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| width | int | Ancho del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| height | int | Altura del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| start_angle | int | Ángulo medido en grados en sentido horario desde el eje x hasta el primer lado de la forma de pastel. |
| sweep_angle | int | Ángulo medido en grados en sentido horario desde el parámetro _startAngle_ hasta el segundo lado de la forma de pastel. |

### Method: draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_xyf_pen_x_y_width_height_start_angle_sweep_angle_120}


```
 draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle) 
```

Dibuja una forma de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de la forma de pastel. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| width | float | Ancho del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| height | float | Altura del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| start_angle | float | Ángulo medido en grados en sentido horario desde el eje x hasta el primer lado de la forma de pastel. |
| sweep_angle | float | Ángulo medido en grados en sentido horario desde el parámetro _startAngle_ hasta el segundo lado de la forma de pastel. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_121}


```
 draw_polygon(pen, points) 
```

Dibuja un polígono definido por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo del polígono. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que representan los vértices del polígono. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_122}


```
 draw_polygon(pen, points) 
```

Dibuja un polígono definido por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo del polígono. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que representan los vértices del polígono. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_polygon_f(pen, points) {#draw_polygon_f_pen_points_123}


```
 draw_polygon_f(pen, points) 
```

Dibuja un polígono definido por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo del polígono. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que representan los vértices del polígono. |

### Method: draw_rect(pen, x, y, width, height) {#draw_rect_pen_x_y_width_height_124}


```
 draw_rect(pen, x, y, width, height) 
```

Dibuja un rectángulo especificado por un par de coordenadas, un ancho y una altura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Un [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo del rectángulo. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo a dibujar. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo a dibujar. |
| width | int | El ancho del rectángulo a dibujar. |
| height | int | La altura del rectángulo a dibujar. |

### Method: draw_rect_f(pen, x, y, width, height) {#draw_rect_f_pen_x_y_width_height_125}


```
 draw_rect_f(pen, x, y, width, height) 
```

Dibuja un rectángulo especificado por un par de coordenadas, un ancho y una altura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Un [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo del rectángulo. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo a dibujar. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo a dibujar. |
| width | float | El ancho del rectángulo a dibujar. |
| height | float | La altura del rectángulo a dibujar. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_126}


```
 draw_rectangle(pen, rect) 
```

Dibuja un rectángulo especificado por una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Un [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo del rectángulo. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que representa el rectángulo a dibujar. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_127}


```
 draw_rectangle(pen, rect) 
```

Dibuja un rectángulo especificado por una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Un [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo del rectángulo. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que representa el rectángulo a dibujar. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_128}


```
 draw_rectangle(pen, x, y, width, height) 
```

Dibuja un rectángulo especificado por un par de coordenadas, un ancho y una altura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Un [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo del rectángulo. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo a dibujar. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo a dibujar. |
| width | float | El ancho del rectángulo a dibujar. |
| height | float | La altura del rectángulo a dibujar. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_129}


```
 draw_rectangle(pen, x, y, width, height) 
```

Dibuja un rectángulo especificado por un par de coordenadas, un ancho y una altura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Un [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo del rectángulo. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo a dibujar. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo a dibujar. |
| width | int | El ancho del rectángulo a dibujar. |
| height | int | La altura del rectángulo a dibujar. |

### Method: draw_rectangle_f(pen, rect) {#draw_rectangle_f_pen_rect_130}


```
 draw_rectangle_f(pen, rect) 
```

Dibuja un rectángulo especificado por una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Un [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo del rectángulo. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que representa el rectángulo a dibujar. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_131}


```
 draw_rectangles(pen, rects) 
```

Dibuja una serie de rectángulos especificados por estructuras [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de los contornos de los rectángulos. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Matriz de estructuras [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que representan los rectángulos a dibujar. |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_132}


```
 draw_rectangles(pen, rects) 
```

Dibuja una serie de rectángulos especificados por estructuras [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de los contornos de los rectángulos. |
| rects | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | Matriz de estructuras [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que representan los rectángulos a dibujar. |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: draw_rectangles_f(pen, rects) {#draw_rectangles_f_pen_rects_133}


```
 draw_rectangles_f(pen, rects) 
```

Dibuja una serie de rectángulos especificados por estructuras [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) que determina el color, el ancho y el estilo de los contornos de los rectángulos. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Matriz de estructuras [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que representan los rectángulos a dibujar. |

### Method: draw_string(s, font, brush, layout_rectangle) {#draw_string_s_font_brush_layout_rectangle_134}


```
 draw_string(s, font, brush, layout_rectangle) 
```

Dibuja la cadena de texto especificada en el rectángulo especificado con los objetos [Brush](/imaging/python-net/aspose.imaging/brush/) y [Font](/imaging/python-net/aspose.imaging/font/) especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| s | string | Cadena a dibujar. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) que define el formato de texto de la cadena. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina el color y la textura del texto dibujado. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que especifica la ubicación del texto dibujado. |

### Method: draw_string(s, font, brush, layout_rectangle, format) {#draw_string_s_font_brush_layout_rectangle_format_135}


```
 draw_string(s, font, brush, layout_rectangle, format) 
```

Dibuja la cadena de texto especificada en el rectángulo especificado con los objetos [Brush](/imaging/python-net/aspose.imaging/brush/) y [Font](/imaging/python-net/aspose.imaging/font/) especificados, utilizando los atributos de formato del [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| s | string | Cadena a dibujar. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) que define el formato de texto de la cadena. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina el color y la textura del texto dibujado. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que especifica la ubicación del texto dibujado. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) que especifica atributos de formato, como el interlineado y la alineación, que se aplican al texto dibujado. |

### Method: draw_string(s, font, brush, point) {#draw_string_s_font_brush_point_136}


```
 draw_string(s, font, brush, point) 
```

Dibuja la cadena de texto especificada en la ubicación especificada con los objetos [Brush](/imaging/python-net/aspose.imaging/brush/) y [Font](/imaging/python-net/aspose.imaging/font/) especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| s | string | Cadena a dibujar. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) que define el formato de texto de la cadena. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina el color y la textura del texto dibujado. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Estructura [PointF](/imaging/python-net/aspose.imaging/pointf/) que especifica la esquina superior izquierda del texto dibujado. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_string(s, font, brush, point, format) {#draw_string_s_font_brush_point_format_137}


```
 draw_string(s, font, brush, point, format) 
```

Dibuja la cadena de texto especificada en la ubicación especificada con los objetos [Brush](/imaging/python-net/aspose.imaging/brush/) y [Font](/imaging/python-net/aspose.imaging/font/) especificados, utilizando los atributos de formato del [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| s | string | Cadena a dibujar. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) que define el formato de texto de la cadena. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina el color y la textura del texto dibujado. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Estructura [PointF](/imaging/python-net/aspose.imaging/pointf/) que especifica la esquina superior izquierda del texto dibujado. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) que especifica atributos de formato, como el interlineado y la alineación, que se aplican al texto dibujado. |

### Method: draw_string(s, font, brush, x, y) {#draw_string_s_font_brush_x_y_138}


```
 draw_string(s, font, brush, x, y) 
```

Dibuja la cadena de texto especificada en la ubicación especificada con los objetos [Brush](/imaging/python-net/aspose.imaging/brush/) y [Font](/imaging/python-net/aspose.imaging/font/) especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| s | string | Cadena a dibujar. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) que define el formato de texto de la cadena. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina el color y la textura del texto dibujado. |
| x | float | La coordenada x de la esquina superior izquierda del texto dibujado. |
| y | float | La coordenada y de la esquina superior izquierda del texto dibujado. |

### Method: draw_string(s, font, brush, x, y, format) {#draw_string_s_font_brush_x_y_format_139}


```
 draw_string(s, font, brush, x, y, format) 
```

Dibuja la cadena de texto especificada en la ubicación especificada con los objetos [Brush](/imaging/python-net/aspose.imaging/brush/) y [Font](/imaging/python-net/aspose.imaging/font/) especificados, utilizando los atributos de formato del [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| s | string | Cadena a dibujar. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) que define el formato de texto de la cadena. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina el color y la textura del texto dibujado. |
| x | float | La coordenada x de la esquina superior izquierda del texto dibujado. |
| y | float | La coordenada y de la esquina superior izquierda del texto dibujado. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) que especifica atributos de formato, como el interlineado y la alineación, que se aplican al texto dibujado. |

### Method: draw_string_at_point_f(s, font, brush, point) {#draw_string_at_point_f_s_font_brush_point_140}


```
 draw_string_at_point_f(s, font, brush, point) 
```

Dibuja la cadena de texto especificada en la ubicación especificada con los objetos [Brush](/imaging/python-net/aspose.imaging/brush/) y [Font](/imaging/python-net/aspose.imaging/font/) especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| s | string | Cadena a dibujar. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) que define el formato de texto de la cadena. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina el color y la textura del texto dibujado. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Estructura [PointF](/imaging/python-net/aspose.imaging/pointf/) que especifica la esquina superior izquierda del texto dibujado. |

### Method: draw_string_at_point_f_format(s, font, brush, point, format) {#draw_string_at_point_f_format_s_font_brush_point_format_141}


```
 draw_string_at_point_f_format(s, font, brush, point, format) 
```

Dibuja la cadena de texto especificada en la ubicación especificada con los objetos [Brush](/imaging/python-net/aspose.imaging/brush/) y [Font](/imaging/python-net/aspose.imaging/font/) especificados, utilizando los atributos de formato del [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| s | string | Cadena a dibujar. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) que define el formato de texto de la cadena. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina el color y la textura del texto dibujado. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Estructura [PointF](/imaging/python-net/aspose.imaging/pointf/) que especifica la esquina superior izquierda del texto dibujado. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) que especifica atributos de formato, como el interlineado y la alineación, que se aplican al texto dibujado. |

### Method: draw_string_at_xy(s, font, brush, x, y) {#draw_string_at_xy_s_font_brush_x_y_142}


```
 draw_string_at_xy(s, font, brush, x, y) 
```

Dibuja la cadena de texto especificada en la ubicación especificada con los objetos [Brush](/imaging/python-net/aspose.imaging/brush/) y [Font](/imaging/python-net/aspose.imaging/font/) especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| s | string | Cadena a dibujar. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) que define el formato de texto de la cadena. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina el color y la textura del texto dibujado. |
| x | float | La coordenada x de la esquina superior izquierda del texto dibujado. |
| y | float | La coordenada y de la esquina superior izquierda del texto dibujado. |

### Method: draw_string_in_rect(s, font, brush, layout_rectangle) {#draw_string_in_rect_s_font_brush_layout_rectangle_143}


```
 draw_string_in_rect(s, font, brush, layout_rectangle) 
```

Dibuja la cadena de texto especificada en el rectángulo especificado con los objetos [Brush](/imaging/python-net/aspose.imaging/brush/) y [Font](/imaging/python-net/aspose.imaging/font/) especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| s | string | Cadena a dibujar. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) que define el formato de texto de la cadena. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina el color y la textura del texto dibujado. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que especifica la ubicación del texto dibujado. |

### Method: draw_string_in_rect_f(s, font, brush, layout_rectangle, format) {#draw_string_in_rect_f_s_font_brush_layout_rectangle_format_144}


```
 draw_string_in_rect_f(s, font, brush, layout_rectangle, format) 
```

Dibuja la cadena de texto especificada en el rectángulo especificado con los objetos [Brush](/imaging/python-net/aspose.imaging/brush/) y [Font](/imaging/python-net/aspose.imaging/font/) especificados, utilizando los atributos de formato del [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| s | string | Cadena a dibujar. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) que define el formato de texto de la cadena. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina el color y la textura del texto dibujado. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que especifica la ubicación del texto dibujado. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) que especifica atributos de formato, como el interlineado y la alineación, que se aplican al texto dibujado. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_145}


```
 fill_closed_curve(brush, points) 
```

Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) . Este método utiliza una tensión predeterminada de 0.5 y el modo de relleno [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) .

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que definen la spline. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_146}


```
 fill_closed_curve(brush, points) 
```

Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) . Este método utiliza una tensión predeterminada de 0.5 y el modo de relleno [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) .

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que definen la spline. |

### Method: fill_closed_curve(brush, points, fill_mode) {#fill_closed_curve_brush_points_fill_mode_147}


```
 fill_closed_curve(brush, points, fill_mode) 
```

Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizando el modo de relleno especificado. Este método utiliza una tensión predeterminada de 0.5.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que definen la spline. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Miembro de la enumeración [FillMode](/imaging/python-net/aspose.imaging/fillmode/) que determina cómo se rellena la curva. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_148}


```
 fill_closed_curve(brush, points, fillmode) 
```

Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizando el modo de relleno especificado. Este método utiliza una tensión predeterminada de 0.5.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que definen la spline. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) |  |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_149}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizando el modo de relleno y la tensión especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Un [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que definen la spline. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Miembro de la enumeración [FillMode](/imaging/python-net/aspose.imaging/fillmode/) que determina cómo se rellena la curva. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_150}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizando el modo de relleno y la tensión especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Un [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que definen la spline. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Miembro de la enumeración [FillMode](/imaging/python-net/aspose.imaging/fillmode/) que determina cómo se rellena la curva. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Method: fill_closed_curve_by_point(brush, points) {#fill_closed_curve_by_point_brush_points_151}


```
 fill_closed_curve_by_point(brush, points) 
```

Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) . Este método utiliza una tensión predeterminada de 0.5 y el modo de relleno [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) .

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que definen la spline. |

### Method: fill_closed_curve_by_point_f(brush, points) {#fill_closed_curve_by_point_f_brush_points_152}


```
 fill_closed_curve_by_point_f(brush, points) 
```

Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) . Este método utiliza una tensión predeterminada de 0.5 y el modo de relleno [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) .

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que definen la spline. |

### Method: fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension) {#fill_closed_curve_by_point_f_fill_mode_tension_brush_points_fillmode_tension_153}


```
 fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension) 
```

Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizando el modo de relleno y la tensión especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Un [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Matriz de estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) que definen la spline. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Miembro de la enumeración [FillMode](/imaging/python-net/aspose.imaging/fillmode/) que determina cómo se rellena la curva. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Method: fill_closed_curve_by_point_fill_mode(brush, points, fillmode) {#fill_closed_curve_by_point_fill_mode_brush_points_fillmode_154}


```
 fill_closed_curve_by_point_fill_mode(brush, points, fillmode) 
```

Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/) utilizando el modo de relleno especificado. Este método utiliza una tensión predeterminada de 0.5.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/) que definen la spline. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Miembro de la enumeración [FillMode](/imaging/python-net/aspose.imaging/fillmode/) que determina cómo se rellena la curva. |

### Method: fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension) {#fill_closed_curve_by_point_fill_mode_tension_brush_points_fillmode_tension_155}


```
 fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension) 
```

Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/) utilizando el modo de relleno y la tensión especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Matriz de estructuras [Point](/imaging/python-net/aspose.imaging/point/) que definen la spline. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Miembro de la enumeración [FillMode](/imaging/python-net/aspose.imaging/fillmode/) que determina cómo se rellena la curva. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_156}


```
 fill_ellipse(brush, rect) 
```

Rellena el interior de una elipse definida por un rectángulo delimitador especificado mediante una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) .

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que representa el rectángulo delimitador que define la elipse. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_157}


```
 fill_ellipse(brush, rect) 
```

Rellena el interior de una elipse definida por un rectángulo delimitador especificado mediante una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) .

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que representa el rectángulo delimitador que define la elipse. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_158}


```
 fill_ellipse(brush, x, y, width, height) 
```

Rellena el interior de una elipse definida por un rectángulo delimitador especificado mediante un par de coordenadas, un ancho y una altura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| width | float | Ancho del rectángulo delimitador que define la elipse. |
| height | float | Altura del rectángulo delimitador que define la elipse. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_159}


```
 fill_ellipse(brush, x, y, width, height) 
```

Rellena el interior de una elipse definida por un rectángulo delimitador especificado mediante un par de coordenadas, un ancho y una altura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| width | int | Ancho del rectángulo delimitador que define la elipse. |
| height | int | Altura del rectángulo delimitador que define la elipse. |

### Method: fill_ellipse_at_xywh(brush, x, y, width, height) {#fill_ellipse_at_xywh_brush_x_y_width_height_160}


```
 fill_ellipse_at_xywh(brush, x, y, width, height) 
```

Rellena el interior de una elipse definida por un rectángulo delimitador especificado mediante un par de coordenadas, un ancho y una altura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| width | int | Ancho del rectángulo delimitador que define la elipse. |
| height | int | Altura del rectángulo delimitador que define la elipse. |

### Method: fill_ellipse_at_xywhf(brush, x, y, width, height) {#fill_ellipse_at_xywhf_brush_x_y_width_height_161}


```
 fill_ellipse_at_xywhf(brush, x, y, width, height) 
```

Rellena el interior de una elipse definida por un rectángulo delimitador especificado mediante un par de coordenadas, un ancho y una altura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| width | float | Ancho del rectángulo delimitador que define la elipse. |
| height | float | Altura del rectángulo delimitador que define la elipse. |

### Method: fill_ellipse_in_rect(brush, rect) {#fill_ellipse_in_rect_brush_rect_162}


```
 fill_ellipse_in_rect(brush, rect) 
```

Rellena el interior de una elipse definida por un rectángulo delimitador especificado mediante una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) .

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que representa el rectángulo delimitador que define la elipse. |

### Method: fill_ellipse_in_rect_f(brush, rect) {#fill_ellipse_in_rect_f_brush_rect_163}


```
 fill_ellipse_in_rect_f(brush, rect) 
```

Rellena el interior de una elipse definida por un rectángulo delimitador especificado mediante una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) .

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que representa el rectángulo delimitador que define la elipse. |

### Method: fill_path(brush, path) {#fill_path_brush_path_164}


```
 fill_path(brush, path) 
```

Rellena el interior de un [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) que representa la ruta a rellenar. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_165}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Rellena el interior de una porción de pastel definida por una elipse especificada mediante una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) y dos líneas radiales.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) que representa el rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| start_angle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el primer lado de la sección de pastel. |
| sweep_angle | float | Ángulo en grados medido en sentido horario desde el parámetro _startAngle_ hasta el segundo lado de la sección de pastel. |


**See also:**

**[Example # 1](#example_95)**: The following example shows how to compose an animated GIF image from individ...


### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_166}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Rellena el interior de una porción de pastel definida por una elipse especificada mediante una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) y dos líneas radiales.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) que representa el rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| start_angle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el primer lado de la sección de pastel. |
| sweep_angle | float | Ángulo en grados medido en sentido horario desde el parámetro _startAngle_ hasta el segundo lado de la sección de pastel. |


**See also:**

**[Example # 1](#example_95)**: The following example shows how to compose an animated GIF image from individ...


### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_167}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Rellena el interior de una porción de pastel definida por una elipse especificada mediante un par de coordenadas, un ancho, una altura y dos líneas radiales.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| width | float | Ancho del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| height | float | Altura del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| start_angle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el primer lado de la sección de pastel. |
| sweep_angle | float | Ángulo en grados medido en sentido horario desde el parámetro _startAngle_ hasta el segundo lado de la sección de pastel. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_168}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Rellena el interior de una porción de pastel definida por una elipse especificada mediante un par de coordenadas, un ancho, una altura y dos líneas radiales.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| width | int | Ancho del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| height | int | Altura del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| start_angle | int | Ángulo en grados medido en sentido horario desde el eje x hasta el primer lado de la sección de pastel. |
| sweep_angle | int | Ángulo en grados medido en sentido horario desde el parámetro _startAngle_ hasta el segundo lado de la sección de pastel. |

### Method: fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_at_xy_brush_x_y_width_height_start_angle_sweep_angle_169}


```
 fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle) 
```

Rellena el interior de una porción de pastel definida por una elipse especificada mediante un par de coordenadas, un ancho, una altura y dos líneas radiales.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| width | int | Ancho del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| height | int | Altura del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| start_angle | int | Ángulo en grados medido en sentido horario desde el eje x hasta el primer lado de la sección de pastel. |
| sweep_angle | int | Ángulo en grados medido en sentido horario desde el parámetro _startAngle_ hasta el segundo lado de la sección de pastel. |

### Method: fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_at_xyf_brush_x_y_width_height_start_angle_sweep_angle_170}


```
 fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle) 
```

Rellena el interior de una porción de pastel definida por una elipse especificada mediante un par de coordenadas, un ancho, una altura y dos líneas radiales.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| width | float | Ancho del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| height | float | Altura del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| start_angle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el primer lado de la sección de pastel. |
| sweep_angle | float | Ángulo en grados medido en sentido horario desde el parámetro _startAngle_ hasta el segundo lado de la sección de pastel. |

### Method: fill_pie_in_rect(brush, rect, start_angle, sweep_angle) {#fill_pie_in_rect_brush_rect_start_angle_sweep_angle_171}


```
 fill_pie_in_rect(brush, rect, start_angle, sweep_angle) 
```

Rellena el interior de una porción de pastel definida por una elipse especificada mediante una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) y dos líneas radiales.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) que representa el rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| start_angle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el primer lado de la sección de pastel. |
| sweep_angle | float | Ángulo en grados medido en sentido horario desde el parámetro _startAngle_ hasta el segundo lado de la sección de pastel. |

### Method: fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle) {#fill_pie_in_rect_f_brush_rect_start_angle_sweep_angle_172}


```
 fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle) 
```

Rellena el interior de una porción de pastel definida por una elipse especificada mediante una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) y dos líneas radiales.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) estructura que representa el rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| start_angle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el primer lado de la sección de pastel. |
| sweep_angle | float | Ángulo en grados medido en sentido horario desde el parámetro _startAngle_ hasta el segundo lado de la sección de pastel. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_173}


```
 fill_polygon(brush, points) 
```

Rellena el interior de un polígono definido por una matriz de puntos especificados mediante estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) y el modo de relleno [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) .

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Arreglo de [PointF](/imaging/python-net/aspose.imaging/pointf/) estructuras que representan los vértices del polígono a rellenar. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_174}


```
 fill_polygon(brush, points) 
```

Rellena el interior de un polígono definido por una matriz de puntos especificados mediante estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) y el modo de relleno [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) .

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Arreglo de [PointF](/imaging/python-net/aspose.imaging/pointf/) estructuras que representan los vértices del polígono a rellenar. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_175}


```
 fill_polygon(brush, points, fill_mode) 
```

Rellena el interior de un polígono definido por una matriz de puntos especificados mediante estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizando el modo de relleno especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Arreglo de [PointF](/imaging/python-net/aspose.imaging/pointf/) estructuras que representan los vértices del polígono a rellenar. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Miembro de la enumeración [FillMode](/imaging/python-net/aspose.imaging/fillmode/) que determina el estilo del relleno. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_176}


```
 fill_polygon(brush, points, fill_mode) 
```

Rellena el interior de un polígono definido por una matriz de puntos especificados mediante estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizando el modo de relleno especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Arreglo de [PointF](/imaging/python-net/aspose.imaging/pointf/) estructuras que representan los vértices del polígono a rellenar. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Miembro de la enumeración [FillMode](/imaging/python-net/aspose.imaging/fillmode/) que determina el estilo del relleno. |

### Method: fill_polygon_by_point(brush, points) {#fill_polygon_by_point_brush_points_177}


```
 fill_polygon_by_point(brush, points) 
```

Rellena el interior de un polígono definido por una matriz de puntos especificados mediante estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) y el modo de relleno [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) .

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Arreglo de [PointF](/imaging/python-net/aspose.imaging/pointf/) estructuras que representan los vértices del polígono a rellenar. |

### Method: fill_polygon_by_point_f(brush, points) {#fill_polygon_by_point_f_brush_points_178}


```
 fill_polygon_by_point_f(brush, points) 
```

Rellena el interior de un polígono definido por una matriz de puntos especificados mediante estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) y el modo de relleno [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) .

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Arreglo de [PointF](/imaging/python-net/aspose.imaging/pointf/) estructuras que representan los vértices del polígono a rellenar. |

### Method: fill_polygon_by_point_f_fill_mode(brush, points, fill_mode) {#fill_polygon_by_point_f_fill_mode_brush_points_fill_mode_179}


```
 fill_polygon_by_point_f_fill_mode(brush, points, fill_mode) 
```

Rellena el interior de un polígono definido por una matriz de puntos especificados mediante estructuras [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizando el modo de relleno especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Arreglo de [PointF](/imaging/python-net/aspose.imaging/pointf/) estructuras que representan los vértices del polígono a rellenar. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Miembro de la enumeración [FillMode](/imaging/python-net/aspose.imaging/fillmode/) que determina el estilo del relleno. |

### Method: fill_polygon_by_point_fill_mode(brush, points, fill_mode) {#fill_polygon_by_point_fill_mode_brush_points_fill_mode_180}


```
 fill_polygon_by_point_fill_mode(brush, points, fill_mode) 
```

Rellena el interior de un polígono definido por una matriz de puntos especificados mediante estructuras [Point](/imaging/python-net/aspose.imaging/point/) utilizando el modo de relleno especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Arreglo de [Point](/imaging/python-net/aspose.imaging/point/) estructuras que representan los vértices del polígono a rellenar. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Miembro de la enumeración [FillMode](/imaging/python-net/aspose.imaging/fillmode/) que determina el estilo del relleno. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_181}


```
 fill_rectangle(brush, rect) 
```

Rellena el interior de un rectángulo especificado mediante una estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) .

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) estructura que representa el rectángulo a rellenar. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_182}


```
 fill_rectangle(brush, rect) 
```

Rellena el interior de un rectángulo especificado mediante una estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) .

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) estructura que representa el rectángulo a rellenar. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_183}


```
 fill_rectangle(brush, x, y, width, height) 
```

Rellena el interior de un rectángulo especificado mediante un par de coordenadas, un ancho y una altura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo a rellenar. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo a rellenar. |
| width | float | Ancho del rectángulo a rellenar. |
| height | float | Altura del rectángulo a rellenar. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_184}


```
 fill_rectangle(brush, x, y, width, height) 
```

Rellena el interior de un rectángulo especificado mediante un par de coordenadas, un ancho y una altura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo a rellenar. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo a rellenar. |
| width | int | Ancho del rectángulo a rellenar. |
| height | int | Altura del rectángulo a rellenar. |

### Method: fill_rectangle_f(brush, rect) {#fill_rectangle_f_brush_rect_185}


```
 fill_rectangle_f(brush, rect) 
```

Rellena el interior de un rectángulo especificado mediante una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) .

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) estructura que representa el rectángulo a rellenar. |

### Method: fill_rectangle_f_with_brush(brush, x, y, width, height) {#fill_rectangle_f_with_brush_brush_x_y_width_height_186}


```
 fill_rectangle_f_with_brush(brush, x, y, width, height) 
```

Rellena el interior de un rectángulo especificado mediante un par de coordenadas, un ancho y una altura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo a rellenar. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo a rellenar. |
| width | float | Ancho del rectángulo a rellenar. |
| height | float | Altura del rectángulo a rellenar. |

### Method: fill_rectangle_with_brush(brush, x, y, width, height) {#fill_rectangle_with_brush_brush_x_y_width_height_187}


```
 fill_rectangle_with_brush(brush, x, y, width, height) 
```

Rellena el interior de un rectángulo especificado mediante un par de coordenadas, un ancho y una altura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo a rellenar. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo a rellenar. |
| width | int | Ancho del rectángulo a rellenar. |
| height | int | Altura del rectángulo a rellenar. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_188}


```
 fill_rectangles(brush, rects) 
```

Rellena los interiores de una serie de rectángulos especificados mediante estructuras [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) .

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| rects | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | Arreglo de [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) estructuras que representan los rectángulos a rellenar. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_189}


```
 fill_rectangles(brush, rects) 
```

Rellena los interiores de una serie de rectángulos especificados mediante estructuras [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) .

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Arreglo de [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) estructuras que representan los rectángulos a rellenar. |

### Method: fill_rectangles_f(brush, rects) {#fill_rectangles_f_brush_rects_190}


```
 fill_rectangles_f(brush, rects) 
```

Rellena los interiores de una serie de rectángulos especificados mediante estructuras [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) .

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Arreglo de [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) estructuras que representan los rectángulos a rellenar. |

### Method: fill_region(brush, region) {#fill_region_brush_region_191}


```
 fill_region(brush, region) 
```

Rellena el interior de una [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) que determina las características del relleno. |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | [Region](/imaging/python-net/aspose.imaging/region/) que representa el área a rellenar. |

### Method: measure_string(text, font, layout_area, string_format) {#measure_string_text_font_layout_area_string_format_192}


```
 measure_string(text, font, layout_area, string_format) 
```

Mide la cadena de texto especificada con los parámetros especificados

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| text | string | El texto a medir. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | La fuente a medir. |
| layout_area | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | El área de diseño. |
| string_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | El formato de cadena. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Tamaño en píxeles de la cadena de texto medida |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_193}


```
 multiply_transform(matrix) 
```

Multiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) que representa la transformación geométrica local de este [Graphics](/imaging/python-net/aspose.imaging/graphics/) por la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada, anteponiendo la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) por la cual multiplicar la transformación geométrica. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_194}


```
 multiply_transform(matrix, order) 
```

Multiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) que representa la transformación geométrica local de este [Graphics](/imaging/python-net/aspose.imaging/graphics/) por la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) por la cual multiplicar la transformación geométrica. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) que especifica en qué orden multiplicar las dos matrices. |

### Method: rotate_transform(angle) {#rotate_transform_angle_195}


```
 rotate_transform(angle) 
```

Rota la transformación geométrica local en la cantidad especificada. Este método antepone la rotación a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| angle | float | El ángulo de rotación. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_196}


```
 rotate_transform(angle, order) 
```

Rota la transformación geométrica local en la cantidad especificada en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| angle | float | El ángulo de rotación. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) que especifica si se debe añadir al final o al principio la matriz de rotación. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_197}


```
 scale_transform(sx, sy) 
```

Escala la transformación geométrica local por las cantidades especificadas. Este método antepone la matriz de escala a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| sx | float | La cantidad por la cual escalar la transformación en la dirección del eje x. |
| sy | float | La cantidad por la cual escalar la transformación en la dirección del eje y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_198}


```
 scale_transform(sx, sy, order) 
```

Escala la transformación geométrica local por las cantidades especificadas en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| sx | float | La cantidad por la cual escalar la transformación en la dirección del eje x. |
| sy | float | La cantidad por la cual escalar la transformación en la dirección del eje y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) que especifica si se debe agregar o anteponer la matriz de escala. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_199}


```
 translate_transform(dx, dy) 
```

Traslada la transformación geométrica local por las dimensiones especificadas. Este método antepone la traslación a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traslación en y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_200}


```
 translate_transform(dx, dy, order) 
```

Traslada la transformación geométrica local por las dimensiones especificadas en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traslación en y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | El orden (anteponer o agregar) en el que se aplica la traslación. |

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

#Crea una instancia de flujo de archivo
with open(r"C:\temp\output.png", "w+b") as stream:
	#Crea una instancia de PngOptions y establece sus diversas propiedades
	pngOptions = PngOptions()
	#Establece la fuente para PngOptions
	pngOptions.source = StreamSource(stream)
	#Crea una instancia de Image
	with Image.create(pngOptions, 500, 500) as image:
		#Crea e inicializa una instancia de la clase Graphics
		graphics = Graphics(image)
		#Limpia la superficie Graphics
		graphics.clear(Color.wheat);
		#Dibuja un arco especificando el objeto Pen que tiene color negro, 
		#un rectángulo que rodea el arco, ángulo de inicio y ángulo de barrido
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#Dibuja una curva Bézier especificando el objeto Pen que tiene color azul y puntos de coordenadas.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#Dibuje una curva especificando el objeto Pen con color Verde y una matriz de Points
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#Dibuje una elipse usando el objeto Pen y un Rectangle circundante
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#Dibuje una línea
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#Dibuje un segmento de Pie
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#Dibuje un polígono especificando el objeto Pen con color Rojo y una matriz de Points
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#Dibuje un Rectangle
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#Cree un objeto SolidBrush y establezca sus diversas propiedades
		brush = SolidBrush()
		brush.color = Color.purple
		#Dibuje un String usando el objeto SolidBrush y Font, en un Point específico
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# guarde todos los cambios.
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


# Crea una instancia de un flujo de archivo
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# Cree una instancia de TiffOptions y establezca sus diversas propiedades
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Establezca la fuente para la instancia de ImageOptions
	tiffOptions.source = StreamSource(stream)
	# Cree una instancia de Image
	with Image.create(tiffOptions, 500, 500) as image:
		# Crea e inicializa una instancia de la clase Graphics
		graphics = Graphics(image)
		# Limpia la superficie Graphics
		graphics.clear(Color.wheat);
		# Cree una instancia de la clase GraphicsPath
		graphics_path = GraphicsPath()
		# Cree una instancia de la clase Figure
		figure = Figure()
		# Agregue Shapes al objeto Figure
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# Agregue el objeto Figure a GraphicsPath
		graphics_path.add_figure(figure)
		# Dibuje la ruta con el objeto Pen de color Black
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# guarde todos los cambios.
		image.save()


```

### This example shows the creation and usage Pen objects. The example creates a new Image and draw rectangles on the Image surface. {#example_14}
``` python

from aspose.imaging import Image, Graphics, Color, Pen, Rectangle, Point, Size
from aspose.imaging.brushes import HatchBrush
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

# Crea una instancia de BmpOptions y establece sus diversas propiedades
bmpOptions = BmpOptions()
bmpOptions.bits_per_pixel = 24
# Cree una instancia de FileCreateSource y asígnela como Source para la instancia de BmpOptions
# El segundo parámetro Boolean determina si el archivo a crear es IsTemporal o no
bmpOptions.source = FileCreateSource(r"C:\temp\sample.bmp", False)
# Crea una instancia de Image en la ruta especificada
with Image.create(bmpOptions, 500, 500) as image:
	# Crea una instancia de Graphics e inicialízala con un objeto Image
	graphics = Graphics(image)
	# Limpia la superficie de Graphics con color blanco
	graphics.clear(Color.white)
	#Crea una instancia de Pen con color rojo y ancho 5
	pen = Pen(Color.red, 5.0);
	# Crea una instancia de HatchBrush y establece sus propiedades
	brush = HatchBrush()
	brush.background_color = Color.wheat;
	brush.foreground_color = Color.red;
	# Crea una instancia de Pen
	# inicialícelo con el objeto HatchBrush y el ancho
	brusedpen = Pen(brush, 5.0)
	# Dibuje rectángulos especificando el objeto Pen
	graphics.draw_rectangles(pen, [
		Rectangle(Point(210, 210), Size(100, 100)),
		Rectangle(Point(110, 110), Size(100, 100)),
		Rectangle(Point(310, 310), Size(100, 100)) ])

	# Dibuje rectángulos especificando el objeto Pen
	graphics.draw_rectangles(brusedpen, [
		Rectangle(Point(310, 110), Size(100, 100)),
		Rectangle(Point(110, 310), Size(100, 100)) ])

	# guarde todos los cambios.
	image.save()


```

### The following example shows how to compose an animated GIF image from individual GIF blocks. {#example_95}
``` python
from aspose.imaging.fileformats.gif.blocks import GifFrameBlock
from aspose.imaging.fileformats.gif import GifImage 
from aspose.imaging.brushes import SolidBrush
from aspose.imaging import Graphics, Color

# Cree una imagen GIF de 100 x 100 px.
# El primer bloque es completamente negro por defecto.
with GifFrameBlock(100, 100) as firstBlock:
	with GifImage(firstBlock) as gifImage:
		# El primer círculo es rojo
		brush1 = SolidBrush(Color.red)

		# El segundo círculo es negro
		brush2 = SolidBrush(Color.black)

		# Aumente gradualmente el ángulo de la forma de arco rojo.
		for angle in range(10, 361, 10):
			block = GifFrameBlock(100, 100)
			gr = Graphics(block)
			gr.fill_pie(brush1, block.bounds, 0, angle)
			gifImage.add_block(block)
		
		# Aumente gradualmente el ángulo del arco negro y elimine el arco rojo.
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
# Cree una imagen PNG de 100x100 px.
with PngImage(100, 100) as png_image:
	# Realice algo de procesamiento de imágenes, p. ej., rellene toda la imagen de rojo.
	graphics = Graphics(png_image)
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, png_image.bounds)
	# Guarde en un archivo.
	png_image.save(join(dir_, "output.png"))


```

