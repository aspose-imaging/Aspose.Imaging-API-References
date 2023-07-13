---
title: BmpOptions Class
type: docs
weight: 30
url: /python-net/aspose.imaging.imageoptions/bmpoptions/
---

The bmp file format creation options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.BmpOptions

**Inheritance:** ImageOptionsBase

**Aspose.Imaging Version:** 23.6

The BmpOptions type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [BmpOptions()](#BmpOptions__0) | Initializes a new instance of the [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) class. |
| [BmpOptions(bmp_options)](#BmpOptions_bmp_options_1) | Initializes a new instance of the [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Gets or sets the XMP metadata container. |
| source | [Source](/imaging/python-net/aspose.imaging/source) | r/w | Gets or sets the source to create image in. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | r/w | Gets or sets the color palette. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting) | r/w | Gets or sets the resolution settings. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions) | r/w | Gets or sets the vector rasterization options. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions) | r/w | The multipage options |
| full_frame | bool | r/w | Gets or sets a value indicating whether [full frame]. |
| bits_per_pixel | int | r/w | Gets or sets the image bits per pixel count. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | r/w | Gets or sets the compression type. The default compression type is [BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/), that allows saving a [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) with transparency. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__2) | Clones this instance. |

### BmpOptions() {#BmpOptions__0}


```
 BmpOptions() 
```

Initializes a new instance of the [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) class.

### BmpOptions(bmp_options) {#BmpOptions_bmp_options_1}


```
 BmpOptions(bmp_options) 
```

Initializes a new instance of the [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bmp_options | [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions) | The BMP options. |

### clone() {#clone__2}


```
 clone() 
```

Clones this instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | Returns shallow copy of this instance |


