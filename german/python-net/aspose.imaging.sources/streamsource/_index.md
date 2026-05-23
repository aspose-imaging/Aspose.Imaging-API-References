---
title: "StreamSource Klasse"
type: docs
weight: 40
url: /de/python-net/aspose.imaging.sources/streamsource/
---

**Summary:** Represents a stream source.

**Module:** [aspose.imaging.sources](/imaging/python-net/aspose.imaging.sources/)

**Full Name:** aspose.imaging.sources.StreamSource

**Inheritance:** Source

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [StreamSource()](#StreamSource__1) | Initialisiert eine neue Instanz der [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) Klasse. |
| [StreamSource(stream)](#StreamSource_stream_2) | Initialisiert eine neue Instanz der [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) Klasse. |
| [StreamSource(stream, dispose_stream)](#StreamSource_stream_dispose_stream_3) | Initialisiert eine neue Instanz der [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| dispose_stream | bool | r | Ermittelt einen Wert, der angibt, ob der Stream verworfen werden soll, wenn der Container verworfen wird. |
| Stream | _io.BufferedRandom | r | Ermittelt den Stream. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | Ruft den Stream-Container ab. |


### Constructor: StreamSource() {#StreamSource__1}


```
 StreamSource() 
```

Initialisiert eine neue Instanz der [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) Klasse.

### Constructor: StreamSource(stream) {#StreamSource_stream_2}


```
 StreamSource(stream) 
```

Initialisiert eine neue Instanz der [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream zum Öffnen. |


**See also:**

**[Example # 1](#example_7)**: This example shows how to load a pixels information in an array of Color, man...


### Constructor: StreamSource(stream, dispose_stream) {#StreamSource_stream_dispose_stream_3}


```
 StreamSource(stream, dispose_stream) 
```

Initialisiert eine neue Instanz der [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream zum Öffnen. |
| dispose_stream | bool | Wenn auf <c>true</c> gesetzt, wird der Stream verworfen. |


**See also:**

**[Example # 1](#example_5)**: This example demonstrates the use of file stream to Create a new Image file (...


### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

Ruft den Stream-Container ab.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | der Stream-Container. |


## **Examples**
### This example demonstrates the use of file stream to Create a new Image file (a JPEG type) {#example_5}
``` python

from aspose.imaging.imageoptions import JpegOptions
from aspose.imaging.sources import StreamSource

# Erstellt eine Instanz von JpegOptions und setzt deren verschiedene Eigenschaften
with JpegOptions() as jpegOptions:
	# Erstelle eine Instanz des Streams
	with open(r"C:\temp\sample.jpeg", "w+b") as stream:
		#Definiere die source-Eigenschaft für die Instanz von JpegOptions
		#Der zweite boolesche Parameter bestimmt, ob der Stream verworfen wird, sobald er den Gültigkeitsbereich verlässt
		jpegOptions.source = StreamSource(stream, True)
		#Erstellt eine Instanz von Image und ruft die Create-Methode mit JpegOptions als Parameter auf, um das Image-Objekt zu initialisieren
		with Image.create(jpegOptions, 500, 500) as image:
			#Führe einige Bildverarbeitungen durch
			pass

```

### This example shows how to load a pixels information in an array of Color, manipulates the array and set it back to the image. To perform these operations, this example creates a new Image file (in GIF format) using MemoryStream object. {#example_7}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Color
from aspose.imaging.externsions import StreamExtensions as strm_ext
from aspose.imaging.imageoptions import GifOptions
from aspose.imaging.sources import StreamSource

# Erstellen Sie eine Instanz von MemoryStream.
with strm_ext.create_memory_stream() as stream:
	#Erstelle eine Instanz von GifOptions und setze deren verschiedene Eigenschaften, einschließlich der Source-Eigenschaft.
	with GifOptions() as gifOptions:
		gifOptions.source = StreamSource(stream)

		# Erstellen Sie eine Instanz von Image
		with as_of(Image.create(gifOptions, 500, 500), RasterImage) as image:
			# Rufe die Pixel des Bildes ab, indem du den Bereich als Bildgrenze angibst.
			pixels = image.load_pixels(image.bounds)

			yellow_color = Color.yellow
			blue_color = Color.blue
			#Durchlaufe das Array und setze die Farbe alternierender indizierter Pixel.
			for index in range(pixel.length):
				if index % 2 == 0:
					#Setze die Farbe des indizierten Pixels auf Gelb.
					pixels[index] = yellow_color
				else:
					#Setze die Farbe des indizierten Pixels auf Blau.
					pixels[index] = blue_color

			#Wende die Pixeländerungen auf das Bild an.
			image.save_pixels(image.bounds, pixels)

			# Alle Änderungen speichern.
			image.save()

	# Schreibe MemoryStream in eine Datei.
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

#Erstellt eine Instanz eines Dateistreams.
with open(r"C:\temp\output.png", "w+b") as stream:
	#Erstelle eine Instanz von PngOptions und setze deren verschiedene Eigenschaften.
	pngOptions = PngOptions()
	#Setze die Quelle für PngOptions.
	pngOptions.source = StreamSource(stream)
	#Erstelle eine Instanz von Image.
	with Image.create(pngOptions, 500, 500) as image:
		#Erstelle und initialisiere eine Instanz der Graphics Klasse.
		graphics = Graphics(image)
		#Lösche die Graphics-Oberfläche.
		graphics.clear(Color.wheat);
		#Zeichne einen Bogen, indem du das Pen-Objekt mit schwarzer Farbe angibst, 
		#ein Rechteck, das den Bogen umgibt, Startwinkel und Sweep-Winkel.
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#Zeichne eine Bézierkurve, indem du das Pen-Objekt mit blauer Farbe und Koordinatenpunkten angibst.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#Zeichnen Sie eine Kurve, indem Sie das Pen-Objekt mit grüner Farbe und einem Array von Punkten angeben.
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#Zeichnen Sie eine Ellipse mit dem Pen-Objekt und einem umgebenden Rechteck.
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#Zeichnen Sie eine Linie
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#Zeichnen Sie ein Kuchenstück.
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#Zeichnen Sie ein Polygon, indem Sie das Pen-Objekt mit roter Farbe und einem Array von Punkten angeben.
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#Zeichnen Sie ein Rechteck.
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#Erstellen Sie ein SolidBrush-Objekt und setzen Sie dessen verschiedene Eigenschaften.
		brush = SolidBrush()
		brush.color = Color.purple
		#Zeichnen Sie einen String mit dem SolidBrush-Objekt und Font an einem bestimmten Punkt.
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# Alle Änderungen speichern.
		image.save();

```

