---
title: "VectorRasterizationOptions 类"
type: docs
weight: 350
url: /zh/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/
---

**Summary:** The vector rasterization options.<br/>            Please note that [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) will no longer derive from [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) <br/>            since `aspose.imaging` 24.12 version.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.VectorRasterizationOptions

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [VectorRasterizationOptions()](#VectorRasterizationOptions__1) | 初始化 VectorRasterizationOptions 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| [background_color](#background_color1) | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | 获取或设置背景颜色。 |
| border_x | float | r/w | 获取或设置边框 X。 |
| border_y | float | r/w | 获取或设置边框 Y。 |
| center_drawing | bool | r/w | 获取或设置一个值，指示是否居中绘制。 |
| draw_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | 获取或设置前景颜色。 |
| page_height | float | r/w | 获取或设置页面高度。<br/>            如果值为 0，将保留源图像的宽高比。 |
| [page_size](#page_size2) | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | 获取或设置页面大小。<br/>            如果 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 的任一维度为 0，将保留源图像的宽高比。 |
| page_width | float | r/w | 获取或设置页面宽度。<br/>            如果值为 0，将保留源图像的宽高比。 |
| [positioning](#positioning3) | [PositioningTypes](/imaging/python-net/aspose.imaging.imageoptions/positioningtypes/) | r/w | 获取或设置定位。 |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | 获取或设置平滑模式。 |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | 获取或设置文本呈现提示。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [clone()](#clone__1) | 创建一个新对象，该对象是当前实例的浅拷贝。 |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | 复制到。 |


### Constructor: VectorRasterizationOptions() {#VectorRasterizationOptions__1}


```
 VectorRasterizationOptions() 
```

初始化 VectorRasterizationOptions 类的新实例

### Property: background_color {#background_color1}

获取或设置背景颜色。

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


### Property: page_size {#page_size2}

获取或设置页面大小。<br/>            如果 [SizeF](/imaging/python-net/aspose.imaging/sizef/) 的任一维度为 0，将保留源图像的宽高比。

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


### Property: positioning {#positioning3}

获取或设置定位。

**See also:**

**[Example # 1](#example_179)**: The following example shows how to set a memory limit when loading a CMX imag...

**[Example # 2](#example_187)**: The following example shows how to export all pages of CDR document to PDF.


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

复制到。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | 向量光栅化选项。 |

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

### The following example shows how to set a memory limit when loading a CMX image. The memory limit is the maximum allowed size (in megabytes) for all internal buffers. {#example_179}
``` python
from aspose.imaging import Image, TextRenderingHint, SmoothingMode, PositioningTypes, LoadOptions
from aspose.imaging.imageoptions import PngOptions, CmxRasterizationOptions
import os

directory = "c:\\aspose.imaging\\issues\\net\\3419\\"
	
# 为目标加载的图像设置 10 兆字节的内存限制。
load_options = LoadOptions()
load_options.buffer_size_hint = 10
with Image.load(os.path.join(directory, "example.cmx"), load_options) as image:
	png_options = PngOptions()
	cmx_spec = CmxRasterizationOptions()
	cmx_spec.text_renderingHint = TextRenderingHint.SINGLE_BIT_PER_PIXEL
	cmx_spec.smoothing_mode = SmoothingMode.ANTI_ALIAS
	cmx_spec.positioning = PositioningTypes.DEFINED_BY_DOCUMENT
	png_options.vector_rasterization_options = cmx_spec
	image.save(os.path.join(directory, "output.png"), png_options)


```

### The following example shows how to export all pages of CDR document to PDF. {#example_187}
``` python
from aspose.imaging import Image, TextRenderingHint, SmoothingMode
from aspose.imaging.imageoptions import PdfOptions, CdrRasterizationOptions, PositioningTypes
from os.path import join

dir_: str = "c:\\3570"
input_cdr_file_name: str = join(dir_, "tiger.cdr")
output_pdf_file_name: str = join(dir_, "tiger.cdr.pdf")
with Image.load(input_cdr_file_name) as image:
	pdf_options = PdfOptions()
	rasterization_options = CdrRasterizationOptions()
	rasterization_options.text_rendering_hint = TextRenderingHint.SINGLE_BIT_PER_PIXEL
	rasterization_options.smoothing_mode = SmoothingMode.NONE
	rasterization_options.positioning = PositioningTypes.DEFINED_BY_DOCUMENT
	pdf_options.vector_rasterization_options = rasterization_options
	image.save(output_pdf_file_name, pdf_options)


```

