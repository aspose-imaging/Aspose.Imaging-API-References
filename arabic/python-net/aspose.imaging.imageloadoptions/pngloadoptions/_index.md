---
title: "PngLoadOptions فئة"
type: docs
weight: 70
url: /ar/python-net/aspose.imaging.imageloadoptions/pngloadoptions/
---

**Summary:** The png load options.

**Module:** [aspose.imaging.imageloadoptions](/imaging/python-net/aspose.imaging.imageloadoptions/)

**Full Name:** aspose.imaging.imageloadoptions.PngLoadOptions

**Inheritance:** LoadOptions

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [PngLoadOptions()](#PngLoadOptions__1) | ينشئ مثلاً جديداً من الفئة [PngLoadOptions](/imaging/python-net/aspose.imaging.imageloadoptions/pngloadoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| concurrent_image_processing | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [concurrent image processing]. |
| data_background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | يحصل أو يعيّن خلفية [Image](/imaging/python-net/aspose.imaging/image/) [Color](/imaging/python-net/aspose.imaging/color/). |
| data_recovery_mode | [DataRecoveryMode](/imaging/python-net/aspose.imaging/datarecoverymode/) | r/w | يحصل أو يعيّن وضع استعادة البيانات. |
| [strict_mode](#strict_mode1) | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان [strict mode]. |
| use_icc_profile_conversion | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تطبيق تحويل ملف تعريف ICC. |


### Constructor: PngLoadOptions() {#PngLoadOptions__1}


```
 PngLoadOptions() 
```

ينشئ مثلاً جديداً من الفئة [PngLoadOptions](/imaging/python-net/aspose.imaging.imageloadoptions/pngloadoptions/).

### Property: strict_mode {#strict_mode1}

يحصل أو يضبط قيمة تشير إلى ما إذا كان [strict mode].

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
# الوضع الافتراضي (غير صارم) - قراءة ناجحة.
with Image.load(input_file_name) as image:
	image.save(output_file_name, PngOptions())

# الوضع الصارم - ImageLoadException : نهاية غير متوقعة للملف.
obj_init = PngLoadOptions()
obj_init.strict_mode = True
with Image.load(input_file_name, obj_init) as image:
	image.save(output_file_name, PngOptions())


```

