---
title: "Класс EmfRecorderGraphics2D"
type: docs
weight: 10
url: /ru/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/
---

**Summary:** The Emf recorder graphics

**Module:** [aspose.imaging.fileformats.emf.graphics](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/)

**Full Name:** aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D

**Inheritance:** MetafileRecorderGraphics2D

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfRecorderGraphics2D(frame, device_size, device_size_mm)](#EmfRecorderGraphics2D_frame_device_size_device_size_mm_1) | Инициализирует новый экземпляр класса [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Получает или задает цвет фона. |
| background_mode | [EmfBackgroundMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfbackgroundmode/) | r/w | Получает или задает режим фона. |
| clip | [Region](/imaging/python-net/aspose.imaging/region/) | r/w | Получает или задает область, ограничивающую область рисования этого Graphics |
| clip_bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Получает границы обрезки. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| clear() | Очищает состояние графического объекта |
| [draw_arc(pen, rect, start_angle, arc_angle)](#draw_arc_pen_rect_start_angle_arc_angle_1) | Рисует дугу, представляющую часть эллипса, заданного структурой Rectangle. |
| [draw_cubic_bezier(pen, pt1, pt2, pt3, pt4)](#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2) | Рисует кубический безье. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_3) | Рисует эллипс. |
| [draw_image(image, dest_rect, src_rect, src_unit)](#draw_image_image_dest_rect_src_rect_src_unit_4) | Рисует указанную часть указанного изображения в указанном месте и с указанным размером. |
| [draw_image(image, location)](#draw_image_image_location_5) | Отрисовывает указанное изображение, используя его оригинальный физический размер, в указанном месте. |
| [draw_image(image_bytes, dest_rect, src_unit)](#draw_image_image_bytes_dest_rect_src_unit_6) | Отрисовывает изображение. |
| [draw_image(stream, dest_rect, src_unit)](#draw_image_stream_dest_rect_src_unit_7) | Отрисовывает изображение. |
| [draw_image_from_bytes(image_bytes, dest_rect, src_unit)](#draw_image_from_bytes_image_bytes_dest_rect_src_unit_8) | Отрисовывает изображение. |
| [draw_image_from_stream(stream, dest_rect, src_unit)](#draw_image_from_stream_stream_dest_rect_src_unit_9) | Отрисовывает изображение. |
| [draw_line(pen, pt1, pt2)](#draw_line_pen_pt1_pt2_10) | Отрисовывает линию. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_11) | Отрисовывает линию. |
| [draw_path(pen, path)](#draw_path_pen_path_12) | Отрисовывает путь. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_13) | Отрисовывает сектор. |
| [draw_poly_cubic_bezier(pen, points)](#draw_poly_cubic_bezier_pen_points_14) | Отрисовывает поликубический Безье. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_15) | Отрисовывает многоугольник. |
| [draw_polyline(pen, points)](#draw_polyline_pen_points_16) | Отрисовывает полилинию. |
| [draw_rectangle(pen, rectangle)](#draw_rectangle_pen_rectangle_17) | Отрисовывает прямоугольник. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_18) | Отрисовывает прямоугольник. |
| [draw_string(string, font, color, x, y)](#draw_string_string_font_color_x_y_19) | Отрисовывает строку. |
| [draw_string(string, font, color, x, y, angle)](#draw_string_string_font_color_x_y_angle_20) | Отрисовывает строку. |
| [end_recording()](#end_recording__21) | Завершает запись. |
| [exclude_clip(rect)](#exclude_clip_rect_22) | Обновляет область отсечения этого Graphics, исключая область, указанную структурой Rectangle. |
| [exclude_clip(region)](#exclude_clip_region_23) | Обновляет область отсечения этого Graphics, исключая область, указанную объектом Region. |
| [exclude_clip_rect(rect)](#exclude_clip_rect_rect_24) | Обновляет область отсечения этого Graphics, исключая область, указанную структурой Rectangle. |
| [exclude_clip_rgn(region)](#exclude_clip_rgn_region_25) | Обновляет область отсечения этого Graphics, исключая область, указанную объектом Region. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_26) | Заполняет эллипс. |
| [fill_path(pen, brush, path)](#fill_path_pen_brush_path_27) | Заполняет путь. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_28) | Заполняет сектор. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_29) | Заполняет многоугольник. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_30) | Заполняет многоугольник. |
| [fill_rectangle(brush, rectangle)](#fill_rectangle_brush_rectangle_31) | Заполняет прямоугольник. |
| [from_emf_image(emf_image)](#from_emf_image_emf_image_32) | Получает экземпляр [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/), содержащий все записи из изображения Emf. |
| [get_transform()](#get_transform__33) | Получает мировое преобразование. |
| [intersect_clip(rect)](#intersect_clip_rect_34) | Обновляет область отсечения этого Graphics до пересечения текущей области отсечения и указанной структуры Rectangle. |
| [intersect_clip(region)](#intersect_clip_region_35) | Обновляет область отсечения этого Graphics до пересечения текущей области отсечения и указанного объекта Region. |
| [intersect_clip_rect_f(rect)](#intersect_clip_rect_f_rect_36) | Обновляет область отсечения этого Graphics до пересечения текущей области отсечения и указанной структуры Rectangle. |
| [intersect_clip_rgn(region)](#intersect_clip_rgn_region_37) | Обновляет область отсечения этого Graphics до пересечения текущей области отсечения и указанного объекта Region. |
| [multiply_transform(matrix)](#multiply_transform_matrix_38) | Умножает мировое преобразование этого Graphics на указанный Matrix. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_39) | Умножает мировое преобразование этого Graphics на указанный Matrix в указанном порядке. |
| reset_clip() | Сбрасывает обрезку. |
| [rotate_transform(angle)](#rotate_transform_angle_40) | Применяет указанное вращение к матрице преобразования этого Graphics. |
| [rotate_transform(angle, center, order)](#rotate_transform_angle_center_order_41) | Применяет указанное вращение к матрице преобразования этого Graphics в указанном порядке. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_42) | Применяет указанную операцию масштабирования к матрице преобразования этого Graphics, предваряя её матрицей преобразования объекта. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_43) | Применяет указанную операцию масштабирования к матрице преобразования этого Graphics в указанном порядке. |
| [set_transform(transform)](#set_transform_transform_44) | Устанавливает преобразование. |
| [translate_transform(x, y)](#translate_transform_x_y_45) | Изменяет начало координат, предваряя указанное перемещение матрицей преобразования этого Graphics. |
| [translate_transform(x, y, order)](#translate_transform_x_y_order_46) | Изменяет начало координат, применяя указанное перемещение к матрице преобразования этого Graphics в указанном порядке. |


### Constructor: EmfRecorderGraphics2D(frame, device_size, device_size_mm) {#EmfRecorderGraphics2D_frame_device_size_device_size_mm_1}


```
 EmfRecorderGraphics2D(frame, device_size, device_size_mm) 
```

Инициализирует новый экземпляр класса [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| frame | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Кадр. |
| device_size | [Size](/imaging/python-net/aspose.imaging/size/) | Размер устройства. |
| device_size_mm | [Size](/imaging/python-net/aspose.imaging/size/) | Размер устройства в мм. |


**See also:**

**[Example # 1](#example_174)**: This example shows how to create a EMF image and draw some geometric shapes o...


### Method: draw_arc(pen, rect, start_angle, arc_angle) {#draw_arc_pen_rect_start_angle_arc_angle_1}


```
 draw_arc(pen, rect, start_angle, arc_angle) 
```

Рисует дугу, представляющую часть эллипса, заданного структурой Rectangle.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Карандаш, определяющий цвет, ширину и стиль фигуры. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Границы эллипса. |
| start_angle | float | Угол в градусах, измеренный по часовой стрелке от оси x до начальной точки дуги. |
| arc_angle | float | Угол в градусах, измеряемый по часовой стрелке от параметра startAngle до конечной точки дуги. |

### Method: draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) {#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2}


```
 draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) 
```

Рисует кубический безье.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Карандаш, определяющий цвет, ширину и стиль фигуры. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | Начальная точка кривой. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | Первая управляющая точка кривой. |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | Вторая управляющая точка кривой. |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | Конечная точка кривой. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_3}


```
 draw_ellipse(pen, rect) 
```

Рисует эллипс.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Карандаш, определяющий цвет, ширину и стиль фигуры. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Границы эллипса. |

### Method: draw_image(image, dest_rect, src_rect, src_unit) {#draw_image_image_dest_rect_src_rect_src_unit_4}


```
 draw_image(image, dest_rect, src_rect, src_unit) 
```

Рисует указанную часть указанного изображения в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Изображение для отрисовки. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура Rectangle, указывающая расположение и размер отрисованного изображения. Изображение масштабируется, чтобы соответствовать прямоугольнику. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура Rectangle, указывающая часть объекта изображения для отрисовки. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Единицы измерения, используемые параметром srcRect. |

### Method: draw_image(image, location) {#draw_image_image_location_5}


```
 draw_image(image, location) 
```

Отрисовывает указанное изображение, используя его оригинальный физический размер, в указанном месте.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Изображение для отрисовки. |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | Расположение верхнего левого угла отрисованного изображения. |

### Method: draw_image(image_bytes, dest_rect, src_unit) {#draw_image_image_bytes_dest_rect_src_unit_6}


```
 draw_image(image_bytes, dest_rect, src_unit) 
```

Отрисовывает изображение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_bytes | System.Byte | Байты изображения. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник назначения. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Исходный блок. |

### Method: draw_image(stream, dest_rect, src_unit) {#draw_image_stream_dest_rect_src_unit_7}


```
 draw_image(stream, dest_rect, src_unit) 
```

Отрисовывает изображение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник назначения. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Исходный блок. |

### Method: draw_image_from_bytes(image_bytes, dest_rect, src_unit) {#draw_image_from_bytes_image_bytes_dest_rect_src_unit_8}


```
 draw_image_from_bytes(image_bytes, dest_rect, src_unit) 
```

Отрисовывает изображение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_bytes | System.Byte | Байты изображения. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник назначения. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Исходный блок. |

### Method: draw_image_from_stream(stream, dest_rect, src_unit) {#draw_image_from_stream_stream_dest_rect_src_unit_9}


```
 draw_image_from_stream(stream, dest_rect, src_unit) 
```

Отрисовывает изображение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник назначения. |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Исходный блок. |

### Method: draw_line(pen, pt1, pt2) {#draw_line_pen_pt1_pt2_10}


```
 draw_line(pen, pt1, pt2) 
```

Отрисовывает линию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Карандаш, определяющий цвет, ширину и стиль фигуры. |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | Первая точка. |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | Вторая точка. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_11}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Отрисовывает линию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Карандаш, определяющий цвет, ширину и стиль фигуры. |
| x1 | int | Координата x первой точки. |
| y1 | int | Координата y первой точки. |
| x2 | int | Координата x второй точки. |
| y2 | int | Координата y второй точки. |

### Method: draw_path(pen, path) {#draw_path_pen_path_12}


```
 draw_path(pen, path) 
```

Отрисовывает путь.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Карандаш, определяющий цвет, ширину и стиль фигуры. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Путь для отрисовки. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_13}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Отрисовывает сектор.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Карандаш, определяющий цвет, ширину и стиль фигуры. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Границы эллипса. |
| start_angle | float | Угол в градусах, измеренный по часовой стрелке от оси x до начальной точки дуги. |
| sweep_angle | float | Угол в градусах, измеряемый по часовой стрелке от параметра startAngle до конечной точки дуги. |

### Method: draw_poly_cubic_bezier(pen, points) {#draw_poly_cubic_bezier_pen_points_14}


```
 draw_poly_cubic_bezier(pen, points) 
```

Отрисовывает поликубический Безье.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Карандаш, определяющий цвет, ширину и стиль фигуры. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Точки. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_15}


```
 draw_polygon(pen, points) 
```

Отрисовывает многоугольник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Карандаш, определяющий цвет, ширину и стиль фигуры. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Точки. |

### Method: draw_polyline(pen, points) {#draw_polyline_pen_points_16}


```
 draw_polyline(pen, points) 
```

Отрисовывает полилинию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Карандаш, определяющий цвет, ширину и стиль фигуры. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Точки. |

### Method: draw_rectangle(pen, rectangle) {#draw_rectangle_pen_rectangle_17}


```
 draw_rectangle(pen, rectangle) 
```

Отрисовывает прямоугольник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Карандаш, определяющий цвет, ширину и стиль фигуры. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник для отрисовки. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_18}


```
 draw_rectangle(pen, x, y, width, height) 
```

Отрисовывает прямоугольник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Карандаш, определяющий цвет, ширину и стиль фигуры. |
| x | int | Координата x левого верхнего угла прямоугольника для рисования. |
| y | int | Координата y левого верхнего угла прямоугольника для рисования. |
| width | int | Ширина прямоугольника для рисования. |
| height | int | Высота прямоугольника для рисования. |

### Method: draw_string(string, font, color, x, y) {#draw_string_string_font_color_x_y_19}


```
 draw_string(string, font, color, x, y) 
```

Отрисовывает строку.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| string | string | Строка. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Шрифт, определяющий формат текста строки. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Цвет текста. |
| x | int | Координата x верхнего левого угла нарисованного текста. |
| y | int | Координата y верхнего левого угла нарисованного текста. |

### Method: draw_string(string, font, color, x, y, angle) {#draw_string_string_font_color_x_y_angle_20}


```
 draw_string(string, font, color, x, y, angle) 
```

Отрисовывает строку.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| string | string | Строка. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Шрифт, определяющий формат текста строки. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Цвет текста. |
| x | int | Координата x верхнего левого угла нарисованного текста. |
| y | int | Координата y верхнего левого угла нарисованного текста. |
| угол | float | Угол в градусах между вектором наклона и осью X устройства. <br/>            Вектор наклона параллелен базовой линии строки текста. |

### Method: end_recording() {#end_recording__21}


```
 end_recording() 
```

Завершает запись.

**Returns**

| Тип | Описание |
| :- | :- |
| [EmfImage](/imaging/python-net/aspose.imaging.fileformats.emf/emfimage/) | Полученное изображение. |


### Method: exclude_clip(rect) {#exclude_clip_rect_22}


```
 exclude_clip(rect) 
```

Обновляет область отсечения этого Graphics, исключая область, указанную структурой Rectangle.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура прямоугольника, указывающая прямоугольник, исключаемый из области отсечения. |

### Method: exclude_clip(region) {#exclude_clip_region_23}


```
 exclude_clip(region) 
```

Обновляет область отсечения этого Graphics, исключая область, указанную объектом Region.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Область, указывающая регион, исключаемый из области отсечения. |

### Method: exclude_clip_rect(rect) {#exclude_clip_rect_rect_24}


```
 exclude_clip_rect(rect) 
```

Обновляет область отсечения этого Graphics, исключая область, указанную структурой Rectangle.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура прямоугольника, указывающая прямоугольник, исключаемый из области отсечения. |

### Method: exclude_clip_rgn(region) {#exclude_clip_rgn_region_25}


```
 exclude_clip_rgn(region) 
```

Обновляет область отсечения этого Graphics, исключая область, указанную объектом Region.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Область, указывающая регион, исключаемый из области отсечения. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_26}


```
 fill_ellipse(brush, rect) 
```

Заполняет эллипс.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Кисть, определяющая характеристики заливки. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Границы эллипса. |

### Method: fill_path(pen, brush, path) {#fill_path_pen_brush_path_27}


```
 fill_path(pen, brush, path) 
```

Заполняет путь.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Карандаш, определяющий цвет, ширину и стиль фигуры. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Кисть, определяющая характеристики заливки. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Путь для заливки. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_28}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Заполняет сектор.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Кисть, определяющая характеристики заливки. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Границы эллипса. |
| start_angle | float | Угол в градусах, измеренный по часовой стрелке от оси x до начальной точки дуги. |
| sweep_angle | float | Угол в градусах, измеряемый по часовой стрелке от параметра startAngle до конечной точки дуги. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_29}


```
 fill_polygon(brush, points) 
```

Заполняет многоугольник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Кисть, определяющая характеристики заливки. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Точки. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_30}


```
 fill_polygon(brush, points, fill_mode) 
```

Заполняет многоугольник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Кисть, определяющая характеристики заливки. |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Точки. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Режим заливки. |

### Method: fill_rectangle(brush, rectangle) {#fill_rectangle_brush_rectangle_31}


```
 fill_rectangle(brush, rectangle) 
```

Заполняет прямоугольник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Кисть, определяющая характеристики заливки. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник для заливки. |

### Method: from_emf_image(emf_image)  [static] {#from_emf_image_emf_image_32}


```
 from_emf_image(emf_image) 
```

Получает экземпляр [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/), содержащий все записи из изображения Emf.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| emf_image | [EmfImage](/imaging/python-net/aspose.imaging.fileformats.emf/emfimage/) | Изображение Emf, из которого читать записи. |

**Returns**

| Тип | Описание |
| :- | :- |
| [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) | Экземпляр [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) |


### Method: get_transform() {#get_transform__33}


```
 get_transform() 
```

Получает мировое преобразование.

**Returns**

| Тип | Описание |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Матрица преобразования. |


### Method: intersect_clip(rect) {#intersect_clip_rect_34}


```
 intersect_clip(rect) 
```

Обновляет область отсечения этого Graphics до пересечения текущей области отсечения и указанной структуры Rectangle.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура прямоугольника для пересечения с текущей областью отсечения. |

### Method: intersect_clip(region) {#intersect_clip_region_35}


```
 intersect_clip(region) 
```

Обновляет область отсечения этого Graphics до пересечения текущей области отсечения и указанного объекта Region.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Область для пересечения с текущей областью. |

### Method: intersect_clip_rect_f(rect) {#intersect_clip_rect_f_rect_36}


```
 intersect_clip_rect_f(rect) 
```

Обновляет область отсечения этого Graphics до пересечения текущей области отсечения и указанной структуры Rectangle.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура прямоугольника для пересечения с текущей областью отсечения. |

### Method: intersect_clip_rgn(region) {#intersect_clip_rgn_region_37}


```
 intersect_clip_rgn(region) 
```

Обновляет область отсечения этого Graphics до пересечения текущей области отсечения и указанного объекта Region.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Область для пересечения с текущей областью. |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_38}


```
 multiply_transform(matrix) 
```

Умножает мировое преобразование этого Graphics на указанный Matrix.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Матрица, умножающая мировое преобразование. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_39}


```
 multiply_transform(matrix, order) 
```

Умножает мировое преобразование этого Graphics на указанный Matrix в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Матрица, умножающая мировое преобразование. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Порядок умножения. |

### Method: rotate_transform(angle) {#rotate_transform_angle_40}


```
 rotate_transform(angle) 
```

Применяет указанное вращение к матрице преобразования этого Graphics.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол вращения в градусах. |

### Method: rotate_transform(angle, center, order) {#rotate_transform_angle_center_order_41}


```
 rotate_transform(angle, center, order) 
```

Применяет указанное вращение к матрице преобразования этого Graphics в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол вращения в градусах. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Центр вращения. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Указывает, добавляется ли вращение к матричной трансформации в конец или в начало.. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_42}


```
 scale_transform(sx, sy) 
```

Применяет указанную операцию масштабирования к матрице преобразования этого Graphics, предваряя её матрицей преобразования объекта.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| sx | float | Коэффициент масштабирования по оси x. |
| sy | float | Коэффициент масштабирования по оси y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_43}


```
 scale_transform(sx, sy, order) 
```

Применяет указанную операцию масштабирования к матрице преобразования этого Graphics в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| sx | float | Коэффициент масштабирования по оси x. |
| sy | float | Коэффициент масштабирования по оси y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Указывает, добавляется ли операция масштабирования к матрице преобразования в начало или в конец. |

### Method: set_transform(transform) {#set_transform_transform_44}


```
 set_transform(transform) 
```

Устанавливает преобразование.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Новая матрица преобразования. |

### Method: translate_transform(x, y) {#translate_transform_x_y_45}


```
 translate_transform(x, y) 
```

Изменяет начало координат, предваряя указанное перемещение матрицей преобразования этого Graphics.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x трансляции. |
| y | float | Координата y трансляции. |

### Method: translate_transform(x, y, order) {#translate_transform_x_y_order_46}


```
 translate_transform(x, y, order) 
```

Изменяет начало координат, применяя указанное перемещение к матрице преобразования этого Graphics в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x трансляции. |
| y | float | Координата y трансляции. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Указывает, добавляется ли трансляция к матрице преобразования в начало или в конец. |

## **Examples**
### This example shows how to create a EMF image and draw some geometric shapes on it using EmfRecorderGraphics2D. {#example_174}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Rectangle, Pen, Color, Point, Image, RasterImage, GraphicsUnit, Font, FontStyle, Figure, GraphicsPath,\
	PointF, RectangleF, Size
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.shapes import ArcShape, BezierShape, PolygonShape, RectangleShape
from aspose.imaging.imageoptions import SvgRasterizationOptions, PngOptions
from aspose.imaging.fileformats.emf.graphics import EmfRecorderGraphics2D
from os.path import join

dir_: str = "c:\\temp"
# Размер изображения в пикселях
device_width: int = 600
device_height: int = 400
# Размер изображения в миллиметрах
device_width_mm = device_width // 100
device_height_mm = device_height // 100
frame = Rectangle(0, 0, device_width, device_height)
# Создать изображение EMF.
graphics = EmfRecorderGraphics2D(frame, Size(device_width, device_height), Size(device_width_mm, device_height_mm))
# Нарисовать черный прямоугольник вдоль границ изображения с использованием черного пера шириной 1 пиксель.
graphics.draw_rectangle(Pen(Color.black, 1), 0, 0, device_width, device_height)
# Заполнить прямоугольник цветом white-smoke.
graphics.fill_rectangle(SolidBrush(Color.white_smoke), Rectangle(10, 10, 580, 380))
# Нарисовать две диагональные линии с использованием пера darkgreen шириной 1 пиксель.
graphics.draw_line(Pen(Color.dark_green, 1), 0, 0, device_width, device_height)
graphics.draw_line(Pen(Color.dark_green, 1), 0, device_height, device_width, 0)
# Нарисовать дугу внутри прямоугольника {0, 0, 200, 200} с использованием синего пера шириной 2 пикселя.
graphics.draw_arc(Pen(Color.blue, 2), Rectangle(0, 0, 200, 200), 90, 270)
# Заполнить дугу
graphics.fill_pie(SolidBrush(Color.light_sky_blue), Rectangle(0, 0, 150, 150), 90, 270)
# Нарисовать кубический безье с использованием красного пера шириной 2 пикселя.
graphics.draw_cubic_bezier(Pen(Color.red, 2), Point(0, 0), Point(200, 133), Point(400, 166), Point(600, 400))

# Нарисовать растровое изображение заданного размера в указанном месте.
# Изображение масштабируется, чтобы соответствовать требуемому прямоугольнику.
with aspycore.as_of(Image.load(join(dir_, "sample.bmp")), RasterImage) as image_to_draw:
	graphics.draw_image(image_to_draw, Rectangle(400, 200, 100, 50), Rectangle(0, 0, device_width, device_height), GraphicsUnit.PIXEL)

# Нарисовать строку текста
graphics.draw_string("Hello World!", Font("Arial", 48, FontStyle.REGULAR), Color.dark_red, 200, 300)

# Создать путь для заполнения
figure_to_fill = Figure()
figure_to_fill.is_closed = True
path_to_fill = GraphicsPath()
path_to_fill.add_figure(figure_to_fill)
figure_to_fill.add_shapes([ArcShape(Rectangle(400, 0, 200, 100), 45, 300), BezierShape([PointF(300, 200), PointF(400, 200), PointF(500, 100), PointF(600, 200)]), PolygonShape([PointF(300, 100)]), RectangleShape(RectangleF(0, 100, 200, 200))])

# Заполнить путь, используя желтую кисть и зеленое перо для обводки
graphics.fill_path(Pen(Color.green, 2), SolidBrushColor.yellow), path_to_fill)

# Создать путь для рисования
path_to_draw = GraphicsPath()
figure_to_draw = Figure()
path_to_draw.add_figure(figure_to_draw)
figure_to_draw.add_shapes([ArcShape(RectangleF(200, 200, 200, 200), 0, 360)])

# Нарисовать путь с использованием оранжевого пера шириной 5 пикселей.
graphics.draw_path(Pen(Color.orange, 5), path_to_draw)

# Получить окончательное изображение WMF, включающее все команды рисования
with graphics.end_recording() as emf_image:
	emf_image.save(join(dir_, "test.output.emf"))


```

