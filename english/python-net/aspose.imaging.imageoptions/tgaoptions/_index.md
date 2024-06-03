---
title: TgaOptions Class
type: docs
weight: 310
url: /python-net/aspose.imaging.imageoptions/tgaoptions/
---

**Summary:** The TGA file format create options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.TgaOptions

**Inheritance:** IHasXmpData, IHasMetadata, ImageOptionsBase

**Aspose.Imaging Version:** 24.6.0

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
| full_frame | bool | r/w | Gets or sets a value indicating whether [full frame]. |
| keep_metadata | bool | r/w | Gets a value whether to keep original image metadata on export. |
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


### Constructor: TgaOptions() {#TgaOptions__1}


```
 TgaOptions() 
```

Initializes a new instance of the [TgaOptions](/imaging/python-net/aspose.imaging.imageoptions/tgaoptions/) class.

### Constructor: TgaOptions(tga_options) {#TgaOptions_tga_options_2}


```
 TgaOptions(tga_options) 
```

Initializes a new instance of the [TgaOptions](/imaging/python-net/aspose.imaging.imageoptions/tgaoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tga_options | [TgaOptions](/imaging/python-net/aspose.imaging.imageoptions/tgaoptions) | The TGA options. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clones this instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | Returns shallow copy of this instance |


