---
title: DxfOptions Class
type: docs
weight: 80
url: /python-net/aspose.imaging.imageoptions/dxfoptions/
---

**Summary:** API for Drawing Interchange Format (DXF) vector image creation offers<br/>            tailored solutions for generating AutoCAD drawing files with precision and<br/>            flexibility. Designed specifically for working with text lines and Bezier<br/>            curves, developers can efficiently manipulate these elements, count Bezier<br/>            points, and convert curves into polylines for seamless exporting, ensuring<br/>            compatibility and fidelity in DXF vector images.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.DxfOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [DxfOptions()](#DxfOptions__1) | Initializes a new instance of the DxfOptions class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bezier_point_count | System.Byte | r/w | How many points to generate when converting Bezier curves to polylines, minimum 4. Used when [DxfOptions.text_as_lines](/imaging/python-net/aspose.imaging.imageoptions/dxfoptions/) and [DxfOptions.convert_text_beziers](/imaging/python-net/aspose.imaging.imageoptions/dxfoptions/) are both  	/// set to <c>true</c> |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| convert_text_beziers | bool | r/w | Works when [DxfOptions.text_as_lines](/imaging/python-net/aspose.imaging.imageoptions/dxfoptions/) is set to <c>true</c>. Wether to convert Bezier curves in text contours to multipoint polylines. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Gets or sets the Exif data. |
| full_frame | bool | r/w | Gets or sets a value indicating whether [full frame]. |
| keep_metadata | bool | r/w | Gets a value whether to keep original image metadata on export. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | The multipage options |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Gets or sets the color palette. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Gets or sets the resolution settings. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Gets or sets the source to create image in. |
| text_as_lines | bool | r/w | Whether text should be exported as contours consisting of polylines (default) or as editable Autocad TEXT entities.<br/>            If this option set |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Gets or sets the vector rasterization options. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Gets or sets the XMP metadata container. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Creates a memberwise clone of this instance. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Tries to set a _metadata_ instance, if this [Image](/imaging/python-net/aspose.imaging/image/) instance supports and implements [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) instance. |


### Constructor: DxfOptions() {#DxfOptions__1}


```
 DxfOptions() 
```

Initializes a new instance of the DxfOptions class

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
### This example demonstrates export to Dxf format {#example_3}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import DxfOptions
#Create Image instance and initialize it with an existing image file from disk location
with Image.load("input.svg") as image:
	options = DxfOptions()
	options.text_as_lines = True
	options.convert_text_beziers = True
	options.bezier_point_count = 20
	image.save("output.dxf", options)


```

