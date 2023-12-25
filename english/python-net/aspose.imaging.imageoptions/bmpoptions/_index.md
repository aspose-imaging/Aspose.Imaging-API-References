---
title: BmpOptions Class
type: docs
weight: 30
url: /python-net/aspose.imaging.imageoptions/bmpoptions/
---

**Summary:** The bmp file format creation options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.BmpOptions

**Inheritance:** ImageOptionsBase

**Aspose.Imaging Version:** 23.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BmpOptions()](#BmpOptions__1) | Initializes a new instance of the [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) class. |
| [BmpOptions(bmp_options)](#BmpOptions_bmp_options_2) | Initializes a new instance of the [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [bits_per_pixel](#bits_per_pixel1) | int | r/w | Gets or sets the image bits per pixel count. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [compression](#compression2) | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | r/w | Gets or sets the compression type. The default compression type is [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/), that allows saving a [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) with transparency. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| full_frame | bool | r/w | Gets or sets a value indicating whether [full frame]. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions) | r/w | The multipage options |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | r/w | Gets or sets the color palette. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting) | r/w | Gets or sets the resolution settings. |
| source | [Source](/imaging/python-net/aspose.imaging/source) | r/w | Gets or sets the source to create image in. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions) | r/w | Gets or sets the vector rasterization options. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Gets or sets the XMP metadata container. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clones this instance. |


### Constructor: BmpOptions() {#BmpOptions__1}


```
 BmpOptions() 
```

Initializes a new instance of the [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) class.

### Constructor: BmpOptions(bmp_options) {#BmpOptions_bmp_options_2}


```
 BmpOptions(bmp_options) 
```

Initializes a new instance of the [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bmp_options | [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions) | The BMP options. |

### Property: bits_per_pixel {#bits_per_pixel1}

Gets or sets the image bits per pixel count.

**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...


### Property: compression {#compression2}

Gets or sets the compression type. The default compression type is [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/), that allows saving a [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) with transparency.

**See also:**

**[Example # 1](#example_89)**: The example shows how to export a BMP with the RGB compression type.


### Method: clone() {#clone__1}


```
 clone() 
```

Clones this instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | Returns shallow copy of this instance |


## **Examples**
### This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance. Several properties for BmpOptions instance are set before creating the actual image. Especially the Source property, that refers to the actual disk location in this case. {#example_4}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#Create an instance of `BmpOptions` and set its various properties
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24

	#Create an instance of `FileCreateSource` and assign it as `source` for the instance of `BmpOptions`
	#Second `Boolean` parameter determines if the file to be created is_temporal or not
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp", False)

	#Create an instance of Image and initialize it with instance of BmpOptions by calling Create method
	with Image.create(bmp_options, 500, 500) as image:
		#do some image processing
		# save all changes
		image.save()


```

### This example demonstrates the use of different classes from `imageoptions` package for export purposes. A gif image is loaded as an instance of Image and then exported out to several formats. {#example_15}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions, JpegOptions, PngOptions, TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from os.path import join as path_join

directory = "c:\\temp\\"
#Load an existing gif image as an instance of Image class
with Image.load(path_join(directory, "sample.gif")) as image:
	# Export to BMP file format using the default options
	image.save(path_join(directory, "output.bmp"), BmpOptions())
	# Export to JPEG file format using the default options
	image.save(path_join(directory, "output.jpg"), JpegOptions())
	# Export to PNG file format using the default options
	image.save(path_join(directory, "output.png"), PngOptions())
	# Export to TIFF file format using the default options
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

# Create a BMP image 100 x 100 px.
with BmpImage(100, 100) as bmpImage:
	# The linear gradient from the left-top to the right-bottom corner of the image.
	brush = LinearGradientBrush(Point(0, 0), Point(bmpImage.width, bmpImage.height),
								Color.red,
								Color.green)
	# Fill the entire image with the linear gradient brush.
	gr = Graphics(bmpImage)
	gr.fill_rectangle(brush, bmpImage.bounds)
	# Get the closest 8-bit color palette which covers as many pixels as possible, so that a palettized image
	# is almost visually indistinguishable from a bmp without palette
	palette = ColorPaletteHelper.get_close_image_palette(bmpImage, 256)
	# 8-bit palette contains at most 256 colors.
	saveOptions = BmpOptions()
	saveOptions.palette = palette
	saveOptions.bits_per_pixel = 8
	
	with stream_ext.create_memory_stream() as stream:
		bmpImage.save(stream, saveOptions)
		print(f"The size of image with palette is {stream.tell()} bytes.")
		stream.seek(0)
		bmpImage.save(stream)
		print(f"The size of image without palette is {stream.tell()} bytes.")

# The output looks like this:
# The size of image with palette is 11078 bytes.
# The size of image without palette is 40054 bytes.

```

### The example shows how to export a BMP with the RGB compression type. {#example_89}
``` python

from aspose.imaging import Image
from aspose.imaging.fileformats.bmp import BitmapCompression
from aspose.imaging.imageoptions import BmpOptions

source_path = "input.png"
output_path = "output.png"
# Load a PNG image from a file.
with Image.load(source_path) as pngImage:
	# BMP image is saved with transparency support by default, that is achieved by using the BitmapCompression.BITFIELDS compression method. 
	# To save a BMP image with the RGB compression method, the BmpOptions with the `compression` property set to BitmapCompression.RGB should be specified.
	bmp_options = BmpOptions()
	bmp_options.compression = BitmapCompression.RGB
	pngImage.save(output_path, bmp_options)


```

