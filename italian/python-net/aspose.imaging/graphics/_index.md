---
title: "Classe Graphics"
type: docs
weight: 5030
url: /it/python-net/aspose.imaging/graphics/
---

**Summary:** Represents the graphics according to the graphics engine used in the current assembly.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Graphics

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [Graphics(source_image)](#Graphics_source_image_1) | Inizializza una nuova istanza della classe [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| clip | [Region](/imaging/python-net/aspose.imaging/region/) | r/w | Ottiene o imposta la regione di ritaglio. |
| compositing_quality | [CompositingQuality](/imaging/python-net/aspose.imaging/compositingquality/) | r/w | Ottiene o imposta la qualità di composizione. |
| dpi_x | float | r | Ottiene la risoluzione orizzontale di questo `aspose.imaging.Graphics`. |
| dpi_y | float | r | Ottiene la risoluzione verticale di questo `aspose.imaging.Graphics`. |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | r | Ottiene l'immagine. |
| interpolation_mode | [InterpolationMode](/imaging/python-net/aspose.imaging/interpolationmode/) | r/w | Ottiene o imposta la modalità di interpolazione. |
| is_in_begin_update_call | bool | r | Ottiene un valore che indica se la grafica è nello stato di chiamata BeginUpdate. |
| page_scale | float | r/w | Ottiene o imposta la scala tra le unità del mondo e le unità della pagina per questo `aspose.imaging.Graphics`. |
| page_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | r/w | Ottiene o imposta l'unità di misura utilizzata per le coordinate della pagina in questo `aspose.imaging.Graphics`. |
| paintable_image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | r/w | Ottiene o imposta le opzioni immagine, utilizzate per creare immagini vettoriali dipingibili da disegnare. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Ottiene o imposta la modalità di smussatura. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Ottiene o imposta il suggerimento di rendering del testo. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Ottiene o imposta una copia della trasformazione geometrica del mondo per questo [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| begin_update() | Avvia la memorizzazione nella cache delle successive operazioni grafiche. Gli effetti grafici applicati successivamente non verranno applicati immediatamente; invece, l'EndUpdate farà sì che tutti gli effetti vengano applicati in una volta sola. |
| [clear(color)](#clear_color_1) | Cancella la superficie grafica utilizzando il colore specificato. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_2) | Disegna un arco che rappresenta una porzione di un'ellisse specificata da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_3) | Disegna un arco che rappresenta una porzione di un'ellisse specificata da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4) | Disegna un arco che rappresenta una porzione di un'ellisse specificata da una coppia di coordinate, una larghezza e un'altezza. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5) | Disegna un arco che rappresenta una porzione di un'ellisse specificata da una coppia di coordinate, una larghezza e un'altezza. |
| [draw_arc_in_rect(pen, rect, start_angle, sweep_angle)](#draw_arc_in_rect_pen_rect_start_angle_sweep_angle_6) | Disegna un arco che rappresenta una porzione di un'ellisse specificata da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle)](#draw_arc_in_rect_f_pen_rect_start_angle_sweep_angle_7) | Disegna un arco che rappresenta una porzione di un'ellisse specificata da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_xy_pen_x_y_width_height_start_angle_sweep_angle_8) | Disegna un arco che rappresenta una porzione di un'ellisse specificata da una coppia di coordinate, una larghezza e un'altezza. |
| [draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_xyf_pen_x_y_width_height_start_angle_sweep_angle_9) | Disegna un arco che rappresenta una porzione di un'ellisse specificata da una coppia di coordinate, una larghezza e un'altezza. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_10) | Disegna una spline Bézier definita da quattro strutture [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_11) | Disegna una spline Bézier definita da quattro strutture [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4)](#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_12) | Disegna una spline Bézier definita da quattro coppie ordinate di coordinate che rappresentano punti. |
| [draw_bezier_by_points(pen, pt1, pt2, pt3, pt4)](#draw_bezier_by_points_pen_pt1_pt2_pt3_pt4_13) | Disegna una spline Bézier definita da quattro strutture [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4)](#draw_bezier_by_points_f_pen_pt1_pt2_pt3_pt4_14) | Disegna una spline Bézier definita da quattro strutture [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_15) | Disegna una serie di spline Bézier da un array di strutture [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_16) | Disegna una serie di spline Bézier da un array di strutture [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_beziers_by_pt_array(pen, points)](#draw_beziers_by_pt_array_pen_points_17) | Disegna una serie di spline Bézier da un array di strutture [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_beziers_by_pt_array_f(pen, points)](#draw_beziers_by_pt_array_f_pen_points_18) | Disegna una serie di spline Bézier da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_19) | Disegna una spline cardinal chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/). Questo metodo utilizza una tensione predefinita di 0.5 e la modalità di riempimento [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_20) | Disegna una spline cardinal chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/). Questo metodo utilizza una tensione predefinita di 0.5 e la modalità di riempimento [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_21) | Disegna una spline cardinal chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando una tensione specificata. Questo metodo utilizza la modalità di riempimento predefinita [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_22) | Disegna una spline cardinal chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando una tensione specificata. Questo metodo utilizza la modalità di riempimento predefinita [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve_by_points(pen, points)](#draw_closed_curve_by_points_pen_points_23) | Disegna una spline cardinal chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/). Questo metodo utilizza una tensione predefinita di 0.5 e la modalità di riempimento [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve_by_points_f(pen, points)](#draw_closed_curve_by_points_f_pen_points_24) | Disegna una spline cardinal chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/). Questo metodo utilizza una tensione predefinita di 0.5 e la modalità di riempimento [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve_by_points_f_tension(pen, points, tension)](#draw_closed_curve_by_points_f_tension_pen_points_tension_25) | Disegna una spline cardinal chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando una tensione specificata. Questo metodo utilizza la modalità di riempimento predefinita [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_closed_curve_by_points_tension(pen, points, tension)](#draw_closed_curve_by_points_tension_pen_points_tension_26) | Disegna una spline cardinal chiusa definita da un array di strutture [Point](/imaging/python-net/aspose.imaging/point/) utilizzando una tensione specificata. Questo metodo utilizza la modalità di riempimento predefinita [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| [draw_curve(pen, points)](#draw_curve_pen_points_27) | Disegna una spline cardinal attraverso un array specificato di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/). Questo metodo utilizza una tensione predefinita di 0.5. |
| [draw_curve(pen, points)](#draw_curve_pen_points_28) | Disegna una spline cardinal attraverso un array specificato di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/). Questo metodo utilizza una tensione predefinita di 0.5. |
| [draw_curve(pen, points, offset, number_of_segments)](#draw_curve_pen_points_offset_number_of_segments_29) | Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/). Il disegno inizia con uno spostamento dall'inizio dell'array.<br/>            Questo metodo utilizza una tensione predefinita di 0,5. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_30) | Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando una tensione specificata. Il disegno inizia con uno spostamento dall'inizio dell'array. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_31) | Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando una tensione specificata. Il disegno inizia con uno spostamento dall'inizio dell'array. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_32) | Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando una tensione specificata. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_33) | Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando una tensione specificata. |
| [draw_curve_by_point_fs(pen, points)](#draw_curve_by_point_fs_pen_points_34) | Disegna una spline cardinale attraverso un array specificato di strutture [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_curve_by_point_fs_tension(pen, points, tension)](#draw_curve_by_point_fs_tension_pen_points_tension_35) | Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando una tensione specificata. |
| [draw_curve_by_points(pen, points)](#draw_curve_by_points_pen_points_36) | Disegna una spline cardinal attraverso un array specificato di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/). Questo metodo utilizza una tensione predefinita di 0.5. |
| [draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension)](#draw_curve_by_points_f_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_37) | Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando una tensione specificata. Il disegno inizia con uno spostamento dall'inizio dell'array. |
| [draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension)](#draw_curve_by_points_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_38) | Disegna una spline cardinale attraverso un array specificato di strutture [Point](/imaging/python-net/aspose.imaging/point/) utilizzando una tensione specificata. |
| [draw_curve_by_points_tension(pen, points, tension)](#draw_curve_by_points_tension_pen_points_tension_39) | Disegna una spline cardinale attraverso un array specificato di strutture [Point](/imaging/python-net/aspose.imaging/point/) utilizzando una tensione specificata. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_40) | Disegna un'ellisse definita da un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) di delimitazione. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_41) | Disegna un'ellisse definita da un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) di delimitazione. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_42) | Disegna un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, un'altezza e una larghezza. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_43) | Disegna un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, un'altezza e una larghezza. |
| [draw_ellipse_by_xy(pen, x, y, width, height)](#draw_ellipse_by_xy_pen_x_y_width_height_44) | Disegna un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, un'altezza e una larghezza. |
| [draw_ellipse_by_xyf(pen, x, y, width, height)](#draw_ellipse_by_xyf_pen_x_y_width_height_45) | Disegna un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, un'altezza e una larghezza. |
| [draw_ellipse_f(pen, rect)](#draw_ellipse_f_pen_rect_46) | Disegna un'ellisse definita da un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) di delimitazione. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_47) | Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_48) | Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_49) | Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_50) | Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_51) | Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_52) | Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_53) | Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_54) | Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate. |
| [draw_image(source_image, point)](#draw_image_source_image_point_55) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato, usando la sua dimensione fisica originale, nella posizione specificata. |
| [draw_image(source_image, point)](#draw_image_source_image_point_56) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato, usando la sua dimensione fisica originale, nella posizione specificata. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_57) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_58) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_59) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_60) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_61) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_62) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_63) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_64) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_65) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_66) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_67) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato, usando la sua dimensione fisica originale, nella posizione specificata. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_68) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato, usando la sua dimensione fisica originale, nella posizione specificata. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_69) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_70) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image_at_point(source_image, point)](#draw_image_at_point_source_image_point_71) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato, usando la sua dimensione fisica originale, nella posizione specificata. |
| [draw_image_at_point_f(source_image, point)](#draw_image_at_point_f_source_image_point_72) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato, usando la sua dimensione fisica originale, nella posizione specificata. |
| [draw_image_at_xy(source_image, x, y)](#draw_image_at_xy_source_image_x_y_73) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato, usando la sua dimensione fisica originale, nella posizione specificata. |
| [draw_image_at_xyf(source_image, x, y)](#draw_image_at_xyf_source_image_x_y_74) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato, usando la sua dimensione fisica originale, nella posizione specificata. |
| [draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit)](#draw_image_dest_point_f_src_rect_f_with_unit_image_dest_points_src_rect_src_unit_75) | Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate. |
| [draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_dest_point_f_src_rect_f_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_76) | Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate. |
| [draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect)](#draw_image_dest_points_f_src_rect_f_image_dest_points_src_rect_77) | Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate. |
| [draw_image_dest_points_src_rect(image, dest_points, src_rect)](#draw_image_dest_points_src_rect_image_dest_points_src_rect_78) | Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate. |
| [draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit)](#draw_image_dest_points_src_rect_with_unit_image_dest_points_src_rect_src_unit_79) | Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate. |
| [draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_dest_points_src_rect_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_80) | Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate. |
| [draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_dest_rect_f_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_81) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_dest_rect_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_82) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image_in_rect(source_image, x, y, width, height)](#draw_image_in_rect_source_image_x_y_width_height_83) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image_in_rect_f(source_image, x, y, width, height)](#draw_image_in_rect_f_source_image_x_y_width_height_84) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image_in_rectangle(source_image, rect)](#draw_image_in_rectangle_source_image_rect_85) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image_points(image, dest_points)](#draw_image_points_image_dest_points_86) | Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate. |
| [draw_image_points_f(image, dest_points)](#draw_image_points_f_image_dest_points_87) | Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate. |
| [draw_image_rectangle_f(source_image, rect)](#draw_image_rectangle_f_source_image_rect_88) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_src_dest_rects_f_with_unit_source_image_rect_source_rect_destination_graphics_unit_89) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_src_dest_rects_with_unit_source_image_rect_source_rect_destination_graphics_unit_90) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_src_dst_rect_f_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_91) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_src_dst_rects_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_92) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit)](#draw_image_to_rect_f_with_unit_source_image_rect_destination_graphics_unit_93) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit)](#draw_image_to_rect_with_unit_source_image_rect_destination_graphics_unit_94) | Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image_unscaled(source_image, point)](#draw_image_unscaled_source_image_point_95) | Disegna un'immagine specificata usando la sua dimensione fisica originale in una posizione specificata. |
| [draw_image_unscaled(source_image, rect)](#draw_image_unscaled_source_image_rect_96) | Disegna un'immagine specificata usando la sua dimensione fisica originale in una posizione specificata. |
| [draw_image_unscaled(source_image, x, y)](#draw_image_unscaled_source_image_x_y_97) | Disegna l'immagine specificata usando la sua dimensione fisica originale nella posizione specificata da una coppia di coordinate. |
| [draw_image_unscaled(source_image, x, y, width, height)](#draw_image_unscaled_source_image_x_y_width_height_98) | Disegna un'immagine specificata usando la sua dimensione fisica originale in una posizione specificata. |
| [draw_image_unscaled_and_clipped(source_image, rect)](#draw_image_unscaled_and_clipped_source_image_rect_99) | Disegna l'immagine specificata senza ridimensionamento e la ritaglia, se necessario, per adattarla al rettangolo specificato. |
| [draw_image_unscaled_in_rectangle(source_image, rect)](#draw_image_unscaled_in_rectangle_source_image_rect_100) | Disegna un'immagine specificata usando la sua dimensione fisica originale in una posizione specificata. |
| [draw_image_unscaled_to_point(source_image, point)](#draw_image_unscaled_to_point_source_image_point_101) | Disegna un'immagine specificata usando la sua dimensione fisica originale in una posizione specificata. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_102) | Disegna una linea che collega due strutture [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_103) | Disegna una linea che collega due strutture [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_104) | Disegna una linea che collega i due punti specificati dalle coppie di coordinate. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_105) | Disegna una linea che collega i due punti specificati dalle coppie di coordinate. |
| [draw_line_by_xy(pen, x1, y1, x2, y2)](#draw_line_by_xy_pen_x1_y1_x2_y2_106) | Disegna una linea che collega i due punti specificati dalle coppie di coordinate. |
| [draw_line_f_by_xy(pen, x1, y1, x2, y2)](#draw_line_f_by_xy_pen_x1_y1_x2_y2_107) | Disegna una linea che collega i due punti specificati dalle coppie di coordinate. |
| [draw_line_point_f(pen, point1, point2)](#draw_line_point_f_pen_point1_point2_108) | Disegna una linea che collega due strutture [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_lines(pen, points)](#draw_lines_pen_points_109) | Disegna una serie di segmenti di linea che collegano un array di strutture [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_lines(pen, points)](#draw_lines_pen_points_110) | Disegna una serie di segmenti di linea che collegano un array di strutture [Point](/imaging/python-net/aspose.imaging/point/). |
| [draw_lines_f(pen, points)](#draw_lines_f_pen_points_111) | Disegna una serie di segmenti di linea che collegano un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_path(pen, path)](#draw_path_pen_path_112) | Disegna un [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_113) | Disegna una forma a torta definita da un'ellisse specificata da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) e due linee radiali. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_114) | Disegna una forma a torta definita da un'ellisse specificata da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) e due linee radiali. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_115) | Disegna una forma a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_116) | Disegna una forma a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali. |
| [draw_pie_in_rect(pen, rect, start_angle, sweep_angle)](#draw_pie_in_rect_pen_rect_start_angle_sweep_angle_117) | Disegna una forma a torta definita da un'ellisse specificata da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) e due linee radiali. |
| [draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle)](#draw_pie_in_rect_f_pen_rect_start_angle_sweep_angle_118) | Disegna una forma a torta definita da un'ellisse specificata da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) e due linee radiali. |
| [draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_xy_pen_x_y_width_height_start_angle_sweep_angle_119) | Disegna una forma a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali. |
| [draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_xyf_pen_x_y_width_height_start_angle_sweep_angle_120) | Disegna una forma a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_121) | Disegna un poligono definito da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_122) | Disegna un poligono definito da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_polygon_f(pen, points)](#draw_polygon_f_pen_points_123) | Disegna un poligono definito da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [draw_rect(pen, x, y, width, height)](#draw_rect_pen_x_y_width_height_124) | Disegna un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [draw_rect_f(pen, x, y, width, height)](#draw_rect_f_pen_x_y_width_height_125) | Disegna un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_126) | Disegna un rettangolo specificato da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_127) | Disegna un rettangolo specificato da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_128) | Disegna un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_129) | Disegna un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [draw_rectangle_f(pen, rect)](#draw_rectangle_f_pen_rect_130) | Disegna un rettangolo specificato da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_131) | Disegna una serie di rettangoli specificati da strutture [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_132) | Disegna una serie di rettangoli specificati da strutture [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_rectangles_f(pen, rects)](#draw_rectangles_f_pen_rects_133) | Disegna una serie di rettangoli specificati da strutture [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [draw_string(s, font, brush, layout_rectangle)](#draw_string_s_font_brush_layout_rectangle_134) | Disegna la stringa di testo specificata nel rettangolo specificato con gli oggetti [Brush](/imaging/python-net/aspose.imaging/brush/) e [Font](/imaging/python-net/aspose.imaging/font/) specificati. |
| [draw_string(s, font, brush, layout_rectangle, format)](#draw_string_s_font_brush_layout_rectangle_format_135) | Disegna la stringa di testo specificata nel rettangolo specificato con gli oggetti [Brush](/imaging/python-net/aspose.imaging/brush/) e [Font](/imaging/python-net/aspose.imaging/font/) specificati, utilizzando gli attributi di formattazione del [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) specificato. |
| [draw_string(s, font, brush, point)](#draw_string_s_font_brush_point_136) | Disegna la stringa di testo specificata nella posizione specificata con gli oggetti [Brush](/imaging/python-net/aspose.imaging/brush/) e [Font](/imaging/python-net/aspose.imaging/font/) specificati. |
| [draw_string(s, font, brush, point, format)](#draw_string_s_font_brush_point_format_137) | Disegna la stringa di testo specificata nella posizione specificata con gli oggetti [Brush](/imaging/python-net/aspose.imaging/brush/) e [Font](/imaging/python-net/aspose.imaging/font/) specificati, utilizzando gli attributi di formattazione del [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) specificato. |
| [draw_string(s, font, brush, x, y)](#draw_string_s_font_brush_x_y_138) | Disegna la stringa di testo specificata nella posizione specificata con gli oggetti [Brush](/imaging/python-net/aspose.imaging/brush/) e [Font](/imaging/python-net/aspose.imaging/font/) specificati. |
| [draw_string(s, font, brush, x, y, format)](#draw_string_s_font_brush_x_y_format_139) | Disegna la stringa di testo specificata nella posizione specificata con gli oggetti [Brush](/imaging/python-net/aspose.imaging/brush/) e [Font](/imaging/python-net/aspose.imaging/font/) specificati, utilizzando gli attributi di formattazione del [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) specificato. |
| [draw_string_at_point_f(s, font, brush, point)](#draw_string_at_point_f_s_font_brush_point_140) | Disegna la stringa di testo specificata nella posizione specificata con gli oggetti [Brush](/imaging/python-net/aspose.imaging/brush/) e [Font](/imaging/python-net/aspose.imaging/font/) specificati. |
| [draw_string_at_point_f_format(s, font, brush, point, format)](#draw_string_at_point_f_format_s_font_brush_point_format_141) | Disegna la stringa di testo specificata nella posizione specificata con gli oggetti [Brush](/imaging/python-net/aspose.imaging/brush/) e [Font](/imaging/python-net/aspose.imaging/font/) specificati, utilizzando gli attributi di formattazione del [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) specificato. |
| [draw_string_at_xy(s, font, brush, x, y)](#draw_string_at_xy_s_font_brush_x_y_142) | Disegna la stringa di testo specificata nella posizione specificata con gli oggetti [Brush](/imaging/python-net/aspose.imaging/brush/) e [Font](/imaging/python-net/aspose.imaging/font/) specificati. |
| [draw_string_in_rect(s, font, brush, layout_rectangle)](#draw_string_in_rect_s_font_brush_layout_rectangle_143) | Disegna la stringa di testo specificata nel rettangolo specificato con gli oggetti [Brush](/imaging/python-net/aspose.imaging/brush/) e [Font](/imaging/python-net/aspose.imaging/font/) specificati. |
| [draw_string_in_rect_f(s, font, brush, layout_rectangle, format)](#draw_string_in_rect_f_s_font_brush_layout_rectangle_format_144) | Disegna la stringa di testo specificata nel rettangolo specificato con gli oggetti [Brush](/imaging/python-net/aspose.imaging/brush/) e [Font](/imaging/python-net/aspose.imaging/font/) specificati, utilizzando gli attributi di formattazione del [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) specificato. |
| end_update() | Termina la memorizzazione nella cache delle operazioni grafiche avviate dopo la chiamata a BeginUpdate. Le operazioni grafiche precedenti verranno applicate immediatamente quando si chiama questo metodo. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_145) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) . Questo metodo utilizza una tensione predefinita di 0,5 e la modalità di riempimento [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) . |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_146) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) . Questo metodo utilizza una tensione predefinita di 0,5 e la modalità di riempimento [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) . |
| [fill_closed_curve(brush, points, fill_mode)](#fill_closed_curve_brush_points_fill_mode_147) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando la modalità di riempimento specificata. Questo metodo utilizza una tensione predefinita di 0,5. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_148) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando la modalità di riempimento specificata. Questo metodo utilizza una tensione predefinita di 0,5. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_149) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando la modalità di riempimento e la tensione specificate. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_150) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando la modalità di riempimento e la tensione specificate. |
| [fill_closed_curve_by_point(brush, points)](#fill_closed_curve_by_point_brush_points_151) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) . Questo metodo utilizza una tensione predefinita di 0,5 e la modalità di riempimento [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) . |
| [fill_closed_curve_by_point_f(brush, points)](#fill_closed_curve_by_point_f_brush_points_152) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) . Questo metodo utilizza una tensione predefinita di 0,5 e la modalità di riempimento [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) . |
| fill_closed_curve_by_point_f_fill_mode(brush, points, fillmode) |  |
| [fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension)](#fill_closed_curve_by_point_f_fill_mode_tension_brush_points_fillmode_tension_153) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando la modalità di riempimento e la tensione specificate. |
| [fill_closed_curve_by_point_fill_mode(brush, points, fillmode)](#fill_closed_curve_by_point_fill_mode_brush_points_fillmode_154) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [Point](/imaging/python-net/aspose.imaging/point/) utilizzando la modalità di riempimento specificata. Questo metodo utilizza una tensione predefinita di 0,5. |
| [fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension)](#fill_closed_curve_by_point_fill_mode_tension_brush_points_fillmode_tension_155) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [Point](/imaging/python-net/aspose.imaging/point/) utilizzando la modalità di riempimento e la tensione specificate. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_156) | Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) . |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_157) | Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) . |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_158) | Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_159) | Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [fill_ellipse_at_xywh(brush, x, y, width, height)](#fill_ellipse_at_xywh_brush_x_y_width_height_160) | Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [fill_ellipse_at_xywhf(brush, x, y, width, height)](#fill_ellipse_at_xywhf_brush_x_y_width_height_161) | Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [fill_ellipse_in_rect(brush, rect)](#fill_ellipse_in_rect_brush_rect_162) | Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) . |
| [fill_ellipse_in_rect_f(brush, rect)](#fill_ellipse_in_rect_f_brush_rect_163) | Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) . |
| [fill_path(brush, path)](#fill_path_brush_path_164) | Riempie l'interno di un [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) . |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_165) | Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) e due linee radiali. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_166) | Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) e due linee radiali. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_167) | Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_168) | Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali. |
| [fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_at_xy_brush_x_y_width_height_start_angle_sweep_angle_169) | Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali. |
| [fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_at_xyf_brush_x_y_width_height_start_angle_sweep_angle_170) | Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali. |
| [fill_pie_in_rect(brush, rect, start_angle, sweep_angle)](#fill_pie_in_rect_brush_rect_start_angle_sweep_angle_171) | Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) e due linee radiali. |
| [fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle)](#fill_pie_in_rect_f_brush_rect_start_angle_sweep_angle_172) | Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) e due linee radiali. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_173) | Riempie l'interno di un poligono definito da un array di punti specificati da strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) e dalla modalità di riempimento [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) . |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_174) | Riempie l'interno di un poligono definito da un array di punti specificati da strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) e dalla modalità di riempimento [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) . |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_175) | Riempie l'interno di un poligono definito da un array di punti specificati da strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando la modalità di riempimento specificata. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_176) | Riempie l'interno di un poligono definito da un array di punti specificati da strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando la modalità di riempimento specificata. |
| [fill_polygon_by_point(brush, points)](#fill_polygon_by_point_brush_points_177) | Riempie l'interno di un poligono definito da un array di punti specificati da strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) e dalla modalità di riempimento [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) . |
| [fill_polygon_by_point_f(brush, points)](#fill_polygon_by_point_f_brush_points_178) | Riempie l'interno di un poligono definito da un array di punti specificati da strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) e dalla modalità di riempimento [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) . |
| [fill_polygon_by_point_f_fill_mode(brush, points, fill_mode)](#fill_polygon_by_point_f_fill_mode_brush_points_fill_mode_179) | Riempie l'interno di un poligono definito da un array di punti specificati da strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando la modalità di riempimento specificata. |
| [fill_polygon_by_point_fill_mode(brush, points, fill_mode)](#fill_polygon_by_point_fill_mode_brush_points_fill_mode_180) | Riempie l'interno di un poligono definito da un array di punti specificati da strutture [Point](/imaging/python-net/aspose.imaging/point/) utilizzando la modalità di riempimento specificata. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_181) | Riempie l'interno di un rettangolo specificato da una struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) . |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_182) | Riempie l'interno di un rettangolo specificato da una struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) . |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_183) | Riempie l'interno di un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_184) | Riempie l'interno di un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [fill_rectangle_f(brush, rect)](#fill_rectangle_f_brush_rect_185) | Riempie l'interno di un rettangolo specificato da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) . |
| [fill_rectangle_f_with_brush(brush, x, y, width, height)](#fill_rectangle_f_with_brush_brush_x_y_width_height_186) | Riempie l'interno di un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [fill_rectangle_with_brush(brush, x, y, width, height)](#fill_rectangle_with_brush_brush_x_y_width_height_187) | Riempie l'interno di un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_188) | Riempie gli interni di una serie di rettangoli specificati da strutture [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) . |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_189) | Riempie gli interni di una serie di rettangoli specificati da strutture [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) . |
| [fill_rectangles_f(brush, rects)](#fill_rectangles_f_brush_rects_190) | Riempie gli interni di una serie di rettangoli specificati da strutture [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) . |
| [fill_region(brush, region)](#fill_region_brush_region_191) | Riempie l'interno di una [Region](/imaging/python-net/aspose.imaging/region/). |
| [measure_string(text, font, layout_area, string_format)](#measure_string_text_font_layout_area_string_format_192) | Misura la stringa di testo specificata con i parametri specificati |
| [multiply_transform(matrix)](#multiply_transform_matrix_193) | Moltiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) che rappresenta la trasformazione geometrica locale di questo [Graphics](/imaging/python-net/aspose.imaging/graphics/) per la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata, pre-pendendo la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_194) | Moltiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) che rappresenta la trasformazione geometrica locale di questo [Graphics](/imaging/python-net/aspose.imaging/graphics/) per la [Matrix](/imaging/python-net/aspose.imaging/matrix/) nell'ordine specificato. |
| reset_transform() | Reimposta la proprietà [Graphics.transform](/imaging/python-net/aspose.imaging/graphics/) a identità. |
| [rotate_transform(angle)](#rotate_transform_angle_195) | Ruota la trasformazione geometrica locale della quantità specificata. Questo metodo prepone la rotazione alla trasformazione. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_196) | Ruota la trasformazione geometrica locale della quantità specificata nell'ordine specificato. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_197) | Scala la trasformazione geometrica locale delle quantità specificate. Questo metodo prepone la matrice di scala alla trasformazione. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_198) | Scala la trasformazione geometrica locale delle quantità specificate nell'ordine specificato. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_199) | Trasla la trasformazione geometrica locale delle dimensioni specificate. Questo metodo prepone la traslazione alla trasformazione. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_200) | Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato. |


### Constructor: Graphics(source_image) {#Graphics_source_image_1}


```
 Graphics(source_image) 
```

Inizializza una nuova istanza della classe [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine di origine. |

### Method: clear(color) {#clear_color_1}


```
 clear(color) 
```

Cancella la superficie grafica utilizzando il colore specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Il colore con cui cancellare la superficie grafica. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...

**[Example # 2](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_2}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Disegna un arco che rappresenta una porzione di un'ellisse specificata da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile dell'arco. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struttura che definisce i confini dell'ellisse. |
| start_angle | float | Angolo in gradi misurato in senso orario dall'asse x al punto di partenza dell'arco. |
| sweep_angle | float | Angolo in gradi misurato in senso orario dal parametro _startAngle_ al punto finale dell'arco. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_3}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Disegna un arco che rappresenta una porzione di un'ellisse specificata da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile dell'arco. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struttura che definisce i confini dell'ellisse. |
| start_angle | float | Angolo in gradi misurato in senso orario dall'asse x al punto di partenza dell'arco. |
| sweep_angle | float | Angolo in gradi misurato in senso orario dal parametro _startAngle_ al punto finale dell'arco. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Disegna un arco che rappresenta una porzione di un'ellisse specificata da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile dell'arco. |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo che definisce l'ellisse. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo che definisce l'ellisse. |
| width | float | Larghezza del rettangolo che definisce l'ellisse. |
| height | float | Altezza del rettangolo che definisce l'ellisse. |
| start_angle | float | Angolo in gradi misurato in senso orario dall'asse x al punto di partenza dell'arco. |
| sweep_angle | float | Angolo in gradi misurato in senso orario dal parametro _startAngle_ al punto finale dell'arco. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Disegna un arco che rappresenta una porzione di un'ellisse specificata da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile dell'arco. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo che definisce l'ellisse. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo che definisce l'ellisse. |
| width | int | Larghezza del rettangolo che definisce l'ellisse. |
| height | int | Altezza del rettangolo che definisce l'ellisse. |
| start_angle | int | Angolo in gradi misurato in senso orario dall'asse x al punto di partenza dell'arco. |
| sweep_angle | int | Angolo in gradi misurato in senso orario dal parametro _startAngle_ al punto finale dell'arco. |

### Method: draw_arc_in_rect(pen, rect, start_angle, sweep_angle) {#draw_arc_in_rect_pen_rect_start_angle_sweep_angle_6}


```
 draw_arc_in_rect(pen, rect, start_angle, sweep_angle) 
```

Disegna un arco che rappresenta una porzione di un'ellisse specificata da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile dell'arco. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struttura che definisce i confini dell'ellisse. |
| start_angle | float | Angolo in gradi misurato in senso orario dall'asse x al punto di partenza dell'arco. |
| sweep_angle | float | Angolo in gradi misurato in senso orario dal parametro _startAngle_ al punto finale dell'arco. |

### Method: draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle) {#draw_arc_in_rect_f_pen_rect_start_angle_sweep_angle_7}


```
 draw_arc_in_rect_f(pen, rect, start_angle, sweep_angle) 
```

Disegna un arco che rappresenta una porzione di un'ellisse specificata da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile dell'arco. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struttura che definisce i confini dell'ellisse. |
| start_angle | float | Angolo in gradi misurato in senso orario dall'asse x al punto di partenza dell'arco. |
| sweep_angle | float | Angolo in gradi misurato in senso orario dal parametro _startAngle_ al punto finale dell'arco. |

### Method: draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_xy_pen_x_y_width_height_start_angle_sweep_angle_8}


```
 draw_arc_xy(pen, x, y, width, height, start_angle, sweep_angle) 
```

Disegna un arco che rappresenta una porzione di un'ellisse specificata da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile dell'arco. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo che definisce l'ellisse. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo che definisce l'ellisse. |
| width | int | Larghezza del rettangolo che definisce l'ellisse. |
| height | int | Altezza del rettangolo che definisce l'ellisse. |
| start_angle | int | Angolo in gradi misurato in senso orario dall'asse x al punto di partenza dell'arco. |
| sweep_angle | int | Angolo in gradi misurato in senso orario dal parametro _startAngle_ al punto finale dell'arco. |

### Method: draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_xyf_pen_x_y_width_height_start_angle_sweep_angle_9}


```
 draw_arc_xyf(pen, x, y, width, height, start_angle, sweep_angle) 
```

Disegna un arco che rappresenta una porzione di un'ellisse specificata da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile dell'arco. |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo che definisce l'ellisse. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo che definisce l'ellisse. |
| width | float | Larghezza del rettangolo che definisce l'ellisse. |
| height | float | Altezza del rettangolo che definisce l'ellisse. |
| start_angle | float | Angolo in gradi misurato in senso orario dall'asse x al punto di partenza dell'arco. |
| sweep_angle | float | Angolo in gradi misurato in senso orario dal parametro _startAngle_ al punto finale dell'arco. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_10}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Disegna una spline Bézier definita da quattro strutture [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile della curva. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struttura che rappresenta il punto di partenza della curva. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struttura che rappresenta il primo punto di controllo per la curva. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struttura che rappresenta il secondo punto di controllo per la curva. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struttura che rappresenta il punto finale della curva. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_11}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Disegna una spline Bézier definita da quattro strutture [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile della curva. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struttura che rappresenta il punto di partenza della curva. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struttura che rappresenta il primo punto di controllo per la curva. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struttura che rappresenta il secondo punto di controllo per la curva. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struttura che rappresenta il punto finale della curva. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) {#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_12}


```
 draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) 
```

Disegna una spline Bézier definita da quattro coppie ordinate di coordinate che rappresentano punti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile della curva. |
| x1 | float | La coordinata x del punto di partenza della curva. |
| y1 | float | La coordinata y del punto di partenza della curva. |
| x2 | float | La coordinata x del primo punto di controllo della curva. |
| y2 | float | La coordinata y del primo punto di controllo della curva. |
| x3 | float | La coordinata x del secondo punto di controllo della curva. |
| y3 | float | La coordinata y del secondo punto di controllo della curva. |
| x4 | float | La coordinata x del punto finale della curva. |
| y4 | float | La coordinata y del punto finale della curva. |

### Method: draw_bezier_by_points(pen, pt1, pt2, pt3, pt4) {#draw_bezier_by_points_pen_pt1_pt2_pt3_pt4_13}


```
 draw_bezier_by_points(pen, pt1, pt2, pt3, pt4) 
```

Disegna una spline Bézier definita da quattro strutture [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile della curva. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struttura che rappresenta il punto di partenza della curva. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struttura che rappresenta il primo punto di controllo per la curva. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struttura che rappresenta il secondo punto di controllo per la curva. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struttura che rappresenta il punto finale della curva. |

### Method: draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4) {#draw_bezier_by_points_f_pen_pt1_pt2_pt3_pt4_14}


```
 draw_bezier_by_points_f(pen, pt1, pt2, pt3, pt4) 
```

Disegna una spline Bézier definita da quattro strutture [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile della curva. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struttura che rappresenta il punto di partenza della curva. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struttura che rappresenta il primo punto di controllo per la curva. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struttura che rappresenta il secondo punto di controllo per la curva. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struttura che rappresenta il punto finale della curva. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_15}


```
 draw_beziers(pen, points) 
```

Disegna una serie di spline Bézier da un array di strutture [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile della curva. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di strutture [Point](/imaging/python-net/aspose.imaging/point/) che rappresentano i punti che determinano la curva. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_16}


```
 draw_beziers(pen, points) 
```

Disegna una serie di spline Bézier da un array di strutture [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile della curva. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di strutture [Point](/imaging/python-net/aspose.imaging/point/) che rappresentano i punti che determinano la curva. |

### Method: draw_beziers_by_pt_array(pen, points) {#draw_beziers_by_pt_array_pen_points_17}


```
 draw_beziers_by_pt_array(pen, points) 
```

Disegna una serie di spline Bézier da un array di strutture [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile della curva. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di strutture [Point](/imaging/python-net/aspose.imaging/point/) che rappresentano i punti che determinano la curva. |

### Method: draw_beziers_by_pt_array_f(pen, points) {#draw_beziers_by_pt_array_f_pen_points_18}


```
 draw_beziers_by_pt_array_f(pen, points) 
```

Disegna una serie di spline Bézier da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile della curva. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che rappresentano i punti che determinano la curva. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_19}


```
 draw_closed_curve(pen, points) 
```

Disegna una spline cardinal chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/). Questo metodo utilizza una tensione predefinita di 0.5 e la modalità di riempimento [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che definiscono la spline. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_20}


```
 draw_closed_curve(pen, points) 
```

Disegna una spline cardinal chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/). Questo metodo utilizza una tensione predefinita di 0.5 e la modalità di riempimento [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che definiscono la spline. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_21}


```
 draw_closed_curve(pen, points, tension) 
```

Disegna una spline cardinal chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando una tensione specificata. Questo metodo utilizza la modalità di riempimento predefinita [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che definiscono la spline. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_22}


```
 draw_closed_curve(pen, points, tension) 
```

Disegna una spline cardinal chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando una tensione specificata. Questo metodo utilizza la modalità di riempimento predefinita [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che definiscono la spline. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Method: draw_closed_curve_by_points(pen, points) {#draw_closed_curve_by_points_pen_points_23}


```
 draw_closed_curve_by_points(pen, points) 
```

Disegna una spline cardinal chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/). Questo metodo utilizza una tensione predefinita di 0.5 e la modalità di riempimento [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che definiscono la spline. |

### Method: draw_closed_curve_by_points_f(pen, points) {#draw_closed_curve_by_points_f_pen_points_24}


```
 draw_closed_curve_by_points_f(pen, points) 
```

Disegna una spline cardinal chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/). Questo metodo utilizza una tensione predefinita di 0.5 e la modalità di riempimento [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che definiscono la spline. |

### Method: draw_closed_curve_by_points_f_tension(pen, points, tension) {#draw_closed_curve_by_points_f_tension_pen_points_tension_25}


```
 draw_closed_curve_by_points_f_tension(pen, points, tension) 
```

Disegna una spline cardinal chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando una tensione specificata. Questo metodo utilizza la modalità di riempimento predefinita [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che definiscono la spline. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Method: draw_closed_curve_by_points_tension(pen, points, tension) {#draw_closed_curve_by_points_tension_pen_points_tension_26}


```
 draw_closed_curve_by_points_tension(pen, points, tension) 
```

Disegna una spline cardinal chiusa definita da un array di strutture [Point](/imaging/python-net/aspose.imaging/point/) utilizzando una tensione specificata. Questo metodo utilizza la modalità di riempimento predefinita [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di strutture [Point](/imaging/python-net/aspose.imaging/point/) che definiscono la spline. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_27}


```
 draw_curve(pen, points) 
```

Disegna una spline cardinal attraverso un array specificato di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/). Questo metodo utilizza una tensione predefinita di 0.5.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che definiscono la spline. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_curve(pen, points) {#draw_curve_pen_points_28}


```
 draw_curve(pen, points) 
```

Disegna una spline cardinal attraverso un array specificato di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/). Questo metodo utilizza una tensione predefinita di 0.5.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che definiscono la spline. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_curve(pen, points, offset, number_of_segments) {#draw_curve_pen_points_offset_number_of_segments_29}


```
 draw_curve(pen, points, offset, number_of_segments) 
```

Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/). Il disegno inizia con uno spostamento dall'inizio dell'array.<br/>            Questo metodo utilizza una tensione predefinita di 0,5.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che definiscono la spline. |
| offset | int | Offset dal primo elemento nell'array del parametro _points_ al punto di partenza della curva. |
| number_of_segments | int | Numero di segmenti dopo il punto di partenza da includere nella curva. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_30}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando una tensione specificata. Il disegno inizia con uno spostamento dall'inizio dell'array.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che definiscono la spline. |
| offset | int | Offset dal primo elemento nell'array del parametro _points_ al punto di partenza della curva. |
| number_of_segments | int | Numero di segmenti dopo il punto di partenza da includere nella curva. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_31}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando una tensione specificata. Il disegno inizia con uno spostamento dall'inizio dell'array.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che definiscono la spline. |
| offset | int | Offset dal primo elemento nell'array del parametro _points_ al punto di partenza della curva. |
| number_of_segments | int | Numero di segmenti dopo il punto di partenza da includere nella curva. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_32}


```
 draw_curve(pen, points, tension) 
```

Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando una tensione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che rappresentano i punti che definiscono la curva. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_33}


```
 draw_curve(pen, points, tension) 
```

Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando una tensione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che rappresentano i punti che definiscono la curva. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Method: draw_curve_by_point_fs(pen, points) {#draw_curve_by_point_fs_pen_points_34}


```
 draw_curve_by_point_fs(pen, points) 
```

Disegna una spline cardinale attraverso un array specificato di strutture [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di strutture [Point](/imaging/python-net/aspose.imaging/point/) che definiscono la spline. |

### Method: draw_curve_by_point_fs_tension(pen, points, tension) {#draw_curve_by_point_fs_tension_pen_points_tension_35}


```
 draw_curve_by_point_fs_tension(pen, points, tension) 
```

Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando una tensione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che rappresentano i punti che definiscono la curva. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Method: draw_curve_by_points(pen, points) {#draw_curve_by_points_pen_points_36}


```
 draw_curve_by_points(pen, points) 
```

Disegna una spline cardinal attraverso un array specificato di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/). Questo metodo utilizza una tensione predefinita di 0.5.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che definiscono la spline. |

### Method: draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) {#draw_curve_by_points_f_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_37}


```
 draw_curve_by_points_f_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) 
```

Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando una tensione specificata. Il disegno inizia con uno spostamento dall'inizio dell'array.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che definiscono la spline. |
| offset | int | Offset dal primo elemento nell'array del parametro _points_ al punto di partenza della curva. |
| number_of_segments | int | Numero di segmenti dopo il punto di partenza da includere nella curva. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Method: draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) {#draw_curve_by_points_offs_num_segm_tension_pen_points_offset_number_of_segments_tension_38}


```
 draw_curve_by_points_offs_num_segm_tension(pen, points, offset, number_of_segments, tension) 
```

Disegna una spline cardinale attraverso un array specificato di strutture [Point](/imaging/python-net/aspose.imaging/point/) utilizzando una tensione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di strutture [Point](/imaging/python-net/aspose.imaging/point/) che definiscono la spline. |
| offset | int | Offset dal primo elemento nell'array del parametro _points_ al punto di partenza della curva. |
| number_of_segments | int | Numero di segmenti dopo il punto di partenza da includere nella curva. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Method: draw_curve_by_points_tension(pen, points, tension) {#draw_curve_by_points_tension_pen_points_tension_39}


```
 draw_curve_by_points_tension(pen, points, tension) 
```

Disegna una spline cardinale attraverso un array specificato di strutture [Point](/imaging/python-net/aspose.imaging/point/) utilizzando una tensione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di strutture [Point](/imaging/python-net/aspose.imaging/point/) che definiscono la spline. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_40}


```
 draw_ellipse(pen, rect) 
```

Disegna un'ellisse definita da un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) di delimitazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile dell'ellisse. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struttura che definisce i confini dell'ellisse. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_41}


```
 draw_ellipse(pen, rect) 
```

Disegna un'ellisse definita da un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) di delimitazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile dell'ellisse. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struttura che definisce i confini dell'ellisse. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_42}


```
 draw_ellipse(pen, x, y, width, height) 
```

Disegna un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, un'altezza e una larghezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile dell'ellisse. |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| width | float | Larghezza del rettangolo di delimitazione che definisce l'ellisse. |
| height | float | Altezza del rettangolo di delimitazione che definisce l'ellisse. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_43}


```
 draw_ellipse(pen, x, y, width, height) 
```

Disegna un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, un'altezza e una larghezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile dell'ellisse. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| width | int | Larghezza del rettangolo di delimitazione che definisce l'ellisse. |
| height | int | Altezza del rettangolo di delimitazione che definisce l'ellisse. |

### Method: draw_ellipse_by_xy(pen, x, y, width, height) {#draw_ellipse_by_xy_pen_x_y_width_height_44}


```
 draw_ellipse_by_xy(pen, x, y, width, height) 
```

Disegna un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, un'altezza e una larghezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile dell'ellisse. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| width | int | Larghezza del rettangolo di delimitazione che definisce l'ellisse. |
| height | int | Altezza del rettangolo di delimitazione che definisce l'ellisse. |

### Method: draw_ellipse_by_xyf(pen, x, y, width, height) {#draw_ellipse_by_xyf_pen_x_y_width_height_45}


```
 draw_ellipse_by_xyf(pen, x, y, width, height) 
```

Disegna un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, un'altezza e una larghezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile dell'ellisse. |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| width | float | Larghezza del rettangolo di delimitazione che definisce l'ellisse. |
| height | float | Altezza del rettangolo di delimitazione che definisce l'ellisse. |

### Method: draw_ellipse_f(pen, rect) {#draw_ellipse_f_pen_rect_46}


```
 draw_ellipse_f(pen, rect) 
```

Disegna un'ellisse definita da un [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) di delimitazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile dell'ellisse. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struttura che definisce i confini dell'ellisse. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_47}


```
 draw_image(image, dest_points) 
```

Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine da disegnare. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di tre strutture PointF che definiscono un parallelogramma. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_48}


```
 draw_image(image, dest_points) 
```

Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine da disegnare. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di tre strutture PointF che definiscono un parallelogramma. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_49}


```
 draw_image(image, dest_points, src_rect) 
```

Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine da disegnare. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di tre strutture PointF che definiscono un parallelogramma. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo di origine. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_50}


```
 draw_image(image, dest_points, src_rect) 
```

Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine da disegnare. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di tre strutture PointF che definiscono un parallelogramma. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il rettangolo di origine. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_51}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine da disegnare. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di tre strutture PointF che definiscono un parallelogramma. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo di origine. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Le unità di misura. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_52}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine da disegnare. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di tre strutture PointF che definiscono un parallelogramma. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il rettangolo di origine. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Le unità di misura. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_53}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine da disegnare. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di tre strutture PointF che definiscono un parallelogramma. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo di origine. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Le unità di misura. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Gli attributi dell'immagine. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_54}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine da disegnare. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di tre strutture PointF che definiscono un parallelogramma. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il rettangolo di origine. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Le unità di misura. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Gli attributi dell'immagine. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_55}


```
 draw_image(source_image, point) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato, usando la sua dimensione fisica originale, nella posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struttura che rappresenta l'angolo superiore sinistro dell'immagine disegnata. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_56}


```
 draw_image(source_image, point) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato, usando la sua dimensione fisica originale, nella posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struttura che rappresenta l'angolo superiore sinistro dell'immagine disegnata. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_57}


```
 draw_image(source_image, rect) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struttura che specifica la posizione e le dimensioni dell'immagine disegnata. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_58}


```
 draw_image(source_image, rect) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struttura che specifica la posizione e le dimensioni dell'immagine disegnata. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_59}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo di destinazione. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unità grafica. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_60}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il rettangolo di destinazione. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unità grafica. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_61}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo di destinazione. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unità grafica. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Gli attributi dell'immagine. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_62}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il rettangolo di destinazione. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unità grafica. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Gli attributi dell'immagine. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_63}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo di origine. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo di destinazione. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unità grafica. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_64}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il rettangolo di origine. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il rettangolo di destinazione. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unità grafica. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_65}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo di origine. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo di destinazione. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unità grafica. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Gli attributi dell'immagine. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_66}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il rettangolo di origine. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il rettangolo di destinazione. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unità grafica. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Gli attributi dell'immagine. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_67}


```
 draw_image(source_image, x, y) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato, usando la sua dimensione fisica originale, nella posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| x | float | La coordinata x dell'angolo superiore sinistro dell'immagine disegnata. |
| y | float | La coordinata y dell'angolo superiore sinistro dell'immagine disegnata. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_68}


```
 draw_image(source_image, x, y) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato, usando la sua dimensione fisica originale, nella posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| x | int | La coordinata x dell'angolo superiore sinistro dell'immagine disegnata. |
| y | int | La coordinata y dell'angolo superiore sinistro dell'immagine disegnata. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_69}


```
 draw_image(source_image, x, y, width, height) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| x | float | La coordinata x dell'angolo superiore sinistro dell'immagine disegnata. |
| y | float | La coordinata y dell'angolo superiore sinistro dell'immagine disegnata. |
| width | float | Larghezza dell'immagine disegnata. |
| height | float | Altezza dell'immagine disegnata. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_70}


```
 draw_image(source_image, x, y, width, height) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| x | int | La coordinata x dell'angolo superiore sinistro dell'immagine disegnata. |
| y | int | La coordinata y dell'angolo superiore sinistro dell'immagine disegnata. |
| width | int | Larghezza dell'immagine disegnata. |
| height | int | Altezza dell'immagine disegnata. |

### Method: draw_image_at_point(source_image, point) {#draw_image_at_point_source_image_point_71}


```
 draw_image_at_point(source_image, point) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato, usando la sua dimensione fisica originale, nella posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struttura che rappresenta l'angolo superiore sinistro dell'immagine disegnata. |

### Method: draw_image_at_point_f(source_image, point) {#draw_image_at_point_f_source_image_point_72}


```
 draw_image_at_point_f(source_image, point) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato, usando la sua dimensione fisica originale, nella posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struttura che rappresenta l'angolo superiore sinistro dell'immagine disegnata. |

### Method: draw_image_at_xy(source_image, x, y) {#draw_image_at_xy_source_image_x_y_73}


```
 draw_image_at_xy(source_image, x, y) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato, usando la sua dimensione fisica originale, nella posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| x | int | La coordinata x dell'angolo superiore sinistro dell'immagine disegnata. |
| y | int | La coordinata y dell'angolo superiore sinistro dell'immagine disegnata. |

### Method: draw_image_at_xyf(source_image, x, y) {#draw_image_at_xyf_source_image_x_y_74}


```
 draw_image_at_xyf(source_image, x, y) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato, usando la sua dimensione fisica originale, nella posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| x | float | La coordinata x dell'angolo superiore sinistro dell'immagine disegnata. |
| y | float | La coordinata y dell'angolo superiore sinistro dell'immagine disegnata. |

### Method: draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit) {#draw_image_dest_point_f_src_rect_f_with_unit_image_dest_points_src_rect_src_unit_75}


```
 draw_image_dest_point_f_src_rect_f_with_unit(image, dest_points, src_rect, src_unit) 
```

Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine da disegnare. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di tre strutture PointF che definiscono un parallelogramma. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il rettangolo di origine. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Le unità di misura. |

### Method: draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_dest_point_f_src_rect_f_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_76}


```
 draw_image_dest_point_f_src_rect_f_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) 
```

Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine da disegnare. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di tre strutture PointF che definiscono un parallelogramma. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il rettangolo di origine. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Le unità di misura. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Gli attributi dell'immagine. |

### Method: draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect) {#draw_image_dest_points_f_src_rect_f_image_dest_points_src_rect_77}


```
 draw_image_dest_points_f_src_rect_f(image, dest_points, src_rect) 
```

Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine da disegnare. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di tre strutture PointF che definiscono un parallelogramma. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il rettangolo di origine. |

### Method: draw_image_dest_points_src_rect(image, dest_points, src_rect) {#draw_image_dest_points_src_rect_image_dest_points_src_rect_78}


```
 draw_image_dest_points_src_rect(image, dest_points, src_rect) 
```

Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine da disegnare. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di tre strutture PointF che definiscono un parallelogramma. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo di origine. |

### Method: draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit) {#draw_image_dest_points_src_rect_with_unit_image_dest_points_src_rect_src_unit_79}


```
 draw_image_dest_points_src_rect_with_unit(image, dest_points, src_rect, src_unit) 
```

Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine da disegnare. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di tre strutture PointF che definiscono un parallelogramma. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo di origine. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Le unità di misura. |

### Method: draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_dest_points_src_rect_with_unit_and_attribs_image_dest_points_src_rect_src_unit_image_attributes_80}


```
 draw_image_dest_points_src_rect_with_unit_and_attribs(image, dest_points, src_rect, src_unit, image_attributes) 
```

Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine da disegnare. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di tre strutture PointF che definiscono un parallelogramma. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo di origine. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Le unità di misura. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Gli attributi dell'immagine. |

### Method: draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_dest_rect_f_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_81}


```
 draw_image_dest_rect_f_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il rettangolo di destinazione in cui disegnare. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unità grafica. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Gli attributi dell'immagine. |

### Method: draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_dest_rect_with_unit_attribs_source_image_rect_destination_graphics_unit_image_attributes_82}


```
 draw_image_dest_rect_with_unit_attribs(source_image, rect_destination, graphics_unit, image_attributes) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo di destinazione. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unità grafica. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Gli attributi dell'immagine. |

### Method: draw_image_in_rect(source_image, x, y, width, height) {#draw_image_in_rect_source_image_x_y_width_height_83}


```
 draw_image_in_rect(source_image, x, y, width, height) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| x | int | La coordinata x dell'angolo superiore sinistro dell'immagine disegnata. |
| y | int | La coordinata y dell'angolo superiore sinistro dell'immagine disegnata. |
| width | int | Larghezza dell'immagine disegnata. |
| height | int | Altezza dell'immagine disegnata. |

### Method: draw_image_in_rect_f(source_image, x, y, width, height) {#draw_image_in_rect_f_source_image_x_y_width_height_84}


```
 draw_image_in_rect_f(source_image, x, y, width, height) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| x | float | La coordinata x dell'angolo superiore sinistro dell'immagine disegnata. |
| y | float | La coordinata y dell'angolo superiore sinistro dell'immagine disegnata. |
| width | float | Larghezza dell'immagine disegnata. |
| height | float | Altezza dell'immagine disegnata. |

### Method: draw_image_in_rectangle(source_image, rect) {#draw_image_in_rectangle_source_image_rect_85}


```
 draw_image_in_rectangle(source_image, rect) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struttura che specifica la posizione e le dimensioni dell'immagine disegnata. |

### Method: draw_image_points(image, dest_points) {#draw_image_points_image_dest_points_86}


```
 draw_image_points(image, dest_points) 
```

Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine da disegnare. |
| dest_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di tre strutture PointF che definiscono un parallelogramma. |

### Method: draw_image_points_f(image, dest_points) {#draw_image_points_f_image_dest_points_87}


```
 draw_image_points_f(image, dest_points) 
```

Disegna la porzione specificata dell'_image_ specificata nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine da disegnare. |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di tre strutture PointF che definiscono un parallelogramma. |

### Method: draw_image_rectangle_f(source_image, rect) {#draw_image_rectangle_f_source_image_rect_88}


```
 draw_image_rectangle_f(source_image, rect) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struttura che specifica la posizione e le dimensioni dell'immagine disegnata. |

### Method: draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_src_dest_rects_f_with_unit_source_image_rect_source_rect_destination_graphics_unit_89}


```
 draw_image_src_dest_rects_f_with_unit(source_image, rect_source, rect_destination, graphics_unit) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il rettangolo di origine. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il rettangolo di destinazione. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unità grafica. |

### Method: draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_src_dest_rects_with_unit_source_image_rect_source_rect_destination_graphics_unit_90}


```
 draw_image_src_dest_rects_with_unit(source_image, rect_source, rect_destination, graphics_unit) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo di origine. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo di destinazione. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unità grafica. |

### Method: draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_src_dst_rect_f_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_91}


```
 draw_image_src_dst_rect_f_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| rect_source | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il rettangolo di origine. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il rettangolo di destinazione. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unità grafica da utilizzare. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Gli attributi dell'immagine da utilizzare. |

### Method: draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_src_dst_rects_with_unit_and_attribs_source_image_rect_source_rect_destination_graphics_unit_image_attributes_92}


```
 draw_image_src_dst_rects_with_unit_and_attribs(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| rect_source | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo di origine. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo di destinazione. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unità grafica. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Gli attributi dell'immagine. |

### Method: draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit) {#draw_image_to_rect_f_with_unit_source_image_rect_destination_graphics_unit_93}


```
 draw_image_to_rect_f_with_unit(source_image, rect_destination, graphics_unit) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| rect_destination | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il rettangolo di destinazione. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unità grafica. |

### Method: draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit) {#draw_image_to_rect_with_unit_source_image_rect_destination_graphics_unit_94}


```
 draw_image_to_rect_with_unit(source_image, rect_destination, graphics_unit) 
```

Disegna il [Graphics.image](/imaging/python-net/aspose.imaging/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| rect_destination | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo di destinazione. |
| graphics_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | L'unità grafica. |

### Method: draw_image_unscaled(source_image, point) {#draw_image_unscaled_source_image_point_95}


```
 draw_image_unscaled(source_image, point) 
```

Disegna un'immagine specificata usando la sua dimensione fisica originale in una posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) struttura che specifica l'angolo superiore sinistro dell'immagine disegnata. |

### Method: draw_image_unscaled(source_image, rect) {#draw_image_unscaled_source_image_rect_96}


```
 draw_image_unscaled(source_image, rect) 
```

Disegna un'immagine specificata usando la sua dimensione fisica originale in una posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) che specifica l'angolo superiore sinistro dell'immagine disegnata. Le proprietà X e Y del rettangolo specificano l'angolo superiore sinistro. Le proprietà Width e Height sono ignorate. |

### Method: draw_image_unscaled(source_image, x, y) {#draw_image_unscaled_source_image_x_y_97}


```
 draw_image_unscaled(source_image, x, y) 
```

Disegna l'immagine specificata usando la sua dimensione fisica originale nella posizione specificata da una coppia di coordinate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| x | int | La coordinata x dell'angolo superiore sinistro dell'immagine disegnata. |
| y | int | La coordinata y dell'angolo superiore sinistro dell'immagine disegnata. |

### Method: draw_image_unscaled(source_image, x, y, width, height) {#draw_image_unscaled_source_image_x_y_width_height_98}


```
 draw_image_unscaled(source_image, x, y, width, height) 
```

Disegna un'immagine specificata usando la sua dimensione fisica originale in una posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| x | int | La coordinata x dell'angolo superiore sinistro dell'immagine disegnata. |
| y | int | La coordinata y dell'angolo superiore sinistro dell'immagine disegnata. |
| width | int | Il parametro non è utilizzato. |
| height | int | Il parametro non è utilizzato. |

### Method: draw_image_unscaled_and_clipped(source_image, rect) {#draw_image_unscaled_and_clipped_source_image_rect_99}


```
 draw_image_unscaled_and_clipped(source_image, rect) 
```

Disegna l'immagine specificata senza ridimensionamento e la ritaglia, se necessario, per adattarla al rettangolo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) in cui disegnare l'immagine. |

### Method: draw_image_unscaled_in_rectangle(source_image, rect) {#draw_image_unscaled_in_rectangle_source_image_rect_100}


```
 draw_image_unscaled_in_rectangle(source_image, rect) 
```

Disegna un'immagine specificata usando la sua dimensione fisica originale in una posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) che specifica l'angolo superiore sinistro dell'immagine disegnata. Le proprietà X e Y del rettangolo specificano l'angolo superiore sinistro. Le proprietà Width e Height sono ignorate. |

### Method: draw_image_unscaled_to_point(source_image, point) {#draw_image_unscaled_to_point_source_image_point_101}


```
 draw_image_unscaled_to_point(source_image, point) 
```

Disegna un'immagine specificata usando la sua dimensione fisica originale in una posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine con cui disegnare. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) struttura che specifica l'angolo superiore sinistro dell'immagine disegnata. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_102}


```
 draw_line(pen, point1, point2) 
```

Disegna una linea che collega due strutture [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile della linea. |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | [Point](/imaging/python-net/aspose.imaging/point/) struttura che rappresenta il primo punto da collegare. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | [Punto](/imaging/python-net/aspose.imaging/point/) struttura che rappresenta il secondo punto da collegare. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_103}


```
 draw_line(pen, point1, point2) 
```

Disegna una linea che collega due strutture [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile della linea. |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [Point](/imaging/python-net/aspose.imaging/point/) struttura che rappresenta il primo punto da collegare. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [Punto](/imaging/python-net/aspose.imaging/point/) struttura che rappresenta il secondo punto da collegare. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_104}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Disegna una linea che collega i due punti specificati dalle coppie di coordinate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile della linea. |
| x1 | int | La coordinata x del primo punto. |
| y1 | int | La coordinata y del primo punto. |
| x2 | int | La coordinata x del secondo punto. |
| y2 | int | La coordinata y del secondo punto. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_105}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Disegna una linea che collega i due punti specificati dalle coppie di coordinate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile della linea. |
| x1 | float | La coordinata x del primo punto. |
| y1 | float | La coordinata y del primo punto. |
| x2 | float | La coordinata x del secondo punto. |
| y2 | float | La coordinata y del secondo punto. |

### Method: draw_line_by_xy(pen, x1, y1, x2, y2) {#draw_line_by_xy_pen_x1_y1_x2_y2_106}


```
 draw_line_by_xy(pen, x1, y1, x2, y2) 
```

Disegna una linea che collega i due punti specificati dalle coppie di coordinate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile della linea. |
| x1 | int | La coordinata x del primo punto. |
| y1 | int | La coordinata y del primo punto. |
| x2 | int | La coordinata x del secondo punto. |
| y2 | int | La coordinata y del secondo punto. |

### Method: draw_line_f_by_xy(pen, x1, y1, x2, y2) {#draw_line_f_by_xy_pen_x1_y1_x2_y2_107}


```
 draw_line_f_by_xy(pen, x1, y1, x2, y2) 
```

Disegna una linea che collega i due punti specificati dalle coppie di coordinate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile della linea. |
| x1 | float | La coordinata x del primo punto. |
| y1 | float | La coordinata y del primo punto. |
| x2 | float | La coordinata x del secondo punto. |
| y2 | float | La coordinata y del secondo punto. |

### Method: draw_line_point_f(pen, point1, point2) {#draw_line_point_f_pen_point1_point2_108}


```
 draw_line_point_f(pen, point1, point2) 
```

Disegna una linea che collega due strutture [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile della linea. |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PuntoF](/imaging/python-net/aspose.imaging/pointf/) struttura che rappresenta il primo punto da collegare. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PuntoF](/imaging/python-net/aspose.imaging/pointf/) struttura che rappresenta il secondo punto da collegare. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_109}


```
 draw_lines(pen, points) 
```

Disegna una serie di segmenti di linea che collegano un array di strutture [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Penna](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile dei segmenti di linea. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di strutture [Punto] che rappresentano i punti da collegare. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_110}


```
 draw_lines(pen, points) 
```

Disegna una serie di segmenti di linea che collegano un array di strutture [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Penna](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile dei segmenti di linea. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di strutture [Punto] che rappresentano i punti da collegare. |

### Method: draw_lines_f(pen, points) {#draw_lines_f_pen_points_111}


```
 draw_lines_f(pen, points) 
```

Disegna una serie di segmenti di linea che collegano un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Penna](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile dei segmenti di linea. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di strutture [PuntoF] che rappresentano i punti da collegare. |

### Method: draw_path(pen, path) {#draw_path_pen_path_112}


```
 draw_path(pen, path) 
```

Disegna un [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Penna](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile del percorso. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) da disegnare. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_113}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Disegna una forma a torta definita da un'ellisse specificata da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) e due linee radiali.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Penna](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile della forma a torta. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struttura che rappresenta il rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| start_angle | float | Angolo misurato in gradi in senso orario dall'asse x al primo lato della forma a torta. |
| sweep_angle | float | Angolo misurato in gradi in senso orario dal parametro _startAngle_ al secondo lato della forma a torta. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_114}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Disegna una forma a torta definita da un'ellisse specificata da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) e due linee radiali.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Penna](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile della forma a torta. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struttura che rappresenta il rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| start_angle | float | Angolo misurato in gradi in senso orario dall'asse x al primo lato della forma a torta. |
| sweep_angle | float | Angolo misurato in gradi in senso orario dal parametro _startAngle_ al secondo lato della forma a torta. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_115}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Disegna una forma a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Penna](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile della forma a torta. |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| width | float | Larghezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| height | float | Altezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| start_angle | float | Angolo misurato in gradi in senso orario dall'asse x al primo lato della forma a torta. |
| sweep_angle | float | Angolo misurato in gradi in senso orario dal parametro _startAngle_ al secondo lato della forma a torta. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_116}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Disegna una forma a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Penna](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile della forma a torta. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| width | int | Larghezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| height | int | Altezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| start_angle | int | Angolo misurato in gradi in senso orario dall'asse x al primo lato della forma a torta. |
| sweep_angle | int | Angolo misurato in gradi in senso orario dal parametro _startAngle_ al secondo lato della forma a torta. |

### Method: draw_pie_in_rect(pen, rect, start_angle, sweep_angle) {#draw_pie_in_rect_pen_rect_start_angle_sweep_angle_117}


```
 draw_pie_in_rect(pen, rect, start_angle, sweep_angle) 
```

Disegna una forma a torta definita da un'ellisse specificata da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) e due linee radiali.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Penna](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile della forma a torta. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struttura che rappresenta il rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| start_angle | float | Angolo misurato in gradi in senso orario dall'asse x al primo lato della forma a torta. |
| sweep_angle | float | Angolo misurato in gradi in senso orario dal parametro _startAngle_ al secondo lato della forma a torta. |

### Method: draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle) {#draw_pie_in_rect_f_pen_rect_start_angle_sweep_angle_118}


```
 draw_pie_in_rect_f(pen, rect, start_angle, sweep_angle) 
```

Disegna una forma a torta definita da un'ellisse specificata da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) e due linee radiali.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Penna](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile della forma a torta. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struttura che rappresenta il rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| start_angle | float | Angolo misurato in gradi in senso orario dall'asse x al primo lato della forma a torta. |
| sweep_angle | float | Angolo misurato in gradi in senso orario dal parametro _startAngle_ al secondo lato della forma a torta. |

### Method: draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_xy_pen_x_y_width_height_start_angle_sweep_angle_119}


```
 draw_pie_xy(pen, x, y, width, height, start_angle, sweep_angle) 
```

Disegna una forma a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Penna](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile della forma a torta. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| width | int | Larghezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| height | int | Altezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| start_angle | int | Angolo misurato in gradi in senso orario dall'asse x al primo lato della forma a torta. |
| sweep_angle | int | Angolo misurato in gradi in senso orario dal parametro _startAngle_ al secondo lato della forma a torta. |

### Method: draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_xyf_pen_x_y_width_height_start_angle_sweep_angle_120}


```
 draw_pie_xyf(pen, x, y, width, height, start_angle, sweep_angle) 
```

Disegna una forma a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Penna](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile della forma a torta. |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| width | float | Larghezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| height | float | Altezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| start_angle | float | Angolo misurato in gradi in senso orario dall'asse x al primo lato della forma a torta. |
| sweep_angle | float | Angolo misurato in gradi in senso orario dal parametro _startAngle_ al secondo lato della forma a torta. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_121}


```
 draw_polygon(pen, points) 
```

Disegna un poligono definito da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Penna](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile del poligono. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di strutture [PuntoF] che rappresentano i vertici del poligono. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_122}


```
 draw_polygon(pen, points) 
```

Disegna un poligono definito da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Penna](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile del poligono. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di strutture [PuntoF] che rappresentano i vertici del poligono. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_polygon_f(pen, points) {#draw_polygon_f_pen_points_123}


```
 draw_polygon_f(pen, points) 
```

Disegna un poligono definito da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Penna](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile del poligono. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di strutture [PuntoF] che rappresentano i vertici del poligono. |

### Method: draw_rect(pen, x, y, width, height) {#draw_rect_pen_x_y_width_height_124}


```
 draw_rect(pen, x, y, width, height) 
```

Disegna un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Una [Penna](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile del rettangolo. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo da disegnare. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo da disegnare. |
| width | int | La larghezza del rettangolo da disegnare. |
| height | int | L'altezza del rettangolo da disegnare. |

### Method: draw_rect_f(pen, x, y, width, height) {#draw_rect_f_pen_x_y_width_height_125}


```
 draw_rect_f(pen, x, y, width, height) 
```

Disegna un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Una [Penna](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile del rettangolo. |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo da disegnare. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo da disegnare. |
| width | float | La larghezza del rettangolo da disegnare. |
| height | float | L'altezza del rettangolo da disegnare. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_126}


```
 draw_rectangle(pen, rect) 
```

Disegna un rettangolo specificato da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Una [Penna](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile del rettangolo. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struttura che rappresenta il rettangolo da disegnare. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_127}


```
 draw_rectangle(pen, rect) 
```

Disegna un rettangolo specificato da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Una [Penna](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile del rettangolo. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Una [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struttura che rappresenta il rettangolo da disegnare. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_128}


```
 draw_rectangle(pen, x, y, width, height) 
```

Disegna un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Una [Penna](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile del rettangolo. |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo da disegnare. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo da disegnare. |
| width | float | La larghezza del rettangolo da disegnare. |
| height | float | L'altezza del rettangolo da disegnare. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_129}


```
 draw_rectangle(pen, x, y, width, height) 
```

Disegna un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Una [Penna](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile del rettangolo. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo da disegnare. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo da disegnare. |
| width | int | La larghezza del rettangolo da disegnare. |
| height | int | L'altezza del rettangolo da disegnare. |

### Method: draw_rectangle_f(pen, rect) {#draw_rectangle_f_pen_rect_130}


```
 draw_rectangle_f(pen, rect) 
```

Disegna un rettangolo specificato da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Una [Penna](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile del rettangolo. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struttura che rappresenta il rettangolo da disegnare. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_131}


```
 draw_rectangles(pen, rects) 
```

Disegna una serie di rettangoli specificati da strutture [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile dei contorni dei rettangoli. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Array di strutture [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che rappresentano i rettangoli da disegnare. |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_132}


```
 draw_rectangles(pen, rects) 
```

Disegna una serie di rettangoli specificati da strutture [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile dei contorni dei rettangoli. |
| rects | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | Array di strutture [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che rappresentano i rettangoli da disegnare. |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: draw_rectangles_f(pen, rects) {#draw_rectangles_f_pen_rects_133}


```
 draw_rectangles_f(pen, rects) 
```

Disegna una serie di rettangoli specificati da strutture [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | [Pen](/imaging/python-net/aspose.imaging/pen/) che determina il colore, la larghezza e lo stile dei contorni dei rettangoli. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Array di strutture [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che rappresentano i rettangoli da disegnare. |

### Method: draw_string(s, font, brush, layout_rectangle) {#draw_string_s_font_brush_layout_rectangle_134}


```
 draw_string(s, font, brush, layout_rectangle) 
```

Disegna la stringa di testo specificata nel rettangolo specificato con gli oggetti [Brush](/imaging/python-net/aspose.imaging/brush/) e [Font](/imaging/python-net/aspose.imaging/font/) specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| s | string | Stringa da disegnare. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) che definisce il formato del testo della stringa. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina il colore e la trama del testo disegnato. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struttura che specifica la posizione del testo disegnato. |

### Method: draw_string(s, font, brush, layout_rectangle, format) {#draw_string_s_font_brush_layout_rectangle_format_135}


```
 draw_string(s, font, brush, layout_rectangle, format) 
```

Disegna la stringa di testo specificata nel rettangolo specificato con gli oggetti [Brush](/imaging/python-net/aspose.imaging/brush/) e [Font](/imaging/python-net/aspose.imaging/font/) specificati, utilizzando gli attributi di formattazione del [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| s | string | Stringa da disegnare. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) che definisce il formato del testo della stringa. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina il colore e la trama del testo disegnato. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struttura che specifica la posizione del testo disegnato. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) che specifica gli attributi di formattazione, come l'interlinea e l'allineamento, che vengono applicati al testo disegnato. |

### Method: draw_string(s, font, brush, point) {#draw_string_s_font_brush_point_136}


```
 draw_string(s, font, brush, point) 
```

Disegna la stringa di testo specificata nella posizione specificata con gli oggetti [Brush](/imaging/python-net/aspose.imaging/brush/) e [Font](/imaging/python-net/aspose.imaging/font/) specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| s | string | Stringa da disegnare. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) che definisce il formato del testo della stringa. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina il colore e la trama del testo disegnato. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struttura che specifica l'angolo in alto a sinistra del testo disegnato. |


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: draw_string(s, font, brush, point, format) {#draw_string_s_font_brush_point_format_137}


```
 draw_string(s, font, brush, point, format) 
```

Disegna la stringa di testo specificata nella posizione specificata con gli oggetti [Brush](/imaging/python-net/aspose.imaging/brush/) e [Font](/imaging/python-net/aspose.imaging/font/) specificati, utilizzando gli attributi di formattazione del [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| s | string | Stringa da disegnare. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) che definisce il formato del testo della stringa. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina il colore e la trama del testo disegnato. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struttura che specifica l'angolo in alto a sinistra del testo disegnato. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) che specifica gli attributi di formattazione, come l'interlinea e l'allineamento, che vengono applicati al testo disegnato. |

### Method: draw_string(s, font, brush, x, y) {#draw_string_s_font_brush_x_y_138}


```
 draw_string(s, font, brush, x, y) 
```

Disegna la stringa di testo specificata nella posizione specificata con gli oggetti [Brush](/imaging/python-net/aspose.imaging/brush/) e [Font](/imaging/python-net/aspose.imaging/font/) specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| s | string | Stringa da disegnare. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) che definisce il formato del testo della stringa. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina il colore e la trama del testo disegnato. |
| x | float | La coordinata x dell'angolo in alto a sinistra del testo disegnato. |
| y | float | La coordinata y dell'angolo in alto a sinistra del testo disegnato. |

### Method: draw_string(s, font, brush, x, y, format) {#draw_string_s_font_brush_x_y_format_139}


```
 draw_string(s, font, brush, x, y, format) 
```

Disegna la stringa di testo specificata nella posizione specificata con gli oggetti [Brush](/imaging/python-net/aspose.imaging/brush/) e [Font](/imaging/python-net/aspose.imaging/font/) specificati, utilizzando gli attributi di formattazione del [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| s | string | Stringa da disegnare. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) che definisce il formato del testo della stringa. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina il colore e la trama del testo disegnato. |
| x | float | La coordinata x dell'angolo in alto a sinistra del testo disegnato. |
| y | float | La coordinata y dell'angolo in alto a sinistra del testo disegnato. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) che specifica gli attributi di formattazione, come l'interlinea e l'allineamento, che vengono applicati al testo disegnato. |

### Method: draw_string_at_point_f(s, font, brush, point) {#draw_string_at_point_f_s_font_brush_point_140}


```
 draw_string_at_point_f(s, font, brush, point) 
```

Disegna la stringa di testo specificata nella posizione specificata con gli oggetti [Brush](/imaging/python-net/aspose.imaging/brush/) e [Font](/imaging/python-net/aspose.imaging/font/) specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| s | string | Stringa da disegnare. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) che definisce il formato del testo della stringa. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina il colore e la trama del testo disegnato. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struttura che specifica l'angolo in alto a sinistra del testo disegnato. |

### Method: draw_string_at_point_f_format(s, font, brush, point, format) {#draw_string_at_point_f_format_s_font_brush_point_format_141}


```
 draw_string_at_point_f_format(s, font, brush, point, format) 
```

Disegna la stringa di testo specificata nella posizione specificata con gli oggetti [Brush](/imaging/python-net/aspose.imaging/brush/) e [Font](/imaging/python-net/aspose.imaging/font/) specificati, utilizzando gli attributi di formattazione del [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| s | string | Stringa da disegnare. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) che definisce il formato del testo della stringa. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina il colore e la trama del testo disegnato. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | [PointF](/imaging/python-net/aspose.imaging/pointf/) struttura che specifica l'angolo in alto a sinistra del testo disegnato. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) che specifica gli attributi di formattazione, come l'interlinea e l'allineamento, che vengono applicati al testo disegnato. |

### Method: draw_string_at_xy(s, font, brush, x, y) {#draw_string_at_xy_s_font_brush_x_y_142}


```
 draw_string_at_xy(s, font, brush, x, y) 
```

Disegna la stringa di testo specificata nella posizione specificata con gli oggetti [Brush](/imaging/python-net/aspose.imaging/brush/) e [Font](/imaging/python-net/aspose.imaging/font/) specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| s | string | Stringa da disegnare. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) che definisce il formato del testo della stringa. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina il colore e la trama del testo disegnato. |
| x | float | La coordinata x dell'angolo in alto a sinistra del testo disegnato. |
| y | float | La coordinata y dell'angolo in alto a sinistra del testo disegnato. |

### Method: draw_string_in_rect(s, font, brush, layout_rectangle) {#draw_string_in_rect_s_font_brush_layout_rectangle_143}


```
 draw_string_in_rect(s, font, brush, layout_rectangle) 
```

Disegna la stringa di testo specificata nel rettangolo specificato con gli oggetti [Brush](/imaging/python-net/aspose.imaging/brush/) e [Font](/imaging/python-net/aspose.imaging/font/) specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| s | string | Stringa da disegnare. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) che definisce il formato del testo della stringa. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina il colore e la trama del testo disegnato. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struttura che specifica la posizione del testo disegnato. |

### Method: draw_string_in_rect_f(s, font, brush, layout_rectangle, format) {#draw_string_in_rect_f_s_font_brush_layout_rectangle_format_144}


```
 draw_string_in_rect_f(s, font, brush, layout_rectangle, format) 
```

Disegna la stringa di testo specificata nel rettangolo specificato con gli oggetti [Brush](/imaging/python-net/aspose.imaging/brush/) e [Font](/imaging/python-net/aspose.imaging/font/) specificati, utilizzando gli attributi di formattazione del [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| s | string | Stringa da disegnare. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | [Font](/imaging/python-net/aspose.imaging/font/) che definisce il formato del testo della stringa. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina il colore e la trama del testo disegnato. |
| layout_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struttura che specifica la posizione del testo disegnato. |
| format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) che specifica gli attributi di formattazione, come l'interlinea e l'allineamento, che vengono applicati al testo disegnato. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_145}


```
 fill_closed_curve(brush, points) 
```

Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) . Questo metodo utilizza una tensione predefinita di 0,5 e la modalità di riempimento [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) .

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che definiscono la spline. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_146}


```
 fill_closed_curve(brush, points) 
```

Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) . Questo metodo utilizza una tensione predefinita di 0,5 e la modalità di riempimento [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) .

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che definiscono la spline. |

### Method: fill_closed_curve(brush, points, fill_mode) {#fill_closed_curve_brush_points_fill_mode_147}


```
 fill_closed_curve(brush, points, fill_mode) 
```

Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando la modalità di riempimento specificata. Questo metodo utilizza una tensione predefinita di 0,5.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che definiscono la spline. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Membro dell'enumerazione [FillMode](/imaging/python-net/aspose.imaging/fillmode/) che determina come viene riempita la curva. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_148}


```
 fill_closed_curve(brush, points, fillmode) 
```

Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando la modalità di riempimento specificata. Questo metodo utilizza una tensione predefinita di 0,5.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che definiscono la spline. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) |  |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_149}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando la modalità di riempimento e la tensione specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Una [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che definiscono la spline. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Membro dell'enumerazione [FillMode](/imaging/python-net/aspose.imaging/fillmode/) che determina come viene riempita la curva. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_150}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando la modalità di riempimento e la tensione specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Una [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che definiscono la spline. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Membro dell'enumerazione [FillMode](/imaging/python-net/aspose.imaging/fillmode/) che determina come viene riempita la curva. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Method: fill_closed_curve_by_point(brush, points) {#fill_closed_curve_by_point_brush_points_151}


```
 fill_closed_curve_by_point(brush, points) 
```

Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) . Questo metodo utilizza una tensione predefinita di 0,5 e la modalità di riempimento [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) .

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che definiscono la spline. |

### Method: fill_closed_curve_by_point_f(brush, points) {#fill_closed_curve_by_point_f_brush_points_152}


```
 fill_closed_curve_by_point_f(brush, points) 
```

Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) . Questo metodo utilizza una tensione predefinita di 0,5 e la modalità di riempimento [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) .

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che definiscono la spline. |

### Method: fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension) {#fill_closed_curve_by_point_f_fill_mode_tension_brush_points_fillmode_tension_153}


```
 fill_closed_curve_by_point_f_fill_mode_tension(brush, points, fillmode, tension) 
```

Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando la modalità di riempimento e la tensione specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Una [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che definiscono la spline. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Membro dell'enumerazione [FillMode](/imaging/python-net/aspose.imaging/fillmode/) che determina come viene riempita la curva. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Method: fill_closed_curve_by_point_fill_mode(brush, points, fillmode) {#fill_closed_curve_by_point_fill_mode_brush_points_fillmode_154}


```
 fill_closed_curve_by_point_fill_mode(brush, points, fillmode) 
```

Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [Point](/imaging/python-net/aspose.imaging/point/) utilizzando la modalità di riempimento specificata. Questo metodo utilizza una tensione predefinita di 0,5.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di strutture [Point](/imaging/python-net/aspose.imaging/point/) che definiscono la spline. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Membro dell'enumerazione [FillMode](/imaging/python-net/aspose.imaging/fillmode/) che determina come viene riempita la curva. |

### Method: fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension) {#fill_closed_curve_by_point_fill_mode_tension_brush_points_fillmode_tension_155}


```
 fill_closed_curve_by_point_fill_mode_tension(brush, points, fillmode, tension) 
```

Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [Point](/imaging/python-net/aspose.imaging/point/) utilizzando la modalità di riempimento e la tensione specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di strutture [Point](/imaging/python-net/aspose.imaging/point/) che definiscono la spline. |
| fillmode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Membro dell'enumerazione [FillMode](/imaging/python-net/aspose.imaging/fillmode/) che determina come viene riempita la curva. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_156}


```
 fill_ellipse(brush, rect) 
```

Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) .

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struttura che rappresenta il rettangolo di delimitazione che definisce l'ellisse. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_157}


```
 fill_ellipse(brush, rect) 
```

Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) .

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struttura che rappresenta il rettangolo di delimitazione che definisce l'ellisse. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_158}


```
 fill_ellipse(brush, x, y, width, height) 
```

Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| width | float | Larghezza del rettangolo di delimitazione che definisce l'ellisse. |
| height | float | Altezza del rettangolo di delimitazione che definisce l'ellisse. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_159}


```
 fill_ellipse(brush, x, y, width, height) 
```

Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| width | int | Larghezza del rettangolo di delimitazione che definisce l'ellisse. |
| height | int | Altezza del rettangolo di delimitazione che definisce l'ellisse. |

### Method: fill_ellipse_at_xywh(brush, x, y, width, height) {#fill_ellipse_at_xywh_brush_x_y_width_height_160}


```
 fill_ellipse_at_xywh(brush, x, y, width, height) 
```

Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| width | int | Larghezza del rettangolo di delimitazione che definisce l'ellisse. |
| height | int | Altezza del rettangolo di delimitazione che definisce l'ellisse. |

### Method: fill_ellipse_at_xywhf(brush, x, y, width, height) {#fill_ellipse_at_xywhf_brush_x_y_width_height_161}


```
 fill_ellipse_at_xywhf(brush, x, y, width, height) 
```

Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| width | float | Larghezza del rettangolo di delimitazione che definisce l'ellisse. |
| height | float | Altezza del rettangolo di delimitazione che definisce l'ellisse. |

### Method: fill_ellipse_in_rect(brush, rect) {#fill_ellipse_in_rect_brush_rect_162}


```
 fill_ellipse_in_rect(brush, rect) 
```

Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) .

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struttura che rappresenta il rettangolo di delimitazione che definisce l'ellisse. |

### Method: fill_ellipse_in_rect_f(brush, rect) {#fill_ellipse_in_rect_f_brush_rect_163}


```
 fill_ellipse_in_rect_f(brush, rect) 
```

Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) .

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struttura che rappresenta il rettangolo di delimitazione che definisce l'ellisse. |

### Method: fill_path(brush, path) {#fill_path_brush_path_164}


```
 fill_path(brush, path) 
```

Riempie l'interno di un [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) .

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) che rappresenta il percorso da riempire. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_165}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) e due linee radiali.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struttura che rappresenta il rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| start_angle | float | Angolo in gradi misurato in senso orario dall'asse x al primo lato della sezione a torta. |
| sweep_angle | float | Angolo in gradi misurato in senso orario dal parametro _startAngle_ al secondo lato della sezione a torta. |


**See also:**

**[Example # 1](#example_95)**: The following example shows how to compose an animated GIF image from individ...


### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_166}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) e due linee radiali.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struttura che rappresenta il rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| start_angle | float | Angolo in gradi misurato in senso orario dall'asse x al primo lato della sezione a torta. |
| sweep_angle | float | Angolo in gradi misurato in senso orario dal parametro _startAngle_ al secondo lato della sezione a torta. |


**See also:**

**[Example # 1](#example_95)**: The following example shows how to compose an animated GIF image from individ...


### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_167}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| width | float | Larghezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| height | float | Altezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| start_angle | float | Angolo in gradi misurato in senso orario dall'asse x al primo lato della sezione a torta. |
| sweep_angle | float | Angolo in gradi misurato in senso orario dal parametro _startAngle_ al secondo lato della sezione a torta. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_168}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| width | int | Larghezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| height | int | Altezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| start_angle | int | Angolo in gradi misurato in senso orario dall'asse x al primo lato della sezione a torta. |
| sweep_angle | int | Angolo in gradi misurato in senso orario dal parametro _startAngle_ al secondo lato della sezione a torta. |

### Method: fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_at_xy_brush_x_y_width_height_start_angle_sweep_angle_169}


```
 fill_pie_at_xy(brush, x, y, width, height, start_angle, sweep_angle) 
```

Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| width | int | Larghezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| height | int | Altezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| start_angle | int | Angolo in gradi misurato in senso orario dall'asse x al primo lato della sezione a torta. |
| sweep_angle | int | Angolo in gradi misurato in senso orario dal parametro _startAngle_ al secondo lato della sezione a torta. |

### Method: fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_at_xyf_brush_x_y_width_height_start_angle_sweep_angle_170}


```
 fill_pie_at_xyf(brush, x, y, width, height, start_angle, sweep_angle) 
```

Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| width | float | Larghezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| height | float | Altezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| start_angle | float | Angolo in gradi misurato in senso orario dall'asse x al primo lato della sezione a torta. |
| sweep_angle | float | Angolo in gradi misurato in senso orario dal parametro _startAngle_ al secondo lato della sezione a torta. |

### Method: fill_pie_in_rect(brush, rect, start_angle, sweep_angle) {#fill_pie_in_rect_brush_rect_start_angle_sweep_angle_171}


```
 fill_pie_in_rect(brush, rect, start_angle, sweep_angle) 
```

Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) e due linee radiali.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) struttura che rappresenta il rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| start_angle | float | Angolo in gradi misurato in senso orario dall'asse x al primo lato della sezione a torta. |
| sweep_angle | float | Angolo in gradi misurato in senso orario dal parametro _startAngle_ al secondo lato della sezione a torta. |

### Method: fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle) {#fill_pie_in_rect_f_brush_rect_start_angle_sweep_angle_172}


```
 fill_pie_in_rect_f(brush, rect, start_angle, sweep_angle) 
```

Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) e due linee radiali.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che rappresenta il rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| start_angle | float | Angolo in gradi misurato in senso orario dall'asse x al primo lato della sezione a torta. |
| sweep_angle | float | Angolo in gradi misurato in senso orario dal parametro _startAngle_ al secondo lato della sezione a torta. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_173}


```
 fill_polygon(brush, points) 
```

Riempie l'interno di un poligono definito da un array di punti specificati da strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) e dalla modalità di riempimento [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) .

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che rappresentano i vertici del poligono da riempire. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_174}


```
 fill_polygon(brush, points) 
```

Riempie l'interno di un poligono definito da un array di punti specificati da strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) e dalla modalità di riempimento [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) .

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che rappresentano i vertici del poligono da riempire. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_175}


```
 fill_polygon(brush, points, fill_mode) 
```

Riempie l'interno di un poligono definito da un array di punti specificati da strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando la modalità di riempimento specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che rappresentano i vertici del poligono da riempire. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Membro dell'enumerazione [FillMode](/imaging/python-net/aspose.imaging/fillmode/) che determina lo stile del riempimento. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_176}


```
 fill_polygon(brush, points, fill_mode) 
```

Riempie l'interno di un poligono definito da un array di punti specificati da strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando la modalità di riempimento specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che rappresentano i vertici del poligono da riempire. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Membro dell'enumerazione [FillMode](/imaging/python-net/aspose.imaging/fillmode/) che determina lo stile del riempimento. |

### Method: fill_polygon_by_point(brush, points) {#fill_polygon_by_point_brush_points_177}


```
 fill_polygon_by_point(brush, points) 
```

Riempie l'interno di un poligono definito da un array di punti specificati da strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) e dalla modalità di riempimento [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) .

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che rappresentano i vertici del poligono da riempire. |

### Method: fill_polygon_by_point_f(brush, points) {#fill_polygon_by_point_f_brush_points_178}


```
 fill_polygon_by_point_f(brush, points) 
```

Riempie l'interno di un poligono definito da un array di punti specificati da strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) e dalla modalità di riempimento [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/) .

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che rappresentano i vertici del poligono da riempire. |

### Method: fill_polygon_by_point_f_fill_mode(brush, points, fill_mode) {#fill_polygon_by_point_f_fill_mode_brush_points_fill_mode_179}


```
 fill_polygon_by_point_f_fill_mode(brush, points, fill_mode) 
```

Riempie l'interno di un poligono definito da un array di punti specificati da strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) utilizzando la modalità di riempimento specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Array di strutture [PointF](/imaging/python-net/aspose.imaging/pointf/) che rappresentano i vertici del poligono da riempire. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Membro dell'enumerazione [FillMode](/imaging/python-net/aspose.imaging/fillmode/) che determina lo stile del riempimento. |

### Method: fill_polygon_by_point_fill_mode(brush, points, fill_mode) {#fill_polygon_by_point_fill_mode_brush_points_fill_mode_180}


```
 fill_polygon_by_point_fill_mode(brush, points, fill_mode) 
```

Riempie l'interno di un poligono definito da un array di punti specificati da strutture [Point](/imaging/python-net/aspose.imaging/point/) utilizzando la modalità di riempimento specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Array di strutture [Point](/imaging/python-net/aspose.imaging/point/) che rappresentano i vertici del poligono da riempire. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Membro dell'enumerazione [FillMode](/imaging/python-net/aspose.imaging/fillmode/) che determina lo stile del riempimento. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_181}


```
 fill_rectangle(brush, rect) 
```

Riempie l'interno di un rettangolo specificato da una struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) .

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) che rappresenta il rettangolo da riempire. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_182}


```
 fill_rectangle(brush, rect) 
```

Riempie l'interno di un rettangolo specificato da una struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) .

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) che rappresenta il rettangolo da riempire. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_183}


```
 fill_rectangle(brush, x, y, width, height) 
```

Riempie l'interno di un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| x | float | La coordinata x dell'angolo superiore sinistro del rettangolo da riempire. |
| y | float | La coordinata y dell'angolo superiore sinistro del rettangolo da riempire. |
| width | float | Larghezza del rettangolo da riempire. |
| height | float | Altezza del rettangolo da riempire. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_184}


```
 fill_rectangle(brush, x, y, width, height) 
```

Riempie l'interno di un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| x | int | La coordinata x dell'angolo superiore sinistro del rettangolo da riempire. |
| y | int | La coordinata y dell'angolo superiore sinistro del rettangolo da riempire. |
| width | int | Larghezza del rettangolo da riempire. |
| height | int | Altezza del rettangolo da riempire. |

### Method: fill_rectangle_f(brush, rect) {#fill_rectangle_f_brush_rect_185}


```
 fill_rectangle_f(brush, rect) 
```

Riempie l'interno di un rettangolo specificato da una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) .

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che rappresenta il rettangolo da riempire. |

### Method: fill_rectangle_f_with_brush(brush, x, y, width, height) {#fill_rectangle_f_with_brush_brush_x_y_width_height_186}


```
 fill_rectangle_f_with_brush(brush, x, y, width, height) 
```

Riempie l'interno di un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| x | float | La coordinata x dell'angolo superiore sinistro del rettangolo da riempire. |
| y | float | La coordinata y dell'angolo superiore sinistro del rettangolo da riempire. |
| width | float | Larghezza del rettangolo da riempire. |
| height | float | Altezza del rettangolo da riempire. |

### Method: fill_rectangle_with_brush(brush, x, y, width, height) {#fill_rectangle_with_brush_brush_x_y_width_height_187}


```
 fill_rectangle_with_brush(brush, x, y, width, height) 
```

Riempie l'interno di un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| x | int | La coordinata x dell'angolo superiore sinistro del rettangolo da riempire. |
| y | int | La coordinata y dell'angolo superiore sinistro del rettangolo da riempire. |
| width | int | Larghezza del rettangolo da riempire. |
| height | int | Altezza del rettangolo da riempire. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_188}


```
 fill_rectangles(brush, rects) 
```

Riempie gli interni di una serie di rettangoli specificati da strutture [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) .

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| rects | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | Array di strutture [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) che rappresentano i rettangoli da riempire. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_189}


```
 fill_rectangles(brush, rects) 
```

Riempie gli interni di una serie di rettangoli specificati da strutture [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) .

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Array di strutture [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) che rappresentano i rettangoli da riempire. |

### Method: fill_rectangles_f(brush, rects) {#fill_rectangles_f_brush_rects_190}


```
 fill_rectangles_f(brush, rects) 
```

Riempie gli interni di una serie di rettangoli specificati da strutture [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) .

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| rects | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | Array di strutture [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) che rappresentano i rettangoli da riempire. |

### Method: fill_region(brush, region) {#fill_region_brush_region_191}


```
 fill_region(brush, region) 
```

Riempie l'interno di una [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | [Brush](/imaging/python-net/aspose.imaging/brush/) che determina le caratteristiche del riempimento. |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | [Region](/imaging/python-net/aspose.imaging/region/) che rappresenta l'area da riempire. |

### Method: measure_string(text, font, layout_area, string_format) {#measure_string_text_font_layout_area_string_format_192}


```
 measure_string(text, font, layout_area, string_format) 
```

Misura la stringa di testo specificata con i parametri specificati

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| text | string | Il testo da misurare. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Il font da misurare. |
| layout_area | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | L'area di layout. |
| string_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Il formato stringa. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Dimensione in pixel della stringa di testo misurata |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_193}


```
 multiply_transform(matrix) 
```

Moltiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) che rappresenta la trasformazione geometrica locale di questo [Graphics](/imaging/python-net/aspose.imaging/graphics/) per la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata, pre-pendendo la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) con cui moltiplicare la trasformazione geometrica. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_194}


```
 multiply_transform(matrix, order) 
```

Moltiplica la [Matrix](/imaging/python-net/aspose.imaging/matrix/) che rappresenta la trasformazione geometrica locale di questo [Graphics](/imaging/python-net/aspose.imaging/graphics/) per la [Matrix](/imaging/python-net/aspose.imaging/matrix/) nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) con cui moltiplicare la trasformazione geometrica. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) che specifica in quale ordine moltiplicare le due matrici. |

### Method: rotate_transform(angle) {#rotate_transform_angle_195}


```
 rotate_transform(angle) 
```

Ruota la trasformazione geometrica locale della quantità specificata. Questo metodo prepone la rotazione alla trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angle | float | L'angolo di rotazione. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_196}


```
 rotate_transform(angle, order) 
```

Ruota la trasformazione geometrica locale della quantità specificata nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angle | float | L'angolo di rotazione. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) che specifica se aggiungere o pre-pendere la matrice di rotazione. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_197}


```
 scale_transform(sx, sy) 
```

Scala la trasformazione geometrica locale delle quantità specificate. Questo metodo prepone la matrice di scala alla trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| sx | float | La quantità con cui scalare la trasformazione lungo l'asse x. |
| sy | float | La quantità con cui scalare la trasformazione lungo l'asse y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_198}


```
 scale_transform(sx, sy, order) 
```

Scala la trasformazione geometrica locale delle quantità specificate nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| sx | float | La quantità con cui scalare la trasformazione lungo l'asse x. |
| sy | float | La quantità con cui scalare la trasformazione lungo l'asse y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) che specifica se aggiungere o anteporre la matrice di scaling. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_199}


```
 translate_transform(dx, dy) 
```

Trasla la trasformazione geometrica locale delle dimensioni specificate. Questo metodo prepone la traslazione alla trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dx | float | Il valore della traslazione in x. |
| dy | float | Il valore della traslazione in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_200}


```
 translate_transform(dx, dy, order) 
```

Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dx | float | Il valore della traslazione in x. |
| dy | float | Il valore della traslazione in y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | L'ordine (anteporre o aggiungere) con cui applicare la traslazione. |

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

#Crea un'istanza di flusso file
with open(r"C:\temp\output.png", "w+b") as stream:
	#Crea un'istanza di PngOptions e imposta le sue varie proprietà
	pngOptions = PngOptions()
	#Imposta la sorgente per PngOptions
	pngOptions.source = StreamSource(stream)
	#Crea un'istanza di Image 
	with Image.create(pngOptions, 500, 500) as image:
		#Crea e inizializza un'istanza della classe Graphics
		graphics = Graphics(image)
		#Cancella la superficie Graphics
		graphics.clear(Color.wheat);
		#Disegna un arco specificando l'oggetto Pen con colore Nero, 
		#un rettangolo che circonda l'arco, angolo di partenza e angolo di sweep
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#Disegna un Bezier specificando l'oggetto Pen con colore Blu e i punti di coordinate.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#Disegna una curva specificando l'oggetto Pen con colore Verde e un array di Points
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#Disegna un'ellisse usando l'oggetto Pen e un Rectangle circostante
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#Disegna una linea
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#Disegna un segmento di torta
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#Disegna un poligono specificando l'oggetto Pen con colore Rosso e un array di Points
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#Disegna un Rectangle
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#Crea un oggetto SolidBrush e imposta le sue varie proprietà
		brush = SolidBrush()
		brush.color = Color.purple
		#Disegna una String usando l'oggetto SolidBrush e Font, in un Point specifico
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# salva tutte le modifiche.
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


# Crea un'istanza di un flusso di file
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# Crea un'istanza di TiffOptions e imposta le sue varie proprietà
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Imposta la sorgente per l'istanza di ImageOptions
	tiffOptions.source = StreamSource(stream)
	# Crea un'istanza di Image
	with Image.create(tiffOptions, 500, 500) as image:
		# Crea e inizializza un'istanza della classe Graphics
		graphics = Graphics(image)
		# Cancella la superficie Graphics
		graphics.clear(Color.wheat);
		# Crea un'istanza della classe GraphicsPath
		graphics_path = GraphicsPath()
		# Crea un'istanza della classe Figure
		figure = Figure()
		# Aggiungi forme all'oggetto Figure
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# Aggiungi l'oggetto Figure a GraphicsPath
		graphics_path.add_figure(figure)
		# Disegna il percorso con l'oggetto Pen di colore Nero
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# salva tutte le modifiche.
		image.save()


```

### This example shows the creation and usage Pen objects. The example creates a new Image and draw rectangles on the Image surface. {#example_14}
``` python

from aspose.imaging import Image, Graphics, Color, Pen, Rectangle, Point, Size
from aspose.imaging.brushes import HatchBrush
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

# Crea un'istanza di BmpOptions e imposta le sue varie proprietà
bmpOptions = BmpOptions()
bmpOptions.bits_per_pixel = 24
# Crea un'istanza di FileCreateSource e assegnala come sorgente per l'istanza di BmpOptions
# Il secondo parametro Booleano determina se il file da creare è temporaneo o meno
bmpOptions.source = FileCreateSource(r"C:\temp\sample.bmp", False)
# Crea un'istanza di Image nel percorso specificato
with Image.create(bmpOptions, 500, 500) as image:
	# Crea un'istanza di Graphics e inizializzala con l'oggetto Image
	graphics = Graphics(image)
	# Cancella la superficie Graphics con colore bianco
	graphics.clear(Color.white)
	#Crea un'istanza di Pen con colore rosso e larghezza 5
	pen = Pen(Color.red, 5.0);
	# Crea un'istanza di HatchBrush e imposta le sue proprietà
	brush = HatchBrush()
	brush.background_color = Color.wheat;
	brush.foreground_color = Color.red;
	# Crea un'istanza di Pen
	# inizializzalo con l'oggetto HatchBrush e la larghezza
	brusedpen = Pen(brush, 5.0)
	# Disegna rettangoli specificando l'oggetto Pen
	graphics.draw_rectangles(pen, [
		Rectangle(Point(210, 210), Size(100, 100)),
		Rectangle(Point(110, 110), Size(100, 100)),
		Rectangle(Point(310, 310), Size(100, 100)) ])

	# Disegna rettangoli specificando l'oggetto Pen
	graphics.draw_rectangles(brusedpen, [
		Rectangle(Point(310, 110), Size(100, 100)),
		Rectangle(Point(110, 310), Size(100, 100)) ])

	# salva tutte le modifiche.
	image.save()


```

### The following example shows how to compose an animated GIF image from individual GIF blocks. {#example_95}
``` python
from aspose.imaging.fileformats.gif.blocks import GifFrameBlock
from aspose.imaging.fileformats.gif import GifImage 
from aspose.imaging.brushes import SolidBrush
from aspose.imaging import Graphics, Color

# Crea un'immagine GIF 100 x 100 px.
# Il primo blocco è completamente nero per impostazione predefinita.
with GifFrameBlock(100, 100) as firstBlock:
	with GifImage(firstBlock) as gifImage:
		# Il primo cerchio è rosso
		brush1 = SolidBrush(Color.red)

		# Il secondo cerchio è nero
		brush2 = SolidBrush(Color.black)

		# Aumenta gradualmente l'angolo della forma dell'arco rosso.
		for angle in range(10, 361, 10):
			block = GifFrameBlock(100, 100)
			gr = Graphics(block)
			gr.fill_pie(brush1, block.bounds, 0, angle)
			gifImage.add_block(block)
		
		# Aumenta gradualmente l'angolo dell'arco nero e cancella l'arco rosso.
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
# Crea un'immagine PNG di 100x100 px.
with PngImage(100, 100) as png_image:
	# Esegui qualche elaborazione dell'immagine, ad es. riempi l'intera immagine di rosso.
	graphics = Graphics(png_image)
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, png_image.bounds)
	# Salva in un file.
	png_image.save(join(dir_, "output.png"))


```

