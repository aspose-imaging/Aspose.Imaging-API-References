---
title: "WmfRasterizationOptions 类"
type: docs
weight: 380
url: /zh/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/
---

**Summary:** The Wmf rasterization options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.WmfRasterizationOptions

**Inheritance:** MetafileRasterizationOptions

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [WmfRasterizationOptions()](#WmfRasterizationOptions__1) | 初始化一个新的 [WmfRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/) 类的实例。 |
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
| [render_mode](#render_mode1) | [WmfRenderMode](/imaging/python-net/aspose.imaging.fileformats.wmf/wmfrendermode/) | r/w | 获取或设置 WMF 渲染模式。 |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | 获取或设置平滑模式。 |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | 获取或设置文本呈现提示。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [clone()](#clone__1) | 创建一个新对象，该对象是当前实例的浅拷贝。 |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | 将此复制到 _vectorRasterizationOptions_。 |


### Constructor: WmfRasterizationOptions() {#WmfRasterizationOptions__1}


```
 WmfRasterizationOptions() 
```

初始化一个新的 [WmfRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/wmfrasterizationoptions/) 类的实例。

### Property: render_mode {#render_mode1}

获取或设置 WMF 渲染模式。

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


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

将此复制到 _vectorRasterizationOptions_。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | vectorRasterizationOptions |

## **Examples**
### This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions. {#example_173}
``` python

from aspose.pycore import as_of, cast
from aspose.imaging import Image, Color, SizeF
from aspose.imaging.fileformats.wmf import WmfImage, WmfRenderMode
from aspose.imaging.imageoptions import SvgOptions, WmfRasterizationOptions

# 使用 Aspose.Imaging.Image.Load 是一种统一的方式来加载包括 WMF 在内的所有类型的图像。
with as_of(Image.load("test.wmf") as image:
	saveOptions = SvgOptions()
	# 文本将被转换为形状。
	saveOptions.text_as_shapes = True
	rasterizationOptions = WmfRasterizationOptions()
	# 绘图表面的背景颜色。
	rasterizationOptions.background_color = Color.white_smoke
	# 页面大小。
	rasterizationOptions.page_size = cast(SizeF, wmfImage.size)
	# 如果存在嵌入的 emf，则渲染 emf；否则渲染 wmf。
	rasterizationOptions.render_mode = WmfRenderMode.AUTO
	saveOptions.vector_rasterization_options = rasterizationOptions
	wmfImage.save("test.output.svg", saveOptions)


```

