---
title: OdgRasterizationOptions Class
type: docs
weight: 220
url: /python-net/aspose.imaging.imageoptions/odgrasterizationoptions/
---

**Summary:** The Odg rasterization options

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.OdgRasterizationOptions

**Inheritance:** OdRasterizationOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [OdgRasterizationOptions()](#OdgRasterizationOptions__1) | Initializes a new instance of the OdgRasterizationOptions class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Gets or sets a background color. |
| border_x | float | r/w | Gets or sets the border X. |
| border_y | float | r/w | Gets or sets the border Y. |
| center_drawing | bool | r/w | Gets or sets a value indicating whether center drawing. |
| draw_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Gets or sets a foreground color. |
| page_height | float | r/w | Gets or sets the page height.<br/>            If the value is 0, the source image aspect ratio will be preserved. |
| page_size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Gets or sets the page size.<br/>            If one of [SizeF](/imaging/python-net/aspose.imaging/sizef/) dimensions is 0, the source image aspect ratio will be preserved. |
| page_width | float | r/w | Gets or sets the page width.<br/>            If the value is 0, the source image aspect ratio will be preserved. |
| positioning | [PositioningTypes](/imaging/python-net/aspose.imaging.imageoptions/positioningtypes/) | r/w | Gets or sets the positioning. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Gets or sets the smoothing mode. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Gets or sets the text rendering hint. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Creates a new object that is a shallow copy of the current instance. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Copies to. |


### Constructor: OdgRasterizationOptions() {#OdgRasterizationOptions__1}


```
 OdgRasterizationOptions() 
```

Initializes a new instance of the OdgRasterizationOptions class

### Method: clone() {#clone__1}


```
 clone() 
```

Creates a new object that is a shallow copy of the current instance.

**Returns**

| Type | Description |
| :- | :- |
| System.Object | A new object that is a shallow copy of this instance. |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

Copies to.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | The vector rasterization options. |

## **Examples**
### The following example shows how to export a FODG (Flat XML ODF Template) image to PDF format. {#example_168}
``` python
from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image, Color, SizeF
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import OdgRasterizationOptions, PdfOptions

dir_: str = "c:\\aspose.imaging\\issues\\net\\3635"
input_file_name: str = join(dir_, "VariousObjectsMultiPage.fodg")
output_file_name: str = input_file_name + ".pdf"
with Image.load(input_file_name) as image:
	rasterization_options = OdgRasterizationOptions()
	rasterization_options.background_color = Color.white
	rasterization_options.page_size = aspycore.cast(SizeF, image.size)
	save_options = PdfOptions()
	save_options.vector_rasterization_options = rasterization_options
	image.save(output_file_name, save_options)


```

