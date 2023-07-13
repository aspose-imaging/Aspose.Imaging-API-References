---
title: EpsRasterizationOptions Class
type: docs
weight: 110
url: /python-net/aspose.imaging.imageoptions/epsrasterizationoptions/
---

The Eps rasterization options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.EpsRasterizationOptions

**Inheritance:** VectorRasterizationOptions

**Aspose.Imaging Version:** 23.6

The EpsRasterizationOptions type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EpsRasterizationOptions()](#EpsRasterizationOptions__0) | Initializes a new instance of the [EpsRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/epsrasterizationoptions/) class. |
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
| border_x | float | r/w | Gets or sets the border X. |
| border_y | float | r/w | Gets or sets the border Y. |
| center_drawing | bool | r/w | Gets or sets a value indicating whether center drawing. |
| page_height | float | r/w | Gets or sets the page height. |
| page_size | [SizeF](/imaging/python-net/aspose.imaging/sizef) | r/w | Gets or sets the page size. |
| page_width | float | r/w | Gets or sets the page width. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color) | r/w | Gets or sets a background color. |
| draw_color | [Color](/imaging/python-net/aspose.imaging/color) | r/w | Gets or sets a foreground color. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode) | r/w | Gets or sets the smoothing mode. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint) | r/w | Gets or sets the text rendering hint. |
| positioning | [PositioningTypes](/imaging/python-net/aspose.imaging.imageoptions/positioningtypes) | r/w | Gets or sets the positioning. |
| preview_to_export | [EpsPreviewFormat](/imaging/python-net/aspose.imaging.fileformats.eps/epspreviewformat/) | r/w | Gets or sets the preview to export. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clones this instance. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Copies to. |

### EpsRasterizationOptions() {#EpsRasterizationOptions__0}


```
 EpsRasterizationOptions() 
```

Initializes a new instance of the [EpsRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/epsrasterizationoptions/) class.

### clone() {#clone__1}


```
 clone() 
```

Clones this instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | Returns shallow copy of this instance |


### copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

Copies to.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions) | The vector rasterization options. |

