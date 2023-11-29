---
title: LoadOptions Class
type: docs
weight: 5770
url: /python-net/aspose.imaging/loadoptions/
---

**Summary:** Represents the loading options.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.LoadOptions

**Aspose.Imaging Version:** 23.11.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LoadOptions()](#LoadOptions__1) | Initializes a new instance of the [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [buffer_size_hint](#buffer_size_hint1) | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| data_background_color | [Color](/imaging/python-net/aspose.imaging/color) | r/w | Gets or sets the [Image](/imaging/python-net/aspose.imaging/image/) background [Color](/imaging/python-net/aspose.imaging/color/). |
| data_recovery_mode | [DataRecoveryMode](/imaging/python-net/aspose.imaging/datarecoverymode) | r/w | Gets or sets the data recovery mode. |
| use_icc_profile_conversion | bool | r/w | Gets or sets a value indicating whether ICC profile conversion should be applied. |


### Constructor: LoadOptions() {#LoadOptions__1}


```
 LoadOptions() 
```

Initializes a new instance of the [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/).

### Property: buffer_size_hint {#buffer_size_hint1}

Gets or sets the buffer size hint which is defined max allowed size for all internal buffers.

**See also:**

**[Example # 1](#example_78)**: The following example shows how to set a memory limit when loading a CMX imag...


## **Examples**
### The following example shows how to set a memory limit when loading a CMX image. The memory limit is the maximum allowed size (in megabytes) for all internal buffers. {#example_78}
``` python
from Aspose.Imaging import Image, TextRenderingHint, SmoothingMode, PositioningTypes
from Aspose.Imaging.ImageOptions import PngOptions, CmxRasterizationOptions

directory = "c:\\aspose.imaging\\issues\\net\\3419\\"
	
# Setting a memory limit of 10 megabytes for a target loaded image.
load_options = new Aspose.Imaging.LoadOptions()
load_options.buffer_size_hint = 10
with Image.load(directory + "example.cmx", load_options) as image:
	png_options = PngOptions()
	cmx_spec = CmxRasterizationOptions()
	cmx_spec.text_renderingHint = TextRenderingHint.SINGLE_BIT_PER_PIXEL
	cmx_spec.smoothing_mode = SmoothingMode.ANTI_ALIAS
	cmx_spec.positioning = PositioningTypes.DEFINED_BY_DOCUMENT
	png_options.vector_rasterization_options = cmx_spec
	image.save(directory + "output.png", png_options)


```

