---
title: "Класс Figure"
type: docs
weight: 4770
url: /ru/python-net/aspose.imaging/figure/
---

**Summary:** The figure. A container for shapes.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Figure

**Inheritance:** ObjectWithBounds

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Figure()](#Figure__1) | Инициализирует новый экземпляр [Figure](/imaging/python-net/aspose.imaging/figure/).<br/> Конструктор, необходимый для десериализации JSON. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Получает или задает границы объекта. |
| is_closed | bool | r/w | Получает или задает значение, указывающее, закрыта ли эта фигура. Закрытая фигура будет иметь значение только в случае, когда<br/> первая и последняя формы фигуры являются непрерывными формами. В таком случае первая точка первой формы будет<br/> соединена прямой линией с последней точкой последней формы. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Получает все сегменты фигуры. |
| shapes | [Shape[]](/imaging/python-net/aspose.imaging/shape/) | r | Получает формы. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_shape(shape)](#add_shape_shape_1) | Добавляет форму к фигуре. |
| [add_shapes(shapes)](#add_shapes_shapes_2) | Добавляет диапазон форм к фигуре. |
| [get_bounds(matrix)](#get_bounds_matrix_3) | Получает границы объекта. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | Получает границы объекта. |
| [remove_shape(shape)](#remove_shape_shape_5) | Удаляет форму из фигуры. |
| [remove_shapes(shapes)](#remove_shapes_shapes_6) | Удаляет диапазон форм из фигуры. |
| reverse() | Разворачивает порядок форм этой фигуры и порядок точек форм. |
| [transform(transform)](#transform_transform_7) | Применяет указанное преобразование к форме. |


### Constructor: Figure() {#Figure__1}


```
 Figure() 
```

Инициализирует новый экземпляр [Figure](/imaging/python-net/aspose.imaging/figure/).<br/> Конструктор, необходимый для десериализации JSON.

### Method: add_shape(shape) {#add_shape_shape_1}


```
 add_shape(shape) 
```

Добавляет форму к фигуре.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| shape | [Shape](/imaging/python-net/aspose.imaging/shape/) | Форма для добавления. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...

**[Example # 2](#example_16)**: This example creates a new Image and draws a variety of shapes using figures ...


### Method: add_shapes(shapes) {#add_shapes_shapes_2}


```
 add_shapes(shapes) 
```

Добавляет диапазон форм к фигуре.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| shapes | [Shape[]](/imaging/python-net/aspose.imaging/shape/) | Формы для добавления. |

### Method: get_bounds(matrix) {#get_bounds_matrix_3}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


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


### Method: remove_shape(shape) {#remove_shape_shape_5}


```
 remove_shape(shape) 
```

Удаляет форму из фигуры.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| shape | [Shape](/imaging/python-net/aspose.imaging/shape/) | Форма для удаления. |

### Method: remove_shapes(shapes) {#remove_shapes_shapes_6}


```
 remove_shapes(shapes) 
```

Удаляет диапазон форм из фигуры.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| shapes | [Shape[]](/imaging/python-net/aspose.imaging/shape/) | Диапазон форм для удаления. |

### Method: transform(transform) {#transform_transform_7}


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

