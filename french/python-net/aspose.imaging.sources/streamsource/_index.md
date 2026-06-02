---
title: "StreamSource Classe"
type: docs
weight: 40
url: /fr/python-net/aspose.imaging.sources/streamsource/
---

**Summary:** Represents a stream source.

**Module:** [aspose.imaging.sources](/imaging/python-net/aspose.imaging.sources/)

**Full Name:** aspose.imaging.sources.StreamSource

**Inheritance:** Source

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [StreamSource()](#StreamSource__1) | Initialise une nouvelle instance de la classe [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/). |
| [StreamSource(stream)](#StreamSource_stream_2) | Initialise une nouvelle instance de la classe [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/). |
| [StreamSource(stream, dispose_stream)](#StreamSource_stream_dispose_stream_3) | Initialise une nouvelle instance de la classe [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| dispose_stream | bool | r | Obtient une valeur indiquant si le stream doit être libéré chaque fois que le conteneur est libéré. |
| flux | _io.BufferedRandom | r | Obtient le stream. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | Obtient le conteneur de flux. |


### Constructor: StreamSource() {#StreamSource__1}


```
 StreamSource() 
```

Initialise une nouvelle instance de la classe [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/).

### Constructor: StreamSource(stream) {#StreamSource_stream_2}


```
 StreamSource(stream) 
```

Initialise une nouvelle instance de la classe [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le stream à ouvrir. |


**See also:**

**[Example # 1](#example_7)**: This example shows how to load a pixels information in an array of Color, man...


### Constructor: StreamSource(stream, dispose_stream) {#StreamSource_stream_dispose_stream_3}


```
 StreamSource(stream, dispose_stream) 
```

Initialise une nouvelle instance de la classe [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le stream à ouvrir. |
| dispose_stream | bool | si défini sur <c>true</c> le stream sera libéré. |


**See also:**

**[Example # 1](#example_5)**: This example demonstrates the use of file stream to Create a new Image file (...


### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

Obtient le conteneur de flux.

**Returns**

| Type | Description |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | le conteneur de flux. |


## **Examples**
### This example demonstrates the use of file stream to Create a new Image file (a JPEG type) {#example_5}
``` python

from aspose.imaging.imageoptions import JpegOptions
from aspose.imaging.sources import StreamSource

# Crée une instance de JpegOptions et définit ses différentes propriétés
with JpegOptions() as jpegOptions:
	# Crée une instance de stream
	with open(r"C:\temp\sample.jpeg", "w+b") as stream:
		#Définissez la propriété source pour l'instance de JpegOptions
		#Le deuxième paramètre booléen détermine si le Stream est libéré une fois sorti de la portée
		jpegOptions.source = StreamSource(stream, True)
		#Crée une instance de Image et appelle la méthode Create avec JpegOptions comme paramètre pour initialiser l'objet Image
		with Image.create(jpegOptions, 500, 500) as image:
			#effectuer un traitement d'image
			pass

```

### This example shows how to load a pixels information in an array of Color, manipulates the array and set it back to the image. To perform these operations, this example creates a new Image file (in GIF format) using MemoryStream object. {#example_7}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Color
from aspose.imaging.externsions import StreamExtensions as strm_ext
from aspose.imaging.imageoptions import GifOptions
from aspose.imaging.sources import StreamSource

# Créer une instance de MemoryStream
with strm_ext.create_memory_stream() as stream:
	#Créez une instance de GifOptions et définissez ses différentes propriétés, y compris la propriété Source
	with GifOptions() as gifOptions:
		gifOptions.source = StreamSource(stream)

		# Créez une instance de Image
		with as_of(Image.create(gifOptions, 500, 500), RasterImage) as image:
			# Obtenez les pixels de l'image en spécifiant la zone comme la bordure de l'image
			pixels = image.load_pixels(image.bounds)

			yellow_color = Color.yellow
			blue_color = Color.blue
			#Parcourez le tableau et définissez la couleur des pixels indexés alternés
			for index in range(pixel.length):
				if index % 2 == 0:
					#Définissez la couleur du pixel indexé sur jaune
					pixels[index] = yellow_color
				else:
					#Définissez la couleur du pixel indexé sur bleu
					pixels[index] = blue_color

			#Appliquez les modifications de pixels à l'image
			image.save_pixels(image.bounds, pixels)

			# enregistrez toutes les modifications.
			image.save()

	# Écrire MemoryStream dans un fichier
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

#Crée une instance de flux de fichier
with open(r"C:\temp\output.png", "w+b") as stream:
	#Créez une instance de PngOptions et définissez ses différentes propriétés
	pngOptions = PngOptions()
	#Définissez la source pour PngOptions
	pngOptions.source = StreamSource(stream)
	#Créez une instance de Image
	with Image.create(pngOptions, 500, 500) as image:
		#Créez et initialisez une instance de la classe Graphics
		graphics = Graphics(image)
		#Efface la surface Graphics
		graphics.clear(Color.wheat);
		#Dessinez un arc en spécifiant l'objet Pen de couleur noire, 
		#un Rectangle entourant l'arc, l'angle de départ et l'angle de balayage
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#Dessinez un Bézier en spécifiant l'objet Pen de couleur bleue et les points de coordonnées.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#Dessinez une courbe en spécifiant l'objet Pen ayant la couleur Verte et un tableau de Points
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#Dessinez une ellipse en utilisant l'objet Pen et un rectangle environnant
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#Dessinez une ligne
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#Dessinez un segment de tarte
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#Dessinez un polygone en spécifiant l'objet Pen ayant la couleur Rouge et un tableau de Points
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#Dessinez un rectangle
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#Créez un objet SolidBrush et définissez ses différentes propriétés
		brush = SolidBrush()
		brush.color = Color.purple
		#Dessinez un String en utilisant l'objet SolidBrush et Font, à un Point spécifique
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# enregistrez toutes les modifications.
		image.save();

```

