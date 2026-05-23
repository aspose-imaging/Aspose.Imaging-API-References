---
title: "StreamSource Clase"
type: docs
weight: 40
url: /es/python-net/aspose.imaging.sources/streamsource/
---

**Summary:** Represents a stream source.

**Module:** [aspose.imaging.sources](/imaging/python-net/aspose.imaging.sources/)

**Full Name:** aspose.imaging.sources.StreamSource

**Inheritance:** Source

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [StreamSource()](#StreamSource__1) | Inicializa una nueva instancia de la clase [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/). |
| [StreamSource(stream)](#StreamSource_stream_2) | Inicializa una nueva instancia de la clase [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/). |
| [StreamSource(stream, dispose_stream)](#StreamSource_stream_dispose_stream_3) | Inicializa una nueva instancia de la clase [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| dispose_stream | bool | r | Obtiene un valor que indica si el flujo debe ser eliminado siempre que el contenedor se elimine. |
| flujo | _io.BufferedRandom | r | Obtiene el flujo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | Obtiene el contenedor de flujo. |


### Constructor: StreamSource() {#StreamSource__1}


```
 StreamSource() 
```

Inicializa una nueva instancia de la clase [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/).

### Constructor: StreamSource(stream) {#StreamSource_stream_2}


```
 StreamSource(stream) 
```

Inicializa una nueva instancia de la clase [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo a abrir. |


**See also:**

**[Example # 1](#example_7)**: This example shows how to load a pixels information in an array of Color, man...


### Constructor: StreamSource(stream, dispose_stream) {#StreamSource_stream_dispose_stream_3}


```
 StreamSource(stream, dispose_stream) 
```

Inicializa una nueva instancia de la clase [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo a abrir. |
| dispose_stream | bool | Si se establece en <c>true</c> el flujo será eliminado. |


**See also:**

**[Example # 1](#example_5)**: This example demonstrates the use of file stream to Create a new Image file (...


### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

Obtiene el contenedor de flujo.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | el contenedor de flujo. |


## **Examples**
### This example demonstrates the use of file stream to Create a new Image file (a JPEG type) {#example_5}
``` python

from aspose.imaging.imageoptions import JpegOptions
from aspose.imaging.sources import StreamSource

# Crea una instancia de JpegOptions y establece sus diversas propiedades
with JpegOptions() as jpegOptions:
	# Crea una instancia de stream
	with open(r"C:\temp\sample.jpeg", "w+b") as stream:
		#Define la propiedad source para la instancia de JpegOptions
		#El segundo parámetro booleano determina si el Stream se elimina una vez que sale del alcance
		jpegOptions.source = StreamSource(stream, True)
		#Crea una instancia de Image y llama al método Create con JpegOptions como parámetro para inicializar el objeto Image
		with Image.create(jpegOptions, 500, 500) as image:
			#realiza algún procesamiento de imagen
			pass

```

### This example shows how to load a pixels information in an array of Color, manipulates the array and set it back to the image. To perform these operations, this example creates a new Image file (in GIF format) using MemoryStream object. {#example_7}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Color
from aspose.imaging.externsions import StreamExtensions as strm_ext
from aspose.imaging.imageoptions import GifOptions
from aspose.imaging.sources import StreamSource

# Crea una instancia de MemoryStream
with strm_ext.create_memory_stream() as stream:
	#Crea una instancia de GifOptions y establece sus diversas propiedades, incluida la propiedad Source
	with GifOptions() as gifOptions:
		gifOptions.source = StreamSource(stream)

		# Cree una instancia de Image
		with as_of(Image.create(gifOptions, 500, 500), RasterImage) as image:
			# Obtén los píxeles de la imagen especificando el área como límite de la imagen
			pixels = image.load_pixels(image.bounds)

			yellow_color = Color.yellow
			blue_color = Color.blue
			#Recorre la matriz y establece el color del píxel indexado alternativo
			for index in range(pixel.length):
				if index % 2 == 0:
					#Establece el color del píxel indexado a amarillo
					pixels[index] = yellow_color
				else:
					#Establece el color del píxel indexado a azul
					pixels[index] = blue_color

			#Aplica los cambios de píxeles a la imagen
			image.save_pixels(image.bounds, pixels)

			# guarde todos los cambios.
			image.save()

	# Escribe MemoryStream en un archivo
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

