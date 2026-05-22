---
title: "الفئة LoadOptions"
type: docs
weight: 6000
url: /ar/python-net/aspose.imaging/loadoptions/
---

**Summary:** Represents the loading options.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.LoadOptions

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [LoadOptions()](#LoadOptions__1) | يُنشئ مثيلاً جديدًا من [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| [buffer_size_hint](#buffer_size_hint1) | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| concurrent_image_processing | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [concurrent image processing]. |
| data_background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | يحصل أو يعيّن خلفية [Image](/imaging/python-net/aspose.imaging/image/) [Color](/imaging/python-net/aspose.imaging/color/). |
| data_recovery_mode | [DataRecoveryMode](/imaging/python-net/aspose.imaging/datarecoverymode/) | r/w | يحصل أو يعيّن وضع استعادة البيانات. |
| use_icc_profile_conversion | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تطبيق تحويل ملف تعريف ICC. |


### Constructor: LoadOptions() {#LoadOptions__1}


```
 LoadOptions() 
```

يُنشئ مثيلاً جديدًا من [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/).

### Property: buffer_size_hint {#buffer_size_hint1}

يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية.

**See also:**

**[Example # 1](#example_179)**: The following example shows how to set a memory limit when loading a CMX imag...


## **Examples**
### The following example shows how to set a memory limit when loading a CMX image. The memory limit is the maximum allowed size (in megabytes) for all internal buffers. {#example_179}
``` python
from aspose.imaging import Image, TextRenderingHint, SmoothingMode, PositioningTypes, LoadOptions
from aspose.imaging.imageoptions import PngOptions, CmxRasterizationOptions
import os

directory = "c:\\aspose.imaging\\issues\\net\\3419\\"
	
# تعيين حد الذاكرة إلى 10 ميغابايت لصورة محمّلة مستهدفة.
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

