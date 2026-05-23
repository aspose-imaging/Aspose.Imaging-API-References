---
title: "StreamSource Класс"
type: docs
weight: 40
url: /ru/python-net/aspose.imaging.sources/streamsource/
---

**Summary:** Represents a stream source.

**Module:** [aspose.imaging.sources](/imaging/python-net/aspose.imaging.sources/)

**Full Name:** aspose.imaging.sources.StreamSource

**Inheritance:** Source

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [StreamSource()](#StreamSource__1) | Инициализирует новый экземпляр класса [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/). |
| [StreamSource(stream)](#StreamSource_stream_2) | Инициализирует новый экземпляр класса [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/). |
| [StreamSource(stream, dispose_stream)](#StreamSource_stream_dispose_stream_3) | Инициализирует новый экземпляр класса [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| dispose_stream | bool | r | Возвращает значение, указывающее, следует ли освобождать поток каждый раз, когда освобождается контейнер. |
| поток | _io.BufferedRandom | r | Возвращает поток. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | Получает контейнер потока. |


### Constructor: StreamSource() {#StreamSource__1}


```
 StreamSource() 
```

Инициализирует новый экземпляр класса [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/).

### Constructor: StreamSource(stream) {#StreamSource_stream_2}


```
 StreamSource(stream) 
```

Инициализирует новый экземпляр класса [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток для открытия. |


**See also:**

**[Example # 1](#example_7)**: This example shows how to load a pixels information in an array of Color, man...


### Constructor: StreamSource(stream, dispose_stream) {#StreamSource_stream_dispose_stream_3}


```
 StreamSource(stream, dispose_stream) 
```

Инициализирует новый экземпляр класса [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток для открытия. |
| dispose_stream | bool | если установить в <c>true</c>, поток будет освобождён. |


**See also:**

**[Example # 1](#example_5)**: This example demonstrates the use of file stream to Create a new Image file (...


### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

Получает контейнер потока.

**Returns**

| Тип | Описание |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | контейнер потока. |


## **Examples**
### This example demonstrates the use of file stream to Create a new Image file (a JPEG type) {#example_5}
``` python

from aspose.imaging.imageoptions import JpegOptions
from aspose.imaging.sources import StreamSource

# Создаёт экземпляр JpegOptions и задаёт его различные свойства
with JpegOptions() as jpegOptions:
	# Создайте экземпляр потока
	with open(r"C:\temp\sample.jpeg", "w+b") as stream:
		#Определите свойство source для экземпляра JpegOptions
		#Второй логический параметр определяет, будет ли поток освобождён после выхода из области видимости
		jpegOptions.source = StreamSource(stream, True)
		#Создаёт экземпляр Image и вызывает метод Create, передавая JpegOptions в качестве параметра, чтобы инициализировать объект Image
		with Image.create(jpegOptions, 500, 500) as image:
			#выполнить обработку изображения.
			pass

```

### This example shows how to load a pixels information in an array of Color, manipulates the array and set it back to the image. To perform these operations, this example creates a new Image file (in GIF format) using MemoryStream object. {#example_7}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Color
from aspose.imaging.externsions import StreamExtensions as strm_ext
from aspose.imaging.imageoptions import GifOptions
from aspose.imaging.sources import StreamSource

# Создать экземпляр MemoryStream
with strm_ext.create_memory_stream() as stream:
	#Создайте экземпляр GifOptions и задайте его различные свойства, включая свойство Source
	with GifOptions() as gifOptions:
		gifOptions.source = StreamSource(stream)

		# Создайте экземпляр Image
		with as_of(Image.create(gifOptions, 500, 500), RasterImage) as image:
			# Получите пиксели изображения, указав область как границу изображения
			pixels = image.load_pixels(image.bounds)

			yellow_color = Color.yellow
			blue_color = Color.blue
			#Пройдитесь по массиву и задайте цвет альтернативных индексированных пикселей
			for index in range(pixel.length):
				if index % 2 == 0:
					#Установите цвет индексированного пикселя в желтый
					pixels[index] = yellow_color
				else:
					#Установите цвет индексированного пикселя в синий
					pixels[index] = blue_color

			#Примените изменения пикселей к изображению
			image.save_pixels(image.bounds, pixels)

			# Сохраните все изменения.
			image.save()

	# Запишите MemoryStream в файл
	stream.seek(0)
	with open(r"C:\temp\output.gif", "wb") as fileStream:
		fileStream.write(stream.read())
}

```

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

