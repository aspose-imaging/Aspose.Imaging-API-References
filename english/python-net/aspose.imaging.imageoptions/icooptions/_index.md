---
title: IcoOptions Class
type: docs
weight: 140
url: /python-net/aspose.imaging.imageoptions/icooptions/
---

The ICO file format creation options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.IcoOptions

**Inheritance:** ImageOptionsBase

**Aspose.Imaging Version:** 23.6

The IcoOptions type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [IcoOptions()](#IcoOptions__0) | Initializes a new instance of the [IcoOptions](/imaging/python-net/aspose.imaging.imageoptions/icooptions/) class with the ICO frame format equals to Png and<br/>            bitsPerPixel equals to 32. |
| [IcoOptions(format, bits_per_pixel)](#IcoOptions_format_bits_per_pixel_1) | Initializes a new instance of the [IcoOptions](/imaging/python-net/aspose.imaging.imageoptions/icooptions/) class. |
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
| format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat) | r/w | Gets or sets the ICO frame format. |
| bits_per_pixel | int | r/w | Gets or sets the bits-per-pixel value. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__2) | Clones this instance. |

### IcoOptions() {#IcoOptions__0}


```
 IcoOptions() 
```

Initializes a new instance of the [IcoOptions](/imaging/python-net/aspose.imaging.imageoptions/icooptions/) class with the ICO frame format equals to Png and<br/>            bitsPerPixel equals to 32.

### IcoOptions(format, bits_per_pixel) {#IcoOptions_format_bits_per_pixel_1}


```
 IcoOptions(format, bits_per_pixel) 
```

Initializes a new instance of the [IcoOptions](/imaging/python-net/aspose.imaging.imageoptions/icooptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat) | The ICO frame format.<br/>            Note that ICO image supports only [PNG](/imaging/python-net/aspose.imaging/fileformat/) and [BMP](/imaging/python-net/aspose.imaging/fileformat/) images as entries. |
| bits_per_pixel | int | The bits-per-pixel value. |

### clone() {#clone__2}


```
 clone() 
```

Clones this instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | Returns shallow copy of this instance |


