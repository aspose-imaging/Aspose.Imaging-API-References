---
title: "PngOptions Klasse"
type: docs
weight: 250
url: /de/python-net/aspose.imaging.imageoptions/pngoptions/
---

**Summary:** Create high-quality Portable Network Graphics (PNG) raster images effortlessly<br/>            with our API, offering customizable options for compression levels,<br/>            bits per pixel depths, and alpha bits. Seamlessly process XMP metadata containers,<br/>            ensuring comprehensive image metadata management, and empowering you to tailor<br/>            PNG images to your exact specifications with ease.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PngOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [PngOptions()](#PngOptions__1) | Initialisiert eine neue Instanz der [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) Klasse. |
| [PngOptions(png_options)](#PngOptions_png_options_2) | Initialisiert eine neue Instanz der [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| DEFAULT_COMPRESSION_LEVEL [static] | [PngCompressionLevel](/imaging/python-net/aspose.imaging.imageoptions/pngcompressionlevel/) | r | Der Standard-Komprimierungsgrad. |
| bit_depth | System.Byte | r/w | Legt die Bit-Tiefenwerte im Bereich von 1, 2, 4, 8, 16 fest oder ruft sie ab.<br/>            <br/><br/>            Beachten Sie die folgenden Grenzen:<br/>            <br/><br/>[PngColorType.INDEXED_COLOR](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) unterstützt Bit-Tiefen von 1, 2, 4, 8.<br/>            <br/><br/>[PngColorType.GRAYSCALE](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/), [PngColorType.GRAYSCALE_WITH_ALPHA](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) unterstützen Bit-Tiefen von 8.<br/>            <br/><br/>[PngColorType.TRUECOLOR](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/), [PngColorType.TRUECOLOR_WITH_ALPHA](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) unterstützen Bit-Tiefen von 8, 16.<br/>            <br/> |
| buffer_size_hint | int | r/w | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [color_type](#color_type1) | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | r/w | Liest oder setzt den Typ der Farbe. |
| [compression_level](#compression_level2) | int | r/w | Legt den Komprimierungsgrad der [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) fest oder ruft ihn ab. |
| freigegeben | bool | r | Liest einen Wert, der angibt, ob diese Instanz freigegeben ist. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Liest oder setzt die Exif-Daten. |
| filter_type | [PngFilterType](/imaging/python-net/aspose.imaging.fileformats.png/pngfiltertype/) | r/w | Legt den Filtertyp fest, der beim Speichern von PNG-Dateien verwendet wird, oder ruft ihn ab. |
| full_frame | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [full frame]. |
| keep_metadata | bool | r/w | Liest einen Wert, ob die ursprünglichen Bildmetadaten beim Export beibehalten werden sollen. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Die Mehrseiten‑Optionen |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Liest oder setzt die Farbpalette. |
| png_compression_level | [PngCompressionLevel](/imaging/python-net/aspose.imaging.imageoptions/pngcompressionlevel/) | r/w | Legt den Komprimierungsgrad der [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) fest oder ruft ihn ab. |
| [progressive](#progressive3) | bool | r/w | Legt einen Wert fest, der angibt, ob eine [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) progressiv ist, oder ruft ihn ab. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Liest oder setzt die Auflösungseinstellungen. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Liest oder setzt die Quelle, in der das Bild erstellt wird. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Liest oder setzt die Vektor‑Rasterisierungsoptionen. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Liest oder setzt den XMP‑Metadatencontainer. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [clone()](#clone__1) | Erstellt eine memberweise Kopie dieser Instanz. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Versucht, eine _metadata_-Instanz zu setzen, falls diese [Image](/imaging/python-net/aspose.imaging/image/)‑Instanz unterstützt und eine [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)‑Instanz implementiert. |


### Constructor: PngOptions() {#PngOptions__1}


```
 PngOptions() 
```

Initialisiert eine neue Instanz der [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) Klasse.

### Constructor: PngOptions(png_options) {#PngOptions_png_options_2}


```
 PngOptions(png_options) 
```

Initialisiert eine neue Instanz der [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| png_options | [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) | Die PNG‑Optionen. |

### Property: color_type {#color_type1}

Liest oder setzt den Typ der Farbe.

**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Property: compression_level {#compression_level2}

Legt den Komprimierungsgrad der [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) fest oder ruft ihn ab.

**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Property: progressive {#progressive3}

Legt einen Wert fest, der angibt, ob eine [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) progressiv ist, oder ruft ihn ab.

**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


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

### The following example shows how to compress a PNG image, using indexed color with best fit palette {#example_21}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, ColorPaletteHelper, RasterImage, PaletteMiningMethod
from aspose.imaging.fileformats.png import PngColorType

# Lädt PNG‑Bild        
sourceFilePath = "OriginalRings.png"
outputFilePath = "OriginalRingsOutput.png"
with Image.load(sourceFilePath) as image:
	png_options = PngOptions()
	png_options.progressive = True
	# Verwende indizierten Farbtyp
	png_options.color_type = PngColorType.INDEXED_COLOR
	# Verwende maximale Kompression
	png_options.compression_level = 9
	# Erhalte die nächstgelegene 8‑Bit-Farbpalette, die so viele Pixel wie möglich abdeckt, sodass ein Bild
	# mit Palette fast visuell nicht von einem Bild ohne Palette zu unterscheiden ist.
	png_options.palette = ColorPaletteHelper.get_close_image_palette(
						as_of(image, RasterImage), 256, 
						PaletteMiningMethod.HISTOGRAM)
		 
	image.save(outputFilePath, png_options);
}
# Die Ausgabedateigröße sollte deutlich reduziert werden

```

