---
title: ApngOptions Class
type: docs
weight: 10
url: /python-net/aspose.imaging.imageoptions/apngoptions/
---

**Summary:** The API for Animated PNG (Animated Portable Network Graphics) image file format<br/>            creation is a dynamic tool for developers seeking to generate captivating<br/>            animated images. With customizable options such as frame duration and the<br/>            number of times to loop, this API allows for fine-tuning animated content<br/>            according to specific needs. Whether creating engaging web graphics or<br/>            interactive visuals, you can leverage this API to seamlessly incorporate<br/>            APNG images with precise control over animation parameters.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.ApngOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, PngOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ApngOptions()](#ApngOptions__1) | Initializes a new instance of the [ApngOptions](/imaging/python-net/aspose.imaging.imageoptions/apngoptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| DEFAULT_COMPRESSION_LEVEL [static] | [PngCompressionLevel](/imaging/python-net/aspose.imaging.imageoptions/pngcompressionlevel/) | r | The default compression level. |
| bit_depth | System.Byte | r/w | Gets or sets the bit depth values in range of 1, 2, 4, 8, 16.<br/>            <br/><br/>            Mind the next limits:<br/>            <br/><br/>[PngColorType.INDEXED_COLOR](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) supports bit depth of 1, 2, 4, 8.<br/>            <br/><br/>[PngColorType.GRAYSCALE](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/), [PngColorType.GRAYSCALE_WITH_ALPHA](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) support bit depth of 8.<br/>            <br/><br/>[PngColorType.TRUECOLOR](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/), [PngColorType.TRUECOLOR_WITH_ALPHA](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) support bit depth of 8, 16.<br/>            <br/> |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| color_type | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | r/w | Gets or sets the type of the color. |
| compression_level | int | r/w | Gets or sets the [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) compression level. |
| [default_frame_time](#default_frame_time1) | int | r/w | Gets or sets the default frame duration. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Gets or sets Exif instance. |
| filter_type | [PngFilterType](/imaging/python-net/aspose.imaging.fileformats.png/pngfiltertype/) | r/w | Gets or sets the filter type used during png file save process. |
| full_frame | bool | r/w | Gets or sets a value indicating whether [full frame]. |
| keep_metadata | bool | r/w | Gets a value whether to keep original image metadata on export. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | The multipage options |
| [num_plays](#num_plays2) | int | r/w | Gets or sets the number of times to loop animation.<br/>            0 indicates infinite looping. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Gets or sets the color palette. |
| png_compression_level | [PngCompressionLevel](/imaging/python-net/aspose.imaging.imageoptions/pngcompressionlevel/) | r/w | Gets or sets the [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) compression level. |
| progressive | bool | r/w | Gets or sets a value indicating whether a [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) is progressive. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Gets or sets the resolution settings. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Gets or sets the source to create image in. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Gets or sets the vector rasterization options. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Gets or sets Xmp data. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Creates a memberwise clone of this instance. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Tries to set a _metadata_ instance, if this [Image](/imaging/python-net/aspose.imaging/image/) instance supports and implements [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) instance. |


### Constructor: ApngOptions() {#ApngOptions__1}


```
 ApngOptions() 
```

Initializes a new instance of the [ApngOptions](/imaging/python-net/aspose.imaging.imageoptions/apngoptions/) class.

### Property: default_frame_time {#default_frame_time1}

Gets or sets the default frame duration.

**See also:**

**[Example # 1](#example_195)**: The following example shows how to export apng APNG file format from other no...


### Property: num_plays {#num_plays2}

Gets or sets the number of times to loop animation.<br/>            0 indicates infinite looping.

**See also:**

**[Example # 1](#example_194)**: The following example shows how to export to APNG file format.


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
| bool | True if _metadata_ is not null and the [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) instance <br/>            supports and/or implements [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) instance; otherwise, false. |


## **Examples**
### The following example shows how to export to APNG file format. {#example_194}
``` python

import aspose.pycore as aspycore
from aspose.imaging import *
from aspose.imaging.imageoptions import *

with Image.load("Animation1.webp") as image:
	# Export to APNG animation with unlimited animation cycles as default
	image.save("Animation1.webp.png", ApngOptions())
	# Setting up animation cycles
	obj_init = ApngOptions()
	# 5 cycles
	obj_init.num_plays = 5
	image.save("Animation2.webp.png", obj_init)


```

### The following example shows how to export apng APNG file format from other non-animated multi-page format. {#example_195}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import ApngOptions

with Image.load("img4.tif") as image:
	# Setting up the default frame duration
	obj_init = ApngOptions()
	# 500 ms
	obj_init.default_frame_time = 500
	image.save("img4.tif.500ms.png", obj_init)
	obj_init2 = ApngOptions()
	# 250 ms
	obj_init2.default_frame_time = 250
	image.save("img4.tif.250ms.png", obj_init2)


```

