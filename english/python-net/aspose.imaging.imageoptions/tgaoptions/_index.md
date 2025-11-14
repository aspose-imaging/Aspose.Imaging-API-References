---
title: TgaOptions Class
type: docs
weight: 320
url: /python-net/aspose.imaging.imageoptions/tgaoptions/
---

**Summary:** The TGA file format create options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.TgaOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TgaOptions()](#TgaOptions__1) | Initializes a new instance of the [TgaOptions](/imaging/python-net/aspose.imaging.imageoptions/tgaoptions/) class. |
| [TgaOptions(tga_options)](#TgaOptions_tga_options_2) | Initializes a new instance of the [TgaOptions](/imaging/python-net/aspose.imaging.imageoptions/tgaoptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Gets or sets the Exif data. |
| full_frame | bool | r/w | Gets or sets a value indicating whether [full frame]. |
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


### Constructor: TgaOptions() {#TgaOptions__1}


```
 TgaOptions() 
```

Initializes a new instance of the [TgaOptions](/imaging/python-net/aspose.imaging.imageoptions/tgaoptions/) class.


**See also:**

**[Example # 1](#example_193)**: Saving of the JPG image as a TGA image.


### Constructor: TgaOptions(tga_options) {#TgaOptions_tga_options_2}


```
 TgaOptions(tga_options) 
```

Initializes a new instance of the [TgaOptions](/imaging/python-net/aspose.imaging.imageoptions/tgaoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tga_options | [TgaOptions](/imaging/python-net/aspose.imaging.imageoptions/tgaoptions/) | The TGA options. |

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
### Saving of the JPG image as a TGA image. {#example_193}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import TgaOptions

with Image.load("test.jpg") as image:
	image.save("test.tga"", TgaOptions())
	

```

