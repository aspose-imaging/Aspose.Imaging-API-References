---
title: "PngLoadOptions 类"
type: docs
weight: 70
url: /zh/python-net/aspose.imaging.imageloadoptions/pngloadoptions/
---

**Summary:** The png load options.

**Module:** [aspose.imaging.imageloadoptions](/imaging/python-net/aspose.imaging.imageloadoptions/)

**Full Name:** aspose.imaging.imageloadoptions.PngLoadOptions

**Inheritance:** LoadOptions

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [PngLoadOptions()](#PngLoadOptions__1) | 初始化 [PngLoadOptions](/imaging/python-net/aspose.imaging.imageloadoptions/pngloadoptions/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| concurrent_image_processing | bool | r/w | 获取或设置一个值，指示是否启用 [concurrent image processing]。 |
| data_background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | 获取或设置 [Image](/imaging/python-net/aspose.imaging/image/) 的背景 [Color](/imaging/python-net/aspose.imaging/color/)。 |
| data_recovery_mode | [DataRecoveryMode](/imaging/python-net/aspose.imaging/datarecoverymode/) | r/w | 获取或设置数据恢复模式。 |
| [strict_mode](#strict_mode1) | bool | r/w | 获取或设置一个值，指示是否[strict mode]。 |
| use_icc_profile_conversion | bool | r/w | 获取或设置一个值，指示是否应应用 ICC 配置文件转换。 |


### Constructor: PngLoadOptions() {#PngLoadOptions__1}


```
 PngLoadOptions() 
```

初始化 [PngLoadOptions](/imaging/python-net/aspose.imaging.imageloadoptions/pngloadoptions/) 类的新实例。

### Property: strict_mode {#strict_mode1}

获取或设置一个值，指示是否[strict mode]。

**See also:**

**[Example # 1](#example_186)**: The following example shows how to read PNG file in a strict mode. The strict...


## **Examples**
### The following example shows how to read PNG file in a strict mode. The strict mode allows to find potential problems in PNG images, e.g. unrecognized data blocks, unexpected end of file. Such files still can be opened in default (non-strict) mode by `aspose.imaging` and by common viewers as well. However any attempts to open them in the strict mode cause a corresponding exception. {#example_186}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.imageloadoptions import PngLoadOptions
from os.path import join as path_join


dir_ = "c:\\testdata"
input_file_name = path_join(dir_, "FC5F1998104EB92469CB14070628073616BB28F9.png")
output_file_name = input_file_name + ".png"
# 默认模式（非严格）- 成功读取。
with Image.load(input_file_name) as image:
	image.save(output_file_name, PngOptions())

# 严格模式 - ImageLoadException：意外的文件结束。
obj_init = PngLoadOptions()
obj_init.strict_mode = True
with Image.load(input_file_name, obj_init) as image:
	image.save(output_file_name, PngOptions())


```

