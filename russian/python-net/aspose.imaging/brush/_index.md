---
title: "Класс Brush"
type: docs
weight: 340
url: /ru/python-net/aspose.imaging/brush/
---

**Summary:** The base brush class.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Brush

**Inheritance:** DisposableObject

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| disposed | bool | r | Получает значение, указывающее, удалён ли этот экземпляр. |
| [opacity](#opacity1) | float | r/w | Получает или задает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видима, значение 1 означает, что кисть полностью непрозрачна. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Создает новый глубокий клон текущего [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Property: opacity {#opacity1}

Получает или задает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видима, значение 1 означает, что кисть полностью непрозрачна.

**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Создает новый глубокий клон текущего [Brush](/imaging/python-net/aspose.imaging/brush/).

**Returns**

| Тип | Описание |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Новый [Brush](/imaging/python-net/aspose.imaging/brush/), который является глубоким клоном этого экземпляра [Brush](/imaging/python-net/aspose.imaging/brush/). |


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

#Создает экземпляр файлового потока.
with open(r"C:\temp\output.png", "w+b") as stream:
	#Создайте экземпляр PngOptions и задайте его различные свойства.
	pngOptions = PngOptions()
	#Установите источник для PngOptions.
	pngOptions.source = StreamSource(stream)
	#Создайте экземпляр Image
	with Image.create(pngOptions, 500, 500) as image:
		#Создайте и инициализируйте экземпляр класса Graphics.
		graphics = Graphics(image)
		#Очистить поверхность Graphics.
		graphics.clear(Color.wheat);
		#Нарисуйте дугу, указав объект Pen с черным цветом, 
		#прямоугольник, окружающий дугу, начальный угол и угол разворота
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#Нарисуйте кривую Безье, указав объект Pen с синим цветом и координатные точки.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#Нарисуйте кривую, указав объект Pen, имеющий зелёный цвет, и массив точек
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#Нарисуйте эллипс, используя объект Pen и окружающий прямоугольник
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#Нарисуйте линию 
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#Нарисуйте сегмент пирога
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#Нарисуйте многоугольник, указав объект Pen, имеющий красный цвет, и массив точек
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#Нарисуйте прямоугольник
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#Создайте объект SolidBrush и задайте его различные свойства
		brush = SolidBrush()
		brush.color = Color.purple
		#Нарисуйте строку, используя объект SolidBrush и Font, в конкретной точке
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# Сохраните все изменения.
		image.save();

```

