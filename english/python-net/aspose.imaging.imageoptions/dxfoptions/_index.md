---
title: DxfOptions Class
type: docs
weight: 80
url: /python-net/aspose.imaging.imageoptions/dxfoptions/
---

The Dxf file format creation options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.DxfOptions

**Inheritance:** ImageOptionsBase

**Aspose.Imaging Version:** 23.6

The DxfOptions type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [DxfOptions()](#DxfOptions__0) | Initializes a new instance of the DxfOptions class |
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
| bezier_point_count | byte | r/w | How many points to generate when converting Bezier curves to polylines, minimum 4. Used when <seealso cref="P:Aspose.Imaging.ImageOptions.DxfOptions.TextAsLines" /> and <seealso cref="P:Aspose.Imaging.ImageOptions.DxfOptions.ConvertTextBeziers" /> are both  	/// set to <c>true</c> |
| convert_text_beziers | bool | r/w | Works when <seealso cref="P:Aspose.Imaging.ImageOptions.DxfOptions.TextAsLines" /> is set to <c>true</c>. Wether to convert Bezier curves in text contours to multipoint polylines. |
| text_as_lines | bool | r/w | Whether text should be exported as contours consisting of polylines (default) or as editable Autocad TEXT entities.<br/>            If this option set |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clones this instance. |

### DxfOptions() {#DxfOptions__0}


```
 DxfOptions() 
```

Initializes a new instance of the DxfOptions class

### clone() {#clone__1}


```
 clone() 
```

Clones this instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | Returns shallow copy of this instance |


