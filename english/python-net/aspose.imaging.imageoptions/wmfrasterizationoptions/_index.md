---
title: WmfRasterizationOptions Class
type: docs
weight: 380
url: /python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/
---

**Summary:** The Wmf rasterization options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.WmfRasterizationOptions

**Inheritance:** IHasXmpData, IHasMetadata, MetafileRasterizationOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WmfRasterizationOptions()](#WmfRasterizationOptions__1) | Initializes a new instance of the [WmfRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color) | r/w | Gets or sets a background color. |
| border_x | float | r/w | Gets or sets the border X. |
| border_y | float | r/w | Gets or sets the border Y. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| center_drawing | bool | r/w | Gets or sets a value indicating whether center drawing. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| draw_color | [Color](/imaging/python-net/aspose.imaging/color) | r/w | Gets or sets a foreground color. |
| full_frame | bool | r/w | Gets or sets a value indicating whether [full frame]. |
| keep_metadata | bool | r/w | Gets a value whether to keep original image metadata on export. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions) | r/w | The multipage options |
| page_height | float | r/w | Gets or sets the page height.<br/>            If the value is 0, the source image aspect ratio will be preserved. |
| page_size | [SizeF](/imaging/python-net/aspose.imaging/sizef) | r/w | Gets or sets the page size.<br/>            If one of [SizeF](/imaging/python-net/aspose.imaging/sizef/) dimensions is 0, the source image aspect ratio will be preserved. |
| page_width | float | r/w | Gets or sets the page width.<br/>            If the value is 0, the source image aspect ratio will be preserved. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | r/w | Gets or sets the color palette. |
| positioning | [PositioningTypes](/imaging/python-net/aspose.imaging.imageoptions/positioningtypes) | r/w | Gets or sets the positioning. |
| [render_mode](#render_mode1) | [WmfRenderMode](/imaging/python-net/aspose.imaging.fileformats.wmf/wmfrendermode/) | r/w | Gets or sets the WMF render mode. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting) | r/w | Gets or sets the resolution settings. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode) | r/w | Gets or sets the smoothing mode. |
| source | [Source](/imaging/python-net/aspose.imaging/source) | r/w | Gets or sets the source to create image in. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint) | r/w | Gets or sets the text rendering hint. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions) | r/w | Gets or sets the vector rasterization options. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Gets or sets Xmp data. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Creates a memberwise clone of this instance. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Copies this to _vectorRasterizationOptions_. |


### Constructor: WmfRasterizationOptions() {#WmfRasterizationOptions__1}


```
 WmfRasterizationOptions() 
```

Initializes a new instance of the [WmfRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/) class.

### Property: render_mode {#render_mode1}

Gets or sets the WMF render mode.

**See also:**

**[Example # 1](#example_150)**: This example shows how to load a WMF image from a file and convert it to SVG ...


### Method: clone() {#clone__1}


```
 clone() 
```

Creates a memberwise clone of this instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | A memberwise clone of this instance. |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

Copies this to _vectorRasterizationOptions_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions) | vectorRasterizationOptions |

## **Examples**
### This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions. {#example_150}
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

