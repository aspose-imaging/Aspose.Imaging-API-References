---
title: "GifOptions-klass"
type: docs
weight: 120
url: /sv/python-net/aspose.imaging.imageoptions/gifoptions/
---

**Summary:** The API for Graphical Interchange Format (GIF) raster image file creation offers<br/>            developers comprehensive options for generating GIF images with precise<br/>            control. With features to set background color, color palette, resolution,<br/>            interlaced type, transparent color, XMP metadata container, and image<br/>            compression, this API ensures flexibility and efficiency in creating optimized<br/>            and visually appealing GIFs tailored to specific application requirements.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.GifOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifOptions()](#GifOptions__1) | Initierar en ny instans av klassen [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/). |
| [GifOptions(gif_options)](#GifOptions_gif_options_2) | Initierar en ny instans av klassen [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Hämtar eller anger bakgrundsfärgen. |
| background_color_index | System.Byte | r/w | Hämtar eller anger GIF:ens bakgrundsfärgsindex. |
| buffer_size_hint | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| color_resolution | System.Byte | r/w | Hämtar eller anger GIF-färglösning. |
| disposed | bool | r | Hämtar ett värde som indikerar om den här instansen är frigjord. |
| do_palette_correction | bool | r/w | Hämtar eller anger ett värde som indikerar om palettkorrigering tillämpas. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Hämtar eller anger Exif-data. |
| full_frame | bool | r/w | Hämtar eller anger ett värde som indikerar om [full frame]. |
| has_trailer | bool | r/w | Hämtar eller anger ett värde som indikerar om GIF har trailer. |
| has_transparent_color | System.Nullable`1[[System.Boolean]] | r/w | Hämtar eller anger ett värde som indikerar om en GIF-bild har transparent färg. <br/>            Om returvärdet är **None**, åsidosätts denna egenskap av källbildens kontext. |
| interlaced | bool | r/w | True om bilden ska vara interlaced. |
| is_palette_sorted | bool | r/w | Hämtar eller anger ett värde som indikerar om palettposter är sorterade. |
| keep_metadata | bool | r/w | Hämtar ett värde som anger om originalmetadata för bilden ska behållas vid export. |
| loops_count | int | r/w | Hämtar eller anger antalet loopar (Standard 1 loop) |
| max_diff | int | r/w | Hämtar eller anger den maximalt tillåtna pixelskillnaden. Om den är större än noll används förlustkomprimering.<br/>            Rekommenderat värde för optimal förlustkomprimering är 80. 30 är mycket lätt komprimering, 200 är tung.<br/>            Det fungerar bäst när endast liten förlust införs, och på grund av begränsningar i komprimeringsalgoritmen ger mycket höga förlustnivåer inte lika stor vinst.<br/>            Intervallet för tillåtna värden är [0, 1000]. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Flersidiga alternativ |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Hämtar eller anger färgpaletten. |
| pixel_aspect_ratio | System.Byte | r/w | Hämtar eller anger GIF-pixelaspektförhållandet. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Hämtar eller anger upplösningsinställningarna. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Hämtar eller anger källan där bilden ska skapas. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Hämtar eller anger vektorrasteriseringsalternativen. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Hämtar eller anger XMP-metadatabehållaren. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Skapar en medlemsvis klon av detta objekt. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Försöker sätta en _metadata_-instans, om detta [Image](/imaging/python-net/aspose.imaging/image/)-instans stödjer och implementerar [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)-instansen. |


### Constructor: GifOptions() {#GifOptions__1}


```
 GifOptions() 
```

Initierar en ny instans av klassen [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/).

### Constructor: GifOptions(gif_options) {#GifOptions_gif_options_2}


```
 GifOptions(gif_options) 
```

Initierar en ny instans av klassen [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| gif_options | [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/) | GIF-alternativen. |

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

