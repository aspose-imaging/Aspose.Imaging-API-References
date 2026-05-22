---
title: "SvgRasterizationOptions 类"
type: docs
weight: 310
url: /zh/python-net/aspose.imaging.imageoptions/svgrasterizationoptions/
---

**Summary:** The SVG rasterization options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.SvgRasterizationOptions

**Inheritance:** VectorRasterizationOptions

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [SvgRasterizationOptions()](#SvgRasterizationOptions__1) | 初始化 [SvgRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/svgrasterizationoptions/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | 获取或设置背景颜色。 |
| border_x | float | r/w | 获取或设置边框 X。 |
| border_y | float | r/w | 获取或设置边框 Y。 |
| center_drawing | bool | r/w | 获取或设置一个值，指示是否居中绘制。 |
| draw_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | 获取或设置前景颜色。 |
| page_height | float | r/w | 获取或设置页面高度。<br/>            如果值为 0，将保留源图像的宽高比。 |
| page_size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | 获取或设置页面大小。<br/>            如果 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 的任一维度为 0，将保留源图像的宽高比。 |
| page_width | float | r/w | 获取或设置页面宽度。<br/>            如果值为 0，将保留源图像的宽高比。 |
| positioning | [PositioningTypes](/imaging/python-net/aspose.imaging.imageoptions/positioningtypes/) | r/w | 获取或设置定位。 |
| scale_x | float | r/w | 获取或设置 scale x。 |
| scale_y | float | r/w | 获取或设置 scale y。 |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | 获取或设置平滑模式。 |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | 获取或设置文本呈现提示。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [clone()](#clone__1) | 创建一个新对象，该对象是当前实例的浅拷贝。 |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | 将此实例复制到 _vectorRasterizationOptions_。 |


### Constructor: SvgRasterizationOptions() {#SvgRasterizationOptions__1}


```
 SvgRasterizationOptions() 
```

初始化 [SvgRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/svgrasterizationoptions/) 类的新实例。

### Method: clone() {#clone__1}


```
 clone() 
```

创建一个新对象，该对象是当前实例的浅拷贝。

**Returns**

| Type | Description |
| :- | :- |
| System.Object | 一个新对象，是此实例的浅拷贝。 |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

将此实例复制到 _vectorRasterizationOptions_。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | 向量光栅化选项。 |

