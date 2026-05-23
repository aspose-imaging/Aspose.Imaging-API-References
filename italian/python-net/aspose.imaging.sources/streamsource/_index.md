---
title: "Classe StreamSource"
type: docs
weight: 40
url: /it/python-net/aspose.imaging.sources/streamsource/
---

**Summary:** Represents a stream source.

**Module:** [aspose.imaging.sources](/imaging/python-net/aspose.imaging.sources/)

**Full Name:** aspose.imaging.sources.StreamSource

**Inheritance:** Source

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [StreamSource()](#StreamSource__1) | Inizializza una nuova istanza della classe [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) |
| [StreamSource(stream)](#StreamSource_stream_2) | Inizializza una nuova istanza della classe [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) |
| [StreamSource(stream, dispose_stream)](#StreamSource_stream_dispose_stream_3) | Inizializza una nuova istanza della classe [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| dispose_stream | bool | r | Ottiene un valore che indica se lo stream deve essere eliminato quando il contenitore viene eliminato |
| stream | _io.BufferedRandom | r | Ottiene lo stream |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | Ottiene il contenitore di flusso. |


### Constructor: StreamSource() {#StreamSource__1}


```
 StreamSource() 
```

Inizializza una nuova istanza della classe [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/)

### Constructor: StreamSource(stream) {#StreamSource_stream_2}


```
 StreamSource(stream) 
```

Inizializza una nuova istanza della classe [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/)

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Lo stream da aprire |


**See also:**

**[Example # 1](#example_7)**: This example shows how to load a pixels information in an array of Color, man...


### Constructor: StreamSource(stream, dispose_stream) {#StreamSource_stream_dispose_stream_3}


```
 StreamSource(stream, dispose_stream) 
```

Inizializza una nuova istanza della classe [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/)

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Lo stream da aprire |
| dispose_stream | bool | se impostato su <c>true</c> lo stream verrà eliminato |


**See also:**

**[Example # 1](#example_5)**: This example demonstrates the use of file stream to Create a new Image file (...


### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

Ottiene il contenitore di flusso.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | il contenitore di flusso. |


## **Examples**
### This example demonstrates the use of file stream to Create a new Image file (a JPEG type) {#example_5}
``` python

from aspose.imaging.imageoptions import JpegOptions
from aspose.imaging.sources import StreamSource

# Crea un'istanza di JpegOptions e imposta le sue varie proprietà
with JpegOptions() as jpegOptions:
	# Crea un'istanza di stream
	with open(r"C:\temp\sample.jpeg", "w+b") as stream:
		#Definisci la proprietà source per l'istanza di JpegOptions
		#Il secondo parametro booleano determina se lo Stream viene eliminato una volta fuori dal contesto
		jpegOptions.source = StreamSource(stream, True)
		#Crea un'istanza di Image e chiama il metodo Create con JpegOptions come parametro per inizializzare l'oggetto Image
		with Image.create(jpegOptions, 500, 500) as image:
			#esegui qualche elaborazione dell'immagine
			pass

```

### This example shows how to load a pixels information in an array of Color, manipulates the array and set it back to the image. To perform these operations, this example creates a new Image file (in GIF format) using MemoryStream object. {#example_7}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Color
from aspose.imaging.externsions import StreamExtensions as strm_ext
from aspose.imaging.imageoptions import GifOptions
from aspose.imaging.sources import StreamSource

# Crea un'istanza di MemoryStream
with strm_ext.create_memory_stream() as stream:
	#Crea un'istanza di GifOptions e imposta le sue varie proprietà, inclusa la proprietà Source
	with GifOptions() as gifOptions:
		gifOptions.source = StreamSource(stream)

		# Crea un'istanza di Image
		with as_of(Image.create(gifOptions, 500, 500), RasterImage) as image:
			# Ottieni i pixel dell'immagine specificando l'area come confine dell'immagine
			pixels = image.load_pixels(image.bounds)

			yellow_color = Color.yellow
			blue_color = Color.blue
			#Itera sull'Array e imposta il colore dei pixel indicizzati alternativi
			for index in range(pixel.length):
				if index % 2 == 0:
					#Imposta il colore del pixel indicizzato a giallo
					pixels[index] = yellow_color
				else:
					#Imposta il colore del pixel indicizzato a blu
					pixels[index] = blue_color

			#Applica le modifiche dei pixel all'immagine
			image.save_pixels(image.bounds, pixels)

			# salva tutte le modifiche.
			image.save()

	# Scrivi MemoryStream su File
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

