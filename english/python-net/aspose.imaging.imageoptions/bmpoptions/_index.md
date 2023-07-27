---
title: BmpOptions Class
type: docs
weight: 30
url: /python-net/aspose.imaging.imageoptions/bmpoptions/
---

**Summary:** The bmp file format creation options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.BmpOptions

**Inheritance:** ImageOptionsBase

**Aspose.Imaging Version:** 23.6

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BmpOptions()](#BmpOptions__1) | Initializes a new instance of the [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) class. |
| [BmpOptions(bmp_options)](#BmpOptions_bmp_options_2) | Initializes a new instance of the [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- |
| bits_per_pixel | int | r/w | Gets or sets the image bits per pixel count. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | r/w | Gets or sets the compression type. The default compression type is [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/), that allows saving a [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) with transparency. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| full_frame | bool | r/w | Gets or sets a value indicating whether [full frame]. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions) | r/w | The multipage options |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | r/w | Gets or sets the color palette. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting) | r/w | Gets or sets the resolution settings. |
| source | [Source](/imaging/python-net/aspose.imaging/source) | r/w | Gets or sets the source to create image in. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions) | r/w | Gets or sets the vector rasterization options. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Gets or sets the XMP metadata container. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clones this instance. |


### Constructor: BmpOptions() {#BmpOptions__1}


```
 BmpOptions() 
```

Initializes a new instance of the [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) class.

### Constructor: BmpOptions(bmp_options) {#BmpOptions_bmp_options_2}


```
 BmpOptions(bmp_options) 
```

Initializes a new instance of the [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bmp_options | [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions) | The BMP options. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clones this instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | Returns shallow copy of this instance |


