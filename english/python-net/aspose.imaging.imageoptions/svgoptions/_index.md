---
title: SvgOptions Class
type: docs
weight: 300
url: /python-net/aspose.imaging.imageoptions/svgoptions/
---

**Summary:** Create Scalar Vector Graphics (SVG) image files with our API, utilizing versatile<br/>            options for color types and compression levels. Seamlessly customize your<br/>            SVG images with precision, ensuring optimal quality and compatibility for your design needs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.SvgOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SvgOptions()](#SvgOptions__1) | Initializes a new instance of the [SvgOptions](/imaging/python-net/aspose.imaging.imageoptions/svgoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| callback | [ISvgResourceKeeperCallback](/imaging/python-net/aspose.imaging.fileformats.svg/isvgresourcekeepercallback/) | r/w | Gets or sets the storing strategy for embedded resousces of [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) such as fonts, nested rasters. |
| color_type | [SvgColorMode](/imaging/python-net/aspose.imaging.fileformats.svg/svgcolormode/) | r/w | Gets or sets the color type for SVG image. |
| [compress](#compress1) | bool | r/w | Gets or sets a value indicating whether the output image must to be compressed. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Gets or sets the Exif data. |
| full_frame | bool | r/w | Gets or sets a value indicating whether [full frame]. |
| keep_metadata | bool | r/w | Gets a value whether to keep original image metadata on export. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | The multipage options |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Gets or sets the color palette. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Gets or sets the resolution settings. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Gets or sets the source to create image in. |
| [text_as_shapes](#text_as_shapes2) | bool | r/w | Gets or sets a value indicating whether text must be rendered as shapes. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Gets or sets the vector rasterization options. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Gets or sets the XMP metadata container. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Creates a memberwise clone of this instance. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Tries to set a _metadata_ instance, if this [Image](/imaging/python-net/aspose.imaging/image/) instance supports and implements [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) instance. |


### Constructor: SvgOptions() {#SvgOptions__1}


```
 SvgOptions() 
```

Initializes a new instance of the [SvgOptions](/imaging/python-net/aspose.imaging.imageoptions/svgoptions/).

### Property: compress {#compress1}

Gets or sets a value indicating whether the output image must to be compressed.

**See also:**

**[Example # 1](#example_174)**: The following example shows how to convert a svg images to svgz format


### Property: text_as_shapes {#text_as_shapes2}

Gets or sets a value indicating whether text must be rendered as shapes.

**See also:**

**[Example # 1](#example_158)**: This example shows how to load a WMF image from a file and convert it to SVG ...


### Method: clone() {#clone__1}


```
 clone() 
```

Creates a memberwise clone of this instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | A memberwise clone of this instance. |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_2}


```
 try_set_metadata(metadata) 
```

Tries to set a _metadata_ instance, if this [Image](/imaging/python-net/aspose.imaging/image/) instance supports and implements [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) instance.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | The metadata. |

**Returns**

| Type | Description |
| :- | :- |
| bool | True, if the [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) instance supports and/or implements [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) instance; otherwise, false. |


## **Examples**
### This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions. {#example_158}
``` python

from aspose.pycore import as_of, cast
from aspose.imaging import Image, Color, SizeF
from aspose.imaging.fileformats.wmf import WmfImage, WmfRenderMode
from aspose.imaging.imageoptions import SvgOptions, WmfRasterizationOptions

# Using Aspose.Imaging.Image.Load is a unified way to load all types of images including WMF.
with as_of(Image.load("test.wmf") as image:
	saveOptions = SvgOptions()
	# Text will be converted to shapes.
	saveOptions.text_as_shapes = True
	rasterizationOptions = WmfRasterizationOptions()
	# The background color of the drawing surface.
	rasterizationOptions.background_color = Color.white_smoke
	# The page size.
	rasterizationOptions.page_size = cast(SizeF, wmfImage.size)
	# If embedded emf exists, then render emf; otherwise render wmf.
	rasterizationOptions.render_mode = WmfRenderMode.AUTO
	saveOptions.vector_rasterization_options = rasterizationOptions
	wmfImage.save("test.output.svg", saveOptions)


```

### The following example shows how to convert a svgz images to svg fromat {#example_171}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image, SizeF
from aspose.imaging.imageoptions import SvgRasterizationOptions, SvgOptions
from os.path import join

file: str = "example.svgz"
base_folder: str = join("D:", "Compressed")
input_file: str = join(base_folder, file)
out_file: str = input_file + ".svg"
with Image.load(input_file) as image:
	obj_init = SvgRasterizationOptions()
	obj_init.page_size = aspycore.cast(SizeF, image.size)
	obj_init2 = SvgOptions()
	obj_init2.vector_rasterization_options = obj_init
	image.save(out_file, obj_init2)


```

### The following example shows how to convert a svg images to svgz format {#example_174}
``` python

from os.path import join as path_combine
import aspose.pycore as aspycore
from aspose.imaging import Image, SizeF
from aspose.imaging.imageoptions import SvgRasterizationOptions, SvgOptions

file = "juanmontoya_lingerie.svg"
base_folder = path_combine("D:", "Compressed")
input_file = path_combine(base_folder, file)
out_file = input_file + ".svgz"
with Image.load(input_file) as image:
	vector_rasterization_options = SvgRasterizationOptions()
	vector_rasterization_options.page_size = aspycore.cast(SizeF, image.size)
	obj_init2 = SvgOptions()
	obj_init2.vector_rasterization_options = vector_rasterization_options
	obj_init2.compress = True
	image.save(out_file, obj_init2)            


```

