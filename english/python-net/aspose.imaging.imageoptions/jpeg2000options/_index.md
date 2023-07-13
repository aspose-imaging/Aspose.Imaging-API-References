---
title: Jpeg2000Options Class
type: docs
weight: 150
url: /python-net/aspose.imaging.imageoptions/jpeg2000options/
---

The Jpeg2000 file format options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.Jpeg2000Options

**Inheritance:** ImageOptionsBase

**Aspose.Imaging Version:** 23.6

The Jpeg2000Options type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [Jpeg2000Options()](#Jpeg2000Options__0) | Initializes a new instance of the [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/) class. |
| [Jpeg2000Options(jpeg_2000_options)](#Jpeg2000Options_jpeg_2000_options_1) | Initializes a new instance of the [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/) class. |
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
| comments | string | r/w | Gets or sets the Jpeg comment markers. |
| codec | [Jpeg2000Codec](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000codec/) | r/w | Gets or sets the JPEG2000 codec |
| compression_ratios | int | r/w | Gets or sets the Array of compression ratio.<br/>            Different compression ratios for successive layers.<br/>            The rate specified for each quality level is the desired<br/>            compression factor.<br/>            Decreasing ratios required. |
| irreversible | bool | r/w | Gets or sets a value indicating whether use the irreversible DWT 9-7 (true) or use lossless DWT 5-3 compression (default). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__2) | Clones this instance. |

### Jpeg2000Options() {#Jpeg2000Options__0}


```
 Jpeg2000Options() 
```

Initializes a new instance of the [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/) class.

### Jpeg2000Options(jpeg_2000_options) {#Jpeg2000Options_jpeg_2000_options_1}


```
 Jpeg2000Options(jpeg_2000_options) 
```

Initializes a new instance of the [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| jpeg_2000_options | [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options) | The Jpeg2000 file format options to copy settings from. |

### clone() {#clone__2}


```
 clone() 
```

Clones this instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | Returns shallow copy of this instance |


