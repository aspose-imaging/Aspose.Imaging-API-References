---
title: PngOptions Class
type: docs
weight: 240
url: /python-net/aspose.imaging.imageoptions/pngoptions/
---

**Summary:** The png file format create options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PngOptions

**Inheritance:** ImageOptionsBase

**Aspose.Imaging Version:** 23.6

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PngOptions()](#PngOptions__1) | Initializes a new instance of the [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) class. |
| [PngOptions(png_options)](#PngOptions_png_options_2) | Initializes a new instance of the [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| DEFAULT_COMPRESSION_LEVEL [static] | int | r | The default compression level. |
| bit_depth | byte | r/w | The bit depth. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [color_type](#color_type1) | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | r/w | Gets or sets the type of the color. |
| [compression_level](#compression_level2) | int | r/w | The png image compression level in the 0-9 range, where 9 is maximum compression and 0 is store mode. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| filter_type | [PngFilterType](/imaging/python-net/aspose.imaging.fileformats.png/pngfiltertype/) | r/w | Gets or sets the filter type used during png file save process. |
| full_frame | bool | r/w | Gets or sets a value indicating whether [full frame]. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions) | r/w | The multipage options |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | r/w | Gets or sets the color palette. |
| [progressive](#progressive3) | bool | r/w | Gets or sets a value indicating whether this [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) is progressive. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting) | r/w | Gets or sets the resolution settings. |
| source | [Source](/imaging/python-net/aspose.imaging/source) | r/w | Gets or sets the source to create image in. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions) | r/w | Gets or sets the vector rasterization options. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Gets or sets the XMP metadata container. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clones this instance. |


### Constructor: PngOptions() {#PngOptions__1}


```
 PngOptions() 
```

Initializes a new instance of the [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) class.

### Constructor: PngOptions(png_options) {#PngOptions_png_options_2}


```
 PngOptions(png_options) 
```

Initializes a new instance of the [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| png_options | [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions) | The PNG options. |

### Property: color_type {#color_type1}

Gets or sets the type of the color.

**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...

### Property: compression_level {#compression_level2}

The png image compression level in the 0-9 range, where 9 is maximum compression and 0 is store mode.

**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...

### Property: progressive {#progressive3}

Gets or sets a value indicating whether this [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) is progressive.

**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...

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
### This example uses Graphics class to create primitive shapes on the Image surface. To demonstrate the operation, the example creates a new Image in PNG format and draw primitive shapes on Image surface using Draw methods exposed by Graphics class {#example_12}
``` python

from aspose.imaging import Image, RotateFlipType, Graphics, Color, Pen, Rectangle, Point, Size,\
	Font, PointF
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.psd import CompressionMethod, ColorModes
from aspose.imaging.sources import StreamSource

from os.path import join as path_join

#Creates an instance of file stream
with open(r"C:\temp\output.png", "w+b") as stream:
	#Create an instance of PngOptions and set its various properties
	pngOptions = PngOptions()
	#Set the Source for PngOptions
	pngOptions.source = StreamSource(stream)
	#Create an instance of Image 
	with Image.create(pngOptions, 500, 500) as image:
		#Create and initialize an instance of Graphics class
		graphics = Graphics(image)
		#Clear Graphics surface
		graphics.clear(Color.wheat);
		#Draw an Arc by specifying the Pen object having Black color, 
		#a Rectangle surrounding the Arc, Start Angle and Sweep Angle
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#Draw a Bezier by specifying the Pen object having Blue color and co-ordinate Points.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#Draw a Curve by specifying the Pen object having Green color and an array of Points
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#Draw an Ellipse using the Pen object and a surrounding Rectangle
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#Draw a Line 
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#Draw a Pie segment
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#Draw a Polygon by specifying the Pen object having Red color and an array of Points
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#Draw a Rectangle
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#Create a SolidBrush object and set its various properties
		brush = SolidBrush()
		brush.color = Color.purple
		#Draw a String using the SolidBrush object and Font, at specific Point
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# save all changes.
		image.save();

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

### The following example shows how to compress a PNG image, using indexed color with best fit palette {#example_21}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, ColorPaletteHelper, RasterImage, PaletteMiningMethod
from aspose.imaging.fileformats.png import PngColorType

# Loads png image        
sourceFilePath = "OriginalRings.png"
outputFilePath = "OriginalRingsOutput.png"
with Image.load(sourceFilePath) as image:
	png_options = PngOptions()
	png_options.progressive = True
	# Use indexed color type
	png_options.color_type = PngColorType.INDEXED_COLOR
	# Use maximal compression
	png_options.compression_level = 9
	# Get the closest 8-bit color palette, covering as many pixels as possible, so that an image
	# with palette is almost visually indistinguishable from an image without a palette.
	png_options.palette = ColorPaletteHelper.get_close_image_palette(
						as_of(image, RasterImage), 256, 
						PaletteMiningMethod.HISTOGRAM)
		 
	image.save(outputFilePath, png_options);
}
# The output file size should be significantly reduced

```

