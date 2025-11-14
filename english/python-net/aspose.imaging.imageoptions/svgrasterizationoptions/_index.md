---
title: SvgRasterizationOptions Class
type: docs
weight: 310
url: /python-net/aspose.imaging.imageoptions/svgrasterizationoptions/
---

**Summary:** The SVG rasterization options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.SvgRasterizationOptions

**Inheritance:** VectorRasterizationOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SvgRasterizationOptions()](#SvgRasterizationOptions__1) | Initializes a new instance of the [SvgRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/svgrasterizationoptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Gets or sets a background color. |
| border_x | float | r/w | Gets or sets the border X. |
| border_y | float | r/w | Gets or sets the border Y. |
| center_drawing | bool | r/w | Gets or sets a value indicating whether center drawing. |
| draw_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Gets or sets a foreground color. |
| page_height | float | r/w | Gets or sets the page height.<br/>            If the value is 0, the source image aspect ratio will be preserved. |
| page_size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Gets or sets the page size.<br/>            If one of [SizeF](/imaging/python-net/aspose.imaging/sizef/) dimensions is 0, the source image aspect ratio will be preserved. |
| page_width | float | r/w | Gets or sets the page width.<br/>            If the value is 0, the source image aspect ratio will be preserved. |
| positioning | [PositioningTypes](/imaging/python-net/aspose.imaging.imageoptions/positioningtypes/) | r/w | Gets or sets the positioning. |
| scale_x | float | r/w | Gets or sets the scale x. |
| scale_y | float | r/w | Gets or sets the scale y. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | Gets or sets the smoothing mode. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | Gets or sets the text rendering hint. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Creates a new object that is a shallow copy of the current instance. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Copies this instance to _vectorRasterizationOptions_. |


### Constructor: SvgRasterizationOptions() {#SvgRasterizationOptions__1}


```
 SvgRasterizationOptions() 
```

Initializes a new instance of the [SvgRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/svgrasterizationoptions/) class.

### Method: clone() {#clone__1}


```
 clone() 
```

Creates a new object that is a shallow copy of the current instance.

**Returns**

| Type | Description |
| :- | :- |
| System.Object | A new object that is a shallow copy of this instance. |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

Copies this instance to _vectorRasterizationOptions_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | The vector rasterization options. |

