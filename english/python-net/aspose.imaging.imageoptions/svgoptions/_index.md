---
title: SvgOptions Class
type: docs
weight: 290
url: /python-net/aspose.imaging.imageoptions/svgoptions/
---

The SVG file format creation options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.SvgOptions

**Inheritance:** ImageOptionsBase

**Aspose.Imaging Version:** 23.6

The SvgOptions type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [SvgOptions()](#SvgOptions__0) | Initializes a new instance of the [SvgOptions](/imaging/python-net/aspose.imaging.imageoptions/svgoptions/). |
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
| color_type | [SvgColorMode](/imaging/python-net/aspose.imaging.fileformats.svg/svgcolormode/) | r/w | Gets or sets the color type for SVG image. |
| text_as_shapes | bool | r/w | Gets or sets a value indicating whether text must be rendered as shapes. |
| callback | [ISvgResourceKeeperCallback](/imaging/python-net/aspose.imaging.fileformats.svg/isvgresourcekeepercallback/) | r/w | Gets or sets the storing strategy for embedded resousces of [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) such as fonts, nested rasters. |
| compress | bool | r/w | Gets or sets a value indicating whether the output image must to be compressed. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clones this instance. |

### SvgOptions() {#SvgOptions__0}


```
 SvgOptions() 
```

Initializes a new instance of the [SvgOptions](/imaging/python-net/aspose.imaging.imageoptions/svgoptions/).

### clone() {#clone__1}


```
 clone() 
```

Clones this instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | Returns shallow copy of this instance |


