---
title: "Klasse GifOptions"
type: docs
weight: 120
url: /de/python-net/aspose.imaging.imageoptions/gifoptions/
---

**Summary:** The API for Graphical Interchange Format (GIF) raster image file creation offers<br/>            developers comprehensive options for generating GIF images with precise<br/>            control. With features to set background color, color palette, resolution,<br/>            interlaced type, transparent color, XMP metadata container, and image<br/>            compression, this API ensures flexibility and efficiency in creating optimized<br/>            and visually appealing GIFs tailored to specific application requirements.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.GifOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [GifOptions()](#GifOptions__1) | Initialisiert eine neue Instanz der Klasse [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/). |
| [GifOptions(gif_options)](#GifOptions_gif_options_2) | Initialisiert eine neue Instanz der Klasse [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Liest oder setzt die Hintergrundfarbe. |
| background_color_index | System.Byte | r/w | Liest oder setzt den Hintergrundfarbindizes des GIFs. |
| buffer_size_hint | int | r/w | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| color_resolution | System.Byte | r/w | Liest oder setzt die Farbauflösung des GIFs. |
| freigegeben | bool | r | Liest einen Wert, der angibt, ob diese Instanz freigegeben ist. |
| do_palette_correction | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die Palettenkorrektur angewendet wird. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Liest oder setzt die Exif-Daten. |
| full_frame | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [full frame]. |
| has_trailer | bool | r/w | Liest oder setzt einen Wert, der angibt, ob das GIF einen Trailer hat. |
| has_transparent_color | System.Nullable`1[[System.Boolean]] | r/w | Liest oder setzt einen Wert, der angibt, ob ein GIF-Bild eine transparente Farbe hat. <br/>            Wenn der Rückgabewert **None** ist, wird diese Eigenschaft vom Quellbildkontext überschrieben. |
| interlaced | bool | r/w | True, wenn das Bild interlaced sein soll. |
| is_palette_sorted | bool | r/w | Liest oder setzt einen Wert, der angibt, ob Paletteneinträge sortiert sind. |
| keep_metadata | bool | r/w | Liest einen Wert, ob die ursprünglichen Bildmetadaten beim Export beibehalten werden sollen. |
| loops_count | int | r/w | Liest oder setzt die Schleifenanzahl (Standard 1 Schleife). |
| max_diff | int | r/w | Liest oder setzt die maximal zulässige Pixeldifferenz. Wenn sie größer als Null ist, wird verlustbehaftete Kompression verwendet.<br/>            Empfohlener Wert für optimale verlustbehaftete Kompression ist 80. 30 ist eine sehr leichte Kompression, 200 ist stark.<br/>            Sie funktioniert am besten, wenn nur wenig Verlust eingeführt wird, und aufgrund der Beschränkung des Kompressionsalgorithmus führen sehr hohe Verluststufen nicht zu einem großen Gewinn.<br/>            Der zulässige Wertebereich ist [0, 1000]. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Die Mehrseiten‑Optionen |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Liest oder setzt die Farbpalette. |
| pixel_aspect_ratio | System.Byte | r/w | Liest oder setzt das Seitenverhältnis der GIF-Pixel. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Liest oder setzt die Auflösungseinstellungen. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Liest oder setzt die Quelle, in der das Bild erstellt wird. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Liest oder setzt die Vektor‑Rasterisierungsoptionen. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Liest oder setzt den XMP‑Metadatencontainer. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [clone()](#clone__1) | Erstellt eine memberweise Kopie dieser Instanz. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Versucht, eine _metadata_-Instanz zu setzen, falls diese [Image](/imaging/python-net/aspose.imaging/image/)‑Instanz unterstützt und eine [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)‑Instanz implementiert. |


### Constructor: GifOptions() {#GifOptions__1}


```
 GifOptions() 
```

Initialisiert eine neue Instanz der Klasse [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/).

### Constructor: GifOptions(gif_options) {#GifOptions_gif_options_2}


```
 GifOptions(gif_options) 
```

Initialisiert eine neue Instanz der Klasse [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| gif_options | [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/) | Die GIF-Optionen. |

### Method: clone() {#clone__1}


```
 clone() 
```

Erstellt eine memberweise Kopie dieser Instanz.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Eine memberweise Kopie dieser Instanz. |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_2}


```
 try_set_metadata(metadata) 
```

Versucht, eine _metadata_-Instanz zu setzen, falls diese [Image](/imaging/python-net/aspose.imaging/image/)‑Instanz unterstützt und eine [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)‑Instanz implementiert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | Die Metadaten. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | True, wenn die [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) Instanz unterstützt und/oder das [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) implementiert; andernfalls false. |


## **Examples**
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

### This example demonstrates the use of different classes from `imageoptions` package for export purposes. A gif image is loaded as an instance of Image and then exported out to several formats. {#example_15}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions, JpegOptions, PngOptions, TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from os.path import join as path_join

directory = "c:\\temp\\"
#Lade ein vorhandenes GIF-Bild als Instanz der Image‑Klasse
with Image.load(path_join(directory, "sample.gif")) as image:
	# Exportiere in das BMP-Dateiformat unter Verwendung der Standardoptionen
	image.save(path_join(directory, "output.bmp"), BmpOptions())
	# Exportiere in das JPEG-Dateiformat unter Verwendung der Standardoptionen
	image.save(path_join(directory, "output.jpg"), JpegOptions())
	# Exportiere in das PNG-Dateiformat unter Verwendung der Standardoptionen
	image.save(path_join(directory, "output.png"), PngOptions())
	# Exportiere in das TIFF-Dateiformat unter Verwendung der Standardoptionen
	image.save(path_join(directory, "output.tif"), TiffOptions(TiffExpectedFormat.DEFAULT))


```

