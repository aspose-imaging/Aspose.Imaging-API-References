---
title: Html5CanvasOptions Class
type: docs
weight: 130
url: /python-net/aspose.imaging.imageoptions/html5canvasoptions/
---

**Summary:** Create HTML5 Canvas files effortlessly with our API, allowing you to seamlessly<br/>            combine elements like forms, text, images, animations, and links. Benefit from<br/>            robust features including tag identifier and encoding settings support,<br/>            ensuring optimal performance and customization for your web projects.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.Html5CanvasOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Html5CanvasOptions()](#Html5CanvasOptions__1) | Initializes a new instance of the [Html5CanvasOptions](/imaging/python-net/aspose.imaging.imageoptions/html5canvasoptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| canvas_tag_id | string | r/w | Gets or sets the canvas tag identifier. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| encoding | string | r/w | Gets or sets the encoding. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Gets or sets the Exif data. |
| full_frame | bool | r/w | Gets or sets a value indicating whether [full frame]. |
| full_html_page | bool | r/w | Gets or sets a value indicating whether the full HTML page should be generated. |
| keep_metadata | bool | r/w | Gets a value whether to keep original image metadata on export. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | The multipage options |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Gets or sets the color palette. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Gets or sets the resolution settings. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Gets or sets the source to create image in. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Gets or sets the vector rasterization options. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Gets or sets the XMP metadata container. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Creates a memberwise clone of this instance. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Tries to set a _metadata_ instance, if this [Image](/imaging/python-net/aspose.imaging/image/) instance supports and implements [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) instance. |


### Constructor: Html5CanvasOptions() {#Html5CanvasOptions__1}


```
 Html5CanvasOptions() 
```

Initializes a new instance of the [Html5CanvasOptions](/imaging/python-net/aspose.imaging.imageoptions/html5canvasoptions/) class.

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
### Any vector image (SVG, WMF, CMX, etc.) can be used as a source for your Canvas images. The following code creates a simple Canvas image. {#example_196}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import Html5CanvasOptions, SvgRasterizationOptions

with Image.load("Sample.svg") as image:
	export_options = Html5CanvasOptions()
	export_options.vector_rasterization_options = SvgRasterizationOptions()
	image.save("Canvas.html", export_options)


```

### You can embed more than one Canvas image within HTML page or update already exsiting page. In order to do that you need to export only the Canvas tag. {#example_197}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import Html5CanvasOptions, SvgRasterizationOptions

with Image.load("Sample.svg") as image:
	options = Html5CanvasOptions()
	options.vector_rasterization_options = SvgRasterizationOptions()
	options.full_html_page = False
	image.save("Canvas.html", options)


```

