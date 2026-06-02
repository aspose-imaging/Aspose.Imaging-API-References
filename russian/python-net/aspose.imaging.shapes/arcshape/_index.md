---
title: "Класс ArcShape"
type: docs
weight: 10
url: /ru/python-net/aspose.imaging.shapes/arcshape/
---

**Summary:** Represents an arc shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.ArcShape

**Inheritance:** IOrderedShape, PieShape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ArcShape()](#ArcShape__1) | Инициализирует новый экземпляр класса [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/). |
| [ArcShape(rectangle, start_angle, sweep_angle)](#ArcShape_rectangle_start_angle_sweep_angle_2) | Инициализирует новый экземпляр класса [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/). |
| [ArcShape(rectangle, start_angle, sweep_angle, is_closed)](#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3) | Инициализирует новый экземпляр класса [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Получает границы объекта. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Возвращает центр фигуры. |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Получает конечную точку фигуры. |
| has_segments | bool | r | Возвращает значение, указывающее, имеет ли фигура сегменты. |
| is_closed | bool | r/w | Получает или задает значение, указывающее, закрыта ли упорядоченная фигура. При обработке закрытой упорядоченной фигуры начальная и конечная точки не имеют значения. |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Возвращает левую нижнюю точку прямоугольника. |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Возвращает левую верхнюю точку прямоугольника. |
| rectangle_height | float | r | Возвращает высоту прямоугольника. |
| rectangle_width | float | r | Возвращает ширину прямоугольника. |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Возвращает правую нижнюю точку прямоугольника. |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Возвращает правую верхнюю точку прямоугольника. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Возвращает сегменты фигуры. |
| start_angle | float | r/w | Получает или задает начальный угол. |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Получает начальную точку фигуры. |
| sweep_angle | float | r/w | Получает или задает угол разворота. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Получает границы объекта. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Получает границы объекта. |
| reverse() | Изменяет порядок точек этой фигуры на обратный. |
| [transform(transform)](#transform_transform_3) | Применяет указанное преобразование к форме. |


### Constructor: ArcShape() {#ArcShape__1}


```
 ArcShape() 
```

Инициализирует новый экземпляр класса [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/).

### Constructor: ArcShape(rectangle, start_angle, sweep_angle) {#ArcShape_rectangle_start_angle_sweep_angle_2}


```
 ArcShape(rectangle, start_angle, sweep_angle) 
```

Инициализирует новый экземпляр класса [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Прямоугольник. |
| start_angle | float | Начальный угол. |
| sweep_angle | float | Угол разворота. |


**See also:**

**[Example # 1](#example_16)**: This example creates a new Image and draws a variety of shapes using figures ...


### Constructor: ArcShape(rectangle, start_angle, sweep_angle, is_closed) {#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3}


```
 ArcShape(rectangle, start_angle, sweep_angle, is_closed) 
```

Инициализирует новый экземпляр класса [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Прямоугольник. |
| start_angle | float | Начальный угол. |
| sweep_angle | float | Угол разворота. |
| is_closed | bool | Если установить значение <c>true</c>, дуга замкнута. Замкнутая дуга фактически вырождается в эллипс. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

Получает границы объекта.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Матрица, применяемая перед вычислением границ. |

**Returns**

| Тип | Описание |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Оценочные границы объекта. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

Получает границы объекта.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Матрица, применяемая перед вычислением границ. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ручка, используемая для объекта. Это может влиять на размер границ объекта. |

**Returns**

| Тип | Описание |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Оценочные границы объекта. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Применяет указанное преобразование к форме.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Преобразование для применения. |

## **Examples**
### This example creates a new Image and draws a variety of shapes using figures and `GraphicsPath` on the `Image` surface {#example_16}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, Rectangle, Size
from aspose.imaging import Point, PointF, Pen
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource
from aspose.imaging.shapes import EllipseShape, PieShape, ArcShape, PolygonShape, RectangleShape
from os.path import join as path_join

#Создаёт экземпляр BmpOptions и устанавливает его различные свойства
with BmpOptions() as bmpOptions:
	bmpOptions.bits_per_pixel = 24
	#Создайте экземпляр FileCreateSource и назначьте его в качестве Source для экземпляра BmpOptions
	#Второй параметр типа Boolean определяет, будет ли создаваемый файл IsTemporal или нет
	bmpOptions.source = FileCreateSource(r"c:\temp\output.bmp", False)
	#Создайте экземпляр Image
	with Image.create(bmpOptions, 500, 500) as image:
		# Создайте и инициализируйте экземпляр класса Graphics.
		graphics = Graphics(image)
		# Очистить поверхность Graphics.
		graphics.clear(Color.wheat)
		# Создайте экземпляр класса GraphicsPath
		graphicspath = GraphicsPath()
		#Создайте экземпляр класса Figure
		figure1 = Figure()
		# Добавьте Shape в объект Figure
		figure1.add_shape(EllipseShape(RectangleF(50, 50, 300, 300)))
		figure1.add_shape(PieShape(Rectangle(Point(110, 110), Size(200, 200)), 0, 90))
		# Создайте экземпляр класса Figure
		figure2 = Figure()
		# Добавьте Shape в объект Figure
		figure2.add_shape(ArcShape(RectangleF(10, 10, 300, 300), 0, 45))
		figure2.add_shape(
			PolygonShape([PointF(150, 10), PointF(150, 200), PointF(250, 300), PointF(350, 400)], True))
		figure2.add_shape(RectangleShape(RectangleF(Point(250, 250), Size(200, 200))))
		# Добавьте объект Figure в GraphicsPath
		graphicspath.add_figures([figure1, figure2])
		# Нарисуйте путь с объектом Pen цвета Black
		graphics.draw_path(Pen(Color.black, 2.0), graphicspath)
		# Сохраните все изменения.
		image.save()


```

