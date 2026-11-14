---
title: PdfOptions Class
type: docs
weight: 240
url: /python-net/aspose.imaging.imageoptions/pdfoptions/
---

**Summary:** The PDF options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PdfOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PdfOptions()](#PdfOptions__1) | Initializes a new instance of the [PdfOptions](/imaging/python-net/aspose.imaging.imageoptions/pdfoptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Gets or sets the Exif data. |
| full_frame | bool | r/w | Gets or sets a value indicating whether [full frame]. |
| keep_metadata | bool | r/w | Gets a value whether to keep the original image metadata on export. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | The multipage options |
| page_size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Gets or sets the size of the page. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Gets or sets the color palette. |
| pdf_core_options | [PdfCoreOptions](/imaging/python-net/aspose.imaging.fileformats.pdf/pdfcoreoptions/) | r/w | The PDF core options |
| pdf_document_info | [PdfDocumentInfo](/imaging/python-net/aspose.imaging.fileformats.pdf/pdfdocumentinfo/) | r/w | Gets or sets metadata for document. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Gets or sets the resolution settings. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Gets or sets the source to create image in. |
| use_original_image_resolution | bool | r/w | Gets or sets a value indicating to use the original image DPI resolution |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Gets or sets the vector rasterization options. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Gets or sets the XMP metadata container. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Creates a memberwise clone of this instance. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Tries to set a _metadata_ instance, if this [Image](/imaging/python-net/aspose.imaging/image/) instance supports and implements [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) instance. |


### Constructor: PdfOptions() {#PdfOptions__1}


```
 PdfOptions() 
```

Initializes a new instance of the [PdfOptions](/imaging/python-net/aspose.imaging.imageoptions/pdfoptions/) class.

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
### The following example shows how to convert a multipage vector image to PDF format in general way without referencing to a particular image type. {#example_204}
``` python
from os.path import join as path_join
import aspose.pycore as aspycore
from aspose.imaging import Image, IMultipageImage, IntRange, VectorImage, Color, TextRenderingHint, SmoothingMode
from aspose.imaging.imageoptions import PdfOptions, MultiPageOptions, VectorRasterizationOptions

dir_: str = "C:\\testdata\\2548"
input_file_path: str = path_join(dir_, "Multipage.cdr")
output_file_path: str = path_join(dir_, "Multipage.cdr.pdf")
export_options = PdfOptions()
with Image.load(input_file_path) as image:
	export_options.multi_page_options = None
	# Export only first two pages to the corresponding pages of the output PDF document.
	if aspycore.is_assignable(image, IMultipageImage)
		multipage_image = aspycore.as_of(image, IMultipageImage)
		if multipage_image.page_count > 2:
			export_options.multi_page_options = MultiPageOptions(IntRange(0, 2))

	if aspycore.is_assignable(image, VectorImage):
		export_options.vector_rasterization_options = aspycore.as_of(image.get_default_options([Color.white, image.width, image.height]), VectorRasterizationOptions)
		export_options.vector_rasterization_options.text_rendering_hint = TextRenderingHint.SINGLE_BIT_PER_PIXEL
		export_options.vector_rasterization_options.smoothing_mode = SmoothingMode.NONE

	image.save(output_file_path, export_options)


```

