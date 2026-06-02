---
title: "Класс EllipseShape"
type: docs
weight: 40
url: /ru/python-net/aspose.imaging.shapes/ellipseshape/
---

**Summary:** Represents an ellipse shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.EllipseShape

**Inheritance:** RectangleShape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EllipseShape()](#EllipseShape__1) | Инициализирует новый экземпляр класса [EllipseShape](/imaging/python-net/aspose.imaging.shapes/ellipseshape/). |
| [EllipseShape(rectangle)](#EllipseShape_rectangle_2) | Инициализирует новый экземпляр класса [EllipseShape](/imaging/python-net/aspose.imaging.shapes/ellipseshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Получает границы объекта. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Возвращает центр фигуры. |
| has_segments | bool | r | Возвращает значение, указывающее, имеет ли фигура сегменты. |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Возвращает левую нижнюю точку прямоугольника. |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Возвращает левую верхнюю точку прямоугольника. |
| rectangle_height | float | r | Возвращает высоту прямоугольника. |
| rectangle_width | float | r | Возвращает ширину прямоугольника. |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Возвращает правую нижнюю точку прямоугольника. |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Возвращает правую верхнюю точку прямоугольника. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Возвращает сегменты фигуры. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Получает границы объекта. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Получает границы объекта. |
| [transform(transform)](#transform_transform_3) | Применяет указанное преобразование к форме. |


### Constructor: EllipseShape() {#EllipseShape__1}


```
 EllipseShape() 
```

Инициализирует новый экземпляр класса [EllipseShape](/imaging/python-net/aspose.imaging.shapes/ellipseshape/).

### Constructor: EllipseShape(rectangle) {#EllipseShape_rectangle_2}


```
 EllipseShape(rectangle) 
```

Инициализирует новый экземпляр класса [EllipseShape](/imaging/python-net/aspose.imaging.shapes/ellipseshape/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Прямоугольник. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


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
### This examples make use of GraphicsPath and Graphics classes to create and manipulate figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end `draw_path` method exposed by Graphics class is called to render the paths on surface. {#example_13}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, PointF, SizeF
from aspose.imaging import Pen
from aspose.imaging.sources import StreamSource
from aspose.imaging.imageoptions import TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from aspose.imaging.shapes import RectangleShape, EllipseShape, PieShape


# Создайте экземпляр файлового потока
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# Создайте экземпляр TiffOptions и установите его различные свойства
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Установите источник для экземпляра ImageOptions
	tiffOptions.source = StreamSource(stream)
	# Создайте экземпляр Image
	with Image.create(tiffOptions, 500, 500) as image:
		# Создайте и инициализируйте экземпляр класса Graphics.
		graphics = Graphics(image)
		# Очистить поверхность Graphics.
		graphics.clear(Color.wheat);
		# Создайте экземпляр класса GraphicsPath
		graphics_path = GraphicsPath()
		# Создайте экземпляр класса Figure
		figure = Figure()
		# Добавьте формы в объект Figure
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# Добавьте объект Figure в GraphicsPath
		graphics_path.add_figure(figure)
		# Нарисуйте путь с объектом Pen цвета Black
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# Сохраните все изменения.
		image.save()


```

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

