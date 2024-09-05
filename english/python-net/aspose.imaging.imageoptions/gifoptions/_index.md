---
title: GifOptions Class
type: docs
weight: 120
url: /python-net/aspose.imaging.imageoptions/gifoptions/
---

**Summary:** The API for Graphical Interchange Format (GIF) raster image file creation offers<br/>            developers comprehensive options for generating GIF images with precise<br/>            control. With features to set background color, color palette, resolution,<br/>            interlaced type, transparent color, XMP metadata container, and image<br/>            compression, this API ensures flexibility and efficiency in creating optimized<br/>            and visually appealing GIFs tailored to specific application requirements.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.GifOptions

**Inheritance:** IHasXmpData, IHasMetadata, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifOptions()](#GifOptions__1) | Initializes a new instance of the [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/) class. |
| [GifOptions(gif_options)](#GifOptions_gif_options_2) | Initializes a new instance of the [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color) | r/w | Gets or sets the background color. |
| background_color_index | byte | r/w | Gets or sets the GIF background color index. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| color_resolution | byte | r/w | Gets or sets the GIF color resolution. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| do_palette_correction | bool | r/w | Gets or sets a value indicating whether palette correction is applied. |
| full_frame | bool | r/w | Gets or sets a value indicating whether [full frame]. |
| has_trailer | bool | r/w | Gets or sets a value indicating whether GIF has trailer. |
| has_transparent_color | bool | r/w | Gets or sets a value indicating whether GIF image has transparent color. |
| interlaced | bool | r/w | True if image should be interlaced. |
| is_palette_sorted | bool | r/w | Gets or sets a value indicating whether palette entries are sorted. |
| keep_metadata | bool | r/w | Gets a value whether to keep original image metadata on export. |
| loops_count | int | r/w | Gets or sets the loops count (Default 1 loop) |
| max_diff | int | r/w | Gets or sets the maximum allowed pixel difference. If greater than zero, lossy compression will be used.<br/>            Recommended value for optimal lossy compression is 80. 30 is very light compression, 200 is heavy.<br/>            It works best when only little loss is introduced, and due to limitation of the compression algorithm very high loss levels won't give as much gain.<br/>            The range of allowed values is [0, 1000]. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions) | r/w | The multipage options |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | r/w | Gets or sets the color palette. |
| pixel_aspect_ratio | byte | r/w | Gets or sets the GIF pixel aspect ratio. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting) | r/w | Gets or sets the resolution settings. |
| source | [Source](/imaging/python-net/aspose.imaging/source) | r/w | Gets or sets the source to create image in. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions) | r/w | Gets or sets the vector rasterization options. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Gets or sets the XMP metadata container. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clones this instance. |


### Constructor: GifOptions() {#GifOptions__1}


```
 GifOptions() 
```

Initializes a new instance of the [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/) class.

### Constructor: GifOptions(gif_options) {#GifOptions_gif_options_2}


```
 GifOptions(gif_options) 
```

Initializes a new instance of the [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| gif_options | [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions) | The GIF Options. |

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
### This example shows how to load a pixels information in an array of Color, manipulates the array and set it back to the image. To perform these operations, this example creates a new Image file (in GIF format) using MemoryStream object. {#example_7}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Color
from aspose.imaging.externsions import StreamExtensions as strm_ext
from aspose.imaging.imageoptions import GifOptions
from aspose.imaging.sources import StreamSource

# Create an instance of MemoryStream
with strm_ext.create_memory_stream() as stream:
	#Create an instance of GifOptions and set its various properties including the Source property
	with GifOptions() as gifOptions:
		gifOptions.source = StreamSource(stream)

		# Create an instance of Image
		with as_of(Image.create(gifOptions, 500, 500), RasterImage) as image:
			# Get the pixels of image by specifying the area as image boundary
			pixels = image.load_pixels(image.bounds)

			yellow_color = Color.yellow
			blue_color = Color.blue
			#Loop over the Array and sets color of alternative indexed pixel
			for index in range(pixel.length):
				if index % 2 == 0:
					#Set the indexed pixel color to yellow
					pixels[index] = yellow_color
				else:
					#Set the indexed pixel color to blue
					pixels[index] = blue_color

			#Apply the pixel changes to the image
			image.save_pixels(image.bounds, pixels)

			# save all changes.
			image.save()

	# Write MemoryStream to File
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

