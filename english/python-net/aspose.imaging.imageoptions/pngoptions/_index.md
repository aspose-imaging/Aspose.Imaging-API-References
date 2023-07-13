---
title: PngOptions Class
type: docs
weight: 240
url: /python-net/aspose.imaging.imageoptions/pngoptions/
---

The png file format create options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PngOptions

**Inheritance:** ImageOptionsBase

**Aspose.Imaging Version:** 23.6

The PngOptions type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [PngOptions()](#PngOptions__0) | Initializes a new instance of the [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) class. |
| [PngOptions(png_options)](#PngOptions_png_options_1) | Initializes a new instance of the [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) class. |
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
| color_type | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | r/w | Gets or sets the type of the color. |
| progressive | bool | r/w | Gets or sets a value indicating whether this [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) is progressive. |
| filter_type | [PngFilterType](/imaging/python-net/aspose.imaging.fileformats.png/pngfiltertype/) | r/w | Gets or sets the filter type used during png file save process. |
| compression_level | int | r/w | The png image compression level in the 0-9 range, where 9 is maximum compression and 0 is store mode. |
| bit_depth | byte | r/w | The bit depth. |
| DEFAULT_COMPRESSION_LEVEL [static] | int | r | The default compression level. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__2) | Clones this instance. |

### PngOptions() {#PngOptions__0}


```
 PngOptions() 
```

Initializes a new instance of the [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) class.

### PngOptions(png_options) {#PngOptions_png_options_1}


```
 PngOptions(png_options) 
```

Initializes a new instance of the [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| png_options | [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions) | The PNG options. |

### clone() {#clone__2}


```
 clone() 
```

Clones this instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | Returns shallow copy of this instance |


