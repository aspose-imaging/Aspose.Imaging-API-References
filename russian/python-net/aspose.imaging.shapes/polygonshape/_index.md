---
title: "Класс PolygonShape"
type: docs
weight: 60
url: /ru/python-net/aspose.imaging.shapes/polygonshape/
---

**Summary:** Represents a polygon shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.PolygonShape

**Inheritance:** IOrderedShape, Shape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PolygonShape()](#PolygonShape__1) | Инициализирует новый экземпляр класса [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/). |
| [PolygonShape(points)](#PolygonShape_points_2) | Инициализирует новый экземпляр класса [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/). |
| [PolygonShape(points, is_closed)](#PolygonShape_points_is_closed_3) | Инициализирует новый экземпляр класса [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Получает границы объекта. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Возвращает центр фигуры. |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Получает конечную точку фигуры. |
| has_segments | bool | r | Возвращает значение, указывающее, имеет ли фигура сегменты. |
| is_closed | bool | r/w | Получает или задает значение, указывающее, закрыта ли фигура. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Получает или задает точки кривой. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Возвращает сегменты фигуры. |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Получает начальную точку фигуры. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Получает границы объекта. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Получает границы объекта. |
| reverse() | Изменяет порядок точек этой фигуры на обратный. |
| [transform(transform)](#transform_transform_3) | Применяет указанное преобразование к форме. |


### Constructor: PolygonShape() {#PolygonShape__1}


```
 PolygonShape() 
```

Инициализирует новый экземпляр класса [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/).

### Constructor: PolygonShape(points) {#PolygonShape_points_2}


```
 PolygonShape(points) 
```

Инициализирует новый экземпляр класса [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив точек. |

### Constructor: PolygonShape(points, is_closed) {#PolygonShape_points_is_closed_3}


```
 PolygonShape(points, is_closed) 
```

Инициализирует новый экземпляр класса [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив точек. |
| is_closed | bool | Если установлено в <c>true</c>, полигон закрыт. |

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

