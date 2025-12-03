---
title: PngLoadOptions Class
type: docs
weight: 60
url: /python-net/aspose.imaging.imageloadoptions/pngloadoptions/
---

**Summary:** The png load options.

**Module:** [aspose.imaging.imageloadoptions](/imaging/python-net/aspose.imaging.imageloadoptions/)

**Full Name:** aspose.imaging.imageloadoptions.PngLoadOptions

**Inheritance:** LoadOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PngLoadOptions()](#PngLoadOptions__1) | Initializes a new instance of the [PngLoadOptions](/imaging/python-net/aspose.imaging.imageloadoptions/pngloadoptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| concurrent_image_processing | bool | r/w | Gets or sets a value indicating whether [concurrent image processing]. |
| data_background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Gets or sets the [Image](/imaging/python-net/aspose.imaging/image/) background [Color](/imaging/python-net/aspose.imaging/color/). |
| data_recovery_mode | [DataRecoveryMode](/imaging/python-net/aspose.imaging/datarecoverymode/) | r/w | Gets or sets the data recovery mode. |
| [strict_mode](#strict_mode1) | bool | r/w | Gets or sets a value indicating whether [strict mode]. |
| use_icc_profile_conversion | bool | r/w | Gets or sets a value indicating whether ICC profile conversion should be applied. |


### Constructor: PngLoadOptions() {#PngLoadOptions__1}


```
 PngLoadOptions() 
```

Initializes a new instance of the [PngLoadOptions](/imaging/python-net/aspose.imaging.imageloadoptions/pngloadoptions/) class.

### Property: strict_mode {#strict_mode1}

Gets or sets a value indicating whether [strict mode].

**See also:**

**[Example # 1](#example_184)**: The following example shows how to read PNG file in a strict mode. The strict...


## **Examples**
### The following example shows how to read PNG file in a strict mode. The strict mode allows to find potential problems in PNG images, e.g. unrecognized data blocks, unexpected end of file. Such files still can be opened in default (non-strict) mode by `aspose.imaging` and by common viewers as well. However any attempts to open them in the strict mode cause a corresponding exception. {#example_184}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.imageloadoptions import PngLoadOptions
from os.path import join as path_join


dir_ = "c:\\testdata"
input_file_name = path_join(dir_, "FC5F1998104EB92469CB14070628073616BB28F9.png")
output_file_name = input_file_name + ".png"
# Default mode (non-strict) - successul reading.
with Image.load(input_file_name) as image:
	image.save(output_file_name, PngOptions())

# Strict mode - ImageLoadException : Unexpected end of file.
obj_init = PngLoadOptions()
obj_init.strict_mode = True
with Image.load(input_file_name, obj_init) as image:
	image.save(output_file_name, PngOptions())


```

