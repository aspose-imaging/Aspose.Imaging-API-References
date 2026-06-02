---
title: "PngOptions klass"
type: docs
weight: 250
url: /sv/python-net/aspose.imaging.imageoptions/pngoptions/
---

**Summary:** Create high-quality Portable Network Graphics (PNG) raster images effortlessly<br/>            with our API, offering customizable options for compression levels,<br/>            bits per pixel depths, and alpha bits. Seamlessly process XMP metadata containers,<br/>            ensuring comprehensive image metadata management, and empowering you to tailor<br/>            PNG images to your exact specifications with ease.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PngOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PngOptions()](#PngOptions__1) | Initierar en ny instans av klassen [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/). |
| [PngOptions(png_options)](#PngOptions_png_options_2) | Initierar en ny instans av klassen [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| DEFAULT_COMPRESSION_LEVEL [static] | [PngCompressionLevel](/imaging/python-net/aspose.imaging.imageoptions/pngcompressionlevel/) | r | Standardkomprimeringsnivån. |
| bit_depth | System.Byte | r/w | Hämtar eller anger bitdjupsvärdena i intervallet 1, 2, 4, 8, 16.<br/>            <br/><br/>            Observera följande begränsningar:<br/>            <br/><br/>[PngColorType.INDEXED_COLOR](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) stöder bitdjup på 1, 2, 4, 8.<br/>            <br/><br/>[PngColorType.GRAYSCALE](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/), [PngColorType.GRAYSCALE_WITH_ALPHA](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) stöder bitdjup på 8.<br/>            <br/><br/>[PngColorType.TRUECOLOR](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/), [PngColorType.TRUECOLOR_WITH_ALPHA](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) stöder bitdjup på 8, 16.<br/>            <br/> |
| buffer_size_hint | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| [color_type](#color_type1) | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | r/w | Hämtar eller anger färgens typ. |
| [compression_level](#compression_level2) | int | r/w | Hämtar eller anger komprimeringsnivån för [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| disposed | bool | r | Hämtar ett värde som indikerar om den här instansen är frigjord. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Hämtar eller anger Exif-data. |
| filter_type | [PngFilterType](/imaging/python-net/aspose.imaging.fileformats.png/pngfiltertype/) | r/w | Hämtar eller anger filtertypen som används under sparprocessen för png‑filen. |
| full_frame | bool | r/w | Hämtar eller anger ett värde som indikerar om [full frame]. |
| keep_metadata | bool | r/w | Hämtar ett värde som anger om originalmetadata för bilden ska behållas vid export. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Flersidiga alternativ |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Hämtar eller anger färgpaletten. |
| png_compression_level | [PngCompressionLevel](/imaging/python-net/aspose.imaging.imageoptions/pngcompressionlevel/) | r/w | Hämtar eller anger komprimeringsnivån för [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| [progressive](#progressive3) | bool | r/w | Hämtar eller anger ett värde som indikerar om en [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) är progressiv. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Hämtar eller anger upplösningsinställningarna. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Hämtar eller anger källan där bilden ska skapas. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Hämtar eller anger vektorrasteriseringsalternativen. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Hämtar eller anger XMP-metadatabehållaren. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Skapar en medlemsvis klon av detta objekt. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Försöker sätta en _metadata_-instans, om detta [Image](/imaging/python-net/aspose.imaging/image/)-instans stödjer och implementerar [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)-instansen. |


### Constructor: PngOptions() {#PngOptions__1}


```
 PngOptions() 
```

Initierar en ny instans av klassen [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/).

### Constructor: PngOptions(png_options) {#PngOptions_png_options_2}


```
 PngOptions(png_options) 
```

Initierar en ny instans av klassen [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| png_options | [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) | PNG-alternativen. |

### Property: color_type {#color_type1}

Hämtar eller anger färgens typ.

**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Property: compression_level {#compression_level2}

Hämtar eller anger komprimeringsnivån för [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/).

**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Property: progressive {#progressive3}

Hämtar eller anger ett värde som indikerar om en [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) är progressiv.

**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Method: clone() {#clone__1}


```
 clone() 
```

Skapar en medlemsvis klon av detta objekt.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | En medlemsvis klon av detta objekt. |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_2}


```
 try_set_metadata(metadata) 
```

Försöker sätta en _metadata_-instans, om detta [Image](/imaging/python-net/aspose.imaging/image/)-instans stödjer och implementerar [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)-instansen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | Metadata. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Sant, om [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/)‑instansen stöder och/eller implementerar [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)‑instansen; annars falskt. |


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

### This example demonstrates the use of different classes from `imageoptions` package for export purposes. A gif image is loaded as an instance of Image and then exported out to several formats. {#example_15}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions, JpegOptions, PngOptions, TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from os.path import join as path_join

directory = "c:\\temp\\"
#Läs in en befintlig gif-bild som en instans av Image-klassen.
with Image.load(path_join(directory, "sample.gif")) as image:
	# Exportera till BMP-filformat med standardalternativen.
	image.save(path_join(directory, "output.bmp"), BmpOptions())
	# Exportera till JPEG-filformat med standardalternativen.
	image.save(path_join(directory, "output.jpg"), JpegOptions())
	# Exportera till PNG-filformat med standardalternativen.
	image.save(path_join(directory, "output.png"), PngOptions())
	# Exportera till TIFF-filformat med standardalternativen.
	image.save(path_join(directory, "output.tif"), TiffOptions(TiffExpectedFormat.DEFAULT))


```

### The following example shows how to compress a PNG image, using indexed color with best fit palette {#example_21}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, ColorPaletteHelper, RasterImage, PaletteMiningMethod
from aspose.imaging.fileformats.png import PngColorType

# Laddar png-bild        
sourceFilePath = "OriginalRings.png"
outputFilePath = "OriginalRingsOutput.png"
with Image.load(sourceFilePath) as image:
	png_options = PngOptions()
	png_options.progressive = True
	# Använd indexerad färgtyp
	png_options.color_type = PngColorType.INDEXED_COLOR
	# Använd maximal komprimering
	png_options.compression_level = 9
	# Hämta den närmaste 8-bitars färgpaletten, som täcker så många pixlar som möjligt, så att en bild
	# med palett är nästan visuellt omöjlig att skilja från en bild utan palett.
	png_options.palette = ColorPaletteHelper.get_close_image_palette(
						as_of(image, RasterImage), 256, 
						PaletteMiningMethod.HISTOGRAM)
		 
	image.save(outputFilePath, png_options);
}
# Utdatafilens storlek bör minskas avsevärt

```

