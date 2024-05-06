---
title: IcoOptions Class
type: docs
weight: 140
url: /python-net/aspose.imaging.imageoptions/icooptions/
---

**Summary:** Create custom ICO image files for application icons effortlessly with our API,<br/>            empowering you to represent your software seamlessly. Our API supports PNG and<br/>            BMP image frames with various bits per pixel values, ensuring versatility and<br/>            compatibility for your icon creation needs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.IcoOptions

**Inheritance:** ImageOptionsBase

**Aspose.Imaging Version:** 24.5.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [IcoOptions()](#IcoOptions__1) | Initializes a new instance of the [IcoOptions](/imaging/python-net/aspose.imaging.imageoptions/icooptions/) class with the ICO frame format equals to Png and<br/>            bitsPerPixel equals to 32. |
| [IcoOptions(format, bits_per_pixel)](#IcoOptions_format_bits_per_pixel_2) | Initializes a new instance of the [IcoOptions](/imaging/python-net/aspose.imaging.imageoptions/icooptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bits_per_pixel | int | r/w | Gets or sets the bits-per-pixel value. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat) | r/w | Gets or sets the ICO frame format. |
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


### Constructor: IcoOptions() {#IcoOptions__1}


```
 IcoOptions() 
```

Initializes a new instance of the [IcoOptions](/imaging/python-net/aspose.imaging.imageoptions/icooptions/) class with the ICO frame format equals to Png and<br/>            bitsPerPixel equals to 32.

### Constructor: IcoOptions(format, bits_per_pixel) {#IcoOptions_format_bits_per_pixel_2}


```
 IcoOptions(format, bits_per_pixel) 
```

Initializes a new instance of the [IcoOptions](/imaging/python-net/aspose.imaging.imageoptions/icooptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat) | The ICO frame format.<br/>            Note that ICO image supports only [FileFormat.PNG](/imaging/python-net/aspose.imaging/fileformat/) and [FileFormat.BMP](/imaging/python-net/aspose.imaging/fileformat/) images as entries. |
| bits_per_pixel | int | The bits-per-pixel value. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clones this instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | Returns shallow copy of this instance |


