---
title: GifOptions Class
type: docs
weight: 120
url: /python-net/aspose.imaging.imageoptions/gifoptions/
---

**Summary:** The gif file format creation options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.GifOptions

**Inheritance:** ImageOptionsBase

**Aspose.Imaging Version:** 23.6

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifOptions()](#GifOptions__1) | Initializes a new instance of the [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/) class. |
| [GifOptions(gif_options)](#GifOptions_gif_options_2) | Initializes a new instance of the [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color) | r/w | Gets or sets the background color. |
| background_color_index | byte | r/w | Gets or sets the GIF background color index. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| color_resolution | byte | r/w | Gets or sets the GIF color resolution. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| do_palette_correction | bool | r/w | Gets or sets a value indicating whether palette correction is applied. |
| full_frame | bool | r/w | Gets or sets a value indicating whether [full frame]. |
| has_trailer | bool | r/w | Gets or sets a value indicating whether GIF has trailer. |
| has_transparent_color | bool | r/w | Gets or sets a value indicating whether GIF image has transparent color. |
| interlaced | bool | r/w | True if image should be interlaced. |
| is_palette_sorted | bool | r/w | Gets or sets a value indicating whether palette entries are sorted. |
| loops_count | int | r/w | Gets or sets the loops count (Default 1 loop) |
| max_diff | int | r/w | Gets or sets the maximum allowed pixel difference. If greater than zero, lossy compression will be used.<br/>            Recommended value for optimal lossy compression is 80. 30 is very light compression, 200 is heavy.<br/>            It works best when only little loss is introduced, and due to limitation of the compression algorithm very high loss levels won't give as much gain.<br/>            The range of allowed values is [0, 1000]. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions) | r/w | The multipage options |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | r/w | Gets or sets the color palette. |
| pixel_aspect_ratio | byte | r/w | Gets or sets the GIF pixel aspect ratio. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting) | r/w | Gets or sets the resolution settings. |
| source | [Source](/imaging/python-net/aspose.imaging/source) | r/w | Gets or sets the source to create image in. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions) | r/w | Gets or sets the vector rasterization options. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Gets or sets the XMP metadata container. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clones this instance. |


### Constructor: GifOptions() {#GifOptions__1}


```
 GifOptions() 
```

Initializes a new instance of the [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/) class.

### Constructor: GifOptions(gif_options) {#GifOptions_gif_options_2}


```
 GifOptions(gif_options) 
```

Initializes a new instance of the [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| gif_options | [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions) | The GIF Options. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clones this instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | Returns shallow copy of this instance |


