---
title: ApngOptions Class
type: docs
weight: 10
url: /python-net/aspose.imaging.imageoptions/apngoptions/
---

**Summary:** The animated PNG file format options

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.ApngOptions

**Inheritance:** PngOptions

**Aspose.Imaging Version:** 23.8.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ApngOptions()](#ApngOptions__1) | Initializes a new instance of the [ApngOptions](/imaging/python-net/aspose.imaging.imageoptions/apngoptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| DEFAULT_COMPRESSION_LEVEL [static] | int | r | The default compression level. |
| bit_depth | byte | r/w | The bit depth. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| color_type | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | r/w | Gets or sets the type of the color. |
| compression_level | int | r/w | The png image compression level in the 0-9 range, where 9 is maximum compression and 0 is store mode. |
| default_frame_time | uint | r/w | Gets or sets the default frame duration. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| filter_type | [PngFilterType](/imaging/python-net/aspose.imaging.fileformats.png/pngfiltertype/) | r/w | Gets or sets the filter type used during png file save process. |
| full_frame | bool | r/w | Gets or sets a value indicating whether [full frame]. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions) | r/w | The multipage options |
| num_plays | int | r/w | Gets or sets the number of times to loop animation.<br/>            0 indicates infinite looping. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | r/w | Gets or sets the color palette. |
| progressive | bool | r/w | Gets or sets a value indicating whether this [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) is progressive. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting) | r/w | Gets or sets the resolution settings. |
| source | [Source](/imaging/python-net/aspose.imaging/source) | r/w | Gets or sets the source to create image in. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions) | r/w | Gets or sets the vector rasterization options. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Gets or sets the XMP metadata container. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clones this instance. |


### Constructor: ApngOptions() {#ApngOptions__1}


```
 ApngOptions() 
```

Initializes a new instance of the [ApngOptions](/imaging/python-net/aspose.imaging.imageoptions/apngoptions/) class.

### Method: clone() {#clone__1}


```
 clone() 
```

Clones this instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | Returns shallow copy of this instance |


