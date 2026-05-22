---
title: "فئة OtgRasterizationOptions"
type: docs
weight: 230
url: /ar/python-net/aspose.imaging.imageoptions/otgrasterizationoptions/
---

**Summary:** The Otg rasterization options

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.OtgRasterizationOptions

**Inheritance:** OdRasterizationOptions

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [OtgRasterizationOptions()](#OtgRasterizationOptions__1) | يُنشئ مثلاً جديداً من فئة OtgRasterizationOptions |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | يحصل أو يعيّن لون خلفية. |
| border_x | float | r/w | الحصول أو تعيين الحد X. |
| border_y | float | r/w | الحصول أو تعيين الحد Y. |
| center_drawing | bool | r/w | الحصول أو تعيين قيمة تشير إلى ما إذا كان يتم الرسم في المركز. |
| draw_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | الحصول أو تعيين لون المقدمة. |
| page_height | float | r/w | الحصول أو تعيين ارتفاع الصفحة.<br/>            إذا كانت القيمة 0، سيتم الحفاظ على نسبة أبعاد الصورة الأصلية. |
| page_size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | الحصول أو تعيين حجم الصفحة.<br/>            إذا كان أحد أبعاد [SizeF](/imaging/python-net/aspose.imaging/sizef/) يساوي 0، سيتم الحفاظ على نسبة أبعاد الصورة الأصلية. |
| page_width | float | r/w | الحصول أو تعيين عرض الصفحة.<br/>            إذا كانت القيمة 0، سيتم الحفاظ على نسبة أبعاد الصورة الأصلية. |
| positioning | [PositioningTypes](/imaging/python-net/aspose.imaging.imageoptions/positioningtypes/) | r/w | الحصول أو تعيين الموضع. |
| smoothing_mode | [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | r/w | يحصل أو يضبط وضع التنعيم. |
| text_rendering_hint | [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | r/w | يحصل أو يضبط تلميح عرض النص. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [clone()](#clone__1) | ينشئ كائنًا جديدًا هو نسخة سطحية من المثيل الحالي. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | ينسخ إلى. |


### Constructor: OtgRasterizationOptions() {#OtgRasterizationOptions__1}


```
 OtgRasterizationOptions() 
```

يُنشئ مثلاً جديداً من فئة OtgRasterizationOptions

### Method: clone() {#clone__1}


```
 clone() 
```

ينشئ كائنًا جديدًا هو نسخة سطحية من المثيل الحالي.

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Object | كائن جديد هو نسخة سطحية من هذا المثيل. |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

ينسخ إلى.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | خيارات التحويل النقطي للمتجه. |

## **Examples**
### The following code snippet demonstrates how to convert an OTG image to PDF and other image formats. {#example_183}
``` python

from aspose.pycore import cast
from aspose.imaging import Image, SizeF
from aspose.imaging.imageoptions import PngOptions, PdfOptions, OtgRasterizationOptions

dir_: str = "c:\\3567\\"
input_file_path: str = dir_ + "VariousObjectsMultiPage.otg"
options = [PngOptions(), PdfOptions()]
for save_options in options:
	extension: str = ".png" if aspycore.is_assignable(save_options, PngOptions) else ".pdf"
	with Image.load(input_file_path) as image:
		otg_rasterization_options = OtgRasterizationOptions()
		otg_rasterization_options.page_size = cast(SizeF, image.size)
		save_options.vector_rasterization_options = otg_rasterization_options
		image.save(input_file_path + extension, save_options)


```

