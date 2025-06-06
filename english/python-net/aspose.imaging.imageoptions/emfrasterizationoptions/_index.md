---
title: EmfRasterizationOptions Class
type: docs
weight: 100
url: /python-net/aspose.imaging.imageoptions/emfrasterizationoptions/
---

**Summary:** The Emf rasterization options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.EmfRasterizationOptions

**Inheritance:** MetafileRasterizationOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfRasterizationOptions()](#EmfRasterizationOptions__1) | Initializes a new instance of the EmfRasterizationOptions class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color) | r/w | Gets or sets a background color. |
| border_x | float | r/w | Gets or sets the border X. |
| border_y | float | r/w | Gets or sets the border Y. |
| center_drawing | bool | r/w | Gets or sets a value indicating whether center drawing. |
| draw_color | [Color](/imaging/python-net/aspose.imaging/color) | r/w | Gets or sets a foreground color. |
| page_height | float | r/w | Gets or sets the page height.<br/>            If the value is 0, the source image aspect ratio will be preserved. |
| page_size | [SizeF](/imaging/python-net/aspose.imaging/sizef) | r/w | Gets or sets the page size.<br/>            If one of [SizeF](/imaging/python-net/aspose.imaging/sizef/) dimensions is 0, the source image aspect ratio will be preserved. |
| page_width | float | r/w | Gets or sets the page width.<br/>            If the value is 0, the source image aspect ratio will be preserved. |
| positioning | [PositioningTypes](/imaging/python-net/aspose.imaging.imageoptions/positioningtypes) | r/w | Gets or sets the positioning. |
| render_mode | [EmfRenderMode](/imaging/python-net/aspose.imaging.fileformats.emf/emfrendermode/) | r/w | Gets or sets the render mode. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode) | r/w | Gets or sets the smoothing mode. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint) | r/w | Gets or sets the text rendering hint. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Creates a new object that is a shallow copy of the current instance. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Copies this to _vectorRasterizationOptions_. |


### Constructor: EmfRasterizationOptions() {#EmfRasterizationOptions__1}


```
 EmfRasterizationOptions() 
```

Initializes a new instance of the EmfRasterizationOptions class

### Method: clone() {#clone__1}


```
 clone() 
```

Creates a new object that is a shallow copy of the current instance.

**Returns**

| Type | Description |
| :- | :- |
| object | A new object that is a shallow copy of this instance. |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

Copies this to _vectorRasterizationOptions_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions) | vectorRasterizationOptions |

