---
title: "ImageOptionsBase‑klass"
type: docs
weight: 5760
url: /sv/python-net/aspose.imaging/imageoptionsbase/
---

**Summary:** The image base options.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageOptionsBase

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, DisposableObject

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [buffer_size_hint](#buffer_size_hint1) | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| disposed | bool | r | Hämtar ett värde som indikerar om den här instansen är frigjord. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Hämtar eller anger Exif-data. |
| full_frame | bool | r/w | Hämtar eller anger ett värde som indikerar om [full frame]. |
| keep_metadata | bool | r/w | Hämtar ett värde som anger om originalmetadata för bilden ska behållas vid export. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Flersidiga alternativ |
| [palette](#palette2) | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Hämtar eller anger färgpaletten. |
| [resolution_settings](#resolution_settings3) | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Hämtar eller anger upplösningsinställningarna. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Hämtar eller anger källan där bilden ska skapas. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Hämtar eller anger vektorrasteriseringsalternativen. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Hämtar eller anger XMP-metadatabehållaren. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Skapar en medlemsvis klon av detta objekt. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Försöker sätta en _metadata_-instans, om detta [Image](/imaging/python-net/aspose.imaging/image/)-instans stödjer och implementerar [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)-instansen. |


### Property: buffer_size_hint {#buffer_size_hint1}

Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar.

**See also:**

**[Example # 1](#example_180)**: The following example shows how to set a memory limit when creating a new JPE...


### Property: palette {#palette2}

Hämtar eller anger färgpaletten.

**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...

**[Example # 3](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...


### Property: resolution_settings {#resolution_settings3}

Hämtar eller anger upplösningsinställningarna.

**See also:**

**[Example # 1](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 2](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...


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

### The following example shows how to set a memory limit when creating a new JPEG image. The memory limit is the maximum allowed size (in megabytes) for all internal buffers. {#example_180}
``` python
from os.path import join
from aspose.imaging import Image
from aspose.imaging.sources import FileCreateSource
from aspose.imaging.imageoptions import JpegOptions
from aspose.imaging.fileformats.jpeg import JpegCompressionMode

dir_: str = "c:\\aspose.imaging\\issues\\net\\3404\\"
# Ställer in en minnesgräns på 50 megabyte för målbilden som skapas
create_options = JpegOptions()
create_options.compression_type = JpegCompressionMode.PROGRESSIVE
create_options.buffer_size_hint = 50
create_options.source = FileCreateSource(join(dir_, "createdFile.jpg"), False)
with Aspose.Imaging.Image.create(create_options, 1000, 1000) as image:
	# spara till samma plats
	image.save()


```

