---
title: "LoadOptions 类"
type: docs
weight: 6000
url: /zh/python-net/aspose.imaging/loadoptions/
---

**Summary:** Represents the loading options.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.LoadOptions

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [LoadOptions()](#LoadOptions__1) | 初始化 [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) 的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| [buffer_size_hint](#buffer_size_hint1) | int | r/w | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| concurrent_image_processing | bool | r/w | 获取或设置一个值，指示是否启用 [concurrent image processing]。 |
| data_background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | 获取或设置 [Image](/imaging/python-net/aspose.imaging/image/) 的背景 [Color](/imaging/python-net/aspose.imaging/color/)。 |
| data_recovery_mode | [DataRecoveryMode](/imaging/python-net/aspose.imaging/datarecoverymode/) | r/w | 获取或设置数据恢复模式。 |
| use_icc_profile_conversion | bool | r/w | 获取或设置一个值，指示是否应应用 ICC 配置文件转换。 |


### Constructor: LoadOptions() {#LoadOptions__1}


```
 LoadOptions() 
```

初始化 [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) 的新实例。

### Property: buffer_size_hint {#buffer_size_hint1}

获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。

**See also:**

**[Example # 1](#example_179)**: The following example shows how to set a memory limit when loading a CMX imag...


## **Examples**
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

