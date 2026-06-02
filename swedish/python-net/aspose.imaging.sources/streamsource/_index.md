---
title: "StreamSource klass"
type: docs
weight: 40
url: /sv/python-net/aspose.imaging.sources/streamsource/
---

**Summary:** Represents a stream source.

**Module:** [aspose.imaging.sources](/imaging/python-net/aspose.imaging.sources/)

**Full Name:** aspose.imaging.sources.StreamSource

**Inheritance:** Source

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [StreamSource()](#StreamSource__1) | Initierar en ny instans av klassen [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/). |
| [StreamSource(stream)](#StreamSource_stream_2) | Initierar en ny instans av klassen [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/). |
| [StreamSource(stream, dispose_stream)](#StreamSource_stream_dispose_stream_3) | Initierar en ny instans av klassen [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| dispose_stream | bool | r | Hämtar ett värde som indikerar om strömmen ska tas bort när behållaren tas bort. |
| ström | _io.BufferedRandom | r | Hämtar strömmen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | Hämtar strömbehållaren. |


### Constructor: StreamSource() {#StreamSource__1}


```
 StreamSource() 
```

Initierar en ny instans av klassen [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/).

### Constructor: StreamSource(stream) {#StreamSource_stream_2}


```
 StreamSource(stream) 
```

Initierar en ny instans av klassen [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att öppna. |


**See also:**

**[Example # 1](#example_7)**: This example shows how to load a pixels information in an array of Color, man...


### Constructor: StreamSource(stream, dispose_stream) {#StreamSource_stream_dispose_stream_3}


```
 StreamSource(stream, dispose_stream) 
```

Initierar en ny instans av klassen [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att öppna. |
| dispose_stream | bool | Om den är inställd på <c>true</c> kommer strömmen att tas bort. |


**See also:**

**[Example # 1](#example_5)**: This example demonstrates the use of file stream to Create a new Image file (...


### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

Hämtar strömbehållaren.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | strömbehållaren. |


## **Examples**
### This example demonstrates the use of file stream to Create a new Image file (a JPEG type) {#example_5}
``` python

from aspose.imaging.imageoptions import JpegOptions
from aspose.imaging.sources import StreamSource

# Skapar en instans av JpegOptions och sätter dess olika egenskaper
with JpegOptions() as jpegOptions:
	# Skapa en instans av stream
	with open(r"C:\temp\sample.jpeg", "w+b") as stream:
		#Definiera source‑egenskapen för instansen av JpegOptions
		#Den andra booleska parametern bestämmer om Stream tas bort när den går ur scope
		jpegOptions.source = StreamSource(stream, True)
		#Skapar en instans av Image och anropar Create‑metoden med JpegOptions som parameter för att initiera Image‑objektet
		with Image.create(jpegOptions, 500, 500) as image:
			#utför någon bildbehandling
			pass

```

### This example shows how to load a pixels information in an array of Color, manipulates the array and set it back to the image. To perform these operations, this example creates a new Image file (in GIF format) using MemoryStream object. {#example_7}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Color
from aspose.imaging.externsions import StreamExtensions as strm_ext
from aspose.imaging.imageoptions import GifOptions
from aspose.imaging.sources import StreamSource

# Skapa en instans av MemoryStream
with strm_ext.create_memory_stream() as stream:
	#Skapa en instans av GifOptions och ange dess olika egenskaper, inklusive Source‑egenskapen
	with GifOptions() as gifOptions:
		gifOptions.source = StreamSource(stream)

		# Skapa en instans av Image
		with as_of(Image.create(gifOptions, 500, 500), RasterImage) as image:
			# Hämta bildens pixlar genom att ange området som bildens gräns
			pixels = image.load_pixels(image.bounds)

			yellow_color = Color.yellow
			blue_color = Color.blue
			#Iterera över arrayen och ange färg för alternerande indexerade pixlar
			for index in range(pixel.length):
				if index % 2 == 0:
					#Ange den indexerade pixelns färg till gul
					pixels[index] = yellow_color
				else:
					#Ange den indexerade pixelns färg till blå
					pixels[index] = blue_color

			#Applicera pixeländringarna på bilden
			image.save_pixels(image.bounds, pixels)

			# spara alla ändringar.
			image.save()

	# Skriv MemoryStream till fil
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

#Skapar en instans av filström
with open(r"C:\temp\output.png", "w+b") as stream:
	#Skapa en instans av PngOptions och ange dess olika egenskaper
	pngOptions = PngOptions()
	#Ange källan för PngOptions
	pngOptions.source = StreamSource(stream)
	#Skapa en instans av Image
	with Image.create(pngOptions, 500, 500) as image:
		#Skapa och initiera en instans av Graphics-klassen
		graphics = Graphics(image)
		#Rensa Graphics-ytan
		graphics.clear(Color.wheat);
		#Rita en båge genom att ange Pen-objektet med svart färg, 
		#en rektangel som omger bågen, startvinkel och svepvinkel
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#Rita en Bezier genom att ange Pen-objektet med blå färg och koordinatpunkter.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#Rita en kurva genom att specificera Pen-objektet med grön färg och en array av punkter
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#Rita en ellips med Pen-objektet och en omgivande Rectangle
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#Rita en linje
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#Rita ett pajsegment
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#Rita en polygon genom att specificera Pen-objektet med röd färg och en array av punkter
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#Rita en Rectangle
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#Skapa ett SolidBrush-objekt och sätt dess olika egenskaper
		brush = SolidBrush()
		brush.color = Color.purple
		#Rita en String med SolidBrush-objektet och Font, vid en specifik Point
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# spara alla ändringar.
		image.save();

```

