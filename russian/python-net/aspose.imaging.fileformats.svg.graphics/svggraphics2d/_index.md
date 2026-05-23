---
title: "Класс SvgGraphics2D"
type: docs
weight: 10
url: /ru/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/
---

**Summary:** Provides drawing commmands to compose an Svg image.

**Module:** [aspose.imaging.fileformats.svg.graphics](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/)

**Full Name:** aspose.imaging.fileformats.svg.graphics.SvgGraphics2D

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SvgGraphics2D(image)](#SvgGraphics2D_image_1) | Инициализирует новый экземпляр класса [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/). |
| [SvgGraphics2D(width, height, dpi)](#SvgGraphics2D_width_height_dpi_2) | Инициализирует новый экземпляр класса [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [draw_arc(pen, rect, start_angle, arc_angle)](#draw_arc_pen_rect_start_angle_arc_angle_1) | Рисует дугу, представляющую часть эллипса, заданного структурой Rectangle. |
| [draw_cubic_bezier(pen, pt1, pt2, pt3, pt4)](#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2) | Рисует кубический безье. |
| [draw_image(image, origin)](#draw_image_image_origin_3) | Рисует указанное изображение в указанном месте. |
| [draw_image(image, origin, size)](#draw_image_image_origin_size_4) | Рисует указанное изображение заданного размера в указанном месте. |
| [draw_image(src_rect, dest_rect, image)](#draw_image_src_rect_dest_rect_image_5) | Рисует указанную часть указанного изображения в указанном месте и заданного размера. |
| [draw_image_point_size(image, origin, size)](#draw_image_point_size_image_origin_size_6) | Рисует указанное изображение заданного размера в указанном месте. |
| [draw_image_src_dst_rects(src_rect, dest_rect, image)](#draw_image_src_dst_rects_src_rect_dest_rect_image_7) | Рисует указанную часть указанного изображения в указанном месте и заданного размера. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_8) | Отрисовывает линию. |
| [draw_path(pen, path)](#draw_path_pen_path_9) | Отрисовывает путь. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_10) | Отрисовывает прямоугольник. |
| [draw_string(font, text, origin, text_color)](#draw_string_font_text_origin_text_color_11) | Рисует строку текста. |
| [end_recording()](#end_recording__12) | Получает окончательное изображение Svg, которое включает все команды рисования, выполненные через объект [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/). |
| [fill_arc(pen, brush, rect, start_angle, arc_angle)](#fill_arc_pen_brush_rect_start_angle_arc_angle_13) | Заполняет дугу, представляющую часть эллипса, указанную структурой Rectangle. |
| [fill_path(pen, brush, path)](#fill_path_pen_brush_path_14) | Заполняет путь. |
| [fill_rectangle(pen, brush, x, y, width, height)](#fill_rectangle_pen_brush_x_y_width_height_15) | Заполняет прямоугольник. |


### Constructor: SvgGraphics2D(image) {#SvgGraphics2D_image_1}


```
 SvgGraphics2D(image) 
```

Инициализирует новый экземпляр класса [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) | Изображение, на котором выполняются операции рисования. |

### Constructor: SvgGraphics2D(width, height, dpi) {#SvgGraphics2D_width_height_dpi_2}


```
 SvgGraphics2D(width, height, dpi) 
```

Инициализирует новый экземпляр класса [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| width | int | Ширина выходного изображения Svg. |
| height | int | Ширина выходного изображения Svg. |
| dpi | int | Разрешение устройства, например 96 точек на дюйм. |


**See also:**

**[Example # 1](#example_171)**: This example shows how to create an SVG image of the specified size and raste...


### Method: draw_arc(pen, rect, start_angle, arc_angle) {#draw_arc_pen_rect_start_angle_arc_angle_1}


```
 draw_arc(pen, rect, start_angle, arc_angle) 
```

Рисует дугу, представляющую часть эллипса, заданного структурой Rectangle.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Перо для рисования контура фигуры. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Границы эллипса. |
| start_angle | float | Угол в градусах, измеряемый по часовой стрелке от оси x до начальной точки дуги. |
| arc_angle | float | Угол в градусах, измеряемый по часовой стрелке от параметра startAngle до конечной точки дуги. |

### Method: draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) {#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2}


```
 draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) 
```

Рисует кубический безье.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Перо, определяющее цвет, ширину и стиль фигуры. |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Начальная точка кривой. |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Первая управляющая точка кривой. |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Вторая управляющая точка кривой. |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Конечная точка кривой. |

### Method: draw_image(image, origin) {#draw_image_image_origin_3}


```
 draw_image(image, origin) 
```

Рисует указанное изображение в указанном месте.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Отрисованное изображение. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | Расположение отрисованного изображения. |

### Method: draw_image(image, origin, size) {#draw_image_image_origin_size_4}


```
 draw_image(image, origin, size) 
```

Рисует указанное изображение заданного размера в указанном месте.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Отрисованное изображение. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | Расположение отрисованного изображения. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Желаемый размер отрисованного изображения. |

### Method: draw_image(src_rect, dest_rect, image) {#draw_image_src_rect_dest_rect_image_5}


```
 draw_image(src_rect, dest_rect, image) 
```

Рисует указанную часть указанного изображения в указанном месте и заданного размера.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Часть объекта изображения для отрисовки. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Расположение и размер отрисованного изображения. Изображение масштабируется, чтобы вписаться в прямоугольник. |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Изображение для отрисовки. |

### Method: draw_image_point_size(image, origin, size) {#draw_image_point_size_image_origin_size_6}


```
 draw_image_point_size(image, origin, size) 
```

Рисует указанное изображение заданного размера в указанном месте.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Отрисованное изображение. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | Расположение отрисованного изображения. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Желаемый размер отрисованного изображения. |

### Method: draw_image_src_dst_rects(src_rect, dest_rect, image) {#draw_image_src_dst_rects_src_rect_dest_rect_image_7}


```
 draw_image_src_dst_rects(src_rect, dest_rect, image) 
```

Рисует указанную часть указанного изображения в указанном месте и заданного размера.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Часть объекта изображения для отрисовки. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Расположение и размер отрисованного изображения. Изображение масштабируется, чтобы вписаться в прямоугольник. |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Изображение для отрисовки. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_8}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Отрисовывает линию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Перо, определяющее цвет, ширину и стиль фигуры. |
| x1 | int | Координата x первой точки. |
| y1 | int | Координата y первой точки. |
| x2 | int | Координата x второй точки. |
| y2 | int | Координата y второй точки. |

### Method: draw_path(pen, path) {#draw_path_pen_path_9}


```
 draw_path(pen, path) 
```

Отрисовывает путь.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Перо для рисования контура фигуры. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Путь для отрисовки. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_10}


```
 draw_rectangle(pen, x, y, width, height) 
```

Отрисовывает прямоугольник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Перо для рисования контура фигуры. |
| x | int | Координата x левого верхнего угла прямоугольника для рисования. |
| y | int | Координата y левого верхнего угла прямоугольника для рисования. |
| width | int | Ширина прямоугольника для рисования. |
| height | int | Высота прямоугольника для рисования. |

### Method: draw_string(font, text, origin, text_color) {#draw_string_font_text_origin_text_color_11}


```
 draw_string(font, text, origin, text_color) 
```

Рисует строку текста.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Шрифт, используемый для отображения текста. |
| text | string | Строка текста Unicode. |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | Верхний левый угол текстового фрагмента. |
| text_color | [Color](/imaging/python-net/aspose.imaging/color/) | Цвет текста. |

### Method: end_recording() {#end_recording__12}


```
 end_recording() 
```

Получает окончательное изображение Svg, которое включает все команды рисования, выполненные через объект [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/).

**Returns**

| Тип | Описание |
| :- | :- |
| [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) | Конечное изображение Svg. |


### Method: fill_arc(pen, brush, rect, start_angle, arc_angle) {#fill_arc_pen_brush_rect_start_angle_arc_angle_13}


```
 fill_arc(pen, brush, rect, start_angle, arc_angle) 
```

Заполняет дугу, представляющую часть эллипса, указанную структурой Rectangle.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Перо для рисования контура фигуры. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Кисть для заполнения внутренней части фигуры. |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Границы эллипса. |
| start_angle | float | Угол в градусах, измеряемый по часовой стрелке от оси x до начальной точки дуги. |
| arc_angle | float | Угол в градусах, измеряемый по часовой стрелке от параметра startAngle до конечной точки дуги. |

### Method: fill_path(pen, brush, path) {#fill_path_pen_brush_path_14}


```
 fill_path(pen, brush, path) 
```

Заполняет путь.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Перо для рисования контура фигуры. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Кисть для заполнения внутренней части фигуры. |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Путь для отрисовки. |

### Method: fill_rectangle(pen, brush, x, y, width, height) {#fill_rectangle_pen_brush_x_y_width_height_15}


```
 fill_rectangle(pen, brush, x, y, width, height) 
```

Заполняет прямоугольник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Перо для рисования контура фигуры. |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Кисть для заполнения внутренней части фигуры. |
| x | int | Координата x левого верхнего угла прямоугольника для рисования. |
| y | int | Координата y левого верхнего угла прямоугольника для рисования. |
| width | int | Ширина прямоугольника для рисования. |
| height | int | Высота прямоугольника для рисования. |

## **Examples**
### This example shows how to create an SVG image of the specified size and rasterize it to PNG. {#example_171}
``` python
from aspose.imaging.fileformats.svg.graphics import SvgGraphics2D
from aspose.imaging import Graphics, Color, Pen
from aspose.imaging.brushes import SolidBrush
from os.path import join

dir_: str = "c:\\temp"
image_width: int = 100
image_height: int = 100
dpi: int = 96
# Создайте SVG-изображение размером 100×100 пикселей.
graphics = SvgGraphics2D(image_width, image_height, dpi)
pen = Pen(Color.yellow, 10)
brush = SolidBrush(Color.red)
# Заполнить всё изображение красным.
# Нарисуйте желтый прямоугольник шириной 10px вдоль границ изображения.
graphics.fill_rectangle(pen, brush, 0, 0, image_width, image_height)
# Получите конечное изображение Svg, которое включает все команды рисования
with graphics.end_recording() as svg_image:
	svg_image.save(join(dir_, "test.output.svg"))


```

