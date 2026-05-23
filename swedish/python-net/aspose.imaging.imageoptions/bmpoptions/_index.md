---
title: "BmpOptions-klass"
type: docs
weight: 30
url: /sv/python-net/aspose.imaging.imageoptions/bmpoptions/
---

**Summary:** The API for BMP and DIB raster image format creation options provides developers<br/>            with a versatile toolset for generating custom Bitmap (BMP) and Device<br/>            Independent Bitmap (DIB) images. With this API, you can precisely define<br/>            image characteristics such as bits per pixel, compression level and compression<br/>            type, tailoring the output to meet specific requirements. This feature-rich<br/>            API empowers developers to create high-quality, customized raster images<br/>            with ease and flexibility for diverse applications.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.BmpOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BmpOptions()](#BmpOptions__1) | Initierar en ny instans av klassen [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/). |
| [BmpOptions(bmp_options)](#BmpOptions_bmp_options_2) | Initierar en ny instans av klassen [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [bits_per_pixel](#bits_per_pixel1) | int | r/w | Hämtar eller anger antalet bildbitar per pixel. |
| buffer_size_hint | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| [compression](#compression2) | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | r/w | Hämtar eller anger komprimeringstypen. Standardkomprimeringstypen är [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/), vilket möjliggör att spara en [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) med transparens. |
| disposed | bool | r | Hämtar ett värde som indikerar om den här instansen är frigjord. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Hämtar eller anger Exif-data. |
| full_frame | bool | r/w | Hämtar eller anger ett värde som indikerar om [full frame]. |
| keep_metadata | bool | r/w | Hämtar ett värde som anger om originalmetadata för bilden ska behållas vid export. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Flersidiga alternativ |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Hämtar eller anger färgpaletten. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Hämtar eller anger upplösningsinställningarna. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Hämtar eller anger källan där bilden ska skapas. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Hämtar eller anger vektorrasteriseringsalternativen. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Hämtar eller anger XMP-metadatabehållaren. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Skapar en medlemsvis klon av detta objekt. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Försöker sätta en _metadata_-instans, om detta [Image](/imaging/python-net/aspose.imaging/image/)-instans stödjer och implementerar [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)-instansen. |


### Constructor: BmpOptions() {#BmpOptions__1}


```
 BmpOptions() 
```

Initierar en ny instans av klassen [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/).


**See also:**

**[Example # 1](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 2](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...


### Constructor: BmpOptions(bmp_options) {#BmpOptions_bmp_options_2}


```
 BmpOptions(bmp_options) 
```

Initierar en ny instans av klassen [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bmp_options | [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) | BMP-alternativen. |

### Property: bits_per_pixel {#bits_per_pixel1}

Hämtar eller anger antalet bildbitar per pixel.

**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 3](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...


### Property: compression {#compression2}

Hämtar eller anger komprimeringstypen. Standardkomprimeringstypen är [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/), vilket möjliggör att spara en [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) med transparens.

**See also:**

**[Example # 1](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 2](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...

**[Example # 3](#example_208)**: Decompress BMP image which was previously compressed using DXT1 compression a...

**[Example # 4](#example_225)**: The example shows how to export a BMP from a PNG file while keeping the alpha...

**[Example # 5](#example_226)**: The example shows how to export a BMP with the RGB compression type.


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
### This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance. Several properties for BmpOptions instance are set before creating the actual image. Especially the Source property, that refers to the actual disk location in this case. {#example_4}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#Skapa en instans av `BmpOptions` och ange dess olika egenskaper
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24

	#Skapa en instans av `FileCreateSource` och tilldela den som `source` för instansen av `BmpOptions`
	#Den andra `Boolean`-parametern bestämmer om filen som ska skapas är_temporal eller inte
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp", False)

	#Skapa en instans av Image och initiera den med en instans av BmpOptions genom att anropa Create-metoden
	with Image.create(bmp_options, 500, 500) as image:
		#utför någon bildbehandling
		# spara alla ändringar
		image.save()


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

### The following example shows how to set a palette to a BMP image to reduce its output size. {#example_20}
``` python

from aspose.pycore import as_of
from aspose.imaging import Point, Color, Graphics, ColorPaletteHelper
from aspose.imaging.brushes import LinearGradientBrush
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.imageoptions import BmpOptions
from os.path import join as path_join

# Skapa en BMP-bild 100 x 100 px.
with BmpImage(100, 100) as bmpImage:
	# Den linjära gradienten från övre vänstra till nedre högra hörnet av bilden.
	brush = LinearGradientBrush(Point(0, 0), Point(bmpImage.width, bmpImage.height),
								Color.red,
								Color.green)
	# Fyll hela bilden med den linjära gradientpenseln.
	gr = Graphics(bmpImage)
	gr.fill_rectangle(brush, bmpImage.bounds)
	# Hämta den närmaste 8-bitars färgpaletten som täcker så många pixlar som möjligt, så att en palettiserad bild
	# är nästan visuellt omöjlig att skilja från en bmp utan palett
	palette = ColorPaletteHelper.get_close_image_palette(bmpImage, 256)
	# 8-bitars palett innehåller högst 256 färger.
	saveOptions = BmpOptions()
	saveOptions.palette = palette
	saveOptions.bits_per_pixel = 8
	
	with stream_ext.create_memory_stream() as stream:
		bmpImage.save(stream, saveOptions)
		print(f"The size of image with palette is {stream.tell()} bytes.")
		stream.seek(0)
		bmpImage.save(stream)
		print(f"The size of image without palette is {stream.tell()} bytes.")

# Utdata ser ut så här:
# Storleken på bilden med palett är 11078 byte.
# Storleken på bilden utan palett är 40054 byte.

```

### The following example loads a BMP image and saves it back to BMP using various save options. {#example_91}
``` python
from aspose.imaging import Image, RasterImage, ColorPaletteHelper, ResolutionSetting
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.fileformats.bmp import BitmapCompression
import os
import aspose.pycore as aspycore

directory = "c:\\temp\\"

with Image.load(os.path.join(directory, "sample.bmp")) as image:
	
	rasterImage = aspycore.as_of(image, RasterImage)

	# Skapa BmpOptions
	saveOptions = BmpOptions()

	# Använd 8 bitar per pixel för att minska storleken på utdatafilen.
	saveOptions.bits_per_pixel = 8

	# Ställ in den närmaste 8-bitars färgpaletten som täcker det maximala antalet bildpixlar, så att en palettiserad bild
	# är nästan visuellt omöjlig att skilja från en icke-paletiserad.
	saveOptions.palette = ColorPaletteHelper.get_close_image_palette(rasterImage, 256)

	# Spara utan komprimering.
	# Du kan också använda RLE-8-komprimering för att minska storleken på den resulterande bilden.
	saveOptions.compression = BitmapCompression.RGB

	# Ställ in horisontell och vertikal upplösning till 96 dpi.
	saveOptions.resolution_settings = ResolutionSetting(96.0, 96.0)

	image.save(os.path.join(directory, "sample.bmpoptions.bmp"), saveOptions)


```

### The following example creates a palettized grayscale BMP image and then saves it to a file. {#example_92}
``` python

from os.path import join as path_join
from aspose.imaging import Image, ColorPaletteHelper, ResolutionSetting, Graphics, Point, Color
from aspose.imaging.sources import FileCreateSource
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.fileformats.bmp import BitmapCompression
from aspose.imaging.brushes import LinearGradientBrush

directory = "c:\\temp\\"
createOptions = BmpOptions()

# Spara till en fil
createOptions.source = FileCreateSource(path_join(directory, "output.palette8bit.bmp"), False)
	
# Använd 8 bitar per pixel för att minska storleken på utdatafilen.
createOptions.bits_per_pixel = 8

# Ställ in den standard 8-bitars gråskala färgpaletten som täcker alla gråskalefärger.
# Om den bearbetade bilden bara innehåller gråskalefärger, så är dess palettiserade version
# är visuellt omöjlig att skilja från en icke-paletiserad.
createOptions.palette = ColorPaletteHelper.create_8_bit_grayscale(False)

# Spara utan komprimering.
# Du kan också använda RLE-8-komprimering för att minska storleken på den resulterande bilden.
createOptions.compression = BitmapCompression.RGB

# Ställ in horisontell och vertikal upplösning till 96 dpi.
createOptions.resolution_settings = ResolutionSetting(96.0, 96.0)

# Skapa en BMP-bild på 100 x 100 px och spara den till en fil.
with Image.create(createOptions, 100, 100) as image:
	graphics = Graphics(image)
	gradientBrush = LinearGradientBrush(Point(0, 0), Point(image.width, image.height), Color.black, Color.white)
	# Fyll bilden med ett gråskaleförlopp
	graphics.fill_rectangle(gradientBrush, image.bounds)
	image.save()


```

### Decompress BMP image which was previously compressed using DXT1 compression algorithm. {#example_208}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions

with Image.load("CompressedTiger.bmp") as image:
	image.save("DecompressedTiger.bmp", BmpOptions())


```

### The example shows how to export a BMP from a PNG file while keeping the alpha channel, save a BMP file with transparency. {#example_225}
``` python
from aspose.imaging import Image
from aspose.imaging.fileformats.png import BmpOptions

source_path = "input.png"
output_path_def = "result_def.bmp"
output_path_def_2 = "result_def-2.bmp"
output_path_bitfields = "result_bitfields.bmp"
# Läs in en PNG-bild från en fil.
with Image.load(source_path) as pngImage:
	# BMP-bild sparas med transparensstöd som standard.
	# Om du vill ange sådant läge explicit bör BmpOptions `compression`-egenskap sättas till BitmapCompression.BITFIELDS.
	# Komprimeringsmetoden BitmapCompression.BITFIELDS är standardkomprimeringsmetoden i BmpOptions.
	# Samma resultat vid export av en Bmp-bild med transparens kan därför uppnås på något av följande sätt.
	# Med implicita standardalternativ:
	pngImage.save(output_path_def)
	# Med explicita standardalternativ:
	pngImage.save(output_path_def_2, BmpOptions())
	# Anger komprimeringsmetoden BitmapCompression.BITFIELDS:
	bmp_options = BmpOptions()
	bmp_options.compression = BitmapCompression.BITFIELDS
	pngImage.save(output_path_bitfields, bmp_options)


```

### The example shows how to export a BMP with the RGB compression type. {#example_226}
``` python

from aspose.imaging import Image
from aspose.imaging.fileformats.bmp import BitmapCompression
from aspose.imaging.imageoptions import BmpOptions

source_path = "input.png"
output_path = "output.png"
# Läs in en PNG-bild från en fil.
with Image.load(source_path) as pngImage:
	# BMP-bild sparas med transparensstöd som standard, vilket uppnås genom att använda komprimeringsmetoden BitmapCompression.BITFIELDS.
	# För att spara en BMP-bild med RGB-komprimeringsmetoden bör BmpOptions med `compression`-egenskapen satt till BitmapCompression.RGB anges.
	bmp_options = BmpOptions()
	bmp_options.compression = BitmapCompression.RGB
	pngImage.save(output_path, bmp_options)


```

