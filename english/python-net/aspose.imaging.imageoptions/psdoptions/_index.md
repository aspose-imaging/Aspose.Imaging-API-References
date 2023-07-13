---
title: PsdOptions Class
type: docs
weight: 250
url: /python-net/aspose.imaging.imageoptions/psdoptions/
---

The psd file format create options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PsdOptions

**Inheritance:** ImageOptionsBase

**Aspose.Imaging Version:** 23.6

The PsdOptions type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [PsdOptions()](#PsdOptions__0) | Initializes a new instance of the [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) class. |
| [PsdOptions(options)](#PsdOptions_options_1) | Initializes a new instance of the [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Get or set XMP data container |
| source | [Source](/imaging/python-net/aspose.imaging/source) | r/w | Gets or sets the source to create image in. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | r/w | Gets or sets the color palette. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting) | r/w | Gets or sets the resolution settings. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions) | r/w | Gets or sets the vector rasterization options. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions) | r/w | The multipage options |
| full_frame | bool | r/w | Gets or sets a value indicating whether [full frame]. |
| version | int | r/w | Gets or sets the psd file version. |
| compression_method | [CompressionMethod](/imaging/python-net/aspose.imaging.fileformats.psd/compressionmethod/) | r/w | Gets or sets the psd compression method. |
| psd_version | [PsdVersion](/imaging/python-net/aspose.imaging.fileformats.psd/psdversion/) | r/w | Gets or sets the file format version. It can be PSD or PSB. |
| color_mode | [ColorModes](/imaging/python-net/aspose.imaging.fileformats.psd/colormodes/) | r/w | Gets or sets the psd color mode. |
| channel_bits_count | short | r/w | Gets or sets the bits count per color channel. |
| channels_count | short | r/w | Gets or sets the color channels count. |
| remove_global_text_engine_resource | bool | r/w | Gets or sets a value indicating whether - Remove the global text engine resource - Used for some text-layered psd files, in only case, when they can not be opened in Adobe Photoshop after processing (mostly for absent fonts text layers related).<br/>            After using this option, user need to Make next in opened in Photoshop file: Menu "Text" -&gt; "Process absent fonts". After that operation all text will appear again.<br/>            Please note, that this operation may cause some final layout changes. |
| refresh_image_preview_data | bool | r/w | Gets or sets a value indicating whether [refresh image preview data] - option used to maximize compatibility with another PSD image viewers.<br/>            Please note, text layers drawing to final layout is not supported for Compact Framework platform |
| vectorization_options | [PsdVectorizationOptions](/imaging/python-net/aspose.imaging.imageoptions/psdvectorizationoptions) | r/w | Gets or sets the PSD vectorization options. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__2) | Clones this instance. |

### PsdOptions() {#PsdOptions__0}


```
 PsdOptions() 
```

Initializes a new instance of the [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) class.

### PsdOptions(options) {#PsdOptions_options_1}


```
 PsdOptions(options) 
```

Initializes a new instance of the [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| options | [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions) | The options. |

### clone() {#clone__2}


```
 clone() 
```

Clones this instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | Returns shallow copy of this instance |


